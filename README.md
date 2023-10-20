# Frontend Mentor - FAQ accordion card solution

This is a solution to the [FAQ accordion card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/faq-accordion-card-XlyjD0Oam). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the component depending on their device's screen size
- See hover states for all interactive elements on the page
- Hide/Show the answer to a question when the question is clicked

### Screenshot

![](screenshot.png)


### Links

- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow


### What I learned

- I learned about the **details and summary** HTML tags, making this challenge significantly faster to resolve since JavaScript was not necessary thanks to these tags

```html for every question
  <details>
    <summary>What is the maximum file upload size?
    </summary>
    <div class="answer">
      No more than 2GB. All files in your account must fit your allotted storage space.
    </div>
  </details>
```
```css for every question
summary{
    display: flex;
    justify-content: space-between;
    gap: 10px;
    cursor: pointer;
} 
```

### Useful resources

- [Mozilla Developer](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/details) - This is where I discovered the details and summary tags 
- [CSS Tricks](https://css-tricks.com/two-issues-styling-the-details-element-and-how-to-solve-them/) - This article helped me to understand the issues of styling these elements and their solutions


## Author

- Frontend Mentor - [@Kriosaber](https://www.frontendmentor.io/profile/yourusername)
