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

### Screenshot

![](/design/Page-Preview.png)

### Links

- Solution URL: [Product Preview Card Solution]()
- Live Site URL: [Product Preview Card Live Page](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flex-box
- CSS Grid
- Mobile-first workflow
- [Google Fonts](https://fonts.google.com/) - Fonts


### What I learned

```HTML
  <div class="image">
    <img class="mobile-view" src="/images/image-product-mobile.jpg" alt="Gabrielle Essence Eau De Parfum">
    <img class="desktop-view" src="/images/image-product-desktop.jpg" alt="Gabrielle Essence Eau De Parfum">
  </div>
```
I learned I can switch these images depending on the screen size, with the help of some CSS.

```CSS
@media (min-width: 1024px) {
  .desktop-view {
    display: block;
  }

  .mobile-view {
    display: none;
  }
}
```
Very simple CSS yet not once did it cross my mind that I could use this to change the main image from one preset size to the next. Also media tags are getting more and more simple to use.

### Continued development

Using the mobile first approach method has helped me so much in cutting down on the frustration I was going through at the beginning of my coding journey. In my mind building the full size webpage seemed like the easy way because my logic was "I can just shrink everything down and change a few things here and there", but boy was I wrong. Moving forward I will start off by laying things down on a mobile view first as it has changed the way I view CSS and how things are structured.

### Useful resources

- [W3Schools](https://www.w3schools.com/) - Will never not use this website to get out of a stumble, it is always the first place I stop by for help.

## Author

- Website - [Juan Vega](https://juantwofour.github.io/Social-Profiles/)
- Frontend Mentor - [@JuanTwoFour](https://www.frontendmentor.io/profile/JuanTwoFour)