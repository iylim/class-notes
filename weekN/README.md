# Post-Graduation Training

Congratulations! You are all now officially consultants; however, your learning is not over.
You should continue to level up your skills over the next few weeks/months on the bench.

I have put together this list of technologies and resources that are hot in the tech world right now.
You may proceed through these lessons at any pace you want.
This list is meant to guide your learning, but feel free to go off on any tangents that interest you.
If you start learning GraphQL and get inspired to build an API for beer, then by all means follow that interest.
In fact, I would recommend trying to build something (it can be small) with every technology you learn.

The most important part of learning is to stay curious and passionate.

- [Frontend](#frontend)
  - [Testing React Applications](#testing-react-applications)
  - [CSS Preprocessors](#css-preprocessors)
  - [Gatsby](#gatsby)
  - [Vue.js](#vuejs)
  - [Angular](#angular)
- [Backend](#backend)
  - [GraphQL](#graphql)
- [Other](#other)

## Frontend

### React

> A JavaScript library for building user interfaces.

#### Task

- Read the docs provided in Resources for futher content.

#### Resources

- [Awesome React: Curated List of awesome things](https://github.com/enaqx/awesome-react#react-general-tutorials)

### React Hooks

> **What is a Hook?** A Hook is a special function that lets you “hook into” React features. For example, `useState` is a Hook that lets you add React state to function components.

> **When would I use a Hook?** If you write a function component and realize you need to add some state to it, previously you had to convert it to a class. Now you can use a Hook inside the existing function component.

#### Task

- Read the docs provided in Resources.

#### Resources

- [React Docs: Hooks and Stateless Functions](https://reactjs.org/docs/hooks-state.html#hooks-and-function-components)

### React Native

> Build native mobile apps using JavaScript and React

#### Task

- Read the docs provided in Resources.

#### Resources

- [React Native: Getting Started](https://facebook.github.io/react-native/docs/getting-started)

### Progressive Web Apps

> Progressive web applications (PWAs) are web applications that load like regular web pages or websites but can offer the user functionality such as working offline, push notifications, and device hardware access traditionally available only to native applications. PWAs combine the flexibility of the web with the experience of a native application.

#### Task

- Read the docs provided in Resources.

#### Resources

- [Google: Building Your first PWA](https://codelabs.developers.google.com/codelabs/your-first-pwapp/#0)

### Testing React Applications

There are many, many ways to test code, and many ways to test React applications specifically.

One of the most popular methods uses Jest with Enzyme.

[Jest](https://jestjs.io/) is a JavaScript unit testing framework, used by Facebook to test services and React applications.

[Enzyme](https://airbnb.io/enzyme/) is a JavaScript Testing utility built by AirBnB for React that makes it easier to assert, manipulate, and traverse your React Components’ output.

#### Task <!-- omit in toc -->

First, work through the [Jest Getting Started Docs](https://jestjs.io/docs/en/getting-started.html) to familiarize yourself with Jest.
Then, follow this tutorial on [Testing React with Jest and Enzyme](https://medium.com/codeclan/testing-react-with-jest-and-enzyme-20505fec4675)

#### Additional Resources <!-- omit in toc -->

- [Jest Docs: Testing React Apps](https://jestjs.io/docs/en/tutorial-react)

### Sass

Sass is completely compatible with all versions of CSS.

> CSS on its own can be fun, but stylesheets are getting larger, more complex, and harder to maintain. This is where a preprocessor can help. Sass lets you use features that don't exist in CSS yet like variables, nesting, mixins, inheritance and other nifty goodies that make writing CSS fun again.

#### Task

Learn one of these and then try to refactor some CSS in an existing project.

#### Resources

- [Sass Guide](https://sass-lang.com/guide)
- [Create React App: Using Sass](https://facebook.github.io/create-react-app/docs/adding-a-sass-stylesheet)

### Gatsby

> Gatsby is a free and open source framework based on React that helps developers build blazing fast websites and apps

Gastby is an open-source framework built on React.
Gastby is a static site generator, which means it takes your React components + your data and outputs plain old HTML and CSS which you can serve from any server.
This makes your sites blazing fast. Gatsby is becoming increasingly popular for this reason

Gastby uses GraphQL to pull in your data from pretty much any sources from MongoDB to Wordpress.
GraphQL is a little weird so you might want to check out those tutorials before tackling Gatsby.

#### Task <!-- omit in toc -->

First, work through the [Gastby tutorials](https://www.gatsbyjs.org/tutorial/).
Their docs are very well-written and easy to follow.

I would also recommend going through Scott Tolinski's [video course](https://www.youtube.com/watch?v=b2H7fWhQcdE&list=PLLnpHn493BHHfoINKLELxDch3uJlSapxg).
He is great at explaining difficult concepts in simple terms.

Once you feel comfortable, try to remake your portfolio site using Gatsby.
Most importantly, try adding some kind of data store for your data (projects, blog posts, etc).
You can use Markdown files or some kind of CMS like [Netlify CMS](https://www.netlifycms.org/)

#### Additional Resources <!-- omit in toc -->

- [Gastby Docs](https://www.gatsbyjs.org/docs/)
- [Gastby Tutorials](https://www.gatsbytutorials.com/)

### Vue.js

Vue is a new(ish) frontend framework.
It's meant to be more approachable than React or Angular.
It is quickly gaining in popularity

#### Task <!-- omit in toc -->

Work through the [Intro to Vue.js](https://www.vuemastery.com/courses/intro-to-vue-js/vue-instance/) video course from Vue Mastery.

I would also recommend going through the [introduction](https://vuejs.org/v2/guide/index.html) from the official Vue docs.

Then, try to remake one of your React projects using Vue.
Try something simple like the Pokemon app or the message board.

#### Additional Resources <!-- omit in toc -->

- [Awesome Vue.js](https://github.com/vuejs/awesome-vue): curated list of awesome Vue resources
- [Vue.js Crash Course](https://courses.vuejsdevelopers.com/p/vue-js-crash-course?utm_source=linkedin-ag&utm_medium=bio)

### Angular

Another frontend framework.
Angular is actually much more robust than React or Vue which are technically just "view libraries."
With React and Vue you need to bring in a bunch of libraries.
Angular has all of the functionality out of the box to make full-fledged web apps.

Angular's robustness makes it very powerful but also intimidating to learn.
Be patient, this one might take some extra time.
But I think learning Angular is important because it will teach you a much deeper understanding of web application architecture.

**Note:** Angular requires TypeScript, which is a language extension of JavaScript that adds a lot of nice features.
You may want to look at TypeScript before tackling Angular.

**Note 2:** The version of Angular that most people use is technically version 2+ of AngularJS.
These are _different_ frameworks.
While they share a lot of similarities, the syntax is very different.
Be careful when looking at docs and StackOverflow.
Make sure they're using Angular 2+, not AngularJS.

#### Task <!-- omit in toc -->

First, check out Traversy Media's [Angular Crash Course](https://www.youtube.com/watch?v=Fdf5aTYRW0E).
This will give you a good overview of the framework.

Then, work through the official [Angular tutorial](https://angular.io/tutorial).

You can also work through this [Angular 7 tutorial](https://mdbootstrap.com/education/angular/).
It will teach you how to build an Angular appp with Bootstrap and Material.

#### Additional Resources <!-- omit in toc -->

- [Angular Docs](https://angular.io/docs)

## Backend

### GraphQL

> GraphQL is an open-source data query and manipulation language for APIs, and a runtime for fulfilling queries with existing data.

GraphQL is basically the next evolution of REST.
It completely changes the way you query and receive data.
It allows you to request exactly the data you want in a declarative syntax.

#### Task <!-- omit in toc -->

Work your way through [How To GraphQL](https://www.howtographql.com/).
This is a fullstack tutorial for GraphQL.
Go through the React + Apollo lessons.
[Apollo](https://www.apollographql.com/) is a frontend client for GraphQL.

You can also check out the [GraphQL tutorial](https://graphql.org/learn/) docs on their own website.

If you're feeling ambitious go through this [video course](https://www.youtube.com/watch?v=7giZGFDGnkc) that teaches you how to build a fullstack application with GraphQL, Node, Mongo, and React

#### Additional Resources <!-- omit in toc -->

- LevelUpTuts AKA Scott Tolinksi AKA El Toro Loco: [What Is GraphQL?](https://www.youtube.com/watch?v=VjXb3PRL9WI)

## Programming Fundamentals

### JS closures

> A closure is the combination of a function and the lexical environment within which that function was declared.

A part of programming that allows you to keep variables alive outside of their normal scope.

#### Task

- Read the docs provided in Resources.

#### Resources

- [Closures - Interview Questions](https://medium.com/javascript-scene/master-the-javascript-interview-what-is-a-closure-b2f0d2152b36)
- [MDN web docs: Closures](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Closures)

### Coding patterns

> Design patterns are used to represent some of the best practices adapted by experienced object-oriented software developers. A design pattern systematically names, motivates, and explains a general design that addresses a recurring design problem in object-oriented systems. It describes the problem, the solution, when to apply the solution, and its consequences.

#### Important

It is worth noting that there is a sort of antithesis to design patterns called the **Anti-Pattern**. This term is an umbrella category for patterns that seemingly addresses a current software engineering problem, but is later discovered to have been a bad decision as it resulted in maintainability issues or worse. For example, many believe that the Singleton Pattern is an anti-pattern as it leads to unintended behaviors when scaling to a multi-threaded environment from a single-threaded environment.

#### Resources

- [Geeks for geeks: Design Patterns](https://www.geeksforgeeks.org/software-design-patterns/)
- [JS Design Patterns](https://medium.com/beginners-guide-to-mobile-web-development/javascript-design-patterns-25f0faaaa15)

### OOP principles

> Object-oriented programming (OOP) is a programming language model in which programs are organized around data, or objects, rather than functions and logic. An object can be defined as a data field that has unique attributes and behavior.

> The four principles of object-oriented programming are encapsulation, abstraction, inheritance, and polymorphism.

#### Task

- Read the docs provided in Resources.

#### Resources

- [OOP - Overview](https://searchmicroservices.techtarget.com/definition/object-oriented-programming-OOP)
- [Introduction to Object Oriented Programming](https://medium.freecodecamp.org/object-oriented-programming-concepts-21bb035f7260)

### FP Principles

> An approach to programming (paradigm) that utilizes pure, first-class, and higher order functions with immutabile data.

#### Task

- Read the docs provided in Resources.

#### Resources

- [Introduction to Functional Programming](https://medium.freecodecamp.org/functional-programming-principles-in-javascript-1b8fc6c3563f)
- [FP in JS Interviews](https://medium.com/javascript-scene/master-the-javascript-interview-what-is-functional-programming-7f218c68b3a0)
- [Difference between Classical and Prototypal Inheritance](https://medium.com/javascript-scene/master-the-javascript-interview-what-s-the-difference-between-class-prototypal-inheritance-e4cd0a7562e9)
- [Curated List of FP Resources](https://github.com/leandrotk/functional-programming-learning-path)

### Solid Principles

- **Single Responsibility:** An object should only have a single responsibility. Consequently, any change to specificiation for that responsibility will be isolated to affected objects and not throughout the entire system.

- **Open/Closed:** Objects should be closed to change, but open to extensibility. The objects should be structured in a way where existing objects should not need to be changed in order to address requirement change. However, when new requirements invalidates old requirements, then this principle is no longer applicable to the existing objects.

- **Liskov Substitution:** Instances of the parent object should be replaceable with instances of their subtype object without altering the correctness of the system. Promotes "design by contracts" in which functionality are expanded through composition of behaviors instead of through direct inheritance of objects.

- **Interface Segregation:** It is better to have many, smaller client-specific interfaces instead of one general-purpose interface. Smaller interfaces allows for more appropriate reusability as it does not lead to enforcing behavior that may not be relevant just so a specific behavior can be inherited.

- **Dependency Inversion:** High level objects should not need to know the specifics of the low level objects that they depend on (i.e. abtractions over implementation). Dependance on abstractions promotes loose coupling of objects since the system is no longer tied to the specific concrete implementation, but rather a specific behavior.

#### Task

- Read the docs provided in Resources.

#### Resources

- [Scotch.io: Solid Principles](https://scotch.io/bar-talk/s-o-l-i-d-the-first-five-principles-of-object-oriented-design)

### Regex

> Regular expressions are patterns used to match character combinations in strings.

#### Task

- Read the docs provided in Resources.

#### Resources

- [MDN Docs: Regex](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Regular_Expressions)
- [Cheatsheet with Descriptions](https://medium.com/factory-mind/regex-tutorial-a-simple-cheatsheet-by-examples-649dc1c3f285)
- [Regex: Sandbox](https://regexr.com/)

### TypeScript

> TypeScript is a superset of JavaScript which primarily provides optional static typing, classes and interfaces. One of the big benefits is to enable IDEs to provide a richer environment for spotting common errors as you type the code.

> JavaScript is **dynamically typed**. This means JavaScript does not know what type a variable is until it is actually instantiated at run-time. This also means that it may be too late. **TypeScript adds type support to JavaScript.** Bugs that are caused by false assumptions of some variable being of a certain type can be completely eradicated if you play your cards right (how strict you type your code or if you type your code at all is up to you).

#### Task

- Read the docs provided in Resources.

#### Resources

- [Scrimba: Free Typescript Tutorial](https://scrimba.com/g/gintrototypescript)
- [Beginners Guide](https://www.typescriptlang.org/docs/handbook/typescript-in-5-minutes.html)
- [Creat-React-App: Typescript Version](https://github.com/Microsoft/TypeScript-React-Starter#typescript-react-starter)

## Work not completed below

- GraphQL
  - [How To GraphQL: Tutorial](https://www.howtographql.com/)
  - [GraphQL with Express](https://graphql.org/graphql-js/running-an-express-graphql-server/)
- Gatsby:
  - [Main Docs](https://www.gatsbyjs.org/)
- Vue
  - [Vue Docs](https://vuejs.org/)
  - [Awesome Vue: Curated List of awesome things](https://github.com/vuejs/awesome-vue)
- Angular
  - [Angular Docs](https://angular.io/docs)
  - [Awesome Angular: Curated list of awesome things](https://github.com/PatrickJS/awesome-angular)
- Architecture
  - [Atomic Design](http://atomicdesign.bradfrost.com/chapter-2/)
- Authentication, payment
- Python & Django
- CI/CD: Travis, Jenkins
- Testing: Jest, Mocha
- CS fundamentals
- ML, data analytics
