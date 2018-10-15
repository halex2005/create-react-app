# react-scripts

This package includes scripts and configuration used by [Create React App](https://github.com/facebook/create-react-app).<br>
Please refer to its documentation:

- [Getting Started](https://github.com/facebook/create-react-app/blob/master/README.md#getting-started) – How to create a new app.
- [User Guide](https://github.com/facebook/create-react-app/blob/master/packages/react-scripts/template/README.md) – How to develop apps bootstrapped with Create React App.

---

# About @marcopeg fork

This fork exists to bring back the basic functionality of `react-app-rewired` in a simple
and non intrusive way. I do my best to keep this fork up-to-date and to inject as little
custom code as possible.

## Quick Start

    create-react-app project-name --scripts-version marcopeg-react-scripts

## Extend Webpack config

In your project's root you'll find `webpack.config.extend.js` which contains a simple
function that could mutate the webpack configuration that is provided by `create-react-app`.

## Extend Webpack DevServer config

The very same concept is applied to the `webpackDevServer.config.extend.js`.
