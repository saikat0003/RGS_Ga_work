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
    - `min5.in`kcal 5 mol<sup>-1</sup>Å<sup>-2</sup>
    - `min6.in`kcal 0 mol<sup>-1</sup>Å<sup>-2</sup> 
  - **NVT Heating**: Files for the constant volume and temperature (NVT) heating steps.
    - `cum_md0.in`
    - `cum_md00.in`
    - `cum_md0000000.in`
  - **NVT Equilibration**: Files for the NVT equilibration steps with different positional constraints from 100 to 0 kcal mol−1Å−2.
    - `1cum_md0000000.in`
    - `2cum_md0000000.in`
    - `3cum_md0000000.in`
    - `4cum_md0000000.in`
    - `5cum_md0000000.in`
    - `6cum_md0000000.in`
  - **NPT Equilibration**: Files for the constant pressure and temperature (NPT) equilibration steps.
  - **Production Run**: Files for the production run.
    - `cum_md1.in`

## Simulation Details

- **Software Used**: Amber 18
- **Simulation Time**: 2 ns for each complex

These files can be used to replicate the simulations and study the conformational dynamics of RGS-Ga complexes.
