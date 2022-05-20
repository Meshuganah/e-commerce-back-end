**E-commerce-back-end

*Project Description

A CLI application for maintaining an e-commerce database

*Installation instructions

npm i

Will install the necessary modules, mysql2, sequelize, dotenv, express

*Usage Information

Set up for this application is somewhat involved, so walk through videos will be included below.

Users will need to do the following:
-log into mysql using the CLI command mysql -u (username) -p
-run the command to create their database SOURCE db/schema.sql;
-exit mysql
-run the following command in the root directory of the app to seed the database node seeds/index.js
-run the following command to connect to start the server and connect to the database npm start
-navigate to insomnia (or like program) to run their api routes (examples will be in the walkthrough videos)