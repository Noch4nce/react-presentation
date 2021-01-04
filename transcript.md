# transcript presentation

## Hello everybody.
### My name is Aleksandt Shestakov. I am a beginner frontend developer. And today I will tell you about React.

### A little bit of history about the React.React was created by Jordan Walke, a software engineer at Facebook. 
### He was inspired by XHP, an HTML component library for PHP. 
### React was first used in a Facebook news feed. It was open-sourced at JSConf in May two thousand thirteen.

### What is React?
### React - most popular library for user interface development. Is open-source library and maintained by Facebook and a big community.
### React can be used to development single page and mobile applications. A single-page application is an app that works inside a browser and does not require page reloading during use. React is only concerned with state management and rendering that state to the DOM.

### React have a programming concept - Virtual DOM. 
### React creates an in-memory data-structure cache, computes the resulting differences, and then updates the browser's displayed DOM efficiently. 
### This process is called reconciliation. This allows the programmer to write code as if the entire page is rendered on each change, while the React libraries only render subcomponents that actually change. This selective rendering provides a major performance boost.

### The library focuses on creating declarative UIs and makes creating interfaces a lot easier by breaking each page into small components. Each section highlighted above is considered a component. 
### A component is a self-contained module that renders some output.React is centered around the concept of components. Your React application will have a root component that after can have childcomponents that create an overall "component tree". Components should render their output based on two things:
* Props - values that are being passed into a component from the outside.
* State - optional and bound to a single instance of a component. The component can pass state down to other components via props.
### There are two ways to create a component
* A component can be described as a function:
* And can also be defined as a JavaScript class:

### React component is easier to create because it uses JavaScript XML. JSX is a language extension JavaScript, a mix of JavaScript and HTML.
### With JSX you can write expressions inside curly braces
### To write HTML on multiple lines, put the HTML inside brackets
### Self-closing tags. JSX follows XML rules, and therefore HTML elements must be properly closed.

### Why you should use React? Because
* Works great for teams, strongly enforcing UI and workflow patterns
* UI code is readable and maintainable
* Componentized UI is the future of web development, and you need to start doing it now.