# About this project

This is the codebase of the backend of the dictionary application. It's inherited from the `todos-app-demo-mern-stack` project (only the backend); It is implemented with Node.js and Express.js. The database is MongoDB.

You will need to modify the code to work with the dictionary application. To run the backend, you need to follow the following steps:

1. install all the dependencies by running `npm install`
2. configure your MongoDB database, and copy/paste the connection string into the `.env` file. In other words, you need to replace the `ATLAS_URI` value with your own connection string. When doing so, please make sure that you have replaced the `<username>`, `<password>`, and `<database>` parts with your own.
3. start the backend by runnning `npm start`.