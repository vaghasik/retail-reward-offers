# Retail rewards program

A retailer offers a rewards program to its customers, which is based on points earned for every purchase.

A customer would receive,
  - Two points for every dollar spent over $100 in each transaction
  - One point for every dollar spent over $50 in each transaction 

For example: In $120 purchase, points earned would be calculated as:
 2 x $20 + 1 x $50 = 90 points

Given a record of every transaction during a three month period, calculate the reward points earned for each customer per month and total.

Transaction List component - Gets all the transaction and displays them. This is shown in Transaction List table.

CustomerByMonth component  - Gets the cutomer data and transaction data, then calculates the points earned per customer. CustomerByMonth table shows this view. 
If the user inputs the full month in the input box, for eg: December or december, and hit Enter key, it would display, points earned in December for the customers. Similarly we can try for November and October.

This app was created using create-react-app. 

Before you start the application with 'npm start', please start the backend server using 'json-server ./src/database/db.json'
 
# How to install?

    Fork and clone the repo.
    Run npm install.
    Run npx json-server --watch ./src/database/db.json to start backend
    Run npm start to run the application
    Run npm run test to run test cases.

# Getting Started with Create React App

This project was bootstrapped with Create React App.

# Note:

Here I use json-server allowing us simulate endpoint.
Available Scripts

In the project directory, you can run:
npm start

Runs the app concurrenlty with the json-server in the development mode.
Open as an example: http://localhost:3001 to view it in your browser. The server will run in for eg: (http://localhost:3000)

The page will reload when you make changes.
You may also see any lint errors in the console.
npm test

Launches the test runner in the interactive watch mode.
See the section about running tests for more information.
npm run build

Builds the app for production to the build folder.
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.
Your app is ready to be deployed!

See the section about deployment for more information.
npm run eject

Note: this is a one-way operation. Once you eject, you can't go back!

If you aren't satisfied with the build tool and configuration choices, you can eject at any time. This command will remove the single build dependency from your project.