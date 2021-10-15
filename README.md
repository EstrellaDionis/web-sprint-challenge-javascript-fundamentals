# Sprint Challenge - JavaScript Fundamentals

**Read these instructions carefully. Understand exactly what is expected _before_ starting this Sprint Challenge.**

This challenge allows you to practice the concepts and techniques learned over the past week and apply them in project. This Sprint explored JavaScript Fundamentals. During this Sprint, you studied array methods, this keyword, prototypes, and class syntax. In your challenge this week, you will demonstrate proficiency by completing a range of JavaScript problems.

This is an individual assessment. All work must be your own. Your challenge score is a measure of your ability to work independently using the material covered through this sprint. You need to demonstrate proficiency in the concepts and objectives introduced and practiced in preceding days.

You are not allowed to collaborate during the sprint challenge. 

## Introduction

The index.js file contains all of your challenges. Please review it in full before answering the questions. If you complete the stretch goals please leave them in your file but commented out so that they do not affect the MVP tasks 

In meeting the minimum viable product (MVP) specifications listed below, you should have all tests passing. You can console.log to check your work and ensure you are submitting the correct results 

### Commits

Set up codegrade early and commit your code regularly and meaningfully. 

## Interview Questions
### (please edit this file and write your answer below each question.)
Demonstrate your understanding of this week's concepts by answering the following free-form questions.

Edit this document to include your answers after each question. Make sure to leave a blank line above and below your answer so it is clear and easy to read.

1. Explain the differences between `.map`, `.reduce` and `.filter` and describe a use case for each. 
.map - is great for when you are CONVERTING data. An example of that might be changing a string to lowercase or uppercase. It also returns a new array and needs a return statement.
.reduce - is great for things such as multiply, subtracting and adding but can be used for anything. It returns a single value but not a new array.
.filter - great for when you want to return a boolean of true or false.Returns a new array, requires a return statment and is used for filtering data which will be included in the array only if it's true.
2. Explain the difference between a callback and a higher order function.
A callback is a function that is passed INTO another function as an argument while a higher order function is a function that receives other functions.

3. Explain what a closure is.
Its when a inner function reaches out of its scope to grab a variable defined in an outer function.
It is also what prevents things such as variables within a function be unnatainable outside of the function.

4. Describe the four principles of the 'this' keyword.
 1) Window binding - if we do not give "this" a context it will return to us the window which is the global object in node or undefined in strict mode.
    2) Implicit binding - applies to objects with methods. When the method is invoked, we're telling it to look to the left of the dot and that is what "this" refers to.
    3) Explicit binding - this is when we tell our function to use .call, .apply and .bind. 
    .call - immediately invokes the function and is passed in arguments 1 by 1
    .apply - immediately invokes the function and is passed arguments as an ARRAY.
    .bind - this takes in arguments 1 by 1 like in .call BUT, unlike the others, you DO NOT immediately invoke the function & it returns a new function that can be invoked later.
    4) New binding - is when we invoke a function with the "new" keyword and makes the function bound to it. When invoked with a constructor function. it is now pointing towards the "new" object that we created.

5. Why do we need super() in an extended class?
We need them in classes to do what object.create and parent.call do.

You are expected to be able to answer questions in these areas. Your responses contribute to your Sprint Challenge grade. 

## Instructions

### Task 1: Set up Project

Using VSCode and Command Line:


1. Fork the repo
2. Go into canvas and connect your reop to codegrade
3. Clone your forked version of the repo
4. DO NOT CREATE A BRANCH. You will be pushing your changes to the main/master today
5. cd into your repo
6. open the terminal in your vs code and type `npm install`
7. next type `npm run test` in your terminal
8. Complete your work making regular commits to main/ master your codegrade score will update each time you make a push.


### Testing & Debugging

Open a second terminal inside of your project by clicking on the split terminal icon
![alt text](assets/split_terminal.png "Split Terminal")

Inside of your second terminal type `npm start` 
![alt text](assets/npm_start.png "type npm start")

You will be running your tests in one terminal and debugging in the other. As you work on your code you should make use of `console.log` to check your progress and debug.
![alt text](assets/tests_debug_terminal_final.png "your terminal should look like this")

### Task 2: Project Requirements (MVP)

You must complete all tasks inside of `index.js` and answer the questions above.

In your solutions, it is essential that you follow best practices and produce clean and professional results. Schedule time to review, refine, and assess your work and perform basic professional polishing including spell-checking and grammar-checking on your work. It is better to submit a challenge that meets MVP than one that attempts too much and does not.

## Resources
 
 [Sprint Challenge Study Guide](https://www.notion.so/lambdaschool/Unit-1-Sprint-3-Study-Guide-033a9a00659a4ef98c12eb97e49a6110)

## Submission format

Please submit your project via codegrade by following [these instructions](https://lambdaschool.notion.site/lambdaschool/Lambda-School-Git-Flow-Step-by-step-269f68ae3bf64eb689a8328715a179f9) See part 2, submitting an assignment with codegrade
