# Chapter 10: Matrices in Two Dimensions

<!-- Page 335 -->

If people do not believe that mathematics is simple, it is only because they do not realize how complicated life is.
- John von Neumann

10
CHAPTER

Matrices in Two Dimensions
10.1 What is a Matrix?

Consider the system of equations
$$\begin{aligned}
2 x+5 y & =1 \\
-3 x-4 y & =-5
\end{aligned}$$

We can express this system with vectors by writing
$$\binom{2 x+5 y}{-3 x-4 y}=\binom{1}{-5} .$$

Each component on the left side is a linear combination of $x$ and $y$. We have a special notation for expressing such a vector; we can express it as multiplication of $\binom{x}{y}$ by a tool we call a matrix. Specifically, we can write
$$\binom{2 x+5 y}{-3 x-4 y}=\left(\begin{array}{cc}
2 & 5 \\
-3 & -4
\end{array}\right)\binom{x}{y} .$$
where $\left(\begin{array}{cc}2 & 5 \\ -3 & -4\end{array}\right)$ is a matrix. (The plural of matrix is matrices.)
A matrix can be viewed as essentially a shorthand for keeping track of the coefficients of the variables in a system of linear equations. We say that the matrix above is a " $2 \times 2$ " matrix because it has 2 rows and 2 columns. In this section, we'll investigate some properties of $2 \times 2$ matrices, starting from the definition
$$\left(\begin{array}{ll}
a & b \\
c & d
\end{array}\right)\binom{x}{y}=\binom{a x+b y}{c x+d y} .$$

335

---

<!-- Page 336 -->

CHAPTER 10. MATRICES IN TWO DIMENSIONS

Note that in this definition, the product of a matrix and a vector is a vector whose components are linear combinations of the components of the original vector.

More formally, a $2 \times 2$ matrix represents a function that has all vectors in two dimensions as its domain, and such that each output vector has components that are linear combinations of the input vector's components. The entries of the matrix describe how these linear combinations are formed, so the matrix $\left(\begin{array}{cc}a & b \\ c & d\end{array}\right)$ represents the function that outputs $\binom{a x+b y}{c x+d y}$ for each input $\binom{x}{y}$. We express this function as the matrix multiplication
$$\left(\begin{array}{ll}
a & b \\
c & d
\end{array}\right)\binom{x}{y}=\binom{a x+b y}{c x+d y}$$
rather than with the usual function notation because the matrix tells us exactly how the output is determined for each input.

We will sometimes refer to a function that has vectors in two dimensions as inputs as having domain $\mathbb{R}^{2}$, and we'll say that a function "maps vectors to vectors" if it has vectors both as inputs and as outputs.

We typically use a bold capital letter to denote a matrix, and sometimes use the corresponding lowercase letter with subscripts to represent the entries in a matrix, like this:
$$\mathbf{A}=\left(\begin{array}{ll}
a_{11} & a_{12} \\
a_{21} & a_{22}
\end{array}\right)$$

For each entry $a_{i j}$, the first number in the subscript indicates the row of the entry and the second number indicates the column, so $a_{21}$ is the first entry of the second row. Also, just as we let $\mathbf{0}$ be the vector with both components equal to 0 , we denote the matrix with all entries equal to 0 as 0 , and call this the zero matrix.

Problems
Problem 10.1: Compute the following products:
(a) $\left(\begin{array}{cc}3 & -1 \\ 6 & 3\end{array}\right)\binom{-2}{5}$
(b) $\quad\left(\begin{array}{ll}0 & -3 \\ 5 & -1\end{array}\right)\binom{-5}{1}$

Problem 10.2: How are $\mathbf{A i}$ and $\mathbf{A j}$ related to $\mathbf{A}$ ?
Problem 10.3: We'd like to define multiplying a matrix by a scalar such that $(c \mathbf{A}) \mathbf{v}=c(\mathbf{A v})$. How should we do so? That is, if $c$ is a scalar and $\mathbf{A}=\left(\begin{array}{ll}a_{11} & a_{12} \\ a_{21} & a_{22}\end{array}\right)$, then what matrix equals $c \mathbf{A}$ ?

Problem 10.4: Show that for any matrix $\mathbf{A}$ and any vectors $\mathbf{v}$ and $\mathbf{w}$, we have $\mathbf{A}(\mathbf{v}+\mathbf{w})=\mathbf{A v}+\mathbf{A w}$.
Problem 10.5: Let $\mathbf{A}=\left(\begin{array}{cc}1 & 3 \\ 5 & -2\end{array}\right), \mathbf{B}=\left(\begin{array}{cc}4 & -3 \\ -1 & 0\end{array}\right)$, and $\mathbf{v}=\binom{x}{y}$.
(a) Find Av and Bv in terms of $x$ and $y$.
(b) Find the matrix $\mathbf{C}$ such that $\mathbf{C v}=\mathbf{A v}+\mathbf{B v}$ for all $\mathbf{v}$.
(c) Let $\mathbf{P}=\left(\begin{array}{ll}p_{11} & p_{12} \\ p_{21} & p_{22}\end{array}\right)$ and $\mathbf{Q}=\left(\begin{array}{ll}q_{11} & q_{12} \\ q_{21} & q_{22}\end{array}\right)$. Suppose we define $\mathbf{P}+\mathbf{Q}$ such that $(\mathbf{P}+\mathbf{Q}) \mathbf{v}=\mathbf{P v}+\mathbf{Q v}$ for all matrices $\mathbf{P}$ and $\mathbf{Q}$ and all vectors $\mathbf{v}$. What matrix equals $\mathbf{P}+\mathbf{Q}$ ?

336

---

<!-- Page 337 -->

10.1. WHAT IS A MATRIX?

We start with some practice multiplying vectors by matrices.
Problem 10.1: Compute the following products:
(a) $\quad\left(\begin{array}{cc}3 & -1 \\ 6 & 3\end{array}\right)\binom{-2}{5}$
(b) $\quad\left(\begin{array}{ll}0 & -3 \\ 5 & -1\end{array}\right)\binom{-5}{1}$

Solution for Problem 10.1: We apply our definition of multiplication of a vector by a matrix:
$$\left(\begin{array}{ll}
a & b \\
c & d
\end{array}\right)\binom{x}{y}=\binom{a x+b y}{c x+d y} .$$
(a) $\left(\begin{array}{cc}3 & -1 \\ 6 & 3\end{array}\right)\binom{-2}{5}=\binom{(3)(-2)+(-1)(5)}{(6)(-2)+(3)(5)}=\binom{-11}{3}$.
(b) $\left(\begin{array}{ll}0 & -3 \\ 5 & -1\end{array}\right)\binom{-5}{1}=\binom{(0)(-5)+(-3)(1)}{(5)(-5)+(-1)(1)}=\binom{-3}{-26}$.

WARNING!!
Multiplication of a vector in two dimensions by a $2 \times 2$ matrix is only defined with the matrix on the left. We have
$$\left(\begin{array}{ll}
a & b \\
c & d
\end{array}\right)\binom{x}{y}=\binom{a x+b y}{c x+d y},$$
but
$$\binom{x}{y}\left(\begin{array}{ll}
a & b \\
c & d
\end{array}\right)$$
is not defined.

Problem 10.2: How are $\mathbf{A i}$ and $\mathbf{A j}$ related to $\mathbf{A}$ ?

Solution for Problem 10.2: We have
$$\left(\begin{array}{ll}
a_{11} & a_{12} \\
a_{21} & a_{22}
\end{array}\right)\binom{1}{0}=\binom{a_{11}}{a_{21}} \quad \text { and } \quad\left(\begin{array}{ll}
a_{11} & a_{12} \\
a_{21} & a_{22}
\end{array}\right)\binom{0}{1}=\binom{a_{12}}{a_{22}} .$$

Therefore, we see that:
Important: Ai is the first column of $\mathbf{A}$ and $\mathbf{A j}$ is the second column of $\mathbf{A}$.
You shouldn't have to memorize this-it's a straightforward application of our definition of the product of a matrix and a vector. However, sometimes this is a very useful way of thinking about matrices: the first column of $\mathbf{A}$ is $\mathbf{A i}$ and the second column is $\mathbf{A j}$.

Problem 10.3: We'd like to define multiplying a matrix by a scalar such that $(c \mathbf{A}) \mathbf{v}=c(\mathbf{A v})$. How should we do so? In other words, if $c$ is a scalar and $\mathbf{A}=\left(\begin{array}{ll}a_{11} & a_{12} \\ a_{21} & a_{22}\end{array}\right)$, then what matrix equals $c \mathbf{A}$ ?

337

---

<!-- Page 338 -->

CHAPTER 10. MATRICES IN TWO DIMENSIONS

Solution for Problem 10.3: Just as with matrix addition, multiplying a matrix by a scalar works in the intuitive way, by multiplying each entry in the matrix by the scalar. We see this by noting that
$$c\left(\mathbf{A}\binom{x}{y}\right)=c\left(\left(\begin{array}{ll}
a_{11} & a_{12} \\
a_{21} & a_{22}
\end{array}\right)\binom{x}{y}\right)=c\binom{a_{11} x+a_{12} y}{a_{21} x+a_{22} y}=\binom{a_{11} c x+a_{12} c y}{a_{21} c x+a_{22} c y}=\left(\begin{array}{ll}
c a_{11} & c a_{12} \\
c a_{21} & c a_{22}
\end{array}\right)\binom{x}{y},$$
so setting
$$c \mathbf{A}=\left(\begin{array}{ll}
c a_{11} & c a_{12} \\
c a_{21} & c a_{22}
\end{array}\right)$$
gives us $(c \mathbf{A}) \mathbf{v}=c(\mathbf{A v})$, as desired.

With this definition of multiplication of a matrix by a scalar, we can also show that $\mathbf{A}(c \mathbf{v})=(c \mathbf{A}) \mathbf{v}=c(\mathbf{A v})$.

For any scalar $c$, vector $\mathbf{v}$ and matrix $\mathbf{A}$, we have
$$(c \mathbf{A}) \mathbf{v}=\mathbf{A}(c \mathbf{v})=c(\mathbf{A v}) .$$

Problem 10.4: Show that for any matrix $\mathbf{A}$ and any vectors $\mathbf{v}$ and $\mathbf{w}$, we have $\mathbf{A}(\mathbf{v}+\mathbf{w})=\mathbf{A v}+\mathbf{A w}$.

Solution for Problem 10.4: Writing out the details of $\mathbf{A}(\mathbf{v}+\mathbf{w})$, we have:
$$\begin{aligned}
\mathbf{A}(\mathbf{v}+\mathbf{w}) & =\left(\begin{array}{ll}
a_{11} & a_{12} \\
a_{21} & a_{22}
\end{array}\right)\left(\binom{v_{1}}{v_{2}}+\binom{w_{1}}{w_{2}}\right) \\
& =\left(\begin{array}{ll}
a_{11} & a_{12} \\
a_{21} & a_{22}
\end{array}\right)\binom{v_{1}+w_{1}}{v_{2}+w_{2}} \\
& =\binom{a_{11} v_{1}+a_{11} w_{1}+a_{12} v_{2}+a_{12} w_{2}}{a_{21} v_{1}+a_{21} w_{1}+a_{22} v_{2}+a_{22} w_{2}} \\
& =\binom{a_{11} v_{1}+a_{12} v_{2}}{a_{21} v_{1}+a_{22} v_{2}}+\binom{a_{11} w_{1}+a_{12} w_{2}}{a_{21} w_{1}+a_{22} w_{2}} \\
& =\left(\begin{array}{ll}
a_{11} & a_{12} \\
a_{21} & a_{22}
\end{array}\right)\binom{v_{1}}{v_{2}}+\left(\begin{array}{ll}
a_{11} & a_{12} \\
a_{21} & a_{22}
\end{array}\right)\binom{w_{1}}{w_{2}} \\
& =\mathbf{A} \mathbf{v}+\mathbf{A} \mathbf{w} .
\end{aligned}$$

Therefore, we have $\mathbf{A}(\mathbf{v}+\mathbf{w})=\mathbf{A v}+\mathbf{A w}$.

Problems 10.3 and 10.4 together tell us that the function that a matrix represents is a linear function. Letting $f$ be one such function, this means that $f(a \mathbf{v})=a f(\mathbf{v})$ for all scalars $a$ and vectors $\mathbf{v}$, and $f(\mathbf{v}+\mathbf{w})=f(\mathbf{v}+\mathbf{w})$ for all vectors $\mathbf{v}$ and $\mathbf{w}$. As we'll show in Problem 10.19, any linear function that maps a vector to a vector can be represented as multiplication by some matrix. Therefore, studying the basic properties of matrices is equivalent to studying linear functions that map vectors to vectors. Since linear functions are part of many fields of study, matrices are an essential mathematical tool with many applications.

Problem 10.5: Let $\mathbf{A}=\left(\begin{array}{cc}1 & 3 \\ 5 & -2\end{array}\right), \mathbf{B}=\left(\begin{array}{cc}4 & -3 \\ -1 & 0\end{array}\right)$, and $\mathbf{v}=\binom{x}{y}$.
(a) Find $\mathbf{A v}$ and $\mathbf{B v}$ in terms of $x$ and $y$.
(b) Find the matrix $\mathbf{C}$ such that $\mathbf{C v}=\mathbf{A v}+\mathbf{B v}$ for all $\mathbf{v}$.
(c) Let $\mathbf{P}=\left(\begin{array}{ll}p_{11} & p_{12} \\ p_{21} & p_{22}\end{array}\right)$ and $\mathbf{Q}=\left(\begin{array}{ll}q_{11} & q_{12} \\ q_{21} & q_{22}\end{array}\right)$. Suppose we define $\mathbf{P}+\mathbf{Q}$ such that $(\mathbf{P}+\mathbf{Q}) \mathbf{v}=\mathbf{P v}+\mathbf{Q v}$ for all matrices $\mathbf{P}$ and $\mathbf{Q}$ and all vectors $\mathbf{v}$. What matrix equals $\mathbf{P}+\mathbf{Q}$ ?

338

---

<!-- Page 339 -->

10.1. WHAT IS A MATRIX?

Solution for Problem 10.5:
(a) We have
$$\mathbf{A} \mathbf{v}=\left(\begin{array}{cc}
1 & 3 \\
5 & -2
\end{array}\right)\binom{x}{y}=\binom{x+3 y}{5 x-2 y} \quad \text { and } \quad \mathbf{B} \mathbf{v}=\left(\begin{array}{cc}
4 & -3 \\
-1 & 0
\end{array}\right)\binom{x}{y}=\binom{4 x-3 y}{-x}$$
(b) Since $\mathbf{A v}+\mathbf{B v}=\binom{x+3 y}{5 x-2 y}+\binom{4 x-3 y}{-x}=\binom{5 x+0 y}{4 x-2 y}$, the matrix $\mathbf{C}$ such that $\mathbf{C v}=\mathbf{A v}+\mathbf{B v}$ for all $\mathbf{v}$ is
$$C=\left(\begin{array}{cc}
5 & 0 \\
4 & -2
\end{array}\right)$$
(c) We use our first two parts as a guide:
$$\begin{aligned}
\mathbf{P}\binom{x}{y}+\mathbf{Q}\binom{x}{y} & =\left(\begin{array}{ll}
p_{11} & p_{12} \\
p_{21} & p_{22}
\end{array}\right)\binom{x}{y}+\left(\begin{array}{ll}
q_{11} & q_{12} \\
q_{21} & q_{22}
\end{array}\right)\binom{x}{y} \\
& =\binom{p_{11} x+p_{12} y}{p_{21} x+p_{22} y}+\binom{q_{11} x+q_{12} y}{q_{21} x+q_{22} y} \\
& =\binom{p_{11} x+p_{12} y+q_{11} x+q_{12} y}{p_{21} x+p_{22} y+q_{21} x+q_{22} y} \\
& =\binom{\left(p_{11}+q_{11}\right) x+\left(p_{12}+q_{12}\right) y}{\left(p_{21}+q_{21}\right) x+\left(p_{22}+q_{22}\right) y} \\
& =\left(\begin{array}{ll}
p_{11}+q_{11} & p_{12}+q_{12} \\
p_{21}+q_{21} & p_{22}+q_{22}
\end{array}\right)\binom{x}{y} .
\end{aligned}$$

So, we see that we should define $\mathbf{P}+\mathbf{Q}$ as
$$\mathbf{P}+\mathbf{Q}=\left(\begin{array}{ll}
p_{11} & p_{12} \\
p_{21} & p_{22}
\end{array}\right)+\left(\begin{array}{ll}
q_{11} & q_{12} \\
q_{21} & q_{22}
\end{array}\right)=\left(\begin{array}{ll}
p_{11}+q_{11} & p_{12}+q_{12} \\
p_{21}+q_{21} & p_{22}+q_{22}
\end{array}\right) .$$

We therefore see that adding matrices works just like adding vectors: we add two matrices by adding the corresponding entries in the two matrices.

Exercises
10.1.1 Find the following products:
(a) $\left(\begin{array}{ll}3 & -4 \\ 5 & -2\end{array}\right)\binom{3}{-5}$
(b) $\quad\left(\begin{array}{cc}-1 & 0 \\ 4 & -2\end{array}\right)\binom{-1}{3}$
10.1.2 We define the difference of two matrices $\mathbf{A}-\mathbf{B}$ to be the matrix $\mathbf{D}$ such that $\mathbf{D}+\mathbf{B}=\mathbf{A}$. Show that if $\mathbf{A}=\left(\begin{array}{ll}a_{11} & a_{12} \\ a_{21} & a_{22}\end{array}\right)$ and $\mathbf{B}=\left(\begin{array}{ll}b_{11} & b_{12} \\ b_{21} & b_{22}\end{array}\right)$, then
$$\mathbf{A}-\mathbf{B}=\left(\begin{array}{ll}
a_{11}-b_{11} & a_{12}-b_{12} \\
a_{21}-b_{21} & a_{22}-b_{22}
\end{array}\right)$$

339

---

<!-- Page 340 -->

CHAPTER 10. MATRICES IN TWO DIMENSIONS
10.1.3 Let $\mathbf{A}=\left(\begin{array}{ll}6 & -4 \\ 3 & -2\end{array}\right)$.
(a) Find $\mathbf{A}\binom{2}{-3}$ and $\mathbf{A}\binom{5}{-1}$.
(b) Are $\binom{2}{-3}$ and $\binom{5}{-1}$ linearly dependent?
(c) Are your results in part (a) linearly dependent?
(d) If your answers to (b) and (c) are the same, then solve those parts again. If they are different, is it just a coincidence? If you choose any two vectors to replace $\binom{2}{-3}$ and $\binom{5}{-1}$ in part (a), will your answer to part (c) still be the same?
10.2 Multiplying Matrices

In the previous section, we found that matrix addition works in the way we might expect: each entry in the sum of two matrices is the sum of the corresponding entries in the two matrices. In this section, we learn how to find the product of two matrices, and find that the process isn't nearly as straightforward as adding two matrices.

Problems

Problem 10.6: Consider the system of equations
$$\begin{array}{l}
4 x+3 y=7 \\
2 x-9 y=5
\end{array}$$

Suppose we wish to write the system in terms of the variables $u$ and $v$, where $x=2 u-v$ and $y=3 u+v$.
(a) Write the original system in the form $\mathbf{A}\binom{x}{y}=\binom{7}{5}$.
(b) For what matrix $\mathbf{B}$ do we have $\binom{x}{y}=\mathbf{B}\binom{u}{v}$ ?
(c) Use substitution to write the original system of equations in terms of $u$ and $v$ rather than $x$ and $y$.
(d) Suppose we define the matrix product $\mathbf{A B}$ so that for any vector $\mathbf{w}$, we have $(\mathbf{A B}) \mathbf{w}=\mathbf{A}(\mathbf{B w})$. What is $\mathbf{A B}$ ?

Problem 10.7: Find a matrix that equals $\mathbf{A B}$, where
$$\mathbf{A}=\left(\begin{array}{ll}
a_{11} & a_{12} \\
a_{21} & a_{22}
\end{array}\right) \quad \text { and } \quad \mathbf{B}=\left(\begin{array}{ll}
b_{11} & b_{12} \\
b_{21} & b_{22}
\end{array}\right) .$$

Problem 10.8: Perform the following matrix multiplications:
(a) $\left(\begin{array}{cc}-3 & 2 \\ -6 & -10\end{array}\right)\left(\begin{array}{cc}0 & 1 \\ -1 & -5\end{array}\right)$
(b) $\quad\left(\begin{array}{cc}-1 & 0 \\ 4 & 3\end{array}\right)\left(\begin{array}{cc}-4 & 5 \\ 1 & -2\end{array}\right)$

340

---

<!-- Page 341 -->

10.2. MULTIPLYING MATRICES

Problem 10.9: Suppose $\mathbf{A}$ and $\mathbf{B}$ are $2 \times 2$ matrices.
(a) Must we have $\mathbf{A}+\mathbf{B}=\mathbf{B}+\mathbf{A}$ ?
(b) Must we have $\mathbf{A B}=\mathbf{B A}$ ?

Problem 10.10:
(a) Is matrix multiplication associative? In other words, is it always true that $\mathbf{A}(\mathbf{B C})=(\mathbf{A B}) \mathbf{C}$ ?
(b) Is matrix multiplication distributive over addition? That is, is it always true that $\mathbf{A}(\mathbf{B}+\mathbf{C})=\mathbf{A B}+\mathbf{A C}$ and $(\mathbf{B}+\mathbf{C}) \mathbf{A}=\mathbf{B A}+\mathbf{C A}$ ?

Problem 10.11:
(a) If $\mathbf{A}\binom{1}{2}=\binom{17}{0}$, then must $\mathbf{A}=\left(\begin{array}{cc}3 & 7 \\ 2 & -1\end{array}\right)$ ?
(b) If $\mathbf{A}\binom{1}{2}=\binom{17}{0}$ and $\mathbf{A}\binom{-2}{-4}=\binom{-34}{0}$, then must $\mathbf{A}=\left(\begin{array}{cc}3 & 7 \\ 2 & -1\end{array}\right)$ ?
(c) If $\mathbf{A}\binom{1}{2}=\binom{17}{0}$ and $\mathbf{A}\binom{2}{-1}=\binom{-1}{5}$, then must $\mathbf{A}=\left(\begin{array}{cc}3 & 7 \\ 2 & -1\end{array}\right)$ ?

Problem 10.12: Suppose $\mathbf{v}$ and $\mathbf{w}$ are linearly independent and $\mathbf{A}$ and $\mathbf{B}$ are matrices such that $\mathbf{A v}=\mathbf{B v}$ and $\mathbf{A w} \boldsymbol{=} \mathbf{B w}$.
(a) Why must $\mathbf{A i}=\mathbf{B i}$ ?
(b) Show that $\mathbf{A}=\mathbf{B}$.

Problem 10.6: Consider the system of equations
$$\begin{array}{l}
4 x+3 y=7 \\
2 x-9 y=5
\end{array}$$

