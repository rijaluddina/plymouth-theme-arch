# Plymouth Theme Arch

Minimal Arch Linux Plymouth theme.

## Preview

![Boot Preview](arch.png)

## Installation

Ensure you are in this project directory, then run the following command:

```bash
makepkg -si
```

This command will build the package and install it to your system automatically.

## Usage

After installation is complete, you can enable the theme with the command:

```bash
sudo plymouth-set-default-theme -R arch
```

Then rebuild the initramfs image:

```bash
sudo mkinitcpio -P
```
