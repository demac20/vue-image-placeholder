# Vue Image Placeholder

## Installation

```sh
npm install vue-image-placeholder
```

## Use it in your app

```ts
import ImagePlaceholder from 'vue-image-placeholder';
```

Render an image with `cats` from [LoremFlickr](https://loremflickr.com/) service

```html
<ImagePlaceholder width=500 height=250 images="cats" />
```

<img src="https://loremflickr.com/500/250/cats"/>


## Properties

`width` final image width (required)

`height` final image height (default is equal to width)

`images` category/categories for the image
  - `single value` returns an image of one category (e.g. 'cats').
  - `comma separated value` returns an image belonging to both categories (e.g. 'animals,cat').
  - `pipe separated value` returns an image belonging to one of the categories (e.g. 'animal|cats').

## Project setup for development
```
npm install
```

### Compiles and minifies for production
```
npm run build
```

### Run your unit tests
```
npm run test:unit
```

### Lints and fixes files
```
npm run lint
```
