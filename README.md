# CalculiX CrunchiX
 A Free Software Three-Dimensional Structural Finite Element Program.

> Notice: The authors acknowledge that naming conventions and input style formats for CalculiX are based on those used by ABAQUS, a proprietary, general purpose finite element code developed and supported by Hibbitt, Karlsson & Sorensen, Inc (HKS) (http://www.abaqus.com) and are used with kind permission from HKS. Results obtained from CalculiX are in no way connected to ABAQUS.

For a reference describing the theory behind CalculiX CrunchiX the user is referred to:
Dhondt, G. The Finite Element Method for Three-Dimensional Thermomechanical Applications, Wiley, 2004.

***

 #### Authors:
[Guido Dhondt](http://www.dhondt.de/authors.htm)  (Finite Element Solver)  
Klaus Wittig (Pre- and Postprocessor)

#### Contributors
For some essential parts of a finite element program such as mathematical solvers, very good source code has been written by people devoting their whole life to it. Therefore, we are especially grateful to those who agreed to have their code included or referred to, specifically (in alphabetical order of the first author):

- C.C. Ashcraft, R.G. Grimes, D.J. Pierce and D.K. Wah for the SPOOLES sparse matrix solver.
- Johannes Barner for the vda2fbd converter.
- Jeff Baylor for the Windows executable of cgx and ccx, starting from Version 1.5.
- Otto-Ernst Bernhardi for the implementation of the C3D8R (hourglass control), the C3D8I element and the box general beam section.
- M. De Marchi for the Windows executable of ccx, Version 1.2.
- R. Felde for the acis2fbd converter.
- Reinhold Fisher for the contact implementation in modal dynamics calculations.
- B. Graf for the installation guides for Max OS X Mavericks.
- Jaro Hokkanen for face-to-face penalty contact.
- Hibbitt, Karlsson & Sorensen, Inc. for allowing us to use the ABAQUS input format.
- Sven Kassbohm for the Ciarlet elastic model for large strains.
- R.B. Lehoucq, D.C. Sorensen and C. Yang for the ARPACK eigenvalue solver.
- Sascha Merz for the implementation of the Zienkiewicz-Zhu error estimator.
- Carlo Monjaraz-Tec for work on explicit dynamics.
- Pascal Mossier for the cadTools.
- Conrad Mottl for implementing multistage MPC's.
- Yannick Muller for the implementation of aerodynamic networks.
- Matteo Pacher for work on implicit dynamics.
- Vito Pasquariello for the Coulomb friction in penalty contact.
- Axel Philipp for the external face extraction within an existing mesh (cgx).
- Samoela Rakotonanahary for auxiliary routines in face-to-face penalty contact.
- Ernst Rank and Martin Ruecker for the C-version of the iterative solver.
- T. Roesener, who found a way for stepped colors in Linux.
- Dave Rossi for the Windows executable of ccx, Version 1.1.
- Stefan Sicklinger for modifications in penalty contact.
- Saskia Sitzmann for the implementation of the Sutherland-Hodgman algorithm.
- Manfred Spraul for generating the rmp archives, enhancements in the numcheck.awk script and the multithreading capability.
- Scott W. Sloan for the profile reduction algorithms.
- Robert Taylor for the permission to use his profile solver (included up to version 1.7).
- Xinan Zhou for supporting me with the wedge element implementation.

The use of Transactions of Mathematical Software (TOMS) routines 496 (lzhes), 581 (hybsvd) and 584 (cubtri) is gratefully acknowledged. Appropriate references have been included in the User's Manual.
Material data can be found at www.matweb.com.

Finally, the authors would like to thank MTU Aero Engines for the permission to publish this work.

***
[CalculiX - A Three-Dimensional Structural Finite Element Program](http://www.calculix.de/)
