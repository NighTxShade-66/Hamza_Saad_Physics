## Problem 1. Vector Algebra

Given:
$\vec{a}=[2,1,-3]$ and $\vec{b}=[4,-2,1]$.

---

### a) Magnitude of Each Vector

**Magnitude in 3D:**

$$
|\vec{v}| = \sqrt{v_x^2 + v_y^2 + v_z^2}.
$$

**For $\vec{a}$:**

$$
|\vec{a}| = \sqrt{2^2 + 1^2 + (-3)^2}
= \sqrt{4 + 1 + 9}
= \sqrt{14}.
$$

**For $\vec{b}$:**

$$
|\vec{b}| = \sqrt{4^2 + (-2)^2 + 1^2}
= \sqrt{16 + 4 + 1}
= \sqrt{21}.
$$

**Result:**

$$
|\vec{a}| = \sqrt{14}, \quad |\vec{b}| = \sqrt{21}.
$$

---

### b) Dot Product $\vec{a} \cdot \vec{b}$

**Dot Product Formula:**

$$
\vec{a} \cdot \vec{b} = a_x b_x + a_y b_y + a_z b_z.
$$

**Calculation:**

$$
\vec{a} \cdot \vec{b} = (2)(4) + (1)(-2) + (-3)(1)
= 8 - 2 - 3
= 3.
$$

**Result:**

$$
\vec{a} \cdot \vec{b} = 3.
$$

---

### c) Cross Product $\vec{a} \times \vec{b}$

**Cross Product Formula:**

$$
\vec{a} \times \vec{b} =
\begin{vmatrix}
\hat{i} & \hat{j} & \hat{k} \\
2 & 1 & -3 \\
4 & -2 & 1
\end{vmatrix}.
$$

**Expanding the Determinant:**

$$
\vec{a} \times \vec{b} = \hat{i}(1 \cdot 1 - (-3) \cdot (-2)) - \hat{j}(2 \cdot 1 - (-3) \cdot 4) + \hat{k}(2 \cdot (-2) - 1 \cdot 4).
$$

**Component-wise Calculation:**

- $\hat{i}$-component: $1 \cdot 1 - (-3) \cdot (-2) = 1 - 6 = -5$.
- $\hat{j}$-component: $-(2 \cdot 1 - (-3) \cdot 4) = -(2 + 12) = -14$.
- $\hat{k}$-component: $2 \cdot (-2) - 1 \cdot 4 = -4 - 4 = -8$.

**Result:**

$$
\vec{a} \times \vec{b} = [-5, -14, -8].
$$

---

### d) Angle Between $\vec{a}$ and $\vec{b}$

**Angle Formula:**

$$
\cos \theta = \frac{\vec{a} \cdot \vec{b}}{|\vec{a}| |\vec{b}|}.
$$

**Substitute Values:**

$$
\cos \theta = \frac{3}{\sqrt{14} \cdot \sqrt{21}}
= \frac{3}{\sqrt{294}}
= \frac{3}{3\sqrt{33}}
= \frac{1}{\sqrt{33}}.
$$

**Final Angle:**

$$
\theta = \arccos\left(\frac{1}{\sqrt{33}}\right).
$$
