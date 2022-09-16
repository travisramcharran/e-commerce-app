# E-Commerce-App
Still a work in progress, some routes are not functional.

## Description
This project uses a combination of express.js, SQL, mysql2, and Sequelize to create the back end of a simple ecommerce site. The purpose of this assignment was to deepen our understanding of Object-Relational Mapping. This was done by letting us connect various parts of an application's back-end, namely its MySQL Database and API routes, through a Node.js package called Sequelize. This is a back-end application for an e-commerce site that allows the company to view information about it's products, their categories, and tags. It also enables the company to create, update, or delete data whenever it is necessary.

## Usage/Installation

     Follow these steps in order to use this application:
     
     Clone repository into local directory.
     
     Open up command-line application and navigate to directory holding this repository.
     
     Type "npm init -y" to initialize Node.js, and then type and enter "npm install" to download the required dependencies in terminal.

     Create a file called .env (in root directory), and enter the database, your MySQL username, and your MySQL password in the following format:

        DB_NAME= ecommerce_db

        DB_USER= your MYSQL username

        DB_PASSWORD= your MySQL password

        Access your MySQL shell ("mysql -u root -p" in the command-line) and create the schema by typing "source db/schema.sql". 
        
        After that, make sure you leave the MySQL Shell using "quit".

        Seed the database from the command-line with "npm run seed".

        Start the application server with "npm start".

        Open an API software such as Insomnia to test the routes!

## Walkthrough Video


