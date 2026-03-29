# ChainPulse Frontend

ChainPulse is a frontend-first Web3 news ecosystem website.

This project currently ships as a static HTML page and is organized so it can scale into a larger app later.

## Project Structure

```text
chainpulse/
  README.md
  docs/
  src/
    index.html
    assets/
      css/
      js/
      images/
```

## Run Locally

Since this is a static frontend right now, you can run it in either way below:

1. Open `src/index.html` directly in your browser.
2. Or use a local server (recommended for future JS modules and API work).

Example with VS Code Live Server:

- Install the Live Server extension.
- Right-click `src/index.html`.
- Select **Open with Live Server**.

## Next Steps (Planned)

- Split inline styles into `src/assets/css/` files.
- Move scripts into `src/assets/js/` modules.
- Add reusable UI components and sections.
- Connect frontend to real Web3/news data sources.
- Add build tooling when needed (Vite/Next.js).

## Notes

- Main entry point: `src/index.html`
- Current title: `ChainPulse | Web3 News Ecosystem`
