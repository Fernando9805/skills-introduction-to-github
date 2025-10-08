# Calculator PWA

A basic calculator implemented as a Progressive Web App (PWA) with offline support and installability.

## Features

- ✨ Basic arithmetic operations (addition, subtraction, multiplication, division)
- 📱 Responsive design that works on desktop and mobile devices
- 🔌 Offline functionality using Service Worker
- 📲 Installable as a standalone app on supported devices
- ⌨️ Keyboard support for faster input
- 🎨 Modern, clean UI with smooth animations

## Calculator Operations

- **Numbers**: Click number buttons (0-9) or use keyboard
- **Operators**: +, -, ×, ÷
- **Clear (C)**: Reset the calculator
- **Backspace (⌫)**: Delete last character
- **Decimal point**: Add decimal numbers
- **Equals (=)**: Calculate the result

## Keyboard Shortcuts

- `0-9`: Number input
- `+`, `-`, `*`, `/`: Operators
- `Enter` or `=`: Calculate result
- `Escape`: Clear display
- `Backspace`: Delete last character
- `.`: Decimal point

## Installation

### As a Web App

1. Open `index.html` in a modern web browser
2. The calculator will work immediately in your browser

### As a PWA (Progressive Web App)

1. Visit the calculator in a PWA-compatible browser (Chrome, Edge, Safari)
2. Click the "Install App" button that appears below the calculator
3. Or use the browser's install option (usually in the address bar or menu)
4. The app will be installed and can be launched like a native app

## Running Locally

You can run the calculator using any static file server. For example:

### Python HTTP Server
```bash
python3 -m http.server 8080
```

Then open `http://localhost:8080` in your browser.

### Node.js HTTP Server
```bash
npx http-server -p 8080
```

Then open `http://localhost:8080` in your browser.

## PWA Features

- **Service Worker**: Caches app resources for offline use
- **Manifest**: Defines app metadata and install behavior
- **Icons**: Custom app icons for home screen and app launcher
- **Standalone Mode**: Runs without browser UI when installed

## File Structure

```
.
├── index.html          # Main HTML file
├── styles.css          # CSS styling
├── app.js              # Calculator logic and PWA install handling
├── service-worker.js   # Service worker for offline support
├── manifest.json       # PWA manifest file
├── icon-192x192.png    # App icon (192x192)
├── icon-512x512.png    # App icon (512x512)
└── README.md           # This file
```

## Browser Compatibility

- Chrome/Edge: Full PWA support
- Safari: PWA support with some limitations
- Firefox: Basic functionality (limited PWA support)

## Technologies Used

- HTML5
- CSS3 (Grid Layout, Flexbox, Animations)
- Vanilla JavaScript (ES6+)
- Service Worker API
- Web App Manifest

## License

This is a demonstration project for educational purposes.
