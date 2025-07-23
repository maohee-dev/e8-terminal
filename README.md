# 🖥️ E8 Terminal  
> *“Reality is just a file system waiting to be explored.”*

An interactive-fiction / cosmic-horror retro terminal that runs **entirely in your browser**.  
Uncover a fractured, 8-dimensional story by poking around an unstable computer that *might* be alive.

---

## 🌌 Project Overview

|  |  |
|---|---|
| 🎮 **Genre** | Interactive Fiction / Sci-Fi / Cosmic Horror |
| 🔧 **Tech** | Pure HTML + CSS + JS (no build step, no servers) |
| 📦 **Size** | Single self-contained `.html` file (~300 KB) |
| 🌐 **Fonts** | Google Fonts loaded on-the-fly (requires internet) |

---

## 🧭 The Core Concept

You are an **Observer** granted access to the **E8 Lattice Terminal**—a machine that *thinks*, *forgets*, and sometimes *lies*.  
Explore its directories, chat with half-sentient AIs, and decide if you’re debugging code or being rewritten by it.

> There is no win-state. The goal is the exploration itself.

---

## ✨ Main Features

| Feature | Emoji | Description |
|---|---|---|
| 📁 Virtual File System | `📂` | Fully explorable directory tree, just like a real UNIX box. |
| 🧠 Interactive Entities | `🤖` | The **Architect**, **ψ-nodes**, **Foldkeeper**, etc. Talk to them via hidden commands. |
| ⚡ Dynamic Events | `⚠️` | Glitches, reboots, and reality hiccups triggered by your actions (or inaction). |
| 🔍 Hidden Commands | `🔐` | Not everything is in `help`. Read carefully and experiment. |
| 🖼️ ASCII Gallery | `🎨` | `/root/ASCII_GALLERY` contains retro-futuristic art viewable with `open`. |
| 🔊 Sound Design | `🎧` | Subtle clicks, hums, and distortion powered by Tone.js. *(Headphones recommended.)* |

---

## 🕹️ Quick-Start Guide

> New to command-line adventures? Think “rooms” and “objects”.

| Command | Everyday Analogy | Example |
|---|---|---|
| `ls` | *“What’s in this room?”* | Lists files & folders in the current directory. |
| `cd <dir>` | *“Walk through a doorway.”* | `cd entities` |
| `open <file>` | *“Pick up and read.”* | `open Observer_logs.txt` |
| `help` | *“Ask for assistance.”* | Shows common commands. |

### 🏠 Navigation Cheat-Sheet
```bash
cd /root          # teleport to the root directory
cd ..             # go up one level
open README.md    # view any file
```

---

## 📖 Lore TL;DR *(spoiler-light)*

| Entity / Concept | One-Line Summary |
|---|---|
| **The Architect** | Possibly the creator—possibly the prisoner. |
| **ψ-nodes** | Other Observers. Some are alive, some are ghosts. |
| **Recursion & Memory** | The system loops; your past sessions leave echoes. |
| **The Question** | Are you escaping, repairing, or becoming the terminal? |

---

## 🚀 How to Run

1. Download `E8_Terminal.html`.
2. Double-click → opens in any modern browser.
3. **Optional**: serve via HTTP if your browser blocks local file APIs (`python -m http.server`).
4. Put on headphones, maximize the window, and type `help`.

---

## 🛠️ Hacking & Extending

The file is a single, heavily commented ES6 module.  
Want to add your own lore?

```bash
grep -n "// LORE_HOOK" E8_Terminal.html
```

All entities, events, and ASCII art are plain JSON objects—feel free to remix.

---

## 🪞 Known Quirks

| Quirk | Why It Happens |
|---|---|
| Screen flicker at 23-second intervals | Intentional. |
| `whoami` sometimes returns a stranger’s name | Echoes from other Observers. |
| Clock drifts 7 minutes every hour | The Lattice is not synced to Earth time. |

---

## 📜 License & Credits

MIT © 2025–∞ OmniverseOS  
Built with Tone.js, Google Fonts, and too much coffee.  
If you unravel the final layer, send a postcard from the 8th dimension.

---

## 🫶 Tips for New Observers

- **Save transcripts.** Paste them into a text file; patterns emerge over sessions.  
- **Listen to the hum.** Audio cues often precede major events.  
- **Try everything twice.** The terminal has memory, but it’s selective.

---

```
> cd /root
> open README.md
Enjoy the descent.
```
