# Front-end

## Table of Contents

* [HTML](#html)
  * Basics
  * Semantic
  * SEO
  * [Accessibility](#accessibility)
* [CSS](#css)
  * Basics
  * [CSS Layout](#css-layout)
  * Media Queries
  * [CSS Frameworks](#css-frameworks)
  * [CSS Architecture](#css-architecture)
  * [CSS Pre-processors](#css-pre-processors)
  * [CSS in JS](#css-in-js)
* [JavaScript](#javascript)
  * Basics
  * DOM Manipulation
  * AJAX / Fetch API
  * Modular JavaScript
  * Concepts
  * [libs](#libs)
* [Web Components](#web-components)
* Frameworks
  * React.js
    * Redux
    * MobX
  * Angular
    * RxJS
    * ngrx
  * Vue.js
* Package Managers
  * npm
  * yarn
* [Build Tools](#build-tools)
  * [Linters and Formatters](#linters-and-formatters)
  * [Task Runners](#task-runners)
  * [Module Bundlers](#module-bundlers)
* Testing
  * Jest
  * Enzyme
  * Cypress
  * Mocha
  * Chai
  * Ava
  * Karma
  * Jasmine
  * Protractor
* [Performance](#performance)
* [Progressive Web Apps](#progressive-web-apps-pwa)
  * [Web APIs](#web-apis)
  * [Calculing, Measuring and improving performance](#calculing-measuring-and-improving-performance)
* Type Checkers
  * TypeScript
  * Flow
* [Server Side Rendering](#server-side-rendering)
* [Static Site Generators](#static-site-generators)
* Desktop Applications
  * Electron
  * Proton Native
  * Carlo
* Mobile Applications
  * React Native
  * NativeScript
* Web Assembly
* Tecniques
  * Micro frontends
* Misc
  * State Management

## HTML

### Accessibility

* WCAG 2.0
* WAI-ARIA

## CSS

### CSS Layout

* Floats
* Positioning
* Display
* Box Model
* CSS Grid
* Flexbox

### CSS Architecture

* [BEM](http://getbem.com/introduction/)
* [OOCSS](https://github.com/stubbornella/oocss/wiki)
* [SMACSS](http://smacss.com/)
* [SUIT CSS](http://suitcss.github.io/)
* [ITCSS](https://itcss.io)
* [ECSS](https://ecss.io/)
* [ACSS](https://acss.io/)

### CSS Pre-processors

* SASS
* PostCSS

### CSS Frameworks

* [Bootstrap](https://getbootstrap.com/)
* Materialize CSS
* Bulma
* Semantic UI

### CSS in JS

* Styled Components
* CSS Modules
* Emotion
* Radium
* Glamorous

## JavaScript

### libs

* [jQuery](https://jquery.com/)
* [Moment](https://momentjs.com/)
* [date-fns](https://date-fns.org/)
* [Lodash](https://lodash.com/)
* [Ramda](https://ramdajs.com/)

## Build Tools

### Linters and Formatters

Opinionated and automated code formatting

* [Prettier](https://prettier.io/)
* Standard
* [ESLint](https://eslint.org/)
* JSHint
* JSLint
* JSCS

### Task Runners

* npm scripts
* gulp

### Module Bundlers

* [webpack](https://webpack.js.org/)
* [Parcel](https://parceljs.org/)
* [Rollup](https://github.com/rollup/rollup)

## Web Components

* [Web Components](https://www.webcomponents.org/)

## Performance

* Angular, React, Vue specific optimizations
* Code Splitting
* Tree Shaking
* Delivering only necessary Javascript code
* Being more mindful of what NPM libraries you are using and minimizing library boat
* Having a performance budget
* Prioritizing assets better through use of CDNs and browser priority tools
  * [CloudFlare](https://www.cloudflare.com/)

## Progressive Web Apps (PWA)

HTTPS, App Shell and Service Workers for some extra offline features, security, and performance.

- [PWA](https://developers.google.com/web/progressive-web-apps/)
- [Launcher icon generator](https://romannurik.github.io/AndroidAssetStudio/icons-launcher.html#foreground.type=clipart&foreground.clipart=android&foreground.space.trim=1&foreground.space.pad=0.25&foreColor=rgba(96%2C%20125%2C%20139%2C%200)&backColor=rgb(68%2C%20138%2C%20255)&crop=0&backgroundShape=square&effects=none&name=ic_launcher)
- [The Web App Manifest](https://developers.google.com/web/fundamentals/web-app-manifest/)
- [pwacompat](https://github.com/GoogleChromeLabs/pwacompat)
* [Lighthouse](https://developers.google.com/web/tools/lighthouse/)
* [Service Workers](https://developers.google.com/web/fundamentals/primers/service-workers/)

### Web APIs

* Storage
  * DOM Storage
  * IndexedDB
    * [idb](https://github.com/jakearchibald/idb)
* Web Sockets
* Service Workers
* Location
* Notifications
* Device Orientation
* Web Payments
* Credential Management API
* Push API
* WebRTC

### Web Payments

* Payment Request API
* Payment Handler API
* Payment Method Identifiers
* Payment Method Manifest

* [Web Payments Overview](https://developers.google.com/web/fundamentals/payments/)
* [How the payment ecosystem works](https://developers.google.com/web/fundamentals/payments/basics/how-payment-ecosystem-works)

### Calculing, Measuring and improving performance

#### PRPL Pattern

* **Push** components for initial route
* **Render** the initial route asap
* **Pre-cache** components for remaining routes
* **Lazy-load** & create next routes on-demand

1. Custom elments
  * Need to manage UI complexity, bring your own framework
2. HTML Imports
  * Need to load components, bring your own JavaScript loader, completity, prevents optimizations
3. HTTP/2
  * HTTP bad for granular resources, bundling, complex toolchains, inefficient bundles
  * HTTP/2 * Server Push
4. Service Worker
  * Websites don't work without network, native apps?
  * Intercept and handle requests
  * Intelligently cache responses
  * Server cache offline
  * Background pre-caching

[Sample](https://shop.polymer-project.org/)

* RAIL Model
* Performance Metrics
* Using Lighthouse
* Using DevTools

## Server Side Rendering

* React.js
  * [Next.js](https://nextjs.org/)
  * After.js
* Angular
  * [Angular Universal](https://angular.io/guide/universal)
* Vue.js
  * [Nuxt.js](https://nuxtjs.org/)

## Static Site Generators

* [GatsbyJS](https://www.gatsbyjs.org/)

## Miscellaneous

* TypeScript: Superset of JavaScript that compiles to JavaScript.
* Flow: static type checker for JavaScript.
* Reason: Typed language that leverages the JavaScript & OCaml ecosystems
* PureScript: A strongly-typed language that compiles to Javascript, written in and inspired by Haskell
* Elm: Purely function language that compiles to Javascript.

`<link rel="preload">`, `<link rel="prefetch">`
