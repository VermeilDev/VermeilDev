<div align="center">

# Vermeil

<p align="center">
  <strong>A modern, tactile, and privacy-focused Minecraft: Java Edition desktop ecosystem.</strong>
</p>

<p align="center">
  <a href="https://vermeillauncher.app/"><img src="https://img.shields.io/badge/Website-vermeillauncher.app-2dd4ef?style=flat-square&logo=cloudflare&logoColor=white&labelColor=15141a" alt="Website" /></a>
  <a href="https://github.com/VermeilDev/Vermeil-Launcher"><img src="https://img.shields.io/badge/Launcher-Tauri%202%20%7C%20Rust-8b5cf6?style=flat-square&logo=tauri&logoColor=white&labelColor=15141a" alt="Launcher" /></a>
  <a href="https://github.com/VermeilDev/Vermeil-Companion"><img src="https://img.shields.io/badge/Companion-Minecraft%20Mod-ec4899?style=flat-square&logo=openjdk&logoColor=white&labelColor=15141a" alt="Companion" /></a>
  <a href="https://vermeillauncher.app/privacy.html"><img src="https://img.shields.io/badge/Telemetry-0%25%20Verified-10b981?style=flat-square&logo=gnuprivacyguard&logoColor=white&labelColor=15141a" alt="Privacy" /></a>
</p>

</div>

---

### 🛠️ Ecosystem Repositories

| Project | Description | Primary Toolchains | Repository |
| :--- | :--- | :--- | :--- |
| **Vermeil Launcher** | Desktop launcher with tactile design and zero telemetry | Tauri 2 · Rust · SolidJS · TypeScript | [`Vermeil-Launcher`](https://github.com/VermeilDev/Vermeil-Launcher) |
| **Vermeil Companion** | Client companion mod for capes, cosmetics, and settings sync | Java (JDK 25 / JDK 8) · Stonecraft · Mixins | [`Vermeil-Companion`](https://github.com/VermeilDev/Vermeil-Companion) |
| **Cloud Settings Roaming** | Zero-telemetry portable settings sync via Google Drive | RFC 7009 · DPAPI / POSIX 0600 · Sandboxed | [`Privacy Policy`](https://vermeillauncher.app/privacy.html) |
| **Web Portal & Distribution** | Web landing page, static documentation, and updates | Cloudflare Workers & Pages | [`vermeillauncher.app`](https://vermeillauncher.app/) |

---

### ✨ Key Features & Design

* 🎛️ **Tactile Bento Design System**: Custom modern UI featuring modular Bento card grids, tactile switches, sunken recessed wells, and in-process Win32 shell icon synchronization.
* 🛡️ **Zero Telemetry & Local-First**: Complete user privacy. No telemetry beacons, no analytics, no background tracking. Credentials and session tokens are encrypted at rest with hardware-backed DPAPI or POSIX permissions.
* 🎴 **3D Character Studio & Custom Capes**: Built-in WebGL skin and cape designer supporting static and animated capes, baked directly into the companion mod without network overhead.
* ⚡ **High-Performance Launch Pipeline**: Sub-millisecond loader profile caching, multi-threaded asset downloads with bounded concurrency, and offline launch support.
* 🧩 **Download-on-Demand Companion Mod**: The client companion mod is never bundled into the launcher binary; verified jars are resolved cryptographically at launch via SHA-1 hashes.

---

### 💡 Engineering Philosophy ("Ponytail" Mode)

Our codebase and engineering workflows are guided by the **"Ponytail" Lazy Senior Dev** decision ladder (adapted from [Dietrich Gebert](https://github.com/DietrichGebert/ponytail)):

* **Efficiency Over Excess**: Lazy means efficient, not careless. The best code is the code never written.
* **The Decision Ladder**: Stop at the first rung that holds — Does it need to be built at all? (YAGNI) $\to$ Does it already exist in the codebase? $\to$ Does the standard library do this? $\to$ Does a native platform feature cover it? $\to$ Does an installed dependency solve it? $\to$ Shortest working diff wins.
* **Root Causes Over Symptoms**: Grep every caller; fix the shared root cause once rather than patching symptoms.
* **Zero Unrequested Abstractions**: Deletion over addition. Boring over clever. Fewest files possible.

---

### 🚀 Quick Dispatch

* 🌐 **Web Portal**: [vermeillauncher.app](https://vermeillauncher.app/)
* 🖥️ **Launcher Repository**: [VermeilDev/Vermeil-Launcher](https://github.com/VermeilDev/Vermeil-Launcher)
* 🧩 **Companion Mod Repository**: [VermeilDev/Vermeil-Companion](https://github.com/VermeilDev/Vermeil-Companion)
* 🛡️ **Security Policy**: [Vermeil Security Policy](https://github.com/VermeilDev/Vermeil-Launcher/blob/main/SECURITY.md)

<div align="center">
  <sub>VERMEIL ECOSYSTEM · FREE & OPEN SOURCE UNDER GNU GPLv3</sub>
</div>