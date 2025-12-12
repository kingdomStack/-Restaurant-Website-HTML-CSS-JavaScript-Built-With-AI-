Here's the updated README with the link added to the "Quick Start" section:

# Élysée Restaurant Website

A modern, responsive website template for a fine dining French restaurant with elegant design and full functionality.

## 🍽️ Overview

Élysée Restaurant Website is a single-page, fully responsive HTML template designed for upscale restaurants. It features a sophisticated dark theme with gold accents, smooth animations, and interactive components to showcase a premium dining experience.

## ✨ Features

### Design & Layout
- **Responsive Design**: Fully responsive across all devices (mobile, tablet, desktop)
- **Modern Aesthetic**: Elegant dark theme with gold accents
- **Smooth Animations**: CSS transitions and keyframe animations
- **Custom Typography**: Cormorant Garamond for headings and Inter for body text
- **Hero Section**: Animated background with zoom effect

### Interactive Components
- **Mobile Navigation**: Hamburger menu for mobile devices
- **Menu Tabs**: Interactive menu categorization (Starters, Mains, Desserts, Wine)
- **Image Gallery**: Lightbox functionality with keyboard navigation
- **Reservation Form**: Fully validated booking form with real-time validation
- **Smooth Scrolling**: Anchor links with smooth scrolling behavior

### Sections
1. **Hero Section** - Introductory banner with call-to-action buttons
2. **About Section** - Restaurant philosophy and concept
3. **Menu Section** - Interactive food and drink menu with tabs
4. **Chef Section** - Executive chef profile and bio
5. **Gallery Section** - Restaurant ambiance and food photography
6. **Reservations Section** - Contact information and booking form
7. **Footer** - Contact details, hours, and social links

### Live Demo
🔗 **[View Live Demo](https://kingdomstack.github.io/-Restaurant-Website-HTML-CSS-JavaScript-Built-With-AI-/)** 🔗

## 🚀 Quick Start
1. **Clone or Download**
   ```bash
   git clone [repository-url]
   ```
   or download the ZIP file

2. **Open the File**
   Simply open `restaurant-website-template.html` in any modern web browser.

3. **No Dependencies Required**
   - All CSS is included in the `<style>` tag
   - All JavaScript is included in the `<script>` tag
   - External resources are loaded via CDN (Font Awesome, Google Fonts)

## 🛠️ Customization

### Easy Customizations

1. **Content Updates**:
   - Replace placeholder text with your restaurant information
   - Update menu items and prices
   - Change contact details (address, phone, email)

2. **Images**:
   - Replace Unsplash image URLs with your own images
   - Update hero background image (line ~155)
   - Replace gallery images (lines ~730-750)

3. **Colors**:
   Modify CSS variables in the `:root` selector (lines ~20-30):
   ```css
   :root {
       --primary-dark: #0a0a0a;
       --secondary-dark: #1a1a1a;
       --accent-gold: #c9a96e;
       --accent-light: #f5f5f5;
       --text-light: #ffffff;
       --text-gray: #a0a0a0;
   }
   ```

4. **Branding**:
   - Change restaurant name in the logo (line ~480)
   - Update footer text and copyright information

### Advanced Customizations

1. **Add New Menu Categories**:
   - Add new tab button in the menu-tabs div
   - Create corresponding menu section with items
   - Update JavaScript to handle the new tab

2. **Modify Form Fields**:
   - Add or remove form fields in the reservation section
   - Update validation logic in the JavaScript

3. **Add New Sections**:
   - Copy existing section structure
   - Add to HTML and CSS
   - Update navigation links

## 📱 Browser Compatibility

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome for Android)

## 🎨 Design Notes

### Typography Hierarchy
- **Headings**: Cormorant Garamond (300-700 weights)
- **Body Text**: Inter (300-600 weights)
- **Accents**: Font Awesome icons

### Color Scheme
- **Primary**: Dark background (#0a0a0a, #1a1a1a)
- **Accent**: Gold (#c9a96e) for highlights and buttons
- **Text**: White (#ffffff) and light gray (#a0a0a0)

### Layout Patterns
- **Grid System**: CSS Grid for responsive layouts
- **Flexbox**: For alignment and spacing
- **CSS Variables**: For consistent theming
- **Media Queries**: Mobile-first responsive design

## 🔧 Technical Details

### Structure
```
├── HTML Structure
│   ├── Header & Navigation
│   ├── Hero Section
│   ├── About Section
│   ├── Menu Section
│   ├── Chef Section
│   ├── Gallery Section
│   ├── Reservations Section
│   └── Footer
│
├── CSS Organization
│   ├── CSS Reset & Variables
│   ├── Typography
│   ├── Component Styles
│   └── Responsive Breakpoints
│
└── JavaScript Functions
    ├── Mobile Navigation Toggle
    ├── Menu Tab Switching
    ├── Gallery Lightbox
    ├── Form Validation
    └── Smooth Scrolling
```

### External Resources
- **Font Awesome 6.4.0** (Icons)
- **Google Fonts** (Cormorant Garamond, Inter)
- **Unsplash** (Placeholder images)

## 📝 Form Functionality

The reservation form includes:
- Real-time validation
- Required field checking
- Email format validation
- Date restriction (past dates disabled)
- Success message display
- Form reset after submission

## 🚀 Performance Features

- All CSS and JavaScript in single file for fast loading
- Optimized images via Unsplash CDN
- Minimal external dependencies
- Efficient JavaScript event handling

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/improvement`)
3. Commit changes (`git commit -am 'Add new feature'`)
4. Push to branch (`git push origin feature/improvement`)
5. Create a Pull Request

## 📄 License

This template is free to use for personal and commercial projects. Attribution is appreciated but not required.

## 🙏 Credits

- Design and Development: KindomStack
- Images: Unsplash 
- Icons: Font Awesome
- Fonts: Google Fonts
