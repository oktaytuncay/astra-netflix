```json
mutation Insert_Genres {
  action: insertreference_list(value: {label:"genre", value:"Action"}) {
    value{value}
  }
  anime: insertreference_list(value: {label:"genre", value:"Anime"}) {
     value{value}
  }
  award: insertreference_list(value: {label:"genre", value:"Award-Winning"}) {
     value{value}
  }
  children: insertreference_list(value: {label:"genre", value:"Children & Family"}) {
     value{value}
  }
  comedies: insertreference_list(value: {label:"genre", value:"Comedies"}) {
     value{value}
  }
  documentaries: insertreference_list(value: {label:"genre", value:"Documentaries"}) {
     value{value}
  }
  drama: insertreference_list(value: {label:"genre", value:"Dramas"}) {
     value{value}
  }
  fantasy: insertreference_list(value: {label:"genre", value:"Fantasy"}) {
     value{value}
  }
  french: insertreference_list(value: {label:"genre", value:"French"}) {
     value{value}
  }
  horror: insertreference_list(value: {label:"genre", value:"Horror"}) {
     value{value}
  }
  independent: insertreference_list(value: {label:"genre", value:"Independent"}) {
     value{value}
  }
  music: insertreference_list(value: {label:"genre", value:"Music"}) {
     value{value}
  }
  romance: insertreference_list(value: {label:"genre", value:"Romance"}) {
     value{value}
  }
  scifi: insertreference_list(value: {label:"genre", value:"Sci-Fi"}) {
     value{value}
  }
  thriller: insertreference_list(value: {label:"genre", value:"Thriller"}) {
     value{value}
  }  
}


mutation Insert_Movies {
  
  creed_1: insertmovies_by_genre(
    value: { 
      genre:"Action", 
      year:2015,
      title:"Creed",
      synopsis:"The former World Heavyweight Champion Rocky Balboa serves as a trainer and mentor to Adonis Johnson, the son of his late friend and former rival Apollo Creed.",
      duration:133,
      thumbnail:"https://i.imgur.com/NQTuLtb.mp4"}) {
    value{title}
  }
  
  creed_2: insertmovies_by_genre(
    value: { 
      genre:"Action", 
      year:2005,
      title:"Creed",
      synopsis:"The former World Heavyweight Champion Rocky Balboa serves as a trainer and mentor to Adonis Johnson, the son of his late friend and former rival Apollo Creed.",
      duration:133,
      thumbnail:"https://i.imgur.com/NQTuLtb.mp4"}) {
    value{title}
  }
  
  creed_3: insertmovies_by_genre(
    value: { 
      genre:"Action", 
      year:1995,
      title:"Creed",
      synopsis:"The former World Heavyweight Champion Rocky Balboa serves as a trainer and mentor to Adonis Johnson, the son of his late friend and former rival Apollo Creed.",
      duration:133,
      thumbnail:"https://i.imgur.com/NQTuLtb.mp4"}) {
    value{title}
  }
  
  furious7_1: insertmovies_by_genre(
    value: { 
      genre:"Action", 
      year:2015,
      title:"Furious7",
      synopsis:"Deckard Shaw seeks revenge against Dominic Toretto and his family for his comatose brother.",
      duration:137,
      thumbnail:"https://i.imgur.com/7ax74eb.mp4"}) {
    value{title}
  }
  
  furious7_2: insertmovies_by_genre(
    value: { 
      genre:"Action", 
      year:2005,
      title:"Furious7",
      synopsis:"Deckard Shaw seeks revenge against Dominic Toretto and his family for his comatose brother.",
      duration:137,
      thumbnail:"https://i.imgur.com/7ax74eb.mp4"}) {
    value{title}
  }
  
  furious7_3: insertmovies_by_genre(
    value: { 
      genre:"Action", 
      year:1995,
      title:"Furious7",
      synopsis:"Deckard Shaw seeks revenge against Dominic Toretto and his family for his comatose brother.",
      duration:137,
      thumbnail:"https://i.imgur.com/7ax74eb.mp4"}) {
    value{title}
  }
  
  guardian_1: insertmovies_by_genre(
    value: { 
      genre:"Action", 
      year:2014,
      title:"Guardians of the Galaxy",
      synopsis:"A group of intergalactic criminals must pull together to stop a fanatical warrior with plans to purge the universe.",
      duration:121,
      thumbnail:"https://i.imgur.com/AylKL2G.mp4"}) {
    value{title}
  }
  
  guardian_2: insertmovies_by_genre(
    value: { 
      genre:"Action", 
      year:2004,
      title:"Guardians of the Galaxy",
      synopsis:"A group of intergalactic criminals must pull together to stop a fanatical warrior with plans to purge the universe.",
      duration:121,
      thumbnail:"https://i.imgur.com/AylKL2G.mp4"}) {
    value{title}
  }
  
  guardian_3: insertmovies_by_genre(
    value: { 
      genre:"Action", 
      year:1994,
      title:"Guardians of the Galaxy",
      synopsis:"A group of intergalactic criminals must pull together to stop a fanatical warrior with plans to purge the universe.",
      duration:121,
      thumbnail:"https://i.imgur.com/AylKL2G.mp4"}) {
    value{title}
  }
  
  suicide_1: insertmovies_by_genre(
    value: { 
      genre:"Action", 
      year:2016,
      title:"Suicide Squad",
      synopsis:"A secret government agency recruits some of the most dangerous incarcerated super-villains to form a defensive task force. Their first mission: save the world from the apocalypse.",
      duration:123,
      thumbnail:"https://i.imgur.com/hwUzoyu.mp4"}) {
    value{title}
  }
  
  suicide_2: insertmovies_by_genre(
    value: { 
      genre:"Action", 
      year:2006,
      title:"Suicide Squad",
      synopsis:"A secret government agency recruits some of the most dangerous incarcerated super-villains to form a defensive task force. Their first mission: save the world from the apocalypse.",
      duration:123,
      thumbnail:"https://i.imgur.com/hwUzoyu.mp4"}) {
    value{title}
  }
  suicide_3: insertmovies_by_genre(
    value: { 
      genre:"Action", 
      year:1996,
      title:"Suicide Squad",
      synopsis:"A secret government agency recruits some of the most dangerous incarcerated super-villains to form a defensive task force. Their first mission: save the world from the apocalypse.",
      duration:123,
      thumbnail:"https://i.imgur.com/hwUzoyu.mp4"}) {
    value{title}
  }

  
  gundamn_1: insertmovies_by_genre(
    value: { 
      genre:"Anime", 
      year:2007,
      title:"Gundam 00",
      synopsis:"In the distant future, mankind has used up all of its fossil fuels, forcing them to turn to Solar Power as an alternate energy source. As a result, this causes a rift to form between richer and poorer nations, eventually leading to war. In the midst of this conflict, a mysterious military group known as 'Celestial Being' aims to use force to bring peace to the world, by using special humanoid weapons known as Gundams.",
      duration:100,
      thumbnail:"https://i.imgur.com/BR9EUGh.mp4"}) {
    value{title}
  }
  
  gundamn_2: insertmovies_by_genre(
    value: { 
      genre:"Anime", 
      year:2017,
      title:"Gundam 00",
      synopsis:"In the distant future, mankind has used up all of its fossil fuels, forcing them to turn to Solar Power as an alternate energy source. As a result, this causes a rift to form between richer and poorer nations, eventually leading to war. In the midst of this conflict, a mysterious military group known as 'Celestial Being' aims to use force to bring peace to the world, by using special humanoid weapons known as Gundams.",
      duration:100,
      thumbnail:"https://i.imgur.com/BR9EUGh.mp4"}) {
    value{title}
  }

  gundamn_3: insertmovies_by_genre(
    value: { 
      genre:"Anime", 
      year:1997,
      title:"Gundam 00",
      synopsis:"In the distant future, mankind has used up all of its fossil fuels, forcing them to turn to Solar Power as an alternate energy source. As a result, this causes a rift to form between richer and poorer nations, eventually leading to war. In the midst of this conflict, a mysterious military group known as 'Celestial Being' aims to use force to bring peace to the world, by using special humanoid weapons known as Gundams.",
      duration:100,
      thumbnail:"https://i.imgur.com/BR9EUGh.mp4"}) {
    value{title}
  }

  dbs_1: insertmovies_by_genre(
    value: { 
      genre:"Anime", 
      year:2015,
      title:"Dragon Ball Super",
      synopsis:"Six months after the defeat of Majin Buu, The mighty Saiyan Son Goku continues his quest on becoming stronger.",
      duration:100,
      thumbnail:"https://i.imgur.com/6u0PCQK.mp4"}) {
    value{title}
  }

  dbs_2: insertmovies_by_genre(
    value: { 
      genre:"Anime", 
      year:2005,
      title:"Dragon Ball Super",
      synopsis:"Six months after the defeat of Majin Buu, The mighty Saiyan Son Goku continues his quest on becoming stronger.",
      duration:100,
      thumbnail:"https://i.imgur.com/6u0PCQK.mp4"}) {
    value{title}
  }

  dbs_3: insertmovies_by_genre(
    value: { 
      genre:"Anime", 
      year:1995,
      title:"Dragon Ball Super",
      synopsis:"Six months after the defeat of Majin Buu, The mighty Saiyan Son Goku continues his quest on becoming stronger.",
      duration:100,
      thumbnail:"https://i.imgur.com/6u0PCQK.mp4"}) {
    value{title}
  }

  aot_1: insertmovies_by_genre(
    value: { 
      genre:"Anime", 
      year:2015,
      title:"Attack on Titan",
      synopsis:"After his hometown is destroyed and his mother is killed, young Eren Jaeger vows to cleanse the earth of the giant humanoid Titans that have brought humanity to the brink of extinction.",
      duration:100,
      thumbnail:"https://i.imgur.com/LItJ5qS.mp4"}) {
    value{title}
  }

  aot_2: insertmovies_by_genre(
    value: { 
      genre:"Anime", 
      year:2005,
      title:"Attack on Titan",
      synopsis:"After his hometown is destroyed and his mother is killed, young Eren Jaeger vows to cleanse the earth of the giant humanoid Titans that have brought humanity to the brink of extinction.",
      duration:100,
      thumbnail:"https://i.imgur.com/LItJ5qS.mp4"}) {
    value{title}
  }

  aot_3: insertmovies_by_genre(
    value: { 
      genre:"Anime", 
      year:1995,
      title:"Attack on Titan",
      synopsis:"After his hometown is destroyed and his mother is killed, young Eren Jaeger vows to cleanse the earth of the giant humanoid Titans that have brought humanity to the brink of extinction.",
      duration:100,
      thumbnail:"https://i.imgur.com/LItJ5qS.mp4"}) {
    value{title}
  }

  bleach_1: insertmovies_by_genre(
    value: { 
      genre:"Anime", 
      year:2004,
      title:"Bleach",
      synopsis:"High school student Ichigo Kurosaki, who has the ability to see ghosts, gains soul reaper powers from Rukia Kuchiki and sets out to save the world from 'Hollows'.",
      duration:100,
      thumbnail:"https://i.imgur.com/W3fTtFS.mp4"}) {
    value{title}
  }

  bleach_2: insertmovies_by_genre(
    value: { 
      genre:"Anime", 
      year:1994,
      title:"Bleach",
      synopsis:"High school student Ichigo Kurosaki, who has the ability to see ghosts, gains soul reaper powers from Rukia Kuchiki and sets out to save the world from 'Hollows'.",
      duration:100,
      thumbnail:"https://i.imgur.com/W3fTtFS.mp4"}) {
    value{title}
  }

  bleach_3: insertmovies_by_genre(
    value: { 
      genre:"Anime", 
      year:2014,
      title:"Bleach",
      synopsis:"High school student Ichigo Kurosaki, who has the ability to see ghosts, gains soul reaper powers from Rukia Kuchiki and sets out to save the world from 'Hollows'.",
      duration:100,
      thumbnail:"https://i.imgur.com/W3fTtFS.mp4"}) {
    value{title}
  }
   

  forest1: insertmovies_by_genre(
    value: { 
      genre:"Award-Winning", 
      year:1994,
      title:"Forest Gump",
      synopsis:"The presidencies of Kennedy and Johnson, the Vietnam War, the Watergate scandal and other historical events unfold from the perspective of an Alabama man with an IQ of 75, whose only desire is to be reunited with his childhood sweetheart.",
      duration:142,
      thumbnail:"https://i.imgur.com/V6WMXYx.mp4"}) {
    value{title}
  }

  forest2: insertmovies_by_genre(
    value: { 
      genre:"Award-Winning", 
      year:2004,
      title:"Forest Gump",
      synopsis:"The presidencies of Kennedy and Johnson, the Vietnam War, the Watergate scandal and other historical events unfold from the perspective of an Alabama man with an IQ of 75, whose only desire is to be reunited with his childhood sweetheart.",
      duration:142,
      thumbnail:"https://i.imgur.com/V6WMXYx.mp4"}) {
    value{title}
  }

  forest3: insertmovies_by_genre(
    value: { 
      genre:"Award-Winning", 
      year:2014,
      title:"Forest Gump",
      synopsis:"The presidencies of Kennedy and Johnson, the Vietnam War, the Watergate scandal and other historical events unfold from the perspective of an Alabama man with an IQ of 75, whose only desire is to be reunited with his childhood sweetheart.",
      duration:142,
      thumbnail:"https://i.imgur.com/V6WMXYx.mp4"}) {
    value{title}
  }

  matrix1: insertmovies_by_genre(
    value: { 
      genre:"Award-Winning", 
      year:1999,
      title:"The Matrix",
      synopsis:"When a beautiful stranger leads computer hacker Neo to a forbidding underworld, he discovers the shocking truth--the life he knows is the elaborate deception of an evil cyber-intelligence.",
      duration:136,
      thumbnail:"https://i.imgur.com/QzJe4nJ.mp4"}) {
    value{title}
  }

  matrix2: insertmovies_by_genre(
    value: { 
      genre:"Award-Winning", 
      year:2009,
      title:"The Matrix",
      synopsis:"When a beautiful stranger leads computer hacker Neo to a forbidding underworld, he discovers the shocking truth--the life he knows is the elaborate deception of an evil cyber-intelligence.",
      duration:136,
      thumbnail:"https://i.imgur.com/QzJe4nJ.mp4"}) {
    value{title}
  }

  matrix3: insertmovies_by_genre(
    value: { 
      genre:"Award-Winning", 
      year:2019,
      title:"The Matrix",
      synopsis:"When a beautiful stranger leads computer hacker Neo to a forbidding underworld, he discovers the shocking truth--the life he knows is the elaborate deception of an evil cyber-intelligence.",
      duration:136,
      thumbnail:"https://i.imgur.com/QzJe4nJ.mp4"}) {
    value{title}
  }

  pulpfiction1: insertmovies_by_genre(
    value: { 
      genre:"Award-Winning", 
      year:1994,
      title:"Pulp Fiction",
      synopsis:"The lives of two mob hitmen, a boxer, a gangster and his wife, and a pair of diner bandits intertwine in four tales of violence and redemption.",
      duration:154,
      thumbnail:"https://i.imgur.com/8xf630M.mp4"}) {
    value{title}
  }

  pulpfiction2: insertmovies_by_genre(
    value: { 
      genre:"Award-Winning", 
      year:2004,
      title:"Pulp Fiction",
      synopsis:"The lives of two mob hitmen, a boxer, a gangster and his wife, and a pair of diner bandits intertwine in four tales of violence and redemption.",
      duration:154,
      thumbnail:"https://i.imgur.com/8xf630M.mp4"}) {
    value{title}
  }

  pulpfiction3: insertmovies_by_genre(
    value: { 
      genre:"Award-Winning", 
      year:2014,
      title:"Pulp Fiction",
      synopsis:"The lives of two mob hitmen, a boxer, a gangster and his wife, and a pair of diner bandits intertwine in four tales of violence and redemption.",
      duration:154,
      thumbnail:"https://i.imgur.com/8xf630M.mp4"}) {
    value{title}
  }

   miamadre1: insertmovies_by_genre(
    value: { 
      genre:"Award-Winning", 
      year:2015,
      title:"Mia Madre",
      synopsis:"Margherita, a director in the middle of an existential crisis, has to deal with the inevitable and still unacceptable loss of her mother.",
      duration:106,
      thumbnail:"https://i.imgur.com/mRz7x3g.mp4"}) {
    value{title}
  }

   miamadre2: insertmovies_by_genre(
    value: { 
      genre:"Award-Winning", 
      year:2005,
      title:"Mia Madre",
      synopsis:"Margherita, a director in the middle of an existential crisis, has to deal with the inevitable and still unacceptable loss of her mother.",
      duration:106,
      thumbnail:"https://i.imgur.com/mRz7x3g.mp4"}) {
    value{title}
  }

   miamadre3: insertmovies_by_genre(
    value: { 
      genre:"Award-Winning", 
      year:1995,
      title:"Mia Madre",
      synopsis:"Margherita, a director in the middle of an existential crisis, has to deal with the inevitable and still unacceptable loss of her mother.",
      duration:106,
      thumbnail:"https://i.imgur.com/mRz7x3g.mp4"}) {
    value{title}
  }
  

  nemo1: insertmovies_by_genre(
    value: { 
      genre:"Children & Family", 
      year:2003,
      title:"Finding Nemo",
      synopsis:"After his son is captured in the Great Barrier Reef and taken to Sydney, a timid clownfish sets out on a journey to bring him home.",
      duration:100,
      thumbnail:"https://i.imgur.com/HtjzC5p.mp4"}) {
    value{title}
  }

   nemo2: insertmovies_by_genre(
    value: { 
      genre:"Children & Family", 
      year:2013,
      title:"Finding Nemo",
      synopsis:"After his son is captured in the Great Barrier Reef and taken to Sydney, a timid clownfish sets out on a journey to bring him home.",
      duration:100,
      thumbnail:"https://i.imgur.com/HtjzC5p.mp4"}) {
    value{title}
  }

   nemo3: insertmovies_by_genre(
    value: { 
      genre:"Children & Family", 
      year:1993,
      title:"Finding Nemo",
      synopsis:"After his son is captured in the Great Barrier Reef and taken to Sydney, a timid clownfish sets out on a journey to bring him home.",
      duration:100,
      thumbnail:"https://i.imgur.com/HtjzC5p.mp4"}) {
    value{title}
  }

  frog1: insertmovies_by_genre(
    value: { 
      genre:"Children & Family", 
      year:2013,
      title:"Frog Kingdom",
      synopsis:"Princess Froglegs goes undercover to compete in her father's Froglympics in order to avoid being married off to a male suitor.",
      duration:86,
      thumbnail:"https://i.imgur.com/TYDj9ud.mp4"}) {
    value{title}
  }

  frog2: insertmovies_by_genre(
    value: { 
      genre:"Children & Family", 
      year:2003,
      title:"Frog Kingdom",
      synopsis:"Princess Froglegs goes undercover to compete in her father's Froglympics in order to avoid being married off to a male suitor.",
      duration:86,
      thumbnail:"https://i.imgur.com/TYDj9ud.mp4"}) {
    value{title}
  }

  frog3: insertmovies_by_genre(
    value: { 
      genre:"Children & Family", 
      year:1993,
      title:"Frog Kingdom",
      synopsis:"Princess Froglegs goes undercover to compete in her father's Froglympics in order to avoid being married off to a male suitor.",
      duration:86,
      thumbnail:"https://i.imgur.com/TYDj9ud.mp4"}) {
    value{title}
  }

  turtle1: insertmovies_by_genre(
    value: { 
      genre:"Children & Family", 
      year:2016,
      title:"Teenage Mutant Ninja Turtles 2",
      synopsis:"The Turtles get into another battle with their enemy the Shredder, who has acquired new allies: the mutant thugs Bebop and Rocksteady and the alien being Krang.",
      duration:116,
      thumbnail:"https://i.imgur.com/KNgrqaP.mp4"}) {
    value{title}
  }

  turtle2: insertmovies_by_genre(
    value: { 
      genre:"Children & Family", 
      year:2006,
      title:"Teenage Mutant Ninja Turtles 2",
      synopsis:"The Turtles get into another battle with their enemy the Shredder, who has acquired new allies: the mutant thugs Bebop and Rocksteady and the alien being Krang.",
      duration:116,
      thumbnail:"https://i.imgur.com/KNgrqaP.mp4"}) {
    value{title}
  }

  turtle3: insertmovies_by_genre(
    value: { 
      genre:"Children & Family", 
      year:1996,
      title:"Teenage Mutant Ninja Turtles 2",
      synopsis:"The Turtles get into another battle with their enemy the Shredder, who has acquired new allies: the mutant thugs Bebop and Rocksteady and the alien being Krang.",
      duration:116,
      thumbnail:"https://i.imgur.com/KNgrqaP.mp4"}) {
    value{title}
  }

  incredible1: insertmovies_by_genre(
    value: { 
      genre:"Children & Family", 
      year:2004,
      title:"The incredibles",
      synopsis:"A family of undercover superheroes, while trying to live the quiet suburban life, are forced into action to save the world.",
      duration:105,
      thumbnail:"https://i.imgur.com/eThziEz.mp4"}) {
    value{title}
  }

  incredible2: insertmovies_by_genre(
    value: { 
      genre:"Children & Family", 
      year:2014,
      title:"The incredibles",
      synopsis:"A family of undercover superheroes, while trying to live the quiet suburban life, are forced into action to save the world.",
      duration:105,
      thumbnail:"https://i.imgur.com/eThziEz.mp4"}) {
    value{title}
  }

  incredible3: insertmovies_by_genre(
    value: { 
      genre:"Children & Family", 
      year:1994,
      title:"The incredibles",
      synopsis:"A family of undercover superheroes, while trying to live the quiet suburban life, are forced into action to save the world.",
      duration:105,
      thumbnail:"https://i.imgur.com/eThziEz.mp4"}) {
    value{title}
  }

  toystory1: insertmovies_by_genre(
    value: { 
      genre:"Children & Family", 
      year:1995,
      title:"Toy Story",
      synopsis:"A cowboy doll is profoundly threatened and jealous when a new spaceman figure supplants him as top toy in a boy's room.",
      duration:81,
      thumbnail:"https://i.imgur.com/8kisA8v.mp4"}) {
    value{title}
  }

  toystory2: insertmovies_by_genre(
    value: { 
      genre:"Children & Family", 
      year:2005,
      title:"Toy Story",
      synopsis:"A cowboy doll is profoundly threatened and jealous when a new spaceman figure supplants him as top toy in a boy's room.",
      duration:81,
      thumbnail:"https://i.imgur.com/8kisA8v.mp4"}) {
    value{title}
  }

toystory3: insertmovies_by_genre(
    value: { 
      genre:"Children & Family", 
      year:2015,
      title:"Toy Story",
      synopsis:"A cowboy doll is profoundly threatened and jealous when a new spaceman figure supplants him as top toy in a boy's room.",
      duration:81,
      thumbnail:"https://i.imgur.com/8kisA8v.mp4"}) {
    value{title}
  }


  bridget1: insertmovies_by_genre(
    value: { 
      genre:"Comedies", 
      year:2016,
      title:"Bridget Jones's Baby",
      synopsis:"Forty-something and single again, Bridget decides to focus on her job and surround herself with friends. In a twist, she finds herself pregnant, but with one hitch - she can only be fifty percent sure of the identity of her baby's father.",
      duration:123,
      thumbnail:"https://i.imgur.com/O6XpreV.mp4"}) {
    value{title}
  }

  bridget2: insertmovies_by_genre(
    value: { 
      genre:"Comedies", 
      year:2006,
      title:"Bridget Jones's Baby",
      synopsis:"Forty-something and single again, Bridget decides to focus on her job and surround herself with friends. In a twist, she finds herself pregnant, but with one hitch - she can only be fifty percent sure of the identity of her baby's father.",
      duration:123,
      thumbnail:"https://i.imgur.com/O6XpreV.mp4"}) {
    value{title}
  }

  bridget3: insertmovies_by_genre(
    value: { 
      genre:"Comedies", 
      year:1996,
      title:"Bridget Jones's Baby",
      synopsis:"Forty-something and single again, Bridget decides to focus on her job and surround herself with friends. In a twist, she finds herself pregnant, but with one hitch - she can only be fifty percent sure of the identity of her baby's father.",
      duration:123,
      thumbnail:"https://i.imgur.com/O6XpreV.mp4"}) {
    value{title}
  }

  bridget4: insertmovies_by_genre(
    value: { 
      genre:"Comedies", 
      year:1986,
      title:"Bridget Jones's Baby",
      synopsis:"Forty-something and single again, Bridget decides to focus on her job and surround herself with friends. In a twist, she finds herself pregnant, but with one hitch - she can only be fifty percent sure of the identity of her baby's father.",
      duration:123,
      thumbnail:"https://i.imgur.com/O6XpreV.mp4"}) {
    value{title}
  }

  ninelives1: insertmovies_by_genre(
    value: { 
      genre:"Comedies", 
      year:2016,
      title:"Nine Lives",
      synopsis:"Forty-something and single again, Bridget decides to focus on her job and surround herself with friends. In a twist, she finds herself pregnant, but with one hitch - she can only be fifty percent sure of the identity of her baby's father.",
      duration:87,
      thumbnail:"https://i.imgur.com/u24oIR1.mp4"}) {
    value{title}
  }

  ninelives2: insertmovies_by_genre(
    value: { 
      genre:"Comedies", 
      year:2006,
      title:"Nine Lives",
      synopsis:"Forty-something and single again, Bridget decides to focus on her job and surround herself with friends. In a twist, she finds herself pregnant, but with one hitch - she can only be fifty percent sure of the identity of her baby's father.",
      duration:87,
      thumbnail:"https://i.imgur.com/u24oIR1.mp4"}) {
    value{title}
  }

  ninelives3: insertmovies_by_genre(
    value: { 
      genre:"Comedies", 
      year:1996,
      title:"Nine Lives",
      synopsis:"Forty-something and single again, Bridget decides to focus on her job and surround herself with friends. In a twist, she finds herself pregnant, but with one hitch - she can only be fifty percent sure of the identity of her baby's father.",
      duration:87,
      thumbnail:"https://i.imgur.com/u24oIR1.mp4"}) {
    value{title}
  }

  ninelives4: insertmovies_by_genre(
    value: { 
      genre:"Comedies", 
      year:1986,
      title:"Nine Lives",
      synopsis:"Forty-something and single again, Bridget decides to focus on her job and surround herself with friends. In a twist, she finds herself pregnant, but with one hitch - she can only be fifty percent sure of the identity of her baby's father.",
      duration:87,
      thumbnail:"https://i.imgur.com/u24oIR1.mp4"}) {
    value{title}
  }

  mike1: insertmovies_by_genre(
    value: { 
      genre:"Comedies", 
      year:2016,
      title:"Mike and Dave Need Wedding Dates",
      synopsis:"Two hard-partying brothers place an online ad to find the perfect dates for their sister's Hawaiian wedding. Hoping for a wild getaway, the boys instead find themselves out-hustled by an uncontrollable duo.",
      duration:88,
      thumbnail:"https://i.imgur.com/4nlbiGT.mp4"}) {
    value{title}
  }

  mike2: insertmovies_by_genre(
    value: { 
      genre:"Comedies", 
      year:2006,
      title:"Mike and Dave Need Wedding Dates",
      synopsis:"Two hard-partying brothers place an online ad to find the perfect dates for their sister's Hawaiian wedding. Hoping for a wild getaway, the boys instead find themselves out-hustled by an uncontrollable duo.",
      duration:88,
      thumbnail:"https://i.imgur.com/4nlbiGT.mp4"}) {
    value{title}
  }

  mike3: insertmovies_by_genre(
    value: { 
      genre:"Comedies", 
      year:1996,
      title:"Mike and Dave Need Wedding Dates",
      synopsis:"Two hard-partying brothers place an online ad to find the perfect dates for their sister's Hawaiian wedding. Hoping for a wild getaway, the boys instead find themselves out-hustled by an uncontrollable duo.",
      duration:88,
      thumbnail:"https://i.imgur.com/4nlbiGT.mp4"}) {
    value{title}
  }

  mike4: insertmovies_by_genre(
    value: { 
      genre:"Comedies", 
      year:1986,
      title:"Mike and Dave Need Wedding Dates",
      synopsis:"Two hard-partying brothers place an online ad to find the perfect dates for their sister's Hawaiian wedding. Hoping for a wild getaway, the boys instead find themselves out-hustled by an uncontrollable duo.",
      duration:88,
      thumbnail:"https://i.imgur.com/4nlbiGT.mp4"}) {
    value{title}
  }
  

  firstp1: insertmovies_by_genre(
    value: { 
      genre:"Documentaries", 
      year:2011,
      title:"First Position",
      synopsis:"A documentary that follows six young dancers from around the world as they prepare for the Youth America Grand Prix, one of the most prestigious ballet competitions in the world.",
      duration:95,
      thumbnail:"https://i.imgur.com/Coz5yzb.mp4"}) {
    value{title}
  }

  firstp2: insertmovies_by_genre(
    value: { 
      genre:"Documentaries", 
      year:2001,
      title:"First Position",
      synopsis:"A documentary that follows six young dancers from around the world as they prepare for the Youth America Grand Prix, one of the most prestigious ballet competitions in the world.",
      duration:95,
      thumbnail:"https://i.imgur.com/Coz5yzb.mp4"}) {
    value{title}
  }

  firstp3: insertmovies_by_genre(
    value: { 
      genre:"Documentaries", 
      year:1991,
      title:"First Position",
      synopsis:"A documentary that follows six young dancers from around the world as they prepare for the Youth America Grand Prix, one of the most prestigious ballet competitions in the world.",
      duration:95,
      thumbnail:"https://i.imgur.com/Coz5yzb.mp4"}) {
    value{title}
  }

  firstp4: insertmovies_by_genre(
    value: { 
      genre:"Documentaries", 
      year:1981,
      title:"First Position",
      synopsis:"A documentary that follows six young dancers from around the world as they prepare for the Youth America Grand Prix, one of the most prestigious ballet competitions in the world.",
      duration:95,
      thumbnail:"https://i.imgur.com/Coz5yzb.mp4"}) {
    value{title}
  }

  path1: insertmovies_by_genre(
    value: { 
      genre:"Documentaries", 
      year:2007,
      title:"Path of glory",
      synopsis:"After refusing to attack an enemy position, a general accuses the soldiers of cowardice and their commanding officer must defend them.",
      duration:88,
      thumbnail:"https://i.imgur.com/xZid5oj.mp4"}) {
    value{title}
  }

   path2: insertmovies_by_genre(
    value: { 
      genre:"Documentaries", 
      year:1997,
      title:"Path of glory",
      synopsis:"After refusing to attack an enemy position, a general accuses the soldiers of cowardice and their commanding officer must defend them.",
      duration:88,
      thumbnail:"https://i.imgur.com/xZid5oj.mp4"}) {
    value{title}
  }

   path3: insertmovies_by_genre(
    value: { 
      genre:"Documentaries", 
      year:1987,
      title:"Path of glory",
      synopsis:"After refusing to attack an enemy position, a general accuses the soldiers of cowardice and their commanding officer must defend them.",
      duration:88,
      thumbnail:"https://i.imgur.com/xZid5oj.mp4"}) {
    value{title}
  }

   path4: insertmovies_by_genre(
    value: { 
      genre:"Documentaries", 
      year:2017,
      title:"Path of glory",
      synopsis:"After refusing to attack an enemy position, a general accuses the soldiers of cowardice and their commanding officer must defend them.",
      duration:88,
      thumbnail:"https://i.imgur.com/xZid5oj.mp4"}) {
    value{title}
  }

 girl1: insertmovies_by_genre(
    value: { 
      genre:"Dramas", 
      year:2016,
      title:"The girl on the Train",
      synopsis:"A divorcee becomes entangled in a missing persons investigation that promises to send shockwaves throughout her life.",
      duration:112,
      thumbnail:"https://i.imgur.com/yinQyyT.mp4"}) {
    value{title}
  }

  doctorstrange1: insertmovies_by_genre(
    value: { 
      genre:"Fantasy", 
      year:2016,
      title:"Doctor Strange",
      synopsis:"While on a journey of physical and spiritual healing, a brilliant neurosurgeon is drawn into the world of the mystic arts.",
      duration:115,
      thumbnail:"https://i.imgur.com/AARIL26.mp4"}) {
    value{title}
  }

  fantastic_beast1: insertmovies_by_genre(
    value: { 
      genre:"Fantasy", 
      year:2016,
      title:"Fantastic Beasts and Where to Find Them",
      synopsis:"The adventures of writer Newt Scamander in New York's secret community of witches and wizards seventy years before Harry Potter reads his book in school.",
      duration:132,
      thumbnail:"https://i.imgur.com/NhenJym.mp4"}) {
    value{title}
  }

  sleeping_beauty1: insertmovies_by_genre(
    value: { 
      genre:"Fantasy", 
      year:2016,
      title:"The Curse of Sleeping Beauty",
      synopsis:"Thomas unexpectedly inherits a property with a mysterious curse.",
      duration:132,
      thumbnail:"https://i.imgur.com/LcqMMwG.mp4"}) {
    value{title}
  }

  lotr1: insertmovies_by_genre(
    value: { 
      genre:"Fantasy", 
      year:2001,
      title:"The Fellowship of the Ring",
      synopsis:"A meek Hobbit from the Shire and eight companions set out on a journey to destroy the powerful One Ring and save Middle-earth from the Dark Lord Sauron.",
      duration:178,
      thumbnail:"https://i.imgur.com/YdhTLqF.mp4"}) {
    value{title}
  }

  mummy1: insertmovies_by_genre(
    value: { 
      genre:"Fantasy", 
      year:1999,
      title:"The Mummy",
      synopsis:"At an archaeological dig in the ancient city of Hamunaptra, an American serving in the French Foreign Legion accidentally awakens a mummy who begins to wreak havoc as he searches for the reincarnation of his long-lost love.",
      duration:124,
      thumbnail:"https://i.imgur.com/62tJ58E.mp4"}) {
    value{title}
  }

 amelie1: insertmovies_by_genre(
    value: { 
      genre:"French", 
      year:2001,
      title:"Amelie",
      synopsis:"Amélie is an innocent and naive girl in Paris with her own sense of justice. She decides to help those around her and, along the way, discovers love.",
      duration:122,
      thumbnail:"https://i.imgur.com/fan0H9k.mp4"}) {
    value{title}
  }
  
 ava1: insertmovies_by_genre(
    value: { 
      genre:"Horror", 
      year:2015,
      title:"Ava's possession.",
      synopsis:"A young woman recovers from a demonic possession.",
      duration:89,
      thumbnail:"https://i.imgur.com/l6krM70.mp4"}) {
    value{title}
  }

  rotting1: insertmovies_by_genre(
    value: { 
      genre:"Horror", 
      year:2016,
      title:"Little Dead Rotting Hood",
      synopsis:"The residents of a small town discover that something more sinister than killer wolves is lurking in the backwoods: first the wolves start turning up dead...then people.",
      duration:88,
      thumbnail:"https://i.imgur.com/C2XcrZJ.mp4"}) {
    value{title}
  }

  room1: insertmovies_by_genre(
    value: { 
      genre:"Horror", 
      year:2015,
      title:"Room",
      synopsis:"Held captive for 7 years in an enclosed space, a woman and her young son finally gain their freedom, allowing the boy to experience the outside world for the first time.",
      duration:118,
      thumbnail:"https://i.imgur.com/Fx5iKwZ.mp4"}) {
    value{title}
  }

  conjuring1: insertmovies_by_genre(
    value: { 
      genre:"Horror", 
      year:2016,
      title:"The Conjuring 2",
      synopsis:"Ed and Lorraine Warren travel to North London to help a single mother raising four children alone in a house plagued by a supernatural spirit.",
      duration:134,
      thumbnail:"https://i.imgur.com/j3qBgq8.mp4"}) {
    value{title}
  }
  

enteringred1: insertmovies_by_genre( value: { genre:"Independent", year:2019, title:"Entering red", synopsis:"A woman walks into a bar and is sold the life of her dreams.", duration:12, thumbnail:"https://i.imgur.com/K7ERYIB.mp4"}) { value{title} }

warroom1: insertmovies_by_genre( value: { genre:"Independent", year:2019, title:"War Room", synopsis:"A seemingly perfect family looks to fix their problems with the help of Miss Clara, an older, wiser woman.", duration:120, thumbnail:"https://i.imgur.com/ZFFosSD.mp4"}) { value{title} }


  goldenage1: insertmovies_by_genre(
    value: { 
      genre:"Music", 
      year:2004,
      title:"The Golden Age",
      synopsis:"A seemingly perfect family looks to fix their problems with the help of Miss Clara, an older, wiser woman.",
      duration:114,
      thumbnail:"https://i.imgur.com/SQyPd7N.mp4"}) {
    value{title}
  }

   whiplash1: insertmovies_by_genre(
    value: { 
      genre:"Music", 
      year:2014,
      title:"Whiplash",
      synopsis:"A promising young drummer enrolls at a cut-throat music conservatory where his dreams of greatness are mentored by an instructor who will stop at nothing to realize a student's potential.",
      duration:106,
      thumbnail:"https://i.imgur.com/ZTOIYrc.mp4"}) {
    value{title}
  }


lovemercy1: insertmovies_by_genre(
    value: { 
      genre:"Romance", 
      year:2014,
      title:"Love and Mercy",
      synopsis:"In the 60s, Beach Boys leader Brian Wilson struggles with emerging psychosis as he attempts to craft his avant-garde pop masterpiece. In the 80s, he is a broken, confused man under the 24-hour watch of shady therapist Dr. Eugene Landy.",
      duration:121,
      thumbnail:"https://i.imgur.com/tZtTkBf.mp4"}) {
    value{title}
  }

perfectmatch1: insertmovies_by_genre(
    value: { 
      genre:"Romance", 
      year:2016,
      title:"The perfect match",
      synopsis:"A playboy named Charlie, convinced that all his relationships are dead, meets the beautiful and mysterious Eva. Agreeing to a casual affair, Charlie then wants a bit more from their relationship.",
      duration:96,
      thumbnail:"https://i.imgur.com/XqSrnvi.mp4"}) {
    value{title}
  }

 terminator2: insertmovies_by_genre(
    value: { 
      genre:"Sci-Fi", 
      year:1991,
      title:"Terminator 2",
      synopsis:"A cyborg, identical to the one who failed to kill Sarah Connor, must now protect her ten year old son, John Connor, from a more advanced and powerful cyborg.",
      duration:137,
      thumbnail:"https://i.imgur.com/0RworbR.mp4"}) {
    value{title}
   }

 inception: insertmovies_by_genre(
    value: { 
      genre:"Sci-Fi", 
      year:2010,
      title:"Inception",
      synopsis:"Cobb steals information from his targets by entering their dreams.",
      duration:121,
      thumbnail:"https://i.imgur.com/RPa4UdO.mp4"}) {
    value{title}
   }
  
  prometheus: insertmovies_by_genre(value: { 
      genre:"Sci-Fi", 
      year:2012,
      title:"Prometheus",
      synopsis:"After a clue to mankind's origins is discovered, explorers are sent to the darkest corner of the universe.",
      duration:134,
      thumbnail:"https://i.imgur.com/L8k6Bau.mp4"}) {
    value{title}
    }
  
    aliens: insertmovies_by_genre(value: { 
      genre:"Sci-Fi", 
      year:1986,
      title:"Aliens",
      synopsis:"Ellen Ripley is sent back to the planet LV-426 to establish contact with a terraforming colony.",
      duration:134,
      thumbnail:"https://i.imgur.com/QvkrnyZ.mp4"}) {
    value{title}
    }
  
    bladeRunner: insertmovies_by_genre(value: { 
      genre:"Sci-Fi", 
      year:1982,
      title:"Blade Runner",
      synopsis:"Young Blade Runner K's discovery of a long-buried secret leads him to track down former Blade Runner Rick Deckard.",
      duration:145,
      thumbnail:"https://i.imgur.com/xhhvmj1.mp4"}) {
    value{title}
    }

    starTrek: insertmovies_by_genre(value: { 
      genre:"Sci-Fi", 
      year:1995,
      title:"Star Trek",
      synopsis:"Star trek, the next generation",
      duration:134,
      thumbnail:"https://i.imgur.com/CyBAqqD.mp4"}) {
    value{title}
    }

    wonderWoman: insertmovies_by_genre(value: { 
      genre:"Sci-Fi", 
      year:2017,
      title:"Wonder Woman",
      synopsis:"When a pilot crashes and tells of conflict in the outside world, Diana, an Amazonian warrior in training, leaves home.",
      duration:134,
      thumbnail:"https://i.imgur.com/WHf4VQf.mp4"}) {
    value{title}
    }
    
    looper: insertmovies_by_genre(value: { 
      genre:"Sci-Fi", 
      year:2012,
      title:"Looper",
      synopsis:"In the near future, the mob sends their victims back in time to get them executed by the loopers.",
      duration:156,
      thumbnail:"https://i.imgur.com/B1v1FRi.mp4"}) {
    value{title}
    }

    exMachina: insertmovies_by_genre(value: { 
      genre:"Sci-Fi", 
      year: 2015,
      title:"Ex machina",
      synopsis:"Caleb Smith, a young programmer, gets a chance to become a part of a strange scientific experiment.",
      duration:134,
      thumbnail:"https://i.imgur.com/CeFGCCH.mp4"}) {
    value{title}
    }

    doctorStrange: insertmovies_by_genre(value: { 
      genre:"Sci-Fi", 
      year:2016,
      title:"Doctor Strange",
      synopsis:"In an accident, Stephen Strange, a famous neurosurgeon, loses the ability to use his hands.",
      duration:156,
      thumbnail:"https://i.imgur.com/VAiM0Pr.mp4"}) {
    value{title}
    }

    her: insertmovies_by_genre(value: { 
      genre:"Sci-Fi", 
      year:2013,
      title:"Her",
      synopsis:" A sensitive and soulful man earns a living by writing personal letters for other people.",
      duration:134,
      thumbnail:"https://i.imgur.com/y3NCz30.mp4"}) {
    value{title}
    }     

    theMartian: insertmovies_by_genre(value: { 
      genre:"Sci-Fi", 
      year:2015,
      title:"The Martian",
      synopsis:"During a manned mission to Mars, Astronaut Mark Watney is presumed dead after a fierce storm and left behind by his crew.",
      duration:134,
      thumbnail:"https://i.imgur.com/DffSwK0.mp4"}) {
    value{title}
    }

    deadpool: insertmovies_by_genre(value: { 
      genre:"Sci-Fi", 
      year:2016,
      title:"Deadpool",
      synopsis:"A wisecracking mercenary gets experimented on and becomes immortal but ugly, and sets out to track down the man who ruined his looks.",
      duration:156,
      thumbnail:"https://i.imgur.com/BmasM7v.mp4"}) {
    value{title}
    }
    
    upgrade: insertmovies_by_genre(value: { 
      genre:"Sci-Fi", 
      year: 2018,
      title:"Upgrade",
      synopsis:"Grey, a technophobe, suffers paralysis and loses his wife during an attack.",
      duration:123,
      thumbnail:"https://i.imgur.com/UgnxAc5.mp4"}) {
    value{title}
    }

    okra: insertmovies_by_genre(value: { 
      genre:"Sci-Fi", 
      year:2018,
      title:"Okra",
      synopsis:"For 10 idyllic years, young Mija has been caretaker and constant companion to Okja - a massive animal and an even bigger friend.",
      duration:123,
      thumbnail:"https://i.imgur.com/ieICjCJ.mp4"}) {
    value{title}
    }

    xMen: insertmovies_by_genre(value: { 
      genre:"Sci-Fi", 
      year:2000,
      title:"X-men",
      synopsis:"X-Men is an American superhero film based on the fictional superhero team of the same name",
      duration:134,
      thumbnail:"https://i.imgur.com/8Fj0T1U.mp4"}) {
    value{title}
    }

    batmanBegins: insertmovies_by_genre(value: { 
      genre:"Sci-Fi", 
      year:2005,
      title:"Batman Begins",
      synopsis:"After witnessing his parents' death, Bruce learns the art of fighting to confront injustice.",
      duration:125,
      thumbnail:"https://i.imgur.com/f5mRd6r.mp4"}) {
    value{title}
    } 

    ironMan: insertmovies_by_genre(value: { 
      genre:"Sci-Fi", 
      year:2008,
      title:"Iron Man",
      synopsis:"After being held captive in an Afghan cave, billionaire engineer Tony Stark creates a unique weaponized suit of armor to fight evil.",
      duration:132,
      thumbnail:"https://i.imgur.com/Y9pEiJH.mp4"}) {
    value{title}
    }
    
    kong: insertmovies_by_genre(value: { 
      genre:"Sci-Fi", 
      year:2017,
      title:"Kong: Skull Island",
      synopsis:"A crew that reaches Skull Island to map it, is attacked by a humongous ape.",
      duration:145,
      thumbnail:"https://i.imgur.com/rXA51dG.mp4"}) {
    value{title}
    }

    aliens3: insertmovies_by_genre(value: { 
      genre:"Sci-Fi", 
      year:1992,
      title:"aliens 3",
      synopsis:"Ellen Ripley's escape pod crash-lands on Fiorina 161, a penal colony planet terrorised by an alien.",
      duration:145,
      thumbnail:"https://i.imgur.com/HrChN9I.mp4"}) {
    value{title}
    }

    avatar: insertmovies_by_genre(value: { 
      genre:"Sci-Fi", 
      year:2009,
      title:"Avatar",
      synopsis:"A paraplegic Marine dispatched to the moon Pandora on a unique mission becomes torn between following his orders and protecting the world.",
      duration:134,
      thumbnail:"https://i.imgur.com/lrAI1jQ.mp4"}) {
    value{title}
    }

 jaws: insertmovies_by_genre(
    value: { 
      genre:"Thriller", 
      year:2018,
      title:"Jaws",
      synopsis:"A movie about an angry Shark.",
      duration:112,
      thumbnail:"https://i.imgur.com/yinQyyT.mp4"}) {
    value{title}
  }

}

query getAllGenre {
    reference_list (value: {label:"genre"}) {
      values {
        value
      }
    }
}


query getMovieAction {
    movies_by_genre (
      value: {genre:"Sci-Fi"},
       orderBy: [year_DESC]) {
      values {
        year,
        title,
        duration,
        thumbnail
      }
    }
}
```