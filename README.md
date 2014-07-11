RedSVD-h
========

A fully templated, header-only version of [RedSVD](https://code.google.com/p/redsvd/).

This is a refactoring of *RedSVD* that removes dependency on scalars of type `float` by explicitly templating all types in the same way the *Eigen* library does.
This makes it possible to use *RedSVD* for matrix types other than `MatrixXf`.
All three classes `RedSVD`, `RedSymEigen` and `RedPCA` can be found in the `include/RedSVD/RedSVD-h` header file.
