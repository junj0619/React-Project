# React-Project

### What is React? ###
React is JavaScirpt library for building fast and interactive user interfaces. 
It was developed at Facebook in 2011 and currently it's the most popular JavaScript library for user interfaces.

At the heart of all React applications are components, a component is essentially a piece of a user interface. So when building applications with React, 
we build a bunch of independent, isolated, reusable components, and then compose them to build complex user interfaces. 
Every React application at least has one component which refer to root component. This component include entire application as well as other child components.
So evey React application is tree of components. 

```javascript

class Component {
  state = {};
  render() {
  
  }
}

```
In terms of implementation, a component is typically implemented as a JavaScript class that has some ***states*** and a ***render method***.
The state is here is the data that we want to display when the component is rendered, and the render method is responsible for descripbing what the UI should looks like.
The output of this render method is a react element, which is a simple plain JavaScript object that maps to a DOM element. 
It is not real DOM element, it's just a plain JavaScript Object that represents the DOM element in memory.
So React keeps a lightweight representation of the DOM in memory which we refer to as the virtual DOM. Unlike real DOM these virtual DOM is cheap to create it.

When we change the state of a component, we get a new React element. React will then compare this element and its children with previous one, it figures out what has changed, and then it will update a part of the real DOM
to keep it in sync with the virtual DOM. So that means when building applications with React unlike JavaScript and JQuery we no longer have to work DOM API in browsers.
In other words, we no longer have to write code in query or manipulate the DOM, or attach event handlers to DOM elements. 

You simplily change the state of our components and React will automatically update the DOM to match that state.
And that's exactly why this library is called React because when the state changes React essentially reacts to the state change and updates the DOM.

### React or Angular? ###
Both React and Angular are similar in terms of component based architecture.
However, ***Angular is a framework or a complete solution***, while ***React is a library***.
It only takes care of rendering the view and making sure the view is in sync with the state. 
That's all React does, nothing less, no more. For this very reason, React has a very small API to learn. 
So when building applications with React, we need to use other libraries or things like routing, or calling http service and so on.
But this is not necessarily a bad thing, because you get to choose the libraries that you prefer. 

As opposed to being fixed with what Angular gives you, which often breaks from one version to another.


### Set up React Environment ###
1. Install Node.js
2. Go to Terminal, run ***sudo npm i -g create-react-app@1.5.2***
3. Open VS Code
4. Install Simple React Snippets
5. Install Prettier - Code formatter
6. Turn on formatOnSave to Yes



