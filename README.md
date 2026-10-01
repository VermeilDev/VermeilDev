<div align="center">

# `VERMEIL DEV` // OPERATOR HUB

<p align="center">
  <strong>TACTILE · ZERO-TELEMETRY · MINECRAFT CLIENT SUITE</strong>
</p>

<p align="center">
  <a href="https://vermeillauncher.app/"><img src="https://img.shields.io/badge/Website-vermeillauncher.app-2dd4ef?style=flat-square&logo=cloudflare&logoColor=white&labelColor=15141a" alt="Website" /></a>
  <a href="https://github.com/VermeilDev/Vermeil-Launcher"><img src="https://img.shields.io/badge/Launcher-Tauri%202%20%7C%20Rust-8b5cf6?style=flat-square&logo=tauri&logoColor=white&labelColor=15141a" alt="Launcher" /></a>
  <a href="https://github.com/VermeilDev/vermeil-companion"><img src="https://img.shields.io/badge/Companion-Minecraft%20Mod-ec4899?style=flat-square&logo=openjdk&logoColor=white&labelColor=15141a" alt="Companion" /></a>
  <a href="https://vermeillauncher.app/privacy.html"><img src="https://img.shields.io/badge/Telemetry-0%25%20Verified-10b981?style=flat-square&logo=gnuprivacyguard&logoColor=white&labelColor=15141a" alt="Privacy" /></a>
</p>

</div>

---

### 🎛️ Operator Bento Deck

```text
┌──────────────────────────────────────────────┬──────────────────────────────────────────────┐
│ [DESKTOP CLIENT]                             │ [MINECRAFT MOD]                              │
│ VERMEIL LAUNCHER                             │ VERMEIL COMPANION                            │
│                                              │                                              │
│ • Tauri 2 · Rust 2021 · SolidJS              │ • Modern Stonecutter Matrix (Fabric/NeoForge)│
│ • Sub-millisecond manifest disk caching      │ • Legacy PvP Forge 1.8.9 Coremod (ASM hook)  │
│ • Win32 COM shell icon & taskbar sync        │ • Dynamic in-game capes & client sync        │
│ • 3D WebGL Character Studio & cape editor    │ • Zero game-loop latency or tick overhead    │
│ → github.com/VermeilDev/Vermeil-Launcher     │ → github.com/VermeilDev/vermeil-companion    │
├──────────────────────────────────────────────┼──────────────────────────────────────────────┤
│ [PRIVACY INVARIANT]                          │ [CLOUD ENGINE]                               │
│ ZERO TELEMETRY                               │ SANDBOXED SETTINGS ROAMING                   │
│                                              │                                              │
│ • 0 Analytics · 0 Beacons · 0 Profiling      │ • Google Drive sandboxed appDataFolder       │
│ • Clean audited codebase (automated gate)    │ • Client-side DPAPI encryption at rest       │
│ • Offline gameplay never blocked on network  │ • Strict local preservation of RAM & display │
│ → vermeillauncher.app/privacy                │ → vermeillauncher.app                        │
└──────────────────────────────────────────────┴──────────────────────────────────────────────┘
```

---

### 🛠️ Ecosystem Repositories & Toolchains

| Project | Role / Scope | Core Toolchains | Status / Repository |
| :--- | :--- | :--- | :---: |
| **Desktop Launcher** | High-performance Minecraft: Java Edition desktop client | Rust 2021 · Tauri 2 · SolidJS · Vite | [`Vermeil-Launcher`](https://github.com/VermeilDev/Vermeil-Launcher) |
| **Companion Mod** | In-game client integration & custom cape renderer | Java 8/25 · Loom · ForgeGradle · Stonecutter | [`vermeil-companion`](https://github.com/VermeilDev/vermeil-companion) |
| **Cloud Engine** | Sandboxed, zero-telemetry cross-device profile sync | RFC 7009 · DPAPI · POSIX 0600 · Google Drive | [`Zero-Telemetry`](https://vermeillauncher.app/privacy.html) |
| **Edge Distribution** | Fast web portal, asset CDN & documentation | Cloudflare Workers · Static Pipeline · HSTS | [`vermeillauncher.app`](https://vermeillauncher.app/) |

---

### ⚡ Architectural Principles ("Ponytail" Mode)

1. **The Ponytail Rule**: The best code is the code never written. Zero unrequested abstractions, zero-copy borrowed flows, and sub-millisecond local disk caching.
2. **Tactile Mechanical Design**: Chunky 3D mechanical bevels, recessed sunken wells (`#0f0e13`), 3px left category accents, and zero decorative fluff.
3. **Download-on-Demand Mod Lifecycle**: Launcher downloads verified companion jars via cryptographically verified `companion-manifest.json` on launch without bundling bloatware.

---

### 🚀 Quick Dispatch

* 🌐 **Web Portal**: [vermeillauncher.app](https://vermeillauncher.app/)
* 🖥️ **Launcher Repository**: [VermeilDev/Vermeil-Launcher](https://github.com/VermeilDev/Vermeil-Launcher)
* 🧩 **Companion Mod Repository**: [VermeilDev/vermeil-companion](https://github.com/VermeilDev/vermeil-companion)
* 🛡️ **Security Policy**: [Responsible Disclosures](https://github.com/VermeilDev/Vermeil-Launcher/security)

<div align="center">
  <sub>SYSTEM: VERMEIL OPERATOR ENVIRONMENT · INVARIANT: TACTILE PRECISION</sub>
</div>