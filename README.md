# Cyborg-and-Bionic-Systems-zs

Supplementary repository for the paper:

> **A Multiscale Neural Interfacing Device for Cross-Brain-Region Electrophysiology**

This repository provides the hardware design files and an example dataset
associated with the paper, to support reproducibility and reuse of the device.

## Contents

| File | Description |
|------|-------------|
| `2.4G射频模块.epro2` | PCB design project for the 2.4 GHz RF module (EasyEDA Pro format) |
| `主控模块pcb.epro2` | PCB design project for the main control module (EasyEDA Pro format) |
| `Fig6_Example_Dataset.zip` | Example dataset underlying Figure 6 of the paper |

## Hardware Design Files

The `.epro2` files are PCB design projects. To open them, use the
corresponding EDA software (e.g., EasyEDA Pro / LCEDA Pro).

These files cover two boards:

- **2.4 GHz RF module** — wireless communication front-end.
- **Main control module** — central control and data acquisition board.

> Note: These are research prototypes and are not certified for clinical
> or human use.

## Example Dataset

`Fig6_Example_Dataset.zip` contains the example data used to generate
Figure 6 in the paper. Unzip it before use:

```
unzip Fig6_Example_Dataset.zip
```

Please refer to the paper for detailed descriptions of the experimental
setup, recording parameters, and data interpretation.

## License

Please contact the authors regarding reuse of the hardware design files and data.
