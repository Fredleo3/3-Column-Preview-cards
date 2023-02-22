# Frontend Mentor - 3-column preview card component solution

Hi! This is my solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

![Screenshot](https://github.com/Fredleo3/3-Column-Preview-cards/blob/main/assets/images/screenshot.PNG)


### Links

- Live Site URL: [3-column preview cards solution](https://fredleo3.github.io/3-Column-Preview-cards/)

## My process

### Built with

- Semantic HTML5 markup
- Mobile first
- CSS custom properties
- Flexbox
- Media query

### What I learned

Box-sizing - Allows you to include the padding and border size in the overall size of the element.

```css
.card{
    box-sizing: border-box;
}
```

letter-spacing - Allows you to change the space between characters.

```css
.card-title{    
    letter-spacing: 0.06em;
}
```

line-height - Allows you to change the space between text lines.

```css
.card-paragraph{
    line-height: 1.8em;  
}
```

flex-grow - Allows you to set how much a flex element can grow relative to other flex elements in the same box.

```css
main{  
    flex-grow: 1;
}
.attribution{
    flex-grow: 0;   
}
```

Media query - Allow changing the behavior or properties of the element according to the established condition.

```css
@media (min-width: 1440px){
    html, body{
        overflow: hidden;
    } 
    body{
        display: flex; 
        flex-direction: column;   
    }
    
    main{
        margin-top: 10em;
    } 
    .card-container{
        display: flex;
        align-items: center;
        justify-content: center;  
        min-width: 20em;      
    }    
    .card-container{
        min-width: 54em;
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

- [MelvinAguilar](https://www.frontendmentor.io/profile/MelvinAguilar) - In the community feedback on Melvin's solution to this challenge, he answers a question  and mentions that he used the extension PerfectPixel. That extension helped me the size of my solution.

