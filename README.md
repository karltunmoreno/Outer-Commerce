
USER STORY:
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies

Criteria
GIVEN a functional Express.js API

WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia
THEN I am able to successfully create, update, and delete data in my database
What was done
Created app in Java script using express and mysql2 to build the backend for the frontend engineer to complete the full site. future development will include a swagger UI for quick REST api access.(See swagger branch for progress)

App build in:

JavaScript

Node.js 

Express.js

MySQL

Instalation
Clone starter code.
Install NODEjs.
Use NPM to install dependencies: "dotenv": "^16.0.0", "express": "^4.17.3", "mysql2": "^2.3.3", "sequelize": "^6.17.0
