# 6G Antenna for Autonomous Vehicles

## Overview

This repository contains the design and simulation data for a **tooth-shaped patch antenna** intended for autonomous vehicles operating within **6G wireless systems**. The novel design provides **higher gain** and improved performance, specifically reducing the **mutual coupling effect** while maintaining **good impedance matching**. This antenna operates at **77 GHz**, a frequency commonly used in vehicular RADAR systems to support features like automatic cruise control, lane change assistance, and pedestrian protection systems.

RESEARCH PAPER : [VIEW](./A_Novel_and_High_Gain_Antenna_Design_for_Autonomous_Vehicles_of_6G_Wireless_Systems.pdf)

## Features

- **Frequency**: 77 GHz (Millimeter-wave band)
- **Gain**: 9.4 dB (2.2 dB improvement over conventional patch antennas)
- **Return Loss**: -37.9441 dB
- **Technology**: Microstrip patch antenna with novel tooth-shaped slots
- **Substrate**: Rogers RO/Duroid 5880 with low moisture absorption and high melting point
- **Applications**: Autonomous vehicle RADAR systems (SRR, MRR, LRR)

## Antenna Design

The antenna is designed for millimeter-wave applications, with key features including:

- **High Gain**: Improved gain through novel shape optimization.
- **Reduced Mutual Coupling**: Tooth-shaped slots reduce magnetic field at slot-2 to minimize mutual coupling effects.
- **Good Impedance Matching**: Enhanced matching for improved performance using the **Inset-fed method**.
- **Stable Performance**: Suitable for **autonomous vehicles** even in challenging conditions like rain or snow.

## Design Parameters

| Parameter          | Value   |
| ------------------ | ------- |
| Center Frequency   | 77 GHz  |
| Patch Length (L)   | 1.2 mm  |
| Patch Width (W)    | 2.43 mm |
| Substrate Height   | 0.19 mm |
| Substrate Material | Rogers RO/Duroid 5880 |
| Return Loss        | -37.9441 dB |
| Gain               | 9.4 dB  |

## Simulation & Tools

- **HFSS Simulation**: The design was simulated using ANSYS HFSS to analyze return loss, gain, current distribution, and mutual coupling.
- **Smith Chart Analysis**: Impedance matching was verified through Smith charts, ensuring the antenna achieves near-perfect matching at 77 GHz.

## Usage

The antenna design provided here can be adapted for various autonomous vehicle applications such as:

- **Short-Range RADAR (SRR)**
- **Medium-Range RADAR (MRR)**
- **Long-Range RADAR (LRR)**

## Future Work

- **Fabrication**: The proposed design is yet to be fabricated and tested in real-world scenarios.
- **Performance Optimization**: Further improvements can be made through additional shape optimization and material testing.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## References

- A. K. M. Baki, et al., "A Novel and High Gain Antenna Design for Autonomous Vehicles of 6G Wireless Systems." IEEE GECOST 2021 Conference Proceedings. 

---

Feel free to contribute, report issues, or improve the design further by submitting pull requests!
