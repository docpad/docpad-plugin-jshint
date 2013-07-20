# [JSHint](http://www.jshint.com/) Plugin for [DocPad](https://docpad.org)

[![NPM version](https://badge.fury.io/js/docpad-plugin-jshint.png)](https://npmjs.org/package/docpad-plugin-jshint "View this project on NPM")

## Install
```
npm install --save docpad-plugin-jshint
```

## Configure
For information on customizing your plugin configuration you can refer to the [DocPad FAQ](https://github.com/bevry/docpad/wiki/FAQ)

### Ignore Paths
```
ignorePaths: ['path/']
```
`ignorePaths` accepts an array of directory paths to ignore while hinting.

### Globals
```
globals: {var: boolean}
```
`globals` is an object of global variables, with keys as names and a boolean value to determine if they are assignable.


### JSHint options
`hintOptions` is an object where you can pass any of [JSHint's options](http://www.jshint.com/docs/#options)

## History
[You can discover the history inside the `History.md` file](https://github.com/jking90/docpad-plugin-jshint/blob/master/History.md)


## Contributing
[You can discover the contributing instructions inside the `Contributing.md` file](https://github.com/jking90/docpad-plugin-jshint/blob/master/Contributing.md)


## License
Licensed under the incredibly [permissive](http://en.wikipedia.org/wiki/Permissive_free_software_licence) [MIT License](http://creativecommons.org/licenses/MIT/)
<br/>Copyright &copy; 2013+ [Jimmy King](http://jimmyking.me) <hello@jimmyking.me>
