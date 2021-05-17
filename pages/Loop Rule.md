Tags: #Topic 

# Loop Rule

Also known as **"Kirchhoff's Voltage Law."**

The voltage of a closed loop is $0$. To get an equation for a loop, you pick a direction to traverse and then sum up the voltages of each circuit element in the loop. 

If the circuit element is a resistor
- If you are traversing in the **opposite direction as the current**, then you get a voltage increase ($+V$).
- If you are traversing in the **same direction as the current**, then you get a voltage drop ($-V$).

Capacitor/Battery
- If you are traversing from the **negative side** $\to$ **positive side**, there is a voltage increase ($+V$).
- If you are traversing from the **positive side** $\to$ **negative side**, there is a voltage drop ($-V$). 

> **Ex.**
> 
> Traversing in the direction of the current $I$,
> 
> $$
\large
\begin{aligned}
V_\text{net} &= 0 \\
&= V_C + V_R + V_\mathcal{E} \\
&= - V_C - I_R R_R  + \mathcal{E} \\
\end{aligned}
> $$
>
> ![](attachments/loop_rule.png)