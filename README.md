# BPU Simulator

Official standalone desktop distribution of the Biological Processing Unit (BPU) Simulator.

---

## ⚡ One-Click Direct Downloads (v0.2.1)

Click the badge for your operating system to download the standalone installer directly:

[![Download Windows](https://img.shields.io/badge/Windows-Download%20Installer%20(.exe)-0078D6?style=for-the-badge&logo=windows&logoColor=white)](https://github.com/neurohil/bpusimulator/releases/download/v0.2.1/BPU.Simulator.Setup.0.1.0.exe)
[![Download macOS Apple Silicon](https://img.shields.io/badge/macOS-Apple%20Silicon%20(.dmg)-000000?style=for-the-badge&logo=apple&logoColor=white)](https://github.com/neurohil/bpusimulator/releases/download/v0.2.1/BPU.Simulator-0.1.0-arm64.dmg)
[![Download macOS Intel](https://img.shields.io/badge/macOS-Intel%20x64%20(.dmg)-555555?style=for-the-badge&logo=apple&logoColor=white)](https://github.com/neurohil/bpusimulator/releases/download/v0.2.1/BPU.Simulator-0.1.0.dmg)
[![Download Linux AppImage](https://img.shields.io/badge/Linux-Download%20AppImage-FCC624?style=for-the-badge&logo=linux&logoColor=black)](https://github.com/neurohil/bpusimulator/releases/download/v0.2.1/BPU.Simulator-0.1.0.AppImage)

---

## 📦 Complete Release Packages

All releases are fully compiled standalone desktop applications (compiled with native C extensions and bundled Electron runtime). Zero Python or environment installation required.

| Platform | Architecture | Package Format | Size | Direct Download |
| :--- | :--- | :--- | :--- | :--- |
| **Windows** | 64-bit (x64) | Setup Installer (`.exe`) | ~105 MB | [**BPU.Simulator.Setup.0.1.0.exe**](https://github.com/neurohil/bpusimulator/releases/download/v0.2.1/BPU.Simulator.Setup.0.1.0.exe) |
| **Windows** | 64-bit (x64) | Portable (`.zip`) | ~140 MB | [**BPU.Simulator-0.1.0-win.zip**](https://github.com/neurohil/bpusimulator/releases/download/v0.2.1/BPU.Simulator-0.1.0-win.zip) |
| **macOS** | Apple Silicon (M1/M2/M3/M4) | Disk Image (`.dmg`) | ~121 MB | [**BPU.Simulator-0.1.0-arm64.dmg**](https://github.com/neurohil/bpusimulator/releases/download/v0.2.1/BPU.Simulator-0.1.0-arm64.dmg) |
| **macOS** | Apple Silicon (M1/M2/M3/M4) | Archive (`.zip`) | ~117 MB | [**BPU.Simulator-0.1.0-arm64-mac.zip**](https://github.com/neurohil/bpusimulator/releases/download/v0.2.1/BPU.Simulator-0.1.0-arm64-mac.zip) |
| **macOS** | Intel (x86_64) | Disk Image (`.dmg`) | ~127 MB | [**BPU.Simulator-0.1.0.dmg**](https://github.com/neurohil/bpusimulator/releases/download/v0.2.1/BPU.Simulator-0.1.0.dmg) |
| **macOS** | Intel (x86_64) | Archive (`.zip`) | ~124 MB | [**BPU.Simulator-0.1.0-mac.zip**](https://github.com/neurohil/bpusimulator/releases/download/v0.2.1/BPU.Simulator-0.1.0-mac.zip) |
| **Linux** | 64-bit (x86_64) | Standalone AppImage | ~156 MB | [**BPU.Simulator-0.1.0.AppImage**](https://github.com/neurohil/bpusimulator/releases/download/v0.2.1/BPU.Simulator-0.1.0.AppImage) |
| **Linux** | 64-bit (x86_64) | Tarball (`.tar.gz`) | ~148 MB | [**bpu-simulator-0.1.0.tar.gz**](https://github.com/neurohil/bpusimulator/releases/download/v0.2.1/bpu-simulator-0.1.0.tar.gz) |

You can also browse all assets and release metadata on the [Official Release Page](https://github.com/neurohil/bpusimulator/releases/tag/v0.2.1).

---

## 💻 Installation & Quick Start

### Windows
1. Download [BPU.Simulator.Setup.0.1.0.exe](https://github.com/neurohil/bpusimulator/releases/download/v0.2.1/BPU.Simulator.Setup.0.1.0.exe).
2. Double-click the installer and follow the setup wizard.
3. Open **BPU Simulator** from the Start Menu or Desktop shortcut.

### macOS (Apple Silicon & Intel)
1. Download the `.dmg` corresponding to your Mac processor:
   - [Apple Silicon (M1/M2/M3/M4)](https://github.com/neurohil/bpusimulator/releases/download/v0.2.1/BPU.Simulator-0.1.0-arm64.dmg)
   - [Intel Processor](https://github.com/neurohil/bpusimulator/releases/download/v0.2.1/BPU.Simulator-0.1.0.dmg)
2. Open the `.dmg` disk image and drag **BPU Simulator** into your **Applications** folder.
3. Launch the app. *(On the first run, right-click the app in Applications and click **Open** to confirm macOS Gatekeeper)*.

### Linux
1. Download [BPU.Simulator-0.1.0.AppImage](https://github.com/neurohil/bpusimulator/releases/download/v0.2.1/BPU.Simulator-0.1.0.AppImage).
2. Give execution permission and run:
   ```bash
   chmod +x BPU.Simulator-0.1.0.AppImage
   ./BPU.Simulator-0.1.0.AppImage
   ```

---

## 🔬 About BPU Simulator

The Biological Processing Unit (BPU) Simulator integrates electrophysiological organoid modeling:
- **Olfactory Organoids:** Dual receptor lineages (immature iOR and mature mOR) with dose-response biophysics.
- **Thalamic & Cortical Organoids:** Thalamocortical relay circuitry, synaptic depression/facilitation, and burst dynamics.
- **High-Density MEA:** 1,024-channel microelectrode array rasterization and Local Field Potential (LFP) computation.
