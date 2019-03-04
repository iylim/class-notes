# Week 6: React!

## Monday

### Consuming APIs

[Fetch](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API): Vanilla JS API for making and consuming HTTP requests

In order to make requests to our server we will also need to enable [CORS](https://developer.mozilla.org/en-US/docs/Web/HTTP/CORS). We can use the [`cors` npm package](https://www.npmjs.com/package/cors).

[Code-along finished code](https://github.com/talent-path-la/message-board/tree/fetch)

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

- `npx create-react-app my-app`
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
19. Lets bring in our API
    1. [concurrently](https://www.npmjs.com/package/concurrently) run sever and client
    2. proxy server address
    3. [axios](https://www.npmjs.com/package/axios)
    4. We will need to call data in [lifecyle hooks](https://reactjs.org/docs/react-component.html#the-component-lifecycle)
20. Let's do the add new comment form now
    1. We need to create a new controlled component
       > the React component that renders a form also controls what happens in that form on subsequent user input. An input form element whose value is controlled by React in this way is called a “controlled component”.
    2. create state and pass to input
    3. create change handler
    4. pass down add comment from app
    5. add submit handler
