# pages
This is a repo for public pages - a static web application for hosting information and data about PassiveProject applications.

## Overview

This repository contains a static website with the following pages:
- **Home** (`index.html`): Landing page with overview and navigation
- **About** (`about.html`): Information about PassiveProject mission and values
- **Privacy Policy** (`privacy.html`): Comprehensive privacy policy
- **Terms of Service** (`terms.html`): Terms and conditions for using PassiveProject applications

## Features

- 🎨 Clean, modern design with responsive layout
- ♿ Accessibility features (ARIA labels, keyboard navigation, focus indicators)
- 🔒 Security best practices (rel="noopener" on external links)
- 📱 Mobile-friendly responsive design
- 🚀 Easy to deploy to any static hosting service

## Local Development

To view the site locally:

```bash
# Using Python
python3 -m http.server 8000

# Using Node.js
npx http-server

# Using PHP
php -S localhost:8000
```

Then open http://localhost:8000 in your browser.

## Deployment

This static website can be deployed to any static hosting service:

### GitHub Pages
1. Go to repository Settings
2. Navigate to Pages
3. Select the branch (e.g., `main`) and root folder
4. Save and wait for deployment

### Netlify
1. Connect your GitHub repository
2. Set build command to empty (no build needed)
3. Set publish directory to `/`
4. Deploy

### Vercel
1. Import the repository
2. No build configuration needed
3. Deploy

### Other Options
- AWS S3 + CloudFront
- Azure Static Web Apps
- Firebase Hosting
- Cloudflare Pages

## File Structure

```
.
├── index.html          # Homepage
├── about.html          # About page
├── privacy.html        # Privacy policy
├── terms.html          # Terms of service
├── styles.css          # Shared stylesheet
├── LICENSE            # Apache 2.0 License
└── README.md          # This file
```

## Customization

To customize the content:
1. Edit the HTML files to update text and content
2. Modify `styles.css` to change colors, fonts, and layout
3. Update links and references as needed

## License

Licensed under the Apache License 2.0. See LICENSE file for details.

