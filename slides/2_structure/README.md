# Part 2 - Angular CLI
## 2 - Structure of an Angular CLI Application

* e2e: where your end-to-end tests are kept.

    * end-to-end is exactly what it sounds like, a methodology used to test the desired functionality of an app from start to finish.

* node_modules: where all of our package dependencies are kept.

    * As we import and use code from these packages, the build system (in this case Webpack) pulls those dependencies in from this folder.

* src: the source code of the application itself.

    * this is the stuff you write as the coder. It can be organized in any way you see fit.

* .angular-cli.json: configurations pertaining to your angular app and it's build process.

* karma.conf.js: your app's unit testing configurations.

* protractor.conf.js: Angular's e2e test configurations.

* tsconfig.json: TypeScript's config file (NOT tslint).

    * the purpose of this file is to let TypeScript know what to compile down into, whether or not to generate source maps, where your type definitions are stored, and other things that have to do with your TypeScript compiler.

* tslint.json: configurations pertaining to styling and idioms to help you write better code.
