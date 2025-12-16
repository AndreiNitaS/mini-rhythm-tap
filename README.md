# Rhythm Tap

A rhythm-based tap game with advanced Web Audio API integration, Canvas animations, and interactive gameplay.

## Project Completion Status

### Stage 1: HTML & CSS
- Complete HTML structure with responsive design
- Modern CSS styling with animations
- Character SVG animations (splashed, mid-air, fullsize states)
- Interactive UI with difficulty selection

### Stage 2: Canvas API
- Dynamic box rendering system (50 interactive boxes)
- Real-time line animation
- Tap zone visualization
- Character jump animations
- Score and beat counter display

### Stage 3: Audio API
- Web Audio Context: Complete audio system with gain control
- Oscillators: Multiple oscillator types (sine, square, triangle) for different sounds
- Gain Nodes: Master volume and background music volume controls
- Analyser Node: Real-time frequency analysis for audio visualization
- Sound Effects:
  - Beat sounds with frequency variation
  - Tap beep with dynamic frequency based on score
  - Wrong beep with frequency sweep
  - Ambient background music
- Audio Visualization: Real-time frequency spectrum visualizer with colorful bars
- Volume Control: Independent sliders for master and background music volume
- Smart Audio Routing: All audio properly routed through analyser for visualization

### Stage 4: Video API (Ready for Implementation)
- Game recording support
- Playback functionality
- Demo video capture

## Features

### Gameplay
- Multiple Difficulty Levels: Easy, Medium, Hard, Insane
- Dynamic Scoring System: Points vary based on timing and position accuracy
- Character Animation: Visual feedback with multi-state character
- Beat Synchronization: Precise timing with BPM-based beat generation (120 BPM)
- Progressive Difficulty: 50 beats to complete each game

### Audio Features
- Volume control for master and background music
- Real-time frequency analysis and visualization
- Multiple waveform types for distinct audio feedback
- Smooth gain envelopes for natural sound
- Ambient background music with multi-frequency pads

### Visual Effects
- Glowing audio visualizer with HSL color gradients
- Box highlighting for active and tapped states
- Dynamic character animations
- Smooth canvas rendering at 60 FPS

## Controls
- SPACE: Tap the box when the red line hits it
- Difficulty Buttons: Select Easy, Medium, Hard, or Insane
- START: Begin a new game
- STOP: End current game
- Volume Sliders: Adjust master and background music volume
- Visualizer Toggle: Show/hide frequency visualizer

## Web APIs Used
1. Canvas API: 2D game rendering, animations, and visualization
2. Web Audio API: Sound synthesis, gain control, frequency analysis
3. JavaScript Web APIs: requestAnimationFrame, AudioContext, event listeners

## Installation
Simply open index.html in a modern web browser that supports Web Audio API.

## Browser Requirements
- Modern browser with Web Audio API support
- Canvas API support (all modern browsers)
- Minimum: Chrome 14+, Firefox 25+, Safari 6+, Edge 12+
