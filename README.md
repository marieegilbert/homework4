# homework4

Pseudocode EC (Week 4 Activities)
01-Stu_This-Window
// console.log(this)
    returns 'window'object
    'this' refers to window
    window is an object representation of an open window in a browser 
    window object contains numerous properties and methods 
    Review: console.log() outputs a message to the web console

02-Ins_Traverse-DOM
//   DOM traversal (Document Object Model)
    connects webpages to scripts by representing the structure of a document (such as HTML) in memory
    Logic tree: each branch of the tree ends in a node, each node contains objects (nodes can also have events attached to them)

03-Stu_Traverse-That-DOM

//Using Chrome Dev Tools to change the DOM elements 
    We have the ability to manipulate the HTML using the DOM
    We can do so using JS file
05-Stu_Setting-Attributes

//Setting attriubtes using Javascript, essentially adding elements via javascript to the HTML
    Element.setAttribute(name, value);
    Sets the value of an attirbute on a specified element 
    If the element already exists, the value is updated 
    document.querySelector();
    document.querySelectorAll();

06-Ins_Create-Append
//Can append HTML elements by using javascript
    Can use document.createElement(); to create a new HTML element
    Can then push this element to the DOM with document.appendChild();

07-Stu_LookMaNoHTML
//It's possible to not have any HTML elements in your HTML document by creating them all in javascript 

# homework4

## Table of Contents

* [Usage](#usage)
* [Credits](#credits)
* [License](#license)

## Description  

From scratch, build a timer-based quiz application that stores high scores client-side. Following the [common templates for user stories](https://en.wikipedia.org/wiki/User_story#Common_templates), we can frame this challenge as follows:

```
As a coding bootcamp student
I want to take a timed quiz on JavaScript fundamentals that stores high scores
so that I can gauge my progress compared to my peers
```

## Credits

I'd like to thank my instructor Omar, and Peter, the TA, who will be grading this assignment.

## License

MIT License

Copyright (c) [2019] [Marie Gilbert]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.