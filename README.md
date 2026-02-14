# G-Fitness - Premium Gym & Membership Platform

A professional, frontend-only gym website built for BIT Web Technology assignment. Features a modern, responsive design with Bootstrap 5, clean HTML5 semantic structure, and interactive JavaScript functionality.

## 🏋️ Project Overview

**Project Name:** G-Fitness  
**Type:** Frontend-only Web Application  
**Purpose:** BIT Web Technology Assignment  
**Technologies:** HTML5, CSS3, JavaScript, Bootstrap 5

## ✨ Features

### Core Features
- ✅ Fixed modern navigation bar with smooth scrolling
- ✅ Hero section with strong call-to-action
- ✅ 3 Membership pricing plans (Basic, Premium, Elite)
- ✅ Product showcase with 12+ gym products in grid layout
- ✅ Trainer showcase section with 8 professional trainers
- ✅ Testimonials carousel
- ✅ Contact form with JavaScript validation
- ✅ Modal popup for "Join Now" registration
- ✅ Back to top button
- ✅ Clean footer with social links
- ✅ Newsletter subscription

### Technical Features
- ✅ HTML5 semantic structure (header, nav, main, section, article, footer)
- ✅ Bootstrap 5 responsive layout
- ✅ Modern CSS (Flexbox/Grid)
- ✅ Google Fonts (Poppins)
- ✅ Clean, well-organized, commented code
- ✅ Accessibility features (aria-labels, alt text, proper headings)
- ✅ Cross-browser compatible
- ✅ Responsive for mobile, tablet, desktop
- ✅ Form validation with real-time feedback
- ✅ Smooth animations (AOS library)

## 📁 Project Structure

```
G-Fitness/
│
├── index.html              # Homepage with hero, features, pricing, products, trainers
├── membership.html         # Detailed membership plans & comparison table
├── products.html          # Full product catalog with filtering
├── trainers.html          # Trainer profiles with detailed modals
├── contact.html           # Contact form, map, and FAQ
│
├── css/
│   └── style.css          # Custom styles with modern design
│
├── js/
│   └── script.js          # JavaScript for validation and interactivity
│
├── images/                # Folder for local images (currently using CDN)
│
└── README.md             # This file

```

## 🎨 Design Features

### Color Scheme
- Primary: #ff6b35 (Orange)
- Secondary: #f7931e (Golden Orange)
- Dark: #1a1a1a
- Light: #f8f9fa

### Typography
- Font Family: Poppins (Google Fonts)
- Clean, modern, and highly readable

### Responsive Breakpoints
- Mobile: < 576px
- Tablet: 576px - 991px
- Desktop: > 992px

## 🚀 Getting Started

### Option 1: Open Directly
1. Navigate to the project folder
2. Double-click `index.html` to open in your default browser

### Option 2: Use Live Server (Recommended)
1. Open the project folder in VS Code
2. Install "Live Server" extension
3. Right-click `index.html` and select "Open with Live Server"

### Option 3: Local Web Server
```bash
# Using Python 3
python -m http.server 8000

# Using Node.js (http-server)
npx http-server
```

Then open `http://localhost:8000` in your browser.

## 📄 Pages Overview

### 1. Home Page (index.html)
- Hero section with compelling CTA
- Feature highlights (4 cards)
- Membership pricing (3 plans)
- Product preview (6 products)
- Trainer preview (4 trainers)
- Testimonials carousel
- Contact section preview
- Full footer

### 2. Membership Page (membership.html)
- Hero header
- 3 detailed pricing cards
- Feature comparison table
- FAQ accordion
- Call-to-action section

### 3. Products Page (products.html)
- Hero header
- Category filtering buttons
- 12 product cards in grid
- Product categories: Equipment, Supplements, Accessories
- Call-to-action section

### 4. Trainers Page (trainers.html)
- Hero header
- 8 trainer cards with profiles
- Detailed trainer modals (4 featured trainers)
- Social media links
- Why choose our trainers section
- Call-to-action section

