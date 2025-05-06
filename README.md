# AI Tools Directory 🤖

> The ultimate directory for discovering AI tools and resources.

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Netlify Status](https://api.netlify.com/api/v1/badges/your-badge-id/deploy-status)](https://app.netlify.com/sites/your-site/deploys)

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Getting Started](#getting-started)
- [Directory Structure](#directory-structure)
- [Customization Guide](#customization-guide)
- [Deployment](#deployment)
- [Custom Domain Setup](#custom-domain-setup)
- [Troubleshooting](#troubleshooting)
- [Support & Resources](#support--resources)

## Overview

AI Tools Directory is a responsive, modern directory website showcasing various artificial intelligence tools and resources. Built with HTML, CSS, and JavaScript, it features a clean 3-column grid layout optimized for discovery and exploration.

## Features

- 🎯 Responsive 3-column grid layout
- 🔍 Search functionality
- 🏷️ Category filtering
- 📱 Mobile-friendly design
- ⚡ Fast loading performance
- 🎨 Customizable styling
- 📊 SEO optimized

## Getting Started

### Prerequisites
- Git
- Text editor (VS Code recommended)
- Basic knowledge of HTML/CSS

### Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/ai-tools-directory.git

# Navigate to project directory
cd ai-tools-directory

# Open index.html in your browser
```

## Directory Structure

```
ai-tools-directory/
├── index.html
├── assets/
│   ├── css/
│   │   ├── style.css
│   │   └── responsive.css
│   ├── js/
│   │   └── main.js
│   └── images/
├── data/
│   └── directory-items.json
└── README.md
```

## Customization Guide

### Adding Directory Items

1. Open `data/directory-items.json`
2. Add new items following this format:

```json
{
  "name": "Tool Name",
  "description": "Tool description",
  "category": "Category",
  "url": "https://toolurl.com",
  "image": "tool-image.jpg"
}
```

### Modifying Categories

1. Open `index.html`
2. Locate the category section:

```html
<div class="categories">
  <button class="category-btn" data-category="all">All</button>
  <button class="category-btn" data-category="chatbots">Chatbots</button>
  <!-- Add more categories here -->
</div>
```

### Updating Hero Section

1. Open `index.html`
2. Modify the hero section:

```html
<section class="hero">
  <h1>Your New Title</h1>
  <p>Your new description</p>
</section>
```

### Customizing Colors

1. Open `assets/css/style.css`
2. Modify the root variables:

```css
:root {
  --primary-color: #your-color;
  --secondary-color: #your-color;
  --text-color: #your-color;
}
```

## Deployment

### Netlify Deployment

1. Create a Netlify account
2. Connect your GitHub repository
3. Configure build settings:
   - Build command: `none`
   - Publish directory: `/`

### GitHub Pages Deployment

1. Go to repository settings
2. Navigate to Pages section
3. Select main branch
4. Save changes

## Custom Domain Setup

1. Purchase domain from registrar
2. Add custom domain in deployment platform
3. Configure DNS settings:
   ```
   A Record: @ -> your-deployment-ip
   CNAME: www -> your-deployment-url
   ```
4. Wait for DNS propagation (24-48 hours)

## Troubleshooting

### Common Issues

**Images not loading**
- Check file paths
- Verify image formats
- Ensure proper permissions

**Category filters not working**
- Check console for JavaScript errors
- Verify category names match exactly
- Clear browser cache

## Support & Resources

- 📖 [Documentation Wiki](https://github.com/yourusername/ai-tools-directory/wiki)
- 🐛 [Issue Tracker](https://github.com/yourusername/ai-tools-directory/issues)
- 💬 [Community Forum](https://github.com/yourusername/ai-tools-directory/discussions)

### Additional Resources
- [HTML Best Practices](https://www.w3schools.com/html/html5_syntax.asp)
- [CSS Guidelines](https://developer.mozilla.org/en-US/docs/Web/CSS)
- [JavaScript Documentation](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Made with ❤️ by [Your Name]