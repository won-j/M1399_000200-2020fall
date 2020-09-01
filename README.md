# M1399.000200 Advanced Statistical Computing @ SNU

This is the course website for M1399.000200: "Advanced Statistical Computing " at Seoul National University in Fall 2020. Assignments, lecture notes, and open source code will all be available on this website.

## Announcements

* 2019-11-26: Homework 4 posted. Note the deadline.
* 2019-11-14: Homework 3 Q2-2 has been clarified. Check out the [link](./hw/hw3/hw03.html).
* 2019-10-31: Homework 3 updated.
* 2019-10-30: Homework 3 posted. Note the new deadline.
* 2019-10-10: Notes on the final project is posted. Check out the [link](./project/project.md).
* 2019-10-10: Homework 2 updated: deadline extended to 2019-10-16.
* 2019-09-25: Homework 2 posted. May go through a few rounds of refinement.
* 2019-09-17: Homework 1 updated: Q7 and Q8 are carried over to HW2; new Q7 has been added.
* 2019-09-09: Homework 1 updated.
* 2019-09-05: Homework 1 posted.
* 2019-09-04: Class time changed.

## Instructor 

Joong-Ho (Johann) Won

**Email**: wonj AT stats DOT snu DOT ac DOT kr

**Class Time**: Mondays/Wednesdays 9:40 - 10:55 in 25-204

**Office Hours**: By appointment.

**Textbook**: There is no required textbook.

**References**: 

