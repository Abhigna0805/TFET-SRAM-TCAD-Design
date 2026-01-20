# Ultra-Compact TFET-Based SRAM Design for Low-Power Applications

Solid State Devices | TCAD-Based Design and Analysis

As technology scales down, conventional CMOS SRAM cells face major challenges such as
high leakage power and limited voltage scalability. This project focuses on the design
and analysis of an ultra-compact Static Random Access Memory (SRAM) cell using Tunnel
Field-Effect Transistors (TFETs), which enable low-voltage operation through band-to-band
tunneling.

The objective of this project is to study TFET-based SRAM architectures and evaluate
their suitability for ultra-low-power and energy-constrained applications such as IoT
and edge computing systems.

---

#### Technology and Tools

- Device Technology: Tunnel Field-Effect Transistors (TFETs)
- Design Domain: Solid State Devices, Low-Power VLSI
- Simulation and Analysis: TCAD-based device and circuit analysis
- Memory Architecture: 3-Transistor (3T) TFET-based SRAM cell
- Documentation Format: IEEE-style technical report

---

#### Design Objective

- Reduce leakage power compared to conventional CMOS SRAM
- Enable stable SRAM operation at ultra-low supply voltages
- Achieve compact cell area for improved energy efficiency
- Study voltage scalability and memory stability using TFET devices

---

#### Design Description

- A 3T TFET-based SRAM cell is designed using reverse-biased TFETs.
- TFETs utilize band-to-band tunneling to achieve subthreshold slopes below 60 mV/dec.
- Negative Differential Resistance (NDR) behavior is leveraged to form a stable latch.
- Write operation is performed by temporarily switching supply rails.
- Read operation is enabled through a dedicated TFET access transistor.

---

#### Working

- TFET device characteristics are analyzed using TCAD-based modeling.
- SRAM cell behavior is evaluated under different supply voltages.
- Leakage current, static noise margin, and voltage scalability are studied.
- Performance is compared conceptually with conventional CMOS SRAM designs.

---

#### Performance Highlights

- Ultra-low leakage current (< 0.1 fA per bit)
- Reliable operation from 0.6 V down to 0.2 V
- Improved subthreshold characteristics compared to CMOS
- Compact cell area suitable for dense memory arrays
- Reduced static and dynamic power consumption

---

#### Applications

- Internet of Things (IoT) devices
- Wearable electronics
- Edge computing systems
- Energy-harvesting applications
- Always-on memory blocks in low-power SoCs

---

#### Results and Outcome

- TFET-based SRAM demonstrates significant leakage power reduction.
- Stable memory operation is achievable at ultra-low voltages.
- Hybrid TFET-CMOS architectures are feasible for practical integration.
- Highlights trade-offs between power efficiency, performance, and fabrication complexity.

---

#### References

- Gupta et al., “Ultra-Compact SRAM Design Using TFETs for Low Power Low Voltage Applications,” IEEE ISCAS, 2016.  
  https://ieeexplore.ieee.org/document/7527342

- Gupta et al., “3T-TFET Bitcell Based TFET-CMOS Hybrid SRAM Design for Ultra-Low Power Applications,” DATE, 2016.

- Bernstein et al., “Device and Architecture Outlook for Beyond CMOS Switches,” Proceedings of the IEEE, 2010.

- Choi et al., “TFETs with Subthreshold Swing Less Than 60 mV/dec,” IEEE Electron Device Letters, 2007.

- Seabaugh and Zhang, “Low-Voltage Tunnel Transistors for Beyond CMOS Logic,” Proceedings of the IEEE, 2010.

- Ahmad et al., “Robust TFET SRAM Cell for Ultra-Low Power IoT Applications,” AEU – International Journal of Electronics and Communications, 2018.  
  https://www.sciencedirect.com/science/article/pii/S1434841117325049
