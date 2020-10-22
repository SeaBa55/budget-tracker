# Budget Tracker
Michigan State Bootcamp Homework assignment 18: Online/Offline Budget Tracker PWA

## Description

This application uses an express along with mongodb (using mongoose ODM) to create a basic budget tracking expreience. The application allows users to track withdrawals and deposits with or without an active data/internet connection and is availible as a downloadable PWA.  

![Budget-Tracker](./public/assets/images/Budget-Tracker.gif)

## Table of Contents

* [Installation](#installation) 
* [License](#license) 
* [Contributors](#contributing) 
* [Tests](#tests)
* [Revisions](#Revisions)

## Installation

Run the app with heroku using the following link: 
> https://lit-reaches-84077.herokuapp.com/


If running app locally from terminal you will need to run the following commands to get started:
> npm i

> npm start

The app will be rendered to: 
>http://localhost:3000/

## License

![License](https://img.shields.io/badge/License-none-blue.svg)

## Contributing

none

## Tests

none

## Revisions

budget-tracker_v1.0 - Initial commit: Added basic README and .gitignore files.

budget-tracker_v1.1 - Added inital service worker, web manifest and db.js for using indexedDb; Also modified server.js for use env parameters for port and mongoose connection.

budget-tracker_v1.2 - Added web manifest link to index.html; Added offline post request functionallity.

budget-tracker_v1.3 - Changed image sizes to reflect actual image sizes in the web manifest.

budget-tracker_v1.4 - PWA install now working, deploying to heroku.

- - -
© 2019 Trilogy Education Services, a 2U, Inc. brand. All Rights Reserved.