Suppose we wish to write the system in terms of the variables $u$ and $v$, where $x=2 u-v$ and $y=3 u+v$.
(a) Write the original system in the form $\mathbf{A}\binom{x}{y}=\binom{7}{5}$.
(b) For what matrix $\mathbf{B}$ do we have $\binom{x}{y}=\mathbf{B}\binom{u}{v}$ ?
(c) Use substitution to write the original system of equations in terms of $u$ and $v$ rather than $x$ and $y$.
(d) Suppose we define the matrix product $\mathbf{A B}$ so that for any vector $\mathbf{w}$, we have $(\mathbf{A B}) \mathbf{w}=\mathbf{A}(\mathbf{B w})$. What is AB ?

Solution for Problem 10.6:
(a) We have $\left(\begin{array}{cc}4 & 3 \\ 2 & -9\end{array}\right)\binom{x}{y}=\binom{7}{5}$, so $\mathbf{A}=\left(\begin{array}{cc}4 & 3 \\ 2 & -9\end{array}\right)$.
(b) We have $\binom{x}{y}=\left(\begin{array}{cc}2 & -1 \\ 3 & 1\end{array}\right)\binom{u}{v}$, so $\mathbf{B}=\left(\begin{array}{cc}2 & -1 \\ 3 & 1\end{array}\right)$.
(c) Substituting $x=2 u-v$ and $y=3 u+v$ into the original system of equations, and then doing some simplifying,

341

---

<!-- Page 342 -->

CHAPTER 10. MATRICES IN TWO DIMENSIONS

gives the system
$$\begin{array}{r}
17 u-v=7 \\
-23 u-11 v=5
\end{array}$$

We can express this system as $\left(\begin{array}{cc}17 & -1 \\ -23 & -11\end{array}\right)\binom{u}{v}=\binom{7}{5}$.
(d) Substituting $\binom{x}{y}=\left(\begin{array}{cc}2 & -1 \\ 3 & 1\end{array}\right)\binom{u}{v}$ from part (b) into $\left(\begin{array}{cc}4 & 3 \\ 2 & -9\end{array}\right)\binom{x}{y}=\binom{7}{5}$ from part (a) gives
$$\left(\begin{array}{cc}
4 & 3 \\
2 & -9
\end{array}\right)\left(\begin{array}{cc}
2 & -1 \\
3 & 1
\end{array}\right)\binom{u}{v}=\binom{7}{5} .$$

Comparing this to part (c), it appears that we should define matrix multiplication such that
$$\left(\begin{array}{cc}
4 & 3 \\
2 & -9
\end{array}\right)\left(\begin{array}{cc}
2 & -1 \\
3 & 1
\end{array}\right)=\left(\begin{array}{cc}
17 & -1 \\
-23 & -11
\end{array}\right) .$$

Notice that this is not what simple intuition might suggest.

WARNING!! We do not multiply two $2 \times 2$ matrices by multiplying corresponding entries. For example,
$$\left(\begin{array}{cc}
4 & 3 \\
2 & -9
\end{array}\right)\left(\begin{array}{cc}
2 & -1 \\
3 & 1
\end{array}\right) \neq\left(\begin{array}{cc}
4 \cdot 2 & 3 \cdot(-1) \\
2 \cdot 3 & -9 \cdot 1
\end{array}\right) .$$

Let's see how matrix multiplication does work, given that we wish to define matrix multiplication so that $(\mathbf{A B}) \mathbf{w}=\mathbf{A}(\mathbf{B w})$ for all $\mathbf{w}$.

Problem 10.7: Find a matrix that equals $\mathbf{A B}$, where
$$\mathbf{A}=\left(\begin{array}{ll}
a_{11} & a_{12} \\
a_{21} & a_{22}
\end{array}\right) \quad \text { and } \quad \mathbf{B}=\left(\begin{array}{ll}
b_{11} & b_{12} \\
b_{21} & b_{22}
\end{array}\right) .$$

Solution for Problem 10.7: We let $\mathbf{w}=\binom{u}{v}$, and we have
$$\begin{aligned}
\mathbf{A}(\mathbf{B} \mathbf{w}) & =\mathbf{A}\left(\left(\begin{array}{ll}
b_{11} & b_{12} \\
b_{21} & b_{22}
\end{array}\right)\binom{u}{v}\right) \\
& =\left(\begin{array}{ll}
a_{11} & a_{12} \\
a_{21} & a_{22}
\end{array}\right)\binom{b_{11} u+b_{12} v}{b_{21} u+b_{22} v} \\
& =\binom{a_{11} b_{11} u+a_{11} b_{12} v+a_{12} b_{21} u+a_{12} b_{22} v}{a_{21} b_{11} u+a_{21} b_{12} v+a_{22} b_{21} u+a_{22} b_{22} v} \\
& =\binom{\left(a_{11} b_{11}+a_{12} b_{21}\right) u+\left(a_{11} b_{12}+a_{12} b_{22}\right) v}{\left(a_{21} b_{11}+a_{22} b_{21}\right) u+\left(a_{21} b_{12}+a_{22} b_{22}\right) v} \\
& =\left(\begin{array}{ll}
a_{11} b_{11}+a_{12} b_{21} & a_{11} b_{12}+a_{12} b_{22} \\
a_{21} b_{11}+a_{22} b_{21} & a_{21} b_{12}+a_{22} b_{22}
\end{array}\right)\binom{u}{v}
\end{aligned}$$

Therefore, we have $\mathbf{A B}=\left(\begin{array}{ll}a_{11} b_{11}+a_{12} b_{21} & a_{11} b_{12}+a_{12} b_{22} \\ a_{21} b_{11}+a_{22} b_{21} & a_{21} b_{12}+a_{22} b_{22}\end{array}\right)$.

342

---

<!-- Page 343 -->

10.2. MULTIPLYING MATRICES

Important: We define the product of two $2 \times 2$ matrices as
$$\left(\begin{array}{ll}
a_{11} & a_{12} \\
a_{21} & a_{22}
\end{array}\right)\left(\begin{array}{ll}
b_{11} & b_{12} \\
b_{21} & b_{22}
\end{array}\right)=\left(\begin{array}{ll}
a_{11} b_{11}+a_{12} b_{21} & a_{11} b_{12}+a_{12} b_{22} \\
a_{21} b_{11}+a_{22} b_{21} & a_{21} b_{12}+a_{22} b_{22}
\end{array}\right) .$$

We can remember how to multiply matrices by viewing each column of a matrix and each row of a matrix as a vector. The column vectors of $\left(\begin{array}{ll}b_{11} & b_{12} \\ b_{21} & b_{22}\end{array}\right)$ are $\binom{b_{11}}{b_{21}}$ and $\binom{b_{12}}{b_{22}}$. Similarly, the two rows of a matrix $\mathbf{A}$ are the row vectors of $\mathbf{A}$. We typically write row vectors horizontally, so the row vectors of $\left(\begin{array}{ll}a_{11} & a_{12} \\ a_{21} & a_{22}\end{array}\right)$ are $\left(\begin{array}{ll}a_{11} & a_{12}\end{array}\right)$ and $\left(\begin{array}{ll}a_{21} & a_{22}\end{array}\right)$.

With this in mind, we can remember how to perform matrix multiplication by noting that the entry of row $i$ and column $j$ of $\mathbf{A B}$ is the dot product of row $i$ of $\mathbf{A}$ and column $j$ of $\mathbf{B}$. For example, the entry in row 1 and column 2 of $\mathbf{A B}$ is
$$\left(\begin{array}{ll}
a_{11} & a_{12}
\end{array}\right) \cdot\binom{b_{12}}{b_{22}}=a_{11} b_{12}+a_{12} b_{22} .$$

If we let the rows of $\mathbf{A}$ be the vectors $\mathbf{a}_{1}$ and $\mathbf{a}_{2}$, and the columns of $\mathbf{B}$ be the vectors $\mathbf{b}_{1}$ and $\mathbf{b}_{2}$, we can therefore express the product $\mathbf{A B}$ as
$$\mathbf{A B}=\binom{\mathbf{a}_{1}}{\mathbf{a}_{2}}\left(\begin{array}{ll}
\mathbf{b}_{1} & \mathbf{b}_{2}
\end{array}\right)=\left(\begin{array}{ll}
\mathbf{a}_{1} \cdot \mathbf{b}_{1} & \mathbf{a}_{1} \cdot \mathbf{b}_{2} \\
\mathbf{a}_{2} \cdot \mathbf{b}_{1} & \mathbf{a}_{2} \cdot \mathbf{b}_{2}
\end{array}\right) .$$

We can also remember this matrix product by noting that each column of $\mathbf{A B}$ equals $\mathbf{A}$ times the corresponding column of B. That is, we can view the product as:
$$\mathbf{A B}=\mathbf{A}\left(\begin{array}{ll}
\mathbf{b}_{1} & \mathbf{b}_{2}
\end{array}\right)=\left(\begin{array}{ll}
\mathbf{A} \mathbf{b}_{1} & \mathbf{A} \mathbf{b}_{2}
\end{array}\right) .$$

Problem 10.8: Perform the following matrix multiplications:
(a) $\quad\left(\begin{array}{cc}-3 & 2 \\ -6 & -10\end{array}\right)\left(\begin{array}{cc}0 & 1 \\ -1 & -5\end{array}\right)$
(b) $\quad\left(\begin{array}{cc}-1 & 0 \\ 4 & 3\end{array}\right)\left(\begin{array}{cc}-4 & 5 \\ 1 & -2\end{array}\right)$

Solution for Problem 10.8:
(a)
$$\begin{aligned}
\left(\begin{array}{cc}
-3 & 2 \\
-6 & -10
\end{array}\right)\left(\begin{array}{cc}
0 & 1 \\
-1 & -5
\end{array}\right) & =\left(\begin{array}{cc}
\left(\begin{array}{ll}
-3 & 2
\end{array}\right) \cdot\binom{0}{-1} & \left(\begin{array}{ll}
-3 & 2
\end{array}\right) \cdot\binom{1}{-5} \\
\left(\begin{array}{ll}
-6 & -10
\end{array}\right) \cdot\binom{0}{-1} & \left(\begin{array}{ll}
-6 & -10
\end{array}\right) \cdot\binom{1}{-5}
\end{array}\right) \\
& =\left(\begin{array}{cc}
(-3)(0)+(2)(-1) & (-3)(1)+(2)(-5) \\
(-6)(0)+(-10)(-1) & (-6)(1)+(-10)(-5)
\end{array}\right) \\
& =\left(\begin{array}{cc}
-2 & -13 \\
10 & 44
\end{array}\right) .
\end{aligned}$$
(b)
$$\left(\begin{array}{cc}
-1 & 0 \\
4 & 3
\end{array}\right)\left(\begin{array}{cc}
-4 & 5 \\
1 & -2
\end{array}\right)=\left(\begin{array}{cc}
(-1)(-4)+(0)(1) & (-1)(5)+(0)(-2) \\
(4)(-4)+(3)(1) & (4)(5)+(3)(-2)
\end{array}\right)=\left(\begin{array}{cc}
4 & -5 \\
-13 & 14
\end{array}\right) .$$

Viewing matrices as representing functions, the matrix product $\mathbf{A B}$ is a composition of functions. The product $\mathbf{A}\left(\mathbf{B}\binom{x}{y}\right)$ tells us to apply the function that $\mathbf{B}$ represents to $\binom{x}{y}$, and then apply the function that $\mathbf{A}$ represents

343

---

<!-- Page 344 -->

CHAPTER 10. MATRICES IN TWO DIMENSIONS

to the result of $\mathbf{B}\binom{x}{y}$. As we have just seen, we can represent the product $\mathbf{A B}$ as a single matrix, and this matrix represents the composition of the functions $\mathbf{A}$ and $\mathbf{B}$ represent. So, the product $(\mathbf{A B})\binom{x}{y}$ tells us to apply the result of this function composition to $\binom{x}{y}$.

Problem 10.9: Suppose $\mathbf{A}$ and $\mathbf{B}$ are $2 \times 2$ matrices.
(a) Must we have $\mathbf{A}+\mathbf{B}=\mathbf{B}+\mathbf{A}$ ?
(b) Must we have $\mathbf{A B}=\mathbf{B A}$ ?

Solution for Problem 10.9:
(a) Yes. We have
$$\begin{aligned}
\mathbf{A}+\mathbf{B}=\left(\begin{array}{ll}
a_{11} & a_{12} \\
a_{21} & a_{22}
\end{array}\right)+\left(\begin{array}{ll}
b_{11} & b_{12} \\
b_{21} & b_{22}
\end{array}\right) & =\left(\begin{array}{ll}
a_{11}+b_{11} & a_{12}+b_{12} \\
a_{21}+b_{21} & a_{22}+b_{22}
\end{array}\right) \\
& =\left(\begin{array}{ll}
b_{11}+a_{11} & b_{12}+a_{12} \\
b_{21}+a_{21} & b_{22}+a_{22}
\end{array}\right)=\left(\begin{array}{ll}
b_{11} & b_{12} \\
b_{21} & b_{22}
\end{array}\right)+\left(\begin{array}{ll}
a_{11} & a_{12} \\
a_{21} & a_{22}
\end{array}\right)=\mathbf{B}+\mathbf{A} .
\end{aligned}$$
(b) The non-intuitive definition of matrix multiplication might make us suspect that $\mathbf{A B}$ is not necessarily equal to BA. We can test it by looking at one of the examples in the previous problem. For example, we found that
$$\left(\begin{array}{cc}
-1 & 0 \\
4 & 3
\end{array}\right)\left(\begin{array}{cc}
-4 & 5 \\
1 & -2
\end{array}\right)=\left(\begin{array}{cc}
4 & -5 \\
-13 & 14
\end{array}\right) .$$

Reversing the order of the matrices in the product, we have
$$\left(\begin{array}{cc}
-4 & 5 \\
1 & -2
\end{array}\right)\left(\begin{array}{cc}
-1 & 0 \\
4 & 3
\end{array}\right)=\left(\begin{array}{ll}
(-4)(-1)+(5)(4) & (-4)(0)+(5)(3) \\
(1)(-1)+(-2)(4) & (1)(0)+(-2)(3)
\end{array}\right)=\left(\begin{array}{cc}
24 & 15 \\
-9 & -6
\end{array}\right) .$$

So, on our first try we found a pair of matrices $\mathbf{A}$ and $\mathbf{B}$ such that $\mathbf{A B}$ and $\mathbf{B A}$ are not equal.

WARNING!! Matrix multiplication is not commutative; the products $\mathbf{A B}$ and $\mathbf{B A}$ are not necessarily equal.

Sidenote: When we think of a matrix as representing a function, it's not surprising that matrix multiplication is not commutative. The product $\mathbf{A B}\binom{x}{y}=\mathbf{A}\left(\mathbf{B}\binom{x}{y}\right)$ tells us to apply the function that B represents to $\binom{x}{y}$, and then apply the function that $\mathbf{A}$ represents to the result of $\mathbf{B}\binom{x}{y}$. The product $\mathbf{B A}\binom{x}{y}=\mathbf{B}\left(\mathbf{A}\binom{x}{y}\right)$ has us apply these functions in the reverse order. But we saw on page 17 that function composition is not commutative; if $f$ and $g$ are functions, then $f \circ g$ is not necessarily the same as $g \circ f$.

344

---

<!-- Page 345 -->

10.2. MULTIPLYING MATRICES

Problem 10.10:
(a) Is matrix multiplication associative? In other words, is it always true that $\mathbf{A}(\mathbf{B C})=(\mathbf{A B}) \mathbf{C}$ ?
(b) Is matrix multiplication distributive over addition? That is, is it always true that $\mathbf{A}(\mathbf{B}+\mathbf{C})=\mathbf{A B}+\mathbf{A C}$ and $(\mathbf{B}+\mathbf{C}) \mathbf{A}=\mathbf{B A}+\mathbf{C A}$ ?

Solution for Problem 10.10:
(a) We have
$$\begin{aligned}
\mathbf{A}(\mathbf{B C}) & =\left(\begin{array}{ll}
a_{11} & a_{12} \\
a_{21} & a_{22}
\end{array}\right)\left(\begin{array}{ll}
b_{11} c_{11}+b_{12} c_{21} & b_{11} c_{12}+b_{12} c_{22} \\
b_{21} c_{11}+b_{22} c_{21} & b_{21} c_{12}+b_{22} c_{22}
\end{array}\right) \\
& =\left(\begin{array}{ll}
a_{11} b_{11} c_{11}+a_{11} b_{12} c_{21}+a_{12} b_{21} c_{11}+a_{12} b_{22} c_{21} & a_{11} b_{11} c_{12}+a_{11} b_{12} c_{22}+a_{12} b_{21} c_{12}+a_{12} b_{22} c_{22} \\
a_{21} b_{11} c_{11}+a_{21} b_{12} c_{21}+a_{22} b_{21} c_{11}+a_{22} b_{22} c_{21} & a_{21} b_{11} c_{12}+a_{21} b_{12} c_{22}+a_{22} b_{21} c_{12}+a_{22} b_{22} c_{22}
\end{array}\right)
\end{aligned}$$
and
$$\begin{aligned}
(\mathbf{A B}) \mathbf{C} & =\left(\begin{array}{ll}
a_{11} b_{11}+a_{12} b_{21} & a_{11} b_{12}+a_{12} b_{22} \\
a_{21} b_{11}+a_{22} b_{21} & a_{21} b_{12}+a_{22} b_{22}
\end{array}\right)\left(\begin{array}{ll}
c_{11} & c_{12} \\
c_{21} & c_{22}
\end{array}\right) \\
& =\left(\begin{array}{ll}
a_{11} b_{11} c_{11}+a_{12} b_{21} c_{11}+a_{11} b_{12} c_{21}+a_{12} b_{22} c_{21} & a_{11} b_{11} c_{12}+a_{12} b_{21} c_{12}+a_{11} b_{12} c_{22}+a_{12} b_{22} c_{22} \\
a_{21} b_{11} c_{11}+a_{22} b_{21} c_{11}+a_{21} b_{12} c_{21}+a_{22} b_{22} c_{21} & a_{21} b_{11} c_{12}+a_{22} b_{21} c_{12}+a_{21} b_{12} c_{22}+a_{22} b_{22} c_{22}
\end{array}\right)
\end{aligned}$$

With a little tedious inspection, we can see that these expressions for $\mathbf{A}(\mathbf{B C})$ and $(\mathbf{A B}) \mathbf{C}$ are indeed the same. Therefore, we can simply write $\mathbf{A B C}$ rather than writing $\mathbf{A}(\mathbf{B C})$ or $(\mathbf{A B}) \mathbf{C}$.

Our proof that $\mathbf{A}(\mathbf{B C})=(\mathbf{A B}) \mathbf{C}$ is not particularly illuminating. We can find a more intuitively satisfying explanation by starting with systems of equations:
$$\begin{array}{lll}
t_{1}=a_{11} u_{1}+a_{12} u_{2}, & u_{1}=b_{11} v_{1}+b_{12} v_{2}, & v_{1}=c_{11} w_{1}+c_{12} w_{2} \\
t_{2}=a_{21} u_{1}+a_{22} u_{2}, & u_{2}=b_{21} v_{1}+b_{22} v_{2}, & v_{2}=c_{21} w_{1}+c_{22} w_{2}
\end{array}$$

We can view these systems as $\mathbf{t}=\mathbf{A} \mathbf{u}, \mathbf{u}=\mathbf{B v}$, and $\mathbf{v}=\mathbf{C w}$. Through a pair of substitutions, we can combine these systems to express $t_{1}$ and $t_{2}$ in terms of $w_{1}$ and $w_{2}$. No matter which order we perform these substitutions, we'll get the same system of equations in the end. If we substitute the expressions for $u_{1}$ and $u_{2}$ from the second system into the first, and then substitute the expressions for $v_{1}$ and $v_{2}$ into the result, we get $\mathbf{t}=(\mathbf{A B})(\mathbf{C w})$. If we instead first substitute the expressions for $v_{1}$ and $v_{2}$ from the the third system into the second, and then substitute the result into the first, we get $\mathbf{t}=\mathbf{A}(\mathbf{B C w})$. Either way, we get the same system.
(b) This one's a good deal easier. We have
$$\begin{aligned}
\mathbf{A}(\mathbf{B}+\mathbf{C}) & =\left(\begin{array}{ll}
a_{11} & a_{12} \\
a_{21} & a_{22}
\end{array}\right)\left(\begin{array}{ll}
b_{11}+c_{11} & b_{12}+c_{12} \\
b_{21}+c_{21} & b_{22}+c_{22}
\end{array}\right) \\
& =\left(\begin{array}{ll}
a_{11} b_{11}+a_{11} c_{11}+a_{12} b_{21}+a_{12} c_{21} & a_{11} b_{12}+a_{11} c_{12}+a_{12} b_{22}+a_{12} c_{22} \\
a_{21} b_{11}+a_{21} c_{11}+a_{22} b_{21}+a_{22} c_{21} & a_{21} b_{12}+a_{21} c_{12}+a_{22} b_{22}+a_{22} c_{22}
\end{array}\right) \\
& =\left(\begin{array}{ll}
a_{11} b_{11}+a_{12} b_{21} & a_{11} b_{12}+a_{12} b_{22} \\
a_{21} b_{11}+a_{22} b_{21} & a_{21} b_{12}+a_{22} b_{22}
\end{array}\right)+\left(\begin{array}{ll}
a_{11} c_{11}+a_{12} c_{21} & a_{11} c_{12}+a_{12} c_{22} \\
a_{21} c_{11}+a_{22} c_{21} & a_{21} c_{12}+a_{22} c_{22}
\end{array}\right) \\
& =\mathbf{A} \mathbf{B}+\mathbf{A} \mathbf{C},
\end{aligned}$$
and similar computations show that $(\mathbf{B}+\mathbf{C}) \mathbf{A}=\mathbf{B A}+\mathbf{C A}$. (Note that we must confirm $\mathbf{A}(\mathbf{B}+\mathbf{C})=\mathbf{A B}+\mathbf{A C}$ and $(\mathbf{B}+\mathbf{C}) \mathbf{A}=\mathbf{B A}+\mathbf{C A}$ separately because matrix multiplication is not commutative.)

345

---

<!-- Page 346 -->

CHAPTER 10. MATRICES IN TWO DIMENSIONS

Important: Matrix multiplication is associative and distributive. So, for all $2 \times 2$ matrices
$! \mathbf{A}, \mathbf{B}$, and $\mathbf{C}$, we have
$$\begin{aligned}
\mathbf{A}(\mathbf{B C}) & =(\mathbf{A B}) \mathbf{C} \\
\mathbf{A}(\mathbf{B}+\mathbf{C}) & =\mathbf{A B}+\mathbf{A C} \\
(\mathbf{B}+\mathbf{C}) \mathbf{A} & =\mathbf{B A}+\mathbf{C A} .
\end{aligned}$$

Sidenote: Again, we can use the fact that a matrix represents a function to understand why matrix multiplication is associative. For any three functions $f, g$, and $h$, we have
$$f \circ(g \circ h)=(f \circ g) \circ h$$

