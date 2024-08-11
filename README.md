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


## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](./screenshot.jpg)


### Links

- Solution URL: (https://github.com/Stanley-24/responsive-product-page.git)
- Live Site URL: (https://responsive-product-page.vercel.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS 
- CSS Variables
- Flexbox
- CSS Media Query

### What I learned

This project set me on challenge to work more with the chrome dev tool, i worked more with CSS flexible layout and added a bonus of javascript function to the button using Chatgpt for the javascript code but i do understand the logic there using the eventlistner 
To see how you can add code snippets, see below:

```html
<div class="product-price" id="product-price"> <!-- flex container in row direction -->
            <span class="sales-price" id="sales-price">
              $149.99
            </span>
            <span class="list-price" id="list-price">
              $169.99
            </span>```
```css
:root {
    --dark-cyan: hsl(158, 36%, 37%);
    --very-dark-green: hsl(158, 45%, 20%);
    --dark-grayish-blue: hsl(228, 12%, 48%);
    --Very-dark-blue: hsl(212, 21%, 14%);
    --cream: hsl(30, 38%, 92%);
    --white: hsl(0, 0%, 100%);
    --black: #1D232B;
}

.desktop-only {
        display: none;
    }
```


### Continued development

Still learning how to use the right html syntax for each code and also want to improove my layout styling using both css flex box and css grid


### Useful resources

- [Conjointly](https://conjointly.com/faq/mobile-desktop-responsive-images/) - I was having issue on how to display the images on different screen, at first i was confuse but i know the way i can archive this was to hide one of them, that's when i looked on google and find this website and get the main ideal from there. The solution was to use Media Query to display one and hide one. 
- [ChatGpt] - I just wanted to add extra to the page, that's when i asked ChatGpt to come up with the code to add EventListner to the button and yeah it work. 



## Author

- Github - [Stanley-24](https://github.com/Stanley-24/)
- Frontend Mentor - [@stanley-24](https://www.frontendmentor.io/profile/Stanley-24)
- Twitter/X - [@stanley_24_](https://x.com/Stanley_24_)

