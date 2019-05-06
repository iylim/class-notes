# Post-Graduation Training

Congratulations! You are all now officially consultants; however, your learning is not over.
You should continue to level up your skills over the next few weeks/months on the bench.

I have put together this list of technologies and resources that are hot in the tech world right now.
You may proceed through these lessons at any pace you want.
This list is meant to guide your learning, but feel free to go off on any tangents that interest you.
If you start learning GraphQL and get inspired to build an API for beer, then by all means follow that interest.
In fact, I would recommend trying to build something (it can be small) with every technology you learn.

The most important part of learning is to stay curious and passionate.

* [Frontend](#frontend)
  * [Testing React Applications](#testing-react-applications)
  * [CSS Preprocessors](#css-preprocessors)
  * [Gatsby](#gatsby)
  * [Vue.js](#vuejs)
  * [Angular](#angular)
* [Backend](#backend)
  * [GraphQL](#graphql)
* [Other](#other)

## Frontend

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

### CSS Preprocessors

> A CSS preprocessor is a program that lets you generate CSS from the preprocessor's own unique syntax.
> There are many CSS preprocessors to choose from, however most CSS preprocessors will add some features that don't exist in pure CSS, such as mixin, nesting selector, inheritance selector, and so on.
> These features make the CSS structure more readable and easier to maintain.
>
> &mdash; [MDN](https://developer.mozilla.org/en-US/docs/Glossary/CSS_preprocessor)

The most popular CSS preprocessors are:

- [Sass](https://sass-lang.com/)
- [Less](http://lesscss.org/)
- [Stylus](http://stylus-lang.com/)
- [PostCSS](https://postcss.org/)

My favorites are Sass and Stylus.

#### Task <!-- omit in toc -->

Learn one of these and then try to refactor some CSS in an existing project.

#### Additional Resources <!-- omit in toc -->

- [Adding a Sass Stylesheet to a React App](https://facebook.github.io/create-react-app/docs/adding-a-sass-stylesheet)

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

## Other

- Architecture
  - [Atomic Design](http://atomicdesign.bradfrost.com/chapter-2/)
- Authentication, payment
- Python & Django
- CI/CD: Travis, Jenkins
- Testing: Jest, Mocha
- CS fundamentals
- ML, data analytics
