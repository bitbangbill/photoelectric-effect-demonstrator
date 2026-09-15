# Photoelectric Effect Demonstrator

The Photoelectric Effect Demonstrator is a USB-C powered all-in-one laboratory instrument and demonstration platform designed to observe and measure the photoelectric effect using a phototube. The system provides a low noise analog environment, a transimpedance amplifier (TIA) with programmable range selection for nA photocurrents, a variable stopping-potential source, all managed by an onboard ATSAMD microcontroller.

## Features

### Sensing & Analog Frontend
* Transimpedance Amplifier (TIA) front-end using low-noise, ultra-low input bias current op-amp OPA140.
* Digitally switchable gain ranges via low-leakage analog switches with feedback resistances from 500 Ω to 50 MΩ to capture nA to low mA photocurrents.

### Power & Isolation
* USB-C powered with independent programming USB-C circuit.
* Isolated power supply section providing clean ±12V analog rails and isolated +5V digital rail to minimize interference with sensitive phototube signals.
* Variable supply for generating fine-tuned stopping potentials across the phototube.
* Multi-channel digital isolation bridging the analog sensing domain and digital processing domain.

### Control & User Interface
* Onboard ATSAMD21G18A 32-bit ARM Cortex-M0+ microcontroller.
* Rotary encoder (PEC11R) with integrated pushbutton navigation.
* Dedicated display interface and user controls.
* USB-C programming and serial debug interface.

## Status : Prototype phase
### Issues
* Majorly over initial budget range.

### In The Works
* Full project reboot.
* Reanalysing research into vacuum tube fundamentals.
* Major circuit design simplifications to reduce complexity.

### Roadmap
The goal is to provide a complete, self-contained educational and laboratory tool for the photoelectric effect and characterising photocathodes. Planned milestones include a custom 3D-printable light-tight optical enclosure, automated stopping-voltage sweeps, and host PC data logging via USB.
