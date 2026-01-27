# OpenMotor-Hardware
Official CAD library for OpenMotor eclectic motor

Welcome to the official hardware repository for **OpenMotor**. This library contains CAD models, technical drawings, and specifications for our open-source industrial propulsion systems.

## License
This hardware is released under the **CERN-OHL-W-2.0** (CERN Open Hardware Licence Version 2 - Weakly Reciprocal).

---

## Naming Convention
Our motor model names contain the technical specification of the unit. Here is how to decode them:

**Example:** `CIANO_1_42 125_40`

| Code | Position | Description | Options |
|:---:|---|---|---|
| **C** | 1. Winding | Concentrated | **C**=Concentrated, **D**=Distributed |
| **I** | 2. Rotor | Inrunner/Outrunner | **I**=Inrunner, **O**=Outrunner |
| **A** | 3. Cooling | Cooling Method | **A**=Air, **L**=Liquid, **O**=Oil |
| **N** | 4. Steel | Stator Material | **G**=Grain Oriented, **N**=Non-Oriented, **C**=FeCo Alloy |
| **O** | 5. Housing | Construction | **O**=Open, **C**=Closed (IP65) |
| **1** | 6. Layers | Winding Layers | 1, 2 |
| **42** | 7. Poles | Pole Count | 12, 28, 42, etc. |
| **125**| 8. Diameter | Stator Diameter (mm)| |
| **40** | 9. Length | Stator Length (mm) | |

---

## Motor Specifications

### Air Cooled Series
Optimized for UAVs and aviation where airflow is available.

| Model Name | Power (kW) | RPM | Trust (kg) | Voltage (V) | Weight (kg) |
|---|---|---|---|---|---|
| **CIAG_2_28 125_25**| 3.7 | 4300 | 21 | 75 | 2 |
| **CIAG_1_42 125_30**| 4.5 | 1900 | 36 | 75 | 2.2 |
| **CIAG_2_28 150_40**| 10 | 2000 | 60 | 400 | 4.9 |
| **CIAG 1_42 175_40**| 13 | 3100 | 60 | 700 | 5.5 |
| **CIAG 2_28 200_30**| 13 | 1600 | 70 | 690 | 7 |

---

## Repository Structure

* **/CAD** - 3D models (STEP format) for integration.
* **/doc** - PDF motors parameters.
* **/test** - Detailed performance curves and thermal data.

---

### Contribution
We welcome contributions! Please open an Issue to discuss proposed changes or submit a Pull Request.
