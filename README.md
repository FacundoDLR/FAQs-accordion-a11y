# Frontend Mentor - FAQ accordion

![Design preview for the FAQ accordion coding challenge](https://fa-qs-accordion-a11y.vercel.app/design/desktop-preview.jpg)

## Welcome! 👋
Hi stranger! Let me intoriduce you to my new project. I hope you enjoy it and don´t forget, if you have any suggestion to help me improve my tech skill no doubt in touch me!! 🚀

Thanks for checking out this front-end coding challenge.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

## The challenge

Your challenge is to build out this FAQ accordion and get it looking as close to the design as possible.

Your users should be able to: 

- Hide/Show the answer to a question when the question is clicked
- Navigate the questions and hide/show answers using keyboard navigation alone
- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page

### Screenshot

> PC

![PC](/assets/screenshots/MacBook-FAQs.jpeg)

> Mobile

![Mobile](/assets/screenshots/iPhone-FAQs.jpeg)

### Links

- [Solution URL over here](https://github.com/FacundoDLR/FAQs-accordion-a11y.git)
- [Live Site URL over here](https://fa-qs-accordion-a11y.vercel.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- Accesibility WCAG AA

### What I learned

To see how you can add code snippets, see below:

```html
<details>
  <summary>Mostrar más</summary>
  <p>contenido</p>
</details>
```
How to remove native arrow from component
```css
details summary {
  cursor: pointer;
  position: relative;
  list-style: none;
}
```
To remove the arrow in browsers like Chrome and Safari we will use the `::-webkit-details-marker property`
```css
details summary::-webkit-details-marker {
  display: none;
}
```

### Useful resources

- [Accordion accessible y reutilizable solo con la etiqueta details y css](https://dev.to/micaavigliano/accordion-accessible-y-reutilizable-solo-con-la-etiqueta-details-y-css-3hb4)
- [Exclusive accordions using the HTML details element](https://developer.mozilla.org/en-US/blog/html-details-exclusive-accordions/)

## Author 🤩
- GitHub - [FacundoDLR](https://github.com/FacundoDLR)
- Frontend Mentor - [@FacundoDLR](https://www.frontendmentor.io/profile/FacundoDLR)