# RGS_Ga_work
This GitHub repository contains the input files of classical MD simulation, topology initial cord, and PDB structures of different RGS-Ga complexes. 
We performed a total of 2 ns simulations for each complex to study the conformational dynamics of the different RGS-Ga complexes. 
We used the Amber 18 package to run the simulation. 
The "input-files" folder contains the minimization (min0.in, min1.in, ...., min6.in), 
NVT heating (cum_md0.in, cum_md00.in, ...., cum_md0000000.in), 
NVT equilibration (1cum_md0000000.in, 2cum_md0000000.in, ...., 6cum_md0000000.in) 
with different positional constraints from 100 to 0 kcal mol−1Å−2 , NPT equilibration, and production run (cum_md1.in) files.
