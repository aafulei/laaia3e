# Linear Algebra and Its Applications

*Third Edition (2003)*

*David C. Lay*

## At a Glance

| Chapter                                   | Basic Sections | Advanced Sections | Theorems |
| ----------------------------------------- | -------------- | ----------------- | -------- |
| 1. Linear Equations in Linear Algebra     | 8              | 2                 | 12       |
| 2. Matrix Algebra                         | 6              | 3                 | 15       |
| 3. Determinants                           | 2              | 1                 | 10       |
| 4. Vector Spaces                          | 7              | 2                 | 18       |
| ***First Half***                          | ***23***       | ***8***           | ***55*** |
| 5. Eigenvalues and Eigenvectors           | 4              | 4                 |  9       |
| 6. Orthogonality and Least Squares        | 6              | 2                 | 17       |
| 7. Symmetric Matrices and Quadratic Forms | 4              | 1                 | 10       |
| ***Second Half***                         | ***14***       | ***7***           | ***36*** |
| **SUM**                                   | **37**         | **15**            | **91**   |

- First Half

  - Chapter 1. Linear Equations in Linear Algebra
  - Chapter 2. Matrix Algebra
  - Chapter 3. Determinants
  - Chapter 4. Vector Spaces

- Second Half

  - Chapter 5. Eigenvalues and Eigenvectors
  - Chapter 6. Orthogonality and Least Squares
  - Chapter 7. Symmetric Matrices and Quadratic Forms

## Contents

- **Chapter 1. Linear Equations in Linear Algebra**

  - 1.1 Systems of Linear Equations
  - 1.2 Row Reduction and Echelon Forms
  - 1.3 Vector Equations
  - 1.4 The Matrix Equation Ax = b
  - 1.5 Solution Sets of Linear Systems
  - 1.6 Applications of Linear Systems \*
  - 1.7 Linear Independence
  - 1.8 Introduction to Linear Transformations
  - 1.9 The Matrix of a Linear Transformation
  - 1.10 Linear Models in Business, Science, and Engineering \*

- **Chapter 2. Matrix Algebra**

  - 2.1 Matrix Operations
  - 2.2 The Inverse of a Matrix
  - 2.3 Characterizations of Invertible Matrices
  - 2.4 Partitioned Matrices
  - 2.5 Matrix Factorizations \*
  - 2.6 The Leontief Input–Output Model \*
  - 2.7 Applications to Computer Graphics \*
  - 2.8 Subspaces of R^n
  - 2.9 Dimension and Rank

- **Chapter 3. Determinants**

  - 3.1 Introduction to Determinants
  - 3.2 Properties of Determinants
  - 3.3 Cramer's Rule, Volume, and Linear Transformations \*

- **Chapter 4. Vector Spaces**

  - 4.1 Vector Spaces and Subspaces
  - 4.2 Null Spaces, Column Spaces, and Linear Transformations
  - 4.3 Linearly Independent Sets; Bases
  - 4.4 Coordinate Systems
  - 4.5 The Dimension of a Vector Space
  - 4.6 Rank
  - 4.7 Change of Basis
  - 4.8 Applications to Difference Equations \*
  - 4.9 Applications to Markov Chains \*

- **Chapter 5. Eigenvalues and Eigenvectors**

  - 5.1 Eigenvectors and Eigenvalues
  - 5.2 The Characteristic Equation
  - 5.3 Diagonalization
  - 5.4 Eigenvectors and Linear Transformations
  - 5.5 Complex Eigenvalues \*
  - 5.6 Discrete Dynamical Systems \*
  - 5.7 Applications to Differential Equations \*
  - 5.8 Iterative Estimates for Eigenvalues \*

- **Chapter 6. Orthogonality and Least Squares**

  - 6.1 Inner Product, Length, and Orthogonality
  - 6.2 Orthogonal Sets
  - 6.3 Orthogonal Projections
  - 6.4 The Gram–Schmidt Process
  - 6.5 Least-Squares Problems
  - 6.6 Applications to Linear Models \*
  - 6.7 Inner Product Spaces
  - 6.8 Applications of Inner Product Spaces \*

- **Chapter 7. Symmetric Matrices and Quadratic Forms**

  - 7.1 Diagonalization of Symmetric Matrices
  - 7.2 Quadratic Forms
  - 7.3 Constrained Optimization
  - 7.4 The Singular Value Decomposition
  - 7.5 Applications to Image Processing and Statistics \*

