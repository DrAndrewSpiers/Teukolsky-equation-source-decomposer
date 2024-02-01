# NP-and-GHP-Formalisms-for-2nd-order-Teukolsky
 
Notebook adapted and built on from "The N.P. and G.H.P. formalisms."  Alfonso García-Parrado Gómez-Lobo, Universidade do Minho, Portugal, September 2009, http://www.xact.es/Documentation/English/PublicNPGHP.nb.  
The specific parts of this notebook which were adapted from "The N.P. and G.H.P. formalisms." are the "Newman Penrose Formalism" (apart from the Teukolsky derivation sections) and "GHP Formalism" chapters in the "Set up Notebook" section. The rest of this notebook was created by the author, Andrew Spiers. Additionally, the results in the "Results" section have been checked against results produced by Jordan Moxon.

The motivation for adapting García-Parrado Gómez-Lobo's notebook began to produce a self contained Mathematica notebook in the positive metric signature based on the tetrad being the fundamental objects (whereas García-Parrado Gómez-Lobo's notebook is in a negative metric signature with spin Dyad spinors as fundamental objects). 

Author: Andrew R.C. Spiers
andrewsp33@hotmail.com
https://github.com/DrAndrewSpiers
Department of Mathematical Sciences, University of Nottingham.
10/05/2023

Notebook adapted and built on from "The N.P. and G.H.P. formalisms."  Alfonso García-Parrado Gómez-Lobo, Universidade do Minho, Portugal, September 2009, http://www.xact.es/Documentation/English/PublicNPGHP.nb and "NP-and-GHP-Formalisms-for-2nd-order-Teukolsky" Andrew Spiers, University of Nottingham, 2023.


Author: Andrew Spiers
andrewsp33@hotmail.com
https://github.com/DrAndrewSpiers
Department of Mathematical Sciences, University of Nottingham.
18/01/2024
Teukolsky-equation-source-decomposer.nb provides an example for decomposing the source of the Teukolsky equation using the half-Held formalism.
Held-formalism.nb is provided for those interested in the full Held formalism. They are both only consistent in the Kinnersley tetrad.


Notebooks created in Mathematica 13.2


####  Citation guide

If you use this notebook for research please cite the accompanying paper:

Title: Efficiently Separating the Source of the Teukolsky Equation
Authors: Andrew Spiers
Year: 2024

Also, please cite the original notebooks Example bibtex:
@misc{npnotebook,
author = {A Garc\'ia-Parrado G\'omez-Lobo},
title = {The N.P. and G.H.P. formalisms.},
year = {2009},
howpublished = {http://www.xact.es/Documentation/English/PublicNPGHP.nb},
organization = {Universidade do Minho},
location = { Portugal},
}

@article{Spiers:2023cip,
    author = "Spiers, Andrew and Pound, Adam and Moxon, Jordan",
    title = "{Second-order Teukolsky formalism in Kerr spacetime: Formulation and nonlinear source}",
    eprint = "2305.19332",
    archivePrefix = "arXiv",
    primaryClass = "gr-qc",
    doi = "10.1103/PhysRevD.108.064002",
    journal = "Phys. Rev. D",
    volume = "108",
    number = "6",
    pages = "064002",
    year = "2023"
}


###  Useful References:

Newman, Ezra, and Roger Penrose. "An approach to gravitational radiation by a method of spin coefficients." Journal of Mathematical Physics 3.3 (1962): 566-578.
S . Teukolsky, The Astrophysical Journal, 185 : 635 - 647, 1973 October 15
S. Chandrasekhar's, The Mathematical theory of black holes, Clarendon Press, Oxford University Press, 1983
Geroch, Robert, Alan Held, and Roger Penrose. "A space-time calculus based on pairs of null directions." Journal of Mathematical Physics 14.7 (1973): 874-881.
