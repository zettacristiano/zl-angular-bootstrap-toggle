### Angular Bootstrap Toggle - [AngularJS](http://angularjs.org/) version of [Bootstrap Toggle](http://www.bootstraptoggle.com/)

# Installation

Installation is easy as UI Bootstrap has minimal dependencies - only the AngularJS and Twitter Bootstrap's CSS are required.
It is strongly recommended you use Angular 1.3+ or higher due to 'Bind Once'. 

#### Install with NPM
```sh
$ npm install zl-angular-bootstrap-toggle --save
```

### Adding dependency to your project

When you are done downloading all the dependencies and project files the only remaining part is to add dependencies on the `ui.toggle` AngularJS module:

```js
angular.module('myApp', ['zl.ui.toggle']);
```

If you're a Browserify or Webpack user, you can do:

```js
var abt = require('zl-angular-bootstrap-toggle');

angular.module('myApp', [abt]);
```

# Support

## FAQ

https://github.com/zettacristiano/zl-angular-bootstrap-toggle/wiki/FAQ

## Supported browsers

Directives from this repository are automatically tested with the following browsers:
* Chrome (stable and canary channel)
* Firefox
* IE 9 and 10
* Opera
* Safari

Modern mobile browsers should work without problems.