**1. Projectile Motion**

**A projectile is fired from the ground with an initial velocity of 100 m/s at an angle of 37° above the horizontal. Assume no air resistance. Derive the differential equations of motion in the horizontal and vertical directions. Determine the time of flight. Determine the maximum height. Determine the range.**

---

**Step 1: Splitting the Speed (Velocity Components)**
When you shoot the ball at an angle, it goes **forward** and **up** at the same time. We need to find these two speeds separately:
* **Forward Speed ($v_{0x}$):** $100 \times \cos(37^\circ) = 100 \times 0.8 = 80 \text{ m/s}$
* **Upward Speed ($v_{0y}$):** $100 \times \sin(37^\circ) = 100 \times 0.6 = 60 \text{ m/s}$



**Step 2: The Rules of the Move (Differential Equations)**
This part is just a fancy way of saying: "Is anything pushing or pulling the ball?"
* **Side-to-side ($x$):** There is no wind or air pushing it. So, the acceleration is zero. 
    $$\frac{d^2x}{dt^2} = 0$$
* **Up-and-down ($y$):** Gravity is pulling it down. So, the acceleration is $-g$.
    $$\frac{d^2y}{dt^2} = -g$$

**Step 3: Total Time in the Air (Time of Flight)**
Imagine you throw a ball up at $60 \text{ m/s}$. Gravity ($9.8 \text{ m/s}^2$) takes about $6$ seconds to stop it at the top, and another $6$ seconds to bring it back down.
* **Formula:** $T = \frac{2 \times \text{Upward Speed}}{g}$
* **Calculation:** $T = \frac{2 \times 60}{9.8} \approx \mathbf{12.24 \text{ seconds}}$

**Step 4: The Highest Point (Maximum Height)**
This is how high the ball goes before it starts falling. 
* **Formula:** $H = \frac{(\text{Upward Speed})^2}{2g}$
* **Calculation:** $H = \frac{60 \times 60}{2 \times 9.8} = \frac{3600}{19.6} \approx \mathbf{183.67 \text{ meters}}$



**Step 5: How Far It Goes (Range)**
To find the total distance, we take the **Forward Speed** (which never changes) and multiply it by the **Total Time** it was in the air.
* **Formula:** $R = \text{Forward Speed} \times \text{Total Time}$
* **Calculation:** $R = 80 \times 12.24 \approx \mathbf{979.2 \text{ meters}}$
