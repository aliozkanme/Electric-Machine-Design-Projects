<p align="center">
  <img height="400" src="General-View.png">
</p>

<h1 align="center"> ⚙️ Inrunner SPM BLDC Motor Design</h1>

---
## Introduction


As an experienced Electrical-Electronics Engineer, I combine my technical domain knowledge with strong SolidWorks skills to design complex **electromechanical systems**. 

While my component modeling focuses on datasheet adherence, my approach to **Electric Machine Design** goes further—bridging the critical gap between electromagnetic specifications and mechanical feasibility. I focus on creating manufacturing-ready motor assemblies that account for:
* **Mechanical Integrity:** Proper bearing selection and interference fits.
* **Electromagnetic Constraints:** Precise stator slot geometry and magnet placement.

This section features high-precision motor assemblies engineered from scratch, serving as reliable assets for both mechanical integration and multi-physics simulations.

### 🎥 Exploded View Animation
To visualize the internal structure, winding layout, and assembly sequence of the motor, you can watch the detailed exploded view animation on YouTube.

[![Watch the Exploded View Animation](https://img.youtube.com/vi/kZ_DtLG9tV0/hqdefault.jpg)](https://www.youtube.com/watch?v=kZ_DtLG9tV0)

> **Click the image above to watch the animation.**

### ⚡ Electromagnetic Finite Element Analysis (FEA) - ANSYS Maxwell

To validate the electromechanical performance, a **2D Transient Magnetic Analysis** was conducted using ANSYS Maxwell. This simulation verifies the magnetic flux path, core saturation levels, and torque production capability under load.

| Analysis Parameter | Value / Condition | Observation |
| :--- | :--- | :--- |
| **Simulation Type** | Transient 2D | 1/2 Symmetry Model |
| **Rotational Speed** | 1593 RPM | Rated Speed Operation |
| **Max Flux Density ($B_{max}$)** | ~2.2 Tesla | Saturation localized at tooth tips (Red zones) |
| **Stator Yoke Flux** | ~1.3 - 1.5 Tesla | Within optimal linear region (Green/Yellow zones) |

#### 🎥 Magnetic Flux Distribution Animation
The visual below displays the **Magnetic Flux Density ($B$)** distribution across the stator core and rotor magnets.

[![Watch the Exploded View Animation](https://img.youtube.com/vi/-LHAmMvmeAM.jpg)](https://www.youtube.com/watch?v=-LHAmMvmeAM)

> **Visualization:** Transient check of flux lines and density at 1592 RPM. **Click the image above to watch the full simulation.**

---

### End Shields
| Component | Model / Part No | Datasheet |
| :--- | :--- | :--- |
| **Front End Shield** | 356.0-T6 Permanent Mold Casting | --- |
| **Rear End Shield** | 356.0-T6 Permanent Mold Casting | --- |

#### BLDC Motor Front End Shield
<p align="center">
  <img src="assets/Front-End-Shield-1.png" width="500" style="margin-right: 10px;" />
  <img src="assets/Front-End-Shield-2.png" width="500" />
</p>

#### BLDC Motor Rear End Shield
<p align="center">
  <img src="assets/Rear-End-Shield-1.png" width="500" style="margin-right: 10px;" />
  <img src="assets/Rear-End-Shield-2.png" width="500" />
</p>

---

### Motor Frame
| Component | Model / Part No | Datasheet |
| :--- | :--- | :--- |
| **Motor Frame** | 356.0-T6 Permanent Mold Casting | --- |

#### BLDC Motor Frame
<p align="center">
  <img src="assets/Motor-Frame-1.png" width="500" style="margin-right: 10px;" />
  <img src="assets/Motor-Frame-2.png" width="500" />
</p>

---

### Ball Bearings
| Component | Model / Part No | Datasheet |
| :--- | :--- | :--- |
| **Ball Bearing** | 6007 | --- |
| **Ball Bearing** | 6010 | --- |

#### Ball Bearings 6007 / 6010
<p align="center">
  <img src="assets/Ball-Bearing-1.png" width="500" style="margin-right: 10px;" />
  <img src="assets/Ball-Bearing-2.png" width="500" />
</p>

---

### Motor Shaft
| Component | Model / Part No | Datasheet |
| :--- | :--- | :--- |
| **Shaft** | AISI 4340 Normalized Steel | --- |

#### BLDC Motor Shaft
<p align="center">
  <img src="assets/Motor-Shaft-1.png" width="500" style="margin-right: 10px;" />
  <img src="assets/Motor-Shaft-2.png" width="500" />
</p>

---

### Magnet Block
| Component | Model / Part No | Datasheet |
| :--- | :--- | :--- |
| **Shaft** | Sintered Neodymium-Iron-Boron Magnets | --- |

#### BLDC Motor Magnets
<p align="center">
  <img src="assets/Block-Magnets-1.png" width="500" style="margin-right: 10px;" />
  <img src="assets/Block-Magnets-2.png" width="500" />
</p>

---

### Lamination Stacks
| Component | Model / Part No | Datasheet |
| :--- | :--- | :--- |
| **Lamination Stack Stator** | M350-50A | --- |
| **Lamination Stack Rotor** | M350-50A | --- |

#### BLDC Motor Stack Stator
<p align="center">
  <img src="assets/Lamination-Stack-Stator-1.png" width="500" style="margin-right: 10px;" />
  <img src="assets/Lamination-Stack-Stator-2.png" width="500" />
</p>

#### BLDC Motor Lamination Stack Rotor
<p align="center">
  <img src="assets/Lamination-Stack-Rotor-1.png" width="500" style="margin-right: 10px;" />
  <img src="assets/Lamination-Stack-Rotor-2.png" width="500" />
</p>

---

### Electromagnetic Core

<p align="center">
  <img src="assets/Electromagnetic-Core-1.png" width="500" style="margin-right: 10px;" />
  <img src="assets/Electromagnetic-Core-2.png" width="500" />
</p>

<p align="center">
  <img src="assets/Electromagnetic-Core-3.png" width="500" style="margin-right: 10px;" />
  <img src="assets/Electromagnetic-Core-4.png" width="500" />
</p>

### BLDC Motor

#### BLDC Motor Back View
<p align="center">
  <img src="assets/Motor-BLDC-Back-1.png" width="500" style="margin-right: 10px;" />
  <img src="assets/Motor-BLDC-Back-2.png" width="500" />
</p>

#### BLDC Motor Front View
<p align="center">
  <img src="assets/Motor-BLDC-Front-1.png" width="500" style="margin-right: 10px;" />
  <img src="assets/Motor-BLDC-Front-2.png" width="500" />
</p>

#### BLDC Motor Frame View
<p align="center">
  <img src="assets/Motor-BLDC-Frame-1.png" width="500" style="margin-right: 10px;" />
  <img src="assets/Motor-BLDC-Frame-2.png" width="500" />
</p>

---
<p align="center">
<img src="https://img.shields.io/badge/License-CC_BY--NC--SA_4.0-lightgrey?style=flat-square&logo=creative-commons" alt="Creative Commons">
</p>
