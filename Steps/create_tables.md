1. Before you begin, check if the `reference_list` and `movies_by_genre` tables exist in the GraphQL database.

    ```sql
    query list_all_tables {
    __schema {
        queryType {
        fields {
            name
          }
        }
      }
    }
    ```

2. If there are, drop them with the query below, if not, please skip step 3.

    ```sql
    #Drop the movies_by_genre table if exist
    mutation drop_table_movies_by_genre { dropTable 
      (
        keyspaceName:"sag_netflix",
        tableName:"movies_by_genre"
      )
    }

    #Drop the reference_list table if exist
    mutation drop_table_reference_list { dropTable 
      (
        keyspaceName:"sag_netflix",
        tableName:"reference_list"
      )
    }
    ```

3. Create the tables with the command below and check if they are created.

    ```sql
    #Create the reference_list table
    mutation create_reference_list_table{
    sag_reference_list: createTable(
        keyspaceName: "sag_netflix"
        tableName: "reference_list"
        ifNotExists: true
        partitionKeys: [{ name: "label", type: { basic: TEXT } }]
        clusteringKeys: [{ name: "value", type: { basic: TEXT }, order: "ASC" }]
      )
    }

    #Create the movies_by_genre table
    mutation create_movies_by_genre_table {
    sag_movies_by_genre: createTable(
        keyspaceName: "sag_netflix"
        tableName: "movies_by_genre"
        ifNotExists: true
        partitionKeys: [{ name: "genre", type: { basic: TEXT } }]
        clusteringKeys: [
            { name: "year", type: { basic: INT }, order: "DESC" }
            { name: "title", type: { basic: TEXT }, order: "ASC" }
        ]
        values: [
        { name: "synopsis", type: { basic: TEXT } }
        { name: "duration", type: { basic: INT } }
        { name: "thumbnail", type: { basic: TEXT } }
        ]
      )
    }

    #Check if tables are created
    query list_all_tables {
    __schema {
        queryType {
        fields {
            name
          }
        }
      }
    }
    ```

4. Execute the `insert_data.md` file which is in the same directory as create_tables.md file.
