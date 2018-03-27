# Project-Trillo

Your all-in-one booking app

## Features

- B.E.M

- Advanced CSS and SASS

- Animations without Javascript

- Flexbox-based Layout

- NPM Scripts

- [ICONMOON](https://icomoon.io/app) SVGs (If you don't want to use Gulp to generate SVG Sprites
  like from [Modern-Workflow](https://github.com/barryblando/modern-workflow))

## SASS/SCSS Lint Installation

- Install sass lint extension on VSCode. Install NPM Package sass-lint. Create .sass-lint.yml and add rules. Done.

## Principles of Responsive Design and Layout Types

- Float Layout
- FlexBox Layout [Used in this Project]
- CSS Grid Layout
- Layout Centering Techniques [Guide](https://dev.to/alanfall/css-layout-centering-techniques--608)

## Inserting SVGs

```html
  <!-- xlink:href attribute is only going to work on a webserver -->
  <!-- advantages of SVG is that it makes it really easy to format icons, icon fonts is really hard -->

  <svg class="search__icon">
    <use xlink:href="img/sprite.svg#icon-magnifying-glass"></use>
  </svg>
```