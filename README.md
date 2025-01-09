# Testimonials Grid Section

![Design preview for the Testimonials grid section coding challenge](./design/desktop-preview.jpg)

## Overview

This is a solution to the [Testimonials Grid Section](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7) challenge on Frontend Mentor. This challenge focuses on building a responsive testimonials grid layout using HTML and CSS.

## Table of Contents

- [Overview](#overview)
- [Built With](#built-with)
- [What I Learned](#what-i-learned)
- [Continued Development](#continued-development)
- [Live Demo](#live-demo)
- [Useful Resources](#useful-resources)
- [Author](#author)

## Built With

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

## What I Learned

This project helped me improve my understanding of:

- CSS Grid for creating responsive layouts.
- Using `@media` queries to adjust layouts for different screen sizes.
- Organizing CSS for reusability and readability.

### Code Example

```html
<div class="testimonial">
  <img src="./images/user-photo.jpg" alt="User photo" class="user-photo">
  <p class="quote">"This is a sample testimonial. The layout adapts beautifully to different screen sizes."</p>
  <h4 class="user-name">John Doe</h4>
  <p class="user-role">Software Engineer</p>
</div>
```

```css
.testimonial {
  display: grid;
  grid-template-rows: auto 1fr auto;
  padding: 1rem;
  background-color: var(--light-gray);
  border-radius: 0.5rem;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
}

@media (min-width: 768px) {
  .testimonial {
    grid-template-columns: auto 1fr;
  }
}
```

## Continued Development

I plan to explore:

- Advanced CSS Grid techniques.
- Accessibility improvements, like ARIA attributes.
- Incorporating JavaScript for additional interactivity.

## Live Demo

Check out the live demo of the project [here](https://amallal2004.github.io/Frontend-Mentor---Testimonials-grid-section/).

## Useful Resources

- [CSS Grid Guide](https://css-tricks.com/snippets/css/complete-guide-grid/) - Helped with understanding CSS Grid.
- [Responsive Design Principles](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Responsive_Design) - Great resource for mobile-first design.

## Author

- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
- GitHub - [@yourusername](https://github.com/yourusername)