### 5. Contact Page (contact.html)
- Hero header
- 4 contact info cards (Location, Phone, Email, Hours)
- Detailed contact form
- Google Maps embed
- FAQ accordion
- Call-to-action section

## 🔧 JavaScript Features

### Form Validation
- Real-time validation on contact form
- Real-time validation on join modal
- Email format validation
- Phone number format validation
- Minimum character requirements
- Visual feedback (green/red borders)

### Interactive Elements
- Smooth scrolling navigation
- Active nav link highlighting
- Back to top button (appears on scroll)
- Modal popups
- Product category filtering
- Carousel controls
- Newsletter subscription
- Mobile-responsive navigation

## ♿ Accessibility Features

- Semantic HTML5 elements
- ARIA labels on interactive elements
- Alt text on all images
- Proper heading hierarchy (h1-h5)
- Keyboard navigation support
- Focus styles for form elements
- High contrast text
- Screen reader friendly

## 📱 Responsive Design

### Mobile (< 576px)
- Stacked layout
- Hamburger menu
- Touch-friendly buttons
- Optimized images
- Reduced padding

### Tablet (576px - 991px)
- 2-column layouts
- Adjusted navigation
- Optimized spacing

### Desktop (> 992px)
- Full multi-column layouts
- Hover effects
- Fixed navigation
- Parallax effects

## 🎯 Assignment Requirements Checklist

✅ **HTML5 Semantic Structure**
- header, nav, main, section, article, footer used throughout

✅ **Bootstrap 5 for Responsive Layout**
- Container, row, col system
- Responsive utilities
- Bootstrap components (navbar, cards, modal, accordion, carousel)

✅ **Modern CSS (Flexbox/Grid)**
- CSS Grid for product layouts
- Flexbox for alignment
- Custom CSS variables
- Media queries

✅ **Google Fonts**
- Poppins font family implemented

✅ **Clean, Well-Organized Code**
- Proper indentation
- Comprehensive comments
- Consistent naming conventions

✅ **Accessibility Features**
- ARIA labels throughout
- Alt text on images
- Semantic headings

✅ **Cross-Browser Compatible**
- Works on Chrome, Firefox, Safari, Edge

✅ **Responsive Design**
- Mobile-first approach
- Tested on all device sizes

✅ **No Backend/Database**
- Pure frontend implementation
- Console logs for form submissions

## 🖼️ Images

Currently using Unsplash CDN for images. To use local images:

1. Download images from Unsplash
2. Place them in the `images/` folder
3. Update image paths in HTML files from CDN URLs to local paths:
   ```html
   <!-- Change from: -->
   <img src="https://images.unsplash.com/..." alt="...">
   
   <!-- To: -->
   <img src="images/your-image.jpg" alt="...">
   ```

## 🌐 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📝 Notes for Instructor

### Key Implementation Highlights:

1. **Semantic HTML5**: All pages use proper HTML5 semantic elements (header, nav, main, section, article, footer, aside)

2. **Bootstrap 5**: Extensive use of Bootstrap grid system, components, and utilities while maintaining custom styling

3. **Modern CSS**: 
   - CSS custom properties (variables)
   - Flexbox and Grid
   - Smooth transitions and animations
   - Mobile-first responsive design

4. **JavaScript Features**:
   - Form validation with real-time feedback
   - Smooth scrolling
   - Dynamic filtering
   - Modal interactions
   - Event listeners for user interactions

5. **Accessibility**:
   - ARIA labels on all interactive elements
   - Alt text on all images
   - Proper heading hierarchy
   - Keyboard navigation support
   - Focus indicators

6. **Best Practices**:
   - Clean, commented code
   - Consistent naming conventions
   - Organized file structure
   - Cross-browser compatibility
   - Performance optimization

## 📧 Contact

For questions about this project:
- Email: info@gfitness.com
- Phone: +1 (555) 123-4567

## 📄 License

This project is created for educational purposes as part of BIT Web Technology assignment.

---

**Developed by:** Samrat  
**Date:** February 2026  
**Assignment:** BIT Web Technology - Frontend Web Development  
**Grade:** [To be filled by instructor]
#   G - F i t n e s s  
 