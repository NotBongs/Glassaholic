[README.md](https://github.com/user-attachments/files/24736780/README.md)
# Glassaholic

> Addicted to transparency

A glass-themed Discord experience with desktop blur effects for Vencord.

![Version](https://img.shields.io/badge/Version-1.0.0-ff7b8a?style=flat-square)
![Vencord](https://img.shields.io/badge/Vencord-Compatible-5865F2?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)

## ✨ Features

- 🪟 **Desktop transparency** - Your wallpaper shows through Discord
- 💨 **Frosted glass blur** - Beautiful backdrop blur effects
- 🎨 **Customizable accent** - Easy hex color customization
- ⚡ **Lightweight** - Optimized performance

## 📸 Preview

_Coming soon_

## 📦 Installation

### Requirements
- [Vencord](https://vencord.dev/)
- Windows: [Mica for Everyone](https://github.com/MicaForEveryone/MicaForEveryone)
- Linux: Compositor with transparency support (e.g., Hyprland, KWin)

### Steps

1. **Download** the theme file:
   - [Glassaholic.theme.css](https://github.com/NotBongs/Glassaholic/blob/main/Glassaholic.theme.css)

2. **Install** to your themes folder:
   ```
   %AppData%\Vencord\themes\
   ```

3. **Enable transparency** (Windows users):
   - Open Mica for Everyone
   - Find Discord in the process list
   - Enable transparency
   - Set backdrop to "Acrylic" or "Mica"

4. **Enable the theme** in Discord:
   - Settings → Themes → Glassaholic → Toggle on
   - Press `Ctrl+R` to reload

## 🎨 Customization

Open `Glassaholic.theme.css` in any text editor and modify:

```css
:root {
    /* Change accent color */
    --accent-hex: #ff7b8a;
    
    /* Adjust blur strength */
    --blur-amount: 16px;
}
```

### Popular Color Options

```css
/* Coral Pink (default) */
--accent-hex: #ff7b8a;

/* Purple */
--accent-hex: #9b59b6;

/* Cyan */
--accent-hex: #1abc9c;

/* Electric Blue */
--accent-hex: #00d4ff;
```

After editing, save and press `Ctrl+R` in Discord to see changes.

## 🛠️ Troubleshooting

### Theme not transparent
- Ensure Mica for Everyone is running (Windows)
- Check Discord is in the allowed processes
- Restart Discord completely

### Text hard to read
Increase background opacity in `source.css`:
```css
--bg-3: rgba(0, 0, 0, 0.35); /* Increase from 0.25 */
```

### Performance issues
Reduce blur amount:
```css
--blur-amount: 10px; /* Reduce from 16px */
```

## 🤝 Contributing

Issues and pull requests are welcome! Feel free to:
- Report bugs
- Suggest features
- Submit improvements

## 📄 License

MIT License - feel free to modify and share!

## 🔗 Links

- [GitHub Repository](https://github.com/NotBongs/Glassaholic)
- [Issues](https://github.com/NotBongs/Glassaholic/issues)
- [Vencord](https://vencord.dev/)
- [Mica For Everyone](https://github.com/MicaForEveryone/MicaForEveryone)

---

<div align="center">

Made with 💖 by [NotBongs](https://github.com/NotBongs)

⭐ Star this repo if you like it!

</div>
