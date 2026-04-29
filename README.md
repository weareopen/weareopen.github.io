# We Are Open Co-op Archive Page

An archive website celebrating We Are Open Co-op's 10-year journey (2016-2026) in digital credentials, open recognition, and systems thinking.

## Overview

This is a single-page HTML website that commemorates WAO's legacy, highlights key partnerships and projects, and provides a curated archive of resources. The page is designed to be brand-compliant, accessible, performant, and machine-readable.

## Features

- **Brand-compliant design** using WAO's official color palette and typography
- **Responsive layout** optimized for mobile, tablet, and desktop (breakpoints: 480px, 768px, 1024px, 1440px)
- **WCAG 2.1 AA accessibility** compliance with proper heading hierarchy, ARIA labels, and keyboard navigation
- **Structured data (JSON-LD)** for AI parsing and search engine optimization
- **Single-file architecture** with embedded CSS and JavaScript for easy deployment
- **Performance optimized** with minimal dependencies and inline assets

## File Structure

```
WAO/
├── index.html          # Main HTML file with embedded CSS and JavaScript
├── logo.svg            # WAO logo (to be provided)
└── README.md           # This file
```

## Setup Instructions

1. **Add the logo file**: Place the WAO logo SVG file in the root directory as `logo.svg`. The page references this file in the header.

2. **Replace placeholder content**: The page includes placeholder markers for:
   - Project descriptions and links in the Achievements section
   - GitHub repository information
   - Podcast archive links and episode information
   - Publication details and archive.org links
   - Social media/contact information in the footer

3. **Update structured data**: Review and update the JSON-LD schema in the `<script type="application/ld+json">` section with:
   - Actual organization URL
   - Logo URL
   - Social media links (replace `[Social media URL placeholder]`)

4. **Test accessibility**: Use tools like:
   - [WAVE Web Accessibility Evaluation Tool](https://wave.webaim.org/)
   - [axe DevTools](https://www.deque.com/axe/devtools/)
   - Browser accessibility inspectors

5. **Validate HTML**: Use the [W3C HTML Validator](https://validator.w3.org/) to ensure valid HTML5.

6. **Deploy**: Upload `index.html` and `logo.svg` to your web server. The page is self-contained and requires no build process.

## Brand Guidelines

### Color Palette

- **Charcoal** (#2F495A): Primary text, headers, dark backgrounds
- **Mountain Meadow** (#00C399): Primary accent, call-to-action buttons
- **Max Yellow Red** (#FFBC42): Secondary accent, highlights
- **Cyan Process** (#16A8E2): Links
- **Orange Red Crayola** (#FC594D): Alerts, emphasis

### Typography

- **Headings (H1, H2)**: Roboto Slab, 700 weight
- **Subheadings (H3)**: Nunito, 700 weight
- **Body text**: Roboto, 400 weight

Fonts are loaded from Google Fonts with appropriate fallbacks.

## Content Sections

1. **Header**: Logo, page title, and tagline
2. **Summary**: Introductory content about WAO's mission and closure
3. **Achievements**: Grid of key partnerships and projects
4. **Resources**: Organized archive of:
   - GitHub repositories
   - Learn with WAO Podcast
   - Publications and articles
   - Other resources
5. **Footer**: Copyright, license information, team acknowledgment

## Browser Support

The page uses modern CSS features (CSS Grid, Flexbox, CSS Custom Properties) and is tested for:
- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

A smooth scrolling polyfill is included for older browsers that don't support native `scroll-behavior`.

## License

This memorial page is licensed under [Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0)](https://creativecommons.org/licenses/by-sa/4.0/).

## Notes

- All placeholder content is clearly marked with `[placeholder]` text or comments
- The page is designed to be easily maintainable - simply replace placeholder text with actual content
- Structured data can be extended with additional schemas (CreativeWork, Publication) for individual resources
- The page is optimized for performance with inline CSS/JS, but can be minified further for production if needed

## Contact

For questions or updates to this memorial page, please contact the WAO team members:
- Doug Belshaw
- John Bevan
- Laura Hilliger
