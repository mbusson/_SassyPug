# SassyPug

SassyPug is a Javascript application boilerplate derived from [Baptiste Briel](https://github.com/baptistebriel/)'s [biggie](https://github.com/baptistebriel/biggie), which is itself based on [bigwheel](https://github.com/bigwheel-framework), a minimalist framework from [Jam3](http://www.jam3.com/). SassyPug is basically biggie with a few variations in features as you can read in the next section. That plus a cool name based on the latter. Clever, innit? (...)

## Features

- [x] Pug preprocessing
- [x] Sass preprocessing
- [x] jQuery and GSAP native implementation
- [x] Browserify, babelify and uglify Javascript files (automatically uses `build/app.js` for dev, `build/app.min.js` for prod)
- [ ] Automatic Linting of Javascript files
- [x] Optimize all assets (CSS, JS, fonts, and images) for production
- [x] Livereload (refreshes the browser automatically whenever you save a file)
- [x] Offer a stable and simple structure to manage and animate your contents
- [x] Fancy utilities from biggie described in Part.3 of the Tutorial

## Quickstart

`git clone https://github.com/mbusson/SassyPug.git folder-name`

`cd folder-name && npm i && gulp`

Your site will be at `http://localhost:3000` by default using [browser-sync](http://www.browsersync.io)

## Tutorial

This tutorial will guide you through the use of SassyPug. It is quite bulky but lays out the basics in order to get a good grasp on what's actually going on.

Part 2 is broadly based on [bigwheel's documentation](https://github.com/bigwheel-framework/documentation) as SassyPug is built upon the framework. The third part is about the use of [biggie](https://github.com/baptistebriel/biggie). Fourth part dispenses handy information to make the best out of SassyPug. Most of these are really helpful if you're not used to frameworks and boilerplates.

##### Part 1:
- [Getting started](quickstart.md) [SOON]
  - [Initiating SassyPug (first use)](quickstart.md) [SOON]
  - [Understanding the framework's structure](quickstart.md) [SOON]

##### Part 2:
- [Managing content with Bigwheel](quickstart.md) [SOON]
  - [Introduction](quickstart.md) [SOON]
  - [Understanding and defining Routes](quickstart.md) [SOON]
  - [Understanding and managing sections](quickstart.md) [SOON]
  - [Good to Know](quickstart.md) [SOON]
      - [Miscellaneous](quickstart.md) [SOON]
      - [Things to look out for](quickstart.md) [SOON]

##### Part 3:
- [Handy template and utilities with Biggie](quickstart.md) [SOON]
  - [CSS GetRect calls](quickstart.md) [SOON]
  - [Javascript utilities](quickstart.md) [SOON]
      - [arrayFrom(opt)](quickstart.md) [SOON]
      - [clamp(min, value, max)](quickstart.md) [SOON]
      - [scrollTop](quickstart.md) [SOON]
  - [Biggie-specific utilities](quickstart.md) [SOON]
      - [getSlug(req)](quickstart.md) [SOON]
      - [createPage(req, slug)](quickstart.md) [SOON]
      - [loadPage(req, view, done)](quickstart.md) [SOON]

##### Part 4:
- [Good to know...](quickstart.md) [SOON]

## Todo

- [ ] Automatic Linting of Javascript files
- [ ] Writing documentation

### Examples

- [ ] None for now

### License

MIT, see [LICENSE.md]().
