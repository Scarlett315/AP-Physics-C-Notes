# 31.1 _LC_ Oscillations
- In an oscillating LC circuit, energy is shuttled periodically between the E field of the capacitor and the B field of the inductor; instantaneous values of the two forms of energy are $$U_E = \frac{q^2}{2C} \quad \text{and} \quad U_B=\frac{Li^2}{2}$$where $q$ is the instantaneous charge on the capacitor and $i$ is the instantaneous current through the inductor
- The total energy $U = U_E + U_B$ remains constant. 
- The principle of conservation of energy leads to $$L\frac{dq^2}{dt} + \frac{1}{C}q = 0$$as the differential equation of LC oscillations (no resistance)
- The solution of this differential equation is $$q = Q\cos(\omega t + \phi)$$in which $Q$ is the charge amplitude (max. charge on capacitor) and the angular frequency $\omega$ of the oscillations is $$\omega = \frac{1}{\sqrt{LC}}$$
- The phase constant $\phi$ is determined by the initial conditions (at t=0) of the system
- The current $i$ in the system at any time is $$i = -\omega Q \sin (\omega t + \phi)$$in which $\omega Q$ is the current amplitude $I$. 
- 8 Stages

| Stage | Charge (capacitor)                      | Current (inductor)                          |
| ----- | --------------------------------------- | ------------------------------------------- |
| 1     | maximum                                 | none                                        |
| 2     | discharging                             | increasing                                  |
| 3     | fully discharged (none)                 | maximum                                     |
| 4     | charging, polarity opposite that of (1) | decreasing                                  |
| 5     | maximum, polarity opposite that of (1)  | none                                        |
| 6     | discharging                             | increasing, dirrection opposite that of (2) |
| 7     | fully discharged (none)                 | maximum                                     |
| 8     | charging                                | decreasing                                  |
# 31.2 Damped Oscillations in an RLC Circuit
- Oscillations in an LC circuit are damped when a dissipative element $R$ is also present in the circuit. $$L\frac{d^2q}{dt^2}+R\frac{dq}{dt}+\frac{1}{C}q=0$$
- The solution of this DE is $$q=Qe^{-Rt/2L}\cos(\omega't+\phi)$$where $$\omega'=\sqrt{\omega^2-(R/2L)^2}$$
- We consider only situations with small $R$ and thus small damping; then $\omega' \approx \omega$ 
# 31.3 Forced Oscillations of Three Simple Circuits SKIP
# 31.4 The Series RLC Circuit (less detail, qualitative only)
lmao nvm
