# BrightNest - A Home That Understands You

A modern, highly interactive landing page for a smart home brand called BrightNest. The design combines neo-brutalist and neo-futurist aesthetics with premium scroll animations and glassmorphic UI elements.

## 🎨 Design Philosophy

**Soft Futurism + Neo-Brutalism**: The interface presents advanced technology in a warm, human-centric way with:
- Clean, squared borders and bold shadows
- Cream/white backgrounds with black and blue text
- Minimalist glassmorphic cards with 10px backdrop blur
- Premium spacing and typography
- Emotion-aware design language

**Brand Tagline**: *"A Home That Understands You"*

## ✨ Features

### Core Sections
1. **Hero Section** - Full-viewport banner with hero image background (30% opacity), floating mode cards, and CTA buttons
2. **How It Works** - 3-step process visualization with connecting gradient lines
3. **Features Grid** - 5 intelligent features with icons and descriptions
4. **Products Section** - 6 product cards with images, pricing, and features
5. **Interactive Demo** - Mood-based environment simulator (Relax/Focus/Sleep modes)
6. **Ecosystem** - Connected device network visualization
7. **Why BrightNest** - Unique value propositions
8. **Testimonials** - User reviews and feedback
9. **Footer** - Brand info, links, and social icons

### Premium Animations & Interactions
- ✓ Scroll-reveal animations with Intersection Observer
- ✓ Staggered product card animations
- ✓ Parallax hero background effect
- ✓ Dynamic scroll-triggered scale effects
- ✓ Floating card animations with sine-wave movement
- ✓ Button ripple effects on press
- ✓ Smooth cubic-bezier transitions
- ✓ GPU-accelerated 60fps animations

### Design System
- **Primary Color**: `#1c2e4a` (Dark Blue - trust, intelligence)
- **Accent Teal**: `#00d4d4` (highlights, interactive states)
- **Accent Purple**: `#6946ff` (subtle gradients)
- **Background**: `#fefdfb` (Cream/Off-white)
- **Border Radius**: 0px (squared, neo-brutalist)
- **Shadows**: 8-12px offset with soft opacity

## 📁 Project Structure

```
UIUX Hackathon/
├── index.html              # Main landing page file
├── README.md              # This file
├── logo.png               # Brand logo (70px height)
├── h1.jpg                 # Hero section background image
├── hero.jpg               # Alternative hero image
├── in between.jpg         # Bundle card image
├── smart light.jpg        # Smart Lighting Hub product image
├── thermostat.jpg         # Smart Thermostat X product image
├── camera.jpg             # Security Camera Pro product image
├── voice.jpg              # Voice Assistant Pro product image
└── central hub.jpg        # BrightNest Hub Central product image
```

## 🚀 Getting Started

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- No build tools or dependencies required
- Pure HTML, CSS, and JavaScript

### Installation
1. Clone or download the project folder
2. Ensure all image files are in the same directory as `index.html`
3. Open `index.html` in your web browser

### File Sizes & Formats
- **Logo**: PNG format (recommended: 200x70px or higher)
- **Hero Image** (h1.jpg): JPG format (recommended: 1920x1080px or higher)
- **Product Images**: JPG format (recommended: 600x400px minimum)

## 🎯 Interactive Elements

### Demo Section
The mood selector allows users to experience how BrightNest adapts to different states:
- **Relax Mode** 😌: Dimmed lights, calming music, aromatherapy
- **Focus Mode** 🧠: Cool white light, focus playlist, notifications muted
- **Sleep Mode** 🌙: Warm amber glow, sleep sounds, lowered temperature

### Product Cards
- Hover effects with shadow transformation
- Product images with object-fit cover
- Feature lists with checkmark indicators
- Call-to-action buttons

### Floating Cards (Hero)
- Continuous smooth floating animation
- Hover scaling and background color change
- Responsive layout (hidden on mobile)

## 🎭 CSS Variables (Customizable)

Edit `:root` in the `<style>` section to customize:
```css
--primary: #1c2e4a;           /* Primary dark blue */
--secondary: #0f3d66;         /* Darker shade of primary */
--accent-teal: #00d4d4;       /* Accent color */
--accent-purple: #6946ff;     /* Secondary accent */
--bg-light: #fefdfb;          /* Background color */
--text-dark: #0a0a0a;         /* Main text color */
--text-soft: #3a3a3a;         /* Secondary text color */
```

## 📱 Responsive Design

The landing page is fully responsive with breakpoints:
- **Desktop**: Full layout with all features visible
- **Tablet (≤1024px)**: Floating cards repositioned, stacked grid layouts
- **Mobile (≤768px)**: Single column layouts, adjusted typography
- **Small Mobile (≤480px)**: Compact spacing, reduced font sizes

## 🔧 JavaScript Features

### Scroll Animations
- `Intersection Observer API` for detecting element visibility
- `requestAnimationFrame` for smooth 60fps parallax effects
- Dynamic scale transforms based on scroll position

### Interactive Demo
- `activateMood()` function handles mood selection
- Dynamic CSS class switching for theme changes
- Real-time feedback text updates

### Performance Optimizations
- `will-change` property for GPU acceleration
- Debounced scroll handlers
- Efficient event delegation

## 📦 Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Grid, Flexbox, Animations, Backdrop Filters
- **Vanilla JavaScript** - No frameworks or dependencies
- **Google Fonts** - Poppins (headings) and Inter (body)
- **Font Awesome 6** - Icon library

## 🌐 Browser Support

- Chrome/Chromium 90+
- Firefox 88+
- Safari 14+
- Edge 90+

## 🎬 Animation Details

### Scroll Reveal
- Fade-up effect: opacity 0→1, translateY 30px→0
- Cubic-bezier easing: `(0.4, 0, 0.2, 1)`
- Observation threshold: 0.1 (10% visibility)

### Staggered Animations
- Product cards: 0.1s incremental delays
- Creates wave-like reveal effect
- Total sequence: 0.6s for all 6 cards

### Parallax Effects
- Hero background: `background-attachment: fixed`, 0.5x scroll speed
- Floating elements: Sine-wave motion with requestAnimationFrame
- Smooth cubic-bezier for all transitions

## 🎨 Design Highlights

### Neo-Brutalist Elements
- Sharp, squared corners (0px radius)
- Bold offset shadows (8-12px)
- Strong borders (2px)
- High contrast text

### Glassmorphism
- 10px backdrop blur
- Semi-transparent backgrounds (rgba)
- Subtle white borders
- Layered depth

### Premium Polish
- Consistent 9rem section spacing
- Generous padding on cards (2-3rem)
- Smooth color transitions
- Refined typography hierarchy

## 🔄 Customization Guide

### Changing Section Spacing
Edit section padding (currently 9rem):
```css
#section-name {
    padding: 9rem 0;  /* Change this value */
}
```

### Modifying Colors
Update CSS variables in `:root`:
```css
:root {
    --primary: #your-color;
}
```

### Updating Images
Replace image filenames in:
1. Hero: `url('h1.jpg')` in `.hero-background`
2. Product cards: `src="filename.jpg"` in product images
3. Logo: `src="logo.png"` in header

## 📧 Support

For questions or customizations, refer to the inline comments in the HTML file for detailed explanations of each section.

## 📄 License

This project is created for the UIUX Hackathon. Feel free to modify and use as needed.

---


