## Dev dependencies:

- webpack: We need Webpack to bundle our code.

- webpack-cli: We will be using some CLI features of Webpack to make our lives easier while writing some scripts.

- webpack-dev-server: I will create a server using the webpack-dev-server package. This is only meant to be used in the development environment, and not for production. This means while developing and working on my code, I don’t need a separate server like NodeJS to setup manually.

- webpack-merge: To divide our configuration into chunks, more on this later

- webpack-visualizer-plugin: To see a visual representation of each of our bundle size — how much space they are taking and what are their dependencies.

- style-loader: This adds CSS to the DOM by injecting a <script /> tag in the header

- sass-loader: For SCSS support

- node-sass: A dependency for sass-loader

- css-loader: To convert our .scss files into .css

- mini-css-extract-plugin: This plugin extracts CSS into separate files. It creates a CSS file per JS file which contains CSS.

- uglifyjs-webpack-plugin: To minify JavaScript code for production

- optimize-css-assets-webpack-plugin To minify CSS code for production

- html-webpack-plugin: This does more then generate an HTML file, it supports on demand .css and .js files automatically added to your HTML files on demand

- copy-webpack-plugin: Copies files/folders to your build folder.

- babel-loader: This is the loader that helps webpack compile .js files

- @babel/core: Babel core compiler, this is a dependency that lets you use babel-loader

- @babel/preset-react Babel preset for React code

- @babel/preset-env: Babel preset that allows you to use the latest JavaScript

- @babel/pollyfill: Babel includes a polyfill that includes a custom regenerator runtime and core-js. This will emulate a full ES2015+ environment. This means support for async/await type of cool syntax sugar.

- @babel/plugin-proposal-class-properties: Coverts your class syntax into a function for browsers that don’t support class syntax

- @babel/plugin-proposal-export-namespace-from Supports syntax like import * as ns from '../path/to/module';

- @babel/plugin-proposal-throw-expressions New syntax to throw exceptions from within an expression context.

- @babel/plugin-syntax-dynamic-import This is what helps with code splitting. Webpack ships with code splitting by default (Since webpack 1). But when you want to code split in webpack while you are using babel, then you need to use this plugin.
