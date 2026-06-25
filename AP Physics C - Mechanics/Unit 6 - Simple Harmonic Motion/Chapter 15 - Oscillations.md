# 15.1 Simple Harmonic Motion
- Hallmarks
	1. The particle's acceleration is always opp. its displacement
	2. The two quantities are always related by a constant
		- For an equation in this form, you can immediately identify the frequency as being the square root of the constants in front of the displacement
$$a = -\omega^2 x(t)$$

- The frequency _f_ of periodic, or oscillatory, motion is the # of oscillations/second. In the SI system, it is measured in hertz $1 \text{Hz} = s^{-1}$ 
- The period _T_ is the time required for one complete oscillation, or cycle. It is related to the frequency by T = 1/f. 
- In SHM, the displacement of a particle from its equilibrium position is described by $$x=x_m\cos(\omega t + \phi)$$in which $x_m$ is the amplitude of the displacement, $\omega t + \phi$ is the phase of the motion, and $\phi$ is the phase constant. 
- The angular freq. is related to the period and freq. of the motion by $\omega = 2\pi/T = 2\pi f$ 
- Differentiating x(t) leads to equations for the particle's SHM velocity and accel. as functions of time $$\begin{aligned} v &=-\omega x_m \sin(\omega t + \phi) \\ a  &= -\omega^2 x_m \cos(\omega t + \phi) \end{aligned}$$
	- In the velocity fn. the positive quantity $\omega x_m$ is the velocity amplitude $v_m$. In the acceleration function, pos. quantity $\omega^2x_m$ is the accel. amplitude $a_m$. 
- A particle with mass _m_ that move under the influence of a Hooke's law restoring force given by F = -kx is a linear simple harmonic oscillator with $$\begin{aligned} \omega &= \sqrt{\frac{k}{m}} \\ T &= 2\pi \sqrt{\frac{m}{k}} \end{aligned}$$
# 15.2 Energy in SHM
- A particle in SHM has $K = \frac{1}{2}mv^2$ and $U=\frac{1}{2}kx^2$. If no friction is present, E = K + U remains constant even though K and U change

# 15.3 An Angular Simple Harmonic Oscillator
- A torsion pendulum consists of an object suspended on a wire. When the wire is twisted & then released, the object oscillates in angular SHM with a period given by $$T = 2\pi\sqrt{\frac{I}{\kappa}}$$where _I_ is the rotational inertia of the object about the axis of rotation and $\kappa$ is the torsion constant of the wire (depends on length, diameter, material). 

# 15.4 Pendulums, Circular Motion
- A simple pendulum consists of a rod of negligible mass that pivots about its upper end, with a particle (the bob) attached at its lower end. If the rod swings through only small angles, its motion is approximately SHM with a period $$T = 2\pi\sqrt{\frac{I}{mgL}}$$where _I_ is the particle's rotational inertia about the pivot, _m_ is the particle's mass, and _L_ is the rod's length.
- A physical pendulum has a more complicated distribution of mass. For small angles of swinging, its motion is SHM with a period given by $$T = 2\pi\sqrt{\frac{I}{mgh}}$$ where _h_ is the distance between the pivot and the pendulum's COM
	- (same except the moment arm is not the length of the string-- from pivot to object's COM)
	- You can measure the free-fall accel. _g_ using a physical pendulum by measuring _L_ and _T_ 
- SHM corresponds to the projection of UCM onto a diameter of the circle
# 15.5 Damped SHM
- THe mech. energy in a real oscillating system decreasues during the oscillations because external forces, such as drag force, inhibit the oscillations and transfer mech. energy to thermal energy. The real oscillator and its motion are said to be damed.
- If the damping force is given by $\vec{F}_d = -b\vec{v}$ where _v_ is the vel. of the oscillator and _b_ is a damping constant, then the displacement of the oscillator is given by $$x(t)=x_me^{-bt/2m}\cos(\omega't+\phi)$$where $\omega'$, the angular freq. of the damped oscillator, is $$w'=\sqrt{\frac{k}{m}-\frac{b^2}{4m^2}}$$
- If the damping constant is small ($b \ll \sqrt{km}$), then $\omega'\approx \omega$, where $\omega$ is the ang. freq. of the undamped oscillator. For small _b_, the mech. energy _E_ of the oscillator is given by  $$E(t) \approx \frac{1}{2}kx_m^2e^{-bt/m}$$

# 15.6 Forced Oscillations and Resonance
- If an external driving force w/ angular freq. $\omega_d$ acts on an oscillating system with natural angular frequency $omega$, the system oscillates with angular frequency $\omega_d$. 
- The velocity amplitude $v_m$ of the system is greatest when $\omega_d = \omega$, a condition called resonance. The amplitude of the system is approx. greatest under the same condition