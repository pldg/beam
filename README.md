# Beam

A responsive CSS grid framework based on [inline-block](https://www.w3schools.com/css/css_inline-block.asp).

## Features

- 12 columns
- Utility classes
- Customizable
- Compatible with IE8+

## Install

Link [*beam.min.css*](https://cdn.jsdelivr.net/gh/pldg/beam/beam.min.css) or [*beam-lite.min.css*](https://cdn.jsdelivr.net/gh/pldg/beam/beam-lite.min.css) in the `<head>` tag before your main stylesheet.

```html
<link rel="stylesheet" type="text/css" href="beam.css">
```

In [*beam-lite.css*](beam-lite.css) (only 5kb minified) utility classes are present but they can't be applied to specific breakpoint, with the exception of `.delete` (read online [documentation](https://pldg.github.io/beam/#utility-classes) for more info). Besides that, *beam-lite.css* is identical to *beam.css*. You can easily customize both *beam-lite.css* and *beam.css* (read the comments inside those files) by adding and removing the code blocks you need.

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

Full [documentation](https://pldg.github.io/beam/) online.

## Customization

Read comments inside [*beam.css*](./beam.css) or [*beam-lite.css*](./beam-lite.css), add and remove code blocks as needed.

## Notes

Inspired by [Bootstrap](https://github.com/twbs/bootstrap) and [Toast](https://github.com/daneden/Toast).
