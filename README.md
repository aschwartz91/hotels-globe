# Hotels Globe

An interactive 3D globe visualization showing hotel locations around the world, built with Three.js.

## Features

- **Interactive 3D Globe**: Drag to rotate, scroll to zoom
- **City Markers**: 60+ cities worldwide with hover tooltips
- **Auto-rotation**: Globe spins automatically when not interacting
- **Responsive Design**: Works on desktop and mobile devices
- **Enhanced Interaction**: Large invisible hit areas make city dots easy to target

## Usage

Simply open `index.html` in a web browser. No build process or server required.

### Controls

- 🖱️ **Drag**: Rotate the globe
- 📍 **Hover**: View city details and stop auto-rotation  
- ⚡ **Scroll**: Zoom in/out

## Technical Details

- Built with [Three.js](https://threejs.org/) for 3D rendering
- Uses [TopoJSON](https://github.com/topojson/topojson) for world map data
- Responsive CSS with dark theme
- Optimized for performance with efficient raycasting

## Recent Improvements

- Enhanced city marker interaction with larger hit areas
- Fixed drag direction to match Google Maps behavior
- Cursor-driven flashlight effect on globe surface
- Reduced city marker size for cleaner appearance