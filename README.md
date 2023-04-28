# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

(./images/screenshot.jpg)


### Links

- Solution URL: (https://github.com/brunomoleta/animated-guide)
- Live Site URL: (https://brunomoleta.github.io/animated-guide/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox


### What I learned

This challenge was the first time in which I separated the css in different files making it more organized. 
Building the static card was straightforward with Flexbox.
The difficult part was to make interactive elements change all at once.
To accomplish the task I used:

To see how you can add code snippets, see below:

```html
<h1>Some HTML code I'm proud of</h1>
```
```css
.container:hover > #overlay > .img-nft {
  opacity: 0.5;
  border-radius: 0.5rem;
}

.container:hover > #overlay > .img-nft > #view {
    opacity: 1;
}


.container:hover > #overlay > .img-nft > #view,
.container:hover > #overlay > .img-nft{
  transition: opacity 500ms;
}

.container:hover > h1,
.container:hover > .credits > p > .author {
  color: var(--primary-cyan);
}
```
All the elements are linked to the hover of the card (.container), so when this element is hovered everything especified interacts.

```js
const proudOfThisFunc = () => {
  console.log('🎉')
}
```

If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more.

**Note: Delete this note and the content within this section and replace with your own learnings.**

### Continued development


**Note: Delete this note and the content within this section and replace with your own plans for continued development.**

### Useful resources

- [Jad Joubran's HTML/CSS course](https://learnhtmlcss.online/) - Jad Joubran's website is a valuable resource for begginers.
- [Josh Cameau blog](https://www.joshwcomeau.com/) - This website goes deep conceptually an it makes it visual explanations, I believe it's great.

## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@brunomoleta](https://www.frontendmentor.io/profile/brunomoleta)
