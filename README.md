# Frontend Mentor - Social links profile solution

This is a solution to the [Social links profile challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [AI Collaboration](#ai-collaboration)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

<p align="center">
  <img src="assets/images/screenshot.PNG" alt="Screenshot of the social links profile card on a dark background" width="600">
</p>

### Links

- GitHub repository: [social-linkes-profile](https://github.com/hossamelgendy101/social-linkes-profile)
- Live site: [social-linkes-profile.vercel.app](https://social-linkes-profile.vercel.app/)

## My process

### Built with

- Semantic HTML5 markup (`main`, `article`, `nav`, `ul`)
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

- **Profile card layout:** I built the card as a single Flexbox column and used `gap` for the spacing between sections instead of margins. I grouped the name and location in their own wrapper so the space between them could be smaller than the space between the other sections.
- **Link buttons:** I learned why the styling belongs on the `<a>` itself with `display: block`. That way the whole button is clickable, and its height comes from `padding` + `line-height` (12 + 21 + 12 = 45px) instead of a fixed `height`.
- **Responsive spacing:** I tested the page from 1440px down to 320px. At 320px the bio wraps to two lines, which is the expected behavior and not a bug. I also learned to use `max-width` with `width: 100%` instead of fixed widths, and `rem` for font sizes.
- **Hover and focus states:** I added `:hover` and `:focus-visible` styles so keyboard users get the same visible feedback as mouse users, and checked it by navigating with the Tab key.
- **Design tools:** I practiced reading values (sizes, colors, spacing, typography) from the Figma file and converting them into CSS.

### Continued development

- Add a `transition` to the link states and compare it with the design.
- Practice `@media` queries on a challenge where the layout actually changes between mobile and desktop.
- Add JavaScript interactions in the next projects.
- Optimize images (size and format) before publishing.

### AI Collaboration

During this project, I collaborated with an AI assistant (**Claude**) to enhance my workflow and problem-solving process.

- **Tools used:** Claude, as a technical consultant and brainstorming partner.
- **How I used it:** For brainstorming, code review, and explanations, such as how to structure the HTML, why certain CSS approaches work, and how to test responsiveness.
- **What worked well:** The explanations helped me understand *why* an approach works rather than just giving me code to copy.
- **What I did myself:** I wrote and implemented the code by hand and fixed the issues that came up in review.

## Author

- GitHub - [@hossamelgendy101](https://github.com/hossamelgendy101)
- Frontend Mentor - [@hossamnabil](https://www.frontendmentor.io/profile/hossamnabil)
- Twitter - [@hossamelgendy](https://www.twitter.com/hossamelgendy)

## Acknowledgments

- Thanks to **Frontend Mentor** for this challenge.
- Thanks to the developer community and AI assistant tools for guidance and brainstorming support.
