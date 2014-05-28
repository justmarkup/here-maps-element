# &lt;nokia-here&gt;

Web Component for Nokia HERE using Polymer.

## Usage

1. Import Web Components' polyfill:

	```
	<script src="//cdnjs.cloudflare.com/ajax/libs/polymer/0.0.20130816/polymer.min.js"></script>
	```

2. Import Custom Element:

	```
	<link rel="import" href="src/nokia-here.html">
	```

3. Start using it!

	```
	<nokia-here width="800" height="400" zoom="8" center="[47.668681, 12.404144]"></nokia-here>
	```

## Options

Attribute   | Options  | Default                                      | Description
---         | ---      | ---                                          | ---
`width`     | *string* | ``  										  | The width of the map
`height`    | *string* | ``  										  | The height of the map
`zoom`      | *int*    | `5`                                          | The zoom of the map
`center`    | *string* | `[52.51, 13.4]`                              | The center of the map


## License

[MIT License](http://opensource.org/licenses/MIT)
