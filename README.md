# Stria Icons Core

The Core assets package for Stria Icons.

Stria is a unified visual language of pixel-perfect SVG icons, built with absolute geometric precision and zero dependency bloat.

## Contents

This package distributes:
- Raw and optimized SVGs: `dist/svg/`
- SVG Sprite sheets: `dist/sprites/`
- Webfonts (WOFF, WOFF2): `dist/webfonts/`
- CSS for Webfont and SVG Masking: `dist/css/stria.css` and `dist/css/stria.min.css`
- Lightweight self-executing vanilla JS replacer utility: `dist/js/stria.js` and `dist/js/stria.min.js`
- ES Modules and CommonJS bundles: `dist/esm/` and `dist/cjs/`
- TypeScript definitions: `dist/types/`
- Complete metadata catalog: `dist/icons.json`

## Installation

```bash
npm install stria-icons
```

## Usage Examples

### 1. Plain HTML / Vanilla JS
Using the lightweight self-executing script (replacer utility):

```html
<script src="https://cdn.jsdelivr.net/npm/stria-icons@latest/dist/js/stria.min.js"></script>

<!-- Add elements with the data-stria attribute -->
<i data-stria="user" data-stria-style="solid"></i>
<i data-stria="home" data-stria-style="regular"></i>

<script>
  stria.replace();
</script>
```

Using CSS Masking:
```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/stria-icons@latest/dist/css/stria.min.css">

<!-- Use the utility classes -->
<i class="stria-solid stria-user"></i>
```

## Licenses

- Code (compiler toolchain, wrappers, build scripts): MIT License
- Icon designs (SVGs in `/icons` directory): CC BY 4.0
