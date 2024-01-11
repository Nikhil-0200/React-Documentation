What is React ?

React is a javascript library which is used for building user interfaces. 

___________________________________________________________________________________________________________________

Who made React ? 

React is a js library used for building UI, and was developed by facebook. It was initially created by the software engineer at FB and was deployed first time at facebook new's feed in 2011. React has since gained widespeard adoption and is used by many other compnaies for making of an dynamic and interactice UI.

___________________________________________________________________________________________________________________

What is Babel ? 

Babel is a translator which is used to convert the JSX - Javascript XML - (which is a syntax extension for J.S and which allows us to write HMTL like code in J.S), into an old plain J.S which a browser can understand.  

___________________________________________________________________________________________________________________

How does Babel convert html code in React into valid code?

It takes JSX code and convert it into an old plaine J.S code. 

___________________________________________________________________________________________________________________

What is ReactDOM used for? Write an example?

ReactDOM is a like bridge between React Elements and the actual DOM elements. It's job is to take React elements and convert it into an real DOM elements and rendered it on the webpage.

EAXMPLE: 

let element = React.createElement("div",{
    className: "class",
    children: "I am a Div",
})

let reactRoot = ReactDOM.createRoot(document.getElementById("root"));

reactRoot.render(element)

___________________________________________________________________________________________________________________

What are the packages that you need to import for react to work with?

1. Importing of React from react.
2. Import of ReactDOM  from react-dom.

___________________________________________________________________________________________________________________

How do you add react to a web application?

Create React Project:
First of all we will start by creating a new React project using tools like Create React App for a simplified setup.

Install React Packages:
Then will install React and ReactDOM packages using npm.

Then will Open our web browser and go to the specified addressv see our React app.

___________________________________________________________________________________________________________________

What is React.createElement?

React.createElements is used to create elements in react, it same document.createElement in Vanila J.S, but the difference between these two is that document.createElements creates elements and directly manipulate with the DOM, while in react it only create elements and later translated it into an actual DOM elements using ReactDOM.

___________________________________________________________________________________________________________________


What are the three properties that createElement accept?

So, the three properties that createElement accepts in react are:

1. Type (or Element):
The first argument is the type of React Element which you are looking to create, it is a string representing the HTML tag ex- "div", "h1" or etc. or it can be a reference to other React Components. 

2. Props (or Attributes):
The second argument is an object representing the properties of an React Element. Ex- className, style and etc.

3. Children:
The remaining arguments to React.createElements is being added to the children.This can a React elements or a plain text.


___________________________________________________________________________________________________________________

What is the meaning of render and root? 

Render:

Process of converting React components into a format for display.
Utilizes ReactDOM.render() to mount React elements into the DOM.

Root:

HTML element where a React application is mounted.
Commonly identified by an element with the ID "root."
Acts as the starting point for rendering the React component tree.


___________________________________________________________________________________________________________________




