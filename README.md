# js_interesting

    In a child class constructor, this cannot be used until super is called.
    ES6 class constructors MUST call super if they are subclasses, or they must explicitly return some object to take the place of the one that was not initialized.

## var_let_const

https://www.w3schools.com/react/react_es6.asp

### var

var has a function scope, not a block scope.
If you use var outside of a function, it belongs to the global scope.

If you use var inside of a function, it belongs to that function.

If you use var inside of a block, i.e. a for loop, the variable is still available outside of that block.

### let

let has a block scope.
let is the block scoped version of var, and is limited to the block (or expression) where it is defined.

If you use let inside of a block, i.e. a for loop, the variable is only available inside of that loop.

### const

const is a variable that once it has been created, its value can never change.

const has a block scope.

### JSX

JSX stands for JavaScript XML.

JSX allows us to write HTML in React.

JSX makes it easier to write and add HTML in React.
JSX is an extension of the JavaScript language based on ES6, and is translated into regular JavaScript at runtime.

Components are like functions that return HTML elements.

Components come in two types, Class components and Function components, in this tutorial we will concentrate on Class components.

The constructor function is where you initiate the component's properties.

In React, component properties should be kept in an object called state.

The constructor function is also where you honor the inheritance of the parent component by including the super() statement, which executes the parent component's constructor function, and your component has access to all the functions of the parent component (React.Component).

Another way of handling component properties is by using props.

Props are like function arguments, and you send them into the component as attributes.
Props are arguments passed into React components.
React Props are like function arguments in JavaScript and attributes in HTML.

To send props into a component, use the same syntax as HTML attributes:

Props are passed to components via HTML attributes.

Props are also how you pass data from one component to another, as parameters.

React is all about re-using code, and it can be smart to insert some of your components in separate files.

Note that the file must start by importing React (as before), and it has to end with the statement export default Car;.
