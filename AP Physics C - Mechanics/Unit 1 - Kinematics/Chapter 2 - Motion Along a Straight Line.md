## 2.1 Position, Displacement, and Average Velocity
> [!abstract] Key Ideas
> - Displacement is a vector and is defined by the change in position $\Delta x = x_2 - x_1$ 
> - Average velocity of a particle that has moved from position $x_1$ to $x_2$ during a time interval $\Delta{t} = t_2 - t_1$ is $v_{\text{avg}} = \frac{\Delta x}{\Delta t}$
> 	- $v_{\text{avg}}$ is a vector quantity, and the algebraic sign indicates the direction of motion
> 	- Average velocity depends on the original and final positions
> - Average speed $s_{avg}$ during $\Delta t$ depends on total distance ($s_{avg} = \frac{\text{total distance}}{\Delta t})$
>
### Motion
- Kinematics: the classification and comparison of motions
- Restrictions on general properties of motion:
	1. The motion is along a straight line only
	2. Forces cause motion but will not be discussed here
	3. The moving object is either a particle (point-like object) or one that moves like a particle (such that every portion moves in the same direction at the same rate)
### Position & Displacement, Describing Speed
- Displacement ($\Delta x$): a change from position $x_1$ to $x_2$ (considers only initial & final positions)
	- Is a vector; you must indicate +/-  (although you don't have to show if it is +)
- Position can be described with a graph of position *x* plotted as a function of time *t*; $x(t)$ 
- Average Velocity ($v_{avg}$): the ratio of displacement $\Delta x$ that occurs during a particular time interval $\Delta t$ to that interval; $v_{\text{avg}} = \frac{\Delta x}{\Delta t}$
	- On a graph of x-t, $v_{avg}$ is the slope of the straight line that connects two particular points on the x(t) curve
	- Is a vector quantity
- Average Speed ($S_{avg}$): involves total distance covered; $\large s_{avg} = \frac{\text{total distance}}{\Delta t}$
	- Not a vector
## 2.2 Instantaneous Velocity and Speed
>[!abstract] Key Ideas
>- The instantaneous velocity $v$ of a moving particle is $\large \lim_{\Delta t \to 0} \frac{\Delta x}{\Delta t} = \frac{dx}{dt}$
>- The instantaneous velocity may be found as the slope (at that particular time) of the graph of x-t
>- Speed is the magnitude of instantaneous velocity

**include pos/vel/accel graph**

### Acceleration
- Acceleration: a change in a particle's velocity
- Average Acceleration ($a_{avg}$): $a_{avg} = \frac{\Delta v}{\Delta t}$ 
- Instantaneous Acceleration (acceleration): $\large a = \frac{dv}{dt}$
- The acceleration of a particle at any instant is the second derivative of it's position x(t) with respect to time, i.e.
	- $\large a = \frac{dv}{dt} = \frac{d}{dt}(\frac{dx}{dt}) = \frac{d^2x}{dt^2}$
- unit is m/s^2 or generally length/time\^2
- Your body responds to accelerations, but not to velocities; i.e. you feel something when a vehicle accelerates/decelerates but not when it is at a constant velocity
- Large accelerations are sometimes expressed in terms of g units, with $1g = 9.8\frac{m}{s^2}$ 
- In common language, the pos. acceleration means that the speed is increasing and vice versa; however scientifically<mark style="background: #ADCCFFA6;"> the sign of acceleration indicates a direction</mark>
	- e.g. if a car with an initial velocity of -25m/s is braked to a stop in 5.0s, then average velocity = + 5.0m/s\^2
	- If the signs of velocity and acceleration are the same, the speed increases and vice versa
## 2.4 Constant Acceleration
>[!abstract] Key Ideas
>The following five equations describe the motion of a particle with constant acceleration:
>- $v = v_0 + at$
>- $v^2 = v_0^2 + 2a(x-x_0)$
>- $x-x_0 = v_0t + \frac{1}{2}at^2$
>- $x-x_0 = \frac{1}{2}(v_0 + v)t$
>- $x - x_0 = vt - \frac{1}{2}at^2$
>
>These are not valid when acceleration is not constant.
### Constant Acceleration: A Special Case
The first and second equations are the <mark style="background: #ADCCFFA6;">basic equations for constant acceleration</mark> and can be used to solve any constant acceleration question provided; the other 3 are derived equations that can be helpful in certain situations. You can solve either by memorizing all 5 or memorizing 1 & 2 and set up a system of equations. 

1. **First Basic Equation--** When acceleration is constant, the average and instantaneous acceleration are equal:
	- $\large a = a_{avg} = \frac{v-v_0}{t-0}$ (where $v_0$ = velocity at time 0 and v is the velocity at any later time t)
	- thus, <mark style="background: #ADCCFFA6;">$v = v_0 + at$</mark>
2. **Second Basic Equation--**<mark style="background: #ADCCFFA6;"> $x - x_0 = v_0t + \frac{1}{2}at^2$</mark> 
	- Rewrite equation for average velocity in a similar manner: $v_{avg} = \frac{x - x_0}{t-0}$ 
	- (1) $x = x_0 + v_{avg}t$                     (\*rewrite to solve for x)
	- (2) $v_{avg} = \frac{1}{2}(v_0 + v)$
	- (3) $v_{avg} = v_0 + \frac{1}{2}at$                   (\*substitute first basic equation in for v)
	- (4) $x - x_0 = v_0t + \frac{1}{2}at^2$            (\*substitute eq. 3 into eq. 1)
	- note that $x-x_0$ is displacement if you are dumb and forget :)
