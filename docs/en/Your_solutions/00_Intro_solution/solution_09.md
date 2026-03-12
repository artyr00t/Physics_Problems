## 9. Optimization Problem

Optimization is a method for finding the "best" version of something—in this case, the largest possible rectangle that can fit in a specific space.

We are placing a rectangle in the first quadrant (where $x$ and $y$ are positive) under the curve $y = 3 - x^2$.

### Step 1: Define the Area

A rectangle's area is its **width** multiplied by its **height**.

* **Width:** The distance along the bottom axis, which we call **$x$**.
* **Height:** The vertical distance up to the curve, which is defined by our function: **$3 - x^2$**.
* **Area ($A$):** $x \times (3 - x^2) = \mathbf{3x - x^3}$

### Step 2: Find the "Peak" Area

To find where the area is at its maximum, we use a derivative to see where the rate of change becomes zero.

* The derivative of $3x$ is $3$.
* The derivative of $-x^3$ is $-3x^2$.
* **$A'(x) = 3 - 3x^2$**

### Step 3: Solve for $x$

We set the derivative to zero to find the "turning point" of the area:

* $3 - 3x^2 = 0$
* $3 = 3x^2$
* $1 = x^2$
* **$x = 1$** (We ignore $-1$ because we are in the first quadrant).

### Step 4: Find the Height ($y$)

Now that we know the best width is $1$, we plug it back into the height formula:

* $y = 3 - (1)^2$
* **$y = 2$**

**The Answer:** To get the maximum area, the rectangle should have a **width of 1** and a **height of 2**. This gives a total area of $2$ units squared.
