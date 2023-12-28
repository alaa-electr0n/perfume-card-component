# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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
- See hover and focus states for button element

### Screenshot

![](./images/screenshots/challenge%20mobile-view.png)
![](./images/screenshots/challenge%20pc-view.png)

### Links

- Solution URL: [solution on Github](https://github.com/alaa-electr0n/perfume-card-component)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

I Learned more about Semantic HTML Element : <figure> and <figcaption> from [W3Schools as a resource](https://www.w3schools.com/tags/tag_figure.asp)

The HTML structure is designed with a semantic approach to enhance accessibility and readability:

- **`<figure class="perfume">`**: Represents the main card container for the perfume details.
  - **`<div class="perfume__hero">`**: Contains images displaying the perfume product in both desktop and mobile views.
  - **`<div class="perfume__details">`**: Houses the title, description, price, and "Add to Cart" button.
    - **`<h1 class="perfume__title">`**: Includes the perfume title.
      - **`<span class="perfume__title-sub">`**: Represents the subtype or category of the perfume.
      - **`<span class="perfume__title-main">`**: Displays the main title of the perfume.
    - **`<figcaption class="perfume__description">`**: Provides a description of the perfume.
    - **`<p class="perfume__price">`**: Displays the price of the perfume.
    - **`<a href="#" class="btn btn--green">`**: A link styled as a button for adding the product to the cart.
- **`<div class="attribution">`**: Displays attribution for the challenge and coder.

#### Techniques Used in CSS

The CSS code employs various techniques and practices to style the Perfume Card Component:

- **Reset and Variables**: Utilizes a CSS reset to normalize styles across different browsers and defines variables for consistent color schemes and fonts.
- **General Styling**:
  - Utilizes `grid` for layout and positioning elements within the `.perfume` container.
  - Defines responsive units (`rem`, `%`, `px`) for sizing and positioning elements.
  - Utilizes `box-shadow` for a subtle shadow effect on the card.
- **Responsiveness**:
  - Implements media queries (`@media`) for responsiveness across different screen sizes.
  - Adjusts font sizes, layout, and image display for smaller devices (e.g., mobiles).

## Author

- Frontend Mentor - [@alaa-electr0n](https://www.frontendmentor.io/profile/alaa-electr0n)