3. **Third Basic Equation--** Eliminate *t* to obtain
	- $v^2 = v_0^2 + 2a(x-x_0)$ 
	- Helpful if we do not know t and are not required to find it
4. **Fourth Basic Equation--** Eliminate a to obtain
	- $x-x_0 = \frac{1}{2}(v_0 + v)t$
5. **Fifth basic Equation--** Eliminate $v_0$ to obtain
	- $x - x_0 = vt - \frac{1}{2}at^2$
	- Notice the difference between this one and the second basic equation, as this one requires velocity at time $t$ 

| Equation <br>Number |             Equation             | Missing <br>Quantity |
| :-----------------: | :------------------------------: | :------------------: |
|      **2-11**       |          $v = v_0 + at$          |       $x-x_0$        |
|      **2-15**       | $x-x_0 = v_0t + \frac{1}{2}at^2$ |         $v$          |
|        2-16         |    $v^2 = v_0^2 + 2a(x-x_0)$     |         $t$          |
|        2-17         | $x-x_0 = \frac{1}{2}(v_0 + v)t$  |         $a$          |
|        2-18         | $x - x_0 = vt - \frac{1}{2}at^2$ |        $v_0$         |

#### Example: Drag Race of Car and Motorcycle
---
A jet airplane, a car, and a motorcycle race from rest along a runway. Initially the motorcycle takes the lead, but then the jet takes the lead, and finally the car blows past the motorcycle. Here let's focus on the car and motorcycle and assign some reasonable values to the motion. The motorcycle first takes the lead because it's (constant) acceleration $a_m = 8.40 \space m / s^2$  is greater than the car's acceleration $a_c = 5.60 \space m/s^2$ but it soon loses to the car because it reaches it's greatest speed $v_m = 58.8 m/s$ before the car reaches it's greatest speed $v_c = 106m/s$. **How long does it take the car to reach the motorcycle?**

---
1. The motorcycle travels in two phases: (1) accelerating through distance $x_{m1}$ from zero initial velocity and acceleration of 8.40 m/s\^2, then (2) traveling through distance $x_{m2}$ with constant velocity v = 58.8 m/s\^2 and 0 acceleration.
2. At some time t, the vehicles will be at the same coordinate $x_c$, i.e. for the motorcycle $$x_c = x_{m1} + x_{m2}$$ 
3. Using equation 2-15 ($x-x_0 = v_0t + \frac{1}{2}at^2$) with $x_0=0$ and $v_0 = 0$, we get $$x_c = \frac{1}{2}a_ct^2$$
4. To fill out $x_{m1}$, we must find the time $t_m$ it takes for the motorcycle to reach it's maximum speed $v_m$ using equation 2-11 ($v = v_0 + at$). Substitute $v_0 = 0$, $v = v_m = 58.8m/s$, $a = a_m = 8.40 m/s^2$ to get $$t_m = \frac{v_m}{a_m} = \frac{58.8m/s}{8.40m/s^2} = 7.00s$$
5. Get the distance $x_{m1}$ using Eq. 2-15 with $x_0 = 0$ and $v_0 = 0$, and substitute from the equation in Step 4: $$x_{m1} = \frac{1}{2}a_m t^2_m = \frac{1}{2}a_m(\frac{v_m}{a_m})^2 = \frac{1}{2}\frac{v^2m}{a_m}$$
6. For the remaining time of $t - t_m$, the motorcycle travels at it's maximum speed with 0 accel.; to get the distance, use Eq. 2-15, but not $v_0 = v_m$ (speed at end of 1st stage) & $a = 0$: $$x_{m2} = v_m(t-t_m) = v_m(t-7.00s)$$
7. Substitute equations from Steps 3, 5, and 6 into the equation from Step 1: $$\frac{1}{2}a_c t^2 = \frac{1}{2}\frac{v^2_m}{a_m} + v_m(t - 7.00s)$$
8. This is a quadratic equation. Substituting in the given data, we solve the equation finding t= 4.44s and t = 16.6s. Reject t = 4.44 because we know that the car passes the motorcycle after it has reached its maximum speed; i.e. t > 7.00. Therefore: $$\large t = 16.6s$$
### Another Look at Constant Acceleration (Using Integration)
- you can also get 2-11 and 2-15 through integration 
- derivation of 2-11:
	1. Given the definition of acceleration $a = \frac{dv}{dt}$, rewrite as $dv = a\space dt$
	2. Write the indefinite integral of both sides: $\int dv = \int a\space dt$ 
	3. Acceleration is a constant and can be taken outside: $\int dv = a \int dt$, or $v = at + C$ 
	4. To evaluate C, let t = 0, at which time v = $v_0$. Substituting into the equation in step 3, we get $v_0 = (a)(0) + C = C$. Substitute into Step 3 again to obtain $v = at + v_0$, or      Eq. 2-11. 

