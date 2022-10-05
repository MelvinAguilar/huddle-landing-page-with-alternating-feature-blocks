# Frontend Mentor - Huddle landing page with alternating feature blocks solution

![](./design/desktop-preview.jpg)

This is a solution to the [Huddle landing page with alternating feature blocks challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/huddle-landing-page-with-alternating-feature-blocks-5ca5f5981e82137ec91a5100). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

<h2 align="center">Links</h2>

- Solution URL: [Huddle Landing Page w/ Alternating Blocks (SASS + Mobile-first + BEM) | Frontend Mentor](https://www.frontendmentor.io/solutions/huddle-landing-page-w-alternating-blocks-sass-mobilefirst-bem-k9VlRPw9Tg)
- Live Site URL: [https://huddle-landing-page-with-alternating-feature-blocks-blush-ten.vercel.app/](https://huddle-landing-page-with-alternating-feature-blocks-blush-ten.vercel.app/)


## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
- [My process](#my-process)
  - [Built with](#built-with)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

## My process

### Built with

- Semantic HTML5 markup
- Mobile-first approach
- Flex Layout
- BEM naming convention
- [SASS](https://sass-lang.com/documentation/modules) - Sass modules


### Useful resources


- [SASS Architecture](https://sass-guidelin.es/#architecture)
- [Mobile-first approach](https://www.freecodecamp.org/news/taking-the-right-approach-to-responsive-web-design/)
- [CSS Guidelines](https://cssguidelin.es/#bem-like-naming)
- [BEM naming convention](https://css-tricks.com/bem-101/)
- [BEM naming examples](https://getbem.com/naming/)


- [How TO - Two Column Layout](https://www.w3schools.com/howto/howto_css_two_columns.asp)
- [Material Design Box Shadows](https://codepen.io/sdthornton/pen/wBZdXq)
- [CSS background Property](https://www.w3schools.com/cssref/css3_pr_background.asp)

- [Solving Sticky Hover States with @media (hover: hover)](https://css-tricks.com/solving-sticky-hover-states-with-media-hover-hover/)

## Author

- Frontend Mentor - [@melvinaguilar](https://www.frontendmentor.io/profile/melvinaguilar)

## Acknowledgments

When using `sass` in order to build this solution

- Install `sass` if not yet installed:

```bash
npm install -g sass
```

- Run build command from command line:

```bash
sass assets/sass/main.scss assets/css/style.css
```

- If you want to edit the code and test, in the root folder of this repository, run this command from the command line:

```bash
sass --watch assets/sass/main.scss assets/css/style.css
```

## File structure

```
.
├── assets
│   ├── css
│   │   ├── style.css
│   │   └── style.css.map
│   ├── images
│   │   ├── bg-hero-desktop.svg
│   │   ├── bg-hero-mobile.svg
│   │   ├── favicon-32x32.png
│   │   ├── icon-email.svg
│   │   ├── icon-location.svg
│   │   ├── icon-phone.svg
│   │   ├── illustration-flowing-conversation.svg
│   │   ├── illustration-grow-together.svg
│   │   ├── illustration-mockups.svg
│   │   ├── illustration-your-users.svg
│   │   └── logo.svg
│   └── sass
│       ├── abstracts
│       │   ├── _animations.scss
│       │   ├── _mixins.scss
│       │   └── _variables.scss
│       ├── base
│       │   ├── _page.scss
│       │   └── _reset.scss
│       ├── component
│       │   ├── _attribution.scss
│       │   ├── _buttons.scss
│       │   ├── _heading.scss
│       │   ├── _horizontal-list.scss
│       │   └── _screen-reader.scss
│       ├── layout
│       │   ├── _card.scss
│       │   ├── _footer.scss
│       │   └── _header.scss
│       └── main.scss
├── design
│   ├── active-states.jpg
│   ├── desktop-design.jpg
│   ├── desktop-preview.jpg
│   └── mobile-design.jpg
├── index.html
└── README.md
```