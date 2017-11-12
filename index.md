## Reactive Programming with RxJS


### Overview
In this blog we will dive into the world of reactive programming with JavaScript. Basically we devided them into three categories:

1. JavaScript basics

2. What is Reactive Programming?

3. Reactive Programming in JavaScript

4. Important Links

So let's get started!

1. **JavaScript basics** 

First of all, let’s do a short recap on javascript. Programming for the Web javascript is the programming language of your choice. Together with HTML and CSS you are ready to become an web developer. Javascript offers even more with node.js the world of server-side development is your’s as well. Brendan Eich invented Javascript back in 1995. Two years after that it became an ECMA standard (“ECMA-262) . 

First steps: Variables and Contants
- Variables
``` 
    var newString = “String”;    ||       let newString = “String”;
    let a, b = 10;                        let c = 10, d = “String”;
```     
- Constants
``` 
    const newConstant = 10;
``` 
Variables in Javascript are declared by “var”. With [ES6](http://www.ecma-international.org/ecma-262/6.0/#sec-let-and-const-declarations ) came ‘let’ and ‘const’. These are scoped to their running execution context. A variable declared with ‘var’ might be used by other functions as they are global when declared outside any function. ‘Let’ on the other hand is only approachable within their context of definition, so called block scoped. 
Quick example:

Moving on to: Arrays and Objects

- Objects
``` 
    var myObject = {
            Name :  “Max”,
            Nachname : “Mustermann”
            Address : {Straße : “Musterstraße”, Hausnummer : 5, PLZ : “11111” , Stadt :
                        “Musterstadt”}
    } 
```
- Arrays
```
    var myElements = [ 2 , 3, 4, 5 ]; || 
    var myElements = new Array(2 , 3, 4, 5);
    var alsoMyElements = [ 2, “Hello”, new Date(), 5 ];
```
    
    
We already looked at Variables, now Objects are like Variables since they are containers for data too. Objects can hold many values. Those values don’t have to be of the same type. Arrays are special variables too. They can contain many values as well. 
How to access those values? With objects you use the names of the values, e.g. myObject.Name returns “Max”. Arrays returns values by numbers, e.g. myElements[1] returns 2. Remember, the first element of an Array is called by 0, the second by 1 and so on. 

Next on the agenda are functions. Functions are blocks of code, defined to fullfil a specific task. They are defined by the keyword **function** and a name, following parentheses, which can contain paramters. A function is executed when something, e.g. an event or even another function, calls is. 

Here some examples:
```
function myObjectFunction (firstname, surname){
        return { Firstname :  firstname,    Surname : surname};
}
var mySecondObjectFunction = function (firstname, surname){
        return { Firstname :  firstname,    Surname : surname};
}

function myFunction (firstname, surname){
        var name = myObjectFunction(firstname, surname); 
        return name;
}

```
The first function is gets two parameters and returns them as object. As soon as the surronding function or script is executed - the first function can be executed. The second function on the other hand is a functional expression and is ready to be executed as soon as the line, in which it is defined, is reached in the executed script. 
