# Post-Graduation Training

Congratulations! You are all now officially consultants; however, your learning is not over.
You should continue to level up your skills over the next few weeks/months on the bench.

I have put together this list of technologies and resources that are hot in the tech world right now.
You may proceed through these lessons at any pace you want.
This list is meant to guide your learning, but feel free to go off on any tangents that interest you.
If you start learning GraphQL and get inspired to build an API for beer, then by all means follow that interest.
In fact, I would recommend trying to build something (it can be small) with every technology you learn.

The most important part of learning is to stay curious and passionate.

### Sass

Sass is completely compatible with all versions of CSS.

> CSS on its own can be fun, but stylesheets are getting larger, more complex, and harder to maintain. This is where a preprocessor can help. Sass lets you use features that don't exist in CSS yet like variables, nesting, mixins, inheritance and other nifty goodies that make writing CSS fun again.

#### Task

- Read the docs provided in Resources.

#### Resources

- [Sass Guide](https://sass-lang.com/guide)
- [Create React App: Using Sass](https://facebook.github.io/create-react-app/docs/adding-a-sass-stylesheet)

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

#### Task

- Read the docs provided in Resources.

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