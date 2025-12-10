# UIC-2025

Static prototype for a driver companion app. The UI is implemented in a single
`index.html` with inline styles and assets, so nothing needs to be built.

## Repository contents

- `index.html`: the full, static prototype (lives at the repository root)
- `README.md`: these instructions

If you're browsing on GitHub, open `index.html` from the repository root and
use the **Raw** button to view or download the file directly.

## How to run

### Option 1: open directly
1. Locate `index.html` in the repository root.
2. Double-click it or open it with your browser of choice. The page will render
   locally with no additional setup.

### Option 2: serve with Python (avoids browser CORS warnings)
1. From the repo root, start a simple server:
   ```bash
   python3 -m http.server 8000
   ```
2. Visit [http://localhost:8000](http://localhost:8000) in your browser. The
   `index.html` page will load at the root.
