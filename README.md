# Bidirectional Dual Active Bridge (DAB) DC-DC Converter

This project focuses on the design, working principles, and control of a **Bidirectional Dual Active Bridge (DAB) DC-DC Converter** for electric vehicles (EVs), vehicle-to-grid (V2G) applications, and advanced battery systems. Developed as part of a university assignment in Power Electronics, this simulation provides insights into **phase shift control**, **high-frequency isolation**, and **power bidirectionality** in EV power architecture.

> Authors: Jas Prajapati, Neel Shah, Urvesh Shah, Tejas Soni  
> Course: Power Electronics – University of Windsor

---

## 🔋 Project Objective

To explore the operational characteristics of a **DAB converter** under bidirectional power transfer, using **phase-shift modulation**. The aim is to demonstrate power flow control between two DC sources (e.g., a battery and a DC bus), enabling both charging and discharging modes in EV systems.

---

## 🧰 Tools & Methodology

- **MATLAB/Simulink** (Suggested for modeling and scope visualization)
- Mathematical modeling of:
  - Power vs. phase shift (ϕ)
  - Output current tracking
  - Input/output voltage waveforms
- Analysis based on high-frequency transformer characteristics, H-bridge switching, and coupling inductance.

---

## 🧩 Key Components & Topology

- **Primary & Secondary H-Bridges**: Each bridge includes 4 switches (MOSFET/IGBT).
- **High-Frequency Transformer**: Provides galvanic isolation and voltage level transformation.
- **Leakage/Resonant Inductance**: Enables energy transfer based on phase shift control.
- **Control Logic**: Implements **phase-shift modulation** to control power flow direction and magnitude.

---

## ⚙️ Working Principle

1. **Primary-side H-Bridge** converts DC into high-frequency AC (square waveform).
2. **AC signal** passes through the transformer and inductance.
3. **Phase shift (ϕ)** between primary and secondary waveforms controls:
   - **Power magnitude** (proportional to sin(ϕ))
   - **Power direction** (positive ϕ → forward; negative ϕ → reverse)
4. **Secondary-side H-Bridge** converts AC back to DC.
5. **Bidirectional power flow** supports both charging and discharging operations.

---

## 📈 Simulation Results & Analysis

- **Power Transfer Graph**: Parabolic relation with maximum power at ±π/2 phase shift.
- **Phase vs. Output Current**: Real-time control shows current tracking reference profiles.
- **Input/Output Voltage Waveforms**: Validate switching symmetry and converter efficiency.

---

## 🔄 Applications

- **Vehicle-to-Grid (V2G)** charging infrastructure  
- **On-board chargers** with bi-directional energy flow  
- **Battery energy storage systems (BESS)**  
- **DC Fast Charging stations**  
- **Regenerative braking systems**

---

## 🧠 Skills Demonstrated

- Power electronics modeling
- Phase shift modulation techniques
- Bidirectional energy transfer analysis
- Transformer-based galvanic isolation design
- Current reference control & waveform tracking
- High-voltage DC link design concepts

---


