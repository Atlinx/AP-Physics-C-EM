Tags: #Topic 

# Magnetic Flux

**Weber** ($W$) - The unit used to measure magnetic flux. It is derived from $W = T \cdot m^2$.

**Magnetic Flux** ($\Phi_B$ : Scalar | $Wb$)- The amount of magnetic field lines that passes through a certain area.

Field lines passing one way through an area will cancel an equal number of field lines passing in the opposite direction. Therefore if the surface contains opposing B-field lines, those field lines will detract from each other and you would get an equation for $B_\text{net}$ like 

$$\large B_\text{net} = B_\text{one direction} - B_\text{opposite direction}$$

---

The formula for magnetic flux is

$$\Large \Phi_B = \int \vec B \cdot d\vec A$$

> **LEGEND:**
> $\vec B$ - Magnetic field passing through the area
> $\vec A$ - Area vector, which has a magnitude of $dA$, the area we are measuring, and a direction perpendicular to the area's surface.

This can alternatively be written as

$$\Large \Phi_B = \int B d A \cos \theta$$

> **LEGEND:**
> $\vec B$ - Magnetic field passing through the area
> $\vec A$ - Area vector, which has a magnitude of the area we are measuring and a direction pointing perpendicularly to the area's surface.
> $\theta$ - Angle between $\vec B$ and $\vec A$.

And if $\vec B$ and $\vec A$ are uniform and perpendicular to each other, the equation can be simplified down to

$$\Large \Phi_B = BA$$

> **LEGEND:**
> $B$ - Magnetic field passing through the area of interest
> $A$ - Area of interest

---

## Strategies for Finding Magnetic Flux

If the area of interest encloses a uniform magnetic field, make sure to use the area of the enclosed B-field as $A$ in $\Phi_B = BA$.  This comes from the original magnetic flux formula, $\Phi_B = \int \vec B \cdot d \vec A$. SInce $B=0$ for all the $dA$s outsides of the uniform B-field, the only $\vec B \cdot d \vec A$s that would get evaluated are the ones inside of the uniform B-field.

> **Ex.**
> From the diagram below,
> 
> $\Phi_{A_2} = B \cdot A_1$
> 
> Note that $\Phi_{A_2} \neq B \cdot A_2$, since $A_2$ also includes points where $B=0$.
> 
> ![](attachments/finding_magnetic_flux_tips.png)

## Magnetic Flux Density

Magnetic flux density is a term that is synonymous with the magnitude of a B-field. It's units is $\dfrac{Wb}{m^2}$, which is just $B$ according to $\Phi_B = BA$.