# Ink Drift

A generative flow-field drawing toy. Drag your mouse (or finger) across the
canvas to paint glowing particle trails that drift along a shifting noise
field; click for a burst of particles radiating outward.

Everything runs in a single HTML file — vanilla JS and the Canvas 2D API,
no build step and no dependencies.

## Running it

Open `index.html` in a browser.

## Controls

| Control | Effect |
|---|---|
| Drag | Paint particle trails |
| Click | Emit a radial burst |
| Flow strength | How strongly particles bend along the noise field |
| Speed | Particle movement speed |
| Trail length | How long particle trails persist before fading |
| Brush size | Spread of particles spawned under the cursor |
| Density | How many particles spawn per frame while dragging |
| Palette swatches | Switch the color scheme (Aurora, Ember, Mint, Mono) |
| Clear | Wipe the canvas |
| Export PNG | Save the current canvas as a PNG image |
| Hide panel | Collapse the controls panel |
