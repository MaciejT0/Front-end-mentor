# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)

## Overview

The goal of this project was to create QR code.

### Screenshot

images/screenshot.jpg

## My process
1. Linking external CSS file for styling.
2. Using <img> and <p> tags, to add contetnt to the page.
3. Containing content in <div> element in order to be able to manipulate the position of the element as well as creating white background around image and text.
4. In this step I started messing with CSS, first objective was to center content of the page. I used display: flex; on body element, to easliy center content of the page. Then i used justify-content: center; to center items horizontally and align-items: center; to center items vertically. Also added height: 100% to html and body elements, to enlarge the scope of the page.
5. I added some temporary border to elements to be able how much space they are taking.
6. Styling class container, by adding border, padding, background color and aligning text to center.
7. Styling img, by adding border-radius and width element.
8. Added google fonts and styled paragraphs.
9. Styling all content by regulating padding, widths, heights to make it look as close as possible to challange example.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid

### What I learned

-Setting up height: 100%; on body and html elements, when content is smaller then max available space let me center vertically <div> element.
```css
html {
    height: 100%;
}
body {
    height: 100%;
}
```
-Changing display to flex on body element, let me center content by using justify-content: center; and align-items: center;
```css
body {
    display: flex;
    background-color: hsl(212, 45%, 89%);
    height: 100%;
    font-size: 15px;
    justify-content: center;  /*centers content horizontally*/
    align-items: center;  /*centers content vertically*/
}
```
-I learned how to import google fonts using @import:
```css
@import url('https://fonts.googleapis.com/css2?family=Outfit:wght@100..900&display=swap');
```

### Continued development

I feel like I'm missing a lot, by not taking notes about what is my thinking process during designing. So the goal for next challenges is: Taking as much notes about what I'm thinking, what I want to accomplishe and whats the outcome.
