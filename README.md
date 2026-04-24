# Frontend Mentor - Social links profile solution

This is a solution to the [Social links profile challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ).

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [AI Collaboration](#ai-collaboration)
- [Author](#author)

## Overview

### The challenge

Users should be able to:
- See hover and focus states for all interactive elements on the page.
- View the optimal layout depending on their device's screen size.

### Links

- Solution URL: [https://github.com/ZakiAlkhaf16/social-links-profile]
- Live Site URL: [https://zakialkhaf16.github.io/social-links-profile/]

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties (Variables)
- **Flexbox** - Used extensively for centering the card and stacking link elements.
- Mobile-first workflow.

### What I learned

This project was a great exercise in refining layout structure. One of the key takeaways was learning how to properly manage the width and spacing of interactive elements. 

Initially, I struggled with the `gap` property and background colors on the link container, but I learned that for a professional "button" look, the background and padding should be applied directly to the anchor tags.

I also focused on making the hover states feel more "premium" rather than just a simple color swap:

```css```
/* Refined hover state for a professional feel */
.links {
    transition: 
        background-color 0.3s ease, 
        color 0.3s ease, 
        transform 0.2s cubic-bezier(0.4, 0, 0.2, 1);
}

.links:hover {
    background-color: var(--green);
    color: var(--grey-900);
    transform: translateY(-2px);
}

# AI Collaboration
I used Gemini AI as a "Senior Pair Programmer" during this project to:

Refine the UI: I initially had a functional but basic hover effect; the AI helped me polish the transitions using cubic-bezier and transform for a smoother feel.


Code Optimization: Improved the responsiveness of the buttons by ensuring they use a flexible width: 100% strategy within a constrained container.

# Author
Frontend Mentor - @Zakialkhalaf16

GitHub - Zakialkhalaf16