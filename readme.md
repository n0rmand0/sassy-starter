# Sassy Starter

A Sass boilerplate organized with [SMACSS](https://smacss.com/) and topped with useful scaffold styles and variables.

## Structure
- **all.scss:** The main entry file.  All partial imports go here.

- **utility:** Sass utility helpers
  - **variables:** Default colors, sizes, spacing, etc.
  - **grid-settings:** Breakpoints and neat setup
  - **mixins:** Global mixins
  - **extends:** Global extends

- **base:** All basic element of the site
  - **reset:** CSS browser reset
  - **fonts:** Font imports
  - **animations:** Global animation keyframes
  - **buttons:** Global link and button styles
  - **forms:** Form styles
  - **lists:** List styles
  - **media:** Media styles. video, img, picture, etc.
  - **tables:** Table styles
  - **typography:** Body typography, H tags, p, etc.

- **layout** All styles used to lay elements out on the page
  - **grid:** Canned layout modules (modules prefixed with 'l')
  - **sections:** Site section styles
  - **header:** Site header styles
  - **footer:** Site footer styles

- **modules** Modules that can be used anywhere. Break bigger modules into their own file.
  - **global:** Global modules

- **pages:** Page specific styles that don't fit into modules
  - **home:** Home page styles

- **themes*** All themes and override styles
  - **ie:** Internet Explorer fixes
  - **print:** Print styles


## Get Started

This boilerplate requires **Neat 2**.

Install Neat into your stylesheet root directory and start Sassing.
- **Neat 2** - [neat.bourbon.io](http://neat.bourbon.io/)
