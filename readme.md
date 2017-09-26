[![forthebadge](http://forthebadge.com/images/badges/built-with-love.svg)](http://forthebadge.com)
[![forthebadge](http://forthebadge.com/images/badges/uses-css.svg)](http://forthebadge.com)
[![forthebadge](http://forthebadge.com/images/badges/gluten-free.svg)](http://forthebadge.com)

# Sassy Starter
A bare bones Sass boilerplate based on Scalable and Modular Architecture for CSS ([SMACSS](https://smacss.com/)) and topped with useful scaffold styles and variables.

## Setup
This boilerplate assumes you you already have a build process in place. This is compatible with any workflow that compiles scss — webpack, gulp, rails, etc.

**Plug & Play:**  Just plug this into your project. Use `all.scss` as the entry point for all the scss.

## Features
- [SMACSS](https://smacss.com/) style organization for SCSS
- [Normalize.css](https://necolas.github.io/normalize.css/) reset
- Base global variables
- Base styles for element selectors
- Media query mixin with customizable query variables
- Example grid layout rules


## Structure
```
stylesheets/
│
├── all.scss
│
├── utility/
│   ├── variables.scss
│   ├── grid-settings.scss
│   ├── mixins.scss
│   └── extends.scss
│
├── base/
│   ├── reset.scss
│   ├── fonts.scss
│   ├── animations.scss
│   ├── buttons.scss
│   ├── forms.scss
│   ├── layout.scss
│   ├── lists.scss
│   ├── media.scss
│   ├── tables.scss
│   └── typography.scss
│
├── layout/
│   ├── footer.scss
│   ├── grid.scss
│   ├── header.scss
│   └── sections.scss
│
├── modules/
│   └── global.scss
│  
└── themes/
    └── print.scss
```

## Media Queries
Define your media queries in `_grid-settings.scss`.  Media queries are stored as a sass map variable. This query setup also supports the neat grid framework: https://neat.bourbon.io/, but it is not required.

Example variable:
```
$large: (
  media: '(min-width: 900px)'
);
```

You may use the included `media($query)` mixin for any media query preset.

Example media query:

```
@include media($large){
  display: none;
}
```

## Layout Rules
https://smacss.com/book/type-layout

Major layout rules are prefixed with `l-`.  Several examples are included in `_sections.scss` and `_grid.scss`.

The grid framework in `_grid.scss` is left intentionally open so that you can build your own reusable layout rules as needed. `_grid.scss` includes several example rules--built in `css grid`.
