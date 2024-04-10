# BTK_drug_resistance WT complex simulations
 Here, we provided the files used in simulating WT complexes right from the first step.
files are named after their PDB for general description we call them XXXX for convinience.
1. XXXX.gro file is the initial ligand structure used in preparation of complex in the first step;
2. XXXX.itp is the ligand parameter file obtained from SwissParam software (http://www.swissparam.ch/);
3. XXXX_WT_protein_input_charmmGUI.pdb this structure was obtained from preprocessing with CHARMM-GUI and used as initial structure to prepare gromacs files;
4. lastframe_1micS_XXXX_WT_complex.pdb this is the last frame structure of XXXX WT complex obtained at the end of 1 microsecond simulation;
5. md_XXXX_WT.tpr file is the input file for launching gromacs production run;
6. topol_XXXX_WT_complex.top is topology file generated for XXXX WT complex using CHARMM27 force field;

