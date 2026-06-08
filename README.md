# EndgameUI

A futuristic tactical glassmorphism theme for Vesktop and Discord.

![EndgameUI Banner](./screenshots/banner.png)

---

## ✨ Features

- Modern glassmorphism UI
- Smooth animations and hover effects
- Rounded and clean interface
- Fully customizable accent colors
- Transparent blurred panels
- Optimized for Vesktop + Vencord
- Tactical/futuristic aesthetic
- Lightweight and organized CSS structure

---

## 📸 Screenshots

> Add screenshots here later.

| Preview | Preview |
|---|---|
| ![](./screenshots/preview1.png) | ![](./screenshots/preview2.png) |

---

## 📦 Installation

### Vesktop / Vencord

1. Download the theme file:

```text
endgame.theme.css
```

2. Move it to your themes folder.

### Windows

```text
%appdata%/Vesktop/themes
```

### Linux

```text
~/.config/vesktop/themes
```

### macOS

```text
~/Library/Application Support/Vesktop/themes
```

3. Open Vesktop:
   - Settings
   - Themes
   - Enable `EndgameUI`

4. Reload Discord/Vesktop.

---

## 🎨 Customization

Edit the `:root` variables inside the CSS file.

Example:

```css
:root {

    /* Accent Color */
    --accent-hue: 282;
    --accent-saturation: 88%;
    --accent-lightness: 62%;

    /* Blur */
    --app-blur: 8px;

    /* Radius */
    --app-radius: 18px;
}
```

---

## 🖼 Changing The Background

You can use your own wallpaper by editing the `--app-bg` variable inside the theme file.

Example:

```css
:root {
    --app-bg: url(https://your-image-link.com/wallpaper.png);
}
```

### Using Local Images

You can also use local files:

```css
:root {
    --app-bg: url("file:///C:/Users/YourName/Pictures/wallpaper.png");
}
```

> Make sure to use forward slashes `/` in file paths.

---

## 💡 Recommended Wallpapers

For the best experience:

- Use dark or slightly dimmed wallpapers
- Avoid overly bright centers
- 1920x1080 or higher recommended
- PNG or JPG supported

Glassmorphism themes look best with:

- Futuristic backgrounds
- Tactical/cyberpunk wallpapers
- Soft gradients
- Minimal artwork

---

## 🛠 Built With

- CSS
- Vesktop
- Vencord
- BetterDiscord-compatible styling

---

## 🚀 Goals

EndgameUI aims to create a premium desktop-style Discord experience with:

- Futuristic visuals
- Clean readability
- Smooth interactions
- Modern glassmorphism design

---

## 📌 Roadmap

- [ ] Multiple color presets
- [ ] Modular theme system
- [ ] Animated UI components
- [ ] Custom settings panel
- [ ] Better mobile scaling
- [ ] Optional compact mode

---

## 🤝 Credits

Inspired by the Discord theming community and modern UI design trends.

Special thanks to:

- Anicord
- Vencord
- Vesktop

---

## 📄 License

MIT License

---

## ⭐ Support

If you like the project, consider starring the repository.
