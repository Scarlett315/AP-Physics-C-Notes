# 27.1 Single-Loop Circuits
- An emf device does work on charges to maintain a potential difference between its output terminals. If _dW_ is the work the device does to force positive charge _dq_ from the negative to the positive termainl, then the emf (work/unit charge of the device is$$\varepsilon= \frac{dW}{dq}$$
- An ideal emf device lacks internal resistance, and the potential difference between its terminals is = to the emf.
- A real emf device has internal resistance; emf = V between terminals only if there is no current
- Change in potential in traversing a resistance _R_ in the direction of the current is _-iR_; in the opposite direction it is _+iR_
- The change in potential in traversing an ideal emf device in the direction of the emf arrow is $+\varepsilon$ and in the opposite direction it is $-\varepsilon$    
- Conservation of Energy --> Loop Rule $\Delta V_{loop} = 0$
- Conservation of Charge --> Junction Rule $I_{in} = I_{out}$ 
- When a real battery does work on the charge carriers in a current _i_ through the battery, the rate _P_ of energy transfer to the charge carriers is $$P=iV$$where V is the potential across the terminals of the battery. 
- The rate $P_r$ at which energy is dissipated as thermal energy in the battery is $$P_r=I^2R$$
- The rate $P_{emf}$ at which the chem. energy in the battery changes is $$P_{emf} = i\varepsilon$$
- When resistances are in series, they have the same current. The equivalent resistance is the sum of the individual resistances. 

# 27.2 Multiloop Circuits
- Resistances in parallel have the same $\Delta V$
- parallel resistors
# 27.3 Ammeter and Voltmeter
- Ammeter - current; Voltmeter - Voltage; Multimeter - V/I/R

# 27.4 RC Circuits
- When an emf $\varepsilon$ is applied to a resistance _R_ and capacitance _C_ in series, the charge on the capacitor increases according to $$q = C\varepsilon(1-e^{\frac{-t}{RC}})$$in which $C\varepsilon = q_0$ is the equilibrium (final) charge and $RC = \tau$ is the capacitive time constant of the circuit
- During the charging, the current is $$i=\frac{dq}{dt}=(\frac{\varepsilon}{R})e^{-t/RC}$$
- When a capacitor discharges through a resistance _R_, the charge on the capacitor decays according to $q=q_0e^{-t/RC}$ 
- During the discharging, the current is $$i=\frac{dq}{dt}=-\frac{q_0}{RC}e^{-t/RC}$$
- Potential Difference across capacitor during charging: $$V_C = \frac{q}{C}=\varepsilon(1-e^\frac{-t}{RC})$$
- A capacitor that is being charged initially acts like ordinary connecting wire relative to the charging current. A long time later, it acts like a broken wire. 

## Derivations
1. Apply the Loop Rule to the circuit: $\varepsilon-\Delta V_{resistor} - \Delta V_{capacitor} = 0$ $$\varepsilon - iR - \frac{q}{C} = 0$$
2. Because $i = \frac{dq}{dt}$, we can substitute and rearrange the first equation to get a differential equation: $$R\frac{dq}{dt}+\frac{q}{C}=\varepsilon$$
3. Separation of Variables: $$R\frac{dq}{dt}=\varepsilon-\frac{q}{C}$$ $$\frac{dq}{CE-q}=\frac{dt}{RC}$$
4. Initial and final conditions
	- Initial: no charge on capacitor, so it acts like a wire-- q = 0 at t = 0
	- Final: when the capacitor is charged, $\frac{dq}{dt} = 0$ and solving for _q_, we get that $q_{final} = q_{max} = C\varepsilon$
5. Integrate both sides  and solve$$\int^q_0\frac{dq}{CE-q}=\int^t_0\frac{dt}{RC}$$ $$-\ln(\frac{CE-q}{CE})=\frac{t}{RC}$$ $$\frac{CE-q}{CE}=e^\frac{-t}{RC}$$ $$\boxed{ \large q(t) = C\varepsilon(1-e^\frac{-t}{RC}) \quad \text{or} \quad q(t) = Q_{max}(1-e^\frac{-t}{\tau})}$$
6. To derive current, differentiate the charge with respect to time: $$i(t) = \frac{d}{dt}[CE(1-e^{\frac{-t}{RC}})]$$ $$\boxed {\large i(t) = \frac{\varepsilon}{R}e^\frac{-t}{RC} \quad \text{or} \quad i(t)= I_{max}e^\frac{-t}{\tau}}$$
