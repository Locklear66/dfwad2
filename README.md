# DFW Adventure Park site

Static HTML and CSS, no build step.

## Files
- index.html (home), pricing.html, book-now.html, contact.html
- css/theme.css: colors (light and dark) and fonts, shared by every page
- css/index.css, pricing.css, book-now.css, contact.css: layout and components for each page
- css/mobile.css: phone, touch and landscape adjustments shared by every page. It loads after the page CSS, so it overrides it. Edit here for anything mobile.
- Small scripts (topographic background, copy buttons) sit at the bottom of each HTML file.

## Preview
Open index.html in a browser, or use the VS Code "Live Server" extension.
Fonts load from Google Fonts, so you need an internet connection to see them.

## Note
The header, footer, buttons and nav styles are repeated in each page's CSS file. A change to one usually needs repeating in the others.

## Mobile
Tested with no sideways scroll at 320, 360, 375, 390, 414px and in landscape. mobile.css is organized by breakpoint: touch devices (no sticky hover), under 900px (header not sticky), under 640px (phones), under 400px and under 340px (small phones).