*Sections with a \* are advanced sections.*

## Chapter 1. Linear Equations in Linear Algebra

| Basic Sections | Advanced Sections | Theorems |
| -------------- | ----------------- | -------- |
| 8              | 2                 | 12       |

### Basic Sections

  - 1.1 Systems of Linear Equations
  - 1.2 Row Reduction and Echelon Forms
  - 1.3 Vector Equations
  - 1.4 The Matrix Equation Ax = b
  - 1.5 Solution Sets of Linear Systems
  - 1.7 Linear Independence
  - 1.8 Introduction to Linear Transformations
  - 1.9 The Matrix of a Linear Transformation

### Advanced Sections

  - 1.6 Applications of Linear Systems
  - 1.10 Linear Models in Business, Science, and Engineering

### Definitions

- echelon form
- pivot position, pivot column
- subset of `R^n` spanned by vectors
- linearly independent, linearly dependent
- linear transformation
- mapping onto
- one-to-one mapping

### Theorems

1. uniqueness of the reduced echelon form
2. existence and uniqueness theorem
3. same solution set for a matrix equation and a vector equation
4. equivalent statements for columns of **b** span `R^m`
5. A(u+v) = Au + Av; A(cu) = c(Au)
6. solution set of Ax = b
7. characterization of linearly dependent sets
8. a set has more vectors than number of vector entries ==>  linearly dependent
9. zero vector in a vector set ==> linearly dependent
10. there exists a unique matrix for any linear transaformation
11. linear transformation is one-to-to if and only if T(x) = 0 has only the trivial solution
12. on-to and one-to-one mappings of linear transformations

## Chapter 2. Matrix Algebra

| Basic Sections | Advanced Sections | Theorems |
| -------------- | ----------------- | -------- |
| 6              | 3                 | 15       |

### Basic Sections

  - 2.1 Matrix Operations
  - 2.2 The Inverse of a Matrix
  - 2.3 Characterizations of Invertible Matrices
  - 2.4 Partitioned Matrices
  - 2.8 Subspaces of R^n
  - 2.9 Dimension and Rank

### Advanced Sections

  - 2.5 Matrix Factorizations
  - 2.6 The Leontief Input–Output Model
  - 2.7 Applications to Computer Graphics

### Definitions

### Theorems

1. matrix arithmetics: addition and scalar multiplication
2. matrix arithmetics: multiplication
3. matrix arithmetics: transpose
4. invertibility of a 2x2 matrix
5. A is an invertible nxn matrix ===> for any b, Ax = b has unique solution
6. matrix arithmetics: inverse
7. invertibility of an nxn matrix
8. the invertible matrix theorem (12 statements, from a. to l.)
9. invertibility of a linear transformation from Rn to Rn
10. column-row expansion of AB
11. solution of production equation \*
12. null space of an mxn matrix
13. pivot columns of A form a basis for its column space
14. the rank theorem: rank A + dim Nul A = n
15. the basis theorem

+. the invertible matrix theorem continued (6 more statements, from m. to r.)


## Chapter 3. Determinants

| Basic Sections | Advanced Sections | Theorems |
| -------------- | ----------------- | -------- |
| 2              | 1                 | 10       |

### Basic Sections

  - 3.1 Introduction to Determinants
  - 3.2 Properties of Determinants

### Advanced Sections

  - 3.3 Cramer's Rule, Volume, and Linear Transformations

### Definitions

### Theorems

1. computation of a determinant by cofactor expansion
2. determinant of a triangular matrix
3. determinant and row operations
4. determinant and invertibility of a square matrix
5. determinant and transpose of a square matrix
6. multiplicative property of determinants
7. cramer's rule \*
8. inverse, determinant and adjugate \*
9. area of parallelogram, volumn of parallelepiped \*
10. linear transformation and area of parallelogram, volumn of parallelepiped \*

## Chapter 4. Vector Spaces

| Basic Sections | Advanced Sections | Theorems |
| -------------- | ----------------- | -------- |
| 7              | 2                 | 18       |

### Basic Sections

  - 4.1 Vector Spaces and Subspaces
  - 4.2 Null Spaces, Column Spaces, and Linear Transformations
  - 4.3 Linearly Independent Sets; Bases
  - 4.4 Coordinate Systems
  - 4.5 The Dimension of a Vector Space
  - 4.6 Rank
  - 4.7 Change of Basis

