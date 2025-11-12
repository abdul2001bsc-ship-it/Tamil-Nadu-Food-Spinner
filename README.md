# 🍛 Tamil Nadu Food Spinner

A fun and interactive web application that helps you decide what to eat from authentic Tamil Nadu cuisine. Simply spin the wheel and let fate choose your meal!

## 🌟 Features

- **Interactive Spinning Wheel**: Smooth, realistic wheel spinning animation with physics-based deceleration
- **16 Authentic Tamil Dishes**: From Idli to Biryani, featuring the best of Tamil cuisine
- **Beautiful Design**: Modern gradient UI with warm colors reflecting Tamil culture
- **Responsive Layout**: Works perfectly on desktop, tablet, and mobile devices
- **Statistics Tracking**: Keep track of your spins and discover your favorite dish
- **Celebration Effects**: Confetti animation when a result is selected
- **No Dependencies**: Pure HTML, CSS, and JavaScript - no external libraries needed

## 🚀 How to Use

1. **Open the HTML file** in your web browser
2. **Click the center "SPIN WHEEL" button** to start spinning
3. **Wait for the wheel to stop** - the red pointer at the top indicates your selection
4. **Enjoy your meal suggestion** with a celebratory confetti effect!

## 🛠️ Technologies Used

- **HTML5**: Semantic structure and Canvas API for the wheel
- **CSS3**: Modern styling with animations, gradients, and transitions
- **JavaScript ES6+**: Interactive functionality and animation logic
- **Canvas API**: Dynamic wheel rendering and animation

## 📁 File Structure

```
tamil-nadu-food-spinner/
├── index.html          # Main application file
└── README.md          # This documentation file
```

## 🍽️ Food Options Included

| Dish | Description |
|------|-------------|
| 🥞 Idli | Steamed rice cakes |
| 🍘 Dosa | Crispy fermented crepe |
| 🍚 Sambar Rice | Lentil-based stew with rice |
| 🥛 Curd Rice | Yogurt mixed with rice |
| 🍗 Chettinad Chicken | Spicy chicken curry |
| 🍛 Biryani | Aromatic rice with meat |
| 🍯 Pongal | Rice and lentil dish |
| 🍩 Vadai | Savory fried doughnut |
| 🍲 Rasam | Tangy tamarind soup |
| 🥬 Kootu | Vegetable stew |
| 🫓 Parotta | Flaky flatbread |
| 🍜 Kothu Parotta | Shredded parotta with spices |
| ☕ Filter Coffee | Strong South Indian coffee |
| 🍮 Payasam | Sweet dessert pudding |
| 🌶️ Milagu Kozhambu | Pepper-based curry |
| 🥞 Appam | Lace-like rice pancake |

## 🎨 Customization

### Adding New Food Options
To add or modify food options, edit the `foodOptions` array in the JavaScript section:

```javascript
const foodOptions = [
    { text: '🥞 Your Dish', color: '#FF6B35' },
    // Add more options here...
];
```

### Changing Colors
Modify the color scheme by updating:
- Background gradient in `body` CSS
- Wheel segment colors in the `foodOptions` array
- Button and accent colors throughout the CSS

### Adjusting Spin Duration
Change the spin duration in the `spinWheel()` function:

```javascript
const spinDuration = 3000 + Math.random() * 2000; // 3-5 seconds
```

## 🌐 Browser Compatibility

This application works on all modern browsers:
- ✅ Chrome 60+
- ✅ Firefox 55+
- ✅ Safari 12+
- ✅ Edge 79+

## 📱 Responsive Design

The spinner wheel automatically adapts to different screen sizes:
- **Desktop**: 400px wheel diameter
- **Mobile**: 320px wheel diameter
- **Tablet**: Proportional scaling

## 🎯 Interactive Elements

- **Hover Effects**: Wheel scales up slightly on hover
- **Active States**: Button press animations
- **Loading States**: Pulse animation during spin
- **Result Display**: Smooth fade-in animation for results
- **Confetti**: Celebration particles on selection

## 🔧 Technical Details

### Wheel Rendering
The wheel is rendered using HTML5 Canvas API with:
- Dynamic segment calculation
- Text rendering with shadows
- Smooth rotation transformations
- Responsive sizing

### Animation Physics
The spinning animation uses:
- Easing functions for realistic deceleration
- RequestAnimationFrame for smooth 60fps animation
- Random spin duration and rotations

## 🤝 Contributing

Contributions are welcome! Please feel free to:
1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

### Ideas for Contributions
- Add more regional Tamil dishes
- Implement sound effects
- Add dish descriptions or recipes
- Create multiple wheel themes
- Add social sharing features

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- Inspired by the rich culinary heritage of Tamil Nadu
- Built with modern web standards
- No external dependencies - pure vanilla web technologies

---

**Made with ❤️ for food lovers everywhere!**

*Spin the wheel and discover your next favorite Tamil dish!* 🎉# Tamil-Nadu-Food-Spinner
# Tamil-Nadu-Food-Spinner
