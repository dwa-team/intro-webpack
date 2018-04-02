## Webpack
### Requirements

- Node.js: `node --version`

### Installation
- Create package.json on yor project root `npm init --yes`

- -> Install webpack locally `npm install --save-dev webpack`
- Install webpack globally `npm install -g webpack`

- -> Install webpack-cli locally: `npm install --save-dev webpack-cli`
- Install webpack-cli: `npm install -g webpack-cli`

- If needed, install webpack-dev-server  `npm install -g webpack-dev-server`

### Usefull Commands
- See error details: `webpack --display-error-details`
- Transform a file on dev mode: `npx webpack src/app.js --output dist/bundle.js -d`
- Transform a file on production mode: `npx webpack src/index.js --output dist/bundle.js -p`
- Add webpack-cli dependencies on package.json: `webpack-cli init`
