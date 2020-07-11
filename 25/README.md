## Experiment 25: three.js - PerspectiveCamera & the Viewing Frustum

#### New to Me
- PerspectiveCamera takes in 4 arguments: field of view, aspect ratio, `near`, and `far`.
- Together these define the camera's "viewing frustum": https://en.wikipedia.org/wiki/Viewing_frustum
- A frustum is the portion of a cone or pyramid which remains after its upper part has been cut off by a plane parallel to its base, or which is intercepted between two such planes.

PerspectiveCamera takes in 4 arguments: field of view, aspect ratio, `near`, and `far`. Together these define the camera's "viewing frustum". A frustum is the portion of a cone or pyramid which remains after its upper part has been cut off by a plane parallel to its base, or which is intercepted between two such planes. So, a viewing frustum is kind of like a space between two planes of different size.