# Babel Webpack Starter

A boiler plate for building Javascript application. It uses webpack, Babel and webpack-dev-server to compile and serve.  
With the following dev dependency:   
  * "babel-core":           Contains the Node API and require hook.  
  * "babel-loader":         Allows transpiling JavaScript files using Babel and webpack.
  * "babel-polyfill":       For new globals such as Promise.
  * "babel-preset-env":     Compile new JS syntax into browser supported ES5.
  * "babel-preset-stage-0": Works with babel-polyfill.
  * "webpack":              Turn modules into static assets without server. 
  * "webpack-dev-server":   Use webpack with a development server that provides live reloading. 

It is fully compatible with Async/Await as it uses the Babel polyfill.

### Installation

Install the dependencies

```
$ npm install
```

### Serve
To serve in the browser  - Runs webpack-dev-server

```
$ npm start
```

### Build
Compile and build

```
$ npm run build
```
