# niricfg
A set of Arch Linux Niri configuration files for VirtualBox in style of  🟣 catppuccin mocha

## 📦 Components

This repository contains configurations for the following components:
*   **[Niri](https://github.com/YaLTeR/niri)** — the main scrollable-tiling Wayland compositor.
*   **[Waybar](https://github.com/Alexays/Waybar)** — highly customizable Wayland bar.
*   **[Alacritty](https://github.com/alacritty/alacritty)** — GPU-accelerated terminal emulator.
*   **[Fuzzel](https://codeberg.org/dnkl/fuzzel)** — application launcher for Wayland.
*   **[awww](https://codeberg.org/dnkl/awww)** — wallpaper daemon for Wayland.

## 🚀 Installation

1. **Clone the repository into your home directory:**
   ```bash
   git clone https://github.com/toor24deb/niricfg
   ```

## Binds:
Super + Z - change background with awww

2. **Install dependencies:**
   # Official packages
   ```bash
   sudo pacman -S --needed - < ~/niricfg/official_packages.txt
   ```
   
# Install AUR packages (requires yay or paru)
   ```bash
yay -S --needed - < ~/niricfg/aur_packages.txt
   ```
3. **Deploy the configuration:**
  # Copy configuration files
```bash
cp -r ~/niricfg/config/* ~/.config/
   ```

  # Copy shell files
   ```bash
cp ~/niricfg/.bashrc ~/
cp ~/niricfg/.bash_profile ~/
   ```
