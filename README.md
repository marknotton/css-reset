
# CSS Reset

This opinionated css reset is forked from [Elad Shechters](https://elad2412.github.io/the-new-css-reset/)  original version. This iteration includes a number of resets I felt were missing.

## How to get started:

```
npm install @marknotton/css-reset
```
```
yarn add @marknotton/css-reset
```

Or [download the latest version](https://raw.githubusercontent.com/marknotton/css-reset/main/css/reset.css).

## How to use:

### The Sass way:

Import directly in your scss file:
```sass
@use "@marknotton/css-reset";
```
Or
```sass
@use "node_module/@marknotton/css-reset/css/reset.css";
```

### The Javascript way:

Include the following snippet in one of the JavaScript/TypeScript entry files:
```js
import "@marknotton/css-reset";
```
Or
```js
import "node_module/@marknotton/css-reset/css/reset.css";
```
