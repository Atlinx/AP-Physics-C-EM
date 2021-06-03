Tags: #Topic 

# RL-Circuits

RL-circuits are circuits involving inductors, resistors, batteries, and switches.

## Transient Equations
 
**Inductor Time Constant** ($\tau_L$) - The time required for the current to change by 60% of it's maximum value starting at $t=0$.

$$\Large \tau_L = \frac{L}{R}$$

### Charging Inductor

Only works for a circuit with one resistor, one voltage source, and one inductor.

$$\Large i(t) = \frac{\mathcal{E}}{R} \left(1 - e^{-t/\tau_L} \right)$$

> **LEGEND:**
> $i(t)$ - Current through the inductor.
> $\mathcal{E}$ - Voltage of the power source.
> $R$ - Resistance of the resistor.
> $\tau_L$ - Inductor time constant.
> $t$ - Time since charging started.

At $t=0$, the inductor blocks any current from going through it.

At $t\to\infty$, the inductor acts as a normal wire with $0$ resistance.

### Discharging Inductor

Only works for a circuit with one resistor and one inductor.

$$\Large i(t) = i_0 \left(e^{-t/\tau_L} \right)$$

> **LEGEND:**
> $i(t)$ - Current through the inductor.
> $i_0$ - Initial current through the inductor.
> $\tau_L$ - Inductor time constant.
> $t$ - Time since discharging started.