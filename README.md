# Course Project EE206: Analog Circuits {Two-Stage OTA Design (TSMC 180nm CMOS, LTspice)} 
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
- [cite_start]`230108034_OJAS_THETE.asc`: LTspice schematic file containing the Two-Stage Miller Compensated OTA design[cite: 172].

### 📄 Documentation
- `Report_230108034.pdf`: Full technical report detailing:
  - [cite_start]Initial design assumptions and DC biasing[cite: 303, 304].
  - [cite_start]Hand calculations for $(\frac{W}{L})$ ratios of M1–M7[cite: 313].
  - [cite_start]Frequency response analysis (Gain and Phase Margin)[cite: 239].
  - [cite_start]Transient response for a $0.2V$ step input[cite: 289].

---

## Technology & Tools
- [cite_start]**LTspice** for circuit simulation and verification[cite: 172].
- [cite_start]**TSMC 180nm CMOS** library (`tsmc018.lib`)[cite: 172, 175].
- [cite_start]**Analog CMOS Design** principles (Miller compensation, pole splitting)[cite: 219, 226].

---

## Key Design Highlights
- [cite_start]✅ **Open-loop gain**: $\approx 2000$ ($\approx 66$ dB)[cite: 213, 493].
- [cite_start]✅ **Closed-loop gain**: $2$ (Non-inverting configuration)[cite: 214, 495].
- [cite_start]✅ **Phase margin**: $60.6^\circ$[cite: 253].
- [cite_start]✅ **3-dB Bandwidth**: $27.88$ MHz[cite: 257].
- [cite_start]✅ **Power Consumption**: $234 \mu W$[cite: 217].

---

## 📚 References
- EE206: Analog Electronic Circuits, IIT Guwahati course materials.
- Behzad Razavi, *Design of Analog CMOS Integrated Circuits*.
