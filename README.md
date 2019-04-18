# mapbox-custom-layers

Demonstrating how overlays can be faster than mapbox custom layers

```js
yarn
yarn start
```

- _current.html_ is the current implementation example in mapbox source code.
- _faster.html_ shows how a canvas overlay is faster.

Faster is 18x faster.

![Performance graphics](/perf.png?raw=true "Performance")

One limitation of the overlay approach is that the z-buffer won't work.
That could be an acceptable limitation for most data vizualization that either fully above or fully flat.

Related to <https://github.com/mapbox/mapbox-gl-js/issues/8159>
