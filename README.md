# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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



## Overview

### The challenge

Users should be able to:

- See hover states for interactive elements

### Screenshot

![](./screenshot.png)


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties


### What I learned

I learned how to change the color of my link elements when I hover with my cursor.

```html
<a href="#" class="payLink"><div class="payment">Proceed to Payment</div></a>
```
```css
.payment {
  font-family: 'Red Hat Display', sans-serif;
  font-weight: 600;
  font-size: 13px;
  text-align: center;
  background-color: rgb(53, 18, 228);
  margin-left: 25px;
  margin-right: 25px;
  border-radius: 10px;
  color: white;
  box-shadow: 0px 20px 10px lightgray;
  padding-top: 15px;
  padding-bottom: 15px;
}

.payment:hover {
  background-color: rgba(53, 18, 228, 0.65);
```

### Continued development

I would like to work more on my flexbox properties and attributes.


### Useful resources

- (https://www.w3schools.com/) - This helped me alot with using the :hover property. 
- (https://paletton.com/#uid=1000u0kllllaFw0g0qFqFg0w0aF) - This helped me find certain colors for my fonts and div container for the payment button

## Author

