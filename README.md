[Online Sheet Click Here](https://coldplazma.github.io/SavagePath-Sheet/swpf_sheet.html)

# Savage Worlds Pathfinder Character Sheet Web App

A responsive, single-page HTML5 web application designed to replace the paper character sheet for **Savage Worlds for Pathfinder**. This tool allows players to track attributes, skills, edges, hindrances, gear, and powers dynamically in a browser environment.

## Features

- **Responsive Design:** optimized for both desktop and mobile devices. Layout adjusts automatically based on screen width.
- **Interactive Die Tracking:** Click attribute and skill dice to cycle through die types (d4, d6, d8, d10, d12).
- **Dynamic Lists:** Add or remove Skills, Weapons, Powers, Edges, and Hindrances as needed.
- **Calculated Stats:** Track derived statistics like Pace, Parry, Toughness, and Power Points.
- **State Tracking:** Toggle Wounds, Fatigue, and Bennies with a click.

## Dual Save System

- **Browser Storage:** Instantly save your character to your device's LocalStorage for persistence across page reloads.
- **Portable Save Codes:** Generate a base64 encoded text block to share characters between devices or backup your data to a text file.

## Usage Guide

### Installation

This application is a self-contained single-page application (SPA).

1. Download the `swpf_sheet.html` file.
2. Open the file in any modern web browser (Chrome, Firefox, Safari, Edge).

No server or internet connection is required after the initial load (internet is only required to fetch the Tailwind CSS and FontAwesome libraries from CDN).

### Managing Stats

- **Attributes & Skills:** Click the die icon (e.g., "d4") to cycle up to the next die type. It cycles `d4 → d6 → d8 → d10 → d12 → d4`.
- **Wounds & Fatigue:** Click the numbered boxes to mark damage. The boxes turn red (Wounds) or yellow (Fatigue) when active.
- **Lists:** Click the small `+` button in section headers to add new items. To remove an item, look for the trash icon (on desktop hover) or double-click the input field.

### Saving and Loading Data

#### Method 1: Quick Save (Browser Memory)

1. Scroll to the **Data Tools** section at the bottom.
2. Click **Save to Browser** to store your current sheet in the browser's cache.
3. Click **Load from Browser** to restore it when you return.

#### Method 2: Portable Backup (Text Block)

1. Click **Generate Save Code**. A long string of text will appear in the text box.
2. Copy this text and save it to a notepad file or email it to yourself.
3. To restore, paste the text into the box and click **Load from Code**.

## Technical Details

- **Frameworks:** None. Built with Vanilla JavaScript.
- **Styling:** Tailwind CSS (via CDN).
- **Icons:** FontAwesome (via CDN).
- **Fonts:** Google Fonts (Cinzel, Lato).

## License (Software)

The HTML, CSS, and JavaScript source code for this web application is licensed under the **MIT License**.

### MIT License

Copyright (c) 2026

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

## Legal & Attribution (Game Content)

This tool is a fan project and is not an official product of Pinnacle Entertainment Group or Paizo Inc.

### Savage Worlds Fan License

This tool references the Savage Worlds game system, available from Pinnacle Entertainment Group at www.peginc.com. Savage Worlds and all associated logos and trademarks are copyrights of Pinnacle Entertainment Group. Used with permission. Pinnacle makes no representation or warranty as to the quality, viability, or suitability for purpose of this product.

### Pathfinder Compatibility

Pathfinder and associated marks and logos are trademarks of Paizo Inc., and are used under license. This web application is not published, endorsed, or specifically approved by Paizo Inc. or Pinnacle Entertainment Group.

