# solution Homework

## Multiple selectors in a find() command


`cd .. week2/01_creating_documents`

`mongorestore dump`

`use video`


`db.movieDetails.find({rated: "PG-13", "awards.wins": 0 , year:2013},{title:1}).pretty();`

##### A Decade of Decadence, Pt. 2: Legacy of Dreams
