# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
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

### Screenshot

![image](./screenshot.jpg)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

The main thing i learned while building this project is the use of media queries and how to adjust the content for different screen sizes.


```css

@media (max-width: 812px) {
  body {
    margin: 3rem;
  }
  #container {
    flex-direction: column;
  }

  #container img {
    width: 100%;
    height: 30vh;
    border-top-left-radius: 25px;
    border-top-right-radius: 25px;
    border-bottom-left-radius: 0;
  }
  #container .product-info {
  }
}

```
## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@Bingolast](https://www.frontendmentor.io/profile/Bingolast)
- Twitter - [@Tiwariparth6165](https://twitter.com/Tiwariparth6165)

## Acknowledgments
Okay idont kown why  u should be readings but while building this project i realiesd that optimizing our code helps you when  your working with media quires.
