# E_CommerceBackEnd

## ⛅Welcome to 'E-Coomerce Back-End'

![Readme Generator](https://github.com/ahrumnoh/E_CommerceBackEnd/blob/main/image/E-%20Commerce%20Back-end.jpg?raw=true)



## Overview

To build the back end for an e-commerce site and also configure a working Express.js API to use Sequelize to interact with a MySQL database.


## 🚩How to execute it? Check the DEMO Video for instruction


![Watch the video](https://github.com/ahrumnoh/ReadmeGenerator/blob/main/Image/Check%20the%20video%20NOW%20(1).jpg?raw=true)





 ## Click the picture below 👇


 🎇 Part1 - Demo Video - node index.js :https://drive.google.com/file/d/18qdX5A_qcp7NijERUVEvgeyQ2P6BiQeK/view

[![Watch the video](https://github.com/ahrumnoh/E_CommerceBackEnd/blob/main/image/Screenshot%20(45).png?raw=true)](https://drive.google.com/file/d/18qdX5A_qcp7NijERUVEvgeyQ2P6BiQeK/view)



 ✨ Part2 - Demo video Insomnia  : https://drive.google.com/file/d/1sn0geS0TWLMqxxV-lMevRDo4n-PNHfzd/view

[![Watch the video](https://github.com/ahrumnoh/E_CommerceBackEnd/blob/main/image/Screenshot%20(44).png?raw=true)](https://drive.google.com/file/d/1sn0geS0TWLMqxxV-lMevRDo4n-PNHfzd/view)





## Installation in VS code

The user should clone the repository from GitHub and Use the schema.sql file in the db folder to create your database with MySQL shell commands


* Change '.env.EXAMPLE' ---> '.env'
* Your details must be put into the file as DB_USER='', DB_PW='' in '.env'file
===============================================================================

* mysql -u root -p
* source db/schema.sql
* DROP DATABASE IF EXISTS ecommerce_db;
* CREATE DATABASE ecommerce_db;
* quit
===============================================================================

* ✔$ npm init -y
* ✔$ npm install
* ✔$ npm install inquirer

===============================================================================

* ✔$ node seeds/index
===============================================================================

## Usage in VS code
* ✔$ npm start
* ✔$ node index.js


## 😎 in this project

* Database Models
* Product belongs to Category, and Category has many Product models, as a category can have multiple products but a product can only belong to one category.
* Product belongs to many Tag models, and Tag belongs to many Product models. Allow products to have multiple tags and tags to have many products by using the ProductTag through model.
* Filled Out the API Routes to Perform RESTful CRUD Operations
* Seed the Database
* server.js to sync the Sequelize models to the MySQL database on server start




## License 
This project is license under MIT


❤ Thank you so much for your time :)





