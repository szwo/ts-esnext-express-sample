# ts-esnext-express-sample

Sample code showing a stock Express project generated via `express-generator` converted to use TypeScript + ES6 modules. The change stems from the `type` configuration in the `package.json` file, which enables ES6 modules in the project.

# Background

This codebase was generated loosely following the following article: [How to enable ES6 (and beyond) syntax with Node and Express](https://www.freecodecamp.org/news/how-to-enable-es6-and-beyond-syntax-with-node-and-express-68d3e11fe1ab/). Originally, the article uses Babel to transpile the ES6 code back to ES5/CommonJS compatible code. I have replaced Babel with TypeScript transpilation to use ES6 modules.