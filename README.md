﻿# for-lock-down
This project was created by the Whetstone Instructors, as a basic demonstration of how to
build a full stack application with the use of ejs. This was paired with a google doc that explained how to build the site step by step, so that it could be printed and studied during the lockdown for COVID-19. The directions are included as pdf files in the instruction folder.

## How To Use 🔧
To install and start the application:

First Download the node_modules
```
npm install
```
Then create your .env file
```
touch .env
```
In your .env file add the following and replace specified values.  
Note: Things that need to be replaced are [site secret, user, password, cluster, dbname]  
```
PORT=3000
SECRET= #Your site secret here
MONGODB_URI='mongodb+srv://<user>:<password>@<cluster>/<dbname>.mongodb.net/test?retryWrites=true'
```
Note: To connect to a local database on your computer set MONGODB_URI to:
```
MONGODB_URI=mongodb://localhost/full-stack-cat
```

Launch the app in developement with live server reloads.
App will run on port 3000
```
npm run dev
```

---

## Technologies used 🛠️

- [Node.js](https://nodejs.org/en/) - JavaScript Runtime
- [Express](https://expressjs.com/) - Server middleware / web framework for node.js
- [MongoDB](https://www.mongodb.com/) - Database
- [Mongoose](https://mongoosejs.com/) - Makes Mongo DB easier to work with
- [EJS](https://ejs.co/) - Templates with JavaScript
- [bcryptjs](https://www.npmjs.com/package/bcryptjs) - Used to hash passwords
- [Passport](http://www.passportjs.org/) - Authenticating Users
- [Axios](https://github.com/axios/axios) - Used to access routes from JavaScript
