# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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



## Overview

### Screenshot

![Screenshot](./screenshot.jpg)


### Links

- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Media query

### What I learned

Box-sizing - Allows you to include the padding and border size in the overall size of the element.

```css
.card{
    box-sizing: border-box;
}
```

Media query - Allow changing the behavior or properties of the element according to the established condition.

```css
@media(max-width: 958px){
    body{
        overflow: scroll;
    }
    .card-container{
        flex-direction: column;        
    }
}
```

### Continued development

- Mobile first. 
- Flex
- Flex-box
- Flex-grid
- Media query

### Useful resources

- [Flexbox playground](https://codepen.io/enxaneta/full/adLPwv) - This helped me understand a bit more about how to use the flex container and flex item properties. This page is a great reference about flex properties.
- [PerfectPixel by WellDoneCode (pixel perfect)](https://chrome.google.com/webstore/detail/perfectpixel-by-welldonec/dkaagdgjmgdmbnecmcefdhjekcoceebi?hl=en) - This is a Google Chrome extension that allows you to compare the original design with your solution.

## Author

- GitHub - [Fredleo3](https://github.com/Fredleo3)
- Frontend Mentor - [@Fredleo3](https://www.frontendmentor.io/profile/Fredleo3)

## Acknowledgments

![MelvinAguilar](https://www.frontendmentor.io/profile/MelvinAguilar) - In the community feedback on Melvin's solution to this challenge, he answers a question  and mentions that he used the extension PerfectPixel. That extension helped me the size of my solution.

