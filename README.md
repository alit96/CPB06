# CPB06
Transformation of a stress tensor on a yield surface CPB06

The program, which transforms the selected stress tensor into a deviatoric stress tensor, calculates the Lode angle \[Theta] and introduces the CPB06 model.
The CPB06 yield surface model has been transformed into a form that depends on \[Theta] and the invariant J2 instead of S1, S2 and S3.
This is followed by the calculation of the new J2* and S1*, S2* and S3*. From the principal stresses, we calculate the tensor sij* (transformation with eigenvectors).
Finally, there is the calculation of the new stress tensor \[Sigma]ij*, which tells us what the stress tensor on the yield surface would be.
