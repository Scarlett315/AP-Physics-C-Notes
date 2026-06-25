# 25.1 Capacitance
-  A capacitor consists of two isolated conductors (plates) with charges +q and -q. Its capacitance _C_ is $$q = CV$$where V is the potential difference between the places.
	- _q_ is the absolute value of the charge on one plate (net charge = 0)
	- The greater the capacitance, the more charge is required
- When a circuit with a battery, open switch, and uncharged capacitor is completed by closing the switch, conduction electrons shift, leaving the capacitor plates with opposite charges
	1. Initial potential difference is 0
	2. e- are driven through the wires by an electric field which the battery sets up in the wires,
		1. driving electrons from the positive plate of the capacitor to the positive terminal of the battery and the pos. plate becomes positively charged
		2. driving electrons from the negative terminal of the battery to the negative plate and the neg. plate becomes neg. charged
	3. Potential difference increases until it equals the potential difference between the terminals of the battery (fully charged capacitor)
	4. There is no longer an electric field in the wire between them

# 25.2 Calculating the Capacitance
- We generally determine the capacitance of a particular capacitor configuration by
	1. Assuming a charge _q_ to have been placed on the plates
	2. Finding the $\vec{E}$ due to this charge (Gauss' Law $\varepsilon_0\oint\vec{E}\cdot d\vec{A}=q$) 
		- Always draw Gaussian surface so that it completely encloses charge on positive plate, E will have a uniform magnitude and E & dA will be parallel, so that it reduces to $q=\varepsilon_0EA$ 
	3. Evaluating the potential difference between the plates
		- Choosing a path that follows an E field line, from the negative to the positive plate, E and ds will have opposite directions & dot product = -Eds
		- $\Delta V=\int^+_-E \ ds$ 
	4. Calculating _C_ from _q = CV_ 
- Some results:
	- Parallel-Plate Capacitor $$C = \frac{\varepsilon_0A}{d}$$
	- Cylindrical Capacitor of length _L_ and radii _a_ and _b.  $$C=2\pi\varepsilon_0\frac{L}{\ln(\frac{b}{a})}$$
	- Spherical Capacitor with concentric spherical plates of radii _a_ and _b_ $$C=4\pi\varepsilon_0\frac{ab}{b-a}$$
	- Isolated sphere of radius _R_ $$C=4\pi\varepsilon_0R$$
# 25.3 Capacitors in Parallel and in Series
- Capacitors in parallel add up; capacitors in series $\frac{1}{C_{eq}} = \sum^n_{j=1}\frac{1}{C_j}$ 
- Capacitors in parallel can be replaced with an equivalent capacitor that has the same total charge _q_ and potential difference _V_ as the actual capacitors
- When a potential difference _V_ is applied across several capacitors connected in series, the capacitors have identical charge _q_. The sum of the potential differences across the capacitors is equal to the applied potential difference. 
	- Capacitors that are connected in series can be replaced with an equivalent capacitor that has the same charge _q_ and _total_ potential difference _V_ as the actual series capacitors

# 25.4 Energy Stored in an Electric Field
- The EPE _U_ of a charged capacitor $$U=\frac{q^2}{2C} = \frac{1}{2}CV^2$$is equal to the work required to charge the capacitor. This energy can be associated with the capacitor's E field. 
- Every E field, in a capacitor or from any other source, has an associated stored energy. In a vacuum, the energy density _u_ (PE/unit volume) in a field of mag. E is $$u=\frac{1}{2}\varepsilon_0E^2$$
# 25.5 Capacitor with a Dielectric
- If the space between the plates of a capacitor is completely filled with a dielectric material, the capacitance _C_ in vacuum is multiplied by the material's dielectric constant $\kappa$, which is a number greater than 1.
- In a region that is completely filled by a dielectric, all electrostatic equations containing the permittivity constant must be modified by replacing $\varepsilon_0$ with $\kappa \varepsilon_0$ 
- When a dielectric material is placed in an external electric field, it develops an internal E field that is oriented opposite the external field ,thus reducing the magnitude of the electric field inside the material. 
- When a dielectric material is placed in a capacitor with a fixed amount of charge on the surface, the net E field between the plates is decreased

# 25.6 Dielectrics and Gauss' Law
- Inserting a dielectric into a capacitor causes induced charge to appear on the faces of he dielectric and weakens the E field between the plates. 
- The induced charge is less than the free charge on the plates.
- When a dielectric is present, Gauss' Law may be generalized to $$\varepsilon_0\oint\kappa\vec{E}\cdot d\vec{A}=q$$where _q_ is the free charge. Any induced surface charge is accounted for by including $\kappa$ in the integral.