If matrices $\mathbf{A}, \mathbf{B}$, and $\mathbf{C}$ represent functions $f, g$, and $h$, respectively, then we have
$$A(B C)=(A B) C .$$

Problem 10.11:
(a) If $\mathbf{A}\binom{1}{2}=\binom{17}{0}$, then must $\mathbf{A}=\left(\begin{array}{cc}3 & 7 \\ 2 & -1\end{array}\right)$ ?
(b) If $\mathbf{A}\binom{1}{2}=\binom{17}{0}$ and $\mathbf{A}\binom{-2}{-4}=\binom{-34}{0}$, then must $\mathbf{A}=\left(\begin{array}{cc}3 & 7 \\ 2 & -1\end{array}\right)$ ?
(c) If $\mathbf{A}\binom{1}{2}=\binom{17}{0}$ and $\mathbf{A}\binom{2}{-1}=\binom{-1}{5}$, then must $\mathbf{A}=\left(\begin{array}{cc}3 & 7 \\ 2 & -1\end{array}\right)$ ?

Solution for Problem 10.11: Let $\mathbf{A}=\left(\begin{array}{ll}a_{11} & a_{12} \\ a_{21} & a_{22}\end{array}\right)$, so $\mathbf{A}\binom{1}{2}=\binom{a_{11}+2 a_{12}}{a_{21}+2 a_{22}}$.
(a) We must have $a_{11}+2 a_{12}=17$ and $a_{21}+2 a_{22}=0$. We have four variables among these two linear equations. Choosing $a_{12}=7$ and $a_{22}=-1$, and then solving for $a_{11}$ and $a_{21}$, gives us $\mathbf{A}=\left(\begin{array}{cc}3 & 7 \\ 2 & -1\end{array}\right)$. But there are other possibilities for $\mathbf{A}$, since these aren't the only possible values we can choose for $a_{12}$ and $a_{22}$. The solution $\mathbf{A}=\left(\begin{array}{cc}17 & 0 \\ 0 & 0\end{array}\right)$ is one particularly obvious possibility for $\mathbf{A}$. Choosing $a_{12}=1$ and $a_{22}=2$, and then solving for $a_{11}$ and $a_{21}$, gives us $\mathbf{A}=\left(\begin{array}{cc}15 & 1 \\ -4 & 2\end{array}\right)$ as another possibility. For any choices of $a_{12}$ and $a_{22}$, we can solve for $a_{11}$ and $a_{21}$ to produce a matrix that satisfies $\mathbf{A}\binom{1}{2}=\binom{17}{0}$, so there are infinitely many possibilities for $\mathbf{A}$.
(b) Now, we have four equations for our four variables. As in part (a), we have
$$\begin{array}{l}
a_{11}+2 a_{12}=17 \\
a_{21}+2 a_{22}=0
\end{array}$$

From $\mathbf{A}\binom{-2}{-4}=\binom{-34}{0}$, we also have
$$\begin{array}{l}
-2 a_{11}-4 a_{12}=-34 \\
-2 a_{21}-4 a_{22}=0
\end{array}$$

Adding twice $a_{11}+2 a_{12}=17$ to $-2 a_{11}-4 a_{12}=-34$ gives us $0=0$. Uh-oh. The same happens when we add twice $a_{21}+2 a_{22}=0$ to $-2 a_{21}-4 a_{22}=0$. The second system of equations above is just -2 times the first

346

---

<!-- Page 347 -->

10.2. MULTIPLYING MATRICES

system! Since the new pair of equations is just the same as the pair of equations we already had, all the solutions in part (a) are also solutions here. Once again, there is not just one possible matrix A.
(c) Again, we must have $a_{11}+2 a_{12}=17$ and $a_{21}+2 a_{22}=0$. From $\mathbf{A}\binom{2}{-1}=\binom{-1}{5}$, we have $2 a_{11}-a_{12}=-1$ and $2 a_{21}-a_{22}=5$. The equations $2 a_{11}-a_{12}=-1$ and $a_{11}+2 a_{12}=17$ give us $a_{11}=3$ and $a_{12}=7$, and the other two equations give us $a_{21}=2$ and $a_{22}=-1$. So, in this part, we must indeed have $\mathbf{A}=\left(\begin{array}{cc}3 & 7 \\ 2 & -1\end{array}\right)$.

What made part (c) different from the other two parts? It isn't surprising that knowing what Av equals for one vector $\mathbf{v}$ isn't enough to figure out what $\mathbf{A}$ is, but why can we figure out what $\mathbf{A}$ is in part (c), but not in part (b)? Looking more closely at (b), we see that the two vectors multiplied by $\mathbf{A}$ are $\binom{1}{2}$ and $\binom{-2}{-4}$, which are not linearly independent. But the two vectors multiplied by A in part (c) are linearly independent. Maybe that's the key? Let's see.

Problem 10.12: Suppose $\mathbf{v}$ and $\mathbf{w}$ are linearly independent and $\mathbf{A}$ and $\mathbf{B}$ are matrices such that $\mathbf{A v}=\mathbf{B v}$ and $\mathbf{A w} \boldsymbol{=} \mathbf{B w}$.
(a) Why must $\mathbf{A i}=\mathbf{B i}$ ?
(b) Show that $\mathbf{A}=\mathbf{B}$.

Solution for Problem 10.12:
(a) In Problem 9.21, we showed that if $\mathbf{v}$ and $\mathbf{w}$ are linearly independent, then every point $(x, y)$ is in the graph of the parametric equation $\binom{x}{y}=p \mathbf{v}+q \mathbf{w}$, where $p$ and $q$ are parameters. Therefore, for any vector $\mathbf{u}$, there are scalars $p$ and $q$ such that $p \mathbf{v}+q \mathbf{w}=\mathbf{u}$. Specifically, there are scalars $r$ and $s$ such that $r \mathbf{v}+s \mathbf{w}=\mathbf{i}$. Adding $r$ times $\mathbf{A v}=\mathbf{B v}$ to $s$ times $\mathbf{A w}=\mathbf{B w}$ gives $r \mathbf{A v}+s \mathbf{A w}=r \mathbf{B v}+s \mathbf{B w}$, which we can manipulate as follows:
$$\begin{array}{rlrl}
r \mathbf{A} \mathbf{v}+s \mathbf{A} \mathbf{w} & =r \mathbf{B} \mathbf{v}+s \mathbf{B} \mathbf{w} \\
\Rightarrow & \mathbf{A}(r \mathbf{v})+\mathbf{A}(s \mathbf{w}) & =\mathbf{B}(r \mathbf{v})+\mathbf{B}(s \mathbf{w}) \\
\Rightarrow & \mathbf{A}(r \mathbf{v}+s \mathbf{w}) & =\mathbf{B}(r \mathbf{v}+s \mathbf{w})
\end{array}$$

We also know that $r \mathbf{v}+s \mathbf{w}=\mathbf{i}$, so we have $\mathbf{A i}=\mathbf{B i}$.
(b) In Problem 10.2, we saw that the first column of A is Ai. Therefore, part (a) tells us that the first column of $\mathbf{A}$ is the same as the first column of $\mathbf{B}$. By a similar argument to part (a), we can show that $\mathbf{A j}=\mathbf{B j}$, so the second column of $\mathbf{A}$ is the same as the second column of $\mathbf{B}$. Since $\mathbf{A}$ and $\mathbf{B}$ have the same first column and the same second column, we have $\mathbf{A}=\mathbf{B}$.

\begin{tabular}{ll} 
Important: & If $\mathbf{v}$ and $\mathbf{w}$ are linearly independent and $\mathbf{A}$ and $\mathbf{B}$ are matrices such that $\mathbf{A v}=\mathbf{B v}$ \\
and $\mathbf{A w}=\mathbf{B w}$, then $\mathbf{A}=\mathbf{B}$.
\end{tabular}

Exercises
10.2.1 Compute the following products:
(a) $\left(\begin{array}{cc}3 & 4 \\ -2 & -6\end{array}\right)\left(\begin{array}{cc}-1 & 0 \\ -5 & -7\end{array}\right)$
(b) $\quad\left(\begin{array}{cc}-4 & -8 \\ 0 & 9\end{array}\right)\left(\begin{array}{ll}-\frac{1}{2} & 2 \\ -3 & 3\end{array}\right)$

347

---

<!-- Page 348 -->

CHAPTER 10. MATRICES IN TWO DIMENSIONS
10.2.2 A $2 \times 2$ matrix is diagonal if it is of the form $\left(\begin{array}{cc}a_{1} & 0 \\ 0 & a_{2}\end{array}\right)$. Show that the product of two diagonal matrices is also diagonal.
10.2.3 Is there a matrix $\mathbf{F}$ such that for any matrix $\mathbf{A}$, the matrix $\mathbf{F A}$ is the matrix formed by swapping the rows of $\mathbf{A}$ ? If such a matrix exists, what is $\mathbf{A F}$ for that matrix?
10.2.4 If $\mathbf{A B}=\mathbf{0}$, then must either $\mathbf{A}$ or $\mathbf{B}$ be $\mathbf{0}$ ?
10.2.5 Let $\mathrm{T}\binom{4}{-3}=\binom{-3}{4}$ and $\mathrm{T}\binom{-3}{1}=\binom{0}{5}$. What is $\mathrm{T}\left(\begin{array}{cc}4 & -3 \\ -3 & 1\end{array}\right)$ ?
10.2.6 In Problem 10.11, we showed that there is more than one matrix $\mathbf{A}$ for which we have $\mathbf{A}\binom{1}{2}=\binom{17}{0}$ and $\mathbf{A}\binom{-2}{-4}=\binom{-34}{0}$. Our first step in doing so was letting $\mathbf{A}=\left(\begin{array}{ll}a_{11} & a_{12} \\ a_{21} & a_{22}\end{array}\right)$ and building systems of equations by multiplying out the left sides of the given equations. Did we have to do that in order to see that the two given equations are really the same equation?
10.3 Matrices as Transformations

Problems

Problem 10.13:
(a) Find a matrix I such that multiplying any vector by I leaves the vector unchanged. In other words, find $\mathbf{I}$ such that $\mathbf{I v}=\mathbf{v}$ for all vectors $\mathbf{v}$. Is this matrix unique?
(b) Do we have $\mathbf{I A}=\mathbf{A}$ for any matrix $\mathbf{A}$ ?

Problem 10.14: Find the matrix $\mathbf{A}$ such that $\mathbf{A v}=k \mathbf{v}$ for all vectors $\mathbf{v}$, where $k$ is a scalar.
Problem 10.15: In this problem, we show that there is a matrix $\mathbf{N}$ such that $\mathbf{N v}$ is a $90^{\circ}$ counterclockwise rotation of $\mathbf{v}$ for all $\mathbf{v}$.
(a) Let $\mathbf{v}=\binom{x}{y}$. Find the image of the point $(x, y)$ under a $90^{\circ}$ counterclockwise rotation. Use your result to find the desired matrix $\mathbf{N}$.
(b) Use part (a) to show that a $90^{\circ}$ counterclockwise rotation is a linear transformation. In other words, show that the image of a $90^{\circ}$ counterclockwise rotation of $c \mathbf{v}$ is $c$ times the $90^{\circ}$ counterclockwise rotation of $\mathbf{v}$, and the image of a $90^{\circ}$ counterclockwise rotation of $\mathbf{v}+\mathbf{w}$ is the sum of the $90^{\circ}$ counterclockwise rotations of $\mathbf{v}$ and $\mathbf{w}$.

Problem 10.16: In this problem, we find a matrix $\mathbf{T}$ such that the vector $\mathbf{T v}$ is a counterclockwise rotation of the vector $\mathbf{v}$ by an angle $\phi$.
(a) Let $\mathbf{v}=\binom{x}{y}$. Suppose the point $P$ is the image upon rotating the point $(x, y)$ an angle $\phi$ counterclockwise about the origin. What are the coordinates of $P$ ?
(b) Find the desired matrix $\mathbf{T}$. Test your matrix by finding $\mathbf{T}$ for $\phi=0^{\circ}$ and $\phi=90^{\circ}$.

348

---

<!-- Page 349 -->

10.3. MATRICES AS TRANSFORMATIONS

Problem 10.17: A sequence $\left(a_{1}, b_{1}\right),\left(a_{2}, b_{2}\right),\left(a_{3}, b_{3}\right), \ldots$ of points in the coordinate plane satisfies
$$\left(a_{n+1}, b_{n+1}\right)=\left(\sqrt{3} a_{n}-b_{n}, \sqrt{3} b_{n}+a_{n}\right)$$
for $n=1,2,3, \ldots$. Suppose that $\left(a_{100}, b_{100}\right)=(2,4)$. What is $a_{1}+b_{1}$ ? (Source: AMC 12)
Problem 10.18: Let $\mathbf{v}=\binom{x}{y}$ and $z$ be the complex number $x+y i$.
(a) Find the matrix $\mathbf{C}$ such that $\mathbf{C v}=\binom{\operatorname{Re}(z i)}{\operatorname{Im}(z i)}$. In other words, find the matrix $\mathbf{C}$ such that multiplying $\mathbf{v}$ by C corresponds to multiplying $z$ by $i$.
(b) Find the matrix $\mathbf{D}$ such that multiplying $\mathbf{v}$ by $\mathbf{D}$ corresponds to multiplying $z$ by $a+b i$. (Your answer should be a matrix whose entries are in terms of $a$ and $b$.)

Problem 10.19: As a reminder, we say that a function $f$ with domain $\mathbb{R}^{2}$ is a linear function if
(i) $f(a \mathbf{v})=a f(\mathbf{v})$ for all scalars $a$ and vectors $\mathbf{v}$, and
(ii) $f(\mathbf{v}+\mathbf{w})=f(\mathbf{v})+f(\mathbf{w})$ for all vectors $\mathbf{v}$ and $\mathbf{w}$.

Suppose $g(\mathbf{w})$ is a linear function that maps vectors to vectors.
(a) Explain why $g(x \mathbf{i}+y \mathbf{j})=x g(\mathbf{i})+y g(\mathbf{j})$.
(b) Why does part (a) tell us that there exists some matrix $\mathbf{A}$ such that $g(\mathbf{w})=\mathbf{A w}$ for all $\mathbf{w}$ ?

Problem 10.13:
(a) Find the matrix I such that multiplying any vector by I leaves the vector unchanged. In other words, find $\mathbf{I}$ such that $\mathbf{I v}=\mathbf{v}$ for all vectors $\mathbf{v}$. Is this matrix unique?
(b) Do we have $\mathbf{I A}=\mathbf{A I}=\mathbf{A}$ for any matrix $\mathbf{A}$ ?

Solution for Problem 10.13:
(a) From Problem 10.2, we know that the first column of $\mathbf{I}$ is $\mathbf{I i}$. Since $\mathbf{I} \mathbf{v}=\mathbf{v}$ for all $\mathbf{v}$, we have $\mathbf{I}=\mathbf{i}$, so the first column of $\mathbf{I}$ is $\mathbf{i}$. Similarly, we have $\mathbf{I} \mathbf{j}=\mathbf{j}$, so the second column of $\mathbf{I}$ must be $\mathbf{j}$. So, if there is a matrix $\mathbf{I}$ such that $\mathbf{I v}=\mathbf{v}$, then it must be
$$\mathbf{I}=\left(\begin{array}{ll}
1 & 0 \\
0 & 1
\end{array}\right) .$$

We aren't quite finished! We have only shown that if there is a matrix such that $\mathbf{I v}=\mathbf{v}$, then it must be $\mathbf{I}=\left(\begin{array}{ll}1 & 0 \\ 0 & 1\end{array}\right)$. We have not shown that this matrix satisfies $\mathbf{I} \mathbf{v}=\mathbf{v}$ for all $\mathbf{v}$; we've only shown that $\mathbf{I} \mathbf{v}=\mathbf{v}$ when $\mathbf{v}$ is $\mathbf{i}$ or $\mathbf{j}$. Fortunately, we can patch this hole very quickly:
$$\left(\begin{array}{ll}
1 & 0 \\
0 & 1
\end{array}\right)\binom{x}{y}=\binom{x}{y},$$
so $\left(\begin{array}{ll}1 & 0 \\ 0 & 1\end{array}\right) \mathbf{v}=\mathbf{v}$ for all $\mathbf{v}$.

349

---

<!-- Page 350 -->

CHAPTER 10. MATRICES IN TWO DIMENSIONS

WARNING!!

Make sure you see why the second part of our solution is necessary. Our first step of considering Ii and Ij only tells us that what the columns of I must be if a matrix with the desired property exists. We need the last part of the solution to show that the matrix thus constructed does indeed satisfy $\mathbf{I} \mathbf{v}=\mathbf{v}$ for all $\mathbf{v}$.
(b) First, we show that $\mathbf{I A}=\mathbf{A}$. The first column of $\mathbf{I A}$ is the product of $\mathbf{I}$ and the first column of $\mathbf{A}$, which is just the first column of A. Similarly, the second column of IA must be the second column of A, so IA = A. We also could have written out both matrices to confirm:
$$\left(\begin{array}{ll}
1 & 0 \\
0 & 1
\end{array}\right)\left(\begin{array}{ll}
a_{11} & a_{12} \\
a_{21} & a_{22}
\end{array}\right)=\left(\begin{array}{ll}
a_{11} & a_{12} \\
a_{21} & a_{22}
\end{array}\right) .$$

For yet another solution, note that part (a) gives $\mathbf{u s} \mathbf{I}(\mathbf{A v})=\mathbf{A v}$ for any matrix $\mathbf{A}$ and vector $\mathbf{v}$. We also have $\mathbf{I}(\mathbf{A v})=(\mathbf{I A}) \mathbf{v}$. Therefore, we must have $(\mathbf{I A}) \mathbf{v}=\mathbf{A v}$ for all vectors $\mathbf{v}$, so $\mathbf{I A}=\mathbf{A}$.

To show that $\mathbf{A I}=\mathbf{A}$, we can again write out both matrices:
$$\left(\begin{array}{ll}
a_{11} & a_{12} \\
a_{21} & a_{22}
\end{array}\right)\left(\begin{array}{ll}
1 & 0 \\
0 & 1
\end{array}\right)=\left(\begin{array}{ll}
a_{11} & a_{12} \\
a_{21} & a_{22}
\end{array}\right) .$$

We could also again use part (a). We have $(\mathbf{A I}) \mathbf{v}=\mathbf{A}(\mathbf{I v})=\mathbf{A v}$ for all vectors $\mathbf{v}$, so we have $\mathbf{A I}=\mathbf{A}$.

Important: The matrix
$$\mathbf{I}=\left(\begin{array}{ll}
1 & 0 \\
0 & 1
\end{array}\right)$$
is called the identity matrix. Multiplying a vector $\mathbf{v}$ by $\mathbf{I}$ leaves the vector unchanged; in other words, $\mathbf{I v}=\mathbf{v}$ for all vectors $\mathbf{v}$. We also have $\mathbf{I A}=\mathbf{A I}=\mathbf{A}$ for any $2 \times 2$ matrix $\mathbf{A}$.

Problem 10.14: Find the matrix $\mathbf{A}$ such that $\mathbf{A v}=k \mathbf{v}$ for all vectors $\mathbf{v}$, where $k$ is a scalar.

Solution for Problem 10.14: Solution 1: Equate corresponding components. Performing the multiplications on both sides of
$$\left(\begin{array}{ll}
a & b \\
c & d
\end{array}\right)\binom{x}{y}=k\binom{x}{y}$$
gives
$$\binom{a x+b y}{c x+d y}=\binom{k x}{k y} .$$

From $a x+b y=k x$, we have $a=k$ and $b=0$, and from $c x+d y=k y$, we have $c=0$ and $d=k$. Checking, we see that
$$\left(\begin{array}{ll}
k & 0 \\
0 & k
\end{array}\right)\binom{x}{y}=\binom{k x}{k y}=k\binom{x}{y}$$
for all $x$ and $y$, as desired.
Solution 2: Apply the result of Problem 10.2. We must have $\mathbf{A v}=k \mathbf{v}$ for all $\mathbf{v}$, so we must have $\mathbf{A i}=k \mathbf{i}$ and $\mathbf{A j}=k \mathbf{j}$. Therefore, if there is a matrix $\mathbf{A}$ such that $\mathbf{A v}=k \mathbf{v}$ for all $\mathbf{v}$, then the first column of $\mathbf{A}$ must be $k \mathbf{i}$ and the second must be $k \mathbf{j}$. We can quickly confirm that $\left(\begin{array}{ll}k & 0 \\ 0 & k\end{array}\right)\binom{x}{y}=k\binom{x}{y}$, so $\mathbf{A}=\left(\begin{array}{ll}k & 0 \\ 0 & k\end{array}\right)$ is the desired matrix.

So far, we have discovered a matrix that does nothing (the identity) and a family of matrices that scale vectors. Now, we turn to matrices that rotate vectors.

350

---

<!-- Page 351 -->

10.3. MATRICES AS TRANSFORMATIONS

Problem 10.15: In this problem, we show that there is a matrix $\mathbf{N}$ such that $\mathbf{N v}$ is a $90^{\circ}$ counterclockwise rotation of $\mathbf{v}$ for all $\mathbf{v}$.
(a) Let $\mathbf{v}=\binom{x}{y}$. Find the image of the point $(x, y)$ under a $90^{\circ}$ counterclockwise rotation. Use your result to find the desired matrix $\mathbf{N}$.
(b) Use part (a) to show that a $90^{\circ}$ counterclockwise rotation is a linear transformation. In other words, show that the image of a $90^{\circ}$ counterclockwise rotation of cv is c times the $90^{\circ}$ counterclockwise rotation of $\mathbf{v}$, and the image of a $90^{\circ}$ counterclockwise rotation of $\mathbf{v}+\mathbf{w}$ is the sum of the $90^{\circ}$ counterclockwise rotations of $\mathbf{v}$ and $\mathbf{w}$.

Solution for Problem 10.15:
(a) What's wrong with the following solution:

Bogus Solution: A $90^{\circ}$ counterclockwise rotation of $\mathbf{i}$ is $\mathbf{j}$, and a $90^{\circ}$ counterclockwise ro-
tation of $\mathbf{j}$ is $-\mathbf{i}$. The product $\mathbf{N i}$ equals the first column of $\mathbf{N}$, so the first column of $\mathbf{N}$ is $\mathbf{j}$. Similarly, the second column of $\mathbf{N}$ is $\mathbf{N j}$, which equals $-\mathbf{i}$. Therefore, $\mathbf{N}=\left(\begin{array}{cc}0 & -1 \\ 1 & 0\end{array}\right)$.

This bogus solution does find the correct matrix. Moreover, the bogus solution shows that if the desired matrix exists, then $\left(\begin{array}{cc}0 & -1 \\ 1 & 0\end{array}\right)$ must be that matrix. However, the solution does not show that $\mathbf{N v}$ is a $90^{\circ}$ counterclockwise rotation of $\mathbf{v}$ for all $\mathbf{v}$.

