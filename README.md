# mongo-start
1)
```javascript
db.books.insertMany([
  {title: "Witcher", description: "Polish fantasy", authors: "Andrzej Sapkowski"},
  {title: "Star Wars", description: "American fantastic", authors: "George Lucas"}
]);
```

2)
```javascript
db.books.find({title: "Witcher"});
```

3)
```javascript
db.books.updateOne(
  {_id: ObjectId("...")},
  {$set: {description: "Political economy", authors: "Vladimir Lenin"}}
 );
```
