# Project-Trillo [DEMO](https://barryblando.github.io/project-trillo/)

Your all-in-one booking app

## Features

- B.E.M

- Advanced CSS and SASS

- DESKTOP APPROACH

- Animations without Javascript

- Flexbox-based Layout.
  - [ [A Visual Guide to CSS3 Flexbox Properties](https://scotch.io/tutorials/a-visual-guide-to-css3-flexbox-properties) ]
  - [ [A Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) ]
  - [ [Solved by Flexbox](https://philipwalton.github.io/solved-by-flexbox/) ]
  - [ [Basic concepts of Flexbox](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout/Basic_Concepts_of_Flexbox) ]

- If you need some extra practice I highly recommend these games to orient yourself!
  - [Flexbox Zombies](https://mastery.games/p/flexbox-zombies)
  - [Flexbox Froggy (Mobile Friendly)](https://flexboxfroggy.com/)
  - [Flexbox Defense](http://www.flexboxdefense.com/)

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
