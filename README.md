# Frontend Mentor - Loopstudios Landing Page Solution

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)


## Overview

### The challenge

For this project, I was tasked with the challenge of:

- Viewing the optimal layout for the site depending on the user's device's screen size
- Seeing hover states for all interactive elements on the page

### Screenshot

![Mobile](./screenshot-mobile.jpg)
![Desktop](./screenshot-desktop.jpg)

### Links

- Solution URL: [Solution](https://your-solution-url.com)
- Live Site URL: [Live Site](https://your-live-site-url.com)

## My process

### Built with

- HTML5
- CSS3
- Bootstrap
- Bootstrap Grid
- Mobile-first Workflow

### What I learned

This project was my first time creating a mobile-first website and it was an exciting challenge to undertake. I was really able to get a stronger grasp on my responsive development, especially when it comes to grid elements. Bootstrap was helpful in this area, and how easy it is to apply classes and styling.

The most fun part of the website to develop were the panels in the 'Our Creations' section. Positioning the images in the panels and aligning the text inside was a unique task.

The most challenging part of the project was creating the grid display section. It was a fun and easy task until I had to make it go from a single line of columns to being an 8 section grid XD. Another challenge was having the See All button go from being at the bottom center of the panels to the top right. However, I was able to achieve both of these challenges through the use of the Bootstrap classes ```.col-lg-3``` for the panels and ```.order-lg-2``` for the button.

Below are some examples of code that I'm proud of in this project:

```html
<div class="row order-lg-3">
    <div class="col-lg-3">
      <a href="">
        <div class="list-img1 panel" alt="the earth from outerspace">
          <p>DEEP EARTH</p>
        </div>
      </a>
    </div>
```
```css
.panel {
  justify-content: center;
  background-repeat: no-repeat;
  background-size: cover;
  width: 100%;
  height: 200px;
  margin-bottom: 50px;
  position: relative;
  flex: 0.5;
  box-shadow: inset 0 0 200px black;
}
```

### Continued development

Although I feel confident in my skills as a developer, there is always more to learn. For areas of improvement, I want to focus on getting better at CSS animations. I feel that these can really level up a website. And while I am slowly implementing these into my websites, I need to study them more to become more proficient.

Along with this, there is also the steady long-term goal of writing cleaner, simpler code, and finding faster and more efficient ways of developing.

## Author

- Website - [Elyse Chambers](https:/diaryofelyse.com)
- Frontend Mentor - [Elyseeloo](https://www.frontendmentor.io/profile/Elyseeloo)
- Twitter - [@Elyseeloo_](https://www.twitter.com/elyseeloo_)
