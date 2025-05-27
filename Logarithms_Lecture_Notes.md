
# Logarithms – Lecture Notes

---

## 1. Definition and Relationship to Exponentials

A **logarithm** answers the question: *To what exponent must the base be raised, to produce a given number?*

```
If b^x = y, then log_b(y) = x
```

Where:
- `b` is the base
- `x` is the exponent
- `y` is the result

### Example:
```
log_2(8) = 3 because 2^3 = 8
```

---

## 2. Laws of Logarithms

These are essential rules for simplifying and manipulating logarithmic expressions:

- **Product Rule**:
  ```
  log_b(M · N) = log_b(M) + log_b(N)
  ```

- **Quotient Rule**:
  ```
  log_b(M / N) = log_b(M) - log_b(N)
  ```

- **Power Rule**:
  ```
  log_b(M^k) = k · log_b(M)
  ```

---

## 3. Expanding and Compressing Log Expressions

### Expanding:
Use the laws to break a single logarithm into multiple terms.

Example:
```
log_2(8x^3) = log_2(8) + log_2(x^3) = 3 + 3log_2(x)
```

### Compressing:
Combine multiple logs into one.

Example:
```
log_b(x) + 2log_b(y) = log_b(xy^2)
```

---

## 4. Solving Logarithmic Equations

Steps:
1. Use laws of logarithms to simplify.
2. Rewrite in exponential form if needed.
3. Solve the resulting equation.

### Example:
```
log_3(x) = 4  →  3^4 = x  →  x = 81
```

More complex:
```
log_2(x) + log_2(x - 2) = 3
→ log_2(x(x - 2)) = 3
→ x(x - 2) = 8
→ x^2 - 2x - 8 = 0
→ x = 4 or x = -2 (Reject -2 because log of negative is undefined)
```

---

## 5. Graphical Representation of Logarithmic Functions

A typical log function:
```
f(x) = log_b(x)
```

### Characteristics:
- Domain: `(0, ∞)`
- Range: `(-∞, ∞)`
- Vertical Asymptote: `x = 0`
- Passes through `(1, 0)` (because log_b(1) = 0)

### Growth:
- If `b > 1`: Increasing function
- If `0 < b < 1`: Decreasing function

**Logs are only defined for positive real numbers.**

---

