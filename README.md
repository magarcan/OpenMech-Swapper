# OpenMech Swapper (OMS) 🔄
### The Open-Source, Fully Mechanical Multi-Filament System

**OpenMech Swapper** is a high-performance, 100% mechanical filament switching system designed specifically for the **Bambu Lab A1 and A1 Mini**. 

Unlike proprietary solutions, OMS is open-source and leverages pure mechanical engineering to enable multi-material printing without extra motors, sensors, or complex electronics. It uses the printer's toolhead movement to index filament slots and the existing extruder motor to drive the system.

---

## ✨ Key Features
- **Zero-Elec Design:** No cables, no extra stepper motors, no PCB.
- **Bambu-Native Integration:** Works via custom G-Code presets in Bambu Studio.
- **Precision Transmission:** Uses standard **GT2 timing belts** for slip-free filament driving.
- **Magnetic Indexing:** Features **Neodymium Magnetic Detents** for perfect slot alignment and tactile reliability.
- **Non-Destructive:** Keep your printer's warranty. Installs and uninstalls in minutes.
- **100% Open Source:** Modification-friendly files (STEP/STL) for the community to improve.

---

## 🛠 Hardware Specs & Improvements
This project improves upon existing mechanical AMS concepts with two major upgrades:

1.  **GT2 Belt Drive:** Replaces printed TPU bands with industrial-standard GT2 belts. This ensures consistent torque and prevents stretching over time, leading to more reliable filament loading.
2.  **Embedded Magnetic Detents:** Uses 4x2mm Neodymium magnets embedded inside the printed parts. These provide a "snap-to-position" feel for each filament slot, ensuring the head is always perfectly aligned with the PTFE output.

---

## 📂 Compatibility
- **Bambu Lab A1:** Full support (optimized for large build volume).
- **Bambu Lab A1 Mini:** Full support (compact design for the Mini's footprint).
- **Slicer:** Optimized for **Bambu Studio** & **Orca Slicer**.

---

## 🚀 Getting Started (WIP)
*Note: This project is currently in the prototyping phase.*

1.  **Print:** Use the provided 3MF profiles (optimized for PETG/PLA).
2.  **Assemble:** Insert the GT2 belt and pause the print to embed the magnets.
3.  **Config:** Import the `OMS_A1_Profile.json` into Bambu Studio.
4.  **Load:** Connect your PTFE tubes and start printing in multi-color.

---

## 🤝 Contributing
As an **Open Source** project, we welcome all improvements! 
- Optimized G-Code for faster purges.
- Variations for different magnet sizes.
- Improved "Push-Lever" geometries.

---

## 📄 License
Distributed under the **MIT License**. See `LICENSE` for more information.
