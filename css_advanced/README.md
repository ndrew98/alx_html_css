# 🎓 SmileSchool Website Documentation

[![Made with Love](https://img.shields.io/badge/Made%20with-❤-red.svg)](https://github.com/yourusername)
[![CSS](https://img.shields.io/badge/CSS-3-blue.svg)](https://www.w3.org/Style/CSS/)
[![HTML](https://img.shields.io/badge/HTML-5-orange.svg)](https://html.spec.whatwg.org/)
[![Figma](https://img.shields.io/badge/Figma-Design-purple.svg)](https://www.figma.com/)

## 🌟 Overview
SmileSchool is a modern, responsive educational website designed to provide smile tutorials and training. The website features a clean, professional design with multiple sections including a hero banner, course listings, testimonials, and membership information.

This assignment is an Alx task on the css_advanced session

## 📁 Project Structure

```bash
css_advanced/
├── 📄 index.html
├── 🎨 styles.css
├── 📸 Pictures/
│   ├── logo.png
│   ├── Object.png
│   ├── play.png
│   └── [other images...]
└── 📝 fonts/
    └── source-sans-pro/
        ├── SourceSansPro-Bold.otf
        ├── SourceSansPro-Regular.otf
        └── [other font files...]
```

## 🎨 Design System

### 🎯 Colors
| Color | Hex Code | Preview |
|-------|----------|---------|
| Primary Purple | `#C271FF` | ![#C271FF](https://via.placeholder.com/15/C271FF/000000?text=+) |
| Dark Background | `#071629` | ![#071629](https://via.placeholder.com/15/071629/000000?text=+) |
| White | `#FFFFFF` | ![#FFFFFF](https://via.placeholder.com/15/FFFFFF/000000?text=+) |
| Gray | `#979797` | ![#979797](https://via.placeholder.com/15/979797/000000?text=+) |

### ✍️ Typography
The website uses the beautiful Source Sans Pro font family:
- 🔤 Source Sans Pro Bold
- 🔤 Source Sans Pro Regular
- 🔤 Source Sans Pro Black
- 🔤 Source Sans Pro Light
- 🔤 Source Sans Pro SemiBold
- 🔤 Source Sans Pro ExtraLight
- 🔤 Source Sans Pro Italic variations

## 🧩 Components

### 📱 Header
- 🔝 Fixed position header with logo and navigation
- 🌫️ Transparent background
- 📱 Responsive navigation links

### 🦸‍♂️ Hero Section
- 🖼️ Full-screen background image
- 📍 Centered content with large heading
- 🔘 Register button with purple background
- ✨ Three-phrase highlight section

### 👨‍🏫 Pros Section
- 📊 Four-column grid layout
- 🎭 Circular profile images
- 👤 Name and title information
- ⚪ White text on dark background

### 💬 Testimonial Section
- 🟣 Purple background
- 📐 Two-column layout with image and quote
- 📱 Responsive design for smaller screens

### 🎥 Tutorial Cards
- 📊 Four-column grid layout
- ▶️ Image with play button overlay
- 📝 Title and description
- 👤 Author information
- ⭐ Star rating system
- ⏱️ Duration indicator

### 🎫 Membership Section
- 🌑 Dark background
- 📊 Four-column feature layout
- 📍 Centered content
- 🔘 Registration button

### ❓ FAQ Section
- 📐 Two-column grid layout
- ❔ Question and answer format
- 📍 Centered headings

### 🦶 Footer
- 🌑 Dark background
- 🎨 Logo and social media icons
- ©️ Copyright information

## 📱 Responsive Design

### 📏 Breakpoints
```css
/* 🖥️ Desktop */
@media (min-width: 1200px) {
    See Style.css
}

/* 💻 Tablet */
@media (max-width: 1199px) and (min-width: 768px) {
  .hero h1 {
      font-size: 64px;
  }

  .pros-cards,
  .tutorial-cards,
  .membership-grid {
      grid-template-columns: repeat(2, 1fr);
  }

  .testimonial-content {
      grid-template-columns: 1fr;
      text-align: center;
  }

  .faq-grid {
      grid-template-columns: 1fr;
  }
}


/* 📱 Mobile */
@media (max-width: 480px) {
  .hero-phrases {
      flex-direction: column;
      gap: 20px;
  }

  .pros-cards,
  .tutorial-cards,
  .membership-grid {
      grid-template-columns: 1fr;
  }
}
```

## 🚀 Getting Started

1. 📥 Clone the repository
```bash
git clone https://github.com/ndrew98/alx_html_css.git
```

2. 📁 Ensure all font files are in the correct directory
3. 🔍 Check image paths in HTML and CSS
4. 🌐 Open index.html in a browser

## ⭐ Best Practices

### 📝 HTML
- ✅ Semantic markup
- ✅ Proper heading hierarchy
- ✅ Accessible form elements
- ✅ Alt text for images

### 🎨 CSS
- ✅ CSS variables for theming
- ✅ Mobile-first approach
- ✅ Modular component styles
- ✅ Consistent naming conventions

## 🔮 Future Enhancements
1. 🔄 Add JavaScript functionality
2. 🔍 Implement course filtering
3. ▶️ Add video player functionality
4. 📱 Enhance mobile navigation
5. ✅ Add form validation
6. 🌓 Implement dark/light theme toggle

## 🤝 Contributing
Feel free to open issues and pull requests!


## 💖 Acknowledgments
- 🙏 Thanks to ALX for this Assignment , and platform to study
- 🎨 Design inspiration from a figma file:
https://www.figma.com/design/dyYL6Ku4WG7vsdpwvlcJZC/Homepage?node-id=0-1&p=f&t=qIkV4JJqOb927f0E-0
- 📚 Built with love for learning

---
Made with ❤️ by Andrew Laryea