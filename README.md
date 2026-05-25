# Turf Gold — Obsidian Theme

A refined Obsidian theme inspired by horse racing data visualization, featuring deep turf greens and warm gold accents. Light mode uses a bright mint green palette, while dark mode embraces rich turf tones.

![Turf Gold Theme](https://img.shields.io/badge/Obsidian-Turf%20Gold-green) ![License](https://img.shields.io/badge/license-MIT-blue)

## Screenshots

*Coming soon*

## Installation

### Manual Installation

1. Download this repository
2. Extract the contents
3. Copy the `Turf Gold` folder to your Obsidian vault's `.obsidian/themes/` directory
4. In Obsidian, go to **Settings → Appearance → Themes**
5. Select **Turf Gold** from the theme dropdown

### macOS / iCloud Vault

If your vault is on iCloud Drive (e.g., `~/Library/Mobile Documents/iCloud~md~obsidian/Documents/`):

```bash
# Clone to a temporary location
git clone https://github.com/yourusername/obsidian-turf-gold-theme.git /tmp/obsidian-turf-gold-theme

# Copy to your vault
cp -r /tmp/obsidian-turf-gold-theme/Turf\ Gold \
  ~/Library/Mobile\ Documents/iCloud~md~obsidian/Documents/.obsidian/themes/

# Clean up
rm -rf /tmp/obsidian-turf-gold-theme
```

### Global Installation (All Vaults)

To use this theme across all your vaults:

```bash
# Copy to Obsidian's global themes directory
cp -r /path/to/obsidian-turf-gold-theme/Turf\ Gold \
  ~/Library/Application\ Support/obsidian/themes/

# Create symbolic links in each vault
ln -s ~/Library/Application\ Support/obsidian/themes/Turf\ Gold \
  ~/path/to/vault/.obsidian/themes/Turf\ Gold
```

## Color Palette

### Dark Mode

| Element | Color | Hex |
|---------|-------|-----|
| Primary Background | Turf | `#0a1d15` |
| Secondary Background | Turf 2 | `#0e2519` |
| Text | Paper | `#f3eddd` |
| Accent | Gold | `#c6a04e` |
| Success | Win | `#3aa978` |
| Warning | Amber | `#dca23f` |
| Error | Loss | `#d8505f` |

### Light Mode

| Element | Color | Hex |
|---------|-------|-----|
| Primary Background | Mint Green | `#eaf0ec` |
| Secondary Background | Mint Green 2 | `#e0eae2` |
| Text | Dark Green | `#142b18` |
| Accent | Gold Deep | `#9a7a32` |
| Success | Win | `#3aa978` |
| Warning | Amber | `#dca23f` |
| Error | Loss | `#d8505f` |

## Typography

- **Body Text**: System fonts (San Francisco, Hiragino Sans, Yu Gothic, Meiryo)
- **Headings**: Obsidian defaults (no font-family override)
- **Monospace**: SF Mono, Menlo, Consolas, Courier New

## Customization

This theme uses CSS variables for easy customization. You can override colors in a CSS snippet:

```css
/* Obsidian Settings → Appearance → CSS Snippets → Create snippet */
.theme-dark {
  --background-primary: #your-color;
  --interactive-accent: #your-accent;
}
```

## Inspiration

This theme is inspired by the color palette from the "優駿牝馬 2026 回顧録" (Yushun Himba 2026 Review) visualization, which uses turf greens and gold accents to represent horse racing data.

## License

MIT License — feel free to use, modify, and distribute as you see fit.

## Author

[norihito](https://github.com/norihito)

## Credits

- Built following the [Obsidian Theme Development Guide](https://github.com/obsidianmd/obsidian-developer-docs/blob/master/en/Themes/App%20themes/Build%20a%20theme.md)
- Color palette inspired by horse racing data visualization
