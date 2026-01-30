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

## Installation

1. Download the latest release from the **[Releases page](https://github.com/StarCrusher96/StarCrusher-s-Interstellar-Parts/releases)**
2. Extract/unzip the `SCIP` folder into your `GameData` folder  
3. Ensure you are running **KSP 1.12.x**  
4. Start the game  

Manual installation only. CKAN is not currently supported.

---

## Communication systems

Interstellar-rated CommNet components intended for distances where stock antennas stop being practical.

All antennas in this pack are relay-capable.

| Antenna      | Antenna Power | Tier               | Intended Role                                       |
| ------------ | ------------- | ------------------ | --------------------------------------------------- |
| RA-NKA-S1        | 1 × 10¹⁶      | Entry interstellar | Early interstellar probes, short-range stellar hops |
| IPD-T Telephone | 5 × 10¹⁶      | Mid interstellar   | Reliable links to nearby star systems               |
| IPD-M Megaphone    | 1 × 10¹⁷      | Baseline relay     | First dedicated interstellar relay backbone         |
| IPD-B Blinker         | 1 × 10¹⁹      | Heavy relay        | Long-range interstellar infrastructure              |
| IPD-R Ranger  | 6 × 10¹⁹      | Extreme relay      | Deep interstellar hubs and multi-system coverage    |

Notes:
- Even the smallest SCIP antenna exceeds stock interplanetary communication ranges.
- Relay chaining is expected and strongly encouraged for long distances.

---

## Propulsion

SRX engines represent fusion-driven propulsion intended for interstellar transfer.
They are based on advanced Helium-fusion concepts and trade efficiency and simplicity for sustained thrust, extreme power draw, and very high thermal output. Operating far beyond current real-world fusion capabilities, these engines require continuous heat rejection and are designed for long-duration interstellar missions rather than short, impulsive burns.

| Engine | Role | Scale | Notes |
|------|------|-------|------|
| SRX-L01 “Wayfarer” | Primary interstellar drive | Large | Designed to push entire vessels between stars. Produces extreme heat and requires substantial radiator capacity. |
| SRX-S01 “Torchline” | Surface-to-space variant | Medium-Large | Intended for direct interstellar injection from gravity wells. Atmospheric operation limits effective cooling. |
| SRX-Flux (Legacy) | Experimental / legacy | Medium | Preserved from early KSS-I era as a functional artifact and niche option. |

Notes:
- SRX engines are **not** intended to be drop-in replacements for stock engines.
- Heat management is a primary design constraint.
- Continuous operation over long mission durations is assumed.

---

## Thermal control

SCIP treats heat as a system-level problem rather than a side effect.

### Thermal Components

| Part | Type | Role | Notes |
|----|------|------|------|
| SCS Spindrift Radiator | Deployable radiator | Primary heat rejection | Large wing-style radiators optimized for continuous fusion heat dissipation. Intended to be used in multiples. |
| Micrometeoroid Shield | Structural protection | Long-duration survivability | Protects against micrometeoroids, thermal stress, and high-velocity debris during interstellar cruise. Jettisonable when no longer required. |

Notes:
- SRX engines assume active heat rejection.
- Radiator area scales with sustained thrust rather than short burns.
- The micrometeoroid shield is optional but recommended for multi-year missions.

---

## Fuel and resources

SCIP propulsion systems operate on a fictional Helium-based fusion fuel.
Fuel tanks are designed specifically to support SRX engines and long-duration missions.

### Helium Storage

| Tank | Form Factor | Intended Use |
|----|-------------|--------------|
| PB-ISV01 “Atlas” | Spherical | Large interstellar vessels and long-range missions |
| PB-H750 | Inline | High-capacity inline storage |
| PB-H101 | Inline | Mid-sized reinforced Helium tank |
| Stratus-V Radial | Radial | Modular Helium storage for compact designs |

Notes:
- All tanks store Helium only.
- No tank is intended to be self-sufficient without SRX-compatible propulsion.
- Radial storage is intended for flexibility, not bulk capacity.

## Resource Collection

### Interstellar Particle Scoop

| Part | Function | Operating Environment | Design Intent |
|----|----------|----------------------|---------------|
| IPM-01 Sieve | Trace resource collection | Atmospheres, exospheres, interstellar medium | Low-rate, high-power collection intended for decades-long missions |

Notes:
- Collection rates are intentionally low.
- Power requirements are high.
- This system is not intended for rapid refueling or short missions.
- Best used as a background sustainment system rather than a primary fuel source.

---

## Balance Notes

- All SCIP parts are balanced relative to each other, not to stock parts.
- Mass, cost, and output values are tuned for interstellar-scale gameplay.
- Exact values may change as balance passes continue.
- Additional variants and parts may be added in future releases.

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
