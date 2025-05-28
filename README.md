**SRAM-based In-Memory Computing Design for Edge Devices**

This project explores an SRAM-based in-memory computing (IMC) architecture tailored for low-power edge devices. It integrates logic functionality directly within memory to reduce data movement and improve energy efficiency.

**Project Highlights**

_6T SRAM Cell Design_: Designed and simulated a 6-transistor SRAM cell for read and write operations. Stability metrics such as Static Noise Margin (SNM) for both read and hold modes were characterized.

_Layout & Physical Verification_: Created the layout of the 6T SRAM cell and verified DRC and LVS using Assura.

_Logic Integration_: Designed and verified a 4-transistor XOR circuit that operates on data from two SRAM cells at the layout level.

_SRAM Array Integration_: Implemented a 4×4 SRAM array with read/write peripheral circuitry and integrated the XOR logic using the gpdk45 PDK on Cadence Virtuoso.


**Tools and Technologies**

Cadence Virtuoso (Schematic, Layout, Simulation)

Assura (DRC and LVS Verification)

gpdk45 (Generic 45nm PDK)

Linux environment for design and simulation workflows


**Acknowledgments**

This project was developed as part of the Bachelor’s Thesis at Indian Institute of Information Technology Kottayam. 

Contact

For questions or collaboration, contact: laahiriadusumilli157@gmail.com
