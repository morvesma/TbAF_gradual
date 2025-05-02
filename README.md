The first lines of this code correspond to the \Pi_ini, that is, the initial data for the program:

arg(a).
arg(b).
arg(c).
arg(d).

value(a,75).
value(a,40).
value(b,80).
value(c,28).
value(d,40).

rel(b,a,r1).
rel(a,b,r1).
rel(d,a,r1).
rel(a,d,r1).
rel(d,a,r2).
rel(b,c,r2).
rel(b,d,r2).
rel(d,b,r2).
rel(d,c,r2).
rel(a,c,r1).
rel(c,a,r1).
rel(c,b,r2).
rel(c,d,r1).


weak(r1).
stre(r2).

This code is for running the example of the article. However, other arguments, relations, and values can be used.
