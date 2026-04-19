# ROP Dataset for Interpretable Hybrid Prediction Framework

This repository provides the dataset used in the study **“An Interpretable Hybrid Framework Integrating Signal Decomposition and Machine Learning for Rate of Penetration Prediction.”** 

## Dataset Description

- **Number of samples:** 2383
- **Number of variables:** 15
- **Target variable:** `ROP (m/h)`
- **Source:** real drilling data from shale gas exploration wells in Xinjiang

The dataset includes the following variables:

| Column name | Description | Unit |
|---|---|---|
| `ROP (m/h)` | Rate of penetration | m/h |
| `Depth (m)` | Measured drilling depth | m |
| `WOB (kN)` | Weight on bit | kN |
| `SPP (MPa)` | Standpipe pressure | MPa |
| `RPM (r/min)` | Rotary speed | r/min |
| `MW (g/cm3)` | Mud weight | g/cm³ |
| `Temperature (°C)`* | Drilling temperature | °C |
| `Q (m3/min)` | Flow rate | m³/min |
| `Bit diameter (mm)` | Drill bit diameter | mm |
| `ECD (g/cm3)` | Equivalent circulating density | g/cm³ |
| `Formation pressure gradient (psi/ft)` | Formation pressure gradient | psi/ft |
| `Porosity` | Formation porosity | — |
| `FV (s)` | Funnel viscosity | s |
| `Solid content (%)` | Solid content in drilling fluid | % |
| `FL (mL)` | Fluid loss | mL |

## File Structure

```text
.
├── qcrop.csv      # Main dataset used in the study
└── README.md      # Dataset description 
```



## Reference

If you use this dataset in your research, please cite the corresponding article:

```bibtex
@article{huang2026rop,
  title={An Interpretable Hybrid Framework Integrating Signal Decomposition and Machine Learning for Rate of Penetration Prediction},
  author={Jie Huang and Lingrong Kong and Yu Wang and Baolin Liu},
  journal={Petroleum Research},
  year={2026}
}
@article{Liu2022,
  title={A stacked generalization ensemble model for optimization and prediction of the gas well rate of penetration: a case study in Xinjiang},
  author={Naipeng Liu and Hui Gao and Zhen Zhao and Yule Hu and Longchen Duan},
  journal = {Journal of Petroleum Exploration and Production Technology},
   year={2022}
}
```
