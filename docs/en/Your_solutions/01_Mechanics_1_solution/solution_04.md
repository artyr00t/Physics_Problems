**4. Vector Calculus**

**The position of an object is given by $\vec{r}(t) = (3t^2)\hat{i} + (5t - 8t^2)\hat{j}$. Find the object's velocity and acceleration vectors as a function of time.**

---

**Step 1: Understanding the Map (Position)**
The formula $\vec{r}(t)$ is like a GPS coordinate that tells you where the object is at any second ($t$). 
* **$\hat{i}$** is the side-to-side (Horizontal) part.
* **$\hat{j}$** is the up-and-down (Vertical) part.

**Step 2: Finding the Speed (Velocity)**
To find the **Velocity** ($\vec{v}$), we look at how the position is changing. In math, we use a trick called the **Derivative**. 
* Basic Rule: If you have $t^n$, it becomes $n \cdot t^{n-1}$. 
* If you have just $t$, it becomes $1$. 
* If you have a plain number, it becomes $0$.

**Calculating Velocity ($\vec{v}$):**
* **Horizontal ($\hat{i}$):** The derivative of $3t^2$ is $2 \times 3t = \mathbf{6t}$.
* **Vertical ($\hat{j}$):** The derivative of $5t$ is $5$, and the derivative of $-8t^2$ is $-16t$. So, $\mathbf{5 - 16t}$.

**Velocity Vector:**
$$\vec{v}(t) = (6t)\hat{i} + (5 - 16t)\hat{j}$$



**Step 3: Finding the Push (Acceleration)**
To find the **Acceleration** ($\vec{a}$), we look at how the **Velocity** is changing. We just do the derivative trick one more time on our velocity answer.

**Calculating Acceleration ($\vec{a}$):**
* **Horizontal ($\hat{i}$):** The derivative of $6t$ is just **$6$**.
* **Vertical ($\hat{j}$):** The derivative of $5$ (plain number) is $0$, and the derivative of $-16t$ is **$-16$**.

**Acceleration Vector:**
$$\vec{a}(t) = (6)\hat{i} + (-16)\hat{j}$$



**Conclusion:**
* **Position:** Where it is.
* **Velocity:** How fast it's moving ($6t$ forward, $5-16t$ vertical).
* **Acceleration:** The constant push it feels ($6$ units right, $16$ units down).