**finish these notes later :(**

## 2.5 Free-Fall Acceleration
>[!abstract] Key Ideas
>- An important example of straight-line motion with constant acceleration is that of an object rising or falling freely near Earth's surface. The constant acceleration equations describe this motion, but we make two changes in notation: 
>1. we refer the motion to the vertical y axis with +y vertically up; 
>2. we replace a with -g, where g is the magnitude of the free-fall acceleration. Near Earth's surface, $g = 9.8\space m/s^2 = 32\space ft/s^2$
- Free-fall acceleration: a certain constant rate where an object accelerates downward near Earth's surface 
- Equations of motion also apply to free fall near earth's surface, with two slight changes:
	1. The directions of motion are now along a vertical y-axis instead of an x-axis (important when combined horizontal and vertical motions are examined)
	2. The free-fall acceleration is negative, thus it has the value -g in equations
		- Note that g is the magnitude of acceleration (g = 9.8 m/s\^2, not -9.8 m/s\^2) 
#### Example: Time for full up-down flight, baseball toss
A pitcher tosses a baseball up along a y-axis, with initial speed 12 m/s.

Note:
- the acceleration is *always* a = -g, from when the ball leaves the pitcher to when it returns to his hand
- the velocity at the maximum height must be 0. 

**A) How long does the ball take to reach its maximum height?**
- Knowing v, a, and $v_0 = 12$, use Eq. 2-11
$$t = \frac{v - v_0}{a} = \frac{0 - 12 m/s}{-9.8 m/s^2} = 1.2s$$
**B) What is the ball's maximum height above its release point?**
- Take the ball's release point as $y_0 = 0$. Write Eq. 2-16 in y notation:
$$y = \frac{v^2-v_0^2}{2a}=\frac{0-(12m/s)^2}{2(-9.8m/s)^2}=7.3\text{m}$$
**C): How long does it take the ball to reach a point 5.0m above its release point?**
1. Knowing displacement = $y - y_0$ = 5.0m, choose Eq. 2-15 and rewrite with y:
$$y = v_0t - \frac{1}{2}gt^2 \quad\text{or} \quad5.0\text{m} = 12(m/s)t-\frac{1}{2}(9.8m/s^2)(t^2)$$
2. Units are consistent so you can temporarily omit them:
$$4.9t^2 - 12t + 5.0 = 0$$
3. Solve the quadratic, which yields t = 0.53s and t = 1.9s. 
	- There are two times that this happens! (once going up, and once on the way down)
## 2.6 Graphical Integration in Motion Analysis
>[!abstract] Key Ideas
>- On a graph of a a-t, the change in velocity is given by $$v_1 - v_0 = \int^{t_1}_{t_0}a \space dt$$
>	- This integral amounts to finding an area on the graph: $$ \int^{t_1}_{t_0}a \space dt = (\text{area between acceleration curve and time axis, from t0 to t1})$$
>- On a graph of v-t, the change in position is given by  $$x_1 - x_0 = \int^{t_1}_{t_0}v \space dt$$
>	- where the integral can be taken from the graph as $$ \int^{t_1}_{t_0}v \space dt = (\text{area between velocity curve and time axis, from t0 to t1})$$

### Graphical Integration in Motion Analysis
- When we have a graph of an object's acceleration a versus time t, we can integrate on the graph to find the velocity at any given time.  $$v_1 - v_0 = \int^{t_1}_{t_0}a \space dt$$
- Similarly, because velocity v is defined in terms of the position x as *v = dx/dt*, then $$x_1 - x_0 = \int^{t_1}_{t_0}v \space dt$$