# Chapter 11: Vectors and Matrices in Three Dimensions, Part 1

<!-- Page 380 -->

CHAPTER 11. VECTORS AND MATRICES IN THREE DIMENSIONS, PART 1

Every new body of discovery is mathematical in form, because there is no other guidance we can have. - Charles Darwin
CHAPTER 11 Vectors and Matrices in Three Dimensions, Part 1
11.1 Vectors in Three Dimensions

Vectors in three dimensions have much in common with vectors in two dimensions. Just as we denote a vector in two dimensions with an ordered pair $\binom{x}{y}$, we denote a vector in three dimensions with an ordered triple $\left(\begin{array}{l}a \\ b \\ c\end{array}\right)$.

We define vector addition and multiplication by a scalar for vectors in three dimensions in essentially the same way we did in two dimensions:
- Vector addition. We add vectors by adding the corresponding components:
$$\left(\begin{array}{l}
a \\
b \\
c
\end{array}\right)+\left(\begin{array}{l}
x \\
y \\
z
\end{array}\right)=\left(\begin{array}{l}
a+x \\
b+y \\
c+z
\end{array}\right) .$$
- Multiplication of a vector by a scalar. We multiply a vector by a scalar by multiplying each component of the vector by the scalar:
$$k\left(\begin{array}{l}
a \\
b \\
c
\end{array}\right)=\left(\begin{array}{l}
k a \\
k b \\
k c
\end{array}\right)$$

We also define the dot product of two vectors in three dimensions much as we defined it for vectors in two

380

---

<!-- Page 381 -->

11.1. VECTORS IN THREE DIMENSIONS

dimensions:
$$\left(\begin{array}{l}
v_{1} \\
v_{2} \\
v_{3}
\end{array}\right) \cdot\left(\begin{array}{l}
w_{1} \\
w_{2} \\
w_{3}
\end{array}\right)=v_{1} \cdot w_{1}+v_{2} \cdot w_{2}+v_{3} \cdot w_{3} .$$

Just as we can represent the vector $\binom{x}{y}$ as an arrow from the origin in the Cartesian plane to the point $(x, y)$, we can represent the vector $\left(\begin{array}{l}x \\ y \\ z\end{array}\right)$ as an arrow from the origin to the point $(x, y, z)$ in space. With this in mind, we can extend the concept of the norm of a vector to vectors in three dimensions. We define the norm of $\left(\begin{array}{l}x \\ y \\ z\end{array}\right)$ as the distance between ( $x, y, z$ ) and the origin. We showed on page 178 that the distance between ( $x_{1}, y_{1}, z_{1}$ ) and $\left(x_{2}, y_{2}, z_{2}\right)$ in space is $\sqrt{\left(x_{2}-x_{1}\right)^{2}+\left(y_{2}-y_{1}\right)^{2}+\left(z_{2}-z_{1}\right)^{2}}$. Therefore, the distance from $(x, y, z)$ to the origin is $\sqrt{x^{2}+y^{2}+z^{2}}$. As in two dimensions, we denote the norm of $\mathbf{v}$ as $\|\mathbf{v}\|$, so we have
$$\left\|\left(\begin{array}{l}
x \\
y \\
z
\end{array}\right)\right\|=\sqrt{x^{2}+y^{2}+z^{2}} .$$

Also as in two dimensions, the norm of a vector is sometimes referred to as the vector's length or magnitude.
A vector with magnitude 1 is called a unit vector. The vector $\left(\begin{array}{l}a \\ b \\ c\end{array}\right)$ is also written $a \mathbf{i}+b \mathbf{j}+c \mathbf{k}$, where $\mathbf{i}, \mathbf{j}$, and $\mathbf{k}$ are unit vectors from the origin in the direction of the positive $x$-axis, $y$-axis, and $z$-axis, respectively. Just as with vectors in two dimensions, a nonzero vector in three dimensions can be written as the product of its magnitude and a unit vector that is sometimes referred to as the direction of the vector.

Problems

Problem 11.1: Let $\mathbf{u}=\left(\begin{array}{c}1 \\ 3 \\ -5\end{array}\right), \mathbf{v}=\left(\begin{array}{c}0 \\ -4 \\ 5\end{array}\right)$, and $\mathbf{w}=\left(\begin{array}{l}x \\ 2 \\ y\end{array}\right)$.
(a) Find $\mathbf{u}+\mathbf{v}$.
(b) Find $3 \mathbf{u}-5 \mathbf{v}$.
(c) Find $x$ and $y$ if $2 \mathbf{w}-\mathbf{u}=t \mathbf{v}$ for some constant $t$.

Problem 11.2: Evaluate $\left(\begin{array}{c}2 \\ -3 \\ 4\end{array}\right) \cdot\left(\begin{array}{c}-1 \\ 3 \\ 5\end{array}\right)$ and $(-5 \mathbf{i}+3 \mathbf{j}-2 \mathbf{k}) \cdot(5 \mathbf{i}-4 \mathbf{j}+0 \mathbf{k})$.
Problem 11.3: Show that for any scalar $c$ and any vectors $\mathbf{u}, \mathbf{v}$, and $\mathbf{w}$, we have:
(a) $\mathbf{v} \cdot \mathbf{w}=\mathbf{w} \cdot \mathbf{v}$
(b) $\mathbf{v} \cdot(c \mathbf{w})=c(\mathbf{v} \cdot \mathbf{w})$
(c) $\mathbf{u} \cdot(\mathbf{v}+\mathbf{w})=\mathbf{u} \cdot \mathbf{v}+\mathbf{u} \cdot \mathbf{w}$
(d) $\mathbf{v} \cdot \mathbf{v}=\|\mathbf{v}\|^{2}$

381

---

<!-- Page 382 -->

CHAPTER 11. VECTORS AND MATRICES IN THREE DIMENSIONS, PART 1

Problem 11.4: Show that if $\mathbf{v}$ and $\mathbf{w}$ are nonzero vectors in three dimensions, then $\mathbf{v} \cdot \mathbf{w}=\|\mathbf{v}\|\|\mathbf{w}\| \cos \theta$, where $\theta$ is the angle between $\mathbf{v}$ and $\mathbf{w}$ when these vectors are drawn from the origin in space.

We start with a little practice adding and subtracting vectors in three dimensions.
Problem 11.1: Let $\mathbf{u}=\left(\begin{array}{c}1 \\ 3 \\ -5\end{array}\right), \mathbf{v}=\left(\begin{array}{c}0 \\ -4 \\ 5\end{array}\right)$, and $\mathbf{w}=\left(\begin{array}{l}x \\ 2 \\ y\end{array}\right)$.
(a) Find $\mathbf{u}+\mathbf{v}$.
(b) Find $3 \mathbf{u}-5 \mathbf{v}$.
(c) Find $x$ and $y$ if $2 \mathbf{w}-\mathbf{u}=t \mathbf{v}$ for some constant $t$.

Solution for Problem 11.1:
(a) We have $\left(\begin{array}{c}1 \\ 3 \\ -5\end{array}\right)+\left(\begin{array}{c}0 \\ -4 \\ 5\end{array}\right)=\left(\begin{array}{c}1+0 \\ 3-4 \\ -5+5\end{array}\right)=\left(\begin{array}{c}1 \\ -1 \\ 0\end{array}\right)$.
(b) We have $3\left(\begin{array}{c}1 \\ 3 \\ -5\end{array}\right)-5\left(\begin{array}{c}0 \\ -4 \\ 5\end{array}\right)=\left(\begin{array}{c}3 \\ 9 \\ -15\end{array}\right)-\left(\begin{array}{c}0 \\ -20 \\ 25\end{array}\right)=\left(\begin{array}{c}3 \\ 29 \\ -40\end{array}\right)$.
(c) Since $2\left(\begin{array}{l}x \\ 2 \\ y\end{array}\right)-\left(\begin{array}{c}1 \\ 3 \\ -5\end{array}\right)=\left(\begin{array}{c}2 x-1 \\ 1 \\ 2 y+5\end{array}\right)$ and $t\left(\begin{array}{c}0 \\ -4 \\ 5\end{array}\right)=\left(\begin{array}{c}0 \\ -4 t \\ 5 t\end{array}\right)$, we must have $2 x+1=0,1=-4 t$, and $2 y+5=5 t$. From the first equation, we have $x=-\frac{1}{2}$. From the second equation, we have $t=-\frac{1}{4}$, and substituting this value of $t$ into the last equation gives $y=-\frac{25}{8}$.

Problem 11.2: Evaluate $\left(\begin{array}{c}2 \\ -3 \\ 4\end{array}\right) \cdot\left(\begin{array}{c}-1 \\ 3 \\ 5\end{array}\right)$ and $(-5 \mathbf{i}+3 \mathbf{j}-2 \mathbf{k}) \cdot(5 \mathbf{i}-4 \mathbf{j}+0 \mathbf{k})$.

Solution for Problem 11.2: Applying the definition for the dot product from the introduction, we have
$$\left(\begin{array}{c}
2 \\
-3 \\
4
\end{array}\right) \cdot\left(\begin{array}{c}
-1 \\
3 \\
5
\end{array}\right)=(2)(-1)+(-3)(3)+(4)(5)=-2-9+20=9$$
and
$$(-5 \mathbf{i}+3 \mathbf{j}-2 \mathbf{k}) \cdot(5 \mathbf{i}-4 \mathbf{j}+0 \mathbf{k})=(-5)(5)+(3)(-4)+(-2)(0)=-37 .$$

Problem 11.3: Show that for any scalar $c$ and any vectors $\mathbf{u}, \mathbf{v}$, and $\mathbf{w}$, we have:
(a) $\mathbf{v} \cdot \mathbf{w}=\mathbf{w} \cdot \mathbf{v}$
(b) $\mathbf{v} \cdot(c \mathbf{w})=c(\mathbf{v} \cdot \mathbf{w})$
(c) $\mathbf{u} \cdot(\mathbf{v}+\mathbf{w})=\mathbf{u} \cdot \mathbf{v}+\mathbf{u} \cdot \mathbf{w}$
(d) $\mathbf{v} \cdot \mathbf{v}=\|\mathbf{v}\|^{2}$

382

---

<!-- Page 383 -->

11.1. VECTORS IN THREE DIMENSIONS

Solution for Problem 11.3: In each of the following parts, we let $\mathbf{u}=u_{1} \mathbf{i}+u_{2} \mathbf{j}+u_{3} \mathbf{k}, \mathbf{v}=v_{1} \mathbf{i}+v_{2} \mathbf{j}+v_{3} \mathbf{k}$, and $\mathbf{w}=w_{1} \mathbf{i}+w_{2} \mathbf{j}+w_{3} \mathbf{k}$.
(a) We have $\mathbf{v} \cdot \mathbf{w}=v_{1} w_{1}+v_{2} w_{2}+v_{3} w_{3}=w_{1} v_{1}+w_{2} v_{2}+w_{3} v_{3}=\mathbf{w} \cdot \mathbf{v}$.
(b) We have
$$\mathbf{v} \cdot(c \mathbf{w})=\left(\begin{array}{l}
v_{1} \\
v_{2} \\
v_{3}
\end{array}\right) \cdot\left(\begin{array}{l}
c w_{1} \\
c w_{2} \\
c w_{3}
\end{array}\right)=\left(v_{1}\right)\left(c w_{1}\right)+\left(v_{2}\right)\left(c w_{2}\right)+\left(v_{3}\right)\left(c w_{3}\right)=c\left(v_{1} w_{1}+v_{2} w_{2}+v_{3} w_{3}\right)=c(\mathbf{v} \cdot \mathbf{w}) .$$
(c) We have
$$\begin{aligned}
\mathbf{u} \cdot(\mathbf{v}+\mathbf{w}) & =u_{1}\left(v_{1}+w_{1}\right)+u_{2}\left(v_{2}+w_{2}\right)+u_{3}\left(v_{3}+w_{3}\right) \\
& =\left(u_{1} v_{1}+u_{2} v_{2}+u_{3} v_{3}\right)+\left(u_{1} w_{1}+u_{2} w_{2}+u_{3} w_{3}\right) \\
& =\mathbf{u} \cdot \mathbf{v}+\mathbf{u} \cdot \mathbf{w}
\end{aligned}$$
(d) We have $\mathbf{v} \cdot \mathbf{v}=v_{1}^{2}+v_{2}^{2}+v_{3}^{2}=\|\mathbf{v}\|^{2}$.

So, we see that the basic properties of the dot product that we showed for two dimensions also hold for three dimensions.

Important: For any scalar $\mathcal{c}$ and any vectors $\mathbf{u}, \mathbf{v}$, and $\mathbf{w}$, we have:
(a) $\mathbf{v} \cdot \mathbf{w}=\mathbf{w} \cdot \mathbf{v}$
(b) $\mathbf{v} \cdot(c \mathbf{w})=c(\mathbf{v} \cdot \mathbf{w})$
(c) $\mathbf{u} \cdot(\mathbf{v}+\mathbf{w})=\mathbf{u} \cdot \mathbf{v}+\mathbf{u} \cdot \mathbf{w}$
(d) $\mathbf{v} \cdot \mathbf{v}=\|\mathbf{v}\|^{2}$

Combining properties (a), (b), and (c) above tells us that the dot product of vectors in three dimensions is bilinear, just like the dot product of vectors in two dimensions. By this, we mean that for any vector $\mathbf{v}$, the functions $f(\mathbf{w})=\mathbf{v} \cdot \mathbf{w}$ and $f(\mathbf{w})=\mathbf{w} \cdot \mathbf{v}$ are both linear functions.

We also discovered a nice geometric interpretation of the dot product of vectors in two dimensions. Let's see if this interpretation holds for vectors in three dimensions, as well.

Problem 11.4: Show that if $\mathbf{v}$ and $\mathbf{w}$ are nonzero vectors in three dimensions, then $\mathbf{v} \cdot \mathbf{w}=\|\mathbf{v}\|\|\mathbf{w}\| \cos \theta$, where $\theta$ is the angle between $\mathbf{v}$ and $\mathbf{w}$ when these vectors are drawn from the origin in space.

Solution for Problem 11.4: If we look back to our proof for vectors in two dimensions in Problem 9.9 on page 309, we have a pleasant surprise: the same proof holds in three dimensions!

At right, we have points $V$ and $W$, where $\vec{V}=\mathbf{v}$ and $\vec{W}=\mathbf{w}$, and we let the origin be $O$. We therefore have $O V=\|\mathbf{v}\|, O W=\|\mathbf{w}\|$, and $W V=\|\overrightarrow{W V}\|=\|\mathbf{v}-\mathbf{w}\|$.

The Law of Cosines gives us $W V^{2}=O V^{2}+O W^{2}-2(O V)(O W) \cos \theta$, or
$$\|\mathbf{v}-\mathbf{w}\|^{2}=\|\mathbf{v}\|^{2}+\|\mathbf{w}\|^{2}-2\|\mathbf{v}\|\|\mathbf{w}\| \cos \theta .$$

Since $\|\mathbf{v}\|^{2}=\mathbf{v} \cdot \mathbf{v},\|\mathbf{w}\|^{2}=\mathbf{w} \cdot \mathbf{w}$, and $\|\mathbf{v}-\mathbf{w}\|^{2}=(\mathbf{v}-\mathbf{w}) \cdot(\mathbf{v}-\mathbf{w})$, we can write the Law of
Cosines equation above as
$$(\mathbf{v}-\mathbf{w}) \cdot(\mathbf{v}-\mathbf{w})=\mathbf{v} \cdot \mathbf{v}+\mathbf{w} \cdot \mathbf{w}-2\|\mathbf{v}\|\|\mathbf{w}\| \cos \theta$$

383

---

<!-- Page 384 -->

CHAPTER 11. VECTORS AND MATRICES IN THREE DIMENSIONS, PART 1

Expanding the dot product on the left gives
$$\mathbf{v} \cdot \mathbf{v}-2 \mathbf{v} \cdot \mathbf{w}+\mathbf{w} \cdot \mathbf{w}=\mathbf{v} \cdot \mathbf{v}+\mathbf{w} \cdot \mathbf{w}-2\|\mathbf{v}\|\|\mathbf{w}\| \cos \theta$$
and simplifying this equation gives the familiar
$$\mathbf{v} \cdot \mathbf{w}=\|\mathbf{v}\|\|\mathbf{w}\| \cos \theta .$$

If you look back to our proof for vectors in two dimensions on page 309, you'll see that it looks very similar to our proof above!

As in two dimensions, we can use this relationship to determine the angle between two vectors, and if two vectors have dot product 0 , then we say they are orthogonal. If orthogonal vectors are nonzero, then their geometric representations are perpendicular, since $\mathbf{v} \cdot \mathbf{w}=0$ for nonzero $\mathbf{v}$ and $\mathbf{w}$ if and only if the cosine of the angle between them is 0 .

Excriscs
11.1.1 Let $\mathbf{u}=4 \mathbf{i}+2 \mathbf{j}-\mathbf{k}$ and $\mathbf{v}=-\mathbf{i}+5 \mathbf{j}+2 \mathbf{k}$.
(a) Find $\mathbf{w}$ if $\mathbf{u}-3 \mathbf{w}=2 \mathbf{v}$.
(b) Do there exist nonzero scalars $a$ and $b$ such that $a \mathbf{u}+b \mathbf{v}=\mathbf{0}$ ?
(c) Does there exist a vector $\mathbf{r}$ such that there is no pair of scalars $(x, y)$ for which $x \mathbf{u}+y \mathbf{v}=\mathbf{r}$ ?
11.1.2 For what values of $x$ and $y$ is $\left(\begin{array}{l}1 \\ x \\ y\end{array}\right)$ orthogonal to both $\left(\begin{array}{c}3 \\ -1 \\ 4\end{array}\right)$ and $\left(\begin{array}{c}-4 \\ 1 \\ 2\end{array}\right)$ ?
11.1.3 Find the angle between $\left(\begin{array}{c}3 \\ -4 \\ 2\end{array}\right)$ and $\left(\begin{array}{c}-1 \\ 4 \\ 7\end{array}\right)$ to the nearest degree.
11.1.4 Suppose the point ( $x, y, z$ ) in space has spherical coordinates ( $\rho, \theta, \phi$ ), where $\rho \geq 0$. If $\mathbf{u}=x \mathbf{i}+y \mathbf{j}+z \mathbf{k}$, then express $\phi$ in terms of $\mathbf{u}, \mathbf{i}, \mathbf{j}$, and $\mathbf{k}$.
11.1.5 Let $\mathbf{v}=x \mathbf{i}+y \mathbf{j}+z \mathbf{k}$ and $\mathbf{w}=\mathbf{i}-2 \mathbf{j}+4 \mathbf{k}$.
(a) Describe the graph of the points $(x, y, z)$ such that $\|\mathbf{v}\|=4$.
(b) Describe the graph of the points $(x, y, z)$ such that $\|\mathbf{v}-\mathbf{w}\|=6$.
(c) ★ Describe the graph of the points $(x, y, z)$ such that $2 \mathbf{v} \cdot \mathbf{w}=\|\mathbf{v}\|\|\mathbf{w}\|$
11.2 $3 \times 3$ Matrices

Just as we used a $2 \times 2$ matrix to help represent a system of two linear equations in two variables, we can use a $3 \times 3$ matrix to help represent a system of three linear equations in three variables. Specifically, we can represent

384

---

<!-- Page 385 -->

11.2. $3 \times 3$ MATRICES

the system
$$\begin{array}{l}
a_{11} x+a_{12} y+a_{13} z=b_{1} \\
a_{21} x+a_{22} y+a_{23} z=b_{2} \\
a_{31} x+a_{32} y+a_{33} z=b_{3}
\end{array}$$
as
$$\left(\begin{array}{lll}
a_{11} & a_{12} & a_{13} \\
a_{21} & a_{22} & a_{23} \\
a_{31} & a_{32} & a_{33}
\end{array}\right)\left(\begin{array}{l}
x \\
y \\
z
\end{array}\right)=\left(\begin{array}{l}
b_{1} \\
b_{2} \\
b_{3}
\end{array}\right) .$$

The product of the $3 \times 3$ matrix and the vector on the left is defined as
$$\left(\begin{array}{lll}
a_{11} & a_{12} & a_{13} \\
a_{21} & a_{22} & a_{23} \\
a_{31} & a_{32} & a_{33}
\end{array}\right)\left(\begin{array}{l}
x \\
y \\
z
\end{array}\right)=\left(\begin{array}{l}
a_{11} x+a_{12} y+a_{13} z \\
a_{21} x+a_{22} y+a_{23} z \\
a_{31} x+a_{32} y+a_{33} z
\end{array}\right)$$

Just as a $2 \times 2$ matrix represents a function that maps vectors in two dimensions to vectors in two dimensions, a $3 \times 3$ matrix represents a function that maps vectors in three dimensions to vectors in three dimensions. We say that such a function has domain $\mathbb{R}^{3}$.

Also as with $2 \times 2$ matrices, we typically use a capital letter to denote a $3 \times 3$ matrix, and often use the lowercase of the letter together with subscripts to denote individual entries of the matrix. The first subscript refers to the row of the entry and the second refers to the column. So, for example, $s_{13}$ refers to the entry of matrix $\mathbf{S}$ in the first row of the third column.

Adding two $3 \times 3$ matrices and multiplying a $3 \times 3$ matrix by a scalar work essentially the same way they do for $2 \times 2$ matrices:
$$\begin{aligned}
\left(\begin{array}{lll}
a_{11} & a_{12} & a_{13} \\
a_{21} & a_{22} & a_{23} \\
a_{31} & a_{32} & a_{33}
\end{array}\right)+\left(\begin{array}{lll}
b_{11} & b_{12} & b_{13} \\
b_{21} & b_{22} & b_{23} \\
b_{31} & b_{32} & b_{33}
\end{array}\right) & =\left(\begin{array}{lll}
a_{11}+b_{11} & a_{12}+b_{12} & a_{13}+b_{13} \\
a_{21}+b_{21} & a_{22}+b_{22} & a_{23}+b_{23} \\
a_{31}+b_{31} & a_{32}+b_{32} & a_{33}+b_{33}
\end{array}\right) \\
k\left(\begin{array}{lll}
a_{11} & a_{12} & a_{13} \\
a_{21} & a_{22} & a_{23} \\
a_{31} & a_{32} & a_{33}
\end{array}\right) & =\left(\begin{array}{lll}
k a_{11} & k a_{12} & k a_{13} \\
k a_{21} & k a_{22} & k a_{23} \\
k a_{31} & k a_{32} & k a_{33}
\end{array}\right) .
\end{aligned}$$

Problems

Problem 11.5: Compute the following products:
(a) $\left(\begin{array}{ccc}1 & 3 & -4 \\ -3 & 0 & 5 \\ -6 & 1 & -2\end{array}\right)\left(\begin{array}{l}0 \\ 3 \\ 5\end{array}\right)$
(b) $\left(\begin{array}{ccc}0 & -5 & 2 \\ -1 & 1 & -3 \\ 5 & -2 & -1\end{array}\right)\left(\begin{array}{c}-3 \\ 2 \\ 6\end{array}\right)$

Problem 11.6: Show that $\mathbf{A}(k \mathbf{v})=k(\mathbf{A v})$ and $\mathbf{A}(\mathbf{v}+\mathbf{w})=\mathbf{A v}+\mathbf{A w}$ for any $3 \times 3$ matrix $\mathbf{A}$, any scalar $k$, and any vectors $\mathbf{v}$ and $\mathbf{w}$ in three dimensions.

385

---

<!-- Page 386 -->

CHAPTER 11. VECTORS AND MATRICES IN THREE DIMENSIONS, PART 1

Problem 11.7: In this problem, we find the product of two $3 \times 3$ matrices. Consider the system of equations
$$\begin{array}{r}
3 x+5 y-2 z=p \\
y-3 z=q \\
-2 x+4 y+z=r
\end{array}$$

