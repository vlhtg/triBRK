# triBRK
tri-Button Rhythm Keyboard is a cheap and simple to produce input device for various rythm games, aiming to fill the niche of three button devices.

This is my first project both in KiCAD and in STM32Cube.

### Hardware

Built around a STM32 "blue-pill", it uses cheap commonly available parts and a 3D printed case. Unlike AVR-based alternatives this is even cheaper, as blue-pills are around 2-3 euros on Chinese websites. Initial designs had a STM32 chip and the auxilliary components placed directly on the board but compared to just soldering a pre-made board this reusulted in useless complexity, longer building times and surprisingly, higher costs per unit.

### Thanks to:

* This library for the blue-pill layout: https://github.com/Mr-JoE1/Kicad-STM32_bluebill
* This library for MX switches layout: https://github.com/perigoso/keyswitch-kicad-library
* STM for the USB HID libraries that are included with STM32CubeIDE.
* [This](https://www.instructables.com/STM32-As-HID-USB-Keyboard-STM32-Tutorials/) guide for helping me navigate the Configurating the IDE for the first time and explaining how to implement a keyboard device in software.
