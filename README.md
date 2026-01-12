# OpenMotor-Hardware
Official CAD library for OpenMotor eclectic motor

Welcome to the official hardware repository for **OpenMotor**. This library contains CAD models, technical drawings, and specifications for our open-source industrial propulsion systems.

## License
This hardware is released under the **CERN-OHL-W-2.0** (CERN Open Hardware Licence Version 2 - Weakly Reciprocal).

---

## Naming Convention
Our motor model names contain the technical specification of the unit. Here is how to decode them:

**Example:** `CIANO421 125_40`

| Code | Position | Description | Options |
|:---:|---|---|---|
| **C** | 1. Winding | Concentrated | **C**=Concentrated, **D**=Distributed |
| **I** | 2. Rotor | Inrunner/Outrunner | **I**=Inrunner, **O**=Outrunner |
| **A** | 3. Cooling | Cooling Method | **A**=Air, **L**=Liquid, **O**=Oil |
| **N** | 4. Steel | Stator Material | **G**=Grain Oriented, **N**=Non-Oriented, **C**=FeCo Alloy |
| **O** | 5. Housing | Construction | **O**=Open, **C**=Closed (IP65) |
| **42** | 6. Poles | Pole Count | 12, 28, 42, etc. |
| **1** | 7. Layers | Winding Layers | 1, 2 |
| **125**| 8. Diameter | Stator Diameter (mm)| |
| **40** | 9. Length | Stator Length (mm) | |

---

## Motor Specifications

### Air Cooled Series
Optimized for UAVs and aviation where airflow is available.

| Model Name | Power (kW) | Torque (Nm) | RPM | Weight (kg) | KV Options |
|---|---|---|---|---|---|
| **CIANO122 42_10** | 0.6 | 0.5 | 12,000 | 0.125 | 650, 325 |
| **CIANO282 100_15**| - | - | - | - | - |
| **CIANO421 125_25**| 5 | 16 | 3,000 | 2.2 | 36, 72 |
| **CIANO421 125_40**| - | - | - | - | - |
| **CIANO421 150_40**| 12 | 57 | 2,000 | 5 | 8, 16, 32 |
| **CIAN282 200_70** | 20 | 95 | 2,000 | 10 | 10, 20 |
| **CIANO421 250_60**| 60 | 286 | 2,000 | 22 | 8, 16 |
| **CIAN421 250_70** | - | - | - | - | - |

### Liquid Cooled Series
Designed for heavy-duty robotics and enclosed systems.

| Model Name | Power (kW) | Torque (Nm) | RPM | Weight (kg) | KV Options |
|---|---|---|---|---|---|
| **CILN282 200_50** | 50 | 120 | 4,000 | 11 | 4.2, 8.4 |
| **CILN282 250_50** | 120 | 350 | 4,000 | 20 | 7, 14 |
| **CILG 300_70** | 170 | 670 | 4,000 | 38 | 6, 12 |

---

## Repository Structure

* **/CAD** - 3D models (STEP format) for integration.
* **/Drawings** - 2D PDF technical drawings with mounting dimensions.
* **/Datasheets** - Detailed performance curves and thermal data.

---

### Contribution
We welcome contributions! Please open an Issue to discuss proposed changes or submit a Pull Request.
