# Embedded PCB Design Showcase

This repository contains a PCB design I’m proud of, created for an embedded wireless controller.

## Highlighted Design Feature

One design choice I’m particularly proud of is how the PSoC-6 BLE module is integrated into the PCB. The module is placed near the board edge with a clearly defined antenna keep-out region and uninterrupted ground reference to minimize RF attenuation and coupling from digital and power circuitry.

High-speed and noisy signals are intentionally routed away from the RF section, while local decoupling capacitors are placed close to the module’s power pins to reduce supply impedance and improve BLE stability. I also exposed reset, SWD, and UART signals via accessible pads/headers to make firmware bring-up and debugging straightforward.

## Files

- **pcb-2d-layout.png** – 2D PCB layout view  
- **pcb-3d-layout.png** – 3D PCB render
