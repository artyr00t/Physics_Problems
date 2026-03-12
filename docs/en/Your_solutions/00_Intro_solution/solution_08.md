## 8. Definite Integrals

A **definite integral** is used to find the exact area between a curved line and the horizontal $x$-axis. Think of it as adding up an infinite number of tiny rectangles to fill the space.

Our function is: 

$$f(x) = \sin(x)$$


We want to find the area from **$x = 0$** to **$x = \pi$**.

### Step 1: Find the Anti-derivative

First, we need to find the function that, when differentiated, gives us $\sin(x)$.

* The derivative of $\cos(x)$ is $-\sin(x)$.
* Therefore, the "anti-derivative" (or integral) of $\sin(x)$ is **$-\cos(x)$**.

### Step 2: Apply the Boundaries

The "Fundamental Theorem of Calculus" says we plug the top number (the end) into our anti-derivative and subtract the bottom number (the start) plugged into it.

* **Top value ($\pi$):** $-\cos(\pi) = -(-1) = 1$
* **Bottom value ($0$):** $-\cos(0) = -(1) = -1$

### Step 3: Subtract

* (Value at $\pi$) - (Value at $0$)
* $1 - (-1) = 1 + 1 = \mathbf{2}$

**The Answer:** The total area under one "hump" of a sine wave (from 0 to $\pi$) is exactly **2**.
