# StarCrusher’s Interstellar Parts (SCIP)

![Latest Release](https://img.shields.io/github/v/release/StarCrusher96/StarCrusher-s-Interstellar-Parts?style=for-the-badge&color=4DC820)
![KSP Version](https://img.shields.io/badge/KSP-1.12.x-blue?style=for-the-badge)
![Downloads](https://img.shields.io/github/downloads/StarCrusher96/StarCrusher-s-Interstellar-Parts/total?style=for-the-badge&color=4DC820)
[![License: CC BY-NC-ND 4.0](https://img.shields.io/badge/License-CC%20BY--NC--ND%204.0-lightgrey.svg?style=for-the-badge)](https://creativecommons.org/licenses/by-nc-nd/4.0/)

SCIP is a simple standalone parts mod for Kerbal Space Program 1.

The parts in this repository originate from Kerbal Star Systems 1 (2015–2018) and have been reworked, upgraded, and separated into a dedicated mod for continued use and maintenance.

This pack is intended for players who want to go interstellar without relying on large or overly complex mod stacks. It provides a simple, robust baseline for interstellar missions, covering propulsion, communication, thermal control, and basic resource support.

---

## Design intent

SCIP focuses on function over complexity.

The goal is not to simulate every subsystem in detail, but to provide parts that:
- work reliably over long missions
- scale cleanly for interstellar distances
- integrate with stock gameplay assumptions where possible
- avoid unnecessary dependencies

These parts assume the player already understands spacecraft design.

---

## Communication systems

Interstellar-rated CommNet components intended for distances where stock antennas stop being practical.

All antennas in this pack are relay-capable.

| Antenna      | Antenna Power | Effective Range (same antenna) | Tier               | Intended Role                                       |
| ------------ | ------------- | ------------------------------ | ------------------ | --------------------------------------------------- |
| RA-NKA-S1        | 1 × 10¹⁶      | 1 × 10¹⁶ m                     | Entry interstellar | Early interstellar probes, short-range stellar hops |
| IPD-T Telephone | 5 × 10¹⁶      | 5 × 10¹⁶ m                     | Mid interstellar   | Reliable links to nearby star systems               |
| IPD-M Megaphone    | 1 × 10¹⁷      | 1 × 10¹⁷ m                     | Baseline relay     | First dedicated interstellar relay backbone         |
| IPD-B Blinker         | 1 × 10¹⁹      | 1 × 10¹⁹ m                     | Heavy relay        | Long-range interstellar infrastructure              |
| IPD-R Ranger  | 6 × 10¹⁹      | 6 × 10¹⁹ m                     | Extreme relay      | Deep interstellar hubs and multi-system coverage    |

---

## Propulsion

Fusion-based propulsion systems for interstellar transfer.

- SRX-L01 Wayfarer  
  Primary interstellar engine for large vessels. Produces high heat output and requires significant radiator capacity.

- SRX-S01 Torchline  
  Surface-to-space variant intended for direct interstellar injection. Cooling is limited during atmospheric operation.

- SRX-Flux  
  Legacy engine retained from early KSS-era experimentation.

---

## Thermal control

- SCS Spindrift radiator  
  Large deployable radiators for sustained fusion heat rejection.

- Micrometeoroid shield  
  Structural and thermal protection for long-duration missions. Can be jettisoned when no longer needed.

---

## Fuel and resources

SCIP propulsion systems operate on a fictional Helium-based fusion fuel.

Fuel containers in this pack are designed specifically to support SRX engines.

- PB-ISV01 Atlas  
- PB-H750  
- PB-H101  
- Stratus-V radial container  

### Resource collection

- IPM-01 Sieve  
  Collects trace Helium and other particles from atmospheres, exospheres, and the interstellar medium.

Collection rates are intentionally low and power requirements are high, making this suitable only for long-duration missions.

---

## Development and credits

SCIP is authored and maintained by StarCrusher96.

Original part design and technical contributions were made by JadeOfMaar. Many of these parts trace back to early KSS1 development between 2015 and 2018.

Balance is still work in progress. This is not a tightly tuned parts pack, and improvements are welcome. Reasonable balance feedback, ModuleManager patches, and compatibility tweaks are appreciated.

---

## Relationship to KSS2

SCIP is developed alongside Kerbal Star Systems 2, but is fully standalone.
It can be used with KSS2 or independently in any save that requires interstellar-capable infrastructure.

---

## Requirements

- Kerbal Space Program 1.12.x  
- Manual installation  
- Dependencies listed per release

---

## License

CC BY-NC-ND 4.0

Redistribution with attribution is allowed.  
Derivative works and asset reuse are not permitted without explicit permission.
