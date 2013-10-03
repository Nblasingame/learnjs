![books](http://learnjs.io/img/books/four-books.png)

# Learn.js
> A series of guidebooks to building javascript projects.

The original Learn.js book started to get big and mushy and confusing, and I realized that what I really needed to do was create a series of smaller books, so that's what I'm working on now.

The original book is now split up into 4 books:

- [Development Environments for Beginners](http://learnjs.io/books/dev-envs/)
- [Learn.js #1: introduction to javascript](http://learnjs.io/books/learnjs-01/)
- [Learn.js #2: making 2d games with node.js and browserify](http://learnjs.io/books/learnjs-02/)
- [Learn.js #3: mapping with leaflet.js](http://learnjs.io/books/learnjs-03/)

Books #2 and #3 will be released in November. You can [buy the 4-book bundle early](http://learnjs.io/) at a discount and get updates to all books for free.

Interested in seeing Learn.js #4 be a specific topic? Let me know at seth@superbigtree.com.

You can purchase the books at [learnjs.io](http://learnjs.io).





Here's the original Learn.js book left in it's WIP form:

# Introduction 

## Thank you. 

You believed in this project enough to get involved early, and your support is making it possible. The first release of _Learn.js_ went out on May 23, 2013. If you've purchased the book you are a serious early adopter, and that's awesome.

Because you got the book so early, you're in a unique position to guide the direction of the book. If there are particular libraries, development tools, or programming patterns that you'd like to see covered, please submit your thoughts at the learnjs issue queue on GitHub, or email me at hi@learnjs.io.

This book is highly inspired by the lean publishing model ([read more about it](https://leanpub.com/manifesto)) proposed by Peter Armstrong, founder of leanpub.com. I'm releasing the book early to get feedback from you, dear readers, so that together we can make the best book about javascript tools and libraries possible.

I'll be releasing updates semi-weekly up until the book is feature-complete at v1.0.0. Help me determine what it will mean for the book to be feature-complete by letting me know what development tools, libraries, and programming patterns you'd be most interested in seeing covered.

The goal: produce a book of roughly 200 pages by the end of July. You're a big part of making that goal real. Thank you.


## Target audience
This book is meant for javascript beginners, but will be useful for anyone that wants to broaden their understanding of javascript. Maybe you've written with jQuery for years and want to get an introduction to server-side code, mapping, or data visualization. Or maybe you've created client-side applications without the use of any development tools like bower, browserify, or grunt, and you want to streamline your development process.

_Learn.js_ will introduce you to a wide range of tools and libraries, and whether you're a beginner or intermediate programmer, you're likely to find helpful material.

## Development tools
The development tools for javascript have changed rapidly in recent years, and the popularity of server-side javascript has matured tools available for client-side developers.

Learning development tools is one of the most difficult parts of starting to work with a programming language. 

Which tools should I use? Are there best practices for workflows? How should I test code?

There are many possible answers to the above questions, and this book won't give all of them, but because it will be a living document that is revised based on changing patterns and practices in the javascript world, we'll be able to create a guide that remains relevant.

### Development tools the book will cover:
- npm, the package manager for node.js, which is also often used for client-side javascript modules.
- bower and component, two package management tools for client-side javascript.
- browserify, a tool for bundling client side code as node-style modules.
- grunt, a build tool that can automate repetitive development tasks.
- Chrome developer tools.
- Git and GitHub. This book won't be a full guide to git, but it will help you improve as a git user.
- Vagrant and Virtualbox. Using these tools you can set up an instance of a linux operating system on your Mac or Windows machine and interact with it from the command line.
- Phonegap/Cordova. This project allows developers to create mobile apps for multiple platforms based on one js/html/css codebase.
- Hosting using Heroku and GitHub pages.
- And other tools. [Let us know what you'd like to see covered](http://hi@learnjs.io).


## Libraries
There are many different libraries available to javascript developers. It takes time just to learn how to find and use javascript libraries, how to tell which libraries will be effective and reliable, and when not to use a library.

We'll show you the best places to look for javascript libraries, the best resources for keeping track of new releases of libraries, and where to go when you need help learning a new library.

_Learn.js_ will cover client-side libraries as well as node.js modules, and explore opportunities for using libraries that work on both the client and the server.

### Some of the javascript modules/libraries the book will cover:
- browserify
- request
- express
- leaflet.js
- d3.js
- crtrdg.js
- voxel.js
- backbone
- angular
- polymer
- And other libraries. [Let us know what you'd like to see covered](http://hi@learnjs.io).

## Programming patterns
Javascript is a very flexible language that can be employed using a number of styles and patterns. In this book we'll take a look at some of the most popular patterns, and develop a simple, clean coding style based on popular open-source style guides already available in the community.

### Some coding styles and programming patterns the book will cover:
- CommonJS and ECMAScript 6 modules.
- Functional programming.
- Prototypal inheritance.
- Constructors.
- And other patterns. [Let us know what you'd like to see covered](http://hi@learnjs.io).


# Code used in this book:

You'll find finished examples of all projects in this book on GitHub.

## Project repositories:
- [node-rogue](https://github.com/learn-js/node-rogue)


# THE BASICS

## In this section, we'll get started learning:

### Chrome's Developer Tools
All browsers include tools for evaluating, debugging, and auditing your code and your site's performance. This section will introduce you to the tools offered in the browser Chrome, and later in the book we'll go into these tools in more detail.

### Basic html and css
For many of our projects in this book, html and css will be kept as minimal as possible. This refresher will get you up to speed if you haven't worked with css or html much before.

### Javascript syntax, variables, data types, functions, and style guidelines
Here we'll go over the basic parts of javascript. We'll cover the equivalents of a programming language's grammar and punctuation, as well as the basic building blocks of javascript: strings, numbers, booleans, arrays, objects, and functions. We'll also briefly explore style guidelines for writing javascript that help will ensure your code is readable and maintainable for you and others.

### Node.js and npm
Server side javascript is a seriously awesome thing, and while this book will only give an introductory look at what's possible, we'll be using many command line tools based on node.js that are installable using `npm`, node's package manager.

### Bower, browserify, and grunt
The command line tools we'll use most commonly in this book are bower, browserify, and grunt. Bower is a package manager for client-side javascript and css. Browserify is a tool that allows us to organize javascript in modules that work the same as node.js modules (and we can even use node modules in our browser code). Grunt is a build tool we'll use to automate repetitive tasks in javascript development. We'll combine bower, browserify, and grunt in the more complicated projects for awesome automation of our code.

### Git and GitHub
Git is a tool for tracking, sharing, and collaborating on versions of your code, and GitHub is the defacto resource for hosting code online. These are essential tools for anyone working on the web, and we'll use them in every part of the book.

### Testing javascript
Writing tests for your code does two things: ensure your code works as expected when changes are made, and provides examples of usage of your project. When applicable we'll write the tests for a project first, before writing the code that does the real work, and we'll describe later why this is a useful workflow.


# Hello, javascript. It's nice to meet you.

```
console.log('hello, javascript. it's nice to meet you');
```

Open up the browser Chrome.

> If you don't already have Chrome installed, download and install it now at [google.com/chrome](http://google.com/chrome)

Now, use this keyboard shortcut on a Mac: command + option + j
Or this for Windows/Linux: control + shift + j

You just opened the javascript console.

**Type in this code:**  
```
console.log('what is this?');
```

You just told the javascript console to print some text!

Any time you put `console.log()` in javascript code that is ran in the browser, whatever you put between the parentheses will show up in your browser's javascript console.

As you learn javascript, `console.log()` will be your best friend. You will use it to help prototype new functionality and to debug your code.

## Your first challenge:

Type this into the console:

```
console.error('this is an error');
```

That's an error! Note how it shows up in red. Look in the bottom right corner of the browser. You'll see a little red circle with an x in the middle, and a number on its right side. That's a helpful little indicator of errors in your javascript, and any time something is wonky with your code that red circle will show up.

With most errors you'll also be able to see a line number from your javascript file, which will help you pinpoint the offending code. We'll get into errors and debugging in more detail later in the book.

## Chrome Developer Tools
The javascript console is just one of the tools available for web development inside of Chrome. For this book we will focus on using Chrome and its developer tools for two reasons: Chrome has a a set of versatile and powerful tools, and focusing on the tools of one browser helps keep the instructions simple.

Expect to learn more about Chrome's Developer Tools throughout the book. Check out the [Browser Developer Tools](TODO) section in the appendix for more information about similar tools in other browsers and more resources for learning about these types of tools.

## Recap! We learned that:
- the javascript console and learned that we can type in javascript!
- we can use code like `console.log()` and `console.error()` to print information to the console.
- Chrome has a lot of useful tools, and later in the book we'll learn how they can help with experimenting with code, auditing the performance of our site, investigating the information sent between the browser and the server, and more.


# HTML & CSS: an introduction

If you're new to building projects for the web, knowing javascript alone won't be enough.

This book focuses on javascript, but you'll certainly pick up some html and css along the way.

You might find it useful to learn about html and css before reading Learn.js, or to have a resource handy that you can refer to when introduced to new html elements or css properties.

## But here's a quick refresher to get you started:

An example of an html element:

```
<h1>This is a headline</h1>
```

That's an `h1` element. It is used for the most prominent headline of a document – often the site title or article title. Note that this element has an opening tag, `<h1>, and a closing tag, `</h1`>, which looks the same except it has a forward slash, `/`.

This is a common pattern for html elements. There are a few html elements that don't require closing tags. Like these:

```
<br>
```

The `br` element creates a line break in text.

```
<hr>
```

The `hr` element creates a horizontal rule, a straight line, across your web site. Usually used as a break between sections.

```
<img src="image.jpg" alt="this is the alt text of an image" />
```

The `img` element is a little unique. Note that it has a `src` attribute that specifies the image we want to have show up, and an `alt` attribute that provides text that will be displayed for screen readers, or that might be used as a caption. The `img` element is also a self-closing tag, meaning it has a forward-slash before the closing angle bracket.


## HTML attributes and CSS selectors.
We just saw the `src` and `alt` attributes on the `img` element. There are many attributes that can be used on any given html element. Some attributes control behavior of the element, some are used as selectors for css rules.

**Here are the two attributes most used as selectors in css rules:**

### `id`

Using the `id` attribute of an html tag looks like this:

```
<p id="introduction">This is the first paragraph of a story.</p>
```

Here we're marking a paragraph (a `p` element) as being the introduction. The `id` of `introduction` should only be used on one html element, making this one `p` element special.

We do this so that later, in the css, we can give the `introduction` different styling than the rest of the `p` elements on the page.

Here's some css that makes the `introduction` italic:

```
p#introduction {
  font-style: italic;
}
```

We don't have to include the `p` in `p#introduction`, but it's useful for clarity. Note the hash mark: `#`. `id` attributes are identified in css by using a `#`.

### `class`
Now, let's say that we want some of the paragraphs in our story to have a different background color to highlight them. One way of accomplishing this would be to add a `class` to these paragraphs.

The use of `class` attributes looks like this:

```
<p class="highlight">This paragraph will be bold and slightly bigger.</p>
```

We've given this `p` element a class of `highlight`, so let's add some css that gives this paragraph a yellow background.

```
p.highlight {
  background-color: yellow;
}
```

One of the differences between `id` and `class` attributes, is that a `class` can be given to multiple elements on a page, whereas an `id` should be unique to one element. So we can give this class to multiple paragraphs to make them highlighted.


### Where does the css go?
There are two options: include separate css files, or place css directly in your html file. In almost all situations, including a separate css file for your styles will be a faster and more organized option.

Here's what it looks like to embed css in your html file.

```
<!DOCTYPE html>
<html>
<head>

  <title>Your website</title>

  <style>

    p.highlight {
      background-color: yellow;
    }

  </style>

</head>
<body>

</body>
</html>
```

You'll add your css between the opening and closing `style` tags, which should in turn go between the opening and closing tags of the `head` element.

But the cleaner option is to create a separate css file that you reference from your html file:

```
<!DOCTYPE html>
<html>
<head>

  <title>Your website</title>

  <link rel="stylesheet" href="style.css" />

</head>
<body>

</body>
</html>
```

This tells the browser to load the css from the `styles.css` file. Having a separate file for your styles helps with keeping your site easy to maintain. Having everything in one big html file can be a pain to work on.

### So where will the javascript be in an html file?

Just as with css, there are a couple options for where you place your javascript code.

You can embed it in your html file between opening and closing `script` tags:

```
<!DOCTYPE html>
<html>
<head>

  <title>Your website</title>

</head>
<body>


<script>
console.log('this is javascript');
</script>

</body>
</html>
```

Or you can use a `script` tag to reference an external javascript file:

```
<!DOCTYPE html>
<html>
<head>

  <title>Your website</title>

</head>
<body>


<script src="site.js"></script>

</body>
</html>
```

Note that the `script` element needs a closing tag even though there's nothing between the opening tag and closing tag.

Just like with css, it's better to keep your javascript in a separate files. By separating the types of code in your project you make it easier for yourself and for others to figure out how to make changes. The more organized your project is, the quicker you can revise its design and functionality.

### Layout with html and css
There are a few common tags used for laying out an html document. Check out this example:

```
<!DOCTYPE html>
<html>
<head>

<title>Your website</title>

</head>
<body>

<header>
    <h1>Your website</h1>
</header>

<main>
  <p>This is the content of your website</p>
</main>

<footer>
  <p>Contact: your info.</p>
</footer>

</body>
</html>
```

We're using the `header` element for the header of the page, the `main` element for the content of the page, and the `footer` element for supplementary information that goes in the footer. All three of these tags are relatively new as part of html5. Another new tag is 'section'. You might use it to break up your main content into parts:

```
<main>
  <section id="part-one">
    <h1>Section one</h1>
    <p>This is the content of the first section</p>
  </section>

  <section id="part-two">
    <h1>Section two</h1>
    <p>This is the content of the second section</p>
  </section>
</main>
```

The `section` element is for breaking up your web page into distinct sections. Note that I've got `h1` tags in each of the sections as headers. In html5 anytime you create a new `section` you're allowed to start a new heirarchy of header tags.

Where `section` elements are for specifying blocks of content on your page in a semantic way, 'div' elements are used primarily for the positioning and alignment of your content. For example, you might want to use a `div` to act as a container that restricts the width of your content:

```
<section id="part-one">
  <div class="container">
    <h1>Section one</h1>
    <p>This is the content of the first section</p>
  </div>
</section>
```

With css like below you can have the `section` tag the full width of the page while the container stays centered at 800 pixels.

```
.container {
  width: 800px;
  margin: 0px auto 0px auto;
}
```

The `div` is centered by using `auto` for the left and right margins (the order goes top, right, bottom, left).

### More resources
This gives you an intro to some of the html and css concepts we'll use most often in the book. 

#### To learn html and css in more depth, check out these resources:
**[Don't Fear The Internet](http://www.dontfeartheinternet.com/)**  
This is a wonderful introduction to html and css. Watch, enjoy, and follow along.

**[Web fundamentals track at codecademy.com](http://www.codecademy.com/tracks/web)**  
After you've had your fears eased by Don't Fear The Internet, check out the codecademy.com web fundamentals course. It'll get you some nitty gritty experience with the basics.

**[Mozilla Documentation](https://developer.mozilla.org/en-US/)**  
Have a question about some css property or html element? The Mozilla Developer Network has awesome documentation. If you're searching on google.com for anything css/html/js related, add the abbreviation "mdn" to your search query to see results from Mozilla Documentation. This site also has a bunch of introductory tutorials that are really useful.

**[WebPlatform.org](http://www.webplatform.org/)**  
This is a newer resource, but a good one. It's got a great design and well-organized resources.



# Introduction to the terminal

Get excited, it's time to use the terminal.


## Mac / Linux

For most purpose, daily activity in the terminal will be the same in Mac and various Linux distros.

Basic commands include:

Changing directory:

```
cd path/of/directories
```

`cd` on its own, or `cd ~` will take you to your home directory.

Create a directory:

```
mkdir directory-name
```

Show the directory you're currently in:

```
pwd
```

List the files in the directory:

```
ls
```

List the files in a more readable way, with useful information like permissions included:

```
ls -al
```

Open a file with its default application:

```
open filename
```

Open current directory in the finder:

```
open .
```

or open some other directory:

```
open path/to/directory
```

Create an empty file if it doesn't already exist:

```
touch file-name
```

Open and edit a file with the simple nano editor:

```
nano file-name
```

Move a file or directory:

```
mv file new/path/to/file
```

Rename a file or directory:

```
mv file new-file-name
```

Copy a file:

```
cp file name-of-file-copy
```

Copy a directory

```
cp -R directory directory-copy
```

The `-R` option allows for recursive copying of files inside the directory.


Delete a file:

```
rm file-name
```

Delete a directory and its contents:

```
rm -rf path/to/directory
```

Never do this:

```
rm -rf /
```

Be very careful with the rm command. You can easily delete things on accident.

Clear the terminal screen of previous activity:

```
clear
```

Reset the terminal:

```
reset
```





## Windows

> This section of the book is still a work in progress. Make suggestions at [github.com/learn-js/learnjs/issues](http://github.com/learn-js/learnjs/issues).


# Introduction to git & GitHub

Developing websites and applications without using git is equivalent to writing in Microsoft Word without ever saving your work.

**Use git.**

Git is a version control system, which means it can track every change you make to your code. This allows you to review and edit past versions if you mess something up. And it allows you to figure out when errors were introduced to the code.

There are many other bonuses to using git, which are mostly out of this book's scope.

The best way to start learning git (and GitHub) is to visit [try.github.com](http://try.github.com). You should also try [githug, a game for learning git](https://github.com/Gazler/githug).

## Here are some basics of using git:

Create a git repository:

```
cd name-of-folder
git init
```

Add files:

```
git add name-of-file

// or add all files in directory:

git add .
```

When you add files to a git repository they are "staged" and ready to be committed.

Remove files:
```
git rm name-of-file

// force removal of files:

git rm -rf name-of-file-or-directory
```

Commit files and add a message using the `-m` option:

```
git commit -m 'a message describing the commit'
```

Create a branch:

```
git branch name-of-branch
```

Checkout a branch:

```
git checkout name-of-branch
```

Shortcut for creating a new branch and checking it out:

```
git checkout -b name-of-branch
```

Merge a branch into the master branch:

```
git checkout master
git merge name-of-branch
```

Add a remote repository:

```
git remote add origin git@github.com:yourname/projectname.git
```

List associated repositories:

```
git remote -v
```

Pull changes from a remote repository:

```
git pull origin master
```

Push changes to a remote repository

```
git push origin master
```

Checkout a remote branch:

```
git checkout -t origin/haml
```

## Get on GitHub
If you haven't already, create an account at [github.com](http://github.com).

GitHub is a great place to host your code. Many employers hiring for developer and designer positions will ask for a GitHub profile, and they'll use your GitHub activity as part of the criteria in their decision-making process.

In fact, if you're looking to get a job with a particular company, try to find _their_ GitHub profile and start contributing to their open source projects. This will help you stand out, and they'll already know your technical abilities based on your open source contributions. That's a big win.

GitHub has become the de facto code hosting service for most open source communities.

### With GitHub Pages you can:
- design a website any way you want by having complete control over the html, css, and javascript.
- use simple templates for getting started using GitHub Pages.
- create sites for yourself and all of your projects hosted on GitHub.
- use a custom domain name if you want!

Visit the [help section for GitHub Pages](https://help.github.com/categories/20/articles) to learn more details about hosting sites on GitHub.


## Create a site for yourself using GitHub

GitHub has a useful service called [GitHub Pages](http://pages.github.com) that allows you to host a simple site on their servers for free.

To get started, fork this simple template: [github.com/maxogden/gh-pages-template](https://github.com/maxogden/gh-pages-template).

Visit that github project, make sure you're logged in, and click Fork in the upper right side of the screen.

Fork gh-pages-template to your personal account.

Rename the repository from gh-pages-template to whatever you want by clicking on Settings on the right side of your fork of the repository, and changing the name there. GitHub will warn

That's it! You now have a website hosted through GitHub Pages.

You'll be able to visit your site at __YOUR-USERNAME__.github.com/__YOUR-PROJECT-NAME__.

You'll want to edit the content though, right? Add your cat pictures or resume or pizza recipes? You can do that.

You can create, edit, move, rename, and delete files all through the GitHub website. Check out these blog posts on GitHub for details on how to do those things:
- [Create files](https://github.com/blog/1327-creating-files-on-github)
- [Edit files](https://github.com/blog/143-inline-file-editing)
- [Move and rename files](https://github.com/blog/1436-moving-and-renaming-files-on-github)
- [Delete files](https://github.com/blog/1545-deleting-files-on-github)

You can also clone the project repository onto your computer:

```
git clone git@github.com:__YOUR-USERNAME__/__YOUR-PROJECT-NAME__.git
```

You can copy the git url to clone from the right-hand sidebar of your project repository.

After cloning the repository, `cd` into it and make some changes:

```
cd __YOUR-PROJECT-NAME__
nano index.html
```

Add a bunch of content to index.html, and change the styles in style.css.

After you've made some changes, add them to the repo and commit the changes:

```
git add .
git commit -m 'include a brief, clear message about the changes'
```

Now, push your changes back to GitHub:

```
git push origin gh-pages
```



> This section of the book is still a work in progress. Make suggestions at [github.com/learn-js/learnjs/issues](http://github.com/learn-js/learnjs/issues).







# Introduction to node.

Node.js is server-side javascript. It is well-suited to real-time applications and systems that are heavy on input and output. You can use it to create web servers, to manage information in databases, to build real-time communication tools, and more.

## In this book, we'll use node in these ways:
- Install command line tools available through node's package manager, `npm`.
- Create basic web servers to serve static content to our web browser.
- Experiment with real-time, multi-user applications.

## To learn node in detail, read these resources in this order:
- [art of node](https://github.com/maxogden/art-of-node)
- [streams handbook](https://github.com/substack/stream-handbook)

## Install node:

There are a few options for this, and I've put them in my order of preference:

### Use nvm to manage node versions.
This option gives you the most control, allows you to switch between versions of node similar to using rvm or rbenv for Ruby. [Get nvm here](https://github.com/creationix/nvm). This is the method I use, and the one I recommend.

### Install using a package manager. 
This is a good option, but sometimes package managers can be out of date. If the node version you'll be using matters for your project, you should make sure that the version in the package manager works for you. [Check out a list of package manager instructions here](https://github.com/joyent/node/wiki/Installing-Node.js-via-package-manager).

### Download an installer from nodejs.org.
[Here's the node.js download page](nodejs.org/download).

Installing node gives us the node package manager `npm`. We'll use it to install a wide range of packages, including web frameworks, game dev libraries, and client-side javascript modules. 

> This section of the book is still a work in progress. Make suggestions at [github.com/learn-js/learnjs/issues](http://github.com/learn-js/learnjs/issues).


# Introduction to npm

You use `npm` to install javascript modules. It is most often used for installing node.js modules, but it is not limited to server side code.

You might expect `npm` to stand for Node Package Manager. But that's misleading – it reinforces the idea that `npm` is just for node.js projects.

Instead, we can follow the guidance of javascript developer Max Ogden and let is stand for Node Packaged Modules.

Read more about this idea on his blog post: [maxogden.com/node-packaged-modules.html](http://maxogden.com/node-packaged-modules.html), where he presents three projects based on the tool `browserify`. We'll make heavy use of browserify in the book.

## Getting started with `npm`
If you've alreadt installed node.js, you've got npm.

Check the version of `npm` like this:

```
npm -v
```

This should return something like:

```
1.2.32
```

The exact version numbers might differ, and that's ok.

Installing a module will automatically place the module in a folder named `node_modules` in your current working directory.

Make a new folder:

```
mkdir npm-experiments
cd npm-experiments
```

Install browserify:

```
npm install browserify
```

Now, if you look in the node_modules directory, you'll see browserify!

You can also install modules globally, typically so that you can run their commands at any time in any directory. This is useful with a module like browserify, so let's try it out:

```
npm install -g browserify
```

It's the `-g` option that install the module globally.

You can delete the node_modules directory:

```
rm -rf node_modules
```

And run the browserify command:

```
browserify
```

Without any options it'll only return help text. For more about browserify, check out the Introduction to browserify section.

To learn more about `npm` run the command without any options:

```
npm
```

This gives you a full list of the commands and options available through `npm`. To learn about any particular command you can run:

```
npm help name-of-command
```

## Creating a module
Any time you're using javascript modules from `npm` in a project you should create a package.json file. In this file you can save the dependencies for your project, along with license, author, repo inforamtion, and other details.

You can use the `npm init` command to generate a package.json file:

```
npm init
```

Answer the questions.

When you're done, you'll have a package.json file. You can install modules and save them as dependencies of your project like this:

```
npm install request --save
```

And if you are installing a module (like a test framework) as a development dependency, you can do so like this:

```
npm install tap --save-dev
```

## Publishing modules
Once you've written a module, you can publish it to `npm` super easy:

```
npm publish .
```

Before running the `npm publish` command you'll want to edit your package.json file to make sure that properties like version, author, homepage, and repository are all filled in. You should also first create a useful readme.md file, as that is displayed on a modules project page on [npmjs.org](http://npmjs.org).

## Finding modules
You can check out [npmjs.org](http://npmjs.org) as well as [npmsearch.com](http://npmsearch.com) to find modules that you can use in your projects.

You can also run the `search` command in the terminal:

```
npm search template
```

This will return a bunch of modules related to templates!


# Introduction to browserify.

There's all this wonderful code on `npm`, the node.js package manager.

What if we could use that code in the browser?

## Hey, we can. Use browserify.

With [browserify](https://github.com/substack/node-browserify), we can use some core node modules and many of the thousands of modules on `npm` in our browser-side code.

We can also write our browser-side javascript in the node.js style by using `require`.

Install browserify:

```
npm install -g browserify
```

We use the `-g` option to install browserify globally on your machine, allowing you to use it on the command line.

### Brief example:

```
// require the core node events module
var EventEmitter = require('events').EventEmitter;

//create a new event emitter
var emitter = new EventEmitter;

// set up a listener for the event
emitter.on('pizza', function(message){
  console.log(message);
});

// emit an event
emitter.emit('pizza', 'pizza is extremely yummy');
```

Put the above code in a file named index.js.

Now, to be able to run this code in the browser, enter this command in the terminal:

```
browserify index.js > bundle.js
```

The bundle.js file now has your event emitter code along with any dependencies on core node modules and shims to make them work in the browser.

You can include bundle.js in your html now like any other javascript file.

Example:

```
<!DOCTYPE html>
<html>
<head>
  <title>node / browserify example</title>
</head>
<body>

<script src="./bundle.js"></script>
</body>
</html>
```

That's it! Now you can use node modules and `require` in the browser!

## Live reload development environment
If you're in the middle of writing code, you'll find running `browserify` in the terminal to regenerate bundle.js, then refreshing the browser to be time-consuming and annoying.

**Enter beefy!**

`beefy` is a command-line tool for automatically generating and serving your browserify bundles as you develop. Each time you save your javascript file `beefy` will regenerate bundle.js and refresh the browser automatically.

Install beefy:

```
npm install -g beefy
```

Now, run this:

```
beefy index.js:bundle.js --live
```

The `--live` option enables the live reload functionality of beefy.

This will by default serve your index.html file at http://localhost:9966. Open Chrome, enter that url, then open the javascript console by using the keyboard shortcut `command+option+j`.

You'll see `pizza is extremely yummy` in the javascript console!


# Introduction to grunt.js

Grunt is a tool for managing the javascript, css, and html files of your web project. Grunt is a task manager similar to Ruby's `rake`. You can run any arbitrary tasks you want, and there are a number of grunt plugins that make it easy to set up common tasks. Grunt is useful for running tests or for build steps, including turning sass, stylus, or less files into css, concatenating files, or creating .zip or .tar.gz packages of your project.

### Outline of the steps in this tutorial:

-   Install node.
-   Install grunt-cli.
-   Setup project.
-   Set up package.json.
-   Create Gruntfile.js.
-   Run grunt tasks.
-   Make an awesome project.

### Install node:

There are a few options for this, and I've put them in my order of preference:

**Use nvm to manage node versions** This option gives you the most control, allows you to switch between versions of node similar to using rvm or rbenv for Ruby. [Get nvm here](https://github.com/creationix/nvm).

**Install using a package manager.** This is a good option, but sometimes package managers can be out of date. If the node version you'll be using matters for your project, you should make sure that the version in the package manager works for you. [Check out a list of package manager instructions here][https://github.com/joyent/node/wiki/Installing-Node.js-via-package-manager].

**Download an installer from nodejs.org.
**[Here's the node.js download page][nodejs.org/download].

Installing node gives us the node package manager `npm`. We'll use it to install grunt-cli, which is the command-line tool that is used to run grunt tasks. 

**Run this in your terminal after installing node.js:**

```
npm intall -g grunt-cli
```

This installs the grunt command-line tool globally on your machine. Now you can run the `grunt `command!

And, it won't do anything.

Bummer. **But it will give you a message like this**:

```
grunt-cli: The grunt command line interface. (v0.1.6)
  Fatal error: Unable to find local grunt.
  If you're seeing this message, either a Gruntfile wasn't found or grunt hasn't been installed locally to your project. For more information about installing and configuring grunt, please see the Getting Started guide: [http://gruntjs.com/getting-started](http://gruntjs.com/getting-started)
```

The grunt command looks for a locally installed version of grunt, which you can include in your project as a development dependency in a package.json file.

### Hey, package.json files are cool.

You can use a package.json file for a lot of useful purposes. Primarily, it's used to list your project's dependencies on npm packages, as well as list the name, description, version, and source repository of the project. You can specify the type of license, version of node the project requires, the project's contributors, and more. Check out [this interactive package.json cheatsheet][http://package.json.nodejitsu.com/] for a nice rundown on the basics.

So, our package.json will specify some development dependencies. 

**Some basic requirements:**

- We'll test the javascript with qunit.
- We'll write scss and compile it to css, then minify the css.
- We'll concatenate and uglify our javascript files.
- We'll use the `grunt watch` command to automatically run grunt tasks when files are edited.
- We'll want a little http server to check out our game as we're developing it. 

Some of the above requirements could be perceived as excessive, but they help make this a meaty and useful tutorial, so deal with it.

**So, we'll need to use some grunt plugins. We'll use these ones:**

- [grunt-contrib-qunit][https://github.com/gruntjs/grunt-contrib-qunit]
- [grunt-contrib-jshint][https://github.com/gruntjs/grunt-contrib-jshint]
- [grunt-contrib-connect][https://github.com/gruntjs/grunt-contrib-connect]
- [grunt-contrib-watch][https://github.com/gruntjs/grunt-contrib-watch]


**That means our package.json file will look like this:**

```
{ 
  "name": "your-project-name", 
  "version": "0.0.1", "author": "Super Big Tree <seth@superbigtree.com>", 
  "description": "A silly game.", 
  "repository": { 
    "type": "git", 
    "url": "https://github.com/your-profile/your-project-name.git" 
  }, 
  "devDependencies": { 
      "grunt": "~0.4.0",
      "grunt-contrib-qunit": "~0.2.0",
      "grunt-contrib-jshint": "~0.1.1",
      "grunt-contrib-connect": "~0.1.2",
      "grunt-contrib-watch": "~0.4.4"
}, 
 "license": "MIT", 
 "engines": { 
 "node": ">=0.8" 
 } 
}
```

**Go to your terminal. Create a folder that you want to serve as the project's folder:**

```
cd wherever/you/want/the/project/to/live
mkdir your-project-name
cd your-project-name
```

Now, create your package.json file:

```
touch package.json
```

Copy and paste the above package.json example into your package.json file using your favorite text editor. Save the file. **Now, you can run
this:**

```
npm install
```

to install all the dependencies.

If you run the command and get an error like this at the end, then something is not ok:

```
npm ERR! not ok code 0
```

There's an error of some kind that will need to be worked out. For me, typically the problem is that I messed up the syntax or put the wrong version number for a dependency, so check things like that first.

### Project setup:

Let's make all our files and folders now!

**This will make all the folders we want:**

```
> mkdir -p test js css/scss img
```

**This will make the files we want:**

```
touch js/player.js js/game.js js/enemies.js js/ui.js \
touch css/scss/main.scss css/scss/reset.scss css/scss/ui.scss \
touch test/player.js test/enemies.js test/game.js test/ui.js
```

Cool. Did that. **Now we make the Gruntfile:**

```
touch Gruntfile.js
```

**Open Gruntfile.js in your favorite editor and paste in this:**

```
module.exports = function(grunt) {
  grunt.initConfig({
    // and here we do some cool stuff
  });
};
```

The above code is the required wrapper code to make a Gruntfile work. Now, remember our package.json file. Buds, we can use the values from that file in our Gruntfile.

**Check it out: **Let's say we're making a javascript library and want to put stuff like the name, version, author, source repository, and license of the project in a multi-line comment at the top of the file. It would be a bummer to have to edit that by hand every time the file is compiled for a new release. Instead, we can use values from package.json in our Gruntfile!

First step is to read the contents of package.json by **putting this line in Gruntfile.js**:

```
pkg: grunt.file.readJSON('package.json');
```

A package.json file is just JSON, right? Yeah, so it's easy to get at the values to do cool stuff.

For fun, let's see what it takes to run a custom task inside a Gruntfile, and have it log some attributes from the package.json file. Alright? OK.

This is a really simple task that logs the package name and version to the console, shown here as the complete Gruntfile.js:

```
module.exports = function(grunt) {
  grunt.initConfig({
    // read the json file
    pkg: grunt.file.readJSON('package.json'),

    log: {
      // this is the name of the project in package.json
      name: '<%= pkg.name %>', 

      // the version of the project in package.json
      version: '<%= pkg.version %>' 
    }
  });

  grunt.registerMultiTask('log', 'Log project details.', function() {     
    // because this uses the registerMultiTask function it runs grunt.log.writeln()     
    // for each attribute in the above log: {} object     
    grunt.log.writeln(this.target + ': ' + this.data);   
  });
};
```

**You can now run your task on the command line!:**

```
grunt log
```


**You should get output like this:**

```
Running 'log:name' (log) task 
name: your-project-name
Running 'log:version' (log) task
version: 0.0.1
Done, without errors.
```

If you didn't get output like that, check your Gruntfile for typos. If you did get output like that: Awesome! So we've made it pretty far. We've set up a project with a bunch of files and folders, created a package.json file with a list of devDependencies, installed the dependencies, and tried out a simple Gruntfile for running arbitrary tasks.

If this seems like a lot, like it's beating up your brain, don't worry. After a few times of starting a project like this, these initial steps will get faster and easier. Heck, you might even create some kind of base project that you can build on with each new project so that you don't have to write the boilerplate every time. Or you could use a project like yeoman for its code generators. That's up to you, but when first learning this it's a reasonable idea to start from scratch and see how everything works.



# Introduction to functions.

## Eating, digesting, and pooping.

A function is a block of code that takes input, processes that input, and then produces output.

You can think of it like eating, digesting, and pooping.

And when we use a number of functions in succession, it's almost like that movie [The Human Centipede](http://www.imdb.com/title/tt1467304/), only less gross.

## Let's make a function named `eat`.

```
// take input / eat food
function eat(food){
  
  // process the input / digest the food
  var poop = digest(food);

  // send output / poop
  return poop;
}
```

The above example should make sense just from reading it.

Note that lines that start with `//` are comments, and they get ignored when the code is executed.

To create a function, we first write `function`. Next, we can name the function, and in this case it is named `eat`.

Inside of the parentheses we specify the input, which are also called arguments. We only have one argument in this case, named `food`.

Next, we use an opening curly bracket to indicate the beginning of the block of code connected with this function.

We create a variable named `poop`, which contains a "digested" form of the `food` argument. Here we're using another function named `digest` that is using the `food` argument as its own input. 

Finally, we `return poop;` so that the output of this function can be used in other parts of our code.

## Using the `eat` function:

We can use the `eat` function like this:

```
eat('pizza');
```

When we run this, it'll return something like `zpzia`, `apizz`, or `pzazi`.
You know, something random like that.

### So what is the `digest` function doing?

You've probably already guessed that it is a function that randomly shuffles letters in a string. In actual production projects you would want to name it something a little more clear, like`shuffleLetters()`.

Here's an example of the `shuffleLetters()` function using our food/poop language:

```
function digest(food){
  var food = food.split('')
  var digesting = food.length, digested, randomFoodPart;

  while (digesting) {

    randomFoodPart = Math.floor(Math.random() * digesting--);

    digested = food[digesting];

    food[digesting] = food[randomFoodPart];

    food[randomFoodPart] = digested;
  }

  var poop = food.join('');

  return poop;
}
```

_Adapted from [Mike Bostocks's Fischer-Yates Shuffle](http://bost.ocks.org/mike/shuffle)._

You're probably aware that this `digest` function is doing the heavy lifting, while the `eat` function is just a wrapper around `digest`.

If you were really modeling eating, digesting, and pooping using javascript functions, how would you do it?

---

## Let's get more in-depth with functions: write a function that adds numbers, and make it awesome.

### Our goals for this section are simple:
- Get familiar with javascript syntax and data types.
- Write a function that does one task really well.
- Try out the Chrome javascript console
- Learn about debugging and refactoring code.

We'll be writing a function that adds numbers. Simple. Almost too easy. But think about it as if you were building a calculator. You'll need functions that add, subtract, multiply, and divide, and depending on the complexity of the calculator, maybe even more than that.

Our goal will be to create an add function that could be reused in various ways throughout our imaginary calculator program. We'll only make `add`, but if you want to experiment and actually make a calculator, that would be awesome! [Let me know how it goes](mailto:hi@learnjs.io).

### Writing javascript on paper.

**You want to write javascript? OK, here's what we'll do:**

- Take out a sheet of paper and a pen.
- Write the following on the paper:

```
var x = 1;  
var y = 2;  
var z = x + y;  
```

- Think about how easy this is and how it's awesome that you're coding with javascript on WHATEVER YOU WANT.

You know what happens when you write `x + y`.

You already know the value of `z`.

This looks just like math, and that's because it is.

Don't worry, writing code isn't all about math, but working with numbers is a big part of the work you'll be doing.

#### If the above is simple math, what's with the word `var`? What's that?  
The word `var` stands for variable. We use it only when creating a variable.
You might remember the concept of variables from math, too. In this case, `x` is just a name that refers to the number 1. Any time we want to create a variable in javascript, we write something like:

```
var nameOfTheVariable = 'whatever the variable should reference';
```

#### Why are there single quotes around the phrase `whatever the variable should reference`?  
Check out the `var x = 1;` statement above. There aren’t any quotes around the `1`. This is how we can tell numbers from text. In javascript (and most programming languages), text like this is called a **string**.

#### Wait, why did I just write that on paper?  
Asking you to write code on paper wasn't arbitrary. It's useful to think about code in different ways, especially in the abstract. Sometimes it takes brainstorming away from the computer to figure out solutions to difficult problems. Another perk to paper coding: your program doesn't have to run, so you can use *pseudocode*.

#### So, what's pseudocode?  
Here's a simple example:

```
if x is greater than 10, subtract 1 from x.  
```

Here's that pseudocode turned into javascript:

```
if (x > 10){  
  x = x - 1;  
}  
```

We won't go into `if` statements in detail here, but based on this pseudocode you should be able to tell what's happening in that javascript.

#### Pseudocode is awesome.
You can use pseudocode to experiment, and to define the outline of a program without worrying about errors or syntax details. It's a great way to start thinking about the structure of the code you're about to write.


### Now let's open up the web browser, Chrome, and do some experimenting.

> If you haven't installed Chrome yet, do so now at [google.com/chrome](http://google.com/chrome)

1. Open a Chrome window.
2. Go to [learnjs.io](http://learnjs.io).
3. Click **View**, in the top menu, hover over **Developer**, then click **Javascript Console**. (TODO: edit for windows, linux, and mac)

> You can also use a keyboard shortcut:
> command+option+j on mac (TODO: edit for windows, linux, and mac)

If you've used a terminal program on your computer, the javascript console is similar, except you write javascript instead of terminal commands.

### Important:
Any time there are code samples just type them straight into the javascript console, hit **Enter**, and see what happens. The best way to learn a programming language is to type it a lot. More than a lot.

In the console, type: 

```
var x = 10;
```

Hit enter, and you'll see the word `undefined` pop up below your line of javascript.
That's fine, it's normal. That's what the console returns when you enter such a statement.
To see the value of `x`, type `x` into the console.

The console should return the number `10`!


### Let's get functional.
Consider this pseudocode:

```
add two arbitrary numbers.
```

We're going to create a function in javascript that adds two numbers.

We've got a function named add, and it takes two arguments and adds them together. For now, we assume the arguments to be numbers.

To use the 'add' function, write something like this:

```
add(3, 7);
```

### Let's add with a function!

A function is a block of executable code, and when we give a function a name, like we do below, it can be used throughout your program. The benefit: define a function once rather than using similar blocks of code in multiple places in your program.

```
function add(x, y){
  return x + y;
}
```

Type the above `add` function into the javascript console, and use it to do some addition!

Important note: using Chrome's javascript console, if you hit **Enter** it will execute the code. To type a function like this onto multiple lines, hit **Shift + Enter** to add a line.

Just like with the variables we created earlier, when we first define a function in the console it will return `undefined` when you hit enter. This is normal.

Also: When you are in the javascript console you can hit the up arrow to revisit previous code that you've typed in.

**Try these examples:**

```
// add 2 and 4:
add(2, 4);

// create a variable named num and set its value to the sum of 3 and 4:
var num = add(3, 4);
```

### Hey, you made `num` equal the usage of the add function.
Heck yeah, buddy. Let's take a look at the definition of the function again:  

```
function add(x, y){
  return x + y;
}
```

Check out the middle line, `return x + y;`.

With most javascript programming, one of your goals should be to write small, simple functions that take arguments as input, modify that input, and output it using the return statement. Whatever a function returns is used elsewhere in your program.

When we make the variable `num` equal `add(3, 4)`, we're really setting `num` to equal the value that's returned from the add function. In this case, `add(3, 4)` will return the number 7, so that's what `num` references.

### Wait, what if I messed up the adder?

Hey, sorry to bother you, but somebody tried to use our add function like this:

```
add(‘1’, ‘5’);
```

Unsurprisingly, it didn’t work as expected. Can you guess what the add function returned?

It returned this: `’15’`.

### Why didn’t it add?
Those numbers had quotes around them. Numbers in javascript do not have quotes around them, only strings. Instead of adding numbers, our program combined two strings.

### Walking like a duck
Javascript is a dynamically-typed language. Remember how we created variables earlier that referenced specific values? Each value that a variable references has a type, and in javascript, you don't have to specify a type when you create a variable. You can change a variable's type later in the program, and you will interact with a variable in different ways depending on its type. Sometimes this is called duck typing. If the variable walks like a duck and talks like a duck, it is a duck.

#### Here are common types in javascript:

##### Boolean: true or false

**Example:**

```
var thisIsNotTrue = false;
var thisIsNotFalse = true;
```

Note that there are no quotes around the words `true` or `false`. The variable named `thisIsNotTrue` references the value `false`, and the variable named `thisIsNotFalse` references the value `true`.

##### Number: integer or float

**Example:**

```
var thisIsAnInteger = 123;
var thisIsAFloat = 3.14;
```

A float is a number with a decimal. An integer is a whole number – without a decimal.

##### String: text in quotes.

**Example:**

```
var thisIsAString = ‘you can tell because this text is inside of quotes’;
```

A string is any text inside of quotes. It can be single or double quotes, but it has to be the same on each end. This will work: `'text'`, and this will work: `"text"`, but this will not work: `'text"`.

### Back to our addition issue:

This usage of our function doesn’t work: `add(‘1’, ‘5’);`.

The reason? The `+` operator and the way it works with strings.

This little buddy does a little more than you might expect at first. It’ll add numbers together, but it’ll also add strings together. When that happens it’s called concatenation.

When we use the `add` function with `'1'` and `'5'` as arguments, it executes a statement like this:

```
return ‘1’ + ‘5’;
```

A string `+` a string equals those two strings combined. That’s concatenation. So `'1' + '5'` becomes `'15'`.

**Some examples:**

```
‘abc’ + ‘def’ // becomes ‘abcdef’
‘This is a ‘ + ‘string’ // becomes ‘This is a string’
‘1’ + ‘5’ // becomes ‘15’
```

Lets add some code to our `add` function to make sure this doesn’t happen. By converting the arguments of the function to numbers, we can allow for the possibility of adding numbers that happen to be strings!

```
function add(x, y) {
  return parseInt(x) + parseInt(y);
}
```

All we added was the usage of the `parseInt` function. This is a part of core javascript, and is used to convert strings and floats to integers. 

### Now we have a float issue.

Somebody tried to add some floats together, like this:

```
add(3.14, 7.28);
```

It did not work as expected. It returned `10`. That's because `parseInt` is only going to return the integer it finds in a string. So maybe `parseInt` isn't the best solution.

**There is an easy fix.** Revise your add function to look like this:

```
function add(x, y) {
  return parseFloat(x) + parseFloat(y);
}
```

Yep, that works. Now that we're using `parseFloat` instead of `parseInt`, decimal numbers stay intact.  Now `add(3.14, 6.28);` returns `9.42`.

### What about adding more than two numbers?

Somebody found a weird workaround for adding multiple numbers using this `add` function:

```
var a = add(1, 3);
var b = add(a, 7);
var c = add(b, 21);
```

That’s just sad. We can make this easier. Rewrite the add function to look like this:

```
function add() {
  var total = 0;
  for (var i = 0; i < arguments.length; i++){
    total += parseFloat( arguments[i] );
  }
  return total;
}
```

Cool. Now we can pass any number of arguments to the `add` function and get the correct result!
With this change we can now pass any number of arguments to `add`, like this: 

```
add(1, 2, 3, 4, 5, 6, 7);
```

This makes `add` much more flexible than the previous workaround.

We used a `for` loop to cycle through all the arguments that are passed to `add`. We also used a variable named `total` to reference the sum of all arguments.

### Looper: cycling through a function's arguments
For loops are easy once you get used to them.

First we set a start value: `var i = 0`. That sets `i` to `0`, which makes our loop start at `0`.

Then compare that to an end value: `i < arguments.length`.
The statement `arguments.length` gives us the number of arguments. `length` returns the number of arguments. So, with usage like this: `add(1, 2, 3);`, `arguments.length` will return `3`.

As long as `i` is less than 3, the loop will run again.

Then we give the loop an increment value: `i++`. The `++` increases `i` by one with every loop.

This might be the point where you get a little overwhelmed if you are new to programming. If so, I recommend you practice things like `for` loops over at [codecademy.com](http://codecademy.com).  It's a great site for building foundational knowledge of javascript basics.

### One last problem: ‘one’.

That’s not a number. Can you guess what happens when someone tries to do this:

```
add(‘one’, ‘two’, 3);
```

Paste in the latest version of the `add` function to the Chrome javascript console. Then try out the above usage of `add`.

It should return something like this:

```
NaN
```

Let’s fix that. The problem: `NaN` means **not a number**. When we run `parseFloat` on a string like `’one’`, it returns `NaN`, and when we try to add `NaN` to a number, the whole sum becomes `NaN`.

There are a few possible solutions to this problem. Here are two:

#### Ignore any argument that is not a number.

```
function add() {
  var total = 0;
  for (var i = 0; i < arguments.length; i++){
    if ( isNaN( parseFloat(arguments[i]) ) === false ) {
      total += parseFloat( arguments[i] );
    }
  }
  return total;
}
```

The new code that we added looks like this:

```
...
    if ( isNaN( parseFloat(arguments[i]) ) === false )  {
      ...
    }
...
```

The function `isNaN` checks to see if `parseFloat(arguments[i])` is a number. If `isNaN` returns false, then we know that the argument is a number.

This checks to see if an argument is a number, and if not, ignores it – but there’s still a problem with this. Ignoring values like `'one'` in our `add` function because it doesn't contain numbers is reasonable. The problem: this error fails silently. 

Any time there's a chance our function can fail because of misuse by yourself or another programmer, it's best for the code to send errors explaining why it fails. We want our code to complain when there is a problem.

Let's switch up our code so that if an argument is not a number, `add` throws an error, and if the argument _is_ a number, it gets added to the `total` variable.

```
function add() {
  var total = 0;
  for (var i = 0; i < arguments.length; i++){
    if ( isNaN( parseFloat(arguments[i]) ) ) {
      throw new Error('Arguments to `add`  must be numbers.');
    } else {
      total += parseFloat( arguments[i] );
    }
  }
  return total;
}
```

Now, when we put that version of `add` into our javascript console and use it like this:

```
add('one', 2);
```

It'll return an error with this text:

```
Error: Arguments to `add` must be numbers.
```

Good, that was our goal. Now any strings that can't be converted to numbers will result in this clear error rather than being ignored.

### Here is what we covered:

#### Chrome javascript console
We started using Chrome's javascript console in a really basic way as preparation for upcoming chapters.

#### Basic data types
We covered the basics of strings, numbers, and booleans.

#### Writing functions.
We went over the basics of writing a simple function.

#### Refactoring code.
As we wrote and experimented use cases of the `add` function we identified ways it could be improved and rewrote the function to guard against mistakes.

#### Debugging and useful errors.
As you're getting started it probably feels like errors are just something to avoid. But, if we can embed useful errors in our code in places where we know there are likely problems, that can make debugging much easier.



# Introduction to callbacks.

A callback is a function that you pass as an argument to another function.
Typically, you'll use a callback as a way to work with data after it's been processed by a function.

A simple callback looks like this:

```
function holla(callback){
  callback();
}
```

Note how we're setting up an argument named `callback`, then calling that argument as a function: `callback()`.

Usage if the `holla` function:

```
holla(function(){
  console.log('this is part of the callback function);
});
```

Our function named `holla()` takes one argument, and we expect it to be a function. In this example we're using an anonymous function, but we could use a named function like this:

```
function holla(callback){
  callback();
}

function back(){
  console.log('this is part of the callback function);
}

holla(back);
```

But usually we're providing a function some kind of parameter,  that function performs an action on the parameter, then we use the callback to work with the output of the function we called. A simple example looks like this:

```
// create an eat function
function eat(food, callback){
  var food = food + " was eaten";
  callback(food);
}

// create a poop function to use as the callback
function poop(output){
  console.log(output);
}

// call the eat function, passing a food and the poop function as arguments
eat("pizza", poop);
```

Note that when we pass the callback function `poop` as an argument we don't write it like `poop()`. This would _call_ or execute the function, and we don't want that to happen when we pass the `poop` function as an argumet. The `poop` function gets called later inside the `eat` function.


# Introduction to testing

In this book we will test code using [tape](https://github.com/substack/tape), and [mocha](https://github.com/visionmedia/mocha).


## tape

tape's api is largely based on

### Install tape as a development dependency:
```
npm install tape --save-dev
```

### Example:
```
var test = require('tape');

test('timing test', function (t) {
    t.plan(2);

    t.equal(typeof Date.now, 'function');
    var start = Date.now();

    setTimeout(function () {
        t.equal(Date.now() - start, 100);
    }, 100);
});
```

## mocha

### Install mocha as a command line tool:

```
npm install -g mocha
```

### Example:

```
var assert = require("assert");

describe('Array', function(){
  describe('#indexOf()', function(){
    it('should return -1 when the value is not present', function(){
      assert.equal(-1, [1,2,3].indexOf(5));
      assert.equal(-1, [1,2,3].indexOf(0));
    });
  });
});
```

### Run the example with the mocha terminal command:

```
mocha
```


# Introduction to canvas
> Creating basic keyboard and mouse interaction with the html5 canvas tag.

We're going to use the html5 canvas tag to draw a small rectangle to the screen and move it around using the keyboard's arrow keys. This will provide a very basic introduction to game development using javascript and the canvas tag.

To get started, we need to create a basic index.html file with these contents: 

```
<!DOCTYPE html>
<html>

<head>
<title>canvas and keyboard interaction example.</title>
</head>

<body>
  <canvas id="game"></canvas>

  <!-- include our javascript -->
  <script src="app.js"></script>
</body>

</html>
```

Now, create an app.js file with these two lines:

```
var canvas = document.getElementById('game');

var context = canvas.getContext('2d');
```

In this code we find the canvas tag by its `game` id and save that to a new canvas variable.

Next, we state we'll be drawing on the canvas in a 2d context by running `canvas.getContext('2d')` and saving that to the `context` variable. To draw in a 3d context we would pass `'webgl'` as the argument rather than `'2d'`. We'll explore 3d/WebGL drawing later in the book.

To experiment with these statements, try running them in the Chrome javascript console.

Copy this and run it in the Chrome console:

```
var canvas = document.getElementById('game');
canvas;
```

You should get something like this returned:

```
<canvas id="game"></canvas>
```

And if you run this in the Chrome console:

```
var context = canvas.getContext('2d');
context;
```

You'll be able to open up and inspect the `context` object that we'll use later to draw to the canvas.

# Starting the game and the game loop

We want our game to perform certain actions every frame, and we'll use a `loop()` function to do that.

To kick off our loop and start the game, we'll define a `startGame()` function like this:

```
function startGame(){ 
  canvas.height = 400;
  canvas.width = 800;

  loop();
}
```

We set the width and height of the canvas, and call the `loop()` function. When `startGame()` is called, the loop will start running. We haven't defined `loop()` yet, so let's do that next.


```
function loop(){
  requestAnimationFrame(loop);

  update();

  draw();
}
```

The `requestAnimationFrame()` function is a browser API that runs animations at a consistent framerate, and pauses the animation automatically when the tab/window loses focus. We pass the `loop` function to `requestAnimationFrame()` so that on each frame, `loop()` is called.

Next we call `update()` and `draw()`.

`update()` performs the calculations in our game. It can calculate trajectory, check for player input, detect collisions, and other actions that are oriented toward math and game state.

`draw()` is used to draw things to the canvas.

Let's define empty `update()` and `draw()` functions so that they exist and can be used later:

```
function update(){
  // update the game
}

function draw(){
  // draw to the canvas
}
```

Now that we've got the basic structure of the game, let's define our player character so it can be drawn to the screen.

We'll name it `box`, since it'll be a box. `box` will be an object with these properties:
- x position
- y position
- width
- height
- speed
- color

Create `box` with these initial values:

```
var box = {
  x: 50,
  y: 50,
  width: 10,
  height: 10,
  speed: 10,
  color: '#4f5654'
};
```

That gives our box a starting position, size, speed and color.

Next we need to define `update()` and `draw()` methods on `box` that can be called on each loop.

Let's start with `draw()`:

```
box.draw = function() {
  context.fillStyle = box.color;

  context.fillRect(box.x, box.y, box.width, box.height);
};
```

`context.fillStyle` is set to the color of the box.

`context.fillRect()` draws a rectangle and accepts the x position, y position, width, and height, of the box. It draws with the color set in `context.fillStyle`.

Now we can add `box.draw()` to the game's `draw()` function:

```
function draw(){
  box.draw()
}
```

Add a call to `startGame()` to the end of the app.js file so we can experiment with the code:

```
startGame();
```

You should see a small dark grey box in the top left corner of the canvas.

Now let's make the box move! Create `box.update()`:

```
box.update = function() {
  box.x += box.speed;
  box.y += box.speed;
};
```

To start, we're making the box move from the top left to the bottom right automatically. Add `box.update()` to the game's `update()` function:

```
function update(){
  box.update()
}
```

Check that out in the browser and you should see the square moving from the top left to the bottom right of the canvas and eventually disappearing past the boundary of the canvas.

Instead of making `box` move automatically, let's make it move when we press the arrow keys.

For this, we need to listen for events that occur when a key is pressed, so we'll use `window.addEventListener()`.

We want to check for when a key is pressed down, and when it is released, so we'll listen for the `keydown` and `keyup` events.

When a key is down, we'll store it's keyCode in an object named `keysDown`.

Initialize the `keysDown` object:

```
var keysDown = {};
```

Implement `window.addEventListener()` for the `keydown` event:

```
window.addEventListener('keydown', function(event) {

  keysDown[event.keyCode] = true;

  if (event.keyCode >= 37 && event.keyCode <= 40) {
    event.preventDefault();
  }
});
```

With this code, we listen for the `keydown` event, and when it fires, the anonymous callback function is executed. We get the `event` object, which has detailed information about the event. The only info we need from `event` in this case is the keyCode of the key that is pressed down, and that is accessible at `event.keyCode`.

With `keysDown[event.keyCode] = true;` we create a property on the `keysDown` object with the name of the property set to the key's keyCode, and the value set to `true`, making it easy to tell if a key is in the `keysDown` object.

The thing about the arrow keys is that they have a purpose in the browser: scrolling the page.

We don't want the page to scroll when we're moving `box` around, so we need to disable that defulat behavior.

`event.preventDefault()` keeps a key from performing its defualt behavior. We want to be careful how we use `event.preventDefault()` for accessibility and usability reasons. If we disabled all keys that would make normal navigation and keyboard actions impossible.

So we use the `if` statement to check if the keys being pressed are the arrow keys: 37, 38, 39, 49.

If the keyCode is 37, 38, 39, or 40, their default behavior is prevented.

Next, we need to listen for `keyup` events. If we don't, the keysDown object will continue to include keys that are no longer being pressed down.

Implement `window.addEventListener()` for the `keyup` event:

```
window.addEventListener('keyup', function(event) {
  delete keysDown[event.keyCode];
});
```

All this does is listen for the `keyup` event, and when it fires, execute the anonymous callback function.

With `delete keysDown[event.keyCode];` we remove the key's keyCode from the `keysDown` object.

In the game's `update()` function add this line so that we can log to the console which keys are currently being pressed:

```
console.log(keysDown);
```

This let's us see which keys are down as we're pressing them.

Next, we need to make the position of `box` changed based on the keys we're pressing.

Let's create a `box.input()` method:

```
box.input = function(){
  // down
  if (40 in keysDown) {
    box.y += box.speed;
  }

  // up
  if (38 in keysDown) {
    box.y -= box.speed;
  }

  // left
  if (37 in keysDown) {
    box.x -= box.speed;
  }

  // right
  if (39 in keysDown) {
    box.x += box.speed;
  }
}
```

It's important to remember that the canvas coordinates start at zero in the top left corner. So to make `box` move down or to the right, we add `box.speed` to its position. And if we want `box` to move up or left, we subtract `box.speed` from its position.

Add `box.input()` to the `box.update()`, replacing what we had there previously:

```
box.update = function() {
  box.input();
};
```

This will run our `box.input()` method every loop, check to see if arrow keys are being pressed, and if so, move the box. Try it out!

Wait a minute, there's been something weird going on. Whenever the box moves, it draws a line. Everywhere you make the box go it leaves a trail.

We need to clear the canvas on every frame so that the old box positions get deleted, and make it look like the box is moving rather than drawing a line.

To do this, we can add `context.clearRect()` to the game's `draw()` function:

```
function draw(){
  context.clearRect(0, 0, canvas.width, canvas.height);
  box.draw();
}
```

Try this out in the browser again and you'll see the box no longer leaves a trail.

# Here's the full code (with comments) for our simple canvas / input example:

```
// Here we select the canvas with an id of game 
// this is where we will draw our game assets
var canvas = document.querySelector('#game');

// What kind of drawing will we do?
// our game is in 2d, so our drawing will happen in the _context_ of 2 dimensions
var context = canvas.getContext('2d');

function startGame(){ 
  // set the width and height of our drawing canvas
  canvas.height = 400;
  canvas.width = 800;

  // start the game loop
  loop();
}

// any thing inside the loop() function gets run on every loop
function loop(){
  // this function runs the loop at a consistent rate, 
  // and only runs the loop when the browser tab is in focus
  requestAnimationFrame( loop, canvas );

  // update the game
  update();

  // draw new stuff after they've been updated
  draw();
}

// make a box object
// give it a starting x, y location, a width, height, speed, and color
var box = {
  x: 50,
  y: 50,
  width: 10,
  height: 10,
  speed: 10,
  color: '#4f5654'
};

// this function manages all the user input for the box object
box.input = function(){
  
  // check if any of the arrow keys are in the keysDown object
  if (40 in keysDown) {
    box.y += box.speed;
  }
  if (38 in keysDown) {
    box.y -= box.speed;
  }
  if (37 in keysDown) {
    box.x -= box.speed;
  }
  if (39 in keysDown) {
    box.x += box.speed;
  }
}

// draw the box
box.draw = function() {
  // set the color of the box
  context.fillStyle = box.color;

  // actually draw the box to the canvas
  context.fillRect(box.x, box.y, box.width, box.height);
};

// update the game
function update(){
  // check for any input relevant to the box
  // every time the game is updated
  box.input();
}

// draw on the canvas
function draw(){
  // this clears the canvas so that when the box is drawn each time
  // it looks like it moves, rather than drawing a line that follows the path
  // of the box. comment out the context.clearRect line to see what i mean.
  context.clearRect(0, 0, canvas.width, canvas.height);
  box.draw();
}

// this object contains any keyboard keys that are currently pressed down
var keysDown = {};

// here we add an event listener that watches for when the user presses any keys
window.addEventListener('keydown', function(event) {

  // add the key being pressed to the keysDown object
  keysDown[event.keyCode] = true;

  // if the user is pressing any of the arrow keys, disable the default
  // behavior so the page doesn't move up and down
  if (event.keyCode >= 37 && event.keyCode <= 40) {
    event.preventDefault();
  }
});

// this event listener watches for when keys are released
window.addEventListener('keyup', function(event) {
  // and removes the key from the keysdown object
  delete keysDown[event.keyCode];
});

// start the game
startGame();
```

That's it, and you made stuff move around the screen!

There are a few things left that you can explore:
- making the box stop at the boundaries of the canvas
- drawing an image instead of a rectangle
- creating an enemy object
- implementing collision detection
- making the player and enemy shoot bullets/arrows/whatever

We'll explore many of these things in upcoming Games chapters.

> This section of the book is still a work in progress. Make suggestions at [github.com/learn-js/learnjs/issues](http://github.com/learn-js/learnjs/issues).


# Package managers for browser code: what should I use?

When should I use npm, bower, or component for managing client-side code?

To start: always use one of them. The old days of downloading js/css libraries one by one and updating them manually are totally over, and that's exciting. Using a package manager for front-end code means we can easily download libraries, keep track of versions, and ease dependency management.

But we still have too many options for how to manage our client-side code. Beyond npm, bower, and component there are still many other options, but those three seem to be settling in as the most widely adopted.

## And all three are quite different:

### npm
npm nominally started out as a package manager for node, but now is used for any javascript, and along with a tool like browserify it's easy to use npm packages and node-style modules in the browser. It's not super useful for css libraries – but it's easy to imagine a tool (built on something like brfs) that could make bundling css npm packages super pleasant.

### bower
bower is a clear hero of client-side code: it's great for both css and javascript. It's easy to manage dependencies – even if those dependencies don't have a config file for bower. You can install a file or git repository as a dependency alongside packages in the bower registry. Bower doesn't make any assumptions about how you build or deploy code, so it is compatible with amd modules.

### component
component is a tool with a more focused and defined goal than npm and bower. It uses common js style modules. Each component may contain javascript, css, fonts, and images. Some javascript-only components can also be used in node.js. See the [Component FAQ](https://github.com/component/component/wiki/F.A.Q) for more details.

## When I use npm for browser code:
Games. There's been a lot of interesting activity in javascript game development in the node.js community using browserify. voxel.js is one of the biggest examples, with a goal of creating minecraft-like games in the browser. See the work of these people for examples:

npm/browserify will also be useful for creating applications that might share javascript code on the server and the browser. This approach also works well when the javascript requirements for the client-side are minimal, or if you prefer to write client-side code in a node style.

## When I use bower for browser code:
When the project requires a front-end framework like backbone, angular, or ember, I use bower as the package manager. It's currently the best way to package arbitrary dependencies of a javascript application. Typically using bower means that I am also using the build tool grunt.

## I don't really use component yet.
I really want to. It seems like there's some great work happening around component. I expect that there will be instances when I'll want to use some of the available components. But when that happens, I'll probably need to figure out a way to integrate component with bower or npm/browserify.

## Use all three at once!
It's possible to use packages from both bower and component while using browserify!

Check out this great guide for using components, bower packages, amd modules, and even global variables with browserify: http://dontkry.com/posts/code/browserify-and-the-universal-module-definition.html



# Websites


# Chapter Three

## A fanpage for pizza.

We're going to make a website for pizza as our first project and host it using GitHub Pages. I'm pretty excited about that. This project starts out a little heavy on html and css, but that's alright for the first project isn't it? Maybe you need an html/css refresher. If you're a hero of markup and styling you should be able to complete this project super fast, or you may want to ski(m/p) this chapter.

### A breakdown of what we'll go over:  
- Sketching the contents of the page.  
- Brief overview of html and css.  
- Using an online editor.  
- Adding text and images.
- Creating a pizza with code.
- Getting photos of pizza from the instagram api.
- Using menu data from your favorite pizza place, aka: using json.
- A map of your favorite pizza places.

### Sketching the contents of the page.
We're making a fanpage about pizza. A microsite. If this were the 1990s we'd be making a zine with paper, scissors, and secretly using a copy machine for free.

**This is not the 1990s.**

But we can build our pizza microsite with a similar tone and purpose. On the web everyone is a publisher, so let's publish something awesome about pizza. 

Choosing pizza as the topic is arbitrary. You could make a fanpage for anything. 

If we were writing a zine in the '90s we might make a quick prototype with a pencil. And you know, that's basically what we'll do right now, too. Instead of calling it a zine, we'll call it a microsite.

Get a pencil and a piece of paper. Or find a marker and go to your window or whiteboard. Whatever. Let's sketch.

#### We'll start by drawing four things:
1. the header
2. the main content area.
3. a large pizza in the main area.
4. the footer.
 
##### The header.
The header will be very simple, just the title, description, and a cool little pizza icon.

##### The main content area.
The main content area will have a few things:

- A large pizza.
- A list of your favorite types of pizza.
- A map of your favorite pizza places.

##### The footer.
The footer of this microsite will be very simple. Think of it like the credits of a movie or masthead of a newspaper. Any small details that people need to know.
Things like:
- Who you are
- How the site was made
- Licensing of the code and content
- Contact information

### Create the project file/directory structure:

#### Create the index.html, app.js, and style.css files:

```
touch index.html app.js style.css
```

#### Create a folder for images:

```
mkdir images
```

#### Add the following markup to your index.html file:

(you don't have to copy the comments)

```
<!DOCTYPE html>
<html>

<head>

<!-- the title of the page – shows up in the browser tab/window -->
<title>I love pizza.</title>

<!-- this ensures ie is using the latest rendering mode -->
<meta http-equiv="X-UA-Compatible" content="IE=edge">

<!-- default viewport settings to help with mobile/responsive design -->
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<!-- include our css styles -->
<link href="style.css" rel="stylesheet">

</head>

<body>
  <h1>I love pizza.</h1>

  <!-- include our javascript -->
  <script src="app.js"></script>
</body>

</html>
```

That'll get us started.

### Adding text and images to our microsite.

#### Add the header:

Replace the current `h1` tag with this markup for the header:

```
<header>
  <h1>I love pizza</h1>
</header>
```

After the closing header tag, add this main content section:

```
<main role="main">
  <p>Pizza is my favorite food in the world, and here's why: it's delicious.</p>
</main>
```

The `main` tag is a fairly new addition to html5. Feel free to use your own text about pizza here.

After the closing body tag, add a footer:

```
<footer>
  <p>Made by YOUR NAME HERE with love for pizza.</p>
</footer>
```

That should give us an html document that looks like this:

```
<!DOCTYPE html>
<html>

<head>

<title>I love pizza.</title>
<meta http-equiv="X-UA-Compatible" content="IE=edge">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<link href="style.css" rel="stylesheet">

</head>

<body>

<header>
  <h1>I love pizza</h1>
</header>

<main role="main">
  <p>Pizza is my favorite food in the world, and here's why: it's delicious.</p>
</main>

<footer>
  <p>Made by YOUR NAME HERE with love for pizza.</p>
</footer>

<script src="app.js"></script>
</body>

</html>
```

### Give the page some very simple styles
Add this to the style.css file:

```
html,
body {
  font: 16px/1.3 "Helvetica Neue", Helvetica, arial, sans-serif;
  color: #444;
  -webkit-font-smoothing: antialiased;
  font-smoothing: antialiased;
  font-weight: 300;
}

a {
  color: #3c80c3;
  text-decoration: none;
}

a:hover {
  text-decoration: underline;
}

a:active,
a:focus {
  color: #1e4062;
}

img {
  max-width: 100%;
  height: auto;
  vertical-align: middle;
}

/* mobile size */
.container {
  width: 80%;
  padding: 0px 10%;
  margin: 0px auto;
}

/* tablet size */
@media only screen and (min-width: 600px) {
  .container {
    width: 540px;
    padding: 0px 20px;
  }
}

/* desktop size */
@media only screen and (min-width: 960px) {
  .container {
    width: 800px;
  }
}
```


### Create a pizza with code.

### Create a map of your favorite pizza places

> This section of the book is still a work in progress. Make suggestions at [github.com/learn-js/learnjs/issues](http://github.com/learn-js/learnjs/issues).



# Games

Some of the things we'll work on in the Games section:
- Simple asteroids-style game without using a js game library.
- Old-school arcade games with crtrdg.jd.
- Minecraft-like games with voxel.js.



# Chapter 1

## Make a game with javascript!

Let's build a game, everybody. Let's have some fun.

We'll create a bunch of objects and functions. We'll put them together to make our game run, and experiment with changing the functions and the object attributes to alter the behavior of the game.

It'll be a single player game. A [roguelike](http://en.wikipedia.org/wiki/Roguelike) [rpg](http://en.wikipedia.org/wiki/Role-playing_video_game) with extremely simple graphics.

Usually roguelike games have procedurally generated levels, but we'll just build static levels for this example.

Our game will feature monsters, weapons, coins, potions, and a hero.

That small list above gives us a good sense of what objects and functions we'll need in our code.

We'll need to represent each of those things in our game code, so let's briefly outline the parts of the game we'll need to build, along with the typical actions each part will have:

### Game
- Loop
- Draw

### Level
- Load level data
- Draw

### Hero
- Update
- Draw
- Drink Potion
- Pick up Coin
- Fight Monster

### Monster
- Update
- Draw
- Fight Hero

### Weapon
- Update
- Draw

### Coin
- Update
- Draw

### Potions
- Update
- Draw

Each of the above headers will be an object in our game, and each of the list items will be methods or attributes of their respective headers.

## Requirements:
You'll need these things installed on your computer:
- node.js
- browserify and beefy

Make sure you're read the intro to node and intro to browserify chapters before starting this project. (TODO: link to those chapters.)

To get started, create a folder for your game. I'm calling it `node-rogue`:

```
mkdir node-rogue
cd node-rogue
```

Run the npm init command to create a package.json file for your project:

```
npm init
```

Answer all the questions however you want. I kept them mostly at the defaults (text in parentheses is the default, if you just hit enter it'll use that default value).

```
name: (node-rogue) 
version: (0.0.0) 
description: a roguelike game made with javascript
entry point: (index.js) game.js
test command: node test.js
git repository: git://github.com/learn-js/node-rogue
keywords: gamezzz
author: seth vincent
license: (BSD) MIT
```

You should end up with a package.json file that looks like this:

```
{
  "name": "node-rogue",
  "version": "0.0.0",
  "description": "a roguelike game made with javascript",
  "main": "game.js",
  "scripts": {
    "test": "node test.js"
  },
  "repository": {
    "type": "git",
    "url": "git://github.com/learnjs/node-rogue"
  },
  "keywords": [
    "gamezzz"
  ],
  "author": "sethvincent",
  "license": "MIT",
  "bugs": {
    "url": "https://github.com/learnjs/node-rogue/issues"
  }
}
```

Now, create the game.js and test.js files:

```
touch game.js test.js
```

We'll also need an index.html file:

```
touch index.html
```

Open up that file and make it look like this:

```
<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8">
  <title>node-rogue</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

<h1 id="title">node-rogue</h1>

<canvas id="game"></canvas>

<script src="./bundle.js"></script>
</body>
</html>
```

Let's add a css file:

```
touch style.css
```

And give it some very basic styles:

```
html,
body {
  font: 16px/1.2 "Helvetica Neue", Helvetica, arial, sans-serif;
  color: #444;
  -webkit-font-smoothing: antialiased;
  font-smoothing: antialiased;
  font-weight: 300;
}

h1#title {
  margin: 30px 0px;
  text-align: center;
  font-weight: 300;
}

canvas#game {
  display: block;
  margin: 0px auto;
}
```

To ease development, we'll use a simple game library I recently created called `crtrdg-gameloop`. All it does is initialize the canvas, and provide a simple api that emits `update` and `draw` events that we can use to make our game. Later we'll take a look at the crtrdg-gameloop module in detail. (TODO: add a link to that chapter)

Install `crtrdg-gameloop` using npm:

```
npm install crtrdg-gameloop --save
```

The `--save` option edits the package.json file and adds the module you're installing the the dependencies list. 

## Now, to start writing javascript! 
Open the game.js file, and get started:

```
// require crtrdg-gameloop
var Game = require('crtrdg-gameloop');

// create a new game
var game = new Game({
  canvasId: 'game',
  width: 800,
  height: 400,
  backgroundColor: '#ff1f1f'
});

// game.on('update', callback) 
//
// this runs each time the game loops
// it is useful for things like checking for user input
// moving the position of characters/items
// checking for game boundaries and collision detection
// and other similar tasks
// interval is the time since the last loop
game.on('update', function(interval){
  console.log('update', interval);
});

// game.on('draw', callback) 
//
// the draw event runs after the update event
// it's used for actually drawing your characters / items / backgrounds to the canvas
// context is the actual canvas context, so you'll
// use it to draw just like in the Introduction to Canvas chapter.
game.on('draw', function(context){
  console.log('draw', context);
  context.fillStyle = '#fff';
  context.fillRect(10, 10, 10, 10);
});

// game.on('pause', callback) 
//
// if game.pause() is called somewhere in your code,
// a `pause` event will be emitted
// listen for it like this:
game.on('pause', function(){
  console.log('paused');
});

// game.on('resume', callback) 
//
// if game.resume() is called somewhere in your code,
// a `resume` event will be emitted
// listen for it like this:
game.on('resume', function(){
  console.log('resumed');
});
```

To run this code we will use [beefy](https://github.com/chrisdickinson/beefy).

Open the package.json file and add a `start` script to the scripts object so it looks like this:

```
"scripts": {
  "test": "node test.js",
  "start": "beefy game.js:bundle.js --live"
},
```

If you've installed browserify and beefy like this:

```
npm install -g browserify beefy
```

You can now run:

```
npm start
```

This will serve your index.html file at http://localhost:9966.

Open Chrome, navigate to that url, and open the javascript console.

You should see the `update` and `draw` messages being logged to the console and a big red canvas with a small white block in the top left corner!

This is the beginning of node-rogue.

## Create the player character

Next, we'll make a player that can move around the screen. We'll make use of another small game module: `[crtrdg-entity](https://github.com/sethvincent/crtrdg-entity)`.

First, install the `crtrdg-entity` module:

```
npm install --save crtrdg-entity
```

Next, create a player.js file that looks like this:

```
// require `crtrdg-entity` module
var Entity = require('crtrdg-entity');
var inherits = require('inherits');

// Make this available as a module that can be required
module.exports = Player;

// make the Player funtion inherit from crtrdg-entity
inherits(Player, Entity);

// create Player function
function Player(options){
  this.position = { 
    x: options.position.x, 
    y: options.position.y 
  };

  this.size = {
    x: options.size.x,
    y: options.size.y
  };

  this.color = options.color
}
```

So we created a constructor that takes position, size, and color options. We can now use `Player` in our game.js file.

Revise game.js to look like this:

```
var Game = require('crtrdg-gameloop');

// Require the Player module
var Player = require('./player');

// the same game code we had before:

var game = new Game({
  canvasId: 'game',
  width: 800,
  height: 400,
  backgroundColor: '#ff1f1f'
});

game.on('update', function(interval){
  console.log('update', interval);
});

game.on('draw', function(context){
  console.log('draw', context);
});

game.on('pause', function(){
  console.log('paused');
});

game.on('resume', function(){
  console.log('resumed');
});

// The new player code:

// create instance of Player with position, size, and color
var player = new Player({
  position: { x: 10, y: 10 },
  size: { x: 10, y: 10 },
  color: '#fff'
});

// add the player to the game
player.addTo(game);

// listen for update event.
// here you can do things like change position or watch for keyboard/mouse events
player.on('update', function(interval){
  console.log(this.position);
});

// listen for draw event.
// context is the canvas context, so you can draw on the canvas like usual.
player.on('draw', function(context){
  context.fillStyle = this.color;
  context.fillRect(this.position.x, this.position.y, this.size.x, this.size.y);
});
```

Check your browser at url http://localhost:9966 and you should see the red canvas with a small white square in the top left corner!

## Adding keyboard interaction

Let's move that little white square around the screen now!

We'll use a module named `crtrdg-keyboard` to listen for keyboard events.

Install it:

```
npm install --save crtrdg-keyboard
```

Require it in game.js:

```
var Keyboard = require('crtrdg-keyboard');
```

Create the keyboard:

```
var keyboard = new Keyboard(game);
```

Revise player.on('update'):

```
player.on('update', function(interval){
  console.log(this.position);

  if ('<up>' in keyboard.keysDown){
    this.position.y -= 1;
  }
  
  if ('<down>' in keyboard.keysDown){
    this.position.y += 1;
  }
  
  if ('<left>' in keyboard.keysDown){
    this.position.x -= 1;
  }

  if ('<right>' in keyboard.keysDown){
    this.position.x += 1;
  }
});
```

So the full code of our game.js file should now look like this:

~~~~
var Game = require('crtrdg-gameloop');
var Keyboard = require('crtrdg-keyboard');
var Player = require('./player');

var game = new Game({
  canvasId: 'game',
  width: 800,
  height: 400,
  backgroundColor: '#ff1f1f'
});

var keyboard = new Keyboard(game);

game.on('update', function(interval){
  console.log('update', interval);
});

game.on('draw', function(context){
  console.log('draw', context);
});

game.on('pause', function(){
  console.log('paused');
});

game.on('resume', function(){
  console.log('resumed');
});

var player = new Player({
  position: { x: 10, y: 10 },
  size: { x: 10, y: 10 },
  color: '#fff'
});

player.addTo(game);

player.on('update', function(interval){
  console.log(this.position);

  if ('<up>' in keyboard.keysDown){
    this.position.y -= 1;
  }
  
  if ('<down>' in keyboard.keysDown){
    this.position.y += 1;
  }
  
  if ('<left>' in keyboard.keysDown){
    this.position.x -= 1;
  }

  if ('<right>' in keyboard.keysDown){
    this.position.x += 1;
  }
});

player.on('draw', function(context){
  context.fillStyle = this.color;
  context.fillRect(this.position.x, this.position.y, this.size.x, this.size.y);
});
```


> This section of the book is still a work in progress. Make suggestions at [github.com/learn-js/learnjs/issues](http://github.com/learn-js/learnjs/issues).


# Chapter 2
## create a minecraft-like world in your browser with voxel.js

voxel.js is a game engine for creating 3d voxel worlds with javascript. It's like minecraft, but open-source. Over {somenum} people have already contributed to the project.

One cool thing about voxel.js is that it isn't just one big library – there's a main game engine, [voxel-engine](http://github.com/maxogden/voxel-engine), and a bunch of [modules that extend the functionality of the engine](http://voxeljs.com/#modules). Quite a few people have created modules for voxel.js, and in this chapter we'll both make a game using voxel.js, and create a module that modifies the gameplay in a new way.

Create a package.json file with these contents:
```
{
  "name": "mygamename",
  "version": "0.0.1",
  "scripts": {
    "start": "beefy game.js:bundle.js --live"
  },
  "dependencies": {
    "voxel-hello-world": "0.6.0"
  },
  "devDependencies": {
    "beefy": "*"
  }
}
```

Install the dependencies:

```
npm install
```

Create a game.js file, and start it out with this code:

```
var createGame = require('voxel-hello-world')
var game = createGame()
```

Here we're requiring the `voxel-hello-world` module, and creating our game with the `createGame()` function.



# Applications

We'll work on apps based on these technologies:
- phonegap
- cocoonjs
- firefox os


# APIs


# Mapping and geodata

We'll work on projects that utilize:
- leaflet.js
- openstreetmaps geocoding service, nominatim.js
- localwiki
- geojson


# Appendix


## Javascript style guide & syntax cheatsheet


### Variables

#### Creating a variable:

```
var nameOfVariable;
```

> Variables are camelCase, meaning first letter is lowercase, and if the variable is made of multiple words, the first letter of following words are capitalized.

#### Creating a variable that references a string:

```
var thisIsAString = 'this is a string';
```

Surround strings with single quotes.


#### Creating a variable that references a number:

```
var thisIsANumber = 3.14;
```

Numbers do not have quotes around them.

#### Creating a variable that references an array:

```
var thisIsAnArray = [1, "two", [3, 4]];
```

Note that one of the values in the array is a number, one is a string, and another is an array. Arrays can hold any value in any order.

#### Accessing the values in an array:

```
thisIsAnArray[0];
```

The above will return the number `1`. Arrays use numbers as the index of their values, and with javascript an array's index always start at `0`, making `0` reference the first value of the array.

```
thisIsAnArray[1];
```

This returns the string 'two';

##### How would you return the number `4` from the nested array?

Like this:

```
thisIsAnArray[2][1];
```

#### Creating a variable that references an object:

var thisIsAnObject = {
  someString: 'some string value',
  someNumber: 1234,
  someFunction: function(){
    return 'a function that belongs to an object';
  }
}

Here we're setting `someString` to `'some string value'`, `someNumber' to `1234`, and we're creating a function named `someFunction` that returns the string `'a function that belongs to an object'`. So how do we access these values?

To get the value of `someString` using dot notation:

```
thisIsAnObject.someString;
```

Or using bracket notation:

```
thisIsAnObject['someString'];
```

To get the value of `someNumber` using dot notation:

```
thisIsAnObject.someNumber;
```

Or using bracket notation:

```
thisIsAnObject['someNumber'];
```

To use the function `someFunction` using dot notation:

```
thisIsAnObject.someFunction();
```

Or using bracket notation:

```
thisIsAnObject['someFunction']();
```

Using square bracket notations with functions looks a little wacky. It will be useful if you are storing function names in variables as strings, and need to use the variable to call the function being stored. Otherwise, stick with dot notation.
That goes for other attributes on an object, too: stick with dot notation unless there's a good reason to use bracket notation.

For instance, it's more clear to use bracket notation in a situation like this:

```
for (var key in object){
  thisIsAnObject[key];
}
```

This gives you an idea of how to iterate through an object using a for...in loop.


## Additional resources

### javascript books:
- [js for cats](https://github.com/maxogden/javascript-for-cats)
- [eloquent javascript](http://eloquentjavascript.net/)
- [learning javascript design patterns](http://www.addyosmani.com/resources/essentialjsdesignpatterns/book/)
- [writing modular javascript](http://addyosmani.com/writing-modular-js/)
- [jquery fundamentals](http://jqfundamentals.com/)
- [javascript enlightenment](http://www.javascriptenlightenment.com/JavaScript_Enlightenment.pdf)

### node.js books:
- [art of node](https://github.com/maxogden/art-of-node)
- [stream handbook](https://github.com/substack/stream-handbook)
- [node beginner book](http://www.nodebeginner.org/)

### html/js/dom books:
- [dive into html5](http://diveintohtml5.info/)
- [dom enlightenmnet](http://domenlightenment.com/)

### Style guides:
- [idiomatic.js](https://github.com/rwldrn/idiomatic.js)
- [idiomatic html](https://github.com/necolas/idiomatic-html)
- [idiomatic css](https://github.com/necolas/idiomatic-css)
- [airbnb js style guide](https://github.com/airbnb/javascript)
- [felixge node style guide](https://github.com/felixge/node-style-guide)
- [jQuery's javascript style guide](http://contribute.jquery.org/style-guide/js/)



# Changelog

## v0.4.0
- Add Introduction to npm
- Add Introduction to callbacks
- Add Introduction to canvas (still working on this)
- Add Introduction to browserify
- Substantial revisions to Chapter 01 - making a game
- Many small typo / formatting fixes

## v0.3.2
- Substantial copy editing
- Start chapter 1 about making an rpg game
- Rearrange and edit Basics intro section

## v0.3.1
- start intro to node section
- add contributors list
- add simple keyboard interaction example

## v0.3.0
- start Basics section
- add intro to Chrome Developer Tools
- add intro to functions

## v0.2.0:
- added introduction to grunt.js
- added introduction to git & GitHub
- small typo fixes

## v0.1.0:
- first release
- intro to functions - create an add function
- appendix with initial style guide and additional resources


# Contributors
These wonderful people have helped the book along by copy editing, reporting errors, providing advice, and more. Thank you!

- Carrie Ramsdell - copy editing
- Sam Sermeno - copy editing
- [Matt Renquist](https://github.com/mattrenquist) - bug fixes, code updates
- [Benjamin Zanatta](https://github.com/benjaminzanatta) - design recommendations
- [Adam Duvander](https://twitter.com/adamd) - typo fixes, feedback on progress
- Peter deHaan - typo fixes


