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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![](./assets/img/screenshot-desktop.png)

### Links

- Solution URL: [Solution](https://your-solution-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

```html
  <picture>
    <source media="(min-width: 1024px)" srcset="./assets/img/image-header-desktop.jpg" type="image/jpg">
    <img src="./assets/img/image-header-mobile.jpg" alt="" />
  </picture>
```
```css
img {
  mix-blend-mode: multiply;
}
```
### Useful resources

- [MDN Web Docs: \<picture>](https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element/picture) - This is an MDN article do which helped me finally understand tag picture.
- [MDN Web Docs: mix-blend-mode](https://developer.mozilla.org/pt-BR/docs/Web/CSS/mix-blend-mode) - This is an MDN article do which helped me finally understand css properties mix-blend-mode.

## Author

- Frontend Mentor - [@fernandoprestes](https://www.frontendmentor.io/profile/fernandoprestes)
