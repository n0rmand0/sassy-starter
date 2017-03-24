# Sassy Starter

A Sass boilerplate organized with [SMACSS](https://smacss.com/) and topped with useful scaffold styles and variables.

## Structure

- **utility:** Sass utility helper folder
  - **variables:** Global variables, default colors, default spacing values
  - **grid-settings:** Breakpoints, max width, and neat setup
  - **mixins:** global mixins
  - **extends:** global extends

- **base:** All basic element of the site
  - **reset:** CSS browser reset
  - **fonts:** Font imports
  - **animations:** Global animation keyframes
  - **buttons:** Global link and button styles
  - **forms:** Base form styles
  - **lists:** Base list styles
  - **media:** Base media styles. video, img, etc
  - **tables:** Base table styles
  - **typography:** Body type, H tags, p etc

- **layout** All styles used to lay elements out on the page
  - **grid:** Canned layout modules (modules prefixed with 'l')
  - **sections:** Site section styles
  - **header:** Site header styles
  - **footer:** Site footer styles

- **modules**
  - **global:**  Modules that can be used anywhere.  Break bigger modules into their own file.

- **pages:** Page specific styles
  - **home:** Home page styles

- **themes*** All theme override styles
  - **ie:** Internet Explorer fixes
  - **print:** Print styles


## Get Started

This boilerplate requires mixins and extends from **Bourbon**, and **Neat**.

Install Neat and Bourbon into the stylesheet directory and start Sassing.
- **Bourbon 5** - [bourbon.io](http://bourbon.io/)
- **Neat 2** - [neat.bourbon.io](http://neat.bourbon.io/)
