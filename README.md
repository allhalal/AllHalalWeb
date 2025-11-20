# AllHalal / HalalScan - Official Website

![AllHalal Logo](assets/images/logo.svg)

**Official marketing landing page and legal document hosting platform for AllHalal (HalalScan)** — a premium iOS mobile application that helps Muslims worldwide identify halal, mushbooh, and haram products through intelligent barcode scanning and ingredient analysis.

---

## 🌙 About AllHalal

AllHalal is a modern, privacy-focused mobile application that empowers Muslims to make informed purchasing decisions by:

- 📷 **Scanning product barcodes** to instantly analyze ingredients
- ✅ **Classifying products** as Halal, Haram, Mushbooh (doubtful), or Unknown
- 🔍 **Providing detailed ingredient breakdowns** with color-coded safety indicators
- 🚫 **Displaying boycott information** for brands subject to consumer boycotts
- 🕌 **Offering Islamic utilities**: Prayer times, Qibla compass, daily hadiths, Islamic calendar

---

## 🌐 Website Overview

This website serves as:

1. **Primary marketing presence** for the mobile app
2. **Legal document repository** (Privacy Policy, Terms of Service, Disclaimer)
3. **Brand authority platform** establishing trust and credibility
4. **App Store submission requirement** (Apple requires hosted legal documents)

---

## 📁 Project Structure

```
webhalal/
├── index.html                    # Home page
├── about.html                    # About page
├── features.html                 # Features page
├── contact.html                  # Contact page
├── legal/
│   ├── privacy-policy.html       # Privacy Policy (standalone)
│   ├── terms-of-service.html     # Terms of Service (standalone)
│   └── disclaimer.html           # Disclaimer (standalone)
├── assets/
│   ├── css/
│   │   ├── normalize.css         # CSS reset
│   │   ├── main.css              # Main styles
│   │   └── legal.css             # Legal document styles
│   ├── js/
│   │   ├── main.js               # Main JavaScript
│   │   └── form-validation.js    # Contact form validation
│   └── images/
│       └── (place images here)
├── sitemap.xml                   # XML sitemap for SEO
├── robots.txt                    # Robots.txt for search engines
└── README.md                     # This file
```

---

## 🎨 Design System

### Color Palette

- **Primary Green (Halal)**: `#34C759`
- **Haram Red**: `#FF3B30`
- **Mushbooh Yellow**: `#FFCC00`
- **Background Light**: `#F2F2F7`
- **Text Primary**: `#1C1C1E`
- **Text Secondary**: `#6C6C70`

### Typography

- **Primary Font**: `system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif`
- **Hero Headline**: `48px` (bold)
- **Section Headings**: `32px` (semibold)
- **Body Text**: `16px` (regular)

---

## 🚀 Getting Started

### Prerequisites

- Modern web browser (Chrome, Firefox, Safari, Edge)
- Basic web server for testing (optional)

### Local Development

1. **Clone or download** this repository

2. **Open in browser**:
   - Simply open `index.html` in your web browser
   - Or use a local server for better testing:

```bash
# Using Python 3
python3 -m http.server 8000

# Using Node.js (http-server)
npx http-server -p 8000

# Using PHP
php -S localhost:8000
```

3. **Navigate** to `http://localhost:8000`

---

## 📄 Pages

### Main Pages

- **Home** (`index.html`) - Hero section, key features, trust section, CTA
- **About** (`about.html`) - Mission, values, what we do/don't do
- **Features** (`features.html`) - Detailed feature showcase
- **Contact** (`contact.html`) - Contact form, FAQ, support information

### Legal Pages

- **Privacy Policy** (`legal/privacy-policy.html`) - GDPR & CCPA compliant
- **Terms of Service** (`legal/terms-of-service.html`) - User agreement
- **Disclaimer** (`legal/disclaimer.html`) - Liability and limitations

---

## ✨ Features

### Technical Features

- ✅ **Fully Responsive** - Mobile-first design, works on all devices
- ✅ **SEO Optimized** - Meta tags, Open Graph, structured data
- ✅ **Accessible** - WCAG 2.1 AA compliant
- ✅ **Fast Loading** - Optimized CSS, minimal JavaScript
- ✅ **Privacy-Focused** - No tracking, no analytics (respects user privacy)
- ✅ **Print-Friendly** - Legal documents optimized for printing

### Design Features

- 🎨 **Apple-Inspired Design** - Minimalist, clean, premium feel
- 🌙 **Dark Mode Support** - Optional dark theme for legal pages
- 📱 **Mobile Navigation** - Hamburger menu for small screens
- ✨ **Smooth Animations** - Fade-in effects, smooth scrolling
- ♿ **Accessibility** - Keyboard navigation, screen reader support

---

## 🔧 Customization

### Updating Content

1. **Edit HTML files** directly to change content
2. **Modify CSS variables** in `main.css` for colors/spacing:

```css
:root {
  --color-primary-green: #34C759;
  --spacing-unit: 16px;
  /* Add more variables as needed */
}
```

### Adding Images

1. Place images in `assets/images/`
2. Update image references in HTML files
3. Use WebP format for best performance
4. Include alt text for accessibility

