# &lt;here-maps&gt;

Web Component for Nokia HERE Maps using Polymer.

## Note

This is not fully tested, so be careful when using it.

## Install

Install the component using [Bower](http://bower.io/):

```sh
$ bower install here-maps-element --save
```

Or [download as ZIP](https://github.com/justmarkup/here-maps-element/archive/master.zip).

## Usage

1. Import Web Components' polyfill:

	```
	<script src="bower_components/platform/platform.js"></script>
	```

2. Import Custom Element:

	```
	<link rel="import" href="bower_components/here-maps-element/src/here-maps.html">
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

Dual licensed under GPLv2 & MIT

Copyright © 2014 justmarkup hallo@justmarkup.com

Permission is hereby granted, free of charge, to any person obtaining a copy of 
this software and associated documentation files (the "Software"), to deal in 
the Software without restriction, including without limitation the rights to use, 
copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the 
Software, and to permit persons to whom the Software is furnished to do so, 
subject to the following conditions:

The above copyright notice and this permission notice shall be included in all 
copies or substantial portions of the Software.
