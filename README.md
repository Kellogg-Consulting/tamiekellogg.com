# Kellogg Consulting

The web home of Kellogg Consulting - a professional consulting firm specializing in strategic initiatives, facilitation services, and public engagement for government and non-profit sectors.

🌐 **Live Site**: [tamiekellogg.com](https://www.tamiekellogg.com/)

## About

Kellogg Consulting, founded in 1990 by Tamie Kellogg, provides strategic guidance for government and non-profit organizations navigating complex public policy issues, stakeholder collaboration, and organizational development challenges.

## Site Structure

This is a static HTML/CSS website designed for deployment to GitHub Pages.

### Pages

- **[index.html](index.html)** - Home page with tagline and service overview
- **[about.html](about.html)** - About Tamie Kellogg and company history
- **[services.html](services.html)** - Detailed services, sectors, and client roster
- **[contact.html](contact.html)** - Contact information (LinkedIn and email)

### Assets

- **css/** - Stylesheet directory
  - `style.css` - Main stylesheet with professional blue color scheme
- **images/** - Image assets directory

## Local Development

To preview the site locally:

1. Clone this repository:
   ```bash
   git clone https://github.com/[username]/tamiekellogg.com.git
   cd tamiekellogg.com
   ```

2. Open in a browser:
   ```bash
   open index.html
   ```
   Or use a simple HTTP server:
   ```bash
   python3 -m http.server 8000
   # Then visit http://localhost:8000
   ```

## Customization

### Colors

The color scheme is defined in CSS variables at the top of [css/style.css](css/style.css):

```css
:root {
    --primary-blue: #2b5a89;
    --secondary-blue: #4a7ba7;
    --light-blue: #6fa3d0;
    --dark-blue: #1a3a5c;
    /* ... */
}
```

Modify these values to change the site's color scheme.

## License

© 2026 Kellogg Consulting. All rights reserved.

## Contact

- **Email**: tamie@tamiekellogg.com
- **LinkedIn**: [linkedin.com/in/tamiekellogg](https://www.linkedin.com/in/tamiekellogg)

