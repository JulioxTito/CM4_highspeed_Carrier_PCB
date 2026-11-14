# CM4 Mini PC - Custom 4-Layer High-Speed Carrier Board

A compact, credit-card-sized (~85 mm × 56 mm) carrier board for the **Raspberry Pi Compute Module 4 (CM4)** designed in **KiCad 8**.

## Project Highlights
* **Form Factor**: Credit-card sized (~85 mm × 56 mm), compatible with standard Raspberry Pi enclosures.
* **Compute**: Dual 100-pin Hirose DF40C high-density mezzanine connectors for Raspberry Pi CM4 (Lite & eMMC variants).
* **Power**: 5V / 3A USB Type-C sink (dual 5.1 kΩ CC pull-downs) + onboard 3.3V power tree.
* **Display**: 1x Full-Size HDMI (HDMI0, 100 Ω differential pairs, ESD protection, DDC level shifting).
* **Networking**: 1x Gigabit Ethernet (10/100/1000 Mbps RJ45 MagJack with internal magnetics).
* **USB**: 4x USB 2.0 Host ports via Microchip USB2514B Hub Controller (90 Ω differential pairs).
* **Storage**: MicroSD Card Slot (for CM4 Lite booting) with power-switching control.
* **Stackup**: 4-Layer controlled-impedance stackup (JLCPCB JLC04161H).

## Repository Structure
* /hardware: KiCad 8 schematics, PCB layout, local library footprints, and symbols.
* /docs: Architecture specifications, pinout maps, impedance calculations, and bring-up checklist.
* /bom: Bill of Materials (LCSC / JLCPCB part numbers).