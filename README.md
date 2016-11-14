#loud-lizard

##Mo and Lisa's Basic Algorithms Project

###Description

###Complete the basic algorithm scripting section here:

Basic Algorithm Scripting on FCC
https://www.freecodecamp.com/map

##Selected Algorithm Solutions

###Return Largest Numbers
```javascript
function largestOfFour(arr) {
var results = [];
for (var n = 0; n < arr.length; n++) {
var largestNumber = 0;
for (var sb = 0; sb < arr[n].length; sb++) {
if (arr[n][sb] > largestNumber) {
largestNumber = arr[n][sb];
}
}

results[n] = largestNumber;
}

return results;
}

// largestOfFour([[4, 5, 1, 3], [13, 27, 18, 26], [32, 35, 37, 39], [1000, 1001, 857, 1]]);
```

###Slasher Flick
```javascript

function slasher(arr, howMany) {
  // it doesn't always pay to be first
  return arr.slice(howMany);
}

slasher([1, 2, 3], 2);
```

##Specification

###Required

Do not remove these specs - they are required for all goals.

 - [x] The artifact produced is properly licensed, preferably with the [MIT license][mit-license].

###Quality rubric one: Code is readable

##Completed Supplemental Lessons

 - [x] FreeCodeCamp - The DOM: What's the Document Object Model?
 - [x] FreeCodeCamp - The DOM: Style in the Header, Script in the Footer
 - [x] FreeCodeCamp - JavaScript Lingo: MDN and Documentation
 - [x] FreeCodeCamp - JavaScript Lingo: Variables & camelCase 
 - [x] FreeCodeCamp - JavaScript Lingo: Finding and Indexing 
 - [x] FreeCodeCamp - JavaScript Lingo: Manipulating Data 
 - [x] FreeCodeCamp - JavaScript Lingo: Math
 - [x] FreeCodeCamp - JavaScript Lingo: Manipulating Data 
 - [x] FreeCodeCamp - JavaScript Lingo: Loops
 - [x] FreeCodeCamp - JavaScript Lingo: Regular Expressions *
 - [x] FreeCodeCamp - Big O Notation: What It Is and Why You Should Care
 - [x] FreeCodeCamp - Big O Notation: A Few Examples
 - [x] A Smarter Way to Learn JS - Chapter Exercises: 1 - 9, 22 *
 - [x] Tutorials Point - HTTP, Express JS, React JS * 
 - [x] React JS Fundamentals - Intro to the React Ecosystem
 - [x] MongoDB Tutorial for Beginners - YouTube Video
 
* These tutorials were very beneficial. 
 
* On FCC's JavaScript Lingo, "learn it, know it" can be a great help for changing strings and for the manipulation of user input.

* On A Smarter Way to Learn JS, we learned that the placement of operators matters when assigning values to a new variable. Example: x-- vs --x
 
* On Tutorials Point, we learned that all Express methods are equivalent to HTTP verbs (i.e., post, Git, etc.) If code works for small calculations/data, it's not always efficient when scaled to larger calculations/data.
 
 
 

