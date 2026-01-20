# Spin Art - Drawing Top

A top-down spinning canvas where you can draw while it spins, creating mesmerizing spin art patterns.

## How to Run

Open `index.html` in any modern web browser:

```bash
open experiments/spinning-top/index.html
```

Or via local server:
```bash
python -m http.server 8000
# Visit http://localhost:8000/experiments/spinning-top/
```

## Features

### Drawing Tools
- **Pencil** - Freehand drawing
- **Line** - Straight lines (click and drag)
- **Fill** - Flood fill areas with color
- **Eraser** - Erase to background color
- **Circle** - Draw circles (click center, drag radius)
- **Rectangle** - Draw rectangles

### Controls
- **Speed** (-200 to 200 RPM) - Real-time, supports reverse spin
- **Brush Size** (1-50px)
- **Opacity** (10-100%)
- **Color Palette** - 24 preset colors + custom picker
- **Background Color** - Changeable anytime

### Keyboard Shortcuts
| Key | Action |
|-----|--------|
| P | Pencil tool |
| L | Line tool |
| F | Fill tool |
| E | Eraser |
| C | Circle tool |
| R | Rectangle tool |
| [ | Decrease brush size |
| ] | Increase brush size |
| Space | Pause/Resume spin |

## How It Works

The app uses two canvases:
1. A hidden drawing canvas where your strokes are recorded
2. A display canvas that shows the drawing canvas rotated

Mouse coordinates are transformed to account for the current rotation angle, so your brush follows your cursor naturally even while the canvas spins.

## Experiment Ideas

- Draw a single line from center outward while spinning slowly
- Create symmetrical patterns by drawing at consistent distances from center
- Use fill tool to create color wheel effects
- Try negative RPM for reverse spin effects
- Draw concentric circles and watch them spin
