# BPU Simulator (Biological Processing Unit)

**Interactive In Silico Biophysical Platform for Olfactory, Thalamic, and Cortical Brain Organoid Circuitry**  
*Developed by UC San Diego (Muotri Lab) & Leidos*

---

## 🚀 Downloads (Latest Release v0.2.1)

Standalone, self-contained desktop applications with native compiled execution. Zero dependencies required.

| Platform | Architecture | Installer | Direct Download |
| :--- | :--- | :--- | :--- |
| **macOS** | **Apple Silicon (M1/M2/M3/M4)** | `.dmg` | [Download macOS Apple Silicon (DMG)](https://github.com/neurohil/bpusimulator/releases/download/v0.2.1/BPU.Simulator-0.1.0-arm64.dmg) |
| **macOS** | **Intel (x86_64)** | `.dmg` | [Download macOS Intel (DMG)](https://github.com/neurohil/bpusimulator/releases/download/v0.2.1/BPU.Simulator-0.1.0.dmg) |
| **Windows** | **64-bit (x64)** | `.exe` (Installer) | [Download Windows Setup (EXE)](https://github.com/neurohil/bpusimulator/releases/download/v0.2.1/BPU.Simulator.Setup.0.1.0.exe) |
| **Windows** | **64-bit (x64)** | `.zip` (Portable) | [Download Windows Portable (ZIP)](https://github.com/neurohil/bpusimulator/releases/download/v0.2.1/BPU.Simulator-0.1.0-win.zip) |
| **Linux** | **64-bit (x64)** | `.AppImage` | [Download Linux (AppImage)](https://github.com/neurohil/bpusimulator/releases/download/v0.2.1/BPU.Simulator-0.1.0.AppImage) |
| **Linux** | **64-bit (x64)** | `.tar.gz` | [Download Linux (Tarball)](https://github.com/neurohil/bpusimulator/releases/download/v0.2.1/bpu-simulator-0.1.0.tar.gz) |

👉 **[View All Release Assets](https://github.com/neurohil/bpusimulator/releases/tag/v0.2.1)**

---

## 🧠 Overview

The **BPU Simulator** provides an end-to-end, multi-organoid biophysical simulation and high-density microelectrode array (HD-MEA) recording environment:

1. **Chemical Plume & Receptor Transduction:**
   - 50 canonical odorants across 7 chemical categories.
   - Dual olfactory receptor lineages: 12 fast insect ionotropic receptors (`iOR/Orco`) and 20 mammalian metabotropic GPCRs (`mOR`).
   - Vectorized competitive syntopic Hill-Langmuir kinetics (*Rospars et al., 2008; Mainland et al., 2015; DoOR 2.0*).

2. **Thalamocortical Relay & Sensory Gating:**
   - Excitatory Thalamocortical Relay neurons (TC, $\text{VGLUT2}^+$) with low-threshold T-type $\text{Ca}^{2+}$ currents ($I_T$).
   - Thalamic Reticular Nucleus interneurons (TRN, $\text{GAD67}^+$) providing divisive shunting inhibition and high-pass onset gating.

3. **Cortical Network Oscillations & Criticality:**
   - 3D spherical organoid volume with 80% glutamatergic pyramidal neurons and 20% GABAergic interneurons (*Trujillo et al., Cell Stem Cell 2019*).
   - Tsodyks-Markram short-term synaptic depression (STP) generating self-terminating nested theta/gamma bursts.

4. **Virtual MaxOne HD-MEA Integration:**
   - 1,024 active recording channels arranged in a $32 \times 32$ planar sensor grid.
   - Real-time extracellular somatic signal and analog local field potential (LFP) monitoring.
   - Open-loop and closed-loop electrical microstimulation routing.

---

## 💻 Quick Start Instructions

### macOS (Intel & Apple Silicon)
1. Download the `.dmg` matching your Mac processor.
2. Open the disk image and drag **BPU Simulator** into your **Applications** folder.
3. Open the app. *(On first run, right-click the app icon and select **Open** to approve Gatekeeper)*.

### Windows
1. Download `BPU.Simulator.Setup.0.1.0.exe`.
2. Run the installer and follow the setup wizard.
3. Launch **BPU Simulator** from the Start Menu or Desktop.

### Linux
1. Download `BPU.Simulator-0.1.0.AppImage`.
2. Make it executable:
   ```bash
   chmod +x BPU.Simulator-0.1.0.AppImage
   ./BPU.Simulator-0.1.0.AppImage
   ```

---

## 📄 License & Attribution
Proprietary — UC San Diego (Muotri Lab) & Leidos. All rights reserved.
