================
jointcal_cholmod
================

This package collects the C functions extracted from **SuiteSparse** we need for jointcal, without any other dependencies. In particular, this avoids a dependency on BLAS/LAPACK, which is unnecessary for jointcal.

http://faculty.cse.tamu.edu/davis/suitesparse.html

This package was created by converting the symlinks in lsst-france/micro_cholmod into real files, from **SuiteSparse** 4.4.6. The various license files in the root were copied from the sub-packages those files were taken from.

The selection of routines is meant to allow the user to perform a simplicial Cholesky factorization of a sparse matrix, possibly followed by small rank updates of the factorization, solving (factorizes) linear systems,  and nothing else. This is why this is a small subset of **SuiteSparse**. 
