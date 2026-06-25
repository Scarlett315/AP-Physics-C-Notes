# 23.1 Electric Flux
- The electric flux $\Phi$ through a surface is the amt. of E field that pierces the surface
- The area vector $d\vec{A}$ for an area element (patch element) on a surface is a vector that is perp. to the element and has a magnitude equal to the area _dA_ of the element. 
- The electric flux $d\Phi$ through a patch element with area vector $d\vec{A}$ is given by a dot product $$d\Phi = \vec{E} \cdot d\vec{A}$$
- The total flux through a surface is given by $$\Phi = \int \vec{E} \cdot d\vec{A}$$ where the integration is carried out over the surface.
	- Inward piercing field: negative flux
	- Outward piercing field: positive flux
	- Skimming field: zero flux
	- Measured in Nm^2 /C
- The net flux through a closed surface (used in Gauss' Law) is given by $$\Phi = \oint\vec{E}\cdot d\vec{A}$$ where the integration is carried out over the entire surface
- Gauss' Law relates the E field at points on a closed Gaussian surface to the net charge enclosed by that surface

# 23.2 Gauss' Law
- Gauss' Law relates the net flux $\Phi$ penetrating a closed surface to the net charge $q_{enc}$ enclosed by the surface: $$\varepsilon_0 \Phi = q_{\text{enc}}$$
- Gauss' Law can also be written in terms of the E field piercing the enclosing Gaussian surface: $$\varepsilon_0\oint\vec{E}\cdot d\vec{A} = q_\text{enc}$$
	- Holds only when the net charge is located in a vacuum (or air, for most practical purposes)
	- $q_{enc}$ is the algebraic sum of all the enclosed positive and negative charges
		- pos. --> net flux outward & v.v. (keep sign in equation)
		- Exact form and location of charges inside are of no concern (only things that matter are the magnitude and sign of the net enclosed charge)
	- $\vec{E}$ is the E field resulting from _all_ charges, both those inside and outside-- E field due to a charge outside contributes zero net flux through the surface
# 23.3 A Charged Isolated Conductor
- An excess charge on an isolated conductor is located entirely on the outer surface of the conductor
	- Intuitively, the excess charges would repel each other
	- This is true for a conductor with a cavity in it
	- Justification using Gauss' Law-- draw a Gaussian surface just inside the conductor surface, net E field must be 0 or conductor would have current
- Unless the conductor is spherical, charge does not distribute itself uniformly
- The internal E field of a charged, isolated conductor is 0, and the external field (at nearby points) is perpendicular to the surface and has a magnitude that depends on the surface charge density $\sigma$: $$E = \frac{\sigma}{\varepsilon_0}$$
# 23.4 Applying Gauss' Law: Cylindrical Symmetry
- The E field at a point near an infinite line of charge (or charged rod) with uniform linear charge density $\lambda$ is perp. to the line and has magnitude $$E = \frac{\lambda}{2\pi\varepsilon_0 r}$$ where r is the perp. distance from the line to the point

# 23.5 Applying Gauss' Law: Planar Symmetry
- The E field due to an infinite nonconducting sheet with uniform surface charge density $\sigma$ is perp. to the plane of the sheet and has magnitude $$E = \frac{\sigma}{2 \varepsilon_0}$$
- The external E field just outside the surface of an isolated charged conductor with surface charge density $\sigma$ is perp. to the surface and has magnitude $$E = \frac{\sigma}{\varepsilon_0}$$
# 23.6 Applying Gauss' Law: Spherical Symmetry
- Outside a spherical shell of uniform charge _q_, the E field due to the shell is radial and has magnitude $$E = \frac{1}{4\pi\varepsilon_0}\frac{q}{r^2}$$ where _r_ is the distance to the point of measurement from the center of the shell. The field is the same as though all of the charge is concentrated as a particle at the center of the shell.
- Inside the shell, the field due to the shell is 0.
- Inside a sphere with uniform volume charge density, the field is radial and has magnitude $$E = \frac{1}{4\pi\varepsilon_0}\frac{q}{R^3}r$$ where _q_ is the total charge, _R_ is the sphere's radius, and _r_ is the radial distance from the center of the sphere to the point of measurement