# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

creation of a page that only contains a card with a qr code and a short description.

### Screenshot

![](./screenshot.png)

## My process


### Built with

- HTML5
- CSS custom properties
- Flexbox

### What I learned

It took me a bit to center the main div but in the process I finally got around to it, I got a better understanding of the flexbox placement and how to center the overall content, its padding and margins.

```html
<div class="contenedor">
    <div class="container">
      <img src="/images/image-qr-code.png" alt="Code qr">
      <h2>Improve your front-end skill by building projects</h2>
      <p>Scan the QR code to visit Frontend Mentor and take your coding skills to the next level.</p> 
    </div>
  </div>
```
```css
.contenedor {
    display: flex;
    justify-content: center;
    justify-items: center;
    margin: 150px 0;
    padding: 30px 0;
}

@media (min-width: 350px ) {
    .card {
        background-color: white;
        display: flex;
        justify-content: center;
        justify-items: center;
        flex-direction: column;
        padding: 25px;
        border-radius: 25px;
        max-width: 70%;
        -webkit-box-shadow: 4px 8px 8px -3px rgba(178,191,190,1);
        -moz-box-shadow: 4px 8px 8px -3px rgba(178,191,190,1);
        box-shadow: 4px 8px 8px -3px rgba(178,191,190,1);
    }
}
```

### Continued development

further improve the use of flexbox


## Author

- Frontend Mentor - [@isghost19](https://www.frontendmentor.io/profile/isghost19)

## Acknowledgments
none.