### Advanced Sections

  - 4.8 Applications to Difference Equations
  - 4.9 Applications to Markov Chains

### Definitions

### Theorems

1. span of vectors is a subspace
2. null space is a subspace
3. column space is a subspace
4. linearly dependence of an indexed set of vectors
5. the spanning set theorem
6. pivot columns of A form a basis for Col A
7. the unique representation theorem
8. coordinate mapping is a one-to-one linear transformation
9. a vector set with more vectors than basis set is linearly dependent
10. every basis of V has exactly n vectors
11. dim H <= dim V for subspace H of V
12. the basis theorem
13. two row equivalent matrices have the same row spaces
14. the rank theorem: rank A + dim Nul A = n

+. the invertible matrix theorem continued (6 more statements, from m. to r.)

15. matrix for change of basis
16. solution for linear difference equations \*
17. solution set for linear difference equations is a vector space \*
18. convergence of a markov chain \*

## Chapter 5. Eigenvalues and Eigenvectors

| Basic Sections | Advanced Sections | Theorems |
| -------------- | ----------------- | -------- |
| 4              | 4                 | 9        |

### Basic Sections

  - 5.1 Eigenvectors and Eigenvalues
  - 5.2 The Characteristic Equation
  - 5.3 Diagonalization
  - 5.4 Eigenvectors and Linear Transformations

### Advanced Sections

  - 5.5 Complex Eigenvalues
  - 5.6 Discrete Dynamical Systems
  - 5.7 Applications to Differential Equations
  - 5.8 Iterative Estimates for Eigenvalues

### Definitions

### Theorems

1. eigenvalues of a triangular matrix
2. linearly independence of eigenvectors

+. the invertible matrix theorem continued (2 more statements, from s. to t.)

3. properties of determinants
4. similar square matrices have the same characteristic polynomial and the same eigenvalues with the same multiplicities
5. the diagonalization theorem
6. diagonalizability of a square matrix
7. multiplicities of a square matrix (from a. to c.)
8. diagonal matrix representation
9. decomposition of 2x2 real matrix with a complex eigenvalue \*


## Chapter 6. Orthogonality and Least Squares

| Basic Sections | Advanced Sections | Theorems |
| -------------- | ----------------- | -------- |
| 6              | 2                 | 17       |

### Basic Sections

  - 6.1 Inner Product, Length, and Orthogonality
  - 6.2 Orthogonal Sets
  - 6.3 Orthogonal Projections
  - 6.4 The Gram–Schmidt Process
  - 6.5 Least-Squares Problems
  - 6.7 Inner Product Spaces

### Advanced Sections

  - 6.6 Applications to Linear Models
  - 6.8 Applications of Inner Product Spaces

### Definitions

### Theorems

1. laws for inner product
2. the pythagorean theorem
3. orthogonal complement between the row space and the null space
4. linearly independence of an orthogonal vector set
5. representing a vector using an orthogonal basis
6. condition for a matrix to have orthonormal columns
7. properties of a matrix with orthonormal columns
8. the orthogonal decomposition theorem
9. the best approximation theorem
10. projection with regard to an orthonormal basis
11. the gram-schmidt process
12. the QR factorization
13. the set of least-squares solutions
14. invertibility of ATA
15. unique least-squares solution and QR factorization
16. the cauchy-schwarz inequality
17. the triangle inequality

## Chapter 7. Symmetric Matrices and Quadratic Forms

| Basic Sections | Advanced Sections | Theorems |
| -------------- | ----------------- | -------- |
| 4              | 1                 | 10       |

### Basic Sections

  - 7.1 Diagonalization of Symmetric Matrices
  - 7.2 Quadratic Forms
  - 7.3 Constrained Optimization
  - 7.4 The Singular Value Decomposition

### Advanced Sections

  - 7.5 Applications to Image Processing and Statistics

### Definitions

### Theorems

1. orthogonality of eigenvectors of a symmetric matrix
2. orthogonal diagonalizability of a square matrix
3. the spectral theorem of symmetric matrices
4. the principal axes theorem
5. quadratic forms and eigvenvalues
6. greatest and least eigenvalues of a symmetric matrix \*
7. max value of xTAx subject to constraints \*
8. max value of xTAx subject to multiple constraints \*
9. orthogonal basis for Col A

+. the invertible matrix theorem continued (4 more statements, from u. to x.)
