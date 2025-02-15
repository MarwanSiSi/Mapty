# Mapty - Workout Mapping Application

## Overview
Mapty is a web application that allows users to log their workouts (running or cycling) on an interactive map. Users can input workout details such as distance, duration, cadence (for running), and elevation gain (for cycling). The application stores workout data locally and displays it on a map with markers.

## Features

- **Interactive Map**: Built using Leaflet.js, the map allows users to click and log workouts at specific locations.
- **Workout Logging**: Users can log running or cycling workouts with details like distance, duration, cadence, and elevation gain.
- **Local Storage**: Workout data is saved in the browser's local storage, ensuring data persistence across sessions.
- **Responsive Design**: The application is designed to work seamlessly on both desktop and mobile devices.
- **Custom Markers**: Different markers for running and cycling workouts with popups displaying workout details.
- **Workout List**: A sidebar displays a list of all logged workouts with detailed information.

## Technology Stack

- **HTML5**
- **CSS3**
- **JavaScript (ES6+)**
- **Leaflet.js** (for interactive maps)
- **Local Storage** (for data persistence)

## Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- Basic understanding of HTML, CSS, and JavaScript

### Installation

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/mapty.git
   ```

2. Navigate to the project directory:
   ```
   cd mapty
   ```

3. Open the application:
   - Double-click on `index.html` file, or
   - Use a local development server (recommended for proper functionality)

### Setting up a local server

For the best experience, I recommend using a simple HTTP server. You can set one up in several ways:

**Using Visual Studio Code:**
1. Install the "Live Server" extension
2. Right-click on `index.html`
3. Select "Open with Live Server"

**Using Node.js:**
1. Install Node.js from https://nodejs.org/
2. Open a terminal in the project folder
3. Run `npx serve`
4. Open your browser and go to `http://localhost:5000`

**Using Python:**
1. Open a terminal in the project folder
2. Run `python -m http.server` (for Python 3) or `python -m SimpleHTTPServer` (for Python 2)
3. Open your browser and go to `http://localhost:8000`

## Project Structure

```
mapty/
├── img/                  # Images and icons
│   ├── logo.png          # Application logo
├── index.html            # Main HTML file
├── script.js             # JavaScript with all functionality
├── style.css             # CSS styling
└── README.md             # Project documentation
```

## Usage

1. **Open the Application**:
   - Launch the application in your browser.

2. **Allow Location Access**:
   - The application will request access to your location to center the map.

3. **Log a Workout**:
   - Click on the map to select a location.
   - Fill in the workout details (distance, duration, cadence for running, or elevation gain for cycling).
   - Click "OK" to log the workout.

4. **View Workouts**:
   - Logged workouts will appear as markers on the map and in the sidebar list.

5. **Reset Data**:
   - To clear all workout data, use the `reset()` method in the browser console:
     ```javascript
     app.reset();
     ```

## Features Explained

### Interactive Map
- Built using Leaflet.js, the map allows users to click anywhere to log a workout.
- Markers are placed at the workout locations with popups displaying workout details.

### Workout Logging
- Users can log running or cycling workouts with specific details.
- Running workouts include cadence (steps per minute).
- Cycling workouts include elevation gain.

### Local Storage
- Workout data is saved in the browser's local storage, ensuring data persistence even after the browser is closed.

### Responsive Design
- The application is designed to work seamlessly on both desktop and mobile devices.

## Credits

This project was created as part of a JavaScript course by Jonas Schmedtmann. The design and concept belong to him. This code is for learning purposes only and should not be used for commercial applications.

## License

This project is intended for educational purposes only. All design and concept rights belong to the original creator. Please do not use for commercial purposes or claim as your own work.

---

Feel free to contribute to this project by creating pull requests or reporting issues!

---

This `README.md` provides a comprehensive overview of the Mapty application, its features, and how to get started. Let me know if you need further adjustments!
