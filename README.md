# Talent Path Frontend Course 💻 📚 🎓

* [Week 1](#week-1)
  * [Technologies](#technologies)
  * [Current Events](#current-events)
  * [How the Web Works](#how-the-web-works)
  * [Group Research Projects](#group-research-projects)
    * [Resources](#resources)
* [General Resources](#general-resources)

## Week 1

### Join Our Discord Server! <!-- omit in toc -->

1. [Click me](https://discord.gg/65YWDF)
2. Create an account
3. Post in #general your current favorite song

### Technologies

__What's important?__
* Frontend
  * HTML
  * CSS
    * Bulma
    * Vuetify
    * Bootstrap
    * Sass
    * BEM
  * JavaScript
    * ES6
      * arrow functions
      * destructuring
      * async/await
      * promises
  * Ruby on Rails
  * React
    * Redux
  * Vue
    * Vuex
  * Angular
  * php (Wordpress)
* Backend
  * Node/Express
  * Mongo
  * SQL
  * Postgres
  * APIs (restful)
    * Google maps
    * Yelp
    * Twitter
  * Authentication
    * Oauth
    * cookies/tokens
  * .NET
* Cloud
  * Azure
  * AWS
  * DigitalOcean
  * Firebase
  * Heroku
* Other languages
  * C++
  * C#
  * Java
  * Assembly
  * Python
  * Matlab
  * Lisp
  * F#
  * Ruby
  * OCamel
  * Haskell
* Soft skills
  * UI/UX
    * Sketch
    * InVision
    * XD
    * Photoshop
    * Illustrator
    * Gimp
  * Whiteboarding, storyboards (user stories)
  * Agile, SCRUM vs Waterfall
  * Interviewing
  * Testing, TDD
    * Mocha
    * Jest
    * JUnit
    * Selenium
    * Integration tests
    * Unit tests
* Developer tools
  * Notepad++
  * Brackets
  * Chrome dev tools
  * VS Code
  * Git
    * GitKraken
    * Github Desktop
  * Sublime
  * Gitlab
  * CI/CD
    * Jenkins
    * Vagrant
    * CircleCI
    * Travis
    * Virtual Box
  * Linux

__Core__

__Exposure__

__Tangential__

### Current Events
* [Google Wants to Kill the URL](https://www.wired.com/story/google-wants-to-kill-the-url/)
* [Google Takes its First Steps Towards Killing the URL](https://www.wired.com/story/google-chrome-kill-url-first-steps/)

Discuss among yourselves. Some questions to consider:
* What is the importance of URLs in our current version of the web?
* Do you think they are flawed? How so? 
* What are some of the pitfalls of using URLs? Benefits?
* What could we use in place of URLs?
* Consider Google's (and Chrome's) place as the _gatekeepers_ of the web. As the article mentions, they're able to propose radical new standards and then "throw Google's weight around to motivate everyone to adopt the practice." Do you think this is a positive use of their power, or could it lead to potential abuse?
* Going off of the above question: what is the role of corporations on the web? What should their role be?

### How the Web Works
Or: __How the Heck Do I Have Access to the Entirety of Human Knowledge at Near Instantaneous Speeds?__

Computers connected to the web are either __clients__ or __servers__ (some are both).

![client & server](week1/client-server.jpg)

Clients _request_ information; servers, well, _serve_ it up. 
Servers are also connected directly to the internet, whereas clients are connected via an internet service provider (ISP). 
That's why you have to pay Time Warner or Verizon or whichever monopoly exists in your area to access the internet.

__So how exactly does data flow through the internet?__

![Trucking](https://vni.s3.amazonaws.com/171221104902022.png)

Let's compare the internet to the shipping network used to transport physical goods all across the world.
In our physical example, we have trucks used to carry the goods, distribution centers, destinations where we want the goods to go, and roads for the trucks to travel on.
The web has a similar set of infastructure that make up the entire system: 

* __Wires, WIFI, and Satellite transmissions__ are the _roads_ that carry all of our data around the world.
* __Assets__ including code files such as HTML, CSS, and JavaScript, as well as images, video, music, etc. These are the _goods_ of our shipping network. The entire reason the internet exists is to transport these assets to anyone connected to the network.
* __Servers__ store the assets and serve them up to any who requests them. These are the _distribution centers_.
* __Clients__ are the ones who request assets. In our analogy this is your _home_, the end goal for all of our _goods_.
* __TCP__, otherwise known as __Transmission Control Protocol__, defines how applications can create channels of communication across a network and manages how a message is assembled into smaller packets. This is similar to the way containers, roads, and trucks are all _standardized_ so that anyone coming onto the network for the first time can immediately interact with it.
* __IP__, otherwise known as __Internet Protocol__, defines how to address and route each packet to make sure it reaches the right destination. This is like the _address_ of the buildings in our network. Every device on the network has a unique __IP address__.
* __DNS__, otherwise known as __Domain Name System__, is how devices translate human-readable _domain names_ to computer-readable IP addresses. DNS is akin to the yellow pages (or Google maps) where I can look up a building's address via the company name.
* __HTTP__ is the application protocol that defines how devices speak to each other and send/request assets. Like TCP, this _standardizes_ a method of communication so any new device can immediately communicate with everyone on the network. In our analogy, __HTTP__ is like the English you would use to verbally order goods.

### Group Research Projects

Topics
* Browser security, including
* Web protocols, including
* Web servers, including
* Browser wars, including

* DNS
  * associates names to corresponding address
  * TTL
  * cache
  * DNS recursor-> root nameserver -> TLD nameserver -> authoritative nameserver (Google domains, Godaddy)
  * [DNS records](https://www.cloudwards.net/what-are-dns-records/)
* HTTP (HyperText Transfer Protocol)
* TCP (Transmission Control Protocol): "defines how applications can create channels of communication across a network" and "manages how a message is assembled into smaller packets"
* IP (Internet Protocol): "defines how to address and route each packet to make sure it reaches the right destination"
* Layers
  * Application layer: provides applications with standardized data exchange including: HTTP, FTP, POP3, SMTP. It's what the web browser uses
  * Transport layer: maintains communications across the network (TCP), chops things up into packages
  * Network layer: connects networks 
* ping, ipconfig/ifconfig
* TLDs
* SSL/TLS & HTTPS (certs)
* Security
  * CORS and XORS
  * DNS spoofing
* Cookies/tokens

Example: 
* Digital Ocean droplet
* Google domains registar
* DO DNS
  * whois command
* Filezilla FTP
* ssh & nano for file manipulation

#### Resources
* [How Does the Internet Work](https://web.stanford.edu/class/msande91si/www-spr04/readings/week1/InternetWhitepaper.htm)
* [MDN Web Docs: How the Web Works](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/How_the_Web_works)
* [How Web Works (verrrry in-depth)](https://github.com/vasanthk/how-web-works)
* [Definitions of Web-related terms](https://developer.mozilla.org/en-US/docs/Glossary)

## General Resources
* [Developer Roadmap](https://github.com/kamranahmedse/developer-roadmap)
* [Front-End Developer Handbook 2018](https://frontendmasters.com/books/front-end-handbook/2018/)
* [w3schools](https://www.w3schools.com/)
* [MDN web docs](https://developer.mozilla.org/en-US/)
* [Odin Project](https://www.theodinproject.com/)
* [hackr.io](https://hackr.io/)
* Wes Bos
  * [CSS Grid](https://cssgrid.io/)
  * [JavaScript 30](https://javascript30.com/)
  * [What the Flexbox](https://flexbox.io/)
  * [Command Line Power User](https://commandlinepoweruser.com/)
* Podcasts
  * [Syntax](https://syntax.fm/)
  * [ShopTalk](https://shoptalkshow.com/)
* YouTube
  * [Level Up Tuts](https://www.youtube.com/channel/UCyU5wkjgQYGRB0hIHMwm2Sg)
* Blogs
  * [Refactoring UI](https://refactoringui.com/)
* [CSS Tricks](https://css-tricks.com/)
* Forums
  * [Stack Overflow](https://stackoverflow.com/)
  * [Hacker News](https://news.ycombinator.com/news)