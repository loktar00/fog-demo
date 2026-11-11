# Volumetric ground fog demo

Volumetric ground fog demo: real-time raymarched fog in three.js that a moving cube stirs, with shadows in the fog, a wake and live controls. Made with DeepSeek V4.1 Flash via the DeepSeek Harness.

**Play:** https://loktar00.github.io/fog-demo/

## Controls

- Drag the cube to move it. Drag empty space to orbit the camera.
- W A S D or the arrow keys move the cube. Q lowers it and E raises it.
- Mouse wheel zooms.
- Left alone, the cube drifts along an automatic figure-eight path. When you take over it stops, and it returns to the path after a few idle seconds.

The side panel has live controls:

- Atmosphere: fog density, haze, fog height, height falloff, sun height, wind speed.
- Stirring: wake strength, stir strength.
- Reactions (toggles): flow field, flow debug overlay, shadows in fog, displacement, wake.

A status line shows the current mode and the frame rate.

## Credits

- Written by DeepSeek V4.1 Flash, driven through the DeepSeek Harness.
- 3D engine: [three.js](https://threejs.org/) (MIT).
