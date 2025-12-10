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

## Viewing at the intended device size

- The prototype is sized for a 412 × 917 Android viewport. On a laptop, the
  page renders inside four centered device frames at that size (or scales down
  if the browser window is smaller).
- To preview the exact mobile viewport in Chrome/Edge devtools: open the page,
  press **Ctrl+Shift+M** (or **Cmd+Shift+M** on macOS), choose **Responsive**
  and enter **412** for width and **917** for height. Safari users can enable
  Responsive Design Mode via **Develop → Enter Responsive Design Mode** and set
  the same dimensions.
