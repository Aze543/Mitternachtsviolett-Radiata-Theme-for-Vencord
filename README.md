# 🌸 Mitternachtsviolett Radiata

> *A dark Discord theme — inspired by the crimson spider lily fields of [Lycoris Radiata by Kuro](https://kuro-kai.itch.io/lycoris-radiata).*

---

## Overview

**midnight-purple** is a custom CSS theme for [Vencord](https://vencord.dev/), built on top of the [midnight-discord](https://github.com/refact0r/midnight-discord) base. It wraps Discord in deep, moody purples and translucent dark panels, evoking the atmosphere of wandering through a night-blooming lycoris field.

---

## Preview

<p align="center">
  <img src="https://github.com/user-attachments/assets/54ef025e-3d30-4360-8e61-edd26cf92caa" width="32%" />
  <img src="https://github.com/user-attachments/assets/2baf494a-3b31-4876-9708-c9a70ce00017" width="32%" />
  <img src="https://github.com/user-attachments/assets/f560ae91-02c5-4afb-a28d-72894c9134db" width="32%" />
</p>

---

## Features

- 🌑 Deep purple/violet dark color palette anchored to `#520b57`
- 🌫️ Frosted glass panels with configurable background blur
- 🖼️ Background image support (set to a moody red-flower wallpaper by default)
- ✨ Smooth animations and hover transitions
- 🌸 Custom DMS icon — a flower petal SVG
- 🔤 [Figtree](https://fonts.google.com/specimen/Figtree) as the default font
- 📐 Separated chatbar layout
- 🪟 Custom window controls



## Installation

1. Install [Vencord](https://vencord.dev/) if you haven't already.
2. Open Discord → **Vencord Settings** → **Themes**.
3. Paste the following import into your **Online Themes** or custom CSS field:

```css
@import url('https://refact0r.github.io/midnight-discord/build/midnight.css');
```

4. Copy the full theme CSS (see [`midnight-purple.theme.css`](./midnight-purple.theme.css)) into your custom theme file.

---

## Customization

All options are in the `body {}` and `:root {}` blocks at the top of the file.

### Background Image

```css
--background-image: on;
--background-image-url: url('YOUR_IMAGE_URL_HERE');
```

### Accent Colors

The theme uses a purple ramp anchored to `oklch(40% 0.18 310)`. To shift the hue, change the `hue` value (310) across all `--purple-*` variables in `:root`.

### Panel Blur / Transparency

```css
--panel-blur: on;
--blur-amount: 12px;
--bg-4: hsla(290, 30%, 8%, 0.6); /* lower alpha = more transparent */
```

### Font

```css
--font: 'figtree'; /* replace with '' to use Discord's default font */
```

---

## Credits

- Theme base: [midnight-discord](https://github.com/refact0r/midnight-discord) by **refact0r**
- Inspiration: [Lycoris Radiata](https://kuro-kai.itch.io/lycoris-radiata) by **Kuro** — a beautiful game about grief, flowers, and the boundary between worlds

---

## License

This theme is for personal use. The underlying [midnight-discord](https://github.com/refact0r/midnight-discord) framework is subject to its own license.
