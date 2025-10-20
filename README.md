# Fjord Theme for warp

A dusk-blue base with soft leaf-green accents, amber selections, and crisp blue/cyan separation for the Warp terminal.

## 🎨 Color Palette

### Core Colors

| Color | Name |
| --------------------------------------------------------- | ----------------- |
| ![#1B2532](https://img.shields.io/badge/%231B2532-1B2532) | **background** |
| ![#222E3F](https://img.shields.io/badge/%23222E3F-222E3F) | **backgroundAlt** |
| ![#1F2A39](https://img.shields.io/badge/%231F2A39-1F2A39) | **surface** |
| ![#233141](https://img.shields.io/badge/%23233141-233141) | **line** |
| ![#E8F0F3](https://img.shields.io/badge/%23E8F0F3-E8F0F3) | **foreground** |
| ![#6C7A86](https://img.shields.io/badge/%236C7A86-6C7A86) | **muted** |
| ![#51606B](https://img.shields.io/badge/%2351606B-51606B) | **mutedDim** |

### Accent Colors

| Color | Name |
| --------------------------------------------------------- | ---------------------------- |
| ![#9DD99A](https://img.shields.io/badge/%239DD99A-9DD99A) | **green** _(primary accent)_ |
| ![#5DA6EA](https://img.shields.io/badge/%235DA6EA-5DA6EA) | **blue** |
| ![#FFD285](https://img.shields.io/badge/%23FFD285-FFD285) | **yellow** |
| ![#B9A0F8](https://img.shields.io/badge/%23B9A0F8-B9A0F8) | **purple** |
| ![#F37C7C](https://img.shields.io/badge/%23F37C7C-F37C7C) | **red** |
| ![#B8E7E9](https://img.shields.io/badge/%23B8E7E9-B8E7E9) | **cyan** |
## 📦 Installation


### Manual Installation


1. Clone this repository:

```bash
git clone https://github.com/fjord-theme/fjord-warp.git --depth 1
```




2. Copy the Warp theme to the correct directory
<details>
   <summary>Windows</summary>
   ```powershell
   New-Item -Path "$env:APPDATA\warp\Warp\data\themes\" -ItemType Directory
   cp fjord-warp/themes/fjord.yaml $env:APPDATA\warp\Warp\data\themes\.
   ```
</details>
<details>
   <summary>Mac</summary>
   ```bash
   mkdir -p $HOME/.warp/themes/
   cp fjord-warp/themes/fjord.yaml $HOME/.warp/themes/.
   ```
</details>
<details>
   <summary>Linux</summary>
   ```bash
   mkdir -p ${XDG_DATA_HOME:-$HOME/.local/share}/warp-terminal/themes/
   cp fjord-warp/themes/fjord.yaml ${XDG_DATA_HOME:-$HOME/.local/share}/warp-terminal/themes/.
   ```
</details>
3. Open Warp and go to Settings → Appearance
4. Select the Fjord theme from your themes list





## 🔧 Configuration

The theme includes:

- Complete 16-color terminal palette
- Optimized background and foreground colors
- Custom selection and cursor colors
- Enhanced readability with proper contrast ratios
## 📸 Preview

![Fjord warp Theme](https://raw.githubusercontent.com/fjord-theme/fjord/main/docs/images/colortest.png)


## 🔄 Updates

This theme is automatically generated from the [main Fjord repository](https://github.com/fjord-theme/fjord). For the latest updates, check the main repository.
## ☕ Support My Work

If you enjoy the Fjord theme and find it useful, consider supporting my work:

[![Buy Me A Coffee](https://img.shields.io/badge/Buy_Me_A_Coffee-99dd9a?style=for-the-badge&logo=buy-me-a-coffee&logoColor=FFD285&logoSize=auto&labelColor=1B2532)](https://buymeacoffee.com/jshuntley)
## 📄 License

MIT License - see [LICENSE](LICENSE) file for details.
## 🤝 Contributing

For theme suggestions or issues, please visit the [main Fjord repository](https://github.com/fjord-theme/fjord).