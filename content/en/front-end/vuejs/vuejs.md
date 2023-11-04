---
title: Vue.js
---

## About

Vue.js is a JavaScript framework created by Evan You that aims to build single page interfaces (SPAs). It uses HTML, CSS and JavaScript (or TypeScript).

Some other information about the framework:

- Progressive framework
- Makes DOM manipulation simple
- Facilitates the division of the interface into components, facilitating maintenance.

### vue-loader

Vue Loader works as a preprocessor for .vue files. When you import a .vue file into your JavaScript code, the Vue Loader fires and performs a series of transformations on the file.

First, Vue Loader extracts the HTML template from the .vue file and compiles it into a JavaScript function that returns the HTML code rendered by the component. It then processes the CSS styles, applying vendor prefixes and resolving dependencies between styles. Finally, Vue Loader compiles the component's JavaScript code, transforming it into a function that can be executed by the browser.

These transformations are performed transparently to the developer, allowing you to write Vue code in a more intuitive and productive format. Vue Loader also supports advanced features such as hot-reloading, which allows you to update component code in real time during development.

## Using VSCode

Extensions that can be useful when using VSCode when developing using Vue.js:

- [Vetur](https://marketplace.visualstudio.com/items?itemName=octref.vetur)
- [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)


