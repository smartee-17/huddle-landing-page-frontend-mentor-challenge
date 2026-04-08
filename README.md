# Frontend Mentor - Huddle landing page with single introductory section solution

This is a solution to the [Huddle landing page with single introductory section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/huddle-landing-page-with-a-single-introductory-section-B_2Wvxgi0). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- View the optimal layout for the page depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

![HuddleLanding Page Screenshots on multiple devices](./photo-collage.png%20(1).png)

### Links

- Solution URL: [Huddle landing page challenge solution link ](hhttps://www.frontendmentor.io/solutions/responsive-huddle-landing-page-with-single-introductory-0eMYlBc1Qk)
- Live Site URL: [Huddle landing page preview](https://smartee-17.github.io/huddle-landing-page-frontend-mentor-challenge/huddle-landing-page-with-single-introductory-section-master%20-%20Copy/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flex-box
- CSS Grid
- Mobile-first workflow

### What I learned

- Responsive design: Using CSS Grid and Flex-box along with custom properties allowed me to quickly adjust layouts for mobile and desktop.

- CSS variables: Made styling consistent across spacing, typography, colors, and components.

- SVG styling: Inline SVGs with the class="icon" allowed hover effects and color changes while respecting prefers-reduced-motion.

- Accessibility: Implemented prefers-reduced-motion media query to respect users who prefer minimal animations.
- Example: 
```css
  @media (prefers-reduced-motion: reduce) {
  .icon {
    transition: none;
  }
  .icon:hover {
    transform: none;
  }
}
```
### Continued development
- Improve typography scaling for larger screens.
- Add animation enhancements that respect accessibility preferences.
- Explore using React components to make sections reusable for larger projects.

### Useful resources 
- [Frontend Mentor Documentation](https://www.frontendmentor.io/docs) - Reference for challenge requirements.
- [MDN CSS Variables](https://developer.mozilla.org/en-US/docs/Web/CSS/Using_CSS_custom_properties) - Helped standardize CSS variables across components.
- [CSS Tricks Flexbox Guide](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - Useful for responsive layout design.

## Author

- Name: Smartee-18
- Frontend Mentor - [smartee-17](https://www.frontendmentor.io/profile/smartee-17)

## Acknowledgments

- Thanks to Frontend Mentor for the challenge and providing design files.

- Inspired by other developers’ solutions for hover effects and responsive layout patterns.
