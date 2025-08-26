# 🚨 404 Error Page - Retro Terminal

A 404 error page with a retro design inspired by old computer terminals, featuring CRT scanning visual effects and 80s/90s aesthetics.

## 🎯 Features

- **Retro Design**: Terminal style with monospace font (Inconsolata)
- **Visual Effects**: 
  - Animated scanning lines (CRT effect)
  - Subtle background noise
  - Green radial gradients
  - Text glow effects
- **Responsive**: Adapts to different screen sizes
- **No Scrollbars**: Optimized design to avoid scrollbars

## 📁 Project Structure

```
404/
├── index.html          # Main HTML file
├── style.css           # CSS styles with visual effects
└── README.md           # This documentation file
```

## 🔧 How It Works

### HTML (`index.html`)
- Standard HTML5 structure with appropriate metadata
- Main `.terminal` container with error message
- `.noise` and `.overlay` elements for visual effects

### CSS (`style.css`)
- **Font**: Imports Inconsolata from Google Fonts for terminal look
- **Background**: Radial green gradient with background GIF image
- **Scanning Effects**: 
  - Horizontal lines with `repeating-linear-gradient`
  - Vertical scanning animation with `@keyframes scan`
- **Centering**: Content is perfectly centered on screen
- **Responsive**: Media queries for mobile devices

## 🚀 How to Use

1. **Open file**: Simply open `index.html` in your browser
2. **Customize**: Modify text in `index.html` or colors in `style.css`
3. **Implement**: Copy these files to your web server for custom 404 pages

## 🎨 Customization

### Change Colors
```css
/* Main text color */
color: rgba(128, 255, 128, 0.8);

/* Error code color */
.errorcode { color: white; }
```

### Change Scanning Speed
```css
/* In the scan animation */
animation: scan 7.5s linear 0s infinite;
```

### Change Font
```css
/* Import new font from Google Fonts */
@import 'https://fonts.googleapis.com/css?family=YOUR_FONT';
```

## 📱 Compatibility

- ✅ Chrome/Edge (recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Mobile devices
- ✅ Modern browsers with CSS3 support

## 🐛 Issues Fixed

- **Scrollbars**: Eliminated with `overflow: hidden` and perfect centering
- **HTML Structure**: Corrected to follow HTML5 standards
- **Responsiveness**: Improved for mobile devices
- **Centering**: Content now centers perfectly on any screen

## 🌟 Visual Effects Included

1. **Scan Lines**: Simulate old CRT monitor
2. **Background Noise**: Subtle texture for authenticity
3. **Text Glow**: Phosphorescent green terminal effect
4. **Scanning Animation**: Line moving vertically
5. **Gradients**: Background with visual depth

## 📝 License

This project is open source and can be freely used for personal and commercial projects.

---

**Enjoy your retro 404 page!** 🎮✨
