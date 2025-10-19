# True Blue Excellence Website

A modern, responsive website for True Blue Excellence irrigation specialists, built with HTML and Tailwind CSS.

## Setup Instructions

1. Install dependencies:
```bash
npm install
```

2. Start the development server:
```bash
npm run dev
```

This will:
- Watch for changes in your CSS files
- Compile Tailwind CSS
- Output the processed CSS to `dist/output.css`

3. For production build:
```bash
npm run build
```

## Project Structure

- `index.html` - Main homepage
- `about.html` - About Us page
- `services.html` - Services page
- `gallery.html` - Projects gallery
- `contact.html` - Contact form and information
- `legal.html` - Legal information and policies
- `src/input.css` - Main CSS file with Tailwind imports and custom styles
- `dist/output.css` - Compiled CSS (generated)
- `tailwind.config.js` - Tailwind configuration
- `package.json` - Project dependencies and scripts

### Assets Structure

```
assets/
├── images/
│   ├── hero/         # Hero section background images
│   ├── services/     # Service-related images
│   ├── gallery/      # Project gallery images
│   ├── team/         # Team member photos
│   └── logos/        # Company and partner logos
├── icons/            # Custom icons and UI elements
└── fonts/           # Custom font files (if any)
```

See `assets/README.md` for detailed guidelines on:
- Image dimensions and formats
- Naming conventions
- Optimization requirements
- Icon guidelines
- Font usage

## Features

- Responsive design
- Mobile-friendly navigation
- Modern UI components
- Optimized for performance
- Custom color scheme and typography
- Image optimization and lazy loading
- Consistent branding across all pages
- Interactive gallery with filters
- Contact form with validation
- POPIA compliance for South African businesses

## Browser Support

The website is compatible with all modern browsers:
- Chrome
- Firefox
- Safari
- Edge

## Image Requirements

Before deploying the website, ensure you have:
1. High-quality hero images (1920x1080px minimum)
2. Service-specific images (800x600px)
3. Gallery images (800x800px)
4. Team photos (400x400px)
5. Company logo in various formats
6. UI icons in SVG format

See individual README files in asset directories for specific requirements.