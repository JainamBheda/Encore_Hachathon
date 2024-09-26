
# Buck Converter Design

## Overview
This repository contains the design documentation and resources for a buck converter that steps down an input voltage of 24V to an output voltage of 5V. The design aims for an efficiency of at least 90% and is suitable for applications requiring efficient voltage regulation.

## Features
- Input Voltage: 24V (± 2% tolerance)
- Output Voltage: 5V
- Maximum Input Current: 1A
- Output Current: Up to 4A
- Efficiency: Minimum 90%
- Components Used
- Power NMOS: IRF540
- Inductor: 130 µH
- Output Capacitor: 47 µF (rated for at least 10V)
- Diode: Schottky diode rated for 5A and 30V
- Resistors: Various resistors for feedback and gate drive

## The design documentation includes:

- Component ratings and calculations (*Word_File*) folder
- Schematic design using KiCad(*Semantic*) folder
- PCB layout (*KiCAD_PCB*) folder
- Semantic diagram illustrating component relationships

## To view the design:

- Clone the repository:
```bash
git clone <https://github.com/JainamBheda/Encore_Hachathon>
```
- Open the design files in KiCad to view schematics and PCB layouts.


## Contributing
If you have suggestions or improvements, feel free to open an issue or submit a pull request.


## Acknowledgments
Texas Instruments for the reference design documentation in prbelm statements

KiCad community for providing an excellent tool for PCB design.
