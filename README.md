# ExcitedStatesQM8

<a>
<img src="https://github.com/raghurama123/ExcitedStatesQM8/blob/main/QM8distribution.png"  height="350">
</a>

The data was used in our first application of machine learning modeling of excited state properties across chemical space.

_Electronic spectra from TDDFT and machine learning in chemical space_              
Raghunathan Ramakrishnan, Mia Hartmann, Enrico Tapavicza, O. Anatole von Lilienfeld           
Journal of Chemical Physics, 143 (2015) 084111 (1-8).   
[https://doi.org/10.1063/1.4928757](https://doi.org/10.1063/1.4928757)


The dataset comprises 
- Structures (Cartesian coordinates in Angstroms) of 21786 (22k) molecules relaxed at the `B3LYP/6-31G(2df,p)` level. This method was used to generate structures of the QM9 dataset (see [Scientific Data, 1 (2014) 140022](https://doi.org/10.1038/sdata.2014.22)).
- Valence electronic excitation energies (in hartree) and oscillator strengths (in atomic unit, length representation) computed at the levels
  - RI-CC2/def2TZVP
  - LR-TDDFT(PBE0/def2SVP)
  - LR-TDDFT(PBE0/def2TZVP)
  - LR-TDDFT(CAMB3LYP/def2TZVP)
 
  # How to download the data?
```
  git clone git@github.com:raghurama123/ExcitedStatesQM8.git

  cd ExcitedStatesQM8

  cd 22k_electronic_spectra_TDDFT_CC2
```

  The file
  - `gdb8_22k_elec_spec.txt` contains electronic excitation energies (in hartree) and oscillator strengths (in atomic unit, length representation)
  - `XYZ_B3LYP_631G2dfp.xyz` contains equilibrium geometries relaxed at the B3LYP/6-31G(2df,p) level.

# Data-mining platform

You can perform data-analysis on this dataset at the MolDis platform [https://moldis.tifrh.res.in/db/dbqm8ex](https://moldis.tifrh.res.in/db/dbqm8ex)    

# References
#### ExcitedStatesQM8 dataset 
_Electronic spectra from TDDFT and machine learning in chemical space_         
Raghunathan Ramakrishnan, Mia Hartmann, Enrico Tapavicza, O. Anatole von Lilienfeld           
Journal of Chemical Physics, 143 (2015) 084111 (1-8).            
[https://doi.org/10.1063/1.4928757](https://doi.org/10.1063/1.4928757)            

#### QM9 dataset
_Quantum chemistry structures and properties of 134 kilo molecules_                
Raghunathan Ramakrishnan, Pavlo O. Dral, Matthias Rupp, O. Anatole von Lilienfeld            
Scientific Data 1, 140022 (2014).          
[https://doi.org/10.1038/sdata.2014.22](https://doi.org/10.1038/sdata.2014.22)          
