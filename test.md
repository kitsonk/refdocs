# Testing #

```js
require(["dojo/dom", "dojo/domReady!"], function(dom){
	console.log("nothing");
});
```

```codeglass
description:

Testing this out.

js:
require(["dojo/dom", "dojo/domReady!"], function(dom){
	console.log(dom.byId("something"));
});

html:
<div id="something">Test</div>

css:
#something { border: 2px solid back; }
```

## See Also ##

* [testing](test)
