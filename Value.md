# OptiSystem DWDM Component Values

Based on the provided schematic, here are the detailed parameter values for the workspace and each component.

## Global Workspace Parameters
* **Layout:** 128 Channel DWDM
* **Author:** Arannamoy Mondal
* **Date:** Thursday, April 30, 2020
* **Sweep Iteration:** 1/1
* **Bit rate (bits/sec):** 1e+10
* **Sequence length (bits):** 1024
* **Samples per bit:** 32
* **Sample rate (Hz):** 3.2e+11
* **Number of samples:** 32768
* **Symbol rate (symbols/sec):** 1e+10
* **Time window (s):** 1.024e-07
* **Guard bits:** 0

---

## Component Parameters

### WDM Transmitter
* **Number of output ports:** 128
* **Frequency:** 193.1 THz
* **Frequency spacing:** 100 GHz
* **Power:** 0 dBm
* **Extinction ratio:** 10 dB
* **Linewidth:** 10 MHz
* **Initial phase:** 0 deg
* **Bit rate:** Bit rate bit/s
* **Modulation type:** NRZ

### WDM Mux ES
* **Number of input ports:** 128
* **Frequency:** 193.1 THz
* **Frequency spacing:** 100 GHz
* **Bandwidth:** 75 GHz

### Optical Fiber
* **Length:** 100 km
* **Attenuation:** 0.2 dB/km
* **Dispersion:** 16.75 ps/nm/km
* **Self-phase modulation:** YES
* **Effective area:** 80 um^2
* **n2:** 2.6e-021 m^2/W
* **Full Raman Response:** NO
* **Intrapulse Raman Scatt.:** NO
* **Raman self-shift time1:** 14.2 fs
* **Raman self-shift time2:** 3 fs
* **Fract. Raman contribution:** 0.18
* **Orthogonal Raman factor:** 0.75

### Optical Amplifier (Pre-DCF)
* **Gain:** 20 dB
* **Noise figure:** 4 dB

### DCF (Dispersion Compensating Fiber)
* **Length:** 20 km
* **Attenuation:** 0.5 dB/km
* **Dispersion:** -83.75 ps/nm/km
* **Self-phase modulation:** YES
* **Effective area:** 22 um^2
* **Self-steepening:** NO
* **Full Raman Response:** NO
* **Intrapulse Raman Scatt.:** NO

### Optical Amplifier_1 (Post-DCF)
* **Gain:** 12 dB
* **Noise figure:** 4 dB

### Loop Control
* **Number of loops:** 1

### WDM Demux ES
* **Number of output ports:** 128
* **Frequency:** 193.1 THz
* **Frequency spacing:** 100 GHz
* **Bandwidth:** 75 GHz
* **Filter order:** 4
* **Order number:** *(blank)*

### Optical Receivers (Rx 1, 32, 64, 96, 98, 128)
* **Cutoff frequency:** 0.75 * Bit rate Hz

### BER Analyzers (1, 32, 64, 96, 98, 128)
* *(No additional parameter values displayed on the workspace)*

### Optical Spectrum Analyzers (Standard and _1)
* *(No additional parameter values displayed on the workspace)*
