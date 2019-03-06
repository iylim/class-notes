# Week 6: React!

## Monday

### Consuming APIs

[Fetch](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API): Vanilla JS API for making and consuming HTTP requests

In order to make requests to our server we will also need to enable [CORS](https://developer.mozilla.org/en-US/docs/Web/HTTP/CORS). We can use the [`cors` npm package](https://www.npmjs.com/package/cors).

[Code-along finished code](https://github.com/talent-path-la/message-board/tree/fetch)

## Tuesday

### React!

![React logo](https://upload.wikimedia.org/wikipedia/commons/thumb/a/a7/React-icon.svg/2000px-React-icon.svg.png)

JavaScript UI library built by Facebook.

> React is a declarative, efficient, and flexible JavaScript library for building user interfaces. It lets you compose complex UIs from small and isolated pieces of code called “components”.

Most often used for Single-Page Applications (SPA).

Sites built with React

- Facebook
- Instagram
- AirBnB

### Tooling

- [React Dev Tools](https://chrome.google.com/webstore/detail/react-developer-tools/fmkadmapgofadopljbjfkapdkoienihi?hl=en)
- [Create React App](https://facebook.github.io/create-react-app/)
- [React snippets](https://marketplace.visualstudio.com/items?itemName=dsznajder.es7-react-js-snippets)

### Building our first app

1. `npx create-react-app my-app`
2. `npm start`

That's it!

So what is happening under the hood?

**[Webpack](https://webpack.js.org/):** module bundler

- Compiles all of our JS into a single file
- Allows us to use cutting-edge JS while still be compatible with (most) browsers

### Important Terms

- state
- props
- data down (lifting state up)
- immutability
- [use callback in setState when referencing previous state](https://github.com/yannickcr/eslint-plugin-react/blob/master/docs/rules/no-access-state-in-setstate.md)

### Message Board in React

1. `npx create-react-app client`
2. lets look at all the things in App
3. delete everything in `src`
4. copy over css from old project
5. create `index.js`
   1. import React and ReactDOM
   2. create a MessageBoard class
   3. render it on page
6. Lets move MessageBoard to its own file
7. Create a file for CommentList
8. Bring that into MessageBoard
9. Now for some data!
   1. Copy over `data.js` (make sure to change export syntax) and import it in
10. set initial state in MessageBoard constructor
11. and pass it down to CommentList using props
12. Let's stop to inspect everything in our devtools
13. render the comments using a map
14. make comment item and use that in CommentList
15. Notice there is a console error: need unique key
16. Now pass each comment as props and lets render it
17. pass down `handleDelete` function
18. CommentItem is getting messy! destructure props
19. Lets bring in our API 1.

    1. [concurrently](https://www.npmjs.com/package/concurrently) run sever and client
       add to your package.json

       ```
       "dev": "concurrently \"npm run server\" \"npm run client\" --names \"server,client\" ",
       "server": "nodemon index.js",
       "client": "cd client && npm start",
       ```

    1. proxy server address
    1. [axios](https://www.npmjs.com/package/axios)
    1. We will need to call data in [lifecyle hooks](https://reactjs.org/docs/react-component.html#the-component-lifecycle)

20. Let's do the add new comment form now
    1. We need to create a new controlled component
       > the React component that renders a form also controls what happens in that form on subsequent user input. An input form element whose value is controlled by React in this way is called a “controlled component”.
    2. create state and pass to input
    3. create change handler
    4. pass down add comment from app
    5. add submit handler

## Wednesday

### Project

Make an app using the [Pokeapi](https://pokeapi.co/)

#### Teams

1. Will & Brock
2. Emily & Kevin B
3. Scott & Jon
4. Hans & Kevin A
5. Ivy & Devon
6. Glen & Sam & Ervin

#### User Stories

- As a trainer I want to search by Pokémon name so that I can find my favorite ones
- As a trainer I want to view details on a specific Pokémon so that I can know if they're right for my team
  - type(s)
  - sprite
  - stats
  - moves
- As a trainer I want to view details on a specific move so that I can assemble the perfect move list
  - Some things you could include (don't need all):
    - PP
    - power
    - accuracy
    - type
    - effect
    - type effectiveness
    - damage class
- As a trainer I want to add a Pokémon to my team so that I can be the very best like no one ever was
  - No more than 6 on a team
- As a trainer I want to view my team so that I can build the perfect team composition

**Bonus**

- As a trainer I want to select my Pokémon's moveset so that I can perfectly balance my team
  - no more than 4 moves per pokemon
- As a trainer I want to search items so that I can give them to my Pokémon
- As a trainer I want to give my Pokemon items so that they will be more powerful in battle
  - No more than 1 item per pokemon

#### Hints

Read the [docs](https://pokeapi.co/docs/v2.html)!

`GET /api/v2/{endpoint}/` will give you a list of all the resources for that endpoint. For example `GET /api/v2/pokemon` will give you a list of all of the Pokémon. By default, this list is limited to 20 results. Use the query param `limit` to get more. For example: `GET /api/v2/pokemon?limit=964` will give you all the Pokémon (with names and url to that resource) in the database. You may want to use this to get your initial state for some of your components (perhaps to make search quicker).

The API is rate limited to 100 requests per minute, so be careful with how often you are hitting the endpoint or you will be throttled.

## Resources

- React
  - [Lifecycle Methods Diagram](http://projects.wojtekmaj.pl/react-lifecycle-methods-diagram/)
