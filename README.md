# Frontend Mentor - Four card feature section solution

This is a solution to the [Four card feature section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Frontend Mentor - Four card feature section solution](#frontend-mentor---four-card-feature-section-solution)
  - [Table of contents](#table-of-contents)
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

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![Design preview for the Four card feature section coding challenge](./design/desktop-design.png)

### Links

- Solution URL: [See the repository](https://github.com/ikitamalarose/four-card-feature-section-master-challenge.git)
- Live Site URL: [Go to the site](https://four-card-feature-section-master-challenge-omega.vercel.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

```css
.container__content {
        display: grid;
        align-items: center;
        grid-template-columns: 21.875rem 21.875rem 21.875rem;
        grid-template-rows: 15.625rem 15.625rem;
        gap: 1.875rem;
    }

.container__card-cyan {
        grid-column: 1 /2;
        grid-row: 1/3;
    }
```

### Useful resources

- [developer mozilla fr / CSS Grid documentation](https://developer.mozilla.org/fr/docs/Web/CSS/CSS_grid_layout) - This helped me for understand and properly arrange my blocks.

## Author

- Frontend Mentor - [@ikitamalarose](https://www.frontendmentor.io/profile/ikitamalarose)
- Twitter - [@ikitamalarose](https://www.twitter.com/ikitamalarose)

