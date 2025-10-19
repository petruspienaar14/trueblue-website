# Assets Directory Structure

This directory contains all the media and asset files for the True Blue Excellence website.

## Directory Structure

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

## Image Guidelines

### Hero Images
- Dimensions: 1920x1080px (minimum)
- Format: JPG/WEBP
- Optimization: Compressed for web
- Content: Landscape shots of irrigation systems, green lawns, sports fields

### Services Images
- Dimensions: 800x600px
- Format: JPG/WEBP
- Categories:
  - Residential irrigation
  - Commercial systems
  - Sports fields
  - Maintenance & repairs

### Gallery Images
- Dimensions: 800x800px (1:1 ratio)
- Format: JPG/WEBP
- Categories:
  - Before/After shots
  - Project completions
  - Installation process

### Team Photos
- Dimensions: 400x400px (1:1 ratio)
- Format: JPG/WEBP
- Style: Professional headshots
- Background: Consistent, neutral

### Logos
- Format: SVG preferred, PNG with transparency as fallback
- Variations:
  - Full logo
  - Icon only
  - Horizontal layout
  - Monochrome version

### Icons
- Format: SVG
- Style: Consistent line weight
- Color: Monochrome, customizable via CSS
- Common icons:
  - Service icons
  - Social media
  - UI elements

## Naming Conventions

- Use lowercase letters
- Replace spaces with hyphens
- Include dimensions in filename for images
- Examples:
  - `hero-lawn-sprinkler-1920x1080.jpg`
  - `service-residential-800x600.jpg`
  - `gallery-sports-field-800x800.jpg`
  - `logo-true-blue-horizontal.svg`
  - `icon-sprinkler.svg`

## Optimization

- All images should be optimized for web use
- Use modern formats (WEBP) with JPG fallbacks
- Implement responsive images using srcset
- Keep file sizes under:
  - Hero images: 300KB
  - Regular images: 100KB
  - Thumbnails: 30KB