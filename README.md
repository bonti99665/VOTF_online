# VOTF Landing Page

This directory contains a professional landing page website for Voice of the Fans (VOTF).

## Files Structure

```
landing_page/
├── index.html              # Main landing page
├── privacy-policy.html     # Privacy Policy page
├── terms-of-service.html   # Terms of Service page
├── contact.html            # Contact Us page
├── styles.css              # Shared CSS styles
├── script.js               # JavaScript for interactivity
└── README.md               # This file
```

## Features

### Landing Page (index.html)
- Hero section with compelling headline
- Features showcase
- How It Works section
- Launch timeline explaining the first month
- Professional design with smooth animations
- Fully responsive

### Privacy Policy
- Comprehensive privacy policy
- GDPR and CCPA compliance ready
- Clear sections on data collection, usage, and rights
- Professional legal language

### Terms of Service
- Complete terms and conditions
- User conduct guidelines
- Content ownership and licensing
- Account termination policies

### Contact Page
- Multiple contact email addresses for different purposes
- Contact form with validation
- Professional layout with cards

## Design Features

- **Modern Dark Theme**: Professional dark color scheme matching the app
- **Responsive Design**: Works on desktop, tablet, and mobile devices
- **Smooth Animations**: Scroll-triggered animations for better UX
- **Professional Typography**: Clean, readable fonts
- **Consistent Branding**: Uses VOTF colors (orange primary, blue secondary)

## Color Scheme

- Primary Color: `#ff6b00` (Orange)
- Secondary Color: `#007AFF` (Blue)
- Dark Background: `#1a1a1a`
- Dark Secondary: `#2a2a2a`
- Text Colors: White, light gray, muted gray

## How to Use

### Option 1: Static File Serving
Simply open `index.html` in a web browser or serve the directory with any static file server:

```bash
# Using Python
python -m http.server 8000

# Using Node.js (http-server)
npx http-server landing_page -p 8000

# Using PHP
php -S localhost:8000 -t landing_page
```

### Option 2: Deploy to Hosting
Upload all files to any web hosting service:
- GitHub Pages
- Netlify
- Vercel
- AWS S3
- Any traditional web hosting

### Option 3: Integrate with Web Server
Place the files in your web server's public directory and configure routing.

## Customization

### Email Addresses
Update the contact email addresses in:
- `contact.html` - Contact page
- `privacy-policy.html` - Privacy contact
- `terms-of-service.html` - Legal contact

### Content
All content can be easily edited in the HTML files. The structure is semantic and well-organized.

### Styling
All styles are in `styles.css`. Customize colors, fonts, and layouts as needed.

## Browser Support

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Notes

- The contact form currently shows an alert. In production, connect it to a backend API or email service.
- The favicon references `../assets/images/favicon.png`. Adjust the path based on your deployment structure.
- All pages are self-contained and can be deployed independently.

## Future Enhancements

- Connect contact form to backend API
- Add analytics tracking
- Implement blog/news section
- Add FAQ page
- Add user testimonials section

