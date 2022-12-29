# Frontend Mentor - Pod request access landing page solution

This is a solution to the [Pod request access landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/pod-request-access-landing-page-eyTmdkLSG). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements
- Receive an error message when the form is submitted if:
  - The `Email address` field is empty should show "Oops! Please add your email"
  - The email is not formatted correctly should show "Oops! Please check your email"

### Screenshot

![](./screenshot/mobile.jpg)

![](./screenshot/tablet.jpg)

![](./screenshot/tablet.jpg)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- Flexbox
- CSS Grid
- BEM Method
- Mobile-first workflow
- JavaScript

### What I learned

In this challenge I learned:
How to embedd an SVG in a page using object element.

```html
<object 
  id="dots"
  data="./assets/desktop/bg-pattern-dots.svg" 
  type="image/svg+xml"
  style="width: 232px; height: 104px;">
</object>
```
How to re-ordering the boxes using flexbox order property

```css
.main-visual { /* This is container of form */
    grid-area: content;
    display: flex;
    flex-direction: column;
}

form {
    order: 1;
}
```

## Author

- Frontend Mentor - [@auriga2124](https://www.frontendmentor.io/profile/auriga2124)
- Twitter - [@ErkaRahman](https://twitter.com/ErkaRahman)
