# 24.1 Electric Potential
- The electric potential _V_ at a point _P_ in the E field of a charged object is $$V = \frac{-W_{\infty}}{q_0}=\frac{U}{q_0}$$ where $W_{\infty}$ is the work that would be done by the E force on a positive test charge $q_0$ were it brought from an infinite distance to _P_, and _U_ is the EPE that would then be stored in the test charge-object system
- If a particle with charge _q_ is placed at a point where the electric potential of a charged object is _V_, the EPE _U_ of the particle-object system is $$U=qV$$
- If the particle moves through a potential difference $\Delta V$, the change in EPE is $$\Delta U = q\Delta V = q(V_f-V_i)$$
- If a particle moves through a change $\Delta V$ in EP w/o an applied force acting on it, applying the conservation of mechanical energy gives the change in KE as $$\Delta KE = -q\Delta V$$
- If instead, an applied force acts on the particle doing $W_{app}$, the change in KE is $$\Delta KE = -q\Delta V + W_{app}$$
- In the special case when $\Delta KE = 0$, the work of an applied force involves only the motion of the particle through a potential difference: $$W_{app} = q\Delta V$$

# 24.2 Equipotential Surfaces & the Electric Field
- The points on an equipotential surface all have the same electric potential. The work done on a test charge in moving it from one such surface to another is independent of the locations of the initial and final points on these surfaces and of the path that joins the points. The electric field is always directed perpendicularly to corresponding equipotential surfaces. 
- The electric potential difference between 2 points _i_ and _f_ is: $$V_f - V_i = -\int^f_i\vec{E}\cdot d\vec{s}$$where the integral is taken over any path connecting the points. If the integration is difficult along any particular path, we can hoose a different path along which the integration might be easier. 
- If we choose $V_i = 0$, we have, for the potential at a particular point$$V = -\int^f_i\vec{E}\cdot d\vec{s}$$
- In a uniform field of magnitude _E_, the change in potential from a higher equipotential surface to a lower one, separated by distance $\Delta x$,is $$\Delta V = -E\Delta x$$
- The electric field vector points from higher potential toward lower potential
# 24.3 Potential Due to a Charged Particle
- The electric potential due to a single charged particle at a distance _r_ from that charged particle is $$V=\frac{1}{4\pi \varepsilon_0}\frac{q}{r}$$where _V_ has the same sign as _q_. 
	- i.e. a positively charged particle produces a positive V and v.v.
- The potential due to a collection of charged particles is $$V=\sum^n_{i=1}V_i=\frac{1}{4\pi \varepsilon_0}\sum^n_{i=1}\frac{q_i}{r_i}$$Thus, the potential is the algebraic sum of the individual potentials, with no consideration of directions
# 24.4 Potential Due to an Electric Dipole
- At a distance _r_ from an electric pole with dipole moment magnitude _p=qd_, the electric potential of the dipole is $$V=\frac{1}{4\pi\varepsilon_0}\frac{p\cos\theta}{r^2}$$for $r\gg d$; the angle $\theta$ lies between the dipole moment vector and a line extending from the dipole midpoint to the point of measurement

# 24.5 Potential Due to a Continuous Charge Distribution
- For a continuous distribution of charge (over an extended object), the potential is found by (1) dividing the distribution into charge elements _dq_ that can be treated as particles and then (2) summing the potential due to each element by integrating over the full distribution $$V=\frac{1}{4\pi\varepsilon_0}\int\frac{dq}{r}$$
- In order to carry out the integration, _dq_ is replaced with the product of either a linear charge density $\lambda$ and a length element (e.g. _dx_) or a surface charge density $\sigma$ and area element (e.g. _dx dy_)
- In some cases where the charge is symmetrically distributed, a 2-D integration can be reduced to a 1-D integration
# 24.6 Calculating Field from Potential
- The component of $\vec{E}$ in any direction is the negative of the rate at which the potential changes with distance in that direction: $$E_s = -\frac{\partial V}{\partial S}$$
- The x, y, and z components of $\vec{E}$ may be found from: $$E_x = -\frac{\partial V}{\partial x} \qquad E_y = -\frac{\partial V}{\partial y}\qquad E_z = -\frac{\partial V}{\partial z}$$
- When $\vec{E}$ is uniform, all this reduces to $$E = -\frac{\Delta V}{\Delta s}$$ where _s_ is perp. to the equipotential surfaces.
- The electric field is zero parallel to an equipotential surface. 
# 24.7 Electric Potential Energy of a System of Charged Particles
- The EPE of a system of charged particles is equal to the work needed to assemble the system with the particles initially at rest and infinitely distant from each other. For two particles at separation _r_, $$U=W=\frac{1}{4\pi\varepsilon_0}\frac{q_1q_2}{r}$$
- For an assembly of charged particles, find the PE of every possible pair and then sum the results
# 24.8 Potential of a Charged Isolated Conductor
- An excess charge placed on a conductor will, in the equilibrium state, be located entirely on the outer surface of the conductor. 
- The entire conductor, including interior points, is at a uniform potential. This is true even if the conductor has an internal cavity and even if that cavity contains a net charge
- If an isolated conductor is placed in an external E field, then at every internal point the E field due to the conduction electrons cancels the external electric field that otherwise would have been there. 
- Also, the net E field at every point on the surface is perp. to the surface