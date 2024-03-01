## Fake Stack Overflow (Not Deployed)

This project is designed to be a small scale recreation of the website stack overflow. It uses javascript and a mongo database to replicate functionality and implementation. Please see below for instructions.

## Instructions

Run npm install in both the client and server directory

Make sure the following packages are install in the server directory:
express, express-session, connect-mongo, nodemon, cors, mongoose

Make sure the following packages are installed in the client directory:
axios

Make sure mongo is running as a background service (this project uses MongoDB Community Server which can be installed here https://www.mongodb.com/docs/manual/administration/install-community/). Mongo can be ran in the terminal as mongod which will establish a connection to the database

To create an admin user you can enter the following while in the server directory terminal:
node init.js username password mongodb://127.0.0.1:27017/fake_so
Please note that some artifical users and post will be created with the above command

Then simply run the server in the server directory:
nodemon server.js

and run our client side code in the client directory:
npm start








