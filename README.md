# User Account System

This project is a fully integrated platform serving online services for all level of bank users. It focuses on integrating basic functionalities in user’s account systems which consists of Account Overview, Card Management, Money Transfer, Payment History and Bill Pay. The project also aims in enhancing the user’s experience and make it extra interactive by adding some brand-new features such as Asset Statistics Chart and Deposit Checks. 

Demo user (automatically created when you start the app):

Login: email@example.com

Password: admin123

## What's inside?

* Login/register
* Accounts
* Transactions + new transaction
* Credit/debit cards + change PIN/limits
* Internal messages
* User profile incl. data change
* Help form
* Income change chart
* Currency stats
* Form validation, async routing
* Dummy data generator

##  Technologies:

WEB:
* React
* Redux
* React Router
* Webpack
* Sass
* Bootstrap 4
* JWT tokens
* recharts
* react-dates

API:
* Node, Express
* JWT tokens
* Database: MongoDB, Mongoose
* Fixer.io for currency rates

## How to use it?

1. Install [Node.js](https://nodejs.org/) and [MongoDB](https://www.mongodb.com/) ([MongoDB Compass](https://www.mongodb.com/products/compass) may be useful as well, to work on the database)
2. Create database called `react-bank-api` or use any other name, but then update it in the `api/.env` config file
3. Install all dependencies both in `web` and `api` folder by typing `npm install` inside each of them
4. Run API: type `npm run start-dev` in `api` folder
5. Run web: type `npm start` in `web` folder

To create an optimized build, run `npm run build` in `web` folder
