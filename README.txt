These are the source codes used in

E. Barreto and J.R. Cressman, "Ion Concentration Dynamics as a
Mechanism for Neuronal Bursting",
Journal of Biological Physics 37, 361-373 (2011).

Link to the paper:
http://www.springerlink.com/content/v52215p195159211/

Author-generated version available at: http://arxiv.org/abs/1012.3124

The .ode files run with XPP.

The .c file is in C and uses headers and the rk4 routine from
Numerical Recipies.

The parameters that recreate the subplots of Figure 4 are shown using
XPP in a collection of jpgs included in this archive. Note that the
XPP code is written so as to measure time in milliseconds.

The authors recommend that modelers use the more efficient C code,
which outputs time in seconds, and which includes in the comments the
parameter values used for all five burst types.

Parameter values for all figures are also listed in the paper itself.
