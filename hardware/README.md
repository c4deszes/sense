# Sensor Hardware

## Requirements

[List of hardware requirements](./docs/requirements)

## Design

[Hardware design overview](./docs/design/hardware.adoc)

## Development process

Development process according to [Hardware SPICE](https://www.intacs.info/images/uploads/intacs_HW_Engineering_PRM_PAM_v20.pdf).

---

## Development tools

| Tool | Version | Purpose |
|--|--|--|
| KiCAD | 5.1+ | Schematic design, PCB layout |
| Python | 3.8+ | *Optional*, used for scripted workflow |

---

## Continuous Integration

GitHub Actions is used for automatically testing some aspects of the design on
each change.

[KiBot](https://github.com/INTI-CMNB/kibot)

[KiCAD Export actions](https://github.com/nerdyscout/kicad-exports)

---

## Helpful links

[Hardware Software Interface](https://nqa2.iscn.com/images/PdfFiles/experience-aspice-safety-integrated.pdf)
