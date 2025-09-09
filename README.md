# U3 LiPo Charging Circuit

A complete modular LiPo battery management solution, designed in KiCad by Eng. Mohamed Yousry. This project combines a charger, protection circuit, and active balancer for safe and efficient LiPo battery management, suited for embedded systems, robotics, and DIY electronics.

***

## Features

- **Battery Charging Circuit**
    - **IC:** BQ24090DGQ
    - Input: 5V (USB or external)
    - Integrated current setting, termination, and charging indicators
    - Optimized for single-cell LiPo batteries
- **Battery Protection Circuit**
    - **IC:** XB8889D
    - Overcharge, overdischarge, and short-circuit protection
    - Automatic recovery feature
    - Output and input connectors included for seamless integration
- **Active Balancer Circuit**
    - Balance two battery cells using autonomous active balancer ICs
    - **Inductor-based charge redistribution** for improved battery health
    - Independent status and enable pins for customization

***

## Schematic Overview

The project schematic is divided into three main sections:

1. **Battery Charging Circuit** – Handles safe charging of the LiPo cell.
2. **Battery Protection Circuit** – Protects against voltage and current faults.
3. **Active Balancer Circuit** – Maintains consistent voltage across multi-cell packs.

_All schematic design is done in KiCad 6.0 and up._

***

## Getting Started

### Prerequisites

- **KiCad** version 6.0+ (required to open Design Files)
- Basic electronics assembly and soldering skills


### Files Included

- `LiPoCharger.kicad_sch`: Complete project schematic
- (You may add: BOM, Gerber files, and 3D models if available)


### How to Use

1. **Review the schematic file** (`.kicad_sch`) in KiCad.
2. Modify component values as needed for your specific battery and current specs.
3. Generate PCB layout and fabricate your board.
4. Solder components according to schematic.
5. Integrate into your battery-powered project.

***

## Block Diagram

```
[5V Charger Input] --> [Charging Circuit] --> [Protection Circuit] --> [Active Balancer] --> [Battery Pack]
```


***

## License

This project is open-source and licensed under the MIT License. See `LICENSE` file for details.

***

## Author

**Eng. Mohamed Yousry**
Mechatronics Engineer / Embedded Hardware \& Software Designer

***

## Contribution \& Support

- Issues and pull requests are welcome!
- For questions or collaboration: mohamed.yousry0023@gmail.com

***

## Acknowledgements

- Designed using KiCad EDA 9.0.3
- Inspired by robust battery management requirements in embedded applications
- Inspired by GreatScott! Youtube channel

***

> **Disclaimer:** Double-check all component ratings for your specific application. Improper LiPo charging/protection can be dangerous.

---
<span style="display:none">[^1]</span>

<div style="text-align: center">⁂</div>

[^1]: image.jpeg

