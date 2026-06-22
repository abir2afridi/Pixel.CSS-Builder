# CSS Pixel Animation Builder

A single-file browser tool for drawing pixel art and generating animated CSS ghost/character loaders. No build step required — just open the HTML file.

## Features

- **Pixel grid editor** with Draw, Erase, Fill, and Eyedropper tools
- **Adjustable grid sizes**: 8×8 to 24×24
- **10 animation presets**: Float, Flicker, Pulse, Shake, Spin, Wave, Bounce, Drift, Heartbeat, Glitch
- **Fine-tune controls**: speed, float height, scale, rotation, timing function
- **Layer toggles**: Float, Flicker, Shadow, Eye movement
- **Flicker pixel palette** with 12 preset colors + custom color picker
- **Built-in ghost presets** for quick start
- **Live preview** with adjustable scale (2×, 3×, 4×) and background toggle
- **Undo/Redo** with up to 80 history steps
- **Collapsible UI sections** for a cleaner workspace
- **Export options**: CSS + HTML or React component (styled-components)
- **Dark theme** with responsive layout

## Usage

Open `css_pixel_animation_builder.html` in any modern browser.

```
open css_pixel_animation_builder.html
```

### Keyboard Shortcuts

| Key | Action |
|-----|--------|
| **D** | Draw tool |
| **E** | Erase tool |
| **F** | Fill tool |
| **I** | Eyedropper tool |
| **Ctrl+Z** | Undo |
| **Ctrl+Y** / **Ctrl+Shift+Z** | Redo |

### Toolbar Tools

| Tool | Action |
|------|--------|
| **Draw** | Paint pixels with the active color |
| **Erase** | Remove pixels |
| **Fill** | Flood-fill an area |
| **Eyedropper** | Pick color from canvas |
| **Clear** | Reset the entire grid |
| **Ghost 1 / Ghost 2** | Load preset pixel art |

### Animation Presets

| Preset | Description |
|--------|-------------|
| Float | Up-down hover loop |
| Flicker | Pixel flicker on tentacles |
| Pulse | Scale breathe effect |
| Shake | Rapid X jitter |
| Spin | Full 360° rotation |
| Wave | Skew side to side |
| Bounce | Squash & stretch |
| Drift | Slow X+Y drift |
| Heartbeat | Double-pump scale |
| Glitch | Skew + translate |

## Export

- **Export CSS + HTML**: Generates standalone CSS with keyframes and pixel grid markup
- **Export as React component**: Generates a styled-components React component

## License

MIT License - see [LICENSE](LICENSE) for details.
