# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![Result screenshot](./screenshot.png)

### Links

- [Solution URL](https://github.com/YuBlum/frontend-mentor-blog-preview-card)
- [Live Site URL](https://yublum.github.io/frontend-mentor-blog-preview-card/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

I finally started to learn about flexbox. It's not as complicated as I thought it would be, but I didn't build anything that amazing with it in this website so it'll probably get more complicated later on.

Using media queries properly and understanding why was also a first. It's pretty cool that CSS has these capabilities.
```css
:root {
    --white:    hsl(0, 0%, 100%);
    --yellow:   hsl(47, 88%, 63%);
    --gray-500: hsl(0, 0%, 42%);
    --gray-950: hsl(0, 0%, 7%);

    --font-size-300: 0.75rem;
    --font-size-400: 0.875rem;
    --font-size-700: 1.25rem;


    --font-weight-regular: 500;
    --font-weight-bold:    800;

    --spacing-300: 24px;
    --spacing-150: 12px;
    --spacing-100: 8px;
    --spacing-50:  4px;

    --font-family: "Figtree", sans-serif;
}

@media (width > 450px) {
    :root {
        --font-size-300: 0.875rem;
        --font-size-400: 1rem;
        --font-size-700: 1.5rem;
    }
}
```

### Continued development

I'll probably go more in-depth in pseudo-classes and flexbox/grid. Those topics are pretty simple to grasp, but their capabilities are so extense, I want to mess with them more.

## Author

- Frontend Mentor - [@YuBlum](https://www.frontendmentor.io/profile/YuBlum)

