# Frontend Mentor - FAQ accordion solution

This is a solution to the [FAQ accordion challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/faq-accordion-wyfFdeBwBz).  

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

The challenge is to build out the given FAQ accordion and get it looking as close to the design as possible.

### The challenge

Users should be able to:

- Hide/Show the answer to a question when the question is clicked
- Navigate the questions and hide/show answers using keyboard navigation alone
- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page

### Screenshot

![Desktop](/assets/screenshots/desktop-preview.png)
![Mobile](/assets/screenshots/mobile-preview.png)
![Active state](/assets/screenshots/desktop-active-preview.png)

### Links

- Live Site URL: [FAQ Accordion](https://veena-k-venugopal.github.io/fm-faq-accordion/)

## My process

I started with designing the base HTML and then moved onto styling the mobile layout. Afterwards, I modified necessary elements to reflect the desktop layout design

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

I was able to understand how to mix an image and a solid color to style an element's background
```css
.proud-of-this-css {
    background-image: url(assets/background-pattern-mobile.svg), linear-gradient(var(--light-pink) 25%, var(--light-pink) 100%);
}
```

### Continued development

The backgorund needs to be improved. It's transition on different screen sizes can be changed. 

### Useful resources

- [Multiple backgrounds](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_backgrounds_and_borders/Using_multiple_backgrounds) - This helped me with styling multiple backgrounds

## Author

- Frontend Mentor - [Veena-K-Venugopal](https://www.frontendmentor.io/profile/Veena-K-Venugopal)
