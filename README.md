# Create React Webpack

In this repo I have created a simple React app with webpack. Each branch contains a step to configure webpack with different features. final code is in the main branch. I will keep on adding branches for more features.

## React & Webpack setup supporting basic features to run a simple app

1.  For creating a blank project
    - npm init -y
2.  npm i react react-dom
3.  For supporting jsx and new js features
    - npm i @babel/core @babel/preset-react --save-dev
4.  npm i webpack webpack-cli --save-dev
5.  Webpack loader for React
    - npm i babel-loader --save-dev
6.  npm i webpack-dev-server --save-dev
7.  npm i html-webpack-plugin --save-dev
8.  create public/index.html
9.  create src/index.js
10. create src/App.js
11. create webpack.config.js
12. add start script in package.json

## Adding CSS support

1.  The css-loader interprets @import and url() like import/require() and will resolve them.
    - npm i css-loader --save-dev
2.  This plugin extracts CSS into separate files. It creates a CSS file per JS file which contains CSS. It supports On-Demand-Loading of CSS and SourceMaps.
    - npm i mini-css-extract-plugin --save-dev
3.  create src/index.css
4.  Move App.jsx to components folder and add App.css
5.  Modified webpack.dev.js to change bundle file names for js and css.
6.  Add build script in package.json to see how bundles are created.
