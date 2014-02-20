*This repository is a mirror of the [component](http://component.io) module [javve/to-string](http://github.com/javve/to-string). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/javve-to-string`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*
![web component logo](http://i49.tinypic.com/e7nj9v.png)

# toString

A minimal Javascript component for converting anything to a string

## Installation

    $ component install javve/to-string

## Example

```js
var toString = require('to-string');

toString(undefind); // returns ""
toString(null); // returns ""
toString(9); // returns "9"
toString({ foo: "bar" }); // returns something like "[object Object]"
toString(function() {}); // returns something like "function () {}"
```

## In action

[List.js](http://listjs.com)

## License

MIT