Suppose we also have $x=3 t-4 u-v, y=-t+v$, and $z=7 t-3 u-v$.
(a) Find matrix $\mathbf{A}$ such that the original system of equations can be expressed as $\mathbf{A}\left(\begin{array}{c}x \\ y \\ z\end{array}\right)=\left(\begin{array}{c}p \\ q \\ r\end{array}\right)$.
(b) Find matrix $\mathbf{B}$ such that $\left(\begin{array}{c}x \\ y \\ z\end{array}\right)=\mathbf{B}\left(\begin{array}{c}t \\ u \\ v\end{array}\right)$.
(c) Suppose we wish to define the product $\mathbf{A B}$ such that $(\mathbf{A B})\left(\begin{array}{c}t \\ u \\ v\end{array}\right)=\mathbf{A}\left(\mathbf{B}\left(\begin{array}{l}t \\ u \\ v\end{array}\right)\right)$ for all $\left(\begin{array}{l}t \\ u \\ v\end{array}\right)$. Find the matrix that equals $\mathbf{A B}$.

Problem 11.8: Find the product
$$\left(\begin{array}{lll}
a_{11} & a_{12} & a_{13} \\
a_{21} & a_{22} & a_{23} \\
a_{31} & a_{32} & a_{33}
\end{array}\right)\left(\begin{array}{lll}
b_{11} & b_{12} & b_{13} \\
b_{21} & b_{22} & b_{23} \\
b_{31} & b_{32} & b_{33}
\end{array}\right) .$$

Problem 11.9: Find the following products:
(a) $\quad\left(\begin{array}{ccc}2 & -3 & 0 \\ -1 & -2 & 5 \\ -2 & -5 & 1\end{array}\right)\left(\begin{array}{ccc}4 & -1 & 2 \\ -1 & 1 & -2 \\ 5 & 0 & -2\end{array}\right)$
(b) $\quad\left(\begin{array}{ccc}3 & -1 & 4 \\ 0 & 1 & 7 \\ 2 & -1 & 3\end{array}\right)\left(\begin{array}{ccc}-1 & 4 & 3 \\ 3 & 5 & -1 \\ 1 & 1 & 5\end{array}\right)$

Problem 11.10: If $\mathbf{A}$ and $\mathbf{B}$ are $3 \times 3$ matrices, must we have $\mathbf{A B}=\mathbf{B A}$ ?
Problem 11.11: If $\mathbf{A}$ and $\mathbf{B}$ are $3 \times 3$ matrices such that $\mathbf{A i}=\mathbf{B i}, \mathbf{A j}=\mathbf{B j}$, and $\mathbf{A k}=\mathbf{B k}$, then must we have $\mathrm{A}=\mathrm{B}$ ?

Problem 11.12:
(a) Find a $3 \times 3$ matrix $\mathbf{I}$ such that $\mathbf{I} \mathbf{A}=\mathbf{A}$ for any $3 \times 3$ matrix $\mathbf{A}$.
(b) Do we also have $\mathbf{A I}=\mathbf{A}$ for this matrix $\mathbf{I}$ ?
(c) Is the matrix you found in part (a) the only matrix $\mathbf{I}$ such that $\mathbf{I A}=\mathbf{A}$ for all $\mathbf{A}$ ? Is it the only matrix such that $\mathbf{A I}=\mathbf{A}$ for all $\mathbf{A}$ ?

Problem 11.13:
(a) Find the matrix $\mathbf{P}$ such that for every $\mathbf{A}$, the product $\mathbf{P A}$ results in a matrix whose third row is the same as that of $\mathbf{A}$, but the first two rows are swapped. (That is, the second row of the product is the first row of A and vice-versa.)
(b) Find a matrix $\mathbf{T}$ such that $\mathbf{T} \neq \mathbf{I}$ and $\mathbf{T}^{3}=\mathbf{I}$.

386

---

<!-- Page 387 -->

11.2. $3 \times 3$ MATRICES

Problem 11.5: Compute the following products:
(a) $\left(\begin{array}{ccc}1 & 3 & -4 \\ -3 & 0 & 5 \\ -6 & 1 & -2\end{array}\right)\left(\begin{array}{l}0 \\ 3 \\ 5\end{array}\right)$
(b) $\left(\begin{array}{ccc}0 & -5 & 2 \\ -1 & 1 & -3 \\ 5 & -2 & -1\end{array}\right)\left(\begin{array}{c}-3 \\ 2 \\ 6\end{array}\right)$

Solution for Problem 11.5:
(a) Applying the definition of multiplication of a vector by a matrix, we have
$$\left(\begin{array}{ccc}
1 & 3 & -4 \\
-3 & 0 & 5 \\
-6 & 1 & -2
\end{array}\right)\left(\begin{array}{l}
0 \\
3 \\
5
\end{array}\right)=\left(\begin{array}{c}
(1)(0)+(3)(3)+(-4)(5) \\
(-3)(0)+(0)(3)+(5)(5) \\
(-6)(0)+(1)(3)+(-2)(5)
\end{array}\right)=\left(\begin{array}{c}
-11 \\
25 \\
-7
\end{array}\right) .$$
(b) We have
$$\left(\begin{array}{ccc}
0 & -5 & 2 \\
-1 & 1 & -3 \\
5 & -2 & -1
\end{array}\right)\left(\begin{array}{c}
-3 \\
2 \\
6
\end{array}\right)=\left(\begin{array}{c}
(0)(-3)+(-5)(2)+(2)(6) \\
(-1)(-3)+(1)(2)+(-3)(6) \\
(5)(-3)+(-2)(2)+(-1)(6)
\end{array}\right)=\left(\begin{array}{c}
2 \\
-13 \\
-25
\end{array}\right) .$$

Problem 11.6: Show that $\mathbf{A}(k \mathbf{v})=k(\mathbf{A v})$ and $\mathbf{A}(\mathbf{v}+\mathbf{w})=\mathbf{A v}+\mathbf{A w}$ for any $3 \times 3$ matrix $\mathbf{A}$, any scalar $k$, and any vectors $\mathbf{v}$ and $\mathbf{w}$ in three dimensions.

Solution for Problem 11.6: We have
$$\mathbf{A}(k \mathbf{v})=\left(\begin{array}{lll}
a_{11} & a_{12} & a_{13} \\
a_{21} & a_{22} & a_{23} \\
a_{31} & a_{32} & a_{33}
\end{array}\right)\left(\begin{array}{l}
k v_{1} \\
k v_{2} \\
k v_{3}
\end{array}\right)=\left(\begin{array}{l}
a_{11} k v_{1}+a_{12} k v_{2}+a_{13} k v_{3} \\
a_{21} k v_{1}+a_{22} k v_{2}+a_{23} k v_{3} \\
a_{31} k v_{1}+a_{32} k v_{2}+a_{33} k v_{3}
\end{array}\right)=k\left(\begin{array}{l}
a_{11} v_{1}+a_{12} v_{2}+a_{13} v_{3} \\
a_{21} v_{1}+a_{22} v_{2}+a_{23} v_{3} \\
a_{31} v_{1}+a_{32} v_{2}+a_{33} v_{3}
\end{array}\right)=k(\mathbf{A v})$$
and
$$\begin{aligned}
\mathbf{A}(\mathbf{v}+\mathbf{w})=\left(\begin{array}{lll}
a_{11} & a_{12} & a_{13} \\
a_{21} & a_{22} & a_{23} \\
a_{31} & a_{32} & a_{33}
\end{array}\right)\left(\begin{array}{l}
v_{1}+w_{1} \\
v_{2}+w_{2} \\
v_{3}+w_{3}
\end{array}\right) & =\left(\begin{array}{l}
a_{11}\left(v_{1}+w_{1}\right)+a_{12}\left(v_{2}+w_{2}\right)+a_{13}\left(v_{3}+w_{3}\right) \\
a_{21}\left(v_{1}+w_{1}\right)+a_{22}\left(v_{2}+w_{2}\right)+a_{23}\left(v_{3}+w_{3}\right) \\
a_{31}\left(v_{1}+w_{1}\right)+a_{32}\left(v_{2}+w_{2}\right)+a_{33}\left(v_{3}+w_{3}\right)
\end{array}\right) \\
& =\left(\begin{array}{l}
a_{11} v_{1}+a_{12} v_{2}+a_{13} v_{3} \\
a_{21} v_{1}+a_{22} v_{2}+a_{23} v_{3} \\
a_{31} v_{1}+a_{32} v_{2}+a_{33} v_{3}
\end{array}\right)+\left(\begin{array}{l}
a_{11} w_{1}+a_{12} w_{2}+a_{13} w_{3} \\
a_{21} w_{1}+a_{22} w_{2}+a_{23} w_{3} \\
a_{31} w_{1}+a_{32} w_{2}+a_{33} w_{3}
\end{array}\right) \\
& =\mathbf{A v}+\mathbf{A} \mathbf{w} .
\end{aligned}$$

\begin{tabular}{|cl|}
\hline Important: & \begin{tabular}{l} 
For any $3 \times 3$ matrix $\mathbf{A}$, any scalar $k$, and any vectors $\mathbf{v}$ and $\mathbf{w}$ in three dimensions, \\
we have $\mathbf{A}(k \mathbf{v})=k \mathbf{A v}$ and $\mathbf{A}(\mathbf{v}+\mathbf{w})=\mathbf{A v}+\mathbf{A w}$
\end{tabular} \\
\hline$\$ &
\end{tabular}

So, we see that the function that a $3 \times 3$ matrix represents is a linear function.

387

---

<!-- Page 388 -->

CHAPTER 11. VECTORS AND MATRICES IN THREE DIMENSIONS, PART 1

Problem 11.7: In this problem, we find the product of two $3 \times 3$ matrices. Consider the system of equations
$$\begin{array}{r}
3 x+5 y-2 z=p \\
y-3 z=q \\
-2 x+4 y+z=r
\end{array}$$

Suppose we also have $x=3 t-4 u-v, y=-t+v$, and $z=7 t-3 u-v$.
(a) Find matrix $\mathbf{A}$ such that the original system of equations can be expressed as $\mathbf{A}\left(\begin{array}{c}x \\ y \\ z\end{array}\right)=\left(\begin{array}{c}p \\ q \\ r\end{array}\right)$.
(b) Find matrix $\mathbf{B}$ such that $\left(\begin{array}{l}x \\ y \\ z\end{array}\right)=\mathbf{B}\left(\begin{array}{l}t \\ u \\ v\end{array}\right)$.
(c) Suppose we wish to define the product $\mathbf{A B}$ such that $(\mathbf{A B})\left(\begin{array}{c}t \\ u \\ v\end{array}\right)=\mathbf{A}\left(\mathbf{B}\left(\begin{array}{c}t \\ u \\ v\end{array}\right)\right)$ for all $\left(\begin{array}{c}t \\ u \\ v\end{array}\right)$. Find the matrix that equals $\mathbf{A B}$.

Solution for Problem 11.7:
(a) Following the definition of a $3 \times 3$ matrix in the introduction, we can write the initial system of equations as
$$\left(\begin{array}{ccc}
3 & 5 & -2 \\
0 & 1 & -3 \\
-2 & 4 & 1
\end{array}\right)\left(\begin{array}{l}
x \\
y \\
z
\end{array}\right)=\left(\begin{array}{l}
p \\
q \\
r
\end{array}\right) .$$
(b) Again using our definition of a $3 \times 3$ matrix, we can express the system $x=3 t-4 u-v, y=-t+v, z=7 t-3 u-v$ as
$$\left(\begin{array}{l}
x \\
y \\
z
\end{array}\right)=\left(\begin{array}{ccc}
3 & -4 & -1 \\
-1 & 0 & 1 \\
7 & -3 & -1
\end{array}\right)\left(\begin{array}{l}
t \\
u \\
v
\end{array}\right) .$$
(c) We'll take two different approaches to find $\mathbf{A B}$.

Method 1. If we substitute the expression we found for $\left(\begin{array}{l}x \\ y \\ z\end{array}\right)$ in part (b) into the equation we found in part (a), we have
$$\left(\begin{array}{ccc}
3 & 5 & -2 \\
0 & 1 & -3 \\
-2 & 4 & 1
\end{array}\right)\left(\begin{array}{ccc}
3 & -4 & -1 \\
-1 & 0 & 1 \\
7 & -3 & -1
\end{array}\right)\left(\begin{array}{l}
t \\
u \\
v
\end{array}\right)=\left(\begin{array}{l}
p \\
q \\
r
\end{array}\right) .$$

Equivalently, we can substitute the given equations $x=3 t-4 u-v, y=-t+v, z=7 t-3 u-v$ into the original system of equations to get
$$\begin{array}{r}
3(3 t-4 u-v)+5(-t+v)-2(7 t-3 u-v)=p \\
(-t+v)-3(7 t-3 u-v)=q \\
-2(3 t-4 u-v)+4(-t+v)+(7 t-3 u-v)=r
\end{array}$$

Simplifying these equations gives
$$\begin{array}{r}
-10 t-6 u+4 v=p, \\
-22 t+9 u+4 v=q, \\
-3 t+5 u+5 v=r,
\end{array}$$

388

---

<!-- Page 389 -->

11.2. $3 \times 3$ MATRICES

which we can write as
$$\left(\begin{array}{ccc}
-10 & -6 & 4 \\
-22 & 9 & 4 \\
-3 & 5 & 5
\end{array}\right)\left(\begin{array}{l}
t \\
u \\
v
\end{array}\right)=\left(\begin{array}{c}
p \\
q \\
r
\end{array}\right)$$

Comparing this to Equation (11.1), we have
$$\left(\begin{array}{ccc}
3 & 5 & -2 \\
0 & 1 & -3 \\
-2 & 4 & 1
\end{array}\right)\left(\begin{array}{ccc}
3 & -4 & -1 \\
-1 & 0 & 1 \\
7 & -3 & -1
\end{array}\right)\left(\begin{array}{l}
t \\
u \\
v
\end{array}\right)=\left(\begin{array}{ccc}
-10 & -6 & 4 \\
-22 & 9 & 4 \\
-3 & 5 & 5
\end{array}\right)\left(\begin{array}{l}
t \\
u \\
v
\end{array}\right)$$
from which we conclude that
$$\left(\begin{array}{ccc}
3 & 5 & -2 \\
0 & 1 & -3 \\
-2 & 4 & 1
\end{array}\right)\left(\begin{array}{ccc}
3 & -4 & -1 \\
-1 & 0 & 1 \\
7 & -3 & -1
\end{array}\right)=\left(\begin{array}{ccc}
-10 & -6 & 4 \\
-22 & 9 & 4 \\
-3 & 5 & 5
\end{array}\right) .$$

Method 2. We use the definition of the product of a matrix and a vector to find $\mathbf{A B}$. Since $\mathbf{B}\left(\begin{array}{l}t \\ u \\ v\end{array}\right)=\left(\begin{array}{l}x \\ y \\ z\end{array}\right)$, we have
$$(\mathbf{A B})\left(\begin{array}{l}
t \\
u \\
v
\end{array}\right)=\mathbf{A}\left(\mathbf{B}\left(\begin{array}{l}
t \\
u \\
v
\end{array}\right)\right)=\mathbf{A}\left(\begin{array}{l}
x \\
y \\
z
\end{array}\right) .$$

In order to find the matrix that equals $\mathbf{A B}$, we must express $\mathbf{A}\left(\begin{array}{l}x \\ y \\ z\end{array}\right)$ as a single matrix times $\left(\begin{array}{l}t \\ u \\ v\end{array}\right)$. We know how to multiply a vector by a matrix, so we express $\left(\begin{array}{l}x \\ y \\ z\end{array}\right)$ in terms of vectors. From the system $x=3 t-4 u-v, y=-t+v, z=7 t-3 u-v$, we have:
$$\left(\begin{array}{l}
x \\
y \\
z
\end{array}\right)=\left(\begin{array}{c}
3 \\
-1 \\
7
\end{array}\right) t+\left(\begin{array}{c}
-4 \\
0 \\
-3
\end{array}\right) u+\left(\begin{array}{c}
-1 \\
1 \\
-1
\end{array}\right) v$$

Substituting this into $\mathbf{A}\left(\begin{array}{l}x \\ y \\ z\end{array}\right)$ gives
$$\begin{aligned}
\left(\begin{array}{ccc}
3 & 5 & -2 \\
0 & 1 & -3 \\
-2 & 4 & 1
\end{array}\right)\left(\begin{array}{l}
x \\
y \\
z
\end{array}\right) & =\left(\begin{array}{ccc}
3 & 5 & -2 \\
0 & 1 & -3 \\
-2 & 4 & 1
\end{array}\right)\left(\left(\begin{array}{c}
3 \\
-1 \\
7
\end{array}\right) t+\left(\begin{array}{c}
-4 \\
0 \\
-3
\end{array}\right) u+\left(\begin{array}{c}
-1 \\
1 \\
-1
\end{array}\right) v\right) \\
& =\left(\begin{array}{ccc}
3 & 5 & -2 \\
0 & 1 & -3 \\
-2 & 4 & 1
\end{array}\right)\left(\begin{array}{c}
3 \\
-1 \\
7
\end{array}\right) t+\left(\begin{array}{ccc}
3 & 5 & -2 \\
0 & 1 & -3 \\
-2 & 4 & 1
\end{array}\right)\left(\begin{array}{c}
-4 \\
0 \\
-3
\end{array}\right) u+\left(\begin{array}{ccc}
3 & 5 & -2 \\
0 & 1 & -3 \\
-2 & 4 & 1
\end{array}\right)\left(\begin{array}{c}
-1 \\
1 \\
-1
\end{array}\right) v \\
& =\left(\begin{array}{c}
-10 \\
-22 \\
-3
\end{array}\right) t+\left(\begin{array}{c}
-6 \\
9 \\
5
\end{array}\right) u+\left(\begin{array}{c}
4 \\
4 \\
5
\end{array}\right) v \\
& =\left(\begin{array}{c}
-10 t-6 u+4 v \\
-22 t+9 u+4 v \\
-3 t+5 u+5 v
\end{array}\right) \\
& =\left(\begin{array}{ccc}
-10 & -6 & 4 \\
-22 & 9 & 4 \\
-3 & 5 & 5
\end{array}\right)\left(\begin{array}{c}
t \\
u \\
v
\end{array}\right) .
\end{aligned}$$

389

---

<!-- Page 390 -->

CHAPTER 11. VECTORS AND MATRICES IN THREE DIMENSIONS, PART 1

Therefore, we have
$$(\mathbf{A B})\left(\begin{array}{l}
t \\
u \\
v
\end{array}\right)=\mathbf{A}\left(\begin{array}{l}
x \\
y \\
z
\end{array}\right)=\left(\begin{array}{ccc}
-10 & -6 & 4 \\
-22 & 9 & 4 \\
-3 & 5 & 5
\end{array}\right)\left(\begin{array}{l}
t \\
u \\
v
\end{array}\right),$$
from which we conclude that $\mathbf{A B}=\left(\begin{array}{ccc}3 & 5 & -2 \\ 0 & 1 & -3 \\ -2 & 4 & 1\end{array}\right)\left(\begin{array}{ccc}3 & -4 & -1 \\ -1 & 0 & 1 \\ 7 & -3 & -1\end{array}\right)=\left(\begin{array}{ccc}-10 & -6 & 4 \\ -22 & 9 & 4 \\ -3 & 5 & 5\end{array}\right)$.

We're now ready to find a method to multiply any two $3 \times 3$ matrices.
Problem 11.8: Find the product
$$\left(\begin{array}{lll}
a_{11} & a_{12} & a_{13} \\
a_{21} & a_{22} & a_{23} \\
a_{31} & a_{32} & a_{33}
\end{array}\right)\left(\begin{array}{lll}
b_{11} & b_{12} & b_{13} \\
b_{21} & b_{22} & b_{23} \\
b_{31} & b_{32} & b_{33}
\end{array}\right) .$$

Solution for Problem 11.8: We use part (c) of the previous problem as a guide. Let the matrices be $\mathbf{A}$ and $\mathbf{B}$; we seek a matrix that equals the product $\mathbf{A B}$, where
$$(\mathbf{A B})\left(\begin{array}{l}
t \\
u \\
v
\end{array}\right)=\mathbf{A}\left(\mathbf{B}\left(\begin{array}{l}
t \\
u \\
v
\end{array}\right)\right)$$
for all $\left(\begin{array}{l}t \\ u \\ v\end{array}\right)$. We have
$$\mathbf{B}\left(\begin{array}{l}
t \\
u \\
v
\end{array}\right)=\left(\begin{array}{lll}
b_{11} & b_{12} & b_{13} \\
b_{21} & b_{22} & b_{23} \\
b_{31} & b_{32} & b_{33}
\end{array}\right)\left(\begin{array}{l}
t \\
u \\
v
\end{array}\right)=\left(\begin{array}{l}
b_{11} t+b_{12} u+b_{13} v \\
b_{21} t+b_{22} u+b_{23} v \\
b_{31} t+b_{32} u+b_{33} v
\end{array}\right)=\left(\begin{array}{l}
b_{11} \\
b_{21} \\
b_{31}
\end{array}\right) t+\left(\begin{array}{l}
b_{12} \\
b_{22} \\
b_{32}
\end{array}\right) u+\left(\begin{array}{l}
b_{13} \\
b_{23} \\
b_{33}
\end{array}\right) v .$$

Substituting this into the right side of Equation (11.3) gives
$$\begin{aligned}
\mathbf{A}\left(\mathbf{B}\left(\begin{array}{l}
t \\
u \\
v
\end{array}\right)\right) & =\left(\begin{array}{lll}
a_{11} & a_{12} & a_{13} \\
a_{21} & a_{22} & a_{23} \\
a_{31} & a_{32} & a_{33}
\end{array}\right)\left(\left(\begin{array}{l}
b_{11} \\
b_{21} \\
b_{31}
\end{array}\right) t+\left(\begin{array}{l}
b_{12} \\
b_{22} \\
b_{32}
\end{array}\right) u+\left(\begin{array}{l}
b_{13} \\
b_{23} \\
b_{33}
\end{array}\right) v\right) \\
& =\left(\begin{array}{lll}
a_{11} & a_{12} & a_{13} \\
a_{21} & a_{22} & a_{23} \\
a_{31} & a_{32} & a_{33}
\end{array}\right)\left(\begin{array}{l}
b_{11} \\
b_{21} \\
b_{31}
\end{array}\right) t+\left(\begin{array}{lll}
a_{11} & a_{12} & a_{13} \\
a_{21} & a_{22} & a_{23} \\
a_{31} & a_{32} & a_{33}
\end{array}\right)\left(\begin{array}{l}
b_{12} \\
b_{22} \\
b_{32}
\end{array}\right) u+\left(\begin{array}{lll}
a_{11} & a_{12} & a_{13} \\
a_{21} & a_{22} & a_{23} \\
a_{31} & a_{32} & a_{33}
\end{array}\right)\left(\begin{array}{l}
b_{13} \\
b_{23} \\
b_{33}
\end{array}\right) v \\
& =\left(\begin{array}{ll}
a_{11} b_{11}+a_{12} b_{21}+a_{13} b_{31} \\
a_{21} b_{11}+a_{22} b_{21}+a_{23} b_{31} \\
a_{31} b_{11}+a_{32} b_{21}+a_{33} b_{31}
\end{array}\right) t+\left(\begin{array}{ll}
a_{11} b_{12}+a_{12} b_{22}+a_{13} b_{32} \\
a_{21} b_{12}+a_{22} b_{22}+a_{23} b_{32} \\
a_{31} b_{12}+a_{32} b_{22}+a_{33} b_{32}
\end{array}\right) u+\left(\begin{array}{l}
a_{11} b_{13}+a_{12} b_{23}+a_{13} b_{33} \\
a_{21} b_{13}+a_{22} b_{23}+a_{23} b_{33} \\
a_{31} b_{13}+a_{32} b_{23}+a_{33} b_{33}
\end{array}\right) v \\
& =\left(\begin{array}{lll}
a_{11} b_{11}+a_{12} b_{21}+a_{13} b_{31} & a_{11} b_{12}+a_{12} b_{22}+a_{13} b_{32} & a_{11} b_{13}+a_{12} b_{23}+a_{13} b_{33} \\
a_{21} b_{11}+a_{22} b_{21}+a_{23} b_{31} & a_{21} b_{12}+a_{22} b_{22}+a_{23} b_{32} & a_{21} b_{13}+a_{22} b_{23}+a_{23} b_{33} \\
a_{31} b_{11}+a_{32} b_{21}+a_{33} b_{31} & a_{31} b_{12}+a_{32} b_{22}+a_{33} b_{32} & a_{31} b_{13}+a_{32} b_{23}+a_{33} b_{33}
\end{array}\right)\left(\begin{array}{l}
t \\
u \\
v
\end{array}\right)
\end{aligned}$$

