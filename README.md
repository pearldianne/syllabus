* **Course:** [COE11, USTP CEA]
* **Instructor:** Jay L. Ginete, [killer.tilapia@gmail.com](mailto:killer.tilapia@gmail.com)
* **Need help?**
    * [![Gitter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/advanced-js/syllabus?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)
        * It sends message digests to people who aren't active in the room, so feel free to ask a question even if no one's around.
    * Look through and create [issues](https://github.com/advanced-js/syllabus/issues)
    * Office Hours during [Hacker Hours](http://hackerhours.org/) (see [schedule](http://www.meetup.com/hackerhours/events/calendar/))
   * [Email](mailto:alf9@nyu.edu) for 1-on-1 help, or to set up a time to meet

## Course Description

Learn best practices in JavaScript in this intensive, five-session course. Topics include data encapsulation, closures, binding, inheritance, and name spacing. Discover some of the lesser-known, yet useful, features of the language, such as how to debug JavaScript problems on different browsers and improve performance. Create interactive webpages using third-party JavaScript libraries.

Computers are provided in the lab, though you are encouraged to bring a laptop for in-class exercises.

## Prerequisites
* Strong computer skills (ie. can locate folders and use a command line)
* Understanding of variables, data types, control flow, and basic function usage in C
* Basic knowledge of HTML, and at least basics of CSS

These won't be enforced by the instructor, but you will be pretty lost without understanding those concepts. 

## Course Overview

We will be learning how to use object oriented concepts to develop solutions that can be modeled into code. We will be using primarily Python with Java as contrast. Topics to be covered are:

* Class based inheritance
* Encapsulation and Abstraction
* Composition
* Test Driven Development
* Source Versioning

Topics will be demonstrated through live-code examples/slides.  Additional exercises will completed in-class.

## Homework/Projects

All assignments are listed within the [Course Outline](#course-outline).

### Workflow

If you're using GitHub Desktop, these general instructions will help:

* <https://guides.github.com/activities/forking/>
* <https://help.github.com/desktop/guides/contributing/>

#### Versions

For exercises with multiple Versions (`V1`, `V2`, etc.) listed in the README: these are intended as guidelines for how to complete the assignments in the smallest/simplest possible increments.  You are expected to reach the highest Version for each assignment by the due date. 

### Requirements

These apply to real life, as well.

* Must apply "good programming style" learned in class
    * Functions should be "short" (see [Sandi Metz's rules for developers](https://robots.thoughtbot.com/sandi-metz-rules-for-developers)).
    * Optimize for readability.
        * ["Programs must be written for people to read, and only incidentally for machines to execute." -Harold Abelson](https://www.goodreads.com/quotes/9168-programs-must-be-written-for-people-to-read-and-only)
    * For projects, use Object-Oriented Programming.
* Any borrowed code must be properly [annotated](#instructor).

#### Extra Credit

Bonus points for:

* Creativity (as long as requirements are fulfilled)
* Anything listed under `BONUS` in the README of the exercise.

## Course Outline

### Class 1

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">Are you new to front-end web development? Here&#39;s a secret: no one else really knows what they&#39;re doing either.</p>&mdash; Nicolas (@necolas) <a href="https://twitter.com/necolas/status/291978260433219584">January 17, 2013</a></blockquote>
<script async src="//platform.twitter.com/widgets.js" charset="utf-8"></script>

1. Introduction
    * Put name on sticky note on back of monitor
    * Discuss what the class is going to cover
    * Everyone introduce themselves
        * Name
        * What you "do"
        * What are your goals for the class?
        * What's something in JS (or technology) you worry that your peers understand but you don't?
1. Setup
    * How many people are comfortable with Git/GitHub?
    * Install [GitHub Desktop](https://desktop.github.com/)
        * If you are comfortable with Git already, you can skip this.
    * Sign up for GitHub
1. GitHub workflow
    * Walk through [workflow](#workflow)
    * Create pull request on [students repository](https://github.com/advanced-js/students)
1. Explain how slides work
1. Get through `countdown_exercise` slide
1. Talk through [requirements](#requirements)

#### Homework

* Join [the chat room](https://gitter.im/advanced-js/syllabus).
* [Set up your GitHub profile.](https://github.com/settings/profile)
* Access [NYU Classes](https://newclasses.nyu.edu) page, where grades will be posted.
    * [Documentation](https://wikis.nyu.edu/display/nyuclasses/Student+Quick-Start)
* Read [JavaScript Garden](http://bonsaiden.github.io/JavaScript-Garden/).
* Finish up and submit [echo](https://github.com/advanced-js/echo) and [countdown](https://github.com/advanced-js/countdown) exercises.
* Complete [blink](https://github.com/advanced-js/blink) exercise.

### Class 2

1. Look at various approaches for `countdown()`
    * Show recursive solution
1. Developer Tools walkthrough
    * Elements (HTML)
    * Console (JS)
    * Scripts (JS)
1. Pair program to build [Memory v1](https://github.com/advanced-js/memory) (see [pairing tips](#pairing-tips))
1. Cover OOP, though "oop_inheritance" slide
    * [Encapsulation example](http://jsbin.com/baqopu/1/edit?css,js,output)
    * Look at [Backbone.js Events](http://backbonejs.org/docs/backbone.html)

#### Homework

* Read [Mozilla's Introduction to Object-Oriented Javascript](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Introduction_to_Object-Oriented_JavaScript)
* [OOP exercise](https://github.com/advanced-js/oop), through V2
* [Memory v2](https://github.com/advanced-js/memory#v2) (individual)

### Class 3

1. Code review Memory
1. Get through [`oop_inheritance`](http://advanced-js.github.io/deck/examples/oop_inheritance/) slide
1. Cover automated testing
    * Build up a test framework from scratch
    * Examples in QUnit
        * [Simple](http://jsbin.com/woqusi/edit?html,js,output)
        * [Classes](http://jsbin.com/nukamun/edit?js,output)
        * [QUnit documentation](http://qunitjs.com/)
    * Other frameworks
1. Cover AJAX/CORS/JSONP ([files](https://github.com/advanced-js/deck/tree/gh-pages/demos/ajax))
    * Network tab in Developer Tools

#### Homework

* Read [Google JavaScript Style Guide](http://google-styleguide.googlecode.com/svn/trunk/javascriptguide.xml)
* Complete [OOP exercise](https://github.com/advanced-js/oop) through V4.
* [Memory V3](https://github.com/advanced-js/memory#v3)

### Class 4

1. Finish slides
1. Getting Serious example
    * Quick intro to Backbone.js
        * [Boilerplate](http://jsbin.com/IGivato/1/edit?html,js,output)
        * Click the Box [example app](http://jsbin.com/IGivato/5/edit?css,js,output)
        * TDD?
1. Multiple async
    * [Promises](https://github.com/advanced-js/deck/tree/gh-pages/demos/ajax/promises)/[jQuery.Deferred](http://api.jquery.com/jQuery.Deferred/)
    * Possibly show [async](https://github.com/caolan/async#control-flow-1) library?

#### Homework

* [Learn about AJAX](https://github.com/advanced-js/deck/tree/gh-pages/demos/ajax#readme)
* [Mashup](https://github.com/advanced-js/mashup)
* Improve your previous assignments

### Class 5

1. Present and code review Mashup projects
1. Possible topics (vote?):
    * Node.js
        * Server "Hello World" (from [Node.js homepage](http://nodejs.org/))
            * [HTTP module docs](http://nodejs.org/api/http.html)
        * HTTP requests
            * [Status codes](http://pretty-rfc.herokuapp.com/RFC2616#status.codes)
            * Headers
        * CommonJS?
    * [Regular Expressions](https://github.com/advanced-js/deck/tree/gh-pages/demos/regex.html)
        * Convert live input from a text area, e.g.
            * Link Twitter handles
            * Substitute select words for emoji, using [emoji-css](http://afeld.github.io/emoji-css/)
    * Object-Oriented design
    * [Code Retreat](http://coderetreat.org/facilitating/structure-of-a-coderetreat) – possible "problems":
        * [Game of Life](http://coderetreat.org/gol)
        * Tic Tac Toe

## Pairing Tips

* Three people is possible, but two works best
* Agree on an editor and environment that you're both comfortable with
* The person who's less experienced/comfortable should have more keyboard time
* Switch who's "driving" regularly
* Make sure to save the code and send it to both people

## Resources

### Required Reading

* To follow

### Recommended Reading

* To follow

#### Other Lists

* [Code School](https://www.codeschool.com/)
* [Teach Yourself to Code](http://teachyourselftocode.com/)

### Tools

* sharing code snippets: [gist.github.com](https://gist.github.com/)
* asking questions: [Stack Overflow](http://stackoverflow.com/)

#### GitHub

* Git and GitHub
    * [Official GitHub Help](https://help.github.com/)
    * [Recommended resources](http://hackerhours.org/resources.html#github)
* GitHub Pages
    * [Official site](https://pages.github.com/)
    * [Thinkful guide](http://www.thinkful.com/learn/a-guide-to-using-github-pages/)

## Grading

* Homework – 100%

## Statements on Plagiarism

### USTP

> USTP takes plagiarism very seriously and regards it as a form of fraud.  The definition of plagiarism that has been adopted by the School of Continuing and Professional Studies is as follows: "Plagiarism is presenting someone else's work as though it were one's own.  More specifically, plagiarism is to present as one's own words quoted without quotation marks from another writer; a paraphrased passage from another writer’s work; or facts or ideas gathered, organized, and reported by someone else, orally and/or in writing.  Since plagiarism is a matter of fact, not of the student's intention, it is crucial that acknowledgement of the sources be accurate and complete.  Even where there is not a conscious intention to deceive, the failure to make appropriate acknowledgement constitutes plagiarism.  Penalties for plagiarism range from failure for a paper or course to dismissal from the University.

### Instructor

Reuse and building upon ideas or code are major parts of modern software development.  As a professional programmer you will never write anything from scratch.  This class is structured such that all solutions are public.  You are encouraged to learn from the work of your peers.  I won't hunt down people who are simply copying-and-pasting solutions, because without challenging themselves, they  are simply wasting their time and money taking this class.

Please respect the terms of use and/or license of any code you find, and if you reimplement or duplicate an algorithm or code from elsewhere, credit the original source with an inline comment.
