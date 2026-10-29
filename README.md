# Nothing Landing Page

A responsive landing page for **Nothing**. The page presents the brand's recommended products, browsable product categories, an "About us" section and a contact form. The goal of the project was to build a pixel-accurate, responsive layout from a design, using semantic HTML, BEM and SCSS.

## Live Preview

[View the live demo](https://dm1trik.github.io/Landing-Page/)

## Design Reference

[Figma design](https://www.figma.com/design/DtkQmQ797hk0nI4KfMi2Uq/BOSE-New-Version?m=auto&t=uiabi8AgPjZXPtFV-1)

## Technologies Used

- HTML5 (semantic markup)
- SCSS with the BEM methodology (variables, mixins, partials)
- CSS Grid and Flexbox
- CSS scroll-driven animations (`animation-timeline: view()`)
- Google Fonts (Space Grotesk, Space Mono)
- Responsive design (mobile first, breakpoints at 576px and 1024px)

## Getting Started

1. Clone the repository:

```
git clone https://github.com/your-username/project-name.git
cd project-name
```

2. Install dependencies:

```
npm install
# or
yarn install
```

3. Run the project locally:

```
npm start
# or
yarn start
```

## Features

- **Fully responsive layout** for mobile, tablet and desktop, built on a custom 2 / 6 / 12-column grid mixin.
- **Fullscreen navigation menu** implemented with the CSS `:target` pseudo-class, with no JavaScript needed to open or close it.
- **Scroll-triggered animations**: sections fade in as they enter the viewport, and the banner slides in from the side.
- **Sticky footer reveal**: the footer image stays fixed while the page content scrolls over it.
- **Hover and active effects** on product images, category tiles, icons, navigation links and buttons.
- **Contact form** with native HTML validation (required fields, email format).
- **Clean, reusable SCSS architecture**: shared variables and mixins, one partial per BEM block.
