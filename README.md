# Unit 18 PWA Homework: Online/Offline Budget Trackers

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Description

Project 18 tasked the student with modifying a budgeting application that has a built out front end and partial express server, and adding Progressive Web Application abilities to allow the application to be downloaded by a mobile device. In addition to the PWA add on, the app needs to function while in airplane mode or in an offline status to where the new updates are pushed to the database once the app comes back online. This was achieved by adding IndexedDB support to the application where the PWA will store this inforamtion in the IndexedDB area on the browser/PWA interface and then push this inforamtion to the connected Mongo Database once the app comes back online. 

As this project had a few broken componets, there was some updating that needed to happen to the existing files including modifying the server file, updating the icon files to ensure they were the correct width and height (updates done in photoshop) as well as adding the missing files to allow the PWA to be downloaded to the mobile device including the manifest and service worker files. In addition to this, an indexedDB file was also added to allow the storing of data while offline to the browser's indexedDB area. 

## Table of Contents

-   [Deployed](#deployed)
-   [Installation](#installation)
-   [Usage](#usage)
-   [Credits](#credits)
-   [License](#license)
-   [Contributing](#contributing)
-   [Questions](#questions)

## Deployed

You can access the delployed version of this application via the URL: [https://damp-depths-86491.herokuapp.com/](https://damp-depths-86491.herokuapp.com/)

## Installation

To install this application, first, branch the Github Repo and clone the repo to your local machine. Then, you will need to install the node dependencies which can be done by running the npm install command in your terminal/bash shell.

After the dependencies have been installed, you can run the app by running NPM Start or Node Server.js. 

## Usage

Once everything has been set up, the application can be launched by running the command node server.js or npm start. You will then need to visit the local host URL for the port that you have set up
for this application. If you are running this via a local machine, you will need to ensure MongoDB is running to support the database connection to this application. If you are using the delployed link in the deployed secion of this README, then you will not need to run MongoDB in the background as this application is already set up with a hosted MongoDB instance. You can pull up the deployed application on your mobile device and download it to the homescreen to use it as a PWA. To test the offline functionality, you can set your device to airplane mode and add new budget items to the app. Once the app comes back online, it will log the changes to the database.  

## Credits

This application was completed by Jeff Quittman as a project for UCLA/Trilogy's Full Stack Software Development Bootcamp.

Dependencies for this project include the node modules:

-Express: for setting up the node server

-Mongoose for setting up the models for MongoDB

-Morgan for adding the http request logger

-NPM Compression to compress the files for better loading and running abilities

## License

    								MIT License

    		Unit 13 Express-Handlebars: Eat-Da-Burger!   Copyright (C) 2020 Jeffrey Quittman

    		Permission is hereby granted, free of charge, to any person obtaining a copy
    		of this software and associated documentation files (the "Software"), to deal
    		in the Software without restriction, including without limitation the rights
    		to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
    		copies of the Software, and to permit persons to whom the Software is
    		furnished to do so, subject to the following conditions:

    		The above copyright notice and this permission notice shall be included in all
    		copies or substantial portions of the Software.

    		THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
    		IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
    		FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
    		AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
    		LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
    		OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
    		SOFTWARE.

## Contributing

If you would like to contribute to this application, please feel free to email me via the email found in the questions section and we can discuss how to collaborate and enhance this application


## Questions

-   For any questions related to this applicaiton, please contact me at: JeffQuittman@gmail.com.

-   Please use this link to access my Github Profile: [https://github.com/JeffQuit](https://github.com/JeffQuit)
