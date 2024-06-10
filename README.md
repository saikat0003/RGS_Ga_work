# RGS_Ga_work

This GitHub repository contains the input files for classical molecular dynamics (MD) simulations, including topology files, initial coordinates, and PDB structures of different RGS-Ga complexes. We performed a total of 2 ns simulations for each complex to study their conformational dynamics using the Amber 18 package.

## Folder Structure

- **input-files**
  - **Minimization**: Files for the minimization steps.
    - `min0.in` 100 kcal mol<sup>-1</sup>Å<sup>-2</sup>
    - `min1.in`
    - `min2.in`
    - `min3.in`
    - `min4.in`
    - `min5.in`
    - `min6.in`
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
