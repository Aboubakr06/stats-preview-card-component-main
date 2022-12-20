# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

### Screenshot

-Mobile version-

![photo](./design/mobile-design.jpg)

 -Desktop version

![photo](./design/desktop-design.jpg)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

```css
@media (min-width: 600px) {
    .product {
        --content-spacing: 0rem;
        text-align: start;
        grid-template-columns: 1fr 1fr;
        grid-template-rows: 1fr;
        
    }

    .product__header {
        grid-template-rows: 1fr 1fr;
        grid-column: 2/-1;
        grid-row: 1/-1;
    }

    .product__img {
        content: url("images/image-header-desktop.jpg");
        min-height: 100%;
        grid-row: 1/-1;
    }
}
```

### Useful resources

- [Learn CSS Grid for free with Per Harald Borgen](https://scrimba.com/learn/cssgrid) - This helped me with positioning the my divs.

## Author

- Frontend Mentor - [@Aboubakr06](https://www.frontendmentor.io/profile/Aboubakr06)
- Twitter - [@elbouzidi99](https://twitter.com/elbouzidi99)

