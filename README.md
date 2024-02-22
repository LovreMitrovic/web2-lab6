# Calories tracker as lab

Deployed at https://web2-lab6-q23z.onrender.com/

## Project Setup

```sh
npm install
```

### Compile and Hot-Reload for Development

```sh
npm run dev
```

### Compile and Minify for Production

```sh
npm run build
```

### Lint with [ESLint](https://eslint.org/)

```sh
npm run lint
```

## Task description

zahtjevi:
 - interpolation/one-way binding - Yes, src/components/ActivityComponent.vue, :4, variable "name" is interpolated
 - two-way binding - Yes, src/components/ListComponent.vue, :11, :33, :51, the variable newActivity is two-way bound.
 - methods - Yes, src/components/ListComponent.vue, :26-:40
 - computed properties - Yes, src/components/ListComponent.vue, :19-:25
 - at least one scoped style - Yes, src/components/ListComponent.vue, :73
 - use at least one lifecycle hook - Yes, src/components/SportComponent.vue, :15-:17
 - routing (multiple pages) - Yes, src/router/index.js, entire file
   - the application must be bookmarkable, so that links work (not just on the root, but also my-web.com/page1, my-web.com/page2)
   - dynamic routing with a 404 page ("catch all")
 - (at least) two components - Yes, src/components/*
   - stateless component, use properties - Yes, src/components/ActivityComponent.vue
   - stateful component - Yes, src/components/ListComponent.vue
 - at least one component must emit at least one event - Yes, src/components/ActivityComponent.vue, :18
 - store (Pinia) - Yes, src/stores/sports.js entire file, used in /src/views/SportView.vue :30, /src/views/HomeView.vue :10, /src/components/SportComponent.vue :13
 - asynchronous data retrieval from the backend, you can: - Yes, asynchronously load a component, src/router/index.js :26
    - use Firebase or Back4App, Mocky, etc.
    - own storage, or
    - you can mock it, keep data in memory, but it must be an asynchronous call/write
    - achieve asynchronous (lazy, on demand) loading of some part of the application (pages or components)
