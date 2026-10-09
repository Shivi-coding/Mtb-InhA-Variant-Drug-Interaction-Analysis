In-Silico Analysis of Mycobacterium tuberculosis InhA Variants and Drug Interactions

1.) Project Overview:
This project investigates the predicted interactions between Mycobacterium tuberculosis InhA (enoyl-ACP reductase) and the isoniazid–NAD adduct (INH-NAD), comparing wild-type InhA with five selected variants: S94A, I21V, T2A, Y158F, and D148G.

The study uses a structure-based bioinformatics workflow to explore protein–ligand interactions, compare docking scores, and examine how amino acid substitutions may influence predicted ligand binding.

2.) Research Question:
How do selected amino acid substitutions in InhA affect the predicted binding affinity and ligand-interacting residues of the INH-NAD adduct compared with wild-type InhA?

3.) Objectives:
Retrieve wild-type and variant protein structures from the RCSB Protein Data Bank.
Prepare protein structures and ligand files for molecular docking.
Compare the predicted interactions of isoniazid and the INH-NAD adduct with InhA.
Analyze docking scores and ligand-contacting residues across selected variants.
Explore the potential relevance of structural differences to isoniazid resistance.

4.) Tools and Resources:
RCSB Protein Data Bank (PDB): Protein structure retrieval
PubChem: Isoniazid structure retrieval
Discovery Studio Visualizer: Structure preparation and interaction visualization
AutoDock Vina / PyRx: Molecular docking
PyMOL: Protein structure visualization, where applicable

5.) Methodology:
Structure retrieval: Obtain the wild-type InhA structure and selected variant structures.
Protein preparation: Remove selected water molecules and crystallographic ligands, prepare receptor structures, and add the required hydrogens and charges.
Ligand preparation: Prepare isoniazid and the INH-NAD adduct for docking.
Molecular docking: Dock isoniazid against wild-type InhA and compare INH-NAD adduct docking across wild-type and variant structures.
Pose analysis: Examine the best-scoring poses, predicted binding affinities, and ligand-contacting residues.
Comparative analysis: Compare the docking results across all six protein structures.


6.) Results:
Docking Scores for the INH-NAD Adduct
Protein structure	Best docking score (kcal/mol)
S94A	-11.8
D148G	-11.0
Wild type	-10.5
Y158F	-10.5
I21V	-10.1
T2A	-9.5

The most negative docking score was observed for S94A (-11.8 kcal/mol), while T2A showed the least negative score (-9.5 kcal/mol) among the tested structures.

For wild-type InhA, the reported docking scores were -5.8 kcal/mol for isoniazid and -10.5 kcal/mol for the INH-NAD adduct.

These values represent computational docking predictions and should not be interpreted as experimentally measured binding affinities.

7.) Conclusion:
This project compares predicted interactions of the INH-NAD adduct with wild-type InhA and five selected variants using a molecular docking workflow. The results demonstrate differences in predicted docking scores among the tested structures.

The findings provide a starting point for further investigation of InhA–ligand interactions. Additional validation, including redocking controls, molecular dynamics simulations, and experimental studies, would be required to establish the biological significance of these predictions and their relationship to drug resistance.

8.) Future Directions:
Molecular dynamics simulations using GROMACS or other suitable simulation packages.
Further analysis of protein–ligand interactions and binding-site stability.
Investigation of additional InhA variants and ligand derivatives.
Comparison of computational predictions with published experimental evidence.


9.) Project Contributors:
Shivangi Singh and Anushreeya Khati


10.) Disclaimer:
This project is an academic computational study. Docking scores are predictions and do not independently establish drug resistance, binding affinity, or biological activity.
