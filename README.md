# Molecular-Docking-for-D-arabinose-5-phosphate-isomerase-gutQ-of-E.-coli-and-Emodin
I did docking with galaxy software for  D-arabinose 5-phosphate isomerase, gutQ of E. coli and Emodin and my output files has been displayed 
Software and Tools Used
Software	Purpose
AutoDock Vina	Molecular docking
PyMOL	Structure visualization
Discovery Studio Visualizer	Interaction analysis
Open Babel	File conversion and ligand preparation
PubChem	Ligand retrieval
Protein Data Bank (PDB)	Protein structure retrieval
Workflow
1. Protein Preparation
Retrieved GutQ protein structure from Protein Data Bank.
Removed water molecules and heteroatoms.
Added polar hydrogens.
Assigned Kollman charges.
Saved prepared protein in .pdbqt format.
2. Ligand Preparation
Downloaded Emodin structure from PubChem.
Converted structure into appropriate docking format.
Energy minimization performed.
Added Gasteiger charges.
Saved ligand in .pdbqt format.
3. Molecular Docking
Defined docking grid around active site residues.
Docking simulation performed using AutoDock Vina.
Multiple binding conformations generated.
Best docking pose selected based on binding affinity.
4. Visualization and Interaction Analysis
Visualized docked complex using PyMOL.
Analyzed hydrogen bonds and hydrophobic interactions.
Identified important interacting residues.
Results
Docking Score -7.47
Parameter	Value


