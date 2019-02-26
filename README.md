# Talent Path Fullstack Course 💻 📚 🎓

**How to use these notes:**
this repository will contain all of the notes for our class.
This README will give a general overview of the entire class, week by week.
You can scan this for a quick reminder of what we did each week.
For more detailed notes, look in the corresponding folder for each week.

These notes will be updated daily (sometimes multiple times a day).
If you have any suggestions, please feel free to make a pull request or file an issue.

* [Week 1](#week-1)
  * [Technologies](#technologies)
  * [Current Events](#current-events)
  * [How the Web Works](#how-the-web-works)
  * [Example: Serving a Static Site](#example-serving-a-static-site)
  * [Group Research Projects](#group-research-projects)
  * [Resources](#resources)
* [Week 2](#week-2)
  * [Current Events](#current-events-1)
  * [Git](#git)
    * [Exercise](#exercise)
  * [HTML](#html)
    * [Project](#project)
  * [CSS](#css)
    * [Code-along](#code-along)
  * [JavaScript](#javascript)
    * [Tooling](#tooling)
    * [Topics](#topics)
    * [Exercises](#exercises)
  * [Resources](#resources-1)
* [General Resources](#general-resources)

## Week 1

### Technologies

Compiled a list of web technologies we are familiar with.
Broke that list down into **core** technologies that we will learn in this class,
ones we will be **exposed** to, and technologies that are **tangential** to what we are learning.

### Current Events

- [Google Wants to Kill the URL](https://www.wired.com/story/google-wants-to-kill-the-url/)
- [Google Takes its First Steps Towards Killing the URL](https://www.wired.com/story/google-chrome-kill-url-first-steps/)

### How the Web Works

- **Wires, WIFI, and Satellite transmissions** carry all of our data around the world.
- **Assets** including code files such as HTML, CSS, and JavaScript, as well as images, video, music, etc.
- **Servers** store the assets and serve them up to any who requests them.
- **Clients** are the ones who request assets.
- **TCP**, otherwise known as **Transmission Control Protocol**, defines how applications can create channels of communication across a network and manages how a message is assembled into smaller packets.
- **IP**, otherwise known as **Internet Protocol**, defines how to address and route each packet to make sure it reaches the right destination.
- **DNS**, otherwise known as **Domain Name System**, is how devices translate human-readable _domain names_ to computer-readable IP addresses.
- **HTTP**, or the HyperText Transfer Protocol, is the application protocol that defines how devices speak to each other and send/request assets.

### Example: Serving a Static Site

- DigitalOcean
- Ubuntu
- Nginx Server
- Google Domains
- Filezilla
- HTML5

### Group Research Projects

- [Browser security](https://docs.google.com/presentation/d/1H0RLt1l6RJ2X6cPXNs0vWv-njQuXuPPFHOw14azf_B8/edit?usp=sharing)
- [Web protocols](https://docs.google.com/presentation/d/1ZPAzd_0jNotDqyjBPLfvv0wQtWqE7SX3KqmJ5_W-mlI/edit?usp=sharing)
- [Web servers](https://docs.google.com/presentation/d/1mFVDEdNmyEwQv8k9bn5ImhDNpblTFxu4vDoxDDMjfp0/edit?usp=sharing)
- [Browser wars](https://docs.google.com/presentation/d/1EtEkxRkd_2M9s4XE41d5H-iJbE9-3S0dkxYeUcryHEA/edit?usp=sharing)

### Resources

- [How Does the Internet Work](https://web.stanford.edu/class/msande91si/www-spr04/readings/week1/InternetWhitepaper.htm)
- [MDN Web Docs: How the Web Works](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/How_the_Web_works)
- [How Web Works (verrrry in-depth)](https://github.com/vasanthk/how-web-works)
- [Definitions of Web-related terms](https://developer.mozilla.org/en-US/docs/Glossary)
- A few articles on HTTP
  - [HTTP — an Application-Level Protocol](https://dev.opera.com/articles/http-basic-introduction/)
  - [HTTP: Let’s GET It On!](https://dev.opera.com/articles/http-lets-get-it-on/)
  - [HTTP: Response Codes](https://dev.opera.com/articles/http-response-codes/)

## Week 2

### Current Events

- [The Great Divide](https://css-tricks.com/the-great-divide/)
- [Codepen.io](https://codepen.io/)
- [Motherfucking Website](http://motherfuckingwebsite.com/)
- [Better Motherfucking Website](http://bettermotherfuckingwebsite.com/)
- [Best Motherfucking Website](https://thebestmotherfucking.website/)
- [Links that don’t go anywhere should be buttons](https://christianheilmann.com/2019/02/05/links-that-dont-go-anywhere-should-be-buttons/)

### Git

![Git workflow](https://appendtonew.wpengine.com/wp-content/uploads/2015/06/Screen-Shot-2015-06-24-at-8.37.13-PM-1024x663.png)

**On a new repository:**

1. `git init`
2. `git add -A`
3. `git commit -m "init"`
4. `git remote add origin <repository URL>`
5. `git push -u origin master`

**For continued work:**

1. `git add`
2. `git commit`
3. `git push`

#### Exercise

[student-directory](https://github.com/talent-path-la/student-directory)

### HTML

Make sure to use semantic elements whenever possible. Avoid "div soup".
![divs vs good markups](http://v1c2v4d1fl-flywheel.netdna-ssl.com/wp-content/uploads/2017/08/semantic.jpg)
Some HTML5 semantic elements include:

- `<header>`- Defines a header for a document or a section
- `<nav>` - Defines a container for navigation links
- `<section>` - Defines a section in a document
- `<article>` - Defines an independent self-contained article
- `<aside>` - Defines content aside from the content (like a sidebar)
- `<footer>` - Defines a footer for a document or a section
- `<details>` - Defines additional details
- `<summary>` - Defines a heading for the `<details>` element

#### Project

[portfolio](https://github.com/talent-path-la/portfolio)

### CSS

#### Code-along

[portfolio](https://github.com/talent-path-la/portfolio)

We learned how to build a splash and a nav (with dropdown).

**Advanced CSS topics:**

- [Responsive design](https://www.w3schools.com/css/css_rwd_intro.asp)
- [Grid](https://css-tricks.com/snippets/css/complete-guide-grid/)
- [Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
- [Animations](https://www.w3schools.com/css/css3_animations.asp) - pure CSS slider

### JavaScript

#### Tooling

- [Node.js](https://nodejs.org/en/)
- [ESLint](https://eslint.org/)
- [JavaScript (ES6) code snippets](https://marketplace.visualstudio.com/items?itemName=xabikos.JavaScriptSnippets)

#### Topics

- general language knowledge
- strings
- numbers
- arrays, especially array functions like `map` and `filter`
- objects

#### Exercises

- [JS Cardio 🏃🏼](https://github.com/talent-path-la/js-cardio)
- [Connect Four](https://github.com/talent-path-la/connect-four)

### Resources

- Git
  - [Merging vs. Rebasing](https://www.atlassian.com/git/tutorials/merging-vs-rebasing)
  - [Git handbook](https://guides.github.com/introduction/git-handbook/)
  - [Git cheatsheets](https://services.github.com/on-demand/resources/cheatsheets/)
- HTML
  - [Style Guide](https://www.w3schools.com/html/html5_syntax.asp)
  - [Semantic HTML For Meaningful Webpages](http://seekbrevity.com/semantic-markup-important-web-design/)
- CSS
  - [Gradient tool](https://cssgradient.io/)
  - [A Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
  - [Grid](https://css-tricks.com/snippets/css/complete-guide-grid/)
  - [6 Tips that Will Improve Your UI Typography](http://www.steveschoger.com/2017/07/19/6-tips-that-will-improve-your-ui-typography/)
- JS
  - [Style Guide](https://www.w3schools.com/js/js_conventions.asp)

## General Resources

- [Developer Roadmap](https://github.com/kamranahmedse/developer-roadmap)
- [Front-End Developer Handbook 2018](https://frontendmasters.com/books/front-end-handbook/2018/)
- [w3schools](https://www.w3schools.com/)
- [MDN web docs](https://developer.mozilla.org/en-US/)
- [Odin Project](https://www.theodinproject.com/)
- [JavaScript.info](https://javascript.info/): The Modern Javascript Tutorial
- [hackr.io](https://hackr.io/)
- [State of JavaScript](https://stateofjs.com/)
- Wes Bos
  - [CSS Grid](https://cssgrid.io/)
  - [JavaScript 30](https://javascript30.com/)
  - [What the Flexbox](https://flexbox.io/)
  - [Command Line Power User](https://commandlinepoweruser.com/)
- Podcasts
  - [Syntax](https://syntax.fm/)
  - [ShopTalk](https://shoptalkshow.com/)
  - [99 Percent Invisible](https://99percentinvisible.org/)
- YouTube
  - [Level Up Tuts](https://www.youtube.com/channel/UCyU5wkjgQYGRB0hIHMwm2Sg)
- Blogs
  - [Refactoring UI](https://refactoringui.com/)
  - [Dev Tips](https://umaar.com/dev-tips/)
  - [CSS Tricks](https://css-tricks.com/)
- Forums
  - [Stack Overflow](https://stackoverflow.com/)
  - [Hacker News](https://news.ycombinator.com/news)
- Fun & Inspirational
  - [Codepen](https://codepen.io/)
  - [Dribble](https://dribbble.com/)
- Coding practice
  - [Frontloops](https://frontloops.io/): HTML/CSS challenges sent via email
  - [Daily CSS Images](http://dailycssimages.com/)
