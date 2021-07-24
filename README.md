<h1>Budget Trackers App</h1>

<h2> Table of Contents </h2>

- [Project Link](#project-link)
- [Getting started](#getting-started)
- [Set up the database](#set-up-the-database)
- [Description](#description)
- [What did we do?](#what-did-we-do)
- [Running the project](#running-the-project)
- [Screenshots](#screenshots)

## Project Link

Click [here](https://whispering-crag-95188.herokuapp.com/) to view the project on Heroku.

## Getting started

    $ git clone https://github.com/otivisan22/budget-trackers/app
    $ cd budget-tracker
    $ npm i

## Set up the database

In Robot 3T Workbench

```
DROP DATABASE IF EXISTS workout;

CREATE DATABASE workout;
```

## Description

Our task was to add functionality to our existing Budget Tracker application to allow for offline access and functionality.
So and AN avid traveller I WANT to be able to track my withdrawals and deposits with or without a data/internet connection
SO THAT my account balance is accurate when I am traveling.

Don't forget to code for fun :rocket: !

## What did we do?

- npm init
- npm i express
- npm i mongoose
- npm i morgan
- npm i nodemon -D
- npm i lite-server

## Running the project

```
$ npm run seed

$ npm run dev
```

## Screenshots

![screenshots1](src/models/public/icons/images/image1.PNG)
![screenshots2](src/public/images/image2.png/)
![screenshots3](src/public/images/image3.png/)
