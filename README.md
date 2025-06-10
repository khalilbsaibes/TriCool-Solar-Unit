# TriCool Solar Unit – Modular Solar-Powered Cooling Roof Tile

**Author:** Khalil Bsaibes

**License:** CERN Open Hardware License v2 (hardware) + Creative Commons Attribution 4.0 (documentation)

A modular, solar-powered cooling tile designed for off-grid applications in caravans, mobile homes, and compact structures. The unit uses a slanted solar panel, aerogel insulation, and a vertically mounted Peltier cooler to deliver cooling during peak sunlight without any need for batteries.

### 🔧 Features

* Self-powered active cooling (no battery needed)
* Triangular shape for modular roof tiling
* Aerogel insulation for thermal isolation
* Dual-fan system (internal cool circulation, external heat exhaust)
* Open-source design

### 🧱 System Overview

**Components:**

* Solar Panel (tilted 30°–60°)
* Aerogel insulation layer
* Peltier module (TEC1-12706) mounted vertically
* Internal Fan to circulate cooled air
* External Fan & Heatsink to expel hot air
* Copper rod or heat pipe to transfer heat through aerogel (optional)

**Dimensions (Prototype Reference):**

* Triangle base: ~20cm
* Height: ~5cm

### 🔁 Operating Principle

1.  Solar panel generates electricity.
2.  Power feeds the Peltier module and both fans.
3.  Heat is expelled outward by the external fan and heatsink.
4.  The cold side cools air inside the space via the internal fan.
5.  Aerogel prevents heat from the solar panel transferring downward.

### 📦 Bill of Materials (BOM)

| **Item** | **Example Model** | **Qty** |
| :---------------- | :--------------------- | :-----: |
| Solar Panel       | 10W-20W, flexible      |    1    |
| Peltier Module    | TEC1-12706             |    1    |
| Aerogel Sheet     | 6mm felt               |    1    |
| Internal Fan      | 5V brushless blower    |    1    |
| External Fan      | 12V CPU fan + heatsink |    1    |
| Copper Rod (opt.) | 6–10mm diameter        |    1    |

### 📜 License

This project is dual-licensed. The license that applies depends on the part of the project being used.

#### Hardware Designs

All hardware design files are licensed under the **CERN Open Hardware Licence Version 2 - Strongly Reciprocal (CERN-OHL-S)**. This includes, but is not limited to:

* Schematic and PCB layout files (`.kicad_sch`, `.kicad_pcb`)
* Gerber and drill files
* 3D models (`.step`, `.stl`)
* The Bill of Materials (BOM)

This source describes Open Hardware and is licensed under the CERN-OHL-S v2.0. You may redistribute and modify this design under the terms of the CERN-OHL-S v2.0. This project is distributed WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the `LICENSE` file for full details.

#### Documentation, Images, and Software

All documentation, non-hardware files, and software are licensed under the **Creative Commons Attribution 4.0 International License (CC BY 4.0)**. This includes:

* Project documentation and this README file (`.md`, `.pdf` files)
* Any software or firmware code (`.py`, `.ino`, etc.)
* Images and diagrams

Under this license, you are free to:

* **Share** — copy and redistribute the material in any medium or format
* **Adapt** — remix, transform, and build upon the material for any purpose, even commercially

This must be done while giving appropriate credit and indicating if changes were made. See the `LICENSE-DOC` file for full details.

### 🙌 Acknowledgments

Concept, design, and open-source release by Khalil Bsaibes.

For collaboration, feedback, or forked builds, visit the GitHub repository:

<https://github.com/khalilbsaibes/TriCool-Solar-Unit>

Let’s cool the world—sun-first ☀️❄️
