# Huddle-landing-page-with-alternating-feature-blocks
This is a solution to the [Huddle landing page with alternating feature blocks challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/huddle-landing-page-with-alternating-feature-blocks-5ca5f5981e82137ec91a5100). Frontend Mentor challenges help you improve your coding skills by building realistic projects.


## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

Phewww.....These past few days have been tough and hectic on me but I still found a way to get this done and I'm super proud of myself for getting it done.

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

### Links

- Solution URL: (https://www.frontendmentor.io/solutions/huddle-landing-page-with-alternating-feature-blocks-solution-5dFPCH63Ju)
- Live Site URL: (https://macnelson9.github.io/Huddle-landing-page-with-alternating-feature-blocks/)

## My process

I started out this project using the mobile-first approach which was more than interesting. I was marbelled at how easy building became since I started writing for mobile-first. Now, I write less CSS media queries because of this approach.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- [Fontawesome](https://fontawesome.com/) - Icon Library

### What I learned

In this project, I learnt how to create the effect of an object lifting off the screen as if it is being picked up.

To see how you can add code snippets to your projects, see below:

```html
      <div class="overlay">
        <h2>Ready To Build Your Community?</h2>
        <button type="button" class="btn btn__colored">
          Get Started For Free
        </button>
      </div>
    </div>
```

```css
.overlay {
  align-items: center;
  background-color: #fff;
  border-radius: 20px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1) 6px 20px rgba(0, 0, 0, 0.1);
  color: var(--Very-Dark-Cyan);
  display: flex;
  flex-direction: column;
  gap: 30px;
  justify-content: center;
  padding: 40px 0;
  position: relative;
  top: 70px;
  transition: transform 0.3s, box-shadow 0.3s;
  z-index: 1;
}

.overlay:hover {
  transform: translateY(-10px);
  box-shadow: 0 10px 15px rgba(0, 0, 0, 0.2), 0 20px 40px rgba(0, 0, 0, 0.2);
}
```

## Author

- Frontend Mentor - [@macnelson9](https://www.frontendmentor.io/profile/macnelson9)
- Twitter/X - [@macnelson92](https://www.x.com/macnelson92)

## Acknowledgments

I would like to acknowledge the ChatGPT team for creating something so useful. It has helped me alot especially in breaking down complex theories and concepts.
