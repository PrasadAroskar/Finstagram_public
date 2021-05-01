# Finsta-Public-Document

**NOTE**

Main project code repository is private.

## Demo:
please visit: https://youtu.be/05OW8wQAZ3Y

## Report:
please check Finsta-Report.pdf

### Overview -
This webapp is social networking platform to connect and share the photos and messages with your friends and family.

### Features -
1. Google and Facebook OAuth
2. Uploading multiple photos and creating posts
3. Adding comments and likes on posts
4. Searching friends
5. Managing friend requests (Add friend, remove friend, accept friends)
6. Private Profiles
7. Viewing wall
8. Send messages to friends 

### Technologies -
1. Backend - NodeJS, Express, Mongoose
2. Frontend - React with Redux, SCSS, JavaScript
3. Database - MongoDB
4. Other Libraries -  Socket, BodyParser, Multer, NodeMon, Passport, cors, cookie-parser, react-bootstrap, redux-thunk, react-router-dom, react-scripts, react-select, redux, nodes-sass

## Installation
1. Clone the repository `git@github.com:neu-mis-info6150-fall-2020/final-project-mindmap.git`.
2. Navigate to project directory `cd final-project-mindmap.git`.
3. Run `npm init`.
4. Run `npm install`.

## Database Installation

Use MongoDB Atlas it is the global cloud database service for modern applications or install MongoDB on respective OS
For Ubutu - 
https://docs.mongodb.com/manual/tutorial/install-mongodb-on-ubuntu/

For Windows - 
https://docs.mongodb.com/manual/tutorial/install-mongodb-on-windows/

For MAC OS -
https://docs.mongodb.com/manual/tutorial/install-mongodb-on-os-x/


### Setup Server
1. Navigate to project directory `cd final-project-mindmap.git/server`.
2. Run `npm install`.
3. Create file `config` folder and create file `keys.js` for the OAuth.
4. Run `npm run dev`
5. Server will get started on port 4000

### Setup webapp
1. Navigate to project directory `cd final-project-mindmap.git/webapp`.
2. Run `npm install`.
4. Run `npm start`
5. Application  will get started on port 3000
