# bspwm-dotfiles



Custom [bspwm](https://github.com/baskerville/bspwm) dotfiles for a minimalist and efficient tiling window manager setup on [Arch Linux](https://archlinux.org/). 
This setup includes configurations for various utilities to help you get a smooth and productive environment. From a dynamic tiling window manager and a beautiful status bar to keybindings, terminal setup, and much more, these dotfiles will elevate your Linux experience.

# Preview

Here’s what the setup looks like:

![Screenshot1](https://github.com/user-attachments/assets/7cd75b10-3b23-42e6-9ec3-44625d3d3338)

![Screenshot2](https://github.com/user-attachments/assets/84b61b43-c24b-457c-aa53-094f5e1d42f4)

![Screenshot3](https://github.com/user-attachments/assets/8306d432-445f-4aff-aa26-48437bb7b10d)

![Screenshot4](https://github.com/user-attachments/assets/5e73970f-d216-4343-9ccf-3dd6b009a92b)

![Screenshot5](https://github.com/user-attachments/assets/02f60f5e-5d1c-41ef-8540-c3bb9a0cbc52)

![Screenshot6](https://github.com/user-attachments/assets/0ec35983-6ed6-4a86-99b2-31581b7357f9)

![Screenshot7](https://github.com/user-attachments/assets/df368305-e883-46ae-b85e-219c08f64788)

## Overview

This repository contains configurations for:

- **vim** configuration
- [**bash**](https://github.com/ohmybash/oh-my-bash) Shell configuration
- [**bspwm**](https://github.com/baskerville/bspwm) configuration
- [**sxhkd**](https://github.com/baskerville/sxhkd) key bindings configuration
- [**polybar**](https://github.com/polybar/polybar) configuration
- [**rofi**](https://github.com/davatorium/rofi) application launcher configuration
- [**betterlockscreen**](https://github.com/betterlockscreen/betterlockscreen) configuration
- [**dunst**](https://github.com/dunst-project/dunst) notification daemon configuration
- [**alacritty**](https://github.com/alacritty/alacritty) terminal emulator configuration
- [**fastfetch**](https://github.com/fastfetch-cli/fastfetch) display a stylish system info
- [**mpd**](https://github.com/MusicPlayerDaemon/MPD) music player daemon configuration
- [**picom**](https://github.com/jonaburg/picom) compositor configuration

# Requirements

Before you begin, make sure you have the following packages installed on your system.

On Arch Linux:
```bash
sudo pacman -S git bspwm sxhkd polybar rofi dunst alacritty fastfetch mpd picom vim nitrogen pamixer brightnessctl
```

On Debian:
```bash
sudo apt install git bspwm sxhkd polybar rofi dunst alacritty fastfetch mpd picom vim nitrogen pamixer brightnessctl
```

# Installation

Clone the repository:
```bash
git clone https://github.com/Wnanovex/bspwm-dotfiles.git
cd bspwm-dotfiles
```

Manually copy or symlink the configs to the appropriate locations (e.g., `~/.config/` or root as needed), or use a dotfile manager like [GNU Stow](https://www.gnu.org/software/stow/).


# Keybindings

| **Keybinding**           | **Action**                                                             |
|--------------------------|------------------------------------------------------------------------|
| **`Super + Return`**        | Launches **Alacritty** (terminal emulator)                             |
| **`Super + p`**             | Launches **dmenu** to run any application                              |
| **`Super + Space`**         | Launches **Rofi** for application launching using `launcher.sh`        |
| **`Super + Shift + p`**     | Launches **Rofi** for the power menu using `powermenu.sh`              |
| **`Super + Shift + b`**     | Launches **Rofi** for Polybar theme selection using `polybar-themes.sh` |
| **`Super + d`**             | Launches **Dolphin** (file manager)                                   |
| **`Super + w`**             | Launches **Firefox** (web browser)                                    |


# Fonts

The fonts used in this setup are:
- **Fantasque Sans Mono**
- **Feather Icons**
- **Iosevka Nerd Font**
- **Material Design Iconic Font**
- **Meslo Nerd Font**
- **Waffle Bitmap Font**
