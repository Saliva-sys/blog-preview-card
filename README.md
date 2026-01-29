# Frontend Mentor - Blog preview card solution

This is my solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). This was a great challenge to practice CSS fundamentals. 

## Table of contents

- [Frontend Mentor - Blog preview card solution](#frontend-mentor---blog-preview-card-solution)
  - [Table of contents](#table-of-contents)
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

- See hover and focus states for all interactive elements on the page
- View the optimal layout for the site depending on their device's screen size.

### Screenshot

[Design preview](./assets/images/screenshot.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first approach
- Responsive design with `calc()`

### What I learned

During this project, I practiced precise layout alignment using a 12-column grid background for development. I also focused on making the component fully responsive.

One of the key things was using `calc()` to ensure perfect margins on mobile devices:

```css
.card {
    width: calc(100% - 48px);
    max-width: 384px;
}
```

### Continued development

In future projects, I want to focus on a deeper understanding of CSS Grid to be able to create complex product grids. I also plan to start using BEM (Block Element Modifier) ​​methodology for better CSS organization, which is crucial when modifying large templates like those in PrestaShop.

### Useful resources

- [MDN Web Docs](https://developer.mozilla.org/) - A basic resource for addressing the correct notation of `calc()` and semantic HTML tags such as `<time>`.
- [Google Fonts](https://fonts.google.com/) - Used to import the Figtree font, which gives the project a modern look.

## Author

- Adriana Weidlichová - [Frontend Mentor Profile](https://www.frontendmentor.io/profile/Saliva-sys)

