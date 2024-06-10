# RGS_Ga_work

This GitHub repository contains the input files for classical molecular dynamics (MD) simulations, including topology files, initial coordinates, and PDB structures of different RGS-Ga complexes. We performed a total of 2 ns simulations for each complex to study their conformational dynamics using the Amber 18 package.

## Folder Structure

- **input-files**
  - **Minimization**: Files for the minimization steps.
    - `min0.in` 100 kcal mol<sup>-1</sup>Å<sup>-2</sup>
    - `min1.in` 25 kcal mol<sup>-1</sup>Å<sup>-2</sup>
    - `min2.in` 20 kcal mol<sup>-1</sup>Å<sup>-2</sup>
    - `min3.in` 15 kcal mol<sup>-1</sup>Å<sup>-2</sup>
    - `min4.in` 10 kcal mol<sup>-1</sup>Å<sup>-2</sup>
    - `min5.in` 5 kcal mol<sup>-1</sup>Å<sup>-2</sup>
    - `min6.in` 0 kcal mol<sup>-1</sup>Å<sup>-2</sup> 
  - **NVT Heating**: Files for the constant volume and temperature (NVT) heating steps.
    - `cum_md0.in` 0-50 K
    - `cum_md00.in` 50-100 K
    - `cum_md000.in` 100-150 K
    - `cum_md0000.in` 150-200 K
    - `cum_md00000.in` 200-250 K
    - `cum_md000000.in` 250-300 K
  - **NVT Equilibration**: Files for the NVT equilibration steps.
    - `cum_md0000000.in` 100 kcal mol<sup>-1</sup>Å<sup>-2</sup>  
    - `1cum_md0000000.in` 25 kcal mol<sup>-1</sup>Å<sup>-2</sup>
    - `2cum_md0000000.in` 20 kcal mol<sup>-1</sup>Å<sup>-2</sup>
    - `3cum_md0000000.in` 15 kcal mol<sup>-1</sup>Å<sup>-2</sup>
    - `4cum_md0000000.in` 10 kcal mol<sup>-1</sup>Å<sup>-2</sup>
    - `5cum_md0000000.in` 5 kcal mol<sup>-1</sup>Å<sup>-2</sup>
    - `6cum_md0000000.in` 0 kcal mol<sup>-1</sup>Å<sup>-2</sup>
  - **NPT Equilibration**: Files for the constant pressure and temperature (NPT) equilibration steps.
    - `npt-equil.in` 1 µs
  - **Production Run**: Files for the production run.
    - `cum_md1.in` 10 ns
- **rgs01-ga** RGS1-Gα<sub>i1
   - PDB ID: [2GTP] (https://www.rcsb.org/structure/2GTP)
- **rgs02-ga** RGS2-Gα<sub>i3
   - PDB ID:
- **rgs04-ga** RGS4-Gα<sub>i1
   - PDB ID:
- **rgs08-ga** RGS8-Gα<sub>i3
   - PDB ID:
- **rgs09-ga** RGS9-Gα<sub>t/i1
   - PDB ID:
- **rgs10-ga** RGS10-Gα<sub>i3
  - PDB ID:
- **rgs16-ga** RGS16-Gα<sub>i1
  - PDB ID:

## Simulation Details

- **Software Used**: Amber 18
- **Simulation Time**: 1 µs for each complex (two times)

These files can be used to replicate the simulations and study the conformational dynamics of RGS-Ga complexes.
