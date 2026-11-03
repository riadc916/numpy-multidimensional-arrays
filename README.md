# Computation with NumPy & N-Dimensional Arrays

This project covers core numerical computing concepts using Python's **NumPy** library, focusing on multi-dimensional array operations, linear algebra, broadcasting, and low-level digital image processing.

---

## Topics Covered
- **NumPy ndarray Fundamentals:** Vector (1D), Matrix (2D), and Tensor (3D/nD) structures, attributes (`.shape`, `.ndim`).
- **Array Slicing & Indexing:** Multi-axis selection, sub-setting, stepping, and array reversal (`np.flip`, `[::-1]`).
- **Mathematical Array Generation:** Generating evenly spaced sequences (`np.arange()`, `np.linspace()`) and random tensors (`np.random.random()`).
- **Linear Algebra & Broadcasting:** Element-wise vector arithmetic, scalar operations via broadcasting, and matrix multiplication using `@` and `np.matmul()`.
- **Digital Image Manipulation:**
  - Loading and interpreting image files as 3D arrays $(H \times W \times C)$.
  - Grayscale conversion using luminance weighting:
    $$Y = 0.2126R + 0.7152G + 0.0722B$$
  - Image inversion (solarization) via scalar broadcasting (`255 - img_array`).
  - Spatial image transformation (rotating and flipping pixel tensors).

---

## Tech Stack & Tools
- **Language:** Python
- **Libraries:** NumPy, Matplotlib, SciPy, Pillow (PIL)
- **Environment:** Google Colaboratory / Jupyter Notebook

---

## How to Run Locally
1. Clone the repository:
   ```bash
   git clone [https://github.com/riadc916/numpy-multidimensional-arrays.git](https://github.com/riadc916/numpy-multidimensional-arrays.git)
   cd numpy-multidimensional-arrays
