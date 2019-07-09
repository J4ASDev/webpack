Webpack 4 Config

'css-loader'
The css-loader interprets @import and url() like import/require() and will resolve them.

https://github.com/webpack-contrib/css-loader

'mini-css-extract-plugin'
This plugin extracts CSS into separate files. It creates a CSS file per JS file which contains CSS. It supports On-Demand-Loading of CSS and SourceMaps.

https://github.com/webpack-contrib/mini-css-extract-plugin

'babel-loader @babel/core @babel/preset-env @babel/preset-react'
This package allows transpiling JavaScript files using Babel and webpack.

https://github.com/babel/babel-loader


'url-loader'
A loader for webpack which transforms files into base64 UR

https://github.com/webpack-contrib/url-loader

'file-loader'
The file-loader resolves import/require() on a file into a url and emits the file into the output directory.

https://github.com/webpack-contrib/file-loader

OPTIMIZATION;

'Chunks/Vendors'

Create a commons chunk, which includes all code shared between entry points.
https://webpack.js.org/plugins/split-chunks-plugin/#split-chunks-example-1

Create a vendors chunk, which includes all code from node_modules in the whole application.
https://webpack.js.org/plugins/split-chunks-plugin/#split-chunks-example-2

Create a custom vendor chunk, which contains certain node_modules packages matched by RegExp.
https://webpack.js.org/plugins/split-chunks-plugin/#split-chunks-example-3

