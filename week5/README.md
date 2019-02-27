# Week 5: Backend

* [Monday](#monday)
  * [Asynchronous JavaScript](#asynchronous-javascript)
    * [Resources](#resources)
  * [Node](#node)
    * [Text File Database](#text-file-database)
    * [Simple Server (static files + API)](#simple-server-static-files--api)
* [Resources](#resources-1)
* [Tuesday](#tuesday)
  * [Node](#node-1)
* [Wednesday: Express API](#wednesday-express-api)
  * [What is Express?](#what-is-express)
  * [What is a RESTful API?](#what-is-a-restful-api)
  * [HTTP Verbs and CRUD 💩](#http-verbs-and-crud-)
  * [HTTP Status Codes](#http-status-codes)
* [Resources](#resources-2)

## Monday

### Asynchronous JavaScript

![Threading vs Asychronisity](https://eloquentjavascript.net/img/control-io.svg)

![Asynchronous stack w/ queue and event loop](https://cdn-images-1.medium.com/max/600/1*9iOmFwC3PWUD8RFLsxzBXQ.jpeg)

![Promise graph](https://cdn-images-1.medium.com/max/1600/1*5Oj4qxp6BaWyAgZzLbddxQ.png)

#### Resources

- [MDN: Promise](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise)
- [MDN: Using Promises](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Using_promises#Creating_a_Promise_around_an_old_callback_API)
- [Async functions - making promises friendly](https://developers.google.com/web/fundamentals/primers/async-functions)
- [Master the JavaScript Interview: What is a Promise?](https://medium.com/javascript-scene/master-the-javascript-interview-what-is-a-promise-27fc71e77261)
- [Async JS Crash Course - Callbacks, Promises, Async Await](https://www.youtube.com/watch?v=PoRJizFvM7s)

### Node

- `npm` & `package.json`
  - `npm init`
  - `npm install uuid`
  - `npm install --save-dev nodemon`
- import/exports in Node
  - `module.exports =`
  - `const name = require()`
  - module wrapper function
- [Path API](https://nodejs.org/dist/latest-v11.x/docs/api/path.html)
  - `__filename`: full path
  - `__dirname`: directory path
  - `path.extname()`: extension name
  - `path.parse()`: create path object
  - `path.join()`: concatenate path
- [File System API](https://nodejs.org/api/fs.html)
  - `fs.mkdir()`: create folder
  - `fs.writeFile()`: create file (if it doesn't exist) & write to it
  - `fs.appendFile()`: append to file
  - `fs.readFile()`: append to file

#### Text File Database

1. Test if db file exists. If not, create it and seed with data
2. Create function to add to db:
   1. Read text content from file
   2. Parse data from text
   3. Create comment and append to data
   4. Convert back to text
   5. Write it to file

#### Simple Server (static files + API)

## Resources

- [Eloquent JavaScript: Node.js](https://eloquentjavascript.net/20_node.html)

## Tuesday

### Node

What can you build with Node?

- [Chip8](https://github.com/taniarascia/chip8): emulator for computer from the 70's

## Wednesday: Express API

### What is [Express](https://expressjs.com/)?

Fast, unopinionated, minimalist web framework for Node.js. It is a **backend** framework. It is by far the most popular Node framework.

- Makes building apps with Node _much_ easier
- Can be used for both server-rendered apps & APIs/microservices
- Light, fast, free

### What is a RESTful API?

REST: **Re**presentational **S**tate **T**ransfer

> Architectural style for providing standards between computer systems on the web, making it easier for systems to communicate with each other.

Consists of

- Resources (comments)
- Representations (JSON)
- Actions (HTTP verbs)

API: **A**pplication **P**rogramming **I**nterface

> Allows applications to talk to eachother and share data

### HTTP Verbs and CRUD 💩

| HTTP verb | CRUD   |
| --------- | ------ |
| POST      | Create |
| GET       | Read   |
| PUT       | Update |
| DELETE    | Delete |

### HTTP Status Codes

| Code                       | Meaning                                                                                            |
| -------------------------- | -------------------------------------------------------------------------------------------------- |
| **Successful responses**   |                                                                                                    |
| 200 Ok                     | The request has succeeded                                                                          |
| 201 Created                | The request has succeeded and a new resource has been created. Sent after a succesful POST request |
| **Client error responses** |                                                                                                    |
| 400 Bad Request            | Server could not understand the request due to invalid syntax                                      |
| 403 Forbidden              | Client does not have permission to access the resource                                             |
| 404 Not found              | The resource cannot be found                                                                       |
| **Server error responses** |                                                                                                    |
| 500 Internal Server Error  | Something went wrong on the server                                                                 |


## Resources

* API
  * [API design is UI design — a way to collaborative handoff](https://uxdesign.cc/api-design-is-ui-design-a-way-to-collaborative-handoff-3d31ff57bb1)
  * [How to design a RESTful API architecture from a human-language spec](https://www.oreilly.com/learning/how-to-design-a-restful-api-architecture-from-a-human-language-spec)
  * [API Design](https://docs.microsoft.com/en-us/azure/architecture/best-practices/api-design)
  * [MDN Docs: HTTP response status codes](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status)
  * [REST API Tutorial](https://www.restapitutorial.com/)
    * [Using HTTP Methods for RESTful Services](https://www.restapitutorial.com/lessons/httpmethods.html)
  * [What is REST?](https://www.codecademy.com/articles/what-is-rest)