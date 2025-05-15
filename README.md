# USB Type-A to Type-C SuperSpeed MUX Board
A high-speed USB 3.1 Gen 2 board designed for converting USB Type-A input to USB Type-C output with integrated signal conditioning, ESD protection, and power control. This 6-layer board was designed to explore differential routing, impedance control, and USB PD compliance.

---

## 🧠 Objective

To design a 10 Gbps USB conversion board using high-speed layout strategies, learn differential pair routing, and integrate proper ESD and power protection.

---

## ⚙️ Core Components

- **TUSB544** – USB 3.1 Gen2 linear redriver
- **TPD8S300** – 8-channel ESD protection
- **TPS2561** – USB charging port controller and power switch

---

## 🔌 Interfaces

- **USB Type-A input**
- **USB Type-C output**
- **I2C interface** for controller configuration

---

## 🔋 Power Management

- Supports USB Power Delivery up to **100W**
- Integrated load switch and current limiting
- Power sequencing and protection control

---

## 🚧 Design Highlights

- 6-layer PCB stack-up optimized for **10 Gbps differential routing**
- **Impedance-matched** differential pairs
- **Shielded signal layers** and ground isolation for EMI control
- **Redriver** for signal integrity
- ESD protection on all high-speed and power lines
- Overcurrent and short-circuit protection
- Stackup planning done using Sierra Circuits’ tool to ensure proper impedance control and manufacturability
- Includes ODB++ for advanced fabrication workflows

---

## 📎 Files

- [`/Documents`](./docs): Schematic, layout image, stack-up planner (Sierra Circuits)
- [`/Gerber`](./Gerber): Standard fabrication files
- [`/ODB++`](./ODB++): Full manufacturing database for fabrication and assembly
- [`/BOM`](./BOM): Component list with part numbers and footprints

> ⚠️ This board was not physically produced. Designed using OrCAD as part of Hasofu Academy's hardware accelerator training.

---

## 👨‍🏫 Acknowledgments

Designed under the guidance of **Kirsch Mackey**, Hasofu Academy founder. Referenced open-source documentation for USB interface design principles.

---

## 🚫 Disclaimer

Project for educational purposes only. USB compliance and signal integrity are simulated, not lab-tested. No proprietary models or NDA-licensed libraries are included.
