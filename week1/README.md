# Week 1

* [Join Our Discord Server!](#join-our-discord-server)
* [Technologies](#technologies)
  * [What Do We Know About?](#what-do-we-know-about)
  * [Core Knowledge](#core-knowledge)
    * [Frontend](#frontend)
    * [Backend](#backend)
    * [Cloud Services](#cloud-services)
    * [Miscellaneous Tech](#miscellaneous-tech)
    * [Soft Skills](#soft-skills)
  * [Will Be Exposed To](#will-be-exposed-to)
  * [Tangential](#tangential)
* [Current Events](#current-events)
* [How the Web Works](#how-the-web-works)
* [Example: Serving a Static Site](#example-serving-a-static-site)
* [Group Research Projects](#group-research-projects)
* [Resources](#resources)

## Join Our Discord Server!

1. [Click me](https://discord.gg/65YWDF)
2. Create an account
3. Post in #general your current favorite song

## Technologies

### What Do We Know About?
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

### Core Knowledge

#### Frontend
* HTML
* CSS
  * Sass
  * Bootstrap
* JavaScript
  * ES6
    * arrow functions
    * destructuring
    * async/await
    * promises
* React
  * Redux

#### Backend
* Node
  * Express
* MongoDB
* Authentication
  * Oauth
  * Cookies

#### Cloud Services
* Heroku
* Netlify

#### Miscellaneous Tech
* External APIs
* Testing
* Git
* Dev tools

#### Soft Skills
* Interviewing
* Whiteboarding
* Agile
* User stories

### Will Be Exposed To

* CSS
  * BEM
* Vue
  * Vuex
* Angular
* GraphQL
* Ruby on Rails
* SQL
* CI/CD

### Tangential
* PHP
* .NET
* Cloud
  * Azure
  * DigitalOcean
  * AWS
* Postgres
* UI/UX tools (Sketch, Illustrator)

## Current Events
* [Google Wants to Kill the URL](https://www.wired.com/story/google-wants-to-kill-the-url/)
* [Google Takes its First Steps Towards Killing the URL](https://www.wired.com/story/google-chrome-kill-url-first-steps/)

Pair up (but not with someone at your table!) & discuss. Some questions to consider:
* What is the importance of URLs in our current version of the web?
* Do you think they are flawed? How so? 
* What are some of the pitfalls of using URLs? Benefits?
* What could we use in place of URLs?
* Consider Google's (and Chrome's) place as the _gatekeepers_ of the web. As the article mentions, they're able to propose radical new standards and then "throw Google's weight around to motivate everyone to adopt the practice." Do you think this is a positive use of their power, or could it lead to potential abuse?
* Going off of the above question: what is the role of corporations on the web? What should their role be?

## How the Web Works
Or: __How the Heck Do I Have Access to the Entirety of Human Knowledge at Near Instantaneous Speeds?__

Computers connected to the web are either __clients__ or __servers__ (some are both).

![client & server](client-server.jpg)

Clients _request_ information; servers, well, _serve_ it up. 
Servers are also connected directly to the internet, whereas clients are connected via an internet service provider (ISP). 
That's why you have to pay Time Warner or Verizon or whichever monopoly exists in your area to access the internet.

__So how exactly does data flow through the internet?__

![Trucking](https://www.nonforceddispatch.com/wp-content/uploads/2017/08/Trucking-with-guns-for-protection.jpg)

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
* __HTTP__, or the HyperText Transfer Protocol, is the application protocol that defines how devices speak to each other and send/request assets. Like TCP, this _standardizes_ a method of communication so any new device can immediately communicate with everyone on the network. In our analogy, __HTTP__ is like the English you would use to verbally order goods.

## Example: Serving a Static Site

What you need

| Tech | What it is | What it does | Alternatives |
| ---- | ---------- | ------------ | ------------ |

<!-- | ---------------- | ----------------------- | ------------------------------------------------------------------------------------- | ------------------------- |
| [DigitalOcean]   | Cloud solutions         | Hosts my own virtual machine                                                          | [AWS], [Azure]            |
| [Ubuntu]         | Linux distrubution      | Operating system for my VM                                                            | [Take your pick][distros] |
| [Nginx]          | Web server software     | Manages all the web traffic on VM                                                     | [Apache]                  |
| [Google Domains] | Domain registar and DNS | Purchasing domain, and connecting server's IP to domain name via a Domain Name Server | [Bluehost], [Namecheap]   |
| [Filezilla]      | FTP client              | Access the files on my server and upload new ones                                     | [Cyberduck]               |
| [HTML]           | Markup                  | Frontend. This is what the browser actually loads and renders                         | .txt                      |

[DigitalOcean]: https://www.digitalocean.com/
[AWS]: https://aws.amazon.com/
[Azure]: https://azure.microsoft.com/en-us/
[Ubuntu]: https://www.ubuntu.com/
[distros]: https://www.wikiwand.com/en/List_of_Linux_distributions
[Nginx]: https://www.nginx.com/
[Apache]: https://httpd.apache.org/
[Google Domains]: https://domains.google/#/
[Bluehost]: https://www.bluehost.com/
[Namecheap]: https://www.namecheap.com/
[Filezilla]: https://filezilla-project.org/
[Cyberduck]: https://cyberduck.io/
[HTML]: https://www.w3schools.com/html/default.asp -->

## Group Research Projects

* [Browser security](https://docs.google.com/presentation/d/1H0RLt1l6RJ2X6cPXNs0vWv-njQuXuPPFHOw14azf_B8/edit?usp=sharing), including
  * HTTPS
  * SSL/TSL
  * CORS
  * XSS attacks
  * DNS spoofing
* [Web protocols](https://docs.google.com/presentation/d/1ZPAzd_0jNotDqyjBPLfvv0wQtWqE7SX3KqmJ5_W-mlI/edit?usp=sharing), including
  * HTTP/HTTPS
  * Websockets
  * FTP
  * IMAP/POP3/SMTP
  * SSL
  * SSH
  * UDP
* [Web servers](https://docs.google.com/presentation/d/1mFVDEdNmyEwQv8k9bn5ImhDNpblTFxu4vDoxDDMjfp0/edit?usp=sharing), including
  * Apache
  * Nginx
  * Node
  * pros/cons, usage
* [Browser wars](https://docs.google.com/presentation/d/1EtEkxRkd_2M9s4XE41d5H-iJbE9-3S0dkxYeUcryHEA/edit?usp=sharing), including
  * Chromium
  * IE is dead??
  * Opera
  * Firefox
  * Brave

## Resources
* [How Does the Internet Work](https://web.stanford.edu/class/msande91si/www-spr04/readings/week1/InternetWhitepaper.htm)
* [MDN Web Docs: How the Web Works](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/How_the_Web_works)
* [How Web Works (verrrry in-depth)](https://github.com/vasanthk/how-web-works)
* [Definitions of Web-related terms](https://developer.mozilla.org/en-US/docs/Glossary)
* A few articles on HTTP
  * [HTTP — an Application-Level Protocol](https://dev.opera.com/articles/http-basic-introduction/)
  * [HTTP: Let’s GET It On!](https://dev.opera.com/articles/http-lets-get-it-on/)
  * [HTTP: Response Codes](https://dev.opera.com/articles/http-response-codes/)