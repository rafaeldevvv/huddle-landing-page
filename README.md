# Frontend Mentor - Huddle landing page with single introductory section solution

This is a solution to the [Huddle landing page with single introductory section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/huddle-landing-page-with-a-single-introductory-section-B_2Wvxgi0). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
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

- View the optimal layout for the page depending on their device's screen size
- See hover states for all interactive elements on the page

### Links

- Solution URL: [click here](https://github.com/rafaeldevvv/huddle-landing-page)
- Live Site URL: [click here](https://rafaeldevvv.github.io/huddle-landing-page/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- SASS

### What I learned

The first time I used mixin in practice and I thought it was quite useful. I used it to space elements equally without specifying each margin property.
```css
@mixin flex-gap($direction: column, $gap: $section-gap) {
  display: flex;
  flex-direction: $direction;
  gap: $gap;
}
```

The aspect ratio property is awesome. I've discovered it recently. I used it so that the social links would be perfect circles and I could position the icons in the exact middle.
```scss
a {
  width: 35px;
  aspect-ratio: 1;
  position: relative;

  .fa {
    position: absolute;
    left: 50%;
    top: 50%;
    transform: translate(-50%, -50%);
  }
}
```

### Continued development

I want to learn more about css techniques of responsive design as well as more things about SASS because it has been very useful in the projects I've been building.

### Useful resources

- [caniuse.com](https://caniuse.com/) - I've discovered this website to see the compatibility of CSS properties.

## Author

- Frontend Mentor - [@rafaeldevvv](https://www.frontendmentor.io/profile/rafaeldevvv)
- Instagram - [@rafffael_maia](https://www.instagram.com/rafffael_maia)
