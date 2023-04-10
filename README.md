## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View an age in years, months, and days after submitting a valid date through the form
- Receive validation errors if:
  - Any field is empty when the form is submitted
  - The day number is not between 1-31
  - The month number is not between 1-12
  - The year is in the future
  - The date is invalid e.g. 31/04/1991 (there are 30 days in April)
- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page
- **Bonus**: See the age numbers animate to their final number when the form is submitted

### Screenshot

![](./screenshots/FireShot%20Capture%20001%20-%20Frontend%20Mentor%20-%20Age%20calculator%20app%20-%20127.0.0.1.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Vanilla javascript
- Mobile-first workflow
- [Js-confetti](https://github.com/loonywizard/js-confetti) - JS library
- [web-speech-api](https://developer.mozilla.org/en-US/docs/Web/API/Web_Speech_API)

### What I learned

I'm so proud of myself for finally completing this frontend mentor [age-calculator challenge](https://www.frontendmentor.io/challenges/age-calculator-app-dF9DFFpj-Q). This project has helped me know how to tackle real time problems using javascript. I learnt how to make good use of **functions** and **Conditional statements**. 
I learnt how to properly write my javascript statements to avoid hoisting issues. For example -

```js
// this will return an error because const are not hoisted
ageCalculator();
const ageCalculator = () => {
  console.log('🎉')
}

// Hoisting actual is done under the hood by javascript for example

console.log(myFunc(1, 5))

function myFunc(a, b) {
  return a + b
}
// this above ☝ code will work because javascript always predefine function keywords above every other thing like this -👇
function myFunc(a, b) {
  return a + b
}

console.log(myFunc(1, 5))
```

So for me to avoid this problems, I maintained the use of **function ageCalculator()** instead of the ES6 syntax
I will be a liar if i should say that I didn't get stuck at a point, not just one point tons of them. 
My advice to you guys is to make sure you only use **const**, **let** and **function** keywords.

### Continued development

I wish I had the time to add animations so this project but let me keep it as my future development

### Useful resources

- [Js-confetti](https://github.com/loonywizard/js-confetti) - This really helped me to add the confetti animation on the project after the form fields are valid and it's super easy to use.

## Author

- Frontend Mentor - [@mosfresh](https://www.frontendmentor.io/profile/mosfresh)
- Twitter - [@Sinclair Udochukwu](https://twitter.com/Sinkycode)

## Acknowledgments

Deep down in my heart I would give a hat tip to [Brad](https://www.youtube.com/@TraversyMedia) known as traversy media. He doesn't know me but I'm a huge fan and I decided to make him my role model in javascript 😋. 
I won't forget to also acknowledge my king of css [kelvin powell](https://www.youtube.com/@KevinPowell). He's taught me a lot in css, I mean a lot.
