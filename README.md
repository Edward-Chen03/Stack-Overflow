## Fake Stack Overflow (Not Deployed)

This project is designed to be a small scale recreation of the website stack overflow. It uses javascript and a mongo database to replicate functionality and implementation. Please see below for instructions.

## Instructions to setup and run project

Run npm install in both the client and server directory

Make sure to install the following packages using npm install in the server directory:


express


express-session


connect-mongo


nodemon


cors


mongoose



 Run npm install axios in the client directory.

Make sure mongosh is running as a background service (this project uses MongoDB Community Server which can be installed here https://www.mongodb.com/docs/manual/administration/install-community/):
run mongod in a separate terminal and then run mongosh in another separate terminal and open mongoDBCompass GUI

To run our project, first make sure to create a fake_so database in the mongo compass (delete the automatic fake_so folder and create a new with fake_so in both fields). Then run our server/init.js file in a server directory terminal to populate the database. The first two arguments will the username and password for an admin user. The third argument will be adress to the mongodb. (node init.js username password (mongoDbAddress)) The email to login to this admin account will be 'admin@gmail.com' Then you can run nodemon server.js in your server directory terminal and then npm start in your separate client directory terminal.






