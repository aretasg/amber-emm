# Performs energy minimization on a small ligand PDB file using AmberTools

## Dependencies & Usage
* AmberTools must be installed for the script to work (intended to be used with AmberTools 18-19). Please consider [conda](https://docs.conda.io/en/latest/miniconda.html) to install [AmberTools](https://anaconda.org/conda-forge/ambertools)
* Python 3.6+
* $AMBERHOME path must be set for the amber directory e.g. 'export AMBERHOME=/home/myname/amber18'. This may be optional if AmberTools was installed using conda
* Replaces input file with the minimized version if no suffix is provided. Make a copy if you want to keep the original ligand PDB file
* For more information about the arguments ```python emm.py -h```

