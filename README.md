# Ctrl+Farm Robot

## About

Ctrl+Farm is an automated farming robot designed to assist with precision planting operations such as **furrowing, seeding, and watering** small-seed crops (e.g., carrots, tomatoes).  
The robot is built to navigate uneven terrain, reduce labor needs, and improve crop uniformity through automation.

---

## Versions

### Version 1 - MyRio Implementation

- Documented in the **Ctrl+Farm Report**.
- Uses **NI myRio-1900** as the main controller.
- Implements a **state machine** to handle sequential farming tasks:
  - Drilling
  - Seeding
  - Watering
  - Filling
- Hardware includes NEMA stepper motors, DC motors, servo motors, and a gear-based switching mechanism.

### Version 2 - Arduino Implementation (Work in Progress)

- Current development branch focuses on replacing the **MyRio** with an **Arduino-based control system**.
- Goal: improve accessibility, reduce cost, and simplify integration for hobbyists and small-scale farmers.
- Work in progress: adapting the state machine logic and hardware drivers to Arduino libraries.
- Not yet fully documented or tested.

---

## Project Goals

- Automate repetitive farming tasks with precision.
- Enhance productivity and reduce manual labor.
- Provide a scalable design that can be adapted to different controllers (MyRio, Arduino).

---

## Status

- ✅ Version 1 (MyRio) complete and documented.
- 🚧 Version 2 (Arduino) under development.

---

## Team Members

- Version 1: Ali Ismail, Michel Abi Saab, Antony Nachar, Carlo Sadek, and Jessica Tannous.
- Version 2: Ali Ismail. Michel Abi Saab, Jessica Tannous.
