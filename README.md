# Frontend Mentor - Four card feature section solution

This is a solution to the [Four card feature section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK). 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)


## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![Mobile view](./images/Screenshot-FM-Four-card-feature-section.png)


### Links

- Solution URL: [Add solution URL here](https://github.com/Glorit74/four-card-feature-section-master)
- Live Site URL: [Add live site URL here](https://glorit74.github.io/four-card-feature-section-master/)

## My process

### Built with

- Semantic HTML5 markup
- Tailwind-CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

Grid in Tailwind. Adjusting the gap was a challenge.

```html
 <article
          class="card border-cyan lg:col-start-1 lg:row-span-2 lg:row-start-2"
        >
```
```css
 .card_container {
    @apply flex flex-col items-center space-y-5 lg:space-y-0 lg:grid lg:grid-cols-3 lg:grid-rows-4 lg:gap-x-14 lg:gap-y-7;
  }
```



