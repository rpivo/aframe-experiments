## Experiment 2: \<a-scene\> and the position Attribute

#### New to Me
- All aframe objects should be wrapped in an `<a-scene>` tag.
- An aframe object has a position attribute that takes three space-separated integers representing x, y, and z in virtual space.
- A position of `0 0 0` effectively puts the object in the same virtual space as the viewer.

I'm able to see that all aframe objects should be wrapped in the `<a-scene>` tag, and that adding new objects is as easy as adding more objects inside the `<a-scene>` tag. I was able to add a second box object in this way. These objects have a `position` object that takes three space-separated integers that represent the x, y, and z location of the object. If the object has a position value of `0 0 0`, this effectively puts the object in the same space as the viewer.