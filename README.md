# Navi R3

**Navi R3** is a source-available, personal DIY project focused on building a **modular wired + wireless mouse** for makers and light gamers.

The project aims to combine learning, experimentation, and real-world usability, while keeping the hardware open enough for others to extend and customize.

## Project Goals

Navi R3 is designed to:

* Learn and experiment with modern mouse hardware
* Build a mouse that can realistically be used daily
* Provide a clean base platform for custom modules

The project has been actively developed for several months and is currently at a **revision 3 (R3)** hardware stage.

## Hardware Overview

### Core Components

* **MCU**: Nordic nRF52820
* **Optical sensor**: PixArt PMW3360
* **Connectivity**:

  * USB (wired mode)
  * Bluetooth Low Energy (wireless)
* **Battery**: 1S Li-Po
* **Charging**: On-board Li-Ion charger
* **Switches**: Omron D2FC-7-N
* **Scroll wheel**: Mechanical quadrature encoder
* **USB**: USB-C
* **RF**: 2.4 GHz antenna (PCB or external)

The PCB is designed to be simple and focused, without unnecessary integrated features.

## Modular System

Navi R3 includes an optional **modular expansion system**.

* The base PCB exposes GPIO pins intended for external modules
* Side buttons are already connected through this system
* Modules can be both **electronic and mechanical**

Examples of possible modules:

* Additional buttons
* Alternative side button layouts
* Encoders or wheels
* LEDs or RGB indicators

The base PCB itself remains minimal; extra functionality is expected to come from modules.

## Project status

| Feature  | Detail                                        | Status |
|----------|-----------------------------------------------|--------|
| Firmware | Readability first, hoping to be speed focused | ❌ |
| Testing  | Test all features                             | ❌|
| Full release | Entire project available to explore | ❌ | 

❌: Not started
⚠️: Currently working on
✅: Feature

### Wireless roadmap

* Current focus: **BLE**
* Planned later: **custom 2.4 GHz dongle**
* OTA updates are **not implemented**, but could be considered in the future

## Project Status

* Hardware: R3 PCB, not fully tested yet but expected to be functional
* Firmware: under active development
* Modules: concept defined, ecosystem expected to grow over time

This revision of the project has been evolving for about 4 months.

## Manufacturing

* PCB: small-batch friendly, not hand-solderable
* Assembly: DIY or PCBA
* Shell: FDM 3D printed (PLA / PETG)

## License

Navi R3 is **source-available**.

* Source code and hardware files can be viewed and modified
* Forks and personal modifications are allowed
* **Commercial use is not permitted without explicit permission**

Please read the license file carefully before using the project.

## Disclaimer

This is an experimental personal project.
It is provided as-is, without warranty, and may change at any time.
