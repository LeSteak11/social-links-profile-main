# Social Links Profile

My solution to the [Social links profile challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ).

## Overview

### The challenge

Build a profile card that matches the mobile and desktop designs, with hover and focus states on every link.

### Screenshot

![Social links profile screenshot](./screenshot.png)

### Links

- Repository: [github.com/lesteak11/social-links-profile-main](https://github.com/lesteak11/social-links-profile-main)
- Live site: [lesteak11.github.io/social-links-profile-main](https://lesteak11.github.io/social-links-profile-main/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- BEM class naming
- Self-hosted Inter font with `@font-face`

### What I learned

- Relative paths matter: `./assets/...` and `.assets/...` are completely different, and a missing slash broke my image.
- `:focus-visible` should sit next to `:hover` so keyboard users get the same feedback as mouse users.
- I chose my breakpoint from the layout, not a default number. The card stops shrinking at 27rem, so that's where the roomier padding starts.

```css
@media (min-width: 27rem) {
    .card {
        padding: 2.5rem;
    }
}
```

### Continued development

- Transitions on hover states
- More practice matching designs without a Figma file

## Author

- GitHub: [@lesteak11](https://github.com/lesteak11)