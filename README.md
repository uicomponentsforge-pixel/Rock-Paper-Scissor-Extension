# Rock Paper Scissors Chrome Extension

A classic Rock Paper Scissors game packaged as a Manifest V3 Chrome Extension.

## Features

- **Interactive Gameplay**: Play Rock, Paper, or Scissors by clicking the respective move icons.
- **Keyboard Shortcuts**: Quickly play moves using your keyboard:
  - Press `r` for **Rock**
  - Press `p` for **Paper**
  - Press `s` for **Scissors**
- **Score Persistence**: Keeps track of your **Wins**, **Losses**, and **Ties**, persisted across browser sessions using `localStorage`.
- **Reset Score**: Reset your score counters at any time.
- **Auto Play Mode**: Sit back and let the extension play automatically at 1-second intervals. Click **Auto Play** again to stop.

## Installation

To install and run this extension locally in Google Chrome:

1. Clone or download this repository to your local machine.
2. Open Google Chrome and navigate to `chrome://extensions/`.
3. Enable **Developer mode** by toggling the switch in the upper-right corner.
4. Click the **Load unpacked** button in the upper-left corner.
5. Select the root folder of this project containing `manifest.json`.
6. The extension will now appear in your Chrome toolbar!

## File Structure

```text
.
├── manifest.json      # Chrome extension configuration (Manifest V3)
├── popup.html         # User interface popup structure
├── style.css          # Styling for the extension popup
├── script.js         # Core game logic and event listeners
├── icons/             # Extension icon(s)
└── images/            # Move icons (rock, paper, scissors)
```

## License

MIT
