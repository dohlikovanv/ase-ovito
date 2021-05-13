# ase-ovito
scripts for calculate energy and electronic density for atomic cluster
Requirement programms
ASE 
https://wiki.fysik.dtu.dk/ase/install.html
OVITO
https://www.ovito.org/
NUMPY
https://numpy.org/install/

surface_energy.py
semi.py
meam.py
This scripts read input file - cluster_tmp.xyz, atomic structure of cluster, and make output file - xyz-file of surface atoms with additional columns. 
In surface_energy.py columns contain values of surface energy and surface energy weighted by the maximum coordination number.
In semi.py columns contain values of electron density, calculated in Finnis-Sinclair, Satton-Chen and Gupta potentials.
In meam.py columns contain values of electron density, calculated in MEAM-model
