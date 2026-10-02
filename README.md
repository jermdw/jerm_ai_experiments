# jerm_ai_experiments

[![GitHub Pages](https://img.shields.io/badge/docs-GitHub_Pages-blue?style=flat-square&logo=github)](https://j3rmbadger.com/jerm_ai_experiments/)
[![Jellyfin](https://img.shields.io/badge/Media%20Server-Jellyfin-purple?style=flat-square&logo=jellyfin)](guides/home-media-server.md)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg?style=flat-square)](LICENSE)

A collection of AI experiments, homelab setup guides, and technical walkthroughs.

> 🌐 **Interactive Documentation Site**: Read with custom navigation, dark mode, and search at [j3rmbadger.com/jerm_ai_experiments](https://j3rmbadger.com/jerm_ai_experiments/)

---

## 📚 Guides & Walkthroughs

### 🎬 [Home Media Server Setup Guide (Old Intel i7 Edition)](guides/home-media-server.md)
A comprehensive guide to repurposing an old Intel Core i7 PC into a high-performance, power-efficient home media server.
- **Hardware Acceleration**: Intel Quick Sync Video (QSV) transcode capabilities across CPU generations.
- **Operating Systems**: Ubuntu Server 24.04 LTS vs Debian, TrueNAS SCALE, Unraid, and Proxmox VE.
- **BIOS & Hardware Tuning**: Headless boot, AC power recovery, and iGPU configuration.
- **Storage**: Automounting media drives persistently using `/etc/fstab`.
- **Docker Compose**: Production-ready Jellyfin stack with `/dev/dri` hardware acceleration passthrough.
- **Security & Remote Access**: Zero-port-forwarding remote streaming via Tailscale.
- **Arr Stack Overview**: Radarr, Sonarr, Prowlarr, and Jellyseerr companion services.

---

## 🛠 Project Structure

```text
.
├── index.html                  # Docsify single-page documentation app for GitHub Pages
├── _sidebar.md                 # Navigation sidebar for Docsify
├── .nojekyll                   # Bypasses Jekyll processing for GitHub Pages
├── guides/
│   └── home-media-server.md    # Dedicated Intel i7 Media Server guide
└── prompts/                    # Experiment prompt archives
```
