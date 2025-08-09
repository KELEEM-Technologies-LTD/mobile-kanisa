# Mempay - Flutter Web Application

## Overview

Mempay is a Flutter web application designed to provide a modern, responsive user experience across web browsers. This project contains the compiled web assets and deployment-ready files for the Mempay application.

## Project Structure

```
mobile.kanisa/
├── assets/                 # Application assets and resources
│   ├── assets/            # Images and media files
│   ├── fonts/             # Custom fonts
│   └── packages/          # Third-party package assets
├── canvaskit/             # CanvasKit rendering engine files
├── icons/                 # Application icons for PWA
├── index.html             # Main HTML entry point
├── main.dart.js           # Compiled Dart application
├── manifest.json          # PWA manifest configuration
├── flutter.js             # Flutter web runtime
└── flutter_bootstrap.js   # Flutter web bootstrap script
```

## Features

- **Responsive Design**: Optimized for various screen sizes and devices
- **Modern UI**: Built with Flutter's Material Design components
- **Cross-Platform**: Runs on any modern web browser

## Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- Web server (for local development)

### Running the Application

1. **Local Development Server**

   ```bash
   # Using Python (if available)
   python -m http.server 8000

   # Using Node.js (if available)
   npx serve .

   # Using PHP (if available)
   php -S localhost:8000
   ```

2. **Access the Application**
   - Open your web browser
   - Navigate to `http://localhost:8000`
   - The application should load automatically

### Deployment

This project is ready for deployment to any static web hosting service:

- **Netlify**: Drag and drop the project folder
- **Vercel**: Connect your repository and deploy
- **GitHub Pages**: Push to a GitHub repository and enable Pages
- **Firebase Hosting**: Use Firebase CLI to deploy

## PWA Features

The application includes Progressive Web App capabilities:

- **Installable**: Users can install the app on their devices
- **Offline Support**: Basic offline functionality
- **App-like Experience**: Full-screen mode and native app feel
- **Push Notifications**: Ready for push notification implementation

## Browser Support

- Chrome 67+
- Firefox 65+
- Safari 12+
- Edge 79+

## Development

### Building from Source

If you have the Flutter source code:

```bash
# Install Flutter SDK
# Navigate to the Flutter project directory
flutter build web
```

### Customization

- **Icons**: Replace files in the `icons/` directory
- **Assets**: Add or modify files in the `assets/` directory
- **Styling**: Modify the compiled CSS in `main.dart.js`
- **Configuration**: Update `manifest.json` for PWA settings

## Dependencies

This web build includes the following Flutter packages:

- `awesome_notifications`: For notification functionality
- `cupertino_icons`: iOS-style icons
- `wakelock_plus`: Screen wake lock functionality
- `youtube_player_iframe`: YouTube video player integration

## Performance

- **Initial Load**: Optimized with CanvasKit rendering
- **Bundle Size**: Compressed and optimized for web delivery
- **Caching**: Service worker for improved performance
- **Lazy Loading**: Assets loaded on demand

## Security

- **Content Security Policy**: Configured for secure execution
- **Cross-Origin**: Properly configured for web deployment

## Troubleshooting

---

**Note**: This is a compiled Flutter web application. For source code modifications, you'll need access to the original Flutter project files.
