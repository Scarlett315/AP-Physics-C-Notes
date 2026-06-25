# 11.1 Rolling as Translation and Rotation Combined
 - For a wheel of radius _R_ rolling smoothly, $$v_{com}=\omega R$$ where $v_{com}$ is the linear speed of the wheel's COM and $\omega$ is the angular speed of the wheel about its center
 - Combination of translation and rotation
	 - Translation: every point on the wheel moves with speed $v_{com}$
	 - Rotation: every point on the wheel moves with angular speed $\omega$, or linear speed $v_{com}$ 
	 - Combined--
		 - Top: $v_{com} \ \text{(translation)} + v_{com} \ \text{(rotation)} = 2v_{com}$
		 -  Bottom: $v_{com} \ \text{(translation)} - v_{com} \ \text{(rotation)} =0$
![rolling_combination_diag](https://i.sstatic.net/yocXf.png)

 - The wheel may also be viewed as rotating instantaneously about the point _P_ of the "road" that is in contact with the wheel (pure rotation). The angular sped of the wheel about this point is the same as the angular speed of the wheel about its center. 
	 - If taking point _P_ as the rotation axis, $v_{top} = \omega(2R) = 2v_{com}$-- agreement

# 11.2 Forces and KE of Rolling
- A smoothly rolling wheel has KE $$K=\frac{1}{2}I_{com}\omega^2+\frac{1}{2}Mv^2_{com}$$where $I_{com}$ is the rotational inertia of the wheel about its COM & _M_ is the mass of the wheel
- If the wheel is being accelerated but is still rolling smoothly, the accel. of the COM $\vec{a}_{com}$ is related to the angular accel. $\alpha$ about the center with $$a_{com} = \alpha R$$
- If the wheel rolls smoothly down a ramp of angle $\theta$, its accel. down an _x_-axis extending up the ramp is $$\large a_{com,x}=\frac{-g\sin\theta}{1+\frac{I_{com}}{MR^2}}$$
# 11.3 The Yo-Yo 
- A yo-yo, which travels vertically up or down a string, can be treated as a wheel rolling along an inclined plane at angle $\theta = 90\degree$ 

# 11.4 Torque Revisited
- In 3 dimensions, $$\vec{\tau} = \vec{r} \times \vec{F} \quad \text{and} \quad \tau = rF\sin \phi=rF_\perp=r_\perp F$$ where $\phi$ is the angle between F and $\tau$
- Direction of $\tau$ is given by RHR for cross products
	1. Slide vector F so that its tail is at the origin
	2. Sweep fingers of right hand from r into F; thumb gives direction of $\tau$ 

# 11.5 Angular Momentum
- Angular momentum $\vec{l}$ of a particle with linear momentum $\vec{p}$, mass _m_, and linear velocity $\vec{v}$ is a vector quantity defined relative to a fixed point (usually an origin) as $$\vec{l} = \vec{r} \times \vec{p} = m(\vec{r} \times \vec{v})$$
- Magnitude given by $$\begin{aligned} l&=rmv \sin\phi \\ &=rp_\perp=rmv_\perp \\ &=r_\perp p = r_\perp mv \end{aligned}$$ where $\phi$ is the angle between r and p, $p_\perp$ and $v_\perp$ are the components of p and v perp. to r, and $r_\perp$ is the perp. distance between the fixed point and the extension of p. 
- The direction is given by the RHR w/ r and p
# 11.6 Newton's Second Law in Angular Form
- Newton's second law for a particle can be written in angular form as $$\vec{\tau_{net}} = \frac{d\vec{l}}{dt}$$
	- has no meaning unless the torques and angular momentum are defined w/ respect to the same point
# 11.7 Angular Momentum of a Rigid Body
- The angular momentum $\vec{L}$ of a system of particles is the vector sum of the angular momenta of the individual particles: $$\vec{L} = \sum^n_{i=1}\vec{l}_i$$
- The time rate of change of the angular momentum is equal to the net ext. torque on the system $$\vec{\tau}_{net} = \frac{d\vec{L}}{dt}$$
- For a rigid body rotating about a fixed axis, the component of its angular momentum parallel to the rotation axis is $$L_\parallel = I\omega$$
# 11.8 Conservation of Angular Momentum
- The angular momentum $\vec{L}$ of a system remains constant if the net external torque acting on the system is zero
- Depending on the torques, the angular momentum of the system might be conserved in only one or two directions but not in all directions:
	- If the component of the net external torque on a system along a certain axis is zero, then the component of the angular momentum of the system along that axis cannot change, no matter what changes take place within the system

# 11.9 Precession of a Gyroscope
- A spinning gyroscope can precess about a vertical axis through its support at the rate $$\Omega = \frac{Mgr}{I\omega}$$ where _M_ is the mass, _r_ is the moment arm, _I_ is rot. inertia, and $\omega$ is the spin rate. 