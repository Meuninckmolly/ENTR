# Neil Ratanji — Built, Not Rushed

A self-contained educational scrollytelling website based on the supplied interview transcript. The page uses Three.js for a fixed, scroll-responsive 3D scene.

## Run it locally

1. Unzip the folder.
2. Open it in VS Code.
3. Start `index.html` with the Live Server extension (or another local web server). A local server is recommended because Three.js is imported as an ES module from a CDN.
4. Keep an internet connection available for the Three.js CDN import.

## Easy customization

- **Colors:** edit `:root` in the CSS and the `COLORS` object in the JavaScript.
- **Text:** edit the chapter sections in the HTML.
- **Text readability:** `.story-section .copy` controls the solid paper panel, padding, and shadow.
- **Scroll scenes:** each chapter uses `data-scene="0"` through `data-scene="5"`.
- **3D visuals:** the JavaScript sections labeled `Opportunity`, `Service`, `Risk`, and `People` create the extra scene layers that fade and morph into view as the story progresses. Adjust their geometry, colors, or positions there.
- **Camera and hotel movement:** edit the `targets` array inside `animate()`.
- **Quiz:** edit the `data-answer` buttons and the feedback text in the final JavaScript section.

## Notes

The hotel and abstract 3D elements are illustrative, not depictions of specific properties. The educational narrative is based on the supplied interview transcript and does not claim to be a complete or current company profile. Text remains readable if the Three.js CDN is unavailable. The page respects the user's reduced-motion preference.
