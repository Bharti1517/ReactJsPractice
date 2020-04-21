## React JS Practice  develop Branch
##           ----------
## Steps to install react project 
## 1.) npm init => create package.json
## 2.) npm install react react-dom  --save
## 3.) INSTALL WEBPACK and Babel =>
## npm install webpack webpack-dev-server webpack-cli babel-core babel-loader babel-preset-env babel-preset-react html-webpack-plugin  --save
## WHY ? => 

## WEBPACK is a module bundler (manages and loads independent modules). It takes dependent modules and compiles them to a single (file) bundle. You can use this bundle while developing apps using command line or, by configuring it using webpack.config file.

## BABEL is a JavaScript compiler and transpiler. It is used to convert one source code to other. Using this you will be able to use the new ES6 features in your code where, babel converts it into plain old ES5 which can be run on all browsers.

## 4.) we need to create certain files namely, index.html, App.js, main.js, webpack.config.js and, .babelrc .
## USING => type nul > name_of_file.extension

## 5.) Webpack.config.js fill this file and index.html as well

## 6.) Remove // "test": "echo \"Error: no test specified\" && exit 1" from Package.json from script 
##     Add => 
##              "start": "webpack-dev-server --mode development --open --hot",
##              "build": "webpack --mode production"


## 7.) 
##  We are setting div id = "app" as a root element for our app and adding index_bundle.js script, which is our bundled app file.