## Experiment 11: Loading in Image Assets With \<a-asset\>

#### New to Me
- To load in an image asset, add an `<img />` tag to `<a-asset>` that contains `id` and `src` attributes.
- All assets loaded in from `<a-asset>` will not work locally unless you're using a local server.
- If setting an image on an `<a-plane>` object, the `<a-plane>` object must have a `height` and `width` in order to see the image.

More about the `<a-assets>` object: the scene won’t render or initialize until the browser fetches (or errors out) all the assets or the asset system reaches the timeout. Image assets can be loaded in by adding an `<img />` tag to the `<a-assets>` object.