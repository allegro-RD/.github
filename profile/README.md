# Allegro R&D

Research & Development engineering group at Allegro sp. z o.o., building embedded hardware and firmware for APMs.

## What We Build

- **Hardware** — PCB designs in KiCad
- **Firmware** — Embedded C firmware (primarily STMicroelectronics STM32)
- **Documentation** — Product Design Specifications and engineering documentation, maintained as LaTeX sources alongside each project's hardware/firmware.

## Repository Conventions

Most project repositories in this organization follow a common layout:

```
hardware/<project_name>/   KiCad project (schematics, PCB, production outputs)
firmware/<project_name>/   Firmware project
docs/                      Product related documents
```

Hardware and firmware changes are validated through CI: KiCad projects run automated Design Rule Checks (DRC) and Electrical Rule Checks (ERC) before production outputs are generated, and firmware changes are built automatically on push/PR.