Comparing this to Equation (11.3), we have the desired definition of the multiplication of two $3 \times 3$ matrices:
$$\left(\begin{array}{lll}
a_{11} & a_{12} & a_{13} \\
a_{21} & a_{22} & a_{23} \\
a_{31} & a_{32} & a_{33}
\end{array}\right)\left(\begin{array}{lll}
b_{11} & b_{12} & b_{13} \\
b_{21} & b_{22} & b_{23} \\
b_{31} & b_{32} & b_{33}
\end{array}\right)=\left(\begin{array}{lll}
a_{11} b_{11}+a_{12} b_{21}+a_{13} b_{31} & a_{11} b_{12}+a_{12} b_{22}+a_{13} b_{32} & a_{11} b_{13}+a_{12} b_{23}+a_{13} b_{33} \\
a_{21} b_{11}+a_{22} b_{21}+a_{23} b_{31} & a_{21} b_{12}+a_{22} b_{22}+a_{23} b_{32} & a_{21} b_{13}+a_{22} b_{23}+a_{23} b_{33} \\
a_{31} b_{11}+a_{32} b_{21}+a_{33} b_{31} & a_{31} b_{12}+a_{32} b_{22}+a_{33} b_{32} & a_{31} b_{13}+a_{32} b_{23}+a_{33} b_{33}
\end{array}\right) .$$

390

---

<!-- Page 391 -->

11.2. $3 \times 3$ MATRICES

Just as with the product of two $2 \times 2$ matrices, this definition is much easier to remember than it looks. We can view each row of a matrix as a vector, and each column of a matrix as a vector. The entry in row $i$ and column $j$ of the product $\mathbf{A B}$ is the dot product of the $i^{\text {th }}$ row of $\mathbf{A}$ and the $j^{\text {th }}$ column of $\mathbf{B}$. For example, the entry in row 2 and column 3 of $\mathbf{A B}$ is
$$\left(\begin{array}{lll}
a_{21} & a_{22} & a_{23}
\end{array}\right)\left(\begin{array}{l}
b_{13} \\
b_{23} \\
b_{33}
\end{array}\right)=a_{21} b_{13}+a_{22} b_{23}+a_{23} b_{33}$$

If we let the rows of $\mathbf{A}$ be the vectors $\mathbf{a}_{1}, \mathbf{a}_{2}$, and $\mathbf{a}_{3}$, and the columns of $\mathbf{B}$ be the vectors $\mathbf{b}_{1}, \mathbf{b}_{2}$, and $\mathbf{b}_{3}$, we can therefore express the product $\mathbf{A B}$ as follows:
$$\mathbf{A B}=\left(\begin{array}{c}
-\mathbf{a}_{1}- \\
-\mathbf{a}_{2}- \\
-\mathbf{a}_{3}-
\end{array}\right)\left(\begin{array}{ccc}
\mid & \mid & \mid \\
\mathbf{b}_{1} & \mathbf{b}_{2} & \mathbf{b}_{3} \\
\mid & \mid & \mid
\end{array}\right)=\left(\begin{array}{lll}
\mathbf{a}_{1} \cdot \mathbf{b}_{1} & \mathbf{a}_{1} \cdot \mathbf{b}_{2} & \mathbf{a}_{1} \cdot \mathbf{b}_{3} \\
\mathbf{a}_{2} \cdot \mathbf{b}_{1} & \mathbf{a}_{2} \cdot \mathbf{b}_{2} & \mathbf{a}_{2} \cdot \mathbf{b}_{3} \\
\mathbf{a}_{3} \cdot \mathbf{b}_{1} & \mathbf{a}_{3} \cdot \mathbf{b}_{2} & \mathbf{a}_{3} \cdot \mathbf{b}_{3}
\end{array}\right) .$$

We can also remember the entry in row $i$ and column $j$ of $\mathbf{A B}$ as the sum $a_{i 1} b_{1 j}+a_{i 2} b_{2 j}+a_{i 3} b_{3 j}$. That is, this entry equals the sum of the three terms of the form $a_{i k} b_{k j}$, for $k=1,2$, and 3 .

Finally, we can also remember this matrix product with the same method we used to find it. Each column of $\mathbf{A B}$ equals $\mathbf{A}$ times the corresponding column of $\mathbf{B}$ :
$$\mathbf{A B}=\mathbf{A}\left(\begin{array}{ccc}
\mid & \mid & \mid \\
\mathbf{b}_{1} & \mathbf{b}_{2} & \mathbf{b}_{3} \\
\mid & \mid & \mid
\end{array}\right)=\left(\begin{array}{ccc}
\mid & \mid & \mid \\
\mathbf{A} \mathbf{b}_{1} & \mathbf{A} \mathbf{b}_{2} & \mathbf{A} \mathbf{b}_{3} \\
\mid & \mid & \mid
\end{array}\right) .$$

Problem 11.9: Find the following products:
(a)
$$\left(\begin{array}{ccc}
2 & -3 & 0 \\
-1 & -2 & 5 \\
-2 & -5 & 1
\end{array}\right)\left(\begin{array}{ccc}
4 & -1 & 2 \\
-1 & 1 & -2 \\
5 & 0 & -2
\end{array}\right)$$
(b) $\quad\left(\begin{array}{ccc}3 & -1 & 4 \\ 0 & 1 & 7 \\ 2 & -1 & 3\end{array}\right)\left(\begin{array}{ccc}-1 & 4 & 3 \\ 3 & 5 & -1 \\ 1 & 1 & 5\end{array}\right)$

Solution for Problem 11.9: We apply the rule for matrix multiplication we just learned to get the products below.
(a) $\quad\left(\begin{array}{ccc}(2)(4)+(-3)(-1)+(0)(5) & (2)(-1)+(-3)(1)+(0)(0) & (2)(2)+(-3)(-2)+(0)(-2) \\ (-1)(4)+(-2)(-1)+(5)(5) & (-1)(-1)+(-2)(1)+(5)(0) & (-1)(2)+(-2)(-2)+(5)(-2) \\ (-2)(4)+(-5)(-1)+(1)(5) & (-2)(-1)+(-5)(1)+(1)(0) & (-2)(2)+(-5)(-2)+(1)(-2)\end{array}\right)=\left(\begin{array}{ccc}11 & -5 & 10 \\ 23 & -1 & -8 \\ 2 & -3 & 4\end{array}\right)$.
(b) $\quad\left(\begin{array}{ccc}(3)(-1)+(-1)(3)+(4)(1) & (3)(4)+(-1)(5)+(4)(1) & (3)(3)+(-1)(-1)+(4)(5) \\ (0)(-1)+(1)(3)+(7)(1) & (0)(4)+(1)(5)+(7)(1) & (0)(3)+(1)(-1)+(7)(5) \\ (2)(-1)+(-1)(3)+(3)(1) & (2)(4)+(-1)(5)+(3)(1) & (2)(3)+(-1)(-1)+(3)(5)\end{array}\right)=\left(\begin{array}{ccc}-2 & 11 & 30 \\ 10 & 12 & 34 \\ -2 & 6 & 22\end{array}\right)$

Problem 11.10: If $\mathbf{A}$ and $\mathbf{B}$ are $3 \times 3$ matrices, must we have $\mathbf{A B}=\mathbf{B A}$ ?

Solution for Problem 11.10: We test if $\mathbf{A B}$ and $\mathbf{B A}$ must be equal by reversing the order of the matrices in the first product we computed in the previous problem. So, we will compare the product
$$\left(\begin{array}{ccc}
4 & -1 & 2 \\
-1 & 1 & -2 \\
5 & 0 & -2
\end{array}\right)\left(\begin{array}{ccc}
2 & -3 & 0 \\
-1 & -2 & 5 \\
-2 & -5 & 1
\end{array}\right)$$
to the product we found in part (a) of Problem 11.9. Applying the definition of matrix multiplication, we find that

391

---

<!-- Page 392 -->

CHAPTER 11. VECTORS AND MATRICES IN THREE DIMENSIONS, PART 1

this product equals
$$\left(\begin{array}{ccc}
(4)(2)+(-1)(-1)+(2)(-2) & (4)(-3)+(-1)(-2)+(2)(-5) & (4)(0)+(-1)(5)+(2)(1) \\
(-1)(2)+(1)(-1)+(-2)(-2) & (-1)(-3)+(1)(-2)+(-2)(-5) & (-1)(0)+(1)(5)+(-2)(1) \\
(5)(2)+(0)(-1)+(-2)(-2) & (5)(-3)+(0)(-2)+(-2)(-5) & (5)(0)+(0)(5)+(-2)(1)
\end{array}\right)=\left(\begin{array}{ccc}
5 & -20 & -3 \\
1 & 11 & 3 \\
14 & -5 & -2
\end{array}\right) .$$

This does not match the result we found in part (a) of Problem 11.9, so we conclude that $\mathbf{A B}$ and $\mathbf{B A}$ are not necessarily equal.

WARNING!!
Matrix multiplication is not commutative. That is, if $\mathbf{A}$ and $\mathbf{B}$ are matrices, then the products $\mathbf{A B}$ and $\mathbf{B A}$ are not necessarily equal.

While $3 \times 3$ matrix multiplication is not commutative, it is associative and distributive.

Important:

For any $3 \times 3$ matrices $\mathbf{A}, \mathbf{B}$, and $\mathbf{C}$, we have
$$\begin{aligned}
(\mathbf{A B}) \mathbf{C} & =\mathbf{A}(\mathbf{B C}), \\
\mathbf{A}(\mathbf{B}+\mathbf{C}) & =\mathbf{A B}+\mathbf{A C}, \\
(\mathbf{A}+\mathbf{B}) \mathbf{C} & =\mathbf{A C}+\mathbf{B C} .
\end{aligned}$$

Because matrix multiplication is associative, we can write a product such as $\mathbf{A}(\mathbf{B C})$ as simply $\mathbf{A B C}$.
The algebraic proofs of these properties are cumbersome and not terribly illuminating, so we won't include them here.

Problem 11.11: If $\mathbf{A}$ and $\mathbf{B}$ are $3 \times 3$ matrices such that $\mathbf{A i}=\mathbf{B i}, \mathbf{A j}=\mathbf{B j}$, and $\mathbf{A k}=\mathbf{B k}$, then must $\mathbf{A}=\mathbf{B}$ ?

Solution for Problem 11.11: We have
$$\left(\begin{array}{lll}
a_{11} & a_{12} & a_{13} \\
a_{21} & a_{22} & a_{23} \\
a_{31} & a_{32} & a_{33}
\end{array}\right)\left(\begin{array}{l}
1 \\
0 \\
0
\end{array}\right)=\left(\begin{array}{l}
a_{11} \\
a_{21} \\
a_{31}
\end{array}\right) .$$

Therefore, $\mathbf{A i}$ equals the first column of $\mathbf{A}$. The equation $\mathbf{A i}=\mathbf{B i}$ then tells us that the first column of $\mathbf{A}$ is the same as the first column of $\mathbf{B}$. Similarly, $\mathbf{A j}$ equals the second column of $\mathbf{A}$ and $\mathbf{A k}$ equals the third column of $\mathbf{A}$, so $\mathbf{A j}=\mathbf{B j}$ and $\mathbf{A k}=\mathbf{B k}$ together tell us that the last two columns of $\mathbf{A}$ match the last two columns of $\mathbf{B}$. Since each column of $\mathbf{A}$ matches the corresponding column of $\mathbf{B}$, we have $\mathbf{A}=\mathbf{B}$.

Our work in Problem 11.11 gives us another way to think about matrices. The first column of a matrix $\mathbf{A}$ tells us what $\mathbf{A i}$ is, the second column tells us what $\mathbf{A j}$ is, and the third column tells us what $\mathbf{A k}$ is. Let's put this observation to work.

Problem 11.12:
(a) Find a $3 \times 3$ matrix $\mathbf{I}$ such that $\mathbf{I A}=\mathbf{A}$ for any $3 \times 3$ matrix $\mathbf{A}$.
(b) Do we also have $\mathbf{A I}=\mathbf{A}$ for this matrix $\mathbf{I}$ ?
(c) Is the matrix you found in part (a) the only matrix $\mathbf{I}$ such that $\mathbf{I A}=\mathbf{A}$ for all $\mathbf{A}$ ? Is it the only matrix such that $\mathbf{A I}=\mathbf{A}$ for all $\mathbf{A}$ ?

392

---

<!-- Page 393 -->

11.2. $3 \times 3$ MATRICES

Solution for Problem 11.12:
(a) The first column of IA equals I times the first column of A. Since IA $=\mathbf{A}$, the product of $\mathbf{I}$ and the first column of $\mathbf{A}$ must therefore be the first column of $\mathbf{A}$. That is, we must have $\mathbf{I v}=\mathbf{v}$ for any vector $\mathbf{v}$. Now, we can find $\mathbf{I}$ by letting $\mathbf{v}$ be each of $\mathbf{i}$, $\mathbf{j}$, and $\mathbf{k}$. Since $\mathbf{I} \boldsymbol{=} \mathbf{i}$, the first column of $\mathbf{I}$ is $\mathbf{i}$. Similarly, since $\mathbf{I} \mathbf{j}=\mathbf{j}$ and $\mathbf{I} \mathbf{k}=\mathbf{k}$, the second and third columns of $\mathbf{I}$ are $\mathbf{j}$ and $\mathbf{k}$.

So, if there is a matrix $\mathbf{I}$ such that $\mathbf{I A}=\mathbf{A}$ for all $\mathbf{A}$, then it must be the matrix whose columns are $\mathbf{i}, \mathbf{j}$, and $\mathbf{k}$, in that order. Checking, we see that we do indeed have
$$\left(\begin{array}{lll}
1 & 0 & 0 \\
0 & 1 & 0 \\
0 & 0 & 1
\end{array}\right)\left(\begin{array}{lll}
a_{11} & a_{12} & a_{13} \\
a_{21} & a_{22} & a_{23} \\
a_{31} & a_{32} & a_{33}
\end{array}\right)=\left(\begin{array}{lll}
a_{11} & a_{12} & a_{13} \\
a_{21} & a_{22} & a_{23} \\
a_{31} & a_{32} & a_{33}
\end{array}\right),$$
so $\mathbf{I A}=\mathbf{A}$ for any $3 \times 3$ matrix $\mathbf{A}$.
(b) We have
$$\left(\begin{array}{lll}
a_{11} & a_{12} & a_{13} \\
a_{21} & a_{22} & a_{23} \\
a_{31} & a_{32} & a_{33}
\end{array}\right)\left(\begin{array}{lll}
1 & 0 & 0 \\
0 & 1 & 0 \\
0 & 0 & 1
\end{array}\right)=\left(\begin{array}{lll}
a_{11} & a_{12} & a_{13} \\
a_{21} & a_{22} & a_{23} \\
a_{31} & a_{32} & a_{33}
\end{array}\right)$$
so the matrix $\mathbf{I}$ we found in part (a) satisfies $\mathbf{I A}=\mathbf{A}$ for any $\mathbf{A}$.
(c) Our work in part (a) shows that if $\mathbf{I A}=\mathbf{A}$ for all $\mathbf{A}$, then the columns of $\mathbf{I}$ must be $\mathbf{i}, \mathbf{j}$, and $\mathbf{k}$, in that order. So, we have shown that this matrix $\mathbf{I}$ is unique.

To see that this matrix is also the only matrix $\mathbf{I}$ such that $\mathbf{A I}=\mathbf{A}$ for all $\mathbf{A}$, suppose we have some matrix $\mathbf{J}$ such that $\mathbf{A J}=\mathbf{A}$ for all $\mathbf{A}$. Now, we let $\mathbf{A}=\mathbf{I}$, the matrix we found in part (a). Then, we have $\mathbf{I} \mathbf{J}=\mathbf{I}$. But we have $\mathbf{I} \mathbf{J}=\mathbf{J}$ because $\mathbf{I A}=\mathbf{A}$ for any $\mathbf{A}$, so we must have $\mathbf{J}=\mathbf{I}$. Therefore, the matrix $\mathbf{I}$ that we found in part (a) is the unique matrix such that $\mathbf{A I}=\mathbf{A}$ for all $\mathbf{A}$.

Important: The $3 \times 3$ matrix $\mathbf{I}$ such that $\mathbf{A I}=\mathbf{I} \mathbf{A}=\mathbf{A}$ for any $3 \times 3$ matrix $\mathbf{A}$ is
$$\mathbf{I}=\left(\begin{array}{lll}
1 & 0 & 0 \\
0 & 1 & 0 \\
0 & 0 & 1
\end{array}\right)$$

We call this the identity matrix.

Problem 11.13:
(a) Find the matrix $\mathbf{P}$ such that for every $\mathbf{A}$, the product $\mathbf{P A}$ results in a matrix whose third row is the same as that of $\mathbf{A}$, but the first two rows are swapped. (That is, the second row of the product is the first row of $\mathbf{A}$ and vice-versa.)
(b) Find a matrix $\mathbf{T}$ such that $\mathbf{T} \neq \mathbf{I}$ and $\mathbf{T}^{3}=\mathbf{I}$.

Solution for Problem 11.13:
(a) We find $\mathbf{P}$ the same way we found the identity matrix, by finding $\mathbf{P i}, \mathbf{P j}$, and $\mathbf{P k}$. Since each column of $\mathbf{P A}$ equals $\mathbf{P}$ times the corresponding column of $\mathbf{A}$, multiplying a vector by $\mathbf{P}$ exchanges the first and second rows of the vector but leaves the last row unchanged. Exchanging the first and second rows of $\mathbf{i}$ gives $\mathbf{j}$, so $\mathbf{P i}=\mathbf{j}$, which means the first column of $\mathbf{P}$ is $\mathbf{j}$. Exchanging first and second rows of $\mathbf{j}$ gives $\mathbf{i}$, so $\mathbf{P j}=\mathbf{i}$, which means the second column of $\mathbf{P}$ is $\mathbf{i}$. Finally, $\mathbf{P k}=\mathbf{k}$, so the third column of $\mathbf{P}$ is $\mathbf{k}$. Checking, we see

393

---

<!-- Page 394 -->

CHAPTER 11. VECTORS AND MATRICES IN THREE DIMENSIONS, PART 1

that we do indeed have
$$\left(\begin{array}{lll}
0 & 1 & 0 \\
1 & 0 & 0 \\
0 & 0 & 1
\end{array}\right)\left(\begin{array}{lll}
a_{11} & a_{12} & a_{13} \\
a_{21} & a_{22} & a_{23} \\
a_{31} & a_{32} & a_{33}
\end{array}\right)=\left(\begin{array}{lll}
a_{21} & a_{22} & a_{23} \\
a_{11} & a_{12} & a_{13} \\
a_{31} & a_{32} & a_{33}
\end{array}\right) .$$
(b) We could write out a $3 \times 3$ matrix for $\mathbf{T}$, cube it, and then compare it to $\mathbf{I}$, but that looks pretty terrifying. Trial-and-error doesn't seem like fun either-who wants to cube random $3 \times 3$ matrices?!?

Instead, we use part (a) as inspiration. There, we found a matrix $\mathbf{P}$ such that the product $\mathbf{P A}$ results in two rows of $\mathbf{A}$ being swapped. So, consider the product PPA. The product PA is just $\mathbf{A}$ with the first two rows swapped. Multiplying again by $\mathbf{P}$ to produce $\mathbf{P}^{2} \mathbf{A}$ simply swaps those two rows again, and gives us A back! So, $\mathbf{P}^{2} \mathbf{A}=\mathbf{A}$ for any $\mathbf{A}$, which means $\mathbf{P}^{2}=\mathbf{I}$ (as we showed in Problem 11.12).

But we want $\mathbf{T}^{3}=\mathbf{I}$, not $\mathbf{T}^{2}=\mathbf{I}$. Rather than swapping two rows, what if we cycled them? In other words, perhaps we can find a matrix $\mathbf{T}$ such that multiplying by $\mathbf{T}$ to get $\mathbf{T A}$ moves the first two rows of A down one row and moves the bottom row to the top. In other words, we want the matrix $\mathbf{T}$ such that $\mathbf{T i}=\mathbf{j}, \mathbf{T j}=\mathbf{k}$, and $\mathbf{T k}=\mathbf{i}$. These results tell us that the columns of $\mathbf{T}$ are, in order, $\mathbf{j}, \mathbf{k}$, and $\mathbf{i}$. Checking, we see that we have
$$\left(\begin{array}{lll}
0 & 0 & 1 \\
1 & 0 & 0 \\
0 & 1 & 0
\end{array}\right)\left(\begin{array}{lll}
a_{11} & a_{12} & a_{13} \\
a_{21} & a_{22} & a_{23} \\
a_{31} & a_{32} & a_{33}
\end{array}\right)=\left(\begin{array}{lll}
a_{31} & a_{32} & a_{33} \\
a_{11} & a_{12} & a_{13} \\
a_{21} & a_{22} & a_{23}
\end{array}\right) .$$

Multiplying a matrix $\mathbf{A}$ by $\mathbf{T}$ moves each row of $\mathbf{A}$ down one row while the last row of $\mathbf{A}$ becomes the first row of the product TA. Performing this operation three times gives us the original matrix back, which means that $\mathbf{T}^{3} \mathbf{A}=\mathbf{A}$. So, we have found a matrix $\mathbf{T}$ such that $\mathbf{T}^{3}$ is the identity. Let's check:
$$\left(\begin{array}{lll}
0 & 0 & 1 \\
1 & 0 & 0 \\
0 & 1 & 0
\end{array}\right)\left(\left(\begin{array}{lll}
0 & 0 & 1 \\
1 & 0 & 0 \\
0 & 1 & 0
\end{array}\right)\left(\begin{array}{lll}
0 & 0 & 1 \\
1 & 0 & 0 \\
0 & 1 & 0
\end{array}\right)\right)=\left(\begin{array}{lll}
0 & 0 & 1 \\
1 & 0 & 0 \\
0 & 1 & 0
\end{array}\right)\left(\begin{array}{lll}
0 & 1 & 0 \\
0 & 0 & 1 \\
1 & 0 & 0
\end{array}\right)=\left(\begin{array}{lll}
1 & 0 & 0 \\
0 & 1 & 0 \\
0 & 0 & 1
\end{array}\right) .$$

Success!

The two matrices we found in Problem 11.13 are called permutation matrices. A permutation matrix is a matrix $\mathbf{P}$ such that for any matrix $\mathbf{A}$, the rows of the product $\mathbf{P A}$ are just a reordering of the rows of $\mathbf{A}$ (or exactly the same ordering-the identity matrix is a permutation matrix, too).

Exercises
11.2.1 Find the following products:
(a) $\quad\left(\begin{array}{ccc}4 & -1 & 3 \\ -1 & 0 & 5 \\ -3 & -1 & 6\end{array}\right)\left(\begin{array}{c}-1 \\ 4 \\ -5\end{array}\right)$
(b) $\quad\left(\begin{array}{ccc}0 & -3 & 2 \\ -1 & -2 & 7 \\ -3 & 2 & 1\end{array}\right)\left(\begin{array}{c}0 \\ -3 \\ 3\end{array}\right)$
11.2.2 Compute the product $\left(\begin{array}{ccc}-1 & -3 & 6 \\ -2 & 4 & 0 \\ -1 & -2 & 0\end{array}\right)\left(\begin{array}{ccc}0 & -1 & 3 \\ 10 & -2 & -3 \\ 4 & 6 & 0.5\end{array}\right)$.
11.2.3 Let $k$ be a nonzero constant. Find a matrix $\mathbf{M}$ such that $\mathbf{M A}=k \mathbf{A}$ for any matrix $\mathbf{A}$
11.2.4 Is the matrix $\mathbf{T}$ we found in part (b) of Problem 11.13 the only matrix $\mathbf{T}$ such that $\mathbf{T} \neq \mathbf{I}$ and $\mathbf{T}^{3}=\mathbf{I}$ ?

