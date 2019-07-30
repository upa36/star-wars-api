# Star Wars API

## Instructions

In the initial commit of this project you have been provided with an express server that has three routes associated with the rebels model.

* The GET `/rebels` route will return a list of all rebels stored in the database.
* The GET `/rebels/:identifier` route will return a single rebel based on the identifier provided. The identifier can be either a numeric ID or a callSign
* The POST `/rebels` route will create a new rebel in the database

Currently only the first route is working correctly. Your task is to configure the project to work with the VS Code Node debugger and then use the debugger to identify and fix these issues with the other two routes.

## Project Setup

* Start by creating a new branch that you'll make all of your changes in
* In your MySQL workbench, create a database into which this project will create data `CREATE DATABASE starwars`
* Make a copy of the `.env-sample` file called `.env` and update all the values for your system
* Start the server using `npm run dev` to have the migrations run and server start up

## Provided Files

**config/sequelize.js** - this file contains the configuration data needed to connect to the database

**migrations/20190729192018-initial-table-creation.js** - this file contains a migration that will set up the table structure in your database that is required for runnning this project

**migrations/20190729192029-initial-data-load.js** - this file contains a migration that will add some initial test data to your database

**models/index.js** - this file contains code to connect to the database and wire your models to your tables

**models/rebels.js** - this file contains the model of the rebels table

**.env-sample** - this file is a sample of the `.env` file you will need to run this project.

**.eslintrc.js** - a config file for ES Lint

**.gitignore** - this file sets the project up to ignore the node_modules folder when committing to git

**index.js** - this file contains the code for setting up the express server

**package.json** - this file sets up the Node project including all the dev dependencies

**package-lock.json** - this file is created and maintained by NPM when installing dependencies

## Exercise Submission

You should submit your working changes in a pull request and request review by your instructor.
