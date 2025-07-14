# Q&P 1000 Steel – Fracture Mechanisms Dataset

This repository provides the open access dataset and analysis scripts supporting the study:

**"Failure Mechanisms in Quenching and Partitioning (Q&P) Steel under Varying Stress States"**  
by Rongfei Juan and Junhe Lian (2025)

## 📁 Repository Contents

- `/data/`
  - Raw and processed mechanical test data (e.g. force–displacement, stress–strain curves)
  - Stress triaxiality and Lode angle values for each geometry
- `/images/`
  - High-resolution SEM and EBSD images (Fig. 4–10 from the manuscript)
- `/ebsd/`
  - EBSD raw data files (`.ang`/`.ctf`) and phase segmentation codes (MTEX scripts)
- `/scripts/`
  - MATLAB and Python scripts for:
    - EBSD post-processing
    - Phase segmentation strategy
    - Defect statistics plotting
    - Cleavage criterion visualization
- `/docs/`
  - Supporting documentation, figures, and metadata

## 📌 Highlights

- Clear phase separation strategy for Q&P steels (RA, FM, F, TMB)
- Transgranular cleavage fracture analysis using SEM and EBSD
- Mechanics-based criterion for fracture mode transition
- Open dataset to support model validation and further research

## 📜 Citation

If you use this dataset, please cite our paper:

> Juan, R., & Lian, J. (2025). Failure Mechanisms in Quenching and Partitioning (Q&P) Steel under Varying Stress States. *Journal Name*, [DOI link here].

## 📄 License

All data and code in this repository are licensed under the **Creative Commons Attribution 4.0 International (CC BY 4.0)** license.
