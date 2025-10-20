# Campus Events — CSS Grid Lab (Finished Example)

This package includes a finished example of the in‑class CSS Grid + subgrid activity and a simple mockup of the expected layout/alignment.

## Files
- `index.html` — Markup for the events grid
- `styles.css` — Final styles using Grid and `subgrid` with a fallback
- `mockup.png` — Wireframe-style mockup demonstrating header/body/footer alignment
- `README.md` — You're reading it

## Quick Start
1. Open `index.html` in your browser (same folder as `styles.css`).
2. Resize the window to see the responsive grid.
3. Note how card header/body/footer rows line up thanks to `subgrid`.
4. On browsers that lack `subgrid`, the `@supports` block falls back to local rows.

## Notes
- Featured card spans 2 columns on screens ≥ 900px.
- Reflection prompts are at the bottom of `styles.css` in comments.