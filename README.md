# DriftLine

Stylized real-time 3D backdrops for ambient loops: a coastal skyline seen from the water, a city across a river, and a mountain lake. Single HTML file (Three.js r160), no build step.

Scenes: **City**, **Landscape**, **Coast**, **Skyline** (tabs, or `index.html#city` / `#landscape` / `#coast` / `#skyline`). Skyline is a dense neon night metropolis behind an elevated expressway, with a locked-off camera.

Art styles: Clean, Low poly, Comic (depth-based ink outlines, flat tones, halftone shadows), Painterly (Kuwahara brush filter), Watercolor (edge darkening, pigment pooling, paper grain), each with strength, saturation and contrast.

- **Camera move:** still, or a straight-on sideways pan (ping-pong or one way, either direction), with frame position with speed, distance, height, tilt and lens; Free mode for orbiting.
- **Sky and weather:** time of day with time-lapse, noon sun bearing, sun height (season), cloud cover, cloud speed and drift, haze, rain, rain slant, and wet streets that reflect the city.
- **Scene:** traffic density, car speed, building height, lit windows, trees, mountain height, waves.
- **Output:** logo overlay (size, position, opacity, shadow), Fill / 16:9 / 21:9 / 32:9 framing, and a clean view with no controls for screen capture (H or Esc to exit).

Run locally: serve the folder with any static server (for example `npx serve .`). Deploys as-is to Vercel or GitHub Pages.
