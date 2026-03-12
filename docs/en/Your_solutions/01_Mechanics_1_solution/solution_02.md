## 2. Range Optimization

To find the best angle for the longest distance (the maximum range), we look at the **Range formula**:


$$R(\theta) = \frac{v_0^2 \sin(2\theta)}{g}$$

In this formula, $v_0$ (the initial speed) and $g$ (gravity) are constants—they stay the same. This means the range depends entirely on the behavior of the **$\sin(2\theta)$** part.

### Method 1: The Maximum Value of Sine

Mathematically, the **Sine** of any angle can never be larger than **1**.

1. To reach the maximum range, we need $\sin(2\theta)$ to be as large as possible.
2. We know that $\sin(90^\circ) = 1$.
3. Therefore, the value inside the sine must be $90^\circ$:

$$2\theta = 90^\circ$$


4. Solving for $\theta$:

$$\mathbf{\theta = 45^\circ}$$



### Method 2: Analytical Proof (Calculus)

To find the exact "peak" of a function, we take the **derivative** and set it to zero. This tells us where the slope of the range curve is flat (the highest point).

1. **Find the derivative** of $R$ with respect to $\theta$:

$$\frac{dR}{d\theta} = \frac{v_0^2}{g} \cdot (2\cos(2\theta))$$


2. **Set the derivative to zero** to find the maximum:

$$\frac{v_0^2}{g} \cdot 2\cos(2\theta) = 0$$


3. Since the speed and gravity aren't zero, **$\cos(2\theta)$** must be the part that equals $0$.
4. The cosine of an angle is $0$ when the angle is $90^\circ$:

$$2\theta = 90^\circ$$


5. Dividing by 2:

$$\mathbf{\theta = 45^\circ}$$



**The Answer:** Both methods show that a launch angle of **$45^\circ$** creates the perfect balance between height and forward speed, resulting in the maximum possible range.
