# Real-Time Virtual Makeup Web App

A web-based virtual makeup application that lets users try on different makeup looks in real-time using their webcam. The makeup effects are applied instantly as you move, with no need to take photos. Built with HTML5, JavaScript, and MediaPipe Face Mesh technology.

## Features

- Real-time face detection and makeup application
- Instant makeup preview as you move
- Multiple makeup features:
  - Lipstick with various colors
  - Eyebrow enhancement
  - Cheek blush
  - Virtual earrings
- Toggle individual makeup features on/off
- Screenshot capability
- User-friendly interface
- No installation required - runs in the browser

## Technologies Used

- HTML5 Canvas
- MediaPipe Face Mesh
- JavaScript
- CSS3

## Getting Started

1. Clone the repository:
```bash
git clone [your-repository-url]
```

2. Start a local server. You can use Python's built-in server:
```bash
python3 -m http.server 8000
```

3. Open your browser and navigate to:
```
http://localhost:8000
```

## Usage

1. Click "Start Camera" to initialize your webcam
2. Wait for face detection to initialize
3. Use the checkboxes to toggle different makeup features
4. Click on color swatches to change makeup colors
5. Use "Take Screenshot" to save your current look

## Browser Compatibility

Tested and working on:
- Google Chrome (recommended)
- Firefox
- Safari
- Edge

## Privacy Note

This application runs entirely in your browser. No images or data are sent to any server. All face detection and makeup application happens locally on your device. 