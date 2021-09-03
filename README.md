# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
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

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

Desktop design

![](https://i.imgur.com/6rzrKJc.png)

Mobile design

![](https://i.imgur.com/UYJd0WN.png)



### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [https://bryan-cloud.github.io/StatsPreviewCardComponent/](https://bryan-cloud.github.io/StatsPreviewCardComponent/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow


### What I learned

I am really happy to know that I have lerned how I can add a background image and also a background color both of them at the same time using the CSS property "background-blend-mode" with the value "soft-light" in order to have the faded pink background color and also the background image:

```html
<section class="img-color">
```
```css
.container .img-color {
    width: 100%;
    height: 25em;
    background-image:url(https://i.imgur.com/hTcFdjS.jpg);
    background-color: rgba(170, 91, 219, 0.7);
    background-blend-mode: soft-light;
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover; }
```

### Continued development

I am committed to keep improving my skills when naming classes and also how to make better responsive images to avoid using so much mediaqueries for them.

### Useful resources

- [How to fade backgrounds with CSS along with images](https://www.youtube.com/watch?v=Rtw7c4S_JyI&t=319s) - This helped me because I did not know how to mix a background image and a background color at the same time.

## Author

- Website - [bryancloud.dev](https://bryancloud.dev)
- Frontend Mentor - [@bryan-cloud](https://www.frontendmentor.io/profile/bryan-cloud)
- Twitter - [@bportillo701](https://twitter.com/bportillo701)


## Acknowledgments

I really want to thank to Codigofacilito, it's a spanish channel on Youtube I learned how to work with the hero image and how to fade it with CSS.

You can check their videos [here:)](https://www.youtube.com/channel/UCLXRGxAzeaLDGaOphqapzmg)
