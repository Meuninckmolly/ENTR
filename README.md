# Neil Ratanji — Built, Not Rushed

A single-page, scroll-driven educational site built with HTML, CSS, and Three.js.

## Run it
- Open `index.html` with a local development server (for example, VS Code Live Server).
- Three.js is loaded from jsDelivr, so the 3D scene requires an internet connection.
- The article content remains readable if the 3D library fails to load.

## Easy adjustments
- **Colors and type:** edit the `:root` variables near the top of `index.html`.
- **Story content:** edit the labeled `CHAPTER` sections in the HTML.
- **3D hotel:** find `3D SCENE — easy-to-adjust controls` in the JavaScript. `COLORS`, the `addBox()` calls, and `satelliteSpecs` control the appearance.
- **Scroll scenes:** change each section's `data-scene="0"` through `data-scene="5"` and edit the `targets` array near the bottom of the script.
- **Quiz:** edit the `data-answer` buttons and the feedback text in `QUICK KNOWLEDGE CHECK`.

## Content note
The educational narrative is based on the supplied interview transcript. The hotel model is an original abstract illustration, not a real property rendering. The site avoids asserting current business details not established by the interview.
