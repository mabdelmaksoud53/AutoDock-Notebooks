[![version](https://img.shields.io/badge/version-1.0v-orange)](https://github.com/mabdelmaksoud53/AutoDock-Notebooks)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mabdelmaksoud53/AutoDock-Notebooks/blob/main/AutoDock4.2/AutoDock4.ipynb)


# **Cloud-based molecular docking using AutoDock4.2 software** 


## Hello there!

This is a Jupyter notebook for running Molecular Docking using AutoDock4.2 software and Google Colab GPUs. This repository is created by [**Mostafa S. Abd El-Maksoud**](https://github.com/mabdelmaksoud53) and I encourage you to watch this [tutorial](https://youtu.be/xMXHnaEO-qk) before using this pipeline.

**Introduction**

- Molecular docking is a computational technique used in drug discovery and structural biology to predict the binding mode and affinity of small molecules with a target protein. AutoDock 4.2 is a popular tool for molecular docking that employs a Lamarckian genetic algorithm to explore ligand conformations and optimize binding interactions.
- AutoDock 4.2 utilizes scoring functions to estimate the binding energy between a ligand and a protein receptor, helping researchers identify potential drug candidates and understand molecular recognition processes. The docking process involves preparing the receptor and ligand structures, defining search parameters, running docking simulations, and analyzing the results to identify favorable binding poses. 
---

**workflows**
1.  Install AutoDock 4.2 and its dependencies. Using shell commands within the notebook to install the software and configure the environment.
2. Upload your receptor and ligand files (in PDBQT format) to Google Drive or directly to the Colab environment. Organize your files in a structured manner for easy access during the docking process.
3. Use your local machine to generate input files required for AutoDock 4.2, including the receptor and ligand files, grid parameter file (GPF), and docking parameter file (DPF).
4. Execute both AutoGrid and AutoDock to generate the grid log files (GLF), and docking log file (DLF). docking runs.
- By integrating AutoDock 4.2 with Google Colab, you can leverage cloud computing resources to accelerate molecular docking experiments and optimize parameter exploration for drug discovery and protein-ligand interaction studies.
---


**Citation**

[Morris, G. M., Huey, R., Lindstrom, W., Sanner, M. F., Belew, R. K., Goodsell, D. S. and Olson, A. J. (2009) Autodock4 and AutoDockTools4: automated docking with selective receptor flexiblity. J. Computational Chemistry 2009, 16: 2785-91.](https://doi.org/10.1002%2Fjcc.21256)

---
## License
Copyright (c) 2024 [Mostafa S. Abd El-Maksoud](https://github.com/mabdelmaksoud53)
