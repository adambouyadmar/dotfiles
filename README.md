# 🖥️ Dotfiles

My personal Linux dotfiles for **Arch Linux** running **ML4W (My Linux For Work)**.

## ✨ Features

- Hyprland
- Waybar
- LazyVim
- Kitty
- Rofi
- SwayNC
- Cava
- Fastfetch
- Wlogout
- Spicetify
- Wallpapers

## 📦 Installation

Clone the repository:

```bash
git clone https://github.com/adambouyadmar/dotfiles.git
cd dotfiles
```

Create the configuration directory if it doesn't exist:

```bash
mkdir -p ~/.config
```

Copy all configurations:

```bash
cp -r .config/* ~/.config/
```

Or install only what you need:

```bash
cp -r .config/hypr ~/.config/
cp -r .config/waybar ~/.config/
cp -r .config/kitty ~/.config/
cp -r .config/nvim ~/.config/
```

Restart Hyprland or log out and log back in to apply the changes.

## 📸 Preview

Screenshots coming soon.

## ⚠️ Notes

These dotfiles are made for my personal setup based on **ML4W**. Some components, fonts, themes, or packages may need to be installed separately.

## 📜 License

MIT
