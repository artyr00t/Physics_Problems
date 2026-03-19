**10. Kinematics**

**Point M moves according to the equation: $\vec{r}(t) = (a\cos(\omega t), b\sin(\omega t), bt)$ where $a, b, \omega$ are positive constants. a) Find the equation of the point's trajectory, b) Compute the path length of the point from time $t=0$ to $t=t_0$, c) Draw the trajectory of this point using Python or interactive HTML. Discuss special cases.**

---

**Step 1: Understanding the Map (Breaking down the Coordinates)**
The formula $\vec{r}(t)$ tells us where the point is in 3D space ($x, y, z$) at any time $t$:
* **$x = a\cos(\omega t)$** (Moving back and forth)
* **$y = b\sin(\omega t)$** (Moving side to side)
* **$z = bt$** (Moving up at a constant speed)

Imagine drawing an oval (ellipse) on the floor while slowly rising up in an elevator. This shape is called a **Helix**.



---

**Step 2: Finding the Shape (Trajectory Equation)**
To see the shape without time ($t$), we use a math trick: $\cos^2(\theta) + \sin^2(\theta) = 1$.
1.  Rearrange $x$ and $y$:
    * $\frac{x}{a} = \cos(\omega t)$
    * $\frac{y}{b} = \sin(\omega t)$
2.  Square them and add them together:
    * $(\frac{x}{a})^2 + (\frac{y}{b})^2 = \cos^2(\omega t) + \sin^2(\omega t)$
3.  **The Result:** $\frac{x^2}{a^2} + \frac{y^2}{b^2} = 1$

This tells us that if you look at the object from directly above, it looks like an **Ellipse**. But because $z = bt$, it is actually a 3D spiral (an **Elliptical Helix**).

---

**Step 3: Measuring the "String" (Path Length)**
To find the total distance traveled ($s$) from $t=0$ to $t=t_0$, we need the speed.
1.  **Find the Velocity ($\vec{v}$):** (Derivative of position)
    * $v_x = -a\omega\sin(\omega t)$
    * $v_y = b\omega\cos(\omega t)$
    * $v_z = b$
2.  **Find the Magnitude (Speed):**
    * $|\vec{v}| = \sqrt{(-a\omega\sin(\omega t))^2 + (b\omega\cos(\omega t))^2 + b^2}$
    * $|\vec{v}| = \sqrt{a^2\omega^2\sin^2(\omega t) + b^2\omega^2\cos^2(\omega t) + b^2}$
3.  **The Path Length Formula:** $s = \int_0^{t_0} |\vec{v}| dt$

*(Note: In the general case where $a \neq b$, this integral is very complex. However, in physics problems, we often look at the special case below.)*

---

**Step 4: Special Cases**
* **If $a = b$:** The ellipse becomes a perfect **Circle**. The speed becomes constant: $|\vec{v}| = \sqrt{a^2\omega^2 + b^2}$.
    * Path Length: $s = t_0 \cdot \sqrt{a^2\omega^2 + b^2}$
* **If $b = 0$ (for $z$):** The object never goes up. It just stays on the floor moving in an ellipse.
* **If $\omega = 0$:** The object doesn't spin; it just sits at $(a, 0)$ and moves straight up the $z$-axis.

---

**Step 5: Interactive Visualization**
You can use this tool to see how changing $a, b,$ and $\omega$ changes the "spiral":
