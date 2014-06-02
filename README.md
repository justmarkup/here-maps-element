# &lt;here-maps&gt;

Web Component for Nokia HERE Maps using Polymer.

## Usage

1. Import Web Components' polyfill:

	```
	<script src="bower_components/platform/platform.js"></script>
	```

2. Import Custom Element:

	```
	<link rel="import" href="bower_components/bing-maps-element/src/bing-maps.html">
	```

3. Start using it!

	```
	<here-maps width="800" height="400" zoom="8" center="[47.668681, 12.404144]"></here-maps>
	```

## Options

Attribute   | Options  | Default                                      | Description
---         | ---      | ---                                          | ---
`key`       | *string* | ``  									      | App_Id
`token`     | *string* | ``  									      | App_Code
`width`     | *string* | `250`  									  | The width of the map in px
`height`    | *string* | `250`  									  | The height of the map in px
`zoom`      | *int*    | `5`                                          | The zoom of the map
`center`    | *string* | `[52.51, 13.4]`                              | The center of the map


## License

[MIT License](http://opensource.org/licenses/MIT)
