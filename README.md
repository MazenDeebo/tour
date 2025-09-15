# 360° Virtual Tour

A stunning interactive 360° virtual tour application built with Three.js and modern web technologies.

## Features

- **Immersive 360° Experience**: Navigate through different rooms with panoramic images
- **Interactive Hotspots**: Click on hotspots to move between rooms
- **AI Chat Assistant**: Built-in chatbot for tour guidance
- **3D Avatar Guide**: Animated virtual guide
- **Modern UI**: Beautiful glassmorphism design with smooth animations
- **Responsive Design**: Works on desktop, tablet, and mobile devices

## Live Demo

Visit the live demo: [https://mazendeebo.github.io/tour/](https://mazendeebo.github.io/tour/)

## Local Development

1. Clone the repository:
```bash
git clone https://github.com/MazenDeebo/tour.git
cd tour
```

2. Open `index.html` in a web browser or serve it using a local server:
```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve .
```

3. Navigate to `http://localhost:8000` in your browser

## Project Structure

```
tour/
├── index.html          # Main application file
├── images/            # Panoramic images
│   ├── shot-panoramic-composition-bathroom.jpg
│   ├── shot-panoramic-composition-bedroom.jpg
│   └── shot-panoramic-composition-living-room.jpg
├── .github/
│   └── workflows/
│       └── deploy.yml  # GitHub Pages deployment
└── README.md
```

## Technologies Used

- **Three.js**: 3D graphics and 360° rendering
- **HTML5 Canvas**: Interactive graphics
- **CSS3**: Modern styling with glassmorphism effects
- **JavaScript ES6+**: Application logic and interactivity
- **GitHub Pages**: Deployment and hosting

## Customization

To add your own panoramic images:

1. Replace the images in the `images/` folder
2. Update the image paths in `index.html` in the `scenes` array
3. Adjust hotspot positions as needed

## Deployment

This project is automatically deployed to GitHub Pages using GitHub Actions. Any push to the `main` branch will trigger a new deployment.

## Browser Support

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## License

MIT License - feel free to use this project for your own virtual tours!
