# PJL Color Palette

Standalone reference page for the PJL color system — every ramp, step and
hex value, with click-to-copy swatches and light/dark themes.

Source of truth: `~/Projects/pjl-brand/brand/pjl-color-palette.md`. When that
file changes, update the `GROUPS` and `QUICK` data at the bottom of
`index.html` to match.

## Structure

```
pjl-color-palette/
├── index.html    the page (styles and script inline)
└── fonts/        PJL Display Bold, PJL Sans Regular + Bold
```

## Viewing

Open `index.html` directly in a browser, or serve the folder:

```bash
python3 -m http.server 4190
```

then visit http://localhost:4190/.
