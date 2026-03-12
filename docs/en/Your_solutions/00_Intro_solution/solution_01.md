## 1. Vector Algebra

Think of a **vector** as an arrow in space. It has a specific **length** (magnitude) and points in a specific **direction**. In 3D space, we describe it using three numbers $[x, y, z]$.

### a) Magnitude (The Length)

To find how long the arrow is, we use a 3D version of the Pythagorean theorem. You square each number, add them together, and then take the square root.

* **For $\vec{a} = [2, 1, -3]$:** * $2^2 = 4$
* $1^2 = 1$
* $(-3)^2 = 9$
* $4 + 1 + 9 = 14$. So, the length is **$\sqrt{14}$** (about **3.74**).


* **For $\vec{b} = [4, -2, 1]$:**
* $4^2 = 16$
* $(-2)^2 = 4$
* $1^2 = 1$
* $16 + 4 + 1 = 21$. So, the length is **$\sqrt{21}$** (about **4.58**).



### b) Dot Product (Matching Directions)

The dot product results in a single **number**, not a vector. It tells us how much two vectors "line up" with each other. We multiply the matching parts and add them up.

* $(2 \times 4) + (1 \times -2) + (-3 \times 1)$
* $8 + (-2) + (-3) = \mathbf{3}$

### c) Cross Product (The Perpendicular Vector)

The **Cross Product** is unique because it takes two vectors and creates a **third vector** that is perfectly perpendicular (at a 90° angle) to both of them.

To calculate it, we use a 3D grid called a **matrix**. We place the unit vectors ($i, j, k$) on top, and our vector numbers underneath:

$$\vec{a} \times \vec{b} = \begin{vmatrix} \mathbf{i} & \mathbf{j} & \mathbf{k} \\ 2 & 1 & -3 \\ 4 & -2 & 1 \end{vmatrix}$$

We solve this by breaking it into three smaller "2x2" calculations:

#### Step 1: Solving for $i$ (The X-component)

Ignore the $i$ column and the top row. Look at the remaining four numbers:


$$\begin{vmatrix} 1 & -3 \\ -2 & 1 \end{vmatrix}$$


Multiply diagonally: $(1 \times 1) - (-3 \times -2) = 1 - 6 = \mathbf{-5}$

#### Step 2: Solving for $j$ (The Y-component)

**Important:** In math, the middle term ($j$) always gets a minus sign flipped in front of it. Ignore the $j$ column:


$$\begin{vmatrix} 2 & -3 \\ 4 & 1 \end{vmatrix}$$


Multiply diagonally: $(2 \times 1) - (-3 \times 4) = 2 - (-12) = 14$
Now, apply the **negative rule**: $\mathbf{-14}$

#### Step 3: Solving for $k$ (The Z-component)

Ignore the $k$ column:


$$\begin{vmatrix} 2 & 1 \\ 4 & -2 \end{vmatrix}$$


Multiply diagonally: $(2 \times -2) - (1 \times 4) = -4 - 4 = \mathbf{-8}$

---

### The Result

When we put those three parts together, we get our new vector:
**$\vec{a} \times \vec{b} = [-5, -14, -8]$**

This vector points in a direction that is perpendicular to the "floor" created by the first two vectors.

### d) The Angle

We use the results from the dot product and the magnitudes to find the angle $\theta$ between the two arrows.

* Formula: $\cos(\theta) = \frac{\text{Dot Product}}{\text{Magnitude A} \times \text{Magnitude B}}$
* $\cos(\theta) = \frac{3}{\sqrt{14} \times \sqrt{21}} \approx 0.175$
* $\theta = \arccos(0.175) \approx \mathbf{79.9^\circ}$

---
