# ExcitedStatesQM8

The data was used in our first application of machine learning modeling of excited state properties across chemical space.

_Electronic spectra from TDDFT and machine learning in chemical space_   
Raghunathan Ramakrishnan, Mia Hartmann, Enrico Tapavicza, O. Anatole von Lilienfeld   
J. Chem. Phys. 143, 084111 (2015)    
[https://doi.org/10.1063/1.4928757](https://doi.org/10.1063/1.4928757)

The dataset comprises 
- structures (Cartesian coordinates in Angstroms) of 21786 (22k) molecules relaxed at the B3LYP/6-31G(2df,p) level. This is the method used to relax the QM9 dataset (from Scientific Data, 1 (2014) 140022).
- valence electronic excitation energies (in hartree) and oscillator strengths (in atomic unit, length representation) computed at the levels
  - RI-CC2/def2TZVP
  - LR-TDDFT(PBE0/def2SVP)
  - LR-TDDFT(PBE0/def2TZVP)
  - LR-TDDFT(CAMB3LYP/def2TZVP)
 
  # How to use?

  git clone git@github.com:raghurama123/ExcitedStatesQM8.git

  cd ExcitedStatesQM8

  cd 22k_electronic_spectra_TDDFT_CC2

  The file
  - `gdb8_22k_elec_spec.txt` contains electronic excitation energies (in hartree) and oscillator strengths (in atomic unit, length representation)
  - `XYZ_B3LYP_631G2dfp.xyz` contains equilibrium geometries relaxed at the B3LYP/6-31G(2df,p) level.

