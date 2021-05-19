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
  - [Useful resources](#useful-resources)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![result](result/desktop.jpg)

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Desktop-first workflow
- [React](https://reactjs.org/) - JS library (planning on using)

### What I learned

```html
<h1>Some HTML code I'm proud of</h1>
```

```css
/* How to center elements */
.container {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
}

/* Another way to center or space the element equally by using margin: auto */
.static {
  display: flex;
  flex-direction: column;
  margin-right: auto;
}

/* How to make the embedded image to have a round corner */
.card {
  display: flex;
  border-radius: 1rem;
  background-color: var(--color-accent);
  width: 75%;
  height: 55%;
  overflow: hidden;
}

/* How to space each flex item  */
.card-content {
  display: flex;
  flex-direction: column;
  background: var(--color-card-primary);
  justify-content: space-evenly;
  margin: 0;
  padding: 2rem;
}

/* How to blend the image and background color, and how to scale the size of the image */
.card-image {
  mix-blend-mode: multiply;
  object-fit: cover;
}
```

### Useful resources

- [Flex box tutorial](https://www.youtube.com/watch?v=fYq5PXgSsbE&t=376s) - This helped me understand the basics of flex layout. It's really clear.
