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


## Overview

### Screenshot

      ***COMPLETE QR CODE COMPONENT***

![](images/QR-code-component.png)



### Links

- Solution URL: [Add solution URL here](https://github.com/Siyamabuza/QR-code-component-solution-frontend-mentor.git)
- Live Site URL: [Add live site URL here](https://github.com/Siyamabuza/Siyamabuza.github.io)

## My process

-I started by drawing the layout to determine how everything is placed.
-Created three(3) divs and ,added the image , h1 ,p tags.
-Determine whether to use grid or flexbox.
-Added CSS to the body ,h1 and p tag. 
-styled the content div (because it was easier).
-Styled the container div.
-added borders to all the divs to see the layout.
-fit the image in the container div.
-Removed all the unnecessary styles and cleaned my code to the best of my abilty.


### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

In this challenge i learned to fit images in a div and make the image fit in the div ,work with flexbox and add google fonts to my project.

```html
<div class="qr-code-container">
      <img src="images/image-qr-code.png" alt="QR-code" class="qr-code-image">
    </div>
```
```css
body {
  font-family: 'Outfit', sans-serif;
  background-color: hsl(212, 45%, 89%);
  display: flex;
  flex-direction: column;
  align-items: center;
  text-align: center;
  margin: 100px;
}

.qr-code-container {
  border-radius: 16px;
  width: 325px;
  height: 325px;
  margin-top: 20px;
  margin-left: 25px;
  margin-right: 25px;
}

.qr-code-image {
  width: 100%;
  height:100%;
  border-radius: 12px;
}
```

### Continued development

I still need to improve my development thought proccess and figuring out whether to use grid or flexbox by looking at the design.I need to work on flexbox and improve my skill in this area of css and also learn to position items. 

### Useful resources

- [w3schools resource 1](https://www.w3schools.com/css/css3_flexbox_container.asp) - This helped me to understand flexbox column and rows.
- [w3schools resource 2](https://www.w3schools.com/css/css3_object-fit.asp) - This helps to understand how images works and learned about the object-fit property
- [https://chat.openai.com/] Used ChatGPT to search : How to fit an image inside a div using html

## Author

- Website - [GitHube](https://github.com/Siyamabuza/Siyamabuza.github.io)
- Frontend Mentor - [Siyabonga Mabuza](https://www.frontendmentor.io/profile/Siyamabuza)

