# for-lock-down

## How To Use 🔧

Download node_modules
```
npm install
```
Create .env file
```
touch .env
```
In your .env file add the following and replace specified values.  
Note: Things that need to be replaced are [site secret, user, password, cluster, dbname]
```
PORT=2000
SECRET= #Your site secret here
DATABASE_URI='mongodb+srv://<user>:<password>@<cluster>/<dbname>.mongodb.net/test?retryWrites=true'
```
Launch the app in developement with live server reloads.
App will run on port 2000
```
npm run dev
```

---

## Technologies used 🛠️

- [Node.js](https://nodejs.org/en/) - JavaScript Runtime
- [MongoDB](https://www.mongodb.com/) - Database
- [Mongoose](https://mongoosejs.com/) - Makes Mongo DB easier to work with
- [EJS](https://ejs.co/) - Templates with JavaScript
- [bcryptjs](https://www.npmjs.com/package/bcryptjs) - Used to hash passwords
- [Passport](http://www.passportjs.org/) - Authenticating Users