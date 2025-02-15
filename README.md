# Voice-Controlled Map

## Overview
This project is a **voice-enabled geospatial web application** that allows users to interact with maps using voice commands. Built with **Leaflet.js** and **Speech Recognition API**, the system enables navigation, zooming, layer toggling, marker addition, and route finding—all through voice input.

## Features
- 🎤 **Voice Commands:** Navigate, zoom, toggle layers, add markers, and find routes.
- 🗺️ **Map Integration:** Uses Leaflet.js for smooth interaction with OpenStreetMap tiles.
- 📍 **Real-time Geolocation:** Tracks and displays the user's live location.
- 🛰 **Layer Switching:** Toggle between satellite and default views.
- 🏎 **Route Finder:** Calculates routes between two locations.
- 🌐 **Offline-Compatible Voice Processing (Future Scope).**

## How It Works
1. Click the **Start Voice Control** button and speak commands like:
   - "Zoom to Ahmedabad"
   - "Show satellite view"
   - "Find route from Delhi to Mumbai"
   - "Add marker"
2. The system **interprets and executes** the command on the interactive map.
3. Users can also track their **current location** with the **Track My Location** button.

## Technology Stack
- **Frontend:** HTML, CSS, JavaScript
- **Mapping Library:** Leaflet.js
- **Voice Recognition:** Web Speech API (browser-based)
- **Geolocation & Routing:** OpenStreetMap & OpenRouteService API

## Installation & Usage
1. Clone this repository:
   ```sh
   git clone https://github.com/your-repo/voice-controlled-map.git
   cd voice-controlled-map
   ```
2. Open `index.html` in a web browser.
3. Click **Start Voice Control** and issue voice commands.
4. (Optional) Use **Track My Location** to show real-time position.

## Voice Commands Guide
| Command | Action |
|---------|--------|
| "Zoom to [City]" | Zooms to the specified city |
| "Show satellite view" | Switches to satellite mode |
| "Show default view" | Switches to default map mode |
| "Find route from [X] to [Y]" | Plots a route between two locations |
| "Add marker" | Adds a marker at the current view |

## Future Enhancements
- 🏗 **Offline Voice Recognition:** Use **Vosk.js** for speech processing without an internet connection.
- 🎙 **Enhanced NLP:** Improve voice command interpretation for natural phrasing.
- 📌 **Save & Share Routes:** Users can save favorite routes or share them.
- 🚀 **AI-powered Geospatial Analysis:** Provide insights based on user navigation patterns.

## Contributors
- **[Your Name]** – Developer & Project Lead

## License
This project is licensed under the MIT License.

---
🚀 *Navigate maps the smart way – with your voice!*

