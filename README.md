# Isomorphic React App ![N|Solid](https://travis-ci.org/PyColors/isomorphic-react-app.svg?branch=master)

![N|Solid](https://camo.githubusercontent.com/f9c8de43f46e984e8f8bbcaca191cd2347048d9a1bed347b485dc5d5680f91d9/68747470733a2f2f7062732e7477696d672e636f6d2f6d656469612f444c3536465357566f41412d4255412e6a70673a6c61726765) 

Isomorphic React App is a Server-Side Rendering application with All Best Practices.  

### Tech

Isomorphic React App uses a number of open source projects to work properly:

* [React] - A JavaScript library for building user interfaces
* [Redux] - Predictable state container for JavaScript apps
* [redux-saga] - An alternative side effect model for Redux apps
* [Jest] - Delightful JavaScript Testing
* [Webpack] - Bundle assets scripts
* [Babel] - The compiler for writing next generation JavaScript

And of course Isomorphic React App itself is open source with a [public repository][dill] on GitHub.

### Installation

This app requires [Node.js](https://nodejs.org/) v8+ to run.

Install the dependencies.

```sh
$ move into directory
$ npm install
```

### Start the server

Start the local server on with livereload by webpack: `port:3000`

```sh
$ npm start-dev
```

### Test

Runs the test

```sh
$ npm test
```

Runs the test watcher in an interactive mode.

```sh
$ jest --watch or npm test --watch
```

### For production

Runs in prod

```sh
$ npm start-test
```

Builds JavaScript for production to the dist folder. 
It correctly bundles React in production mode and optimizes the build for the best performance.

```sh
$ npm build
```

License
----

MIT

**Free Software, Hell Yeah!**

[//]: # 
   [dill]: <https://github.com/PyColors/isomorphic-react-app>
   [React]: <https://github.com/facebook/react>
   [Jest]: <https://github.com/facebook/jest>
   [Webpack]: <https://github.com/webpack/webpack>
   [Babel]: <https://babeljs.io/>
   [redux-saga]: <https://github.com/redux-saga/redux-saga>
   [redux]: <https://github.com/reduxjs/redux>
   
