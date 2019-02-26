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

## Resources
