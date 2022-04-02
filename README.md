# PWA Budget Tracker

![License Badge](https://img.shields.io/github/license/mmeii/progressive-budget-tracker) ![Top Language](https://img.shields.io/github/languages/top/mmeii/progressive-budget-tracker)

A Budget Tracker application that allows users to add expenses and deposits to their budget with or without a connection. When entering transactions offline, they should populate the total when brought back online.

## Table of Contents

* [Installation](#installation)
* [Usage](#usage)
* [Links](#Links)
* [Features](#Features)
* [License](#License)

## Installation

1. Download or clone repository
2. `npm install` to install the required npm packages to run

## Usage

* Application will be invoked by using the following command:

  `node server.js`

* Open your browser and go to
  
  `http://localhost:3000`

* User can add transactions as deposits or expenses by inputting the following:
  * Name of transaction
  * Transaction amount
  * For deposits - select **Add Funds**
  * For expenses - select **Subtract Funds**

* The total amount is reflected as soon as funds are entered

* The graph portrays the total funds over time by date entered for each transaction

  ![PWA Budget Tracker Screenshot](https://github.com/mflanigan13/pwa-budget-tracker/blob/main/public/images/budget-tracker.png)

* The app can be used online and offline

* Offline Functionality:
  * Enter deposits offline
  * Enter expenses offline

* When brought back online:
  * Offline entries should be added to tracker

## Links

* [Github](https://github.com/mflanigan13/pwa-budget-tracker)
* [Live Heroku App](https://pwa-budget-tracker-13.herokuapp.com/)

## Features

* Node
* Express
* JavaScript
* MongoDB
* Mongoose
* Progressive Web Application

## License
  
  Licensed under the [MIT](LICENSE) license.
  
