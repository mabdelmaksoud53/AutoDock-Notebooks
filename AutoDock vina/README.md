[![version](https://img.shields.io/badge/version-1.0v-orange)](https://github.com/mabdelmaksoud53/AutoDock-Notebooks)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mabdelmaksoud53/AutoDock-Notebooks/blob/main/AutoDock%20vina/Autodock_vina.ipynb)

# **Cloud-based molecular docking using AutoDock vina software** 


## Hello there!

This is a Jupyter notebook for running Molecular Docking using AutoDock Vina software and Google Colab GPUs. This repository is created by [**Mostafa S. Abd El-Maksoud**](https://github.com/mabdelmaksoud53) and I encourage you to watch this [tutorial](https://youtu.be/xMXHnaEO-qk) before using this pipeline.

**Introduction**

- Molecular docking plays a crucial role in drug discovery and computational biology by predicting the binding modes and affinities of small molecules to target proteins. AutoDock Vina is a widely used software for molecular docking due to its accuracy and efficiency in predicting ligand-protein interactions.
- AutoDock Vina utilizes a scoring function to evaluate the binding energy between a ligand and a protein, helping researchers identify potential drug candidates and understand molecular interactions at a detailed level. The process involves preparing the protein structure, defining the search space (grid box), specifying ligand parameters, running the docking simulation, and analyzing the results.
- Integrating AutoDock Vina with Google Colab offers several advantages, including increased computational power, accessibility from anywhere, and the ability to run multiple docking experiments simultaneously. 
---

**workflows**
1. Begin by setting up a Google Colab notebook with the necessary libraries and dependencies for running AutoDock Vina. This may include installing software packages, mounting Google Drive for data storage, and importing required Python modules.
2. Upload your protein structure files (PDB format) and ligand files (PDBQT format) to Google Drive. Organize them in a suitable directory structure within your Google Drive for easy access during the docking process.
3. Create a configuration file for AutoDock Vina, specifying parameters such as the search space dimensions and exhaustiveness of the search.
4. Runs molecular docking and obtains the output files like ligand_protein complex and log file, the integration allows you to leverage Colab's resources for parallel processing, significantly reducing docking time compared to sequential runs.
- Finally, By integrating AutoDock Vina with Google Colab, you can streamline your molecular docking workflows, optimize resource utilization, and accelerate the discovery of potential drug candidates or protein-ligand interactions.
---

**Citation**

[J. Eberhardt, D. Santos-Martins, A. F. Tillack, and S. Forli. (2021). AutoDock Vina 1.2.0: New Docking Methods, Expanded Force Field, and Python Bindings. Journal of Chemical Information and Modeling.](https://pubs.acs.org/doi/10.1021/acs.jcim.1c00203)

[O. Trott and A. J. Olson. (2010). AutoDock Vina: improving the speed and accuracy of docking with a new scoring function, efficient optimization, and multithreading. Journal of computational chemistry, 31(2), 455-461.](https://onlinelibrary.wiley.com/doi/10.1002/jcc.21334)

---
## License
Copyright (c) 2024 [Mostafa S. Abd El-Maksoud](https://github.com/mabdelmaksoud53)
