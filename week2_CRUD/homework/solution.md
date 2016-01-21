# solution Homework

## Multiple selectors in a find() command


`cd .. week2/01_creating_documents`

`mongorestore dump`

`use video`


`db.movieDetails.find({rated: "PG-13", "awards.wins": 0 , year:2013},{title:1}).pretty();`

##### A Decade of Decadence, Pt. 2: Legacy of Dreams


## Homework: Arrays with nested documents


`use video`

##### `{"awards.oscars.award": "bestPicture"}`


## Homework: Simple projection

##### `{"title": 1, "_id": 0}`

## Homework: Arrays with nested documents

The first result of `db.getCollection('movieDetails').find({"countries.1":"Sweden"}).pretty();`

##### The Girl with the Dragon Tattoo

## Homework: Equality queries on arrays

##### `db.movieDetails.find({genres: ["Comedy", "Crime"]}).count();`

##### 20

## Homework: Array Operators

##### `db.getCollection('movieDetails').find({genres: {$all: ["Comedy", "Crime"]}}).count()`

##### 56

## Homework: Updating scalar fields

##### $set
