# 🔊 Volume Control Pro

**Volume Control Pro** is an advanced volume management utility for Windows, built with AutoHotkey v2. This tool enhances your system audio control by combining custom hotkey increments with a dynamic visual indicator in the system tray.

---

## ✨ Features

* **Dynamic Tray Icon**: Displays the current volume percentage directly in the system tray.
* **Precision Increments**: Use modifier keys to adjust volume by specific amounts (1%, 2%, 5%, or 10%).
* **Custom OSD**: A sleek On-Screen Display (OSD) appears at the bottom of your screen to confirm volume changes.
* **Tray Interactions**: 
    * **Single-Click**: Toggle mute instantly.
    * **Double-Click**: Open the Windows Volume Mixer.
* **Device Awareness**: Automatically updates when you switch audio playback devices.

---

## ⌨️ Hotkeys

| Key Combination | Action | Increment |
| :--- | :--- | :--- |
| **Volume Up/Down** | Standard adjustment | +/- 5% |
| **Shift + Vol Up/Down** | Fine adjustment | +/- 2% |
| **Alt + Vol Up/Down** | Ultra-fine adjustment | +/- 1% |
| **Ctrl + Vol Up/Down** | Large adjustment | +/- 10% |
| **Volume Mute** | Toggle mute | N/A |

---

## 🛠️ Configuration & Setup

### Requirements
* **AutoHotkey v2.0+**: Required to run the `.ahk` script.
* **Operating System**: Windows 10/11 (Compatible with versions up to 10.0.18362.0).

### Icon Assets
The script requires a folder named `icons` in the same directory as the executable/script.
* **Standard Icons**: `vol_0.ico` through `vol_100.ico`.
* **Mute Icons**: `vol_0_muted.ico` through `vol_100_muted.ico`.
* *Note: `.png` files are also supported if `.ico` files are missing.*

---

## 📜 License

### CC0 1.0 Universal
This project is licensed under the **Creative Commons Legal Code CC0 1.0 Universal**. 

To the extent possible under law, the author(s) have dedicated all copyright and related and neighboring rights to this software to the public domain worldwide. This software is distributed without any warranty.
