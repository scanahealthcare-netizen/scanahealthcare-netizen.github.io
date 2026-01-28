# SCANA - Company Website

A modern, aesthetic website for SCANA, a health startup revolutionizing wound care with 3D imaging and AI.

## Overview

SCANA is a cutting-edge solution that uses advanced 3D imaging and artificial intelligence to transform wound care management. This website showcases the company's mission, technology, market opportunity, and team.

## Features

- **Modern Design**: Clean, professional aesthetic with gradient backgrounds and smooth animations
- **Fully Responsive**: Optimized for desktop, tablet, and mobile devices
- **Interactive Elements**: Smooth scrolling, fade-in animations, and hover effects
- **Comprehensive Content**: All sections from the pitch presentation including:
  - Hero section with key statistics
  - Problem statement and current methods
  - Solution overview with features
  - Market opportunity analysis
  - Business model details
  - Regulatory strategy
  - Team profiles
  - Contact information

## Getting Started

### Prerequisites

No special prerequisites needed! This is a static website that can be opened directly in any modern web browser.

### Installation

1. Clone or download this repository
2. Open `index.html` in your web browser
3. That's it! The website is ready to view.

### Local Development

If you want to make changes or run a local server:

#### Option 1: Simple HTTP Server (Python)
```bash
# Python 3
python3 -m http.server 8000

# Then open http://localhost:8000 in your browser
```

#### Option 2: Simple HTTP Server (Node.js)
```bash
# Install http-server globally
npm install -g http-server

# Run the server
http-server

# Then open http://localhost:8080 in your browser
```

#### Option 3: VS Code Live Server
- Install the "Live Server" extension in VS Code
- Right-click on `index.html` and select "Open with Live Server"

## File Structure

```
SCANA/
├── index.html          # Main HTML file
├── styles.css          # All styling and responsive design
├── script.js           # Interactive features and animations
└── README.md           # This file
```

## Customization

### Colors

The website uses CSS custom properties (variables) defined in `styles.css`. You can easily change the color scheme by modifying these variables:

```css
:root {
    --primary-color: #2563eb;
    --secondary-color: #10b981;
    --accent-color: #f59e0b;
    /* ... more variables */
}
```

### Content

All content is directly in `index.html`. Simply edit the HTML to update text, add sections, or modify the structure.

### Styling

All styles are in `styles.css`. The design uses:
- Modern CSS Grid and Flexbox layouts
- CSS gradients for visual appeal
- Smooth transitions and animations
- Responsive breakpoints for mobile devices

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with Grid, Flexbox, and animations
- **JavaScript (Vanilla)**: Interactive features without dependencies
- **Google Fonts**: Inter font family

## Sections

1. **Hero**: Eye-catching introduction with key statistics
2. **Problem**: Diabetic wounds and current care challenges
3. **Unmet Needs**: Gaps in current wound care solutions
4. **Solution**: SCANA's features and capabilities
5. **Market**: Market size and opportunity
6. **Business Model**: Revenue streams and strategy
7. **Regulatory**: FDA pathway and go-to-market plan
8. **Team**: Founders and their expertise
9. **Contact**: Team contact information

## Performance

- Lightweight: No external dependencies (except Google Fonts)
- Fast loading: Optimized CSS and JavaScript
- Smooth animations: Hardware-accelerated transforms
- SEO-friendly: Semantic HTML structure

## Future Enhancements

Potential additions:
- Contact form with backend integration
- Blog section for updates
- Case studies and testimonials
- Interactive demo or video
- Multi-language support
- Analytics integration

## License

© 2025 SCANA. All rights reserved.

## Contact

- **Heran Pradhan** (CEO): heran_pradhan@brown.edu
- **Sonia Kumar** (COO): sonia_kumar@brown.edu
- **Varun Satheesh** (CTO): varun_satheesh@brown.edu

---

Built with ❤️ for SCANA