Our first step in testing that Nv is a $90^{\circ}$ counterclockwise rotation of $\mathbf{v}$ for all $\mathbf{v}$ is to figure out, in terms of $x$ and $y$, what vector results when $\mathbf{v}$ is rotated $90^{\circ}$ counterclockwise. We let $P$ be ( $x, y$ ) and $P^{\prime}$ be the image of $P$ upon a $90^{\circ}$ counterclockwise rotation. Rotation is often easier to analyze with polar coordinates. We let the polar coordinates of $P$ be $(r, \theta)$, so the polar coordinates of $P^{\prime}$ are $\left(r, \theta+90^{\circ}\right)$. Converting these to rectangular coordinates, the rectangular coordinates of $P$ are $x=r \cos \theta$ and $y=r \sin \theta$, and the rectangular coordinates of $P^{\prime}$ are
$$\begin{array}{l}
x^{\prime}=r \cos \left(\theta+90^{\circ}\right)=r\left(\cos \theta \cos 90^{\circ}-\sin \theta \sin 90^{\circ}\right)=-r \sin \theta \\
y^{\prime}=r \sin \left(\theta+90^{\circ}\right)=r\left(\sin \theta \cos 90^{\circ}+\sin 90^{\circ} \cos \theta\right)=r \cos \theta
\end{array}$$

Comparing our expressions for $x^{\prime}$ and $y^{\prime}$ to those for $x$ and $y$, we find that $x^{\prime}=-y$ and $y^{\prime}=x$, so the rectangular coordinates of $P^{\prime}$ are $(-y, x)$.

Now we can check that the matrix we found in the Bogus Solution does indeed produce the desired result for all vectors $\mathbf{v}$ :
$$\left(\begin{array}{cc}
0 & -1 \\
1 & 0
\end{array}\right)\binom{x}{y}=\binom{-y}{x} .$$

This matches our work above and thereby tells us that $\left(\begin{array}{cc}0 & -1 \\ 1 & 0\end{array}\right) \mathbf{v}$ is indeed a $90^{\circ}$ counterclockwise rotation of $\mathbf{v}$ for all $\mathbf{v}$.
(b) We showed earlier that the function represented by a matrix is a linear function. That is, we have $\mathbf{N}(c \mathbf{v})=c \mathbf{N v}$ and $\mathbf{N}(\mathbf{v}+\mathbf{w})=\mathbf{N v}+\mathbf{N w}$ for any scalar $c$ and any vectors $\mathbf{v}$ and $\mathbf{w}$. The fact that we can represent a $90^{\circ}$ counterclockwise rotation of a vector as multiplication by a matrix $\mathbf{N}$ tells us that such a rotation is linear, too.

Important: If a function that maps a vector to another vector can be represented by a matrix,
then the function is linear.

351

---

<!-- Page 352 -->

CHAPTER 10. MATRICES IN TWO DIMENSIONS

We'll now generalize Problem 10.15.
Problem 10.16: Given an angle $\phi$, find a matrix $\mathbf{T}$ such that for any vector $\mathbf{v}$, the vector $\mathbf{T v}$ is a counterclockwise rotation of $\mathbf{v}$ by $\phi$.

Solution for Problem 10.16: We use our solution for a $90^{\circ}$ rotation as our guide. We let $P$ be $(x, y)$ and $P^{\prime}$ be the image of $P$ upon a counterclockwise rotation by angle $\phi$. Rotation suggests polar coordinates, so we let $(r, \theta)$ be the polar coordinates of $P$, which means that $x=r \cos \theta, y=r \sin \theta$, and the polar coordinates of $P^{\prime}$ are ( $r, \theta+\phi$ ). If ( $x^{\prime}, y^{\prime}$ ) are the rectangular coordinates of $P^{\prime}$, then we must have
$$\begin{array}{l}
x^{\prime}=r \cos (\theta+\phi)=r \cos \theta \cos \phi-r \sin \theta \sin \phi=x \cos \phi-y \sin \phi \\
y^{\prime}=r \sin (\theta+\phi)=r \sin \theta \cos \phi+r \cos \theta \sin \phi=y \cos \phi+x \sin \phi
\end{array}$$

We could now find the columns of $\mathbf{T}$ by finding $\mathbf{T i}$ and $\mathbf{T j}$, and then confirm that the resulting matrix produces the desired expression for $\mathbf{T v}$ for any $\mathbf{v}$. Or, we could simply consider the product $\mathbf{T}\binom{x}{y}$ and compare it directly to the desired result. Taking the latter approach, we seek the matrix such that
$$\left(\begin{array}{ll}
a & b \\
c & d
\end{array}\right)\binom{x}{y}=\binom{x^{\prime}}{y^{\prime}}=\binom{x \cos \phi-y \sin \phi}{x \sin \phi+y \cos \phi} .$$

Therefore, we must have $a x+b y=x \cos \phi-y \sin \phi$ and $c x+d y=x \sin \phi+y \cos \phi$, which means our desired matrix is
$$\left(\begin{array}{cc}
\cos \phi & -\sin \phi \\
\sin \phi & \cos \phi
\end{array}\right) .$$

We can test that our matrix produces the correct result when $\phi=0^{\circ}$ and $\phi=90^{\circ}$. A rotation of $0^{\circ}$ is the identity transformation-nothing is changed. Sure enough, setting $\phi=0^{\circ}$ gives us
$$\left(\begin{array}{cc}
\cos 0^{\circ} & -\sin 0^{\circ} \\
\sin 0^{\circ} & \cos 0^{\circ}
\end{array}\right)=\left(\begin{array}{ll}
1 & 0 \\
0 & 1
\end{array}\right),$$
which is the identity matrix.
When $\phi=90^{\circ}$, we have
$$\left(\begin{array}{cc}
\cos 90^{\circ} & -\sin 90^{\circ} \\
\sin 90^{\circ} & \cos 90^{\circ}
\end{array}\right)=\left(\begin{array}{cc}
0 & -1 \\
1 & 0
\end{array}\right),$$
which is the matrix we found in Problem 10.15 for a $90^{\circ}$ counterclockwise rotation.

Important: If
$!!$
$$\mathbf{T}=\left(\begin{array}{cc}
\cos \phi & -\sin \phi \\
\sin \phi & \cos \phi
\end{array}\right)$$
then $\mathbf{T v}$ is a counterclockwise rotation of $\mathbf{v}$ by an angle of $\phi$.

Problem 10.17: A sequence $\left(a_{1}, b_{1}\right),\left(a_{2}, b_{2}\right),\left(a_{3}, b_{3}\right), \ldots$ of points in the coordinate plane satisfies
$$\left(a_{n+1}, b_{n+1}\right)=\left(\sqrt{3} a_{n}-b_{n}, \sqrt{3} b_{n}+a_{n}\right)$$
for $n=1,2,3, \ldots$. Suppose that $\left(a_{100}, b_{100}\right)=(2,4)$. What is $a_{1}+b_{1}$ ? (Source: AMC 12)

352

---

<!-- Page 353 -->

10.3. MATRICES AS TRANSFORMATIONS

Solution for Problem 10.17: The ordered pair $\left(\sqrt{3} a_{n}-b_{n}, \sqrt{3} b_{n}+a_{n}\right)$ is a linear combination of the components of the ordered pair $\left(a_{n}, b_{n}\right)$. This means that we can represent $\binom{\sqrt{3} a_{n}-b_{n}}{\sqrt{3} b_{n}+a_{n}}$ as the product of matrix and $\binom{a_{n}}{b_{n}}$. Specifically, we have
$$\binom{a_{n+1}}{b_{n+1}}=\binom{\sqrt{3} a_{n}-b_{n}}{\sqrt{3} b_{n}+a_{n}}=\left(\begin{array}{cc}
\sqrt{3} & -1 \\
1 & \sqrt{3}
\end{array}\right)\binom{a_{n}}{b_{n}} .$$

The $\sqrt{3}$ entries make us think of rotation, but the entries clearly cannot all be cosines and sines because cosines and sines cannot be greater than 1 . However, dividing all the entries in the matrix by 2 (factoring the scalar 2 out of the matrix) gives us some very familiar fractions:
$$\binom{a_{n+1}}{b_{n+1}}=2\left(\begin{array}{cc}
\sqrt{3} / 2 & -1 / 2 \\
1 / 2 & \sqrt{3} / 2
\end{array}\right)\binom{a_{n}}{b_{n}}$$

Now, we're in familiar territory, and we see that
$$\binom{a_{n+1}}{b_{n+1}}=2\left(\begin{array}{cc}
\cos 30^{\circ} & -\sin 30^{\circ} \\
\sin 30^{\circ} & \cos 30^{\circ}
\end{array}\right)\binom{a_{n}}{b_{n}}$$

The product $\left(\begin{array}{rr}\cos 30^{\circ} & -\sin 30^{\circ} \\ \sin 30^{\circ} & \cos 30^{\circ}\end{array}\right)\binom{a_{n}}{b_{n}}$ gives us a vector that is a $30^{\circ}$ counterclockwise rotation of $\binom{a_{n}}{b_{n}}$. Letting $\mathbf{T}=\left(\begin{array}{cc}\cos 30^{\circ} & -\sin 30^{\circ} \\ \sin 30^{\circ} & \cos 30^{\circ}\end{array}\right)$ and $\mathbf{v}_{n}=\binom{a_{n}}{b_{n}}$, we have
$$\mathbf{v}_{100}=2 \mathbf{T} \mathbf{v}_{99}=2 \mathbf{T}\left(2 \mathbf{T} \mathbf{v}_{98}\right)=\cdots=2^{99} \underbrace{\mathbf{T} \cdots \mathbf{T}}_{99 \mathbf{T}^{\prime} \mathbf{s}} \mathbf{v}_{1}$$

Just as we use an exponent to denote a repeated product of any number, we can write the product of $99 \mathbf{T}^{\prime}$ s as $\mathbf{T}^{99}$, so we have
$$\mathbf{v}_{100}=2^{99} \mathbf{T}^{99} \mathbf{v}_{1}$$

We know that $\mathbf{T} \mathbf{v}_{1}$ is a $30^{\circ}$ counterclockwise rotation of $\mathbf{v}_{1}$, so $\mathbf{T}^{12} \mathbf{v}_{1}$ is a $12 \cdot 30^{\circ}=360^{\circ}$ rotation of $\mathbf{v}_{1}$. Therefore, we have $\mathbf{T}^{12} \mathbf{v}_{1}=\mathbf{v}_{1}$, which means that $\mathbf{T}^{12}=\mathbf{I}$. Since $99=3+12 \cdot 8$, we have
$$\mathbf{v}_{100}=2^{99} \mathbf{T}^{99} \mathbf{v}_{1}=2^{99} \mathbf{T}^{3}\left(\mathbf{T}^{12}\right)^{8} \mathbf{v}_{1}=2^{99} \mathbf{T}^{3} \mathbf{v}_{1}$$

Since $\mathbf{T} \mathbf{v}_{1}$ is a $30^{\circ}$ counterclockwise rotation of $\mathbf{v}_{1}$, the product $\mathbf{T}^{3} \mathbf{v}_{1}$ gives us a vector that is a $90^{\circ}$ counterclockwise rotation of $\mathbf{v}_{1}$. So, we have
$$\mathbf{v}_{100}=2^{99}\left(\begin{array}{cc}
\cos 90^{\circ} & -\sin 90^{\circ} \\
\sin 90^{\circ} & \cos 90^{\circ}
\end{array}\right)\binom{a_{1}}{b_{1}}=2^{99}\left(\begin{array}{cc}
0 & -1 \\
1 & 0
\end{array}\right)\binom{a_{1}}{b_{1}}=2^{99}\binom{-b_{1}}{a_{1}},$$
which means $\binom{a_{100}}{b_{100}}=\binom{-2^{99} b_{1}}{2^{99} a_{1}}$. We are given that $a_{100}=2$ and $b_{100}=4$, so
$$a_{1}+b_{1}=\frac{b_{100}}{2^{99}}-\frac{a_{100}}{2^{99}}=\frac{4-2}{2^{99}}=\frac{1}{2^{98}}$$

Problem 10.18: Let $\mathbf{v}=\binom{x}{y}$. Find the matrix $\mathbf{D}$ such that multiplying $\mathbf{v}$ by $\mathbf{D}$ corresponds to multiplying $x+y i$ by $a+b i$. (Your answer should be a matrix whose entries are in terms of $a$ and $b$.)

353

---

<!-- Page 354 -->

CHAPTER 10. MATRICES IN TWO DIMENSIONS

Solution for Problem 10.18: We have
$$(a+b i)(x+y i)=(a x-b y)+(b x+a y) i .$$

Therefore, we must have
$$\mathbf{D}\binom{x}{y}=\binom{a x-b y}{b x+a y} .$$

From this, we can easily read the components of $\mathbf{D}$ :
$$\left(\begin{array}{cc}
a & -b \\
b & a
\end{array}\right)\binom{x}{y}=\binom{a x-b y}{b x+a y} .$$

We've seen now that a great many different transformations of vectors can be represented by matrices. Now, we turn to our claim on page 338 that any linear function that maps vectors to vectors can be represented as multiplication by a matrix.

Problem 10.19: As a reminder, we say that a function $f$ with domain $\mathbb{R}^{2}$ is a linear function if
(i) $f(a \mathbf{v})=a f(\mathbf{v})$ for all scalars $a$ and vectors $\mathbf{v}$, and
(ii) $f(\mathbf{v}+\mathbf{w})=f(\mathbf{v})+f(\mathbf{w})$ for all vectors $\mathbf{v}$ and $\mathbf{w}$.

Suppose $g(\mathbf{w})$ is a linear function that maps vectors to vectors.
(a) Explain why $g(x \mathbf{i}+y \mathbf{j})=x g(\mathbf{i})+y g(\mathbf{j})$.
(b) Why does part (a) tell us that there exists some matrix $\mathbf{A}$ such that $g(\mathbf{w})=\mathbf{A w}$ for all $\mathbf{w}$ ?

Solution for Problem 10.19:
(a) Applying item (ii) in our definition of a linear function, we have $g(x \mathbf{i}+y \mathbf{j})=g(x \mathbf{i})+g(y \mathbf{j})$. Then, we apply item (i) twice to find $g(x \mathbf{i})+g(y \mathbf{j})=x g(\mathbf{i})+y g(\mathbf{j})$. Therefore, we have $g(x \mathbf{i}+y \mathbf{j})=x g(\mathbf{i})+y g(\mathbf{j})$.
(b) We can write any vector $\mathbf{v}$ as $v_{1} \mathbf{i}+v_{2} \mathbf{j}$ for some scalars $v_{1}$ and $v_{2}$. So, for any linear function $g$, applying part (a) gives us
$$g(\mathbf{v})=g\left(v_{1} \mathbf{i}+v_{2} \mathbf{j}\right)=v_{1} g(\mathbf{i})+v_{2} g(\mathbf{j}) .$$

Since $g$ maps vectors to vectors, there exist scalars $a_{11}, a_{21}, a_{12}$, and $a_{22}$ such that $g(\mathbf{i})=a_{11} \mathbf{i}+a_{21} \mathbf{j}$ and $g(\mathbf{j})=a_{12} \mathbf{i}+a_{22} \mathbf{j}$. Therefore, we have
$$g(\mathbf{v})=v_{1}\left(a_{11} \mathbf{i}+a_{21} \mathbf{j}\right)+v_{2}\left(a_{12} \mathbf{i}+a_{22} \mathbf{j}\right)=\left(v_{1} a_{11}+v_{2} a_{12}\right) \mathbf{i}+\left(v_{1} a_{21}+v_{2} a_{22}\right) \mathbf{j} .$$

If you don't see Av on the right side in this notation, perhaps you will if we write the right side like this:
$$g(\mathbf{v})=\binom{v_{1} a_{11}+v_{2} a_{12}}{v_{1} a_{21}+v_{2} a_{22}}=\left(\begin{array}{ll}
a_{11} & a_{12} \\
a_{21} & a_{22}
\end{array}\right)\binom{v_{1}}{v_{2}} .$$

Letting $\mathbf{A}=\left(\begin{array}{ll}a_{11} & a_{12} \\ a_{21} & a_{22}\end{array}\right)$, we have shown that there is a matrix $\mathbf{A}$ such that $g(\mathbf{v})=\mathbf{A v}$ for all $\mathbf{v}$. The columns of $\mathbf{A}$ are $g(\mathbf{i})$ and $g(\mathbf{j})$, so $\mathbf{A}$ is uniquely determined by $g$. Therefore, we have proved the following:

Important: Any linear function that maps vectors to vectors can be expressed as multipli- cation by a matrix, where the columns of the matrix are given by the vectors to which $\mathbf{i}$ and $\mathbf{j}$ are mapped by the function.

354

---

<!-- Page 355 -->

10.4. THE DETERMINANT

The final observation above gives us a very easy way to re-create the matrices we discovered in this chapter whenever we need them. For example, now that we know that rotation is a linear transformation, to find the matrix $\mathbf{N}$ that corresponds to a $90^{\circ}$ counterclockwise rotation, we only need to find $\mathbf{N i}$ and $\mathbf{N j}$. A $90^{\circ}$ counterclockwise rotation of $\mathbf{i}$ is $\mathbf{j}$, and a $90^{\circ}$ counterclockwise rotation of $\mathbf{j}$ is $-\mathbf{i}$. Therefore, the first column of $\mathbf{N}$ is $\mathbf{j}$ and the second is $-\mathbf{i}$, which means $\mathbf{N}=\left(\begin{array}{cc}0 & -1 \\ 1 & 0\end{array}\right)$. Similarly, we can determine the effect of any linear transformation on any vector by examining the effect of the transformation on the easy-to-handle vectors $\mathbf{i}$ and $\mathbf{j}$.

Exercises
10.3.1 Suppose that $\mathbf{A}\binom{3}{-2}=\binom{3}{-2}$. Must $\mathbf{A}$ be the identity matrix? If not, find a possible matrix $\mathbf{A}$ besides $\mathbf{I}$.
10.3.2 Suppose a function $g$ maps the vector $\mathbf{v}$ to the reflection of $\mathbf{v}$ over the $x$-axis. Is there a matrix $\mathbf{A}$ such that $g(\mathbf{v})=\mathbf{A v}$ for all vectors $\mathbf{v}$ ? If so, find it. If not, explain why there is not.
10.3.3 Suppose a function $f$ maps the vector $\binom{x}{y}$ to the vector $\binom{x^{2}}{y^{2}}$. Is there a matrix $\mathbf{A}$ such that $f(\mathbf{v})=\mathbf{A v}$ for all vectors $\mathbf{v}$ ? If so, find it. If not, explain why there is not.
10.3.4 Show how to use the rotation matrix we discovered in Problem 10.16 to recall the angle sum identities for sine and cosine.
10.3.5 Suppose a point $P$ is reflected over the $x$-axis and the image is rotated $90^{\circ}$ counterclockwise about the origin. Is the result the same as if we first rotate $P$ by $90^{\circ}$ counterclockwise about the origin, and then reflect the result over the $x$-axis?
10.4 The Determinant

We introduced $2 \times 2$ matrices with a system of two linear equations with two variables. We start this section by considering when it is possible to find a unique solution to such a system.

Problem 10.20: Let $a, b, c, d, u$, and $v$ be constants in the system of equations
$$\begin{array}{l}
a x+b y=u \\
c x+d y=v
\end{array}$$
(a) Show that if $a d-b c \neq 0$, then the system has a unique solution $(x, y)$.
(b) Show that if $a d-b c=0$, then the system either has no solutions $(x, y)$ or has infinitely many solutions.

Solution for Problem 10.20:
(a) We eliminate $y$ by multiplying the first equation by $d$ and the second by $b$ to get
$$\begin{aligned}
a d x+b d y & =d u \\
b c x+b d y & =b v
\end{aligned}$$
and then subtracting the second equation from the first to find
$$a d x-b c x=d u-b v$$

355

---

<!-- Page 356 -->

CHAPTER 10. MATRICES IN TWO DIMENSIONS

Factoring the left gives $(a d-b c) x=d u-b v$. Since $a d-b c \neq 0$, we can solve for $x$ by dividing both sides to find
$$x=\frac{d u-b v}{a d-b c} .$$

Similarly, we find $y$ by subtracting $c$ times $a x+b y=u$ from $a$ times $c x+d y=v$ to get
$$(a d-b c) y=a v-c u$$

Once again, we need to have $a d-b c \neq 0$ in order to divide both sides by $a d-b c$ to produce
$$y=\frac{a v-c u}{a d-b c}$$

Therefore, if $a d-b c \neq 0$, the system has the unique solution $(x, y)=\left(\frac{d u-b v}{a d-b c}, \frac{a v-c u}{a d-b c}\right)$.
(b) Before tackling the proof that there are either no solutions or infinitely many solutions, we'll get some geometric intuition for what's going on. The graphs of the two equations in the system are lines with direction vectors $\binom{-b}{a}$ and $\binom{-d}{c}$, respectively. These lines either don't intersect (and the system has no solutions) or are the same line (and the system has infinitely many solutions) if and only if $\binom{-b}{a}=k\binom{-d}{c}$ for some scalar $k$, or if $c=d=0$. In either case, we have $a d-b c=0$, since $b=k d$ and $a=k c$ gives $a d-b c=k c d-k c d=0$, and $c=d=0$ gives $a d-b c=0$.

Now, let's take a more rigorous approach. In part (a), we showed that the system of equations implies the equations
$$\begin{array}{l}
(a d-b c) x=d u-b v \\
(a d-b c) y=a v-c u
\end{array}$$

If $a d-b c=0$, then these equations become
$$\begin{array}{l}
0=d u-b v \\
0=a v-c u
\end{array}$$

So, if $d u-b v \neq 0$ or $a v-c u \neq 0$, then the corresponding equation above cannot be true, which means the system has no solutions. If $d u-b v=0$ and $a v-c u=0$, then we have $d u=b v$ and $a v=c u$. To see what this means for our original system of equations, $a x+b y=u, c x+d y=v$, we multiply the first by $v$ and the second by $u$, to get
$$\begin{array}{l}
a v x+b v y=u v \\
c u x+d u y=u v
\end{array}$$

If $d u=b v$ and $a v=c u$, then these two equations are the same, so any of the infinitely many solutions $(x, y)$ to the first equation are also solutions to the second. If $u$ and $v$ are nonzero, then dividing the first equation above by $v$ and the second by $u$ shows that these infinitely many values of $(x, y)$ are solutions to the original system. With some careful casework, we can show that even if $u$ or $v$ is 0 , then these infinitely many values of $(x, y)$ are still solutions to the original system.

Therefore, if $a d-b c=0$, the system
$$\begin{array}{l}
a x+b y=u \\
c x+d y=v
\end{array}$$
either has no solutions or it has infinitely many solutions.

356

---

<!-- Page 357 -->

10.4. THE DETERMINANT

