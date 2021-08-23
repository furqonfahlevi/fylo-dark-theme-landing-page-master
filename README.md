# Frontend Mentor - Fylo dark theme landing page solution

This is a solution to the [Fylo dark theme landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/fylo-dark-theme-landing-page-5ca5f2d21e82137ec91a50fd). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [The challenge](#the-challenge)
- [Built with](#built-with)
- [What I learnt](#what-i-learned)
- [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

## My process

### Built with

- Mix (Semantic & Non-Semantic) HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learnt

From this challenge, I learnt about CSS Grid, Position Absolute with Responsive, Transform attribute, Hover between Text and Logo and Z-Index attribute.

To see how you can add code snippets, see below:

```css
.get-early-section {
  position: absolute;
  top: -60%;
  left: 50%;
  transform: translate(-50%, 0);
}

.fylo-works-icon-arrow-content:hover {
  color: white;
  fill: white;
  border-bottom: 1px solid white;
}

.fylo-works-icon-arrow-content:hover a {
  color: white;
}

.fylo-works-icon-arrow-content:hover svg {
  fill: white;
  cursor: pointer;
}

.quote-container {
  position: absolute;
  margin: 0 auto;
  top: -35px;
  left: 50px;
  z-index: -1;
}
```

### Useful resources

- [Stackoverflow](https://stackoverflow.com/) - Stackoverflow really help me to solve my problems.

## Author

- Frontend Mentor - [@furqonfahlevi](https://www.frontendmentor.io/profile/furqonfahlevi)

## Acknowledgments

These are the person who helped me out through this project:

- [Aang/Gluekol] (https://github.com/milhamm)
- [Ditya/Duduh] (https://github.com/Dityath)
