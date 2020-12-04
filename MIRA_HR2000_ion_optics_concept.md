<script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script>

## The ion optic concept of the MIRA-HR2000 instrument

The aim is to design and build a high mass resolution mass spectrometer based on the existing MIRA instrument. The minimum mass resolution required to resolve the key contaminants for clumped isotope analysis is approximately 1600. Thus we are aiming for an instrument that can operate with a resolution in excess of 2000. 

We have demonstrated that MIRA currently has a potential resolution of approximately 1400 when operating under absolutely optimal conditions. The limitation to further increase in the resolution is the energy dispersion of the Nier type ion source and the second order geometric aberrations associated with the beam divergence. In theory it is possible to minimise the geometric aberrations by limiting the beam divergence from the ion source. However, this comes at the loss of sensitivity.

A second approach is to reconfigure MIRA as a double focusing instrument using an electrostatic analyser (esa) between the source and magnet. Double focussing instruments focus with respect to energy and momentum. The energy dispersion of the esa is equal, but opposite in sign to that of the magnet. Thus the two cancel each other out. Similarly, with careful selection of the esa parameters the second order geometric aberrations are the same as for the magnet and cancel.

The design of double focusing instruments is covered by Johnson and Nier (1953) - Angular aberrations in sector shaped electromagnetic lenses for focusing beams of charged particles, Physical Review, 91, 10-17.

### Conditions for Double focusing

The conditions for a combination of energy and second-order divergence focusing are described in detail in Johnson and Nier (1953). It is necessary to solve two simultaneous equations, the first being the energy (or velocity) focusing condition and the second the second-order divergence focusing condition:

$$
M_m \cdot D_e + D_m = 0
$$			

$$
M_m \cdot L_e + L_m = 0
$$	

where *M* represents the magnification of the magnet, *D* represents the energy (or velocity dispersion) and L represents the second-order geometric aberrations. The subscripts *e* and *m* represent the esa and magnet respectively.

For the MIRA magnet *M<sub>m</sub>* = -1. Thus we can write equations 1 and 2 as:

$$
D_e = D_m
$$									

$$L_e = L_m
$$	

*(i) Energy (velocity) focusing*

The velocity dispersion of the MIRA magnet is given by:

$$
D_m = 4 \cdot r_m \cdot \beta
$$	

This is equation 35 of Johnson and Nier (1953), for a z value of 1 (symmetric analyser where the object and image distances are equal) and multiplied by a factor 2 to account for the extended geometry of the MIRA magnet in which the pole faces are rotated with respect to the normal of the optic axis (Wollnik, 1983).

The velocity dispersion of the esa is given by (Johnson and Nier, eqn. 36):

$$
D_e = 2 \cdot r_e \cdot \beta
$$

Again this equation describes the dispersion of a symmetric esa in which the object and image distances are equal. 

Equating equations (5) and (6)  we find for velocity focussing:

$$
r_e = 2 \cdot r_m
$$

The radius of the electrostatic analyser is two times that of the radius of the extended geometry magnet. The MIRA magnet has a radius of 250 mm, thus the esa radius will be 500 mm.

*(ii) Second-order geometry focusing*

Nier and Johnson (1953) give the second-order aberrations for a symmetric magnet as:

$$
L_m = -r_m \cdot \alpha^2
$$

where *α* is the beam divergence. This is for a normal geometry magnet pole faces are normal to the optic axis. In extended geometry instruments we find (Brown et al., 1964):

$$L_m = -4 \cdot r_m \cdot \alpha^2
$$

We can express equation (9) in terms of the esa radius using the relationship between rm and re (equation (7) for a velocity focussing instrument with an extended geometry magnet):

$$
L_m = -2 \cdot r_e \cdot \alpha^2
$$

For a symmetric esa the second-order geometry focusing is a function of the esa sector angle and is given by (Johnson and Nier,  eqn. 31):

$$
L_e = - [\frac{9}{12} \cdot 2 \cdot csc^2 (\frac{\phi_e}{\sqrt 2} - \frac{2}{12})] \cdot r_e \cdot \alpha^2
$$


The solution to the simultaneous equations (10) and (11) gives the condition for second-order geometric focusing. This is illustrated in figure 1 in which *L<sub>m</sub>/r<sub>e</sub>.α*<sup>2</sup> and *L<sub>e</sub>/r<sub>e</sub>.α*<sup>2</sup> are plotted as a function of *Φ*, the esa sector angle.


[image.pdf]


A solution is found for an esa sector angle of 79.6°.

Conclusion

Conditions for double focusing are met using the MIRA magnet and an esa with a sector angle of 79.6° and a radius of 500 mm.
