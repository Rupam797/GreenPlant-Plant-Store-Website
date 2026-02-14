# PlantWebsite

A small static website showcasing plant-related content and assets.

## Overview

- **Purpose:** Simple front-end project demonstrating layout, styles, and basic interactivity.
- **Tech:** HTML, CSS, and JavaScript (no build tools required).

## Files

- [index.html](index.html) — main HTML entry.
- [styles.css](styles.css) — project styles.
- [main.js](main.js) — site interactions.
- [scrollreveal.min.js](scrollreveal.min.js) — optional reveal animations.
- `assets/` — images and other static assets.

## Run / Preview

The easiest way is to open [index.html](index.html) in your browser. For a local HTTP server (recommended for some APIs and features), run one of these commands from the project root:

```bash
# Using Python 3
python -m http.server 8000

# Or using Node (http-server)
npx http-server -p 8000
```

Then open http://localhost:8000 in your browser.

Note: `main.js` is intended for browser usage. Running `node main.js` is not required and may exit with errors.

## Development

- Edit `index.html`, `styles.css`, or `main.js` and refresh the browser.
- Add images to `assets/` and update `index.html` accordingly.

## Troubleshooting

- If styles or scripts don't load, ensure files are served over HTTP (see Run/Preview).
- Check the browser console for JS errors.

## Contributing

Feel free to open issues or submit pull requests with improvements.

## License

This project is provided as-is. Add a license file if you intend to publish.