394

---

<!-- Page 395 -->

11.3. DETERMINANTS OF $3 \times 3$ MATRICES
11.3 Determinants of $3 \times 3$ Matrices

We introduced the determinant of a $2 \times 2$ matrix by solving a system of two linear equations in two variables. So, you might not be surprised that we introduce the determinant of a $3 \times 3$ matrix by solving a system of three linear equations in three variables.

Problem 11.14: Consider the system of equations
$$\begin{array}{l}
a_{1} x+b_{1} y+c_{1} z=d_{1} \\
a_{2} x+b_{2} y+c_{2} z=d_{2} \\
a_{3} x+b_{3} y+c_{3} z=d_{3}
\end{array}$$
where the $a_{i}, b_{i}, c_{i}$, and $d_{i}$ are constants. Show that if $a_{1}\left|\begin{array}{ll}b_{2} & c_{2} \\ b_{3} & c_{3}\end{array}\right|-b_{1}\left|\begin{array}{ll}a_{2} & c_{2} \\ a_{3} & c_{3}\end{array}\right|+c_{1}\left|\begin{array}{ll}a_{2} & b_{2} \\ a_{3} & b_{3}\end{array}\right| \neq 0$, then
$$x=\frac{d_{1}\left|\begin{array}{ll}
b_{2} & c_{2} \\
b_{3} & c_{3}
\end{array}\right|-b_{1}\left|\begin{array}{ll}
d_{2} & c_{2} \\
d_{3} & c_{3}
\end{array}\right|+c_{1}\left|\begin{array}{ll}
d_{2} & b_{2} \\
d_{3} & b_{3}
\end{array}\right|}{a_{1}\left|\begin{array}{ll}
b_{2} & c_{2} \\
b_{3} & c_{3}
\end{array}\right|-b_{1}\left|\begin{array}{ll}
a_{2} & c_{2} \\
a_{3} & c_{3}
\end{array}\right|+c_{1}\left|\begin{array}{ll}
a_{2} & b_{2} \\
a_{3} & b_{3}
\end{array}\right|}$$

Solution for Problem 11.14: We start by eliminating $z$ from the second and third equations. Subtracting $c_{2}$ times the first equation from $c_{1}$ times the second equation and subtracting $c_{3}$ times the first equation from $c_{1}$ times the third gives the system
$$\begin{array}{l}
\left(a_{2} c_{1}-a_{1} c_{2}\right) x+\left(b_{2} c_{1}-b_{1} c_{2}\right) y=d_{2} c_{1}-d_{1} c_{2} \\
\left(a_{3} c_{1}-a_{1} c_{3}\right) x+\left(b_{3} c_{1}-b_{1} c_{3}\right) y=d_{3} c_{1}-d_{1} c_{3}
\end{array}$$

We can use Cramer's rule to solve for $x$ and $y$ if and only if $\left|\begin{array}{ll}a_{2} c_{1}-a_{1} c_{2} & b_{2} c_{1}-b_{1} c_{2} \\ a_{3} c_{1}-a_{1} c_{3} & b_{3} c_{1}-b_{1} c_{3}\end{array}\right| \neq 0$. Let's take a closer look at this determinant. We have
$$\left|\begin{array}{ll}
a_{2} c_{1}-a_{1} c_{2} & b_{2} c_{1}-b_{1} c_{2} \\
a_{3} c_{1}-a_{1} c_{3} & b_{3} c_{1}-b_{1} c_{3}
\end{array}\right|=\left(a_{2} c_{1}-a_{1} c_{2}\right)\left(b_{3} c_{1}-b_{1} c_{3}\right)-\left(b_{2} c_{1}-b_{1} c_{2}\right)\left(a_{3} c_{1}-a_{1} c_{3}\right)$$

When we expand the products, the $a_{1} b_{1} c_{2} c_{3}$ terms cancel. All remaining terms have at least one factor of $c_{1}$. Factoring $c_{1}$ out of everything and grouping the remaining terms by factors $a_{1}, b_{1}$, and $c_{1}$, we have
$$\left|\begin{array}{ll}
a_{2} c_{1}-a_{1} c_{2} & b_{2} c_{1}-b_{1} c_{2} \\
a_{3} c_{1}-a_{1} c_{3} & b_{3} c_{1}-b_{1} c_{3}
\end{array}\right|=c_{1}\left[a_{1}\left(b_{2} c_{3}-b_{3} c_{2}\right)+b_{1}\left(c_{2} a_{3}-c_{3} a_{2}\right)+c_{1}\left(b_{3} a_{2}-b_{2} a_{3}\right)\right]$$

