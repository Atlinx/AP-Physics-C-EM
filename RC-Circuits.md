Tags: #Topic 

# RC-Circuits

RC-circuits are circuits involving capacitors, resistors, batteries, and switches.

## Transient Equations
 
**Capacitor Time Constant** ($\tau_C$) - The time required for the current to change by 60% of it's maximum value starting at $t=0$.

$$\Large \tau_C = RC$$

### Charging Capacitor

Only works for a circuit with one resistor, one voltage source, and one capacitor.

#### Current

$$\Large i(t) = \frac{\mathcal{E}}{R} \left(e^{-t/\tau_C} \right)$$

> **LEGEND:**
> $i(t)$ - Current through the capacitor.
> $\mathcal{E}$ - Voltage of the power source.
> $R$ - Resistance of the resistor.
> $\tau_C$ - Capacitor time constant.
> $t$ - Time since charging started.

At $t=0$, the capacitor acts as a normal wire with $0$ resistance.

At $t\to\infty$, the capacitor blocks any current from going through it.

#### Voltage

$$\Large V(t) = \mathcal{E} \left(1 - e^{-t/\tau_C} \right)$$

> **LEGEND:**
> $V(t)$ - Voltage across the capacitor.
> $\mathcal{E}$ - Voltage of the power source.
> $\tau_C$ - Capacitor time constant.
> $t$ - Time since charging started.

#### Charge

$$\Large Q(t) = C\mathcal{E} \left(1 - e^{-t/\tau_C} \right)$$

> **LEGEND:**
> $V(t)$ - Voltage across the capacitor.
> $\mathcal{E}$ - Voltage of the power source.
> $C$ - Capacitance of the capacitor.
> $\tau_C$ - Capacitor time constant.
> $t$ - Time since charging started.

### Discharging Capacitor

Only works for a circuit with one resistor and one capacitor.

#### Current

$$\Large i(t) = i_0 \left(e^{-t/\tau_C} \right)$$

> **LEGEND:**
> $i(t)$ - Current through the inductor.
> $i_0$ - Initial current through the inductor.
> $\tau_L$ - Inductor time constant.
> $t$ - Time since discharging started.

#### Voltage

$$\Large V(t) = V_0 \left(e^{-t/\tau_C} \right)$$

> **LEGEND:**
> $V(t)$ - Voltage across the capacitor.
> $V_0$ - Initial voltage across the capacitor.
> $\tau_C$ - Capacitor time constant.
> $t$ - Time since discharging started.

#### Charge

$$\Large Q(t) = Q_0 \left(e^{-t/\tau_C} \right)$$

> **LEGEND:**
> $V(t)$ - Voltage across the capacitor.
> $\mathcal{E}$ - Voltage of the power source.
> $C$ - Capacitance of the capacitor.
> $\tau_C$ - Capacitor time constant.
> $t$ - Time since discharging started.