We can write the original system of equations in Problem 10.20 as
$$\left(\begin{array}{ll}
a & b \\
c & d
\end{array}\right)\binom{x}{y}=\binom{u}{v} .$$

Our work in the solution shows that this system has a unique solution $\binom{x}{y}$ if and only if $a d-b c \neq 0$. This is such an important property that for any matrix $\left(\begin{array}{ll}a & b \\ c & d\end{array}\right)$, we have a special name for the quantity $a d-b c$.

Definition: The determinant of the matrix $\left(\begin{array}{ll}a & b \\ c & d\end{array}\right)$ is the quantity $a d-b c$. We often denote this determinant as $\left|\begin{array}{ll}a & b \\ c & d\end{array}\right|$, so
$$\left|\begin{array}{ll}
a & b \\
c & d
\end{array}\right|=a d-b c .$$

We also can denote the determinant of a matrix $\mathbf{A}$ as $\operatorname{det}(\mathbf{A})$.
In Problem 10.20, we proved that if $a d-b c \neq 0$, then the system of equations
$$\begin{array}{l}
a x+b y=u \\
c x+d y=v
\end{array}$$
has the unique solution $(x, y)=\left(\frac{d u-b v}{a d-b c}, \frac{a v-c u}{a d-b c}\right)$. We can write this solution in terms of determinants:
$$x=\frac{\left|\begin{array}{ll}
u & b \\
v & d
\end{array}\right|}{\left|\begin{array}{ll}
a & b \\
c & d
\end{array}\right|}, \quad y=\frac{\left|\begin{array}{ll}
a & u \\
c & v
\end{array}\right|}{\left|\begin{array}{ll}
a & b \\
c & d
\end{array}\right|} .$$

If we express the system of equations as $\mathbf{M}\binom{x}{y}=\binom{u}{v}$, where $\mathbf{M}=\left(\begin{array}{ll}a & b \\ c & d\end{array}\right)$, we see that each denominator in the solution to the system is $\operatorname{det}(\mathbf{M})$. The numerator of $x$ is the determinant of the matrix formed by replacing the first column of $\mathbf{M}$ (which corresponds to the coefficients of $x$ in the system of equations) with the column $\binom{u}{v}$. Similarly, we find the numerator of $y$ by replacing the second column of $\mathbf{M}$ with $\binom{u}{v}$ and then taking the determinant of the resulting matrix. This method for solving a system of two linear equations with two variables is referred to as Cramer's rule.

For the rest of this section, we will explore properties of the determinant.
Problems
Problem 10.21: Solve each of the following systems of equations with Cramer's rule:

(a)
$$\begin{aligned}
4 x-14 y & =7 \\
-19 x+88 y & =-1
\end{aligned}$$
(b)
$$\begin{aligned}
9 a & =5 b+7, \\
29 a & =-3 .
\end{aligned}$$

Problem 10.22:
(a) Evaluate $\left|\begin{array}{cc}-2 & 3 \\ 4 & 7\end{array}\right|,\left|\begin{array}{cc}-2+4 & 3+7 \\ 4 & 7\end{array}\right|$, and $\left|\begin{array}{cc}-2+3 \cdot 4 & 3+3 \cdot 7 \\ 4 & 7\end{array}\right|$.
(b) Make a conjecture based on your results from part (a), and then prove your conjecture.

357

---

<!-- Page 358 -->

CHAPTER 10. MATRICES IN TWO DIMENSIONS

Problem 10.23:
(a) Suppose $\mathbf{B}=2 \mathbf{A}$. How are $\operatorname{det}(\mathbf{A})$ and $\operatorname{det}(\mathbf{B})$ related?
(b) Let $\mathbf{C}$ be the matrix formed by doubling the entries in the first row of $\mathbf{A}$. How are $\operatorname{det}(\mathbf{A})$ and $\operatorname{det}(\mathbf{C})$ related?

Problem 10.24: Evaluate $\left|\begin{array}{ll}157 & 199 \\ 314 & 399\end{array}\right|$ and $\left|\begin{array}{cc}33 & -77 \\ -1200 & 3600\end{array}\right|$.
Problem 10.25:
(a) Evaluate $\left|\begin{array}{cc}4 & 5 \\ -3 & 7\end{array}\right|$ and $\left|\begin{array}{cc}-3 & 7 \\ 4 & 5\end{array}\right|$.
(b) Make a conjecture based on your results from part (a), and then prove your conjecture.

Problem 10.26:
(a) Find three matrices with nonzero components such that each has determinant 0 .
(b) Notice anything interesting about your matrices in part (a)? Specifically, how are the rows related to each other in a matrix with determinant 0 ?
(c) How is your answer to part (b) related to what happens in a system of equations in which we cannot apply Cramer's rule because the denominators would come out to be 0 ?

Problem 10.27: Let $\mathbf{A}=\left(\begin{array}{cc}1 & 7 \\ -2 & -5\end{array}\right)$ and $\mathbf{B}=\left(\begin{array}{cc}2 & -7 \\ 6 & 4\end{array}\right)$.
(a) Find $\operatorname{det}(\mathbf{A})$, $\operatorname{det}(\mathbf{B})$, $\operatorname{det}(\mathbf{A B})$, and $\operatorname{det}(\mathbf{A}+\mathbf{B})$.
(b) Make a conjecture based on your results from part (a), and then prove your conjecture.

We start with a little practice computing determinants and applying Cramer's rule.
Problem 10.21: Solve each of the following systems of equations with Cramer's rule:
(a)
$$\begin{aligned}
4 x-14 y & =7 \\
-19 x+88 y & =-1
\end{aligned}$$
(b) $9 a=5 b+7$, $-16 b+29 a=-3$.

Solution for Problem 10.21:
(a) Applying Cramer's rule gives
$$\begin{array}{l}
x=\frac{\left|\begin{array}{cc}
7 & -14 \\
-1 & 88
\end{array}\right|}{\left|\begin{array}{cc}
4 & -14 \\
-19 & 88
\end{array}\right|}=\frac{(7)(88)-(-1)(-14)}{(4)(88)-(-19)(-14)}=\frac{602}{86}=7 \\
y=\frac{\left|\begin{array}{cc}
4 & 7 \\
-19 & -1
\end{array}\right|}{\left|\begin{array}{cc}
4 & -14 \\
-19 & 88
\end{array}\right|}=\frac{(4)(-1)-(-19)(7)}{86}=\frac{129}{86}=\frac{3}{2}
\end{array}$$
(b) What's wrong with the following start:

358

---

<!-- Page 359 -->

10.4. THE DETERMINANT

There are all sorts of things wrong with this start, and they all stem from blindly sticking the coefficients and constants into Cramer's rule without first organizing the data in the problem in a way that makes Cramer's rule easy to apply. In our expression of Cramer's rule, we defined the coefficients such that all the variables are on the left sides of the equations and the constants are on the right sides. We also avoid mistakes by writing the variables in alphabetical order. Reorganizing the original system of equations in these ways gives us
$$\begin{aligned}
9 a-5 b & =7 \\
29 a-16 b & =-3
\end{aligned}$$

Now, we apply Cramer's rule to find
$$\begin{array}{l}
a=\frac{\left|\begin{array}{cc}
7 & -5 \\
-3 & -16
\end{array}\right|}{\left|\begin{array}{cc}
9 & -5 \\
29 & -16
\end{array}\right|}=\frac{(7)(-16)-(-3)(-5)}{(9)(-16)-(29)(-5)}=\frac{-112-15}{-144+145}=-127, \\
b=\frac{\left|\begin{array}{cc}
9 & 7 \\
29 & -3
\end{array}\right|}{\left|\begin{array}{cc}
9 & -5 \\
29 & -16
\end{array}\right|}=\frac{(9)(-3)-(29)(7)}{(9)(-16)-(29)(-5)}=\frac{-27-203}{1}=-230 .
\end{array}$$

Now that we have a little practice in computing determinants, let's explore some properties of determinants that can make evaluating them easier.

Problem 10.22:
(a) Evaluate $\left|\begin{array}{cc}-2 & 3 \\ 4 & 7\end{array}\right|,\left|\begin{array}{cc}-2+4 & 3+7 \\ 4 & 7\end{array}\right|$, and $\left|\begin{array}{cc}-2+3 \cdot 4 & 3+3 \cdot 7 \\ 4 & 7\end{array}\right|$.
(b) Make a conjecture based on your results from part (a), and then prove your conjecture.

Solution for Problem 10.22:
(a) We have
$$\begin{aligned}
\left|\begin{array}{cc}
-2 & 3 \\
4 & 7
\end{array}\right| & =(-2)(7)-(4)(3)=-26, \\
\left|\begin{array}{cc}
-2+4 & 3+7 \\
4 & 7
\end{array}\right| & =(-2+4)(7)-(4)(3+7)=-2(7)+4(7)-4(3)-4(7)=-26, \\
\left|\begin{array}{cc}
-2+3 \cdot 4 & 3+3 \cdot 7 \\
4 & 7
\end{array}\right| & =(-2+3 \cdot 4)(7)-(4)(3+3 \cdot 7)=-2(7)+3 \cdot 4(7)-4(3)-4 \cdot 3(7)=-26 .
\end{aligned}$$

The latter two matrices are formed by adding a constant times the second row to the first row. Our results suggest that this procedure will always leave the determinant unchanged. Our writing out the computations of the latter two determinants in great detail gives us a pretty good clue why this will always happen.

359

---

<!-- Page 360 -->

CHAPTER 10. MATRICES IN TWO DIMENSIONS
(b) Now that we know what to look for, it's easy to find. We wish to show that adding a multiple of one row to the other will not alter the determinant of the matrix. We have
$$\left|\begin{array}{cc}
a+k c & b+k d \\
c & d
\end{array}\right|=(a+k c)(d)-(c)(b+k d)=a d+k c d-b c-k c d=a d-b c=\left|\begin{array}{ll}
a & b \\
c & d
\end{array}\right|,$$
and
$$\left|\begin{array}{cc}
a & b \\
c+k a & d+k b
\end{array}\right|=(a)(d+k b)-(b)(c+k a)=a d+k a b-b c-k a b=a d-b c=\left|\begin{array}{ll}
a & b \\
c & d
\end{array}\right|.$$

Therefore, adding a multiple of one row of a $2 \times 2$ matrix to the other row of the matrix does not change the determinant of the matrix.

As an Exercise, you'll show that adding a multiple of one column of a $2 \times 2$ matrix to the other column of the matrix leaves the determinant of the matrix unchanged.

Important: $\quad\left|\begin{array}{ll}a & b \\ c & d\end{array}\right|=\left|\begin{array}{cc}a+k c & b+k d \\ c & d\end{array}\right|=\left|\begin{array}{cc}a & b \\ c+k a & d+k b\end{array}\right|=\left|\begin{array}{ll}a+k b & b \\ c+k d & d\end{array}\right|=\left|\begin{array}{ll}a & b+k a \\ c & d+k c\end{array}\right|$

Problem 10.23:
(a) Suppose $\mathbf{B}=k \mathbf{A}$. How are $\operatorname{det}(\mathbf{A})$ and $\operatorname{det}(\mathbf{B})$ related?
(b) Let $\mathbf{C}$ be the matrix formed by multiplying the entries in the first row of $\mathbf{A}$ by $k$. How are $\operatorname{det}(\mathbf{A})$ and $\operatorname{det}(\mathrm{C})$ related?

Solution for Problem 10.23: Let $\mathbf{A}=\left(\begin{array}{cc}a & b \\ c & d\end{array}\right)$, so $\operatorname{det}(\mathbf{A})=a d-b c$.
(a) We have
$$\operatorname{det}(\mathbf{B})=\operatorname{det}(k \mathbf{A})=\left|\begin{array}{ll}
k a & k b \\
k c & k d
\end{array}\right|=(k a)(k d)-(k b)(k c)=k^{2}(a d-b c)=k^{2} \operatorname{det}(\mathbf{A}) .$$

Important: For any $2 \times 2$ matrix $\mathbf{A}$ and any constant $k$, we have $\operatorname{det}(k \mathbf{A})=k^{2} \operatorname{det}(\mathbf{A})$.
(b) We have
$$\operatorname{det}(\mathbf{C})=\left|\begin{array}{cc}
k a & k b \\
c & d
\end{array}\right|=(k a)(d)-(k b)(c)=k(a d-b c)=k \operatorname{det}(\mathbf{A}) .$$

Similarly, multiplying the second row of $\mathbf{A}$ by any constant $k$ gives a matrix with determinant $k \operatorname{det}(\mathbf{A})$, and multiplying either column of $\mathbf{A}$ by any constant $k$ gives a matrix with determinant $k \operatorname{det}(\mathbf{A})$.

\begin{tabular}{|l|} 
Important: Multiplying either column or either row of a matrix $\mathbf{A}$ by any constant $k$ gives \\
a matrix with determinant $k \operatorname{det}(\mathbf{A})$.
\end{tabular}

We can sometimes use the rules that we proved in the previous two problems to simplify the computation of the determinant of a matrix.

Problem 10.24: Evaluate $\left|\begin{array}{ll}157 & 199 \\ 314 & 399\end{array}\right|$ and $\left|\begin{array}{cc}33 & -77 \\ -1200 & 3600\end{array}\right|$.

360

---

<!-- Page 361 -->

10.4. THE DETERMINANT

Solution for Problem 10.24: For the first matrix, we notice that 314 is double 157 , so we add -2 times the first row to the second row, and we have
$$\left|\begin{array}{ll}
157 & 199 \\
314 & 399
\end{array}\right|=\left|\begin{array}{cc}
157 & 199 \\
314-2(157) & 399-2(199)
\end{array}\right|=\left|\begin{array}{cc}
157 & 199 \\
0 & 1
\end{array}\right|=(157)(1)-(0)(199)=157 .$$

Turning to the second matrix, we see a common factor of 11 in the first row and 1200 in the second. Repeatedly applying the principle we proved in part (b) of Problem 10.23, we have
$$\left|\begin{array}{cc}
33 & -77 \\
-1200 & 3600
\end{array}\right|=11\left|\begin{array}{cc}
3 & -7 \\
-1200 & 3600
\end{array}\right|=(11)(1200)\left|\begin{array}{cc}
3 & -7 \\
-1 & 3
\end{array}\right|=(11)(1200)((3)(3)-(-7)(-1))=26400 .$$

Problem 10.25:
(a) Evaluate $\left|\begin{array}{cc}4 & 5 \\ -3 & 7\end{array}\right|$ and $\left|\begin{array}{cc}-3 & 7 \\ 4 & 5\end{array}\right|$.
(b) Make a conjecture based on your results from part (a), and then prove your conjecture.

Solution for Problem 10.25:
(a) We have $\left|\begin{array}{cc}4 & 5 \\ -3 & 7\end{array}\right|=(4)(7)-(-3)(5)=28+15=43$ and $\left|\begin{array}{cc}-3 & 7 \\ 4 & 5\end{array}\right|=(-3)(5)-(4)(7)=-15-28=-43$.
(b) It looks like swapping the rows of a $2 \times 2$ matrix $\mathbf{A}$ produces a matrix with determinant $(-1) \operatorname{det}(\mathbf{A})$. Proving this is true is straightforward:
$$\left|\begin{array}{ll}
c & d \\
a & b
\end{array}\right|=c b-a d=-(a d-b c)=-\left|\begin{array}{ll}
a & b \\
c & d
\end{array}\right| .$$

\begin{tabular}{|ll|}
\hline Important: & For any $2 \times 2$ matrix $\mathbf{A}$, swapping the rows or columns of $\mathbf{A}$ produces a matrix \\
with determinant $(-1) \operatorname{det}(\mathbf{A})$ & .
\end{tabular}

Problem 10.26:
(a) Find three matrices with nonzero components such that each has determinant 0 .
(b) Notice anything interesting about your matrices in part (a)? Specifically, how are the rows related to each other in a matrix with determinant 0 ?
(c) How is your answer to part (b) related to what happens in a system of equations in which we cannot apply Cramer's rule because the denominators would come out to be 0 ?

Solution for Problem 10.26:
(a) With a little trial and error, we can find many matrices with determinant 0 . Here are some:
$$\left|\begin{array}{cc}
1 & 1 \\
-1 & -1
\end{array}\right|=\left|\begin{array}{cc}
2 & 3 \\
2 & 3
\end{array}\right|=\left|\begin{array}{cc}
3 & -5 \\
6 & -10
\end{array}\right|=\left|\begin{array}{cc}
-2 & -8 \\
1 & 4
\end{array}\right|=\left|\begin{array}{cc}
-5 & 6 \\
25 & -30
\end{array}\right|=0 .$$
(b) In each of the example matrices in part (a), the first row is a multiple of the second. To see why this is happening, we note that $\left|\begin{array}{ll}a & b \\ c & d\end{array}\right|=a d-b c$. This equals 0 if and only if $a d=b c$, which we can write as $\frac{a}{c}=\frac{b}{d}$

361

---

<!-- Page 362 -->

CHAPTER 10. MATRICES IN TWO DIMENSIONS

when $c d \neq 0$. When $\frac{a}{c}=\frac{b}{d}$, the first row of the matrix $\left(\begin{array}{ll}a & b \\ c & d\end{array}\right)$ is a multiple of the second. If $c=0$, then we can only have $a d-b c=0$ if $a=0$ or $d=0$. In either case, the second row is a multiple of the first. (Similarly, if $d=0$, we have $b c=0$, from which we find that the second row is a multiple of the first.)

Therefore, the determinant of a $2 \times 2$ matrix is 0 if and only if one row is a multiple of the other.
(c) We can only apply Cramer's rule to the system
$$\begin{array}{l}
a x+b y=u \\
c x+d y=v
\end{array}$$
if $a d-b c \neq 0$. What goes wrong when $a d-b c=0$ ? As we saw in part (b), we have $a d-b c=0$ if and only if one row of the matrix $\left(\begin{array}{ll}a & b \\ c & d\end{array}\right)$ is a multiple of the other. This corresponds to the left side of one of the equations in our system being a constant multiple of the other left side. Geometrically speaking, the graphs of the two equations are either the same line or parallel lines. So, we cannot have a unique solution to the system of equations.

Just as we can describe a pair of vectors as being linearly dependent if one is a constant times the other, we can describe two rows of a matrix as being linearly dependent if either is a constant times the other.

Important: The determinant of a $2 \times 2$ matrix is 0 if and only if the rows of the matrix are
□ linearly dependent.

We can equivalently state this fact as, "The determinant of a $2 \times 2$ matrix is nonzero if and only if the rows of the matrix are linearly independent."

Matrices with determinant 0 are so important that we have a special name for them. A matrix with determinant 0 is called a singular matrix, and a matrix with nonzero determinant is called a nonsingular matrix.

Problem 10.27: Let $\mathbf{A}=\left(\begin{array}{cc}1 & 7 \\ -2 & -5\end{array}\right)$ and $\mathbf{B}=\left(\begin{array}{cc}2 & -7 \\ 6 & 4\end{array}\right)$.
(a) Find $\operatorname{det}(\mathbf{A}), \operatorname{det}(\mathbf{B}), \operatorname{det}(\mathbf{A B})$, and $\operatorname{det}(\mathbf{A}+\mathbf{B})$.
(b) Make a conjecture based on your results from part (a), and then prove your conjecture.

Solution for Problem 10.27:
(a) We have $\operatorname{det}(\mathbf{A})=(1)(-5)-(7)(-2)=-5+14=9, \operatorname{det}(\mathbf{B})=(2)(4)-(-7)(6)=8+42=50, \operatorname{det}(\mathbf{A}+\mathbf{B})= \left|\begin{array}{cc}3 & 0 \\ 4 & -1\end{array}\right|=-3$, and
$$\operatorname{det}(\mathbf{A B})=\left|\begin{array}{cc}
44 & 21 \\
-34 & -6
\end{array}\right|=2\left|\begin{array}{cc}
44 & 21 \\
-17 & -3
\end{array}\right|=2 \cdot 3\left|\begin{array}{cc}
44 & 7 \\
-17 & -1
\end{array}\right|=6((44)(-1)-(7)(-17))=6(75)=450 .$$
(b) In part (a), we don't see any obvious relationship between $\operatorname{det}(\mathbf{A}+\mathbf{B})$ and $\operatorname{det}(\mathbf{A})+\operatorname{det}(\mathbf{B})$, but we do have $\operatorname{det}(\mathbf{A B})=\operatorname{det}(\mathbf{A}) \operatorname{det}(\mathbf{B})$. Let's see if this is always the case. We have
$$\begin{aligned}
\left|\begin{array}{ll}
a_{11} & a_{12} \\
a_{21} & a_{22}
\end{array}\right|\left|\begin{array}{ll}
b_{11} & b_{12} \\
b_{21} & b_{22}
\end{array}\right| & =\left(a_{11} a_{22}-a_{21} a_{12}\right)\left(b_{11} b_{22}-b_{21} b_{12}\right) \\
& =a_{11} a_{22} b_{11} b_{22}-a_{11} a_{22} b_{21} b_{12}-a_{21} a_{12} b_{11} b_{22}+a_{21} a_{12} b_{21} b_{12} \\
& =a_{11} a_{22} b_{11} b_{22}+a_{12} a_{21} b_{12} b_{21}-a_{11} a_{22} b_{12} b_{21}-a_{12} a_{21} b_{11} b_{22}
\end{aligned}$$

362

---

<!-- Page 363 -->

10.4. THE DETERMINANT

where we have reorganized the terms in the last row to make it easier to compare to $\operatorname{det}(\mathbf{A B})$. Speaking of which, we have
$$\begin{aligned}
\operatorname{det}\left(\left(\begin{array}{ll}
a_{11} & a_{12} \\
a_{21} & a_{22}
\end{array}\right)\left(\begin{array}{ll}
b_{11} & b_{12} \\
b_{21} & b_{22}
\end{array}\right)\right)= & =\left|\begin{array}{ll}
a_{11} b_{11}+a_{12} b_{21} & a_{11} b_{12}+a_{12} b_{22} \\
a_{21} b_{11}+a_{22} b_{21} & a_{21} b_{12}+a_{22} b_{22}
\end{array}\right| \\
= & \left(a_{11} b_{11}+a_{12} b_{21}\right)\left(a_{21} b_{12}+a_{22} b_{22}\right)-\left(a_{11} b_{12}+a_{12} b_{22}\right)\left(a_{21} b_{11}+a_{22} b_{21}\right) \\
= & a_{11} b_{11} a_{21} b_{12}+a_{11} b_{11} a_{22} b_{22}+a_{12} b_{21} a_{21} b_{12}+a_{12} b_{21} a_{22} b_{22} \\
& -a_{11} b_{12} a_{21} b_{11}-a_{11} b_{12} a_{22} b_{21}-a_{12} b_{22} a_{21} b_{11}-a_{12} b_{22} a_{22} b_{21} .
\end{aligned}$$

