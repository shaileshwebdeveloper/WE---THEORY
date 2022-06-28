# WE---THEORY

1. What is the difference between Props and State?

State
The state is an updatable structure that is used to contain data or information about the component and can change over time. The change in state can happen as a response to user action or system event. It is the heart of the react component which determines the behavior of the component and how it will render. A state must be kept as simple as possible. It represents the component's local state or information. It can only be accessed or modified inside the component or by the component directly.

Props
Props are read-only components. It is an object which stores the value of attributes of a tag and work similar to the HTML attributes. It allows passing data from one component to other components. It is similar to function arguments and can be passed to the component the same way as arguments passed in a function. Props are immutable so we cannot modify the props from inside the component.

2.  Explain the useState API?

The useState() is a Hook that allows you to have state variables in functional components . so basically useState is the ability to encapsulate local state in a functional component. React has two types of components, one is class components which are ES6 classes that extend from React and the other is functional components. Class components a Component and can have state and lifecycle methods: class Message extends React. The  useState hook is a special function that takes the initial state as an argument and returns an array of two entries.  UseState encapsulate only singular value from the state, for multiple state need to have useState calls.

3.  Explain the how map, filter, reduce work

The map() function is used to iterate over an array and manipulate or change data items. In React, the map() function is most commonly used for rendering a list of data to the DOM.

Filtering in React is pretty much what it says it is. It’s the process of looping through an array and including or excluding elements inside that array based on a condition that you provide.

As the name suggests it reduces the number of values in an array to one. we have access to the array's previous value apart from its current value and index.
we will send the accumulator's start value to the callback function; so when we first start previous value will be the same as the accumulator's start value
