# Mivhala Palette Generator

<div align="center">
  <img src="https://res.cloudinary.com/dgwtaivvf/image/upload/v1773223507/Mivhala_icon_j1hf7l.png" alt="Mivhala Logo" width="120" height="120">
</div>

A beautiful, interactive color palette generator designed for designers and developers. Create stunning color harmonies with real-time preview, fine-tune controls, and export capabilities.

## Features

### 🎨 Color Harmony Modes
- **Analogous** - Colors adjacent on the color wheel
- **Complementary** - Opposite colors for high contrast
- **Triadic** - Three evenly spaced colors
- **Split Complementary** - A variation of complementary scheme
- **Monochromatic** - Variations of a single hue
- **Tetradic** - Four-color rectangular scheme

### 🎛️ Fine-Tune Controls
- **Base Hue** - Adjust the foundation color (0-360°)
- **Saturation Variance** - Control color intensity (0-100%)
- **Lightness Spread** - Manage brightness distribution (0-100%)

### 🔧 Interactive Features
- **Lock Colors** - Preserve specific colors while regenerating
- **Copy to Clipboard** - Click any color to copy its HEX value
- **Real-time Preview** - See changes instantly with animated blob backgrounds
- **Keyboard Shortcuts** - Press spacebar to generate new palettes

### 📤 Export Options
- **CSS Variables** - Ready-to-use CSS custom properties
- **Tailwind CSS** - Tailwind color configuration
- **SCSS Variables** - Sass variable definitions
- **PNG Export** - Download palette as image
- **PDF Export** - Print-ready palette documentation

## Usage

1. **Generate Palettes** - Click "Generate" or press spacebar for random palettes
2. **Adjust Parameters** - Use the fine-tune sliders to customize colors
3. **Switch Harmonies** - Select different color theory modes
4. **Lock Colors** - Click the lock icon to preserve colors you like
5. **Copy Colors** - Click on any color swatch to copy its HEX code
6. **Export** - Use the Export button to get code in various formats

## Technical Details

### Technologies Used
- **HTML5** - Semantic markup
- **Tailwind CSS** - Utility-first styling
- **Vanilla JavaScript** - No framework dependencies
- **HSL Color Space** - Professional color manipulation

### Color Algorithm
The app uses HSL (Hue, Saturation, Lightness) color space for accurate color theory calculations:
- Hue rotation for different harmony types
- Saturation and lightness variance for visual interest
- Mathematical color relationships for professional results

### Browser Support
- Modern browsers with ES6+ support
- Chrome, Firefox, Safari, Edge
- Mobile responsive design

## File Structure

```
mivhala.html
├── HTML Structure
│   ├── Header with Mivhala branding
│   ├── Harmony mode selector
│   ├── Color palette grid (5 colors)
│   └── Fine-tune controls
├── CSS Styling
│   ├── Glass morphism design
│   ├── Animated blob backgrounds
│   └── Custom form controls
└── JavaScript Logic
    ├── State management
    ├── Color calculations
    ├── UI interactions
    └── Export functionality
```

## Branding

- **Logo**: Mivhala icon
- **Favicon**: Custom Mivhala icon
- **Design**: Glass morphism with animated backgrounds
- **Theme**: Dark mode with vibrant color accents

## Getting Started

Simply open `mivhala.html` in a modern web browser. No installation or build process required.

## Customization

### Adding New Harmony Modes
Edit the `calculateColors()` function in the JavaScript section to add new color harmony algorithms.

### Modifying Export Formats
Update the export functions to support additional code formats or file types.

### Styling Changes
Modify the CSS variables in the `:root` section to change the overall appearance.

## License

This project is part of the Mivhala brand ecosystem. Use according to brand guidelines.

## Support

For issues, feature requests, or questions about the Mivhala Palette Generator, please refer to the brand's support channels.

---

**Mivhala** - Professional color tools for designers and developers
