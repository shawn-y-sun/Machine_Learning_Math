# Mathematics for Machine Learning - Code Template

## 1. Linear Algebra
**Identifying Special Matrices**
A function that will test if a 4x4 matrix is singular
1. convert a matrix to echelon form, 
2. Then test if this fails by leaving zeros that can't be removed on the leading diagonal

**Gram-Schmidt process**
A function to perform the Gram-schmidt procedure, which takes a list of vectors and forms an orthonormal basis from this set

**Reflecting Bear**
A function that will produce a transformation matrix for reflecting vectors in an arbitrarily angled mirror

**Page Rank**
In this notebook, you'll build on your knowledge of eigenvectors and eigenvalues by exploring the PageRank algorithm. The notebook is in two parts:
- the first is a worksheet to get you up to speed with how the algorithm works - here we will look at a micro-internet with fewer than 10 websites and see what it does and what can go wrong. 
- the second is an assessment which will test your application of eigentheory to this problem by writing code and calculating the page rank of a large network representing a sub-section of the internet.
