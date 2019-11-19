# React-Boilerplate

## Table of contents

- [General info](#general-info)
- [How it works](#how-it-works)
- [Installation](#installation)

## General info

Boilerplate code to create a React app. React and CSS styling are configured using Webpack and Babel. This is a very basic starting point that can be expanded.

## How it works

Webpack and Babel packages are installed as dev dependencies.
Babel is configured in `.babalrc` using the previously installed presets.
Webpack is configured in `webpack.config.js` by using a babel loader and the html-webpack-plugin to serve the JavaScript file into the html. A css and style loader is used to recognize CSS files.

## Installation

From root directory:

```
$ yarn install
$ yarn start
```
