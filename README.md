# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Frontend Mentor - Order summary card solution](#frontend-mentor---order-summary-card-solution)
  - [Table of contents](#table-of-contents)
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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- See hover states for interactive elements

### Screenshot

![](./screenshot.png)

### Links

- Solution URL: [GitHub Repository](https://github.com/Bry-cmd/order-summary-component-main)
- Live Site URL: [GitHub Pages](https://bry-cmd.github.io/order-summary-component-main/index.html)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid

### What I learned

My most significant learning from this project was how a parent's background image can be shifted in position due to the parent's children. When I put the background image on the body, I was confused at first because it was shifted downward due to the card. To fix this, I managed to use the background-position CSS property to shift the background image to the desired position

```css
body {
  background-image: url("../images/pattern-background-desktop.svg");
  background-position: right -13rem;
}
```

### Continued development

I want to be able to start using SASS for my next projects to optimize my workflow.

### Useful resources

- [w3schools](https://www.w3schools.com/) - This helped me a lot when it came to quickly reviewing functions of code which I forgot, especially when it came to reviewing background images.
- [CSS Tricks](https://css-tricks.com/snippets/css/complete-guide-grid/) - This provided a very in-depth discussion on the use of CSS Grid, allowing me to use them to accomplish this challenge.

## Author

- Github - [Bry-cmd](https://github.com/Bry-cmd)
- Frontend Mentor - [@Bry-cmd](https://www.frontendmentor.io/profile/Bry-cmd)
- LinkedIn - [Bryan Sanchez](https://www.linkedin.com/in/bryan-sanchez-b316b7203/)