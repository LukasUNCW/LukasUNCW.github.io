# lukas-nilsson.com

Portfolio site for Lukas Nilsson. Scroll through a 3D Manhattan trading floor at sunset and land over a trader's shoulder; the main terminal then shows each project live.

- Single `index.html` built on [Three.js](https://threejs.org) (loaded from jsDelivr), no build step.
- `assets/people/`: seated business avatars from [Microsoft Rocketbox](https://github.com/microsoft/Microsoft-Rocketbox) (MIT, see `ROCKETBOX-LICENSE.md`), textures resized for the web.
- `assets/anim/`: Rocketbox "sit at table" animations, stripped down to JSON clips.
- `assets/env/`: `venice_sunset_1k.hdr` from [Poly Haven](https://polyhaven.com/a/venice_sunset) (CC0) for lighting and reflections.

Run locally with any static server (e.g. `python3 -m http.server`); opening the file directly won't load the assets.
