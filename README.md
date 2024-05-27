# counter-app

Built using create app with Vue. Followed along with Quick Start: https://vuejs.org/guide/quick-start

## Project Setup

```sh
npm install
```

### Compile and Hot-Reload for Development

```sh
npm run dev
```

___

## Quick Introduction

This is a quick project to build up confident using vue 2 and vue 3. 

Starting with basic's, build a counter in vue. 

**Aim is to achieve the following:**

* Confidence in reading the Vue Documentation 
* Confidence in the terminology and structure of Vue/ CSS/ TypeScript
* Less reliance on Chat GPT, go back to overstack articles, understanding concept etc
* Build the application first and then watch a video tutorial if needed

Following along in Udemy: 

Learn to built frontend Vue 3 applications using Pinia, TypeScript, Supabase and the Composition API

Instructor: Laith Harb || Software Engineer

## Additional Notes:

### Type Support for `.vue` Imports in TS

TypeScript cannot handle type information for `.vue` imports by default, so we replace the `tsc` CLI with `vue-tsc` for type checking. In editors, we need [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) to make the TypeScript language service aware of `.vue` types.

### Type-Check, Compile and Minify for Production

```sh
npm run build
```

### Lint with [ESLint](https://eslint.org/)

```sh
npm run lint
```
