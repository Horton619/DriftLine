# DriftLine

Stylized real-time 3D backdrops for ambient loops: a coastal skyline seen from the water, a city across a river, and a mountain lake. Single HTML file (Three.js r160), no build step.

Scenes: **City**, **Landscape**, **Coast**, **Freeway**, **Skyline**, **Drive** (tabs, or `index.html#city` / `#landscape` / `#coast` / `#freeway` / `#skyline`). Freeway is a blue-hour view from an overpass down a 12-lane trench freeway into two downtowns, with long-exposure light trails (white toward camera, red away), sodium-lamp starbursts and lit tower crowns. Skyline is a dense neon night metropolis behind an elevated expressway, with a locked-off camera. Drive is an endless synthwave road with a hero car, chase camera and passing neon towers, palms and traffic.

Art styles: Clean, Low poly, Comic (depth-based ink outlines, flat tones, halftone shadows), Painterly (Kuwahara brush filter), Watercolor (edge darkening, pigment pooling, paper grain), Synthwave (gradient grade, scanlines, color fringing), Pixel art (block size, palette, dither), Film (grain, halation, vignette, fringing, AgX tone mapping, ambient occlusion), each with strength, saturation and contrast.

- **Camera move:** still, or a straight-on sideways pan (ping-pong or one way, either direction), with frame position with speed, distance, height, tilt and lens; Free mode for orbiting.
- **Sky and weather:** time of day with time-lapse, noon sun bearing, sun height (season), cloud cover, cloud speed and drift, haze, rain, rain slant, and wet streets that reflect the city.
- **Scene:** traffic density, car speed, light trails (long-exposure length; cars hide at long exposures at night), lamp flares, building height, lit windows, trees, mountain height, waves.
- **Record video:** renders frame by frame to MP4 (H.264, VP9 fallback) at 1080p, 1440p or 4K, 30 or 60 fps, with the logo burned in or left off; length can match one camera cycle exactly. Downloads work on the hosted site, not inside the Claude preview.
- **Output:** logo overlay (size, position, opacity, shadow), Fill / 16:9 / 21:9 / 32:9 framing, and a clean view with no controls for screen capture (H or Esc to exit).

Run locally: serve the folder with any static server (for example `npx serve .`). Deploys as-is to Vercel or GitHub Pages.
