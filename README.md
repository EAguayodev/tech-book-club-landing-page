# Frontend Mentor - Tech book club landing page solution

This is a solution to the [Tech book club landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/tech-book-club-landing-page-fZQidjHU73). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Vercel](https://tech-book-club-landing-page-alpha.vercel.app/)

## My process
For the Tech Book Club Landing Page challenge, I employed a desktop-first workflow to build the design. Here’s a breakdown of my process:

1. HTML Structure:

I began by creating the semantic HTML structure for the page, ensuring the layout followed a logical and accessible hierarchy.
Class names and IDs were chosen to align with the content sections, improving readability and maintainability.


2. Desktop Styling with CSS:

- Starting with desktop screen sizes, I styled the page using CSS Flexbox to create a clean and organized layout.
- I focused on ensuring consistent spacing, alignment, and typography across the design.
- Styling decisions were influenced by the desktop design specifications, with particular attention to responsive font sizes and grid alignment.


3. Adapting for Tablet and Mobile:

- After completing the desktop layout, I added media queries to adapt the design for smaller screen sizes.
- Using Flexbox, I restructured the layout for tablet and mobile views, stacking elements where necessary to improve readability and user experience.
- Adjustments included:
  - Scaling down font sizes.
  - Reorganizing content blocks to fit the smaller screens.
  - Modifying padding and margins to maintain a balanced appearance.


4. Testing and Refinements:

- I tested the layout across different screen sizes to ensure the design was fully responsive.
- Iterations were made to improve alignment and spacing for an optimal user experience on all devices.

By following this structured approach, I successfully created a visually appealing, responsive landing page that adapts seamlessly to various screen sizes while maintaining the design’s original intent.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Desktop-first workflow

### What I learned



To see how you can add code snippets, see below:

```html
<section class="ultimate-tech__section">
    <a href="index.html">
      <img class="logo" src="assets/images/logo.svg" alt="Tech book club">
    </a>
    <div class="row">
     <div>
      <h1 class="book-club__heading">Join the ultimate tech book club</h1>
      <p class="book-club__description">
        Turn your reading time into learning time with fellow tech enthusiasts.
        Get curated recommendations, join vibrant discussions, and level up your
        skills one chapter at a time.
      </p>
      
      <button class="btn btn-member__options">Review membership options <img src="assets/images/icon-arrow-down.svg" alt="arrow pointing down"></button>
      
      <div class="avatars-box">
        <div>
          <img class="testimonial-avatars" src="assets/images/image-avatars.webp" alt="avatar img of testimonials">
        </div>
        <div>
          <img class="icon-star" src="assets/images/icon-star.svg" alt="icon star">
          <img class="icon-star" src="assets/images/icon-star.svg" alt="icon star">
          <img class="icon-star" src="assets/images/icon-star.svg" alt="icon star">
          <img class="icon-star" src="assets/images/icon-star.svg" alt="icon star">
          <img class="icon-star" src="assets/images/icon-star.svg" alt="icon star">
          <p class="joined-description">200+ developers joined already</p>
        </div>
      </div>
     </div>
     <div>
     <picture>
       <source srcset="assets/images/image-hero-mobile.webp" media="(min-width: 29.99rem)">
       <source srcset="assets/images/image-hero-tablet.webp" media="(min-width: 30rem) and (max-width: 47.99rem)">
       <source srcset="assets/images/image-hero-desktop.webp" media="(min-width: 48rem)">
      <img class="image-hero" src="assets/images/image-hero-mobile.webp" alt="image hero of bookclubbers socializing">
     </picture>
    </div>
    </div>
  </section>
```
```css
.book-club__heading {
    background: linear-gradient(107deg, #FF9A60 -11.37%, #062630 61.84%);
    -webkit-text-fill-color: transparent;
    background-clip: text;
    font-size: 3.875rem;
    font-family: var(--martian-mono);
    font-weight: 600;
    width: 35.625rem;
}
```

### Continued development
For continued development when improving my css skills will be to consistently incorporate css resets (didn't add it for this challenge) to ensure consistency across all browsers, and undo all default styles. In addition, I'll be getting back on course to mastering my skills in Javascript and learning a js framework so I'm job ready for web developer roles by end of April; currently web content editor and email developer.

### Useful resources

- [MDN web docs](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/picture) - This helped me for XYZ reason. I really liked this pattern and will use it going forward.
still learning this concept.

## Author

- Website - [Eric Aguayo](https://www.ericaguayo.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/EAguayodev)

## Acknowledgments