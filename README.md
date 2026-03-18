# SignSymphony

Transform sign language into stunning visual art in real-time.

## Quick Start

```bash
# Open directly
open index.html

# Or serve
python -m http.server 8000
# Then visit http://localhost:8000
```

## Features

- **Real-time gesture recognition** via MediaPipe Hands
- **100,000 particles** rendered with Three.js
- **6 visual themes**: Cosmic, Nature, Cyberpunk, Minimalist, Fire, Ocean
- **4 modes**: Solo, Performance, Adaptive, Demo
- **15 signs** with emotion-based visual mapping
- **Fully accessible**: keyboard controls, screen reader support, high contrast
- **100% local**: no cloud uploads, privacy-first

## Controls

| Key | Action |
|-----|--------|
| Space | Trigger random sign |
| 1-6 | Switch theme |
| M | Cycle mode |
| D | Toggle demo |
| C | Toggle camera |
| T | Toggle captions |
| F | Fullscreen |

## Tech

- Three.js (WebGL particles + shaders)
- MediaPipe Hands (gesture detection)
- Single HTML file (zero dependencies)

## License

MIT
