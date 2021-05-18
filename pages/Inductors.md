Tags: #Topic

# Inductors

Inductors are electrical components that store energy in magnetic fields. Their use is similar to the use of a [[Capacitors]], except they store energy differently.

**Inductance** ($L$ : Scalar | $H$) - A tendency for an electrical conductor to oppose the current that flows through it.

**Henry** ($H$) - A unit of inductance. $H = \frac{T \cdot m^2}{A}$.

Formula for the inductance of an inductor,

$$\Huge L = \frac{N \Phi_B}{i}$$

> **LEGEND:**
> $\Phi_B$ - Magnetic flux created by $i$.
> $i$ - Current through the inductor.

For a solenoid inductor,

$$\Huge L = \frac{N \Phi_B}{i}$$

> **LEGEND:**
> $N$ - Number of turns in solenoid inductor.
> $\Phi_B$ - Magnetic flux through the center of the solenoid created by $i$.
> $i$ - Current through the solenoid.

> **NOTE:**
> $N\Phi_B$ is called **"magnetic flux linkage"** because the windings in the solenoid are said to be "linked" by the shared magnetic flux.

## Inductance Per Unit Length of Solenoid

$$
\large
\begin{aligned}
B & = \mu_0 i n \\\\

L &= \frac{N \Phi_B}{i} \\
&= \frac{nl \cdot BA}{i} \\
&= \frac{nl \cdot \mu_0\bcancel{i}n \cdot A}{\bcancel{i}} \\\\

L &= \mu_0 n^2l A \\
\frac{L}{l} &= \mu_0 n^2 A \\
\end{aligned}
$$

## [[Self-Induction]]

## Electric Potential in Inductor

Although electric potentials do not exist for the area inside the self-induced E-field of the solenoid, we can still define electric potential at the terminals of the solendoid.

## Energy Stored in an Inductor

An inductor can hold energy in its magnetic field. This stored energy is denoted by $U_B$ and follows the formula,

$$\Huge U_B = \frac{1}{2} L i^2$$

This equation takes a similar form to the [[Capacitors]] equation of $U_C= \dfrac{1}{2}CV^2$.

## Energy Density of a Magnetic Field

**Energy Density of a B-Field** ($u_B$ : Scalar | $\frac{J}{m^3}$) - The volume energy density of a magnetic field. 

Since the magnetic field of a solenoid is uniform and contained completely within the solenoid, we can write an equation for the energy density of the solenoid.

$$
\Large
\begin{aligned}
V &= Al \\
U_B &= \frac{1}{2} L i^2 \\
\frac{L}{l} &= \mu_0 n^2 A \\
B &= \mu_0 i n \\\\

u_B &= \frac{U_B}{V} \\
&= \frac{1}{2} L i^2 \cdot \frac{1}{Al} \\
&= \frac{L}{l} \cdot \frac{i^2}{2A} \\
&= \mu_0 n^2 \bcancel{A} \cdot \frac{i^2}{2\bcancel{A}} \\
&= \frac{\mu_0 i^2 n^2}{2} \\
&= \frac{\mu_0 i n}{2} \cdot \frac{\mu_0}{\mu_0} \cdot \frac{i n}{1}\\
&= \frac{\mu_0 i n}{2\mu_0} \cdot \frac{\mu_0 i n}{1}\\
&= \frac{B}{2\mu_0} \cdot \frac{B}{1}\\
u_B &= \frac{B^2}{2\mu_0} \\
\end{aligned}
$$