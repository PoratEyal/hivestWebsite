# Hivest Website - Project Structure

## 📁 File Organization

```
hivestWebsite/
├── index.html              # Main HTML file
├── css/
│   └── styles.css         # All website styles
├── assets/
│   ├── logo2.png          # Site logo
│   ├── logoApp2.png       # App logo (legacy)
│   ├── previewed.png      # App screenshot (single phone)
│   └── previewed (1).png  # App screenshots (dual phones)
├── contact.html           # Contact page
├── privacy.html           # Privacy policy
├── terms.html            # Terms of service
└── delete.html           # Account deletion page
```

## 🎨 Styles Organization (css/styles.css)

The styles are organized into clear sections:

1. **Variables & Base Styles** - Color scheme and global styles
2. **Header** - Navigation and branding
3. **Hero Section** - Landing area with call-to-action
4. **Why Section** - Features showcase with phone mockups
5. **Testimonials Section** - User reviews grid
6. **Footer** - Site footer
7. **Responsive Design** - Media queries for mobile/tablet

## 📄 HTML Sections (index.html)

The main page consists of:

1. **Header** (`<header>`)
   - Logo and site name
   - Navigation links (Privacy, Terms, Delete, Contact)

2. **Hero Section** (`<main class="wrap">`)
   - Main title and subtitle
   - Download buttons (App Store & Google Play)
   - Featured testimonial
   - App screenshot

3. **Why Use Hivest Section** (`<section class="why-section">`)
   - Section title and description
   - Phone mockups showcase
   - Three feature cards:
     - Social Investment Feed
     - Compete on Leaderboards
     - Secure Portfolio Tracking

4. **Testimonials Section** (`<section class="testimonials-section">`)
   - Section title
   - Grid of 6 user testimonials
   - Each with 5-star rating, quote, and author initials

5. **Footer** (`<footer>`)
   - Copyright notice

## 🎯 Design System

### Colors
- **Primary Background**: `#0a0e1a`
- **Secondary Background**: `#161d2d` (Why Section)
- **Tertiary Background**: `#0d1520` (Testimonials)
- **Accent Cyan**: `#4cafef`
- **Accent Teal**: `#1ee3c2`
- **Text Color**: `#e8ecf4`
- **Muted Text**: `#8899aa`

### Typography
- **Font Family**: Inter, system-ui, -apple-system, Segoe UI, Roboto, Arial, sans-serif
- **Base Size**: 16px
- **Line Height**: 1.6

### Breakpoints
- **Desktop**: > 1024px
- **Tablet**: 641px - 1024px
- **Mobile**: ≤ 640px

## 🔧 Future Improvements

- [ ] Split CSS into multiple files (components, utilities, etc.)
- [ ] Add JavaScript for interactive features
- [ ] Consider using a CSS preprocessor (SASS/LESS)
- [ ] Implement a build system for optimization
- [ ] Add analytics tracking
- [ ] Optimize images for web

## 📝 Notes

- All external styles are now in `css/styles.css`
- HTML is clean and semantic
- Responsive design implemented for all screen sizes
- No JavaScript dependencies currently
- Images should be optimized for production use

