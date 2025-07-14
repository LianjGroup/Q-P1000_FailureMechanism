# Q&P 1000 Steel – Fracture Mechanisms Dataset

This repository provides the open access dataset and analysis scripts supporting the study:

**"Failure Mechanisms in Quenching and Partitioning (Q&P) Steel under Varying Stress States"**  
by Rongfei Juan and Junhe Lian (2025)

## 📁 Repository Contents
### 🔬 Experimental Data

- `/data/`
  - Raw and processed mechanical test data for all geometries (e.g. SDB, CH, SH)

### 🖼️ SEM Images

- `/images/initial_SEM/`
  - Scanning Electron Microscopy (SEM) images of undeformed Q&P 1000 steel
- `/images/fracture_SEM/`
  - Fractography SEM images of all fractured specimens at various magnifications
- `/images/cross_section_SEM/`
  - SEM images of metallographic cross-sections used for damage mechanism analysis

### 🧭 EBSD Data

- `/ebsd/initial_EBSD/`
  - Raw `.ang` or `.ctf` files, phase maps, grain maps, GOS/PQ maps of the initial microstructure
- `/ebsd/fractured_EBSD/`
  - EBSD characterization near crack initiation sites for each geometry (e.g., CH, SH, NDB-R6)
  - Includes orientation, strain localization, and phase transformation maps

### 🧩 Scripts

- `/scripts/`
  - MATLAB scripts for EBSD phase segmentation and MTEX workflow
  - Python scripts for plotting damage statistics and cleavage criteria
  - Calculation scripts for fracture strain and critical triaxiality

### 📑 Documentation

- `/docs/`
  - Metadata summary of all datasets (materials, SEM/EBSD settings, etc.)
  - Figure-to-data cross-reference list

## 📌 Highlights

- Clear phase separation strategy for Q&P steels (RA, FM, F, TMB)
- Transgranular cleavage fracture analysis using SEM and EBSD
- Mechanics-based criterion for fracture mode transition
- Open dataset to support model validation and further research

## 📜 Citation

If you use this dataset, please cite our paper:

> Juan, R., & Lian, J. (2025). Failure Mechanisms in Quenching and Partitioning (Q&P) Steel under Varying Stress States. JMST, [DOI link here].

## 📄 License

This repository is licensed under the [MIT License](./LICENSE).  
You are free to use, modify, and distribute this work, provided that proper credit is given.

