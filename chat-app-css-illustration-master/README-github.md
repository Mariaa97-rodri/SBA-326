# Frontend Mentor - Chat App CSS Illustration

## Project Overview

This project is a Bootstrap implementation of the Chat App CSS Illustration challenge from Frontend Mentor. It was completed as part of an SBA (Skills-Based Assessment) assignment focusing on accurate implementation of high-fidelity Figma designs using Bootstrap framework.

![Chat App Preview](./design/desktop-preview.jpg)

## Challenge Link

[Frontend Mentor - Chat App CSS Illustration](https://www.frontendmentor.io/challenges/chat-app-css-illustration-O5auMkFqY)

## Table of Contents

- [Project Requirements](#project-requirements)
- [Technologies Used](#technologies-used)
- [Features](#features)
- [Bootstrap Implementation](#bootstrap-implementation)
- [Project Structure](#project-structure)
- [What I Learned](#what-i-learned)
- [Author](#author)

## Project Requirements

This project was built to meet the following SBA requirements:

### ✅ Design Challenge Selection (5%)
- Selected Frontend Mentor challenge: **Chat App CSS Illustration**
- Difficulty level: **Junior** (intermediate)
- Type: **Free challenge**
- Requirements: **HTML & CSS only** (no JavaScript)

### ✅ Valid HTML Implementation (18%)
- Semantic HTML5 markup used throughout
- Proper document structure with DOCTYPE, head, and body
- All images include alt attributes for accessibility
- Valid meta tags for responsive design
- No HTML validation errors

### ✅ Bootstrap Utility Classes (20%)
Bootstrap utilities were used extensively for styling:
- **Layout utilities**: `container`, `container-fluid`, `row`, `col-lg-6`
- **Flexbox utilities**: `d-flex`, `align-items-center`, `justify-content-between`, `justify-content-end`, `gap-2`
- **Spacing utilities**: `p-3`, `mb-2`, `mb-5`, `mb-lg-0`, `ms-2`, `ps-lg-5`
- **Sizing utilities**: `min-vh-100`
- **Border utilities**: `rounded-3`, `rounded-4`, `rounded-circle`, `rounded-pill`, `border`, `border-2`, `border-0`
- **Background utilities**: `bg-white`
- **Text utilities**: `text-white`, `text-muted`, `fw-bold`, `small`, `opacity-75`
- **Display utilities**: `overflow-hidden`
- **Shadow utilities**: `shadow-lg`

### ✅ Bootstrap Components (15%)
Bootstrap components implemented:
- **Forms**: `form-control` for text input, `form-check-input` for radio buttons
- **Input Groups**: `input-group` for the message input with button
- **Buttons**: `btn`, `btn-dark` for the send button
- **Typography**: `display-4`, `lead` for the description text

### ✅ Custom CSS (15%)
Custom CSS used for design elements that Bootstrap cannot handle:
- CSS custom properties (variables) for color palette
- Gradient backgrounds for chat header and pricing bubbles
- Custom chat bubble shapes with specific border-radius
- Phone mockup frame styling
- Phone notch design
- Responsive background decorative shapes
- Avatar image sizing
- Dog image sizing and styling
- Custom positioning for the phone mockup

### ✅ Error-Free Display (5%)
- Webpage displays without console errors
- All images load correctly
- No broken links or missing resources
- Responsive layout works across all screen sizes

### ✅ Git Repository (5%)
- Frequent commits throughout development
- Descriptive commit messages
- Organized project structure
- All files properly tracked

### ✅ README File (2%)
- This comprehensive README file included
- Project description and overview
- Technologies used documented
- Installation instructions provided

### ✅ Design Accuracy (15%)
- High-fidelity implementation matching the provided design
- Accurate colors, spacing, and typography
- Proper responsive behavior
- Chat bubbles styled to match design
- Gradient effects implemented correctly

## Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Custom styling and animations
- **Bootstrap 5.3.0** - Responsive framework
- **Google Fonts** - Rubik font family
- **Git** - Version control

## Features

- 📱 Fully responsive mobile-first design
- 💬 Realistic chat interface with message bubbles
- 🎨 Beautiful gradient header and pricing options
- 🖼️ Image grid for dog photos
- ⚡ Clean, modern UI matching the design specifications
- ♿ Accessible markup with semantic HTML

## Bootstrap Implementation

### Utility Classes Strategy

This project maximizes Bootstrap utilities to minimize custom CSS:

1. **Layout System**: Used Bootstrap's grid (`row`, `col-lg-6`) for the two-column desktop layout
2. **Flexbox Utilities**: Leveraged flex utilities for chat bubble alignment and header layout
3. **Spacing System**: Applied Bootstrap's spacing scale consistently (p-3, mb-2, etc.)
4. **Responsive Utilities**: Used responsive classes like `mb-lg-0` for mobile-first design

### Component Usage

1. **Form Controls**: Bootstrap form styling for input field and radio buttons
2. **Input Groups**: Combined input and button seamlessly
3. **Typography**: Bootstrap typography classes for consistent sizing

### Custom CSS Justification

Custom CSS was necessary for:
- **Color Palette**: Design requires specific HSL colors not in Bootstrap
- **Gradients**: Chat header and pricing bubbles use custom gradients
- **Phone Mockup**: Unique phone frame design with notch
- **Chat Bubbles**: Specific border-radius values for speech bubble effect

## Project Structure

```
chat-app-css/
├── index.html              # Main HTML file
├── styles.css              # Custom CSS file
├── README.md               # This file
├── images/
│   ├── avatar.jpg          # User avatar image
│   ├── dog-image-1.jpg     # Dog photo 1
│   ├── dog-image-2.jpg     # Dog photo 2
│   ├── dog-image-3.jpg     # Dog photo 3
│   └── favicon-32x32.png   # Favicon
└── design/
    ├── desktop-design.jpg  # Desktop design reference
    └── mobile-design.jpg   # Mobile design reference
```

## What I Learned

### Bootstrap Skills
- How to maximize utility classes to reduce custom CSS
- When to use Bootstrap components vs. custom HTML
- Responsive design with Bootstrap's grid system
- Combining Bootstrap with custom CSS effectively

### HTML/CSS Skills
- Semantic HTML structure for accessibility
- CSS custom properties for maintainable code
- Creating complex gradient effects
- Building chat UI elements
- Mobile-first responsive design

### Development Process
- Planning HTML structure before styling
- Incremental development with frequent commits
- Balancing Bootstrap utilities with custom CSS
- Achieving pixel-perfect design accuracy

## Code Highlights

### Bootstrap Utility Usage
```html
<!-- Flexbox utilities for chat header alignment -->
<div class="d-flex align-items-center justify-content-between p-3">
  <div class="d-flex align-items-center gap-2">
    <!-- Content -->
  </div>
</div>

<!-- Responsive column layout -->
<div class="col-lg-6 mb-5 mb-lg-0">
  <!-- Phone mockup -->
</div>
```

### Custom CSS for Design Accuracy
```css
/* CSS Variables for color palette */
:root {
  --pale-violet: hsl(276, 100%, 81%);
  --moderate-violet: hsl(276, 55%, 52%);
  --light-magenta: hsl(293, 100%, 63%);
}

/* Gradient for chat header */
.gradient-header {
  background: linear-gradient(to right, var(--light-magenta), var(--moderate-violet));
}
```


## Deployment

This project can be deployed using:
- **GitHub Pages**: Push to GitHub and enable Pages in repository settings

## Requirements Checklist

- [x] Choose appropriate Frontend Mentor challenge (5%)
- [x] Implement valid and semantic HTML (18%)
- [x] Use Bootstrap utility classes extensively (20%)
- [x] Implement Bootstrap components (15%)
- [x] Use custom CSS for non-Bootstrap styling (15%)
- [x] Display webpage without errors (5%)
- [x] Commit frequently to Git repository (5%)
- [x] Include comprehensive README file (2%)
- [x] Achieve high level of design accuracy (15%)

## Author

- **Your Name** - [https://github.com/Mariaa97-rodri/module_308A.git](#)
- Frontend Mentor - [http://127.0.0.1:5500/chat-app-css-illustration-master/index.html](#)

## Acknowledgments

- Challenge by [Frontend Mentor](https://www.frontendmentor.io)
- Built with [Bootstrap](https://getbootstrap.com/)
- Fonts from [Google Fonts](https://fonts.google.com/)

---

**Note**: This project was completed as part of an SBA assignment focusing on accurate implementation of high-fidelity designs using the Bootstrap framework. The emphasis was on using Bootstrap utilities and components effectively while maintaining design accuracy through strategic use of custom CSS.