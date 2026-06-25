# 9.1 Center of Mass
- The **center of mass** of a system of particles is the point that moves as though (1) all of the system's mass were concentrated there and (2) all external forces were applied there
- The center of mass of a system of _n_ particles is defined to be the point whose coordinates are given by $$x_{com}=\frac{1}{M}\sum^n_{i=1}m_ix_i, \ \ y_{com}=\frac{1}{M}\sum^n_{i=1}m_iy_i \ \ z_{com}=\frac{1}{M}\sum^n_{i=1}m_iz_i$$ or $$\vec{r}_{com}=\frac{1}{M}\sum^n_{i=1}m_i\vec{r}_i$$ where _M_ is the total mass of the system
- An ordinary object can be treated as a continuous distribution of matter, i.e. an integral: $$x_{com}=\frac{1}{M}\int x \ dm$$ & etc. for the other dimensions
	- With density $\rho = \frac{dm}{dV}=\frac{M}{V}$ $$x_{com}=\frac{M}{V}\int x \ dV$$
- If an object has a point/line/plane of symmetry you can bypass these integrals b/c the COM lies at that point, on that line, or in that plane
	- e.g. sphere --> center, cone --> on the axis
- The center of mass of an object need not lie within the object
# 9.2 Newton's Second Law for a Series of Particles
- The motion of the COM of any system of particles is governed by Newton's second law for a system of particles, which is $$\vec{F}_{net} = M\vec{a}_{com}$$
	1. $\vec{F}_{net}$ is the net force of all the external forces acting on the system, not forces on one part of the system from another part (internal forces)
	2. _M_ is the total mass of the system (assume that no mass enters/leaves, M remains constant-- closed system)
	3. $\vec{a}_{com}$ is the acceleration of the system's center of mass, not of any other point in the system.
- When you roll a cue ball at a second billiard ball that is at rest, it is the center of mass of the two-ball system that moves forward. It remains at the same velocity after the collision because the collision causes internal forces. (F = Ma --> a = 0 --> v remains the same)
# 9.3 Linear Momentum
- For a single particle, we define a quantity $\vec{p}$ called its **linear momentum** as $$\vec{p} = m\vec{v}$$, which is a vector quantity that has the same direction as the particle's velocity.
	- Units: $\frac{kg\cdot m}{s}$
- We can write Newton's second law in terms of this momentum: $$\vec{F}_{net} = \frac{d\vec{p}}{dt}$$
	- i.e. The time rate of change of the momentum of a particle is equal to the net force acting on the particle and is in the direction of that force. 
	- $\vec{F}_{net} = \frac{dp}{dt}=\frac{d}{dt}(mv)=m\frac{dv}{dt}=ma$
- For a system of particles these relations become $$\vec{P} = M\vec{v}_{com} \quad \text{and} \quad \vec{F}_{net} = \frac{d\vec{P}}{dt}$$ where P is the system's total linear momentum $\vec{P} = \vec{p}_1 + \vec{p}_2+...+\vec{p}_n$
- Linear momentum can be changed only by a net external force. If there is no net external force, $\vec{p}$ / $\vec{P}$ _cannot_ change. --> this is a powerful tool for solving problems
# 9.4 Collision and Impulse
- In a collision or crash, the external force on the body is brief, has large magnitude, and suddenly change the body's momentum. 
- **Impulse**: A measure of the magnitude and duration of the collision force
	- Applying Newton's second law in momentum form to a particle-like body involved in a collision leads to the impulse-linear momentum theorem: $$\vec{p}_f - \vec{p}_i = \Delta \vec{p} = \vec{J}$$ where $\vec{p}_f - \vec{p}_i = \Delta \vec{p}$ is the change in the body's linear momentum, and $\vec{J}$ is the impulse due to the force $\vec{F}(t)$ exerted on the body by the other body in the collision: $$\vec{J} = \int^{t_f}_{t_i} \vec{F}(t) \ dt$$
- If $F_{avg}$ is the average magnitude of $\vec{F}(t)$ during the collision and $\Delta t$ is the duration of the collision, then for one-dimensional motion $$J = F_{avg} \ \Delta t$$
- When a steady stream of bodies, each with mass _m_ and speed _v_, collides with a body whose position is fixed, the average force on the fixed body is $$F_{avg} = -\frac{n}{\Delta t} \Delta p = -\frac{n}{\Delta t}m\Delta v$$where $n/\Delta t$ is the rate at which the bodies collide with the fixed body, and $\Delta v$ is the change in velocity of each colliding body. This average force can also be written as $F_{avg} = -\frac{\Delta m}{\Delta t} \Delta v$, where $\Delta m / \Delta t$ is the rate at which mass collides with the fixed body. The change in velocity is $\Delta v = -v$ if the bodies stop upon impact and $\Delta v = -2v$ if they bounce directly backward with no change in their speed. 
# 9.5 Conservation of Linear Momentum
- If a system is closed and isolated so that no net external force acts on it, then the linear momentum $\vec{P}$ must be constant even if there are internal changes
- This **conservation of linear momentum** can also be written in terms of the system's initial momentum and its momentum at some later instant: $$\vec{P}_i = \vec{P}_f$$
	- If there is no net force & no impulse, $\frac{dP}{dt} = 0$ and so $\vec{P} = \text{constant}$ 
	- $\large \binom{\text{total linear momentum}}{\text{at some initial time } t_i} = \binom{\text{total linear momentum}}{\text{at some later time } t_f}$
	- \*\*do not confuse with energy-- in many cases momentum is conserved but energy is not
