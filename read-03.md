Read: Class 03

# Readings: HTML Lists, Control Flow with JS, and the CSS Box Model

## Learn HTML

1. When should you use an unordered list in your HTML document?
- < ul > elements are used for grouping a collection of items that do not have a numerical ordering, and their order in the list is meaningless. Typically, unordered-list items are displayed with a bullet, which can be of several forms, like a dot, a circle, or a square.

2. How do you change the bullet style of unordered list items?
- You need to use CSS to change the style. You can use list-style-type and the following values to edit:
- disc: Filled circle (default)
- circle: Empty circle
- square: Filled square
- none: No bullet

3. When should you use an ordered list vs an unorder list in your HTML document?
- You should use and ordered list when you want to rank something or put it in order. It uses numbers instead of bullet points, so it's easier to understand. 

4. Describe two ways you can change the numbers on list items provided by an ordered list?
- You can change in CSS by using values for list-style-type. Here are some examples:
- decimal: 1, 2, 3 
- lower-roman: i, ii, iii
- upper-roman: I, II, III
- lower-alpha: a, b, c
- upper-alpha: A, B, C
- lower-greek: α, β, γ


## Learn CSS

1. Describe the CSS properties of margin and padding as characters in a story. What is their role in a story titled: “The Box Model”?

- Margin (Marge): Marge is a friendly and outgoing character in our story. She's the space-loving aunt of our protagonist, Padding. Marge is always eager to make sure everyone has enough room to breathe and move around comfortably.

- Padding (Paddy): Paddy is the protagonist of our story. He's a bit more reserved and introspective compared to his aunt, Marge. Paddy provides a cushioning layer of comfort and security for everyone he meets.

  (got help with chatgpt on this one)

2. List and describe the four parts of an HTML elements box as referred to by the box model.

- Content box: The area where your content is displayed; size it using properties like inline-size and block-size or width and height.

- Padding box: The padding sits around the content as white space; size it using padding and related properties.

- Border box: The border box wraps the content and any padding; size it using border and related properties.

- Margin box: The margin is the outermost layer, wrapping the content, padding, and border as whitespace between this box and other elements; size it using margin and related properties.


## Learn JS

1. What data types can you store inside of an Array?

- you can store numbers, strings, booleans, objects, arrays and functions in an array.

2. Is the people array a valid JavaScript array? If so, how can I access the values stored? If not, why?

- It is a valid array, and you can use array indexing to access the values stored.

const people = [['pete', 32, 'librarian', null], ['Smith', 40, 'accountant', 'fishing:hiking:rock_climbing'], ['bill', null, 'artist', null]];

3. List five shorthand operators for assignment in javascript and describe what they do.

- += Addition assignment
- -= Subtraction assignment
- /= Division assignment
- *= Multiplication assignment
- %= Remainder assignment

4. Read the code below and evaluate the last expression and explain what the result would be and why.

- It would be '10dog'

5. Describe a real world example of when a conditional statement should be used in a JavaScript program.

- Online Shopping Cart. You can use if and else statments to apply discounts to products. If you reach a certain threshold, the discount will apply.

6. Give an example of when a Loop is useful in JavaScript.
-   Processing a list of user messages. Users can send messages, and you want to implement a feature that checks each message for certain keywords. If a keyword is found, you want to take a specific action.