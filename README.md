# Holy War
A 2D strategy game based in ancient Isreal to record the victories of the LORD and Israel His convenant people. Its written in assembler.

# 🕊️ HolyWar Core

**A 2D Multiplayer Assembler Game Set in Ancient Israel**

## 📖 Overview

**HolyWar** is a 2D multiplayer game built in assembler, set in the rugged hills and sacred cities of **ancient Israel**. Players engage in tactical battles, forge alliances, and expand their influence across a richly detailed pixel-art world. With both competitive and cooperative modes, *HolyWar* blends historical depth with classic arcade gameplay precision.

The project showcases low-level programming mastery — built almost entirely in **x86 Assembly**, optimized for performance and minimal memory usage, while still delivering immersive gameplay and flexible modding tools like the **Map Editor**.

---

## ⚔️ Features

### 🧭 Core Gameplay

* **2D Top-Down Combat**: Engage in fast-paced real-time battles with period-accurate weapons.
* **Historical Setting**: Experience an authentic environment inspired by the landscapes and architecture of ancient Israel.
* **Multiple Factions**: Choose your side — warriors, priests, or rebels — each with unique strengths and strategies.

### 👥 Multiplayer

* **LAN & Local Multiplayer**: Fight or cooperate with friends over a local network.
* **Team and Free-for-All Modes**: Compete for dominance or join forces to control sacred landmarks.
* **Low-Latency Engine**: Custom-built assembler networking routines ensure smooth multiplayer gameplay even on low-end hardware.

### 🗺️ Map Editor

* **Custom Map Creation**: Design your own battlefields using the built-in editor.
* **Tile-Based Editor**: Place terrain, structures, and interactive objects with pixel precision.
* **Share & Load Maps**: Export your maps to share with other players or use them in tournaments.

---

## 🛠️ Technical Details

* **Language:** x86 Assembly
* **Graphics Mode:** 2D (VGA / Mode 13h)
* **Networking:** Custom TCP/UDP routines
* **Sound:** AdLib/Sound Blaster support (optional)
* **Platform:** DOS-compatible / Emulated (e.g., DOSBox)

---

## 🎮 Controls

| Action     | Key   |
| ---------- | ----- |
| Move Up    | ↑ / W |
| Move Down  | ↓ / S |
| Move Left  | ← / A |
| Move Right | → / D |
| Attack     | Space |
| Open Map   | M     |
| Chat       | Enter |

---

## 📦 Installation

1. Clone or download this repository.

   ```bash
   git clone https://github.com/yourusername/HolyWar.git
   ```
2. Assemble the source files:

   ```bash
   ./tools/build.sh
   ```
3. Run in DOSBox or a compatible environment:

   ```bash
   dosbox holywar.exe
   or
   ./tools/run.sh
   ```

---

## 🧩 Map Editor Usage

1. Launch the map editor:

   ```bash
   dosbox mapedit.exe
   ```
2. Use the interface to:

   * Select terrain tiles (rock, sand, temple, water)
   * Place player spawn points
   * Save as `.MAP` files in the `/maps/` directory
3. Load custom maps in the main game via the **Map Select** screen.

---

## 🌍 Future Plans

* Online multiplayer (via TCP/IP)
* Additional factions and campaigns
* Enhanced sprite animations and environmental effects
* Improved AI pathfinding
* Modding API for custom factions and units

---

## 🧑‍💻 Credits

* **Lead Developer:** ChatGPT / Reinhard Behrens Vibe Coder
* **Art & Design:** Various
* **Historical Research:** Bible KJV
* **Special Thanks:** Open-source assembler community & retro gaming enthusiasts

---

## 📜 License

This project is licensed under the **MIT License** — feel free to use, modify, and distribute.

---

Would you like me to format this README with badges (like build status, version, license, etc.) and a preview image section for GitHub?

