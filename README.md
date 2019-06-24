# Beam

![size-badge](https://img.shields.io/github/size/pldg/beam/beam-lite.min.css.svg)
![downloads-badge](https://img.shields.io/npm/dt/beam-css-grid.svg)

A responsive css grid framework based on [inline-block](https://www.w3schools.com/css/css_inline-block.asp), with 12 columns and utility classes, customizable and compatible with Internet Explorer 8 and newer versions.

## Install

### Locally

Download [*beam.min.css*](./beam.min.css) (or [*beam-lite.min.css*](./beam-lite.min.css)) and link it before your main css:

```html
<link rel="stylesheet" type="text/css" href="beam.css">
```

### CDN

Link [*beam.min.css*](https://cdn.jsdelivr.net/gh/pldg/beam/beam.min.css) (or [*beam-lite.min.css*](https://cdn.jsdelivr.net/gh/pldg/beam/beam-lite.min.css)) before your main css:

```html
<link rel="stylesheet" type="text/css" href="https://cdn.jsdelivr.net/gh/pldg/beam/beam.min.css">
```

### NPM

Install with:

```txt
npm install --save beam-css-grid
```

And [import css](https://github.com/pldg/learn-webpack/tree/master/load-css) in your project using a javascript bundler.

## Quick Start

```html
<div class="container">
  <div class="row">
    <div class="s6"></div>
    <div class="s6"></div>
  </div>
  <div class="row">
    <div class="s3"></div>
    <div class="s3"></div>
    <div class="s3"></div>
    <div class="s3"></div>
  </div>
</div>
```

## Documentation

Read [documentation](https://pldg.github.io/beam/) online (served from gh-pages branch).

## Customization

Read comments inside [*beam.css*](./beam.css), add/remove code blocks as needed.

## Notes

In [*beam-lite.css*](beam-lite.css) (only 4kb minified) utility classes are present but they can't be applied to specific breakpoint, with the exception of `.delete` (read online [documentation](https://pldg.github.io/beam/#utility-classes) for more info). Besides that, *beam-lite.css* is identical to *beam.css*. You can easily customize both *beam-lite.css* and *beam.css* (read the comments inside those files) by adding and removing the code blocks you need.

Inspired by [Bootstrap](https://github.com/twbs/bootstrap) and [Toast](https://github.com/daneden/Toast).
