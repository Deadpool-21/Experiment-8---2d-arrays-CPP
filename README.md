# 2D Arrays in C++

## **AIM**

Understand the concept and operations of a 2D matrix in C++.

## **Software Used**

* Visual Studio Code (VS Code)

---

## **Theory**

A **matrix** is a rectangular arrangement of numbers, symbols, or expressions in rows and columns.
In programming, a matrix is typically implemented using a **two-dimensional (2D) array**, which stores data in a grid-like structure for quick access and manipulation.

---

## **Importance of Matrices**

* **Engineering:** Circuit parameters, stress–strain relationships, transformations.
* **Computer Science:** Data tables, images, graphs.
* **Mathematics:** Solving systems of linear equations, transformations, statistical analysis.
* **Physics:** Modeling physical systems (quantum states, kinematics).
* **Data Science:** Datasets, transformations, correlations.

---

## **Properties of Matrices**

* **Order:** Defined by rows *(m)* × columns *(n)*.
* **Square Matrix:** Rows = Columns.
* **Diagonal Elements:** Elements where row index = column index.
* **Symmetric Matrix:** Equal to its transpose.
* **Sparse Matrix:** Contains mostly zeros (optimized storage).

---

## **Common Matrix Operations**

1. **Matrix Addition**

   * Add corresponding elements of two matrices (same order).
2. **Matrix Multiplication**

   * Dot product of rows (Matrix A) and columns (Matrix B).
   * Valid when columns in A = rows in B.
3. **Transpose**

   * Swap rows and columns.
4. **Diagonal Operations**

   * Sum or multiply main diagonal elements.

---

## **Relevance in Programming**

Matrices are used in:

* Image/video processing (pixels as matrix).
* Encryption and security algorithms.
* Neural network weights representation.
* 3D modeling and CAD.
* Network analysis and graph theory.

---

## **Algorithms**

### 1. General 2D Array Input/Output

```
1. Start
2. Declare 2D array
3. Input each element
4. Display in matrix form
5. Stop
```

### 2. Matrix Addition

```
1. Start
2. Input dimensions (must match)
3. Input elements of Matrix A & Matrix B
4. Add corresponding elements → Result Matrix
5. Display Result Matrix
6. Stop
```

### 3. Matrix Multiplication

```
1. Start
2. Input dimensions (cols of A = rows of B)
3. Input both matrices
4. For each result element: sum(row × column products)
5. Display Result Matrix
6. Stop
```

### 4. Transpose

```
1. Start
2. Input rows & columns
3. Place element (i, j) → (j, i) in transpose matrix
4. Display transpose
5. Stop
```

### 5. Diagonal Operations

```
1. Start
2. Input square matrix
3. Loop where i = j (main diagonal)
4. Sum or multiply these elements
5. Display result
6. Stop
```

---

## **Conclusion**

Matrices are more than just static data holders—they are **powerful tools** for representing relationships, modeling systems, and performing transformations in science, technology, and engineering.
Mastering both the **mathematical concepts** and **computational implementation** ensures the ability to efficiently solve complex problems in areas such as **image processing, machine learning, cryptography, and scientific simulations**.

