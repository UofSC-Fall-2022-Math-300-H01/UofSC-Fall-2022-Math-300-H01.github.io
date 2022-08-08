---
layout: page
title: Row Echelon Form
nav_order: 6
has_children: false
has_toc: false
parent: Solving Linear Systems
grand_parent: Notes
---

## Simpler system of linear equations

What is the simpliest system of linear equation you can think of?

How about solving 
$$
    x = 1 \\
    y = 2 \\
    z = 3 \ ?
$$

Pretty simple, right? If we represented this system as augmented 
matrix then it would look like 
$$
    \begin{pmatrix} 
        1 & 0 & 0 &\bigg| & 1 \\
        0 & 1 & 0 &\bigg| & 2 \\
        0 & 0 & 1 &\bigg| & 3
    \end{pmatrix}
$$
The key observation from inspecting this is that we have a lot of 
$0$'s in the coefficient matrix. In fact, we only have a single 
entry in each column that is nonzero. 

Of course, not all systems are so simple.

**Question:** Can we operate, in some way, on a matrix $[A|b]$ that 
- does not change the set of solutions to the system but
- simplifies the coefficient matrix by zeroing out more entries?

The answer is yes, as we will see shortly. 

In fact, we can bring the augmented matrix 
$[A|b]$ to a canonical form that, while not as simple as the example 
above, is incredibly useful for solving the system. 

### Row Echelon Form

**Definition**: We say a matrix $A$ is in _row echelon form_ if 
- all zero rows are at the bottom of $A$ and 
- reading left to right, the first nonzero entry of a row is always 
strictly to the right first nonzero entry of the row above it. 

It helps our communication and understanding to be more precise 
and to do so we need 
to introduce some notation. For an matrix $A = (a_{ij})$, let's 
write $A_{\bullet s}$ as shorthand for the vector that is the 
$s$-th row of $A$. So in the example
$$
    A = 
    \begin{pmatrix}
        7 & -1 & 0 & 2 \\
        3 & 3 & 3 & -1 \\
        -1 & 2 & -4 & 0 
    \end{pmatrix}
$$
we have 
$$
   \mathbf{R}_1^A = \begin{pmatrix} 7 & -1 & 0 & 2 \end{pmatrix} \\
   \mathbf{R}_2^A = \begin{pmatrix} 3 & 3 & 3 & -1 \end{pmatrix} \\
    \mathbf{R}_3^A = \begin{pmatrix} -1 & 2 & -4 & 0 \end{pmatrix}.
$$

Similarly we introduce the notation $A_{t \bullet}$ for the 
$t$-th column vector of $A$. Continuing the example we have 
$$
    \mathbf{C}^A_{1} = \begin{pmatrix} 7 \\ 3 \\ -1 \end{pmatrix} \ , \
    \mathbf{C}^A_{2} = \begin{pmatrix} -1 \\ 3 \\ 2 \end{pmatrix} \\
    \mathbf{C}^A_{3} = \begin{pmatrix} 0 \\ 3 \\ 4 \end{pmatrix} \ , \
    \mathbf{C}^A_{4} = \begin{pmatrix} 2 \\ -1 \\ 0 \end{pmatrix} 
$$
We will often omit the $A$ superscript if the context is clear. 

We say a vector $\mathbf{v}$ is _non-zero_ if at least one entry 
is not $0$. 

**Definition**: For a non-zero vector $\mathbf{v}$, the _pivot_ of
$\mathbf{v}$ is the first non-zero entry of $\mathbf{v}$. 

For example, the pivot of 
$$
    \begin{pmatrix} 0 \\ 3 \\ 4 \end{pmatrix}
$$
is the second entry in list, $3$. For 
$$
    \begin{pmatrix} -1 & 2 & -4 & 0 \end{pmatrix}
$$
the pivot is the first entry in the list, $-1$. 

Note that we can only talk about pivots for non-zero vectors. 

Given these notions, we can rephrase the definition row echelon form 
as 

**Definition**: A matrix $A$ is in _row echelon form_ if 
- all zero rows are at the bottom of $A$ and 
- for all nonzero rows $A_{\bullet s}$ the index of the pivot of 
$A_{\bullet s}$ is strictly greater that the index of the pivot of 
$A_{\bullet (s-1)}$. In less words, 
$$
    \operatorname{index} (\operatorname{Pivot}(A_{\bullet (s-1)})) \lneq 
    \operatorname{index} (\operatorname{Pivot}(A_{\bullet s}))
$$

We say an augmented matrix $[A|b]$ is in row echelon form if $A$ is in 
row echelon form. 

For example, 
$$
    A = 
    \begin{pmatrix}
        7 & -1 & 0 & 2 \\
        3 & 3 & 3 & -1 \\
        -1 & 2 & -4 & 0 
    \end{pmatrix}
$$
is _not_ in row echelon form since 
- all rows are non-zero so none need to be at the bottom _but_ 
- the indices of the pivots are all three rows are $1$; they 
do not strictly decrease as we move down the matrix. 

The pivots of the nonzero rows should look like a staircase. Here are two 
examples of matrices in row echelon form. 
$$
    B = 
    \begin{pmatrix}
        7 & -1 & 0 & 2 \\
        0 & 3 & 3 & -1 \\
        0 & 0 & -4 & 0 
    \end{pmatrix}
$$
and 
$$
    B = 
    \begin{pmatrix}
        7 & -1 & 2 \\
        0 & 0 & -1 \\
        0 & 0 & 0 
    \end{pmatrix}
$$

There is a more refined form row echelon row. 

### Reduced row echelon form 

**Definition**: A matrix $A$ is in _reduced row echelon form_ if 
- $A$ is row echelon form,
- all the pivots of the rows of $A$ have value $1$, and 
- each pivot is the only non-zero entry in its column. 

We say an augmented matrix $[A|b]$ is in reduced row echelon form if $A$ is in 
reduced row echelon form. 

All the examples we have seen so far are _not_ in reduced row echelon 
form, even if they were in row echelon form. 

An example in reduced row echelon is 
$$
    \begin{pmatrix}
        1 & 0 & 5 \\
        0 & 1 & 3 
    \end{pmatrix}
$$

We will introduce [operations]({% link notes/solving_linear_systems/row_operations.md %}) 
which will allow us to transform any matrix into reduced row echelon. For 
an augmented matrix $[A|b]$, the operations will preserve the set of solutions to 
the associated linear system. 
