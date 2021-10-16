# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). 

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

### Screenshot

![Desktop Layout](/design/Desktop-1440.png)
Desktop Layout (1440 px)  

![Mobile Layout](/design/iPhone%20X.png)
Mobile Layout (375 px)  

### Links

- [Solution URL](https://github.com/Muhammad-Nabeel-Sh/Stats-Preview-Card-Component-Challenge-Hub)
- [Live Site URL](https://muhammad-nabeel-sh.github.io/Stats-Preview-Card-Component-Challenge-Hub/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Variables


### What I learned

Throughout this challenge, I reinforced some frontend skills :

* Using emmet abbreviations for writing markup more efficiently 

```
div.flex-container-outer[role="grid"]>(div.flex-container-inner[role="row"]>div.flex-item.item-head[role="gridcell"]+div.flex-item.item-head[role="gridcell"])*3
```

```html
<div class="flex-container-outer" role="grid">
  <div class="flex-container-inner" role="row">
    <div class="flex-item item-head" role="gridcell"></div>
    <div class="flex-item item-head" role="gridcell"></div>
  </div>
  <div class="flex-container-inner" role="row">
    <div class="flex-item item-head" role="gridcell"></div>
    <div class="flex-item item-head" role="gridcell"></div>
  </div>
  <div class="flex-container-inner" role="row">
    <div class="flex-item item-head" role="gridcell"></div>
    <div class="flex-item item-head" role="gridcell"></div>
  </div>
</div>
```

* Manipulating an image on Photoshop then styling the image using css blend modes and filter properties

```css
figure {
  background-blend-mode: multiply;
  filter: contrast(85%) brightness(120%) saturate(1.5) grayscale(0.2);
}
```

* Using `transform: translateX() | translateY();` to vertically position objects
* Using `:not()` CSS pseudo class
* 
* Using **Github Pages**
* Documenting steps and learnt skills through this `README.MD` file
* Setting a default font size then using relative units `em` and `rem`
* Listing the color palette and assigning it to CSS variables
* Making a responsive UI for multiple screen sizes
* Incorporating accessibility features:
  * Roles
  * Landmarks and sectioning elements

## Author

- [Frontend Mentor](https://www.frontendmentor.io/profile/Muhammad-Nabeel-Sh)
- [LinkedIn](https://www.linkedin.com/in/muhammad-nabil-ibrahim-728b571b8/)