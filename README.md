# Repurposing FDA-Approved Drugs to Inhibit Monkeypox DNA Polymerase

### Overview

This project focuses on identifying potential inhibitors of Monkeypox virus DNA polymerase through drug repurposing approaches using computational biology and molecular modeling techniques. FDA-approved drugs were screened using molecular docking, molecular dynamics simulation, and ADMET analysis to identify promising therapeutic candidates.

The study aims to accelerate antiviral drug discovery by evaluating already approved compounds for potential activity against Monkeypox virus replication machinery.

### Objectives
Select FDA-approved drug molecules for screening
Retrieve and prepare the Monkeypox DNA polymerase structure
Prepare ligand molecules for docking
Perform molecular docking analysis
Analyze docking scores and binding interactions
Evaluate pharmacokinetic and toxicity properties using ADMET analysis
Identify top candidate molecules for potential repurposing


### Workflow
1. Target Structure Retrieval
Retrieved Monkeypox DNA polymerase structure from public protein databases
Verified structural integrity and suitability for docking studies
2. Protein Preparation
Removed water molecules and unwanted chains
Added hydrogens and optimized the structure
Performed energy minimization using Schrodinger tools
3. Ligand Preparation
Selected FDA-approved drugs from public databases
Converted structures into suitable docking formats
Generated optimized ligand conformations
4. Molecular Docking
Generated receptor grids
Performed docking using Schrodinger Glide
Ranked compounds based on docking scores and binding affinity
5. Binding Interaction Analysis
Visualized protein–ligand interactions using PyMOL
Identified hydrogen bonds, hydrophobic interactions, and key residues
6. ADMET Analysis
Evaluated:
Absorption
Distribution
Metabolism
Excretion
Toxicity
Used SwissADME and ADMETlab for pharmacokinetic profiling
7. Candidate Selection
Shortlisted compounds showing:
Strong binding affinity
Stable interactions
Favorable ADMET properties
8. Molecular Dynamics Simulation
The stability of the protein-ligand complex was evaluated
Hellped analyze the dynamic behavior and interaction stability of shortlisted drug candidates with Monkeypox DNA polymerase over time.

### Tools and Software Used
Schrodinger -	Molecular docking and simulation
PyMOL -	Visualization and interaction analysis
SwissADME -	Drug-likeness and pharmacokinetic analysis
ADMETlab - ADMET property prediction

### Key Outcomes
Identified several FDA-approved compounds with promising binding affinity toward Monkeypox DNA polymerase
Observed stable protein–ligand interactions through docking analysis
Shortlisted drug candidates with favorable pharmacokinetic properties for further investigation

### Future Scope
Molecular dynamics simulation for stability validation
MM-GBSA binding free energy calculations
In vitro and in vivo validation studies
Structure-based optimization of shortlisted compounds


Muhsina Shahul
Postgraduate in Bioinformatics 
