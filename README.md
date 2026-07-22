# PCB design and layout for Analog Circuits Characterization 

This repository documents the design and implementation of high-performance test PCBs developed during my internship, specifically engineered for the characterization of 2x2mm bare silicon dies.

## 🛠 Project Overview
I designed four 2-layer (80x80mm) PCBs optimized for high-frequency signal integrity. The boards facilitate testing of critical analog circuits, including **Bandgap Reference circuits**, **oscillators**, etc.

### Key Technical Specifications
* **Chip-on-Board (COB) Layout:** * Centralized 7x7mm footprint designed for bare die wire-bonding.
* **Signal Integrity & RF Routing:**
  * High-frequency signals routed from COB pads to edge-mount female SMA connectors.
  * **Impedance Matching:** Controlled 50Ohm impedance path.
  * **EMI Mitigation:** Comprehensive via stitching and shielding along all critical signal traces.
* **DC Signal & Power Management:**
  * Dedicated routing for DC signals.
  * Secure connection interfaces using M2.5mm mounting screws (2.7mm plated through-hole for mechanical stability + 1mm PTH for wire redundancy).
  * Robust grounding: AVSS pads connected to a continuous bottom-layer ground plane via stitching.

## 💻 Technical Stack
* **PCB Design:** Altium Designer
* **Circuit Simulation:** LTspice (extensively used for understanding Bandgap Reference modeling and PSRR/GSRR analysis).

## 🎓 Credits & Mentorship
Special thanks to my mentors for their guidance throughout this project:
* **Professor Sarvana Kumar M**
* **Dr. Snehalatha L**

---
*This repository serves as a record of my engineering design process and practical application of analog IC characterization techniques.*
