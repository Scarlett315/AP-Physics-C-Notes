# 22.1 The Electric Field
- A charged particle sets up an electric field (vector) in the surrounding space. IF a second charged particle is located in that space, an electrostatic force acts on it due to the magnitude and direction of the field at its location.
- The electric field $\vec{E}$ at any point is defined in terms of the electrostatic force $\vec{F}_e$ that would be exerted on a positive test charge $q_0$ placed there: $$\vec{E} = \frac{\vec{F}}{q_0}$$
	- Measured in N/C
- Electric field lines help us visualize the direction and magnitude of electric fields.
	- The electric field vector at any point is tangent to the field line through that point
	- In a plane perp. to the field liens, the density of field lines in a region is proportional to the electric field there--> closer lines represent a stronger field
	- Originate on positive charges and terminate on negative charges
- We always represent an electric field with an arrow with its tail anchored on the point where the measurement is made

# 22.2 Electric Field due to a Charged Particle
- The magnitude of the electric field set up by a particle at a distance _r_ from the particle is $$E = \frac{1}{4\pi\varepsilon_0}\frac{|q|}{r^2}$$
- The electric field vectors set up by a pos. charged particle all point directly away from the particle, and v.v.
- If more than one charged particle sets up an elec. field at a point, the net elec. field is the vector sum of the individual electric fields (superposition)
# 22.3 Electric Field due to a Dipole
- An electric dipole consists of 2 particles with charges of equal mag. _q_ but opposite signs, separated by a small distance _d_. 
- The electric dipole moment $\vec{p}$ has magnitude _qd_ and points from the negative charge to the positive charge. (measured Coulomb-meter)
- The magnitude of the electric field set up by an electric dipole at a distant point on the dipole axis (which runs through both particles) can be written in terms of either the product _qd_ of the magnitude _p_ of the dipole moment e$$E = \frac{1}{2\pi \varepsilon_0}\frac{qd}{z^3}=\frac{1}{2\pi \varepsilon_0}\frac{p}{z^3}$$ where $z$ is the distance between the point and the center of the dipole
	- At distant points we can never find _q_ and _d_ separately by measuring the E field
- Because of the 1/z^3 dependence, the field magnitude of an electric dipole decreases more rapidly with distance than the field magnitude of either of the individual charges former the dipole (1/r^2)
	- From far away, a dipole looks like 2 particles that almost-- but not quite-- coincide, so they almost cancel each other
- Derivation: $$\begin{aligned} E = E_{(+)} - E_{(-)} &= \frac{1}{4\pi\varepsilon_0}\frac{q}{r^2_{(+)}} - \frac{1}{4\pi\varepsilon_0}\frac{q}{r^2_{(-)}} \\&= \frac{q}{4\pi\varepsilon_0(z-\frac{1}{2}d)^2} - \frac{q}{4\pi\varepsilon_0(z+\frac{1}{2}d)^2}  \\ & \text{Simplify and neglect d/2z  << 1}\\ E &= \frac{1}{2\pi\varepsilon_0}\frac{qd}{z^3}\end{aligned} $$

# 22.4 Electric Field due to a Line of Charge
- THe equation for the E field set up by a particle does not apply to an extended object with charge (continuous charge distribution)
- To find the E field of an extended object at point, we first consider the E field set up by a charge element _dq_ in the object, where the element is small enough for us to apply the equation for a particle. Then we sum, via integration, components of the electric fields $d\vec{E}$ from all the charge elements.
- Because the individual E fields have different magnitudes and point in different directions, we first see if symmetry allows us to cancel out any of the components of the fields, to simplify the integration
- Steps!
	1. Pick a charge element and write charge _dq_ in terms of given charge density & length/area
	2. Rewrite field equation for a particle in terms of new symbols _dE_ and _dq_, then replace _dq_ with Step 1
	3. Replace "illegal" variables with given ones
	4. If possible, eliminate sets of components via symmetry
	5. Set up and solve an integral for the remaining component
	6. Replace with total charge if applicable

---
### A Field Guide for Lines of Charge
![[Screenshot 2026-02-22 at 11.54.31 AM.png]]
# 22.5 Electric Field due to a Charged Disk
- On the central axis through a uniformly charged disk, $$E = \frac{\sigma}{2\pi\varepsilon_0}(1-\frac{z}{\sqrt{z^2+R^2}})$$ gives the electric field magnitude. Here _z_ is the distance along the axis from the center of the disk, R is the radius of the disk, and $\sigma$ is the surface charge density
- Allowing $R \to \infty$ while keeping _z_ finite gives $$E = \frac{\sigma}{2\varepsilon_0}$$, the E field produced by an infinite sheet of uniform charge located on one side of a nonconductor. Allowing $z \to \infty$ gives the same result, so the E field set up by the disk at points very close to the disk is the same as if the disk were inf. in extent

# 22.6 Point Charge in an Electric Field
- If a particle with charge _q_ is placed in an external electric field $\vec{E}$, an electrostatic force acts on the particle: $$\vec{F} = q\vec{E}$$
- If charge _q_ is positive, the force vector is in the same direction as the field vector. If charge _q_ is negative, the force vector is in the opposite direction (minus sign reverses force vector from field vector)
# 22.7 Dipole in an Electric Field
- The torque on an electric dipole of dipole moment $\vec{p}$ when placed in an external E field is given by a cross product: $$\vec{\tau} = \vec{p} \times \vec{E}$$
- A potential energy U is associated with the orientation of the dipole moment in the field, as given by a dot product $$U = -\vec{p} \cdot \vec{E}$$
	- Taking $\theta = 90$ as ref. zero-PE config.
	- Electric dipole acts like a pendulum-- lowest PE In equilibrium
- If the dipole orientation changes, the work done by the E field is $$W = -\Delta U$$. If the change in orientation is due to an external agent, the work done by the agent is $W_a = -W$. 
