# NumPy - Introduction

**Tags:** #Python #NumPy #DataScience #LinearAlgebra

---

## What is NumPy?

**NumPy (Numerical Python)** is the fundamental numerical computing library for Python.

It provides:

- Fast numerical computations
- Efficient multidimensional arrays (`ndarray`)
- Linear algebra operations
- Mathematical functions
- Random number generation
- Statistical operations

---

## Why NumPy?

Python lists are not designed for large-scale numerical computation.

NumPy provides:

- Faster execution
- Lower memory usage
- Vectorized operations
- Optimized mathematical functions
- Linear algebra support

---

## Why is NumPy Important?

NumPy is the foundation of the Python Data Science ecosystem.

Many libraries are built on top of NumPy:

- Pandas
- SciPy
- Matplotlib
- Scikit-learn
- TensorFlow
- PyTorch

---

## Why is NumPy Fast?

Reasons:

- Written using optimized C backend
- Continuous memory allocation
- Homogeneous data types
- CPU cache friendly
- Vectorized operations

---

## Python Lists vs NumPy Arrays

| Python Lists | NumPy Arrays |
|--------------|--------------|
| Slow | Fast |
| High memory usage | Memory efficient |
| Stores Python objects | Stores raw numerical values |
| Uses Python loops | Uses vectorization |
| General-purpose | Numerical computing |

---

## NumPy Arrays

The primary data structure in NumPy is the **ndarray (N-dimensional Array).**

Supports:

- 1D Arrays
- 2D Arrays
- 3D Arrays
- N-Dimensional Arrays

---

## Types of Arrays

### Vector

- 1-D array
- Shape: `(n,)`

Example

```python
np.array([1,2,3,4])
```

---

### Matrix

- 2-D array
- Shape: `(rows, columns)`

Example

```python
np.array([
    [1,2],
    [3,4]
])
```

A matrix can have:

- One row `(1,n)`
- One column `(n,1)`

---

## Vectorization

**Definition**

Applying operations to an entire array without writing explicit loops.

Example

```python
arr * 2
```

Benefits:

- Faster
- Cleaner code
- Less error-prone

---

## Applications

- Machine Learning
- Deep Learning
- Computer Vision
- Medical Image Analysis
- Data Science
- Scientific Computing
- Remote Sensing
- GIS
- Robotics

---

## Key Takeaways

- NumPy = Numerical Python
- Foundation of Data Science in Python
- Uses `ndarray`
- Extremely fast
- Memory efficient
- Supports vectorization
- Provides Linear Algebra operations
- Used by almost every ML/DL library