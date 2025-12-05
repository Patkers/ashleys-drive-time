# Ashley's Drive Time 🚗✨

A beautiful, real-time travel time calculator with interactive maps and traffic information.

![Ashley's Drive Time](https://img.shields.io/badge/status-active-success)

## ✨ Features

- **Real-time Traffic** - Get accurate arrival times based on current traffic conditions
- **Interactive Map** - Visual route display with Google Maps integration
- **Departure Scheduling** - Choose "Leave Now" or schedule a specific departure time
- **Favorite Routes** - Save and quickly reload your common trips
- **Street View** - See your destination before you arrive
- **Map Themes** - Choose from Standard, Night Mode, Retro, or Pink themes
- **Route Animation** - Watch your route animate on the map
- **Traffic Toggle** - Show/hide live traffic conditions

## 🚀 Quick Start

1. Clone this repository
2. Get a free Google Maps API key from [Google Cloud Console](https://console.cloud.google.com/)
3. Enable these APIs:
   - Maps JavaScript API
   - Distance Matrix API
   - Directions API
4. Open `index.html` and replace `YOUR_API_KEY_HERE` with your actual API key (around line 399)
5. Open `index.html` in your web browser

## 📋 Setup Instructions

### Getting Your Google Maps API Key

1. Go to [Google Cloud Console](https://console.cloud.google.com/)
2. Create a new project (or select existing)
3. Go to "APIs & Services" → "Library"
4. Search for and enable:
   - **Maps JavaScript API**
   - **Distance Matrix API**
   - **Directions API**
5. Go to "APIs & Services" → "Credentials"
6. Click "Create Credentials" → "API Key"
7. Copy your API key
8. (Optional) Click "Restrict Key" and select only the APIs above

### Installing the API Key

1. Open `index.html` in a text editor
2. Find line 399 (or search for `const API_KEY`)
3. Replace `'AIzaSyANarr0VysL_utEFMW4vjmLdhRUyY6lFZo'` with your new API key
4. Save the file

## 💡 How to Use

1. **Enter Locations**: Type your starting location and destination
2. **Choose Departure Time**: Select "Leave Now" or "Leave At" for scheduled trips
3. **Calculate**: Click "Calculate Arrival Time"
4. **Explore**: Use the map controls to toggle traffic, change themes, or animate your route
5. **Save Favorites**: Click "⭐ Save Route" to bookmark common trips

## 🎨 Map Features

- **Traffic Layer** - Toggle live traffic conditions
- **Themes** - Standard, Night Mode, Retro, or Pink
- **Animation** - Watch a marker travel along your route
- **Street View** - Preview your destination (when available)

## 💾 Saved Routes

Your favorite routes are saved locally in your browser. Use the dropdown at the top to quickly reload them!

## 📱 Mobile Friendly

Works great on phones and tablets! Just open in your mobile browser.

## 🔒 Privacy & API Usage

- **Free Tier**: Google provides $200/month in free API credits (covers ~40,000 requests)
- **Local Storage**: Saved routes are stored only in your browser
- **No Backend**: All data stays on your device
- **API Key**: Keep your API key secure and don't share it publicly

## 🛠️ Technical Details

- Pure HTML/CSS/JavaScript - no build process required
- Google Maps JavaScript API
- Responsive design with Tailwind-style utilities
- LocalStorage for saving favorites
- No external dependencies except Google Maps

## 📄 License

Free to use and modify for personal projects!

## 🤝 Contributing

Feel free to fork and customize! This is a personal project made with love.

## ⚠️ Important Notes

- Requires active internet connection
- Google Maps API key required
- Traffic data availability varies by region
- Some features (like Street View) may not be available in all locations

## 🎉 Enjoy!

Made for Ashley with 💕
