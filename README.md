# SRAM-based In-Memory Computing Design for Edge Devices

This project explores an SRAM-based in-memory computing (IMC) architecture tailored for low-power edge devices. The design integrates logic functionality directly within memory cells to minimize data movement and enhance energy efficiency.

---

## Project Highlights

- **6T SRAM Cell Design**  
  Designed and simulated a 6-transistor SRAM cell supporting reliable read and write operations. Characterized stability metrics such as Static Noise Margin (SNM) for both read and hold conditions.

- **Layout & Physical Verification**  
  Created the physical layout of the 6T SRAM cell and performed Design Rule Check (DRC) and Layout Versus Schematic (LVS) verification using Assura.

- **Logic Integration**  
  Designed and verified a 4-transistor XOR logic circuit operating on data from two SRAM cells, verified at the layout level (DRC and LVS).

- **SRAM Array Integration**  
  Implemented a 4×4 SRAM array with associated read/write peripheral circuitry, integrating the XOR logic using the gpdk45 Process Design Kit (PDK) on Cadence Virtuoso.

---

## Tools and Technologies

- Cadence Virtuoso (Schematic capture, Layout, and Simulation)  
- Assura (DRC and LVS physical verification)  
- gpdk45 (Generic 45nm Process Design Kit)  
- Linux environment for design workflows and simulation

---

## Acknowledgments

This project was developed as part of the Bachelor’s Thesis at Indian Institute of Information Technology Kottayam.

---

## Contact

For questions or collaboration, please reach out:  
**Email:** laahiriadusumilli157@gmail.com

