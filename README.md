# quickstart-angular2

Prerequisite: Node.js

- Step 1: Create the app’s project folder and define package dependencies and special project setup
- Step 2: Create the app’s Angular root component
- Step 3: Create an Angular Module
- Step 4: Add main.ts, identifying the root component to Angular
- Step 5: Add index.html, the web page that hosts the application
- Step 6: Build and run the app


* package.json lists packages the QuickStart app depends on and defines some useful scripts. See Npm Package Configuration for details.
* tsconfig.json is the TypeScript compiler configuration file. See TypeScript Configuration for details.
* typings.json identifies TypeScript definition files. See TypeScript Configuration for details.
* systemjs.config.js, the SystemJS configuration file. See discussion below.


#### Install packages

```
$ npm install
```


We execute most npm scripts in the following way: npm run followed by a script-name. Some commands (such as start) don't require the run keyword.

Here's what these scripts do:

`npm start` - runs the compiler and a server at the same time, both in "watch mode"

`npm run tsc` - runs the TypeScript compiler once

`npm run tsc:w` - runs the TypeScript compiler in watch mode; the process keeps running, awaiting changes to TypeScript files and recompiling when it sees them

`npm run lite` - runs the lite-server, a light-weight, static file server with excellent support for Angular apps that use routing

`npm run typings` - runs the typings tool separately

`npm run postinstall` - called by npm automatically after it successfully completes package installation. This script installs the TypeScript definition files defined in typings.json


### Build and run the app!

```
$ npm start
```

That command runs two parallel node processes

The TypeScript compiler in watch mode
A static server called lite-server that loads index.html in a browser and refreshes the browser when application files change
In a few moments, a browser tab should open
