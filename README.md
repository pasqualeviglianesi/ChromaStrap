# ChromaStrap 

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![Bootstrap](https://img.shields.io/badge/bootstrap-5.3+-purple.svg)
![Style](https://img.shields.io/badge/style-Sass-pink.svg)

**ChromaStrap** is a vibrant CSS library that extends Bootstrap's color system. It provides 50+ modern, high-contrast color utilities for text, backgrounds, buttons, and borders—all while maintaining the familiar Bootstrap syntax.

---

## Demo

[Demo](https://pasqualeviglianesi.github.io/ChromaStrap/)

---

## Key Features

- **Native integration:** no new syntax. Use `.btn-neon-pink` just like you use `.btn-primary`.
- **50+ premium colors:** carefully curated palettes including neon, cyberpunk, luxury metals, and earth tones.
- **Auto-contrast logic:** buttons automatically switch text color between black and white based on background luminosity.
- **Utility-first:** ready-to-use classes for `text-`, `bg-`, `border-`, and `btn-`.

---

## Installation

1. **Download** the `chromastrap.min.css` from the `dist/` folder.
2. **Include** it in your HTML after the Bootstrap CSS:

```html
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
<link rel="stylesheet" href="dist/chromastrap.min.css">
```

---

## The palette

### Neon & vibrant
`neon-pink`, `cyber-yellow`, `venom-green`, `ocean-glance`, `toxic-orange`, `laser-lemon`, `plasma-purple`, `acid-lime`, `electric-indigo`, `digital-cyan`, `infra-red`, `plasma-beam`

### Dark & moody
`deep-space`, `midnight-ash`, `obsidian`, `vampire-red`, `gunmetal`, `ocean-abyss`

### Luxury & metals
`royal-velvet`, `emerald-city`, `sapphire-blue`, `gold-leaf`, `rose-gold`, `silver-fox`, `bronze-statue`, `platinum`, `champagne`

### Earth & nature
`desert-sand`, `forest-edge`, `burnt-sienna`, `olive-drab`, `teal-dream`

---

## Usage examples

### Buttons
```html
<button class="btn btn-neon-pink">Vibrant Action</button>
<button class="btn btn-deep-space">Dark Theme</button>
<button class="btn btn-gold-leaf">Premium Style</button>
```

### Backgrounds & text
```html
<div class="bg-deep-space text-cyber-yellow p-4 rounded">
  Deep space background with cyber yellow text.
</div>

<p class="text-electric-violet fw-bold">Electric violet text example.</p>
```

---

## Development (Sass)

To compile your own version:

```bash
npx sass scss/chromastrap.scss dist/chromastrap.min.css --style compressed
```
