# reichsCrispy

Steve Reich-inspired 31-bar additive/subtractive pattern sequencer. Load any audio file and it generates evolving rhythmic patterns following Reich's phase-shifting approach.

## Features

- **Concentric UI matrix** - Visual pattern sequencer with 31 bars × 16 beats
- **Sample & hold** - Capture and loop audio segments while holding a button
- **Waveform scrubbing** - Click/drag on waveform to position sample start
- **Audio export** - Generate .WAV files of the full 31-bar performance
- **BPM control** - Adjust tempo from the interface
- **Repeats mode** - Configure repetitions per bar (1, 2, or 4)

## How It Works

1. Load an audio file (WAV, MP3, M4A)
2. Use the concentric rings to select/preview different audio sections
3. Press and hold the center "Sample & Hold" circle to capture audio
4. Release to auto-play the captured loop through the pattern matrix
5. Patterns evolve from 1 bar to 31 bars (additive/subtractive pattern)
6. Export the result as a .WAV file

## Technology

Self-contained HTML application with:
- Web Audio API for audio processing and synthesis
- SVG for the visual matrix interface
- Inline CSS styling
- Google Fonts (Inter) via CDN

---

*All HTML files — right-click, save as, use anywhere.*

[View on GitHub](https://github.com/frenchbloke/reichsCrispy)