# E-Commerce_Backend
E-Commerce backend using Express.js and Sequilize.

## Description  

Express.js API application that uses Sequilize to interact with a simple e-commerce database.

## Usage  

Application is interacted with via Insomnia (or other API-capable interface).

A schema is provided for creating the database, as well as seed data for each table, and an executable script for seeding the tables with this data.

Routes are available for categories, products, and tags.

Each of these will respond to GET, POST, PUT, and DELETE calls.

Each route has both select all ('/') and select by id ('/:id', example: 'products/1') GET methods.

PUT and DELETE methods also uses id specification.


GitHub Repository can be found here:

https://github.com/creechj/E-Commerce_Backend

Video of usage:  





![Screenshot of Application](./assets/E-Commerce_Database_Screenshot.png)


## Credits

Sequilize include & through inside of API calls:  
https://sequelize.org/docs/v6/advanced-association-concepts/eager-loading/


Sequilize many-to-many realtionship creation:  
https://www.bezkoder.com/sequelize-associate-many-to-many/  

https://sequelize.org/docs/v6/advanced-association-concepts/advanced-many-to-many/#the-best-of-both-worlds-the-super-many-to-many-relationship


## License

Please see license in repository for this application