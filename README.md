# K-plasma Boot Screen

A minimalist Plymouth boot animation for KDE Plasma, available in both light and dark variants.

![K-plasma Boot Screen Preview](assets/boot%20screen%20preview.png)

## Features

- Clean, minimalist design that complements KDE Plasma
- Light and dark variants to match your system theme
- Smooth animations and transitions
- Progress bar indicating boot status
- Support for system updates and firmware upgrades

## Requirements

- Plymouth boot splash system
- Inter font (recommended for best appearance)

## Installation

### Manual Installation

1. Clone this repository or download it as a ZIP file
2. Copy your preferred theme folder to the Plymouth themes directory:

```bash
# For the dark variant
sudo cp -r "k-plasma Plymouth (Dark)/k-plasma-dark" /usr/share/plymouth/themes/

# For the light variant
sudo cp -r "k-plasma Plymouth (Light)/k-plasma-light" /usr/share/plymouth/themes/
```

3. Set the theme as your default Plymouth theme:

```bash
# For the dark variant
sudo plymouth-set-default-theme k-plasma-dark -R

# For the light variant
sudo plymouth-set-default-theme k-plasma-light -R
```


## License

This project is licensed under the [GNU General Public License v3.0](LICENSE).
