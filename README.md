# Manage-Landing-Page

# Frontend Mentor - Manage landing page solution

This is a solution to the [Manage landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/manage-landing-page-SLXqC6P5). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page
- See all testimonials in a horizontal slider

### Screenshot

![](./screenshot.jpg)

![Page Screenshot](<../../vite-project/Manage-Landing-Page/images/Page Screenshot.png>)

### Links

- Live Site URL: https://triftytexas.github.io/Manage-Landing-Page/

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- [React](https://reactjs.org/) - JS library
- [Next.js](https://nextjs.org/) - React framework
- [Styled Components](https://styled-components.com/) - For styles
- Kevin Powell - Youtube Guide for references

### What I learned
The use of sliders to create a carosel for the page was new and very interesting to learn
```html
<ul class="slider">
        <li>
          <img src="images/avatar-anisha.png" alt="">
```
Using various utility classes and predefining values manually was new and inovative approach, the use of a11y slider programs healped a ton.
```css
.a11y-slider-container {
  margin-block: var(--size-700);
  margin-inline: var(--size-400);
}
```

```js
navToggle.addEventListener("click", () => {
    primaryNav.hasAttribute("data-visible")
        ? navToggle.setAttribute("aria-expanded", false)
        : navToggle.setAttribute("aria-expanded", true);
    primaryNav.toggleAttribute("data-visible");
    primaryHeader.toggleAttribute("data-overlay");
});
```

### Continued development

Future development of the project is planned to include more interactive features and animations to enhance the user experience, creating a more immersive and engaging experience for the user. A multipage website with proper navigation and routing, utilization of react hooks for state management, and improvement of accessibility features.

## Author

- Name - [Surya Prasath]
- Instagram - [@trifty_texas](https://www.instagram.com/trifty_texas/)
- Twitter - [@Surya](https://x.com/Surya85796146)
