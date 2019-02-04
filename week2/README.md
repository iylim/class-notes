# Week 2: HTML, CSS, & JavaScript 

* [Current Events](#current-events)
* [Tools Check](#tools-check)
* [Git](#git)
  * [Code-along](#code-along)
  * [Skills Check Exercise](#skills-check-exercise)
* [HTML](#html)
  * [Key 🔑 Elements](#key--elements)
  * [Why Semantics Matter](#why-semantics-matter)
* [Project: Portfolio Site](#project-portfolio-site)
  * [Some things you should have on your site](#some-things-you-should-have-on-your-site)
  * [Examples](#examples)
  * [Github Pages](#github-pages)
* [CSS](#css)
* [Resources](#resources)
* [Schedule](#schedule)

## Current Events

[The Great Divide](https://css-tricks.com/the-great-divide/)

> "We're seeing coding schools absolutely explode and produce fairly talented developers in less than a year. These code school graduates are filling labor gaps, but more importantly starting to lead industry discussions rather than be passive followers of them."

Discuss among yourselves. Some questions to consider:
* Why do you think this "Great Divide" arose?
* How should we be distinguishing all of these different sides of web development? 
* How can employers specify this in there job postings? Also, what should you be looking for in job postings in order to know what kind of role you're applying to?
* Coyier warns that it's possible for JavaScript developers to "become  so framework-driven going down this path that your wider problem-solving skills suffer." How do you think we can avoid stagnating into merely "framework implementers"?

Some questions from Coyier:
* Is there any solution to these problems of suffering craftsmanship and skill devaluation? 
* Are the problems systemic and deeply rooted, or are they surface level and without severe consequence? 
* Is the divide real, or a temporary rift? 
* Is the friction settling down or heating up? 
* Will the front-end developer skill set widen or narrow as the years pass?

> "The only constant is change."

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
* Add your own contact info, using [Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
* commit, push, PR, merge

## HTML

From today's article:
> "One of the most glaring issues with making Full Stack Developers the gatekeepers of all-things-code is the pitiful quality of the HTML output. Most come from a computer science background, and document structure is simply not taught alongside control structure."

### Key 🔑 Elements
* `<!DOCTYPE html>`
* `<html>` root element
* `head`
  * `title`
  * `meta` tags
    * viewport: `<meta name="viewport" content="width=device-width, initial-scale=1.0">`
    * favicon: `<link rel="shortcut icon" type="image/png" href="/favicon.png"/>`
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
    ```html
    <picture>
      <source media="(min-width: 650px)" srcset="img_pink_flowers.jpg">
      <source media="(min-width: 465px)" srcset="img_white_flower.jpg">
      <img src="img_orange_flowers.jpg" alt="Flowers" style="width:auto;">
    </picture>
    ```
* [video](https://www.w3schools.com/tags/tag_video.asp)
  ```html
  <video width="320" height="240" controls>
    <source src="movie.mp4" type="video/mp4">
    <source src="movie.ogg" type="video/ogg">
    Your browser does not support the video tag.
  </video>
  ```
* tables
  * `tr`, `th`, `td`
* iframe
* semantic elements
  * `<header>`- Defines a header for a document or a section
  * `<nav>` - Defines a container for navigation links
  * `<section>` - Defines a section in a document
  * `<article>` - Defines an independent self-contained article
  * `<aside>` - Defines content aside from the content (like a sidebar)
  * `<footer>` - Defines a footer for a document or a section
  * `<details>` - Defines additional details
  * `<summary>` - Defines a heading for the `<details>` element

### Why Semantics Matter
* SEO
* Accessibility
* Maintainability
![divs vs good markups](http://v1c2v4d1fl-flywheel.netdna-ssl.com/wp-content/uploads/2017/08/semantic.jpg)

## Project: Portfolio Site

For now, use just HTML. Focus on semantics and structure.

### Some things you should have on your site

### Examples
* [Wes Bos](https://wesbos.com/)
* [Steve Schoger](http://www.steveschoger.com/)
* [Jonluca De Caro](https://jonlu.ca/#)
* [Matt Farley](http://mattfarley.ca/)

### Github Pages

Create a repository called ___username_.github.io__.
Push all of your code to this repo and it will automatically be hosted at _username_.github.io

[Documentation](https://pages.github.com/)

## CSS

* 3 ways to add:
  * Inline - by using the style attribute in HTML elements
  * Internal - by using a `<style>` element in the `<head>` section
  * External - by using an external CSS file
    * `<link rel="stylesheet" href="styles.css">`
* [Selectors](https://www.w3schools.com/cssref/css_selectors.asp)
  * element
  * class
  * id
  * [combinators](https://www.w3schools.com/css/css_combinators.asp): 
    * descendant selector (`space`)
    * child selector (`>`)
    * adjacent sibling selector (`+`)
    * general sibling selector (`~`)
  * [psuedo-class](https://www.w3schools.com/css/css_pseudo_classes.asp)
    * hover
    * link: visited, active
    * first-child, nth-child(an + b)
    * first-of-type
    * not
  * [psuedo-elements](https://www.w3schools.com/css/css_pseudo_elements.asp)
    * first-letter, first-line
    * before, after
    * selection
* [Colors](https://www.w3schools.com/css/css_colors.asp)
  * names
  * rgb/rgba
  * hex
  * hsl/hsla
* [Background](https://www.w3schools.com/css/css_background.asp)

## Resources

* Git
  * [Merging vs. Rebasing](https://www.atlassian.com/git/tutorials/merging-vs-rebasing)
* HTML
  * [Semantic HTML For Meaningful Webpages](http://seekbrevity.com/semantic-markup-important-web-design/)
* Git
  * [Git handbook](https://guides.github.com/introduction/git-handbook/)
  * [Git cheatsheets](https://services.github.com/on-demand/resources/cheatsheets/)

## Schedule
1. recap Disney trip, write down some thoughts: 8:45 - 9
2. current events: 9:15 - 9:45
3. Git lesson: 9:45 - 10:15
4. BREAK: 9:15 - 9:30
5. HTML code-along: 9:30 - 10:00
6. HTML portfolio exercise: 10:00 - Noon
7. LUNCH: noon - 1:00
8. CSS: 1:00 - 1:30
9.  CSS in portfolio
10. Extra time:
    1.  Bootstrap
    2.  Introduce group projects, put in groups, begin to brainstorm