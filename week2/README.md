# Week 2: HTML, CSS, & JavaScript 

* [Monday](#monday)
  * [Disney Recap](#disney-recap)
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
* [Tuesday](#tuesday)
  * [Current Events](#current-events-1)
  * [CSS](#css)
* [Wednesday: Advanced Design](#wednesday-advanced-design)
  * [Current Events](#current-events-2)
  * [Some Design Guidelines](#some-design-guidelines)
    * [Visual Hierarchy](#visual-hierarchy)
    * [Typography](#typography)
  * [Responsive](#responsive)
  * [Flexbox](#flexbox)
  * [Grid](#grid)
  * [Animations](#animations)
* [Thursday: JavaScript](#thursday-javascript)
  * [Current Events](#current-events-3)
  * [Javascript Basics](#javascript-basics)
* [Resources](#resources)
* [Schedule](#schedule)
  * [Monday](#monday-1)
  * [Tuesday](#tuesday-1)
  * [Wednesday](#wednesday)

## Monday

### Disney Recap

* streaming (direct to consumer). What kind of tech to be involved with streaming?
  * SPA
  * [HLS](https://www.wikiwand.com/en/HTTP_Live_Streaming)
* UI/UX
  * really high demand
  * people aren't learning design
* React
* MEAN/MERN
* DATA 📈
  * data-driven decision-making
  * ML
  * capture as much data as you can
  * in-house anaylizing and collection
  * modelling
  * cross-referencing data
* how to secure funding/gain support
  * understanding the bigger picture of the company
* WALL-E
* Agile

### Current Events

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

### Tools Check

Does everyone have?
- [ ] Code editor
- [ ] Git
- [ ] Some way to access command prompt
- [ ] GitKraken or other desktop git client (if you'd like)

### Git

![Git workflow](https://appendtonew.wpengine.com/wp-content/uploads/2015/06/Screen-Shot-2015-06-24-at-8.37.13-PM-1024x663.png)

#### Code-along

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

#### Skills Check Exercise

__Now everyone do it with [student-directory]()__
* clone repo
* make your own branch
* Add your own contact info, using [Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
* commit, push, PR, merge

### HTML

From today's article:
> "One of the most glaring issues with making Full Stack Developers the gatekeepers of all-things-code is the pitiful quality of the HTML output. Most come from a computer science background, and document structure is simply not taught alongside control structure."

#### Key 🔑 Elements
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

#### Why Semantics Matter
* SEO
* Accessibility
* Maintainability
![divs vs good markups](http://v1c2v4d1fl-flywheel.netdna-ssl.com/wp-content/uploads/2017/08/semantic.jpg)

### Project: Portfolio Site

For now, use just HTML. Focus on semantics and structure.

#### Some things you should have on your site
* projects
* overview/about
* contact
* resume
* blog
* picture of yourself
* links to social media

#### Examples
* [Wes Bos](https://wesbos.com/)
* [Steve Schoger](http://www.steveschoger.com/)
* [Jonluca De Caro](https://jonlu.ca/#)
* [Matt Farley](http://mattfarley.ca/)

#### Github Pages

Create a repository called ___username_.github.io__.
Push all of your code to this repo and it will automatically be hosted at _username_.github.io

[Documentation](https://pages.github.com/)

## Tuesday

### Current Events

[Codepen.io](https://codepen.io/): "social development environment for front-end designers and developers" AKA a place to share dope HTML/CSS/JS projects.

Find a cool pen and show a neighbor.
Tell them what you like about it, why you think it's interesting.

### CSS

[Starter files for code-along exercise](https://github.com/talent-path-la/portfolio)

* 3 ways to add:
  * Inline - by using the style attribute in HTML elements
  * Internal - by using a `<style>` element in the `<head>` section
  * External - by using an external CSS file
    * `<link rel="stylesheet" href="styles.css" type="text/css">`
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
* box model: margin/padding
  ![box model diagram](boxmodel.png) 
* borders and border-radius
* [Colors](https://www.w3schools.com/css/css_colors.asp)
  * names
  * rgb/rgba
  * hex
  * hsl/hsla
    ![HSL cone](https://upload.wikimedia.org/wikipedia/commons/2/2d/HSL_color_solid_dblcone.png)
* [Background](https://www.w3schools.com/css/css_background.asp)
  * color
  * image
  * repeat
  * position
  * [gradient](https://www.w3schools.com/css/css3_gradients.asp)
* fonts
  * [Google fonts](https://fonts.google.com/)
* [units](https://www.w3schools.com/css/css_units.asp)
  * vw/vh
  * px
  * em/rem
  * %
* box-shadow, text-shadow
* lists (making a nav)
* position
* varibles

## Wednesday: Advanced Design

Today's gonna be great!

### Current Events

* [Motherfucking Website](http://motherfuckingwebsite.com/)
* [Better Motherfucking Website](http://bettermotherfuckingwebsite.com/)
* [Best Motherfucking Website](https://thebestmotherfucking.website/)

Discuss with your peers:
* What is the message behind each website? What ideals are each website championing or improving upon from the last?
* Which one do you like the most? Why?
* To what extent is it true that "Good design is as little design as possible"?

### Some Design Guidelines

#### Visual Hierarchy
> Visual hierarchy is the order in which a user processes information on a page; its function in user interface (UI) design is to allow users to understand information easily.
> 
> &mdash; Interaction Design Foundation's [Visual Hierchay](https://www.interaction-design.org/literature/topics/visual-hierarchy)

Hierarchy can be communicated through:
* __Size:__ the larger the element, the more attention it will attract
* __Color:__ bright colors are more likely to draw attention over muted ones
* __Contrast:__ dramatically contrasted colors will catch the eye easily
* __Alignment:__ an element that breaks away from the alignment of others will attract more attention
* __Repetition:__ repeating styles can give the impression that content is related
* __Proximity:__ closely placed elements will also appear related
* __Whitespace:__ more space around elements will attract the eye toward them
* __Texture and style:__ richer textures will attract more attention than flat ones
* __Movement:__ animated elements will catch the user's eye

Hierarchy is used to direct a reader's eye in order to craft a specific user experience.
_We as designers_ are responsible for (subtly) telling the user what to do.

#### Typography
> 95% of the information on the web is written language. It is only logical to say that a web designer should get good training in the main discipline of shaping written information, in other words: Typography.
> 
> &mdash; [The Web Is All About Typography. Period.](https://ia.net/topics/the-web-is-all-about-typography-period) by Oliver Reichenstein (2006)

Here are a few guidelines for improving your typography (taken from Steve Schroger's [6 Tips that Will Improve Your UI Typography](http://www.steveschoger.com/2017/07/19/6-tips-that-will-improve-your-ui-typography/)):

__Use liberal spacing__
![font-size: 16px; line-height: 1.5em](http://www.steveschoger.com/img/170719-improving-typography/01-spacing.png)

Line height should be somewhere between 1.4 and 1.6, depending on the font. 
> The main goal is to make it so you can comfortably jump from one line to the next without getting disoriented.

Combined with text width, a comfortable line-height can make content less intimidating and more inviting.

__Establish a visual rhythm__

When defining margins and padding, use multiples of a relative unit (like `rem`) to maintain consistency.

![In the image, I've used multiples of 6 to define both the line height and the margins.](http://www.steveschoger.com/img/170719-improving-typography/02-baseline-example.png)

__Use color and contrast__

> Sometimes, in order to make something stand out, you need to make other elements of the design stand back.

![contrast of the paragraph text by 20 - 30%](http://www.steveschoger.com/img/170719-improving-typography/03-contrast.png)

You can use 3 shade variations for text to create hierachy and relieve monotony.

![3 shade variations: #222, #6e6e6e, #4a4a4a](http://www.steveschoger.com/img/170719-improving-typography/04-shade-varients.png)

Make sure the contrast meets [accessibility standards](https://webaim.org/resources/contrastchecker/)!

__Never go full black__

Its easier to read dark grey text than black text when on a white background.

![#4a4a4a on white bg](http://www.steveschoger.com/img/170719-improving-typography/05-black-text.png)

Instead of a dark grey text, you can also use grey saturated a bit with the brand color. 
This will really tie the design together. 
Checkout Facebook:

![Facebook saturates all of their greys with blue](http://www.steveschoger.com/img/170719-improving-typography/06-facebook-hue.png)

__Don't use grey text on a colored background__

You can also use this saturation technique when working with colored backgrounds.
Instead of using grey, saturate the text with a bit of the background color.

![Include a bit of the bg color](http://www.steveschoger.com/img/170719-improving-typography/07-pure-grey-on-color.png)

__Use a comfortable line length__

Text should never fill the entire screen. Whitespace is ok. Aim for a line length of around 80 characters.

![Line length 70-80 characters is ideal](http://www.steveschoger.com/img/170719-improving-typography/08-line-length.png)

__Left align large blocks of text__

![Left aligned text](http://www.steveschoger.com/img/170719-improving-typography/09-alignment.png)

### Responsive

### Flexbox

### Grid

### Animations

## Thursday: JavaScript

### Current Events

[Links that don’t go anywhere should be buttons](https://christianheilmann.com/2019/02/05/links-that-dont-go-anywhere-should-be-buttons/)

Be careful with your JavaScript! 
You can do anything you want... doesn't mean you should.
Markup still matters.

### Javascript Basics
1. install [node](https://nodejs.org/en/)
     * Optional: use a package manager
       * [Chocolatey](https://chocolatey.org/)  (Windows)
       * [Homebrew](https://brew.sh/) (Mac)
2. Go over important basics
   1. [string methods](https://www.w3schools.com/js/js_string_methods.asp)
   2. [number methods](https://www.w3schools.com/js/js_number_methods.asp)
   3. [array methods](https://www.w3schools.com/js/js_array_methods.asp)
   4. [DOM manipulation]()
3. array cardio
   1. Teams:
      1. Scott & Brock
      2. Emily & Ivy
      3. Hans & Sam
      4. Jon & Ervin
      5. Kevin B & Glen
      6. Devon & Will & Kevin A

## Resources

* Git
  * [Merging vs. Rebasing](https://www.atlassian.com/git/tutorials/merging-vs-rebasing)
  * [Git handbook](https://guides.github.com/introduction/git-handbook/)
  * [Git cheatsheets](https://services.github.com/on-demand/resources/cheatsheets/)
* HTML
  * [Style Guide](https://www.w3schools.com/html/html5_syntax.asp)
  * [Semantic HTML For Meaningful Webpages](http://seekbrevity.com/semantic-markup-important-web-design/)
* CSS
  * [Gradient tool](https://cssgradient.io/)
  * [A Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
* JS
  * [Style Guide](https://www.w3schools.com/js/js_conventions.asp)

## Schedule

### Monday
1. recap Disney trip, write down some thoughts: 8:45 - 9
2. current events: 9:15 - 10:00
3. Git lesson: 10:00 - 11:00
4. Git exercise: 11:30 - 12:30
5. LUNCH: 12:30 - 1:30
6. HTML code-along: 1:30 - 3:00
7. HTML portfolio exercise: 3:00 - 5:00

### Tuesday
1. Current events: 8:30 - 8:45
2. CSS codealong: 9:00 - 10:30
3. Portfolio projects (adding styles): rest of day

### Wednesday
1. Current events: 8:30 - 8:45
2. Design discussion on hiearchy: 8:45 - 9:15
3. Design discussion on typography: 9:30 - 10:00
4. Portfolio work: 10:00 - lunch
5. LUNCH: noon - 1:00
6. CSS grid: 1:00 - 2:00
7. Portfolio work: rest of day