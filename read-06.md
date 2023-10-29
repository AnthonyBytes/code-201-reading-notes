Read: Class 06

# Readings: Problem Domain, Objects, and the DOM

## Why this topic matters


It's improtant because its teaching us about objects which are key to data organization and code reusability. Learning about the DOM is important because it is a fundamental concept in web development that provides a structured representation of a web page, which allows JavaScript to interact with the webpage.

## JavaScript Object Basics

1. How would you describe an object to a non-technical friend you grew up with?


An object is a collection of related data and/or functionality. These usually consist of several variables and functions (which are called properties and methods when they are inside objects). You can think of it like creating and folder, and within that folder is list all of the qualities in that folder. Thes are contained in the folder, which is now an object. 


2. What are some advantages to creating object literals?


Object literal is when you literally write out the object contents. It is very common to create an object using an object literal when you want to transfer a series of structured, related data items in some manner, for example sending a request to the server to be put into a database. Sending a single object is much more efficient than sending several items individually, and it is easier to work with than an array, when you want to identify individual items by name.


3. How do objects differ from arrays?


They are similar, but objects are used to group related data together using key-value pairs, while arrays are used to store ordered collections of data that can be accessed by numerical index. 


4. Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation.


Dot notation is generally preferred over bracket notation because it is more succinct and easier to read. However there are some cases where you have to use square brackets. For example, if an object property name is held in a variable, then you can't use dot notation to access the value, but you can access the value using bracket notation.


5. Evaluate the code below. What does the term this refer to and what is the advantage to using this?


It defines a dog with various properties like name, age and color. The advantage to using 'this' is that it allows you to access properties of the objects. This also makes the code more flexible and reusable. 

const dog = {
  name: 'Spot',
  age: 2,
  color: 'white with black spots',
  humanAge: function (){
    console.log(`${this.name} is ${this.age*7} in human years`);
  }
}

## Introduction To The DOM

1. What is the DOM?


The Document Object Model (DOM) is a programming interface for web documents. It represents the page so that programs can change the document structure, style, and content. The DOM represents the document as nodes and objects; that way, programming languages can interact with the page.


2. Briefly describe the relationship between the DOM and JavaScript.


The DOM is not a programming language, but without it, the JavaScript language wouldn't have any model or notion of web pages, HTML documents, SVG documents, and their component parts. Instead it is a Web API used to build websites.

## Thins I want to know more about

- I want to learn more about the different types of objects and when to use them
- I would also like to more about the Dom.