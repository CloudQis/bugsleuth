# 🕵️‍♂️ BugSleuth – The Ethical Glitch Explorer for Minecraft

> **See the glitch. Learn the mechanic. Respect the game.**

BugSleuth is a **client-side Fabric mod** for Minecraft Java Edition that **detects known bugs and glitches in real time** — strictly for **educational, testing, and learning purposes**. It helps you understand *how* exploits work, *why* they exist, and *whether* a world is vulnerable — **without ever automating abuse or connecting to external servers**.

✅ 100% local  
✅ No telemetry, no internet  
✅ Open source (MIT)  
✅ Works on **any server** (but only *detects*, never *exploits*)  
✅ Built for **learners**, **builders**, and **ethical players**

---

## 🚫 Important: What This Is NOT

- ❌ **NOT** an exploit tool  
- ❌ **NOT** for cheating on public servers (Hypixel, 2b2t, etc.)  
- ❌ **NOT** a hacking or cheating mod  
- ❌ **Does NOT** trigger, automate, or assist in performing glitches  

> **Abusing bugs on servers you don’t own violates Mojang’s EULA, server rules, and community trust.**  
> BugSleuth is designed to **prevent accidental abuse** and **promote understanding** — not enable it.

---

## 🎯 Who Is This For?

- 🧱 **Map & adventure creators** testing for unintended mechanics  
- ⚡ **Speedrun learners** studying glitch boundaries safely  
- 🔌 **Redstone engineers** debugging odd behavior  
- 🛠️ **Server owners** checking if their world is patched  
- 🤔 **Curious players** who want to *understand* Minecraft deeply  

---

## 📦 Features

- **Tweakeroo-style HUD** – Clean, minimal warnings (e.g., `⚠️ Shulker Dupe: PATCHED`)  
- **50+ passive detectors** – Duplication, movement, block, redstone, and inventory bugs  
- **In-game config (`F8`)** – Toggle detectors, adjust HUD, enable safe mode  
- **Local logging only** – All data stays on your machine  
- **Version-aware** – Knows if a bug was patched in 1.19.4, 1.20, etc.  
- **Zero performance impact** – Lightweight and efficient  

---

## 🧪 Example Detections

| Bug | Detection Message |
|-----|------------------|
| Shulker Box Dupe | `⚠️ Shulker Dupe: 1.19.4+ PATCHED (some server are not patched yet)` |
| Boat Fly | `🔍 Boat Fly: POSSIBLE (unpatched server)` |
| Ghost Blocks | `💡 Ghost Block detected at X:120 Y:64 Z:-32` |
| Villager Z-Fight | `⚠️ Villager breeder glitch active` |

> All detections are **passive observations** — **no actions are taken**.

---

## 🛠️ Installation

1. Install [Fabric Loader](https://fabricmc.net/use/) for **Minecraft 1.20.1**
2. Download the latest `bugsleuth-*.jar` from [Releases](https://github.com/CloudQis/bugsleuth/releases)
3. Place it in your `.minecraft/mods/` folder
4. Launch Minecraft → Play!
5. Press **`F8`** to open the config menu

> ✅ Works on **vanilla**, **Paper**, **Purpur**, and **any server** — no server mod needed.

---

## 🔒 Code of Ethical Use

By using BugSleuth, you agree to:

- ✅ Use detections **only in single-player** or **servers you own/admin**
- ✅ Use knowledge to **learn**, **test**, or **report bugs responsibly**
- ❌ **Never** use detected exploits on public or community servers
- ❌ **Never** redistribute modified versions that enable automation

> *"Knowing a glitch isn’t about breaking the game — it’s about understanding it."*

---

## 📚 Companion App (Planned)

A standalone desktop app is in development to provide:
- Full **Bug Encyclopedia** with GIF demos
- One-click **test world generation**
- **Bug report templates** for server owners
- **Offline-only** — no cloud, no tracking

> Stay tuned on [GitHub Projects](https://github.com/CloudQis/bugsleuth/projects)!

---

## 🧑‍💻 Build From Source

```bash
git clone https://github.com/CloudQis/bugsleuth.git
cd bugsleuth
./gradlew build
