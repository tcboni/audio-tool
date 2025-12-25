# Audio Tool

A browser-based audio editor with a clean, modern interface. No installation required – works entirely in your browser.

**[→ Open Audio Tool](https://tcboni.github.io/audio-tool/)**

## Features

### Core Editing

- **Import** audio files (MP3, WAV, OGG, FLAC)
- **Export** to WAV, MP3, or FLAC formats
- **Record** audio directly from your microphone with real-time waveform visualization
- **Selection** - Click and drag to select regions, Shift+click to extend
- **Cut, Copy, Paste, Delete** - Standard clipboard operations
- **Undo/Redo** - Full history support (up to 50 states)

### Audio Processing

- **Fade In/Out** - Smooth volume transitions
- **Normalize** - Maximize volume without clipping
- **Reverse** - Reverse audio selection or entire track
- **Silence** - Mute selected regions
- **Amplify** - Increase or decrease volume with dB control
- **Remove Silence** - Automatically detect and remove silent regions
- **Crop** - Keep only the selected region

### Playback

- **Transport controls** - Play, pause, stop, skip to start/end
- **Seek** - Click on waveform to jump to position
- **Loop** - Loop playback of selection or entire track
- **Volume control** - Adjust playback volume
- **VU meters** - Real-time stereo level monitoring

### Navigation

- **Zoom** - Zoom in/out on the waveform
- **Scroll** - Navigate through the audio
- **Timeline** - Visual time ruler with markers

## Keyboard Shortcuts

| Key                    | Action            |
| ---------------------- | ----------------- |
| `Space`                | Play/Pause        |
| `Home`                 | Skip to start     |
| `End`                  | Skip to end       |
| `←` / `→`              | Seek ±1 second    |
| `+` / `-`              | Zoom in/out       |
| `L`                    | Toggle loop       |
| `Ctrl/Cmd + A`         | Select all        |
| `Ctrl/Cmd + C`         | Copy              |
| `Ctrl/Cmd + X`         | Cut               |
| `Ctrl/Cmd + V`         | Paste             |
| `Ctrl/Cmd + Z`         | Undo              |
| `Ctrl/Cmd + Shift + Z` | Redo              |
| `Delete`               | Delete selection  |
| `C`                    | Crop to selection |
| `I`                    | Fade in           |
| `O`                    | Fade out          |
| `N`                    | Normalize         |
| `R`                    | Reverse           |
| `A`                    | Amplify           |

## Technology

Built with vanilla HTML, CSS, and JavaScript. Uses:

- [Web Audio API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API) for audio processing
- [MediaRecorder API](https://developer.mozilla.org/en-US/docs/Web/API/MediaRecorder) for recording
- [lamejs](https://github.com/zhuker/lamejs) for MP3 encoding
- [libflac.js](https://github.com/nickarbon/libflac.js) for FLAC encoding
