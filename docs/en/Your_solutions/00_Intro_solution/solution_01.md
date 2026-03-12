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

Unlike the dot product, the cross product creates a **new vector**. This new vector is special because it stands perfectly upright (perpendicular) to both original vectors.

* To calculate it, we use a specific pattern (matrix determinant):
* $x = (1 \times 1) - (-3 \times -2) = 1 - 6 = \mathbf{-5}$
* $y = -[(2 \times 1) - (-3 \times 4)] = -(2 + 12) = \mathbf{-14}$
* $z = (2 \times -2) - (1 \times 4) = -4 - 4 = \mathbf{-8}$


* **Result:** **$[-5, -14, -8]$**

### d) The Angle

We use the results from the dot product and the magnitudes to find the angle $\theta$ between the two arrows.

* Formula: $\cos(\theta) = \frac{\text{Dot Product}}{\text{Magnitude A} \times \text{Magnitude B}}$
* $\cos(\theta) = \frac{3}{\sqrt{14} \times \sqrt{21}} \approx 0.175$
* $\theta = \arccos(0.175) \approx \mathbf{79.9^\circ}$

---