We can clean this up a bit by organizing the terms in each product. When we do so, we see that we have some convenient cancellation:
$$\begin{aligned}
\operatorname{det}\left(\left(\begin{array}{ll}
a_{11} & a_{12} \\
a_{21} & a_{22}
\end{array}\right)\left(\begin{array}{ll}
b_{11} & b_{12} \\
b_{21} & b_{22}
\end{array}\right)\right)= & a_{11} a_{21} b_{11} b_{12}+a_{11} a_{22} b_{11} b_{22}+a_{12} a_{21} b_{12} b_{21}+a_{12} a_{22} b_{21} b_{22} \\
& -a_{11} a_{21} b_{11} b_{12}-a_{11} a_{22} b_{12} b_{21}-a_{12} a_{21} b_{11} b_{22}-a_{12} a_{22} b_{21} b_{22} \\
= & a_{11} a_{22} b_{11} b_{22}+a_{12} a_{21} b_{12} b_{21}-a_{11} a_{22} b_{12} b_{21}-a_{12} a_{21} b_{11} b_{22},
\end{aligned}$$
which does indeed match our expression above for $\operatorname{det}(\mathbf{A}) \operatorname{det}(\mathbf{B})$.
Important: We have $\operatorname{det}(\mathbf{A B})=\operatorname{det}(\mathbf{A}) \operatorname{det}(\mathbf{B})$ for any $2 \times 2$ matrices $\mathbf{A}$ and $\mathbf{B}$.
WARNING!! The values of $\operatorname{det}(\mathbf{A})+\operatorname{det}(\mathbf{B})$ and $\operatorname{det}(\mathbf{A}+\mathbf{B})$ are not necessarily equal.
A

Exercises
10.4.1 Use Cramer's rule to solve the system $3 x+4 y=-3 x+7,5 y=-2 x+9$.
10.4.2 Evaluate the following determinants:
(a) $\left|\begin{array}{cc}-3 & -5 \\ 6 & 18\end{array}\right|$
(b) $\left|\begin{array}{ll}2400 & 3200 \\ 25 / 3 & 31 / 3\end{array}\right|$
10.4.3 Is it true that $\operatorname{det}(\mathbf{A B})=\operatorname{det}(\mathbf{B A})$ ?
10.4.4 The first column of $\mathbf{B}$ is the same as the first column of $\mathbf{A}$. The second column of $\mathbf{B}$ is the sum of the second column of $\mathbf{A}$ and $k$ times the first column of $\mathbf{A}$. Show that $\operatorname{det}(\mathbf{A})=\operatorname{det}(\mathbf{B})$.
10.4.5 We showed in the text that $\operatorname{det}(\mathbf{A})+\operatorname{det}(\mathbf{B})$ does not necessarily equal $\operatorname{det}(\mathbf{A}+\mathbf{B})$.
(a) What if $\operatorname{det}(\mathbf{A})=\operatorname{det}(\mathbf{B})=0$ ? Then, must we have $\operatorname{det}(\mathbf{A})+\operatorname{det}(\mathbf{B})=\operatorname{det}(\mathbf{A}+\mathbf{B})$ ?
(b) What if we have $\operatorname{det}(\mathbf{A})=0$ but $\operatorname{det}(\mathbf{B}) \neq 0$. Then, must we have $\operatorname{det}(\mathbf{A})+\operatorname{det}(\mathbf{B})=\operatorname{det}(\mathbf{A}+\mathbf{B})$ ?

363

---

<!-- Page 364 -->

CHAPTER 10. MATRICES IN TWO DIMENSIONS
10.5 Geometric Interpretation of the Determinant

Problems

Problem 10.28: In this problem, we investigate the geometric significance of the determinant of a $2 \times 2$ matrix. Let $\mathbf{M}=\left(\begin{array}{ll}a & b \\ c & d\end{array}\right)$, let $O$ be the origin, and let $V$ and $W$ be the points such that $\vec{V}=\mathbf{M i}$ and $\vec{W}=\mathbf{M j}$.
(a) Show that the area of the parallelogram with $\overline{O V}$ and $\overline{O W}$ as sides equals $\|\vec{V}\|\|\vec{W}\| \sin \theta$, where $\theta$ is the angle between $\vec{V}$ and $\vec{W}$.
(b) Express the area in terms of $\vec{V} \cdot \vec{W},\|\vec{V}\|$, and $\|\vec{W}\|$.
(c) Find the area in terms of $a, b, c$, and $d$.

Problem 10.29:
(a) What is the geometric significance of a 0 determinant?
(b) Find several matrices with a negative determinant, and draw the corresponding parallelograms. Make a conjecture about the geometric significance of a negative determinant.
(c) Prove your conjecture in part (b). Hints: 160, 112

Problem 10.30: Use the geometric interpretation of the determinant to explain why $\operatorname{det}(k \mathbf{A})=k^{2} \operatorname{det}(\mathbf{A})$ for any $2 \times 2$ matrix $\mathbf{A}$.

Problem 10.31: Use the geometric interpretation of the determinant to explain why adding a multiple of either column of a $2 \times 2$ matrix to the other column leaves the determinant of the matrix unchanged.

Problem 10.32: In this problem, we find a method for finding the area of a triangle given the coordinates of its vertices.
(a) Find the area of a triangle with vertices $(0,0),(5,4)$, and $(1,-3)$.
(b) Find the area of a triangle with vertices $(4,5),(7,10)$, and $(-3,7)$.
(c) Find a formula for the area of a triangle with vertices $\left(x_{1}, y_{1}\right),\left(x_{2}, y_{2}\right)$, and $\left(x_{3}, y_{3}\right)$, where these vertices are in counterclockwise order.

Problem 10.28: Let $O$ be the origin, $V$ be $(a, c)$, and $W$ be $(b, d)$. Show that the area of the parallelogram with $\overline{O V}$ and $\overline{O W}$ as sides is the absolute value of $\operatorname{det}(\mathbf{M})$, where $\mathbf{M}=\left(\begin{array}{cc}a & b \\ c & d\end{array}\right)$.

Solution for Problem 10.28: First, we find the fourth vertex of the parallelogram by noting that if $P$ is the point such that $\vec{V}+\vec{W}=\vec{P}$, then $O V P W$ is a parallelogram. Since $\triangle O V W \cong \triangle P W V$, we have $[O V P W]=2[O V W]=2\left(\frac{1}{2}(O V)(O W) \sin \theta\right)$, where $\theta=\angle V O W$. Therefore, we have $[O V P W]=\|\vec{V}\|\|\vec{W}\| \sin \theta$, where $\theta$ is the angle between $\vec{V}$ and $\vec{W}$. The dot product gives us another relationship involving $\vec{V}, \vec{W}$, and $\theta$ :
$$\vec{V} \cdot \vec{W}=\|\vec{V}\|\|\vec{W}\| \cos \theta$$

364

---

<!-- Page 365 -->

10.5. GEOMETRIC INTERPRETATION OF THE DETERMINANT

We can now eliminate $\sin \theta$ from our expression for [OVPW]. Since $0^{\circ} \leq \theta \leq 180^{\circ}$, we have $\sin \theta \geq 0$, so we take the positive root from $\sin \theta=\sqrt{1-\cos ^{2} \theta}$, and we have
$$\begin{aligned}
{[O V P W] } & =\|\vec{V}\|\|\vec{W}\| \sin \theta \\
& =\|\vec{V}\|\|\vec{W}\| \sqrt{1-\cos ^{2} \theta} \\
& =\|\vec{V}\|\|\vec{W}\| \sqrt{1-\frac{(\vec{V} \cdot \vec{W})^{2}}{\|\vec{V}\|^{2}\|\vec{W}\|^{2}}} \\
& =\sqrt{\|\vec{V}\|^{2}\|\vec{W}\|^{2}-(\vec{V} \cdot \vec{W})^{2}} \\
& =\sqrt{\left(a^{2}+c^{2}\right)\left(b^{2}+d^{2}\right)-(a b+c d)^{2}} \\
& =\sqrt{a^{2} b^{2}+a^{2} d^{2}+b^{2} c^{2}+c^{2} d^{2}-a^{2} b^{2}-2 a b c d-c^{2} d^{2}} \\
& =\sqrt{a^{2} d^{2}-2 a b c d+b^{2} c^{2}}=\sqrt{(a d-b c)^{2}}=|a d-b c|
\end{aligned}$$
as desired.

Repeatedly referring to the "absolute value" of $\operatorname{det}(\mathbf{M})$ is pretty unwieldy. Let's take a closer look at what a negative determinant corresponds to geometrically.

Problem 10.29:
(a) What is the geometric significance of a 0 determinant?
(b) Find several matrices with a negative determinant, and draw the corresponding parallelograms. Make a conjecture about the geometric significance of a negative determinant.
(c) Prove your conjecture in part (b).

Solution for Problem 10.29:
(a) If $\mathbf{v}$ and $\mathbf{w}$ are nonzero, then the parallelogram with sides $\mathbf{v}$ and $\mathbf{w}$ drawn from the origin has area 0 if and only if $\mathbf{v}$ and $\mathbf{w}$ are in the same or opposite directions. This occurs if and only if $\mathbf{v}$ is a multiple of $\mathbf{w}$. This corresponds to the fact that the determinant $\left|\begin{array}{ll}v_{1} & w_{1} \\ v_{2} & w_{2}\end{array}\right|$ is zero if and only if the columns are linearly dependent.
(b) To learn the significance of a negative determinant, we examine a few cases. Below are the parallelograms whose areas correspond to the determinants $\left|\begin{array}{cc}2 & 4 \\ 1 & -2\end{array}\right|,\left|\begin{array}{cc}-3 & 4 \\ 2 & -1\end{array}\right|$, and $\left|\begin{array}{cc}-2 & -2 \\ -3 & 0\end{array}\right|$.

365

---

<!-- Page 366 -->

CHAPTER 10. MATRICES IN TWO DIMENSIONS

In each case, the determinant is negative. In each case, the smallest rotation from the vector given by the first column to the vector given by the second column is a clockwise rotation, as indicated by the arrows in the diagrams.

Swapping the columns of a $2 \times 2$ matrix produces a matrix whose determinant is the opposite of the determinant of the original matrix. Doing so for our three example matrices gives us $\left|\begin{array}{cc}4 & 2 \\ -2 & 1\end{array}\right|,\left|\begin{array}{cc}4 & -3 \\ -1 & 2\end{array}\right|$, and $\left|\begin{array}{cc}-2 & -2 \\ 0 & -3\end{array}\right|$, and the corresponding parallelograms are below.

These are the same parallelograms as before, since the columns of the matrices are the same as before, only in opposite order. However, now the smallest rotation from the direction of the first column to the direction of the second is counterclockwise. We conjecture that the determinant of a $2 \times 2$ matrix is positive if and only if the smallest rotation from the vector of the first column to the vector of the second is counterclockwise.
(c) Let the columns of $\mathbf{A}$ be nonzero vectors $\mathbf{v}$ and $\mathbf{w}$, so $\mathbf{A}=\left(\begin{array}{ll}v_{1} & w_{1} \\ v_{2} & w_{2}\end{array}\right)$. (If $\mathbf{v}$ or $\mathbf{w}$ is $\mathbf{0}$, then $\operatorname{det}(\mathbf{A})=0$.) We need to relate $\operatorname{det}(\mathbf{A})$ to the angle between $\mathbf{v}$ and $\mathbf{w}$, so we let $\theta$ be the smallest rotation that must be applied to $\mathbf{v}$ to make it have the same direction as $\mathbf{w}$. (As usual, if $\theta>0$, this rotation is counterclockwise, and if $\theta<0$, then this rotation is clockwise.) Therefore, the vector $\left(\begin{array}{cc}\cos \theta & -\sin \theta \\ \sin \theta & \cos \theta\end{array}\right) \mathbf{v}$ has the same direction as $\mathbf{w}$, so there is some positive constant $k$ such that
$$\mathbf{w}=k\left(\begin{array}{cc}
\cos \theta & -\sin \theta \\
\sin \theta & \cos \theta
\end{array}\right) \mathbf{v}=k\left(\begin{array}{cc}
\cos \theta & -\sin \theta \\
\sin \theta & \cos \theta
\end{array}\right)\binom{v_{1}}{v_{2}}=\binom{k v_{1} \cos \theta-k v_{2} \sin \theta}{k v_{1} \sin \theta+k v_{2} \cos \theta} .$$
(Specifically, $k=\|\mathbf{w}\| /\|\mathbf{v}\|$.)
Therefore, we have
$$\begin{aligned}
\operatorname{det}(\mathbf{A}) & =\left|\begin{array}{ll}
v_{1} & k v_{1} \cos \theta-k v_{2} \sin \theta \\
v_{2} & k v_{1} \sin \theta+k v_{2} \cos \theta
\end{array}\right| \\
& =v_{1}\left(k v_{1} \sin \theta+k v_{2} \cos \theta\right)-v_{2}\left(k v_{1} \cos \theta-k v_{2} \sin \theta\right) \\
& =k\left(v_{1}^{2}+v_{2}^{2}\right) \sin \theta
\end{aligned}$$

Aha! Now we have the whole story. Since $k, v_{1}^{2}$, and $v_{2}^{2}$ are all nonnegative, the sign of $\operatorname{det}(\mathbf{A})$ must match the sign of $\sin \theta$. We have $\sin \theta>0$ for $0<\theta<\pi$, and $\sin \theta<0$ for $-\pi<\theta<0$. Since positive values of $\theta$ correspond to counterclockwise rotations and negative values of $\theta$ correspond to clockwise rotations, we see that the determinant of a matrix is negative if the smallest rotation from the direction of the first column to the direction of the second column is a clockwise rotation, and positive if the smallest such rotation is a counterclockwise rotation. If the two columns have the same or opposite directions, then the columns are linearly dependent and the determinant is 0 .

366

---

<!-- Page 367 -->

10.5. GEOMETRIC INTERPRETATION OF THE DETERMINANT

We can get rid of the "absolute value" in the statement, "The absolute value of the determinant $\left|\begin{array}{ll}a & b \\ c & d\end{array}\right|$ equals the area of the parallelogram that has as two sides the vectors $\binom{a}{c}$ and $\binom{b}{d}$ drawn from the origin" by using the concept of signed area. We define the signed area of a polygon by first assigning an orientation, clockwise or counterclockwise, to the polygon. If the orientation is counterclockwise, as shown in the diagram at left below, then we say the signed area is positive. If the orientation is clockwise, then we say the signed area is negative.

Figure 10.1: A Parallelogram with Positive Area

Figure 10.2: A Parallelogram with Negative Area

With this definition in hand, we can refine the relationship between the determinant of a matrix and area.
Important: The value of the determinant $\left|\begin{array}{ll}a & b \\ c & d\end{array}\right|$ equals the signed area of the parallelogram that has as two sides the vectors $\binom{a}{c}$ and $\binom{b}{d}$ drawn from the origin, where the orientation of the parallelogram is determined by the path around the parallelogram with first step from the origin to $(a, c)$.

We learned in Section 10.3 that multiplying a vector by a matrix corresponds to a transformation of the vector. Our work so far in this section tells us about the effect of such a transformation on area.

Specifically, we showed that if $\mathbf{M}=\left(\begin{array}{ll}a & b \\ c & d\end{array}\right)$ and we let $\mathbf{v}=\mathbf{M i}=\binom{a}{c}$ and $\mathbf{w}=\mathbf{M j}=\binom{b}{d}$, then the signed area of the parallelogram with sides $\mathbf{v}$ and $\mathbf{w}$ is $\operatorname{det}(\mathbf{M})$. Since the signed area of the parallelogram with sides $\mathbf{i}$ and $\mathbf{j}$ is simply 1 , we see that multiplication by $\mathbf{M}$ scales the area of this parallelogram by $\operatorname{det}(\mathbf{M})$.

We can extend this result to any two linearly independent vectors, not just $\mathbf{i}$ and $\mathbf{j}$. If $\mathbf{r}$ and $\mathbf{s}$ are linearly independent, then the signed area of the parallelogram with sides $\mathbf{M r}$ and $\mathbf{M s}$ is $\operatorname{det}(\mathbf{M})$ times the signed area of the parallelogram with sides $\mathbf{r}$ and $\mathbf{s}$. You'll be asked to prove this claim as a Challenge Problem.

Problem 10.30: Use the geometric interpretation of the determinant to explain why $\operatorname{det}(k \mathbf{A})=k^{2} \operatorname{det}(\mathbf{A})$ for any $2 \times 2$ matrix $\mathbf{A}$.

Solution for Problem 10.30: Let $\mathcal{P}$ be the parallelogram with sides $\mathbf{v}$ and $\mathbf{w}$ drawn from the origin, and let $Q$ be the parallelogram with sides $k \mathbf{v}$ and $k \mathbf{w}$ drawn from the origin. $Q$ is formed by scaling the sides of $\mathcal{P}$ by a factor of $k$. Therefore, $Q$ and $\mathcal{P}$ are similar, and the ratio of the lengths of corresponding sides is $k$, which means the ratio of their areas is $k^{2}$.

In our discussion above, we've glossed over the issue of negative determinants and what happens when $k<0$. Our discussion in Problem 10.29 takes care of both these concerns. The smallest rotation from the direction of $\mathbf{v}$ to the direction of $\mathbf{w}$ is the same as the smallest rotation from the direction of $k \mathbf{v}$ to the direction of $k \mathbf{w}$ (no matter what the sign of $k$ is). Therefore, the determinants of $\mathbf{A}$ and $k \mathbf{A}$ must have the same sign.

367

---

<!-- Page 368 -->

CHAPTER 10. MATRICES IN TWO DIMENSIONS

Problem 10.31: Use the geometric interpretation of the determinant to explain why adding a multiple of either column of a $2 \times 2$ matrix to the other column leaves the determinant of the matrix unchanged.

Solution for Problem 10.31: To add $k \mathbf{w}$ to $\mathbf{v}$ geometrically, we first draw $\mathbf{v}$ from the origin to $V$, and then draw $k w$ starting from $V$. Because $k w$ is parallel to $\mathbf{w}$, the head of $\mathbf{v}+k \mathbf{w}$, point $T$ in the diagram, is on the line through $V$ parallel to $\mathbf{w}$. Therefore, the distances from $V$ and $T$ to $\overleftrightarrow{O W}$ are equal, which means that the areas of OWV and OWT are the same. This means that the area of the parallelogram with sides $\mathbf{v}$ and $\mathbf{w}$ (parallelogram OVPW) equals the area of the parallelogram with sides $\mathbf{v}+k \mathbf{w}$ and $\mathbf{w}$ (parallelogram OTUW).

Letting $\mathbf{v}=\binom{v_{1}}{v_{2}}$ and $\mathbf{w}=\binom{w_{1}}{w_{2}}$, this gives us
$$\left|\begin{array}{ll}
v_{1} & w_{1} \\
v_{2} & w_{2}
\end{array}\right|=\left|\begin{array}{ll}
v_{1}+k w_{1} & w_{1} \\
v_{2}+k w_{2} & w_{2}
\end{array}\right| .$$

We haven't yet explained why the signs of these determinants are the same. When determining the orientation of the parallelogram corresponding to each of the determinants above, the last step in the path around the parallelogram in each is from $W$ to $O$. So, the two parallelograms have the same orientation if these last steps complete circuits about the parallelograms with the same orientation. This is the case if and only if $V$ and $T$ are not on opposite sides of $\overleftarrow{O W}$. Because $\overline{V T} \| \overline{O W}$, we know that $V$ and $T$ (the heads of $\mathbf{v}$ and $\mathbf{v}+k \mathbf{w}$ ) cannot be on opposite sides of $\overleftrightarrow{\mathrm{OW}}$. Therefore, the orientations of the parallelograms corresponding to the determinants are the same, so the signs of the determinants are the same. (In the case shown, both are clockwise, and hence have negative area.)

Similarly, we can add any multiple of the first column to the second without changing the determinant.
Problem 10.32: In this problem, we find a method for finding the area of a triangle given the coordinates of its vertices.
(a) Find the area of a triangle with vertices $O=(0,0), A=(5,4)$, and $B=(1,-3)$.
(b) Find the area of a triangle with vertices $P=(4,5), Q=(7,10)$, and $R=(-3,7)$.
(c) Find a formula for the area of a triangle with vertices $\left(x_{1}, y_{1}\right),\left(x_{2}, y_{2}\right)$, and $\left(x_{3}, y_{3}\right)$, where these vertices are in counterclockwise order.

Solution for Problem 10.32:
(a) We know how to handle a parallelogram, so we "complete" the parallelogram by finding the point $C$ such that $\vec{C}=\vec{A}+\vec{B}$. As shown, this point is $(5+1,4+(-3))=(6,1)$. Since $\triangle O A B \cong \triangle C B A$, we have
$$[O A B]=\frac{1}{2}[O A C B]=\frac{1}{2}\left|\operatorname{det}\left(\begin{array}{cc}
5 & 1 \\
4 & -3
\end{array}\right)\right|=\frac{1}{2}|(5)(-3)-(4)(1)|=\frac{19}{2} .$$
(b) From part (a) we know how to find the area of a triangle with one vertex at the origin, so we translate the triangle so that $P$ is at the origin. The translation that maps $(4,5)$ to $(0,0)$ also maps $(7,10)$ to $(7-4,10-5)= (3,5)$ and maps $(-3,7)$ to $(-3-4,7-5)=(-7,2)$. Therefore, we now seek the area of the triangle with vertices $(0,0),(3,5)$ and $(-7,2)$. By the same argument as in part (a), the area of this triangle is
$$\frac{1}{2}\left|\operatorname{det}\left(\begin{array}{cc}
3 & -7 \\
5 & 2
\end{array}\right)\right|=\frac{1}{2}|(3)(2)-(-7)(5)|=\frac{41}{2} .$$

368

---

<!-- Page 369 -->

10.6. INVERTING A MATRIX
(c) Part (b) gives us a guide; we start by translating one vertex to the origin. The same translation that maps ( $x_{1}, y_{1}$ ) to ( 0,0 ) also maps ( $x_{2}, y_{2}$ ) to ( $x_{2}-x_{1}, y_{2}-y_{1}$ ) and maps ( $x_{3}, y_{3}$ ) to ( $x_{3}-x_{1}, y_{3}-y_{1}$ ). Since the vertices ( $x_{1}, y_{1}$ ), ( $x_{2}, y_{2}$ ), and ( $x_{3}, y_{3}$ ) are in counterclockwise order, so are the vertices ( 0,0 ), ( $x_{2}-x_{1}, y_{2}-y_{1}$ ), and $\left(x_{3}-x_{1}, y_{3}-y_{1}\right)$. The area of this triangle is half the area of the parallelogram with $\binom{x_{2}-x_{1}}{y_{2}-y_{1}}$ and $\binom{x_{3}-x_{1}}{y_{3}-y_{1}}$ as sides, so the desired area is
$$\frac{1}{2} \operatorname{det}\left(\begin{array}{ll}
x_{2}-x_{1} & x_{3}-x_{1} \\
y_{2}-y_{1} & y_{3}-y_{1}
\end{array}\right) .$$

