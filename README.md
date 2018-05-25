<p align="center">
  <a href="https://baianat.github.io/verte/" target="_blank">
    <img width="400" alt="verte" src="https://baianat.github.io/verte/verte.png">
  </a>
</p>

[![Build Status](https://img.shields.io/travis/baianat/verte.svg?style=flat-square)](https://travis-ci.org/baianat/verte)
[![Codecov](https://img.shields.io/codecov/c/github/baianat/verte.svg?style=flat-square)](https://codecov.io/github/baianat/verte)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/32d598bdf1094532baf51ac7d89aebfd)](https://www.codacy.com/app/logaretm/verte?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=baianat/verte&amp;utm_campaign=Badge_Grade)

# Verte (WIP) 🐛

Color-picker designed for Vue

## Getting Started

### Installation

First step is to install it using `yarn` or `npm`:

```bash
npm install verte --save

# or use yarn
yarn add verte
```

### Basic usage

```html {2,8,13}
<template>
  <verte :picker="wheel" :model="rgb"></verte>
</template>

<script>
  import Verte from './dist/verte.js';
  // register component globally
  Vue.component(Verte.name, Verte);

  new Vue ({
    el: '#app',
    // OR register locally
    components: { Verte }
  });
</script>

```

## License

MIT