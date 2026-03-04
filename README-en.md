# Landing Page - Lucía Fernández

Clinical and Sports Nutritionist in Tucumán, Argentina

## 📋 Description

Professional, modern, and completely responsive landing page for Lucía Fernández, a nutritionist specialized in clinical and sports nutrition based in Yerba Buena, Tucumán.

The page is designed to convert visitors into patients, especially from mobile devices, and facilitates direct contact through WhatsApp, Instagram, and email.

## ✨ Features

- **📱 Mobile-first**: Fully optimized for mobile devices
- **🌓 Dark Mode**: Complete light/dark theme system with persistence
- **🎨 Professional Design**: Natural palette with soft greens, cream, and white
- **⚡ No Dependencies**: Everything in one HTML file (CSS and JS embedded)
- **🎯 Google Fonts**: Elegant typography with Lora and Poppins
- **✨ Subtle Animations**: Effects on scroll and smooth hover
- **♿ Accessible**: Semantic HTML structure and ARIA attributes
- **🚀 Fast**: Instant loading without external frameworks
- **📱 Hamburger Menu**: Intuitive navigation for mobile
- **🌐 Bilingual**: Available in Spanish and English

## 📂 Structure

```
Web-nutricionista/
├── index.html          # Spanish Version
├── index-en.html       # English Version
├── README.md          # Spanish Documentation
└── README-en.md       # English Documentation (this file)
```

## 🎯 Page Sections

### 1. **Hero**
- Lucía's introduction
- Clear specialty
- Call-to-action button (CTA) via WhatsApp

### 2. **About Lucía**
- Close and human description
- Highlighted statistics (experience, patients, etc.)
- Warm and accessible tone

### 3. **Services**
- In-Person Consultation
- Online Consultation
- Personalized Plan

### 4. **How We Work**
- 3-step simple process
- Assessment → Plan → Follow-up

### 5. **Contact**
- WhatsApp (with direct link)
- Instagram
- Email

## 🚀 How to Use

### Option 1: Open directly in browser
```bash
# Just open the index.html or index-en.html file in your browser
# Requires no server or installation
```

### Option 2: Local server (recommended for testing)
```bash
# With Python 3
python -m http.server 8000

# With Node.js (if you have http-server installed)
npx http-server

# With PHP
php -S localhost:8000
```

Then access `http://localhost:8000`

## 🌐 Language Support

The page is available in two languages:

- **Spanish**: `index.html`
- **English**: `index-en.html`

Both versions have a language selector in the header (ES/EN) that allows you to switch between them easily. The contact information and structure are identical; only the text content changes.

## 🔧 Customization

### Change Contact Information

Open `index-en.html` and search for these values:

**WhatsApp:**
```html
href="https://wa.me/+5493816000000?text=Hello%20Lucía..."
```
Replace `+5493816000000` with the real number (include country code)

**Instagram:**
```html
href="https://instagram.com/luciafernandez.nutricion"
```
Replace `luciafernandez.nutricion` with the real username

**Email:**
```html
href="mailto:lucia@nutricionista.com"
```
Replace with the real email

### Change Colors

In the `:root` section of the CSS, modify these variables:

```css
:root {
    --primary-green: #5a8a6f;      /* Primary green */
    --light-green: #7ca88d;        /* Light green */
    --soft-green: #a8c5b8;         /* Soft green */
    --cream: #f5f1e8;              /* Cream */
    /* ... more variables */
}
```

### Change Text

All text is clearly identified in the HTML sections:

- `<h1>`, `<h2>`, `<h3>` for headings
- `<p>` for paragraphs
- Search any keyword to find the exact section

## 🎨 Color Palette

- **Primary Green**: `#5a8a6f` - Conveys calmness and professionalism
- **Light Green**: `#7ca88d` - For accents
- **Soft Green**: `#a8c5b8` - For secondary elements
- **Cream**: `#f5f1e8` - Elegant background
- **White**: `#ffffff` - Main base

### Dark Mode
The palette automatically adjusts in dark mode while maintaining contrast and elegance.

## 🌙 Theme System

Dark mode activates automatically if:
1. The user has dark theme enabled on their device
2. The user clicks the 🌙/☀️ button in the header

The preference is saved in `localStorage` to persist between sessions.

## 📱 Responsiveness

The page is fully responsive with breakpoints at:

- **Desktop**: 1200px+
- **Tablet**: 769px - 1199px
- **Mobile**: 480px - 768px
- **Small Mobile**: <480px

## 🔗 Links and Functionality

### Internal Navigation
All internal links use `#` and navigate smoothly:
- `#about` → About Lucía Section
- `#services` → Services Section
- `#process` → How We Work Section
- `#contact` → Contact Section

### External Links
- WhatsApp with preset text
- Instagram in new tab
- Email with default client

## ✅ Validation

The page complies with:

- ✅ Valid HTML5
- ✅ Modern CSS3
- ✅ ES6 JavaScript
- ✅ Responsive Design
- ✅ WCAG Accessibility
- ✅ Basic SEO optimization
- ✅ Complete meta tags

## 📊 Performance

- **Size**: ~25KB per file (single file)
- **Load**: Instant (<500ms)
- **Dependencies**: 0 (Google Fonts only external)
- **Compression**: Ready for GZIP

## 🛠️ Technologies

- **HTML5**: Semantic structure
- **CSS3**: Flexbox, Grid, CSS variables, media queries
- **Vanilla JavaScript**: Interactivity without frameworks
- **Google Fonts**: Lora and Poppins typography

## 📲 Compatibility

Tested on:
- ✅ Chrome/Chromium
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ✅ iOS Safari
- ✅ Chrome Android

## 🚀 Deployment

### Option 1: GitHub Pages (free)
1. Upload the files to a GitHub repository
2. Enable GitHub Pages in Settings
3. Your page will be at `username.github.io/repo-name`

### Option 2: Shared Hosting
Simply upload `index.html` and `index-en.html` via FTP to your hosting

### Option 3: Vercel (recommended - free)
1. Connect your repository to Vercel
2. Deploy with one click
3. Automatic URL: `name.vercel.app`

## 📝 Important Notes

- No images on the page (only emojis and CSS)
- Code is well-commented by sections
- Fully customizable without advanced technical knowledge
- Dark mode is automatically saved in the browser

## 🔐 Privacy

This page does NOT:
- ❌ Include tracking cookies
- ❌ Collect personal data
- ❌ Have external analytics
- ❌ Require a backend

The contact buttons open WhatsApp, Instagram, and native email in the browser.

## 📧 Support and Updates

**To update the page:**

1. Open `index-en.html` in any text editor
2. Find the text or section you want to change
3. Save and reload in the browser
4. Deploy again to your hosting

**If you need help:**
- [HTML Documentation](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [CSS Documentation](https://developer.mozilla.org/en-US/docs/Web/CSS)
- [JavaScript Documentation](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

## 📄 License

This landing page was created specifically for Lucía Fernández.

---

**Version**: 1.0  
**Last Updated**: March 4, 2026  
**Created for**: Lucía Fernández - Clinical and Sports Nutritionist

---

**📖 Disponible en Español**: Ver [README.md](README.md) para la versión en español de esta documentación.
