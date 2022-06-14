# Frontend Mentor - FAQ accordion card solution

This is a solution to the [FAQ accordion card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/faq-accordion-card-XlyjD0Oam). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the component depending on their device's screen size
- See hover states for all interactive elements on the page
- Hide/Show the answer to a question when the question is clicked

### Screenshot

![](/solution/screenshot-desktop.jpg)
![](/solution/screenshot-mobile.jpg)


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

```html
<details class="accordion">
        <summary class="question">
          What is the maximum file upload size?
        </summary>
        <div class="answer">
          No more than 2GB. All files in your account must fit your allotted storage space.
        </div>
</details>
```
```css
#images::after{
    content: url(/assets/img/illustration-woman-online-mobile.svg);
    position: absolute;
    width: 73%;
    max-width: 19rem;
    top: -1rem;
    left: 50%;
    transform: translate(-50%, -50%);
}
```

### Useful resources

- [Developer Mozilla - HTML Elements | <details>](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/details) - This helped me to make an accordion with a semantic meaning and found the right tag elements for me not to neccesarly  use javascript to make it work. I really liked this pattern and will use it going forward.

## Author

- Frontend Mentor - [@dannxvc](https://www.frontendmentor.io/profile/yourusername)
- Instagram - [@dannxvc](https://www.twitter.com/yourusername)


