# hello-world-pages

A minimal "Hello, world" page served with GitHub Pages.

Live: https://justinwlin.github.io/hello-world-pages/

A single `index.html` with inline CSS and JS, no build step and no npm. Built by an agent driven from Hermes via herdr.

- **Light / dark mode:** follows the OS preference by default. The sun/moon button overrides it and the choice is kept in `localStorage`.
- **Avatar:** a small animated robot built from three.js primitives (three.js 0.170.0, loaded as an ES module from jsDelivr through an import map). It blinks, bobs, follows the pointer and changes colors with the theme. It holds still under `prefers-reduced-motion`, and falls back to a 🤖 emoji when WebGL or the CDN is unavailable.
