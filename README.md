# three.fly

This is adoptation of three.js [FlyControls](http://threejs.org/examples/#misc_controls_fly)
to common js module, with major rewrite of internal structure.

# usage

``` js
// 1. Create fly controls:
// container is a DOM element where you want to receive input 
// e.g.: document.body
// THREE is a main namespace of three.js
var fly = require('three.fly');
var controls = fly(camera, container, THREE);

// 2. Inside your update scene loop (e.g. inside requestAnimationFrame()):
controls.update(1); // `1` is time delta.
```

# install

With [npm](https://npmjs.org) do:

```
npm install three.fly
```

# license

MIT
