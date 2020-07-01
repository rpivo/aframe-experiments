## Experiment 11: The \<a-sky\> & \<-assets\> Objects

#### New to Me
- The `<a-sky>` object can be used to set a global "sky" color.
- The `opacity` attribute can be used to set the opacity of the sky (between 0 and 1).
- The `<a-assets>` object can be used to store assets like images that will be used within the render.

The `<a-plane>` object creates a plane. I don't think this plane can have depth since there is the `<a-box>` object, which is like `<a-plane>` but with depth. The size of the plane can be controlled with the `width` and `height` attributes. Note that the `<a-plane>` be standing up straight in its default state and will have to be set with an x rotation of `-90` if it should act as a floor. The `<a-assets>` object can be used to store assets like images that will be used within the render. For example, if you want to use a source image as the texture for the `<a-sky>` object, you can import this image in the `<a-assets>` object.