# SGroup123
SGroup123 is a program to analyze spage group symmetry for 1D, 2D, and 3D periodic systems. The first version of SGroup123 was programmed in FORTRAN 77 as a part of the energy band DFT module mainly between 2005-2007 when I worked in [Prof. Wenjian Liu's group](http://old.chem.pku.edu.cn/lwj/) at Peking University. Starting from 2017, we have been rewriting the program in Fortran 90.

This webpage is still under construction, and the Fortran 90 source codes of SGroup123 are not provided at the moment. However a win32 binary excutable file with a manual (in Chinese) and some tests can be obtained from my personal webpage [http://qchem.pw/mycode/index.html](http://qchem.pw/mycode/index.html).

## Features

1. Determination or definition of 75 rod groups, 80 slab sroups (or layer groups), and 230 space groups for 1D, 2D, and 3D periodic systems.
2. Plot Wigner-Seitz cell and irreducible Brillouin zone using Matlab.

### To be done

1. An interface to the quantum chemistry program [BDF](http://182.92.69.169:7226/) for periodic boundary condition calculations.
2. Plot Wigner-Seitz cell and irreducible Brillouin zone using [Asymptote](http://asymptote.sourceforge.net/).
