# Read04

## React Docs - Forms

### What is a ‘Controlled Component’?
- A Controlled Component is one that takes its current value through props and notifies changes through callbacks like onChange

### Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.
- Since handleChange runs on every keystroke to update the React state, the displayed value will update as the user types.

### How do we target what the user is entering if we have an event handler on an input field?
- When you need to handle multiple controlled input elements, you can add a name attribute to each element and let the handler function choose what to do based on the value of event.target.name.

## The Conditional (Ternary) Operator Explained

### Why would we use a ternary operator?
- to simplify your if-else statements that are used to assign values to variables

### Rewrite the following statement using a ternary statement
  if(x===y){
 console.log(true);
  } else {
 console.log(false);
  }

x===y? true
         : false
