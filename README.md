# Frontend Mentor - Huddle landing page with single introductory section solution

This is a solution to the [Huddle landing page with single introductory section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/huddle-landing-page-with-a-single-introductory-section-B_2Wvxgi0). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Layout](#-layout)
  - [Links](#links)
- [My process](#my-process)
  - [Technologies](#-technologies)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the page depending on their device's screen size
- See hover states for all interactive elements on the page

### 🔖 Layout

<div align="center">
    <p>Web Layout:</p>
    <img src="./design/web-layout.png">
</div>

<div align="center">
    <p>Mobile Layout:</p>
    <img src="./design/mobile-layout.png">
</div>

### Links

- Solution URL: [GitHub Repo](https://github.com/bigodrigo/huddle-frontend-challenge)
- Live Site URL: [GitHub Page](https://bigodrigo.github.io/huddle-frontend-challenge)

## My process

### 🚀 Technologies

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Responsive media queries

### What I learned

I have experience with other projects involving JS and importing icons. In this current project, I have downloaded and incorporated these icons into the CSS. Additionally, my previous work has mainly been focused on Mobile applications, so I am not as familiar with creating hovering styles. However, in this case, I needed to implement a shadow and hover effect. The code snippets below outline the implementation for achieving this effect.

```html
<a href="">
  <i class="fab fa-facebook-f"></i>
</a>
```
```css
.info button {
  background-color: white;
  color: hsl(257, 40%, 49%);
  cursor: pointer;
  transition: 0.3s;
  box-shadow: 5px 5px 3px rgba(0, 0, 0, 0.4);
}

.info button:hover {
  background-color: hsl(300, 69%, 71%);
  color: white;
}
```

## Author

- Portfolio - [Rodrigo](https://portfolio-bigodrigo.vercel.app/)
- GitHub - [bigodrigo](https://github.com/bigodrigo)
- Linkedin - [rodrigo-boquer](https://www.linkedin.com/in/rodrigo-boquer/)
