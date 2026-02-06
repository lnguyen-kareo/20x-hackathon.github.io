# 20x Hackathon Presentation

A dynamic, self-contained single-page presentation showcasing the 20x Hackathon results.

## Quick Start

Simply open `presentation.html` in any modern web browser:

```bash
open presentation.html
```

Or double-click the file in Finder.

## Features

- ✨ **Zero dependencies** - No build step, no npm install required
- 🎨 **Scroll-triggered animations** - Smooth fade-ins and slide-ups using Motion One
- 📊 **Animated counters** - Stats that count up when scrolled into view
- 🎯 **Interactive cards** - Hover effects on project cards
- 📱 **Fully responsive** - Works on desktop, tablet, and mobile
- 🎨 **Teal branding** - Matches the provided illustration design
- 📈 **Progress indicator** - Visual scroll progress bar at the top

## Structure

```
presentation.html           # Main presentation file (self-contained)
presentation-assets/
  └── saxophone.png        # Branding illustration
```

## Sections

1. **Hero** - "Not a Roadmap Priority" wish list intro
2. **Problem** - Lingering bugs and backlog issues
3. **Solution** - 20x Hackathon stats (3 tools, 3 people, 2 days)
4. **AI Planning** - Beyond "using AI to code"
5. **Process** - Repeatable methodology
6. **Projects** - UI/UX Logger, DevX System, Arcade Hub
7. **Vision** - Innovation Sprints & Tebra Labs
8. **Closing** - Force-multipliers for big ideas
9. **CTA** - Call to action

## Technology

- **HTML5/CSS3** - Modern semantic markup and styling
- **Motion One** - Lightweight animation library (loaded via CDN)
- **Vanilla JavaScript** - No framework dependencies
- **Intersection Observer API** - Efficient scroll detection

## Customization

The presentation uses CSS custom properties (variables) for easy theming:

```css
--primary-dark: #004d40;
--primary-teal: #2d6b6b;
--accent-teal: #5f9ea0;
--light-teal: #e0f2f1;
```

Edit these values in the `<style>` section to adjust the color scheme.

## Browser Compatibility

Works in all modern browsers:

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)

## Notes

- The presentation is designed for full-screen viewing
- Use scroll or arrow keys to navigate between sections
- All animations are hardware-accelerated for smooth performance
