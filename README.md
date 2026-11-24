# 📊 Vectors & Matrices | Linear Algebra with Python

A practical **Linear Algebra and Mathematics project** demonstrating vector operations, matrix calculations, geometric transformations, and eigen-decomposition using **Python, NumPy, and Pandas**.

This repository contains a Jupyter Notebook with hands-on implementations and a theory PDF covering the mathematical concepts behind the practical work.

---

## 📁 Project Files

| File | Description |
|---|---|
| `Practical_PR_4.ipynb` | Python notebook implementing vector and matrix operations on student score data |
| `Part A - Theory of Vectors & Matrices.pdf` | Theory notes covering vectors, norms, dot/cross products, projections, matrices, determinants, geometry, eigenvalues, and covariance |

---

## 🎯 Project Objective

The objective of this practical is to understand how mathematical concepts from **Linear Algebra** can be represented and computed using Python libraries.

The notebook uses a sample dataset containing marks of five students across three subjects:

- Mathematics
- Statistics
- Python

The data is converted into a NumPy array and used to perform the required calculations.

---

## 🧰 Tools & Technologies

- **Python**
- **NumPy** — numerical and linear algebra operations
- **Pandas** — tabular data creation and manipulation
- **Jupyter Notebook** — interactive execution and documentation

---

## 📚 Topics Covered

### Part A — Vector & Matrix Fundamentals
- Representing each student's subject scores as a vector
- L1 (Manhattan) norm
- L2 (Euclidean) norm
- Dot product between student score vectors
- Cross product for 3D vectors
- Vector projection

### Part B — Matrix Operations
- Creating a students × subjects matrix
- Matrix addition
- Matrix multiplication
- Matrix transpose
- Matrix inverse (when applicable)
- Determinant calculation

### Part C — Linear Transformations & Geometry
- Line, plane, and hyperplane concepts
- Linear transformation using matrix multiplication
- Dimensionality: 2D, 3D, and higher-dimensional data

### Part D — Eigenvalues & Decomposition
- Covariance matrix of subject scores
- Eigenvalues and eigenvectors
- Sorting eigenvalues and corresponding eigenvectors in descending order

---

## 🧪 Practical Dataset

The notebook creates a small sample dataset directly in Python.

| Student | Mathematics | Statistics | Python |
|---|---:|---:|---:|
| S1 | 80 | 75 | 90 |
| S2 | 65 | 70 | 60 |
| S3 | 90 | 85 | 95 |
| S4 | 55 | 60 | 65 |
| S5 | 75 | 80 | 70 |

**Dataset dimensions:** 5 students × 3 subjects

---

## ⚙️ Setup & Installation

### 1. Clone the repository

```bash
git clone <your-repository-url>
cd <repository-folder>
```

### 2. Install the required libraries

```bash
pip install numpy pandas jupyter
```

### 3. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open `Practical_PR_4.ipynb` and run the notebook cells in order.

---

## 💻 Key Code Examples

### Convert DataFrame to NumPy Array

```python
X = DF.to_numpy()
```

### Calculate L1 and L2 Norms

```python
L1 = np.linalg.norm(S1, ord=1)
L2 = np.linalg.norm(S1, ord=2)
```

### Dot Product

```python
Dot = np.dot(S1, S2)
```

### Cross Product

```python
Cross = np.cross(S1, S2)
```

### Matrix Multiplication

```python
Multiplication = X.T @ X
```

### Covariance Matrix and Eigen-Decomposition

```python
Covariance = np.cov(X, rowvar=False)

Eigenvalues, Eigenvectors = np.linalg.eigh(Covariance)
```

---

## 📈 Learning Outcomes

After completing this project, learners can:

- Represent structured data as vectors and matrices
- Calculate vector magnitude using L1 and L2 norms
- Measure vector alignment using the dot product
- Understand cross products and vector projections
- Perform core matrix operations with NumPy
- Apply matrix transformations to vectors
- Calculate covariance matrices
- Compute and interpret eigenvalues and eigenvectors
- Build mathematical foundations for **Data Science, Machine Learning, and PCA**

---

## 🔗 Connection to Data Science & Machine Learning

These concepts are foundational for several data science techniques:

- **Vector operations** — similarity and mathematical representation of data
- **Matrix multiplication** — transformations and model computations
- **Covariance matrix** — understanding relationships between features
- **Eigen-decomposition** — mathematical foundation of Principal Component Analysis (PCA)
- **Dimensionality reduction** — representing high-dimensional data in a lower-dimensional space

---

## 👨‍💻 Author

**Harshit Dara**  
BCA Student | Aspiring Data Analyst

---

## ⭐ Support

If you find this project useful for learning Linear Algebra with Python, consider giving the repository a ⭐ on GitHub.
