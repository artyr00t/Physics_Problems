## 3. Path Intersection

In this problem, we are looking at two people (Alice and Bob) moving through space over time ($t$). We need to determine if they ever stand on the same spot at the same time.

**Alice's path:** $A(t) = (2 + t, 8 - 3t)$
**Bob's path:** $B(t) = (2t - 1, 2t + 2)$

### Step 1: Check for Collision

For a collision to occur, their $x$ positions must be equal **and** their $y$ positions must be equal at the exact same time ($t$).

1. **Set the x-coordinates equal:**
$2 + t = 2t - 1$
Subtract $t$ from both sides: $2 = t - 1$
Add $1$ to both sides: **$t = 3$**
2. **Check the y-coordinates at $t = 3$:**
* **Alice's $y$:** $8 - 3(3) = 8 - 9 = \mathbf{-1}$
* **Bob's $y$:** $2(3) + 2 = 6 + 2 = \mathbf{8}$



Since $-1 \neq 8$, they are at different heights when $t=3$. **They do not collide.**

### Step 2: Find the Minimum Distance

Since they don't collide, we want to find when they are closest to each other. We use the distance formula between their positions:
$D^2 = (x_B - x_A)^2 + (y_B - y_A)^2$

1. **Difference in $x$:** $(2t - 1) - (2 + t) = \mathbf{t - 3}$
2. **Difference in $y$:** $(2t + 2) - (8 - 3t) = \mathbf{5t - 6}$
3. **Square of Distance ($f(t)$):**
$f(t) = (t - 3)^2 + (5t - 6)^2$
$f(t) = (t^2 - 6t + 9) + (25t^2 - 60t + 36)$
$f(t) = 26t^2 - 66t + 45$

### Step 3: Find the Minimum ($t$)

We take the derivative and set it to zero:
$f'(t) = 52t - 66$
$52t = 66$
$t = \frac{66}{52} \approx \mathbf{1.27 \text{ seconds}}$

### Step 4: Calculate the Distance

Plug $t \approx 1.27$ back into the distance squared formula:
$f(1.27) = 26(1.27)^2 - 66(1.27) + 45 \approx 3.06$
Distance = $\sqrt{3.06} \approx \mathbf{1.75 \text{ meters}}$

**The Answer:** Alice and Bob do not collide. Their paths intersect spatially, but they reach the intersection at different times. They are closest to each other at **$t \approx 1.27$ seconds**, with a minimum distance of approximately **$1.75$ meters**.
