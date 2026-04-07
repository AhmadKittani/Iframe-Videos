# Iframe Video Viewer

A minimalist, single-page application for viewing videos and embedded content via iframe. Simply paste a link and watch fullscreen with a clean, distraction-free interface.

## 🚀 Live Demo

👉 **[https://ahmadkittani.github.io/Iframe-Videos/](https://ahmadkittani.github.io/Iframe-Videos/)**

## Features

- **Simple URL Input** - Paste any embeddable link to load content
- **Auto-Convert YouTube Links** - Supports regular YouTube watch links and youtu.be shortlinks
- **Fullscreen Mode** - Enter fullscreen for immersive viewing
- **Lock Feature** - Hide the search bar for a clean viewing experience
- **Minimalist Design** - Black background with clean typography
- **Responsive** - Maintains 16:9 aspect ratio across all devices

## How to Use

1. **Open the page** - Visit the [live demo](https://ahmadkittani.github.io/Iframe-Videos/) or open `index.html` locally
2. **Enter a URL** - Paste a link in the search field and click "Load" (or press Enter)
3. **Watch** - View your content in the iframe
4. **Fullscreen** - Click the fullscreen button to enter fullscreen mode
5. **Lock** - Scroll down and click the lock button to hide/show the search bar

### Supported URLs

- YouTube videos (e.g., `https://www.youtube.com/watch?v=...`)
- YouTube shortlinks (e.g., `https://youtu.be/...`)
- Direct embed URLs (e.g., `https://www.youtube.com/embed/...`)
- Vimeo and other embeddable iframe sources

## Controls

| Control | Action |
|---------|--------|
| Load Button / Enter Key | Load the URL in the iframe |
| ⛶ Fullscreen | Enter fullscreen mode for the video |
| 🔓 Unlock / 🔒 Lock | Toggle visibility of the search bar |

## Technical Details

- **HTML5 iframe** with sandbox restrictions for security
- **Vanilla JavaScript** - No dependencies
- **Responsive CSS** - Works on all screen sizes
- **YouTube URL Parser** - Automatically converts watch URLs to embed format

## Installation

No installation required. Simply visit the [live demo](https://ahmadkittani.github.io/Iframe-Videos/) or download the `index.html` file and open it locally in your browser.

```bash
# To use locally
open index.html
```

## Browser Support

- Chrome/Edge 60+
- Firefox 55+
- Safari 11+
- All modern browsers with HTML5 support

## License

Free to use and modify.
