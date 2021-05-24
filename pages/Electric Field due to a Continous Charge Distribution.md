Tags: #Topic 

# Electric Field due to a Continous Charge Distribution
Derived from the electric field strength formula, the electric field for a small change in charge is

$$
\Large
\begin{aligned}
Q &= \lambda l \\\\

dE &= d \left( \frac{kq}{r^2} \right) \\
&= \frac{k \cdot dq}{r^2} \\
&= \frac{k (\lambda \cdot dl)}{r^2} \\
\end{aligned}
$$
> **LEGEND:**
> $\lambda$ - Charge per unit length.
> $l$ - Length of a continous line of charge.

Therefore the net electric potential at a point is

$$\Large E_\text{net} = \int \frac{k \lambda}{r^2} \cdot dl$$

## Electric Field at Center of Ring of Charge

$$
\Large
\begin{aligned}
r &= \sqrt{z^2 + R^2}\\\\ 

E_\text{net} &= \int \frac{k \lambda}{r^2} \cdot dl \\
E_\text{net} &= \int \frac{k \lambda}{r^2} \cdot \cos \theta \cdot dl \\
&= \int \frac{k \lambda \cos \theta}{\sqrt{z^2 + R^2}} \cdot dl\\
\end{aligned}
$$

Following the diagram below.

![](attachments/e_field_ring_of_charge.png)

> **NOTE:**
> We have $\cos \theta$ because the $y$ component of each charge cancels out.
> 
> ![](attachments/e_field_ring_of_charge_cancel.png)