(PLUGIN AUTHOR: Please read [Plugin README conventions](https://github.com/wearefractal/gulp/wiki/Plugin-README-Conventions), then delete this line)

# gulp-clipboard
[![NPM version][npm-image]][npm-url] [![Build Status][travis-image]][travis-url]  [![Coverage Status][coveralls-image]][coveralls-url] [![Dependency Status][depstat-image]][depstat-url]

> clipboard plugin for [gulp](https://github.com/wearefractal/gulp)

## Usage

First, install `gulp-clipboard` as a development dependency:

```shell
npm install --save-dev gulp-clipboard
```

Then, add it to your `gulpfile.js`:

```javascript
var clipboard = require("gulp-clipboard");

gulp.src("./src/*.ext")
	.pipe(clipboard({
		msg: "Hello Gulp!"
	}))
	.pipe(gulp.dest("./dist"));
```

## API

### clipboard(options)

#### options.msg
Type: `String`  
Default: `Hello World`

The message you wish to attach to file.


## License

[MIT License](http://en.wikipedia.org/wiki/MIT_License)

[npm-url]: https://npmjs.org/package/gulp-clipboard
[npm-image]: https://badge.fury.io/js/gulp-clipboard.png

[travis-url]: http://travis-ci.org/duivvv/gulp-clipboard
[travis-image]: https://secure.travis-ci.org/duivvv/gulp-clipboard.png?branch=master

[coveralls-url]: https://coveralls.io/r/duivvv/gulp-clipboard
[coveralls-image]: https://coveralls.io/repos/duivvv/gulp-clipboard/badge.png

[depstat-url]: https://david-dm.org/duivvv/gulp-clipboard
[depstat-image]: https://david-dm.org/duivvv/gulp-clipboard.png