Note that if the vertices were in clockwise order rather than counterclockwise, then the expression above is negative, and gives the signed area of the triangle.
|||||
Exercises
10.5.1 Find the determinant of the rotation matrix $\left(\begin{array}{cc}\cos \theta & -\sin \theta \\ \sin \theta & \cos \theta\end{array}\right)$. Explain the result geometrically.
10.5.2 Find the area of the quadrilateral with vertices $(-2,3),(1,-5),(7,-4)$, and $(8,1)$.
10.5.3 Explain geometrically why multiplying one column of $\mathbf{A}$ by a constant $k$ produces a matrix with determinant $k \operatorname{det}(\mathbf{A})$.
10.5.4 A lattice point is a point in the Cartesian plane with integer coordinates. Suppose $\mathcal{T}$ is a triangle in the Cartesian plane such that all three vertices of $\mathcal{T}$ are lattice points. Show that doubling the area of $\mathcal{T}$ must produce an integer.
10.5.5 ★ In Exercise 10.1.3, we discovered a matrix $\mathbf{F}$ such that multiplying a matrix on the right by $\mathbf{F}$ swaps the columns of the matrix. That is, the first column of AF is the second column of A, and the second column of AF is the first column of A. Explain geometrically what the determinant of F must be.
10.6 Inverting a Matrix

We have seen that we can solve the system of equations described by
$$\left(\begin{array}{ll}
3 & -4 \\
2 & -1
\end{array}\right)\binom{x}{y}=\binom{5}{-10}$$
with Cramer's rule. Rather than grinding through Cramer's rule, it sure would be nice to be able to divide by the matrix on the left. Unfortunately, division by a matrix is not defined. However, we can take another look solving equations with division by real numbers to get an idea how we might accomplish our goal. Consider the equation
$$3 x=9 .$$

To solve this equation we can "divide both sides by 3 ." What we're really doing when we "divide both sides by 3 " is "multiplying both sides by $\frac{1}{3}$." More precisely, we are multiplying by the multiplicative inverse of 3 , which eliminates the 3 on the left side. Multiplying both sides of $3 x=9$ by $\frac{1}{3}$ gives
$$\frac{1}{3} \cdot 3 x=\frac{1}{3} \cdot 9 .$$

The $\frac{1}{3}$ and 3 cancel, and we're left with $x=\frac{1}{3} \cdot 9=3$.

369

---

<!-- Page 370 -->

CHAPTER 10. MATRICES IN TWO DIMENSIONS

Let's see if we can accomplish something similar with matrices.
Problems
Problem 10.33: Suppose that $\mathbf{A B v}=\mathbf{v}$ for all vectors $\mathbf{v}$. What matrix must $\mathbf{A B}$ equal?
Problem 10.34: If $\mathbf{A B}$ equals the answer you found in Problem 10.33, then we say that $\mathbf{A}$ is the inverse of $\mathbf{B}$ and that $\mathbf{B}$ is invertible. We often denote the inverse of a matrix $\mathbf{B}$ as $\mathbf{B}^{-1}$. Let $\mathbf{M}=\left(\begin{array}{ll}2 & 3 \\ 6 & 7\end{array}\right)$. Find $\mathbf{M}^{-1}$.

Problem 10.35: Does the matrix $\mathbf{M}=\left(\begin{array}{cc}3 & 5 \\ -6 & -10\end{array}\right)$ have an inverse? If it does, then find it. If it doesn't, explain why not.

Problem 10.36: If $\mathbf{A}$ is invertible, then how are $\operatorname{det}(\mathbf{A})$ and $\operatorname{det}\left(\mathbf{A}^{-1}\right)$ related?
Problem 10.37: Let $\mathbf{A}=\left(\begin{array}{ll}a & b \\ c & d\end{array}\right)$. In this problem, we find the conditions under which $\mathbf{A}$ is invertible, and we find the inverse in terms of $a, b, c$, and $d$.
(a) Suppose $\mathbf{A}$ is invertible, and let $\mathbf{A}^{-1}=\left(\begin{array}{ll}p & q \\ r & s\end{array}\right)$. What matrix must $\mathbf{A}^{-1} \mathbf{A}$ equal?
(b) Use your answer to (a) to find a system of equations in terms of $p, q, a, b, c$, and $d$. Solve the system for $p$ and $q$ in terms of the components of $\mathbf{A}$.
(c) Find $r$ and $s$ in terms of the components of $\mathbf{A}$.
(d) Under what conditions is it possible to find an inverse of $\mathbf{A}$, and what is that inverse in terms of $a, b, c$, and $d$ ?
(e) Confirm your result from part (d) by multiplying $\mathbf{A}$ by the matrix you found in part (d).

Problem 10.38:
(a) Find the inverse of $\left(\begin{array}{cc}4 & -3 \\ 5 & 7\end{array}\right)$.
(b) Use your answer to part (a) to solve the system of equations $4 x-3 y=-2,5 x+7 y=-3$.
(c) Find the inverse of $\left(\begin{array}{cc}-0.1 & 5 \\ -0.4 & 30\end{array}\right)$.
(d) Use your answer to part (c) to solve the system of equations $-0.1 t+5 u=-3,-0.4 t+30 u=7$.

Problem 10.39: If $\mathbf{A}=\left(\begin{array}{cc}4 & -3 \\ 2 & 1\end{array}\right)$ and $\mathbf{B}=\left(\begin{array}{ll}-5 & 3 \\ -8 & 2\end{array}\right)$, then find all matrices $\mathbf{M}$ such that $\mathbf{A M}=\mathbf{B}$.
Problem 10.40: Earlier we saw that $\mathbf{A B}$ is not necessarily equal to $\mathbf{B A .}$ Must $\mathbf{A A}^{-1}$ equal $\mathbf{A}^{-1} \mathbf{A}$ ?
Problem 10.41: Suppose $\mathbf{A}$ and $\mathbf{B}$ are invertible. Prove that $(\mathbf{A B})^{-1}=\mathbf{B}^{-1} \mathbf{A}^{-1}$.

Problem 10.33: Suppose the product $\mathbf{A B v}=\mathbf{v}$ for all vectors $\mathbf{v}$. What matrix must $\mathbf{A B}$ equal?

370

---

<!-- Page 371 -->

10.6. INVERTING A MATRIX

Solution for Problem 10.33: In Problem 10.13, we discovered the identity matrix $\mathbf{I}$, which is the unique matrix such that $\mathbf{I} \mathbf{v}=\mathbf{v}$ for all vectors $\mathbf{v}$. If $\mathbf{A B v}=\mathbf{v}$ for all vectors $\mathbf{v}$, then $\mathbf{A B}$ must be this matrix. That is, we must have $\mathbf{A B}=\left(\begin{array}{ll}1 & 0 \\ 0 & 1\end{array}\right)$.

Problem 10.34: If $\mathbf{A B}=\mathbf{I}$, then we say that $\mathbf{A}$ is the inverse of $\mathbf{B}$ and that $\mathbf{B}$ is invertible. We often denote the inverse of a matrix $\mathbf{B}$ as $\mathbf{B}^{-1}$. Let $\mathbf{M}=\left(\begin{array}{ll}2 & 3 \\ 6 & 7\end{array}\right)$. Find $\mathbf{M}^{-1}$.

Solution for Problem 10.34: We seek the matrix such that
$$\left(\begin{array}{ll}
a & b \\
c & d
\end{array}\right)\left(\begin{array}{ll}
2 & 3 \\
6 & 7
\end{array}\right)=\left(\begin{array}{ll}
1 & 0 \\
0 & 1
\end{array}\right)$$

Expanding the product on the left, we have
$$\left(\begin{array}{ll}
2 a+6 b & 3 a+7 b \\
2 c+6 d & 3 c+7 d
\end{array}\right)=\left(\begin{array}{ll}
1 & 0 \\
0 & 1
\end{array}\right) .$$

From the entries in the first rows, we have $2 a+6 b=1$ and $3 a+7 b=0$. Solving this system gives $a=-\frac{7}{4}$ and $b=\frac{3}{4}$. From the entries in the second rows, we have $2 c+6 d=0$ and $3 c+7 d=1$. Solving this system gives $c=\frac{3}{2}$ and $d=-\frac{1}{2}$. Checking, we find that
$$\left(\begin{array}{cc}
-7 / 4 & 3 / 4 \\
3 / 2 & -1 / 2
\end{array}\right)\left(\begin{array}{cc}
2 & 3 \\
6 & 7
\end{array}\right)=\left(\begin{array}{ll}
1 & 0 \\
0 & 1
\end{array}\right)$$
so $\mathbf{M}^{-1}=\left(\begin{array}{cc}-7 / 4 & 3 / 4 \\ 3 / 2 & -1 / 2\end{array}\right)$.
Problem 10.35: Does the matrix $\mathbf{M}=\left(\begin{array}{cc}3 & 5 \\ -6 & -10\end{array}\right)$ have an inverse? If it does, then find it. If it doesn't, explain why not.

Solution for Problem 10.35: Suppose $\mathbf{A}=\left(\begin{array}{ll}a & b \\ c & d\end{array}\right)$ is the inverse of $\mathbf{M}$. Then we must have $\mathbf{A M}=\mathbf{I}$, or
$$\left(\begin{array}{ll}
a & b \\
c & d
\end{array}\right)\left(\begin{array}{cc}
3 & 5 \\
-6 & -10
\end{array}\right)=\left(\begin{array}{ll}
1 & 0 \\
0 & 1
\end{array}\right) .$$

Expanding the product on the left gives
$$\left(\begin{array}{cc}
3 a-6 b & 5 a-10 b \\
3 c-6 d & 5 c-10 d
\end{array}\right)=\left(\begin{array}{ll}
1 & 0 \\
0 & 1
\end{array}\right)$$

From the entries in the first rows, we have $3 a-6 b=1$ and $5 a-10 b=0$. The second equation gives $a=2 b$, but substituting this into the first equation gives $6 b-6 b=1$. Uh-oh; this equation has no solution! Therefore, we cannot find a matrix $\mathbf{A}$ such that $\mathbf{A M}=\mathbf{I}$, which means that $\mathbf{M}$ does not have an inverse.

Why doesn't M have an inverse? Here's a clue:
Problem 10.36: If $\mathbf{A}$ is invertible, then how are $\operatorname{det}(\mathbf{A})$ and $\operatorname{det}\left(\mathbf{A}^{-1}\right)$ related?
Solution for Problem 10.36: We have $\mathbf{A}^{-1} \mathbf{A}=\mathbf{I}$, so $\operatorname{det}\left(\mathbf{A}^{-1} \mathbf{A}\right)=\operatorname{det}(\mathbf{I})=(1)(1)-(0)(0)=1$. We also have $\operatorname{det}\left(\mathbf{A}^{-1} \mathbf{A}\right)=\operatorname{det}\left(\mathbf{A}^{-1}\right) \cdot \operatorname{det}(\mathbf{A})$, so we must have $\operatorname{det}\left(\mathbf{A}^{-1}\right) \cdot \operatorname{det}(\mathbf{A})=1$.

371

---

<!-- Page 372 -->

CHAPTER 10. MATRICES IN TWO DIMENSIONS

Now we see why the matrix $\mathbf{M}=\left(\begin{array}{cc}3 & 5 \\ -6 & -10\end{array}\right)$ in Problem 10.35 has no inverse. Since
$$\operatorname{det}(\mathbf{M})=(3)(-10)-(-6)(5)=0$$
we know that there can be no matrix $\mathbf{M}^{-1}$ such that $\operatorname{det}\left(\mathbf{M}^{-1}\right) \cdot \operatorname{det}(\mathbf{M})=1$.
Problem 10.37: Let $\mathbf{A}=\left(\begin{array}{ll}a & b \\ c & d\end{array}\right)$. Under what conditions does $\mathbf{A}$ have an inverse? If $\mathbf{A}$ has an inverse, what is that inverse in terms of $a, b, c$, and $d$ ?

Solution for Problem 10.37: Suppose $\mathbf{A}$ is invertible. We let $\mathbf{A}^{-1}=\left(\begin{array}{cl}p & q \\ r & s\end{array}\right)$, so we must have
$$\left(\begin{array}{ll}
p & q \\
r & s
\end{array}\right)\left(\begin{array}{ll}
a & b \\
c & d
\end{array}\right)=\left(\begin{array}{ll}
1 & 0 \\
0 & 1
\end{array}\right) .$$

Expanding the product on the left gives
$$\left(\begin{array}{cc}
p a+q c & p b+q d \\
r a+s c & r b+s d
\end{array}\right)=\left(\begin{array}{ll}
1 & 0 \\
0 & 1
\end{array}\right) .$$

Equating the corresponding entries on the first rows gives the system $p a+q c=1, p b+q d=0$, and equating the corresponding entries on the second rows gives $r a+s c=0, r b+s d=1$. If $\left|\begin{array}{ll}a & c \\ b & d\end{array}\right| \neq 0$, then applying Cramer's rule to solve the system $p a+q c=1, p b+q d=0$ for $p$ and $q$ gives
$$p=\frac{\left|\begin{array}{ll}
1 & c \\
0 & d
\end{array}\right|}{\left|\begin{array}{ll}
a & c \\
b & d
\end{array}\right|}=\frac{d}{\left|\begin{array}{ll}
a & c \\
b & d
\end{array}\right|} \quad \text { and } \quad q=\frac{\left|\begin{array}{ll}
a & 1 \\
b & 0
\end{array}\right|}{\left|\begin{array}{ll}
a & c \\
b & d
\end{array}\right|}=\frac{-b}{\left|\begin{array}{ll}
a & c \\
b & d
\end{array}\right|} .$$

Similarly, if $\left|\begin{array}{ll}a & c \\ b & d\end{array}\right| \neq 0$, then we can apply Cramer's rule to $r a+s c=0, r b+s d=1$ to give
$$r=\frac{\left|\begin{array}{ll}
0 & c \\
1 & d
\end{array}\right|}{\left|\begin{array}{ll}
a & c \\
b & d
\end{array}\right|}=\frac{-c}{\left|\begin{array}{ll}
a & c \\
b & d
\end{array}\right|} \quad \text { and } \quad s=\frac{\left|\begin{array}{ll}
a & 0 \\
b & 1
\end{array}\right|}{\left|\begin{array}{ll}
a & c \\
b & d
\end{array}\right|}=\frac{a}{\left|\begin{array}{ll}
a & c \\
b & d
\end{array}\right|} .$$

Since $\left|\begin{array}{ll}a & c \\ b & d\end{array}\right|=a d-b c=\operatorname{det}(\mathbf{A})$, the denominator in each of the results for $p, q, r$, and $s$ equals $\operatorname{det}(\mathbf{A})$, and we have
$$\mathbf{A}^{-1}=\frac{1}{\operatorname{det}(\mathbf{A})}\left(\begin{array}{cc}
d & -b \\
-c & a
\end{array}\right) .$$

Checking, we find that
$$\mathbf{A}^{-1} \mathbf{A}=\frac{1}{\operatorname{det}(\mathbf{A})}\left(\begin{array}{cc}
d & -b \\
-c & a
\end{array}\right)\left(\begin{array}{cc}
a & b \\
c & d
\end{array}\right)=\frac{1}{\operatorname{det}(\mathbf{A})}\left(\begin{array}{cc}
d a-b c & d b-b d \\
-c a+a c & -c b+a d
\end{array}\right)=\frac{1}{\operatorname{det}(\mathbf{A})}\left(\begin{array}{cc}
a d-b c & 0 \\
0 & a d-b c
\end{array}\right)=\left(\begin{array}{cc}
1 & 0 \\
0 & 1
\end{array}\right)$$
as expected.
Our work above shows that we can find an inverse of any $2 \times 2$ matrix with a nonzero determinant. We say that such a matrix is invertible. Our solution also tells us that if $\mathbf{A}$ is invertible, then its inverse is unique. That is, if $\mathbf{A}$ is invertible, there is only one matrix $\mathbf{A}^{-1}$ such that $\mathbf{A}^{-1} \mathbf{A}=\mathbf{I}$.

372

---

<!-- Page 373 -->

10.6. INVERTING A MATRIX

Important: Let $\mathbf{A}=\left(\begin{array}{ll}a & b \\ c & d\end{array}\right)$. If $\operatorname{det}(\mathbf{A})=0$, then $\mathbf{A}$ does not have an inverse. Otherwise, we have
$$\mathbf{A}^{-1}=\frac{1}{\operatorname{det}(\mathbf{A})}\left(\begin{array}{cc}
d & -b \\
-c & a
\end{array}\right)$$

Problem 10.38:
(a) Find the inverse of $\left(\begin{array}{cc}4 & -3 \\ 5 & 7\end{array}\right)$.
(b) Use your answer to part (a) to solve the system of equations $4 x-3 y=-2,5 x+7 y=-3$.
(c) Find the inverse of $\left(\begin{array}{cc}-0.1 & 5 \\ -0.4 & 30\end{array}\right)$.
(d) Use your answer to part (c) to solve the system of equations $-0.1 t+5 u=-3,-0.4 t+30 u=7$.

Solution for Problem 10.38:
(a) The determinant of the matrix is $(4)(7)-(-3)(5)=43$, so the inverse of the matrix is
$$\frac{1}{43}\left(\begin{array}{cc}
7 & 3 \\
-5 & 4
\end{array}\right)=\left(\begin{array}{cc}
\frac{7}{43} & \frac{3}{43} \\
-\frac{5}{43} & \frac{4}{43}
\end{array}\right)$$
(b) We can write the system of equations as $\left(\begin{array}{cc}4 & -3 \\ 5 & 7\end{array}\right)\binom{x}{y}=\binom{-2}{-3}$. Multiplying both sides of this equation by the inverse we found in part (a), we have
$$\left(\begin{array}{cc}
\frac{7}{43} & \frac{3}{43} \\
-\frac{5}{43} & \frac{4}{43}
\end{array}\right)\left(\begin{array}{cc}
4 & -3 \\
5 & 7
\end{array}\right)\binom{x}{y}=\left(\begin{array}{cc}
\frac{7}{43} & \frac{3}{43} \\
-\frac{5}{43} & \frac{4}{43}
\end{array}\right)\binom{-2}{-3}=\binom{-\frac{23}{43}}{-\frac{2}{43}} .$$

The product of a matrix and its inverse is the identity, so we have $\binom{x}{y}=\binom{-23 / 43}{-2 / 43}$.
(c) The determinant of the matrix is $(-0.1)(30)-(5)(-0.4)=-1$, so the inverse of the matrix is
$$\frac{1}{-1}\left(\begin{array}{cc}
30 & -5 \\
0.4 & -0.1
\end{array}\right)=\left(\begin{array}{cc}
-30 & 5 \\
-0.4 & 0.1
\end{array}\right)$$
(d) We write the system as $\left(\begin{array}{cc}-0.1 & 5 \\ -0.4 & 30\end{array}\right)\binom{t}{u}=\binom{-3}{7}$. Multiplying both sides by the inverse we found in part (c), we have
$$\left(\begin{array}{cc}
-30 & 5 \\
-0.4 & 0.1
\end{array}\right)\left(\begin{array}{cc}
-0.1 & 5 \\
-0.4 & 30
\end{array}\right)\binom{t}{u}=\left(\begin{array}{cc}
-30 & 5 \\
-0.4 & 0.1
\end{array}\right)\binom{-3}{7}=\binom{125}{1.9} .$$

As before, the product of a matrix and its inverse is the identity, so we have $\binom{t}{u}=\binom{125}{1.9}$.

Problem 10.39: If $\mathbf{A}=\left(\begin{array}{cc}4 & -3 \\ 2 & 1\end{array}\right)$ and $\mathbf{B}=\left(\begin{array}{ll}-5 & 3 \\ -8 & 2\end{array}\right)$, then find all matrices $\mathbf{M}$ such that $\mathbf{A M}=\mathbf{B}$.

Solution for Problem 10.39: We can't divide by $\mathbf{A}$, but because its determinant is nonzero, we can multiply by its inverse. The determinant of the matrix is 10 , so $\mathbf{A}^{-1}=\frac{1}{10}\left(\begin{array}{cc}1 & 3 \\ -2 & 4\end{array}\right)=\left(\begin{array}{cc}0.1 & 0.3 \\ -0.2 & 0.4\end{array}\right)$. What's wrong with this next step:

373

---

<!-- Page 374 -->

CHAPTER 10. MATRICES IN TWO DIMENSIONS

Bogus Solution: Multiplying both sides of the given equation by $\mathbf{A}^{-1}$ gives us
$$\mathrm{IM}=\mathrm{BA}^{-1} .$$

The problem here is that we started with $\mathbf{A M}=\mathbf{B}$ and multiplied $\mathbf{A M}$ on the left by $\mathbf{A}^{-1}$ to get IM, but we multiplied $\mathbf{B}$ on the right by $\mathbf{A}^{-1}$. While we can go from $t=s$ to $r t=s r$ with real numbers, we can't go from $\mathbf{T}=\mathbf{S}$ to $\mathbf{R T}=\mathbf{S R}$ with matrices, since matrix multiplication is not commutative.

We multiply both sides of the equation $\mathbf{A M}=\mathbf{B}$ on the left by $\mathbf{A}^{-1}$ to produce $\mathbf{A}^{-1} \mathbf{A M}=\mathbf{A}^{-1} \mathbf{B}$. The left side then becomes IM, which equals M, so we have
$$\mathbf{M}=\mathbf{A}^{-1} \mathbf{B}=\left(\begin{array}{cc}
0.1 & 0.3 \\
-0.2 & 0.4
\end{array}\right)\left(\begin{array}{ll}
-5 & 3 \\
-8 & 2
\end{array}\right)=\left(\begin{array}{ll}
-2.9 & 0.9 \\
-2.2 & 0.2
\end{array}\right) .$$

So, we see that there is a unique solution to the equation $\mathbf{A M}=\mathbf{B}$. Moreover, our solution shows us that whenever A is invertible, there is a unique solution for $\mathbf{M}$ to the equation $\mathbf{A M}=\mathbf{B}$, which is $\mathbf{M}=\mathbf{A}^{-1} \mathbf{B}$.

Problem 10.40: Earlier we saw that $\mathbf{A B}$ is not necessarily equal to $\mathbf{B A}$. Must $\mathbf{A A}^{-1}$ equal $\mathbf{A}^{-1} \mathbf{A}$ ?
Solution for Problem 10.40: We have defined $\mathbf{A}^{-\mathbf{1}}$ as the matrix such that $\mathbf{A}^{-\mathbf{1}} \mathbf{A}=\mathbf{I}$, so to check if $\mathbf{A A}^{-1}=\mathbf{A}^{-\mathbf{1}} \mathbf{A}$, we need only compute $\mathbf{A A}^{-1}$. Letting $\mathbf{A}=\left(\begin{array}{ll}a & b \\ c & d\end{array}\right)$, we have
$$\mathbf{A A}^{-1}=\left(\begin{array}{ll}
a & b \\
c & d
\end{array}\right)\left(\frac{1}{\operatorname{det}(\mathbf{A})}\left(\begin{array}{cc}
d & -b \\
-c & a
\end{array}\right)\right)=\frac{1}{\operatorname{det}(\mathbf{A})}\left(\begin{array}{ll}
a & b \\
c & d
\end{array}\right)\left(\begin{array}{cc}
d & -b \\
-c & a
\end{array}\right)=\frac{1}{\operatorname{det}(\mathbf{A})}\left(\begin{array}{cc}
a d-b c & 0 \\
0 & a d-b c
\end{array}\right)=\mathbf{I} .$$

