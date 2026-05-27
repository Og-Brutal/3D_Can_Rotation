# 3D Can Rotation

A CSS-only interactive 3D can/soda bottle rotation animation with a responsive design. This project showcases modern CSS techniques including 3D transforms, animations, and responsive layouts without using JavaScript.

## 🎨 Project Overview

This project features a beautiful, fully responsive interactive soda can display that rotates between two different product designs on hover. Built entirely with HTML and CSS, it demonstrates advanced styling techniques to create a professional, modern web experience.

**Languages Used:**
- HTML: 25.9%
- CSS: 74.1%

## ✨ Features

- **Pure CSS 3D Effects**: No JavaScript required - all animations are powered by CSS
- **Interactive Hover Animation**: Smooth product rotation on hover with parallax effects
- **Responsive Design**: Fully responsive layout that works on desktop, tablet, and mobile devices
- **Parallax Background**: Dynamic background elements that move on interaction
- **Cross-browser Compatible**: Uses modern CSS properties with fallbacks
- **Custom Fonts**: Integrated Google Fonts (Karantina and Poppins) for elegant typography

## 📁 Project Structure

```
3D_Can_Rotation/
├── index.html          # Main HTML file with markup
├── style.css           # All styling and animations
├── images/             # Directory for image assets
│   ├── bg.png          # Product background image 1
│   ├── bg2.png         # Product background image 2
│   ├── mockup.png      # Can/bottle mockup template
│   ├── rock1.png       # Rock decoration element 1
│   ├── rock2.png       # Rock decoration element 2
│   ├── rock3.png       # Rock decoration element 3
│   ├── 2.png           # Header image
│   ├── code.png        # Code icon image
│   └── bg.jpg          # Background texture
└── README.md           # This file
```

## 🚀 Key Components

### HTML Structure
- **Header Section**: Displays "CSS ONLY" title, author name (Abdul Wahab), and design credits
- **Banner Section**: 
  - Product display with two rotating soda can designs
  - Rock elements for environmental styling

### CSS Techniques Used

1. **3D Transforms**: `transform`, `rotate`, `translateX`, `translateY` for depth and movement
2. **CSS Variables**: `--url` and `--left` for dynamic background positioning
3. **Mask Images**: `mask-image` for cutting the product shape
4. **Hover Effects**: `:hover` and `:has()` selector for interactive animations
5. **Responsive Grid**: Media queries for mobile (767px), tablet (1023px), and desktop
6. **Blend Modes**: `multiply` for realistic image blending
7. **Transitions**: Smooth 0.7-0.8s animations for all interactions
8. **Background Gradients**: Grid pattern and overlay effects

## 💻 How It Works

### Interactive Rotation
When hovering over the product area:
1. The can lifts up (bottom: 170px → 300px)
2. The first product fades out while the second fades in
3. The background position shifts to display the alternate design
4. Surrounding rocks animate to create depth and parallax effect

### Responsive Behavior
- **Desktop (1023px+)**: Full 280px can width with complete animations
- **Tablet (768px-1023px)**: Can width increases to 400px for better visibility
- **Mobile (<768px)**: Can width reduces to 250px, header images hidden, full-width author section

## 📱 Browser Support

- Chrome/Edge (Latest)
- Firefox (Latest)
- Safari (Latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🎯 Use Cases

This project is perfect for:
- Portfolio showcasing CSS expertise
- E-commerce product display examples
- Learning advanced CSS animations
- Marketing campaign landing pages
- Interactive product visualization

## 🔧 Customization

To modify this project:

1. **Change Product Images**: Replace `images/bg.png` and `images/bg2.png` with your own product images
2. **Adjust Colors**: Modify the background-color and gradient values in the body styling
3. **Update Text**: Edit the header title, author name, and design credits
4. **Modify Animations**: Adjust transition times and transform values in the CSS
5. **Scale Products**: Change the `.soda` width and aspect ratio values

## 📝 Credits

- **Design & Code**: Abdul Wahab
- **Fonts**: Google Fonts (Karantina, Poppins)

## 📄 License

This project is open source and available for personal and educational use.

## 🌐 Live Demo

To view this project:
1. Clone the repository
2. Ensure all image assets are in the `images/` folder
3. Open `index.html` in a web browser
4. Hover over the product to see the 3D rotation effect

## 📞 Contact

Created and maintained by Abdul Wahab

---

**Note**: This project demonstrates that you don't always need JavaScript to create impressive interactive experiences. Modern CSS provides powerful tools for animations, transforms, and responsive design.
