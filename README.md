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

## Live Demo

- Try the live site: https://mygreenplantstore.netlify.app/

## Screenshots

Below are example screenshots from the live site. To include them in this README, place the image files in `assets/screenshots/` with the filenames shown and they will render below.

- ![Hero section] <img width="1919" height="874" alt="Screenshot 2026-02-14 120325" src="https://github.com/user-attachments/assets/98989463-6a01-4fb0-8c92-d5eacccbe558" />

- *Hero / landing section.*

- ![About section](<img width="1919" height="863" alt="Screenshot 2026-02-14 120356" src="https://github.com/user-attachments/assets/b0ca7198-5095-4e14-87c1-60985e43ea2e" />
)
- *About / features section.*

- ![Products grid](<img width="1919" height="882" alt="Screenshot 2026-02-14 120429" src="https://github.com/user-attachments/assets/f574ade3-63e9-4368-b167-e7ad474732e0" />
)
- *Products listing.*

- ![Contact / footer](<img width="1910" height="868" alt="Screenshot 2026-02-14 120505" src="https://github.com/user-attachments/assets/0c38a3f0-d7c9-45dc-ae59-9c6efda26196" />
)
- *Contact form and footer.*

If you'd like, I can import the attached images into `assets/screenshots/` and update the README to display them directly. Reply `yes` to proceed.

## Run / Preview

The easiest way is to open [index.html](index.html) in your browser. For a local HTTP server (recommended for some APIs and features), run one of these commands from the project root:

```bash
# Using Python 3
python -m http.server 8000

# Or using Node (http-server)
npx http-server -p 8000
```

Then open http://localhost:8000 in your browser.

Alternatively, you can visit the live demo at https://mygreenplantstore.netlify.app/.

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
