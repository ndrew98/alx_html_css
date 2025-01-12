# Headphones Website Project

![Project Banner](images/headphones_hero_1.jpg)

A fully responsive, modern website for a headphones brand built with pure HTML and CSS. The project demonstrates mobile-first design principles, CSS animations, and accessibility best practices.

## 🎯 Project Overview

This project showcases a professional landing page with:
- Responsive design for mobile, tablet, and desktop views
- Pure CSS animations and transitions
- Hamburger menu navigation (no JavaScript)
- Custom form styling
- Image-based pentagon shapes for statistics
- Social media integration

## 📱 Responsive Breakpoints

The website is fully responsive with the following breakpoints:

| Device  | Width (px) | Description |
|---------|------------|-------------|
| Mobile  | < 768px    | Single column layout, hamburger menu |
| Tablet  | 768-1023px | 2-column grid, expanded navigation |
| Desktop | ≥ 1024px   | 4-column grid, full navigation |

## 🎨 Design Features

### Header Section
- Full-width hero image
- Animated hamburger menu
- Call-to-action button
- Responsive text sizing

### What We Do Section
- Icon grid layout
- Custom icons
- Responsive spacing
- Centered content

### Results Section
- Pentagon image backgrounds
- Percentage statistics
- Dark background
- Grid layout

### Contact Section
- Custom form styling
- Floating labels
- Validation states
- Submit button styling

## 📁 Project Structure

```
headphones/
│
├── index.html
├── styles.css
├── README.md
│
├── images/
│   ├── headphones_hero_1.jpg
│   ├── logo.png
|   ├── headphones_hero_1.jpg
│   ├── pentagone.png
│   └── social-icons/
│       ├── fb.png
│       ├── twitter.png
│       └── insta.png
├── Pictures/
│   ├── hearing.png
│   ├── logo_footer.png
│   ├── media.png
│   ├── play.png
│   ├── sound.png
```

## 🛠️ Technical Details

### HTML Structure
- Semantic HTML5 elements
- Proper ARIA labels
- Organized section structure
- Clean, readable code

### CSS Features
- CSS Custom Properties (variables)
- Mobile-first media queries
- BEM naming convention
- Pure CSS animations

### Key CSS Components:
```css
/* Custom Properties */
:root {
    --color-primary: #FF6565;
    --color-dark: #071629;
    --color-white: #FFFFFF;
    --max-width: 1000px;
}

/* Responsive Container */
.container {
    width: 100%;
    max-width: var(--max-width);
    margin: 0 auto;
    padding: 0 1rem;
}

/* Mobile Navigation Toggle */
.nav__toggle:checked ~ .nav__menu {
    transform: translateY(0);
}
```

## 📱 Screenshots

### Mobile View
[Mobile Screenshot Placeholder](/Three_screens/01_headphones_mobile@2x.png)

### Tablet View
[Tablet Screenshot Placeholder](/Three_screens/01_headphones_tablet@2x.png)

### Desktop View
[Desktop Screenshot Placeholder](/Three_screens/01_headphones_desktop@2x.png)

## ✨ CSS Animations

The project includes several smooth animations:
- Menu toggle transitions
- Button hover effects
- Form label animations
- Opacity transitions

## 🚀 Getting Started

1. Clone the repository:
```bash
git clone https://github.com/ndrew98/alx_html_css/headphones.git
```

2. Open `index.html` in your browser

3. No build process required - pure HTML and CSS!

## 💻 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## ♿ Accessibility

- Semantic HTML structure
- ARIA labels where needed
- Proper heading hierarchy
- Keyboard navigation support
- Screen reader friendly

## 📈 Performance

- Optimized images
- Minimal CSS
- No JavaScript dependencies
- Fast loading times


## 🙋‍♂️ Author

[Andrew Laryea]
- GitHub: [@ndrew98](https://github.com/ndrew98)


## 🎉 Acknowledgments

- Design inspiration from Figma template provided by Alx
- Icons from [ALX]
- Images from [ALX]
