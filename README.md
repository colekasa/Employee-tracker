## Employee Tracker

This command-line application allows you to manage employees in a company. The application is built with Node.js and uses MySQL to store and retrieve data.

# Installation

To use this application, you will need Node.js and MySQL installed on your machine. Follow these steps to install the application:

Clone this repository to your local machine

Install the required dependencies by running the following command in your terminal:

npm install

Set up the database by running the following command in your terminal:

mysql -u root -p < db/schema.sql

If you wish to seed the database with sample data, run the following command:

npm run seed

# Usage

To use the application, run the following command in your terminal:

npm start

This will launch the application and display a menu with the following options:

View All Employees
View All Roles
View All Departments
Add Employee
Add Role
Add Department

Select the desired option from the menu by typing the corresponding number and pressing enter. Follow the prompts to enter the required information.

# Contributing

If you would like to contribute to this project, please submit a pull request with your proposed changes.

# License

This project is licensed under the MIT License.
