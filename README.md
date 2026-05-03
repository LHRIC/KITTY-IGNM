# 4-Cylinder Ignition Module PCB

This is a custom PCB ignition module for a 4-cylinder engine.

The board uses four IGBTs as low-side switches, with one IGBT for each ignition coil signal.

## What It Does

- Takes in 4 ignition signals
- Uses each signal to control one IGBT
- Each IGBT connects one coil to ground when active
- Designed for low-side ignition coil switching

## Power Distribution

The board also has a simple 12V splice section.

It takes:

- 2 × 12V inputs

And provides:

- 4 × 12V outputs

The 12V traces are only used to split power to the coils. They are not used anywhere else on the board.

## Notes

- Made for a 4-cylinder ignition setup
- Low-side switched design
- 12V section is only for coil power distribution
- Coil dwell/control timing should come from the ECU
