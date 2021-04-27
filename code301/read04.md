# Controlled Component

In a controlled component, form data is handled by a React component. The alternative is uncontrolled components, where form data is handled by the DOM itself. To write an uncontrolled component, instead of writing an event handler for every state update, you can use a ref to get form values from the DOM.


![img](https://curriculum-content.s3.amazonaws.com/react/react-forms/Image_23_FlowchartControlled.png)

## Controlled Inputs
An input is said to be “controlled” when React is responsible for maintaining and setting its state. The state is kept in sync with the input’s value, meaning that changing the input will update the state, and updating the state will change the input.
![img](https://the-guild.dev/medium/c7455683b79da1438932e5b04bb9cc36.png)

When using React, we generally don’t need to call addEventListener to add listeners to a DOM element after it is created. Instead, just provide a listener when the element is initially rendered.

# Using  Events in React
Keyboard events are pretty standard in web development. Users interact with a web app using three keyboard events:

* onKeyDown
* onKeyUp
* onKeyPress
These events are triggered when users touch, release, or hold keys, and they are used to to process specific user input.

![img](https://packt-type-cloud.s3.amazonaws.com/uploads/sites/3237/2018/12/3702ea56-01ab-4d19-8078-5e1cd4b0e080.png)

# The Conditional (Ternary) Operator Explained
The ternary operator in the react js works in the same way how it works in the Javascript. With the help of the ternary operator, we can display the contents on the basis of one condition where everything depends on the condition true and false we can put the contents on the conditional basis. We can take an example of a ternary operator like we fetch data from server and data is empty then we can use a data check ternary operator where if data is empty or server is returning empty date then display some static data so that it will look good instead of displaying an empty to end-users.
![img](https://media.geeksforgeeks.org/wp-content/uploads/20190920114837/Flow-Chart-of-Conditional-or-Ternary-Operator-__-in-C_C.jpg)