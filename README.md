# CUB_RS
Software for computing algebraic cubature rules of degree n on domains defined parametrically by rational splines.

» Object: CUB_RS: Matlab toolbox for algebraic cubature on NURBS-shaped domains. 

The main folder CUB_RS contains:

PAPER_EXPERIMENTS that includes all the Matlab routines useful for reproducing the experiments described in the work [1] and [2] (see references below);
BEZIER_ROUTINES that includes all the Matlab routines useful for integration over domains whose boundary is defined by composite Bezier arcs;
NURBS_ROUTINES that includes all the Matlab routines useful for integration over domains whose boundary is defined by NURBS;
SPLINE_ROUTINES that includes all the Matlab routines useful for integration over domains whose boundary is defined by general parametric splines.
All these folders contain several demos, useful to define the domains, to understand how to use the indomain routine as well as the cubature routine. Some examples on hyperinterpolation are also available. 

The main routines are:

inRS that implements a fast indomain algorithm for these instances; the last update presents a faster indomain algorithm inRS, presented in [2]; the older version introduced in [1] is present in the file inRS_21;
cubRS that determines an algebraic cubature formula of the desired degree of exactness, with low cardinality, internal nodes and positive weights.



» Sources: 

Paper: 
» [1] A. Sommariva and M. Vianello, Low-cardinality Positive Interior cubature on NURBS-shaped domains, [PDF]; 
» [2] A. Sommariva and M. Vianello, inRS: implementing the indicator function for NURBS-shaped planar domains. 
Codes:
Last version: [MATLAB CODES (zip file)],

Presentation:
Presentation at SA 2022: [PDF (Beamer)]
» Last update: January 05, 2022. 