We recognize the expressions in the inner parentheses as determinants of $2 \times 2$ matrices, and we have
$$\left|\begin{array}{ll}
a_{2} c_{1}-a_{1} c_{2} & b_{2} c_{1}-b_{1} c_{2} \\
a_{3} c_{1}-a_{1} c_{3} & b_{3} c_{1}-b_{1} c_{3}
\end{array}\right|=c_{1}\left(a_{1}\left|\begin{array}{ll}
b_{2} & c_{2} \\
b_{3} & c_{3}
\end{array}\right|-b_{1}\left|\begin{array}{ll}
a_{2} & c_{2} \\
a_{3} & c_{3}
\end{array}\right|+c_{1}\left|\begin{array}{ll}
a_{2} & b_{2} \\
a_{3} & b_{3}
\end{array}\right|\right)$$
(We'll explain why we write the middle term as $-b_{1}\left|\begin{array}{ll}d_{2} & c_{2} \\ d_{3} & c_{3}\end{array}\right|$ rather than $b_{1}\left|\begin{array}{ll}c_{2} & d_{2} \\ c_{3} & d_{3}\end{array}\right|$ later in this section.)
We need the determinant on the left side of Equation (11.4) to be nonzero in order to be able to apply Cramer's rule to the system
$$\begin{array}{l}
\left(a_{2} c_{1}-a_{1} c_{2}\right) x+\left(b_{2} c_{1}-b_{1} c_{2}\right) y=d_{2} c_{1}-d_{1} c_{2} \\
\left(a_{3} c_{1}-a_{1} c_{3}\right) x+\left(b_{3} c_{1}-b_{1} c_{3}\right) y=d_{3} c_{1}-d_{1} c_{3}
\end{array}$$

395

---

<!-- Page 396 -->

CHAPTER 11. VECTORS AND MATRICES IN THREE DIMENSIONS, PART 1

We are given that the expression in parentheses on line (11.4) is nonzero. But we'll also need $c_{1} \neq 0$ in order to apply Cramer's rule. We'll tackle the case in which $c_{1} \neq 0$ now, and defer the case in which $c_{1}=0$ to Problem 11.18.

WARNING!!
We have to be very careful about 0 , and often have to deal with 0 as a separate case when constructing proofs and solving problems.

Assuming that $c \neq 0$, the determinant on line (11.4) is nonzero, and we can apply Cramer's rule to find
$$x=\frac{\left|\begin{array}{ll}
d_{2} c_{1}-d_{1} c_{2} & b_{2} c_{1}-b_{1} c_{2} \\
d_{3} c_{1}-d_{1} c_{3} & b_{3} c_{1}-b_{1} c_{3}
\end{array}\right|}{\left|\begin{array}{ll}
a_{2} c_{1}-a_{1} c_{2} & b_{2} c_{1}-b_{1} c_{2} \\
a_{3} c_{1}-a_{1} c_{3} & b_{3} c_{1}-b_{1} c_{3}
\end{array}\right|} .$$

Following the same expansion, cancellation, and factorization steps as above, we find that
$$x=\frac{c_{1}\left[d_{1}\left(b_{2} c_{3}-b_{3} c_{2}\right)+b_{1}\left(c_{2} d_{3}-c_{3} d_{2}\right)+c_{1}\left(b_{3} d_{2}-b_{2} d_{3}\right)\right]}{c_{1}\left[a_{1}\left(b_{2} c_{3}-b_{3} c_{2}\right)+b_{1}\left(c_{2} a_{3}-c_{3} a_{2}\right)+c_{1}\left(b_{3} a_{2}-b_{2} a_{3}\right)\right]}=\frac{d_{1}\left|\begin{array}{ll}
b_{2} & c_{2} \\
b_{3} & c_{3}
\end{array}\right|-b_{1}\left|\begin{array}{ll}
d_{2} & c_{2} \\
d_{3} & c_{3}
\end{array}\right|+c_{1}\left|\begin{array}{ll}
d_{2} & b_{2} \\
d_{3} & b_{3}
\end{array}\right|}{a_{1}\left|\begin{array}{ll}
b_{2} & c_{2} \\
b_{3} & c_{3}
\end{array}\right|-b_{1}\left|\begin{array}{ll}
a_{2} & c_{2} \\
a_{3} & c_{3}
\end{array}\right|+c_{1}\left|\begin{array}{ll}
a_{2} & b_{2} \\
a_{3} & b_{3}
\end{array}\right|} .$$

As a reminder, we'll deal with the case in which $c_{1}=0$ in Problem 11.18.

We use the unwieldy expressions in the numerator and denominator of our result for $x$ above to define the determinant of a $3 \times 3$ matrix.

Definition: We define the determinant of a $3 \times 3$ matrix as follows:
$$\begin{aligned}
\left|\begin{array}{lll}
a_{1} & b_{1} & c_{1} \\
a_{2} & b_{2} & c_{2} \\
a_{3} & b_{3} & c_{3}
\end{array}\right| & =a_{1}\left|\begin{array}{ll}
b_{2} & c_{2} \\
b_{3} & c_{3}
\end{array}\right|-b_{1}\left|\begin{array}{ll}
a_{2} & c_{2} \\
a_{3} & c_{3}
\end{array}\right|+c_{1}\left|\begin{array}{ll}
a_{2} & b_{2} \\
a_{3} & b_{3}
\end{array}\right| \\
& =a_{1} b_{2} c_{3}+b_{1} c_{2} a_{3}+c_{1} a_{2} b_{3}-a_{1} c_{2} b_{3}-b_{1} a_{2} c_{3}-c_{1} b_{2} a_{3} .
\end{aligned}$$

We can also denote the determinant of a matrix $\mathbf{A}$ as $\operatorname{det}(\mathbf{A})$.
Letting $\mathbf{A}=\left(\begin{array}{lll}a_{1} & b_{1} & c_{1} \\ a_{2} & b_{2} & c_{2} \\ a_{3} & b_{3} & c_{3}\end{array}\right)$, we can write the original system in Problem 11.14 as
$$\mathbf{A}\left(\begin{array}{l}
x \\
y \\
z
\end{array}\right)=\left(\begin{array}{l}
d_{1} \\
d_{2} \\
d_{3}
\end{array}\right) .$$

In Problem 11.14, we found that if $\operatorname{det}(\mathbf{A}) \neq 0$, then
$$x=\frac{\left|\begin{array}{lll}
d_{1} & b_{1} & c_{1} \\
d_{2} & b_{2} & c_{2} \\
d_{3} & b_{3} & c_{3}
\end{array}\right|}{a_{1}\left|\begin{array}{ll}
b_{2} & c_{2} \\
b_{3} & c_{3}
\end{array}\right|-b_{1}\left|\begin{array}{ll}
a_{2} & c_{2} \\
a_{3} & c_{3}
\end{array}\right|+c_{1}\left|\begin{array}{lll}
a_{2} & b_{2} \\
a_{3} & b_{3}
\end{array}\right|}=\frac{\left|\begin{array}{lll}
d_{1} & b_{1} & c_{1} \\
d_{2} & b_{2} & c_{2} \\
d_{3} & b_{3} & c_{3}
\end{array}\right|}{\operatorname{det}(\mathbf{A})} .$$

This gives us an expression for $x$ that is very much like the expression we found in Cramer's rule for systems of two linear equations with two variables. Indeed, we can go through essentially the same steps to show that if

396

---

<!-- Page 397 -->

11.3. DETERMINANTS OF $3 \times 3$ MATRICES

$\operatorname{det}(\mathbf{A}) \neq 0$, then the system has the solution
$$x=\frac{\left|\begin{array}{lll}
d_{1} & b_{1} & c_{1} \\
d_{2} & b_{2} & c_{2} \\
d_{3} & b_{3} & c_{3}
\end{array}\right|}{\operatorname{det}(\mathbf{A})}, \quad y=\frac{\left|\begin{array}{lll}
a_{1} & d_{1} & c_{1} \\
a_{2} & d_{2} & c_{2} \\
a_{3} & d_{3} & c_{3}
\end{array}\right|}{\operatorname{det}(\mathbf{A})}, \quad z=\frac{\left|\begin{array}{lll}
a_{1} & b_{1} & d_{1} \\
a_{2} & b_{2} & d_{2} \\
a_{3} & b_{3} & d_{3}
\end{array}\right|}{\operatorname{det}(\mathbf{A})} .$$

We call this Cramer's rule for a three-variable system of three linear equations.
Cramer's rule is just one application of determinants of $3 \times 3$ matrices. You'll encounter applications of determinants in various areas of mathematics, physics, economics, and engineering.

Looking back at our solution to Problem 11.14, we see one particularly useful application of the determinant. Specifically, our work there, together with corresponding work solving for $y$ and $z$, shows that the system
$$\begin{array}{l}
a_{1} x+b_{1} y+c_{1} z=d_{1} \\
a_{2} x+b_{2} y+c_{2} z=d_{2} \\
a_{3} x+b_{3} y+c_{3} z=d_{3}
\end{array}$$
has a unique solution for $x$ if
$$\left|\begin{array}{lll}
a_{1} & b_{1} & c_{1} \\
a_{2} & b_{2} & c_{2} \\
a_{3} & b_{3} & c_{3}
\end{array}\right| \neq 0$$

In other words, if the determinant of the matrix given by the coefficients of the variables in the system is nonzero, then the system has a unique solution.

Just as with $2 \times 2$ matrices, we say that a $3 \times 3$ matrix is singular if its determinant is 0 and nonsingular if its determinant is nonzero. Therefore, the system $\mathbf{A v}=\mathbf{c}$ has a unique solution if $\mathbf{A}$ is nonsingular.

As you'll see in Section 12.5, we can use this observation as a starting point to determine whether or not a given $3 \times 3$ matrix has an inverse. But we'll need a few more important concepts before we can tackle that, so now we'll get more accustomed to the determinant by exploring some of its properties.

When you're first getting started with the determinants of $3 \times 3$ matrices, it can be pretty hard to remember how to compute them. One handy way of remembering the expression for the determinant of a $3 \times 3$ matrix is shown at right. We copy the first two columns of
the matrix after the third column as shown. We add the products of three numbers along the three northwest-to-southeast diagonals (the diagonals along solid gray lines in the diagram) and subtract the products of three numbers along the three northeast-to-southwest diagonals (those along dashed gray lines in the diagram). This is sometimes referred to as the Rule of Sarrus.

Problems

Problem 11.15: Evaluate each of the following:
(a) $\left|\begin{array}{ccc}4 & -1 & 0 \\ 5 & 7 & -2 \\ -3 & -2 & 1\end{array}\right|$
(b) $\left|\begin{array}{ccc}5 & 3 & -1 \\ 4 & 1 & -5 \\ -3 & 2 & 6\end{array}\right|$

397

---

<!-- Page 398 -->

CHAPTER 11. VECTORS AND MATRICES IN THREE DIMENSIONS, PART 1

Problem 11.16: Let $\mathbf{A}=\left(\begin{array}{lll}a_{1} & b_{1} & c_{1} \\ a_{2} & b_{2} & c_{2} \\ a_{3} & b_{3} & c_{3}\end{array}\right)$. The transpose of $\mathbf{A}$, which is denoted as $\mathbf{A}^{T}$, is defined as follows:
$$\mathbf{A}^{T}=\left(\begin{array}{lll}
a_{1} & a_{2} & a_{3} \\
b_{1} & b_{2} & b_{3} \\
c_{1} & c_{2} & c_{3}
\end{array}\right)$$

We can think of the transpose as the result of "flipping" the matrix over the diagonal from upper left to lower right of the matrix. Show that $\operatorname{det}(\mathbf{A})=\operatorname{det}\left(\mathbf{A}^{T}\right)$.

Problem 11.17:
(a) Suppose each entry in one row of $\mathbf{A}$ is multiplied by some constant $k$. How is the determinant of the new matrix related to $\operatorname{det}(\mathbf{A})$ ?
(b) Suppose each entry in one column of $\mathbf{A}$ is multiplied by some constant $k$. How is the determinant of the new matrix related to $\operatorname{det}(\mathbf{A})$ ?
(c) How is $\operatorname{det}(k \mathbf{A})$ related to $\operatorname{det}(\mathbf{A})$, where $\mathbf{A}$ is a $3 \times 3$ matrix?

Problem 11.18:
(a) Suppose $\mathbf{B}$ is the matrix formed when we swap the first and second rows of $\mathbf{A}$. How are $\operatorname{det}(\mathbf{A})$ and $\operatorname{det}(\mathbf{B})$ related?
(b) Patch the hole in our solution to Problem 11.14 by using part (a) to address the case in which $c_{1}=0$.

Problem 11.19:
(a) Show that if one row of $\mathbf{A}$ is a constant times another row, then $\operatorname{det}(\mathbf{A})=0$.
(b) If $\operatorname{det}(\mathbf{A})=0$, then must either one row of $\mathbf{A}$ be a constant times another row or one column be a constant times another column?

Problem 11.20:
(a) Show that $\left|\begin{array}{lll}a_{1} & b_{1} & c_{1} \\ a_{2} & b_{2} & c_{2} \\ a_{3} & b_{3} & c_{3}\end{array}\right|=-a_{2}\left|\begin{array}{ll}b_{1} & c_{1} \\ b_{3} & c_{3}\end{array}\right|+b_{2}\left|\begin{array}{ll}a_{1} & c_{1} \\ a_{3} & c_{3}\end{array}\right|-c_{2}\left|\begin{array}{ll}a_{1} & b_{1} \\ a_{3} & b_{3}\end{array}\right|$.
(b) Show that $\left|\begin{array}{lll}a_{1} & b_{1} & c_{1} \\ a_{2} & b_{2} & c_{2} \\ a_{3} & b_{3} & c_{3}\end{array}\right|=c_{1}\left|\begin{array}{ll}a_{2} & b_{2} \\ a_{3} & b_{3}\end{array}\right|-c_{2}\left|\begin{array}{ll}a_{1} & b_{1} \\ a_{3} & b_{3}\end{array}\right|+c_{3}\left|\begin{array}{ll}a_{1} & b_{1} \\ a_{2} & b_{2}\end{array}\right|$.

Problem 11.21:
(a) How are $\left|\begin{array}{ccc}1 & 3 & 4 \\ 2 & -1 & 2 \\ 5 & 0 & 3\end{array}\right|+\left|\begin{array}{ccc}-3 & 2 & -1 \\ 2 & -1 & 2 \\ 5 & 0 & 3\end{array}\right|$ and $\left|\begin{array}{ccc}-2 & 5 & 3 \\ 2 & -1 & 2 \\ 5 & 0 & 3\end{array}\right|$ related?
(b) Notice that the first row of the final matrix in part (a) is the sum of the first rows of the other two matrices, and that the last two rows of all three matrices are the same. Does the relationship you found in part (a) generalize? That is, must we always have
$$\left|\begin{array}{lll}
a_{1} & b_{1} & c_{1} \\
a_{2} & b_{2} & c_{2} \\
a_{3} & b_{3} & c_{3}
\end{array}\right|+\left|\begin{array}{lll}
a_{1}^{\prime} & b_{1}^{\prime} & c_{1}^{\prime} \\
a_{2} & b_{2} & c_{2} \\
a_{3} & b_{3} & c_{3}
\end{array}\right|=\left|\begin{array}{ccc}
a_{1}+a_{1}^{\prime} & b_{1}+b_{1}^{\prime} & c_{1}+c_{1}^{\prime} \\
a_{2} & b_{2} & c_{2} \\
a_{3} & b_{3} & c_{3}
\end{array}\right| .$$
(c) Must we have $\operatorname{det}(\mathbf{A})+\operatorname{det}(\mathbf{B})=\operatorname{det}(\mathbf{A}+\mathbf{B})$ for any matrices $\mathbf{A}$ and $\mathbf{B}$ ?

398

---

<!-- Page 399 -->

11.3. DETERMINANTS OF $3 \times 3$ MATRICES

Problem 11.22: Let $\mathbf{A}=\left(\begin{array}{ccc}1 & 3 & 5 \\ -1 & 4 & 2 \\ -3 & 0 & 6\end{array}\right)$ and let $\mathbf{B}=\left(\begin{array}{ccc}1 & 3 & 5 \\ 2 & 13 & 17 \\ -3 & 0 & 6\end{array}\right)$, where $\mathbf{B}$ is the matrix formed by adding 3 times the first row of $\mathbf{A}$ to the second row of $\mathbf{A}$ and leaving the other two rows unchanged. How are $\operatorname{det}(\mathbf{A})$ and $\operatorname{det}(\mathbf{B})$ related? Can you generalize this observation?

Problem 11.23: Evaluate each of the following:
(a) $\left|\begin{array}{ccc}13 & -26 & 39 \\ 8 & 32 & -23 \\ 4 & 16 & -12\end{array}\right|$
(b) $\left|\begin{array}{ccc}2009 & 10050 & -2010 \\ 328 & 1640 & -328 \\ -602 & -2990 & 598\end{array}\right|$

We start with a little practice evaluating determinants of $3 \times 3$ matrices.
Problem 11.15: Evaluate each of the following:
(a) $\left|\begin{array}{ccc}4 & -1 & 0 \\ 5 & 7 & -2 \\ -3 & -2 & 1\end{array}\right|$
(b) $\left|\begin{array}{ccc}5 & 3 & -1 \\ 4 & 1 & -5 \\ -3 & 2 & 6\end{array}\right|$

Solution for Problem 11.15:
(a) We have
$$\begin{aligned}
\left|\begin{array}{ccc}
4 & -1 & 0 \\
5 & 7 & -2 \\
-3 & -2 & 1
\end{array}\right| & =4\left|\begin{array}{cc}
7 & -2 \\
-2 & 1
\end{array}\right|-(-1)\left|\begin{array}{cc}
5 & -2 \\
-3 & 1
\end{array}\right|+0\left|\begin{array}{cc}
5 & 7 \\
-3 & -2
\end{array}\right| \\
& =4((7)(1)-(-2)(-2))+1((5)(1)-(-2)(-3))+0=4(3)+1(-1)=11
\end{aligned}$$
(b) We have
$$\begin{aligned}
\left|\begin{array}{ccc}
5 & 3 & -1 \\
4 & 1 & -5 \\
-3 & 2 & 6
\end{array}\right| & =5\left|\begin{array}{cc}
1 & -5 \\
2 & 6
\end{array}\right|-3\left|\begin{array}{cc}
4 & -5 \\
-3 & 6
\end{array}\right|+(-1)\left|\begin{array}{cc}
4 & 1 \\
-3 & 2
\end{array}\right| \\
& =5((1)(6)-(2)(-5))-3((4)(6)-(-5)(-3))+(-1)((4)(2)-(1)(-3)) \\
& =5(16)-3(9)+(-1)(11)=42
\end{aligned}$$

Problem 11.16: Let $\mathbf{A}=\left(\begin{array}{lll}a_{1} & b_{1} & c_{1} \\ a_{2} & b_{2} & c_{2} \\ a_{3} & b_{3} & c_{3}\end{array}\right)$. The transpose of $\mathbf{A}$, which is denoted as $\mathbf{A}^{T}$, is defined as follows:
$$\mathbf{A}^{T}=\left(\begin{array}{lll}
a_{1} & a_{2} & a_{3} \\
b_{1} & b_{2} & b_{3} \\
c_{1} & c_{2} & c_{3}
\end{array}\right)$$

We can think of the transpose as the result of "flipping" the matrix over the diagonal from upper left to lower right of the matrix. Show that $\operatorname{det}(\mathbf{A})=\operatorname{det}\left(\mathbf{A}^{T}\right)$.

399

---

<!-- Page 400 -->

CHAPTER 11. VECTORS AND MATRICES IN THREE DIMENSIONS, PART 1

Solution for Problem 11.16: We have
$$\operatorname{det}(\mathbf{A})=a_{1} b_{2} c_{3}+b_{1} c_{2} a_{3}+c_{1} a_{2} b_{3}-a_{1} c_{2} b_{3}-b_{1} a_{2} c_{3}-c_{1} b_{2} a_{3}$$
and
$$\begin{aligned}
\operatorname{det}\left(\mathbf{A}^{T}\right)=\left|\begin{array}{lll}
a_{1} & a_{2} & a_{3} \\
b_{1} & b_{2} & b_{3} \\
c_{1} & c_{2} & c_{3}
\end{array}\right| & =a_{1} b_{2} c_{3}+a_{2} b_{3} c_{1}+a_{3} b_{1} c_{2}-a_{1} b_{3} c_{2}-a_{2} b_{1} c_{3}-a_{3} b_{2} c_{1} \\
& =a_{1} b_{2} c_{3}+c_{1} a_{2} b_{3}+b_{1} c_{2} a_{3}-a_{1} c_{2} b_{3}-b_{1} a_{2} c_{3}-c_{1} b_{2} a_{3} \\
& =a_{1} b_{2} c_{3}+b_{1} c_{2} a_{3}+c_{1} a_{2} b_{3}-a_{1} c_{2} b_{3}-b_{1} a_{2} c_{3}-c_{1} b_{2} a_{3}
\end{aligned}$$
so $\operatorname{det}(\mathbf{A})=\operatorname{det}\left(\mathbf{A}^{T}\right)$.

Important: For any matrix $\mathbf{A}$, we have $\operatorname{det}\left(\mathbf{A}^{T}\right)=\operatorname{det}(\mathbf{A})$, where $\mathbf{A}^{T}$ is the transpose of $\mathbf{A}$.
D

We'll see why this fact is useful in the next problem.
Problem 11.17:
(a) Suppose each entry in one row of $\mathbf{A}$ is multiplied by some constant $k$. How is the determinant of the new matrix related to $\operatorname{det}(\mathbf{A})$ ?
(b) Suppose each entry in one column of $\mathbf{A}$ is multiplied by some constant $k$. How is the determinant of the new matrix related to $\operatorname{det}(\mathbf{A})$ ?
(c) How is $\operatorname{det}(k \mathbf{A})$ related to $\operatorname{det}(\mathbf{A})$, where $\mathbf{A}$ is a $3 \times 3$ matrix?

Solution for Problem 11.17:
(a) We have
$$\begin{aligned}
\left|\begin{array}{ccc}
k a_{1} & k b_{1} & k c_{1} \\
a_{2} & b_{2} & c_{2} \\
a_{3} & b_{3} & c_{3}
\end{array}\right| & =k a_{1} b_{2} c_{3}+k b_{1} c_{2} a_{3}+k c_{1} a_{2} b_{3}-k a_{1} c_{2} b_{3}-k b_{1} a_{2} c_{3}-k c_{1} b_{2} a_{3} \\
& =k\left(a_{1} b_{2} c_{3}+b_{1} c_{2} a_{3}+c_{1} a_{2} b_{3}-a_{1} c_{2} b_{3}-b_{1} a_{2} c_{3}-c_{1} b_{2} a_{3}\right) \\
& =k\left|\begin{array}{lll}
a_{1} & b_{1} & c_{1} \\
a_{2} & b_{2} & c_{2} \\
a_{3} & b_{3} & c_{3}
\end{array}\right|
\end{aligned}$$

So, multiplying the first row of a matrix by $k$ multiplies the determinant by $k$. Similarly, if we multiply any row or any column by $k$, we multiply each term in the determinant by $k$, thereby multiplying the whole determinant by $k$.
(b) Rather than going through all the computations, we can use part (a) together with what we just learned about the determinant of the transpose of a matrix. Suppose we multiply the first column of $\mathbf{A}$ by $k$. Since the determinant of a matrix equals the determinant of its transpose, we have
$$\operatorname{det}\left(\begin{array}{lll}
k a_{1} & b_{1} & c_{1} \\
k a_{2} & b_{2} & c_{2} \\
k a_{3} & b_{3} & c_{3}
\end{array}\right)=\operatorname{det}\left(\begin{array}{ccc}
k a_{1} & k a_{2} & k a_{3} \\
b_{1} & b_{2} & b_{3} \\
c_{1} & c_{2} & c_{3}
\end{array}\right)=k \operatorname{det}\left(\begin{array}{lll}
a_{1} & b_{1} & c_{1} \\
a_{2} & b_{2} & c_{2} \\
a_{3} & b_{3} & c_{3}
\end{array}\right)=k \operatorname{det}\left(\mathbf{A}^{T}\right)=k \operatorname{det}(\mathbf{A}),$$
where we used part (a) to "factor" $k$ out of the first row. We can go through similar steps if any other column is multiplied by $k$ to show that multiplying any column of a matrix multiplies its determinant by $k$.

400

---

<!-- Page 401 -->

11.3. DETERMINANTS OF $3 \times 3$ MATRICES
(c) Multiplying a row by $k$ multiplies the determinant by $k$. To produce $k \mathbf{A}$, we multiply each of the three rows by $k$, thereby multiplying the determinant by $k$ three times. So, we have $\operatorname{det}(k \mathbf{A})=k^{3} \operatorname{det}(\mathbf{A})$.

Our solution to part (b) shows how useful the fact that $\operatorname{det}(\mathbf{A})=\operatorname{det}\left(\mathbf{A}^{T}\right)$ can be.
```
Concept: Because }\operatorname{det}(\mathbf{A})=\operatorname{det}(\mp@subsup{\mathbf{A}}{}{T})\mathrm{ , for anything we prove regarding the rows and the
```

```
determinant of a matrix, we can prove a corresponding fact about the columns and the determinant of a matrix.
```

Problem 11.18:
(a) Suppose B is the matrix formed when we swap the first and second rows of A. How are $\operatorname{det}(\mathbf{A})$ and $\operatorname{det}(\mathbf{B})$ related?
(b) Patch the hole in our solution to Problem 11.14 by using part (a) to address the case in which $c_{1}=0$.

Solution for Problem 11.18:
(a) We have
$$\begin{aligned}
\left|\begin{array}{lll}
a_{1} & b_{1} & c_{1} \\
a_{2} & b_{2} & c_{2} \\
a_{3} & b_{3} & c_{3}
\end{array}\right| & =a_{1} b_{2} c_{3}+b_{1} c_{2} a_{3}+c_{1} a_{2} b_{3}-a_{1} c_{2} b_{3}-b_{1} a_{2} c_{3}-c_{1} b_{2} a_{3} \\
\left|\begin{array}{lll}
a_{2} & b_{2} & c_{2} \\
a_{1} & b_{1} & c_{1} \\
a_{3} & b_{3} & c_{3}
\end{array}\right| & =a_{2} b_{1} c_{3}+b_{2} c_{1} a_{3}+c_{2} a_{1} b_{3}-a_{2} c_{1} b_{3}-b_{2} a_{1} c_{3}-c_{2} b_{1} a_{3} \\
& =b_{1} a_{2} c_{3}+c_{1} b_{2} a_{3}+a_{1} c_{2} b_{3}-c_{1} a_{2} b_{3}-a_{1} b_{2} c_{3}-b_{1} c_{2} a_{3}
\end{aligned}$$

We see that the terms in the second determinant are the opposites of those in the first determinant. (We have $a_{1} b_{2} c_{3}$ in first and $-a_{1} b_{2} c_{3}$ in the second, and so on.) Therefore, the second determinant is the negative of the first.

We can go through essentially the same manipulations as above to show the following:
Important: If we produce matrix $\mathbf{B}$ by swapping any two rows or any two columns of $\mathbf{A}$, then $\operatorname{det}(\mathbf{B})=-\operatorname{det}(\mathbf{A})$.
(b) Let $\mathbf{A}=\left(\begin{array}{lll}a_{1} & b_{1} & c_{1} \\ a_{2} & b_{2} & c_{2} \\ a_{3} & b_{3} & c_{3}\end{array}\right)$. In Problem 11.14 and the discussion thereafter, we showed that if $\operatorname{det}(\mathbf{A})$ and $c_{1} \neq 0$, then the system of equations
$$\begin{array}{l}
a_{1} x+b_{1} y+c_{1} z=d_{1} \\
a_{2} x+b_{2} y+c_{2} z=d_{2} \\
a_{3} x+b_{3} y+c_{3} z=d_{3}
\end{array}$$

401

---

<!-- Page 402 -->

CHAPTER 11. VECTORS AND MATRICES IN THREE DIMENSIONS, PART 1

has the unique solution
$$x=\frac{\left|\begin{array}{lll}
d_{1} & b_{1} & c_{1} \\
d_{2} & b_{2} & c_{2} \\
d_{3} & b_{3} & c_{3}
\end{array}\right|}{\operatorname{det}(\mathbf{A})}, \quad y=\frac{\left|\begin{array}{lll}
a_{1} & d_{1} & c_{1} \\
a_{2} & d_{2} & c_{2} \\
a_{3} & d_{3} & c_{3}
\end{array}\right|}{\operatorname{det}(\mathbf{A})}, \quad z=\frac{\left|\begin{array}{lll}
a_{1} & b_{1} & d_{1} \\
a_{2} & b_{2} & d_{2} \\
a_{3} & b_{3} & d_{3}
\end{array}\right|}{\operatorname{det}(\mathbf{A})} .$$

To deal with the case in which $c_{1}=0$, we note that if $c_{1}=0$, then either $c_{2}$ or $c_{3}$ must be nonzero, since otherwise we would have $\operatorname{det}(\mathbf{A})=0$ (because there is a factor of the form $c_{i}$ in each term of the expansion of $\operatorname{det}(\mathbf{A})$ ).

Suppose $c_{2} \neq 0$. Then, we can view our system of equations as
$$\begin{array}{l}
a_{2} x+b_{2} y+c_{2} z=d_{2} \\
a_{1} x+b_{1} y+c_{1} z=d_{1} \\
a_{3} x+b_{3} y+c_{3} z=d_{3}
\end{array}$$
where all we have done is swapped the first and second equations. Then, our work in Problem 11.14 tells us that
$$x=\frac{\left|\begin{array}{lll}
d_{2} & b_{2} & c_{2} \\
d_{1} & b_{1} & c_{1} \\
d_{3} & b_{3} & c_{3}
\end{array}\right|}{\left|\begin{array}{lll}
a_{2} & b_{2} & c_{2} \\
a_{1} & b_{1} & c_{1} \\
a_{3} & b_{3} & c_{3}
\end{array}\right|} .$$

Applying the result of part (a), we swap the first and second rows of each determinant and have
$$x=\frac{\left|\begin{array}{lll}
d_{2} & b_{2} & c_{2} \\
d_{1} & b_{1} & c_{1} \\
d_{3} & b_{3} & c_{3}
\end{array}\right|}{\left|\begin{array}{lll}
a_{2} & b_{2} & c_{2} \\
a_{1} & b_{1} & c_{1} \\
a_{3} & b_{3} & c_{3}
\end{array}\right|}=x=\frac{-\left|\begin{array}{lll}
d_{1} & b_{1} & c_{1} \\
d_{2} & b_{2} & c_{2} \\
d_{3} & b_{3} & c_{3}
\end{array}\right|}{-\left|\begin{array}{lll}
a_{1} & b_{1} & c_{1} \\
a_{2} & b_{2} & c_{2} \\
a_{3} & b_{3} & c_{3}
\end{array}\right|}=\frac{\left|\begin{array}{lll}
d_{1} & b_{1} & c_{1} \\
d_{2} & b_{2} & c_{2} \\
d_{3} & b_{3} & c_{3}
\end{array}\right|}{\operatorname{det}(\mathbf{A})},$$
as desired. We can do essentially the same for $y$ and $z$, so Cramer's rule holds if $\operatorname{det}(\mathbf{A}) \neq 0, c_{1}=0$, and $c_{2} \neq 0$.

Finally, we can go through essentially the same steps as above if $c_{1}=c_{2}=0$ and $c_{3} \neq 0$, by swapping the first and third equations in the original system of equations. We have therefore patched the hole in our solution to Problem 11.14 and shown that the system has the unique solution given above even if $c_{1}=0$.

Problem 11.19:
(a) Show that if one row of $\mathbf{A}$ is a constant times another $\operatorname{row}$, then $\operatorname{det}(\mathbf{A})=0$.
(b) If $\operatorname{det}(\mathbf{A})=0$, then must either one row of $\mathbf{A}$ be a constant times another row or one column be a constant times another column?

Solution for Problem 11.19:
(a) If the third row is $k$ times the second row, then we have
$$\left|\begin{array}{ccc}
a_{1} & b_{1} & c_{1} \\
a_{2} & b_{2} & c_{2} \\
k a_{2} & k b_{2} & k c_{2}
\end{array}\right|=a_{1}\left|\begin{array}{cc}
b_{2} & c_{2} \\
k b_{2} & k c_{2}
\end{array}\right|-b_{1}\left|\begin{array}{cc}
a_{2} & c_{2} \\
k a_{2} & k c_{2}
\end{array}\right|+c_{1}\left|\begin{array}{cc}
a_{2} & b_{2} \\
k a_{2} & k b_{2}
\end{array}\right| .$$

402

---

<!-- Page 403 -->

11.3. DETERMINANTS OF $3 \times 3$ MATRICES

In each of the $2 \times 2$ determinants, one row is a constant times the other, so all three of these determinants are 0 , which means that the determinant of the $3 \times 3$ matrix is zero.

If the first row is a constant times the second row, then we can swap the first and third rows and use the proof above to find that the determinant of the resulting matrix is 0 . The swapping of rows only reverses the sign of the determinant, so the original matrix has determinant 0 as well. Similarly, if the first row is a constant times the third row, we can swap the first and second rows and use a proof similar to that above to show that the determinant of the original matrix is 0 .

Important: If one row of a $3 \times 3$ matrix is a constant times another row, or one column of the
(1) matrix is a constant times another column, then the determinant of the matrix is 0 .
(b) No! Here's a counterexample:
$$\left|\begin{array}{lll}
1 & 0 & 2 \\
0 & 1 & 1 \\
1 & 1 & 3
\end{array}\right|=(1)(1)(3)+(0)(1)(1)+(2)(0)(1)-(1)(1)(1)-(0)(0)(3)-(2)(1)(1)=0$$

No row is a constant times another and no column is a constant times another, and yet the determinant is still 0 . We'll learn what's going on here in the next chapter.

Problem 11.20:
(a) Show that $\left|\begin{array}{lll}a_{1} & b_{1} & c_{1} \\ a_{2} & b_{2} & c_{2} \\ a_{3} & b_{3} & c_{3}\end{array}\right|=-a_{2}\left|\begin{array}{ll}b_{1} & c_{1} \\ b_{3} & c_{3}\end{array}\right|+b_{2}\left|\begin{array}{ll}a_{1} & c_{1} \\ a_{3} & c_{3}\end{array}\right|-c_{2}\left|\begin{array}{ll}a_{1} & b_{1} \\ a_{3} & b_{3}\end{array}\right|$.
(b) Show that $\left|\begin{array}{lll}a_{1} & b_{1} & c_{1} \\ a_{2} & b_{2} & c_{2} \\ a_{3} & b_{3} & c_{3}\end{array}\right|=c_{1}\left|\begin{array}{ll}a_{2} & b_{2} \\ a_{3} & b_{3}\end{array}\right|-c_{2}\left|\begin{array}{ll}a_{1} & b_{1} \\ a_{3} & b_{3}\end{array}\right|+c_{3}\left|\begin{array}{ll}a_{1} & b_{1} \\ a_{2} & b_{2}\end{array}\right|$.

Solution for Problem 11.20:
(a) The desired expression on the right side looks a lot like our definition of the determinant, except each term on the right has an entry in the second row times a $2 \times 2$ determinant, rather than an entry in the first row times a $2 \times 2$ determinant. By swapping the first two rows in the $3 \times 3$ matrix, we produce a matrix with determinant -1 times the original matrix. The new matrix has $a_{2}, b_{2}$, and $c_{2}$ in the first row, which gives us the desired right side when we express the determinant with our definition:
$$\begin{aligned}
\left|\begin{array}{lll}
a_{1} & b_{1} & c_{1} \\
a_{2} & b_{2} & c_{2} \\
a_{3} & b_{3} & c_{3}
\end{array}\right|=-\left|\begin{array}{lll}
a_{2} & b_{2} & c_{2} \\
a_{1} & b_{1} & c_{1} \\
a_{3} & b_{3} & c_{3}
\end{array}\right| & =-\left(a_{2}\left|\begin{array}{ll}
b_{1} & c_{1} \\
b_{3} & c_{3}
\end{array}\right|-b_{2}\left|\begin{array}{ll}
a_{1} & c_{1} \\
a_{3} & c_{3}
\end{array}\right|+c_{2}\left|\begin{array}{ll}
a_{1} & b_{1} \\
a_{3} & b_{3}
\end{array}\right|\right) \\
& =-a_{2}\left|\begin{array}{ll}
b_{1} & c_{1} \\
b_{3} & c_{3}
\end{array}\right|+b_{2}\left|\begin{array}{ll}
a_{1} & c_{1} \\
a_{3} & c_{3}
\end{array}\right|-c_{2}\left|\begin{array}{ll}
a_{1} & b_{1} \\
a_{3} & b_{3}
\end{array}\right|
\end{aligned}$$
as desired.
(b) We wrote the expression for a $3 \times 3$ determinant in terms of $2 \times 2$ determinants by selectively factoring out first row terms when writing the expression
$$\left|\begin{array}{lll}
a_{1} & b_{1} & c_{1} \\
a_{2} & b_{2} & c_{2} \\
a_{3} & b_{3} & c_{3}
\end{array}\right|=a_{1}\left(b_{2} c_{3}-c_{2} b_{3}\right)-b_{1}\left(a_{2} c_{3}-c_{2} a_{3}\right)+c_{1}\left(a_{2} b_{3}-b_{2} a_{3}\right)$$

403

---

<!-- Page 404 -->

CHAPTER 11. VECTORS AND MATRICES IN THREE DIMENSIONS, PART 1

If we instead expanded all these products and grouped the resulting terms by the third column entry that appears in each term, we have
$$\begin{aligned}
\left|\begin{array}{lll}
a_{1} & b_{1} & c_{1} \\
a_{2} & b_{2} & c_{2} \\
a_{3} & b_{3} & c_{3}
\end{array}\right| & =a_{1} b_{2} c_{3}-a_{1} c_{2} b_{3}-b_{1} a_{2} c_{3}+b_{1} c_{2} a_{3}+c_{1} a_{2} b_{3}-c_{1} b_{2} a_{3} \\
& =c_{1}\left(a_{2} b_{3}-b_{2} a_{3}\right)-c_{2}\left(a_{1} b_{3}-b_{1} a_{3}\right)+c_{3}\left(a_{1} b_{2}-b_{1} a_{2}\right) \\
& =c_{1}\left|\begin{array}{ll}
a_{2} & b_{2} \\
a_{3} & b_{3}
\end{array}\right|-c_{2}\left|\begin{array}{ll}
a_{1} & b_{1} \\
a_{3} & b_{3}
\end{array}\right|+c_{3}\left|\begin{array}{ll}
a_{1} & b_{1} \\
a_{2} & b_{2}
\end{array}\right| .
\end{aligned}$$
(We could also have solved part (a) similarly, by grouping terms with $a_{2}$, terms with $b_{2}$, and terms with $c_{2}$.)

Our initial definition of the determinant of a $3 \times 3$ matrix and the two equivalent expressions we found in the previous problem are examples of a process called expansion by minors. A minor of a matrix $\mathbf{A}$, denoted as $A_{i j}$, is the determinant of the matrix that remains when row $i$ and column $j$ are omitted from matrix $\mathbf{A}$. So, if
$$\mathbf{A}=\left(\begin{array}{lll}
a_{11} & a_{12} & a_{13} \\
a_{21} & a_{22} & a_{23} \\
a_{31} & a_{32} & a_{33}
\end{array}\right)$$
then we find $A_{12}$ by omitting row 1 and column 2 , and then taking the determinant of the remaining $2 \times 2$ matrix:
$$\left(\begin{array}{lll}
a_{11} & a_{13} \\
a_{21} & a_{22} & a_{23} \\
a_{31} & a_{32} & a_{33}
\end{array}\right) \Rightarrow A_{12}=\left|\begin{array}{ll}
a_{21} & a_{23} \\
a_{31} & a_{33}
\end{array}\right|$$

Similarly, we find $A_{31}$ by omitting row 3 and column 1, and taking the determinant of the remaining $2 \times 2$ matrix:
$$\left(\begin{array}{lll}
a_{1} & a_{12} & a_{13} \\
a_{11} & a_{22} & a_{23} \\
a_{31} & a_{32}
\end{array}\right) \quad \Rightarrow \quad A_{31}=\left|\begin{array}{ll}
a_{12} & a_{13} \\
a_{22} & a_{23}
\end{array}\right|$$

With this notation, we can express our definition of the determinant as follows:
$$\begin{aligned}
\operatorname{det}\left(\begin{array}{lll}
a_{11} & a_{12} & a_{13} \\
a_{21} & a_{22} & a_{23} \\
a_{31} & a_{32} & a_{33}
\end{array}\right) & =a_{11}\left|\begin{array}{ll}
a_{22} & a_{23} \\
a_{32} & a_{33}
\end{array}\right|-a_{12}\left|\begin{array}{ll}
a_{21} & a_{23} \\
a_{31} & a_{33}
\end{array}\right|+a_{13}\left|\begin{array}{ll}
a_{22} & a_{23} \\
a_{32} & a_{33}
\end{array}\right| \\
& =a_{11} A_{11}-a_{12} A_{12}+a_{13} A_{13} .
\end{aligned}$$

Our work in part (a) above shows that we can "expand along the second row," too:
$$\begin{aligned}
\operatorname{det}\left(\begin{array}{lll}
a_{11} & a_{12} & a_{13} \\
a_{21} & a_{22} & a_{23} \\
a_{31} & a_{32} & a_{33}
\end{array}\right) & =-a_{21}\left|\begin{array}{ll}
a_{12} & a_{13} \\
a_{32} & a_{33}
\end{array}\right|+a_{22}\left|\begin{array}{ll}
a_{11} & a_{13} \\
a_{31} & a_{33}
\end{array}\right|-a_{23}\left|\begin{array}{ll}
a_{12} & a_{13} \\
a_{32} & a_{33}
\end{array}\right| \\
& =-a_{21} A_{21}+a_{22} A_{22}-a_{23} A_{23} .
\end{aligned}$$

By "expand along the second row," we mean that each term in our evaluation of the determinant is the product of an entry in the second row, which is $a_{2 j}$ for $j=1,2$, or 3 , and the corresponding minor $A_{2 j}$. As we have seen, sometimes these terms are added and sometimes they are subtracted. There's a pattern to which are added and which are subtracted: we add when the sum of the subscripts of the minor is even, and we subtract when that sum is odd.

404

---

<!-- Page 405 -->

11.3. DETERMINANTS OF $3 \times 3$ MATRICES

Noting that $(-1)^{i+j}$ is -1 if $i+j$ is odd and 1 if $i+j$ is even, we can express the "expansion along the third column" in part (b) as
$$\begin{aligned}
\operatorname{det}\left(\begin{array}{lll}
a_{11} & a_{12} & a_{13} \\
a_{21} & a_{22} & a_{23} \\
a_{31} & a_{32} & a_{33}
\end{array}\right) & =a_{13}\left|\begin{array}{ll}
a_{21} & a_{22} \\
a_{31} & a_{32}
\end{array}\right|-a_{23}\left|\begin{array}{ll}
a_{11} & a_{12} \\
a_{31} & a_{32}
\end{array}\right|+a_{33}\left|\begin{array}{ll}
a_{11} & a_{12} \\
a_{21} & a_{22}
\end{array}\right| \\
& =(-1)^{1+3} a_{13} A_{13}+(-1)^{2+3} a_{23} A_{23}+(-1)^{3+3} a_{33} A_{33}
\end{aligned}$$

That we can expand along any row as described above can be expressed as
$$\operatorname{det}(\mathbf{A})=(-1)^{i+1} a_{i 1} A_{i 1}+(-1)^{i+2} a_{i 2} A_{i 2}+(-1)^{i+3} a_{i 3} A_{i 3}$$
for $i=1,2$, or 3 . (The result for $i=1$ is line (11.5) and the result for $i=2$ is line (11.6).) Similarly, we can express the fact that we can expand along any column in this way as
$$\operatorname{det}(\mathbf{A})=(-1)^{1+j} a_{1 j} A_{1 j}+(-1)^{2+j} a_{2 j} A_{2 j}+(-1)^{3+j} a_{3 j} A_{3 j}$$
for $j=1,2$, or 3 . The result for $j=3$ is line (11.7).

Writing out all six products in the determinant makes it clear why we can expand by minors along any row or column. We start with
$$\left|\begin{array}{lll}
a_{1} & b_{1} & c_{1} \\
a_{2} & b_{2} & c_{2} \\
a_{3} & b_{3} & c_{3}
\end{array}\right|=a_{1} b_{2} c_{3}+b_{1} c_{2} a_{3}+c_{1} a_{2} b_{3}-a_{1} c_{2} b_{3}-b_{1} a_{2} c_{3}-c_{1} b_{2} a_{3},$$
and note that each term is of the form $a_{i} b_{j} c_{k}$, where $i, j, k$ are $1,2,3$ in some order. So, each term has one factor corresponding to each column (the letters) and one factor corresponding to each row (the numbers). We can group by any number to produce an expansion along a row, such as
$$\left|\begin{array}{lll}
a_{1} & b_{1} & c_{1} \\
a_{2} & b_{2} & c_{2} \\
a_{3} & b_{3} & c_{3}
\end{array}\right|=a_{2}\left(b_{3} c_{1}-b_{1} c_{3}\right)+b_{2}\left(a_{1} c_{3}-a_{3} c_{1}\right)+c_{2}\left(a_{3} b_{1}-a_{1} b_{3}\right)=-a_{2}\left|\begin{array}{ll}
b_{1} & c_{1} \\
b_{3} & c_{3}
\end{array}\right|+b_{2}\left|\begin{array}{ll}
a_{1} & c_{1} \\
a_{3} & c_{3}
\end{array}\right|-c_{2}\left|\begin{array}{ll}
a_{1} & b_{1} \\
a_{3} & b_{3}
\end{array}\right|,$$
or we can group by any letter to produce an expansion along a column, as we did in part (b) of Problem 11.20.
Problem 11.21:
(a) How are $\left|\begin{array}{ccc}1 & 3 & 4 \\ 2 & -1 & 2 \\ 5 & 0 & 3\end{array}\right|+\left|\begin{array}{ccc}-3 & 2 & -1 \\ 2 & -1 & 2 \\ 5 & 0 & 3\end{array}\right|$ and $\left|\begin{array}{ccc}-2 & 5 & 3 \\ 2 & -1 & 2 \\ 5 & 0 & 3\end{array}\right|$ related?
(b) Notice that the first row of the final matrix in part (a) is the sum of the first rows of the other two matrices, and that the last two rows of all three matrices are the same. Does the relationship you found in part (a) generalize? That is, must we always have
$$\left|\begin{array}{lll}
a_{1} & b_{1} & c_{1} \\
a_{2} & b_{2} & c_{2} \\
a_{3} & b_{3} & c_{3}
\end{array}\right|+\left|\begin{array}{lll}
a_{1}^{\prime} & b_{1}^{\prime} & c_{1}^{\prime} \\
a_{2} & b_{2} & c_{2} \\
a_{3} & b_{3} & c_{3}
\end{array}\right|=\left|\begin{array}{ccc}
a_{1}+a_{1}^{\prime} & b_{1}+b_{1}^{\prime} & c_{1}+c_{1}^{\prime} \\
a_{2} & b_{2} & c_{2} \\
a_{3} & b_{3} & c_{3}
\end{array}\right| .$$
(c) Must we have $\operatorname{det}(\mathbf{A})+\operatorname{det}(\mathbf{B})=\operatorname{det}(\mathbf{A}+\mathbf{B})$ for any matrices $\mathbf{A}$ and $\mathbf{B}$ ?

405

---

<!-- Page 406 -->

CHAPTER 11. VECTORS AND MATRICES IN THREE DIMENSIONS, PART 1

Solution for Problem 11.21:
(a) We have
$$\begin{aligned}
\left|\begin{array}{ccc}
1 & 3 & 4 \\
2 & -1 & 2 \\
5 & 0 & 3
\end{array}\right| & =(1)(-1)(3)+(3)(2)(5)+(4)(2)(0)-(1)(2)(0)-(3)(2)(3)-(4)(-1)(5)=29 \\
\left|\begin{array}{ccc}
-3 & 2 & -1 \\
2 & -1 & 2 \\
5 & 0 & 3
\end{array}\right| & =(-3)(-1)(3)+(2)(2)(5)+(-1)(2)(0)-(-3)(2)(0)-(2)(2)(3)-(-1)(-1)(5)=12 \\
\left|\begin{array}{ccc}
-2 & 5 & 3 \\
2 & -1 & 2 \\
5 & 0 & 3
\end{array}\right| & =(-2)(-1)(3)+(5)(2)(5)+(3)(2)(0)-(-2)(2)(0)-(5)(2)(3)-(3)(-1)(5)=41
\end{aligned}$$
and we see that the sum of the first two equals the third.
(b) Expanding each determinant in the sum along the first row gives:
$$\begin{aligned}
\left|\begin{array}{lll}
a_{1} & b_{1} & c_{1} \\
a_{2} & b_{2} & c_{2} \\
a_{3} & b_{3} & c_{3}
\end{array}\right|+\left|\begin{array}{lll}
a_{1}^{\prime} & b_{1}^{\prime} & c_{1}^{\prime} \\
a_{2} & b_{2} & c_{2} \\
a_{3} & b_{3} & c_{3}
\end{array}\right| & =a_{1}\left|\begin{array}{ll}
b_{2} & c_{2} \\
b_{3} & c_{3}
\end{array}\right|-b_{1}\left|\begin{array}{ll}
a_{2} & c_{2} \\
a_{3} & c_{3}
\end{array}\right|+c_{1}\left|\begin{array}{ll}
a_{2} & b_{2} \\
a_{3} & b_{3}
\end{array}\right| \\
& +a_{1}^{\prime}\left|\begin{array}{ll}
b_{2} & c_{2} \\
b_{3} & c_{3}
\end{array}\right|-b_{1}^{\prime}\left|\begin{array}{ll}
a_{2} & c_{2} \\
a_{3} & c_{3}
\end{array}\right|+c_{1}^{\prime}\left|\begin{array}{ll}
a_{2} & b_{2} \\
a_{3} & b_{3}
\end{array}\right| \\
& =\left(a_{1}+a_{1}^{\prime}\right)\left|\begin{array}{ll}
b_{2} & c_{2} \\
b_{3} & c_{3}
\end{array}\right|-\left(b_{1}+b_{1}^{\prime}\right)\left|\begin{array}{ll}
a_{2} & c_{2} \\
a_{3} & c_{3}
\end{array}\right|+\left(c_{1}+c_{1}^{\prime}\right)\left|\begin{array}{ll}
a_{2} & b_{2} \\
a_{3} & b_{3}
\end{array}\right| \\
& =\left|\begin{array}{ccc}
a_{1}+a_{1}^{\prime} & b_{1}+b_{1}^{\prime} & c_{1}+c_{1}^{\prime} \\
a_{2} & b_{2} & c_{2} \\
a_{3} & b_{3} & c_{3}
\end{array}\right| .
\end{aligned}$$

There's nothing special about the first row. For example, suppose two matrices have the same first and third rows. The sum of the determinants of these matrices equals the determinant of the matrix with those same first and third rows and with second row equal to the sum of the second rows of the original two matrices:
$$\left|\begin{array}{lll}
a_{1} & b_{1} & c_{1} \\
a_{2} & b_{2} & c_{2} \\
a_{3} & b_{3} & c_{3}
\end{array}\right|+\left|\begin{array}{lll}
a_{1} & b_{1} & c_{1} \\
a_{2}^{\prime} & b_{2}^{\prime} & c_{2}^{\prime} \\
a_{3} & b_{3} & c_{3}
\end{array}\right|=\left|\begin{array}{ccc}
a_{1} & b_{1} & c_{1} \\
a_{2}+a_{2}^{\prime} & b_{2}+b_{2}^{\prime} & c_{2}+c_{2}^{\prime} \\
a_{3} & b_{3} & c_{3}
\end{array}\right|$$

There's nothing special about rows, either. If two columns in one matrix are the same as the corresponding two columns in the other, then the sum of the determinants of these matrices equals the determinant of the matrix with those same two corresponding columns and with the other column equal to the sum of the two differing columns in the original two matrices. For example, we have
$$\left|\begin{array}{lll}
a_{1} & b_{1} & c_{1} \\
a_{2} & b_{2} & c_{2} \\
a_{3} & b_{3} & c_{3}
\end{array}\right|+\left|\begin{array}{lll}
a_{1} & b_{1} & c_{1}^{\prime} \\
a_{2} & b_{2} & c_{2}^{\prime} \\
a_{3} & b_{3} & c_{3}^{\prime}
\end{array}\right|=\left|\begin{array}{lll}
a_{1} & b_{1} & c_{1}+c_{1}^{\prime} \\
a_{2} & b_{2} & c_{2}+c_{2}^{\prime} \\
a_{3} & b_{3} & c_{3}+c_{3}^{\prime}
\end{array}\right|$$
(c) No. We can find a counterexample quickly by letting $\mathbf{A}=\mathbf{B}=\mathbf{I}$. Then, we have $\operatorname{det}(\mathbf{A})=\operatorname{det}(\mathbf{B})=\operatorname{det}(\mathbf{I})=1$, so $\operatorname{det}(\mathbf{A})+\operatorname{det}(\mathbf{B})=2$, but
$$\operatorname{det}(\mathbf{A}+\mathbf{B})=\left|\begin{array}{lll}
2 & 0 & 0 \\
0 & 2 & 0 \\
0 & 0 & 2
\end{array}\right|=2^{3}=8$$

So, $\operatorname{det}(\mathbf{A})+\operatorname{det}(\mathbf{B})$ and $\operatorname{det}(\mathbf{A}+\mathbf{B})$ are not necessarily the same.

406

---

<!-- Page 407 -->

11.3. DETERMINANTS OF $3 \times 3$ MATRICES

With a great deal of perseverance, we can show that $\operatorname{det}(\mathbf{A}) \operatorname{det}(\mathbf{B})=\operatorname{det}(\mathbf{A B})$ for any two $3 \times 3$ matrices $\mathbf{A}$ and $\mathbf{B}$.
Problem 11.22: Let $\mathbf{A}=\left(\begin{array}{ccc}1 & 3 & 5 \\ -1 & 4 & 2 \\ -3 & 0 & 6\end{array}\right)$ and let $\mathbf{B}=\left(\begin{array}{ccc}1 & 3 & 5 \\ 2 & 13 & 17 \\ -3 & 0 & 6\end{array}\right)$, where $\mathbf{B}$ is the matrix formed by adding 3 times the first row of $\mathbf{A}$ to the second row of $\mathbf{A}$ and leaving the other two rows unchanged. How are $\operatorname{det}(\mathbf{A})$ and $\operatorname{det}(\mathbf{B})$ related? Can you generalize this observation?

Solution for Problem 11.22: We have
$$\operatorname{det}(A)=(1)(4)(6)+(3)(2)(-3)+(5)(-1)(0)-(1)(2)(0)-(3)(-1)(6)-(5)(4)(-3)=84$$
and
$$\operatorname{det}(\mathbf{B})=(1)(13)(6)+(3)(17)(-3)+(5)(2)(0)-(1)(17)(0)-(3)(2)(6)-(5)(13)(-3)=84,$$
so $\operatorname{det}(\mathbf{A})=\operatorname{det}(\mathbf{B})$.
There doesn't appear to be anything special about A or B. So we suspect that, in general, if we add a constant times one row to another row of a matrix, then the resulting matrix will have the same determinant as the original matrix.

Rather than starting from the definition of the determinant to generalize this observation, we instead combine properties of the determinant that we discovered in earlier problems. Suppose that $\mathbf{T}$ is formed by adding $k$ times the first row of $\mathbf{M}$ to the second row of $\mathbf{M}$. From the property we discovered in Problem 11.21, we can write $\operatorname{det}(\mathbf{T})$ as:
$$\operatorname{det}(\mathbf{T})=\left|\begin{array}{ccc}
m_{11} & m_{12} & m_{13} \\
m_{21}+k m_{11} & m_{22}+k m_{12} & m_{23}+k m_{13} \\
m_{31} & m_{32} & m_{33}
\end{array}\right|=\left|\begin{array}{lll}
m_{11} & m_{12} & m_{13} \\
m_{21} & m_{22} & m_{23} \\
m_{31} & m_{32} & m_{33}
\end{array}\right|+\left|\begin{array}{ccc}
m_{11} & m_{12} & m_{13} \\
k m_{11} & k m_{12} & k m_{13} \\
m_{31} & m_{32} & m_{33}
\end{array}\right| .$$

The first determinant on the right end is just $\operatorname{det}(\mathbf{M})$. The second is the determinant of a matrix in which one row is a constant times another. We showed in Problem 11.19 that the determinant of such a matrix is 0 , so we have $\operatorname{det}(\mathbf{T})=\operatorname{det}(\mathbf{M})$.

By working through essentially the same steps as we did above, we can show the following:

\begin{tabular}{|l|}
\hline Important: \\
times any row of $\mathbf{M}$ to another row of $\mathbf{M}$ equals $\operatorname{det}(\mathbf{M})$. Similarly, the deter- \\
minant of a matrix formed when we add a constant times any column of $\mathbf{M}$ to \\
another column of $\mathbf{M}$ equals $\operatorname{det}(\mathbf{M})$.
\end{tabular}

We usually have to grind out a bunch of multiplications to evaluate the determinant of a $3 \times 3$ matrix, which is why we typically use a computer to evaluate them. But sometimes we can use the properties we have discovered in this section to evaluate a determinant pretty quickly.

407

---

<!-- Page 408 -->

CHAPTER 11. VECTORS AND MATRICES IN THREE DIMENSIONS, PART 1

Problem 11.23: Evaluate each of the following:
(a) $\left|\begin{array}{ccc}13 & -26 & 39 \\ 8 & 32 & -23 \\ 4 & 16 & -12\end{array}\right|$
(b) $\left|\begin{array}{ccc}2009 & 10050 & -2010 \\ 328 & 1640 & -328 \\ -602 & -2990 & 598\end{array}\right|$

Solution for Problem 11.23:
(a) Having 0s in a matrix makes finding its determinant easier since some of the products in the expression for the determinant will be 0 . So, we subtract twice the third row from the second. We also can factor 13 out of the first row and 4 out of the last row, so we have:
$$\begin{aligned}
\left|\begin{array}{ccc}
13 & -26 & 39 \\
8 & 32 & -23 \\
4 & 16 & -12
\end{array}\right| & =\left|\begin{array}{ccc}
13 & -26 & 39 \\
0 & 0 & 1 \\
4 & 16 & -12
\end{array}\right|=13\left|\begin{array}{ccc}
1 & -2 & 3 \\
0 & 0 & 1 \\
4 & 16 & -12
\end{array}\right|=13 \cdot 4\left|\begin{array}{ccc}
1 & -2 & 3 \\
0 & 0 & 1 \\
1 & 4 & -3
\end{array}\right| \\
& =52((-2)(1)(1)-(1)(1)(4))=-312 .
\end{aligned}$$
(b) We factor 10 out of the second column, and add the first column to the third to give us a 0 . This gives
$$\left|\begin{array}{ccc}
2009 & 10050 & -2010 \\
328 & 1640 & -328 \\
-602 & -2990 & 598
\end{array}\right|=10\left|\begin{array}{ccc}
2009 & 1005 & -2010 \\
328 & 164 & -328 \\
-602 & -299 & 598
\end{array}\right|=10\left|\begin{array}{ccc}
2009 & 1005 & -1 \\
328 & 164 & 0 \\
-602 & -299 & -4
\end{array}\right| .$$

Subtracting twice the middle column from the first will give us another 0 :
$$10\left|\begin{array}{ccc}
2009 & 1005 & -1 \\
328 & 164 & 0 \\
-602 & -299 & -4
\end{array}\right|=10\left|\begin{array}{ccc}
-1 & 1005 & -1 \\
0 & 164 & 0 \\
-4 & -299 & -4
\end{array}\right| .$$

Aha! The first and last columns are the same, so the determinant equals 0 .

Exercises
11.3.1 Compute the following two determinants:
(a) $\left|\begin{array}{ccc}1 & 5 & 0 \\ -3 & -2 & 6 \\ -1 & 7 & -3\end{array}\right|$
(b) $\left|\begin{array}{ccc}-3 & 4 & 0.5 \\ 0.25 & -6 & -1 \\ 0 & 8 & 2\end{array}\right|$
11.3.2 Show that $(\mathbf{A}+\mathbf{B})^{T}=\mathbf{A}^{T}+\mathbf{B}^{T}$.
11.3.3 Show that if $\mathbf{A}$ and $\mathbf{B}$ have the same second and third columns, then $\operatorname{det}(\mathbf{A})+\operatorname{det}(\mathbf{B})=\operatorname{det}(\mathbf{A}+\mathbf{B})$.
11.3.4 Evaluate $\left|\begin{array}{ccc}30 & 51 & 20 \\ 15 & 24 & 10 \\ -46 & 28 & -29\end{array}\right|$ without a calculator or computer.
11.3.5 An upper triangular matrix is a matrix for which all the entries below the main diagonal are 0 . That is, it is a matrix of the form
$$\left(\begin{array}{ccc}
a_{11} & a_{12} & a_{13} \\
0 & a_{22} & a_{23} \\
0 & 0 & a_{33}
\end{array}\right) .$$

What is the determinant of such a matrix?

408

---

<!-- Page 409 -->

11.4. MORE THAN JUST $2 \times 2$ AND $3 \times 3$
11.4 More Than Just $2 \times 2$ and $3 \times 3$

We introduced $2 \times 2$ and $3 \times 3$ matrices with systems of equations in which the number of variables equals the number of equations. But what if the number of equations does not equal the number of variables? For example, can we use matrices and vectors to express this system:
$$\begin{array}{l}
w-3 x+5 y-2 z=a \\
-2 w+x-y+5 z=b ?
\end{array}$$

Yes, we can:
$$\left(\begin{array}{cccc}
1 & -3 & 5 & -2 \\
-2 & 1 & -1 & 5
\end{array}\right)\left(\begin{array}{c}
w \\
x \\
y \\
z
\end{array}\right)=\binom{a}{b} .$$

On the left side, we have a couple of mathematical objects we haven't seen before, a matrix with 2 rows and 4 columns, which we call a $2 \times 4$ matrix, and a vector with 4 components. The product of the $2 \times 4$ matrix and the vector in 4 dimensions gives us a vector in 2 dimensions. In other words, the $2 \times 4$ matrix represents a linear function that maps a vector in 4 dimensions to a vector in 2 dimensions.

In general, we can make a matrix with any positive integer number of rows and any positive integer number of columns, and a vector can have any positive integer number of components. In fact, the vectors we have studied so far can be viewed as a matrix with only one column. We call such a vector a column vector, and a matrix with only one row can be considered a row vector. So, for example, each of the $c$ columns of an $r \times c$ matrix (a matrix with $r$ rows and $c$ columns) is itself a vector with $r$ components, while each of the $r$ rows is a vector with $c$ components.

Collectively, we call the number of rows and the number of columns of a matrix the dimensions of matrix. We read the dimensions $r \times c$ as " $r$ by $c^{\prime \prime}$.

As we have seen, we can use the product of an $r \times c$ matrix and a vector with $c$ components to represent the expressions on one side of a system of $r$ linear equations with $c$ variables. In general, we define the product of an $r \times c$ matrix and a vector in $c$ dimensions analogously to how we defined the product of a $2 \times 2$ matrix and a vector in 2 dimensions:
$$\left(\begin{array}{ccccc}
m_{11} & m_{12} & m_{13} & \cdots & m_{1 c} \\
m_{21} & m_{22} & m_{23} & \cdots & m_{2 c} \\
\vdots & \vdots & \vdots & \ddots & \vdots \\
m_{r 1} & m_{r 2} & m_{r 3} & \cdots & m_{r c}
\end{array}\right)\left(\begin{array}{c}
v_{1} \\
v_{2} \\
v_{3} \\
\vdots \\
v_{c}
\end{array}\right)=\left(\begin{array}{c}
m_{11} v_{1}+m_{12} v_{2}+m_{13} v_{3}+\cdots+m_{1 c} v_{c} \\
m_{21} v_{1}+m_{22} v_{2}+m_{23} v_{3}+\cdots+m_{2 c} v_{c} \\
m_{31} v_{1}+m_{32} v_{2}+m_{33} v_{3}+\cdots+m_{3 c} v_{c} \\
\vdots \\
m_{r 1} v_{1}+m_{r 2} v_{2}+m_{r 3} v_{3}+\cdots+m_{r c} v_{c}
\end{array}\right) .$$

Note again that the product of an $r \times c$ matrix and vector in $c$ dimensions is a vector in $r$ dimensions. So, an $r \times c$ matrix represents a linear function that maps a vector in $c$ dimensions to a vector in $r$ dimensions.

We define the addition of two vectors in $n$ dimensions and scalar multiplication of vectors in $n$ dimensions just as we did in 2 and 3 dimensions:
$$\mathbf{v}+\mathbf{w}=\left(\begin{array}{c}
v_{1} \\
v_{2} \\
\vdots \\
v_{n}
\end{array}\right)+\left(\begin{array}{c}
w_{1} \\
w_{2} \\
\vdots \\
w_{n}
\end{array}\right)=\left(\begin{array}{c}
v_{1}+w_{1} \\
v_{2}+w_{2} \\
\vdots \\
v_{n}+w_{n}
\end{array}\right), \quad k \mathbf{v}=k\left(\begin{array}{c}
v_{1} \\
v_{2} \\
\vdots \\
v_{n}
\end{array}\right)=\left(\begin{array}{c}
k v_{1} \\
k v_{2} \\
\vdots \\
k v_{n}
\end{array}\right) .$$

409

---

<!-- Page 410 -->

CHAPTER 11. VECTORS AND MATRICES IN THREE DIMENSIONS, PART 1

Note that we cannot add two vectors that have differing numbers of components.
The dot product and the norm of vectors in $n$ dimensions are defined just as they are in 2 and 3 dimensions:

\begin{tabular}{|l|l|}
\hline Important: (1) & For any vectors $\mathbf{v}$ and $\mathbf{w}$ in $n$ dimensions, we have
$$\begin{aligned}
\mathbf{v} \cdot \mathbf{w} & =v_{1} w_{1}+v_{2} w_{2}+\cdots+v_{n} w_{n} \\
\|\mathbf{v}\| & =\sqrt{v_{1}^{2}+v_{2}^{2}+\cdots+v_{n}^{2}}
\end{aligned}$$ \\
\hline
\end{tabular}

Problems

Problem 11.24: In this problem, we explore matrix addition.
(a) We can define the sum of two vectors only if the two vectors have the same number of components. Show that $\mathbf{A v}+\mathbf{B v}$ is defined if and only if $\mathbf{A}$ and $\mathbf{B}$ have the same dimensions.
(b) Let $\mathbf{A}$ and $\mathbf{B}$ be $r \times c$ matrices. We'd like to define the matrix sum $\mathbf{A}+\mathbf{B}$ such that $(\mathbf{A}+\mathbf{B}) \mathbf{v}=\mathbf{A v}+\mathbf{B v}$ for all $\mathbf{v}$. Show that such a matrix $\mathbf{A}+\mathbf{B}$ exists and explain how to compute it.

Problem 11.25: We define the matrix $k \mathbf{B}$ such that $(k \mathbf{B}) \mathbf{v}=k(\mathbf{B} \mathbf{v})$ for all $\mathbf{v}$. Show that each entry in $k \mathbf{B}$ is $k$ times the corresponding entry in $\mathbf{B}$.

Problem 11.26: Let $\mathbf{A}$ be an $r \times s$ matrix and $\mathbf{B}$ be a $q \times c$ matrix. Suppose there are vectors $\mathbf{v}$ and $\mathbf{w}$ such that $\mathbf{v}=\mathbf{A}(\mathbf{B} \mathbf{w})$.
(a) How many components must $w$ have?
(b) Show that $s=q$.
(c) How many components must $\mathbf{v}$ have?

Problem 11.27: We define the product of an $r \times s$ matrix $\mathbf{A}$ and an $s \times c$ matrix $\mathbf{B}$ to be the matrix $\mathbf{A B}$ such that $(\mathbf{A B}) \mathbf{v}=\mathbf{A}(\mathbf{B v})$ for every vector $\mathbf{v}$ in $c$ dimensions.
(a) What are the dimensions of the matrix that equals $\mathbf{A B}$ ?
(b) We have seen that if $\mathbf{M}$ and $\mathbf{N}$ are $3 \times 3$ matrices, then the entry in row $i$ and column $j$ of the product $\mathbf{M N}$ is the dot product of row $i$ of $\mathbf{M}$ and column $j$ of $\mathbf{N}$. Can we use the same process to find the product $\mathbf{A B}$ ?

Problem 11.28: Compute the following products:
(a)
$$\left(\begin{array}{ccc}
5 & -1 & 0 \\
-3 & 8 & -2
\end{array}\right)\left(\begin{array}{ccc}
4 & -3 & 8 \\
5 & -1 & 0 \\
-2 & -2 & 8
\end{array}\right)$$
(b) $\left(\begin{array}{cc}4 & 8 \\ -1 & 3 \\ 0 & 8 \\ -1 & -1\end{array}\right)\left(\begin{array}{ccc}6 & -2 & -3 \\ -1 & -7 & 4\end{array}\right)$

Problem 11.24: In this problem, we explore matrix addition.
(a) We can define the sum of two vectors only if the two vectors have the same number of components. Show that $\mathbf{A v}+\mathbf{B v}$ is defined if and only if $\mathbf{A}$ and $\mathbf{B}$ have the same dimensions.
(b) Let $\mathbf{A}$ and $\mathbf{B}$ be $r \times c$ matrices. We'd like to define the matrix sum $\mathbf{A}+\mathbf{B}$ such that $(\mathbf{A}+\mathbf{B}) \mathbf{v}=\mathbf{A v}+\mathbf{B v}$ for all $\mathbf{v}$. Show that such a matrix $\mathbf{A}+\mathbf{B}$ exists and explain how to compute it.

410

---

<!-- Page 411 -->

11.4. MORE THAN JUST $2 \times 2$ AND $3 \times 3$

Solution for Problem 11.24:
(a) Suppose that $\mathbf{v}$ has $c$ components. In order to be able to define the product $\mathbf{A v}$, the matrix $\mathbf{A}$ must have $c$ columns. Similarly, B must have $c$ columns.

Next, let $\mathbf{A}$ have $r$ rows, so the product $\mathbf{A v}$ is a vector with $r$ components. In order to be able to perform the vector addition $\mathbf{A v}+\mathbf{B v}$, the vectors $\mathbf{A v}$ and $\mathbf{B v}$ must have the same number of components. Therefore, Bv must have $r$ components, which means that B must have $r$ rows. Therefore, B must be an $r \times c$ matrix, just like A.
(b) Since we have
$$\begin{aligned}
\mathbf{A v}+\mathbf{B} \mathbf{v} & =\left(\begin{array}{ccccc}
a_{11} & a_{12} & a_{13} & \cdots & a_{1 c} \\
a_{21} & a_{22} & a_{23} & \cdots & a_{2 c} \\
\vdots & \vdots & \vdots & \ddots & \vdots \\
a_{r 1} & a_{r 2} & a_{r 3} & \cdots & a_{r c}
\end{array}\right)\left(\begin{array}{c}
v_{1} \\
v_{2} \\
v_{3} \\
\vdots \\
v_{c}
\end{array}\right)+\left(\begin{array}{ccccc}
b_{11} & b_{12} & b_{13} & \cdots & b_{1 c} \\
b_{21} & b_{22} & b_{23} & \cdots & b_{2 c} \\
\vdots & \vdots & \vdots & \ddots & \vdots \\
b_{r 1} & b_{r 2} & b_{r 3} & \cdots & b_{r c}
\end{array}\right)\left(\begin{array}{c}
v_{1} \\
v_{2} \\
v_{3} \\
\vdots \\
v_{c}
\end{array}\right) \\
& =\left(\begin{array}{c}
a_{11} v_{1}+a_{12} v_{2}+a_{13} v_{3}+\cdots+a_{1 c} v_{c} \\
a_{21} v_{1}+a_{22} v_{2}+a_{23} v_{3}+\cdots+a_{2 c} v_{c} \\
\vdots \\
a_{r 1} v_{1}+a_{r 2} v_{2}+a_{r 3} v_{3}+\cdots+a_{r c} v_{c}
\end{array}\right)+\left(\begin{array}{c}
b_{11} v_{1}+b_{12} v_{2}+b_{13} v_{3}+\cdots+b_{1 c} v_{c} \\
b_{21} v_{1}+b_{22} v_{2}+b_{23} v_{3}+\cdots+b_{2 c} v_{c} \\
\vdots \\
b_{r 1} v_{1}+b_{r 2} v_{2}+b_{r 3} v_{3}+\cdots+b_{r c} v_{c}
\end{array}\right) \\
& =\left(\begin{array}{c}
\left(a_{11}+b_{11}\right) v_{1}+\left(a_{12}+b_{12}\right) v_{2}+\left(a_{13}+b_{13}\right) v_{3}+\cdots+\left(a_{1 c}+b_{1 c}\right) v_{c} \\
\left(a_{21}+b_{21}\right) v_{1}+\left(a_{22}+b_{22}\right) v_{2}+\left(a_{23}+b_{23}\right) v_{3}+\cdots+\left(a_{2 c}+b_{2 c}\right) v_{c} \\
\vdots \\
\left(a_{r 1}+b_{r 1}\right) v_{1}+\left(a_{r 2}+b_{r 2}\right) v_{2}+\left(a_{r 3}+b_{r 3}\right) v_{3}+\cdots+\left(a_{r c}+b_{r c}\right) v_{c}
\end{array}\right) \\
& =\left(\begin{array}{cccc}
a_{11}+b_{11} & a_{12}+b_{12} & a_{13}+b_{13} & \cdots \\
a_{21}+b_{21}+b_{1 c} \\
\vdots & a_{22}+b_{22} & a_{23}+b_{23} & \cdots \\
\vdots & \vdots & \ddots & a_{2 c}+b_{2 c} \\
\vdots & \vdots & \vdots \\
a_{r 1}+b_{r 1} & a_{r 2}+b_{r 2} & a_{r 3}+b_{r 3} & \cdots \\
a_{r c}+b_{r c}
\end{array}\right)\left(\begin{array}{c}
v_{1} \\
v_{2} \\
v_{3} \\
\vdots \\
v_{c}
\end{array}\right),
\end{aligned}$$
we can define the matrix $\operatorname{sum} \mathbf{A}+\mathbf{B}$ as
$$\mathbf{A}+\mathbf{B}=\left(\begin{array}{ccccc}
a_{11}+b_{11} & a_{12}+b_{12} & a_{13}+b_{13} & \cdots & a_{1 c}+b_{1 c} \\
a_{21}+b_{21} & a_{22}+b_{22} & a_{23}+b_{23} & \cdots & a_{2 c}+b_{2 c} \\
\vdots & \vdots & \vdots & \ddots & \vdots \\
a_{r 1}+b_{r 1} & a_{r 2}+b_{r 2} & a_{r 3}+b_{r 3} & \cdots & a_{r c}+b_{r c}
\end{array}\right) .$$

Important: Two matrices can be added if and only if they have the same dimensions. Each
entry in the sum is the sum of the corresponding entries in the two matrices.
So, addition works in the "obvious" way. How about multiplication of a matrix by a scalar?
Problem 11.25: We define the matrix equal to $k \mathbf{B}$ such that $(k \mathbf{B}) \mathbf{v}=k(\mathbf{B v})$ for all $\mathbf{v}$. Show that each entry in $k \mathbf{B}$ is $k$ times the corresponding entry in $\mathbf{B}$.

411

---

<!-- Page 412 -->

CHAPTER 11. VECTORS AND MATRICES IN THREE DIMENSIONS, PART 1

Solution for Problem 11.25: We have
$$\begin{aligned}
(k \mathbf{B}) \mathbf{v}=k(\mathbf{B v})=k\left(\left(\begin{array}{ccccc}
b_{11} & b_{12} & b_{13} & \cdots & b_{1 c} \\
\vdots & \vdots & \vdots & \ddots & \vdots \\
b_{r 1} & b_{r 2} & b_{r 3} & \cdots & b_{r c}
\end{array}\right)\left(\begin{array}{c}
v_{1} \\
v_{2} \\
\vdots \\
v_{c}
\end{array}\right)\right) & =k\left(\begin{array}{c}
b_{11} v_{1}+b_{12} v_{2}+b_{13} v_{3}+\cdots+b_{1 c} v_{c} \\
\vdots \\
b_{r 1} v_{1}+b_{r 2} v_{2}+b_{r 3} v_{3}+\cdots+b_{r c} v_{c}
\end{array}\right) \\
& =\left(\begin{array}{c}
k b_{11} v_{1}+k b_{12} v_{2}+k b_{13} v_{3}+\cdots+k b_{1 c} v_{c} \\
\vdots \\
k b_{r 1} v_{1}+k b_{r 2} v_{2}+k b_{r 3} v_{3}+\cdots+k b_{r c} v_{c}
\end{array}\right) \\
& =\left(\begin{array}{ccccc}
k b_{11} & k b_{12} & k b_{13} & \cdots & k b_{1 c} \\
\vdots & \vdots & \vdots & \ddots & \vdots \\
k b_{r 1} & k b_{r 2} & k b_{r 3} & \cdots & k b_{r c}
\end{array}\right)\left(\begin{array}{c}
v_{1} \\
v_{2} \\
\vdots \\
v_{c}
\end{array}\right) \\
& =\left(\begin{array}{ccccc}
k b_{11} & k b_{12} & k b_{13} & \cdots & k b_{1 c} \\
\vdots & \vdots & \vdots & \ddots & \vdots \\
k b_{r 1} & k b_{r 2} & k b_{r 3} & \cdots & k b_{r c}
\end{array}\right) \mathbf{v} .
\end{aligned}$$

So, each entry in $k \mathbf{B}$ is $k$ times the corresponding entry in $\mathbf{B}$.

Important: We multiply a matrix by a scalar by multiplying each entry in the matrix by the scalar.

So, addition of two $r \times c$ matrices works in the expected way, as does multiplication of any matrix by a scalar. In the following series of problems, we explore general matrix multiplication.

Problem 11.26: Let $\mathbf{A}$ be an $r \times s$ matrix and $\mathbf{B}$ be a $q \times c$ matrix. Suppose there are vectors $\mathbf{v}$ and $\mathbf{w}$ such that $\mathbf{v}=\mathbf{A}(\mathbf{B} \mathbf{w})$.
(a) How many components must $\mathbf{w}$ have?
(b) Show that $s=q$.
(c) How many components must $\mathbf{v}$ have?

Solution for Problem 11.26:
(a) The product Bw is defined if and only if the number of columns in B equals the number of components in w, so w must have $c$ components.
(b) Because $\mathbf{B}$ is a $q \times c$ matrix, the product $\mathbf{B w}$ must be a vector in $q$ dimensions. The product $\mathbf{A}(\mathbf{B w})$ is defined if and only if the number of columns in $\mathbf{A}$ matches the number of components in the vector $\mathbf{B w}$. Therefore, we must have $s=q$.
(c) As explained in part (b), the vector $\mathbf{B w}$ is a vector in $s$ dimensions. Since $\mathbf{A}$ is an $r \times s$ matrix, it maps vectors in $s$ dimensions to vectors in $r$ dimensions. Therefore, the product $\mathbf{A}(\mathbf{B w})$ is a vector with $r$ components.

As an example, suppose $\mathbf{A}$ is a $4 \times 2$ matrix and $\mathbf{B}$ is a $2 \times 3$ matrix. If vectors $\mathbf{v}$ and $\mathbf{w}$ satisfy $\dot{\mathbf{v}}=\mathbf{A}(\mathbf{B w})$, then

412

---

<!-- Page 413 -->

11.4. MORE THAN JUST $2 \times 2$ AND $3 \times 3$

$\mathbf{v}$ has 4 components and $\mathbf{w}$ has 3 components, and the equation $\mathbf{v}=\mathbf{A}(\mathbf{B w})$ looks like:
$$\left(\begin{array}{l}
v_{1} \\
v_{2} \\
v_{3} \\
v_{4}
\end{array}\right)=\left(\begin{array}{ll}
a_{11} & a_{12} \\
a_{21} & a_{22} \\
a_{31} & a_{32} \\
a_{41} & a_{42}
\end{array}\right)\left(\left(\begin{array}{lll}
b_{11} & b_{12} & b_{13} \\
b_{21} & b_{22} & b_{23}
\end{array}\right)\left(\begin{array}{l}
w_{1} \\
w_{2} \\
w_{3}
\end{array}\right)\right) .$$

Problem 11.27: We define the product of an $r \times s$ matrix $\mathbf{A}$ and an $s \times c$ matrix $\mathbf{B}$ to be the matrix $\mathbf{A B}$ such that $(\mathbf{A B}) \mathbf{v}=\mathbf{A}(\mathbf{B v})$ for every vector $\mathbf{v}$ in $c$ dimensions.
(a) What are the dimensions of the matrix that equals $\mathbf{A B}$ ?
(b) We have seen that if $\mathbf{M}$ and $\mathbf{N}$ are $3 \times 3$ matrices, then the entry in row $i$ and column $j$ of the product $\mathbf{M} \mathbf{N}$ is the dot product of row $i$ of $\mathbf{M}$ and column $j$ of $\mathbf{N}$. Can we use the same process to find the product AB ?

Solution for Problem 11.27:
(a) Let $\mathbf{T}=\mathbf{A B}$. The product Tv is defined only if the number of columns in $\mathbf{T}$ equals the number of components of $\mathbf{v}$. Therefore, $\mathbf{T}$ has $c$ columns.

The number of components in the product $\mathbf{T v}$ is the number of rows in $\mathbf{T}$. Since $\mathbf{T v}=\mathbf{A}(\mathbf{B v})$, the number of rows in $\mathbf{T}$ equals the number of components in $\mathbf{A}(\mathbf{B v})$. The matrix $\mathbf{A}$ maps vectors in $s$ dimensions to vectors in $r$ dimensions, so the result of $\mathbf{A}(\mathbf{B v})$ is a vector in $r$ dimensions. Therefore, $\mathbf{T}$ has $r$ rows, which means $\mathbf{T}$ is an $r \times c$ matrix.
(b) We discover how to multiply two matrices (when such a product is defined) in the same way we discovered the process for multiplying two $3 \times 3$ matrices. Suppose $\mathbf{A}$ is a $r \times s$ matrix and $\mathbf{B}$ is a $s \times c$ matrix and that $(\mathbf{A B}) \mathbf{v}=\mathbf{A}(\mathbf{B v})$ for all vectors $\mathbf{v}$ in $c$ dimensions. Let the rows of $\mathbf{A}$ be $\mathbf{a}_{1}, \mathbf{a}_{2}, \ldots, \mathbf{a}_{r}$ and the columns of $\mathbf{B}$ be $\mathbf{b}_{1}, \mathbf{b}_{2}, \ldots, \mathbf{b}_{c}$. Then, we have
$$\begin{aligned}
(\mathbf{A B}) \mathbf{v}=\mathbf{A}(\mathbf{B v})=\mathbf{A}\left(\left(\begin{array}{cccc}
\mid & \mid & & \mid \\
\mathbf{b}_{1} & \mathbf{b}_{2} & \cdots & \mathbf{b}_{c} \\
\mid & \mid & & \mid
\end{array}\right)\left(\begin{array}{c}
v_{1} \\
v_{2} \\
\vdots \\
v_{c}
\end{array}\right)\right) & =\mathbf{A}\left(\begin{array}{c}
b_{11} v_{1}+b_{12} v_{2}+b_{13} v_{3}+\cdots+b_{1 c} v_{c} \\
b_{21} v_{1}+b_{22} v_{2}+b_{23} v_{3}+\cdots+b_{2 c} v_{c} \\
\vdots \\
b_{r 1} v_{1}+b_{r 2} v_{2}+b_{r 3} v_{3}+\cdots+b_{r c} v_{c}
\end{array}\right) \\
& =\mathbf{A}\left(v_{1} \mathbf{b}_{1}+v_{2} \mathbf{b}_{2}+\cdots+v_{c} \mathbf{b}_{c}\right) \\
& =v_{1} \mathbf{A b}_{1}+v_{2} \mathbf{A b}_{2}+\cdots+v_{c} \mathbf{A} \mathbf{b}_{c} \\
& =\left(\begin{array}{ccc}
\mid & \mid & \mid \\
\mathbf{A b}_{1} & \mathbf{A} \mathbf{b}_{2} & \cdots \\
\mid & \mathbf{A b} \mathbf{b}_{c} \\
\mid & \mid
\end{array}\right)\left(\begin{array}{c}
v_{1} \\
v_{2} \\
\vdots \\
v_{c}
\end{array}\right) \\
& =\left(\begin{array}{ccc}
\mid & \mid & \mid \\
\mathbf{A} \mathbf{b}_{1} & \mathbf{A} \mathbf{b}_{2} & \cdots \\
\mid & \mathbf{A b} \mathbf{b}_{c} \\
\mid & \mid
\end{array}\right) \mathbf{v}
\end{aligned}$$

Therefore, we have
$$\mathbf{A B}=\left(\begin{array}{cccc}
\mid & \mid & & \mid \\
\mathbf{A b}_{1} & \mathbf{A b}_{2} & \cdots & \mathbf{A b}_{c} \\
\mid & \mid & & \mid
\end{array}\right) .$$

413

---

<!-- Page 414 -->

CHAPTER 11. VECTORS AND MATRICES IN THREE DIMENSIONS, PART 1

Since for each $i$, we have
$$\mathbf{A b}_{i}=\left(\begin{array}{c}
-\mathbf{a}_{1} \\
-\mathbf{a}_{2} \\
\vdots \\
-\mathbf{a}_{r}
\end{array}\right) \mathbf{b}_{i}=\left(\begin{array}{c}
\mathbf{a}_{1} \cdot \mathbf{b}_{i} \\
\mathbf{a}_{2} \cdot \mathbf{b}_{i} \\
\vdots \\
\mathbf{a}_{r} \cdot \mathbf{b}_{i}
\end{array}\right),$$
we have
$$\mathbf{A B}=\left(\begin{array}{cccc}
\mid & \mid & & \mid \\
\mathbf{A} \mathbf{b}_{1} & \mathbf{A} \mathbf{b}_{2} & \cdots & \mathbf{A} \mathbf{b}_{c} \\
\mid & \mid & & \mid
\end{array}\right)=\left(\begin{array}{ccccc}
\mathbf{a}_{1} \cdot \mathbf{b}_{1} & \mathbf{a}_{1} \cdot \mathbf{b}_{2} & \mathbf{a}_{1} \cdot \mathbf{b}_{3} & \cdots & \mathbf{a}_{1} \cdot \mathbf{b}_{c} \\
\mathbf{a}_{2} \cdot \mathbf{b}_{1} & \mathbf{a}_{2} \cdot \mathbf{b}_{2} & \mathbf{a}_{2} \cdot \mathbf{b}_{3} & \cdots & \mathbf{a}_{2} \cdot \mathbf{b}_{c} \\
\vdots & \vdots & \vdots & \ddots & \vdots \\
\mathbf{a}_{r} \cdot \mathbf{b}_{1} & \mathbf{a}_{r} \cdot \mathbf{b}_{2} & \mathbf{a}_{r} \cdot \mathbf{b}_{3} & \cdots & \mathbf{a}_{r} \cdot \mathbf{b}_{c}
\end{array}\right) .$$

Problem 11.28: Compute the following products:
(a) $\quad\left(\begin{array}{ccc}5 & -1 & 0 \\ -3 & 8 & -2\end{array}\right)\left(\begin{array}{ccc}4 & -3 & 8 \\ 5 & -1 & 0 \\ -2 & -2 & 8\end{array}\right)$
(b) $\left(\begin{array}{cc}4 & 8 \\ -1 & 3 \\ 0 & 8 \\ -1 & -1\end{array}\right)\left(\begin{array}{ccc}6 & -2 & -3 \\ -1 & -7 & 4\end{array}\right)$

Solution for Problem 11.28:
(a) The product of a $2 \times 3$ matrix and a $3 \times 3$ matrix is a $2 \times 3$ matrix:
$$\begin{aligned}
\left(\begin{array}{ccc}
5 & -1 & 0 \\
-3 & 8 & -2
\end{array}\right) & \left(\begin{array}{ccc}
4 & -3 & 8 \\
5 & -1 & 0 \\
-2 & -2 & 8
\end{array}\right) \\
& =\left(\begin{array}{ccc}
(5)(4)+(-1)(5)+(0)(-2) & (5)(-3)+(-1)(-1)+(0)(-2) & (5)(8)+(-1)(0)+(0)(8) \\
(-3)(4)+(8)(5)+(-2)(-2) & (-3)(-3)+(8)(-1)+(-2)(-2) & (-3)(8)+(8)(0)+(-2)(8)
\end{array}\right) \\
& =\left(\begin{array}{ccc}
15 & -14 & 40 \\
32 & 5 & -40
\end{array}\right)
\end{aligned}$$
(b) The product of a $4 \times 2$ matrix and a $2 \times 3$ matrix is a $4 \times 3$ matrix:
$$\begin{aligned}
\left(\begin{array}{cc}
4 & 8 \\
-1 & 3 \\
0 & 8 \\
-1 & -1
\end{array}\right)\left(\begin{array}{ccc}
6 & -2 & -3 \\
-1 & -7 & 4
\end{array}\right) & =\left(\begin{array}{ccc}
(4)(6)+(8)(-1) & (4)(-2)+(8)(-7) & (4)(-3)+(8)(4) \\
(-1)(6)+(3)(-1) & (-1)(-2)+(3)(-7) & (-1)(-3)+(3)(4) \\
(0)(6)+(8)(-1) & (0)(-2)+(8)(-7) & (0)(-3)+(8)(4) \\
(-1)(6)+(-1)(-1) & (-1)(-2)+(-1)(-7) & (-1)(-3)+(-1)(4)
\end{array}\right) \\
& =\left(\begin{array}{ccc}
16 & -64 & 20 \\
-9 & -19 & 15 \\
-8 & -56 & 32 \\
-5 & 9 & -1
\end{array}\right)
\end{aligned}$$

We say that a matrix is square if it has the same number of rows and columns. We can define the determinant of a square matrix with more than 3 rows by using expansion by minors in much the same manner as we did for $3 \times 3$ matrix. This is what it looks like for a $4 \times 4$ matrix:
$$\left|\begin{array}{llll}
a_{1} & b_{1} & c_{1} & d_{1} \\
a_{2} & b_{2} & c_{2} & d_{2} \\
a_{3} & b_{3} & c_{3} & d_{3} \\
a_{4} & b_{4} & c_{4} & d_{4}
\end{array}\right|=a_{1}\left|\begin{array}{lll}
b_{2} & c_{2} & d_{2} \\
b_{3} & c_{3} & d_{3} \\
b_{4} & c_{4} & d_{4}
\end{array}\right|-b_{1}\left|\begin{array}{lll}
a_{2} & c_{2} & d_{2} \\
a_{3} & c_{3} & d_{3} \\
a_{4} & c_{4} & d_{4}
\end{array}\right|+c_{1}\left|\begin{array}{lll}
a_{2} & b_{2} & d_{2} \\
a_{3} & b_{3} & d_{3} \\
a_{4} & b_{4} & d_{4}
\end{array}\right|-d_{1}\left|\begin{array}{lll}
a_{2} & b_{2} & c_{2} \\
a_{3} & b_{3} & c_{3} \\
a_{4} & b_{4} & c_{4}
\end{array}\right| .$$

414

---

<!-- Page 415 -->

11.5. SUMMARY

(Note: the "Rule of Sarrus" gimmick for remembering the formula for the determinant of a $3 \times 3$ matrix does not work for finding the determinant of larger matrices.)

If you enjoy computer programming, try writing a program for finding the determinant of a $4 \times 4$ matrix. As a bigger challenge, try writing a program for finding the determinant of any $n \times n$ matrix.

Exercises
11.4.1 Find the product $\left(\begin{array}{cc}3 & 4 \\ -1 & 5 \\ 0 & 2\end{array}\right)\left(\begin{array}{cccc}-3 & 4 & -2 & -1 \\ 7 & 8 & -1 & 0\end{array}\right)$.
11.4.2 Find the product $\binom{4}{1}\left(\begin{array}{lll}-1 & 5 & -3\end{array}\right)$.
11.4.3 Show that if $\mathbf{v}$ and $\mathbf{w}$ are vectors in $n$ dimensions, then $\mathbf{v} \cdot \mathbf{w}=\mathbf{w} \cdot \mathbf{v}$.
11.4.4 Show that for any scalar $a$ and any vectors $\mathbf{u}, \mathbf{v}$, and $\mathbf{w}$ in $n$ dimensions, then we have the following:
(a) $\mathbf{v} \cdot(a \mathbf{w})=(a \mathbf{v}) \cdot \mathbf{w}=a \mathbf{v} \cdot \mathbf{w}$
(b) $\mathbf{u} \cdot(\mathbf{v}+\mathbf{w})=\mathbf{u} \cdot \mathbf{v}+\mathbf{u} \cdot \mathbf{w}$
11.4.5 Suppose $\mathbf{A}$ is a $2 \times 3$ matrix. Is there a matrix $\mathbf{I}$ such that $\mathbf{I A}=\mathbf{A}$ for all $\mathbf{A}$ ? If so, what is it?
11.5 Summary

We denote a vector in three dimensions with an ordered triple $\left(\begin{array}{l}a \\ b \\ c\end{array}\right)$, which can also be written as $a \mathbf{i}+b \mathbf{j}+c \mathbf{k}$, where $\mathbf{i}, \mathbf{j}$, and $\mathbf{k}$ are unit vectors from the origin in the direction of the positive $x$-axis, $y$-axis, and $z$-axis, respectively. Addition, scalar multiplication, and norm are defined as follows:
$$\left(\begin{array}{l}
a \\
b \\
c
\end{array}\right)+\left(\begin{array}{l}
x \\
y \\
z
\end{array}\right)=\left(\begin{array}{l}
a+x \\
b+y \\
c+z
\end{array}\right), \quad k\left(\begin{array}{l}
a \\
b \\
c
\end{array}\right)=\left(\begin{array}{l}
k a \\
k b \\
k c
\end{array}\right), \quad\left\|\left(\begin{array}{l}
x \\
y \\
z
\end{array}\right)\right\|=\sqrt{x^{2}+y^{2}+z^{2}}$$
and the dot product is defined as
$$\left(\begin{array}{l}
v_{1} \\
v_{2} \\
v_{3}
\end{array}\right) \cdot\left(\begin{array}{l}
w_{1} \\
w_{2} \\
w_{3}
\end{array}\right)=v_{1} \cdot w_{1}+v_{2} \cdot w_{2}+v_{3} \cdot w_{3}$$

The dot product has the following properties:
- $\mathbf{u} \cdot \mathbf{v}=\mathbf{v} \cdot \mathbf{u}$
- $\mathbf{u} \cdot(a \mathbf{v})=a(\mathbf{u} \cdot \mathbf{v})$
- $\mathbf{u} \cdot(\mathbf{v}+\mathbf{w})=\mathbf{u} \cdot \mathbf{v}+\mathbf{u} \cdot \mathbf{w}$
- $\mathbf{v} \cdot \mathbf{v}=\|\mathbf{v}\|^{2}$
- $\mathbf{v} \cdot \mathbf{w}=\|\mathbf{v}\|\|\mathbf{w}\| \cos \theta$, where $\theta$ is the angle between $\mathbf{v}$ and $\mathbf{w}$

415

---

<!-- Page 416 -->

CHAPTER 11. VECTORS AND MATRICES IN THREE DIMENSIONS, PART 1

A $3 \times 3$ matrix represents a linear function that maps vectors in 3 dimensions to vectors in 3 dimensions. This mapping is illustrated as a product of the matrix and a vector according to the definition
$$\left(\begin{array}{lll}
a_{11} & a_{12} & a_{13} \\
a_{21} & a_{22} & a_{23} \\
a_{31} & a_{32} & a_{33}
\end{array}\right)\left(\begin{array}{l}
x \\
y \\
z
\end{array}\right)=\left(\begin{array}{l}
a_{11} x+a_{12} y+a_{13} z \\
a_{21} x+a_{22} y+a_{23} z \\
a_{31} x+a_{32} y+a_{33} z
\end{array}\right) .$$

For any matrix $\mathbf{A}$, any scalar $c$, and any vectors $\mathbf{v}$ and $\mathbf{w}$, we have $\mathbf{A}(c \mathbf{v})=c(\mathbf{A v})$ and $\mathbf{A}(\mathbf{v}+\mathbf{w})=\mathbf{A v}+\mathbf{A w}$.
We add two matrices by adding the corresponding components in the matrices, and define the product of two matrices as follows:
$$\left(\begin{array}{lll}
a_{11} & a_{12} & a_{13} \\
a_{21} & a_{22} & a_{23} \\
a_{31} & a_{32} & a_{33}
\end{array}\right)\left(\begin{array}{lll}
b_{11} & b_{12} & b_{13} \\
b_{21} & b_{22} & b_{23} \\
b_{31} & b_{32} & b_{33}
\end{array}\right)=\left(\begin{array}{lll}
a_{11} b_{11}+a_{12} b_{21}+a_{13} b_{31} & a_{11} b_{12}+a_{12} b_{22}+a_{13} b_{32} & a_{11} b_{13}+a_{12} b_{23}+a_{13} b_{33} \\
a_{21} b_{11}+a_{22} b_{21}+a_{23} b_{31} & a_{21} b_{12}+a_{22} b_{22}+a_{23} b_{32} & a_{21} b_{13}+a_{22} b_{23}+a_{23} b_{33} \\
a_{31} b_{11}+a_{32} b_{21}+a_{33} b_{31} & a_{31} b_{12}+a_{32} b_{22}+a_{33} b_{32} & a_{31} b_{13}+a_{32} b_{23}+a_{33} b_{33}
\end{array}\right) .$$

Matrix multiplication is not commutative, but it is associative and distributive.

Important: The $3 \times 3$ matrix $\mathbf{I}$ such that $\mathbf{A I}=\mathbf{I A}=\mathbf{A}$ for any $3 \times 3$ matrix $\mathbf{A}$ is
$$\mathbf{I}=\left(\begin{array}{lll}
1 & 0 & 0 \\
0 & 1 & 0 \\
0 & 0 & 1
\end{array}\right) .$$

We call this the identity matrix.

Definition: We define the determinant of a $3 \times 3$ matrix as follows:
$$\begin{aligned}
\left|\begin{array}{lll}
a_{1} & b_{1} & c_{1} \\
a_{2} & b_{2} & c_{2} \\
a_{3} & b_{3} & c_{3}
\end{array}\right| & =a_{1}\left|\begin{array}{ll}
b_{2} & c_{2} \\
b_{3} & c_{3}
\end{array}\right|-b_{1}\left|\begin{array}{ll}
a_{2} & c_{2} \\
a_{3} & c_{3}
\end{array}\right|+c_{1}\left|\begin{array}{ll}
a_{2} & b_{2} \\
a_{3} & b_{3}
\end{array}\right| \\
& =a_{1} b_{2} c_{3}+b_{1} c_{2} a_{3}+c_{1} a_{2} b_{3}-a_{1} c_{2} b_{3}-b_{1} a_{2} c_{3}-c_{1} b_{2} a_{3}
\end{aligned}$$

We can also denote the determinant of a matrix $\mathbf{A}$ as $\operatorname{det}(\mathbf{A})$.

We say a matrix is singular if its determinant is 0 , and nonsingular if its determinant is nonzero. If $\operatorname{det}(\mathbf{A}) \neq 0$, then for any vector $\mathbf{c}$, there is unique vector $\mathbf{v}$ such that $\mathbf{A v}=\mathbf{c}$.

The determinant has the following properties:
- If we produce matrix $\mathbf{B}$ by multiplying a row or a column of $\mathbf{A}$ by some constant $k$, then $\operatorname{det}(\mathbf{B})=k \operatorname{det}(\mathbf{A})$.
- For any $3 \times 3$ matrix $\mathbf{A}$ and any constant $k$, we have $\operatorname{det}(k \mathbf{A})=k^{3} \operatorname{det}(\mathbf{A})$.
- For any $3 \times 3$ matrix $\mathbf{A}$, swapping the rows or columns of $\mathbf{A}$ produces a matrix with determinant $(-1) \operatorname{det}(\mathbf{A})$.
- If one row of a $3 \times 3$ matrix is a constant times another row, or one column of the matrix is a constant times another column, then the determinant of the matrix is 0 .
- For any matrix $\mathbf{M}$, the determinant of a matrix formed when we add a constant times any row of $\mathbf{M}$ to another row of $\mathbf{M}$ equals $\operatorname{det}(\mathbf{M})$. Similarly, the determinant of a matrix formed when we'add a constant times any column of $\mathbf{M}$ to another column of $\mathbf{M}$ equals $\operatorname{det}(\mathbf{M})$.

416

---

<!-- Page 417 -->

REVIEW PROBLEMS

A minor of a matrix $\mathbf{A}$, denoted as $A_{i j}$, is the determinant of the matrix that remains when row $i$ and column $j$ are omitted from matrix $\mathbf{A}$. We can compute the determinant of $\mathbf{A}$ as
$$\operatorname{det}(\mathbf{A})=(-1)^{i+1} a_{i 1} A_{i 1}+(-1)^{i+2} a_{i 2} A_{i 2}+(-1)^{i+3} a_{i 3} A_{i 3}$$
for $i=1,2$, or 3, and as
$$\operatorname{det}(\mathbf{A})=(-1)^{1+j} a_{1 j} A_{1 j}+(-1)^{2+j} a_{2 j} A_{2 j}+(-1)^{3+j} a_{3 j} A_{3 j}$$
for $j=1,2$, or 3 . This technique is called expansion by minors.
An matrix with $r$ rows and $c$ columns (an $r \times c$ matrix) represents a linear function that maps vectors with c components to vectors with $r$ components. The product of an $r \times c$ matrix and a vector with $c$ components is defined as follows:

We can define the matrix sum $\mathbf{A}+\mathbf{B}$ if and only if $\mathbf{A}$ and $\mathbf{B}$ have the same dimensions, in which case each entry in the sum $\mathbf{A}+\mathbf{B}$ is the sum of the corresponding entries in the two matrices.

Let the rows of $\mathbf{A}$ be $\mathbf{a}_{1}, \mathbf{a}_{2}, \ldots, \mathbf{a}_{r}$ and the columns of $\mathbf{B}$ be $\mathbf{b}_{1}, \mathbf{b}_{2}, \ldots, \mathbf{b}_{c}$. If the matrix product $\mathbf{A B}$ is defined, then the product is given by
$$\mathbf{A B}=\left(\begin{array}{ccccc}
\mathbf{a}_{1} \cdot \mathbf{b}_{1} & \mathbf{a}_{1} \cdot \mathbf{b}_{2} & \mathbf{a}_{1} \cdot \mathbf{b}_{3} & \cdots & \mathbf{a}_{1} \cdot \mathbf{b}_{c} \\
\mathbf{a}_{2} \cdot \mathbf{b}_{1} & \mathbf{a}_{2} \cdot \mathbf{b}_{2} & \mathbf{a}_{2} \cdot \mathbf{b}_{3} & \cdots & \mathbf{a}_{2} \cdot \mathbf{b}_{c} \\
\vdots & \vdots & \vdots & \ddots & \vdots \\
\mathbf{a}_{r} \cdot \mathbf{b}_{1} & \mathbf{a}_{r} \cdot \mathbf{b}_{2} & \mathbf{a}_{r} \cdot \mathbf{b}_{3} & \cdots & \mathbf{a}_{r} \cdot \mathbf{b}_{c}
\end{array}\right) .$$

Review Problems

Unless stated otherwise, all vectors in the Review Problems and Challenge Problems are in 3 dimensions, and all matrices are $3 \times 3$ matrices.
11.29 Let $\mathbf{u}=\left(\begin{array}{c}2 \\ 3 \\ -5\end{array}\right)$ and $\mathbf{v}=\left(\begin{array}{c}4 \\ 5 \\ -1\end{array}\right)$.
(a) Find $\|\mathbf{u}\|$ and $\|\mathbf{v}\|$.
(b) Find $(2 \mathbf{u}+3 \mathbf{v}) \cdot(\mathbf{u}-3 \mathbf{v})$.

417

---

<!-- Page 418 -->

CHAPTER 11. VECTORS AND MATRICES IN THREE DIMENSIONS, PART 1
11.30 Which two of the following four vectors are orthogonal: $\left(\begin{array}{c}4 \\ 5 \\ -1\end{array}\right),\left(\begin{array}{c}-3 \\ 4 \\ 2\end{array}\right),\left(\begin{array}{c}-4 \\ 2 \\ 3\end{array}\right),\left(\begin{array}{c}-2 \\ -3 \\ 3\end{array}\right)$ ?
11.31 Show that $\left(x_{1} y_{1}+x_{2} y_{2}+x_{3} y_{3}\right)^{2} \leq\left(x_{1}^{2}+x_{2}^{2}+x_{3}^{2}\right)\left(y_{1}^{2}+y_{2}^{2}+y_{3}^{2}\right)$.
11.32
(a) Find the product $\left(\begin{array}{ccc}4 & 5 & -2 \\ 1 & -3 & 4 \\ 0 & 1 & -2\end{array}\right)\left(\begin{array}{c}-1 \\ 1 \\ 4\end{array}\right)$.
(b) Is the matrix in part (a) the only matrix that can be multiplied by $\left(\begin{array}{c}-1 \\ 1 \\ 4\end{array}\right)$ to give your answer to part (a)? If not, then find another.
(c) Is the vector $\left(\begin{array}{c}-1 \\ 1 \\ 4\end{array}\right)$ from part (a) the only vector that can be multiplied by the matrix given in part (a) to get your answer to part (a)?
11.33
(a) If Av equals the vector $\mathbf{0}$, then must either $\mathbf{A}$ be $\mathbf{0}$ or $\mathbf{v}$ be $\mathbf{0}$ ?
(b) If $\mathbf{A B}$ equals the matrix $\mathbf{0}$, then must either $\mathbf{A}$ or $\mathbf{B}$ be $\mathbf{0}$ ?
11.34 Find the product $\left(\begin{array}{ccc}4 & -2 & -1 \\ 0 & 5 & -1 \\ -2 & 0 & -1\end{array}\right)\left(\begin{array}{ccc}-3 & 2 & 6 \\ -1 & 3 & -5 \\ 7 & 0 & 3\end{array}\right)$.
11.35
(a) Is there a matrix $\mathbf{P}$ such that $\mathbf{P A}$ is the matrix that results when we swap the first two columns of $\mathbf{A}$ and leave the third column unchanged?
(b) Is there a matrix $\mathbf{P}$ such that $\mathbf{A P}$ is the matrix that results when we swap the first two columns of $\mathbf{A}$ and leave the third column unchanged?
11.36 If $\mathbf{A v}+\mathbf{B v}=\mathbf{0}$ for all vectors $\mathbf{v}$, then must $\mathbf{A}=-\mathbf{B}$ ?
11.37 Compute the following two determinants:
(a) $\left|\begin{array}{ccc}-2 & -4 & 1 \\ -5 & 3 & 2 \\ -3 & 1 & 8\end{array}\right|$
(b) $\quad\left|\begin{array}{ccc}1 / 3 & 1 / 5 & 6 \\ 4 & -3 & 5 \\ -1 & 6 & -10\end{array}\right|$
11.38 Use Cramer's rule to solve the following system of equations:
$$\begin{aligned}
x-2 y+5 z & =-3 \\
2 x-5 y+3 z & =4 \\
-5 x+2 y+3 z & =-1
\end{aligned}$$
11.39 Evaluate $\left|\begin{array}{ccc}x-4 & x-3 & x-2 \\ x-1 & x & x+1 \\ x+2 & x+3 & x+4\end{array}\right|$.

418

---

<!-- Page 419 -->

CHALLENGE PROBLEMS
11.40
(a) As described on page 399, the matrix $\mathbf{A}^{T}$ is the transpose of $\mathbf{A}$. Show that if $\mathbf{A}$ and $\mathbf{B}$ are $3 \times 3$ matrices, then $(\mathbf{A B})^{T}=\mathbf{B}^{T} \mathbf{A}^{T}$.
(b) We can extend the concept of a transpose matrix to $r \times c$ matrices as follows. Let $\mathbf{A}$ be an $r \times c$ matrix with row vectors, in order, of $\mathbf{a}_{1}, \mathbf{a}_{2}, \ldots, \mathbf{a}_{r}$. The transpose of $\mathbf{A}$, denoted $\mathbf{A}^{T}$, is the $c \times r$ matrix whose columns, in order, are $\mathbf{a}_{1}, \mathbf{a}_{2}, \ldots, \mathbf{a}_{r}$. Show that if $\mathbf{A B}$ is defined, then $(\mathbf{A B})^{T}=\mathbf{B}^{T} \mathbf{A}^{T}$.
11.41 Find the product $\left(\begin{array}{ccc}4 & 0 & 2 \\ 5 & -1 & -1 \\ 3 & -2 & 7 \\ -1 & 5 & 2\end{array}\right)\left(\begin{array}{cc}7 & -1 \\ 0 & -2 \\ -1 & 2\end{array}\right)$.
11.42 If $\mathbf{A}$ is $3 \times 4$ matrix, $\mathbf{C}$ is $3 \times 6$ matrix, and $\mathbf{A B}=\mathbf{C}$, then what are the dimensions of $\mathbf{B}$ ?
11.43
(a) Show that if the product of two square matrices is defined, then the two matrices have the same dimensions, and the product has the same dimensions as the original matrices.
(b) If the product $\mathbf{A B}$ equals a square matrix, then must $\mathbf{A}$ and $\mathbf{B}$ be square matrices?

Challenge Problems
11.44 Let $\mathbf{u}, \mathbf{v}$, and $\mathbf{w}$ be vectors such that each vector has magnitude 1 and each vector is orthogonal to the other two. Show that if $\mathbf{r}=a \mathbf{u}+b \mathbf{v}+c \mathbf{w}$, then we must have $a=\mathbf{r} \cdot \mathbf{u}, b=\mathbf{r} \cdot \mathbf{v}$, and $c=\mathbf{r} \cdot \mathbf{w}$.
11.45 Let $\mathbf{u}=\mathbf{i}+\mathbf{j}+z \mathbf{k}$ and $\mathbf{v}=2 \mathbf{i}-\mathbf{j}+3 \mathbf{k}$.
(a) Find all $z$ such that the angle between $\mathbf{u}$ and $\mathbf{v}$ is $\pi / 2$.
(b) Find all $z$ such that the angle between $\mathbf{u}$ and $\mathbf{v}$ is $\pi / 3$.
(c) ★ Find the maximum possible value of $\cos ^{2} \theta$ if it is possible to find a value of $z$ such that the angle between $\mathbf{u}$ and $\mathbf{v}$ is $\theta$. Hints: 34,33
11.46 Express $\left|\begin{array}{lll}1 & a & a^{2} \\ 1 & b & b^{2} \\ 1 & c & c^{2}\end{array}\right|$ as a product of three polynomials in $a, b$, and $c$ with nonzero degree. Hints: 71
11.47 We say that a matrix $\mathbf{M}$ is skew-symmetric if it satisfies $\mathbf{M}^{T}=-\mathbf{M}$. Show that if a $3 \times 3$ matrix $\mathbf{M}$ is skew-symmetric, then $\operatorname{det}(\mathbf{M})=0$.
11.48★
(a) Show that if $\lambda$ is a constant such that there exists a nonzero vector $\mathbf{v}$ for which $\mathbf{A v}=\lambda \mathbf{v}$, then $\operatorname{det}(\mathbf{A}-\lambda \mathbf{I})=0$.

Hints: 51
(b) Let $\mathbf{A}=\left(\begin{array}{ccc}-8 & 1 & 3 \\ -4 & 1 & 7 \\ 8 & 1 & -1\end{array}\right)$. Find three values of $\lambda$ such that $\operatorname{det}(\mathbf{A}-\lambda \mathbf{I})=0$. These values are called the eigenvalues of $\mathbf{A}$.
(c) For each value of $\lambda$ you found in part (b), find a nonzero vector $\mathbf{v}$ such that $\mathbf{A v}=\lambda \mathbf{v}$. These vectors are called eigenvectors of $\mathbf{A}$.

419

---

<!-- Page 420 -->

CHAPTER 11. VECTORS AND MATRICES IN THREE DIMENSIONS, PART 1
11.49 Let $\mathbf{A}=\left(\begin{array}{lll}1 & 1 & 0 \\ 0 & 1 & 1 \\ 0 & 0 & 1\end{array}\right)$. Find $\mathbf{A}^{n}$.
11.50 Suppose $\mathbf{A}=\left(\begin{array}{ccc}5 & 3 & -2 \\ -1 & 5 & 4\end{array}\right)$ and $\mathbf{B}=\left(\begin{array}{cc}-6 & -20 \\ 8 & 24\end{array}\right)$. Is there a matrix $\mathbf{M}$ such that $\mathbf{A M}=\mathbf{B}$ ? If so, is it unique?
11.51 Suppose that $\mathbf{A}$ and $\mathbf{B}$ are matrices such that $\mathbf{A B}=-\mathbf{B A}$.
(a) If $\mathbf{A}$ and $\mathbf{B}$ are $2 \times 2$ matrices, must at least one of $\mathbf{A}$ and $\mathbf{B}$ be singular?
(b) If $\mathbf{A}$ and $\mathbf{B}$ are $3 \times 3$ matrices, must at least one of $\mathbf{A}$ and $\mathbf{B}$ be singular?
11.52 ★ Let $\mathbf{A}=\left(\begin{array}{ccc}-2 & 4 & -4 \\ 0 & 2 & -6 \\ -8 & -2 & 4\end{array}\right)$. Prove that $\operatorname{det}\left(\mathbf{I}-\mathbf{A}^{2006}\right)$ is not equal to 0 . Hints: 245,123

420

---

