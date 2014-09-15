# &lt;time-ago&gt;

Time Ago element using Polymer and Moment.js

> Maintained by [Bruno Ziiê](https://github.com/brunoziie).

## Demo

> [Check it live](http://brunoziie.github.io/time-ago-element).

## Usage

1. Import Web Components' polyfill:

	```html
	<script src="//cdnjs.cloudflare.com/ajax/libs/polymer/0.3.4/platform.js"></script>
	<script src="//cdnjs.cloudflare.com/ajax/libs/polymer/0.3.4/polymer.js"></script>	

	```
2. Import Moment.js library

	```html
	<script src="lib/moment.min.js"></script>
	```
3. Import Custom Element:

	```html
	<link rel="import" href="src/time-ago.html">
	```
4. Start using it!

	```html
	<time-ago datetime="2013-08-25 20:40:00"></time-ago>
	```

## Options

Attribute   | Options      | Default                 | Description
---         | ---          | ---                     | ---
`datetime`  | *string*     | `0000-00-00 00:00:00`   | Date and time in YYYY-MM-DD HH:mm:ss format
`refresh`   | *boolean*    | `true`               	 | Auto refresh
`delay`     | *int*        | `60000`               	 | Delay to auto refresh (in milliseconds)


## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request

## History

* v0.0.1 August 25, 2013
	* Created timeago element
* v0.0.2 August 26, 2013
	* Add delay attribute

## License

[MIT License](http://opensource.org/licenses/MIT)
