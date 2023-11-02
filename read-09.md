Read: Class 09

# Readings: Forms and JS Events

## Why is this important

- 

## HTML Forms

1. Why are forms so important in web development?

Web forms are one of the main points of interaction between a user and a website or application. Forms allow users to enter data, Web forms are one of the main points of interaction between a user and a website or application. Forms allow users to enter data. They are important for collecting user data, which most sites use in some way (like siginng in, provided contact details, etc.)

2. When designing a form, what are some key things to keep in mind when it comes to user experience?

- Think like a user
- Have strong info architecture
- label placement
- Input optimization
- Clear labels
- Efficient fields description


3. List 5 form elements and explain their importance.

- < Form > a container that groups together form controls like input fields, buttons, etc.
- < Fieldset > groups related form controls together.
- < legend > used inside a < fieldset > to provide a title or description for the group of form controls.
- < label > provides a label or description for an input element.
- < button > used to create clickable buttons. 

## Learn JS

1. How would you describe events to a non-technical friend?

Events are things that happen in the system you are programming, which the system tells you about so your code can react to them. For example, if the user clicks a button on a webpage, you might want to react to that action by displaying an information box.


2. When using the addEventListener() method, what 2 arguments will you need to provide?

- Event Type - This is a string that specifies the type of event you want to listen for. 
- Event Listener Function - This is the function that will be executed when the specified event occurs. 

3. Describe the event object. Why is the target within the event object useful?

The event object is an object that contains information about an event that has occurred. It is automatically passed as an argument to the event handler function when an event is triggered. 

4. What is the difference between event bubbling and event capturing?

Event bubbling and event capturing are two phases in the DOM. In event bubbling, when an event occurs on an element, it triggers the event handlers on the innermost element first and then goes through its ancestors. Event capturing is the opposite, where the event starts from the root element and goes down to the target element.

## Things I want to know more about

- More about forms and how to create different types. 