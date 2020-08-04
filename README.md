# Node-Js-Authentication
Node Js authentication using express and passport module with bcrypt password-hashing function.
### passport-local
[Passport](http://www.passportjs.org/) strategy for authenticating with a username and password.
This module lets you authenticate using a username and password in your Node.js applications. By plugging into Passport, local authentication can be easily
and unobtrusively integrated into any application or framework that supports Connect-style middleware, including Express.
### Bcrypt
[Bcrypt](https://www.npmjs.com/package/bcrypt-nodejs) is a password hashing function. By using this bcrypt module, you can store your password safely.
### Express-session
 [Express. js](http://expressjs.com/) uses a cookie to store a session id (with an encryption signature) in the user's browser and then,
 on subsequent requests, uses the value of that cookie to retrieve session information stored on the server.
# Install
These are the modules need to be installed before using this project.
```
$ npm install express
$ npm install express-session
$ npm install passport
$ npm install passport-local
$ npm install bcrypt
```
