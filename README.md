## MongoDB CRUD in NodeJS - Example / Demo code

## What is this?
Demo code that excercises MongoDB Create Read Update Delete (CRUD) operations with the mongoose npm module

## Contains
- /config = mongo config sample file
- /controller = controller code with routes and DB operations in  personController.js
- /public = stylesheet for HTML views
- /views EJS views for the various application HTML pages
- app.js main webserver code

### Mongo Functionality:
- Add a person
- List person(s)
- Update person (needs MongoID from list function)
- Delete person (needs MongoID from list function)

## Acknowledgements
CSS template inspired from: https://www.sanwebe.com/2014/08/css-html-forms-designs


## Installation overview

### Clone Repo an install module dependencies

```
git clone https://github.com/ajyounguk/mongodb-crud-demo
cd mongodb-crud-demo
npm install
```

### Mongo Config:
Copy /config/mongo-config-sample.json to mongo-config.json
Needs mongo username and password and mongo running with --auth
```
cp config-sample.json config.json
```


## How to run it
node app.js

point your browser at the local/remoteIP port 3000 to load the HTML app


### EOF Readme..
For more information on MongoDB:
https://www.mongodb.com/what-is-mongodb

For more information on Express:
https://www.npmjs.com/package/express

For more information on Mongoose:
https://www.npmjs.com/package/mongoose
