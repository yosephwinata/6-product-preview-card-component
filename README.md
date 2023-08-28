# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Links

- Solution URL: [https://github.com/yosephwinata/product-preview-card-component](https://github.com/yosephwinata/product-preview-card-component)
- Live Site URL: [https://product-preview-card-component-lovat-eta.vercel.app/](https://product-preview-card-component-lovat-eta.vercel.app/)

## My process

### Built with

- Semantic HTML5 markup
- Flexbox
- CSS Grid

### What I learned

This is how you use multiple images for responsive designs.

```html
<picture class="product-img">
  <source media="(max-width:640px)" srcset="/images/image-product-mobile.jpg" />
  <img src="/images/image-product-desktop.jpg" alt="Product Image" />
</picture>
```
