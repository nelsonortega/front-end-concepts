# Javascript

### Closures 

```
function init() {
  var name = 'Nelson' // name is a local variable created by init
  
  function displayName() { // displayName() is an inner function, a closure
    alert(name) // use variable declared in the parent function
  }
  
  displayName()
}

init()
```

### Hoisting 

### const - var - let

# React

### Optimize React App
### Virtual DOM
Update the DOM can be expensive and time-consuming since you have to re-render every time there is a change. With virtual DOM, every change on props, state, etc, will render this change first on the virtual DOM, and then render the new element on the real DOM with the minimum changes possible.
### Class vs Functional Components
### Higher Order Components


# Typescript

### Generics
