----------
exafs_coeff_simple

Prepare feff.inp

change x position and distance to X.X

for example,

before

ATOMS * this list contains 2 atoms

* x y z ipot tag distance

0.00000 0.00000 0.00000 0 32 0.00000 0

2.5 0.00000 0.00000 1 52 2.5 1


after

ATOMS * this list contains 2 atoms

* x y z ipot tag distance

0.00000 0.00000 0.00000 0 32 0.00000 0

X.X 0.00000 0.00000 1 52 X.X 1


command

chmod +x exafs_coeff_simple

exafs_coeff_simple

----------
exafs_coeff_beta1

command

chmod +x exafs_coeff_beta1

exafs_coeff_beta1 atom1 atom2

for example,

exafs_coeff_beta1 Ge Te

automatically makes feff.inp

However, smoll distance case shows error

----------
