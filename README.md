# Frontend Mentor - Clipboard landing page solution

This is a solution to the [Clipboard landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/clipboard-landing-page-5cc9bccd6c4c91111378ecb9). Frontend Mentor challenges help improve coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [AI Collaboration](#ai-collaboration)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

## My process

### Built with

- Semantic HTML5 markup
- Flexbox
- CSS media queries for a mobile-first responsive layout
- CSS `:hover` pseudo-class for interactive states
- Git and GitHub for version control

### What I learned

This project stepped up the responsive design work from my previous project into a full multi-section landing page, and introduced me to version control with Git and GitHub for the first time.

The biggest new concepts for me were:

- **Flexbox for multi-section layouts** — reusing the same `display: flex` approach across several different sections (buttons, feature lists, the icon row, the footer), rather than just one card:

```css
.snippets-layout {
  display: flex;
  flex-direction: row;
  align-items: center;
  gap: 64px;
}
```

- **The direct child combinator (`>`)** — learning the difference between selecting every matching element inside a container versus only its direct children:

```css
.workflow > p {
  color: hsl(201, 11%, 66%);
}
```

- **Git and GitHub** — initializing a repository, making commits at each stage of the build, and pushing to GitHub instead of submitting a zipped folder:

```bash
git add .
git commit -m "Add hero section HTML"
git push
```

### Continued development

- Get more practice with Git — branching, and working with commits beyond a single linear history
- Explore CSS Grid as an alternative to Flexbox for more complex multi-column layouts
- Start introducing JavaScript into projects, since everything so far has been HTML/CSS only

### AI Collaboration

I used Claude at some points of this project as a step-by-step mentor. I planned the page section by section from the design files and style guide before writing any code, built the HTML structure first, then worked through the CSS one section at a time — base styles, then each content section, then the responsive media query and hover states last. Claude then walked me through Git and GitHub for the first time, since this was new to me this week.

What worked well: breaking a large page into small, checkable pieces made a multi-section layout feel manageable instead of overwhelming, and having Git explained step-by-step (rather than just given as commands to copy) meant I understood what each command was actually doing, not just that it worked.

## Author

- GitHub - [@COSPRO-DEV](https://github.com/COSPRO-DEV)
- LinkedIn - [Tochukwu Nwodo](https://www.linkedin.com/in/tochukwu-nwodo-6a453a28b/)