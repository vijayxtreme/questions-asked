# Front End JavaScript & JQuery

## Javascript (needs updating for ES6)

- Difference between == and ===, one compares two values, the other compares types 
- Difference between window.onload and $(document).ready()
- Document.ready waits until all scripts have loaded, while load loads page in order of the scripts that have run
- Explain Inheritance / Prototypes
  - Almost everything is an object in javascript.  Every object has a constructor property and a prototype property→ the prototype is the constructor function that created the object which we can add methods on, while the constructor property is the what was used to create the object
- What is a string + a number type produce?  (A new string→ coerced string)
- What is object reflection?
  - Being able to look through ones own properties and methods
- What is the hasOwnProperty method?  Typeof? Object.create?  Object.assign?
- How do arrays work in Javascript?  Associative arrays?  Are you familiar with hashes to search key/value pairs?
- How do you declare an object in Javascript?
- What is Closure? (Encapsulation)
  - Relates to function scope, where a function has memory access to its internal values and properties, and can be store in a variable for later use.
- Are closure variables passed by reference or by value?
- What is Event Bubbling?
- Where an eventHandler is applied on every element from deep down to up
- Apply vs Call in Javascript (why do you use these functions, what do they do?)
- apply-> to this obj, with an array, call→ apply to some obj with args
- Explain Map, Filter, Reduce; write the code to create these functions
- What is ‘this’ in Javascript?  How do you determine scope?
- What are constructors?  How do you use them?
- What is the constructor invocation pattern?
- What is the function invocation pattern?
- What are ‘arguments’ in Javascript?
- How would you fire an Ajax call without using JQuery?  (How would you handle this in different browsers, like IE?)
- Difference between an object and JSON in JavaScript
  - http://stackoverflow.com/questions/2904131/what-is-the-difference-between-json-and-object-literal-notation 
- Difference between JSON and JSONP
  - http://stackoverflow.com/questions/2887209/what-are-the-differences-between-json-and-jsonp 
  - JSONP has a string padding around it, so you can write functions in JSONP and call them on your page when the JSONP loads
- How do you use a ternary operator, and is it a statement or an expression? Why?
- Have you used Modules, if so what do you use? (Mixins, Plugins (aka userAgent))
- What is a callback function?  How does it work?
- In Javascript, do you pass by variable or by reference (or both-- what are the cases?)
- Sort an array using an object so no duplicates arise (Yahoo Question)
  - http://www.programcreek.com/2013/01/leetcode-remove-duplicates-from-sorted-array-java/ 
  - http://stackoverflow.com/questions/9355403/deleting-duplicates-on-sorted-array 
- Write a method to sort an object (evaluate its efficiency)
- Reverse a string?
  - http://www.programmingsimplified.com/c-program-reverse-string 
- Write a hide / show method without using JQuery
- How would you edit a string so it’s 20 chars or less and replace it with an ellipsis?
- How would you sort a JavaScript object by property ASC & DESC?
- How would you filter an array so it only contained objects with key?
- How would you reduce an array?
- What is blocking? (Hint: think callback functions)
- Is Javascript compiled or interpreted as a language?
- Compiled (2 passes, first read thru, then store variables), but could be interpreted too with eval statement
- What is the Queue pattern (Event queue)? Or event delegation?
- What is the typeof an HTMLElement on the DOM?
- How would you change the color of an element in the DOM without using JQuery?
  - style property
- What are promises in JavaScript, how do you use them?
- What is the async/await function all about?
- What are generators and how can we use them?  How about iterators?
- What are JavaScript modules?
- What’s the difference between AMD and CommonJS?  How about UMD? 
- How were JavaScript modules developed in the old days of JQuery?
- What are regular expressions and how can they help us speed up workflow?
- Give some example usage


## Intermediate JavaScript

- Write your own foreach method
- Write your own filter, map and reduce method
- What is the point of extending an object?  How do you do it?
- What's memoizing in JS? Give an example
- What does currying mean? Give an example
- How would you build your own hash in JS without using an object? Give a basic implementation
- Create your own array data structure with JS, support methods for pop, push, slice
- Shallow vs deep copy over an object / array -- show examples and explain.
- Why is cloning an element useful over just using a reference?
- What's the difference between passing by reference and passing by value?
- What is strict mode in JavaScript?
- What is the Object.create method? Give an example
- What is the Object.keys method? Object.values method? Give examples

## JQuery
- Tell me three ways to declare a JQuery variable (e.g. $, JQuery)
- What is the JQuery load function used for?
- How to make an Ajax call / why would you use it?
- How do you use a JQuery .bind?  Why would you use it?
- Changes in JQuery (between 1x and 2x)
- Queueing
- Difference between JSON & JSONP -- Illegal Reference Error-- What is it?
- What are some advantages and disadvantages to using JQuery?  Can you rely on it for everything?  When would you not want to use JQuery?
- Create a drop down list using jQuery

## Other Libraries

- Are you familiar with -- NodeJS, Ember, KnockoutJS, RequireJS, BackboneJS, UnderscoreJS, AngularJS, Rhino, Greensock? CartJS?
- What experience do you have working with (above library)?
- Can you show us some work with BackboneJS, NodeJS?
- What libraries do you know beyond just JQuery?
- What libraries do you not like and why? 
- JQuery Mobile → too many CSS elements, not easily able to control
- Can you write in pure Javascript (no JQuery) if you had to?
- How would you animate a div to move across the screen in JS without JQuery?  (setInterval or setTimeout)
- What is MVC?
- What are some frameworks that use MVC and can you pick your framework to describe?
- What sort of templating tools do you use with your code?
- What is the _.each function used for? Spend time w/LoDash library
