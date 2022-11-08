# jfs-22-ProductApp

# The Product APP

Initialize with spring.io (either via spring initializr or intelliJ directly)
Should use postgresql
Use data.sql and schema.sql to initialize database  
Host the database on elephant, or optionally using docker
Build a JPA-repo to interact with database
Create endpoints with spring-web
Connect to nextJS frontend

Specification
Must be able to
Add product to database
Get product(s) from database
Delete product from database
Should patch product in database
Should be able to
Commit crud operations from front end (?)
Must initialize database with predetermined data
May contain relational data between product categories
Should use TDD
Should not change table structure after DB is initialized
Mayhaps use docker :( 

At the end of the day, you should be able to read and write from a database in SQL and see the result in postman. If you have time, connect it to a front-end application using next.js. Cascading superfun sheets are optional.






Data for  e-commerce

Product
id: a numerical, auto-generated Primary Key
title: A text field
price: a numerical value
description: a text fild
Image: a text field
category_id : foreign key to category table


Category
id: a numerical, auto-generated Primary Key
category: A text field
