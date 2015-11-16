####Name: Shenisis Kirkland
####ScriptEd
####Topic: JavaScript

* Explain what a function is. Give an example.
* a code that performs a task Ex) function multiply(x,y) { return x*y; }
* Explain what a parameter is. Give an example.
* a local scope that is contained within parenthesis of function. Ex) function poop(x) 
* When we want to look up what a word means, we go to a dictionary. Similarly, when we want to look up what a standard JavaScript function does, we look at console.log.
* In the following piece of code, what variable(s) are in scope at Point A, Point B, and 
Point C?

```
var hooligan = true;

function hva() {
  var num = 3;
  // Point A encopasses hooligan and num
}

function rocks() {
  var str = "scope";
  // Point B encompasses str and hooligan
}

// Point C encompasses hooligan
```
* What does the following code print?
it prints Inside the function, x is 10
Outside the function, x is 7
```
var x = 7;

function someFunction() {
  var x = 10;
  console.log("Inside the function, x is " + x);
}

console.log("Outside the function, x is " + x);
someFunction();
```
* Write a function that returns the result of the following equation: 5a^2 + 4b + c. You should use the pow() function. Your function should take in three parameters (a,b,c).
* function equation(a,b,c) {
*return 5 * Math.pow(a,2) + 4*b + c;
}

####Some review
* Close this HTML element (remember HTML??): `<h2> My Books` </h2>
* What HTML element is used to create an **ordered list** of items? <ul>
* Write a CSS rule that will make only the word *Adams* red: 
`<span id="first">Washington </span><span id="second">Adams </span><span id="third>Jefferson</span>"`
