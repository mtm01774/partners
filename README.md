# Partnerships Wireframe

Low-fidelity, grayscale, desktop-first responsive wireframe built with plain HTML, CSS, and minimal vanilla JavaScript.

## Files
- `index.html`: semantic page structure, accessible tab interface, and tab keyboard interactions.
- `styles.css`: grayscale wireframe styles, responsive layout rules, and utility-like component classes.

## Run
1. Open `index.html` directly in a browser.
2. Or serve locally from this folder:
   - `python3 -m http.server 8000`
   - Open `http://localhost:8000`

## Accessibility notes
- Tabs use `role="tablist"`, `role="tab"`, and `role="tabpanel"` with linked ARIA attributes.
- Keyboard support:
  - `ArrowLeft` / `ArrowRight`: move focus between tabs
  - `Home` / `End`: jump focus to first/last tab
  - `Enter` / `Space`: activate focused tab
