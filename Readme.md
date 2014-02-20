*This repository is a mirror of the [component](http://component.io) module [segmentio/is-meta](http://github.com/segmentio/is-meta). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/segmentio-is-meta`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*
# is-meta

  Checks whether a DOM `click` event should open a link in a new tab.

## Installation

    $ component install segmentio/is-meta

## Example
    
```js
var isMeta = require('is-meta');

a.onclick = function (event) { 
  isMeta(event); // true or false
};
```

## License

  MIT
