<script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script>

## The ion optic concept of the MIRA-HR2000 instrument ##


MIRA HR-2000 is a high mass resolution mass spectrometer for stable isotope
measurements and based on the existing MIRA instrument. The reason for designing
a new high mass resolution instrument is because we want to resolve the key
contaminants in clumped isotope analysis of CO$$_2$$ gas. Notably, at mass 47 we
observe the principal contaminants to occur at a lower mass and with a mass
difference of less than 1 in 1600. This suggests that chloro-carbon species such as
$$^{12}$$C$$^{35}$$Cl are likely to be important, rather than hydrocarbons which
would occur on the high mass side of the m/z = 47 peak. To resolve completely
$$^{12}$$C$$^{35}$$Cl from $$^{13}$$C$$^{18}$$O$$^{16}$$O requires a mass
resolution of >1350. We are aiming for an instrument that can operate with a
resolution in excess of 2000.

Previously, we have demonstrated that MIRA currently has a potential resolution
of approximately 1400 when operating under optimal conditions. The limitations to
further increases in the resolution are the energy dispersion associated with the
Nier type ion source (typically 4 to 5 eV) and the second order geometric
aberrations due to the beam divergence from the source - the so called
$$\alpha$$ angle. These aberrations are proportional to $$\alpha^2$$. Thus, a first approach could be to minimise the
geometric aberrations by limiting the beam divergence from the ion
source. This reduces the source aperture and comes with a
loss of sensitivity. This is analogous to the operation of a camera lens where
the sharpest images are obtained with the smallest aperture but the amount of
light collected is restricted. Increasing the aperture to allow in more light
sees a reduction in the sharpness of the image.

A second approach is to reconfigure the single focusing MIRA as a double focusing instrument using
an electrostatic analyser (esa) between the source and magnet. Double focusing
instruments focus with respect to both energy and momentum whereas the single focusing instrument focuses with respect to momentum alone. The energy dispersion of
the esa is equal, but opposite in sign to that of the magnet. Thus the two
cancel each other out. Similarly, with careful selection of the esa geometry
the second order geometric aberrations are the same magnitude but in the
opposite direction as for the magnet and cancel.

The concept for the MIRA HR-2000 instrument is based on the theoretical
treatment of double focusing instruments given by Johnson and Nier (1953) - Angular
aberrations in sector shaped electromagnetic lenses for focusing beams of
charged particles, Physical Review, 91, 10-17. Here we summarise the key aspects
of this paper in relation to designing an esa for the existing MIRA instrument.

The MIRA magnet is an extended geometry design with a radius of 250 mm radius and a 
120$$^\circ$$ sector field giving an effective dispersion equivalent to
that of a 500mm radius normal geometry magnetic sector. The magnet has a
magnification in the x-y plane of -1

### Geometric conditions for double focusing

The conditions for a combination of energy and second-order divergence focusing
are described in detail in Johnson and Nier (1953). It is necessary to solve two
simultaneous equations, the first being the energy (or velocity) focusing
condition and the second the second-order divergence focusing condition:

$$
M_m \cdot D_e + D_m = 0
$$

$$
M_m \cdot L_e + L_m = 0
$$

where *M* represents the magnification of the magnet, *D* represents the energy
(or velocity dispersion) and L represents the second-order geometric
aberrations. The subscripts *e* and *m* represent the esa and magnet
respectively.

For the MIRA magnet *M*$$_m$$ = -1. Thus we can write equations 1 and 2 as:

$$
D_e = D_m
$$

$$
L_e = L_m
$$

*(i) Energy (velocity) focusing*

The velocity dispersion of the MIRA magnet is given by:

$$
D_m = 4 \cdot r_m \cdot \beta
$$

This is equation 35 of Johnson and Nier (1953), for a z value of 1 (symmetric
analyser where the object and image distances are equal) and multiplied by a
factor 2 to account for the extended geometry of the MIRA magnet in which the
pole faces are rotated with respect to the normal of the optic axis (Wollnik,
1983).

The velocity dispersion of the esa is given by (Johnson and Nier, eqn. 36):

$$
D_e = 2 \cdot r_e \cdot \beta
$$

Again this equation describes the dispersion of a symmetric esa in which the
object and image distances are equal.

Equating equations (5) and (6) we find for velocity focussing:

$$
r_e = 2 \cdot r_m
$$

The radius of the electrostatic analyser is two times that of the radius of the
extended geometry magnet. The MIRA magnet has a radius of 250 mm, thus the esa
radius will be 500 mm.

*(ii) Second-order geometry focusing*

Nier and Johnson (1953) give the second-order aberrations for a symmetric magnet
as:

$$
L_m = -r_m \cdot \alpha^2
$$

where *α* is the beam divergence. This is for a standard magnet where the pole
faces are oriented normal to the optic axis. In extended geometry instruments we find
(Brown *et al*., 1964):

$$
L_m = -4 \cdot r_m \cdot \alpha^2
$$

We can express equation (9) in terms of the esa radius using the relationship
between rm and re (equation (7) for a velocity focussing instrument with an
extended geometry magnet):

$$
L_m = -2 \cdot r_e \cdot \alpha^2
$$

For a symmetric esa the second-order geometry focusing is a function of the esa
sector angle and is given by (Johnson and Nier, eqn. 31):

$$
L_e = - \left[\frac{9}{12} \cdot 2 \cdot csc^2 \left(\frac{\phi_e}{\sqrt 2} - \frac{2}{12}\right)\right] \cdot r_e \cdot \alpha^2
$$

The solution to the simultaneous equations (10) and (11) gives the condition for
second-order geometric focusing. This is illustrated in figure 1 in which
*L*$$_m/r_m.α^2$$ and *L*$$_e/r_e.α^2$$ are plotted as a function of *Φ*, the
esa sector angle.

<img src="images/double_focusing_condition.jpg?raw=true"/>

A solution is found for an esa sector angle of 79.6°.

### Conclusion

The geometric conditions for double focusing are met using the MIRA magnet (250
mm, 120$$^\circ$$ extended geometry) and an esa with a sector angle of 79.6° and
a radius of 500 mm.

### References

Brown, K. L., Belbeoch, R., & Bounin, P. (1964). First- and Second-Order
Magnetic Optics Matrix Equations for the Midplane of Uniform-Field Wedge
Magnets. Review of Scientific Instruments, 35(4), 481–485.
http://doi.org/10.1063/1.1718851

Johnson, E. G., & Nier, A. O. (1953). Angular Aberrations in Sector Shaped
Electromagnetic Lenses for Focusing Beams of Charged Particles. Physical Review
A., 91(1), 10-17.

Wollnik, H. (1987). Optics of Charged Particles. Academic Press. 293pp
