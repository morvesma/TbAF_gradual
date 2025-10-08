The first lines of this code correspond to the \Pi_ini, that is, the initial data for the program:

arg(a1).
arg(a2).
arg(a3).
arg(a4).
arg(a5).
arg(a6).
arg(a7).
arg(a8).
arg(a9).

value(a1,90).
value(a2,90).
value(a3,100).
value(a4,65).
value(a5,90).
value(a6,90).
value(a7,90).
value(a8,92).
value(a8,100).
value(a9,65).


rel(a6,a9,r1).
rel(a9,a6,r1).
rel(a7,a9,r1).
rel(a9,a7,r1).
rel(a8,a9,r1).
rel(a9,a8,r1).
rel(a6,a7,r2).
rel(a7,a6,r2).
rel(a7,a8,r2).
rel(a8,a7,r2).
rel(a6,a8,r2).
rel(a8,a6,r2).

weak(r1).
stre(r2).

This code is for running the example of the article. However, other arguments, relations, and values can be used.
