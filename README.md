# E-commerce
Week-12 Challenge

## Table of Contents
*  [Description](#Description)
*  [Links](#Links)
*  [Installation](#Installation)
*  [Usage-Information](#Usage-Information)

##  Description 
This application provides an integrated Postgres database and Sequelize for the efficient management of e-commerce businesses. Sequelize serves as an ORM, enhancing code readability and reusability. Users can interact with the database through API routes, eliminating the need for a user interface. Overcoming challenges with table joins, the application simplifies complex relationships between categories, products, and tags.

## Links

Live Screen Recording of Application Functionality: https://watch.screencastify.com/v/0Luy9EF1oXGaQSNgND7L

## Installation

1. Clone the repo: `git clone git@github.com:Jhona11/`

2. Open in VS Code. If you do not have VS code you must install it.

3. Using the terminal, `npm install node.js`. If you have homebrew, the command should look like the following (brew install node@16), however this may vary and the documentation should be consulted.

4. Once node.js is installed, in the terminal, utilize the command `npm init` to initialize and create a package.json where project files will be stored.

5. Next, use the terminal to run the following commands to install the dependencies associated with this application.

* `npm install pg`
* `npm install sequelize`
* `npm install dotenv`

6. Install PostgreSQL, if it is not already. https://www.postgresql.org/download/

7. In the terminal, navigate to the directory of the project.

8. Enter the PostgreSQL shell, using `psql`, and run the `schema.sql` file (`\i schema.sql`).

9. In the VS Code terminal, run the command `npm run seed` to seed the database with initial data.

10. To run the program, within the terminal, type the command `node server.js`.

11. Once the server is running, the user can use applications such as Insomnia to test the functionality of the routes within the program.

## Usage Information
Usage of this application as of now, can be seen through the running and testing of routes with applications like Insomnia or strictly through using a MySQL shell. Once the database has been created, seeded, and the server spun up (see installation section for instructions on how to get the database set up and the server running), users can interact with the database through routing of different api end points.