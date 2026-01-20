# Spinning Top Simulator

An interactive web-based spinning top simulator for experimenting with different top designs, patterns, and physics parameters.

## How to Run

Simply open `index.html` in any modern web browser:

```bash
# From the repository root
open experiments/spinning-top/index.html

# Or use a local server
python -m http.server 8000
# Then visit http://localhost:8000/experiments/spinning-top/
```

## Features

### Physics Controls
- **Spin Speed**: Set the target RPM (0-200)
- **Friction**: Controls how quickly the top slows down (higher = longer spin)
- **Wobble Amount**: How much the top wobbles as it slows
- **Precession Speed**: Speed of the wobble rotation (gyroscopic precession)

### Top Designs
Five different shapes:
- **Classic**: Traditional wooden top with dome and handle
- **Flat Disc**: Low-profile disc top
- **Cone**: Conical top design
- **Tiered**: Multi-layer stacked disc design
- **Mushroom**: Mushroom-shaped top

### Patterns
Five pattern options:
- **Spiral**: Three-armed spiral pattern
- **Segments**: Pie-slice segments
- **Concentric Rings**: Bullseye pattern
- **Dots**: Dotted rings
- **Radial Stripes**: Alternating stripes from center

### Color Customization
- Primary, secondary, and accent colors
- Full color picker support

### Presets
- **Classic**: Traditional toy top look
- **Hypnotic**: Mesmerizing spiral pattern
- **Rainbow**: Colorful multi-segment design
- **Minimal**: Clean, simple aesthetic

## Experiment Ideas

1. **Optimal friction**: What friction value gives the longest spin time?
2. **Visual illusions**: Which patterns create interesting optical effects when spinning?
3. **Shape comparison**: Compare spin stability between different shapes
4. **Color blending**: Observe how colors blend at different speeds
5. **Wobble physics**: Study precession behavior at different speeds

## Technical Notes

- Built with HTML5 Canvas and vanilla JavaScript
- No external dependencies
- Uses `requestAnimationFrame` for smooth 60fps animation
- Physics simulation includes basic friction and precession models

## Future Improvements

Potential enhancements to explore:
- 3D rendering with WebGL
- Sound effects
- Multiple tops spinning simultaneously
- Export/import custom designs
- More realistic physics (moment of inertia, angular momentum)
