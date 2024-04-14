# About REACT

<p>In 2013, a JavaScript library was introduced to the world and changed the course of web dev forever. React is a JavaScript library used for building websites with reusable components. It lets you create a multi-page website and not have to update things repeatedly in different files.<p>

Some of React's most useful features include:

<ul>
<li>An interesting flavor of JavaScript called JSX.</li>
<li>An efficient way to update parts of your site.</li>
<li>It's fast and scalable!</li>
</ul>

<p> Hot reloading is a feature in React that allows developers to instantly see changes made to their code in real time. The output gets updated with every character we type in the code editor.</p>
<p>Before React, updating your website meant changing the same element in every file. With React, you change a single element in one place and that change applies everywhere!</p>

## Brief history

<p>Initially developed by a small team at Facebook for their Newsfeed feature, React was eventually open-sourced to the public in 2013. While still maintained by Facebook, React has grown a large following of open source contributors</p>

## React Syntax

<p> JSX is like "syntactic sugar" because it looks like HTML, but it's actually JavaScript! We can define JSX either in a .js file or a .jsx file. For this course, we're using .js files! When you run your code, JSX gets transpiled, or translated into plain JavaScript and then read by the browser.</p>

<p> Sometimes referred to as "JavaScript Syntax Extension", parts of JSX are disguised as HTML. When you run a React app, the HTML-like parts are transpiled into browser-readable JavaScript! JSX can also be written as a function that returns markup. JSX is only valid if everything is wrapped under a single element. This is the power of React that allows us to use a function to return our website's markup! </p>

## Building Blocks

<p> If JSX is like the "language" of React, then components are like the "building blocks" of the website's user interface. Components are defined like functions that return JSX content. <p>

<p>Components are pieces of JSX that make up most of the website. They can be anything from labels to buttons to navigation menus.</p>

A few things to consider:

<ul>
<li>The name of the component must begin with a capital letter, and be in "PascalCase".</li>
<li>The JSX returned by a component is bundled under a single element and rendered as a single part, or component, of a website.</li>
</ul>

## Attributes

<p> Just like with HTML, JSX supports attributes for applying cool settings to your content. Any valid HTML and their associated attributes are supported in JSX…mostly. For example: img tag with common attributes src and alt</p>

```
const selfie = <img src="username/camera/recents/today.png" alt="a selfie" />
```

<p>Unlike HTML, there are some important naming differences with JSX. One of the most widely used attributes in HTML is class. However, the JSX-equivalent to this is className. In JavaScript, "class" is actually a reserved keyword. Therefore, we use className! </p>

<p>  In React, "attributes" are more commonly known as props. Props are pieces of data that are given to JSX elements for them to use or pass from parent to child component. You can use any data type for props, including objects and functions! </p>

## Parents and Children

<p> No matter how many components are in a React app, they all trace back to a single root. React apps are like upside down trees with a root element at the top. Underneath, the root contains an <"App"> component, which also contains components. These components share a parent-child relationship. Parent components hold one or more child components In a React app, we can pass prop data down from parent to child component. </p>

## State

<p> For React components, props are ideal if the data isn't expected to change after being set. But what if our component is using data that might change? A component's state is the data that can change over time. </p>
