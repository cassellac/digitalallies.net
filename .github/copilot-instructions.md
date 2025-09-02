# Copilot Instructions for digitalallies.net

## Project Overview
This repository contains static HTML files and assets for the Digital Allies website. The site aims to build digital confidence, foster community, and empower exploration. There is no backend or build system; all files are served as-is.

## Key Files & Structure
- `index.html`: Likely the main entry point for the website.
- `digital_allies_website.html`, `ada_guide.html`, `visual_brand_mockups.html`: Additional site pages.
- `assets/`: Contains images and branding assets (logos, favicon).

## Developer Workflows
- **No build or test commands**: All files are static. Editing HTML and assets directly updates the site.
- **No package manager or dependencies**: No `package.json`, `requirements.txt`, or similar files present.
- **No backend/server code**: All logic is client-side (HTML, CSS, JS if present).

## Project-Specific Conventions
- **File naming**: HTML files are named descriptively by purpose (e.g., `ada_guide.html` for accessibility guide).
- **Assets**: All images are stored in the `assets/` directory. Use PNG format for logos and favicon.
- **Branding**: Use provided logos from `assets/` for consistent branding. Refer to `visual_brand_mockups.html` for examples.

## Patterns & Examples
- **Navigation**: If updating navigation, ensure all HTML pages link to each other as needed.
- **Accessibility**: Refer to `ada_guide.html` for accessibility guidelines and patterns.
- **Branding**: Use `logo_horizontal_primary.png` for main site branding unless otherwise specified.

## Integration Points
- **No external integrations**: The site does not currently integrate with external services or APIs.

## How to Contribute
- Edit HTML files directly for content or structure changes.
- Add new assets to the `assets/` directory and reference them in HTML as needed.
- Keep file naming clear and descriptive.

## Example: Adding a New Page
1. Create a new HTML file (e.g., `community_resources.html`).
2. Add links to the new page from `index.html` and other relevant pages.
3. Place any new images in `assets/` and reference them with relative paths.

## References
- `README.md`: Project description and purpose.
- `visual_brand_mockups.html`: Branding usage examples.
- `ada_guide.html`: Accessibility guidelines.

---
For questions or unclear conventions, review existing HTML files for examples or ask for clarification.
