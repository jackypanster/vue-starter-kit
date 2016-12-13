## jue-cli

A customized scaffolding Vue.js project similar to [react-redux-starter-kit] (https://github.com/davezuko/react-redux-starter-kit).

It aims to provide the following features with simple use case:

+ vuex
+ webpack
+ express
+ babel
+ eslint
+ vue-loader
+ bootstrap
+ vue-router
+ mongoDB/mongoose

### Installation
```bash
git clone https://github.com/jackypanster/vue-starter-kit.git <my-project-name>
cd <my-project-name>
npm install
```

While developing, you will probably rely mostly on `npm start`; however, there are additional scripts at your disposal:

|`npm run <script>`|Description|
|------------------|-----------|
|`start`|Serves your app at `localhost:3000`. HMR will be enabled in development.|
|`compile`|Compiles the application to disk (`~/dist` by default).|
|`dev`|Same as `npm start`, but enables nodemon for the server as well.|
|`test`|Runs unit tests with Karma and generates a coverage report.|
|`test:dev`|Runs Karma and watches for changes to re-run tests; does not generate coverage reports.|
|`deploy`|Runs linter, tests, and then, on success, compiles your application to disk.|
|`deploy:dev`|Same as `deploy` but overrides `NODE_ENV` to "development".|
|`deploy:prod`|Same as `deploy` but overrides `NODE_ENV` to "production".|
|`lint`|Lint all `.js` files.|
|`lint:fix`|Lint and fix all `.js` files. [Read more on this](http://eslint.org/docs/user-guide/command-line-interface.html#fix).|

### Application Structure
