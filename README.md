# Steven Slate Drums - Wireframe Design

A modern, responsive wireframe design for Steven Slate Drums (SSD) product website. This project showcases a clean, professional interface for showcasing drum software products with smooth animations, dark mode support, and an intuitive user experience.

## Features

- **Responsive Design**: Fully responsive layout that works seamlessly across desktop, tablet, and mobile devices
- **Dark Mode**: Complete dark theme implementation with a theme switcher toggle in the footer
- **Animated Components**:
  - Infinite sliding album artworks carousel with fade effects
  - Rotating artist showcase with synchronized quote and image transitions
  - Animated genre slider in the hero section
- **Clean UI Elements**:
  - Minimal playlist tracks with hover interactions
  - Feature cards with statistics
  - Testimonials grid layout
  - FAQ accordion section
  - Expansion packs showcase
- **Modern Typography**: Clean, readable fonts with proper spacing and hierarchy
- **Smooth Transitions**: CSS transitions and animations throughout for a polished experience

## Sections

1. **Hero Section**: Main headline with genre slider animation
2. **Highlights**: Key feature highlights
3. **Features & Playlists**: Drum kit features with playable track lists
4. **Software Parts**: Showcase of drum software components
5. **Features Grid**: Detailed feature cards with statistics
6. **Album Artworks**: Infinite scrolling artwork gallery
7. **Buy Section**: Product purchase section
8. **Expansion Packs**: Additional product offerings
9. **FAQ**: Frequently asked questions with expandable answers
10. **Artist Showcase**: Rotating testimonials from professional producers
11. **Genres Section**: Genre-focused section with image and copy
12. **Free Section**: Free trial offering
13. **Social Proof**: Customer testimonials
14. **Final CTA**: Call-to-action section

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

## Theme Toggle

The website includes a theme switcher in the footer that allows users to toggle between light and dark modes. The preference is saved to localStorage and persists across page reloads.

## Browser Support

- Modern browsers (Chrome, Firefox, Safari, Edge)
- CSS Grid and Flexbox support required
- CSS Custom Properties (CSS Variables) required

## Project Structure

```
drums-revamp/
├── index.html          # Main HTML file
├── style.css           # All styles and animations
└── README.md           # Project documentation
```

## Customization

The design uses CSS custom properties for easy theming:

```css
:root {
  --text: #0f0f0f;
  --muted: #6b6b6b;
  --border: #e6e6e6;
  --bg-alt: #fafafa;
  --accent: #000;
}
```

These can be modified to change the overall color scheme.

## Notes

- All images are currently placeholders and should be replaced with actual product images
- The design follows a wireframe approach, focusing on layout, typography, and user flow
- All interactive elements are functional and ready for integration with backend services

## License

This is a design wireframe project. Please refer to the project license for usage terms.
