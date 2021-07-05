# Fylo_Page
Frontend Mentor Project

# Frontend Mentor - Fylo dark theme landing page solution

This is a solution to the [Fylo dark theme landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/fylo-dark-theme-landing-page-5ca5f2d21e82137ec91a50fd). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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
- See hover states for all interactive elements on the page

### Full Screenshot

![](https://github.com/Karllouise-code/fylo-dark-theme-page/blob/master/images/fyloscreenshot.png)

### Built with

- HTML5
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

I learned a lot about making your website responsive. It is my first making a website that is compatible with phone. This challenge improves my skills.

```html
<h1>Some HTML code I'm proud of</h1>
<script
  src="https://kit.fontawesome.com/de376feec1.js"
  crossorigin="anonymous"
></script>
```

```css
.proud-of-this-css {
  :root {
    /** Primary */
    --intro-email-background: hsl(217, 28%, 15%);
    --main-background: hsl(218, 28%, 13%);
    --footer-background: hsl(216, 53%, 9%);
    --testimonials-background: hsl(219, 30%, 18%);
    /** Accent */
    --cta-light: hsl(176, 68%, 64%);
    --cta-dark: hsl(198, 60%, 50%);
    /** Neutral */
    --font-color: hsl(0, 0%, 100%);
  }
}
```

```js
const proudOfThisFunc = function checkInputs() {
  //get values from the inputs
  const emailValue = email.value.trim();

  if (emailValue === "") {
    //show error
    // add error class
    setErrorFor(email, "Please enter a valid email address");
  } else if (!isEmail(emailValue)) {
    setErrorFor(email, "Please enter a valid email address");
  } else {
    //add success class
    setSuccessFor(email);
  }
};
```

### Continued development

For my future projects I want to try some projects wherein I got to test my javascript skills and then learn more about animations and try some css frameworks.

## Author

- Github - [Lester Niel Fong](https://github.com/Lester-Fong)
- Facebook - [Lester Niel Fong](https://www.facebook.com/LesterNielFong22)
- linkedIn - [Lester-Fong](https://www.linkedin.com/in/lesterfong22/)

## Acknowledgments

I would like to thank anyone who have helped me complete this project.