Therefore, $\mathbf{A A}^{-1}=\mathbf{A}^{-1} \mathbf{A}=\mathbf{I}$.

We therefore see that if $\mathbf{A}$ is invertible, then the inverse of $\mathbf{A}^{-1}$ is $\mathbf{A}$.
Important: If $\mathbf{A}$ is invertible, then we have $\mathbf{A A}^{-1}=\mathbf{A}^{-1} \mathbf{A}=\mathbf{I}$.
(1)

Problem 10.41: Suppose $\mathbf{A}$ and $\mathbf{B}$ are invertible. Prove that $(\mathbf{A B})^{-1}=\mathbf{B}^{-1} \mathbf{A}^{-1}$.
Solution for Problem 10.41: If $\mathbf{M}$ is the inverse of $\mathbf{A B}$, then we must have $\mathbf{M}(\mathbf{A B})=\mathbf{I}$. So, we test $\mathbf{M}=\mathbf{B}^{-1} \mathbf{A}^{-1}$, and using the associative property, we find
$$\left(B^{-1} A^{-1}\right)(A B)=B^{-1}\left(A^{-1}(A B)\right)=B^{-1}\left(\left(A^{-1} A\right) B\right)=B^{-1} I B=B^{-1} B=I .$$

Therefore, the inverse of $\mathbf{A B}$ is $\mathbf{B}^{-1} \mathbf{A}^{-1}$.
10.6.1 What is the inverse of $\mathbf{I}$ ?
10.6.2 For each of the following matrices, find the inverse or show that the matrix does not have an inverse.
(a) $\quad\left(\begin{array}{cc}6 & 8 \\ -2 & 4\end{array}\right)$
(b) $\quad\left(\begin{array}{cc}2 & -1 \\ -0.9 & 0.5\end{array}\right)$
(c) $\quad\left(\begin{array}{cc}-40 & 30 \\ 8 & -6\end{array}\right)$

374

---

<!-- Page 375 -->

10.7. SUMMARY
10.6.3 Suppose we are given matrix $\mathbf{A}$ and vector $\mathbf{v}$.
(a) If $\mathbf{A}$ is nonsingular, must there be a vector $\mathbf{w}$ such that $\mathbf{A w}=\mathbf{v}$ ?
(b) If $\mathbf{A}$ is singular, can we conclude that there is no vector such that $\mathbf{A w}=\mathbf{v}$ ?
10.6.4 All of the entries of $\mathbf{M}$ and $\mathbf{M}^{-1}$ are integers. Find all possible values of $\operatorname{det}(\mathbf{M})$.
10.6.5 In Problem 10.41, we showed that if $\mathbf{A}$ and $\mathbf{B}$ are invertible, then $(\mathbf{A B})^{-1}=\mathbf{B}^{-1} \mathbf{A}^{-1}$. If $\mathbf{A}$ and $\mathbf{B}$ are invertible, then must we have $(\mathbf{A}+\mathbf{B})^{-1}=\mathbf{B}^{-1}+\mathbf{A}^{-1}$ ?
10.6.6 In Problem 10.18, we found that multiplying $\binom{x}{y}$ by the matrix $\left(\begin{array}{cc}a & -b \\ b & a\end{array}\right)$ corresponds to multiplying the complex number $x+y i$ by $a+b i$. Find the matrix $\mathbf{M}$ such that multiplying $\binom{x}{y}$ by $\mathbf{M}$ corresponds to dividing $x+y i$ by $a+b i$ (assuming $a$ and $b$ are not both 0 ).
10.7 Summary

A $2 \times 2$ matrix represents a linear function that maps vectors in 2 dimensions to vectors in 2 dimensions. This mapping is typically illustrated as a product of the matrix and a vector according to the definition
$$\left(\begin{array}{ll}
a & b \\
c & d
\end{array}\right)\binom{x}{y}=\binom{a x+b y}{c x+d y} .$$

For any matrix $\mathbf{A}$, any scalar $c$, and any vectors $\mathbf{v}$ and $\mathbf{w}$, we have $\mathbf{A}(c \mathbf{v})=c(\mathbf{A v})$ and $\mathbf{A}(\mathbf{v}+\mathbf{w})=\mathbf{A v}+\mathbf{A w}$.
We add two matrices by adding the corresponding components in the matrices, and define the product of two matrices as follows:
$$\left(\begin{array}{ll}
a_{11} & a_{12} \\
a_{21} & a_{22}
\end{array}\right)\left(\begin{array}{ll}
b_{11} & b_{12} \\
b_{21} & b_{22}
\end{array}\right)=\left(\begin{array}{ll}
a_{11} b_{11}+a_{12} b_{21} & a_{11} b_{12}+a_{12} b_{22} \\
a_{21} b_{11}+a_{22} b_{21} & a_{21} b_{12}+a_{22} b_{22}
\end{array}\right) .$$

Matrix multiplication is not commutative, but it is associative and distributive.

\begin{tabular}{|l|l|}
\hline Important: & If $\mathbf{v}$ and $\mathbf{w}$ are linearly independent and $\mathbf{A}$ and $\mathbf{B}$ are matrices such that $\mathbf{A v}=\mathbf{B v}$ and $\mathbf{A w}=\mathbf{B w}$, then $\mathbf{A}=\mathbf{B}$. \\
\hline Important: & \begin{tabular}{l}
The matrix
$$\mathbf{I}=\left(\begin{array}{ll}
1 & 0 \\
0 & 1
\end{array}\right)$$ \\
is called the identity matrix. Multiplying a vector $\mathbf{v}$ by $\mathbf{I}$ leaves the vector unchanged; in other words, $\mathbf{I v}=\mathbf{v}$ for all vectors $\mathbf{v}$. We also have $\mathbf{I A}=\mathbf{A I}=\mathbf{A}$ for any $2 \times 2$ matrix $\mathbf{A}$.
\end{tabular} \\
\hline Important: & Any linear function that maps vectors to vectors can be expressed as multiplication by a matrix, where the columns of the matrix are given by the vectors to which $\mathbf{i}$ and $\mathbf{j}$ are mapped by the function. \\
\hline
\end{tabular}

375

---

<!-- Page 376 -->

CHAPTER 10. MATRICES IN TWO DIMENSIONS

Definition: The determinant of the matrix $\left(\begin{array}{ll}a & b \\ c & d\end{array}\right)$ is the quantity $a d-b c$. We often denote this determinant as $\left|\begin{array}{ll}a & b \\ c & d\end{array}\right|$, so
$$\left|\begin{array}{ll}
a & b \\
c & d
\end{array}\right|=a d-b c$$

We also can denote the determinant of a matrix $\mathbf{A}$ as $\operatorname{det}(\mathbf{A})$.
We say a matrix is singular if its determinant is 0 , and nonsingular if its determinant is nonzero. If $\operatorname{det}(\mathbf{A}) \neq 0$, then for any vector $\mathbf{c}$, there is unique vector $\mathbf{v}$ such that $\mathbf{A v}=\mathbf{c}$.

The determinant has the following properties:
$$\left|\begin{array}{ll}
a & b \\
c & d
\end{array}\right|=\left|\begin{array}{cc}
a+k c & b+k d \\
c & d
\end{array}\right|=\left|\begin{array}{cc}
a & b \\
c+k a & d+k b
\end{array}\right|=\left|\begin{array}{ll}
a+k b & b \\
c+k d & d
\end{array}\right|=\left|\begin{array}{ll}
a & b+k a \\
c & d+k c
\end{array}\right| \text {. }$$
- For any $2 \times 2$ matrix $\mathbf{A}$ and any constant $k$, we have $\operatorname{det}(k \mathbf{A})=k^{2} \operatorname{det}(\mathbf{A})$.
- Multiplying either column or either row of a matrix $\mathbf{A}$ by any constant $k$ gives a matrix with determinant $k \operatorname{det}(\mathbf{A})$.
- For any $2 \times 2$ matrix $\mathbf{A}$, swapping the rows or columns of $\mathbf{A}$ produces a matrix with determinant $(-1) \operatorname{det}(\mathbf{A})$.
- The determinant of a $2 \times 2$ matrix is 0 if and only if the rows of the matrix are linearly dependent.
- We have $\operatorname{det}(\mathbf{A B})=\operatorname{det}(\mathbf{A}) \operatorname{det}(\mathbf{B})$ for any $2 \times 2$ matrices $\mathbf{A}$ and $\mathbf{B}$.
- The absolute value of the determinant $\left|\begin{array}{ll}a & b \\ c & d\end{array}\right|$ equals the area of the parallelogram that has as two sides the vectors $\binom{a}{c}$ and $\binom{b}{d}$ drawn from the origin.

If $\mathbf{B A}=\mathbf{I}$, then we say that $\mathbf{B}$ is the inverse of $\mathbf{A}$ and that $\mathbf{A}$ is invertible. We typically denote the inverse of $\mathbf{A}$ as $\mathbf{A}^{-1}$, and we have $\mathbf{A A}^{-1}=\mathbf{A}^{-1} \mathbf{A}=\mathbf{I}$.

Important: Let $\mathbf{A}=\left(\begin{array}{ll}a & b \\ c & d\end{array}\right)$. If $\operatorname{det}(\mathbf{A})=0$, then $\mathbf{A}$ does not have an inverse. Otherwise, we $\square$ have
$$\mathbf{A}^{-1}=\frac{1}{\operatorname{det}(\mathbf{A})}\left(\begin{array}{cc}
d & -b \\
-c & a
\end{array}\right)$$

REVIEW PROBLEMS
10.42 Find constants $a, b$, and $c$ such that $\left(\begin{array}{ll}a & 4 \\ 7 & 2\end{array}\right)+c\left(\begin{array}{cc}6 & b \\ -3 & -1\end{array}\right)=\left(\begin{array}{cc}32 & 9 \\ -8 & -3\end{array}\right)$.
10.43 Let $\mathbf{M}=\left(\begin{array}{cc}2 & 3 \\ -7 & 0\end{array}\right)$ and $\mathbf{N}=\left(\begin{array}{cc}-3 & -1 \\ 5 & 2\end{array}\right)$. Find $\mathbf{M N}$ and $\mathbf{N M}$.

376

---

<!-- Page 377 -->

REVIEW PROBLEMS
10.44 Show that the rows of a matrix are linearly dependent if and only if the columns of the matrix are linearly dependent.
10.45 Is there a matrix $\mathbf{F}$ such that for all matrices $\mathbf{A}$, the product $\mathbf{F A}$ is the matrix formed by swapping the columns of $\mathbf{A}$ ? If such a matrix exists, what is $\mathbf{A F}$ for that matrix?
10.46 Suppose $\mathbf{A v}=\binom{3}{-2}$ and $\mathbf{A w}=\binom{-7}{4}$. Find $\mathbf{A}(3 \mathbf{v}-4 \mathbf{w})$.
10.47
(a) Find two matrices besides 0 and the identity such that $\mathbf{A}^{2}=\mathbf{A}$.
(b) Find a matrix besides 0 and the identity such that $\mathbf{A}^{3}=\mathbf{A}$ and $\mathbf{A}^{3} \neq \mathbf{A}^{2}$.
10.48
(a) Find a matrix $\mathbf{A}$ such that $\mathbf{A v}$ is the reflection of $\mathbf{v}$ over the $y$-axis.
(b) Find a matrix $\mathbf{B}$ such that $\mathbf{B v}$ is the reflection of $\mathbf{v}$ over the graph of $x=y$.
10.49 What is the matrix $\mathbf{R}$ such that $\mathbf{R} \mathbf{v}$ is a clockwise rotation of $\mathbf{v}$ by an angle $\theta$ for all vectors $\mathbf{v}$ ?
10.50 Let $\mathbf{T}=\left(\begin{array}{cc}\cos \theta & -\sin \theta \\ \sin \theta & \cos \theta\end{array}\right)$. Compute $\mathbf{T}^{2}$ and $\mathbf{T}^{3}$ and confirm that these equal the rotation matrices for angles of $2 \theta$ and $3 \theta$, respectively.
10.51 Find $\mathbf{M}^{10}$ if $\mathbf{M}=\left(\begin{array}{cc}\sqrt{2} & -\sqrt{2} \\ \sqrt{2} & \sqrt{2}\end{array}\right)$.
10.52 Point $P$ is reflected over the $y$-axis and the result is rotated $60^{\circ}$ counterclockwise about the origin. The point that results is $(-2-\sqrt{3}, 1-2 \sqrt{3})$. What are the coordinates of point $P$ ?
10.53 Show that $f(0)=0$ for any linear function $f$ that maps vectors to vectors.
10.54 Evaluate the following:
(a) $\left|\begin{array}{cc}7 & -4 \\ -2 & 7\end{array}\right|$
(b) $\left|\begin{array}{cc}0.27 & -175 \\ -0.15 & 95\end{array}\right|$
10.55
(a) Must the product of two singular matrices be singular?
(b) Must the product of two nonsingular matrices be nonsingular?
(c) Is the product of a singular matrix and nonsingular matrix always singular, always nonsingular, or sometimes singular and sometimes nonsingular?
10.56 Suppose we form the first row of $\mathbf{C}$ by adding $k$ times the second row of $\mathbf{A}$ to the first row of $\mathbf{A}$, and we form the second row of $\mathbf{C}$ by adding $j$ times the first row of $\mathbf{A}$ to the second row of $\mathbf{A}$. Must the determinants of $\mathbf{A}$ and $\mathbf{C}$ be the same?
10.57 Explain geometrically why swapping the columns of $\mathbf{A}$ produces a matrix with determinant $(-1) \operatorname{det}(\mathbf{A})$.
10.58 For each of the following matrices, find the inverse, or show that the matrix does not have an inverse.
(a) $\left(\begin{array}{ll}-2 & 3 \\ -2 & 8\end{array}\right)$
(b) $\quad\left(\begin{array}{cc}0 & -3 \\ -2 & 0\end{array}\right)$
(c) $\left(\begin{array}{cc}6 & 12 \\ -2 & -4\end{array}\right)$
10.59 Suppose that $\mathbf{A}^{-1}=\mathbf{A}$. Find all possible values of $\operatorname{det}(\mathbf{A})$.

377

---

<!-- Page 378 -->

CHAPTER 10. MATRICES IN TWO DIMENSIONS
10.60 The transpose of a matrix $\left(\begin{array}{ll}a & b \\ c & d\end{array}\right)$ is $\left(\begin{array}{ll}a & c \\ b & d\end{array}\right)$. We denote the transpose of $\mathbf{A}$ as $\mathbf{A}^{T}$.
(a) Show that $(\mathbf{A}+\mathbf{B})^{\vec{T}}=\mathbf{A}^{T}+\mathbf{B}^{T}$.
(b) If $\mathbf{A}$ is invertible, must $\mathbf{A}^{T}$ be invertible?
(c) If $\mathbf{A}^{T}$ is invertible, must $\left(\mathbf{A}^{T}\right)^{-1}$ equal $\left(\mathbf{A}^{-1}\right)^{T}$ ?
(d) Let $\mathbf{R}=\left(\begin{array}{cc}2 & 3 \\ -1 & 4\end{array}\right)$ and $\mathbf{S}=\left(\begin{array}{ll}-1 & 5 \\ -6 & 3\end{array}\right)$. Find $\mathbf{R S},(\mathbf{R S})^{T}, \mathbf{R}^{T} \mathbf{S}^{T}$, and $\mathbf{S}^{T} \mathbf{R}^{T}$. If you notice anything interesting in your results, try to prove that what you noticed holds for any matrices $\mathbf{R}$ and $\mathbf{S}$.

Challenge Problems
10.61 Find two nonzero matrices $\mathbf{A}$ and $\mathbf{B}$ such that neither matrix is the identity, $\mathbf{A} \neq \mathbf{B}$, and $\mathbf{A B}=\mathbf{B A} \neq \mathbf{0}$. As an extra challenge, find a pair such that no entry in either matrix is 0 . Hints: 118
10.62 Suppose $\mathbf{A}^{6}=\mathbf{A}$. Find all possible values of $\operatorname{det}(\mathbf{A})$, assuming all the entries of $\mathbf{A}$ are real. What if we allow the entries of $\mathbf{A}$ to be nonreal?
10.63 Find a matrix such that $\mathbf{A}^{4}=\mathbf{A}$, but $\mathbf{A}^{2} \neq \mathbf{A}$. Hints: 230, 202
10.64 Let $\mathbf{A}$ and $\mathbf{B}$ be two $2 \times 2$ matrices. Prove that $\operatorname{det}(\mathbf{A}+\mathbf{B})+\operatorname{det}(\mathbf{A}-\mathbf{B})=2(\operatorname{det}(\mathbf{A})+\operatorname{det}(\mathbf{B}))$.
10.65 Explain why the line through the points $\left(x_{1}, y_{1}\right)$ and $\left(x_{2}, y_{2}\right)$ is the graph of the equation $\left|\begin{array}{ll}x-x_{1} & y-y_{1} \\ x-x_{2} & y-y_{2}\end{array}\right|=0$.
10.66 ★ Let $\mathbf{A}=\left(\begin{array}{ll}1 & 1 \\ 1 & 0\end{array}\right)$.
(a) Prove that $\mathbf{A}^{n}=\left(\begin{array}{cc}F_{n+1} & F_{n} \\ F_{n} & F_{n-1}\end{array}\right)$, where $F_{n}$ denotes the $n^{\text {th }}$ Fibonacci number.
(b) Prove that $F_{n+1} F_{n-1}-F_{n}^{2}=(-1)^{n}$ for all $n \geq 0$. Hints: 136
10.67 Describe all $(x, y)$ such that there exists a value of $\theta$ for which $x \cos \theta-y \sin \theta=3$ and $x \sin \theta+y \cos \theta=2$. Hints: 115
10.68
(a) Show that reflection over any line through the origin is a linear transformation.
(b) Find the reflection of $(4,-6)$ over the line $y=2 x$.
(c) Let $f$ be a function that maps a point $(x, y)$ to the image of the reflection of $(x, y)$ over the line $x+y=6$. Is $f$ a linear function?
10.69 Let $\mathbf{A}=\left(\begin{array}{cc}-2 & 6 \\ 2 & -1\end{array}\right)$.
(a) Find all nonzero vectors $\mathbf{v}$ such that there exists a constant $\lambda$ for which $\mathbf{A v}=\lambda \mathbf{v}$.
(b) For each vector $\mathbf{v}$ and corresponding $\lambda$ you find in part(a), find $\operatorname{det}(\mathbf{A}-\lambda \mathbf{I})$. Explain your results. Hints: 213
10.70 Suppose the columns of $\mathbf{A}$ are orthogonal. Find both a geometric and an algebraic proof that $|\operatorname{det}(\mathbf{A})|$ equals the product of the norms of the columns.

378

---

<!-- Page 379 -->

CHALLENGE PROBLEMS
10.71 ★ Suppose that the points $\left(x_{1}, y_{1}\right),\left(x_{2}, y_{2}\right), \ldots,\left(x_{n}, y_{n}\right)$ are the vertices of a convex polygon, in counterclockwise order. We can find the area of this polygon with the following process:
1. List the vertices in order, as shown in the middle two columns at right, and include ( $x_{1}, y_{1}$ ) a second time at the end of the list.
2. Take pairwise diagonal products, as shown in the first and fourth columns at right.
3. Sum the first column and sum the fourth column. The area of the polygon then is half the difference of the fourth column sum and the first column sum.
This fact is sometimes sometimes referred to Shoelace Theorem.
(a) Prove the Shoelace Theorem for $n=3$.
(b) Prove the Shoelace Theorem for $n=4$. Hints: 18
(c) Prove the Shoelace Theorem for any integer $n$ with $n \geq 3$. Hints: 287
10.72 Back on page 367, we made the claim that the parallelogram with sides Ar and As has signed area $\operatorname{det}(\mathbf{A})$ times the signed area of the parallelogram with sides $\mathbf{r}$ and $\mathbf{s}$, where the orientation is determined by traveling first from the origin along $\mathbf{r}$. We proved this statement when $\mathbf{r}$ and s are $\mathbf{i}$ and $\mathbf{j}$. In this problem, we'll prove it for any linearly independent pair of vectors $\mathbf{r}$ and $\mathbf{s}$.
(a) Why must there exist a matrix $\mathbf{B}$ such that $\mathbf{B i}=\mathbf{r}$ and $\mathbf{B j}=\mathbf{s}$ ?
(b) In terms of $\mathbf{A}$ and $\mathbf{B}$, what is the signed area of the parallelogram with sides $\mathbf{r}$ and $\mathbf{s}$ ?
(c) In terms of $\mathbf{A}$ and $\mathbf{B}$, what is the signed area of the parallelogram with sides Ar and As? Note that you cannot simply multiply your answer from part (b) by $\operatorname{det}(\mathbf{A})$; we are trying to prove such a multiplication works!
(d) Complete the proof by showing that the parallelogram with sides Ar and As has signed area $\operatorname{det}(\mathbf{A})$ times the signed area of the parallelogram with sides $\mathbf{r}$ and s .
10.73 For any vector $\mathbf{v}$, the product $\mathbf{T v}$ is the reflection of $\mathbf{v}$ over the line $y=3 x$. Find $\operatorname{det}(\mathbf{T})$. Hints: 144
10.74 Find all matrices $\mathbf{A}$ such that $\mathbf{A}^{2}=\mathbf{I}$. Hints: 75, 116
10.75 Is it true that $\mathbf{A}^{2}-\mathbf{B}^{2}=(\mathbf{A}-\mathbf{B})(\mathbf{A}+\mathbf{B})$ for all matrices $\mathbf{A}$ and $\mathbf{B}$ ?
$\mathbf{1 0 . 7 6} \boldsymbol{\star}$ Let $\mathbf{A}$ and $\mathbf{B}$ be matrices such that $\mathbf{A}+\mathbf{B}=\mathbf{A B}$. Show that $\mathbf{A B}=\mathbf{B A}$. Hints: 222, 277, 54
$\mathbf{1 0 . 7 7} \star$ Let $\mathbf{A}$ be a $2 \times 2$ matrix such that $\mathbf{A}\binom{1}{3}=\binom{4}{5}$ and $\mathbf{A}^{2}-\mathbf{A}+5 \mathbf{I}=\mathbf{0}$. Find $\mathbf{A}$. Hints: 119
10.78
(a) If $\mathbf{A}^{2}=\mathbf{0}$, then must $\mathbf{A}=\mathbf{0}$ ?
(b) $\star$ If $\mathbf{A}^{3}=\mathbf{0}$, then must $\mathbf{A}^{2}=\mathbf{0}$ ? Hints: 221

379

---

