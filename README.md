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

### Point and tune
Point a controller at a signal and pull the **trigger**: an amber slice locks onto it with a frequency/mode tag.
The pick snaps to the strongest signal within about 3 kHz. On a desktop, click a signal.

### AE screen (the AetherSDR window in VR)
1. On the PC running AetherSDR, open **[send.html](https://nigelfenton.github.io/waterfall-vr/send.html)**,
   press *Choose the AetherSDR window* and pick it. The page shows a 4-digit code.
2. On the Quest, press **AE screen**, enter the code, then **Enter VR**. The window floats to your left;
   point at it and hold **grip** to move it.

View only (no clicks back to the PC). Video goes peer-to-peer over WebRTC; the free public
[PeerJS](https://peerjs.com/) server is only used to introduce the two devices.

## On a desktop or phone
Drag to orbit, scroll or pinch to zoom. The view buttons switch between terrain, a classic top-down waterfall,
a low "valley floor" view and an automatic fly-along.

## Status
Concept demo for a possible VR view in [AetherSDR](https://github.com/aethersdr/AetherSDR). All data is
simulated; a live version would take AetherSDR's TCI spectrum stream.

Built with [three.js](https://threejs.org/). Nigel G0JKN & Claude (AI dev partner).
