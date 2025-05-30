
# Vectors II – Lecture Notes

---

## 1. Dot Product and Its Geometric Meaning

The **dot product** (also called scalar product) of two vectors **a** = (a₁, a₂) and **b** = (b₁, b₂) is:

$$
\vec{a} \cdot \vec{b} = a₁b₁ + a₂b₂
$$

### Geometric Interpretation:
$$
\vec{a} \cdot \vec{b} = |\vec{a}||\vec{b}|\cos(θ)
$$

Where:
- $θ$ is the angle between the vectors
- If dot product > 0 → acute angle
- If dot product = 0 → vectors are perpendicular
- If dot product < 0 → obtuse angle

---

## 2. Angle Between Vectors

Use the dot product formula:

$$
\cos(θ) = \frac{\vec{a} \cdot \vec{b}}{|\vec{a}||\vec{b}|}
$$

Solve for θ using inverse cosine.

---

## 3. Linearly Dependent vs. Independent Vectors

- **Dependent**: One vector is a scalar multiple of another.

$$
\vec{a} = k\vec{b}
$$
- **Independent**: Vectors are not scalar multiples; they span a plane or space.

This concept is crucial in linear algebra for solving vector equations and matrix rank.

---

## 4. Applications to Geometry: Triangles and Polygons

### Triangle using vectors:
To find side lengths and angles, use vectors between points.

- Side AB = $\vec{B} - \vec{A}$
- Use dot product to find angle between sides.

### Quadrilateral (e.g., square or rectangle):
- Check right angles using dot product = 0
- Use vector addition to verify closed shape

---

## Additional Tools:

- **Midpoint** of AB:

$$
M = \left(\frac{x₁ + x₂}{2}, \frac{y₁ + y₂}{2}\right)
$$

- **Distance** between two points A and B:

$$
d = \sqrt{(x₂ - x₁)^2 + (y₂ - y₁)^2}
$$

---

## Summary:

Vectors allow us to solve geometric problems efficiently by translating shapes and positions into algebraic forms. Understanding dot product and angles is crucial for deeper applications in physics and engineering.

---
