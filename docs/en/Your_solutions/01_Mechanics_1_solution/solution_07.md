**7. Elimination of time and interpretation of acceleration**

**The path equation is given in parametric form: $x(t) = 2t^2, y(t) = 3t^3$. Eliminate the parameter $t$. Draw the trajectory. Calculate $\vec{v}(t), |\vec{v}(t)|, \vec{a}(t)$ and $|\vec{a}(t)|$. Is the acceleration constant?**

---

**Step 1: Eliminate the Parameter $t$ (The "Combine" Step)**
To see the shape of the path on a graph ($y$ vs $x$), we need to get rid of $t$. 
1.  From the first equation: $x = 2t^2 \rightarrow t^2 = \frac{x}{2} \rightarrow t = \sqrt{\frac{x}{2}}$
2.  Plug this $t$ into the $y$ equation: $y = 3 \cdot (\sqrt{\frac{x}{2}})^3$
3.  **Final Equation:** $y = 3 \cdot (\frac{x}{2})^{3/2}$ (This looks like a curve that starts at $(0,0)$ and grows faster as $x$ increases).



---

**Step 2: Calculate Velocity ($\vec{v}$) and its Magnitude ($|\vec{v}|$)**
Velocity is the "change" in position. We take the **Derivative** of $x(t)$ and $y(t)$:
* **Horizontal ($v_x$):** Derivative of $2t^2$ is **$4t$**.
* **Vertical ($v_y$):** Derivative of $3t^3$ is **$9t^2$**.
* **Vector:** $\vec{v}(t) = (4t)\hat{i} + (9t^2)\hat{j}$

The **Magnitude** ($|\vec{v}|$) is just the "speedometer" reading. We use the Pythagorean Theorem:
* **Magnitude:** $|\vec{v}(t)| = \sqrt{(4t)^2 + (9t^2)^2} = \sqrt{16t^2 + 81t^4}$

---

**Step 3: Calculate Acceleration ($\vec{a}$) and its Magnitude ($|\vec{a}|$)**
Acceleration is the "change" in velocity. Take the **Derivative** of our velocity results:
* **Horizontal ($a_x$):** Derivative of $4t$ is **$4$**.
* **Vertical ($a_y$):** Derivative of $9t^2$ is **$18t$**.
* **Vector:** $\vec{a}(t) = (4)\hat{i} + (18t)\hat{j}$

The **Magnitude** ($|\vec{a}|$) is:
* **Magnitude:** $|\vec{a}(t)| = \sqrt{4^2 + (18t)^2} = \sqrt{16 + 324t^2}$

---

**Step 4: Is the Acceleration Constant?**
A "constant" acceleration means the numbers never change, no matter what time ($t$) it is. 
* Look at our acceleration vector: $\vec{a}(t) = 4\hat{i} + 18t\hat{j}$.
* Because of that **$18t$**, the vertical part of the acceleration gets bigger and bigger as time goes on. 
* **Answer:** **No**, the acceleration is **not constant** because it depends on time ($t$).



**Conclusion:**
* **Trajectory:** A curve moving up and to the right.
* **Speed:** Getting faster very quickly.
* **Acceleration:** Not constant; the "push" is increasing every second!
