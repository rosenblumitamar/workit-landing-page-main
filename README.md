# Frontend Mentor - Workit landing page solution

This is a solution to the [Workit landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/workit-landing-page-2fYnyle5lu). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page

### Screenshot

#### Desktop View
![desktop-view](/images/desktop-view.png)

#### Tablet View
![tablet-view](/images/tablet-view.png)

#### Mobile View
![mobile-view](/images/mobile-view.png)

### Links

- Solution URL: [https://www.frontendmentor.io/solutions/workit-landing-page-033HPRZjcZ](https://www.frontendmentor.io/solutions/workit-landing-page-033HPRZjcZ)
- Live Site URL: [https://workit-landing-page-project.netlify.app/](https://workit-landing-page-project.netlify.app)

## My process

### Built with

- Semantic HTML5 markup
- CSS Variables
- CSS Flexbox
- CSS Media Queries

### What I learned

I learned how to create CSS Counters using CSS Counters and Content properties:

```css
ul {
  list-style-type: none;
  counter-reset: card;
}

li::before {
  counter-increment: card;
  content: counters(card, " ");
}
```

I learned how to create curved sections using CSS Border Radius property:

```css
div {
  border-bottom-left-radius: 55% 15%;
  border-bottom-right-radius: 55% 15%;
}
```

I learned how to use CSS Background property, and set both background image and background color:

```css
div {
    background:
  url("/images/bg-pattern-1.svg") no-repeat -100px 150px,
  url("/images/bg-pattern-2.svg") no-repeat 103.5% 360px,
  var(--purple);
}
```

I learned how to create CSS Media Queries for different screen sizes:

```css
/* Small tablets to big tablets up to 1024px */
@media screen and (max-width: 1024px) { }

/* Small phones to small tablets up to 767px */
@media screen and (max-width: 767px) { }

/* Small phones up to 480px */
@media screen and (max-width: 480px) { }

/* Small phones up to 390px */
@media screen and (max-width: 390px) { }
```

I learned how to change an image color using CSS Filter property:

```css
img:hover { filter: contrast(2); }
```

### Continued development

I'm to continue honing my skills in responsive web design, focusing specifically on mastering CSS Flexbox and Grid techniques.

### Useful resources

- [W3Schools - CSS Counters](https://www.w3schools.com/css/css_counters.asp) - This article helped me to understand how to create CSS Counters.
- [W3Schools - CSS Image Filter Effects](https://www.example.com) - This article helped me to understand CSS Image Filter Effect.
- [Stackoverflow - Curved Sections With Pure CSS](https://stackoverflow.com/questions/54719260/curved-header-with-pure-css) - This post helped me to understand how to create cuvred scetions using CSS.
- [CSS-Tricks - Media Queries for Standard Devices](https://css-tricks.com/snippets/css/media-queries-for-standard-devices/) - This article helped me to understand better CSS Media Queries.

## Author

- Frontend Mentor - [@rosenblumitamar](https://www.frontendmentor.io/profile/rosenblumitamar)
- Twitter - [@rosenblumitamar](https://x.com/ItamarRosenblum)
