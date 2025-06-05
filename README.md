# 🌍 GeoNavigator

A GIS-themed arcade game where you navigate a coordinate grid to collect location data while avoiding rogue satellites. Built as a modern browser-based twist on classic maze navigation games.

## 🎮 Game Overview

**GeoNavigator** puts you in control of Earth's digital navigation system. Your mission: collect all location data points (📍) scattered across a geographic coordinate grid while avoiding malfunctioning satellites (🛰️) that threaten to disrupt your systems.

### Key Features

- **Smooth Grid-Based Movement**: Classic arcade-style navigation with modern smooth animations
- **Intelligent Satellite AI**: Four unique satellite behaviors that create challenging but predictable gameplay
- **GIS-Themed Elements**: Professional mapping terminology and geographic concepts
- **Progressive Difficulty**: Strategic gameplay requiring timing and spatial awareness
- **Power-Up System**: Survey markers (🎯) temporarily disable satellites for strategic advantages

## 🎯 How to Play

### Controls
- **Arrow Keys** (⬆️⬇️⬅️➡️): Navigate the globe around the coordinate grid
- **Objective**: Collect all 📍 location pins to complete the mission
- **Avoid**: 🛰️ Satellites - each has unique movement patterns
- **Power-ups**: Grab 🎯 survey markers to temporarily neutralize satellites

### Satellite Behaviors
- **🔴 Red (Chaser)**: Direct pursuit - always moves toward your current position
- **🩷 Pink (Patrol)**: Prefers straight-line movement, changes direction when blocked
- **🔵 Blue (Ambush)**: Targets where you're heading, not where you are
- **🟠 Orange (Shy)**: Chases when far away, retreats when you get too close

### Scoring
- **Location Pins**: 10 points each
- **Survey Markers**: 50 points each
- **Satellite Capture** (during power mode): 200 points each

## 🚀 Technical Details

### Built With
- **HTML5 Canvas**: For smooth 60fps game rendering
- **Vanilla JavaScript**: No external dependencies
- **CSS3**: Modern styling with gradients and animations
- **Responsive Design**: Works on desktop browsers

### Game Engine Features
- Grid-based collision detection
- Smooth interpolation between grid positions
- State-based AI for satellite behaviors
- Frame-rate independent game logic
- Comprehensive game state management

## 📁 Installation & Usage

### Quick Start
1. Clone this repository
2. Open `index.html` in any modern web browser
3. Click "🚀 Start Mission" to begin playing

No build process, server, or dependencies required - it's a single HTML file!

### Browser Requirements
- Modern browser with HTML5 Canvas support
- JavaScript enabled
- Keyboard input capability

## 🎨 Game Design

### Visual Theme
- **Color Scheme**: Professional GIS mapping colors (greens, blues, earth tones)
- **Typography**: Monospace fonts for that technical/mapping feel
- **Animations**: Smooth sine-wave movement easing
- **UI**: Clean, modern interface with appropriate GIS terminology

### Gameplay Balance
- Player moves every 12 frames for comfortable control
- Satellites move every 14 frames (slightly slower)
- Power mode lasts 5 seconds
- Strategic maze layout with multiple path options

## 🔧 Customization

The game is designed to be easily customizable:

- **Maze Layout**: Modify the `maze` array to create new levels
- **Speed Settings**: Adjust `MOVE_SPEED` constant for different difficulties  
- **Colors & Styling**: Update CSS variables for different themes
- **Satellite AI**: Modify behavior patterns in `updateGhosts()` function

## 📝 License

This project is open source and available under the MIT License.

## 🤝 Contributing

Feel free to submit issues, feature requests, or pull requests to improve the game!

## 🎓 Educational Use

Perfect for:
- **GIS Education**: Teaching coordinate systems and spatial navigation
- **Game Development Learning**: Clean, well-commented JavaScript game code
- **Web Development**: Modern HTML5/CSS3/JavaScript techniques
- **Algorithm Study**: Pathfinding and AI behavior implementations

---

*Navigate smart, collect all data points, and avoid those rogue satellites! 🛰️*
