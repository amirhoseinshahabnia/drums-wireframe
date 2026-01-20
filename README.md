# Steven Slate Drums - Wireframe Design

A modern, responsive wireframe for Steven Slate Drums (SSD) product website. Features a clean interface with smooth animations, comprehensive dark mode support, and a cohesive design system built on a HSL-based gray scale palette.

## Features

- **Responsive Design**: Fully responsive across all devices
- **Dark Mode**: Complete dark theme with theme switcher (defaults to dark mode)
- **Modern Design System**: HSL-based gray scale color palette (50-900) for consistent theming
- **Animated Components**: Infinite carousels, rotating showcases, and smooth transitions
- **Clean UI**: Minimal design with backdrop blur navigation, interactive elements, and polished animations

## Technology Stack

- **HTML5**: Semantic markup
- **CSS3**: Modern CSS with custom properties (CSS variables), animations, and responsive design
- **Vanilla JavaScript**: Theme switcher and interactive components

## Getting Started

1. Clone the repository:

   ```bash
   git clone <repository-url>
   cd drums-revamp
   ```

2. Open `index.html` in your web browser

3. No build process required - this is a static HTML/CSS/JS project

## Color System

The design uses a HSL-based gray scale system with 10 shades (50-900) that power all colors throughout the site. All colors reference these variables for consistency and easy theming.

**Gray Scale Palette:**

- `--gray-50` through `--gray-900` (HSL format)
- Semantic mappings: `--text`, `--muted`, `--border`, `--bg-alt`, `--accent`
- Automatically adapts between light and dark themes

## Theme Toggle

Theme switcher in the footer allows toggling between light and dark modes. The preference is saved to localStorage. Dark mode is the default theme.

## Browser Support

- Modern browsers (Chrome, Firefox, Safari, Edge)
- Requires CSS Grid, Flexbox, and CSS Custom Properties
- Backdrop filter support recommended (graceful degradation for older browsers)

## Project Structure

```
drums-revamp/
├── index.html          # Main HTML file
├── style.css           # All styles and animations
└── README.md           # Project documentation
```

## Customization

The entire color system is built on HSL gray scale variables. To customize colors, modify the gray scale palette in `style.css`:

```css
:root {
  /* Gray scale palette (HSL format) */
  --gray-50: hsl(0, 0%, 98%);
  --gray-100: hsl(0, 0%, 96%);
  --gray-200: hsl(0, 0%, 90%);
  /* ... through gray-900 */

  /* Semantic mappings automatically use gray scale */
  --text: var(--gray-900);
  --muted: var(--gray-600);
  --border: var(--gray-200);
  --bg-alt: var(--gray-50);
  --accent: var(--gray-900);
}
```

All colors throughout the site reference these variables, making global color changes simple and consistent.

## License

This is a design wireframe project. Please refer to the project license for usage terms.
