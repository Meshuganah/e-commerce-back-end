**E-commerce-back-end

*Project Description

A CLI application for maintaining an e-commerce database

*Installation instructions

npm i

Will install the necessary modules, mysql2, sequelize, dotenv, express

*Usage Information

Set up for this application is somewhat involved, so walk through videos will be included below.

Users will need to do the following:
-Create a .env file with the following and fill out with their mysql information
    -DB_NAME='ecommerce_db'
    -DB_USER=''
    -DB_PW=''
-log into mysql using the CLI command mysql -u (username) -p
-run the command to create their database SOURCE db/schema.sql;
-exit mysql
-run the following command in the root directory of the app to seed the database node seeds/index.js
-run the following command to connect to start the server and connect to the database npm start
-navigate to insomnia (or like program) to run their api routes (examples will be in walkthrough video in assets folder)



https://user-images.githubusercontent.com/98676392/169625246-7eb8c5de-166b-4042-a265-d649f90680f4.mp4

