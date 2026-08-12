JavaScript Fundamentals Activity  

Part A – Annotated Timeline (research) 

 

JavaScript History — Annotated Timeline 

Introduction 

JavaScript is a programming language that was originally created for use in web browsers. It allows developers to add dynamic behaviour and interaction to websites. JavaScript is closely connected to ECMAScript, which is the standard that defines the language. ECMAScript is specified through the ECMA-262 standard. 

This timeline highlights important milestones in the development of JavaScript and ECMAScript, from the creation of JavaScript in 1995 to modern versions of the language. 

 

1995 — JavaScript Is Created 

JavaScript was created by Brendan Eich while he was working at Netscape. The language first appeared in Netscape Navigator 2.0 in September 1995. It was designed to bring scripting and interactive behaviour to web pages. 

Why this was important: 
The creation of JavaScript allowed websites to become more interactive and dynamic instead of consisting only of static HTML content. JavaScript later became one of the main technologies used for web development. 

Annotation: 
This was the starting point for JavaScript and established it as a browser-based scripting language. 

 

1996–1997 — JavaScript Becomes ECMAScript 

In November 1996, Netscape began working with Ecma International to standardise JavaScript. The first edition of the ECMAScript standard was adopted by the Ecma General Assembly in June 1997. 

The standardised language became known as ECMAScript and was defined under the ECMA-262 standard. 

Why this was important: 
Standardisation helped establish common rules for implementations of the language and provided a foundation for its continued development. 

Annotation: 
JavaScript is the name commonly used by developers, while ECMAScript is the formal language standard that JavaScript follows. 

 

1999 — ECMAScript 3 

The third edition of ECMAScript was adopted in December 1999. 

It introduced several important language improvements, including: 

Regular expressions 

Improved string handling 

New control statements 

try/catch exception handling 

Improved error definitions 

ECMAScript 3 became an important foundation for the growth of JavaScript on the World Wide Web. 

Why this was important: 
These improvements gave developers more tools for handling errors, processing text and building more capable web applications. 

Annotation: 
ECMAScript 3 helped establish many features that developers would continue using for years. 

 

2009 — ECMAScript 5 (ES5) 

ECMAScript 5, commonly called ES5, was approved in December 2009. It was a major update to the ECMAScript language. 

Some of its important additions included: 

Strict mode 

JSON support 

Accessor properties 

Improved object property controls 

Additional array manipulation methods 

Improvements to object creation and inspection 

Why this was important: 
ES5 improved JavaScript's reliability and gave developers better tools for writing structured programs. Features such as additional array methods also made it easier to work with collections of data. 

Example: 

const numbers = [1, 2, 3, 4]; 

 

const doubled = numbers.map(function(number) { 

    return number * 2; 

}); 

 

console.log(doubled); 

Annotation: 
ES5 was an important step toward the more modern JavaScript that developers use today. 

 

2015 — ECMAScript 2015 (ES6) 

ECMAScript 2015, commonly known as ES6, was adopted in June 2015. It was the sixth edition of the ECMAScript specification and was described by Ecma as the most extensive update since the first edition in 1997. 

ES6 introduced many major features, including: 

let and const 

Arrow functions 

Classes 

Modules 

Promises 

Destructuring 

Iterators and generators 

Template literals 

Maps and Sets 

For example: 

const name = "Azasange"; 

let age = 22; 

 

console.log(`My name is ${name} and I am ${age} years old.`); 

Why this was important: 
ES6 significantly modernised JavaScript and provided features that made it easier to develop larger and more complex applications. It also created the foundation for regular, incremental improvements to the language. 

Annotation: 
ES6 is one of the most important milestones in JavaScript's history because it introduced many features that are still commonly used in modern JavaScript development. 

 

2016 — ECMAScript 2016 (ES2016) 

ECMAScript 2016 was the first ECMAScript edition released under a yearly release process. Instead of waiting many years for another large release, new versions could introduce smaller improvements on a regular basis. 

