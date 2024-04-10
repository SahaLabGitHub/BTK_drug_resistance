# BTK_drug_resistance MT simulation files
 Here, we provided the files used in simulating MT complexes right from the first step.
files are named after their PDB for general description we call them XXXX for convinience.
1. XXXX.gro file is the initial ligand structure used in preparation of complex in the first step;
2. XXXX.itp is the ligand parameter file obtained from SwissParam software (http://www.swissparam.ch/);
3. XXXX_MT_protein_input_stc_from_100ns_WT_sim.pdb this structure was obtained from simulation XXXX WT complex for 100 ns and then we mutate it and remove its ligand to simulate for 20 ns;
4. XXXX_MT_protein_after_20ns_sim_for_docking.pdb this structure was obtained from 20 ns mutant simulation and used for docking with the respective ligand;
5. lastframe_1micS_XXXX_MT_complex.pdb this is the last frame structure of XXXX MT complex obtained at the end of 1 microsecond simulation;
6. md_XXXX_MT.tpr file is the input file for launching gromacs production run;
7. topol_XXXX_MT_complex.top is topology file generated for XXXX MT complex using CHARMM27 force field;
8. XXXX_docked.pdb is that pose obtained from docking which was used as initial structure for running simulations.
