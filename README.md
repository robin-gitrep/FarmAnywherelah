# FarmAnywherelah!

It is a school project made by SGUS B11 Group 2 **National University of Singapore**'s [FintechSG Programme](https://fintechlab.nus.edu.sg/nus-fintechsg-programme/).

DISCLAIMER: The enclosed document is the outcome of a student project, and does not necessarily represent the views of **National University of Singapore** in or any other individuals referenced or acknowledged within the project. The project is solely for educational purposes. 

This project app is developed with the following components **Front End: HTML-CSS-Javascript Middleware: Node.js Backend(DB): MySQL**.

This repository consists of the following folders:
```
/frontend         HTML, CSS, Javascript code for the frontend client
/backend          The Java script codes for the middle ware codes to import Node JS components 
                  Express is a perfect choice for a server when it comes to creating and exposing APIs
                  Body-Parser for parsing the incoming request bodies in a middleware before you handle it
                  CORS mechanism to allow or restrict requested resources on a web server depend on where the HTTP request was initiated.
                  Express Router to create a new router object in your program to handle requests.
/database_sample  Sample data to load into your MySQL database

Node.js:          Used Node.JS, the back-end JavaScript runtime environment to execute JavaScript code outside a web browser.
```

## Steps to Install in your local machine and demonstrate the Application

### To clone the file in your local directory
* Open windows command prompt, select the folder you want to clone and run the below command
1. git clone https://github.com/robin-gitrep/Farmanywherelah-.git
* To install msql and node.js application
1. Install Visual Studio Code
1. Install MYSQL Extensions in VSC
1. Ask the Administrator for the updated .env file with database connectiong string
* To Initialize Node JS
1. From VSC, Run the Integrated Terminal
1. Run the below commands one by one to Initialize Node JS and Install mysql, express and body-parser
1. `npm init`
1. `npm install --save mysql express body-parser cors dotenv`
1. `npm install --save mysql express body-parser cors dotenv` 
* To create database and table schema
1. Run the scripts in [Create DB Schema](https://github.com/robin-gitrep/Wiki/blob/main/SQL_DB_Scripts.sql)
* To launch node js middleware and connect to database, run the command
`node main.js`
* To launch the Farmanywherelah gaming app. Click on [Farmanywherelah](http://localhost:3000/index.html)

