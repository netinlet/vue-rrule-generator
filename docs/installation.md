# Installation

## Direct Download / CDN

https://unpkg.com/vue-rrule-generator/dist/vue-rrule-generator 

[unpkg.com](https://unpkg.com) provides NPM-based CDN links. The above link will always point to the latest release on NPM. You can also use a specific version/tag via URLs like https://unpkg.com/vue-rrule-generator@{{ $version }}/dist/vue-rrule-generator.js
 
Include vue-rrule-generator after Vue and it will install itself automatically:

```html
<script src="https://unpkg.com/vue/dist/vue.js"></script>
<script src="https://unpkg.com/vue-rrule-generator/dist/vue-rrule-generator.js"></script>
```

## NPM

```sh
$ npm install vue-rrule-generator
```

## Yarn

```sh
$ yarn add vue-rrule-generator
```

When used with a module system, you must explicitly install the `vue-rrule-generator` via `Vue.use()`:

```javascript
import Vue from 'vue'
import vue-rrule-generator from 'vue-rrule-generator'

Vue.use(vue-rrule-generator)
```

You don't need to do this when using global script tags.

## Dev Build

You will have to clone directly from GitHub and build `vue-rrule-generator` yourself if
you want to use the latest dev build.

```sh
$ git clone https://github.com//vue-rrule-generator.git node_modules/vue-rrule-generator
$ cd node_modules/vue-rrule-generator
$ npm install
$ npm run build
```

