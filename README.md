# 20 m Waterfall VR

A simulated 20 m amateur band shown as a scrolling 3D waterfall terrain, with a WebXR **Enter VR** mode
for Meta Quest headsets.

**Live:** https://nigelfenton.github.io/waterfall-vr/

- Frequency runs left to right (14.000–14.350 MHz), newest spectrum at the front, history rolls away behind.
- Height and colour are signal strength above the noise floor.
- Simulated signals: keyed CW, an FT8 cluster on its 15 s cycle, RTTY, speech-like SSB and a tune-up carrier.

## On a Quest
Open the link in the Quest browser and press **Enter VR**. The band sits on a table in front of you; walk round it.
Thumbstick up/down shrinks or grows it, left/right turns it.

## On a desktop or phone
Drag to orbit, scroll or pinch to zoom. The view buttons switch between terrain, a classic top-down waterfall,
a low "valley floor" view and an automatic fly-along.

## Status
Concept demo for a possible VR view in [AetherSDR](https://github.com/aethersdr/AetherSDR). All data is
simulated; a live version would take AetherSDR's TCI spectrum stream.

Built with [three.js](https://threejs.org/). Nigel G0JKN & Claude (AI dev partner).
