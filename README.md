# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Frontend Mentor - Blog preview card solution](#frontend-mentor---blog-preview-card-solution)
  - [Table of contents](#table-of-contents)
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

- See hover and focus states for all interactive elements on the page

### Screenshot

![desktop screenshot](/desktop.png)

![mobile screenshot](/mobile.png)

### Links

- Solution URL: [blog card preview on github](https://github.com/dearestalexander/blogCardPrev)
- Live Site URL: [blog card preview on github pages](https://dearestalexander.github.io/blogCardPrev/)

## My process

- Read the specification and take some notes
- It was my first time using variable fonts, so I started by reading up on it
- I then started by drafting the HTML
- Then the CSS for desktop
  - I started by setting variables for all colours and the base font-size
  - I then set up the layout:
    - At first I set the frame, and then aligned inner elements using margin-left
    - Afterwards I adjusted to add padding to the frame
    - This allowed me to remove left-margin from all the inner elements, simplifying it
  - Then I adjusted the content for all the elements:
    - I used calc() to set font-sizes on the basis of the variable for the paragraph font
    - This made it easy to slightly reduce font-size for mobile
- Finally the CSS for mobile:
  - I only had to make minor adjustments to width, height and font.

### Built with

- CSS:
  - Variables and calc() method to set font-sizes relative to the base paragraph size
  - Flexbox
  - @Media

### What I learned

- I learnt about variable fonts, the links provided were very interesting and useful
- I also had the chance to refresh my memory using calc() when setting font sizes
- Also refreshed my memory on shadows
- The layout:
  - I liked the background highlighted 'topic' below the image
  - I also like how varied font size and weight is utilised

### Continued development

I'm currently working on my own website and I think I will work on some variations of this for it.

### Useful resources

Mainly the provided references on variable fonts.

## Author

- Website - [Alexander Roan (kind of under construction)](https://www.alexroan.com)
- Frontend Mentor - [@dearestalexander](https://www.frontendmentor.io/profile/dearestalexander)
- Twitter - [@xander_roan](https://x.com/xander_roan)

## Acknowledgments

Thanks for FrontendMentor for this exercise
