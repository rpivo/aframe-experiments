## Experiment 15: three.js - The Object3D Base Class

#### New to Me
- The `Scene` class's `add()` method actually originates from `Object3D` since the `Scene` class extends `Object3D`.
- `onBeforeRender` is a callback property on `Object3D` that fires before render.
- `onAfterRender` is a callback property on `Object3D` that fires after render.

`Object3D` is the base class for most objects in three.js and provides a set of properties and methods for manipulating objects in 3D space. These properties and methods can also be used on the `Scene` class and any other classes that extend `Object3D`. `onBeforeRender` is a callback property that fires before render, while `onAfterRender` is a callback property that fires after render.