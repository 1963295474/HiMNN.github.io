# HiMNN: A Hierarchy-aware Multimodal Neural Network for Electrolyte Formulations Property Prediction


---

## 🔬 Overview

**HiMNN** (Hierarchy-aware Multimodal Neural Network) is a novel deep-learning framework for **accurate property prediction in multimolecular systems** (e.g., electrolyte formulations).  
By constructing a **multiscale graph** (atom → molecule → formulation) and **hierarchy-aware multimodal fusion**(atom → molecule → formulation → task) , HiMNN explicitly captures **intermolecular interactions** and **cross-modal relationships**, achieving state-of-the-art performance on four electrolyte datasets.

---

## 📊 Datasets

All datasets are released under **MIT license** and hosted in the [`data/`](data/) folder.  
After paper acceptance, the **full curated splits**, **pre-processing scripts**, and **all model code** will also be made available in this repository.

| Dataset | Domain | #Samples | #Components | Properties | Source |
|---------|--------|----------|-------------|------------|--------|
| **LCE_23** | Liquid electrolytes | 152 | 2–6 | Coulombic efficiency (CE) | [Kim et al. 2023](https://doi.org/10.1039/D3DD00063A) |
| **LiquidCond** | Liquid electrolytes | 3,114 | 2–5 | Ionic conductivity (σ) | [Bradford et al. 2023](https://pubs.acs.org/doi/10.1021/acscentsci.2c01181) |
| **SolidCond** | Solid polymer electrolytes | 11,186 | 2–5 | Ionic conductivity (σ) | [Bradford et al. 2023](https://pubs.acs.org/doi/10.1021/acscentsci.2c01181) |
| **LCE_25*** | Liquid electrolytes | 173 | 2–6 | Coulombic efficiency (CE) | This work (to be released) |

> **LCE_25** extends LCE_23 with all publicly available studies up to **May 2025**; **zero overlap** with LCE_23.  
> These four datasets constitute the most comprehensive electrolyte formulation library publicly available to date, covering all commonly used components.


