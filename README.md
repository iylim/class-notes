# Talent Path Frontend Course 💻 📚 🎓

* [Week 1](#week-1)
  * [Join Our Discord Server!](#join-our-discord-server)
  * [In the News](#in-the-news)
  * [Technologies](#technologies)
  * [How the Web Works](#how-the-web-works)
    * [Resources](#resources)
* [General Resources](#general-resources)

## Week 1

### Join Our Discord Server!

1. [Click me](https://discord.gg/65YWDF)
2. Create an account
3. Post in #general your current favorite song

### In the News
* [Google Wants to Kill the URL](https://www.wired.com/story/google-wants-to-kill-the-url/)
* [Google Takes its First Steps Towards Killing the URL](https://www.wired.com/story/google-chrome-kill-url-first-steps/)

### Technologies

__What did we learn in school?__

__What do we need to learn to work on the web?__

__What do we want to learn?__

### How the Web Works
Or: __How the Heck Do I Have Access to the Entirety of Human Knowledge at Near Instantaneous Speeds?__

Computers connected to the web are either __clients__ or __servers__ (some are both).
![client & server](week1/client-server.jpg)
Clients _request_ information; servers, well, _serve_ it up. 
Servers are also connected directly to the internet, whereas clients are connected via an internet service provider (ISP). 
That's why you have to pay Time Warner or Verizon or whichever monopoly exists in your area to access the internet.



* IP address
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