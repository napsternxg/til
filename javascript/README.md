---
layout: default
title: Javascript
has_children: true
permalink: /js
---


# Create shareable get param URLs using `history.replaceState`

```javascript

// Create new URL
var url = new URL(window.location.href);
var search_params = new URLSearchParams();

// We wish to set the following param to the URL
search_params.set("param1", "value1");
url.search = search_params;
history.replaceState(null, "", url.search.toString());
```


# Links

* Javascript learning via creep design simulator game - https://screeps.com/a/#!/sim/tutorial
* Javascript tutorial via elevator design game - http://play.elevatorsaga.com/ 
  - Taken from - https://github.com/michelpereira/awesome-gamesofcoding
