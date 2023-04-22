# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

-   [Overview](#overview)
    -   [The challenge](#the-challenge)
    -   [Links](#links)
-   [My process](#my-process)
    -   [Built with](#built-with)
    -   [What I learned](#what-i-learned)
    -   [Continued development](#continued-development)
-   [Author](#author)

## Overview

### The challenge

Users should be able to:

-   View the optimal layout depending on their device's screen size
-   See hover states for interactive elements

### Links

-   Solution URL: [Github](https://github.com/levinbaenninger/nft-preview-card-component)
-   Live Site URL: [Netlify](https://nft-card-component-levinbaenninger.netlify.app/)

## My process

### Built with

-   Semantic HTML5 markup
-   CSS
-   Flexbox
-   Mobile-first workflow

### What I learned

I learned how to make the special hover effect on the image. I had to try many different things but in the end it came out pretty well!

```css
.container .main-image {
	position: relative;
}

.container .main-image div {
	position: absolute;
	top: 0;
	background-color: hsl(178, 100%, 50%, 60%);
	width: 100%;
	height: calc(100% - 4px);
	z-index: 999;
	opacity: 0;
	border-radius: 0.5em;
	transition: opacity 0.3s ease-in-out;
}

.container .main-image div:hover {
	opacity: 1;
	cursor: pointer;
}

.container .main-image div img {
	position: absolute;
	left: 50%;
	top: 50%;
	transform: translate(-50%, -50%);
}
```

### Continued development

I futher want to improve my skills on the responsive web design.

## Author

-   Frontend Mentor - [@levinbaenninger](https://www.frontendmentor.io/profile/levinbaenninger)
-   Twitter - [@levinbaenninger](https://www.twitter.com/levinbaenninger)
