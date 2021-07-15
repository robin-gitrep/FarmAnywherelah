# FarmAnywherelah!

# Release Notes:

## Steps to Deploy the source, configure, test and demonstrate the Application from any windows local machine

### To clone the files in your local directory
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
1. Run the scripts in [MSSQL](https://github.com/robin-gitrep/Wiki/blob/main/SQL_DB_Scripts.sql)
* To launch node js middleware and connect to database, run the command
`node main.js` from VSC Integrated terminal
* To launch the Farmanywherelah gaming app. Click on [Farmanywherelah](http://localhost:3000/index.html)

