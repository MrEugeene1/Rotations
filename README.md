
# ✨ 3D Rotating Container Animation

A stunning, modern web project featuring a smooth 3D rotating container with dynamic color transitions and elegant animations.

---

## 🎨 Features

- **3D Rotation Effects** - Smooth X and Y axis rotations creating a mesmerizing visual effect
- **Color Transitions** - Dynamic background color changes throughout the animation sequence
- **Responsive Design** - Centered container that adapts to different screen sizes
- **Infinite Animation** - Continuous looping animation for a hypnotic effect
- **Lightweight & Fast** - Pure HTML and CSS with no external dependencies

---

## 🚀 Quick Start

1. **Open in Live Server**
   - Launch the `index.html` file with VS Code Live Server extension
   - Watch the animated container come to life!

2. **File Structure**
   ```
   📁 Trials/
   ├── 📄 index.html      (HTML structure)
   ├── 🎨 styles.css      (Animations & styling)
   └── 📖 README.md       (This file)
   ```

---

## 🎯 How It Works

### HTML Structure
The project features a simple, semantic HTML5 structure:
- Proper DOCTYPE and meta tags for responsive design
- Single `.container` div that serves as the animated element
- Clean, accessible markup

### CSS Animation

The magic happens in the `@keyframes myGlow` animation:

| Keyframe | Rotation | Color |
|----------|----------|-------|
| **0%** | rotateX(0°) rotateY(0°) | Blue (#3498db) |
| **30%** | rotateX(90°) rotateY(0°) | Blue (#3498db) |
| **60%** | rotateX(180°) rotateY(180°) | Red (#e74c3c) |
| **100%** | rotateX(360°) rotateY(0°) | Orange (#ea9605) |

---

## 🎨 Customization Guide

### Change Colors
Edit the `background-color` values in `styles.css`:
```css
@keyframes myGlow {
    0% {
        background-color: #YOUR_COLOR_HERE;
    }
    /* ... */
}
```

### Adjust Animation Speed
Modify the animation duration (currently 2 seconds):
```css
animation: myGlow 2s infinite;  /* Change 2s to desired duration */
```

### Resize Container
Update width and height in the `.container` class:
```css
.container {
    width: 300px;   /* Change width */
    height: 100px;  /* Change height */
}
```

### Modify Rotation Angles
Customize the rotation values in the `@keyframes`:
```css
transform: rotateX(45deg) rotateY(45deg);  /* Adjust angles */
```

---

## 💻 Technologies Used

- **HTML5** - Semantic markup and structure
- **CSS3** - 3D transforms and animations
- **Live Server** - Local development and preview

---

## 🌟 Tips & Best Practices

✅ Use Chrome/Edge for best 3D transform support  
✅ Test on different devices for responsive behavior  
✅ Adjust animation timing for slower/faster effects  
✅ Experiment with different color palettes  
✅ Try adding multiple elements for complex animations  

---

## 📝 License

This project is open source and free to use, modify, and distribute.

---

## 🎬 Preview

Experience the smooth 3D rotation and color transitions by running the project with Live Server. The container continuously rotates on both X and Y axes while transitioning through a beautiful color palette.

---

**Happy Coding!** 🚀✨
