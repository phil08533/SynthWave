# SynthWave

A Lissajous synth. Every layer is two oscillators in a frequency ratio (e.g. 3:2). The X oscillator plays the root note and the Y oscillator plays the ratio above it, panned left and right like an oscilloscope, and the glowing figure on screen is what that interval looks like.

Open `index.html` in a browser (works on phones). Press play.

- **Layers**: `+` adds one, tap a chip or swipe the figure to move between them. Each layer has its own note, octave, ratio, waveform, volume and phase.
- **Stack** plays every layer at once. **Sequence** steps through the layers at the chosen tempo.
- **Morph (LFO)**: glides a layer's ratio back and forth between its ratio and a second one, in sound and shape. Set the target ratio, rate (0.05 Hz to 2 kHz) and depth. Above a few Hz it becomes audio-rate FM, which gives buzzy synth timbres.
- **Drift** slowly rotates the shapes.
