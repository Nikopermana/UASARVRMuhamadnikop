## SUMBER/REFRENSI

- https://aframe.io/
- https://aframe.io/aframe/examples/ 
- https://github.com/aframevr/aframe-site
- Diego Marcos
  https://github.com/dmarcos
- Mozilla Developer Relations
  https://github.com/mozdevs
- The Khronos Group
  https://github.com/KhronosGroup/glTF-Sample-Models
- Pinterst
  https://id.pinterest.com/
- Preefik
  https://www.freepik.com/
- Sketchfab
  https://sketchfab.com/feed
  - Kemal Çolak
    https://sketchfab.com/3d-models/farm-free-low-poly-game-objects-f61d98fe3a1c4cdf99b12f96315d76d8
  - Edgar_koh
    https://sketchfab.com/3d-models/camping-buscraft-ambience-7b65e4df95c3492fbf4e0641e3b472c1


## License

Source code released under the **Mozilla Public License 2.0**. Read [`LICENSE`](LICENSE) for details.

The following images have been released by NASA in the public domain: `images/earth.png`, `images/moon.jpg`, `images/stars.jpg`.

## A-Frame Builds

To include these builds, you can download and serve them locally.

To include the latest [master build](#master-builds) from a CDN, include the
script below from the [jsdelivr CDN](https://www.jsdelivr.com/):

```html
<html>
  <head>
    <script src="https://cdn.jsdelivr.net/gh/aframevr/aframe@84bdb3cf4bdba86a20c603f792e283ca13bfba20/dist/aframe-master.min.js"></script>
  </head>
  <body>
    <a-scene>
      <!-- ... -->
    </a-scene>
  </body>
</html>
```

### Release Builds

These builds are available via `https://aframe.io/releases/x.x.x/<filename>`
where `x.x.x` is the latest stable version.

- `aframe-vx.x.x.min.js` - Minified production build, **recommended**.
- `aframe-vx.x.x.min.js.map` - Source maps for minified production build.
- `aframe-vx.x.x.js` - Unminified build, for development or debugging.
- `aframe-vx.x.x.js.map` - Source maps for unminified build.

### Master Builds

These master builds are unstable **bleeding-edge unstable builds** that contain
newer fixes or features from the **master branch** on GitHub, but may contain
regressions or breaking changes.

If you're pointing to these builds via the [jsDelivr CDN](https://www.jsdelivr.com/features#gh),
we recommend locking it down to a commit hash rather than pointing directly at
master such that your scene does not break unexpectedly.

- [`aframe-master.min.js`](aframe-master.min.js) - Minified production build.
- [`aframe-master.min.js.map`](aframe-master.min.js.map) - Source maps for minified production build.
- [`aframe-master.js`](aframe-master.js) - Unminified build, for development or debugging.
- [`aframe-master.js.map`](aframe-master.js.map) - Source maps for unminified build.

