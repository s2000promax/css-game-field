# create project
1. npm init -y
2. create webpack.config.js
    ## https://webpack.js.org/guides/getting-started/#basic-setup
3. npm install webpack webpack-cli --save-dev

# configure webpack.config.js
 1. add module.exports = {}

    ## add plugins: https://webpack.js.org/plugins/html-webpack-plugin
    2. npm install --save-dev html-webpack-plugin
    3. npm install copy-webpack-plugin --save-dev
    4. npm install --save-dev clean-webpack-plugin (https://www.npmjs.com/package/clean-webpack-plugin)
    5. npm install --save-dev mini-css-extract-plugin

    ## add loaders: https://webpack.js.org/loaders/
    6. npm install sass-loader sass webpack --save-dev (https://webpack.js.org/loaders/sass-loader)
    7. npm install --save-dev css-loader (https://webpack.js.org/loaders/css-loader/)

    ## add babel: https://babeljs.io/setup#installation
    8. npm install --save-dev babel-loader @babel/core
    9. npm install @babel/preset-env --save-dev
 
10. add env: npm install --save-dev cross-env
    
    ## add Dev-server: (https://webpack.js.org/configuration/dev-server/) -> https://github.com/webpack/webpack-dev-server 
    11. npm install webpack-dev-server --save-dev

    ## add @babel/polyfill: for asinc-awaint error
    12. npm install --save @babel/polyfill

    ## add esLint
    13. npm install --save-dev eslint eslint-loader babel-eslint 
    14. npm install --save-dev eslint-config-google

# layout 
1. npm install --save normalize.css (https://github.com/necolas/normalize.css/)
    
