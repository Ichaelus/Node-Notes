# Node-Notes
Things to remember

npm install express hjs-webpack react react-dom babel-preset-es2015 url-loader --save

bzw.

npm install express hjs-webpack react react-dom babel-preset-es2015 babel-loader url-loader --save-dev

mkfile webpack.config.js

> var getConfig = require('hjs-webpack');
> module.exports = getConfig({
>  in: 'src/main.js',
>  out: 'public',
>  clearBeforeBuild: true
>});

npm init
npm start --watch