- James Gentle, [Computational Statistics](https://link.springer.com/book/10.1007%2F978-0-387-98144-4), 2nd Edition, Springer (2009).
- Gene Golub and Charles Van Loan, [Matrix Computation](https://www.amazon.com/Computations-Hopkins-Studies-Mathematical-Sciences/dp/1421407949/ref=sr_1_1?keywords=matrix+computation+golub&qid=1567157884&s=gateway&sr=8-1), 4th Edition, Johns Hopkins Press (2012).
- Kenneth Lange, [Numerical Analysis for Statisticians](https://link.springer.com/book/10.1007%2F978-1-4419-5945-4), 2nd Edition, Springer (2010).
- Stephen Boyd and Lieven Vandenberghe, [Convex Optimization](https://web.stanford.edu/~boyd/cvxbook/), Cambridge University Press (2004).
- Dimitri P. Bertsekas, [Convex Optimization Theory](http://www.athenasc.com/convexduality.html) Athena Scientific (2009).
	

## Course Objectives

By the end of this course, you will be able to acquire

- basic programming skills using the [Julia programming language](https://julialang.org);
- basic knowledge of computer arithmetic;
- fundamental knowledge of numerical algorithms for statistical computing;
- hands-on knowledge of various optimization problems in statistical computing;
- basic theoretical understanding of mathematical optimization;
- wisdom of how *not* to reinvent the wheel.

## Course Overview

### Assessment

The course will be graded based on the following components:

- **Attendance** (10%): Mandatory.
- **Assignments** (65%): You will be assigned 4 homework assignments to be completed using Julia regularly throughout class. 
- **Final project** (25%): The project will be a reproduction of the code and results in a recent computational statistics research paper chosen *in Julia* by yourself. The ideas for projects will be provided towards the midpoint of the semester.

### Schedule

The following schedule is tentative, and is subject to change over the course.

| Week | Topic | Assignment | Due Date |
|---| --- | --- | --- | 
| 1 (9/2, 9/4)      | [Introduction](./lectures/01-intro/intro.html), [Julia ](./lectures/02-juliaintro/juliaintro.html) [[jupyter](./lectures/02-juliaintro/juliaintro.ipynb)], [Plotting](./lectures/02-juliaintro/juliaplots.html) [[jupyter](./lectures/02-juliaintro/juliaplots.ipynb)], [Jupyter](./lectures/02-juliaintro/jupyter.html) | [Homework 1](./hw/hw1/hw01.html) [[jupyter](./hw/hw1/hw01.ipynb)] | 9/22/2019 |
| 2 (9/9, 9/11)     | [Computer Arithmetic](./lectures/03-arith/arith.html) [[jupyter](./lectures/03-arith/arith.ipynb)] |  |   |
| 3 (9/16, 9/18)    | [Algorithm](./lectures/04-algo/algo.html) [[jupyter](./lectures/04-algo/algo.ipynb)], Numerical Linear Algebra: [BLAS](./lectures/05-numalgintro/numalgintro.html) [[jupyter](./lectures/05-numalgintro/numalgintro.ipynb)], [Triangular systems](./lectures/06-trisys/trisys.html) [[jupyter](./lectures/06-trisys/trisys.ipynb)]|  |  |
| 4 (9/23, 9/25)    | Numerical Linear Algebra: [LU decomposition](./lectures/07-gelu/gelu.html) [[jupyter](./lectures/07-gelu/gelu.ipynb)], [Cholesky](./lectures/08-chol/chol.html) [[jupyter](./lectures/08-chol/chol.ipynb)], [QR decomposition](./lectures/09-qr/qr.html) [[jupyter](./lectures/09-qr/qr.ipynb)] | [Homework 2](./hw/hw2/hw02.html) [[jupyter](./hw/hw2/hw02.ipynb)] | 10/16/2019  |
| 5 (9/30, 10/2)    | [Linear regression](./lectures/10-linreg/linreg.html) [[jupyter](./lectures/10-linreg/linreg.ipynb)], Iterative methods: [Basics](./lectures/11-iterative/iterative.html) [[jupyter](./lectures/11-iterative/iterative.ipynb)] | |  |  |
| 6 (10/7)          | [Conjugate Gradient](./lectures/12-cg/cg.html) [[jupyter](./lectures/12-cg/cg.ipynb)] |  |  |
| 7 (10/15, 10/17)  | [Eigenvalue and singular value decompositions](./lectures/13-eigsvd/eigsvd.html) [[jupyter](./lectures/13-eigsvd/eigsvd.ipynb)]  | [Final Project Proposal](./project/project.md)  | 10/26/2019  |
| 8 (10/21, 10/23)  | [Introduction to mathematical optimization](./lectures/14-optmintro/optmintro.html), [Optimization in Julia](./lectures/15-juliaopt/juliaopt.html) [[jupyter]](./lectures/15-juliaopt/juliaopt.ipynb) | | |
| 9 (10/28, 10/30)  | [Linear programming](./lectures/16-lp/lp.html) [[jupyter]](./lectures/16-lp/lp.ipynb), [Quadratic programming](./lectures/17-qp/qp.html) [[jupyter]](./lectures/17-qp/qp.ipynb)  | [Homework 3](./hw/hw3/hw03.html) [[jupyter](./hw/hw3/hw03.ipynb)] | 11/17/2019 |
| 10 (11/4, 11/6)   | [Second-order cone programming](./lectures/18-socp/socp.html) [[jupyter]](./lectures/18-socp/socp.ipynb), [Semidefinite programming](./lectures/19-sdp/sdp.html) [[jupyter]](./lectures/19-sdp/sdp.ipynb) |  |  |
| 11 (11/11, 11/13) | [Geometric programming](./lectures/20-gp/gp.html) [[jupyter]](./lectures/20-gp/gp.ipynb), [KKT conditions](./lectures/21-kkt/kkt.html) | | |
| 12 (11/18, 11/20) | [Newton's method, nonlinear regression](./lectures/22-newton/newton.html) [[jupyter]](./lectures/22-newton/newton.ipynb)  | |  |
| 13 (11/25, 11/27) | [First-order methods](./lectures/23-first/first.html) | [Homework 4](./hw/hw4/hw04.html) [[jupyter](./hw/hw4/hw04.ipynb)] | 12/15/2019 |
| 14 (12/2, 12/4)   | [MM algorithms](./lectures/24-mm/mm.html) |  |  |
| 15 (12/9, 12/11)  | Final Projects      |  |  |


