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


# Pipes in JS

Source: https://medium.com/@venomnert/pipe-function-in-javascript-8a22097a538e

```js
const _pipe = (a, b) => (arg) => b(a(arg));
const pipe = (...ops) => ops.reduce(_pipe)
```


# Links

* Javascript learning via creep design simulator game - https://screeps.com/a/#!/sim/tutorial
* Javascript tutorial via elevator design game - http://play.elevatorsaga.com/ 
  - Taken from - https://github.com/michelpereira/awesome-gamesofcoding
* Modern JS tutorial - https://javascript.info/
* IndexedDB - https://dexie.org/
* You can access SQLlite db files using javascript without any server - https://phiresky.github.io/blog/2021/hosting-sqlite-databases-on-github-pages/
* WebGazer.js do gaze tracking in JS - https://webgazer.cs.brown.edu/
