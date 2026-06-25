
# Practice
## Unit 1 Electrostatics
- To get V at a point evaluate $$V = -\int_\infty^rE(r)dr$$
## Unit 2 Potential
- The electric field inside a conductor is 0
- The potential inside a conductor is uniform ($\Delta V = -\int E dr$ )
## Unit 3 Capacitance
- Capacitors in series have the same charge as the total
	- i.e. $Q_{tot}=Q_{each-capacitor}=C_{eq}\Delta V$ 
- Capacitors in parallel have the same potential difference
- Capacitor comparison problems
	- When capacitors are charged and disconnected from a voltage source, the CHARGE is constant
	- When capacitors are charged and stay connected to a voltage source, the POTENTIAL DIFFERENCE is constant
	- When capacitors are charged and a dielectric is inserted, it reduces the electric field
		- Other things depend on whether there is a voltage source or not-- use equations
- When a capacitor is partially filled with a dielectric, treat the filled and non-filled areas as capacitors in parallel
- Instead of doing the crazy integral thing to get $\Delta V$ you can just find the potential at both points and take the... difference lol
## Unit 4 Circuits
- When doing RC circuit derivations make sure to write out everything, incl. u-substitution because the negative sign is going to disappear somehow or some other stupid thing will happen...
## Unit 5 Magnetism
- The work done by the magnetic force on a point charge is 0 (v always perp. to F_B)
- Current density is current / unit cross-sectional area (not volume!)
## Unit 6 Electromagnetism & Induction
- Magnet falling through solenoid / wire loop; the magnet induces an opposite pole at the top of the solenoid, and use RHR accordingly

---
# Practice Tests
## 04/05/26
- 
## 04/12/26
- Motional emf of loop moving in mag. field --> induced $\varepsilon = BLv$ & $P=\Delta V^2/R = I^2R$ ==> $P = \frac{(BLv)^2}{R}$ 
	- Since is this power dissipated in the *resistor*, it's fine to use $\Delta V$ 
- Without current, resistors do not cause a voltage drop
- use the freaking capacitor formulas correctly bro
- $$\varepsilon = \frac{-d\Phi_B}{dt}=\frac{-d(BA\cos\theta)}{dt}$$
	- when something is constant take it out of the derivative
## 04/19/26

## 2023 FRQ, Set 2
- Electric force on conductor  --> polarization of conductor --> less effect
	- (for a force caused by a positive charge) negative charges are attracted
- always always include all variation and relationships/the full thing in justifications
- energy dissipated by resistors in an RC circuit: use $$\Delta E_R = U_c - U_{0c}$$, and use $Q^2/2C$ to calculate the initial and final energies
- The potential difference across capacitors in parallel are the same, so their charges are proportional
- Use Kirchoff's Loop rule...it's helpful sometimes....
## 2023 FRQ, Set 1
- How does the force on the bar in motional emf vary?
	- If there is a driving force pulling at constant velocity-- resistive (braking) force is constant, current is constant, induced emf is constant
	- Released from rest, falling on incline-- velocity increasing --> braking force increases --> eventually reaches a terminal velocity
	- Released from rest, no driving force-- as it slows, the braking force decreases exponentially; velocity and force decay logarithmically and asymptote

# 2024 FRQ, Set 1
- The direction of an E field is vector is perpendicular to an equipotential line
- Approximation of electric field, use the space between equipotential lines: $$E_x = |\frac{\Delta V}{\Delta x}|$$
## 2022 FRQ, Set 1
- V always increases toward positive, decreases toward negative and a drawn curve MUST BE CONTINUOUS
	- Think about enclosed charge, and what can you treat as a point change
- Wire loop above wire with current-- if some parts of the rectangle are further away, then $\Phi_B$ is less, and the rate of change in magnetic flux has the same dependence on distance
- For the "think of a source of error" questions DO NOT say something that has to do with user error, instead say something like it's uncalibrated, or whatever-- taking many measurements is usually a safe "remedy"

## Course and Exam Desc. Example FRQs
- Current source and capacitor
	- **Linear Voltage Ramp:** Unlike a voltage source, which charges a capacitor exponentially, a constant current source creates a linear increase in voltage (\(V_{c}\)) over time (\(t\)).
	- **Ideal vs. Real Behaviour:** In theory, an ideal current source would increase the capacitor's voltage to infinity. In reality, the voltage will rise until the current source reaches its maximum voltage limit (compliance voltage) or the capacitor breaks down.
	- **Initial State:** At \(t=0\), if the capacitor is not charged, the voltage is 0 and increases linearly from there

## AP Classroom Practice Test
### MCQ
- Changing the PERPENDICULAR field component induces an emf
- When comparing E fields of shells, use Gauss' law to quantify
	- The field within a conductor must be 0
	- Field varies with distance obvs
- Integrating J $$I = \int \vec J (\vec r) \cdot d\vec A$$
	- and $d \vec A = 2\pi r d\vec r$  (circular shells!)
- Ferromagnetic-- magnetic domains remain even after removal
- $\Delta V$ greatest in magnitude when $|\Delta U|$ is greatest
- The magnetic field at the center of a loop is inversely proportional to the radius (not the square of the radius) 
	- Biot-Savart law, but $(dl \times r)$ becomes $2\pi r$ with the integral so an $r$ cancels
- Magnet falling through a wire loop....![[Screenshot 2026-05-11 at 2.42.04 PM.png|431]]
- make sure you have the right thing on top with proportions and do a sanity check; a higher resistance will not result in a higher current lmao
- oh my god add your electric field vectors as vectors
- Electrostatic Shielding: surrounding a region with a closed, conducting shell to create a region inside the conductor that is free from ext. electric fields
	- Potential everywhere on the surface of a conductor is the same, the potential at the inner surface of the shell will be the same
	- No charges w/in the shell
	- No electric field inside the shell
- B field inv proportional to distance-- intuitively closer --> stronger
### FRQ
- DO ALGEBRA CORRECTLY
	- how does one solve a differential equation correctly but forget to distribute a variable in parentheses? you can do better
- if there is an asymptote at zero just draw it on the zero line
- Remember # of turns $N$ for induced emf of a solenoid$$\varepsilon_{\text{solenoid}} = \textbf{N}(-\frac{d\Phi_B}{dt})$$
- if the thing is uniform you can just use $\rho V$ to find charge no need to do calculus every time lmao
	- and if you do use calculus pls use the correct shape-- spherical shells ($4\pi r^2$) for spheres, circles( $2\pi r$ ) for disks
## 2025 FRQ
- remember that E and V have the negative sign $E = -\frac{dV}{dr}$ and $V = -\int E dr$ 
- the form of $\sin^2/\cos^2$ is still like smooth and *sinusoidal* 
- in justifications state constants as well as what changes

