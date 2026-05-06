# OpenMech Swapper (OMS) 🔄
### The Open-Source, Fully Mechanical Multi-Filament System for Bambu Lab A1 Series

**OpenMech Swapper (OMS)** is a high-performance, 100% mechanical filament switching system. It is designed to bring multi-material capabilities to the **Bambu Lab A1 and A1 Mini** without the need for extra motors, sensors, or complex electronics.

---

## 💡 Origin & Credits
This project is an **Open Source evolution** inspired by the brilliant mechanical concept of **MechAMS** created by [Sipers Mechatronics](https://sipersmechatronics.com). 

While the original idea proved that a fully 3D-printable mechanical AMS was possible, **OMS** aims to make this technology accessible to everyone under an open-source license, incorporating community-driven improvements for better durability and precision.

---

## ✨ Key Features
- **Purely Mechanical:** Driven by your toolhead position and the existing extruder motor.
- **GT2 Belt Drive:** Upgraded from friction bands to **standard 6mm GT2 timing belts** for zero-slip and high-torque transmission.
- **Magnetic Indexing:** Uses **embedded Neodymium magnets** (4x2mm) to create precise "detents," ensuring perfect alignment of the filament slots with zero mechanical wear.
- **Zero Electronics:** No cables, no PCB, no extra steppers.
- **Non-Destructive:** Quick installation that keeps your printer's warranty intact.

---

## 🛠 Improvements over the Concept
1.  **Reliability:** By using GT2 belts, we eliminate the stretching issues of printed TPU bands.
2.  **Precision:** The "Magnetic Snap" system ensures the indexing gear stays locked in the correct position even during high-speed printing.
3.  **Accessibility:** All files (STEP/STL) are open for the community to remix and adapt to other printers.

---

## 📂 Compatibility
- **Hardware:** Bambu Lab A1 & A1 Mini.
- **Software:** Custom G-Code presets for **Bambu Studio** and **Orca Slicer**.

---

## 🔧 Hardware Requirements (BOM)
- **Main Body:** Printed in PETG or PLA.
- **Drive System:** 1x GT2 Timing Belt (6mm width).
- **Indexing:** 4x2mm Neodymium Magnets (N52 recommended).
- **Path:** Standard 4mm OD PTFE Tube.

---

## 🚀 Status: Prototyping
Check the `Hardware/` folder for current STL files and the `Software/` folder for the initial G-Code logic. 

**Note:** Always remember to calibrate your "Head-Push" coordinates before the first run to avoid bed collision.
---
---
[Video](https://github.com/magarcan/OpenMech-Swapper/raw/refs/heads/main/Docs/Grabaci%C3%B3n%202026-05-06%20132207.mp4)
---

## 🤝 Contributing & License
We welcome all contributions! Whether it's optimizing G-Code macros or refining the mechanical tolerances.

Distributed under the **MIT License**.
