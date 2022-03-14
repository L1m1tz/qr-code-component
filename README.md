# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Frontend Mentor - QR code component solution](#frontend-mentor---qr-code-component-solution)
  - [Table of contents](#table-of-contents)
  - [Overview](#overview)
    - [Screenshot](#screenshot)
    - [Links](#links)
  - [My process](#my-process)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)
    - [Continued development](#continued-development)
    - [Useful resources](#useful-resources)
  - [Author](#author)

## Overview

### Screenshot

![](./screenshot.png)

### Links

- Solution URL: [qr component github](https://github.com/L1m1tz/qr-code-component)
- Live Site URL: [qr component live](https://l1m1tz.github.io/qr-code-component/)

## My process


### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Desktop first workflow


### What I learned

In this exercise I've learned how to use Grid and flexboxs in much more effective manner. 
centering the container for the NFT componet to the center of the screen has been a challange

to accomplish the centering of the componet,
I created a div called page to cover 90% of the page, i then gave it a grid property.
I then used the place-items:center property to center the component 



```html
<div id="page">
```
```css
#page {
      display: grid;
      place-items: center;
      height: 90%;
      margin: auto;
    }
footer {
      background: hsl(218, 44%, 22%);
      height: 10%;
      padding: 0;
      color: white;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
    }
```




### Continued development

I'd like to continue strengthening my css grid and flexbox understanding

### Useful resources

- [Flexbox Layout](https://youtu.be/3YW65K6LcIA) - This video helped me gather the basics of flexbox it.
  
- [Flexbox Froggy](http://flexboxfroggy.com/) - This game helped me gain a better understanding of how all the different flex properties work.
  
- [How to build your own css Grid Container](https://www.udacity.com/blog/2021/06/how-to-build-your-own-css-grid-container.html) - This blog post helped me gather the basics of gid.


## Author

- Website - [Andrewmk](http://siteforge.co.za/)
- Frontend Mentor - [@L1m1tz](https://www.frontendmentor.io/profile/L1m1tz)

