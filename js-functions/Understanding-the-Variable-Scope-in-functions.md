```ngMeta
name: Understanding the Variable Scope in functions
```

# Understanding the Variable Scope in functions

variables declared within a function have local scope that means they cannot be viewed or used from outside of that function, as shown in the example below:

```javascript

// Defining function

function greetWorld() {
 var greet = "Hello World!";
 console.log(greet);
}
 
greetWorld(); // Outputs: Hello World!
 
console.log(greet); // Uncaught ReferenceError: greet is not defined
 

```

See in the above example, if you see greet is declared inside a function and we tried to print it outside. So, it gave a Reference error.So, here we have to know that greet has local scope(inside the function block). 
 
However, any variables declared in a program outside of a function have global scope(defined outside the function block) i.e. it will be available to the whole file, whether that variable is inside a function or outside. Here's an example:

```javascript

var greet = "Hello World!";
// Defining function
function greetWorld() {
  console.log(greet);
}
greetWorld();  // Outputs: Hello World!
console.log(greet); // Outputs: Hello World!

```