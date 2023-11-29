# MongoDB-basics
This repo is for basic operations we can perform through mongoDB database.

Comparison with SQL

![image](https://github.com/SanchitBatra-DevelopAnything/MongoDB-basics/assets/61592754/9aa3b6e3-e736-49d4-b00b-3421dda34183)

--------------

1.) Install community edition through brew
2.) Start the background mongodb service
3.) Do mongosh in terminal to get started

Instructions : https://www.mongodb.com/docs/manual/tutorial/install-mongodb-on-os-x/#std-label-install-mdb-community-macos
----------------

Some concepts : 

1.) db.collection.insertOne({.............data here})

db refers to the current database which has been selected , eg : use houses (houses is the db name , and db. means houses ke andar)
say we have collection called Rohini

db.Rohini.insertOne({...})

means houses me Rohini collection ke andar ye data daaldo

