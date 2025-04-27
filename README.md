# Allissee & Company Website

A professional, responsive website for Allissee & Company, a leading palm oil production and hybrid seedling germination company in Africa.

## Features

- Clean, modern design with mobile-first approach
- Responsive navigation with hamburger menu for mobile devices
- Interactive gallery with filtering and modal view
- Contact form with validation
- Google Maps integration
- WhatsApp chat button for quick customer support
- Blog section with featured articles
- Newsletter subscription form
- Optimized for performance and SEO

## File Structure

```
allissee-website/
├── index.html
├── about.html
├── products.html
├── gallery.html
├── blog.html
├── contact.html
├── css/
│   └── style.css
├── js/
│   └── script.js
├── images/
│   ├── logo.png
│   ├── hero-bg.jpg
│   ├── gallery/
│   ├── blog/
│   └── icons/
└── README.md
```

## Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/allissee-website.git
   cd allissee-website
   ```

2. Replace placeholder images:
   - Add your company logo to `images/logo.png`
   - Add hero background image to `images/hero-bg.jpg`
   - Add gallery images to `images/gallery/`
   - Add blog post images to `images/blog/`
   - Add SVG icons to `images/icons/`

3. Update contact information:
   - Edit phone numbers and email addresses in `contact.html`
   - Update WhatsApp number in all HTML files
   - Update Google Maps embed code in `contact.html`

4. Customize content:
   - Update company information and text content
   - Modify product details and pricing
   - Add your own blog posts
   - Adjust color scheme in `css/style.css` (CSS variables)

## Deployment to Firebase Hosting

1. Install Firebase CLI:
   ```bash
   npm install -g firebase-tools
   ```

2. Login to Firebase:
   ```bash
   firebase login
   ```

3. Initialize Firebase project:
   ```bash
   firebase init hosting
   ```
   - Select your Firebase project
   - Set public directory to the root folder (.)
   - Configure as single-page app: No
   - Set up automatic builds: No

4. Deploy to Firebase:
   ```bash
   firebase deploy
   ```

## Development

- The website uses vanilla HTML, CSS, and JavaScript
- CSS variables for consistent theming
- Mobile-first responsive design
- Progressive enhancement approach
- Semantic HTML for better accessibility
- Optimized assets for performance

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Opera (latest)
- Mobile browsers (iOS Safari, Android Chrome)

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contact

Your Name - your.email@example.com
Project Link: https://github.com/yourusername/allissee-website 