# Quick Context (For Claude Resume)

## Project
**Name**: SignSymphony
**Purpose**: Transform sign language into visual art via webcam
**Status**: MVP Complete

## Tech Stack
**Frontend**: Vanilla JS + Three.js + MediaPipe Hands
**Rendering**: WebGL particles (100K), shader-based
**Input**: Webcam gesture recognition, keyboard fallback

## Critical Rules
- All processing LOCAL (no cloud uploads)
- Single HTML file (self-contained)
- Accessibility first (keyboard, screen reader, high contrast)

## File Locations
- Main app: `index.html` (single file, all-in-one)

## Key Commands
```bash
# Open directly in browser
open index.html

# Or serve locally
python -m http.server 8000
```

## Architecture
```
Input Layer → AI Core → Visual Engine
    ↓            ↓            ↓
MediaPipe    Sign→Emotion   Three.js
Webcam       Detection      Particles
Keyboard     Context        Shaders
```

## Features Implemented
- 6 themes (Cosmic, Nature, Cyberpunk, Minimalist, Fire, Ocean)
- 4 modes (Solo, Performance, Adaptive, Demo)
- 15 sign vocabulary with emotion mapping
- 12 particle effects (burst, spiral, heart, etc.)
- Demo mode with choreographed poem

## Remember
> "Sign language as visual superpower - magical, empowering, transformative"
