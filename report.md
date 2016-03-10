UECM3033 Assignment #2 Report
========================================================

- Prepared by: Alex Yong Wei Chun
- Tutorial Group: T2

--------------------------------------------------------

## Task 1 --  $LU$ Factorization or SOR method

The reports, codes and supporting documents are to be uploaded to Github at: 

https://github.com/0904694/UECM3033_assign2/blob/master/task1.py


Explain your selection criteria here.
I will check whether the matrix A is positive definite matrix or not by using Convergence theorem of SOR method, which states that, SOR method will converge if and only if A is positive definite. A matrix is positive definite it mean that it can apply cholesky factorization. So if A cant apply cholesky factorization then we can use LU method to solve the system.



Explain how you implement your `task1.py` here.
Using python function of LU factorization and SOR method. The answer for the first system is [ 1. 1. 1.] and it is solved by LU method. The answer for the second system is [ 1. -1. 4. -3.5 7. -1. ], it is solved by LU method also.


---------------------------------------------------------

## Task 2 -- SVD method and image compression

Put here your picture file 

https://github.com/0904694/UECM3033_assign2/blob/master/Image.jpg



How many non zero element in $\Sigma$?

800 nonzero element in sigma for each color





Put here your lower and better resolution pictures. Explain how you generate
these pictures from `task2.py`.

https://github.com/0904694/UECM3033_assign2/blob/master/low_plots.jpg

https://github.com/0904694/UECM3033_assign2/blob/master/better_plots.jpg





What is a sparse matrix?

Sparse matrix is a matrix in which most of the elements are zero. If most of the elements are nonzero, then the matrix is considered dense.

-----------------------------------

<sup>last modified: change your date here</sup>
