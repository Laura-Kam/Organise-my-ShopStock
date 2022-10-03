# Title of Project: Organise My ShopStock

![License](https://img.shields.io/badge/license-MIT-blue.svg)

## Table of Contents:

- [Username](#username)
- [Project Description](#description)
- [License](#license)
- [Command to install](#command-to-install)
- [Instructions for users](#instructions-for-users-of-the-app)
- [Features of the project](#features-of-the-project)
- [Link to GitHub Repo](#Link-to-Git-hub-repo.)
- [Screenshot of Application](#Screenshot-of-Application)
- [Bugs](#bugs)
- [Version History](#Version-history)
- [Link to video](#Link-to-video)
- [How to contribute](#how-to-contribute)
- [Questions](#questions)

## Username

    Laura-Kam

## Description

The motivation behind this project was to build the back end for an e-commerce site. The app allows the user to view and format their databases in an accessible manner.

AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies

GIVEN a functional Express.js API

- WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
  THEN I am able to connect to a database using Sequelize
- WHEN I enter schema and seed commands
  THEN a development database is created and is seeded with test data
- WHEN I enter the command to invoke the application
  THEN my server is started and the Sequelize models are synced to the MySQL database
- WHEN I open API GET routes in Insomnia Core for categories, products, or tags
  THEN the data for each of these routes is displayed in a formatted JSON
- WHEN I test API POST, PUT, and DELETE routes in Insomnia Core
  THEN I am able to successfully create, update, and delete data in my database

## License

MIT

## Command to install

npm i.

## Instructions for users of the app

Clone the application, install dependencies: Inquirer, MySQL2, Dotenv, Sequelize,Express and UUID. Run the schema and then seeds.sql files. Seeding can be done through 'npm run seed' Then run the app using node server.js using 'npm start'.

## Features of the project

It is a command-line application, it creates, updates and deletes database records through command line inputs using MYSQL and Sequelize.

## Link to Git-hub repo.

[Link to repo](https://github.com/Laura-Kam/Organise-my-ShopStock)

## Screenshot of application:

[Screenshot of website](https://github.com/Laura-Kam/Organise-my-ShopStock/issues/1#issue-1393870325)

## Bugs

- Delete function would not work on categories. Resolved by re-seeding data.
- Connection failed to work. Resolved.
- Router.post for product-route failed to update, issue resolved by including a category_id property in the payload.

## Version history

- 0.1 .env file configured, dependencies installed.
- 0.2 Created connection and finished models.
- 0.3 Completed routes with express
- 0.4 Created delete routes.

# Link to video

- [Organise-my-ShopStock Video Google Drive](https://drive.google.com/file/d/1_rwMTO6LAPSpBq4diffA0-2MI05qjncW/view)

- [Organise-my-ShopStock Screencastify](https://watch.screencastify.com/v/OA1SjIsSOTd4Mn7v8I2b)

## How to contribute

Git clone the repo, work on the code, then make a pull request.

## Questions

If you have any questions, or would like to get in touch find me on GitHub [Laura-Kam](https://github.com/Laura-Kam)
or email me at laura_ek@yahoo.co.uk.
