# Course Project EE206: Analog Circuits {Two-Stage OTA Design (TSMC180nm CMOS, LTspice)} 
**Author:** Ojas Thete (ID: 230108034)

## Problem Statement

Design a two-stage operational transconductance amplifier (OTA) using **TSMC 180nm technology** with the following specifications:

- OTA should be used in a **non-inverting amplifier** configuration with a **closed-loop gain of 2**.
- The **open-loop DC gain** of the OTA must be **at least 40 dB**.
- The amplifier must be **stable**, with a **phase margin of approximately 60°**.
- The design should respond properly to a **0.2 V step input**.

All simulations are performed in **LTspice**, and manual calculations were used for designing transistor widths, lengths, compensation, and other key analog parameters.

---

## 📁 Files Included

### 📄 Design Files
- `230108034_OTA_Design.asc`: LTspice schematic file featuring the Miller-compensated Two-Stage OTA.
- `tsmc018.lib`: The TSMC 180nm CMOS library file required to run the simulation.

### 📄 Documentation
- `Report_230108034.pdf`: Full technical report containing:
  - Detailed design procedure and DC biasing point analysis.
  - Hand calculations for MOSFET sizing (W/L).
  - Frequency response analysis (Gain, Phase Margin, and Bandwidth).
  - Observations from transient simulations.

---

## Technology & Tools
- **LTspice** for high-fidelity circuit simulation.
- **TSMC 180nm CMOS** design assumptions.
- **Analog CMOS Design** principles (manual sizing, Miller compensation, and pole-splitting).

---

## Key Design Highlights
- ✅ **Open-loop gain**: ≈ 2000 (≈ 66 dB)
- ✅ **Closed-loop gain**: 2 (Non-inverting configuration)
- ✅ **Phase margin**: 60.6°
- ✅ **3-dB Bandwidth**: 27.88 MHz
- ✅ **Power Consumption**: 234 μW

---

## 📚 References
- EE206: Analog Electronic Circuits, Indian Institute of Technology Guwahati.
- Behzad Razavi, *Design of Analog CMOS Integrated Circuits*.
