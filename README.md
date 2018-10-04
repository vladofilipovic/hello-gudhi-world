# hello-gudhi-world

## Purpose

This project is an example to help developpers to make their own C++ project on top of the GUDHI library.

## Third party installation

Please refer to [GUDHI installation](http://gudhi.gforge.inria.fr/doc/latest/installation.html) page and [CGAL installation](https://doc.cgal.org/latest/Manual/installation.html) page.

In this example we will compile the Alpha complex persistence utility in an external project.

This requires c++11, Boost ≥ 1.48.0, CMake ≥ 3.1, CGAL ≥ 4.7.0, Eigen3 ≥ 3.1.0 and GMP.
TBB will be optional for CGAL and GUDHI modules.

Note that GUDHI needs to be installed ('make install').