ES2016 introduced features including: 

The exponentiation operator ** 

The Array.prototype.includes() method 

Example: 

const numbers = [1, 2, 3]; 

 

console.log(numbers.includes(2)); 

Output: 

true 

Why this was important: 
The yearly release cycle allowed ECMAScript to continue improving through smaller and more regular updates. 

Annotation: 
This marked a change in how JavaScript evolved, moving toward regular yearly improvements. 

 

2017 — ECMAScript 2017 (ES2017) 

ECMAScript 2017 introduced several features, including async functions, as well as Shared Memory and Atomics. 

One of the most useful additions for developers was async/await, which made asynchronous code easier to write and understand. 

Example: 

async function getData() { 

    const response = await fetch("data.json"); 

    const data = await response.json(); 

 

    console.log(data); 

} 

Why this was important: 
Asynchronous operations are common in web applications, particularly when communicating with servers and APIs. async/await provided a cleaner way to work with promise-based asynchronous operations. 

Annotation: 
ES2017 made asynchronous JavaScript easier to read and manage. 

 

2020 — ECMAScript 2020 (ES2020) 

ECMAScript 2020 was approved by the Ecma General Assembly in June 2020 as the 11th edition of the ECMAScript language specification. 

One notable modern JavaScript feature associated with this period is optional chaining (?.). 

Example: 

const user = {}; 

 

console.log(user.profile?.name); 

Instead of throwing an error when profile does not exist, optional chaining safely returns undefined. 

Why this was important: 
Features such as optional chaining made JavaScript code shorter and easier to write when working with values that may be missing. 

Annotation: 
Modern JavaScript continued to focus on making common programming tasks simpler and safer. 

 

2020s — Continuous Development 

JavaScript continues to evolve through regular ECMAScript updates. The language is no longer developed through occasional large changes only; instead, new features and improvements are introduced through the ongoing ECMAScript standardisation process. 

ECMAScript has grown from a browser scripting language into a general-purpose language used in browsers, servers and other environments. 

Why this was important: 
Continuous development allows JavaScript to adapt to the needs of modern software development while maintaining compatibility with existing applications. 

Annotation: 
JavaScript's continued development is one reason it remains an important language for software and web development. 

 

Conclusion 

JavaScript has changed significantly since it was created in 1995. It began as a scripting language for adding interaction to web pages and developed into a general-purpose programming language. 

Some of the most important milestones include: 

1995 — JavaScript was created by Brendan Eich at Netscape. 

1997 — ECMAScript was standardised, providing a formal specification for the language. 

1999 — ECMAScript 3 introduced important language features such as regular expressions and try/catch. 

2009 — ES5 introduced improvements such as strict mode, JSON support and additional array methods. 

2015 — ES6/ES2015 significantly modernised JavaScript with features such as let, const, classes, modules, promises and destructuring. 

2016 onward — yearly ECMAScript releases introduced smaller, regular improvements. 

2017 — ES2017 introduced async functions and other improvements for modern programming. 

2020 — ES2020 continued modernising the language with features such as optional chaining. 

Overall, JavaScript's history shows how the language has continuously developed to meet the changing needs of web and software developers. 

 

Sources 

MDN Web Docs — JavaScript: Origins and History 
MDN Web Docs — JavaScript 

Ecma International — ECMAScript 2015 Language Specification (ECMA-262, 6th Edition) 
ECMAScript 2015 Language Specification 

Ecma International — ECMAScript 2017 Language Specification (ECMA-262, 8th Edition) 
ECMAScript 2017 Language Specification 

Ecma International — ECMAScript 5 Approval Announcement 
Ecma International — ECMAScript 5 

Ecma International — ECMAScript 20th Anniversary / History 
Ecma International — ECMAScript History 

MDN Web Docs — Optional Chaining 
MDN Web Docs — Optional Chaining 

 

Console & DOM Challenges 

https://github.com/AzasangeT/JS-FUNDAMENTALS-CHALLENGES.git 

 