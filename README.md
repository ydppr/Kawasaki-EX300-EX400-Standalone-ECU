# Kawasaki EX300 / EX400 — Standalone ECU Integration

### P.U.R.E. Formula SAE | Polytechnic University of Puerto Rico

**Technical contributor:** Guillermo Toledo  
**Role:** Lead Electronics — P.U.R.E. Formula SAE

This repository documents the integration and crankshaft trigger calibration of Kawasaki EX300 and EX400 engines using standalone engine management systems in Formula SAE applications.

## Engine Configurations

| Engine | ECU | TDC Offset | Verification |
|---|---|---|---|
| Kawasaki EX300 (296 cc) | Alpha X Custom ECU | 130° | Timing-light verified |
| Kawasaki EX400 (399 cc) | Haltech Elite 2000 | 120° | Preliminary calculation |

**Important:** These values are project-specific references, not factory specifications. Trigger configuration, sensor alignment, ECU conventions, and ignition timing must be independently verified.

## Kawasaki EX300 — Alpha X Custom ECU

P.U.R.E. Formula SAE successfully operated a Kawasaki EX300 using an Alpha X custom standalone ECU. Guillermo Toledo determined and verified a 130° TDC trigger offset using a timing light.

The EX300 with Alpha X ECU was used by P.U.R.E. at Formula SAE Michigan 2026.

### Project Evidence

[EX300 Standalone ECU Running — Instagram Reel](https://www.instagram.com/reel/DeZdNzYNjfX/)

[Formula SAE Michigan 2026 Official Results](https://www.fsaeonline.com/CompResources/2026/4357e4f0-86f0-4f66-b813-42cd62f97b1c/FSAE_2026_MI5_results.pdf)

The SAE results document P.U.R.E.'s competition participation; the specific ECU integration and offset are documented by the project developer.

## Kawasaki EX400 — Haltech Elite 2000

Current standalone ECU integration project.

- ECU: Haltech Elite 2000
- Crank trigger: 24-2, based on physical inspection
- Crankshaft rotation: Counterclockwise, as observed
- Calculated TDC offset: 120°
- Verification status: Timing-light confirmation pending

The initial 120° calculation was based on counting eight nominal tooth positions on a 24-position crank trigger wheel (15° per position). The correct trigger reference and ECU convention must be confirmed during synchronization testing.

## Engineering Documentation

Planned additions include:

- Crank trigger diagrams and measurements
- ECU trigger configuration screenshots
- Ignition timing verification records
- Sensor integration and wiring documentation
- Formula SAE implementation notes

## Attribution

**Guillermo Toledo**  
Lead Electronics — P.U.R.E. Formula SAE  
Polytechnic University of Puerto Rico

EX300 and EX400 trigger offset measurement and configuration work credited to Guillermo Toledo.

## Disclaimer

These settings are provided for educational and technical reference. Verify all crank and ignition synchronization settings on each installation before operating the engine. This repository does not claim a verified worldwide first implementation.

## Project Status

- **EX300:** Operational, timing-light-verified standalone ECU configuration
- **EX400:** Under development; preliminary trigger offset awaiting validation
