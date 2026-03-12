## 10. Infinite Series

This problem tracks the journey of an ant moving in four directions. To find the final "resting point," we treat the horizontal movement (East/West) and the vertical movement (North/South) as two separate math problems.

### The Horizontal Position ($x$)

The ant moves East (positive) and West (negative) in a repeating pattern:

* Move 1: +1 meter
* Move 3: -1/3 meter
* Move 5: +1/5 meter
* **The Series:** $1 - 1/3 + 1/5 - 1/7 + \dots$

This is a famous mathematical pattern called the **Leibniz series**. It is known that if you continue this pattern forever, the sum perfectly equals **$\frac{\pi}{4}$** (approximately **0.785**).

### The Vertical Position ($y$)

The ant moves North (positive) and South (negative) in a similar way:

* Move 2: +1/2 meter
* Move 4: -1/4 meter
* Move 6: +1/6 meter
* **The Series:** $1/2 - 1/4 + 1/6 - 1/8 + \dots$

To solve this, we can factor out a $1/2$ from everything:

* $1/2 \times (1 - 1/2 + 1/3 - 1/4 + \dots)$
* The part inside the parentheses is the **alternating harmonic series**, which equals the natural log of 2, written as **$\ln(2)$**.
* So, the final vertical position is **$\frac{\ln(2)}{2}$** (approximately **0.347**).

**The Answer:** The ant eventually stops at the coordinate **$(\frac{\pi}{4}, \frac{\ln(2)}{2})$**, which is roughly **(0.785, 0.347)**. Even though the ant keeps moving forever, the steps get so small that it never leaves this specific spot.
