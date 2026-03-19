**6. Variable Velocity**

**An object's velocity is given by $v(t) = t^2 + 2t - 5$. If the object was at $x = 4$ at $t = 0$, what is its position and acceleration at time $t = 3$?**

---

**Step 1: Finding the Acceleration (The Push)**
Acceleration ($a$) is how much the velocity changes. To find it, we take the **Derivative** of the velocity formula. 
* **Rule:** $t^2$ becomes $2t$, and $2t$ becomes $2$. The $-5$ disappears because it's a constant.
* **Formula:** $a(t) = 2t + 2$

Now, we just plug in the time **$t = 3$**:
* $a(3) = 2(3) + 2 = 6 + 2 = \mathbf{8 \text{ m/s}^2}$



---

**Step 2: Finding the Position (The Location)**
Position ($x$) is the total distance covered. To find it, we go the opposite way and use the **Integral** of the velocity. 
* **Rule:** $t^n$ becomes $\frac{t^{n+1}}{n+1}$.
* **Integral of $v(t)$:** $\int (t^2 + 2t - 5) \, dt = \frac{t^3}{3} + t^2 - 5t + C$

The **$C$** is the starting point. The problem says at $t=0$, the object is at $x=4$. So, **$C = 4$**.
* **Full Position Formula:** $x(t) = \frac{t^3}{3} + t^2 - 5t + 4$



---

**Step 3: Calculating the Final Position at $t=3$**
Now, we put the number **$3$** into our position formula:
* $x(3) = \frac{3^3}{3} + (3)^2 - 5(3) + 4$
* $x(3) = \frac{27}{3} + 9 - 15 + 4$
* $x(3) = 9 + 9 - 15 + 4$
* $x(3) = 18 - 15 + 4 = \mathbf{7 \text{ meters}}$

---

**Conclusion:**
At exactly 3 seconds:
* **Acceleration:** The object is getting faster by **$8 \text{ m/s}^2$**.
* **Position:** The object is at the **$7\text{-meter}$** mark on the track.
