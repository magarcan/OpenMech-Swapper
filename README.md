# OpenMech Swapper (OMS)

**OpenMech Swapper (OMS)** is a 100% mechanical filament switching solution for the **Bambu Lab A1 and A1 Mini**. It allows multi-material printing without requiring extra motors, complex electronics, or proprietary sensors.

---

## Background

OMS (OpenMech Swapper) is an open-source experimental project exploring mechanical approaches to multi-material filament switching for desktop FDM printers.

The project was developed independently as part of the broader community interest in mechanically actuated filament systems, including publicly discussed projects such as MechAMS, ZSwitch, TetraFlow, and other mechanical MMU concepts.

OMS focuses on:

* open-source accessibility
* modular mechanical experimentation
* use of standard off-the-shelf components
* community-driven iteration and testing

All OMS CAD, hardware layouts, and implementation details are independently created and released under an open-source license

---

## Why OMS?
*   **Purely Mechanical:** The system is driven entirely by the toolhead’s movement and the existing extruder motor.
*   **GT2 Belt Drive:** We ditched 3D-printed TPU bands in favor of **standard 6mm GT2 timing belts** to eliminate slip and increase torque.
*   **Magnetic Indexing:** Uses 4x2mm Neodymium magnets to create physical "detents." This ensures that the clutch plates remain perfectly aligned at all times without causing wear on the mechanical components.
*   **Plug & Play (Mostly):** No electronics, no PCBs, and no extra steppers. It’s a non-destructive mod that won't void your warranty.

---

## Key Improvements
1.  **Reliability:** GT2 belts don't stretch or snap over time like printed bands do.
2.  **Precision:** The "Magnetic Snap" system keeps the indexing gear locked during high-speed moves.
3.  **Open Access:** All G Code and STL files are available for the community to remix or port to other printers.

---

## Requirements & Compatibility
*   **Printers:** Bambu Lab A1 & A1 Mini.
*   **Slicer:** Compatible with **Bambu Studio** and **Orca Slicer** (requires custom G-Code presets).
*   **BOM Highlights:** 
    *   PETG or PLA for the body.
    *   Standard 6mm GT2 Belt.
    *   4x2mm Neodymium Magnets (N52).
    *   MR 115 Bearing.
    *   Standard 4mm OD PTFE tubing.
    *   Pneumatic coupling PC4-M10
    *   Steel D-Shaft 5mm x 90mm
    *   Prusa Mk3s Extruder Gears

---

## Current Status: Prototyping
The files are currently located in the “Hardware/” folder, and the preliminary G-code logic can be found in “Software/”. The priority is to get the hardware up and running before prototyping the software.

Unfortunately, I don't even own a 3D printer, so I'm really counting on you to help refine the hardware.

---
## Images:

![alt text](https://raw.githubusercontent.com/magarcan/OpenMech-Swapper/refs/heads/main/Docs/Images/1.png)
![alt text](https://raw.githubusercontent.com/magarcan/OpenMech-Swapper/refs/heads/main/Docs/Images/2.png)
![alt text](https://raw.githubusercontent.com/magarcan/OpenMech-Swapper/refs/heads/main/Docs/Images/3.png)
![alt text](https://raw.githubusercontent.com/magarcan/OpenMech-Swapper/refs/heads/main/Docs/Images/4.png)
![alt text](https://raw.githubusercontent.com/magarcan/OpenMech-Swapper/refs/heads/main/Docs/Images/5.png)
![alt text](https://raw.githubusercontent.com/magarcan/OpenMech-Swapper/refs/heads/main/Docs/Images/6.png)
![alt text](https://raw.githubusercontent.com/magarcan/OpenMech-Swapper/refs/heads/main/Docs/Images/7.png)

---
## Contributing
We’re looking for help with G-Code macro optimization and mechanical tolerance refining. Feel free to open a PR or an issue.

**License:** MIT
