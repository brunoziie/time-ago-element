# &lt;timeago&gt;

Timeago element using Polymer and Moment.js

> Maintained by [Bruno Ziiê](https://github.com/brunoziie).

## Demo

> [Check it live](http://brunoziie.github.io/timeago-element).

## Usage

1. Import Web Components' polyfill:

	```html
	<script src="lib/polymer.min.js"></script>
	```
2. Import Moment.js library

	```html
	<script src="lib/moment.min.js"></script>
	```
	2.1. If you need set a globally specific language, import the moment lang file
	```html
	<script src="lib/lang/pt-br.js"></script>
	```
	2.2. If you need set a locally specific language, import the moment lang file and set lang attribute
	```html
	<timeago datetime="2013-08-25 20:40:00" lang="pt-br"></timeago>
	```

3. Import Custom Element:

	```html
	<link rel="import" href="src/timeago.html">
	```
4. Start using it!

	```html
	<timeago datetime="2013-08-25 20:40:00"></timeago>
	```

## Options

Attribute   | Options      | Default                 			| Description
---         | ---          | ---                     			| ---
`datetime`  | *string*     | `0000-00-00 00:00:00`   			| Date and time in YYYY-MM-DD HH:mm:ss format
`refresh`   | *boolean*    | `true`               	 			| Auto refresh
`refresh`   | *int*        | `60000`               	 			| Delay to auto refresh (in milliseconds)
`lang`   		| *string*     | `en` or latest lang imported | Language for output


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
* v0.0.3 August 31, 2013
	* Add lang attribute

## License

[MIT License](http://opensource.org/licenses/MIT)