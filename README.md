# NCZarr evaluation

Meta repo for the NCZarr eval project.

## Models and use cases

### SWM

An implementation of the [shallow-water equations](https://en.wikipedia.org/wiki/Shallow_water_equations) in Fortran.

- model code: https://git.geomar.de/swm/swm
- build / runtime env: https://git.geomar.de/swm/docker-images
- use cases for the evaluation: https://github.com/martinclaus/swm-nczarr-use-case/

### FESOM

The Finite-volumE Sea ice–Ocean Model (FESOM2).

- docs: https://fesom2.readthedocs.io/
- code: https://github.com/FESOM/fesom2
- build / runtime env: https://github.com/FESOM/FESOM2_Docker/
- quick instructions for running a containerised test case: https://github.com/FESOM/FESOM2_Docker/tree/master/fesom2_test

## Misc pointers

- Even though the current release of netcdf-fortran does not support NCZarr directly, there is a way of building the Fortran lib against the netCDF-C with NCZarr enabled: https://github.com/Unidata/netcdf-fortran/issues/209
- ...
