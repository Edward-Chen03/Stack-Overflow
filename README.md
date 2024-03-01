## Fake Stack Overflow (Not Deployed)

This project is designed to be a small scale recreation of the website stack overflow. It uses javascript and a mongo database to replicate functionality and implementation. Please see below for instructions.

## Features

- Postings and Discussion Board: Incorporates a comprehensive postings and discussion board feature, empowering users to create, share, and engage in discussions around various topics. This functionality facilitates the creation of posts by users, enabling them to express their thoughts, share insights, and initiate discussions. Furthermore, it provides a platform for users to interact, exchange ideas, and foster a vibrant community within the application.

- Tags for Organization and Search: Implements a robust tagging system that allows users to categorize and organize their creations effectively. By enabling users to assign relevant tags to their posts, the system enhances discoverability and facilitates streamlined searching and sorting functionalities. This feature empowers users to easily locate and access content based on specific topics or themes, enriching the overall user experience and promoting content engagement.

- Comments and Voting Mechanisms: Facilitates interactive user engagement through commenting and voting functionalities. Users have the ability to express their opinions by upvoting or downvoting posts, thereby influencing their visibility and prominence within the community. Additionally, the availability of comments fosters in-depth discussions and facilitates dialogue among users, promoting active participation and community engagement. These features collectively contribute to a dynamic and interactive user experience, enriching the overall platform's functionality and fostering a sense of community engagement and collaboration.


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

## Project Specifications
- Employs MongoDB, a NoSQL database, for robust and flexible data storage. This structure allows seamless handling and organization of complex objects within the application, facilitating efficient data retrieval and manipulation.
- Utilizes JavaScript and Node.js to develop a dynamic and scalable application. Node.js enables server-side execution of JavaScript, ensuring consistent performance and streamlined development. Axios is employed for frontend interactions, providing a reliable means of making HTTP requests, while Express, a minimalist web framework for Node.js, powers the backend, enabling rapid development of RESTful APIs and handling of routing and middleware.
- Implements bcrypt encryption library to fortify the security of user information. By employing robust cryptographic hashing techniques, sensitive user data such as passwords are securely encrypted before storage, mitigating the risk of unauthorized access or data breaches. This enhances the overall security posture of the application, instilling confidence in users regarding the protection of their personal information.






