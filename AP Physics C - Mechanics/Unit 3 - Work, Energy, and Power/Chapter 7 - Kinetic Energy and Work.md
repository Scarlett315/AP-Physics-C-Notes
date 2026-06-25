# 7.1 Kinetic Energy
- **Energy**: Scalar quality that is associated with the state (or condition) or one or more objects
	- Energy is conserved; it can be transformed and transferred, but the total amount is always the same
- Energy is measured in **Joules (J)**, where $$1 \text{ joule} = 1\frac{\text{ kg}\cdot m^2}{s^2}=1\text{N}\cdot\text{m}$$
- The kinetic energy _K_ associated with the motion of a particle of mass _m_ and speed _v_ is $$K=\frac{1}{2}mv^2$$
# 7.2 Work and Kinetic Energy
- **Work _W_**:  energy transferred to/from an object via a force acting on the object. Energy transferred to the object is positive work, and from the object, negative work.
	- Same units as energy (J) and is a scalar quantity
	- A force does positive work when it has a vector component in the same direction as the displacement, and it does negative work when it has a vector component in the opp. direction. It does zero work when it has no such vector component. 
- The work done on a article by a constant force $\vec{F}$ during displacement $\vec{d}$ is $$W = Fd\cos\phi =\vec{F} \cdot \vec{d}$$
	- in which $\phi$ is the constant angle between the directions of $\vec{F}$ and $\vec{d}$
- Only the component of $\vec{F}$ that is along the displacement can do work on the object.
- When two or more forces act on a object, their net work is the sum of the individual works done by the forces, which is also equal to the work that would be done on the object by the net force $\vec{F}_{net}$ of those forces.
- Two ways to find **Net Work**: 
	1. Find the work done by each force and then sum the works
	2. Find the net force of those forces, then use the equation to solve for work
- (**Work-Kinetic Energy Theorem**) For a particle, a change $\Delta K$ in the kinetic energy equals the net work W done on the particle: $$\Delta K = K_f - K_i = W$$
	- in which $K_i$ is the initial KE of the particle and $K_f$ is the KE after the work is done. 
	- Rearranging the equation gives $K_f = K_i + W$. 
	- This says that $$\binom {\text{KE after}} {\text{net work is done}} = \binom {\text{KE before}} {\text{net work}} + \binom {\text{the net}} {\text{work done}}$$
- Cautions 
	- Force must be a constant force
	- The object must be particle-like (rigid)


# 7.3 Work Done by the Gravitational Force
- The work $W_g$ done by the grav. force $\vec{F}_g$ on a particle-like object of mass _m_ as the object moves through a displacement $\vec{d}$ is given by : $$W_g = mgd\cos \phi$$
	- in which $\phi$ is the angle between $\vec{F}_g$ and $\vec{d}$ 
	- For a rising object, gravity does negative work & v.v.
- The work $W_a$ done by an appl. force as a particle-like object is either lifted/lowered is related to the work $W_g$ done by the gravitational force and the change $\Delta K$ in the object's KE by: $$\Delta K = K_f - K_i = W_a + W_g$$
	- If $K_f = K_i$, the equation reduces to $$W_a = -W_g\qquad\text{or}\qquad W_a=-mgd\cos \phi $$which tells us that the applied force transfers as much energy to the object as the gravitational force transfers from it.
- Independent from the magnitude of the force used; if an object is stationary before and after lifting it, the work done by it is still $-Wg$ regardless of how the force varies during the lift
# 7.4 Work Done By a Spring Force
- A **spring force** acts to restore the relaxed state (so it is sometimes called the restoring force)
- The force $\vec{F}_s$ done by a spring is $$\vec{F}_s = -k\vec{d} \qquad \text{(Hooke's Law)}$$
	- $\vec{d}$: displacement of the spring's free end from its position when the spring is in its relaxed state (neither compressed nor extended)
	- _k_: spring constant (measure of spring's stiffness); Newton/meter
	- If it's just in the x-axis $F_x = -kx$ works
- A spring force is a variable force b/c it varies with the displacement of the spring's free end
- If an object is attached to the spring's free end, the work $W_s$ done on the object by the spring force when the object is moved from an initial position $x_i$ to a final position $x_f$ is $$W_s=\frac{1}{2}x^2_i-\frac{1}{2}x^2_f$$If $x_i = 0$ & $x_f = x$, $$W_s=-\frac{1}{2}x^2$$
	- **Derivation**:
		- Divide the distance between $x_i$ and $x_f$ into many segments of length $\Delta x$. As the block moves through a segment, the spring force hardly varies because the segment is so short that x hardly varies, so we can approximate the force magnitude as being constant within the segment; we call these magnitudes $F_{x1}, F_{x2}$, etc. 
		- To find the total work done by the spring, we sum all of the works done in each individual segment: $$W_s=\sum -F_{xj}\Delta x$$ where j labels the segments. As $\Delta x$ approaches zero, $$W_s = \int^{x_f}_{x_i}-kx \ dx=-\frac{1}{2}k \ (x^2)|^{x_f}_{x_i}=-\frac{1}{2}k (x_f^2-x_i^2)$$ $$\boxed{W_s=\frac{1}{2}x^2_i-\frac{1}{2}x^2_f}$$
	- $W_s$ is positive if the block ends up closer to the relaxed position (x=0) than it was initially; neg. if it ends up farther away, and zero if the block ends up at the same dist. from x=0
- If we apply a force, $$\Delta K = W_a + W_s$$ and if the block is stationary before and after the displacement, $\Delta K = 0$ and $$W_a = - W_s$$
- If a block that is attached to a spring is stationary before and after a displacement, the work done on it by the applied force displacing it is the negative of the work done on it by the spring force. 
# 7.5 Work Done by a General Variable Force
- When the force on a particle-like object depends on the position of the object, the work done must be found by integrating the force. If we assume that $F_x$ may depend on _x_ but not on _y_ or _z_, and etc. for the other dimensions, $$W=\int^{x_f}_{x_i}F_xdx+\int^{y_f}_{y_i}F_ydy+\int^{z_f}_{z_i}F_zdz$$
- derivation was pretty much the same as spring force but more general

# 7.6 Power
- **Power**: the rate at which a force does work on an object. 
	- Measured in **Watts** = Joules / seconds
	- If a force does work _W_ over a time interval $\Delta t$, the average power due to the force over that time interval is $$P_{avg} = \frac{W}{\Delta t}$$
	- Instantaneous power is the instantaneous rate of doing work: $$P=\frac{dW}{dt}$$
- For a force $\vec{F}$ at an angle $\phi$ to the direction of travel of the instantaneous velocity $\vec{v}$, the instantaneous power is $$P=Fv\cos\phi = F\cdot v$$
- Work can be expressed as a power multiplied by time
	- Kilowatt-Hour: $\text {1 kilowatt-hour} = 1kW \cdot h = (10^3W)(3600s)=3.60\times 10^6 J = 3.60MJ$
