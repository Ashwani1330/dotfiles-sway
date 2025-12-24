# Dotfiles (SwayFX)

Minimalist configuration for SwayFX (Wayland).

## Preview
<img width="1600" height="900" alt="Desktop Preview" src="https://github.com/user-attachments/assets/c59d7526-c87b-42d6-b585-a51255bc480a" />

## Components

| Component | Application | Notes |
| :--- | :--- | :--- |
| **Window Manager** | [SwayFX](https://github.com/WillPower3309/swayfx) | Blur & Radius enabled |
| **Bar** | [Waybar](https://github.com/Alexays/Waybar) | Custom CSS & Modules |
| **Terminal** | [Kitty](https://sw.kovidgoyal.net/kitty/) | Catppuccin Mocha Theme |
| **Launcher** | [Rofi](https://github.com/davatorium/rofi) | Run / Drun modes |
| **Lock Screen** | [Swaylock](https://github.com/swaywm/swaylock) | Custom ring colors |
| **Notifications** | [Mako](https://github.com/emersion/mako) | Minimalist daemon |
| **Compositor** | Native | SwayFX handles composition |

## Theming

* **Palette:** Catppuccin Mocha
* **Bar Font:** SF Pro Text, Inter, NotoSans Nerd Font
* **Terminal Font:** FiraCode Nerd Font Mono
* **Icons:** Oranchelo
* **Wallpaper:** Managed via Sway config

## Key Bindings

| Keybind | Action |
| :--- | :--- |
| `Mod` + `Enter` | Terminal |
| `Mod` + `d` | App Launcher |
| `Mod` + `n` | File Manager |
| `Mod` + `Shift` + `q` | Kill Focused Window |
| `Mod` + `Shift` + `s` | Screenshot (Region) |
| `Mod` + `Shift` + `x` | Lock Screen |
| `Mod` + `Shift` + `c` | Reload Config |
| `Mod` + `Shift` + `e` | Exit Session |

## Utilities Setup

* **Screenshot:** `grim` + `slurp` (Copies to clipboard)
* **Clipboard:** `greenclip` daemon
* **Auth Agent:** `polkit-gnome`
* **Tiling:** `autotiling` script

---

### Sources
* **Waybar Config Base:** [Prateek7071/dotfiles](https://github.com/Prateek7071/dotfiles)
* **Wallpapers:** [dharmx/walls](https://github.com/dharmx/walls)
