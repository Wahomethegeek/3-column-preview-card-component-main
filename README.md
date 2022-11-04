# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)




## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![desktop ](./images/Screenshot%202022-11-04%20at%2023-10-16%20Frontend%20Mentor%203-column%20preview%20card%20component.png)
![mobile](./images/Screenshot%202022-11-04%20at%2023-10-57%20Frontend%20Mentor%203-column%20preview%20card%20component.png)


### Links

- Solution URL: [solution URL here](https://github.com/Wahomethegeek/3-column-preview-card-component-main.git)
- Live Site URL: [live site URL here](https://3-column-preview-card-component-nine-tau.vercel.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Desktop-first workflow



### What I learned

I was able to remind myself on how to use flexbox and using pseudo classes.

```css
.card:first-child{
    background-color: var(--bg-color-sedans);
    border-radius: 10px 0 0 10px ;
   
}
.card:nth-child(2){
    background-color: var(--bg-color-suvs);
}
.card:nth-child(3){
    background-color: var(--bg-color-luxury);
    border-radius: 0 10px 10px 0 ;
}
```


## Author

- Frontend Mentor - [wahomethegeel](https://www.frontendmentor.io/profile/Wahomethegeek)
- Twitter - [@_Wahomekelvin](https://www.twitter.com/_Wahomekelvin)

