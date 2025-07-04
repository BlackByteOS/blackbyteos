# BlackByte OS Website

A professional website for BlackByte OS - a next-generation operating system built with pure HTML, CSS, and JavaScript.

## Features

- **Clean Dark UI**: Modern, responsive design with a beautiful dark theme
- **Pure HTML/CSS/JS**: No frameworks or build tools required
- **Mobile Responsive**: Optimized for all device sizes
- **Fast Loading**: Optimized for performance with minimal dependencies
- **SEO Friendly**: Proper meta tags and semantic HTML structure

## Pages Included

1. **index.html** - Homepage with hero section and feature preview
2. **404.html** - Custom error page with terminal theme
3. **fund.html** - Funding page with Bitcoin and Litecoin wallet addresses
4. **wiki.html** - Comprehensive documentation and guides
5. **install.html** - Installation guide with GitHub repository links
6. **features.html** - Detailed OS features and capabilities
7. **downloads.html** - Download page with different OS editions
8. **community.html** - Community platforms and contribution ways
9. **support.html** - Support resources and help options
10. **news.html** - News updates and announcements
11. **contact.html** - Contact form and team information

## Files Structure

```
blackbyte-os-site/
├── index.html          # Homepage
├── 404.html           # Error page
├── fund.html          # Funding/donations
├── wiki.html          # Documentation
├── install.html       # Installation guide
├── features.html      # OS features
├── downloads.html     # Download page
├── community.html     # Community
├── support.html       # Support
├── news.html          # News/updates
├── contact.html       # Contact
├── style.css          # Main stylesheet
├── script.js          # JavaScript functionality
└── README.md          # This file
```

## Design Features

- **Dark Theme**: Professional black/orange color scheme
- **Typography**: Clean, readable fonts with proper hierarchy
- **Interactive Elements**: Hover effects, animations, and transitions
- **Terminal Aesthetics**: Code blocks and terminal windows for tech appeal
- **Gradient Accents**: Orange gradient highlights throughout
- **Card-based Layout**: Modern card components for content organization

## JavaScript Functionality

- Mobile menu toggle
- Smooth scrolling navigation
- Copy wallet address functionality
- Form validation and submission
- Typewriter animation effect
- Tab switching for wiki sections
- Search functionality
- Notification system
- Back to top button

## Required GitHub Repositories

To make the website fully functional, you'll need to create these GitHub repositories:

### Main Repository
- **BlackByteOS/BlackByteOS** - Main operating system repository

### Additional Repositories
- **BlackByteOS/releases** - OS releases and downloads
- **BlackByteOS/docs** - Documentation and wiki content
- **BlackByteOS/artwork** - Design assets, themes, and wallpapers
- **BlackByteOS/issues** - Bug tracking and feature requests
- **BlackByteOS/keys** - GPG signing keys for verification
- **BlackByteOS/tutorials** - Video tutorials and guides
- **BlackByteOS/code-of-conduct** - Community guidelines

### Repository Structure Suggestions

#### BlackByteOS/BlackByteOS (Main repo)
```
BlackByteOS/
├── kernel/           # Kernel source code
├── userspace/        # User space applications
├── desktop/          # Desktop environment (BlackDE)
├── drivers/          # Hardware drivers
├── tools/            # System tools and utilities
├── build/            # Build scripts and configuration
├── docs/             # Basic documentation
└── README.md         # Project overview
```

#### BlackByteOS/releases
```
releases/
├── 2024.1/
│   ├── blackbyte-os-2024.1-amd64.iso
│   ├── blackbyte-os-2024.1-amd64.iso.sig
│   ├── blackbyte-os-2024.1-minimal-amd64.iso
│   ├── blackbyte-os-2024.1-server-amd64.iso
│   └── blackbyte-os-2024.1-arm64.iso
└── dev/
    └── nightly builds
```

#### BlackByteOS/docs
```
docs/
├── installation/     # Installation guides
├── user-guide/       # User documentation
├── admin-guide/      # System administration
├── development/      # Developer documentation
├── api/              # API documentation
└── troubleshooting/  # Common issues and solutions
```

## Customization

### Colors
The website uses CSS custom properties for easy theming:
```css
:root {
    --bg-primary: #0a0a0a;
    --bg-secondary: #1a1a1a;
    --accent-primary: #ff6b35;
    --text-primary: #ffffff;
    /* ... more variables */
}
```

### Adding New Pages
1. Create a new HTML file following the existing structure
2. Include the navigation and footer
3. Add appropriate meta tags
4. Link the CSS and JavaScript files
5. Update navigation links in all existing pages

### Wallet Addresses
Update the cryptocurrency wallet addresses in `fund.html`:
- Bitcoin wallet: Line 89
- Litecoin wallet: Line 109

## Deployment

### GitHub Pages
1. Push code to a GitHub repository
2. Enable GitHub Pages in repository settings
3. Select source branch (usually `main` or `gh-pages`)

### Netlify
1. Connect repository to Netlify
2. Set build command to none (static site)
3. Set publish directory to repository root

### Custom Server
Simply upload all files to your web server's document root.

## Browser Support

- Chrome/Chromium 80+
- Firefox 75+
- Safari 13+
- Edge 80+

## License

Open source project - follow the same license as BlackByte OS main repository.

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test on multiple devices/browsers
5. Submit a pull request

## Contact

For website-specific issues, please contact the web development team or create an issue in the website repository.
