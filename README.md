# E-commerce-back-end

## Description

The purpose of this app is to provide a back-end database for an e-commerce platform. This project was created using database schemas which include tables for products, categories, tags, and product tags. The tables are connected together using primary and foreign keys in order to connect all data together. There are API routes included in order to create, remove, update, and edit information in the tables.

## Table of Contents 

- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [License](#license)
- [Questions](#questions)

## Installation

The user will need to have a functional terminal and the ability to install node.js. They will also need to install MySQL, the MySQL Wokbench, and an open source app to interact with API's such as Insomnia. The user will need to install the following dependencies using the terminal: dotenv, express, mysql2, and sequelize.

## Usage

Once the user has created their repository using GitHub, they will need to clone their repository into their VSCode. After it is done, they will need to create their package.json using "npm init" or "npm init -y" to answer all prompted questions as yes. Then the user will need to install the dependencies dotenv, express, mysql2, and sequelize by using their respective "npm i" commands.

The user will then create their database using the MySQL Wokbench and use their terminal to seed their data by using the command "node seeds/index.js". After, the user will verify that their .env file contains the correct database name, user, and password to run the schema. 

The user is now ready to to start running their server by using the command "node server.js", "nodemon server.js", "npm run start" or "npm run watch". Once the server has started running, the user will switch to their API app such as Insonmia.

In Insomnia, the user will run different endpoints depending on the data they would like to receive back. The following is a list of possible endpoints and their functionality.

•	GET /api/categories - Returns a list of all categories in the database.
•	GET /api/products - Returns a list of all products in the database.
•	GET /api/tags - Returns a list of all tags in the database.
•	GET /api/categories/:id – Returns the category requested by the associated id.
•	GET /api/products/:id – Returns the product requested by the associated id.
•	GET /api/tags/:id – Returns the tag requested by the associated id.
•	POST /api/categories - Creates a new category in the database.
•	POST /api/products - Creates a new product in the database.
•	POST /api/tags - Creates a new tag in the database.
•	PUT /api/categories/:id - Updates an existing category in the database by the associated id.
•	PUT /api/products/:id - Updates an existing product in the database by the associated id.
•	PUT /api/tags/:id - Updates an existing tag in the database by the associated id.
•	DELETE /api/categories/:id - Deletes an existing category from the database with the associated id.
•	DELETE /api/products/:id - Deletes an existing product from the database with the associated id.
•	DELETE /api/tags/:id - Deletes an existing tag from the database with the associated id.

This is a link to a demo video of this application: 

## Credits

As always, huge shoutout to our instructor, Bryan, our TA, Shawn, and my amazing classmates at the UCLA Extended Campus Full Stack Bootcamp.

## License

'[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)'

## Questions

For questions, contact me at brittany.wood0308@yahoo.com.

My GitHub username is Bboughter and here is a link to the repository for this project: https://github.com/Bboughter/E-commerce-back-end