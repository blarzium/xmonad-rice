# 📁 xmonad-rice

A clean, crisp, and nostalgic minimalism meets modern tiling efficiency. This repository contains my personal dotfiles for a **Windows 95** inspired rice, powered by the **XMonad** window manager. 

> "Start Me Up." — 1995

---

## 📷 Screenshots

| Desktop Empty | Desktop Full |
| --- | --- |
| *<img width="1920" height="1079" alt="2026-05-25_20-35" src="https://github.com/user-attachments/assets/3a89c930-99e5-466b-b092-26021621b8fe" />* | *<img width="1920" height="1080" alt="2026-05-25_20-29" src="https://github.com/user-attachments/assets/b364d6dc-ccc7-44ae-b851-4725ba729775" />
* |

---

## 📦 Dependencies

To replicate this setup, you will need the following core components:

* **Window Manager:** `xmonad` (with `xmonad-contrib`)
* **Status Bar:** `polybar`
* **Application Launcher:** `rofi`
* **Terminal Emulator:** `kitty`
* **Theme & Icons:** [Chicago95](https://github.com/grassmunk/Chicago95) (GTK engine and icon pack)
* **Qt6 Applications:** Configured to inherit GTK styles (via `qt6ct`)
* **Web Browser:** `brave` (using the Windows 95 theme from the Chrome Web Store)
* **Wallpaper:** A solid teal/gray-green color (`#008080`)

---

## 🚀 Quick Installation

Follow these steps to deploy the configuration on your system:

### 1. Clone and Copy Dotfiles
Clone this repository and copy the configurations directly into your `~/.config` directory:

```bash
git clone [https://github.com/blarzium/xmonad-rice.git](https://github.com/blarzium/xmonad-rice.git)
cd xmonad-rice
cp -r xmonad polybar picom rofi kitty ~/.config/
