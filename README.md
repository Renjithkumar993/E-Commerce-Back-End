# E-COMMERCE BACK-END


Welcome to the E-Commerce Back End application! This application provides a back end for an e-commerce website that can compete with other e-commerce companies. It is built using the latest technologies, including Express.js, Sequelize, and MySQL.

## Installation
To install the application, follow these steps:

* Clone the repository to your local machine.
* Run npm install to install the necessary dependencies.
* Create a .env file and add your MySQL database name, username, and password in the following format:

* DB_NAME='your_database_name'
* DB_USER='your_database_username'
* DB_PW='your_database_password'

Open MySQL shell and run source db/schema.sql to create the database.
Seed the database with test data by running npm run seed.
Start the application by running npm start.
## Usage
Once the application is running, you can use Insomnia or a similar API testing tool to test the API routes. The following API routes are available:

* /api/categories: GET all categories, POST a new category
* /api/categories/:id: GET a single category by id, PUT update a category by id, DELETE a category by id
* /api/products: GET all products, POST a new product
* /api/products/:id: GET a single product by id, PUT update a product by id, DELETE a product by id
* /api/tags: GET all tags, POST a new tag
* /api/tags/:id: GET a single tag by id, PUT update a tag by id, DELETE a tag by id
To test the API routes, use the appropriate HTTP method (GET, POST, PUT, or DELETE) and URL for the desired route. For example, to get all categories, use a GET request to http://localhost:3001/api/categories.

## Walkthrough Video
To see the application in action and ensure that all acceptance criteria are met, please watch the following walkthrough video: 

![](./assets/Untitled_%20Apr%2016%2C%202023%204_18%20PM.gif)
![](./assets/Untitled_%20Apr%2016%2C%202023%204_32%20PM.gif)
![](./assets/Untitled_%20Apr%2016%2C%202023%205_01%20PM.gif)


## Credits
This application was built using the following technologies:

* Express.js
* Sequelize
* MySQL
* dotenv
* nodemon
* MySQL2
## License
This application is licensed under the MIT license.
