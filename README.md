# 13-ecomerce-backend

## Description

13-ecomerce-backend is the backend for an e-commerce or internet retail site. The task was to take a working Express.js API and
configure it to use Sequalize to interact with a MySQL database.  

AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies

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


## Built With

* JavaScript
* Express
* MySQL
* Sequelize

## Usage

Open two terminal windows and navigate to the Develop directory
In one windw, run <npm run seed> then <mysql -u root>. From here, you can view the ecommerce_db databse and its tables.
In the second window start the server by running <node server.js>
Use Insomnia to test the API GET, POST, PUT, and DELETE routes for category, tag, and product

See link to a walkthorugh video: https://drive.google.com/file/d/1dTi2H7WLafjLWrJB_GZQe-BqH5x7DX87/view

## Contributing
Made with &hearts; by Lara DeStein