# 🎨 Clone Hero Custom Name Generator

Create unique and visually stunning custom player names for Clone Hero with gradient colors, individual letter styling, and direct export to your profile.

[![Python Version](https://img.shields.io/badge/python-3.6%2B-blue)](https://python.org)
[![Platform](https://img.shields.io/badge/platform-Windows-blue)](https://github.com/iamjrmh/CHColorGen)
[![License](https://img.shields.io/badge/license-MIT-green)](https://github.com/iamjrmh/CHColorGen)

---

## THIS REPO IS NO LONGER MAINTAINED.
For the most up-to-date Clone Hero modding programs, check out my AIO [CHSuite.](https://github.com/iamjrmh/CHSuite) All future updates to my programs will be through here. Thank you!

---

## ✨ Features

- **Gradient Name Generation** - Create smooth color gradients across your player name with multiple color stops
- **Individual Letter Coloring** - Assign unique colors and styling to each letter independently
- **Advanced Text Styling** - Bold, italic, underline, and strikethrough options for maximum customization
- **Global Font Controls** - Adjust font size and character spacing for perfect visual balance
- **Live Preview** - Real-time visual feedback as you design your name
- **Direct Export** - One-click export to `profiles.ini` ready for Clone Hero
- **Intuitive Interface** - Modern, user-friendly GUI built with Tkinter

## 🚀 Quick Start

### Installation (Windows Executable)

1. **Download** the latest `.exe` from the [Releases](https://github.com/iamjrmh/CHColorGen/releases) page
2. **Extract** the zip file to your preferred location
3. **Run** `jrmh.rh Name Gen.exe`

No Python installation required!

## 🎨 Creating Your Custom Name

### Gradient Mode

Perfect for smooth, flowing color transitions across your entire name.

1. **Switch to "Gradient" tab** (may be labeled "Home")
2. **Enter your name** in the "Name:" field
3. **Choose colors**:
   - Select **Start Color** and **End Color**
   - Optionally add up to 3 intermediate colors for complex gradients
4. **Apply styling** (optional): Bold, Italic, Underline, Strikethrough
5. **Adjust spacing** (optional): Font Size, Character Spacing
6. **Click "Generate"**
7. **Preview** your name in real-time

### Individual Letter Mode

Perfect for rainbow effects or unique per-character styling.

1. **Switch to "Single Letter Coloring" tab**
2. **Enter your name** in the "Name:" field
3. **Click "Update Letters"** to generate controls for each character
4. **Customize each letter**: color, Bold, Italic, Underline, Strikethrough
5. **Set global controls** (optional): Font Size, Character Spacing
6. **Click "Generate"**
7. **Preview** your creation

## 📁 File Locations

| File | Location |
|---|---|
| Clone Hero Profiles | `Documents\Clone Hero\profiles.ini` |

## 🎨 Color Format

Colors use standard hex format: `#RRGGBB`

**Examples:** `#FF0000` Red · `#00FF00` Green · `#0000FF` Blue · `#FF00FF` Magenta · `#FFFF00` Yellow

**Tips:**
- Use [coolors.co](https://coolors.co) to find color schemes
- High contrast colors make names more readable
- Test in-game to ensure visibility against backgrounds

## 🐛 Troubleshooting

**Export button doesn't work**
`profiles.ini` is in use or read-only. Close Clone Hero and ensure the file isn't read-only.

**Preview looks different than in-game**
Preview is approximate. Test in-game for final appearance.

**"Permission denied" error**
Run as administrator or check folder permissions on your Documents folder.

## 💡 Pro Tips

- **Gradient:** Use 2–3 colors for smooth transitions. Similar hues = subtle, contrasting hues = bold.
- **Individual letters:** Red → Orange → Yellow → Green → Blue → Purple for a classic rainbow.
- **Styling:** Bold helps visibility on busy backgrounds. Avoid stacking too many effects at once.

## 🔧 Running from Source

```
pip install tkinter
python "jrmh.rh Name Gen.py"
```

## 📄 License

MIT License - Feel free to use, modify, and distribute.

## ⚠️ Disclaimer

Use at your own risk. I am not responsible for profile data loss.


## 🎮 Related Projects

- [Clone Hero](https://clonehero.net/) - The rhythm game this tool supports
- [CHMenuChanger](https://github.com/iamjrmh/CHMenuChanger) - Swap out Clone Hero's menu background textures
- [CHCleaner](https://github.com/iamjrmh/CHCleaner) - Clean up problematic songs from your library
- [Chorus](https://chorus.fightthe.pw/) - Song database and downloader

---

Made with 🎸 for the Clone Hero community
