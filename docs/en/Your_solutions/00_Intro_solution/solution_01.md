# Vector Algebra – Step by Step Solution

Given:

\[
\vec{a} = [2, 1, -3]
\]

\[
\vec{b} = [4, -2, 1]
\]

---

# (a) Magnitude of Each Vector

## Formula for Magnitude of a Vector

For a vector:

\[
\vec{v} = [x, y, z]
\]

The magnitude is:

\[
|\vec{v}| = \sqrt{x^2 + y^2 + z^2}
\]

---

## Magnitude of **a**

\[
|\vec{a}| = \sqrt{2^2 + 1^2 + (-3)^2}
\]

Step-by-step:

\[
= \sqrt{4 + 1 + 9}
\]

\[
= \sqrt{14}
\]

\[
|\vec{a}| = \sqrt{14}
\]

---

## Magnitude of **b**

\[
|\vec{b}| = \sqrt{4^2 + (-2)^2 + 1^2}
\]

Step-by-step:

\[
= \sqrt{16 + 4 + 1}
\]

\[
= \sqrt{21}
\]

\[
|\vec{b}| = \sqrt{21}
\]

---

# (b) Dot Product

## Formula for Dot Product

\[
\vec{a} \cdot \vec{b} = a_1b_1 + a_2b_2 + a_3b_3
\]

---

Substitute values:

\[
= (2)(4) + (1)(-2) + (-3)(1)
\]

Step-by-step:

\[
= 8 - 2 - 3
\]

\[
= 3
\]

\[
\vec{a} \cdot \vec{b} = 3
\]

---

# (c) Cross Product

## Formula for Cross Product

\[
\vec{a} \times \vec{b} =
\begin{vmatrix}
\mathbf{i} & \mathbf{j} & \mathbf{k} \\
a_1 & a_2 & a_3 \\
b_1 & b_2 & b_3
\end{vmatrix}
\]

---

Substitute values:

\[
=
\begin{vmatrix}
\mathbf{i} & \mathbf{j} & \mathbf{k} \\
2 & 1 & -3 \\
4 & -2 & 1
\end{vmatrix}
\]

---

### Expand the determinant

\[
= \mathbf{i}
\begin{vmatrix}
1 & -3 \\
-2 & 1
\end{vmatrix}
-
\mathbf{j}
\begin{vmatrix}
2 & -3 \\
4 & 1
\end{vmatrix}
+
\mathbf{k}
\begin{vmatrix}
2 & 1 \\
4 & -2
\end{vmatrix}
\]

---

### Compute each 2×2 determinant

First determinant:

\[
(1)(1) - (-3)(-2)
\]

\[
= 1 - 6
\]

\[
= -5
\]

---

Second determinant:

\[
(2)(1) - (-3)(4)
\]

\[
= 2 - (-12)
\]

\[
= 14
\]

---

Third determinant:

\[
(2)(-2) - (1)(4)
\]

\[
= -4 - 4
\]

\[
= -8
\]

---

### Substitute back

\[
= -5\mathbf{i} - 14\mathbf{j} - 8\mathbf{k}
\]

\[
\vec{a} \times \vec{b} = [-5, -14, -8]
\]

---

# (d) Angle Between the Vectors

## Formula

\[
\vec{a} \cdot \vec{b} = |\vec{a}| |\vec{b}| \cos\theta
\]

Solve for \( \cos\theta \):

\[
\cos\theta = \frac{\vec{a} \cdot \vec{b}}{|\vec{a}| |\vec{b}|}
\]

---

Substitute known values:

\[
\cos\theta = \frac{3}{\sqrt{14}\sqrt{21}}
\]

\[
= \frac{3}{\sqrt{294}}
\]

\[
\cos\theta = \frac{3}{\sqrt{294}}
\]

---

### Now find the angle

\[
\theta = \cos^{-1}\left(\frac{3}{\sqrt{294}}\right)
\]

Approximate value:

\[
\sqrt{294} \approx 17.15
\]

\[
\cos\theta \approx \frac{3}{17.15} \approx 0.175
\]

\[
\theta \approx 79.9^\circ
\]

---

# ✅ Final Answers

Magnitude:
\[
|\vec{a}| = \sqrt{14}
\]
\[
|\vec{b}| = \sqrt{21}
\]

Dot Product:
\[
\vec{a} \cdot \vec{b} = 3
\]

Cross Product:
\[
\vec{a} \times \vec{b} = [-5, -14, -8]
\]

Angle Between Them:
\[
\theta = \cos^{-1}\left(\frac{3}{\sqrt{294}}\right) \approx 79.9^\circ
\]
