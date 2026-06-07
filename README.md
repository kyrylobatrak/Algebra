# Abstract Algebra Labs with SageMath

This repository contains a collection of laboratory works on Abstract Algebra, implemented using [SageMath](https://www.sagemath.org/) in Jupyter Notebooks. The labs explore various algebraic structures, including groups, fields, and polynomial rings, demonstrating how computational tools can be used to solve abstract mathematical problems.

## 📚 Repository Contents

### [Lab 01: Introduction to SageMath Basic Syntax](lab01.ipynb)
An introductory notebook covering the foundational syntax and capabilities of SageMath:
- Basic arithmetic and integer operations (factorization, modulo).
- Symbolic expressions, equation solving, and expression simplification.
- Calculus operations: derivatives, indefinite and definite integrals.
- Matrix algebra: transpositions, determinants, eigenvalues, and linear systems.
- 2D plotting of functions.

### [Lab 03: Cyclic Groups, Order of Elements](lab03.ipynb)
A deep dive into group theory concepts:
- **Cyclic Groups $\mathbb{Z}_n$**: Analyzing divisors, Euler's totient function $\phi(n)$, element orders, and subgroup counting $\tau(n)$.
- **Dihedral Groups $D_n$**: Investigating the existence and count of elements of specific orders.
- **Discrete Logarithms**: Exploring the group $\mathbb{Z}_n^*$, checking for cyclicity, finding generator elements, and computing discrete logarithms.
- **Matrix Groups**: Analyzing properties (finiteness, abelian nature, element orders, and isomorphisms) of specific matrix subgroups in $GL_2(\mathbb{Z})$.

### [Lab 06: Fields and Field Extensions](lab06.ipynb)
Exploration of field theory and Galois theory fundamentals:
- **Field Extensions**: Building extensions like $\mathbb{Q}(\sqrt[3]{2}, i)$, finding extension degrees, bases, and minimal polynomials.
- **Splitting Fields**: Constructing splitting fields for polynomials over $\mathbb{Q}$ and $\mathbb{Z}_p$, and factoring polynomials into linear terms.
- **Finite Fields**: Constructing finite fields (e.g., $GF(8)$), generating multiplication tables, and working with quotient rings $\mathbb{Z}_p[x]/(f(x))$.
- **Isomorphisms**: Finding primitive elements and establishing isomorphisms between different representations of finite fields.

## 🛠️ Prerequisites

To run the notebooks in this repository, you need to have **SageMath** installed. 

- [Download SageMath](https://www.sagemath.org/download.html)
- The notebooks were created using the **SageMath 10.7** kernel.

## 🚀 How to Run

1. Clone this repository to your local machine:
   ```bash
   git clone [https://github.com/kyrylobatrak/algebra.git](https://github.com/kyrylobatrak/algebra.git)
   cd algebra
