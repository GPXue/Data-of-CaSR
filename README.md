# Data-of-CaSR

### File “CaSR.pdb”: protein pdb structure used for docking procedure.

### Directory “docking”
- Docking results of all peptides with sdf format.
- A csv file "paper_data_smiles.csv" contains all peptides names, SMILES， MM-GBSA score, EC50.

### Directory "peptide6g_MDproduction" 
- Topology and coordinate files of complex models both in solvent and in vacuo ("*.prmtop": topology files, "*.inpcrd": coordinate files);
- Inputs for AMBER MD engine "*.in" for "minimization", "heating", "prodcution", repsectively.

### Directory "analysis_files"
- subdirectory "energy_decomposition", contains free energy desomposition raws;
- subdirectory "hydrogen_bonds", contains raw file of hydrogen bonds through 500 ns MD production;
- subdirectory "rmsd", contains raw file of root mean square deviation of both protein and peptide 6g through 500 ns MD production;
- subdirectory "rmsf", contains raw files of root mean square deviation of bothe protein and peptide 6g through 500 ns MD production;
- subdirectory 'imgs', contains all figures generated within directory "analysis_files";
- Jupyter Notebook file "plot.ipynb", contains all codes that used for analysis.

