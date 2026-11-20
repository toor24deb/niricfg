# niricfg
A set of Arch Linux Niri configuration files for VirtualBox in style of  🟣 catppuccin mocha
<a href="https://i.ibb.co/hF98Sxz8/image.png"><img src="https://i.ibb.co/hF98Sxz8/image.png" alt="image" border="0"></a>

## 📦 Components

This repository contains configurations for the following components:
*   **[Niri](https://github.com/YaLTeR/niri)** — the main scrollable-tiling Wayland compositor.
*   **[Waybar](https://github.com/Alexays/Waybar)** — highly customizable Wayland bar.
*   **[Alacritty](https://github.com/alacritty/alacritty)** — GPU-accelerated terminal emulator.
*   **[Fuzzel](https://codeberg.org/dnkl/fuzzel)** — application launcher for Wayland.
*   **[awww](https://codeberg.org/LGFae/awww)** — wallpaper daemon for Wayland.

## Binds:
Super + Z - change background with awww

# 🚀 Installation

1. ## Clone the repository into your home directory:
   ```bash
   git clone https://github.com/toor24deb/niricfg
   ```

2. ## Install dependencies:
   **Official packages**
   ```bash
   sudo pacman -S --needed - < ~/niricfg/official_packages.txt
   ```
   
   **Install AUR packages (requires yay or paru)**
   ```bash
   yay -S --needed - < ~/niricfg/aur_packages.txt
   ```

3. ## Deploy the configuration:
   **Copy configuration files**
   ```bash
   cp -r ~/niricfg/config/* ~/.config/
   ```

   **Copy shell files**
   ```bash
   cp ~/niricfg/.bashrc ~/
   cp ~/niricfg/.bash_profile ~/
   ```
