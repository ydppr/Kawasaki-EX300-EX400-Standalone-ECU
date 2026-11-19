
# Kawasaki EX300 — Standalone ECU Trigger Configuration

**Technical Developer:** Guillermo Toledo  
**Team:** P.U.R.E. Formula SAE  
**Institution:** Polytechnic University of Puerto Rico  
**Competition:** Formula SAE Michigan 2026  
**ECU:** Alpha X Custom Standalone ECU

---

## 1. Project Overview

This document describes the integration and crankshaft trigger offset calibration of the Kawasaki EX300 engine using an Alpha X custom standalone ECU.

The configuration was developed by Guillermo Toledo for P.U.R.E. Formula SAE at the Polytechnic University of Puerto Rico.

The EX300 engine successfully operated with the Alpha X standalone ECU and was used by the team during Formula SAE Michigan 2026.

## 2. Engine Specifications

| Parameter | Specification |
|---|---|
| Manufacturer | Kawasaki |
| Engine | EX300 / Ninja 300 |
| Displacement | 296 cc |
| Configuration | Parallel Twin |
| Engine Management | Alpha X Custom ECU |
| Application | Formula SAE |
| TDC Trigger Offset | 130° |
| Verification Method | Timing Light |
| Verification Status | Verified by Project Developer |

## 3. Crankshaft Trigger Configuration

### TDC Trigger Offset: 130°

The crankshaft trigger offset was determined during the standalone ECU integration process.

A **130° TDC offset** was established and verified using a timing light against the engine's crankshaft timing references.

This value represents the operational configuration developed for the P.U.R.E. Formula SAE EX300 engine.

### Important Technical Notes

- The 130° value was verified using the Alpha X custom standalone ECU.
- The offset is specific to the tested ECU configuration.
- Trigger wheel geometry and reference-edge settings require additional documentation.
- Other standalone ECUs may use different trigger offset conventions.
- Ignition timing must be independently verified on other installations.

## 4. Ignition Timing Verification

Ignition synchronization was checked using a timing light and the crankshaft timing marks.

The purpose of this procedure was to confirm agreement between commanded ECU ignition timing and the crankshaft's actual timing reference.

The developer reports successful verification of the 130° offset.

Additional ECU screenshots, timing-light photographs, and detailed trigger measurements will be included when available.

## 5. Formula SAE Michigan 2026

P.U.R.E. Formula SAE participated in Formula SAE Michigan 2026 representing the Polytechnic University of Puerto Rico.

The team's EX300-powered vehicle used the Alpha X custom standalone ECU, as reported by the project developer.

Official competition results document the team's participation and 296 cc engine displacement.

### Official SAE Documentation

[FSAE Michigan 2026 Competition Results](https://www.fsaeonline.com/CompResources/2026/4357e4f0-86f0-4f66-b813-42cd62f97b1c/FSAE_2026_MI5_results.pdf)

## 6. Engine Running Evidence

Video documentation of the EX300 running with the Alpha X custom standalone ECU:

[EX300 Alpha X — Instagram Reel](https://www.instagram.com/reel/DeZdNzYNjfX/)

The video is identified by the project developer as footage of the operating EX300 standalone ECU implementation.

## 7. Development Attribution

**Guillermo Toledo**  
Lead Electronics — P.U.R.E. Formula SAE  
Polytechnic University of Puerto Rico

Crankshaft trigger offset development, standalone ECU integration, and ignition synchronization work are credited to Guillermo Toledo.

## 8. Future Technical Documentation

Planned additions:

- Crankshaft trigger wheel geometry
- Trigger reference-angle measurements
- ECU trigger configuration screenshots
- Ignition timing verification photographs
- Wiring and sensor integration documentation
- Additional engine operation and calibration records

## 9. Disclaimer

This documentation describes a specific Formula SAE engine management implementation.

The published 130° offset is not presented as a Kawasaki factory specification or as a universal setting for every standalone ECU.

Incorrect ignition synchronization can cause engine damage. Independent verification is required before applying the configuration to another engine.

---

**Project:** Kawasaki EX300 Standalone ECU Integration  
**Technical Developer:** Guillermo Toledo  
**Organization:** P.U.R.E. Formula SAE  
**Institution:** Polytechnic University of Puerto Rico