- Momentum can be conserved in one axis, e.g. if you throw something the only external force is $F_g$ downward, so horizontal component of momentum is constant

# 9.6 Momentum and Kinetic Energy in Collisions
- Elastic Collision: KE is conserved
- In an inelastic collision of 2 bodies, the KE of the 2-body system is not conserved. If the system is closed and isolated, the total linear momentum of the system must be conserved: $$\vec{p}_{1i} + \vec{p}_{2i} = \vec{p}_{1f} + \vec{p}_{2f}$$
- If the motion of the bodies is along a single axis, the collision is one-dimensional: $$m_{1i}v_{1i} + m_{2i}v_{2i}=m_{1f}v_{1f}+m_{2f}v_{2f}$$
- If the bodies stick together, the collision is completely inelastic and the bodies have the same final velocity _V_ (b/c they are stuck together); this is the most lost in KE
- The COM of a closed, isolated system of two colliding bodies is not affected by a collision. In particular, the velocity $\vec{v}_{com}$ of the center of mass cannot be changed by the collision.
# 9.7 Elastic Collisions in One Dimension
- An **elastic collision** is a special type of collision in which the KE of a system of colliding bodies is conserved. 
	- If the system is closed and isolated, its linear momentum is also conserved. 
	- For a one-dimensional collision in which body 2 is a target and body 1 is an incoming projectile, conservation of KE and linear momentum yield the following expressions for the velocities immediately after the collision: $$v_{1f} = \frac{m_1 - m_2}{m_1 + m_2}v_{1i} + \frac{2m_2}{m_1 + m_2} \quad \text{and} \quad v_{2f} =  \frac{2m_1}{m_1 + m_2}v_{1i} + \frac{m_2 - m_1}{m_1 + m_2}v_{2i}$$
- $m_1$ moves forward if $m_1 > m_2$ but rebounds if $m_1 < m_2$
	1. Equal Masses: if $m_1 = m_2$, the equations reduce to $v_{1f} = 0$ and $v_{2f} = v_{1i}$ ; after a head-on collision with two masses, body 1 stops dead in its tracks and body 2 takes off with the initial speed of body 1, i.e. they exchange velocities (even if body 2 is not initially at rest)
	2. A Massive Target: if $m_2 \gg m_1$, $v_{1f} \approx -v_{1i}$ and $v_{2f} \approx \frac{2m_1}{m_2}v_{1i}$; body 1 simply bounces back along its incoming path with essentially unchanged speed & body 2 moves forward at a low speed
	3. A Massive Projectile: if $m_1 \gg m_2$, $v_{1f} \approx v_{1i}$ and $v_{2f} \approx 2v_{1i}$; body 1 simply keeps on going, barely slowed by the collision while body 2 charges ahead at twice the speed of body 1
# 9.8 Collisions in Two Dimensions
- If two bodies collide and their motion is not along a single axis (the collision is not head-on), the collision is two-dimensional. If the two-body system is closed and isolated, the law of conservation of momentum applies to the collision: $$\vec{P}_{1i} + \vec{P}_{2i} = \vec{P}_{1f} + \vec{P}_{2f}$$
- In component form, the law gives two equation that describe the collision, one for each dimension. If the collision is also elastic, $$K_{1i} + K_{2i} = K_{1f} + K_{2f}$$
# 9.9 Systems With Varying Mass: A Rocket
- In the absence of external forces a rocket accelerates at an instantaneous rate given by $$Rv_{rel} = Ma \quad \text{(first rocket equation)}$$ in which _M_ is the rocket's instantaneous mass (including unexpended fuel), _R_ is the fuel consumption rate, and $v_{rel}$ is the fuel's exhaust speed relative to the rocket. The term $Rv_{rel}$ is the thrust of the rocket engine. 
- For a rocket with constant _R_ and $v_{rel}$, whose speed changes from $v_i$ to $v_f$ when its mass changes from $M_i$ to $M_f$, $$v_f - v_i = v_{rel}\ln\frac{Mi}{M_f} \quad \text{(second rocket equation)}$$