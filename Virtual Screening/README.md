# **Cloud-based molecular docking using AutoDock vina software** 


## Hello there!

This is a Jupyter notebook for performing Multiple ligand docking using AutoDock Vina software and Google colab GPUs. This repository is created by ([**Mostafa S. Abd El-Maksoud**](https://github.com/mabdelmaksoud53)) and I encourage you to watch this [tutorial](https://youtu.be/xMXHnaEO-qk) before using this pipeline.

**Introduction**

- Molecular docking is a computational technique used in drug discovery and molecular biology to predict the binding mode and affinity of small molecules with a target protein. Multiple ligand docking involves docking several ligands to a protein simultaneously to identify potential drug candidates from a large library of compounds.

- AutoDock Vina is a widely used software for molecular docking due to its accuracy and efficiency in predicting ligand-protein interactions. It employs an efficient search algorithm and scoring function to explore ligand conformations and evaluate binding affinities, making it suitable for both multiple ligand docking and virtual screening studies. 

**workflows**

1. Start by setting up a Google Colab notebook and ensure that GPU acceleration is enabled. Colab provides free access to GPU resources, which can drastically speed up the docking calculations, especially for virtual screening with a large ligand library.

2. Upload your protein and ligand library (in PDBQT format) to Google Drive or directly to the Colab environment. Organize the library for easy access and management during the docking simulations.

3. Create a configuration file for AutoDock Vina, specifying parameters such as the search space dimensions, exhaustiveness of the search, and other settings relevant to virtual screening.

4. Write bash script to automate the multiple ligand docking and virtual screening process. These script will handle file paths, execute Vina commands for each ligand in parallel, and manage the output files.

- By integrating AutoDock Vina with Google Colab and leveraging GPU acceleration, you can accelerate the virtual screening process, enhance computational efficiency, and expedite the discovery of promising drug candidates from large ligand libraries.
---

**Run The Notebook** [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mabdelmaksoud53/VinaDock-Notebooks/blob/main/VinaDock_Notebooks.ipynb)  - `Multiple ligand docking usin AutoDock vina software`

---
**Bugs**
- If you encounter any bugs, please report the issue to https://github.com/mabdelmaksoud53/VinaDock-Notebooks/issues

---
**Citation**

[J. Eberhardt, D. Santos-Martins, A. F. Tillack, and S. Forli. (2021). AutoDock Vina 1.2.0: New Docking Methods, Expanded Force Field, and Python Bindings. Journal of Chemical Information and Modeling.](https://pubs.acs.org/doi/10.1021/acs.jcim.1c00203)

[O. Trott and A. J. Olson. (2010). AutoDock Vina: improving the speed and accuracy of docking with a new scoring function, efficient optimization, and multithreading. Journal of computational chemistry, 31(2), 455-461.](https://onlinelibrary.wiley.com/doi/10.1002/jcc.21334)

---
## Follow Me

[![ResearchGate](https://img.shields.io/badge/Follow%20me%20on-ResearchGate-00A98F?style=for-the-badge&logo=ResearchGate&logoColor=white)](https://www.researchgate.net/profile/Mostafa-Abd-El-Maksoud)
[![YouTube](https://img.shields.io/badge/Subscribe-YouTube-FF0000?style=for-the-badge&logo=YouTube&logoColor=white)](https://www.youtube.com/@mabdelmaksoud)
[![Facebook](https://img.shields.io/badge/Follow%20me%20on-Facebook-1877F2?style=for-the-badge&logo=Facebook&logoColor=white)](https://www.facebook.com/ph.mostsfa)
[![LinkedIn](https://img.shields.io/badge/Connect%20with%20me%20on-LinkedIn-0077B5?style=for-the-badge&logo=LinkedIn&logoColor=white)](https://www.linkedin.com/in/mostafa-sayed-abd-elmaksoud)
