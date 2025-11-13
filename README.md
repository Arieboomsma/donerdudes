# Doner Dudes - Complete Website

A fully functional, self-contained website for Doner Dudes vegan kebab and shoarma restaurant chain.

## Overview

This is a complete, multi-page website featuring:

- **Home Page**: Welcome section with brand messaging and mission statement
- **Menu Page**: Complete menu with all items, categories, and descriptions
- **Order Page**: Location-based ordering system with links to all 24+ locations
- **Allergens Page**: Comprehensive allergen information and safety guidelines
- **Join Us Page**: Franchise opportunity information and contact details
- **Contact Page**: Contact form and business information

## Features

✅ **Fully Self-Contained**: No external redirects - all content is built-in
✅ **Responsive Design**: Works perfectly on desktop, tablet, and mobile
✅ **Professional Styling**: Modern UI with brand colors and smooth animations
✅ **Complete Menu**: All items with descriptions
✅ **All Locations**: 24+ Doner Dudes locations with order links
✅ **Allergen Information**: Detailed allergen tables and warnings
✅ **Franchise Information**: Complete franchise opportunity details
✅ **Contact Form**: Working contact form with email integration
✅ **Fast Loading**: Optimized images and minimal dependencies
✅ **SEO Ready**: Proper meta tags and semantic HTML

## File Structure

```
donerdudes/
├── index.html              # Home page
├── menu.html               # Menu page with all items
├── order.html              # Order page with locations
├── allergens.html          # Allergen information
├── joinus.html             # Franchise/Join Us page
├── contact.html            # Contact page with form
├── css/
│   └── style.css           # Main stylesheet
├── assets/
│   ├── logo.webp           # Doner Dudes logo
│   └── hero.webp           # Hero section image
├── README.md               # This file
└── .gitignore              # Git ignore file
```

## Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- No server-side requirements - pure static HTML/CSS

### Local Development

1. **Clone the repository**:
```bash
git clone https://github.com/yourusername/donerdudes.git
cd donerdudes
```

2. **Open locally**:
```bash
# Simply open index.html in your browser
open index.html
```

Or use a local server:
```bash
# Python 3
python3 -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000

# Node.js
npx http-server
```

Then visit `http://localhost:8000` in your browser.

## Pages Overview

### Home Page (index.html)
- Hero section with call-to-action
- Loyalty club information
- Brand mission and values
- Franchise information teaser
- Navigation to all sections

### Menu Page (menu.html)
- Complete menu organized by category:
  - Mains (Pita & Durum)
  - Sides (Fries, Nuggets, Onion Rings, etc.)
  - Dip Sauces
- Item descriptions
- Responsive grid layout

### Order Page (order.html)
- 24+ location cards
- Direct order links for each location
- How-to-order instructions
- Location selection interface

### Allergens Page (allergens.html)
- Allergen safety information
- Comprehensive allergen table
- Top 14 allergens list
- Safety warnings and guidelines
- Contact link for specific concerns

### Join Us Page (joinus.html)
- Franchise opportunity information
- Contact methods (phone, email, Calendly)
- Why choose Doner Dudes section
- Franchise 3.0 benefits
- Link to brightkitchen.nl

### Contact Page (contact.html)
- Contact form with email integration
- Business hours
- Phone and email contact info
- Quick links to other pages
- JavaScript-based form handling

## Customization

### Colors
Main brand color: `#f4c430` (Gold)
Dark background: `#1a1a1a`
Light background: `#ffffff`

To change colors, edit `css/style.css`:
```css
:root {
    --primary-color: #f4c430;
    --dark-bg: #1a1a1a;
    --light-bg: #ffffff;
}
```

### Images
Replace images in `assets/` folder:
- `logo.webp`: Header logo
- `hero.webp`: Hero section background

### Content
Edit HTML files directly to update:
- Menu items and descriptions
- Location information
- Contact details
- Business hours
- Franchise information

### Links
Update external links in:
- Order page: Location order links
- Join Us page: Franchise links
- Contact page: Email and phone links

## Deployment

### GitHub Pages

1. Create a GitHub repository named `donerdudes`
2. Push this project to the repository
3. Go to Settings > Pages
4. Select "Deploy from a branch"
5. Choose "master" branch and "/root" folder
6. Your site will be available at `https://yourusername.github.io/donerdudes/`

### Custom Domain

To use a custom domain (e.g., donerdudes.nl):

1. Add a `CNAME` file with your domain name
2. Update your domain's DNS settings to point to GitHub Pages
3. Enable custom domain in repository settings

### Other Hosting

This is a static website - it can be hosted on:
- Netlify
- Vercel
- AWS S3
- Any web hosting provider
- Your own server

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance

- Fully static HTML/CSS (no database)
- Optimized WebP images
- Minimal CSS (inline for faster delivery)
- No external dependencies
- Fast page load times
- Mobile-optimized

## SEO

- Semantic HTML structure
- Proper meta tags
- Descriptive page titles
- Mobile-friendly design
- Fast loading times
- Clean URL structure

## Contact Information

**Doner Dudes**
- Phone: +31 20 809 0077
- Email: info@donerdudes.nl
- Website: https://donerdudes.nl
- Franchise: https://brightkitchen.nl

## License

This project is created for Doner Dudes. All rights reserved.

## Version History

- **v2.0** (2025-11-13): Complete multi-page website with all content
- **v1.0** (2025-11-13): Initial redirectory page

## Support

For issues or questions about this website, please contact Doner Dudes directly at +31 20 809 0077 or info@donerdudes.nl.

---

**Last Updated**: November 13, 2025
**Created by**: Manus AI
