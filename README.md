# Electrical Installation

Design, implementation, and technical documentation of a small-scale indoor electrical installation in **Heraklion, Crete, Greece**.

The project was completed in two phases between **September–October 2024** and **February 2025**.

The complete project documentation, including electrical schematics, architectural drawings, distribution board diagrams, LED control diagrams, and photographs of the completed installation, is available in the PDF included in this repository.

---

## Project Overview

The project involved the design and implementation of an electrical installation for a small indoor space.

The work was completed in two main phases:

- **Phase 1 – Mezzanine**
- **Phase 2 – Ground Floor Extension**

The project included:

- On-site measurements
- Architectural layout design
- Electrical installation design
- Power outlet circuits
- Lighting circuits
- Electrical distribution board design
- Circuit protection
- Cable routing
- Junction boxes
- Multi-point lighting control
- RGBW LED lighting
- Raspberry Pi based LED control
- Installation and commissioning
- Technical documentation
- Final photographic documentation

---

## Phase 1 – Mezzanine

The first phase focused on the electrical installation of a mezzanine with an area of approximately **25 m²**.

The electrical supply for the mezzanine originates from the main distribution board located on the ground floor.

A dedicated sub-distribution board was installed for the mezzanine.

The supply cable used between the main panel and the mezzanine subpanel is:

```text
3 × 4 mm² NYY
```

The installation includes circuits for:

- General-purpose power outlets
- Computer workstations
- Lighting
- Retro-style lighting fixtures
- Spot lighting
- Staircase LED lighting
- Decorative hidden LED lighting
- Auxiliary electrical equipment

The electrical design and panel drawings were created using **AutoCAD Electrical**.

---

## Lighting Control

Different switching configurations were used depending on the lighting requirements.

These include:

- Single-pole switches
- Two-way switches
- Intermediate switches
- Multi-point lighting control

The staircase lighting can be controlled from different locations, improving accessibility when moving between the ground floor and mezzanine.

---

## RGBW LED Control System

A dedicated **LED Control Panel** was developed for the hidden decorative lighting.

The system controls LED lighting installed around parts of the room and staircase.

A **Raspberry Pi** is used as a local server for the lighting control system.

Users can connect to the Raspberry Pi through the local network and access the lighting-control interface through its IP address.

Example:

```text
http://192.168.1.100
```

The interface provides control of the RGBW lighting, including:

- White LED brightness
- RGB color control
- Lighting intensity

A separate electronic driver circuit receives control signals and drives the LED lighting.

---

## Phase 2 – Ground Floor Extension

The second phase expanded the existing installation to the ground floor.

The extension included:

- New electrical circuits
- Additional power outlets
- New lighting circuits
- Modifications to the main distribution board
- New junction boxes
- Additional cable routing
- Integration with the mezzanine installation

Two separate power outlet circuits were installed to supply the ground-floor equipment.

A dedicated lighting circuit was also installed.

---

## Multi-Point Lighting Control

One of the lighting circuits was designed so that the same light can be controlled from **three different locations**.

The configuration uses:

```text
Two-way switch
       │
       ▼
Intermediate switch
       │
       ▼
Two-way switch
```

This allows the lighting fixture to be switched ON or OFF from any of the three control points.

---

## Electrical Protection

During the second phase, modifications were made to the electrical protection system.

The **Residual Current Device (RCD)** was relocated to the main distribution board so that it provides protection for both the:

- Ground floor
- Mezzanine

The project documentation includes the updated distribution board design.

---

## Electrical Drawings

The complete technical report contains the electrical and architectural drawings used during the project.

These include:

- Architectural plans
- Electrical floor plans
- Cable routing
- Lighting circuits
- Power outlet circuits
- Mezzanine sub-distribution board
- Main distribution board
- Ground-floor electrical installation
- LED control system block diagram

The drawings are included directly inside the project PDF.

---

## Technologies & Tools

### Electrical

- Electrical distribution boards
- MCB circuit protection
- RCD protection
- NYY power cables
- Lighting circuits
- Power outlet circuits
- Two-way switches
- Intermediate switches
- LED lighting
- RGBW LED strips

### Electronics & Control

- Raspberry Pi
- Custom LED driver electronics
- Local web server
- RGBW lighting control

### Design & Documentation

- AutoCAD Electrical
- Visual Paradigm
- LaTeX

---

## Full Technical Report

The complete **38-page technical report** contains the schematics, designs, diagrams, explanations, and photographs of the completed installation.

[**View the Electrical Installation Technical Report (PDF)**](./Electrical%20Installation.pdf)

---

## Repository Structure

```text
Electrical-Installation/
│
├── README.md
│
└── Electrical Installation.pdf
```

All schematics, drawings, photographs, and technical information are contained inside the PDF.

---

## Project Responsibilities

### Stamatios Mavitzis

**Project Lead / Electrical Engineer**

Responsibilities included:

- Electrical installation planning
- Electrical schematic design
- Distribution board design
- Circuit planning
- Electrical installation work
- Installation supervision
- System integration
- Testing
- Technical documentation

### Additional Contributors

The first phase of the project was completed with the assistance of:

- Annis Fountoulakis
- Konstantinos Bourbakis
- Stelios Deligiannis Makris

---

## Location

**Heraklion, Crete, Greece**

---

## Project Timeline

| Phase | Period |
|---|---|
| Phase 1 – Mezzanine | September – October 2024 |
| Phase 2 – Ground Floor Extension | February 2025 |

---

## Safety Notice

This repository documents an electrical installation project and is intended for technical, educational, and portfolio purposes.

Working with mains electricity can cause serious injury, fire, or death. Electrical installations should be performed and verified by appropriately qualified personnel and must comply with applicable electrical regulations and safety standards.

---

## Author

**Stamatios Mavitzis**

Electrical & Computer Engineering
