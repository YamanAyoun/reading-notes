# React 1

React is a JavaScript library, and so we’ll assume you have a basic understanding of the JavaScript language. 
If you don’t feel very confident, we recommend going through a JavaScript tutorial to check your knowledge level and enable you to follow along 
this guide without getting lost.

## Why JSX?
* React embraces the fact that rendering logic is inherently coupled with other UI logic: how events are handled, how the state changes over time, and how the data is prepared for display.

* Instead of artificially separating technologies by putting markup and logic in separate files, React separates concerns with loosely coupled units called “components” that contain both. We will come back to components in a further section, but if you’re not yet comfortable putting markup in JS, this talk might convince you otherwise.

* React doesn’t require using JSX, but most people find it helpful as a visual aid when working with UI inside the JavaScript code. It also allows React to show more useful error and warning messages.

## Rendering Elements
Elements are the smallest building blocks of React apps.

An element describes what you want to see on the screen:

``const element = <h1>Hello, world</h1>;``

## Rendering an Element into the DOM
Let’s say there is a <div> somewhere in your HTML file:

``<div id="root"></div>``

To render a React element, first pass the DOM element to ReactDOM.createRoot(), then pass the React element to root.render():

``const root = ReactDOM.createRoot(
  document.getElementById('root')
);
const element = <h1>Hello, world</h1>;
root.render(element);``

## Components and Props
Conceptually, components are like JavaScript functions. They accept arbitrary inputs (called “props”) 
and return React elements describing what should appear on the screen.

The simplest way to define a component is to write a JavaScript function:

``function Welcome(props) {
  return <h1>Hello, {props.name}</h1>;
}``

## State and Lifecycle

Consider the ticking clock example from one of the previous sections. In Rendering Elements, we have only learned one way to update the UI. We call root.render() to change the rendered output:

  
```
const root = ReactDOM.createRoot(document.getElementById('root'));

function tick() {
  const element = (
    <div>
      <h1>Hello, world!</h1>
      <h2>It is {new Date().toLocaleTimeString()}.</h2>
    </div>
  );
  root.render(element);
}

setInterval(tick, 1000);
```
## Utility First CSS
* An approach to writing Cascading Style Sheets (CSS) that emphasizes the creation of small, single-purpose utility classes for styling individual elements on a web page. These utility classes are atomic and have single responsibilities, making it easy to compose complex styles by combining them. 

* Utility-first CSS frameworks like Tailwind CSS provide a predefined set of utility classes for rapid development, responsive design, and maintainability. While it can speed up development and improve code consistency, it requires learning a new set of class names and conventions, which can have a learning curve. 

## What is Next.js?
Next.js is a flexible React framework that gives you building blocks to create fast web applications.

But what exactly do we mean by this? Let’s spend some time expanding on what React and Next.js are and how they can help.

Building Blocks of a Web Application
There are a few things you need to consider when building modern applications. Such as:

* User Interface - how users will consume and interact with your application.
* Routing - how users navigate between different parts of your application.
* Data Fetching - where your data lives and how to get it.
* Rendering - when and where you render static or dynamic content.
* Integrations - what third-party services you use (CMS, auth, payments, etc) and how you connect to them.
* Infrastructure - where you deploy, store, and run your application code (Serverless, CDN, Edge, etc).
* Performance - how to optimize your application for end-users.
* Scalability - how your application adapts as your team, data, and traffic grow.
* Developer Experience - your team’s experience building and maintaining your application.
