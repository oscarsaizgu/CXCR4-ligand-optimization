# CXCR4-ligand-optimization
Computational workflow for the optimization of ligands targeting CXCR4 using Scipion-chem, DeepFrag, and AutoGrow4.

This repository contains the final master's thesis project by Óscar Saiz Gutiérrez, focused on the development of a computational pipeline for the **in silico optimization of ligands targeting the CXCR4 protein**, a key receptor involved in cancer and HIV.

The project integrates multiple tools within the [Scipion-chem](https://github.com/scipion-chem) platform, including:
- **DeepFrag**: fragment-based optimization using deep learning
- **AutoGrow4**: genetic algorithm for de novo ligand design
- **AutoDock-GPU, LeDock, Vina**: docking engines
- **fpocket, p2rank, AutoSite**: for pocket detection and consensus

All steps —from protein preparation to lead optimization— are documented and reproducible, providing a valuable reference for bioinformaticians working on structure-based drug design.

> 📘 [Final PDF Report](./docs/tfm_oscarsaizgutierrez.pdf)
