# Frontend Mentor - Four card feature section solution

This is a solution to the [Four card feature section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![](./screenshot.jpg)
file-path for screenshot of my solution to the mobile view: my solution screenshot/fout-card feautre challenge desktop-view.PNG
file-path for screenshot of my solution to the Desktop view: my solution screenshot/fout-card feautre challenge mobile-view.PNG

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

the problem which occured to me when I do this challenge was to make the four-card layout in the desktop-view but later I solve it by wrapping second and third article element within div class of container-2 and give a display flex property to container.

```
HTML
<section class="skills">
    <article class="skill supervisor">
      <h1 class="work-title">Supervisor</h1>

      <p class="work-text">Monitors activity to identify project roadblocks
      </p>

      <img src="./images/icon-supervisor.svg" alt="a magnifier" class="icon">
    </article>
    <!-- wrapping the second and third article within a div helped to make the four cards in the desktop-view then I->
    <div class="container-2">
    <article class="skill team-builder">
      <h1 class="work-title">Team Builder</h1>

      <p class="work-text">Scans our talent network to create the optimal team for your project
      </p>

      <img src="./images/icon-team-builder.svg" alt="small house infront of small card" class="icon">
    </article>

    <article class="skill karma">
      <h1 class="work-title">Karma</h1>

      <p class="work-text">Regularly evaluates our talent to ensure quality
      </p>

      <img src="./images/icon-karma.svg" alt="a magnifier" class="iight bulb">
    </article>
    </div>

    <article class="skill calculator">
      <h1 class="work-title">Calculator</h1>

      <p class="work-text">Uses data from past projects to provide better delivery estimates
      </p>

      <img src="./images/icon-calculator.svg" alt="a desktop" class="icon">
    </article>
</section>
```

```
css
.container-2 {
  display: flex;
  flex-direction: column;
  gap: 23px;
}

@media screen and (min-width: 400px) {
  .container-2 {
    width: 351px;
    align-items: center;
  }

}
```

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

### Continued development

I want to perfect my skills of css flexbox,css grid and responsive design.

## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@aemrobe](https://www.frontendmentor.io/profile/aemrobe)
- Twitter - [@Aemro112](https://www.twitter.com/Aemro112)

## Acknowledgments

I want to thanks to my team members who always give me feedback to my solution.
