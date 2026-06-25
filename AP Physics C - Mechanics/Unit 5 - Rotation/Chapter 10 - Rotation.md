

# 10.1 Rotational Variables
- To describe the rotation of a rigid body about a fixed axis (rotation axis), we assume a reference line is fixed in the body perpendicular to that axis and rotating with the body. We measure the angular position $\theta$ of this line relative to a fixed direction. When $\theta$ is measured in radians, $\theta = \frac{s}{r}$ where _s_ is the arc length of a circular path of radius _r_ and angle $\theta$. 
- A body that rotates about a rotation axis, changing its angular position from $\theta_1$ to $\theta_2$, undergoes an angular displacement $$\Delta \theta = \theta_2 - \theta_1$$ where $\Delta \theta$ is pos. for counterclockwise rotation & v.v.
- If a body rotates through an angular displacement $\Delta \theta$ in a time interval $\Delta t$, its average angular velocity $\omega_{avg}$ is $$\omega_{\text{avg}} = \frac{\Delta \theta}{\Delta t}$$. The instantaneous angular velocity is $$\omega = \frac{d\theta}{dt}$$
	- Both are vectors, with directions given by a right-hand rule. They are pos. for counterclockwise rotation and neg. for clockwise rotation. The magnitude of the body's angular velocity is the angular speed. 
- The average angular acceleration $\alpha_{avg}$ is $$\alpha_{avg} = \frac{\Delta \omega}{\Delta t}$$ & the instantaneous angular accel. is $$\alpha = \frac{d \omega}{dt}$$
	- Both are vectors
- Angular accel. and vel. vectors go through the axis of rotation & direction is determined by RHR (curl fingers in direction of rotation)
- Angular disp. cannot be represented by a vector (fails superposition)

# 10.2 Rotation with Constant Angular Acceleration
- Constant angular accel. is an important special cases of rotational motion. The appropriate kinematic equations are:  $$\begin{aligned} \omega&=\omega_0 + \alpha t \\ \theta -\theta_0 &= \omega_0t + \frac{1}{1}\alpha t^2 \\ \omega^2 &= \omega_0^2 + 2\alpha(\theta-\theta_0)\\ \text{etc...}\end{aligned}$$

# 10.3 Relating the Linear and Angular Variables
- everything in radians
- A point in a rigid rotating body at a perpendicular distance _r_ from the rotation axis, moves in a circle with radius _r_. If the body rotates through an angle $\theta$, the point moves along an arc with length _s_ given by $$s = \theta r$$
- The linear velocity $\vec{v}$ of the point is tangent to the circle, the point's linear speed is given by $$v = \omega r$$
- The linear accel. $\vec{a}$ of the point has both tangental and radial components. The tangental component is $$a_T = \alpha r$$. The radial component is $$a_r = \frac{v^2}{r} = \omega^2r$$
- If the point moves in uniform circular motion, the period _T_ of the motion for the point and the body is $$T = \frac{2\pi r}{v} = \frac{2 \pi}{w}$$

# 10.4 Kinetic Energy of Rotation
- The kinetic energy _K_ of a rigid body rotating about a fixed axis is given by $$K = \frac{1}{2}I \omega^2$$ in which _I_ is the rotational inertia (a.k.a. moment of inertia) of the body, defined as $$I = \sum m_i r_i^2$$ for a system of discrete particles. 
	- _I_ is always defined with respect to an axis
	- Measured in kilogram-square-meters kgm\^2 
	- Not only mass but also how that mass is distributed
- If we have a few particles and a specified rotation axis, we find $mr^2$ for each particle and then add the results to get _I_. If we want the total rotational KE, we substitute _I_ into the KE equation.

# 10.5 Calculating the Rotational Inertia
- _I_ is the rotational inertia of the body, defined as $$I = \sum m_i r_i^2$$ for a system of discrete particles and $$I = \int r^2 dm$$ for a body with continuously distributed mass. The _r_ and $r_i$ in these expresses represent the $\perp$ distance from the axis of rotation to each mass element in the body, and the integration is carried out over the entire body so as to include every mass element. 
- The parallel-axis theorem relates the rotational inertia _I_ of a body about any axis to that of the same body about a parallel axis through the center of mass: $$I = I_{com} + Mh^2$$
	- _h_: $\perp$ distance between two axes
	- $I_{com}$: rotational inertia of the body about an axis through the COM
	- i.e. _h_ is the distance the actual rotation axis has been shifted from the rotation axis through the COM

# 10.6 Torque
- Torque is a turning of twisting action on a body about a rotation due to a force. If it is exerted at a point given by the position vector $\vec{r}$ relative to the axis, the magnitude of the torque is $$\tau = rF_t = r_{\perp}F = rF\sin \phi$$
	- $F_t$: component of $\vec{F}$ perpendicular to $\vec{r}$
	- $\phi$: angle between $\vec{r}$ and $\vec{F}$
	- $r_{\perp}$ (Moment Arm of $\vec{F}$): perp. distance between the rotation axis and an extended line running through the $\vec{F}$ vector (line of action)
		- _r_ is also the moment arm of $F_t$ 
- The SI unit of torque is the Newton-meter; it is pos. if it tends to rotate a body at rest counterclockwise and negative if it tends to rotate the body clockwise
- Net torque $\tau_{net}$ is the sum of individual torques; torques obey superposition
# 10.7 Newton's Second Law for Rotation
- The rotational analog of Newton's second law is $$\tau_{net} = I\alpha$$
	- $\tau_{net}$: net torque acting on a particle or rigid body
	- _I_: rotational inertia of the particle/body about the rotation axis
	- $\alpha$: resulting angular acceleration about that axis
# 10.8 Work and Rotational KE
- The equations used for calculating work and powier in rotational motion correspond to equations used for translational rotation and are $$W = \int^{\theta_f}_{\theta_i}\tau \ d\theta$$ and $$P = \frac{dW}{dt} = \tau{\omega}$$
- When $\tau$ is constant, the integral reduces to $$W = \tau(\theta_f - \theta_i)$$
- The form of the work-KE theorem used for rotating bodies is $$\Delta K = K_f - K_i = \frac{1}{2}I\omega_f^2-\frac{1}{2}I\omega_i^2=W$$