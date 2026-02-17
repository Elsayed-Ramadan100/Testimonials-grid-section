

# Frontend Mentor - Testimonials grid section solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Links

- Solution URL: [Add your solution URL here]
- Live Site URL: [Add your live site URL here]

## My process

### Built with

- Semantic HTML5 markup
- CSS Grid
- Flexbox
- Responsive Web Design (Media Queries)
- [Google Fonts](https://fonts.google.com/) - Barlow Semi Condensed

### What I learned

In my previous project, I set a goal to learn and implement **CSS Grid** for complex layouts. In this project, I successfully achieved that goal! I learned how powerful `grid-template-areas` can be for positioning elements exactly where they need to go, making the HTML structure much cleaner.

Here is the CSS snippet showcasing how I used grid areas to build the desktop layout:

```css
.grid-container {
    width: 77%;
    display: grid;
    grid-template-areas: 
        "a a b c" 
        "d e e c";
    grid-template-columns: 1fr 1fr 1fr 1fr;
    grid-template-rows: 1fr 1fr;
    gap: 30px 38px;
}

```

I also learned how to seamlessly combine **CSS Grid** for the macro-layout (the main container) with **Flexbox** for the micro-layout (aligning the user image, name, and verified status inside each card):

```css
.inline {
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;
    width: 100%;
}

```

### Continued development

Now that I have a solid understanding of both Flexbox and CSS Grid, I want to focus on creating more fluid and responsive typography using functions like `clamp()` or `calc()`. I also plan to start exploring CSS variables (Custom Properties) more deeply to manage colors and spacing across my entire stylesheet efficiently.

## Author

* Name - Elsayed Ramadan
* GitHub - [@Elsayed-Ramadan100]()
* LinkedIn - [Elsayed Ramadan]()
