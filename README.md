# Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS).

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![](/screenshot.png)

### Links

- [Live Site](https://blog-preview-card-tan-five.vercel.app/)
- [Figma](https://www.figma.com/design/9Bl8QekwXmI7VuQezDYTys/blog-preview-card?m=auto&t=URYRProBEIH3vKO5-6)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties

### What I learned

Use CSS function `clamp()`.

```css
.card-date {
  ...
  font-size: clamp(0.75rem, 3vw, 0.875rem);
  ...
}
```

## Author

- Frontend Mentor - [@m4rcone](https://www.frontendmentor.io/profile/m4rcone)
