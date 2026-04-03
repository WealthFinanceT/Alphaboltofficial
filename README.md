# Quadri Isiaka - Personal Portfolio vCard

A fully customized, responsive personal portfolio website showcasing web development, graphic design, motion graphics, and blockchain expertise.

## ✨ Features

### Core Sections
- **About**: Professional overview with services, testimonials with auto-switching carousel, and client logos
- **Resume**: Work experience and skills timeline
- **Portfolio**: Filterable project gallery with web development, graphic design, and motion graphics (includes embedded videos)
- **Blog**: 6 full-length blog articles on design, development, motion graphics, and UI/UX
- **Contact**: Interactive map (Surulere, Lagos), contact form with email integration

### Customizations Applied
- **Color Scheme**: Purple/Green gradient theme (primary: hsl(270, 85%, 55%), secondary: hsl(145, 75%, 45%))
- **Services**: Web Developer, Graphics Designer, Motion Graphic Designer, Blockchain Developer
- **Testimonials**: Auto-rotating carousel with "see more" modal for full testimonials (Emily Evans, Henry Williams, others)
- **Blog Pages**: 
  - Design conferences in 2026 (linked externally)
  - Best fonts every designer (linked externally)
  - Design digest #80 (blog-3.html)
  - UI interactions of the week (blog-4.html)
  - The forgotten art of spacing (blog-5.html)
  - Motion graphics trends (blog-6.html)
- **Portfolio**: Video embed for motion graphics projects, multiple project categories
- **Mobile Responsive**: Optimized for all device sizes with dedicated mobile CSS

## 📂 Project Structure

```
index.html              # Main portfolio page (all sections in one)
blog-3.html            # Design digest #80 full article
blog-4.html            # UI interactions full article
blog-5.html            # Spacing in design full article
blog-6.html            # Motion graphics trends full article
README.md              # This file

assets/
├── css/
│   └── style.css      # All styling (purple/green theme, responsive)
├── js/
│   └── script.js      # Interactivity (testimonials, contact form, navigation)
└── images/
    ├── my-avatar.png
    ├── blog-1.jpg to blog-6.jpg
    ├── project-*.png, *.jpg (portfolio items)
    ├── avatar-*.png (testimonials)
    ├── logo-*.png (client logos)
    ├── icon-*.svg (service icons)
    └── motion 1.mp4, motion 3.MP4 (video files)
```

## 🚀 How to Use

### Open Locally
Simply double-click `index.html` in your file explorer to open in default browser.

### Run with Local Server
```bash
# Windows PowerShell
cd "c:\Users\Admin\Downloads\vcard\my portfolio"
python -m http.server 8000

# Then visit http://localhost:8000 in browser
```

## 📋 Customization Guide

### Edit Content
- **Profile Info**: Edit sidebar section in `index.html` (lines ~45-50)
- **Services**: Modify services list (line ~300+)
- **Portfolio Items**: Add/remove projects in portfolio section
- **Blog Posts**: Create new `blog-X.html` files following the template of blog-3.html
- **Testimonials**: Update testimonials HTML with new data attributes

### Change Colors
Edit CSS variables in `assets/css/style.css` (top of file ~line 20):
```css
--purple-1: hsl(270, 85%, 55%);   /* Primary purple */
--green-1: hsl(145, 75%, 45%);    /* Primary green */
```

### Update Contact Info
- **Email**: Change in `index.html` (line ~75) and `assets/js/script.js` (line ~200)
- **Phone**: Update in sidebar contacts
- **Map Location**: Edit iframe src in contact section (line ~1265)

## 📞 Contact Information

**Email**: princeholufreshgold@gmail.com  
**Phone**: +2347065552478  
**WhatsApp**: +2349126341303  
**Telegram**: https://t.me/alphaboltarts  
**Twitter/X**: https://x.com/alphaboltt  
**Instagram**: https://www.instagram.com/alphaboltt  

**Location**: Surulere, Lagos, Nigeria

## 🎯 Technical Details

### Technologies Used
- **HTML5**: Semantic structure and forms
- **CSS3**: Custom properties, gradients, flexbox, grid, media queries
- **JavaScript ES6+**: DOM manipulation, event listeners, form handling
- **IonIcons**: Icon library for UI elements
- **OpenStreetMap**: Embedded interactive map
- **SVG**: Custom service icons

### Browser Support
- Chrome/Edge: ✅
- Firefox: ✅
- Safari: ✅
- Mobile browsers: ✅

### Responsive Breakpoints
- **Mobile**: < 768px (single column, optimized touch targets)
- **Tablet**: 768px - 1024px (2-column layouts)
- **Desktop**: 1024px+ (full multi-column layout)

## 🔧 Features Implemented

✅ Sidebar with collapsible contacts  
✅ Navbar with smooth section switching  
✅ Auto-rotating testimonials carousel with pause on hover  
✅ Portfolio filter by category (Web Dev, Graphic Design, Motion Graphics)  
✅ Blog with full-page article links  
✅ Contact form with email sending (mailto protocol)  
✅ Embedded Surulere, Lagos map  
✅ Dark theme with gradient accents  
✅ Mobile-first responsive design  
✅ Modal popups for testimonial expansion  
✅ Video support in portfolio  

## 📝 Recent Updates

- ✨ Added full blog pages (blog-3.html - blog-6.html) with complete articles
- 🎨 Updated color scheme to purple/green gradient family
- 🗺️ Embedded Surulere, Lagos map in contact section
- 📧 Implemented contact form with email integration
- 🎬 Added video embed support for motion graphics projects
- 📱 Enhanced mobile responsiveness with dedicated CSS media queries
- 🔄 Implemented auto-rotating testimonials with speed control
- ➕ Added "see more" buttons to all testimonials
- 🎯 Full customization of services, skills, and portfolio items

## 📄 License

This project is customized from the original vCard template by codewithsadee.
For your use: Reference original repo if redistributing.

