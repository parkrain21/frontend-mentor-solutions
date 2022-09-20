# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)


## Overview

### Screenshot

![Full](./screenshots/screenshot1.png)
![Narrow](./screenshots/screenshot2.png)


### Links

- Solution URL: [Add solution URL here](https://github.com/parkrain21/frontend-mentor-solutions/tree/main/1.%20QR%20Component)

## My process
1. Created 3 divs:
  - `.site-container` for the whole site container (the lightblue background)
  - `.qr-container` for the qr card (the white background)
  - `.qr-image` for the qr code image itself
2. Used flexbox for the `.qr-container` positioning

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Flexbox

### What I learned

Learned how to set/initialize the document size using the universal selector.
```css
/* Globals */
* {
    margin: 0;
    padding: 0;
    font-family: 'Outfit', sans-serif;
}

html,
body {
    height: 100%;
    width: 100%;
}
```

Also learened how to center a div using the `direction: flex;` style.
```
.site-container {
    background: #d5e1ef;
    height: 100vh;
    display: flex;
    align-items: center;
    justify-content: center;
}
```