### Contact Form Integration

The contact form currently uses mock submission. To integrate with a backend:

1. Open `assets/js/form-validation.js`
2. Uncomment the `fetch()` code in the `submitForm()` function
3. Replace `/api/contact` with your actual endpoint
4. Handle server-side validation and email sending

---

## 📊 SEO & Performance

### SEO Checklist

- ✅ Unique title tags for each page
- ✅ Meta descriptions (150-160 characters)
- ✅ Open Graph tags for social sharing
- ✅ Structured data (JSON-LD)
- ✅ XML sitemap (`sitemap.xml`)
- ✅ Robots.txt configured
- ✅ Semantic HTML structure
- ✅ Alt text for all images

### Performance Tips

- Optimize images (compress, use modern formats)
- Minify CSS and JavaScript for production
- Enable gzip/brotli compression on server
- Use CDN for static assets
- Implement caching headers

---

## 🌍 Deployment

### Static Hosting Options

1. **GitHub Pages** (Free)
   - Push to GitHub repository
   - Enable GitHub Pages in settings
   - Custom domain supported

2. **Netlify** (Free tier available)
   - Drag & drop deployment
   - Automatic HTTPS
   - Continuous deployment from Git

3. **Vercel** (Free tier available)
   - Zero-config deployment
   - Automatic HTTPS
   - Edge network

4. **Cloudflare Pages** (Free)
   - Global CDN
   - DDoS protection
   - Analytics included

### HTTPS Requirement

⚠️ **Important**: Apple App Store requires HTTPS for all legal document links. Ensure your hosting provider offers SSL/TLS certificates.

---

## 🔒 Privacy & Security

This website is designed with privacy in mind:

- ❌ **No tracking scripts** (no Google Analytics, Facebook Pixel, etc.)
- ❌ **No cookies** (except essential session cookies if you add backend)
- ✅ **HTTPS only** (force HTTPS redirect on server)
- ✅ **Minimal data collection** (contact form only)
- ✅ **Transparent practices** (see Privacy Policy)

---

## 📝 Legal Documents

The three legal documents are:

1. **Privacy Policy** - Data collection, processing, user rights
2. **Terms of Service** - User agreement, acceptable use, liability
3. **Disclaimer** - Limitations, not a religious authority, no warranties

These documents are:

- ✅ Standalone HTML pages (work without external dependencies)
- ✅ Print-friendly (optimized CSS for printing)
- ✅ Accessible (proper heading hierarchy, semantic HTML)
- ✅ Mobile-responsive (readable on all devices)
- ✅ Apple App Store compliant (required for app submission)

---

## 🛠️ Technology Stack

- **HTML5** - Semantic markup
- **CSS3** - Modern styling (Flexbox, Grid, Custom Properties)
- **Vanilla JavaScript** - No frameworks, lightweight and fast
- **No build tools** - Simple, direct deployment

---

## 📱 App Store Requirements

For Apple App Store submission, ensure:

1. ✅ Legal documents are publicly accessible
2. ✅ Direct URLs work (no redirects):
   - `https://allhalal.info/legal/privacy-policy.html`
   - `https://allhalal.info/legal/terms-of-service.html`
   - `https://allhalal.info/legal/disclaimer.html`
3. ✅ Documents load quickly (< 2 seconds)
4. ✅ HTTPS enabled (SSL/TLS certificate)
5. ✅ Mobile-responsive (readable on iPhone)

---

## 🤝 Contributing

This is a private project for AllHalal. If you're part of the team:

1. Follow the existing code style
2. Test on multiple devices/browsers
3. Update this README if adding new features
4. Keep legal documents up-to-date

---

## 📧 Contact

**Email**: [info@gezellix.com](mailto:info@gezellix.com)  
**Website**: [gezellix.com](https://gezellix.com)  
**App Store**: [Download AllHalal](https://apps.apple.com/app/allhalal) _(link to be updated)_

---

## 📄 License

© 2025 AllHalal. All rights reserved.

This website and its content are proprietary. Unauthorized copying, distribution, or modification is prohibited.

---

## 🎯 Roadmap

### Completed ✅

- [x] Homepage with hero section
- [x] About page with mission and values
- [x] Features page with detailed descriptions
- [x] Contact page with form
- [x] Legal documents (Privacy, Terms, Disclaimer)
- [x] Responsive design (mobile, tablet, desktop)
- [x] SEO optimization (meta tags, sitemap, robots.txt)
- [x] Accessibility features (WCAG 2.1 AA)

### Future Enhancements 🚀

- [ ] Multi-language support (Arabic, Urdu, Turkish, etc.)
- [ ] Blog section for halal-related articles
- [ ] FAQ page with common questions
- [ ] Testimonials section with user reviews
- [ ] Video demonstrations of app features
- [ ] Integration with app download analytics
- [ ] Newsletter signup functionality

---

## 🙏 Acknowledgments

**JazakAllahu Khairan** (May Allah reward you) for using and supporting AllHalal.

This project is built with care for the Muslim community worldwide.

---

**Made with 💚 for the Ummah**

