# Node-Notes
Things to remember

npm install react --save


npm install hjs-webpack ... --save-dev

wird zu {
  "name": "reactTut",
  "version": "1.0.0",
  "description": "Setting up npm / react / webpack.. scary by now",
  "main": "main.js",
  "dependencies": {
    "react": "^15.0.1"
  },
  "devDependencies": {
    "babel": "^6.5.2",
    "babel-core": "^6.7.6",
    "babel-loader": "^6.2.4",
    "babel-preset-es2015": "^6.6.0",
    "babel-preset-react": "^6.5.0",
    "babel-preset-react-hmre": "^1.1.1",
    "css-loader": "^0.23.1",
    "express": "^4.13.4",
    "file-loader": "^0.8.5",
    "hjs-webpack": "^8.1.0",
    "postcss-loader": "^0.8.2",
    "react-dom": "^15.0.1",
    "react-hot-loader": "^1.3.0",
    "style-loader": "^0.13.1",
    "url-loader": "^0.5.7",
    "webpack": "^1.12.14"
  },
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1",
    "start": "hjs-dev-server",
    "build": "webpack",
    "deploy": "npm run build && surge -p public -d somedomain.com"
  },
  "author": "Michael Leimstädtner",
  "license": "MIT"
}


#mkfile webpack.config.js

> var getConfig = require('hjs-webpack');
> module.exports = getConfig({
>  in: 'src/main.js',
>  out: 'public',
>  clearBeforeBuild: true
>});

npm init
npm start --watch



