# vue-typescript

Adding typescript to vue webpack template.

## Pre Requisites
1. Install Visual Studio Code
1. Install Vetur extension https://github.com/vuejs/vetur
1. Install webpack template: `vue init webpack vue-typescript`

## Config Changes
1. `npm install --save-dev ts-loader typescript`
1. create `tsconfig.json`
1. create `src/typings.d.ts`
1. add ts-loader to webpack base config
2. change the entry file from `main.js` to `main.ts`

## Write Code
1. Add `lang="ts"` to script tag
1. Change `export default {}` to `export default Vue.extend({})`
1. Add types and have fun!

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report
```

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).
