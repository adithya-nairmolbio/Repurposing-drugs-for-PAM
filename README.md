Drug Repurposing for Primary Amebic Meningoencephalitis (PAM)

Primary Amebic Meningoencephalitis (PAM) is a rare, rapidly fatal infection caused by Naegleria fowleri.
This project focuses on computational drug repurposing to identify FDA-approved compounds with potential inhibitory activity against key PAM target proteins.


---

🔍 Project Objectives

Identify druggable target proteins associated with PAM

Prepare structure and ligand datasets

Perform molecular docking–based virtual screening

Run molecular dynamics (MD) simulations for top hits

Calculate binding affinity (MM/GBSA or similar)

Rank and prioritize repurposable drug candidates

-----

🧪 Methodology

1. Protein Preparation

Obtained target protein structure (PDB)

Removed water molecules

Added hydrogens and assigned charges

Energy minimized


2. Ligand Library

FDA-approved drugs downloaded from public databases

Converted to .pdbqt format

Energy minimized


3. Molecular Docking

Performed using AutoDock Vina / PyRx

Set exhaustiveness and grid parameters appropriately

Selected top compounds based on binding affinity


4. Molecular Dynamics Simulations

Performed MD using GROMACS

Protein–ligand complexes were solvated and neutralized

100 ns simulation

RMSD, RMSF, Rg, H-bond analysis performed


5. Binding Energy Analysis

MM/GBSA calculations

Identified most stable protein–ligand complexes



---

📁 Project Structure

├── data/        # Protein structures, ligand libraries
├── scripts/     # Docking and MD scripts
├── results/     # Docking results, MD outputs
└── docs/        # Method notes, workflow documentation


---

🧬 Tools Used

AutoDock Vina
MAESTRO
PyMOL
Alphafold



---

🚀 Status

This repository is a work in progress. Experimental files (docking results, MD trajectories, scripts) will be uploaded soon.


---

👤 Author

Adithya Nair
MSc Molecular Biology
GitHub: your username
LinkedIn: your link
