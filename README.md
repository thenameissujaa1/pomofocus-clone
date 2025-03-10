# Pomodoro Timer by Sujan

A minimalist Pomodoro Timer application to boost your productivity. This application helps you manage your work sessions using the Pomodoro Technique.

## Features

- 🕒 25-minute Pomodoro work sessions
- ☕ 5-minute short breaks
- 🌟 15-minute long breaks
- 🔊 Audio notifications for session changes
- 🎨 Color themes for different session types
- 📱 Responsive design for all devices

## Quick Start

Since this is an optimized build version (only 4.4MB), you can run it without any node modules or dependencies:

1. Navigate to the `build` directory:
```bash
cd build
```

2. Start the Python HTTP server:
```bash
python3 -m http.server 3000
```

3. Open in your browser:
```
http://localhost:3000
```

## File Structure

- `build/` - Contains the optimized production build (4.4MB)
  - All static assets (JS, CSS, sounds, images)
  - HTML and configuration files
- `src/` - Source code (if you want to modify the application)
- `public/` - Public assets and template files

## Development

If you want to modify the application, you'll need to:

1. Install Node.js
2. Install dependencies: `npm install`
3. Start development server: `npm start`
4. Build production version: `npm run build`

## Technologies Used

- React
- Redux for state management
- CSS Modules for styling
- HTML5 Audio for sound effects

## License

© Sujan Deep 2025. All rights reserved. 
