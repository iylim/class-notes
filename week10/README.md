# Week 10

## Monday

### Authenticaton

#### Backend

installs

1. bcrypt
2. [jsonwebtoken](https://www.npmjs.com/package/jsonwebtoken)
3. [passport](http://www.passportjs.org/)
4. [passport-jwt](https://github.com/themikenicholson/passport-jwt)

Process 1: Registration

Required Parameters: Username, Email, Password, Password2

1. Check the database for an existing user by Email and Username.
   1. If there is not a user already, move on.
   2. If there is a user already, return an error.
2. Compare the password fields.
   1. If they match, move on.
   2. If they don't, return an error
3. Salt and Hash the password in a `pre` save hook
4. Save User to Database.
5. Return success to the client.

Process 2: Authentication

Required parameters: Username, Password.

1. Grab User from Database.
2. Salt/Hash Entered password from User
3. Compare Entered vs. Stored passwords.
   3.1 if password hashes match, generate a token and send to the user
   3.2 if password hashes don't match, return an error.

Protecting routes

1. setup passport config with strategy

#### **Uh oh**

Password is exposed in JWT. My bad.

Here's how we can hide it

```js
const userObj = user.toObject();
delete userObj.password;
```

#### Making this fullstack

1. [concurrently](https://www.npmjs.com/package/concurrently) run sever and client

add to the scripts of your server's `package.json`

```
"dev": "concurrently \"npm run server\" \"npm run client\" --names \"server,client\" ",
"server": "nodemon index.js",
"client": "cd client && npm start"
```

2. proxy server address

add to your client's `package.json`

```
"proxy": "http://localhost:<PORT>/"
```

where PORT is the port you set in your env file.

3. Change API calls to be relative

#### Frontend

Let's clean up the code and make sure everything is working with our new API

1. `CommentList`: change `id` to `_id`

I also want to change something about our backend because I made a stupid mistake

Now we're ready to get into it

1. install react router
2. copy code for login and singup forms
3. add buttons to app
4. drop in my css (`nav.css`, `LoginForm.css`)
5. Login
   1. `POST` to `/api/auth/login`
   2. set token in local storage
6. Add headers to create comment
7. Auth Service:
   1. isLoggedIn
   2. isExpired
8. **BONUS** App nav: conditionally show login button

### Resources

- [JSON Web Tokens](https://jwt.io/)
- [Using JSON Web Token for Authentication](https://hptechblogs.com/using-json-web-token-for-authentication/)
- [JSON Web Token Authentication in React and react-router](https://hptechblogs.com/using-json-web-token-react/)
- [NodeJS Authentication with Password and JWT in Express](https://medium.com/@therealchrisrutherford/nodejs-authentication-with-passport-and-jwt-in-express-3820e256054f)
- [Token Based Authentication with Node.js, Express, Mongoose and Passport](https://techbrij.com/token-authentication-nodejs-express-mongo-passport)
- [Adding Salt to Hashing: A Better Way to Store Passwords](https://auth0.com/blog/adding-salt-to-hashing-a-better-way-to-store-passwords/)
- [How to Implement Authentication For Your React App](https://medium.appbase.io/how-to-implement-authentication-for-your-react-app-cf09eef3bb0b)
- [React + Redux - JWT Authentication Tutorial & Example](http://jasonwatmore.com/post/2017/12/07/react-redux-jwt-authentication-tutorial-example)
