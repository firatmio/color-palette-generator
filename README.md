# Color Palette Generator

![Node.js](https://img.shields.io/badge/Node.js-18.x-green?logo=node.js)
![Electron](https://img.shields.io/badge/Electron-28.x-blue?logo=electron)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
![GitHub stars](https://img.shields.io/github/stars/firatmio/color-palette-generator?style=social)

A lightweight desktop application that helps you quickly generate multiple shades of a single color for design purposes.  
The goal is to create consistent palettes that transition smoothly from dark to light.  
This application is built with **Electron** and can be run instantly.

## Features
- Automatically generates multiple shades of a single color (including grayscale when needed).
- Shades are ordered from darker (left) to lighter (right).
- Text color (black/white) is automatically chosen for readability.
- Clicking on a color tile copies the hex code to your clipboard.

## Project Structure
```
.
├─ forge.config.js
├─ package.json
├─ src/
│  ├─ index.html   # UI and palette generation
│  ├─ index.js     # Electron main process
│  ├─ preload.js   # (if used) renderer bridge
│  ├─ index.css    # Styling
└─ LICENSE
```

## Installation
Requirements: **Node.js** and **npm**

```bash
npm install
npm start
```

That’s it!  
Once the app opens, you’ll see an automatically generated palette.  
You can click **Generate** to create a new palette or **Export** to download the JSON output.

## License
This project is licensed under the MIT License — see the [LICENSE](./LICENSE) file for details.
