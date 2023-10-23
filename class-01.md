**Why this topic matters**

These topics are important for building a strong foundation in coding. You cannot learn more complex concepts without first learning the basics.

**Getting Started**

1. Compose a short poem describing how HTTP sends data between computers.

In realms of code, where networks sprawl,
A tale of data, I now recall.
HTTP, the messenger, swift and true,
Links distant lands, old and new.

2. Describe how HTML, CSS, and JS files are “parsed” in the browser.

When browsers send requests to servers for HTML files, those HTML files often contain link elements referencing external CSS stylesheets and script elements referencing external JavaScript scripts.

The browser parses the HTML file first, and that leads to the browser recognizing any link element references to external CSS stylesheets and any script element references to scripts.

As the browser parses the HTML, it sends requests back to the server for any CSS files it has found from link elements, and any JavaScript files it has found from script elements, and from those, then parses the CSS and JavaScript.

The browser generates an in-memory DOM tree from the parsed HTML, generates an in-memory CSSOM structure from the parsed CSS, and compiles and executes the parsed JavaScript.

As the browser builds the DOM tree and applies the styles from the CSSOM tree and executes the JavaScript, a visual representation of the page is painted to the screen, and the user sees the page content and can begin to interact with it.

3. How can you find images to add to a Website?

You can go to Google Images and search for something.

When you find the image you want, click on the image to get an enlarged view of it.

Right-click the image (Ctrl + click on a Mac), choose Save Image As…, and choose a safe place to save your image. Alternatively, copy the image's web address from your browser's address bar for later use.

4. How do you create a String vs a Number in JavaScript?

A string is put into quotes ('') while a number isn't. for example - 
'3' - string
3 - number

5. What is a Variable and why are they important in JavaScript?

A variable is a named storage location that can hold a value or a reference to a value. Variables allow us to store and manipulate data dynamically.

**Introduction to HTML**

1. What is an HTML attribute?

An attribute is provided within the opening tag of an element. Attributes provide extra details about the element, which can be used by browsers or scripts for various purposes.

2. Describe the Anatomy of an HTMl element.

The element is the opening tag, followed by content, followed by the closing tag.

3. What is the Difference between <article> and <section> element tags?

The <article> element is used to represent a self-contained, independent piece of content that can be distributed or reused on its own. 

The <section> element is a more generic container that groups together related content within a document.

4. What Elements does a “typical” website include?

<!doctype html>
<html lang="en-US">
  <head>
    <meta charset="utf-8" />
    <title></title>
  </head>
  <body>
    <p></p>
  </body>
</html>


5. How does metadata influence Search Engine Optimization?

Metadata is data that provides search engines with important information about the content of a webpage. This information helps search engines understand what a page is about and how relevant it is to specific searches.

6. How is the <meta> HTML tag used when specifying metadata?

The <meta> tag is self closing and placed in the head. It's typically used by browsers, search engines, and other web services.  

**How to start to design a Website.**

1. What is the first step to designing a Website?

There are a few questions you should answer before anything else:

- What exactly do I want to accomplish?
- How will a website help me reach my goals?
- What needs to be done, and in what order, to reach my goals?

2. What is the most important question to answer when designing a Website?

What exactly do you want to accomplish is the most important question, becasue it drives everything else.

**Semantics.**

1. Why should you use an <h1> element over a <span> element to display a top level heading?

h1 is a heading (the top heading) for websites and has a semantic value, while span may look like a heading but has no semantic value.

2. What are the benefits of using semantic tags in our HTML?

Some of the benefits from writing semantic markup are as follows:

- Search engines will consider its contents as important keywords to influence the page's search rankings (see SEO)
- Screen readers can use it as a signpost to help visually impaired users navigate a page
- Finding blocks of meaningful code is significantly easier than searching through endless divs with or without semantic or namespaced classes
- Suggests to the developer the type of data that will be populated
- Semantic naming mirrors proper custom element/component naming

**What is JavaScript?**

1. Describe 2 things that require JavaScript in the Browser?

Any time you want a web page to be more than just static information for you to look at.

Interactive maps 

Animations

2. How can you add JavaScript to an HTML document?

JavaScript is applied to your HTML page using the <script> element. 

## Things I want to know more about

More about Javascript 