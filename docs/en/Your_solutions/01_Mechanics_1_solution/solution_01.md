## Section 1: Mechanics I

---

### 1. Projectile Motion

Projectile motion happens when an object is thrown into the air and only gravity acts upon it. We break the movement into two separate parts: **horizontal** ($x$) and **vertical** ($y$).

**Given:**

* Initial velocity ($v_0$): $100$ m/s
* Launch angle ($\theta$): $37^\circ$
* Assume gravity ($g$): $9.8$ m/s$^2$

First, we find the starting speeds for each direction:

* **Horizontal speed ($v_{0x}$):** $100 \cdot \cos(37^\circ) \approx 100 \cdot 0.8 = \mathbf{80 \text{ m/s}}$
* **Vertical speed ($v_{0y}$):** $100 \cdot \sin(37^\circ) \approx 100 \cdot 0.6 = \mathbf{60 \text{ m/s}}$

#### a) Differential Equations of Motion

These equations describe how the position of the object changes over time based on the forces acting on it. Since we assume no air resistance, there is no force in the $x$ direction, and only gravity in the $y$ direction.

* **Horizontal ($x$):** There is no acceleration.

$$\frac{d^2x}{dt^2} = 0$$


* **Vertical ($y$):** Gravity pulls the object down.

$$\frac{d^2y}{dt^2} = -g$$



#### b) Time of Flight ($t_{total}$)

The object stays in the air until it hits the ground again (when $y = 0$). The time it takes to go up and come back down is:

* Formula: $t = \frac{2 \cdot v_{0y}}{g}$
* Calculation: $\frac{2 \cdot 60}{9.8} \approx \mathbf{12.24 \text{ seconds}}$

#### c) Maximum Height ($H$)

The object reaches its highest point when its vertical speed becomes zero for a split second.

* Formula: $H = \frac{v_{0y}^2}{2g}$
* Calculation: $\frac{60^2}{2 \cdot 9.8} = \frac{3600}{19.6} \approx \mathbf{183.67 \text{ meters}}$

#### d) Range ($R$)

The range is the total horizontal distance traveled. Since the horizontal speed ($80$ m/s) never changes, we just multiply it by the total time.

* Formula: $R = v_{0x} \cdot t_{total}$
* Calculation: $80 \cdot 12.24 \approx \mathbf{979.2 \text{ meters}}$

---

