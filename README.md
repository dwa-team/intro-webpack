## CSS, COMPASS and SASS

This exaple shows how to integrate Compass and Sass on a basic html-css-js project. 

-


## Webpack

### Requirements
	- Node.js: `node --version`

### Installation
	- to see all versions of webpack: `npm view webpack versions --json`
	- to install webpack: `npm install webpack`
		- add as DevDependency: `-D`
		- add as globally: `-g`

### Usefull Commands
    - create package.json `npm init --yes`
    - to transform a file: `webpack .src/input.js ./dist/output.js`
        - to watch changes: `--watch` or `-d`
        - to build for production: `-p`
    - to import a file: `require("./miFile.js")`
    - install and require modules, fuctions , and so on
    - install loaders: `npm install css-loader style-loader --save-dev`
    - creatie configuration file: `webpack.config.js` y ejecutar: `webpack`
    - define content
    - install webpack-dev-server: `npm install webpack-dev-server --save-dev`
    - set package.json
    - install babel: `npm install babel-core babel-loader babel-preset-es2015 --save-dev`


