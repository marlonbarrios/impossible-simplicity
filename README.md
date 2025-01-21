# Interactive Audio-Reactive Body Visualization

An interactive art piece that creates a dynamic visualization using body tracking and audio input. The visualization responds to movement, hand positions, and sound amplitude to create an organic, flowing experience.

## Features

### Color Transitions
- Default state: Red (Pantone #e71d36)
- Transitions to white when hands are near the center
- Changes to turquoise (#2ec4b6) when hands are above head
- Shifts to yellow/orange (#ff9f1c) when hands are below hips

### Growth Effects
- Entire visualization expands when hands are raised above head
- Scales from center point
- Maximum growth factor of 2x
- Smooth transitions between states

### Audio Reactivity
- Responds to microphone input
- Affects multiple aspects of the visualization:
  - Movement speed and wave patterns
  - Size and thickness of elements
  - Glow intensity and opacity
  - Particle behavior
  - Rotation and spiral effects

### Visual Elements
1. Body Framework
   - Elastic lines connecting body points
   - Dynamic thickness and glow effects
   - Spring-like movement
   - Audio-reactive wobble

2. Chest Vortex
   - Central spiral effect
   - Glowing core
   - Dynamic particles
   - Responds to:
     - Hand proximity
     - Audio amplitude
     - Movement speed

3. Organic Tendrils
   - Flowing cilia/flagella effects
   - Reach toward nearby points
   - Audio-reactive waves
   - Glowing tips
   - Dynamic movement patterns

## Controls
- Start Audio: Click the "Start Audio" button to enable microphone input
- Hand Position:
  - Above head: Turquoise color + growth
  - Center: White color
  - Below hips: Yellow/orange color
- Audio Input: Speak or make sounds to affect the visualization

## Technical Details
- Uses MediaPipe for body tracking
- P5.js for visualization
- Web Audio API for sound processing
- Real-time audio analysis and response
- Smooth transitions using lerp functions

## Requirements
- Modern web browser with webcam access
- Microphone access for audio reactivity
- Sufficient lighting for body tracking

# [GO TO LIVE APP](https://marlonbarrios.github.io/impossible-simplicity/)

  Created during a artistic reserach residency at [Lake Studios Berlin](https://lakestudiosberlin.com/) in February 2024
