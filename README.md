# CMOS Inverter Design using Cadence Virtuoso

## Overview

This project demonstrates the complete custom CMOS inverter design flow using Cadence Virtuoso and GPDK090 technology.

The inverter was designed, simulated, laid out, and verified through DRC and LVS checks.

## Specifications

* Technology: GPDK090
* Supply Voltage (VDD): 1.2 V
* Tool: Cadence Virtuoso
* Simulator: Spectre

## Design Flow

1. CMOS Inverter Schematic Design
2. Transient Simulation using Spectre
3. Layout Creation
4. Design Rule Check (DRC)
5. Layout Versus Schematic (LVS)

---

## Schematic

Insert image:

![Schematic](schematic.png)

---

## Transient Response

Insert image:

![Transient Response](transient_response)

### Observation

The output is the logical complement of the input:

| Input | Output |
| ----- | ------ |
| 0     | 1      |
| 1     | 0      |

The transient simulation verifies correct inverter operation.

---

## Layout

Insert image:

![Layout](layout.png)

---

## DRC Verification

Insert image:

![DRC](drc_clean.png)

Result: No DRC Errors Found

---

## LVS Verification

Insert image:

![LVS](inverter_lvs_clean.png)

Result: Schematic and Layout Match

---

## Conclusion

A CMOS inverter was successfully designed and verified using the complete custom IC design flow in Cadence Virtuoso. The design passed both DRC and LVS verification and produced the expected transient response.
