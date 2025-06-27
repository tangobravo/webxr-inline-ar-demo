This sample demonstrates how an `immersive-ar` session with `camera-access`
and `dom-overlay` features can be used to render an AR scene to a DOM canvas
with correct frame sync and reasonable performance.

It also demonstrates some differences between the `immersive-ar` fullscreen
mode and the behaviour of an `immersive-ar` session with `dom-overlay`.

I believ a native "inline-ar" session type would be preferable to avoid the
enforced full-screen switch and extreme aspect ratio. I assume it could also
offer better performance than this approach.

Originally based on the ar-barbones sample from Immersive WebXR Samples Repo.
LICENSE.md, css, and the WebXR logo were also taken from the same source.
https://github.com/immersive-web/webxr-samples
