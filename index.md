## Reactive Programming with RxJS


### Overview
In this blog we will dive into the world of reactive programming with JavaScript. Basically we devided them into three categories:

1.JavaScript basics
2. What is Reactive Programming?
3. Reactive Programming in JavaScript
4. Important Links

So let's get started!

1. JavaScript basics 

First of all, let’s do a short recap on javascript. Programming for the Web javascript is the programming language of your choice. Together with HTML and CSS you are ready to become an web developer. Javascript offers even more with node.js the world of server-side development is your’s as well. Brendan Eich invented Javascript back in 1995. Two years after that it became an ECMA standard (“ECMA-262) . 

First steps: Variables and Contants
Variables
    var newString = “String”;    ||       let newString = “String”;
    let a, b = 10;                        let c = 10, d = “String”;
    
Constants
    const newConstant = 10;
Variables in Javascript are declared by “var”. With [ES6](http://www.ecma-international.org/ecma-262/6.0/#sec-let-and-const-declarations ) came ‘let’ and ‘const’. These are scoped to their running execution context. A variable declared with ‘var’ might be used by other functions as they are global when declared outside any function. ‘Let’ on the other hand is only approachable within their context of definition, so called block scoped. 
Quick example:

Moving on to: Arrays and Objects
Objects
    var myObject = {
            Name :  “Max”,
            Nachname : “Mustermann”
Address : {Straße : “Musterstraße”, Hausnummer : 5, PLZ : “11111” , Stadt :
        “Musterstadt”}

    }
Arrays
    var myElements = [ 2 , 3, 4, 5 ]; || 
var myElements = new Array(2 , 3, 4, 5);
        var alsoMyElements = [ 2, “Hello”, new Date(), 5 ];
We already looked at Variables, now Objects are like Variables since they are containers for data too. Objects can hold many values. Those values don’t have to be of the same type. Arrays are special variables too. They can contain many values as well. 
How to access those values? With objects you use the names of the values, e.g. myObject.Name returns “Max”. Arrays returns values by numbers, e.g. myElements[1] returns 2. Remember, the first element of an Array is called by 0, the second by 1 and so on. 




You can use the [editor on GitHub](https://github.com/manuelhuber/ReactiveProgramming/edit/master/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/manuelhuber/ReactiveProgramming/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
