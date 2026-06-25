# 30.1 Faraday's Law and Lenz's Law
- The magnetic flux $\Phi_B$ through an area $A$ in a magnetic field $\vec B$ is defined as $$\Phi_B==\int\vec B \cdot d\vec A$$where the integral is taken over the area. the SI unit of magnetic flux is the weber, where $1\text{Wb} = \text{T} \cdot \text{m}^2$ 
- If $\vec B$ is perp. to the area and uniform over it, the flux is $$\Phi_B = BA$$
- If the magnetic flux through an area bounded by a closed conducting loop changes with time,  a current and an emf are produced in the loop; this process is called induction. The inducted emf is $$\varepsilon=-\frac{d\Phi_B}{dt} \quad \text{(Faraday's Law)}$$If the loop is replaced by a closely-packed coil of $N$ turns, the induced emf is $$\varepsilon - -N\frac{d\Phi_B}{dt}$$
- An induced current has a direction such that the magnetic field due to the current opposes the charge in the magnetic flux that induces the current. The induced emf has the same direction as the induced current. 
- Induced emf: work per unit charge done in maintaining current due to a changing magnetic flux; the work done per unit charge on a charged particle that moves around a closed path in a changing magnetic flux
# 30.2 Induction and Energy Transfers
- The induction of a current by a changing flux means that energy is being transferred to that current. The energy can then be transformed into other forms, such as thermal energy. 
- Eddy Current-- instead of using a loop, using a solid conducting plate & moving it in and out of the magnetic field causes electrons to swirl about within the plate, as if they were caught in an _eddy_ of water
# 30.3 Induced Electric Fields
- An emf is induced by a changing magnetic flux even if the loop through which the flux is changing is not a physical conductor but an imaginary line. The changing magnetic field induces and E field $\vec E$ at every point of such a loop; the induced emf is related to $\vec E$ by: $$\varepsilon=\oint\vec E \cdot d\vec s$$
- Using the induced electric field, we can write Faraday's law in its most general form as $$\oint E \cdot d\vec s = -\frac{d\Phi_B}{dt}$$**A changing magnetic field induces an electric field $\vec E$.** 
	- Can be applied to any closed path that can be drawn in a changing magnetic field
- Induced emf: the sum (integration) of quantities $\vec E \cdot d\vec s$ around a closed path
- Electric potential has meaning for E fields that are produced by static charges; it has no meaning for E fields that are produced by induction
	- Field lines produced by static charges start on positive charges and end on neg. charges; field lines produced by induction form closed loops
# 30.4 Inductors and Inductance
- An inductor is a device that can be used to produce a known magnetic field in a specified region. If a current $i$ is established through each of the $N$ windings of an inductor, a magnetic flux $\Phi_B$ links those windings. The inductance $L$ of the inductor is $$L = \frac{N\Phi_B}{i}$$
- The SI unit of inductance is the henry, where $$1 \text H = 1 \text T \cdot \text m^2 / \text A$$
- The inductance per unit length near the middle of a long solenoid of cross-sectional area $A$ and $n$ turns/unit length is $$\frac{L}{l}=\mu_0n^2 A$$
# 30.5 Self-Induction
- If a current $i$ in a coil changes with time, an emf is induced in the coil. This self-induced emf is $$\varepsilon_L = -L\frac{di}{dt}$$
- The direction of $\varepsilon_L$ is round from Lenz's Law: The self-induced emf acts to oppose the change that produces it
- We cannot define an electric potential w/in the inductor, where the flux is changing; potentials can still be defined at points of the circuit that are not w/in the inductor (E fields are due to charge distributions)
- We can define a self-induced potential diff. $V_L$ across an inductor (between its terminals, outside the region of changing flux). For an ideal inductor (negligible resistance), the magnitude of $V_L$ is equal to the magnitude of self-induced emf $\varepsilon_L$ 
- If, instead, the wire in the inductor has resistance _r_, we mentally separate the inductor into a resistance _r_ and an ideal inductor of self-induced emf $\varepsilon_L$
# 30.5 RL Circuits
- Initially, an inductor acts to oppose changes in the current through it. A long time later, it acts like ordinary connecting wire. 
- If a constant emf $\varepsilon$ is introduced into a single-loop circuit containing a resistance _R_ and an inductance _L_, the current rises to an equilibrium value of $\varepsilon/R$ according to $$i = \frac{\varepsilon}{R}(1-e^{-t/\tau_L}) \quad \text{rise of current}$$Here, $\tau_L = L/R$ governs the rate of rise of the current and is called the inductive time constant of the circuit. When the source of constant emf is removed, the current decays from a value $i_0$ according to $$i = i_0(e^{-t/\tau_L}) \quad \text{decay of current}$$
# 30.7 Energy Stored in a Magnetic Field
- If an inductor $L$ carries a current $i$, the inductor's magnetic field stores an energy given by $$U_B = \frac{1}{2}Li^2$$
# 30.8 Energy Density of a Magnetic Field
- If $B$ is the magnitude of a magnetic field at any point (in an inductor or anywhere else) the density of stored magnetic energy at that point is $$u_B = \frac{B^2}{2\mu_0}$$ (magnetic energy density)
# 30.9 Mutual Induction
- If coils 1 & 2 are near each other, a changing current in either coil can induce an emf in the other. This mutual induction is described by $$\begin{aligned} \varepsilon_2 &= -M\frac{di_1}{dt} \\ \\ \varepsilon_1 &= -M\frac{di_2}{dt} \end{aligned}$$