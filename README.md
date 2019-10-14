# Bootstrap Steps

[![npm version](https://img.shields.io/npm/v/bootstrap-steps.svg)](https://www.npmjs.com/package/bootstrap-steps)
[![Software License](https://img.shields.io/badge/license-MIT-brightgreen.svg)](LICENSE.md)

A simple Bootstrap steps plugin, support mobile client.

## Demo

See [Demo](https://ycs77.github.io/bootstrap-steps/).

## Getting started

Must include [Bootstrap 4](https://getbootstrap.com/).

### Installation

Install Bootstrap steps package:
```
$ npm install bootstrap-steps
```
or
```
$ yarn add bootstrap-steps
```

### Import

Import to your scss file and build:

```scss
@import '~bootstrap/scss/bootstrap';
@import '~bootstrap-steps/scss/bootstrap-steps';
```

Or use CDN:
```html
<link  href="https://cdnjs.cloudflare.com/ajax/libs/twitter-bootstrap/4.3.1/css/bootstrap.min.css" rel="stylesheet"><!-- Bootstrap is required -->
<link  href="/path/to/bootstrap-steps.css" rel="stylesheet">
```

### Usage

```html
<ul class="steps">
  <li class="step step-success">
    <div class="step-content">
      <span class="step-circle">1</span>
      <span class="step-text">Step 1</span>
    </div>
  </li>
  <li class="step step-active">
    <div class="step-content">
      <span class="step-circle">2</span>
      <span class="step-text">Step 2</span>
    </div>
  </li>
  <li class="step">
    <div class="step-content">
      <span class="step-circle">3</span>
      <span class="step-text">Step 3</span>
    </div>
  </li>
  <li class="step">
    <div class="step-content">
      <span class="step-circle">4</span>
      <span class="step-text">Step 4</span>
    </div>
  </li>
</ul>
```
