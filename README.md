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
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![Desktop Preview](./screenshot/desktop-preview.jpg)
![Phone Preview](./screenshot/mobile-preview.jpg)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- VS Code

### What I learned
- Learnt About Media query
```css
@media only screen and (max-width:600px){
    section{
        flex-direction: column;
        width:400px;
    }

    h1 {
        margin-top: 10px;
        margin-bottom: 10px;
    }

    .price{
        display: flex;
        align-items: center;
        margin-top: 20px;
        margin-bottom: 20px;
    }

    img {
        width: 100%;
        border-top-left-radius: 20px;
        border-top-right-radius: 20px;
        border-bottom-left-radius: 0px;
}

}

```
## Author

- Website - [kartik Pandey](https://github.com/KartikPandey19)

