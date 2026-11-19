
# Kawasaki EX400 — Haltech Elite 2000 Trigger Configuration

**Technical Developer:** Guillermo Toledo  
**Team:** P.U.R.E. Formula SAE  
**Institution:** Polytechnic University of Puerto Rico  
**ECU:** Haltech Elite 2000  
**Project Status:** Under Development

---

## 1. Project Overview

This document describes the standalone ECU integration and crankshaft trigger offset investigation of the Kawasaki EX400 engine for P.U.R.E. Formula SAE.

The project uses a Haltech Elite 2000 standalone ECU.

Crankshaft trigger measurements and preliminary offset calculations were performed by Guillermo Toledo, Lead Electronics for P.U.R.E. Formula SAE.

## 2. Engine and ECU Specifications

| Parameter | Configuration |
|---|---|
| Manufacturer | Kawasaki |
| Engine | EX400 / Ninja 400 |
| Displacement | 399 cc |
| Configuration | Parallel twin |
| ECU | Haltech Elite 2000 |
| Crank trigger pattern | 24-2 (physically observed) |
| Observed crank rotation | Counterclockwise |
| Preliminary TDC offset | 120° |
| Timing-light verification | Pending |

## 3. Crankshaft Trigger Wheel

Physical inspection identified a crankshaft trigger wheel with a nominal 24-position pattern and two missing teeth.

### Trigger Geometry

Nominal tooth position angle:

360° / 24 = 15°

Eight nominal tooth positions correspond to:

8 × 15° = 120°

This calculation provides a preliminary geometric reference for the ECU trigger offset.

The actual Haltech TDC offset depends on the trigger reference event, selected trigger edge, sensor configuration, and angle convention.

The measured 120° value has not yet been confirmed as the final ECU setting.

## 4. Measurement Method

The preliminary offset was calculated using:

1. Physical crankshaft timing reference.
2. Observed crankshaft rotation direction.
3. Identification of the crankshaft position sensor.
4. Identification of the missing-tooth gap.
5. Counting eight nominal tooth positions.
6. Calculation using 15° per nominal tooth position.

This procedure establishes a starting point for ignition synchronization testing, not a factory Kawasaki calibration specification.

## 5. Ignition Timing Verification

**Status: Pending**

Before the preliminary offset is declared verified, the following information must be established:

- Correct cylinder TDC reference
- ECU trigger event and reference edge
- Trigger sensor polarity and signal stability
- Commanded versus measured ignition timing
- Timing-light verification against the crankshaft TDC reference

A fixed ignition timing command should be checked against a corresponding timing-light measurement using the correct crankshaft timing marks.

The final verified offset will be added to this document once testing is complete.

## 6. Haltech Elite 2000 Integration

The EX400 engine is being integrated with a Haltech Elite 2000 engine management system for Formula SAE application.

Technical documentation planned for this section includes:

- Trigger and home synchronization configuration
- Crankshaft position sensor integration
- Ignition system architecture
- Fuel injection configuration
- ECU power and grounding
- Additional engine sensor integration

These details will be documented after verification of the final working configuration.

## 7. EX300 Development Background

The EX400 project builds upon P.U.R.E. Formula SAE's previous Kawasaki EX300 standalone ECU development.

The EX300 used an Alpha X custom ECU with a reported timing-light-verified 130° trigger offset.

The EX300 configuration was used by the team at Formula SAE Michigan 2026.

See:

[EX300 Trigger Configuration](../EX300/Trigger-Configuration.md)

## 8. Development Attribution

**Guillermo Toledo**  
Lead Electronics — P.U.R.E. Formula SAE  
Polytechnic University of Puerto Rico

Crankshaft trigger measurements, preliminary TDC offset calculation, and standalone ECU integration development are credited to Guillermo Toledo.

## 9. Project Status

| Milestone | Status |
|---|---|
| Haltech Elite 2000 selected | Complete |
| Crank trigger physically inspected | Complete |
| Preliminary 120° offset calculated | Complete |
| Timing-light verification | Pending |
| Final trigger offset documented | Pending |
| Full ECU calibration published | Pending |

## 10. Technical Disclaimer

The 120° offset is a preliminary project-specific calculation and has not been verified using a timing light.

It must not be treated as a confirmed factory specification or a universally applicable Haltech setting.

Incorrect trigger synchronization and ignition timing can cause engine damage.

---

**Technical Developer:** Guillermo Toledo  
**Organization:** P.U.R.E. Formula SAE  
**Institution:** Polytechnic University of Puerto Rico
