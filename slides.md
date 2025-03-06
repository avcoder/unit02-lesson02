---
# You can also start simply with 'default'
theme: default
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: /assets/intro.jpg
# some information about your slides (markdown enabled)
title: Software Development | Foundations
info: |
  ## Software Development | Foundations
# apply unocss classes to the current slide
class: text-left
drawings:
  persist: false
transition: slide-left
mdc: true
---

# JavaScript - part 2/8
JavaScript Foundations
- [ ] Conditional statements
- [ ] Arrays and array methods (length, push, pop, shift, unshift, slice, splice)
- [ ] Functions

<div class="abs-br m-6 text-xl">
  <a href="https://github.com/slidevjs/slidev" target="_blank" class="slidev-icon-btn">
    <carbon:logo-github />
  </a>
</div>

<!--
TODO: fill in anchor href above to point to github repo for these slides
- Personal Website assignment due this Sunday midnight EST
-->

---
transition: slide-left
---

# Recap
(10 min) 

- recall variables, oprations, expressions
- revisit Guess the number game
- use `debugger` tool to view execution

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

<!--
- use debugger for guest the number 
-->

---
transition: slide-left
---

# Conditionals statements
(40 min) What is a conditional statement, how to write them

- Goto: https://codepen.io/codevilla/pen/VYwWexd
- Boolean values
- truthy vs falsy
- `if`, `else if`, `else`
- `switch statement`
- `ternary operator`
- Challenge: how would you check if a number is even?


<!--
- use Github Desktop to share exercises, ask students to fork it, and create PR when done
READ: https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Scripting/Conditionals
-->

---
layout: image-right
transition: slide-left
image: /assets/wesbos.png
backgroundSize: 500px 400px
class: text-left
---

# 5 minute break

🍦 Cool Tips, Trends and Resources:
- ▶️ [JS30](https://www.youtube.com/watch?v=VuN8qwZoego&list=PLu8EoSxDXHP6CGK4YVJhL_VWetA865GOH)
- 📒 [JS Notes](https://wesbos.com/javascript)
- 🔎 [Exploring JavaScript](https://exploringjs.com/js/downloads/exploring-js-screen-preview.pdf)
- ⛏️ [Modern JS from the beginning](https://www.youtube.com/watch?v=BI1o2H9z9fo&pp=ygUTdHJhdmVyc3kgamF2YXNjcmlwdA%3D%3D)
- 🆙 [Better JavaScript](https://levelup.video/tutorials/better-javascript)



<br>
<hr>
<br>

- 🧪 [Enter anonymous lab questions](https://docs.google.com/forms/d/e/1FAIpQLSevvGARdHQikso-uLqFCO481MABKE5HofuSrlzEPMNQ2ZLykw/viewform?usp=dialog)
- ℹ️ [Course feedback survey](https://circuitstream.typeform.com/to/ZoyYk7px#course_id=SoftwareAN&instructor=9514)

<!-- 
- remember: take attendance
-->

---
transition: slide-left
---

# Arrays
(40s min) What is an array, how to create one and access its elements

- View instructions: https://codepen.io/codevilla/pen/mydwevq
- See all array methods [here ](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/at)

<!-- 
READ: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array
-->

---
layout: image-right
transition: slide-left
image: /assets/kylesimpson.png
backgroundSize: 500px 480px
class: text-left
---

# 5 minute break
<br/>

🍦 Cool Tips, Trends and Resources:
- ▶️ [Kyle Simpson's JS advice](https://x.com/FrontendMasters/status/1648035941800464384)
- 🆕 [YDKJS: Get Started](https://github.com/getify/You-Dont-Know-JS/blob/2nd-ed/get-started/README.md)
- 🗳️ [YDKJS: Scopes & Closures](https://github.com/getify/You-Dont-Know-JS/blob/2nd-ed/scope-closures/README.md)
- 👋 [YDKJS: this & Object Prototypes](https://github.com/getify/You-Dont-Know-JS/blob/1st-ed/this%20&%20object%20prototypes/README.md#you-dont-know-js-this--object-prototypes)
- 📚 [YDKJS: Types & Grammar](https://github.com/getify/You-Dont-Know-JS/blob/1st-ed/types%20&%20grammar/README.md#you-dont-know-js-types--grammar)
- 🛜 [YDKJS: Async & Performance](https://github.com/getify/You-Dont-Know-JS/blob/1st-ed/async%20&%20performance/README.md#you-dont-know-js-async--performance)
- 👾 [YDKJS: ES6 & Beyond](https://github.com/getify/You-Dont-Know-JS/blob/1st-ed/es6%20&%20beyond/README.md#you-dont-know-js-es6--beyond)

<br>
<hr>
<br>

- 🧪 [Enter anonymous lab questions](https://docs.google.com/forms/d/e/1FAIpQLSevvGARdHQikso-uLqFCO481MABKE5HofuSrlzEPMNQ2ZLykw/viewform?usp=dialog)
- ℹ️ [Course feedback survey](https://circuitstream.typeform.com/to/ZoyYk7px#course_id=SoftwareAN&instructor=9514)
<!-- 
- remember: take attendance
-->


---
transition: slide-left
---

# Functions
(50 min) What are functions, and why are they important?

- Goto: https://codepen.io/codevilla/pen/EaxXKBr
- How to create one
- arguments vs parameters
- returning values
- arrow functions
- Challenge: Write a function that takes a number argument (i.e. student score) and returns a letter grade
- Challenge: Write a function that takes a string argument and counts all vowels
- Challenge: write a function that takes a weather condition as a string (i.e. 'rainy') and returns an appropriate message (i.e. 'Bring an umbrella')

<!-- 
- groups together sets of statements performing work (and sometimes returning a value)
- Challenge: emulate: .includes, Math.max(x, y), calculate Bill (including tax) based on Province
- storing a value returned from a function
- scope (create a fn, try accessing a variable not scoped)
- nesting functions
- default args
- different ways to declare fn, anonymous fn
- arrow fn, iife
- methods are fn living inside objects
- callbacks, setTimeout
-->

---
transition: slide-left
---

# Group Exercise: 
(remainder of time) 

```js
// Given the following variables,
// Create a program that prompts the user, showing the question,
// and possible 4 answers, and the user chooses 1,2,3 or 4. 
// Alert user if they were correct or not.
// Tip: Try pseudo coding solution first with English language in comments first

const question = 'In computing terms, typically what does CLI stand for?';
const correctAnswer = 'Command Line Interface';
const incorrectAnswers = [
  "Common Language Input",
  "Control Line Interface",
  "Common Language Interface"
];
```

<!-- 
-->

---
transition: slide-left
---

## For homework:

- "Personal Website" assignment (aka Portfolio assignment) due this Sun. Mar. 9 midnight EST is part of the 20% of final grade
- Continue doing daily JS exercises on [FreeCodeCamp - JS Algorithms & Data Structures](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures-v8/)


<!--
- take attendance
-->
