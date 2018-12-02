## JavaScript is ...
a `dynamic`, `weakly typed`, `prototype-based` language with `first-class functions`.

## Planning
| Sr.No. | Topic | Read | 
| ---- | ----- | ---- | 
| 1. | Basic JavaScript | [Basic JavaScript](https://github.com/ps0305/Javascript-Algorithms-And-Data-Structures/tree/master/Basic%20JavaScript) 
| 2. | ES6 | [ES6](https://github.com/ps0305/Javascript-Algorithms-And-Data-Structures/tree/master/ES6) | 
| 3. | Debugging | [Debugging](https://github.com/ps0305/Javascript-Algorithms-And-Data-Structures/tree/master/Debugging) |
| 4. | Algorithms Scripting | [Algorithms Scripting](https://github.com/ps0305/Javascript-Algorithms-And-Data-Structures/tree/master/Basic%20Algorithm%20Scripting) |
| 5. | Object oriented Programming | [Object oriented Programming](https://github.com/ps0305/Javascript-Algorithms-And-Data-Structures/tree/master/Object%20Oriented%20Programming) |
| 6. | Functional Programming | [Functional Programming](https://github.com/ps0305/Javascript-Algorithms-And-Data-Structures/tree/master/Functional%20Programming) | 
| 7. | Intermediate Algorithm Scripting| [Intermediate Algorithm Scripting](#) |




## JS is Dynamic
```js
//Compilation and execution happen together.

var propMap = {
  val: "value", html: "innerHTML"
};

for(var fnName in propMap){
	
  $.prototype[fnName] = (function(prop){
  	return function(){
  	  return this[prop];
  	}
  })(propMap[fnName]);
}
```

## JS is Weakly Typed
```js
//Type associated with value, not variable.

var a = 1;
a = "one";
a = [1];
a = {one: 1};
```
## JS has 1st Class Functions
```js
//Treat like any object

var square = function(x){ return x*x },  //create

  	 mult = function(f1, f2){            // Return
    		return function(n){
      		return f1(n)*f2(n);
    		}
  	 },

  	 bigF = mult(square, square),        // ARG

value = bigF(2); // 16
```

## JS is Prototype Based
![image](https://user-images.githubusercontent.com/34129569/42721434-90dd4da2-8758-11e8-870e-276cbabef051.png)



JavaScript (JS) is a lightweight, interpreted or `JIT compiled programming language` with `first-class functions`. Most well-known as the scripting language for Web pages, `many non-browser environments` also use it, such as `node.js` and Apache `CouchDB`. JS is a `prototype-based`, multi-paradigm, dynamic scripting language, supporting object-oriented, imperative, and declarative (e.g. functional programming) styles. 

### Tutorials
* Basics
* Inline JavaScript
* Internal JavaScript
* External JavaScript
* Variable Declaration
* Data Types
* Operators
* Conditional Statements
* Objects
* Arrays
* Functions
* Math Date Objects
* DOM Manipulation
* Scopes
* Compilation & Interpretation
* Closures
* Objects in Depth
* Project Typing Tester App
* Event Listener
* ES6 Promises
