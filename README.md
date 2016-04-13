jointcal_cholmod
#############

This package groups C functions extracted from **SuiteSparse** to collect the
functions we need, without any other dependencies.

http://faculty.cse.tamu.edu/davis/suitesparse.html

This package was created by converting the symlinks in lsst-framce/micro_cholmod into real files from **SuiteSparse** 4.4.6. The various license files in the root were copied from the sub-packages the files were taken from.

The selection of routines is meant to allow the user to perform a simplicial
Cholesky factorization of a sparse matrix, possibly followed by small rank updates of the factorization, solving (factorizes) linear systems,  and nothing else. This is why this is a small subset of **SuiteSparse**. 
