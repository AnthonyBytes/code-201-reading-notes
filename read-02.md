Read: Class 02

**Why does this topic matter as it relates to what we are studying in this module?**
- This topic is very important for building a strong developer foundation. Before we can learn more complex coding, we need to have a strong understanding of HTML, CSS and JavaScript.

**Introduction to HTML** - HTML Text Fundamentals. HTML Advanced Text Formatting.
1. Why is it important to use semantic elements in our HTML?

    Semantics give text meaning, so the browser knows how to display it correctly. 

2. How many levels of headings are there in HTML?

    There are six heading elements: h1, h2, h3, h4, h5, h6. Each element represents a different level of priority, with h1 being the highest and h6 being the lowest.

3. What are some uses for the sup and sub elements? 

    The superscript and subscript can be used when you are marking up items like dates, chemical formulae, and mathematical equations. This will make sure they have the correct meaning.

4. When using the <abbr> element, what attribute must be added to provide the full expansion of the term?
When using the <abbr> element, you should add the title attribute to provide the full explanation of the term. 


**Learn CSS** - How CSS Is Structured.
1. What are ways we can apply CSS to our HTML?

    You can create an external stylesheet with a .css extension. You can create an internal stylesheet that resides within your HTML using < style > inside the < head >. You can create inline styles by puting a style attribute in an element.

2. Why should we avoid using inline styles?

    It is the least efficient implementation of CSS for maintenance. One styling change might require multiple edits within a single web page. Second, inline CSS also mixes (CSS) presentational code with HTML and content, making everything more difficult to read and understand. Separating code and content makes maintenance easier for all who work on the website.

3. Review the block of code below and answer the following questions:
- What is representing the selector?
    
    h2

- Which components are the CSS declarations?

    color: black;
    padding: 5px;

- Which components are considered properties?
   
      color 
      padding

   *h2 {*
     *color: black;*
     *padding: 5px;*
   *}*

**Learn JS** -  JavaScript Basics
1. What data type is a sequence of text enclosed in single quote marks?

    string

2. List 4 types of JavaScript operators.

    Addition (+), subtraction (-), multiplication(*), division(/), assignment(=), strict equality(===), not(!), does-not-equal (!==)

3. Describe a real world Problem you could solve with a Function.

    You can create a online retailer that uses functions to add things to a virtual cart, and allows the user to pay and ship their items.

Making Decisions In Your Code – Conditionals.
1. An if statement checks a __ and if it evaluates to ___, then the code block will execute.

    Condition, true

2. What is the use of an else if?

    This allows you to chain extra choices or outcomes to your statements. If when the function is run, if the first statement is not true, it will go to the else if statement. 

3. List 3 different types of comparison operators.

    === strictly equal
    
    !== Strictly-not-equal
    
    < Less than
    
    .> greater than 

4. What is the difference between the logical operator && and ||?

    && represents AND. This allows you to chain together two or more expressions so that all of them have to individually evaluate to true for the whole expression to return true.
    
    || represent OR. This allows you to chain together two or more expressions so that one or more of them have to individually evaluate to true for the whole expression to return true.