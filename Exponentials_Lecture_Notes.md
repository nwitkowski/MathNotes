
# Exponentials – Lecture Notes

---

## 1. Definition of Exponential Functions

An **exponential function** is a mathematical function of the form:


$f(x) = a · b^x$


- `a` is a constant (initial value).
- `b` is the base of the exponential and must be positive (`b > 0`, `b ≠ 1`).
- `x` is the exponent (typically representing time or steps).

### Key Properties:
- If `b > 1`: **Exponential Growth**
- If `0 < b < 1`: **Exponential Decay**

---

## 2. Simple vs. Compound Interest Formulas

### ✅ Simple Interest

Used when interest is calculated only on the original amount (principal):

$I = P · r · t$

- `I`: interest earned
- `P`: principal (starting amount)
- `r`: annual interest rate (decimal)
- `t`: time in years

To find the total amount:

$A = P + I = P(1 + rt)$

---

### ✅ Compound Interest

Used when interest is added to the principal, so future interest earns interest too:


$A = P · (1 + \\frac{r}{n})^{nt}$

- `A`: total amount after time `t`
- `P`: principal
- `r`: annual interest rate (decimal)
- `n`: number of times interest is compounded per year
- `t`: time in years

If interest is compounded **annually**, then `n = 1`:

$A = P · (1 + r)^{t}$


---

## 3. Graphing Exponential Growth and Decay

### Exponential Growth Example:

$f(x) = 2^x$

- The graph rises rapidly as `x` increases.
- Passes through `(0, 1)` because any number to the power of 0 is 1.

### Exponential Decay Example:

$f(x) = (1/2)^x$

- The graph decreases as `x` increases.
- It approaches 0 but never touches the x-axis (asymptote).

### Characteristics of Both:
- **Domain:** `(-∞, ∞)`
- **Range:** `(0, ∞)`
- **Horizontal Asymptote:** `y = 0`

---

## 4. Solving Exponential Word Problems

### Steps:
1. Identify the initial value, rate, and time.
2. Choose the correct formula (simple/compound interest, population growth, etc.).
3. Plug in known values.
4. Solve for the unknown (often `A`, `t`, or `P`).

### Example – Compound Interest:
> You invest $1,000 at an annual interest rate of 5% compounded yearly. How much will you have after 3 years?

$$A = 1000 · (1 + 0.05)^3 = 1000 · 1.157625 = \$1157.63$$
