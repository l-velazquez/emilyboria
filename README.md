# Emily Thais Boria Figueroa - Portfolio Website

A modern, responsive personal portfolio website for Emily Thais Boria Figueroa, a Researcher, Scholar, and Advocate in Rehabilitation Counseling at UPR-Ponce.

## 🌐 Live Site

Visit the live website at: [emilyboria.com](https://emilyboria.com)

## 📋 Overview

This is a elegant, single-page portfolio website showcasing professional background, expertise, and accomplishments. The site features a beautiful, modern design with smooth animations and is fully responsive across all devices.

## ✨ Features

- **Modern Design**: Clean and elegant interface with smooth animations
- **Responsive Layout**: Fully responsive design that works on desktop, tablet, and mobile devices
- **Professional CV**: Integrated CV display (CV.html) with complete academic and professional information
- **Decorative Elements**: Animated floral background elements that add visual interest
- **Optimized Performance**: Optimized images (WebP format), pre-loaded fonts, and efficient asset loading
- **PWA Support**: Web app manifest for progressive web app capabilities
- **Accessibility**: Semantic HTML structure with proper meta tags and accessibility considerations
- **Theme Support**: Light and dark theme support with system preference detection

## 🛠️ Technology Stack

- **HTML5**: Semantic markup and structure
- **CSS3**: Modern styling with CSS custom properties, Flexbox, animations, and gradients
- **Fonts**: Google Fonts (Josefin Sans for body text, Mrs Saint Delafield for decorative text)
- **Icons**: Multiple favicon formats (.ico, .svg, .png) for cross-platform support
- **Web Assets**: High-quality images in WebP format for optimized loading

## 📁 Project Structure

```
emilyboria/
├── index.html              # Main portfolio page
├── CV.html                 # Professional curriculum vitae
├── styles/                 # CSS stylesheets (directory)
├── scripts/                # JavaScript files (directory)
├── images/                 # Image assets
├── favicon.ico             # Browser tab icon
├── favicon.svg             # SVG favicon
├── favicon-96x96.png       # PNG favicon
├── apple-touch-icon.png    # iOS home screen icon
├── site.webmanifest        # PWA manifest file
├── emily-logo.png          # Logo (raster)
├── emily-logo.svg          # Logo (vector)
├── CNAME                   # Custom domain configuration
└── README.md              # This file
```

## 🎨 Design Highlights

- **Color Scheme**: Warm, inviting palette with cream background (#fffdf8) and brown text (#2d1810)
- **Accent Colors**: Orange (#ff9a2e), deep orange (#ff7a1a), and yellow (#ffd234) for highlights
- **Typography**: Elegant serif fonts paired with clean sans-serif
- **Animations**: Smooth entrance animations and breathing effects on decorative elements
- **Dark Mode**: Automatically adapts to system dark mode preferences with adjusted colors

## 📱 Browser Compatibility

- Chrome/Chromium (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🚀 Getting Started

### Prerequisites

No build tools or dependencies required - this is a static HTML/CSS website.

### Local Development

1. Clone the repository:
   ```bash
   git clone https://github.com/l-velazquez/emilyboria.git
   cd emilyboria
   ```

2. Open the website locally:
   - Simply open `index.html` in your web browser, or
   - Use a local server (recommended):
     ```bash
     python -m http.server 8000
     # or
     npx http-server
     ```

3. Open `http://localhost:8000` in your browser

## 📝 Content

### Main Page (index.html)
- Professional introduction
- Brief bio
- Call-to-action for CV
- Link to download/view full CV

### CV Page (CV.html)
- Comprehensive curriculum vitae
- Academic background
- Professional experience
- Research and scholarly work
- Publications and presentations
- Awards and recognitions

## 🔧 Customization

### Updating Content

Edit `index.html` to update:
- Personal information
- Bio and introduction
- Links and call-to-action buttons

Edit `CV.html` to update:
- Educational background
- Professional experience
- Publications and research
- Skills and certifications

### Changing Colors

Modify CSS custom properties in `index.html` `<style>` section:
```css
:root {
  --bg: #fffdf8;           /* Background color */
  --text: #2d1810;         /* Primary text color */
  --text-muted: #8b6914;   /* Muted text color */
  --orange: #ff9a2e;       /* Accent color */
  /* ... more colors ... */
}
```

### Updating Images

Replace image files in the `images/` directory and update references in HTML files.

## 📦 Assets

### Icons and Branding
- `emily-logo.svg` - Vector logo (recommended for scalability)
- `emily-logo.png` - Raster logo for fallback
- Multiple favicon formats for cross-platform support

### Images
- Optimized in WebP format for better performance
- Located in `images/` directory

## 🌍 Deployment

This site is configured for GitHub Pages:

1. Repository is set to deploy from the main branch
2. Custom domain `emilyboria.com` is configured in `CNAME` file
3. Static files are served directly without build process

### Deploying Changes

Simply push to the `main` branch:
```bash
git add .
git commit -m "Update portfolio content"
git push origin main
```

Changes will be automatically deployed to the live site.

## 📊 Performance

- **Optimized Images**: WebP format with PNG fallbacks
- **Font Preloading**: Google Fonts preconnected for faster loading
- **CSS Animations**: GPU-accelerated using `will-change` property
- **Minimal Dependencies**: No external JavaScript libraries required

## ♿ Accessibility

- Semantic HTML5 markup
- Proper heading hierarchy
- Meta descriptions for SEO
- Viewport configuration for responsive design
- Color contrast compliant with WCAG guidelines

## 📄 License

This project is maintained as a personal portfolio website. Please contact for usage inquiries.

## 👤 Author

**Emily Thais Boria Figueroa**
- Researcher, Scholar, and Advocate in Rehabilitation Counseling
- University of Puerto Rico - Ponce Campus

## 🔗 Links

- **Website**: [emilyboria.com](https://emilyboria.com)
- **GitHub Repository**: [github.com/l-velazquez/emilyboria](https://github.com/l-velazquez/emilyboria)

## 📞 Support

For questions or inquiries about this portfolio website, please reach out through the contact information available on the main website.

---

**Last Updated**: April 2026

Website built with ❤️ - Static HTML/CSS portfolio
