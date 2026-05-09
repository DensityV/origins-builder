# Origins Builder

A visual block editor for the Minecraft Origins mod (Forge 1.20.1).

## How to Build

### Requirements
- [Node.js](https://nodejs.org/) v18 or later

### Steps

1. **Install dependencies**
   ```
   npm install
   ```

2. **Run in development** (opens the app without building)
   ```
   npm start
   ```

3. **Build Windows installer (.exe)**
   ```
   npm run build-win
   ```
   Output: `dist/Origins Builder Setup 1.0.0.exe`

4. **Build Mac (.dmg)**
   ```
   npm run build-mac
   ```

5. **Build Linux (.AppImage)**
   ```
   npm run build-linux
   ```

## Files
- `origins-manager.html` — main file manager (namespaces, origins, powers, layers)
- `origins-editor.html` — visual block editor
- `origins-settings.html` — customization settings
- `main.js` — Electron entry point

## Usage
The app opens with the **Manager** as the home screen. From there you can:
- Create namespaces, origins, powers and layers
- Open the block editor to visually build power JSON
- Export a complete datapack ZIP
- Open Settings to customize colors and layout
