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
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Links

- Solution URL: [HERE](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-/hub/3column-preview-card-component-n_0pbp9n8)
- Live Site URL: [HERE](https://ma1021.github.io/05_3-column-preview-card-component-main/)

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

**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

1. Curiosity on should I use img tag or psuedo selector to place the icon

https://stackoverflow.com/questions/41087410/why-use-before-pseudo-elements-to-display-glyph-icons

Intense discussion over should img use or background-image used
https://stackoverflow.com/questions/492809/when-to-use-img-vs-css-background-image?page=1&tab=votes#tab-top

2. Difference between :before and ::before

First of all, they are the same. :before is the CSS2 syntax while ::before is the CSS3 syntax. Why they need to renew the syntax? This is done to separate pseudo-element(::type) from pseudo-class(like :hover), more in https://www.d.umn.edu/~lcarlson/csswork/selectors/pseudo_dif.html.

Their difference is pseudo-element selecting part of the element, while pseudo-class specifying the state of the element.

The syntax of using :: 
https://stackoverflow.com/questions/7327326/what-is-the-difference-between-before-and-before

3. Struggling on how to deal with mobile size

This website helped me alot!!! He really did the mobile first responsive design!!!!! I should not be too stubborn on using flex on everything. Simply using div will already make the div stack by themselves.

https://github.com/SankThomas/3-column-preview-card-component/blob/main/style.css


Too tired to put all the details this time. I will redo this challenge using the mobile first approach.

### Continued development

Practice on mobile first. Try not to think too complicated

## Author

- Frontend Mentor - [@Ma1021](https://www.frontendmentor.io/profile/Ma0121)

## Acknowledgments

Amazing code by tsbsankara!
https://www.youtube.com/watch?v=2Wy_MJPDfCw
