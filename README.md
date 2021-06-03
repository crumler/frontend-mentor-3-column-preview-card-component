# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)


## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements (in this project's case: the buttons)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

I started off by utilizing CSS Flexbox to ensure that the container that would house the content would be displayed in the center of the page.

Once that was completed, I utilized Flexbox again to ensure that each section (Sedan, SUVs, Luxury) was relegated to their own respective areas.

From there, I began styling the elements based on the instructions provided by the project's style guide.

After that, I began to match the font sizes, margin, and padding of each of my elements with the example design screenshots that were included in this project.

Once I was satisfied with that, I created media queries for mobile responsiveness.  The primary purpose of this was to change the flex direction of my content container's from "row" to "column".  I also made some changes to the margins.

Once I was done, I went back and re-factored my code (which included creating CSS variables for the various colors that were used in this project).

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

This project marked the first time that I looked at documentation to learn how creating and utilizing CSS variables worked.

### Continued development

I am not confident that I went about utilizing the images properly.  As I shrink and grow the browser window, the images shrink and grow with the size of the browser.  I do not believe that is optimal, but I am unsure how to correct it (if it truly is not optimal).

I also have issue with how the buttons shift unevenly with each other when the browser window shrinks and grows at certain breakpoints.  But, again, I'm unsure how to address that.

## Author

- Website - [Chris Rumler](https://www.chrisrumler.com)
- Frontend Mentor - [@crumler](https://www.frontendmentor.io/profile/crumler)