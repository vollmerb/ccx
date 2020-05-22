# SPOOLES 2.2 : SParse Object Oriented Linear Equations Solver

**SPOOLES** is a library for solving sparse real and complex linear systems of equations, written in the C language using object oriented design. At present, there is the following functionality:

1.  Compute multiple minimum degree, generalized nested dissection and multisection orderings of matrices with symmetric structure.
    
2.  Factor and solve square linear systems of equations with symmetric structure, with or without pivoting for stability. The factorization can be symmetric LDLT, Hermitian LDLH, or nonsymmetric LDU. A direct factorization or a drop tolerance factorization can be computed. The factors and solve can be done in serial mode, multithreaded with Solaris or POSIX threads, or with MPI.
    
3.  Factor and solve overdetermined full rank systems of equations using a multifrontal QR factorization, in serial or using POSIX threads.
    
4.  Solve square linear systems using a variety of Krylov iterative methods. The preconditioner is a drop tolerance factorization, constructed with or without pivoting for stability.

***
The SPOOLES library has been developed by members of the Mathematics and Engineering Analysis Unit of Boeing Phantom Works. The library was supported in part by DARPA contract DABT63-95-C-0122 and the DoD High Performance Computing Modernization Program Common HPC Software Support Initiative.

Individuals who have contributed to this package include:

1.  Cleve Ashcraft, Boeing Phantom Works
2.  Roger Grimes, Boeing Phantom Works
3.  Joseph Liu, York University
4.  Jim Patterson, Boeing Phantom Works
5.  Dan Pierce, Boeing Phantom Works
6.  Yichi Pierce, Boeing Phantom Works
7.  Peter Schartz, CSAR Corporation
8.  Juergen Schulze, University of Paderborn
9.  Wei-Pai Tang, University of Waterloo
10.  David Wah, Boeing Phantom Works
11.  Jason Wu, Boeing Phantom Works

**This release is entirely within the public domain; there are no licensing restrictions, and there is no warranty of any sort.**

Contact  cleve.ashcraft@boeing.com  for more information, comments and bug reports.

***
[http://www.netlib.org/linalg/spooles/spooles.2.2.html](http://www.netlib.org/linalg/spooles/spooles.2.2.html)

