# Learn-React-fast
Are you an impatient learner like me? This is the React tutorial for you.

# Before we start...
I’m writing this because of two reasons: The first is to ensure I know React so well that I can write a tutorial. The second is that I consider most tutorials to be very slow and I like going fast and straight to action, so here you will see little text just to know what is going on.

# Introduction
React.js is an Open Source library developed by Facebook Developers, for building User Interfaces (UI). React makes user interfaces very easy to build by cutting each page into pieces. We call these pieces **components**.

<img align="middle" src="https://github.com/LeWanderer/Learn-React-fast/blob/draft/images/components.png?raw=true" alt="Google components">

React is fairly easy to understand and at this moment has an excellent reputation and a great community. It supports ES6 and can perform client-side as well as server side rendering.

**Note:** Represents View in Model-View-Controller architectural pattern, that means you will need more tools in the future to cover the Model and Controller part.

## Virtual DOM
<img align="middle" src="https://github.com/LeWanderer/Learn-React-fast/blob/draft/images/DOM%20and%20Virtual%20DOM.png?raw=true" alt="DOM and Virtual DOM comparison">

Consider a page displaying a list containing 10 items and one is getting updated. DOM will rebuild the entire list making it work 10 times more than what is necessary.

Virtual DOM is an abstract, lightweight copy of DOM. It can be changed as and when we want and then can be saved to the real DOM. Whenever a change occurs, Virtual DOM efficiently rerenders the DOM. It is much faster than DOM. It has the same properties as a real DOM object.

## JSX
<img align="middle" src="https://github.com/LeWanderer/Learn-React-fast/blob/draft/images/JSX%20example%201.png?raw=true" alt="JSX Example 1">
<img align="middle" src="https://github.com/LeWanderer/Learn-React-fast/blob/draft/images/JSX%20example%202.png?raw=true" alt="JSX Example 2">

React uses a syntax extension of JavaScript called JSX that allows you to write HTML directly within JavaScript. It is not necessary to use it but I recommend it as it makes your code more readable.

![#f03c15](https://placehold.it/15/f03c15/000000?text=+) `However, because JSX is not valid JavaScript, JSX code must be compiled into JavaScript. The transpiler Babel is a popular tool for this process.` 

**Note**: You can use Javascript inside HTML (JSX) writing {code} (Second picture).

# Basic
Building Blocks of ReactJS
A typical ReactJS program constitutes:
- Components (Next section!).
- Elements: An element describes what you want to see on the screen. Unlike browser DOM elements, React elements are plain objects, and are cheap to create. In the official document they talk more about them, but I consider them a waste of time so I’m not gonna cover them.
<img align="middle" src="https://github.com/LeWanderer/Learn-React-fast/blob/draft/images/Element%20example.png?raw=true" alt="Element example">

- Props
- States
- Functions

## What is a React Component?
Javascript function/class that represents a piece of a webpage. To build a page, we call these functions/classes in a certain order, put the result together, and show it to the user.

### Function component
<img align="middle" src="https://github.com/LeWanderer/Learn-React-fast/blob/draft/images/Function%20component%201.png?raw=true" alt="Function component example 1">
<img align="middle" src="https://github.com/LeWanderer/Learn-React-fast/blob/draft/images/Function%20component%202.png?raw=true" alt="Function component example 2">



### Class component
<img align="middle" src="https://github.com/LeWanderer/Learn-React-fast/blob/draft/images/Class%20component.png?raw=true" alt="Function component example 1">

If we call the OurFirstComponent() function we’ll get back a bit of JSX. We can use something called ReactDOM.render(Component,locationForComponent) to put it on the page.


### Input example
<img align="middle" src="https://github.com/LeWanderer/Learn-React-fast/blob/draft/images/ReactDOM.render%20example.png?raw=true" alt="ReactDOM.render() example">

### Output example
<img align="middle" src="https://github.com/LeWanderer/Learn-React-fast/blob/draft/images/ReactDOM.render%20test%20result.png?raw=true" alt="ReactDOM.render() result">


### When to use Function or Class component
The main difference between Function or Class is that Classes have more features, like state, lifecycle, handling events, etc. You will learn about them soon

