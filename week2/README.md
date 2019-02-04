# Week 2: HTML, CSS, & JavaScript 

* [Current Events](#current-events)
* [Tools Check](#tools-check)
* [Git](#git)
  * [Code-along](#code-along)
  * [Skills Check Exercise](#skills-check-exercise)
* [HTML](#html)
  * [Why Semantics Matter](#why-semantics-matter)
  * [Key 🔑 Elements](#key--elements)
* [Project: Portfolio Site](#project-portfolio-site)
  * [Some things you should have on your site](#some-things-you-should-have-on-your-site)
  * [Examples](#examples)
  * [Github Pages](#github-pages)
* [Resources](#resources)
* [Schedule](#schedule)

## Current Events

[The Great Divide](https://css-tricks.com/the-great-divide/)

## Tools Check

Does everyone have?
- [ ] Code editor
- [ ] Git
- [ ] Some way to access command prompt
- [ ] GitKraken or other desktop git client (if you'd like)

## Git

![Git workflow](https://appendtonew.wpengine.com/wp-content/uploads/2015/06/Screen-Shot-2015-06-24-at-8.37.13-PM-1024x663.png)

### Code-along

__First, try this on the command line:__
1. create directory locally
2. create `README.md` file
3. create repo online
4. `git init`
5. `git add .`
6. `git commit -m "init"`
7. `git remote add origin <new-repository>`
8. `git push -u origin master`
9. 💵💵💵

Wipe the code from drive

__Now let's do it with GitKraken__
1. clone repo via GitKraken (demonstrate how to do this on command line)
2. Make a new branch (or `git checkout -b <branch-name>`
3. Make an edit
4. Add
5. Commit
6. Push
7. Create pull request
8. Merge and close

### Skills Check Exercise

__Now everyone do it with [student-directory]()__
* clone repo
* make your own branch
* Add your own contact info, using Markdown
* commit, push, PR, merge

## HTML

### Why Semantics Matter
* SEO
* Accessibility
* Maintainability

### Key 🔑 Elements
* `<!DOCTYPE html>`
* `<html>` root element
* `head`
  * `title`
  * `meta` tags
    * viewport: `<meta name="viewport" content="width=device-width, initial-scale=1.0">`
    * favicon
* headings: `h1` through `h6`
  > "Search engines use the headings to index the structure and content of your web pages. Users skim your pages by its headings. It is important to use headings to show the document structure"
* `p`
* links
  * href
  * target
    * `_blank` - Opens the linked document in a new window or tab
    * `_self` - Opens the linked document in the same window/tab as it was clicked (this is default)
    * `_parent` - Opens the linked document in the parent frame
    * `_top` - Opens the linked document in the full body of the window
  * linking to pages on same domain
  * bookmarks: `<h2 id="C4">Chapter 4</h2>` + `<a href="#C4">Jump to Chapter 4</a>`
* inline elements: `span`, `b`, `i`, `strong`, `em`, `sub` & `sup`
* `pre`
  > The text inside a `<pre>` element is displayed in a fixed-width font (usually Courier), and it preserves both spaces and line breaks
* `br` and `hr`
* comments
* `div`
* lists (`ul` & `ol`)
* images
  * src
  * alt
  * [`<picture>`](https://www.w3schools.com/tags/tag_picture.asp)
* tables
* semantic elements
  * `<header>`- Defines a header for a document or a section
  * `<nav>` - Defines a container for navigation links
  * `<section>` - Defines a section in a document
  * `<article>` - Defines an independent self-contained article
  * `<aside>` - Defines content aside from the content (like a sidebar)
  * `<footer>` - Defines a footer for a document or a section
  * `<details>` - Defines additional details
  * `<summary>` - Defines a heading for the `<details>` element

## Project: Portfolio Site

For now, use just HTML. Focus on semantics and structure.

### Some things you should have on your site

### Examples

### Github Pages

Create a repository called ___username_.github.io__.
Push all of your code to this repo and it will automatically be hosted at _username_.github.io

[Documentation](https://pages.github.com/)

## Resources

* [Semantic HTML For Meaningful Webpages](http://seekbrevity.com/semantic-markup-important-web-design/)

## Schedule
1. recap Disney trip, write down some thoughts: 8 - 8:15
2. current events: 8:15 - 8:45
3. Git lesson: 8:45 - 9:15
4. BREAK: 9:15 - 9:30
5. HTML code-along: 9:30 - 10:00
6. HTML group article exercise: 10:00 - Noon
7. LUNCH: noon - 1:00
8. Deploying site: 1:00 - 1:15
9. CSS: 1:15 - 1:45
10. CSS in portfolio
11. Extra time:
    1.  Bootstrap
    2.  Introduce group projects, put in groups, begin to brainstorm