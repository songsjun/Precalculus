# Chapter 12: Vectors and Matrices in Three Dimensions, Part 2

<!-- Page 421 -->

If there's no struggle, there's no progress. - Frederick Douglass
стонте 12

Vectors and Matrices in Three Dimensions, Part 2
12.1 Lines and Planes in Three Dimensions

As in two dimensions, a linear combination of a set of vectors $\mathbf{v}_{1}, \mathbf{v}_{2}, \ldots, \mathbf{v}_{n}$ is a sum
$$a_{1} \mathbf{v}_{1}+a_{2} \mathbf{v}_{2}+\cdots+a_{n} \mathbf{v}_{n}$$
of products of scalars and the vectors. In this section, we'll investigate the geometry of linear combinations of vectors in three dimensions.

Problems

Problem 12.1: In this problem, we explore using equations to describe lines in three dimensions. Let $A$ be $(3,4,-2)$ and $B$ be $(-1,5,0)$, and let $\ell$ be the line through $A$ and $B$.
(a) Suppose that $C$ is a point on $\ell$ besides $A$ and $B$. How must $\overrightarrow{A C}$ and $\overrightarrow{A B}$ be related?
(b) Show that if ( $x, y, z$ ) is on $\ell$, then we must have
$$\left(\begin{array}{l}
x \\
y \\
z
\end{array}\right)=\left(\begin{array}{c}
3 \\
4 \\
-2
\end{array}\right)+\left(\begin{array}{c}
-4 \\
1 \\
2
\end{array}\right) t$$
for some value of $t$. Does substituting any real number $t$ into this equation produce a point ( $x, y, z$ ) that is on $\ell$ ?

Problem 12.2: Let $A$ be $(-1,3,2), B$ be $(-3,5,-1), C$ be $(0,-2,8)$, and $D$ be $(4,1,7)$. Do $\overleftrightarrow{A B}$ and $\overleftrightarrow{C D}$ intersect?

421

---

<!-- Page 422 -->

CHAPTER 12. VECTORS AND MATRICES IN THREE DIMENSIONS, PART 2

Problem 12.3: In this problem, we investigate linear combinations of pairs of vectors. For each of the values of $\mathbf{v}$ and $\mathbf{w}$ given below, describe the graph of all points $(x, y, z)$ that satisfy $\left(\begin{array}{l}x \\ y \\ z\end{array}\right)=s \mathbf{v}+t \mathbf{w}$ for some values of $s$ and $t$.
(a) $\mathbf{v}=\mathbf{j}, \mathbf{w}=3 \mathbf{j}$
(b) $\mathbf{v}=\mathbf{i}, \mathbf{w}=\mathbf{j}$
(c) $\mathbf{v}=\mathbf{i}+\mathbf{k}, \mathbf{w}=\mathbf{k}$
(d) Your answer to part (a) should be a different type of geometric object than your answers to parts (b) and (c). Why does this occur?

Problem 12.4:
(a) Describe the graph of the parametric equation $\left(\begin{array}{l}x \\ y \\ z\end{array}\right)=\left(\begin{array}{c}-1 \\ 3 \\ 4\end{array}\right)+s \mathbf{i}+t \mathbf{j}$, where $s$ and $t$ are parameters.
(b) How is the graph in part (a) related to the graph of $\left(\begin{array}{l}x \\ y \\ z\end{array}\right)=s \mathbf{i}+t \mathbf{j}$ ?

Problem 12.5: Suppose neither $\mathbf{v}$ nor $\mathbf{w}$ is a multiple of the other. Show that the graphs of the parametric equations
$$\begin{array}{l}
\left(\begin{array}{l}
x \\
y \\
z
\end{array}\right)=\left(\begin{array}{l}
a_{1} \\
b_{1} \\
c_{1}
\end{array}\right)+s_{1} \mathbf{v}+t_{1} \mathbf{w} \\
\left(\begin{array}{l}
x \\
y \\
z
\end{array}\right)=\left(\begin{array}{l}
a_{2} \\
b_{2} \\
c_{2}
\end{array}\right)+s_{2} \mathbf{v}+t_{2} \mathbf{w}
\end{array}$$
are either the same or do not intersect.

Problem 12.1: In this problem, we explore using equations to describe lines in three dimensions. Let $A$ be $(3,4,-2)$ and $B$ be $(-1,5,0)$, and let $\ell$ be the line through $A$ and $B$.
(a) Suppose that $C$ is a point on $\ell$ besides $A$ and $B$. How must $\overrightarrow{A C}$ and $\overrightarrow{A B}$ be related?
(b) Show that if ( $x, y, z$ ) is on $\ell$, then we must have
$$\left(\begin{array}{l}
x \\
y \\
z
\end{array}\right)=\left(\begin{array}{c}
3 \\
4 \\
-2
\end{array}\right)+\left(\begin{array}{c}
-4 \\
1 \\
2
\end{array}\right) t$$
for some value of $t$. Does substituting any real number $t$ into this equation produce a point $(x, y, z)$ that is on $\ell$ ?

Solution for Problem 12.1:
(a) If $A, B$, and $C$ are collinear, then the angle between $\overrightarrow{A C}$ and $\overrightarrow{A B}$ must be either 0 or $\pi$, so $\overrightarrow{A C}$ must be a scalar multiple of $\overrightarrow{A B}$.

422

---

<!-- Page 423 -->

12.1. LINES AND PLANES IN THREE DIMENSIONS
(b) Let $C$ be ( $x, y, z$ ). Since $C$ is on $\ell$, we must have $\overrightarrow{A C}=t \overrightarrow{A B}$ for some scalar $t$. Since $\overrightarrow{A C}=\vec{C}-\vec{A}$ and $\overrightarrow{A B}=\vec{B}-\vec{A}$, we have $\vec{C}=\vec{A}+t(\vec{B}-\vec{A})$, or
$$\left(\begin{array}{l}
x \\
y \\
z
\end{array}\right)=\left(\begin{array}{c}
3 \\
4 \\
-2
\end{array}\right)+\left(\left(\begin{array}{c}
-1 \\
5 \\
0
\end{array}\right)-\left(\begin{array}{c}
3 \\
4 \\
-2
\end{array}\right)\right) t=\left(\begin{array}{c}
3 \\
4 \\
-2
\end{array}\right)+\left(\begin{array}{c}
-4 \\
1 \\
2
\end{array}\right) t$$

Any point $(x, y, z)$ on $\ell$ must satisfy this equation for some value of $t$. Conversely, every value of $t$ gives a point ( $x, y, z$ ) on the line, because $C$ is on $\ell$ whenever $\overrightarrow{A C}=t \overrightarrow{A B}$. Therefore, Equation (12.1) gives us parametric equations whose graph is a line in space: $x=3-4 t, y=4+t, z=-2+2 t$.

Our solution to Problem 12.1 should be familiar, since it's the same process we used to describe a line in two dimensions in Section 9.3. We can use this same procedure to express any line in space with a parametric equation of the form
$$\left(\begin{array}{l}
x \\
y \\
z
\end{array}\right)=\left(\begin{array}{l}
a \\
b \\
c
\end{array}\right)+t \mathbf{d}$$

The point ( $a, b, c$ ) is on the line and $\mathbf{d}$ is a direction vector of the line. Any vector between two distinct points on the line must be a scalar multiple of $\mathbf{d}$. We also sometimes say that this direction vector is "parallel" to the line. We can think of the parametric equation as telling us, "To get to any point $(x, y, z)$ on the graph, start at $(a, b, c)$ and then travel in the direction of $\mathbf{d}$ (or the opposite direction)." Since every point in the graph besides ( $a, b, c$ ) is the same (or opposite) direction from ( $a, b, c$ ), the graph of this equation produces the line through ( $a, b, c$ ) in direction $\mathbf{d}$.

Just as in two dimensions, a given line does not have a unique direction vector, but if $\mathbf{d}_{1}$ and $\mathbf{d}_{2}$ are both possible direction vectors for the same line, then $\mathbf{d}_{1}=k \mathbf{d}_{2}$ for some nonzero scalar $k$.

Problem 12.2: Let $A$ be ( $-1,3,2$ ), $B$ be ( $-3,5,-1$ ), $C$ be ( $0,-2,8$ ), and $D$ be ( $4,1,7$ ). Do $\overleftrightarrow{A B}$ and $\overleftrightarrow{C D}$ intersect?
Solution for Problem 12.2: We start by finding parametric forms for both lines. Proceeding as in the previous problem, for any point $(x, y, z)$ on $\overleftrightarrow{A B}$, we must have
$$\left(\begin{array}{l}
x \\
y \\
z
\end{array}\right)=\vec{A}+(\vec{B}-\vec{A}) t=\left(\begin{array}{c}
-1 \\
3 \\
2
\end{array}\right)+\left(\left(\begin{array}{c}
-3 \\
5 \\
-1
\end{array}\right)-\left(\begin{array}{c}
-1 \\
3 \\
2
\end{array}\right)\right) t=\left(\begin{array}{c}
-1 \\
3 \\
2
\end{array}\right)+\left(\begin{array}{c}
-2 \\
2 \\
-3
\end{array}\right) t=\left(\begin{array}{c}
-1-2 t \\
3+2 t \\
2-3 t
\end{array}\right)$$

So, $\overleftrightarrow{A B}$ is the graph of the parametric equations $x=-1-2 t, y=3+2 t, z=2-3 t$.
Turning to $\overleftrightarrow{C D}$, the point $(x, y, z)$ is on $\overleftrightarrow{C D}$ if
$$\left(\begin{array}{l}
x \\
y \\
z
\end{array}\right)=\vec{C}+(\vec{D}-\vec{C}) u=\left(\begin{array}{c}
0 \\
-2 \\
8
\end{array}\right)+\left(\left(\begin{array}{l}
4 \\
1 \\
7
\end{array}\right)-\left(\begin{array}{c}
0 \\
-2 \\
8
\end{array}\right)\right) u=\left(\begin{array}{c}
0 \\
-2 \\
8
\end{array}\right)+\left(\begin{array}{c}
4 \\
3 \\
-1
\end{array}\right) u=\left(\begin{array}{c}
4 u \\
-2+3 u \\
8-u
\end{array}\right) .$$

Therefore, $\overleftrightarrow{C D}$ is the graph of the parametric equations $x=4 u, y=-2+3 u, z=8-u$.
Since all points on $\overleftrightarrow{A B}$ are of the form $(-1-2 t, 3+2 t, 2-3 t)$ for some $t$, and all points on $\overleftrightarrow{C D}$ are of the form $(4 u, 2+3 u, 8-u)$ for some $u$, lines $\overleftrightarrow{A B}$ and $\overleftrightarrow{C D}$ intersect if and only if there are values of $t$ and $u$ for which these two points are the same. This gives us the system
$$\begin{aligned}
-1-2 t & =4 u \\
3+2 t & =2+3 u \\
2-3 t & =8-u
\end{aligned}$$

423

---

<!-- Page 424 -->

CHAPTER 12. VECTORS AND MATRICES IN THREE DIMENSIONS, PART 2

Adding the first equation to the second gives $2=2+7 u$, from which we have $u=0$. Substituting this into the first equation gives $t=-1 / 2$. However, $(t, u)=(-1 / 2,0)$ does not satisfy the third equation, so there is no solution to this system of equations. Therefore, $\overleftrightarrow{A B}$ and $\overleftrightarrow{C D}$ do not intersect.

Now that we have a sense of the geometry that results from considering all multiples of a single vector in three dimensions, let's take a look at linear combinations of pairs of vectors in three dimensions.

Problem 12.3: For each of the values of $\mathbf{v}$ and $\mathbf{w}$ given below, describe the graph of all points $(x, y, z)$ that satisfy $\left(\begin{array}{l}x \\ y \\ z\end{array}\right)=s \mathbf{v}+t \mathbf{w}$ for some values of $s$ and $t$.
(a) $\mathbf{v}=\mathbf{j}, \mathbf{w}=3 \mathbf{j}$
(b) $\mathbf{v}=\mathbf{i}, \mathbf{w}=\mathbf{j}$
(c) $\mathbf{v}=\mathbf{i}+\mathbf{k}, \mathbf{w}=\mathbf{k}$
(d) Your answer to part (a) should be a different type of geometric object than your answers to parts (b) and (c). Why does this occur?

Solution for Problem 12.3:
(a) We have
$$\left(\begin{array}{l}
x \\
y \\
z
\end{array}\right)=s \mathbf{v}+t \mathbf{w}=s \mathbf{j}+3 t \mathbf{j}=(s+3 t) \mathbf{j}=\left(\begin{array}{c}
0 \\
s+3 t \\
0
\end{array}\right)$$

Since $s$ and $t$ can take on any value, the expression $s+3 t$ can take on any value. Therefore, every point on the $y$-axis is in the graph, and no other points are. So, the graph is the $y$-axis, which is a line.
(b) We have
$$\left(\begin{array}{c}
x \\
y \\
z
\end{array}\right)=s \mathbf{v}+t \mathbf{w}=s \mathbf{i}+t \mathbf{j}=\left(\begin{array}{c}
s \\
t \\
0
\end{array}\right)$$

Since $s$ and $t$ can take on any value, every point in the $x y$-plane appears in the graph. There are no points in the graph with nonzero $z$-coordinate, so the graph is the $x y$-plane.
(c) We have
$$\left(\begin{array}{l}
x \\
y \\
z
\end{array}\right)=s \mathbf{v}+t \mathbf{w}=s \mathbf{i}+s \mathbf{k}+t \mathbf{k}=s \mathbf{i}+(s+t) \mathbf{k}=\left(\begin{array}{c}
s \\
0 \\
s+t
\end{array}\right) .$$

To see that any point $(a, 0, b)$ in the $x z$-plane is in the graph, note that letting $s=a$ and $t=b-a$ in the equation above gives $(x, y, z)=(a, 0, b)$. Therefore, the graph is the $x z$-plane.
(d) In the first part, $\mathbf{w}$ is a multiple of $\mathbf{v}$, and the resulting graph is a line. To check if the graph is always a line when $\mathbf{w}$ is a multiple of $\mathbf{v}$, we let $\mathbf{w}=c \mathbf{v}$ for some constant $c$. Then, we have
$$\left(\begin{array}{l}
x \\
y \\
z
\end{array}\right)=s \mathbf{v}+t \mathbf{w}=s \mathbf{v}+t c \mathbf{v}=(s+t c) \mathbf{v}$$

Since we can choose any values of $s$ and $t$, the expression $(s+t c) \mathbf{v}$ can be any multiple of $\mathbf{v}$. Therefore, the graph is a line through the origin with direction vector $\mathbf{v}$.

In parts (b) and (c), $\mathbf{w}$ cannot be expressed as a constant times $\mathbf{v}$, and the resulting graph in each case is a plane, not a line.

424

---

<!-- Page 425 -->

12.1. LINES AND PLANES IN THREE DIMENSIONS

Just as we did in two dimensions, we say that a pair of vectors $\mathbf{v}$ and $\mathbf{w}$ are linearly dependent if and only if there are nonzero scalars $a_{1}$ and $a_{2}$ such that $a_{1} \mathbf{v}+a_{2} \mathbf{w}=\mathbf{0}$. Otherwise, the vectors are linearly independent. Since we can write $\mathbf{w}=c \mathbf{v}$ as $c \mathbf{v}+(-1) \mathbf{w}=0$, our work in part (d) above shows that that the graph of
$$\left(\begin{array}{l}
x \\
y \\
z
\end{array}\right)=s \mathbf{v}+t \mathbf{w}$$
is a line if $\mathbf{v}$ and $\mathbf{w}$ are linearly dependent (and not both $\mathbf{0}$ ).
Our work in parts (b) and (c) gives two examples in which $\mathbf{v}$ and $\mathbf{w}$ are linearly independent and the resulting graph fits our geometric concept of a plane. Let's think a little bit about why the graph of all points corresponding to linear combinations of two linearly independent vectors matches our geometric idea of a plane. What follows is not intended to be a rigorous proof, but rather to give us some intuition for why our geometric idea of a plane fits with the graph of all linear combinations of two linearly independent vectors. We'll start with the fact that any three noncollinear points in space define a plane-the plane that contains the triangle with those three points as vertices.

Suppose we start with the three noncollinear points $V, W$, and the origin, which we'll call $O$. We'll let $\mathbf{v}=\vec{V}$ and $\mathbf{w}=\vec{W}$, so $\mathbf{v}$ and $\mathbf{w}$ drawn from the origin are two sides of $\triangle V O W$. Let $\mathcal{P}$ be the plane that contains this triangle, and let $\ell_{\mathrm{v}}$ and $\ell_{\mathrm{w}}$ be the lines through the origin that contain $\mathbf{v}$ and $\mathbf{w}$, respectively. Then, lines $\ell_{\mathbf{v}}$ and $\ell_{\mathbf{w}}$ are in $\mathcal{P}$. Since any multiple of $\mathbf{v}$ lies along $\ell_{\mathbf{v}}$ and any multiple of $\mathbf{w}$ lies along $\ell_{\mathbf{w}}$, the vectors $s \mathbf{v}$ and $t \mathbf{w}$ are also in $\mathcal{P}$. We locate $s \mathbf{v}+t \mathbf{w}$ by completing the parallelogram with one vertex at the origin and sides $s \mathbf{v}$ and $t \mathbf{w}$, as shown at right. Since the triangle with sides $s \mathbf{v}$ and $t \mathbf{w}$ is in $\mathcal{P}$, so is this parallelogram, which means that $s \mathbf{v}+t \mathbf{w}$ is in $\mathcal{P}$, too.

This gives us some idea why $s \mathbf{v}+t \mathbf{w}$ must be in the same plane as $\mathbf{v}$ and $\mathbf{w}$, but it doesn't explain why every point in this plane is in the graph of
$$\left(\begin{array}{l}
x \\
y \\
z
\end{array}\right)=s \mathbf{v}+t \mathbf{w} .$$

Suppose that $Q$ is a point in plane $\mathcal{P}$. If $Q$ is on $\ell_{\mathbf{v}}$ or $\ell_{\mathbf{w}}$, then we clearly have $\vec{Q}=s \mathbf{v}+t \mathbf{w}$ for some $s$ and $t$. Otherwise, we draw lines through $Q$ parallel to $\ell_{\mathbf{v}}$ and $\ell_{\mathbf{w}}$, thereby completing a parallelogram $O A Q B$, as shown. Since $A$ is on $\ell_{\mathbf{v}}$ and $B$ is on $\ell_{\mathbf{w}}$, we have $\vec{A}=s \mathbf{v}$ and $\vec{B}=t \mathbf{w}$ for some constants $s$ and $t$. Therefore, we have
$$\vec{Q}=\vec{A}+\vec{B}=s \mathbf{v}+t \mathbf{w},$$
which means that $Q$ is in the graph of (12.2).

The graph of linear combinations of two linearly independent vectors so nicely matches our concept of a plane that we use it to define a plane algebraically.

425

---

<!-- Page 426 -->

CHAPTER 12. VECTORS AND MATRICES IN THREE DIMENSIONS, PART 2

Definition: Let $\mathbf{v}$ and $\mathbf{w}$ be linearly independent. The plane through the origin generated by $\mathbf{v}$ and $\mathbf{w}$ is the graph of the parametric equation
$$\left(\begin{array}{l}
x \\
y \\
z
\end{array}\right)=s \mathbf{v}+t w,$$
where $s$ and $t$ are parameters.
We will say that a vector $\mathbf{v}$ is in a plane $\mathcal{P}$ if there is some pair of points in $\mathcal{P}$ such that the vector between the points is $\mathbf{v}$. So, for example, the vector $\mathbf{i}+\mathbf{j}$ is "in the $x y$-plane."

Our definition only covers planes through the origin. What about planes that don't pass through the origin?
Problem 12.4:
(a) Describe the graph of the parametric equation $\left(\begin{array}{l}x \\ y \\ z\end{array}\right)=\left(\begin{array}{c}-1 \\ 3 \\ 4\end{array}\right)+s \mathbf{i}+t \mathbf{j}$.
(b) How is the graph in part (a) related to the graph of $\left(\begin{array}{l}x \\ y \\ z\end{array}\right)=s \mathbf{i}+t \mathbf{j}$ ?

Solution for Problem 12.4:
(a) We have
$$\begin{aligned}
\left(\begin{array}{l}
x \\
y \\
z
\end{array}\right) & =\left(\begin{array}{c}
-1 \\
3 \\
4
\end{array}\right)+s \mathbf{i}+t \mathbf{j} \\
& =\left(\begin{array}{c}
-1 \\
3 \\
4
\end{array}\right)+\left(\begin{array}{l}
s \\
0 \\
0
\end{array}\right)+t\left(\begin{array}{c}
0 \\
t \\
0
\end{array}\right) \\
& =\left(\begin{array}{c}
-1+s \\
3+t \\
4
\end{array}\right) .
\end{aligned}$$

Since $s$ and $t$ can take on any values, the first two coordinates of ( $-1+s, 3+t, 4$ ) can be anything. So, the graph consists of all the points in space with $z=4$, which means that the graph is a plane parallel to the $x y$-plane and 4 units above the $x y$-plane.

Another way to think about this is to start with the plane generated by $\mathbf{i}$ and $\mathbf{j}$. Then, we form the graph of
$$\left(\begin{array}{l}
x \\
y \\
z
\end{array}\right)=\left(\begin{array}{c}
-1 \\
3 \\
4
\end{array}\right)+s \mathbf{i}+t \mathbf{j}$$
by adding $\left(\begin{array}{c}-1 \\ 3 \\ 4\end{array}\right)$ to every vector from the origin to a point in a plane generated by $\mathbf{i}$ and $\mathbf{j}$. In other words, we translate the plane generated by $\mathbf{i}$ and $\mathbf{j}$ by the vector $\left(\begin{array}{c}-1 \\ 3 \\ 4\end{array}\right)$.

426

---

<!-- Page 427 -->

12.1. LINES AND PLANES IN THREE DIMENSIONS

Yet another way to think about it is that we form the graph by starting from $(-1,3,4)$, and then traveling by the vector $s \mathbf{i}+t \mathbf{j}$ to find $(x, y, z)$. Starting from a point and then considering the result of traveling by every possible linear combination of two linearly independent vectors is exactly how we (algebraically) defined a plane through the origin. The only difference here is that we are starting from ( $-1,3,4$ ) instead of the origin. This observation inspires a definition of a plane defined by two linearly independent vectors and a point through which the plane passes:

Definition: Let $\mathbf{v}$ and $\mathbf{w}$ be linearly independent. The plane through the point ( $a, b, c$ ) generated by $\mathbf{v}$ and $\mathbf{w}$ is the graph of the parametric equation
$$\left(\begin{array}{l}
x \\
y \\
z
\end{array}\right)=\left(\begin{array}{l}
a \\
b \\
c
\end{array}\right)+s \mathbf{v}+t \mathbf{w},$$
where $s$ and $t$ are parameters.

Notice that when we have $(a, b, c)=(0,0,0)$, this definition matches our earlier definition of a plane through the origin.
(b) The graph of $\left(\begin{array}{l}x \\ y \\ z\end{array}\right)=s \mathbf{i}+t \mathbf{j}$ is the $x y$-plane, as described in part (b) of Problem 12.3. This plane is the graph of $z=0$. The plane in part (a) is the graph of $z=4$. We cannot have both $z=0$ and $z=4$, so the plane in this part and the plane in part (a) do not intersect.

We say that two planes are parallel if either they don't intersect or they are the same plane. The planes in Problem 12.4 are generated by the same two vectors, and we found that the resulting planes are parallel. Geometrically, this makes sense. The vectors that generate a plane determine the "direction" of the plane, so it's not surprising that the two planes generated by the same vectors are parallel. We can use our algebraic definition of a plane to prove that this is the case.

Problem 12.5: Suppose $\mathbf{v}$ and $\mathbf{w}$ are linearly independent. Show that the graphs of the parametric equations
$$\begin{array}{l}
\left(\begin{array}{l}
x \\
y \\
z
\end{array}\right)=\left(\begin{array}{l}
a \\
b \\
c
\end{array}\right)+s \mathbf{v}+t \mathbf{w} \\
\left(\begin{array}{l}
x \\
y \\
z
\end{array}\right)=\left(\begin{array}{l}
a^{\prime} \\
b^{\prime} \\
c^{\prime}
\end{array}\right)+p \mathbf{v}+q \mathbf{w}
\end{array}$$
are parallel.

Solution for Problem 12.5: The two graphs have a point in common if and only if there are scalars $s_{1}, t_{1}, p_{1}, q_{1}$ such that
$$\left(\begin{array}{l}
a \\
b \\
c
\end{array}\right)+s_{1} \mathbf{v}+t_{1} \mathbf{w}=\left(\begin{array}{l}
a^{\prime} \\
b^{\prime} \\
c^{\prime}
\end{array}\right)+p_{1} \mathbf{v}+q_{1} \mathbf{w} .$$

427

---

<!-- Page 428 -->

CHAPTER 12. VECTORS AND MATRICES IN THREE DIMENSIONS, PART 2

If there are no such scalars, then the graphs do not intersect, and the graphs are parallel. All that's left to show is that if such scalars exist, then the graphs are the same.

For any point $\left(x_{0}, y_{0}, z_{0}\right)$ on (12.3), there are scalars $s_{0}$ and $t_{0}$ such that
$$\left(\begin{array}{l}
x_{0} \\
y_{0} \\
z_{0}
\end{array}\right)=\left(\begin{array}{l}
a \\
b \\
c
\end{array}\right)+s_{0} \mathbf{v}+t_{0} \mathbf{w}$$

To see that $\left(x_{0}, y_{0}, z_{0}\right)$ is on (12.4), we first rearrange (12.5) as
$$\left(\begin{array}{l}
a^{\prime} \\
b^{\prime} \\
c^{\prime}
\end{array}\right)=\left(\begin{array}{l}
a \\
b \\
c
\end{array}\right)+\left(s_{1}-p_{1}\right) \mathbf{v}+\left(t_{1}-q_{1}\right) \mathbf{w} .$$

Now, letting $p=p_{1}-s_{1}+s_{0}$ and $q=q_{1}-t_{1}+t_{0}$ in (12.4) gives
$$\begin{aligned}
\left(\begin{array}{l}
x \\
y \\
z
\end{array}\right) & =\left(\begin{array}{l}
a^{\prime} \\
b^{\prime} \\
c^{\prime}
\end{array}\right)+\left(p_{1}-s_{1}+s_{0}\right) \mathbf{v}+\left(q_{1}-t_{1}+t_{0}\right) \mathbf{w} \\
& =\left(\left(\begin{array}{l}
a \\
b \\
c
\end{array}\right)+\left(s_{1}-p_{1}\right) \mathbf{v}+\left(t_{1}-q_{1}\right) \mathbf{w}\right)+\left(p_{1}-s_{1}+s_{0}\right) \mathbf{v}+\left(q_{1}-t_{1}+t_{0}\right) \mathbf{w} \\
& =\left(\begin{array}{l}
a \\
b \\
c
\end{array}\right)+s_{0} \mathbf{v}+t_{0} \mathbf{w},
\end{aligned}$$
which equals our expression for $\left(\begin{array}{l}x_{0} \\ y_{0} \\ z_{0}\end{array}\right)$ from (12.6). Therefore, $\left(x_{0}, y_{0}, z_{0}\right)$ is in both graphs. Similarly, we can show that any point in the graph of (12.4) is in the graph of (12.3), so the graphs of the two equations are the same.

Since the planes that are the graphs of (12.3) and (12.4) either don't intersect or are the same, they are parallel.

Exercises
12.1.1 Find vectors $\mathbf{v}$ and $\mathbf{w}$ such that
$$\left(\begin{array}{l}
x \\
y \\
z
\end{array}\right)=\mathbf{v}+\mathbf{w} t$$
describes the line through $(-4,5,0)$ and $(-5,-1,2)$. Are the vectors you found the only possible values of $\mathbf{v}$ and $\mathbf{w}$ ?
12.1.2 Find a vector that is parallel to the graph of $x=4-2 t, y=2+t, z=2-3 t$.
12.1.3 Let $\mathcal{P}$ be the plane through $(-2,-1,4)$ generated by $2 \mathbf{i}-\mathbf{j}+\mathbf{k}$ and $-3 \mathbf{i}+2 \mathbf{k}$. Show that $(10,-4,3)$ is on $\mathcal{P}$, but ( $-1,5,2$ ) is not.
12.1.4 Find $x$ if $x \mathbf{i}+7 \mathbf{j}+10 \mathbf{k}$ is in the plane through the points $(-1,2,4),(3,-1,2)$, and $(5,1,6)$.
12.2 More Planes in Three Dimensions

Now that we have an algebraic definition of a plane, we can use algebraic tools on problems involving planes. In this section, we'll explore these tools. We'll also address the question of what happens when we consider linear

428

---

<!-- Page 429 -->

12.2. MORE PLANES IN THREE DIMENSIONS

combinations of three vectors in three dimensions.
Problems
Problem 12.6: Let $\mathbf{v}$ and $\mathbf{w}$ be linearly independent and let $\mathbf{a}$ and $\mathbf{b}$ be linearly independent. In this problem, we show that if $\mathbf{v}$ and $\mathbf{w}$ are in the plane through the origin generated by $\mathbf{a}$ and $\mathbf{b}$, then the graphs of
$$\left(\begin{array}{c}
x \\
y \\
z
\end{array}\right)=s \mathbf{v}+t \mathbf{w} \quad \text { and } \quad\left(\begin{array}{l}
x \\
y \\
z
\end{array}\right)=p \mathbf{a}+q \mathbf{b}$$
are the same.
(a) Show that for every choice of $s$ and $t$, we can find values of $p$ and $q$ such that both equations produce the same point ( $x, y, z$ ). Hints: 32,274
(b) Show that for every choice of $p$ and $q$, we can find values of $s$ and $t$ such that both equations produce the same point ( $x, y, z$ ). Hints: 5

Problem 12.7: In this problem, we find an equation whose graph is the plane through the points $(0,4,0)$, $(3,-1,-3)$, and $(2,-2,-4)$.
(a) Find a parametric equation whose graph is the plane.
(b) Show that there is an equation of the form $a x+b y+c z=d$, where $a, b, c$, and $d$ are constants, whose graph contains every point in the plane.

Problem 12.8: In this problem, we show that the graph of $n_{1} x+n_{2} y+n_{3} z=d$ is a plane, where $n_{1}, n_{2}, n_{3}$ and $d$ are constants and at least one of $n_{1}, n_{2}, n_{3}$ is nonzero.
(a) Suppose $n_{1} \neq 0$. Solve the equation for $x$. Use the result to express the equation in a form that fits our algebraic definition of a plane.
(b) Complete the proof by addressing the case $n_{1}=0$.

Problem 12.9: Let $\mathbf{v}$ and $\mathbf{w}$ be linearly independent and let $x_{0}, y_{0}$, and $z_{0}$ be constants.
(a) Show that we can always eliminate the parameters from the parametric equation
$$\left(\begin{array}{l}
x \\
y \\
z
\end{array}\right)=\left(\begin{array}{l}
x_{0} \\
y_{0} \\
z_{0}
\end{array}\right)+s \mathbf{v}+t \mathbf{w}$$
to produce an equation of the form $n_{1} x+n_{2} y+n_{3} z=d$, where $n_{1}, n_{2}, n_{3}$, and $d$ are constants.
(b) Show that every point in the graph of the equation of the form $n_{1} x+n_{2} y+n_{3} z=d$ produced by eliminating the parameters is in the graph of the original parametric equation.

Problem 12.10: In this problem, we find a vector that is orthogonal to every vector in the plane through the origin generated by $\mathbf{v}=3 \mathbf{i}+4 \mathbf{j}-\mathbf{k}$ and $\mathbf{w}=4 \mathbf{i}-2 \mathbf{j}+3 \mathbf{k}$.
(a) Find an equation of the form $n_{1} x+n_{2} y+n_{3} z=0$ whose graph is the plane through the origin generated by $\mathbf{v}$ and $\mathbf{w}$.
(b) Let $\mathbf{n}=n_{1} \mathbf{i}+n_{2} \mathbf{j}+n_{3} \mathbf{k}$. Show that $\mathbf{n}$ is orthogonal to both $\mathbf{v}$ and $\mathbf{w}$.
(c) Is $\mathbf{n}$ orthogonal to every vector in the plane?

429

---

<!-- Page 430 -->

CHAPTER 12. VECTORS AND MATRICES IN THREE DIMENSIONS, PART 2

Problem 12.11: In Problem 12.7, you found the equation of a plane through the points $(0,4,0),(3,-1,-3)$, and $(2,-2,-4)$. This answer should be of the form $n_{1} x+n_{2} y+n_{3} z=d$, where $n_{1}, n_{2}, n_{3}$, and $d$ are constants. Is $\mathbf{n}=n_{1} \mathbf{i}+n_{2} \mathbf{j}+n_{3} \mathbf{k}$ orthogonal to the vector between any two points in the plane?

Problem 12.12: Show that the vector
$$\mathbf{n}=n_{1} \mathbf{i}+n_{2} \mathbf{j}+n_{3} \mathbf{k}$$
is orthogonal to the vector between any two points in the graph of
$$n_{1} x+n_{2} y+n_{3} z=d$$
where $n_{1}, n_{2}, n_{3}$, and $d$ are constants.
Problem 12.13:
(a) Find an expression for $\operatorname{proj}_{\mathbf{w}} \mathbf{v}$ in terms of $\mathbf{v} \cdot \mathbf{w},\|\mathbf{w}\|$, and $\mathbf{w}$.
(b) The distance between a point and a plane is the length of the shortest segment between the point and a point in the plane. Find an expression for the distance between the point ( $x_{0}, y_{0}, z_{0}$ ) and the plane $a x+b y+c z+d=0$, where $a, b, c$, and $d$ are constants.

Problem 12.14: Let $\mathbf{u}, \mathbf{v}$, and $\mathbf{w}$ be vectors in three dimensions such that $\mathbf{v}$ and $\mathbf{w}$ are linearly independent. We will explore the graph of the parametric equation
$$\left(\begin{array}{l}
x \\
y \\
z
\end{array}\right)=r \mathbf{u}+s \mathbf{v}+t \mathbf{w}$$
(a) Show that if $\mathbf{u}$ is a linear combination of $\mathbf{v}$ and $\mathbf{w}$, then the graph of Equation (12.8) is a plane.
(b) Suppose that $\mathbf{u}$ is not a linear combination of $\mathbf{v}$ and $\mathbf{w}$. Then, what is the graph of
$$\left(\begin{array}{l}
x \\
y \\
z
\end{array}\right)=\mathbf{u}+s \mathbf{v}+t \mathbf{w} ?$$
(Notice that the coefficient of $\mathbf{u}$ here is 1 , not $r$.)
(c) Suppose that $\mathbf{u}$ is not a linear combination of $\mathbf{v}$ and $\mathbf{w}$. Then, what is the graph of
$$\left(\begin{array}{l}
x \\
y \\
z
\end{array}\right)=2 u+s v+t w ?$$

How is your answer related to the graph in part (b)?
(d) Suppose that $\mathbf{u}$ is not a linear combination of $\mathbf{v}$ and $\mathbf{w}$. What is the graph of Equation (12.8)?

Problem 12.15: We say that $\mathbf{v}_{1}, \mathbf{v}_{2}$, and $\mathbf{v}_{3}$ are linearly dependent if there exist constants $a_{1}, a_{2}$, and $a_{3}$, not all 0 , such that $a_{1} \mathbf{v}_{1}+a_{2} \mathbf{v}_{2}+a_{3} \mathbf{v}_{3}=\mathbf{0}$. Otherwise, we say the vectors are linearly independent. Show that if $\mathbf{u}, \mathbf{v}$, and w are linearly independent, then for any $(x, y, z)$, then there is exactly one ordered triple $(r, s, t)$ such that
$$\left(\begin{array}{l}
x \\
y \\
z
\end{array}\right)=r \mathbf{u}+s \mathbf{v}+t \mathbf{w}$$

430

---

<!-- Page 431 -->

12.2. MORE PLANES IN THREE DIMENSIONS

Problem 12.6: Let $\mathbf{v}$ and $\mathbf{w}$ be linearly independent and let $\mathbf{a}$ and $\mathbf{b}$ be linearly independent. Show that if $\mathbf{v}$ and $\mathbf{w}$ are in the plane through the origin generated by $\mathbf{a}$ and $\mathbf{b}$, then the graphs of
$$\left(\begin{array}{l}
x \\
y \\
z
\end{array}\right)=s \mathbf{v}+t \mathbf{w} \quad \text { and } \quad\left(\begin{array}{l}
x \\
y \\
z
\end{array}\right)=p \mathbf{a}+q \mathbf{b}$$
are the same.

Solution for Problem 12.6: We must show that every point in the graph of
$$\left(\begin{array}{l}
x \\
y \\
z
\end{array}\right)=s \mathbf{v}+t \mathbf{w}$$
is also in the graph of
$$\left(\begin{array}{l}
x \\
y \\
z
\end{array}\right)=p \mathbf{a}+q \mathbf{b}$$
and vice versa.
We'll first show that every point in the graph of (12.9) is on the graph of (12.10). We do so by showing that for any choice of $s$ and $t$ in (12.9), we can find values of $p$ and $q$ in (12.10) that produce the same ( $x, y, z$ ).

We are given that $\mathbf{v}$ and $\mathbf{w}$ are in the graph of (12.10), so there are scalars $p_{1}, q_{1}, p_{2}, q_{2}$ such that
$$\begin{aligned}
\mathbf{v} & =p_{1} \mathbf{a}+q_{1} \mathbf{b}, \\
\mathbf{w} & =p_{2} \mathbf{a}+q_{2} \mathbf{b} .
\end{aligned}$$

Substituting these into (12.9) gives
$$\left(\begin{array}{l}
x \\
y \\
z
\end{array}\right)=s\left(p_{1} \mathbf{a}+q_{1} \mathbf{b}\right)+t\left(p_{2} \mathbf{a}+q_{2} \mathbf{b}\right)=\left(s p_{1}+t p_{2}\right) \mathbf{a}+\left(s q_{1}+t q_{2}\right) \mathbf{b} .$$

So, for any choice of $s$ and $t$ in (12.9), letting $p=s p_{1}+t p_{2}$ and $q=s q_{1}+t q_{2}$ in (12.10) produces the same ( $x, y, z$ ). Therefore, every point in the graph of (12.9) is also in the graph of (12.10).

We must now show that we can go the other way. Specifically, we must show that for any choice of $p$ and $q$ in (12.10), we can find $s$ and $t$ in (12.9) that produces the same ( $x, y, z$ ). Equation (12.11) gives us a good starting point. The graph of Equation (12.11) is the same as the graph of Equation (12.9). So, if for any $p$ and $q$, we can find $s$ and $t$ such that
$$\begin{array}{l}
p=s p_{1}+t p_{2} \\
q=s q_{1}+t q_{2}
\end{array}$$
then the graphs of (12.9) and (12.10) are the same. This system has a solution $(s, t)$ for any $(p, q)$ if and only if $\left|\begin{array}{ll}p_{1} & p_{2} \\ q_{1} & q_{2}\end{array}\right| \neq 0$. To show that this determinant is nonzero, we go back to the definitions of $p_{1}, q_{1}, p_{2}, q_{2}$. These are the scalars such that
$$\begin{aligned}
\mathbf{v} & =p_{1} \mathbf{a}+q_{1} \mathbf{b}, \\
\mathbf{w} & =p_{2} \mathbf{a}+q_{2} \mathbf{b} .
\end{aligned}$$

431

---

<!-- Page 432 -->

CHAPTER 12. VECTORS AND MATRICES IN THREE DIMENSIONS, PART 2

If $\left|\begin{array}{ll}p_{1} & p_{2} \\ q_{1} & q_{2}\end{array}\right|=0$, then one column of $\left(\begin{array}{ll}p_{1} & p_{2} \\ q_{1} & q_{2}\end{array}\right)$ must be a multiple of the other. But this would mean that one of $\mathbf{v}$ and $\mathbf{w}$ is a multiple of the other, which we can't have because $\mathbf{v}$ and $\mathbf{w}$ are linearly independent. Therefore, we conclude that $\left|\begin{array}{ll}p_{1} & p_{2} \\ q_{1} & q_{2}\end{array}\right| \neq 0$, which means that for every pair $(p, q)$, we can find constants $s$ and $t$ such that $s p_{1}+t p_{2}=p$ and $s q_{1}+t q_{2}=q$. So, for every choice of $p$ and $q$ in (12.10), we can find values of $s$ and $t$ in (12.9) that produce the same $(x, y, z)$.

We have therefore shown that every point in the graph of (12.9) is in the graph of (12.10), and vice versa. We conclude that the graphs of these equations are the same. In other words, the plane generated by $\mathbf{v}$ and $\mathbf{w}$ is the same as the plane generated by $\mathbf{a}$ and $\mathbf{b}$.

As a key step in our solution to Problem 12.6, we proved that if linearly independent vectors $\mathbf{v}$ and $\mathbf{w}$ are both in the plane generated by linearly independent vectors $\mathbf{a}$ and $\mathbf{b}$, then $\mathbf{a}$ and $\mathbf{b}$ are in the plane generated by $\mathbf{v}$ and w. This statement is equivalent to the following:

> Important: If linearly independent vectors $\mathbf{v}$ and $\mathbf{w}$ are both linear combinations of linearly
> ! independent vectors $\mathbf{a}$ and $\mathbf{b}$, then $\mathbf{a}$ and $\mathbf{b}$ are both linear combinations of $\mathbf{v}$ and $\mathbf{w}$.

Since we can choose $\mathbf{v}$ and $\mathbf{w}$ to be any two linearly independent vectors in the plane generated by a and $\mathbf{b}$, our work in Problem 12.6 also tells us that:

> Important:
> !

Any two linearly independent vectors in a plane can be used to generate the plane.

Also, there's nothing special about planes through the origin. We could have used the same steps we used in Problem 12.6 to show that any two linearly independent vectors in a plane $\mathcal{P}$ through a point ( $a, b, c$ ) generate $\mathcal{P}$.

Problem 12.7: In this problem, we find an equation whose graph is the plane through the points ( $0,4,0$ ), $(3,-1,-3)$, and $(2,-2,-4)$.
(a) Find a parametric equation whose graph is the plane.
(b) Show that there is an equation of the form $a x+b y+c z=d$, where $a, b, c$, and $d$ are constants, whose graph contains every point in the plane.

Solution for Problem 12.7:
(a) We know how to find equations for a plane given a point in the plane and two vectors contained by the plane. We can use the three given points to produce the two needed vectors. Let ( $0,4,0$ ) be $A$, let point $(3,-1,-3)$ be $B$, and let $(2,-2,-4)$ be $C$. Then, the plane is the graph of
$$\left(\begin{array}{l}
x \\
y \\
z
\end{array}\right)=\vec{A}+s \overrightarrow{A B}+t \overrightarrow{A C}=\left(\begin{array}{l}
0 \\
4 \\
0
\end{array}\right)+s\left(\begin{array}{c}
3-0 \\
-1-4 \\
-3-0
\end{array}\right)+t\left(\begin{array}{c}
2-0 \\
-2-4 \\
-4-0
\end{array}\right)=\left(\begin{array}{l}
0 \\
4 \\
0
\end{array}\right)+s\left(\begin{array}{c}
3 \\
-5 \\
-3
\end{array}\right)+t\left(\begin{array}{c}
2 \\
-6 \\
-4
\end{array}\right) .$$

We could have replaced $\left(\begin{array}{l}0 \\ 4 \\ 0\end{array}\right)$ with $\left(\begin{array}{c}3 \\ -1 \\ -3\end{array}\right),\left(\begin{array}{c}2 \\ -2 \\ -4\end{array}\right)$, or any other vector corresponding to a point in the plane.

432

---

<!-- Page 433 -->

12.2. MORE PLANES IN THREE DIMENSIONS
(b) We can write our parametric equation as a system of equations:
$$\begin{array}{l}
x=3 s+2 t \\
y=4-5 s-6 t \\
z=-3 s-4 t
\end{array}$$

We produce an equation involving only $x, y$, and $z$ by eliminating the parameters. Adding the first and third equations gives $x+z=-2 t$. Subtracting 5 times the third equation from 3 times the second gives $3 y-5 z=12+2 t$. Adding $x+z=-2 t$ to $3 y-5 z=12+2 t$ gives
$$x+3 y-4 z=12$$

Our solution to Problem 12.7 doesn't show that the graph of the parametric equation is the same as the graph of $x+3 y-4 z=12$. We only showed that every point in the graph of the parametric equation is in the graph of $x+3 y-4 z=12$. We didn't show that every point in the graph of $x+3 y-4 z=12$ is in the graph of the parametric equations. We'll defer that proof to Problem 12.9, where we tackle the general case.

Back in Chapter 9, we showed that the graph in two dimensions of any equation of the form $a x+b y=c$ is a line, and that every line in two dimensions is the graph of an equation of this form. Our work in Problem 12.7 suggests we might be able to prove a similar statement about planes in three dimensions.

In the next two problems, we show that every plane in three dimensions is the graph of an equation of the form $n_{1} x+n_{2} y+n_{3} z=d$. We do so by first showing that the graph of every equation of the form $n_{1} x+n_{2} y+n_{3} z=d$ is the same as the graph of some equation of the form
$$\left(\begin{array}{l}
x \\
y \\
z
\end{array}\right)=\left(\begin{array}{l}
x_{0} \\
y_{0} \\
z_{0}
\end{array}\right)+s \mathbf{v}+t \mathbf{w},$$
where $\mathbf{v}$ and $\mathbf{w}$ are linearly independent. Then, we use this fact to show that the graph of any equation of the form (12.12) is the same as the graph of some equation of the form $n_{1} x+n_{2} y+n_{3} z=d$. Make sure you see why both of these steps are necessary-the first tells us that the graph of $n_{1} x+n_{2} y+n_{3} z=d$ is always a plane, and the second tells us that every plane is the graph of some equation of this form.

We go through this trouble for several reasons. Sometimes equations of the form $n_{1} x+n_{2} y+n_{3} z=d$ are much more convenient to work with than equations of the form (12.12). More importantly, we will use these forms together to explore graphs of linear combinations of three linearly independent vectors. Finally, in Section 12.3, we'll use them to discover a very useful operation for vectors in three dimensions.

Problem 12.8: Show that the graph of $n_{1} x+n_{2} y+n_{3} z=d$ is a plane, where $n_{1}, n_{2}, n_{3}$, and $d$ are constants and at least one of $n_{1}, n_{2}, n_{3}$ is nonzero.

Solution for Problem 12.8: To show that the graph must be a plane, we must show that the graph fits our algebraic definition of a plane. This means we have to show that it is the graph of a parametric equation of the form
$$\left(\begin{array}{l}
x \\
y \\
z
\end{array}\right)=\left(\begin{array}{l}
a \\
b \\
c
\end{array}\right)+s \mathbf{v}+t \mathbf{w}$$
for some linearly independent vectors $\mathbf{v}$ and $\mathbf{w}$ and some constants $a, b$, and $c$. To see how, let's focus on $x$ in the parametric form. We wish to have $x=a+s v_{1}+t w_{1}$, where $v_{1}$ and $w_{1}$ are the first components of $\mathbf{v}$ and $\mathbf{w}$. On the right side of the parametric equation, only $s$ and $t$ can vary- $a, v_{1}$, and $w_{1}$ are constants. So, we seek an equation of the form $x=a+s v_{1}+t w_{1}$, in which $x$ is expressed in terms of two variables.

433

---

<!-- Page 434 -->

CHAPTER 12. VECTORS AND MATRICES IN THREE DIMENSIONS, PART 2

If $x \neq 0$, we can solve the given equation $n_{1} x+n_{2} y+n_{3} z=d$ for $x$ in terms of the variables $y$ and $z$, which gives us
$$x=\frac{d}{n_{1}}-\frac{n_{2}}{n_{1}} y-\frac{n_{3}}{n_{1}} z .$$

So, we can simply let $y=s$ and $z=t$ be the parameters. Therefore, the graph of $n_{1} x+n_{2} y+n_{3} z=d$ is the graph of
$$\left(\begin{array}{l}
x \\
y \\
z
\end{array}\right)=\left(\begin{array}{c}
d / n_{1} \\
0 \\
0
\end{array}\right)+s\left(\begin{array}{c}
-n_{2} / n_{1} \\
1 \\
0
\end{array}\right)+t\left(\begin{array}{c}
-n_{3} / n_{1} \\
0 \\
1
\end{array}\right) .$$

The vectors $\left(\begin{array}{c}-n_{2} / n_{1} \\ 1 \\ 0\end{array}\right)$ and $\left(\begin{array}{c}-n_{3} / n_{1} \\ 0 \\ 1\end{array}\right)$ are linearly independent, since the only way to make the last two components of $s\left(\begin{array}{c}-n_{2} / n_{1} \\ 1 \\ 0\end{array}\right)+t\left(\begin{array}{c}-n_{3} / n_{1} \\ 0 \\ 1\end{array}\right)$ equal 0 is to let $s=t=0$. Therefore, the graph of (12.13) is a plane.

If $n_{1}=0$, then at least one of $n_{2}$ and $n_{3}$ is nonzero. We can solve $n_{1} x+n_{2} y+n_{3} z=d$ for the variable corresponding to the nonzero coefficient just as we solved for $x$ above. Then, we can use the other two variables as the parameters, just as we used $y$ and $z$ as parameters above. So, in this case, we can still express the equation in a parametric form matching our algebraic definition of a plane.

Important: If $a, b, c$, and $d$ are constants and at least one of $a, b$, and $c$ is nonzero, then the
! graph of $a x+b y+c z=d$ is a plane.

Problem 12.9: Let $\mathbf{v}$ and $\mathbf{w}$ be linearly independent and let $x_{0}, y_{0}$, and $z_{0}$ be constants.
(a) Show that we can always eliminate the parameters from the parametric equation
$$\left(\begin{array}{l}
x \\
y \\
z
\end{array}\right)=\left(\begin{array}{l}
x_{0} \\
y_{0} \\
z_{0}
\end{array}\right)+s \mathbf{v}+t \mathbf{w}$$
to produce an equation of the form
$$n_{1} x+n_{2} y+n_{3} z=d$$
where $n_{1}, n_{2}, n_{3}$, and $d$ are constants.
(b) Show that every point in the graph of the equation of the form $n_{1} x+n_{2} y+n_{3} z=d$ produced by eliminating the parameters is in the graph of the original parametric equation.

Solution for Problem 12.9:
(a) We write the parametric equation as the system
$$\begin{array}{l}
x=x_{0}+s v_{1}+t w_{1} \\
y=y_{0}+s v_{2}+t w_{2} \\
z=z_{0}+s v_{3}+t w_{3}
\end{array}$$

We could eliminate the parameters one at a time, but instead, we'll be a little more clever, and try to eliminate them both at once. We think to do this by noticing that the last two terms in each of the equations

434

---

<!-- Page 435 -->

12.2. MORE PLANES IN THREE DIMENSIONS

above are a dot product:
$$\begin{array}{l}
x=x_{0}+\binom{s}{t} \cdot\binom{v_{1}}{w_{1}}, \\
y=y_{0}+\binom{s}{t} \cdot\binom{v_{2}}{w_{2}}, \\
z=z_{0}+\binom{s}{t} \cdot\binom{v_{3}}{w_{3}} .
\end{array}$$

This is nice because it allows us to deal with both $s$ and $t$ at the same time-if we eliminate $\binom{s}{t}$ from the system, then we have eliminated both parameters. We now wish to show that there are constants $n_{1}, n_{2}$, and $n_{3}$, not all 0 , such that we can multiply the first equation by $n_{1}$, the second by $n_{2}$, and the third by $n_{3}$, add the three resulting equations, and thereby eliminate both parameters. After we perform this multiplication and addition, we have
$$\begin{aligned}
n_{1} x+n_{2} y+n_{3} z & =n_{1} x_{0}+n_{2} y_{0}+n_{3} z_{0}+n_{1}\binom{s}{t} \cdot\binom{v_{1}}{w_{1}}+n_{2}\binom{s}{t} \cdot\binom{v_{2}}{w_{2}}+n_{3}\binom{s}{t} \cdot\binom{v_{3}}{w_{3}} \\
& =n_{1} x_{0}+n_{2} y_{0}+n_{3} z_{0}+\binom{s}{t} \cdot\left(n_{1}\binom{v_{1}}{w_{1}}+n_{2}\binom{v_{2}}{w_{2}}+n_{3}\binom{v_{3}}{w_{3}}\right) .
\end{aligned}$$

We can eliminate $\binom{s}{t}$ if we can choose $n_{1}, n_{2}, n_{3}$, not all 0 , such that $n_{1}\binom{v_{1}}{w_{1}}+n_{2}\binom{v_{2}}{w_{2}}+n_{3}\binom{v_{3}}{w_{3}}$ is $\mathbf{0}$. Because any three vectors in two dimensions are linearly dependent, we are guaranteed to be able to find scalars $n_{1}, n_{2}, n_{3}$, not all 0 , such that $n_{1}\binom{v_{1}}{w_{1}}+n_{2}\binom{v_{2}}{w_{2}}+n_{3}\binom{v_{3}}{w_{3}}=\mathbf{0}$. Letting $n_{1}, n_{2}, n_{3}$ take on these values eliminates the dot product and leaves us
$$n_{1} x+n_{2} y+n_{3} z=n_{1} x_{0}+n_{2} y_{0}+n_{3} z_{0}$$

Note that the right side of this equation isn't surprising because the point ( $x_{0}, y_{0}, z_{0}$ ) must be on the plane.
Letting $d=n_{1} x_{0}+n_{2} y_{0}+n_{3} z_{0}$ in Equation (12.14) completes our proof that we can always eliminate the parameters to produce an equation of the form $n_{1} x+n_{2} y+n_{3} z=d$, where $n_{1}, n_{2}, n_{3}$, and $d$ are constants.
(b) Our work in part (a) shows that we can eliminate the parameters from a parametric equation of the form
$$\left(\begin{array}{l}
x \\
y \\
z
\end{array}\right)=\left(\begin{array}{l}
x_{0} \\
y_{0} \\
z_{0}
\end{array}\right)+s \mathbf{v}+t \mathbf{w}$$
to produce an equation of the form $n_{1} x+n_{2} y+n_{3} z=d$. This means that every point in the graph of the parametric equation is in the graph of $n_{1} x+n_{2} y+n_{3} z=d$. But we haven't shown that every point in the graph of $n_{1} x+n_{2} y+n_{3} z=d$ is in the graph of the parametric equation, so we don't yet know that the graphs are the same. In Problem 12.8, we showed that we can go from an equation of the form $n_{1} x+n_{2} y+n_{3} z=d$ back to a parametric equation. Specifically, the graph of $n_{1} x+n_{2} y+n_{3} z=d$ is the same as the graph of the parametric equation
$$\left(\begin{array}{l}
x \\
y \\
z
\end{array}\right)=\left(\begin{array}{l}
x_{1} \\
y_{1} \\
z_{1}
\end{array}\right)+p \mathbf{a}+q \mathbf{b}$$
for some point $\left(x_{1}, y_{1}, z_{1}\right)$ and some linearly independent vectors $\mathbf{a}$ and $\mathbf{b}$. Now our problem is to show that the graphs of (12.15) and (12.16) are the same.

435

---

<!-- Page 436 -->

CHAPTER 12. VECTORS AND MATRICES IN THREE DIMENSIONS, PART 2

We know that every point in the graph of (12.15) is in the graph of (12.16). Specifically, we know that ( $x_{0}, y_{0}, z_{0}$ ) is in the graph of (12.16), so by Problem 12.5, the graph of (12.16) is the same as the graph of
$$\left(\begin{array}{c}
x \\
y \\
z
\end{array}\right)=\left(\begin{array}{c}
x_{0} \\
y_{0} \\
z_{0}
\end{array}\right)+p \mathbf{a}+q \mathbf{b} .$$

Because every point in the graph of (12.15) is in the graph of (12.17), we know that there are two points in (12.17) such that the vector between them is $\mathbf{v}$. In other words $\mathbf{v}$ is in plane (12.17), as is $\mathbf{w}$. Our work in Problem 12.6 then tells us that the plane generated by $\mathbf{a}$ and $\mathbf{b}$ is the same as the plane generated by $\mathbf{v}$ and $\mathbf{w}$. We therefore conclude that the graphs of (12.15) and (12.17) are the same, which means that the graphs of (12.15) and $n_{1} x+n_{2} y+n_{3} z=d$ are the same.

At long last, we have proved the following:

Make sure you see why this statement is different from, "The graph of the equation $a x+b y+c z=d$, where $a$, $b, c$, and $d$ are constants, is a plane."

Problem 12.10: In this problem, we find a vector that is orthogonal to every vector in the plane through the origin generated by $\mathbf{v}=3 \mathbf{i}+4 \mathbf{j}-\mathbf{k}$ and $\mathbf{w}=4 \mathbf{i}-2 \mathbf{j}+3 \mathbf{k}$.
(a) Find an equation of the form $n_{1} x+n_{2} y+n_{3} z=0$ whose graph is the plane through the origin generated by $\mathbf{v}$ and $\mathbf{w}$.
(b) Let $\mathbf{n}=n_{1} \mathbf{i}+n_{2} \mathbf{j}+n_{3} \mathbf{k}$. Show that $\mathbf{n}$ is orthogonal to both $\mathbf{v}$ and $\mathbf{w}$.
(c) Is $\mathbf{n}$ orthogonal to every vector in the plane?

Solution for Problem 12.10:
(a) The plane is the graph of
$$\left(\begin{array}{l}
x \\
y \\
z
\end{array}\right)=s \mathbf{v}+t \mathbf{w}=s\left(\begin{array}{c}
3 \\
4 \\
-1
\end{array}\right)+t\left(\begin{array}{c}
4 \\
-2 \\
3
\end{array}\right) .$$

So, we have
$$\begin{array}{l}
x=3 s+4 t \\
y=4 s-2 t \\
z=-s+3 t
\end{array}$$

Adding 3 times the equation for $z$ to the equation for $x$ gives $x+3 z=13 t$. Adding 4 times the equation for $z$ to the equation for $y$ gives $y+4 z=10 t$. Subtracting 13 times $y+4 z=10 t$ from 10 times $x+3 z=13 t$ eliminates $t$ and leaves
$$10 x-13 y-22 z=0 .$$
(b) Letting $\mathbf{n}=10 \mathbf{i}-13 \mathbf{j}-22 \mathbf{k}$, we have
$$\begin{aligned}
\mathbf{n} \cdot \mathbf{v} & =(10)(3)+(-13)(4)+(-22)(-1)=0 \\
\mathbf{n} \cdot \mathbf{w} & =(10)(4)+(-13)(-2)+(-22)(3)=0
\end{aligned}$$
so $\mathbf{n}$ is orthogonal to both $\mathbf{v}$ and $\mathbf{w}$.

436

---

<!-- Page 437 -->

12.2. MORE PLANES IN THREE DIMENSIONS
(c) Let $\mathbf{u}$ be a vector from the origin to a point in the plane. By definition, such a vector must be a linear combination of $\mathbf{v}$ and $\mathbf{w}$, so we have $\mathbf{u}=s \mathbf{v}+t \mathbf{w}$ for some constants $s$ and $t$. Therefore, we have
$$\mathbf{n} \cdot \mathbf{u}=\mathbf{n} \cdot(s \mathbf{v}+t \mathbf{w})=\mathbf{n} \cdot(s \mathbf{v})+\mathbf{n} \cdot(t \mathbf{w})=s \mathbf{n} \cdot \mathbf{v}+t \mathbf{n} \cdot \mathbf{w}=0$$
which tells us that $\mathbf{n}$ is orthogonal to every vector in the plane through the origin generated by $\mathbf{v}$ and $\mathbf{w}$.

The plane in Problem 12.10 passes through the origin. Let's take a look at a plane that doesn't pass through the origin.

Problem 12.11: In Problem 12.7, we found that the plane through the points $(0,4,0),(3,-1,-3)$, and $(2,-2,-4)$ is the graph of the equation $x+3 y-4 z=12$. Let $\mathbf{n}=\mathbf{i}+3 \mathbf{j}-4 \mathbf{k}$, where the components of $\mathbf{n}$ are taken from the coefficients of $x+3 y-4 z=12$. Is $\mathbf{n}$ orthogonal to the vector between any two points in the plane?

Solution for Problem 12.11: Let $\left(x_{1}, y_{1}, z_{1}\right)$ and $\left(x_{2}, y_{2}, z_{2}\right)$ be two points in the plane, so
$$\begin{array}{l}
x_{1}+3 y_{1}-4 z_{1}=12 \\
x_{2}+3 y_{2}-4 z_{2}=12
\end{array}$$

The vector from the first point to the second is $\left(x_{2}-x_{1}\right) \mathbf{i}+\left(y_{2}-y_{1}\right) \mathbf{j}+\left(z_{2}-z_{1}\right) \mathbf{k}$. These differences appear if we subtract the first equation above from the second equation. This subtraction gives
$$\left(x_{2}-x_{1}\right)+3\left(y_{2}-y_{1}\right)-4\left(z_{2}-z_{1}\right)=0 .$$

The expression on the left is $(\mathbf{i}+3 \mathbf{j}-4 \mathbf{k}) \cdot\left(\left(x_{2}-x_{1}\right) \mathbf{i}+\left(y_{2}-y_{1}\right) \mathbf{j}+\left(z_{2}-z_{1}\right) \mathbf{k}\right)$. Since this equals 0 , the vector $\mathbf{n}=\mathbf{i}+3 \mathbf{j}-4 \mathbf{k}$ is orthogonal to any vector between the two points in the plane.

We have confirmed that the vector $n_{1} \mathbf{i}+n_{2} \mathbf{j}+n_{3} \mathbf{k}$ is orthogonal to every vector in the plane $n_{1} x+n_{2} y+n_{3} z=d$ for two different planes. Our solution to Problem 12.11 gives us a guide to prove that this is the case for all planes.

Problem 12.12: Show that the vector $\mathbf{n}=n_{1} \mathbf{i}+n_{2} \mathbf{j}+n_{3} \mathbf{k}$ is orthogonal to the vector between any two points in the graph of $n_{1} x+n_{2} y+n_{3} z=d$, where $n_{1}, n_{2}, n_{3}$, and $d$ are constants.

Solution for Problem 12.12: Let $\left(x_{1}, y_{1}, z_{1}\right)$ and $\left(x_{2}, y_{2}, z_{2}\right)$ be two points in the plane, so
$$\begin{array}{l}
n_{1} x_{1}+n_{2} y_{1}+n_{3} z_{1}=d \\
n_{1} x_{2}+n_{2} y_{2}+n_{3} z_{2}=d
\end{array}$$

Subtracting the first equation from the second gives
$$n_{1}\left(x_{2}-x_{1}\right)+n_{2}\left(y_{2}-y_{1}\right)+n_{3}\left(z_{2}-z_{1}\right)=0$$
which we can write as
$$\left(n_{1} \mathbf{i}+n_{2} \mathbf{j}+n_{3} \mathbf{k}\right) \cdot\left(\left(x_{2}-x_{1}\right) \mathbf{i}+\left(y_{2}-y_{1}\right) \mathbf{j}+\left(z_{2}-z_{1}\right) \mathbf{k}\right)=0 .$$

Therefore, $\mathbf{n}$ is orthogonal to any vector between two points in the plane.
Note that this isn't the only vector that is orthogonal to every vector in the plane generated by $\mathbf{v}$ and $\mathbf{w}$. We can multiply the equation above by any scalar $k$ to yield
$$\left(k n_{1} \mathbf{i}+k n_{2} \mathbf{j}+k n_{3} \mathbf{k}\right) \cdot\left(\left(x_{2}-x_{1}\right) \mathbf{i}+\left(y_{2}-y_{1}\right) \mathbf{j}+\left(z_{2}-z_{1}\right) \mathbf{k}\right)=0,$$
which tells us that $k \mathbf{n}$ is orthogonal to any vector in the plane, as well. Specifically, there are two directions that are normal to the plane, the direction of $\mathbf{n}$ and the direction opposite that of $\mathbf{n}$, which is the direction of $-\mathbf{n}$.

437

---

<!-- Page 438 -->

CHAPTER 12. VECTORS AND MATRICES IN THREE DIMENSIONS, PART 2

Important: A vector that is orthogonal to all vectors in a certain plane is said to be normal
! to the plane. The vector $a \mathbf{i}+b \mathbf{j}+c \mathbf{k}$ is normal to the plane $a x+b y+c z=d$.

This should look familiar-we showed back on page 325 that in two dimensions, the vector $a \mathbf{i}+b \mathbf{j}$ is normal to the line $a x+b y=c$. We then used that normal vector to find a formula for the distance between a point and a line. Let's see if we can do something similar to find the distance between a point and a plane in three dimensions.

Problem 12.13:
(a) Find an expression for $\operatorname{proj}_{\mathbf{w}} \mathbf{v}$ in terms of $\mathbf{v} \cdot \mathbf{w},\|\mathbf{w}\|$, and $\mathbf{w}$.
(b) The distance between a point and a plane is the length of the shortest segment between the point and a point in the plane. Find an expression for the distance between the point ( $x_{0}, y_{0}, z_{0}$ ) and the plane $a x+b y+c z+d=0$, where $a, b, c$, and $d$ are constants.

Solution for Problem 12.13:
(a) Flip back to the solution to Problem 9.26 on page 327 and read through it closely, looking for any reference to the fact that the vectors are in two dimensions. You won't find any. The entire proof holds for vectors in three dimensions, as well. So, we don't have to do any more work to see that:

Important: For any vector $\mathbf{v}$ and any nonzero vector $\mathbf{w}$, we have
$$\operatorname{proj}_{\mathbf{w}} \mathbf{v}=\frac{\mathbf{v} \cdot \mathbf{w}}{\|\mathbf{w}\|^{2}} \mathbf{w} .$$
(b) Looking back at two dimensions saves us a whole lot of trouble on this part, too. Rather than start from scratch, we do exactly what we did in Problem 9.26 in two dimensions. Let point $A$ with coordinates $(x, y, z)$ be on the plane, so that $a x+b y+c z+d=0$. Letting $P$ be ( $x_{0}, y_{0}, z_{0}$ ), we find the distance from $P$ to the plane by finding the length of the projection of $\overrightarrow{A P}$ onto the vector normal to the plane. The vector $\mathbf{n}=a \mathbf{i}+b \mathbf{j}+c \mathbf{k}$ is normal to the plane, so
the desired length is
$$\begin{aligned}
\left\|\frac{\overrightarrow{A P} \cdot \mathbf{n}}{\|\mathbf{n}\|^{2}} \mathbf{n}\right\| & =\left|\frac{\overrightarrow{A P} \cdot \mathbf{n}}{\|\mathbf{n}\|^{2}}\right|\|\mathbf{n}\| \\
& =\left|\frac{\left(\left(x_{0}-x\right) \mathbf{i}+\left(y_{0}-y\right) \mathbf{j}+\left(z_{0}-z\right) \mathbf{k}\right) \cdot(a \mathbf{i}+b \mathbf{j}+c \mathbf{k})}{\|\mathbf{n}\|^{2}}\right|\|\mathbf{n}\| \\
& =\frac{\left|a x_{0}+b y_{0}+c z_{0}-a x-b y-c z\right|}{\|\mathbf{n}\|}
\end{aligned}$$

Since $a x+b y+c z+d=0$, we have $-a x-b y-c z=d$. Moreover, $\|\mathbf{n}\|=\sqrt{a^{2}+b^{2}+c^{2}}$, so the desired distance between $\left(x_{0}, y_{0}, z_{0}\right)$ and $a x+b y+c z+d=0$ is
$$\frac{\left|a x_{0}+b y_{0}+c z_{0}+d\right|}{\sqrt{a^{2}+b^{2}+c^{2}}} .$$

Now that we understand the graph of linear combinations of two vectors, let's take a look at linear combinations of three vectors.

438

---

<!-- Page 439 -->

12.2. MORE PLANES IN THREE DIMENSIONS

Problem 12.14: Let $\mathbf{u}, \mathbf{v}$, and $\mathbf{w}$ be vectors in three dimensions such that $\mathbf{v}$ and $\mathbf{w}$ are linearly independent. We will explore the graph of the parametric equation
$$\left(\begin{array}{l}
x \\
y \\
z
\end{array}\right)=r \mathbf{u}+s \mathbf{v}+t \mathbf{w}$$
(a) Show that if $\mathbf{u}$ is a linear combination of $\mathbf{v}$ and $\mathbf{w}$, then the graph of Equation (12.18) is a plane.
(b) Suppose that $\mathbf{u}$ is not a linear combination of $\mathbf{v}$ and $\mathbf{w}$. Then, what is the graph of
$$\left(\begin{array}{l}
x \\
y \\
z
\end{array}\right)=\mathbf{u}+s \mathbf{v}+t \mathbf{w} ?$$
(Notice that the coefficient of $\mathbf{u}$ here is 1 , not $r$.)
(c) Suppose that $\mathbf{u}$ is not a linear combination of $\mathbf{v}$ and $\mathbf{w}$. Then, what is the graph of
$$\left(\begin{array}{l}
x \\
y \\
z
\end{array}\right)=2 \mathbf{u}+s \mathbf{v}+t \mathbf{w} ?$$

How is your answer related to the graph in part (b)?
(d) Suppose that $\mathbf{u}$ is not a linear combination of $\mathbf{v}$ and $\mathbf{w}$. Then, what is the graph of Equation (12.18)?

Solution for Problem 12.14:
(a) If $\mathbf{u}$ is a linear combination of $\mathbf{v}$ and $\mathbf{w}$, then $\mathbf{u}=p \mathbf{v}+q \mathbf{w}$ for some constants $p$ and $q$. Then, Equation (12.18) becomes
$$\left(\begin{array}{l}
x \\
y \\
z
\end{array}\right)=r \mathbf{u}+s \mathbf{v}+t \mathbf{w}=r(p \mathbf{v}+q \mathbf{w})+s \mathbf{v}+t \mathbf{w}=(r p+s) \mathbf{v}+(r q+t) \mathbf{w}$$

So, the graph consists of all linear combinations of $\mathbf{v}$ and $\mathbf{w}$, which is the plane through the origin generated by $\mathbf{v}$ and $\mathbf{w}$.
(b) Let $\mathbf{u}=\left(\begin{array}{l}u_{1} \\ u_{2} \\ u_{3}\end{array}\right)$. Then, the graph of
$$\left(\begin{array}{l}
x \\
y \\
z
\end{array}\right)=\mathbf{u}+s \mathbf{v}+t \mathbf{w}=\left(\begin{array}{l}
u_{1} \\
u_{2} \\
u_{3}
\end{array}\right)+s \mathbf{v}+t \mathbf{w}$$
is the plane through $\left(u_{1}, u_{2}, u_{3}\right)$ generated by $\mathbf{v}$ and $\mathbf{w}$.
(c) The graph of
$$\left(\begin{array}{l}
x \\
y \\
z
\end{array}\right)=2 \mathbf{u}+s \mathbf{v}+t \mathbf{w}=\left(\begin{array}{l}
2 u_{1} \\
2 u_{2} \\
2 u_{3}
\end{array}\right)+s \mathbf{v}+t \mathbf{w}$$
is the plane through $\left(2 u_{1}, 2 u_{2}, 2 u_{3}\right)$ generated by $\mathbf{v}$ and $\mathbf{w}$. As shown in Problem 12.5, this plane is parallel to the plane in part (b) because this plane is generated by the same vectors as the plane in part (b). To show that the planes in these two parts are not the same plane, we will show that it is impossible for the two planes to intersect. If they do intersect, then there must be some point $(x, y, z)$ on both, so there must be

439

---

<!-- Page 440 -->

CHAPTER 12. VECTORS AND MATRICES IN THREE DIMENSIONS, PART 2

scalars $s_{1}, t_{1}, s_{2}, t_{2}$ such that
$$\left(\begin{array}{l}
u_{1} \\
u_{2} \\
u_{3}
\end{array}\right)+s_{1} \mathbf{v}+t_{1} \mathbf{w}=\left(\begin{array}{l}
2 u_{1} \\
2 u_{2} \\
2 u_{3}
\end{array}\right)+s_{2} \mathbf{v}+t_{2} \mathbf{w} .$$

Rearranging this equation gives
$$\left(\begin{array}{l}
u_{1} \\
u_{2} \\
u_{3}
\end{array}\right)=\left(s_{1}-s_{2}\right) \mathbf{v}+\left(t_{1}-t_{2}\right) \mathbf{w} .$$

But this equation says that that $\mathbf{u}$ is a linear combination of $\mathbf{v}$ and $\mathbf{w}$, which we know is not the case. Therefore, the plane in part (b) cannot intersect the plane in this part.
(d) Continuing in the vein of part (b) and part (c), for each possible value of $r$, the graph of
$$\left(\begin{array}{l}
x \\
y \\
z
\end{array}\right)=r \mathbf{u}+s \mathbf{v}+t \mathbf{w} .$$
is a plane through ( $r u_{1}, r u_{2}, r u_{3}$ ) generated by $\mathbf{v}$ and $\mathbf{w}$. Moreover, for the same reason explained in part (c), all of these planes are parallel. So, by varying $r$, we produce a set of parallel planes. Intuitively, it seems like every point in space is included in one of these planes, but we have to prove it.

We'll start by getting a little more geometric intuition for why each point is in one of these planes. In the diagram at right, plane $\mathcal{P}$ is the plane through the origin $O$ generated by $\mathbf{v}$ and $\mathbf{w}$. Obviously, the graph of (12.19) passes through all points in $\mathcal{P}$, since $\mathcal{P}$ is the graph of (12.19) when $r=0$.

To show that the graph of (12.19) passes through any point $A$ not in $\mathcal{P}$, we consider the plane $Q$ through $A$ parallel to $\mathcal{P}$. Since $\mathbf{u}, \mathbf{v}$, and $\mathbf{w}$ are linearly independent, when we draw $\mathbf{u}$ from the
origin, it is not in $\mathcal{P}$. Therefore, the line through the origin with direction $\mathbf{u}$ intersects $Q$ at some point $U$, so $\vec{U}=r$ u for some $r$. Let $B$ be the point in $\mathcal{P}$ such that $\overleftrightarrow{O B} \| \overleftrightarrow{U A}$ and $O B=U A$, so $U O B A$ is a parallelogram (unless $U$ is $A$, in which case $A$ is obviously in the graph of (12.19)).

Since $\vec{B}$ is in $\mathcal{P}$, we have $\vec{B}=s \mathbf{v}+t \mathbf{w}$ for some $s$ and $t$. Since $U O B A$ is a parallelogram, we have $\vec{A}=\vec{U}+\vec{B}=r \mathbf{u}+s \mathbf{v}+t \mathbf{w}$, which means $A$ is in the graph of (12.19).

This gives some geometric intuition for why the graph of
$$\left(\begin{array}{l}
x \\
y \\
z
\end{array}\right)=r \mathbf{u}+s \mathbf{v}+t \mathbf{w}$$
is all of $\mathbb{R}^{3}$. We'll now prove that every point ( $x, y, z$ ) is on the graph.
Let $a x+b y+c z=0$ be the plane $\mathcal{P}$ through the origin generated by $\mathbf{v}$ and $\mathbf{w}$. Any point ( $x_{0}, y_{0}, z_{0}$ ) in space is on a plane parallel to $\mathcal{P}$, since for $k_{0}=a x_{0}+b y_{0}+c z_{0}$, the point ( $x_{0}, y_{0}, z_{0}$ ) is on the graph of $a x+b y+c z=k_{0}$. All we have left is to show that this plane is among the set of parallel planes produced by graphing (12.20). To do so, we just have to show that some multiple of $\mathbf{u}$ produces the plane $a x+b y+c z=k_{0}$. Letting $k_{\mathbf{u}}=a u_{1}+b u_{2}+c u_{3}$, the point ( $u_{1}, u_{2}, u_{3}$ ) is on the graph of $a x+b y+c z=k_{\mathbf{u}}$. Since $\mathbf{u}, \mathbf{v}$ and $\mathbf{w}$ are linearly independent, we know that $\mathbf{u}$ is not in $\mathcal{P}$, so we must have $k_{\mathbf{u}} \neq 0$. Therefore, we can multiply $a u_{1}+b u_{2}+c u_{3}=k_{\mathbf{u}}$ by $\frac{k_{0}}{k_{\mathbf{u}}}$ to give
$$a\left(u_{1} \cdot \frac{k_{0}}{k_{\mathbf{u}}}\right)+b\left(u_{2} \cdot \frac{k_{0}}{k_{\mathbf{u}}}\right)+c\left(u_{3} \cdot \frac{k_{0}}{k_{\mathbf{u}}}\right)=k_{0}$$

440

---

<!-- Page 441 -->

12.2. MORE PLANES IN THREE DIMENSIONS

which means that $\left(u_{1} \cdot \frac{k_{0}}{k_{\mathrm{u}}}, u_{2} \cdot \frac{k_{0}}{k_{\mathrm{u}}}, u_{3} \cdot \frac{k_{0}}{k_{\mathrm{u}}}\right)$ is in the graph of $a x+b y+c z=k_{0}$. This tells us that the graph of $a x+b y+c z=k_{0}$ is the same as the graph of
$$\left(\begin{array}{l}
x \\
y \\
z
\end{array}\right)=\frac{k_{0}}{k_{\mathbf{u}}} \mathbf{u}+s \mathbf{v}+t \mathbf{w},$$
which means $\left(x_{0}, y_{0}, z_{0}\right)$ is in the graph of (12.20). Therefore, every point in space is in the graph of (12.20).

Problem 12.14 allows us to extend our notion of linear dependence and linear independence to three vectors in three dimensions. We say that $\mathbf{v}_{1}, \mathbf{v}_{2}$, and $\mathbf{v}_{3}$ are linearly dependent if and only if there exist constants $a_{1}, a_{2}$, and $a_{3}$, not all 0 , such that $a_{1} \mathbf{v}_{1}+a_{2} \mathbf{v}_{2}+a_{3} \mathbf{v}_{3}=\mathbf{0}$. Otherwise, we say the vectors are linearly independent. Our work in part (d) shows that if $\mathbf{u}, \mathbf{v}$, and $\mathbf{w}$ are linearly independent, then the graph of
$$\left(\begin{array}{l}
x \\
y \\
z
\end{array}\right)=r \mathbf{u}+s \mathbf{v}+t \mathbf{w}$$
is all possible points $(x, y, z)$. More succinctly, we say that this graph is $\mathbb{R}^{3}$. We also now know that there's nothing to be gained by throwing more vectors into the mix-we can get all of $\mathbb{R}^{3}$ with linear combinations of three linearly independent vectors, so we can't get "more" by taking linear combinations of more than three vectors.

Problem 12.15: Show that if $\mathbf{u}, \mathbf{v}$, and $\mathbf{w}$ are linearly independent, then for any ( $x, y, z$ ), there is exactly one ordered triple ( $r, s, t$ ) such that
$$\left(\begin{array}{l}
x \\
y \\
z
\end{array}\right)=r \mathbf{u}+s \mathbf{v}+t \mathbf{w} .$$

Solution for Problem 12.15: We know that there is at least one such ordered triple, since the graph of the parametric equation is $\mathbb{R}^{3}$. Suppose we have both
$$\left(\begin{array}{c}
x \\
y \\
z
\end{array}\right)=r_{1} \mathbf{u}+s_{1} \mathbf{v}+t_{1} \mathbf{w} \quad \text { and } \quad\left(\begin{array}{c}
x \\
y \\
z
\end{array}\right)=r_{2} \mathbf{u}+s_{2} \mathbf{v}+t_{2} \mathbf{w} .$$

Subtracting the second equation from the first gives
$$\mathbf{0}=\left(r_{1}-r_{2}\right) \mathbf{u}+\left(s_{1}-s_{2}\right) \mathbf{v}+\left(t_{1}-t_{2}\right) \mathbf{w}$$

Since $\mathbf{u}, \mathbf{v}$, and $\mathbf{w}$ are linearly independent, we must have $r_{1}-r_{2}=s_{1}-s_{2}=t_{1}-t_{2}=0$, so $r_{1}=r_{2}$, $s_{1}=s_{2}$, and $t_{1}=t_{2}$. Therefore, there cannot be two different ordered triples $(r, s, t)$ that satisfy the equation for the same $(x, y, z)$. Since we have showed that there is at least one ordered triple ( $r, s, t$ ) that satisfies the problem, but there can't be more than one, we conclude that there is exactly one such ordered triple.
12.2.1 Find a vector with magnitude 1 that is normal to the graph of $4 x-3 y+12 z=5$.
12.2.2 Let $\mathbf{n}=n_{1} \mathbf{i}+n_{2} \mathbf{j}+n_{3} \mathbf{k}$. Show that if $\mathbf{v}$ is a nonzero vector such that $\mathbf{n} \cdot \mathbf{v}=0$, then there are two points $A$ and $B$ on the plane $n_{1} x+n_{2} y+n_{3} z=d$ such that $\overrightarrow{A B}=\mathbf{v}$.
12.2.3 Find the projection of $3 \mathbf{i}+2 \mathbf{j}-2 \mathbf{k}$ onto $4 \mathbf{i}-\mathbf{j}+8 \mathbf{k}$.

441

---

<!-- Page 442 -->

CHAPTER 12. VECTORS AND MATRICES IN THREE DIMENSIONS, PART 2
12.2.4 Find $b$ and $c$ if $\left(\begin{array}{l}3 \\ b \\ c\end{array}\right)$ is normal to the graph of $2 x-y+3 x=5$.
12.2.5 Find all values of $b$ such that the distance between $(3, b,-5)$ and the plane $x+2 y-2 z=8$ is 8 .
12.2.6 We can extend our definition of linear dependence to any number of vectors. Specifically, the vectors $\mathbf{v}_{1}, \mathbf{v}_{2}, \ldots, \mathbf{v}_{n}$ are linearly dependent if and only if there exist constants $a_{1}, a_{2}, \ldots, a_{n}$ such that $a_{1} \mathbf{v}_{1}+a_{2} \mathbf{v}_{2}+\cdots+a_{n} \mathbf{v}_{n}=\mathbf{0}$ and not all of the $a_{i}$ are 0 . Otherwise, the vectors are linearly independent. Show that any set of four or more vectors in three dimensions is linearly dependent.
12.3 The Cross Product

In Problem 12.10 of the previous section, we found a vector $\mathbf{n}$ that is orthogonal to both $\mathbf{v}=3 \mathbf{i}+4 \mathbf{j}-\mathbf{k}$ and $\mathbf{w}=4 \mathbf{i}-2 \mathbf{j}+3 \mathbf{k}$. We did so by showing that the plane through the origin generated by $\mathbf{v}$ and $\mathbf{w}$ is the graph of $10 x-13 y-22 z=0$. We then showed that the vector $\mathbf{n}=10 \mathbf{i}-13 \mathbf{j}-22 \mathbf{k}$ is orthogonal to any vector between two points in the plane. Specifically, $\mathbf{n}$ is orthogonal to both $\mathbf{v}$ and $\mathbf{w}$.

We start this section by generalizing this process, showing that we can go straight from the linearly independent vectors to the normal vector without bothering with the intermediate step of finding the plane generated by the linearly independent vectors. While doing so, we will discover a vector operation, the cross product, that we use in a great many applications of mathematics to physics and engineering.

Problem 12.16: Find a nonzero vector that is orthogonal to linearly independent vectors $\mathbf{v}=v_{1} \mathbf{i}+v_{2} \mathbf{j}+v_{3} \mathbf{k}$ and $\mathbf{w}=w_{1} \mathbf{i}+w_{2} \mathbf{j}+w_{3} \mathbf{k}$, in terms of the components of $\mathbf{v}$ and $\mathbf{w}$.

Solution for Problem 12.16: We can use our solution to Problem 12.10 as a guide. There, found an equation of the form $n_{1} x+n_{2} y+n_{3} z=0$ whose graph is the plane through the origin generated by $\mathbf{v}$ and $\mathbf{w}$. So, we start with the plane through the origin generated by $\mathbf{v}=v_{1} \mathbf{i}+v_{2} \mathbf{j}+v_{3} \mathbf{k}$ and $\mathbf{w}=w_{1} \mathbf{i}+w_{2} \mathbf{j}+w_{3} \mathbf{k}$. Parametric equations whose graph is this plane are
$$\begin{array}{l}
x=v_{1} s+w_{1} t \\
y=v_{2} s+w_{2} t \\
z=v_{3} s+w_{3} t
\end{array}$$
where $s$ and $t$ are parameters. We produce an equation of the form $n_{1} x+n_{2} y+n_{3} z=0$ with the same graph as the parametric equations by eliminating the parameters. We first eliminate $s$ by subtracting $v_{2}$ times the first equation from $v_{1}$ times the second equation, and by subtracting $v_{3}$ times the first equation from $v_{1}$ times the third equation. This gives us
$$\begin{array}{l}
-v_{2} x+v_{1} y=-v_{2} w_{1} t+v_{1} w_{2} t=\left(v_{1} w_{2}-v_{2} w_{1}\right) t \\
-v_{3} x+v_{1} z=-v_{3} w_{1} t+v_{1} w_{3} t=\left(v_{1} w_{3}-v_{3} w_{1}\right) t
\end{array}$$

Next, we set up elimination of $t$ by multiplying the first equation above by $\left(v_{1} w_{3}-v_{3} w_{1}\right)$ and the second by $\left(v_{1} w_{2}-v_{2} w_{1}\right)$ :
$$\begin{array}{l}
-v_{2}\left(v_{1} w_{3}-v_{3} w_{1}\right) x+v_{1}\left(v_{1} w_{3}-v_{3} w_{1}\right) y=\left(v_{1} w_{2}-v_{2} w_{1}\right)\left(v_{1} w_{3}-v_{3} w_{1}\right) t \\
-v_{3}\left(v_{1} w_{2}-v_{2} w_{1}\right) x+v_{1}\left(v_{1} w_{2}-v_{2} w_{1}\right) z=\left(v_{1} w_{2}-v_{2} w_{1}\right)\left(v_{1} w_{3}-v_{3} w_{1}\right) t
\end{array}$$

Subtracting the first equation from the second eliminates $t$ and leaves
$$\left(-v_{3}\left(v_{1} w_{2}-v_{2} w_{1}\right)+v_{2}\left(v_{1} w_{3}-v_{3} w_{1}\right)\right) x-v_{1}\left(v_{1} w_{3}-v_{3} w_{1}\right) y+v_{1}\left(v_{1} w_{2}-v_{2} w_{1}\right) z=0$$

442

---

<!-- Page 443 -->

12.3. THE CROSS PRODUCT

Fortunately, the coefficient of $x$ can be simplified a bit:
$$-v_{3}\left(v_{1} w_{2}-v_{2} w_{1}\right)+v_{2}\left(v_{1} w_{3}-v_{3} w_{1}\right)=-v_{1} v_{3} w_{2}+v_{2} v_{3} w_{1}+v_{1} v_{2} w_{3}-v_{2} v_{3} w_{1}=-v_{1} v_{3} w_{2}+v_{1} v_{2} w_{3}=v_{1}\left(v_{2} w_{3}-v_{3} w_{2}\right) .$$

This leaves us
$$v_{1}\left(v_{2} w_{3}-v_{3} w_{2}\right) x-v_{1}\left(v_{1} w_{3}-v_{3} w_{1}\right) y+v_{1}\left(v_{1} w_{2}-v_{2} w_{1}\right) z=0 .$$

If $v_{1}$ is nonzero, then we can divide both sides of the equation by $v_{1}$ to get
$$\left(v_{2} w_{3}-v_{3} w_{2}\right) x-\left(v_{1} w_{3}-v_{3} w_{1}\right) y+\left(v_{1} w_{2}-v_{2} w_{1}\right) z=0$$
(If $v_{1}=0$, we can go through the steps above slightly differently to produce this same equation. We eliminated $s$ by subtracting multiples of our parametric equation for $x$ from the parametric equations for $y$ and $z$. If we started instead by subtracting multiples of the parametric equation for $y$ from the equations for $x$ and $z$, we'd end up with $v_{2}$ times (12.21) rather than $v_{1}$ times it .)

Equation (12.21) gives us the desired equation of the form $a x+b y+c z=d$ whose graph is the plane through the origin generated by $\mathbf{v}$ and $\mathbf{w}$. We can read the components of a vector that is normal to the plane generated by $\mathbf{v}$ and $\mathbf{w}$ from the coefficients of $x, y$, and $z$. Therefore, the vector
$$\left(v_{2} w_{3}-v_{3} w_{2}\right) \mathbf{i}-\left(v_{1} w_{3}-v_{3} w_{1}\right) \mathbf{j}+\left(v_{1} w_{2}-v_{2} w_{1}\right) \mathbf{k}$$
is orthogonal to every vector in the plane generated by $\mathbf{v}$ and $\mathbf{w}$. Specifically, it is orthogonal to $\mathbf{v}$ and $\mathbf{w}$ themselves.

For any two vectors $\mathbf{v}=v_{1} \mathbf{i}+v_{2} \mathbf{j}+v_{3} \mathbf{k}$ and $\mathbf{w}=w_{1} \mathbf{i}+w_{2} \mathbf{j}+w_{3} \mathbf{k}$, we call the vector
$$\left(v_{2} w_{3}-v_{3} w_{2}\right) \mathbf{i}-\left(v_{1} w_{3}-v_{3} w_{1}\right) \mathbf{j}+\left(v_{1} w_{2}-v_{2} w_{1}\right) \mathbf{k}$$
the cross product of $\mathbf{v}$ and $\mathbf{w}$, and we denote it as $\mathbf{v} \times \mathbf{w}$. Fortunately, we have an easy way to remember this expression for the cross product. First, we notice that the expressions in parentheses above are determinants of $2 \times 2$ matrices, so we can write $\mathbf{v} \times \mathbf{w}$ as
$$\mathbf{v} \times \mathbf{w}=\left|\begin{array}{ll}
v_{2} & v_{3} \\
w_{2} & w_{3}
\end{array}\right| \mathbf{i}-\left|\begin{array}{ll}
v_{1} & v_{3} \\
w_{1} & w_{3}
\end{array}\right| \mathbf{j}+\left|\begin{array}{ll}
v_{1} & v_{2} \\
w_{1} & w_{2}
\end{array}\right| \mathbf{k} .$$

The expression on the right side has the same form as one of our expressions for the determinant of a $3 \times 3$ matrix. So, we can borrow the notation of the determinant of a $3 \times 3$ matrix to remember the expression for the cross product of two vectors:
$$\mathbf{v} \times \mathbf{w}=\left|\begin{array}{cc}
v_{2} & v_{3} \\
w_{2} & w_{3}
\end{array}\right| \mathbf{i}-\left|\begin{array}{cc}
v_{1} & v_{3} \\
w_{1} & w_{3}
\end{array}\right| \mathbf{j}+\left|\begin{array}{cc}
v_{1} & v_{2} \\
w_{1} & w_{2}
\end{array}\right| \mathbf{k}=\left|\begin{array}{ccc}
\mathbf{i} & \mathbf{j} & \mathbf{k} \\
v_{1} & v_{2} & v_{3} \\
w_{1} & w_{2} & w_{3}
\end{array}\right| .$$

The vector given by $\mathbf{v} \times \mathbf{w}$ is not the only vector orthogonal to both $\mathbf{v}$ and $\mathbf{w}$. Because ( $k \mathbf{p}) \cdot \mathbf{r}=k(\mathbf{p} \cdot \mathbf{r})$ for any scalar $k$ and any vectors $\mathbf{p}$ and $\mathbf{r}$, we can multiply our expression for $\mathbf{v} \times \mathbf{w}$ above by any scalar and produce another vector that has a dot product of 0 with both $\mathbf{v}$ and $\mathbf{w}$. We choose the particular vector above from among all of those that are orthogonal to both $\mathbf{v}$ and $\mathbf{w}$ because it has many convenient properties that we will explore in the next set of problems.

Problems
Problem 12.17: Let $\mathbf{v}=4 \mathbf{i}-\mathbf{j}+3 \mathbf{k}$ and $\mathbf{w}=-\mathbf{i}+2 \mathbf{j}+7 \mathbf{k}$.
(a) Find $\mathbf{v} \times \mathbf{w}$ and $\mathbf{w} \times \mathbf{v}$.
(b) How are the two results you found in part (a) related? For any two vectors $\mathbf{r}$ and s , does the same relationship hold between $\mathbf{r} \times \mathrm{s}$ and $\mathrm{s} \times \mathbf{r}$ ?

443

---

<!-- Page 444 -->

CHAPTER 12. VECTORS AND MATRICES IN THREE DIMENSIONS, PART 2

Problem 12.18: Show that for any scalar $c$ and any two vectors $\mathbf{u}$ and $\mathbf{v}$, we have $\mathbf{u} \times(c \mathbf{v})=(c \mathbf{u}) \times \mathbf{v}=c(\mathbf{u} \times \mathbf{v})$.
Problem 12.19: Show that for any vectors $\mathbf{u}, \mathbf{v}$, and $\mathbf{w}$ in three dimensions, we have $\mathbf{u} \times(\mathbf{v}+\mathbf{w})=\mathbf{u} \times \mathbf{v}+\mathbf{u} \times \mathbf{w}$ and $(\mathbf{u}+\mathbf{v}) \times \mathbf{w}=\mathbf{u} \times \mathbf{w}+\mathbf{v} \times \mathbf{w}$.

Problem 12.20: Let $\mathbf{u}=\left(\begin{array}{l}u_{1} \\ u_{2} \\ u_{3}\end{array}\right)$ and $\mathbf{v}=\left(\begin{array}{l}v_{1} \\ v_{2} \\ v_{3}\end{array}\right)$ be nonzero vectors. In this problem, we show that we have $\|\mathbf{u} \times \mathbf{v}\|=\|\mathbf{u}\|\|\mathbf{v}\| \sin \theta$, where $\theta$ is the angle between $\mathbf{u}$ and $\mathbf{v}$.
(a) Find $\|\mathbf{u} \times \mathbf{v}\|$ in terms of the components of $\mathbf{u}$ and $\mathbf{v}$.
(b) What trigonometric function of $\theta$ do you already know how to express in terms of $\mathbf{u}$ and $\mathbf{v}$ ?
(c) Show that $\|\mathbf{u} \times \mathbf{v}\|=\|\mathbf{u}\|\|\mathbf{v}\| \sin \theta$, where $\theta$ is the angle between $\mathbf{u}$ and $\mathbf{v}$.

Problem 12.21: Find $\mathbf{i} \times \mathbf{j}, \mathbf{j} \times \mathbf{k}$, and $\mathbf{k} \times \mathbf{i}$.
Problem 12.22:
(a) Find $(6 \mathbf{i}+9 \mathbf{j}-3 \mathbf{k}) \times(2 \mathbf{i}+3 \mathbf{j}-\mathbf{k})$.
(b) If $\mathbf{r}=c \mathbf{s}$ for some scalar $c$, then must we have $\mathbf{r} \times \mathbf{s}=\mathbf{0}$ ?
(c) If $\mathbf{r} \times \mathbf{s}=\mathbf{0}$ and $\mathbf{s} \neq \mathbf{0}$, then must we have $\mathbf{r}=c \mathbf{s}$ for some scalar $c$ ?

Problem 12.23: If $\mathbf{u}, \mathbf{v}$, and $\mathbf{w}$ are nonzero vectors such that $\mathbf{u} \times \mathbf{v}=\mathbf{u} \times \mathbf{w}$, then must we have $\mathbf{v}=\mathbf{w}$ ?
Problem 12.24: Let $A=(1,3,2), B=(-3,5,3)$, and $C=(0,-2,-6)$. Let $\mathcal{P}$ be the plane that contains all three of these points. In this problem, we find the equation whose graph is $\mathcal{P}$.
(a) Find a vector that is normal to $\mathcal{P}$.
(b) Find an equation whose graph is $\mathcal{P}$.

Problem 12.25: Let $E$ be $(1,0,-2)$, let $F$ be $(-2,3,-1)$, let $G$ be $(4,2,-3)$, and let $H$ be the point such that $E F G H$ is a parallelogram. Find the area of $E F G H$.

Problem 12.17: Let $\mathbf{v}=4 \mathbf{i}-\mathbf{j}+3 \mathbf{k}$ and $\mathbf{w}=-\mathbf{i}+2 \mathbf{j}+7 \mathbf{k}$.
(a) Find $\mathbf{v} \times \mathbf{w}$ and $\mathbf{w} \times \mathbf{v}$.
(b) How are the two results you found in part (a) related? For any two vectors $\mathbf{r}$ and $\mathbf{s}$, does the same relationship hold between $\mathbf{r} \times \mathbf{s}$ and $\mathbf{s} \times \mathbf{r}$ ?

Solution for Problem 12.17:
(a) We have
$$\begin{array}{l}
\mathbf{v} \times \mathbf{w}=\left|\begin{array}{ccc}
\mathbf{i} & \mathbf{j} & \mathbf{k} \\
4 & -1 & 3 \\
-1 & 2 & 7
\end{array}\right|=\left|\begin{array}{cc}
-1 & 3 \\
2 & 7
\end{array}\right| \mathbf{i}-\left|\begin{array}{cc}
4 & 3 \\
-1 & 7
\end{array}\right| \mathbf{j}+\left|\begin{array}{cc}
4 & -1 \\
-1 & 2
\end{array}\right| \mathbf{k}=-13 \mathbf{i}-31 \mathbf{j}+7 \mathbf{k}, \\
\mathbf{w} \times \mathbf{v}=\left|\begin{array}{ccc}
\mathbf{i} & \mathbf{j} & \mathbf{k} \\
-1 & 2 & 7 \\
4 & -1 & 3
\end{array}\right|=\left|\begin{array}{cc}
2 & 7 \\
-1 & 3
\end{array}\right| \mathbf{i}-\left|\begin{array}{cc}
-1 & 7 \\
4 & 3
\end{array}\right| \mathbf{j}+\left|\begin{array}{cc}
-1 & 2 \\
4 & -1
\end{array}\right| \mathbf{k}=13 \mathbf{i}+31 \mathbf{j}-7 \mathbf{k} .
\end{array}$$
(b) In part (a), we see that $\mathbf{v} \times \mathbf{w}=-\mathbf{w} \times \mathbf{v}$. Let's see why this relationship holds for any two vectors. Swapping

444

---

<!-- Page 445 -->

12.3. THE CROSS PRODUCT

two rows of a matrix multiplies the determinant of the matrix by -1 , so we have
$$\mathbf{r} \times \mathrm{s}=\left|\begin{array}{ccc}
\mathbf{i} & \mathbf{j} & \mathbf{k} \\
r_{1} & r_{2} & r_{3} \\
s_{1} & s_{2} & s_{3}
\end{array}\right|=-\left|\begin{array}{ccc}
\mathbf{i} & \mathbf{j} & \mathbf{k} \\
s_{1} & s_{2} & s_{3} \\
r_{1} & r_{2} & r_{3}
\end{array}\right|=-s \times \mathbf{r} .$$

\begin{tabular}{|l|}
\hline Important: For any two vectors $\mathbf{v}$ and $\mathbf{w}$ in three dimensions, we have \\
$\mathbf{v} \times \mathbf{w}=-\mathbf{w} \times \mathbf{v}$.
\end{tabular}

WARNING!! The cross product is not commutative. If $\mathbf{v} \times \mathbf{w}$ is nonzero, then it does not equal $\mathbf{w} \times \mathbf{v}$.

The relationship $\mathbf{v} \times \mathbf{w}=-\mathbf{w} \times \mathbf{v}$ has a geometric significance that makes it easy to visualize. We defined $\mathbf{v} \times \mathbf{w}$ by looking for a vector that is orthogonal to both $\mathbf{v}$ and $\mathbf{w}$. In Problem 12.16, we saw that such a vector is orthogonal to any linear combination of $\mathbf{v}$ and $\mathbf{w}$. That is, the vector $\mathbf{v} \times \mathbf{w}$ is normal to the plane that is generated by $\mathbf{v}$ and $\mathbf{w}$.

However, there are two directions that are normal to this plane, one in each direction away from the plane. The direction of $\mathbf{v} \times \mathbf{w}$ satisfies what we call the right-hand rule. To find the direction of $\mathbf{v} \times \mathbf{w}$, start by pointing the index finger of your right hand in the direction of $\mathbf{v}$ and the middle finger of your right hand along $\mathbf{w}$ in such a way that the middle finger is between your index finger and your palm, as shown at right. Then, extend your thumb "up" perpendicular to the plane generated by your index and middle fingers. This is the direction of $\mathbf{v} \times \mathbf{w}$, as shown.

WARNING!! $\stackrel{\Delta}{\Delta}$

The right-hand rule only works if you are using your right hand, not your left hand. Hence, we have the name "right-hand rule!"

The vector $-\mathbf{v} \times \mathbf{w}$ is in the exact opposite direction from $\mathbf{v} \times \mathbf{w}$. We can visualize this with the right-hand rule. In finding $\mathbf{w} \times \mathbf{v}$, you start with your index finger (of your right hand!) fully extended along $\mathbf{w}$ and your middle finger along $\mathbf{v}$ such that your middle finger is between your index finger and your palm. Then, extend your thumb perpendicular to the plane generated by these two fingers, and your thumb will be pointing in exactly the opposite direction from the way it pointed when we found $\mathbf{v} \times \mathbf{w}$, as shown.

Problem 12.18: Show that for any scalar $c$ and any two vectors $\mathbf{u}$ and $\mathbf{v}$, we have $\mathbf{u} \times(c \mathbf{v})=(c \mathbf{u}) \times \mathbf{v}=c(\mathbf{u} \times \mathbf{v})$.

Solution for Problem 12.18: Our expression of the cross product as the determinant of a $3 \times 3$ matrix makes this pretty straightforward:
$$\left|\begin{array}{ccc}
\mathbf{i} & \mathbf{j} & \mathbf{k} \\
c u_{1} & c u_{2} & c u_{3} \\
v_{1} & v_{2} & v_{3}
\end{array}\right|=c\left|\begin{array}{ccc}
\mathbf{i} & \mathbf{j} & \mathbf{k} \\
u_{1} & u_{2} & u_{3} \\
v_{1} & v_{2} & v_{3}
\end{array}\right|=\left|\begin{array}{ccc}
\mathbf{i} & \mathbf{j} & \mathbf{k} \\
u_{1} & u_{2} & u_{3} \\
c v_{1} & c v_{2} & c v_{3}
\end{array}\right|,$$

445

---

<!-- Page 446 -->

CHAPTER 12. VECTORS AND MATRICES IN THREE DIMENSIONS, PART 2

so
$$(c \mathbf{u}) \times \mathbf{v}=c(\mathbf{u} \times \mathbf{v})=\mathbf{u} \times(c \mathbf{v}) .$$

Problem 12.19: Show that $\mathbf{u} \times(\mathbf{v}+\mathbf{w})=\mathbf{u} \times \mathbf{v}+\mathbf{u} \times \mathbf{w}$ and $(\mathbf{u}+\mathbf{v}) \times \mathbf{w}=\mathbf{u} \times \mathbf{w}+\mathbf{v} \times \mathbf{w}$.

Solution for Problem 12.19: Again, the properties we proved about determinants of $3 \times 3$ matrices save the day. We have
$$\mathbf{u} \times \mathbf{v}+\mathbf{u} \times \mathbf{w}=\left|\begin{array}{ccc}
\mathbf{i} & \mathbf{j} & \mathbf{k} \\
u_{1} & u_{2} & u_{3} \\
v_{1} & v_{2} & v_{3}
\end{array}\right|+\left|\begin{array}{ccc}
\mathbf{i} & \mathbf{j} & \mathbf{k} \\
u_{1} & u_{2} & u_{3} \\
w_{1} & w_{2} & w_{3}
\end{array}\right|=\left|\begin{array}{ccc}
\mathbf{i} & \mathbf{j} & \mathbf{k} \\
u_{1} & u_{2} & u_{3} \\
v_{1}+w_{1} & v_{2}+w_{2} & v_{3}+w_{3}
\end{array}\right|=\mathbf{u} \times(\mathbf{v}+\mathbf{w}),$$
where we used the principle we proved in Problem 11.21 to combine the sum of determinants of matrices with two rows in common into one determinant.

Combining this result with the fact that $\mathbf{a} \times \mathbf{b}=-\mathbf{b} \times \mathbf{a}$ for all $\mathbf{a}$ and $\mathbf{b}$, we have
$$(\mathbf{u}+\mathbf{v}) \times \mathbf{w}=-\mathbf{w} \times(\mathbf{u}+\mathbf{v})=-\mathbf{w} \times \mathbf{u}-\mathbf{w} \times \mathbf{v}=\mathbf{u} \times \mathbf{w}+\mathbf{v} \times \mathbf{w} .$$

Combining Problems 12.18 and 12.19, we see that for any $\mathbf{u}$, both $f(\mathbf{v})=\mathbf{u} \times \mathbf{v}$ and $f(\mathbf{v})=\mathbf{v} \times \mathbf{u}$ are linear, so the cross product is bilinear, just like the dot product. (However, as a reminder, the cross product is not commutative, but the dot product is.)

Problem 12.20: Show that if $\theta$ is the angle between nonzero vectors $\mathbf{u}$ and $\mathbf{v}$, then $\|\mathbf{u} \times \mathbf{v}\|=\|\mathbf{u}\|\|\mathbf{v}\| \sin \theta$.

Solution for Problem 12.20: We start by writing an expression for our target, $\|\mathbf{u} \times \mathbf{v}\|$ :
$$\begin{aligned}
\|\mathbf{u} \times \mathbf{v}\| & =\sqrt{\left|\begin{array}{ll}
u_{2} & u_{3} \\
v_{2} & v_{3}
\end{array}\right|^{2}+\left|\begin{array}{ll}
u_{1} & u_{3} \\
v_{1} & v_{3}
\end{array}\right|^{2}+\left|\begin{array}{ll}
u_{1} & u_{2} \\
v_{1} & v_{2}
\end{array}\right|^{2}} \\
& =\sqrt{\left(u_{2} v_{3}-u_{3} v_{2}\right)^{2}+\left(u_{1} v_{3}-u_{3} v_{1}\right)^{2}+\left(u_{1} v_{2}-u_{2} v_{1}\right)^{2}} \\
& =\sqrt{u_{2}^{2} v_{3}^{2}+u_{3}^{2} v_{2}^{2}+u_{1}^{2} v_{3}^{2}+u_{3}^{2} v_{1}^{2}+u_{1}^{2} v_{2}^{2}+u_{2}^{2} v_{1}^{2}-2 u_{2} u_{3} v_{2} v_{3}-2 u_{1} v_{1} u_{3} v_{3}-2 u_{1} u_{2} v_{1} v_{2}}
\end{aligned}$$

That's quite a mess. However, looking at the other side of the desired equation, $\|\mathbf{u}\|\|\mathbf{v}\| \sin \theta$, we have some hope, since terms like $u_{2}^{2} v_{3}^{2}$ will appear in the product $\|\mathbf{u}\|\|\mathbf{v}\|$. We don't immediately know how to express $\sin \theta$ in terms of $\mathbf{u}$ and $\mathbf{v}$, but we do know how to deal with $\cos \theta$, since $\mathbf{u} \cdot \mathbf{v}=\|\mathbf{u}\|\|\mathbf{v}\| \cos \theta$. Combining this with $\sin ^{2} \theta=1-\cos ^{2} \theta$, we can express $\|\mathbf{u}\|\|\mathbf{v}\| \sin \theta$ in terms of the components of $\mathbf{u}$ and $\mathbf{v}$. We start by finding $(\|\mathbf{u}\|\|\mathbf{v}\| \sin \theta)^{2}$, since this gets rid of the annoying square root signs:
$$\begin{aligned}
\|\mathbf{u}\|^{2}\|\mathbf{v}\|^{2} \sin ^{2} \theta & =\|\mathbf{u}\|^{2}\|\mathbf{v}\|^{2}\left(1-\cos ^{2} \theta\right) \\
& =\|\mathbf{u}\|^{2}\|\mathbf{v}\|^{2}\left(1-\frac{(\mathbf{u} \cdot \mathbf{v})^{2}}{\|\mathbf{u}\|^{2}\|\mathbf{v}\|^{2}}\right) \\
& =\|\mathbf{u}\|^{2}\|\mathbf{v}\|^{2}-(\mathbf{u} \cdot \mathbf{v})^{2} \\
& =\left(u_{1}^{2}+u_{2}^{2}+u_{3}^{2}\right)\left(v_{1}^{2}+v_{2}^{2}+v_{3}^{2}\right)-\left(u_{1} v_{1}+u_{2} v_{2}+u_{3} v_{3}\right)^{2}
\end{aligned}$$

The terms $u_{1}^{2} v_{1}^{2}, u_{2}^{2} v_{2}^{2}$, and $u_{3}^{2} v_{3}^{2}$ appear in both the expansion of the product and of the square, so these cancel when we subtract, and we're left with
$$\|\mathbf{u}\|^{2}\|\mathbf{v}\|^{2} \sin ^{2} \theta=u_{2}^{2} v_{3}^{2}+u_{3}^{2} v_{2}^{2}+u_{1}^{2} v_{3}^{2}+u_{3}^{2} v_{1}^{2}+u_{1}^{2} v_{2}^{2}+u_{2}^{2} v_{1}^{2}-2 u_{2} u_{3} v_{2} v_{3}-2 u_{1} v_{1} u_{3} v_{3}-2 u_{1} u_{2} v_{1} v_{2},$$
which is exactly the square of the expression we found for $\|\mathbf{u} \times \mathbf{v}\|$, so $\|\mathbf{u} \times \mathbf{v}\|^{2}=\|\mathbf{u}\|^{2}\|\mathbf{v}\|^{2} \sin ^{2} \theta$. Since we have $0 \leq \theta \leq \pi$, we know that $\|\mathbf{u}\|\|\mathbf{v}\| \sin \theta$ is nonnegative, so taking the square root of both sides gives us $\|\mathbf{u} \times \mathbf{v}\|=\|\mathbf{u}\|\|\mathbf{v}\| \sin \theta$.

446

---

<!-- Page 447 -->

12.3. THE CROSS PRODUCT

Important: For any nonzero vectors $\mathbf{u}$ and $\mathbf{v}$ in three dimensions, we have
$$\|\mathbf{u} \times \mathbf{v}\|=\|\mathbf{u}\|\|\mathbf{v}\| \sin \theta,$$
where $\theta$ is the angle between $\mathbf{u}$ and $\mathbf{v}$.

Problem 12.21: Find $\mathbf{i} \times \mathbf{j}, \mathbf{j} \times \mathbf{k}$, and $\mathbf{k} \times \mathbf{i}$.

Solution for Problem 12.21: We could use the determinant formula for the cross product to compute the results, but we can also find them with a little geometric intuition. In each case, both vectors have magnitude 1, and the angle between the vectors is $\frac{\pi}{2}$, so the relationship $\|\mathbf{v} \times \mathbf{w}\|=\|\mathbf{v}\|\|\mathbf{w}\| \sin \theta$ tells us that the magnitude of each cross product is 1 , since $\sin \frac{\pi}{2}=1$.

All we have left is to determine the direction of each cross product. Each of $\mathbf{i}$, $\mathbf{j}$, and $\mathbf{k}$ is orthogonal to the other two. Combining this with the fact that $\mathbf{i} \times \mathbf{j}$ has magnitude 1 , we know that $\mathbf{i} \times \mathbf{j}$ is either $\mathbf{k}$ or $-\mathbf{k}$. Applying the right-hand rule reveals
that $\mathbf{i} \times \mathbf{j}=\mathbf{k}$. Similarly, we find $\mathbf{j} \times \mathbf{k}=\mathbf{i}$ and $\mathbf{k} \times \mathbf{i}=\mathbf{j}$.

We can visualize these relationships with the diagram at right. For any cross product of the two vectors, if we go in the direction of the arrows (which is in the direction of alphabetical order starting with i) to get from the first vector in the cross product directly to the second, then the cross product equals the third vector. If we must go in the opposite direction of the arrows, such as $\mathbf{k} \times \mathbf{j}$, then the
result is the negative of the third vector, so $\mathbf{k} \times \mathbf{j}=-\mathbf{i}$.

Problem 12.22:
(a) Find $(6 \mathbf{i}+9 \mathbf{j}-3 \mathbf{k}) \times(2 \mathbf{i}+3 \mathbf{j}-\mathbf{k})$.
(b) If $\mathbf{r}=c \mathbf{s}$ for some scalar $c$, then must we have $\mathbf{r} \times \mathbf{s}=\mathbf{0}$ ?
(c) If $\mathbf{r} \times \mathbf{s}=\mathbf{0}$ and $\mathbf{s} \neq \mathbf{0}$, then must we have $\mathbf{r}=c \mathbf{s}$ for some scalar $c$ ?

Solution for Problem 12.22:
(a) We have
$$\mathbf{u} \times \mathbf{v}=\left|\begin{array}{ccc}
\mathbf{i} & \mathbf{j} & \mathbf{k} \\
6 & 9 & -3 \\
2 & 3 & -1
\end{array}\right|=0 \mathbf{i}+0 \mathbf{j}+0 \mathbf{k}=\mathbf{0} .$$

We also could have seen that this determinant equals $\mathbf{0}$ by noting that the second row is a constant times the third.
(b) Our final observation in part (a) makes it clear that the answer to this part is yes. Letting $\mathbf{s}=s_{1} \mathbf{i}+s_{2} \mathbf{j}+s_{3} \mathbf{k}$, we have
$$\mathbf{r} \times \mathbf{s}=(c \mathbf{s}) \times \mathbf{s}=\left|\begin{array}{ccc}
\mathbf{i} & \mathbf{j} & \mathbf{k} \\
c s_{1} & c s_{2} & c s_{3} \\
s_{1} & s_{2} & s_{3}
\end{array}\right|=\mathbf{0},$$
since the second row is a constant times the third. We can also see that $\mathbf{r} \times \mathbf{s}=\mathbf{0}$ if $\mathbf{r}=c \mathbf{s}$ by noting that the angle $\theta$ between nonzero vectors s and $c \mathrm{~s}$ is 0 if $c>0$ and $\pi$ if $c<0$. In either case, we have $\sin \theta=0$, so
$$\|\mathbf{r} \times \mathbf{s}\|=\|\mathbf{r}\|\|\mathbf{s}\| \sin \theta=0 .$$

Therefore, we must have $\mathbf{r} \times \mathbf{s}=\mathbf{0}$.
We also could have noted that $(c \mathbf{s}) \times \mathbf{s}=c(\mathbf{s} \times \mathbf{s})$. Since $\mathbf{a} \times \mathbf{b}=-\mathbf{b} \times \mathbf{a}$ for any a and $\mathbf{b}$, letting $\mathbf{a}=\mathbf{b}=\mathbf{s}$ gives $\mathbf{s} \times \mathbf{s}=-\mathbf{s} \times \mathbf{s}$, so $\mathbf{s} \times \mathbf{s}=\mathbf{0}$. Therefore, we have $(c \mathbf{s}) \times \mathbf{s}=c(\mathbf{s} \times \mathbf{s})=\mathbf{0}$.

447

---

<!-- Page 448 -->

CHAPTER 12. VECTORS AND MATRICES IN THREE DIMENSIONS, PART 2
(c) Since $\|\mathbf{r} \times \mathbf{s}\|=\|\mathbf{r}\|\|\mathbf{s}\| \sin \theta$, where $\theta$ is the angle between $\mathbf{r}$ and $\mathbf{s}$, we must have $\mathbf{r}=\mathbf{0}$ or $\sin \theta=0$ if $\mathbf{r} \times \mathbf{s}=\mathbf{0}$ and $\mathbf{s} \neq \mathbf{0}$. If $\mathbf{r}=\mathbf{0}$, then $\mathbf{r}=0 \mathbf{s}$. If $\sin \theta=0$, then $\theta=0$ or $\theta=\pi$. If $\theta=0$, then $\mathbf{r}$ and $\mathbf{s}$ are in the same direction, so $\mathbf{r}=c \mathbf{s}$ for some positive $c$. If $\theta=\pi$, then $\mathbf{r}$ and $\mathbf{s}$ are in opposite directions, so $\mathbf{r}=c \mathbf{s}$ for some negative $c$. Therefore, in all possible cases, there is a scalar $c$ such that $\mathbf{r}=c \mathbf{s}$.

Problem 12.23: If $\mathbf{u}, \mathbf{v}$, and $\mathbf{w}$ are nonzero vectors such that $\mathbf{u} \times \mathbf{v}=\mathbf{u} \times \mathbf{w}$, then must we have $\mathbf{v}=\mathbf{w}$ ?
Solution for Problem 12.23: We subtract $\mathbf{u} \times \mathbf{w}$ from both sides and we have
$$\mathbf{u} \times \mathbf{v}-\mathbf{u} \times \mathbf{w}=\mathbf{0} .$$

Applying the properties we proved in Problems 12.18 and 12.19, we have
$$\mathbf{u} \times(\mathbf{v}-\mathbf{w})=\mathbf{0} .$$

Since there are vectors besides $\mathbf{0}$ whose cross product with $\mathbf{u}$ is $\mathbf{0}$ (namely, $k \mathbf{u}$ for any scalar $k$ ), we cannot conclude that $\mathbf{v}-\mathbf{w}=\mathbf{0}$ from the fact that $\mathbf{u} \times(\mathbf{v}-\mathbf{w})=\mathbf{0}$. Therefore, we cannot conclude that $\mathbf{v}=\mathbf{w}$.
$$\begin{array}{|ll}
\text { WARNING!! } & \text { If nonzero vectors } \mathbf{u}, \mathbf{v} \text {, and } \mathbf{w} \text { satisfy } \mathbf{u} \times \mathbf{v}=\mathbf{u} \times \mathbf{w} \text {, then we cannot conclude } \\
\text { that } \mathbf{v} \text { and } \mathbf{w} \text { are equal. }
\end{array}$$

Problem 12.24: Let $A=(1,3,2), B=(-3,5,3)$, and $C=(0,-2,-6)$. Find an equation whose graph is the plane that passes through all three points.

Solution for Problem 12.24: We know how to find an equation of a plane given a point in the plane and a vector normal to the plane, so all we have to do is find a vector normal to the plane through $A, B$, and $C$. We've just learned a tool for finding a vector normal to two other vectors: the cross product. So, to find a vector normal to the plane, we find $\overrightarrow{A B} \times \overrightarrow{A C}$. We have
$$\begin{array}{l}
\overrightarrow{A B}=\vec{B}-\vec{A}=(-3-1) \mathbf{i}+(5-3) \mathbf{j}+(3-2) \mathbf{k}=-4 \mathbf{i}+2 \mathbf{j}+\mathbf{k} \\
\overrightarrow{A C}=\vec{C}-\vec{A}=(0-1) \mathbf{i}+(-2-3) \mathbf{j}+(-6-2) \mathbf{k}=-\mathbf{i}-5 \mathbf{j}-8 \mathbf{k}
\end{array}$$

Therefore, we have
$$\overrightarrow{A B} \times \overrightarrow{A C}=\left|\begin{array}{ccc}
\mathbf{i} & \mathbf{j} & \mathbf{k} \\
-4 & 2 & 1 \\
-1 & -5 & -8
\end{array}\right|=-11 \mathbf{i}-33 \mathbf{j}+22 \mathbf{k},$$
so $-11 \mathbf{i}-33 \mathbf{j}+22 \mathbf{k}$ is normal to the plane through $A, B$, and $C$. Factoring out 11 , we can write this vector as $11(-\mathbf{i}-3 \mathbf{j}+2 \mathbf{k})$, so $-\mathbf{i}-3 \mathbf{j}+2 \mathbf{k}$ is normal to the plane, and the desired equation is $-x-3 y+2 z=d$ for some constant $d$. Point $A$ is on the graph of this equation, so we substitute $(1,3,2)$ into the equation to find $d=-6$. Therefore, the graph of $-x-3 y+2 z=-6$ is the plane that passes through $A, B$, and $C$.

Problem 12.25: Let $E$ be $(1,0,-2)$, let $F$ be $(-2,3,-1)$, let $G$ be $(4,2,-3)$, and let $H$ be the point such that $E F G H$ is a parallelogram. Find the area of $E F G H$.

448

---

<!-- Page 449 -->

12.3. THE CROSS PRODUCT

Solution for Problem 12.25: The area of a parallelogram equals the length of a side times the distance between that side and the opposite side. We can easily find the side lengths of the parallelogram, but finding the distance between opposite sides is cumbersome. Instead, we note that drawing a diagonal of the parallelogram divides it into two congruent triangles,
as shown at right. So, the area of $E F G H$ is twice the area of $\triangle E F G$. But how will we find [EFG]? We turn to trigonometry, and we have
$$[E F G H]=2[E F G]=2\left(\frac{1}{2}(E F)(F G) \sin \angle E F G\right)=(E F)(F G) \sin \angle E F G .$$

This expression looks familiar! Back in Problem 12.20, we found that $\|\mathbf{u} \times \mathbf{v}\|=\|\mathbf{u}\|\|\mathbf{v}\| \sin \theta$, where $\theta$ is the angle between $\mathbf{u}$ and $\mathbf{v}$. Applying this here, we have $\|\overrightarrow{F E} \times \overrightarrow{F G}\|=(E F)(F G) \sin \angle E F G$, so the area of $\mathcal{A}$ equals $\|\overrightarrow{F E} \times \overrightarrow{F G}\|$. Since $\overrightarrow{F E}=(1-(-2)) \mathbf{i}+(0-3) \mathbf{j}+((-2)-(-1)) \mathbf{k}=3 \mathbf{i}-3 \mathbf{j}-\mathbf{k}$ and $\overrightarrow{F G}=(4-(-2)) \mathbf{i}+(2-3) \mathbf{j}+((-3)-(-1)) \mathbf{k}=6 \mathbf{i}-\mathbf{j}-2 \mathbf{k}$, we have
$$\text { Area of } \mathcal{A}=\|\overrightarrow{F E} \times \overrightarrow{F G}\|=\left\|\operatorname{det}\left(\begin{array}{ccc}
\mathbf{i} & \mathbf{j} & \mathbf{k} \\
3 & -3 & -1 \\
6 & -1 & -2
\end{array}\right)\right\|=\|5 \mathbf{i}+0 \mathbf{j}+15 \mathbf{k}\|=\sqrt{5^{2}+15^{2}}=5 \sqrt{10} .$$

In the process of solving Problem 12.25, we found another relationship between geometry and the cross product.
```
Important: The area of a parallelogram with v and w as sides is |v\timesw|\mathrm{ . }
    Q
```

Exercises
12.3.1 Let $\mathbf{a}=\left(\begin{array}{c}3 \\ 4 \\ -1\end{array}\right), \mathbf{b}=\left(\begin{array}{c}-1 \\ 7 \\ 0\end{array}\right)$, and $\mathbf{c}=\left(\begin{array}{c}-4 \\ -1 \\ 3\end{array}\right)$.
(a) Find $\mathbf{a} \times \mathbf{b}$.
(b) Find $\mathbf{b} \times \mathbf{c}$.
(c) Find $\mathbf{c} \times \mathbf{a}$.
12.3.2 Find an equation whose graph is a plane through $(-1,3,4),(2,1,-5)$, and $(-7,-1,0)$.
12.3.3 Find nonzero vectors $\mathbf{u}, \mathbf{v}$, and $\mathbf{w}$ such that $\mathbf{u} \times \mathbf{v}=\mathbf{u} \times \mathbf{w}$, but $\mathbf{v} \neq \mathbf{w}$.
12.3.4 Find the area of a triangle with vertices $(-1,3,0),(-2,5,6)$, and $(6,0,-4)$.
12.3.5 Show that $\|\mathbf{u} \times \mathbf{v}\|^{2}=\|\mathbf{u}\|^{2}\|\mathbf{v}\|^{2}-(\mathbf{u} \cdot \mathbf{v})^{2}$. This is called the Lagrange Identity.
12.3.6 ★
(a) Show that $\mathbf{a} \times(\mathbf{b} \times \mathbf{c})=(\mathbf{a} \cdot \mathbf{c}) \mathbf{b}-(\mathbf{a} \cdot \mathbf{b}) \mathbf{c}$.
(b) Show that $\mathbf{a} \times(\mathbf{b} \times \mathbf{c})+\mathbf{b} \times(\mathbf{c} \times \mathbf{a})+\mathbf{c} \times(\mathbf{a} \times \mathbf{b})=\mathbf{0}$. This is called the Jacobi Identity.

449

---

<!-- Page 450 -->

CHAPTER 12. VECTORS AND MATRICES IN THREE DIMENSIONS, PART 2
12.4 Geometric Interpretation of the Determinant

In Section 10.5, we found a geometric interpretation of the determinant of a $2 \times 2$ matrix. This interpretation described the determinant in terms of area. Moving up to three dimensions, maybe we can describe the determinant of a $3 \times 3$ matrix in terms of volume.

In two dimensions, we linked the determinant to the area of a parallelogram. The three-dimensional analogue of a parallelogram is a parallelepiped, which is a prism in which all six faces are parallelograms. An example is shown at right.

Problems
Problem 12.26: Let $O$ be the origin, $U$ be $\left(u_{1}, u_{2}, u_{3}\right), V$ be $\left(v_{1}, v_{2}, v_{3}\right)$, and $W$ be $\left(w_{1}, w_{2}, w_{3}\right)$. Also, let $\mathbf{u}=\vec{U}$, $\mathbf{v}=\vec{V}$, and $\mathbf{w}=\vec{W}$. In this problem, we show that the volume of the parallelepiped with $\overline{\mathrm{OU}}, \overline{\mathrm{OV}}$, and $\overline{\mathrm{OW}}$ as edges is $|\mathbf{u} \cdot(\mathbf{v} \times \mathbf{w})|$.
(a) Let $\mathcal{P}$ be the parallelogram with sides $\overline{\mathrm{OV}}$ and $\overline{\mathrm{OW}}$. Find the area of $\mathcal{P}$ in terms of $\mathbf{v}$ and $\mathbf{w}$.
(b) Find the distance from $U$ to the plane of $\mathcal{P}$ in terms of $\mathbf{u}, \mathbf{v}$, and $\mathbf{w}$.
(c) Show that the volume of the parallelepiped with $\overline{\mathrm{OU}}, \overline{\mathrm{OV}}$, and $\overline{\mathrm{OW}}$ as edges is $|\mathbf{u} \cdot(\mathbf{v} \times \mathbf{w})|$.

Problem 12.27: Let $\mathbf{u}=u_{1} \mathbf{i}+u_{2} \mathbf{j}+u_{3} \mathbf{k}, \mathbf{v}=v_{1} \mathbf{i}+v_{2} \mathbf{j}+v_{3} \mathbf{k}$, and $\mathbf{w}=w_{1} \mathbf{i}+w_{2} \mathbf{j}+w_{3} \mathbf{k}$. Express $\mathbf{u} \cdot(\mathbf{v} \times \mathbf{w})$ as the determinant of a $3 \times 3$ matrix whose entries are components of $\mathbf{u}, \mathbf{v}$, and $\mathbf{w}$.

Problem 12.28: Find the volume of the tetrahedron with vertices $(3,4,-1),(-2,3,5),(4,-1,0)$, and $(-5,5,2)$.
Problem 12.29: Let $\mathbf{A}=\left(\begin{array}{ccc}3 & -1 & 4 \\ -1 & 1 & -2 \\ -5 & 2 & -7\end{array}\right)$.
(a) Find $\operatorname{det}(\mathbf{A})$.
(b) Why does your answer to part (a) tell you that the vectors $\left(\begin{array}{c}3 \\ -1 \\ 4\end{array}\right),\left(\begin{array}{c}-1 \\ 1 \\ -2\end{array}\right)$, and $\left(\begin{array}{c}-5 \\ 2 \\ -7\end{array}\right)$ are not linearly independent?

Problem 12.30: Let $\mathbf{M}$ be a $3 \times 3$ matrix.
(a) Show that $\operatorname{det} \mathbf{M}=0$ if and only if the rows of $\mathbf{M}$ are linearly dependent.
(b) Show that $\operatorname{det} \mathbf{M}=0$ if and only if the columns of $\mathbf{M}$ are linearly dependent.

We found in Section 10.5 that if two given vectors from the same point represent the sides of a parallelogram, then the signed area of the parallelogram equals the determinant of the matrix with these two vectors as columns (or rows). A reasonable guess in three dimensions is that the determinant corresponds to the volume of a parallelepiped. So, let's see if we can find an expression for the volume of a parallelepiped in terms of three vectors that represent edges from the same vertex of the parallelepiped.

Problem 12.26: Let $O$ be the origin, $U$ be $\left(u_{1}, u_{2}, u_{3}\right), V$ be $\left(v_{1}, v_{2}, v_{3}\right)$, and $W$ be $\left(w_{1}, w_{2}, w_{3}\right)$. Also, let $\mathbf{u}=\vec{U}$, $\mathbf{v}=\vec{V}$, and $\mathbf{w}=\vec{W}$. Show that the volume of the parallelepiped with $\overline{O U}, \overline{O V}$, and $\overline{O W}$ as edges is $|\mathbf{u} \cdot(\mathbf{v} \times \mathbf{w})|$.

450

---

<!-- Page 451 -->

12.4. GEOMETRIC INTERPRETATION OF THE DETERMINANT

Solution for Problem 12.26: The volume of a parallelepiped equals the area of a face times the distance between that face and the opposite face. Each face of a parallelepiped is a parallelogram, and we know how to find the area of a parallelogram that has two vectors as consecutive sides. We let $Y$ be the point such that $O V Y W$ is a parallelogram, and let $\theta=\angle V O W$. Then,
$$[O V Y W]=(O V)(O W) \sin \theta=\|\mathbf{v} \times \mathbf{w}\| .$$

To find the distance between $O V Y W$ and the opposite face, we find the distance must $U$ to $O V Y W$. We discovered how to do this in Problem 12.13; this distance is the magnitude of the projection of $\vec{U}$ onto a vector normal to the plane of $O V Y W$. We know how to find such a normal vector: $\mathbf{v} \times \mathbf{w}$ is normal to the plane generated by $\mathbf{v}$ and $\mathbf{w}$. So, since $\vec{U}=\mathbf{u}$, the desired height is $\operatorname{proj}_{\mathbf{v} \times \mathbf{w}} \mathbf{u}$, as shown in the diagram. This gives us
$$\begin{aligned}
\text { Volume }=\left\|\operatorname{proj}_{\mathbf{v} \times \mathbf{w}} \mathbf{u}\right\|[O V Y W] & =\left\|\frac{\mathbf{u} \cdot(\mathbf{v} \times \mathbf{w})}{\|\mathbf{v} \times \mathbf{w}\|^{2}}(\mathbf{v} \times \mathbf{w})\right\|\|\mathbf{v} \times \mathbf{w}\| \\
& =\frac{|\mathbf{u} \cdot(\mathbf{v} \times \mathbf{w})|}{\|\mathbf{v} \times \mathbf{w}\|^{2}}\|\mathbf{v} \times \mathbf{w}\|^{2} \\
& =|\mathbf{u} \cdot(\mathbf{v} \times \mathbf{w})|
\end{aligned}$$

We can use signed volume to get rid of the absolute value sign in $|\mathbf{u} \cdot(\mathbf{v} \times \mathbf{w})|$, similar to how we used signed area in two dimensions. Specifically, we say the volume of the parallelepiped with edges $\mathbf{u}, \mathbf{v}$ and $\mathbf{w}$ is positive if the vector given by $\mathbf{v} \times \mathbf{w}$ makes an acute angle with $\mathbf{u}$, and the volume is negative if $\mathbf{v} \times \mathbf{w}$ makes an obtuse angle with $\mathbf{u}$. Another way to think about this is with the right-hand rule. If $\mathbf{u}$ is on the same side of the plane generated by $\mathbf{v}$ and $\mathbf{w}$ as indicated by the right-hand rule applied to $\mathbf{v} \times \mathbf{w}$, then the volume is positive. If $\mathbf{u}$ is on the opposite side, then the volume is negative.

> Important: Let $O$ be the origin, $U$ be $\left(u_{1}, u_{2}, u_{3}\right), V$ be $\left(v_{1}, v_{2}, v_{3}\right)$, and $W$ be $\left(w_{1}, w_{2}, w_{3}\right)$. Also,
> \let $\mathbf{u}=\vec{U}, \mathbf{v}=\vec{V}$, and $\mathbf{w}=\vec{W}$. The signed volume of the parallelepiped with $\overline{O U}, \overline{O V}$, and $\overline{O W}$ as edges is $\mathbf{u} \cdot(\mathbf{v} \times \mathbf{w})$.

We call $\mathbf{u} \cdot(\mathbf{v} \times \mathbf{w})$ a box product or scalar triple product of $\mathbf{u}, \mathbf{v}$, and $\mathbf{w}$.
Now, we're ready to relate the determinant of a $3 \times 3$ matrix to volume.
Problem 12.27: Let $\mathbf{u}=u_{1} \mathbf{i}+u_{2} \mathbf{j}+u_{3} \mathbf{k}, \mathbf{v}=v_{1} \mathbf{i}+v_{2} \mathbf{j}+v_{3} \mathbf{k}$, and $\mathbf{w}=w_{1} \mathbf{i}+w_{2} \mathbf{j}+w_{3} \mathbf{k}$. Express $\mathbf{u} \cdot(\mathbf{v} \times \mathbf{w})$ as the determinant of a $3 \times 3$ matrix whose entries are components of $\mathbf{u}, \mathbf{v}$, and $\mathbf{w}$.

Solution for Problem 12.27: We have
$$\begin{aligned}
\mathbf{u} \cdot(\mathbf{v} \times \mathbf{w})=\left(u_{1} \mathbf{i}+u_{2} \mathbf{j}+u_{3} \mathbf{k}\right) \cdot\left|\begin{array}{ccc}
\mathbf{i} & \mathbf{j} & \mathbf{k} \\
v_{1} & v_{2} & v_{3} \\
w_{1} & w_{2} & w_{3}
\end{array}\right| & =\left(u_{1} \mathbf{i}+u_{2} \mathbf{j}+u_{3} \mathbf{k}\right) \cdot\left(\left|\begin{array}{ll}
v_{2} & v_{3} \\
w_{2} & w_{3}
\end{array}\right| \mathbf{i}-\left|\begin{array}{ll}
v_{1} & v_{3} \\
w_{1} & w_{3}
\end{array}\right| \mathbf{j}+\left|\begin{array}{ll}
v_{1} & v_{2} \\
w_{1} & w_{2}
\end{array}\right| \mathbf{k}\right) \\
& =u_{1}\left|\begin{array}{cc}
v_{2} & v_{3} \\
w_{2} & w_{3}
\end{array}\right|-u_{2}\left|\begin{array}{ll}
v_{1} & v_{3} \\
w_{1} & w_{3}
\end{array}\right|+u_{3}\left|\begin{array}{cc}
v_{1} & v_{2} \\
w_{1} & w_{2}
\end{array}\right| \\
& =\left|\begin{array}{ccc}
u_{1} & u_{2} & u_{3} \\
v_{1} & v_{2} & v_{3} \\
w_{1} & w_{2} & w_{3}
\end{array}\right| .
\end{aligned}$$

451

---

<!-- Page 452 -->

CHAPTER 12. VECTORS AND MATRICES IN THREE DIMENSIONS, PART 2

Therefore, we can express the volume of a parallelepiped as a box product, and we can express the box product as a determinant. Putting these together, we have:

Important: Let $O$ be the origin, $U$ be $\left(u_{1}, u_{2}, u_{3}\right), V$ be $\left(v_{1}, v_{2}, v_{3}\right)$, and $W$ be $\left(w_{1}, w_{2}, w_{3}\right)$. The
determinant
$$\left|\begin{array}{ccc}
u_{1} & u_{2} & u_{3} \\
v_{1} & v_{2} & v_{3} \\
w_{1} & w_{2} & w_{3}
\end{array}\right|$$
equals the signed volume of the parallelepiped with $\overline{O U}, \overline{O V}$, and $\overline{O W}$ as edges.

We noted on page 367 that if $\mathbf{M}$ is a $2 \times 2$ matrix and $\mathbf{v}$ and $\mathbf{w}$ are vectors in 2 dimensions, then the parallelogram with $\mathbf{M v}$ and $\mathbf{M w}$ as sides has signed area $\operatorname{det}(\mathbf{M})$ times the signed area of the parallelogram with $\mathbf{v}$ and $\mathbf{w}$. Analogously, if $\mathbf{N}$ is a $3 \times 3$ matrix and $\mathbf{r}, \mathbf{s}$, and $\mathbf{t}$ are vectors in 3 dimensions, then the parallelepiped with edges $\mathbf{N r} \boldsymbol{,} \mathbf{N s}$, and Nt has signed volume $\operatorname{det}(\mathbf{N})$ times the signed volume of the parallelepiped with edges $\mathbf{r}, \mathbf{s}$, and $\mathbf{t}$.

This observation gives us an intuitive understanding for the following:

Important: If $\mathbf{A}$ and $\mathbf{B}$ are $3 \times 3$ matrices, then
$\operatorname{det}(\mathbf{A B})=\operatorname{det}(\mathbf{A}) \operatorname{det}(\mathbf{B})$.

Specifically, if we multiply each of $\mathbf{r}$, $\mathbf{s}$, and $\mathbf{t}$ by $\mathbf{A B}$, we get the same three vectors as if we multiply each first by $\mathbf{B}$ and then multiply the resulting products by $\mathbf{A}$. So, scaling the signed volume in one step by $\operatorname{det}(\mathbf{A B})$ gives the same signed volume as first scaling by $\operatorname{det}(\mathbf{B})$ and then scaling the result by $\operatorname{det}(\mathbf{A})$. Therefore, $\operatorname{det}(\mathbf{A B})=\operatorname{det}(\mathbf{A}) \operatorname{det}(\mathbf{B})$. (Note that this isn't a proof; it is an intuitive explanation meant to make you have a better feel for the result. Proving that $\operatorname{det}(\mathbf{A B})=\operatorname{det}(\mathbf{A}) \operatorname{det}(\mathbf{B})$ requires some more serious machinery, or a lot of patience with algebra.)

Problem 12.28: Find the volume of the tetrahedron with vertices $(3,4,-1),(-2,3,5),(4,-1,0)$, and $(-5,5,2)$.

Solution for Problem 12.28: First, we give the points the labels $O, A, B, C$, respectively. We know how to find the volume of a parallelepiped, so we try to relate the tetrahedron to a parallelepiped we can handle. Specifically, we know how to handle the parallelepiped with $\overline{O A}, \overline{O B}$, and $\overline{O C}$ as edges, so we try to relate the desired tetrahedron to this parallelepiped.

Let $D$ be the point such that $A O B D$ is a parallelogram, let $\mathcal{T}$ be tetrahedron $O A B C$, let $h$ be the height from $C$ to $A O B D$, and let $\mathcal{P}$ be the parallelepiped with $\overline{O A}, \overline{O B}$, and $\overline{O C}$ as edges. Then, we have
$$\operatorname{Volume}(\mathcal{T})=\frac{h[A O B]}{3}=\frac{h([A O B D] / 2)}{3}=\frac{h[A O B D]}{6}=\frac{\operatorname{Volume}(\mathcal{P})}{6} .$$

By Problem 12.27, the volume of $\mathcal{P}$ equals the absolute value of the determinant of the matrix with $\overrightarrow{O A}, \overrightarrow{O B}$, and $\overrightarrow{O C}$ as rows. Therefore, we have
$$\operatorname{Volume}(\mathcal{T})=\frac{1}{6}\left|\operatorname{det}\left(\begin{array}{ccc}
(-2)-3 & 3-4 & 5-(-1) \\
4-3 & (-1)-4 & 0-(-1) \\
(-5)-3 & 5-4 & 2-(-1)
\end{array}\right)\right|=\frac{1}{6}\left|\operatorname{det}\left(\begin{array}{ccc}
-5 & -1 & 6 \\
1 & -5 & 1 \\
-8 & 1 & 3
\end{array}\right)\right|=\frac{143}{6} .$$

452

---

<!-- Page 453 -->

12.4. GEOMETRIC INTERPRETATION OF THE DETERMINANT

Problem 12.29: Let $\mathbf{A}=\left(\begin{array}{ccc}3 & -1 & 4 \\ -1 & 1 & -2 \\ -5 & 2 & -7\end{array}\right)$.
(a) Find $\operatorname{det}(\mathbf{A})$.
(b) Why does your answer to part (a) tell you that the vectors $\left(\begin{array}{c}3 \\ -1 \\ 4\end{array}\right),\left(\begin{array}{c}-1 \\ 1 \\ -2\end{array}\right)$, and $\left(\begin{array}{c}-5 \\ 2 \\ -7\end{array}\right)$ are not linearly independent?

Solution for Problem 12.29:
(a) We have
$$\begin{aligned}
\operatorname{det}(\mathbf{A}) & =(3)(1)(-7)+(-1)(-2)(-5)+(4)(-1)(2)-(3)(-2)(2)-(-1)(-1)(-7)-(4)(1)(-5) \\
& =-21-10-8-(-12)-(-7)-(-20)=0 .
\end{aligned}$$
(b) By Problem 12.27, the determinant equals the signed volume of the parallelepiped with edges represented by the vectors $\mathbf{u}=\left(\begin{array}{c}3 \\ -1 \\ 4\end{array}\right), \mathbf{v}=\left(\begin{array}{c}-1 \\ 1 \\ -2\end{array}\right)$, and $\mathbf{w}=\left(\begin{array}{c}-5 \\ 2 \\ -7\end{array}\right)$. Since the determinant is 0 , we know that the volume of this parallelepiped is 0 . That is, the distance from the head of $\mathbf{u}$ to the plane generated by $\mathbf{v}$ and $\mathbf{w}$ is 0 . This means that $\mathbf{u}$ is in the plane generated by $\mathbf{v}$ and $\mathbf{w}$, so $\mathbf{u}$ is a linear combination of $\mathbf{v}$ and $\mathbf{w}$.

Problem 12.30: Let $\mathbf{M}$ be a $3 \times 3$ matrix.
(a) Show that $\operatorname{det} \mathbf{M}=0$ if and only if the rows of $\mathbf{M}$ are linearly dependent.
(b) Show that $\operatorname{det} \mathbf{M}=0$ if and only if the columns of $\mathbf{M}$ are linearly dependent.

Solution for Problem 12.30:
(a) We have already done all the heavy lifting for this problem. Suppose $U, V$ and $W$ are points in space, and let $\mathbf{M}$ be the matrix whose rows are $\vec{U}, \vec{V}$, and $\vec{W}$. Let $\mathcal{P}$ be the parallelepiped with edges $\overline{O U}, \overline{O V}$, and $\overline{O W}$. As usual, we let $O$ be the origin.

The volume of $\mathcal{P}$ is 0 if and only if $\vec{U}, \vec{V}$, and $\vec{W}$ are in the same plane, which is true if and only if these vectors are linearly dependent. Since $\operatorname{det}(\mathbf{M})$ equals the signed volume of $\mathcal{P}$, we therefore have $\operatorname{det}(\mathbf{M})$ if and only if $\vec{U}, \vec{V}$, and $\vec{W}$ are linearly dependent.

\begin{tabular}{ll} 
Important: & The determinant of a $3 \times 3$ matrix is 0 if and only if its rows are linearly \\
dependent.
\end{tabular}
(b) In Problem 11.16, we showed that $\operatorname{det}(\mathbf{M})=\operatorname{det}\left(\mathbf{M}^{T}\right)$. From part (a), $\operatorname{det}\left(\mathbf{M}^{T}\right)=0$ if and only if the rows of $\mathbf{M}^{T}$ are linearly dependent. The rows of $\mathbf{M}^{T}$ are the columns of $\mathbf{M}$ ! So, we have $\operatorname{det}(\mathbf{M})=0$ if and only if the columns of $\mathbf{M}$ are linearly dependent.

Important: The determinant of a $3 \times 3$ matrix is 0 if and only if its columns are linearly
dependent.

453

---

<!-- Page 454 -->

CHAPTER 12. VECTORS AND MATRICES IN THREE DIMENSIONS, PART 2

Combining parts (a) and (b) of this solution, we see that:
Important: The rows of a $3 \times 3$ matrix are linearly dependent if and only if the columns of the matrix are linearly dependent.

Exercises
12.4.1 The point $(-2,1,5)$ is one vertex of a parallelepiped, and it is connected by edges of the parallelepiped to $(4,-1,-2),(-1,2,-1)$, and $(4,-3,0)$. What is the volume of the parallelepiped?
12.4.2 Show that $\mathbf{a} \cdot(\mathbf{b} \times \mathbf{c})=(\mathbf{a} \times \mathbf{b}) \cdot \mathbf{c}$.
12.4.3 Suppose that each two rows of matrix $\mathbf{M}$ are orthogonal. Show that the product of the magnitudes of the rows equals | $\operatorname{det}(\mathbf{M})$ |.
12.5 Inverse of a $3 \times 3$ Matrix

As with $2 \times 2$ matrices, an inverse of a $3 \times 3$ matrix $\mathbf{A}$ is a matrix $\mathbf{B}$ such that $\mathbf{B A}=\mathbf{I}$. We denote the inverse of $\mathbf{A}$ as $\mathbf{A}^{-1}$. In Section 10.6, we showed that a $2 \times 2$ matrix has an inverse if and only if the determinant of the matrix is nonzero. In this section, we prove the same condition for the existence of an inverse of a $3 \times 3$ matrix.

Problems
Problem 12.31: As a reminder, we say that function $f$ that maps vectors to vectors is a linear function if
(i) $f(a \mathbf{v})=a f(\mathbf{v})$ for all scalars $a$ and vectors $\mathbf{v}$, and
(ii) $f(\mathbf{v}+\mathbf{w})=f(\mathbf{v})+f(\mathbf{w})$ for all vectors $\mathbf{v}$ and $\mathbf{w}$.

Show that if $g$ is a linear function that maps vectors to vectors (in three dimensions), then there is a matrix $\mathbf{A}$ such that $g(\mathbf{w})=$ Aw for all $\mathbf{w}$. Is this matrix unique for each function $g$ ?

Problem 12.32:
(a) Show that if $\operatorname{det}(\mathbf{A}) \neq 0$, then there exists a function $f$ such that for every $\mathbf{c}$, we have $\mathbf{A}(f(\mathbf{c}))=\mathbf{c}$.
(b) Show that the function you found in part (a) is linear.

Problem 12.33:
(a) Show that if $\operatorname{det}(\mathbf{A}) \neq 0$, then there is a matrix $\mathbf{B}$ such that $\mathbf{B A}=\mathbf{I}$.
(b) Is the matrix $\mathbf{B}$ you found in part (a) unique?
(c) Do we also have $\mathbf{A B}=\mathbf{I}$ for the matrix $\mathbf{B}$ you found in part (a)?

Problem 12.34: In this problem, we show that if $\operatorname{det}(\mathbf{A})=0$, then $\mathbf{A}$ does not have an inverse.
(a) Show that if $\operatorname{det}(\mathbf{A})=0$, then there is some vector $\mathbf{c}$ such that there is no solution $\mathbf{v}$ to $\mathbf{A v}=\mathbf{c}$.
(b) Use part (a) to show that $\mathbf{A}$ does not have an inverse if $\operatorname{det}(\mathbf{A})=0$.

454

---

<!-- Page 455 -->

12.5. INVERSE OF A $3 \times 3$ MATRIX

Problem 12.31: As a reminder, we say that function $f$ that maps vectors to vectors is a linear function if
(i) $f(a \mathbf{v})=a f(\mathbf{v})$ for all scalars $a$ and vectors $\mathbf{v}$, and
(ii) $f(\mathbf{v}+\mathbf{w})=f(\mathbf{v})+f(\mathbf{w})$ for all vectors $\mathbf{v}$ and $\mathbf{w}$.

Show that if $g$ is a linear function that maps vectors to vectors (in three dimensions), then there is a matrix $\mathbf{A}$ such that $g(\mathbf{w})=$ Aw for all $\mathbf{w}$. Is this matrix unique for each function $g$ ?

Solution for Problem 12.31: Back on page 354, we proved the equivalent statement in two dimensions. We use the same approach here.

We can write any vector $\mathbf{v}$ as $v_{1} \mathbf{i}+v_{2} \mathbf{j}+v_{3} \mathbf{k}$. Applying item (ii) in our definition of a linear function gives
$$g\left(v_{1} \mathbf{i}+v_{2} \mathbf{j}+v_{3} \mathbf{k}\right)=g\left(v_{1} \mathbf{i}\right)+g\left(v_{2} \mathbf{j}\right)+g\left(v_{3} \mathbf{k}\right) .$$

Then, applying item (i) to each term on the right, we have
$$g\left(v_{1} \mathbf{i}+v_{2} \mathbf{j}+v_{3} \mathbf{k}\right)=g\left(v_{1} \mathbf{i}\right)+g\left(v_{2} \mathbf{j}\right)+g\left(v_{3} \mathbf{k}\right)=v_{1} g(\mathbf{i})+v_{2} g(\mathbf{j})+v_{3} g(\mathbf{k}) .$$

Since $g$ maps vectors to vectors, we have
$$g(\mathbf{i})=\left(\begin{array}{c}
a_{11} \\
a_{21} \\
a_{31}
\end{array}\right), \quad g(\mathbf{j})=\left(\begin{array}{c}
a_{12} \\
a_{22} \\
a_{32}
\end{array}\right), \quad g(\mathbf{k})=\left(\begin{array}{c}
a_{13} \\
a_{23} \\
a_{33}
\end{array}\right),$$
for some scalars $a_{11}, a_{12}, \ldots, a_{33}$. Therefore, we have
$$g\left(\left(\begin{array}{l}
v_{1} \\
v_{2} \\
v_{3}
\end{array}\right)\right)=v_{1}\left(\begin{array}{l}
a_{11} \\
a_{21} \\
a_{31}
\end{array}\right)+v_{2}\left(\begin{array}{l}
a_{12} \\
a_{22} \\
a_{32}
\end{array}\right)+v_{3}\left(\begin{array}{l}
a_{13} \\
a_{23} \\
a_{33}
\end{array}\right)=\left(\begin{array}{l}
v_{1} a_{11}+v_{2} a_{12}+v_{3} a_{13} \\
v_{1} a_{21}+v_{2} a_{22}+v_{3} a_{23} \\
v_{1} a_{31}+v_{2} a_{32}+v_{3} a_{33}
\end{array}\right)=\left(\begin{array}{lll}
a_{11} & a_{12} & a_{13} \\
a_{21} & a_{22} & a_{23} \\
a_{31} & a_{32} & a_{33}
\end{array}\right)\left(\begin{array}{l}
v_{1} \\
v_{2} \\
v_{3}
\end{array}\right) .$$

This tells us that there exists a matrix $\mathbf{A}$ such that $g(\mathbf{v})=\mathbf{A v}$ for all vectors $\mathbf{v}$. Moreover, the matrix is unique, since its columns, in order, must be $g(\mathbf{i}), g(\mathbf{j})$, and $g(\mathbf{k})$.

\begin{tabular}{|cl|}
\hline Important: & Any linear function $g$ that maps vectors in $\mathbb{R}^{3}$ to vectors in $\mathbb{R}^{3}$ can be expressed \\
as multiplication by a unique $3 \times 3$ matrix, where the columns of the matrix are \\
$g(\mathbf{i}), g(\mathbf{j})$, and $g(\mathbf{k})$.
\end{tabular}

Problem 12.32:
(a) Show that if $\operatorname{det}(\mathbf{A}) \neq 0$, then there exists a function $f$ such that for every $\mathbf{c}$, we have $\mathbf{A}(f(\mathbf{c}))=\mathbf{c}$.
(b) Show that the function you found in part (a) is linear.

Solution for Problem 12.32:
(a) We showed on page 397 that if $\operatorname{det}(\mathbf{A}) \neq 0$, then the equation $\mathbf{A v}=\mathbf{c}$ has a unique solution $\mathbf{v}$ for each vector c. Since for each $\mathbf{c}$ there is a unique $\mathbf{v}$ such that $\mathbf{A v}=\mathbf{c}$, we can define a function $f(\mathbf{c})$ to return the vector $\mathbf{v}$ such that $\mathbf{A v}=\mathbf{c}$.
(b) We must show the following:
(i) $f(k c)=k f(c)$ for all scalars $k$ and vectors $\mathbf{c}$, and
(ii) $f(\mathbf{b}+\mathbf{c})=f(\mathbf{b})+f(\mathbf{c})$ for all vectors $\mathbf{b}$ and $\mathbf{c}$.

455

---

<!-- Page 456 -->

CHAPTER 12. VECTORS AND MATRICES IN THREE DIMENSIONS, PART 2

We tackle item (i) first. Let $f(\mathbf{c})=\mathbf{v}$, so $\mathbf{A v}=\mathbf{c}$. Multiplying both sides by $k$ gives $k \mathbf{A v}=k \mathbf{c}$. Since $k \mathbf{A} \mathbf{v}=\mathbf{A}(k \mathbf{v})$, we have $\mathbf{A}(k \mathbf{v})=k \mathbf{c}$. Therefore, we have $f(k \mathbf{c})=k \mathbf{v}=k f(\mathbf{c})$.

Turning to item (ii), let $f(\mathbf{b})=\mathbf{u}$, so $\mathbf{A u}=\mathbf{b}$. Adding $\mathbf{A v}=\mathbf{c}$ to this gives $\mathbf{A u}+\mathbf{A v}=\mathbf{b}+\mathbf{c}$, so $\mathbf{A}(\mathbf{u}+\mathbf{v})=\mathbf{b}+\mathbf{c}$. Therefore, we have $f(\mathbf{b}+\mathbf{c})=\mathbf{u}+\mathbf{v}=f(\mathbf{b})+f(\mathbf{c})$.

Since we have showed that $f$ satisfies conditions (i) and (ii) above, we conclude that $f$ is linear.

Problem 12.33:
(a) Show that if $\operatorname{det}(\mathbf{A}) \neq 0$, then there is a matrix $\mathbf{B}$ such that $\mathbf{B A}=\mathbf{I}$.
(b) Is the matrix $\mathbf{B}$ you found in part (a) unique?
(c) Do we also have $\mathbf{A B}=\mathbf{I}$ for the matrix $\mathbf{B}$ you found in part (a)?

Solution for Problem 12.33:
(a) We did all the heavy lifting in Problem 12.32. There, we showed that if $\operatorname{det}(\mathbf{A}) \neq 0$, then there is a linear function $f$ such that, for every $\mathbf{c}$, the vector $f(\mathbf{c})$ is the vector $\mathbf{v}$ such that $\mathbf{A v}=\mathbf{c}$. Because the function is linear, there exists a matrix $\mathbf{B}$ such that $f(\mathbf{c})=\mathbf{B} \mathbf{c}$. Therefore, if $\mathbf{A v}=\mathbf{c}$, then $\mathbf{B c}=\mathbf{v}$. Multiplying both sides of $\mathbf{A v}=\mathbf{c}$ on the left by $\mathbf{B}$, we have
$$\mathbf{B A v}=\mathbf{B c}=\mathbf{v}$$
for all $\mathbf{v}$. Therefore, we must have $\mathbf{B A}=\mathbf{I}$.
(b) The linear function we found in Problem 12.32 is unique for each $\mathbf{A}$, since it is determined by the unique solutions to $\mathbf{A v}=\mathbf{i}, \mathbf{A v}=\mathbf{j}$, and $\mathbf{A v}=\mathbf{k}$. In Problem 12.31, we showed that a linear function that maps vectors to vectors can be expressed uniquely as multiplication by a matrix. Therefore, the matrix $\mathbf{B}$ such that $\mathbf{B A}=\mathbf{I}$ is unique.
(c) As explained in part (b), we have $\mathbf{B} \mathbf{c}=\mathbf{v}$ if $\mathbf{A v}=\mathbf{c}$. Multiplying both sides of $\mathbf{B} \mathbf{c}=\mathbf{v}$ on the left by $\mathbf{A}$, we have
$$\mathbf{A B C}=\mathbf{A v}=\mathbf{c}$$
for any vector $\mathbf{c}$, so $\mathbf{A B}=\mathbf{I}$. In other words, if $\mathbf{B}$ is the inverse of $\mathbf{A}$, then $\mathbf{A}$ is the inverse of $\mathbf{B}$.

Important: If $\operatorname{det}(\mathbf{A}) \neq 0$, then there is a unique matrix $\mathbf{A}^{-1}$, called the inverse of $\mathbf{A}$, such
that $\mathbf{A}^{-1} \mathbf{A}=\mathbf{A A}^{-1}=\mathbf{I}$.

As with $2 \times 2$ matrices, we say that a matrix is invertible if it has an inverse. We found that a $2 \times 2$ matrix is not invertible if its determinant is 0 . Let's see if the same is true of a $3 \times 3$ matrix.

Problem 12.34: In this problem, we show that if $\operatorname{det}(\mathbf{A})=0$, then $\mathbf{A}$ does not have an inverse.
(a) Show that if $\operatorname{det}(\mathbf{A})=0$, then there is some vector $\mathbf{c}$ such that there is no solution $\mathbf{v}$ to $\mathbf{A v}=\mathbf{c}$.
(b) Use part (a) to show that $\mathbf{A}$ does not have an inverse if $\operatorname{det}(\mathbf{A})=0$.

Solution for Problem 12.34:
(a) Let the columns of $\mathbf{A}$ be $\mathbf{a}_{1}, \mathbf{a}_{2}$, and $\mathbf{a}_{3}$. Since $\operatorname{det}(\mathbf{A})=0$, the columns of $\mathbf{A}$ are linearly dependent. So, as explained in Problem 12.14, the graph of
$$\left(\begin{array}{l}
x \\
y \\
z
\end{array}\right)=v_{1} \mathbf{a}_{1}+v_{2} \mathbf{a}_{2}+v_{3} \mathbf{a}_{3},$$

456

---

<!-- Page 457 -->

12.6. SUMMARY

where $v_{1}, v_{2}, v_{3}$ are parameters, is not all of $\mathbb{R}^{3}$. In other words, there is some vector $\mathbf{c}$ such that there are no values of $v_{1}, v_{2}, v_{3}$ for which $\mathbf{c}=v_{1} \mathbf{a}_{1}+v_{2} \mathbf{a}_{2}+v_{3} \mathbf{a}_{3}$. Since
$$v_{1} \mathbf{a}_{1}+v_{2} \mathbf{a}_{2}+v_{3} \mathbf{a}_{3}=v_{1} \mathbf{A i}+v_{2} \mathbf{A j}+v_{3} \mathbf{A k}=\mathbf{A}\left(v_{1} \mathbf{i}+v_{2} \mathbf{j}+v_{3} \mathbf{k}\right),$$
there is no vector $\mathbf{v}$ for which $\mathbf{c = A v}$.
(b) If $\mathbf{A}^{-1}$ exists, then we can multiply both sides of $\mathbf{A v}=\mathbf{c}$ on the left to get $\mathbf{A}^{-1} \mathbf{A v}=\mathbf{A}^{-1} \mathbf{c}$, so $\mathbf{v}=\mathbf{A}^{-1} \mathbf{c}$. In other words, if $\mathbf{A}$ is invertible, then for any $\mathbf{c}$, the vector $\mathbf{v}=\mathbf{A}^{-1} \mathbf{c}$ is a solution to $\mathbf{A v}=\mathbf{c}$. But we showed in part (a) that if $\operatorname{det}(\mathbf{A})=0$, then there is some vector $\mathbf{c}$ such that there is no solution $\mathbf{v}$ to the equation $\mathbf{A v}=\mathbf{c}$. So, we conclude that $\mathbf{A}$ is not invertible if $\operatorname{det}(\mathbf{A})=0$.

Important: A $3 \times 3$ matrix has an inverse if and only if the determinant of the matrix is
□ nonzero.

As a reminder, we say that a $3 \times 3$ matrix is singular if its determinant is 0 and nonsingular if its determinant is nonzero. So, a $3 \times 3$ matrix has an inverse if and only if it is nonsingular.

Exercises
12.5.1 If $\mathbf{A}$ is nonsingular, then how are $\operatorname{det}(\mathbf{A})$ and $\operatorname{det}\left(\mathbf{A}^{-1}\right)$ related?
12.5.2 Find all $x$ such that $\left(\begin{array}{ccc}1 & 5 & 5 \\ -2 & 6 & x \\ x & -2 & 1\end{array}\right)$ does not have an inverse.
12.5.3 Must the sum of two singular matrices be singular?
12.5.4 A $3 \times 3$ matrix is an upper triangular matrix if all the entries below the main diagonal are 0 . That is, it is a matrix of the form
$$\left(\begin{array}{ccc}
a_{11} & a_{12} & a_{13} \\
0 & a_{22} & a_{23} \\
0 & 0 & a_{33}
\end{array}\right)$$
(a) Show that if all the entries on the main diagonal of an upper triangular matrix ( $a_{11}, a_{22}$, and $a_{33}$ above) are nonzero, then the matrix is invertible.
(b) Show that if an upper triangular matrix is invertible, then its inverse is also an upper triangular matrix.
12.6 Summary

The vectors $\mathbf{v}_{1}, \mathbf{v}_{2}, \ldots, \mathbf{v}_{n}$ are linearly dependent if there exist constants $a_{1}, a_{2}, \ldots, a_{n}$, not all 0 , such that we have $a_{1} \mathbf{v}_{1}+a_{2} \mathbf{v}_{2}+\cdots+a_{n} \mathbf{v}_{n}=\mathbf{0}$. Otherwise, we say the vectors are linearly independent.

The graph of $\left(\begin{array}{l}x \\ y \\ z\end{array}\right)=\left(\begin{array}{l}x_{0} \\ y_{0} \\ z_{0}\end{array}\right)+t \mathbf{v}$ is a line through $\left(x_{0}, y_{0}, z_{0}\right)$ with direction vector $\mathbf{v}$.

457

---

<!-- Page 458 -->

CHAPTER 12. VECTORS AND MATRICES IN THREE DIMENSIONS, PART 2

If $\mathbf{v}$ and $\mathbf{w}$ are linearly independent, then the graph of
$$\left(\begin{array}{l}
x \\
y \\
z
\end{array}\right)=\left(\begin{array}{l}
x_{0} \\
y_{0} \\
z_{0}
\end{array}\right)+s \mathbf{v}+t \mathbf{w}$$
is the plane through $\left(x_{0}, y_{0}, z_{0}\right)$ generated by $\mathbf{v}$ and $\mathbf{w}$. Any two linearly independent vectors in a plane can be used to generate the plane. A vector is normal to a plane if it is orthogonal to every vector in the plane. The graph of any equation of the form $a x+b y+c z=d$, where $a, b$, and $c$ are not all 0 , is a plane. Every plane is the graph of an equation of this form, and the vector $a \mathbf{i}+b \mathbf{j}+c \mathbf{k}$ is normal to the graph.

If $\mathbf{u}, \mathbf{v}$, and $\mathbf{w}$ are linearly independent, then the graph of $\left(\begin{array}{l}x \\ y \\ z\end{array}\right)=r \mathbf{u}+s \mathbf{v}+t \mathbf{w}$ is all of $\mathbb{R}^{3}$.
We define the cross product of two vectors as
$$\mathbf{v} \times \mathbf{w}=\left|\begin{array}{cc}
v_{2} & v_{3} \\
w_{2} & w_{3}
\end{array}\right| \mathbf{i}-\left|\begin{array}{cc}
v_{1} & v_{3} \\
w_{1} & w_{3}
\end{array}\right| \mathbf{j}+\left|\begin{array}{cc}
v_{1} & v_{2} \\
w_{1} & w_{2}
\end{array}\right| \mathbf{k}=\left|\begin{array}{ccc}
\mathbf{i} & \mathbf{j} & \mathbf{k} \\
v_{1} & v_{2} & v_{3} \\
w_{1} & w_{2} & w_{3}
\end{array}\right|$$

The cross product $\mathbf{v} \times \mathbf{w}$ is orthogonal to both $\mathbf{v}$ and $\mathbf{w}$, and has the following properties:
- $\mathbf{v} \times \mathbf{w}$ satisfies the "right-hand rule," which is illustrated at right
- $\mathbf{v} \times \mathbf{w}=-\mathbf{w} \times \mathbf{v}$
- $\mathbf{u} \times(c \mathbf{v})=(c \mathbf{u}) \times \mathbf{v}=c(\mathbf{u} \times \mathbf{v})$
- $\mathbf{u} \times(\mathbf{v}+\mathbf{w})=\mathbf{u} \times \mathbf{v}+\mathbf{u} \times \mathbf{w}$ and $(\mathbf{u}+\mathbf{v}) \times \mathbf{w}=\mathbf{u} \times \mathbf{w}+\mathbf{v} \times \mathbf{w}$
- $\|\mathbf{u} \times \mathbf{v}\|=\|\mathbf{u}\|\|\mathbf{v}\| \sin \theta$
- $\mathbf{r} \times \mathbf{s}=0$ if and only if $\mathbf{r}$ and s are linearly dependent

The signed volume of the parallelepiped with $\mathbf{u}, \mathbf{v}$, and $\mathbf{w}$ as edges is $\mathbf{u} \cdot(\mathbf{v} \times \mathbf{w})$, where $\mathbf{u} \cdot(\mathbf{v} \times \mathbf{w})$ is called a box product or scalar triple product. We can compute such a product with a determinant:
$$\mathbf{u} \cdot(\mathbf{v} \times \mathbf{w})=\left|\begin{array}{ccc}
u_{1} & u_{2} & u_{3} \\
v_{1} & v_{2} & v_{3} \\
w_{1} & w_{2} & w_{3}
\end{array}\right|$$

The determinant of a $3 \times 3$ matrix also has the following properties:
- If $\mathbf{A}$ and $\mathbf{B}$ are $3 \times 3$ matrices, then $\operatorname{det}(\mathbf{A B})=\operatorname{det}(\mathbf{A}) \operatorname{det}(\mathbf{B})$.
- The determinant of a $3 \times 3$ matrix is 0 if and only if its rows are linearly dependent.
- The determinant of a $3 \times 3$ matrix is 0 if and only if its columns are linearly dependent.

If $\operatorname{det}(\mathbf{A}) \neq 0$, then there is a unique matrix $\mathbf{A}^{-1}$, called the inverse of $\mathbf{A}$, such that $\mathbf{A}^{-1} \mathbf{A}=\mathbf{A A}^{-1}=\mathbf{I}$. If $\operatorname{det}(\mathbf{A})=0$, then $\mathbf{A}$ does not have an inverse.

458

---

<!-- Page 459 -->

REVIEW PROBLEMS

REVIEW PROBLEMS
12.35 Let $\mathbf{v}=\left(\begin{array}{c}1 \\ 2 \\ -5\end{array}\right), \mathbf{w}=\left(\begin{array}{c}-3 \\ 4 \\ -2\end{array}\right)$, and $\mathbf{p}=\left(\begin{array}{l}x \\ y \\ z\end{array}\right)$.
(a) What is the shape of the graph of all points $(x, y, z)$ such that $\mathbf{p} \cdot \mathbf{v}=4$ ?
(b) What is the shape of the graph of all points $(x, y, z)$ such that $\mathbf{p} \cdot \mathbf{v}=\mathbf{p} \cdot \mathbf{w}$ ?
(c) What is the shape of the graph of all points $(x, y, z)$ such that $\mathbf{p} \cdot \mathbf{v}=4$ and $\mathbf{p} \cdot \mathbf{w}=4$ ?
12.36 Find $a$ and $b$ such that $(a, 2, b)$ is on the line through $(2,4,2)$ and $(1,6,-1)$.
12.37 Find $a$ and $b$ if the graphs of $3 x-2 y+8 z=5$ and $a x+b y-4 z=7$ are parallel planes.
12.38 Let $\ell$ be the line through $(5,4,1)$ and $(11,1,-8)$ and $m$ be the line through $(5,-1,2)$ and $(0,14,7)$.
(a) Show that $\ell$ and $m$ intersect, and find the point at which they intersect.
(b) Find an equation whose graph is a plane that contains both $\ell$ and $m$.
12.39 Let $\left(x_{1}, y_{1}, z_{1}\right),\left(x_{2}, y_{2}, z_{2}\right)$, and $\left(x_{3}, y_{3}, z_{3}\right)$ be three noncollinear points. Show that the graph of
$$\left|\begin{array}{ccc}
x-x_{1} & y-y_{1} & z-z_{1} \\
x_{2}-x_{1} & y_{2}-y_{1} & z_{2}-z_{1} \\
x_{3}-x_{1} & y_{3}-y_{1} & z_{3}-z_{1}
\end{array}\right|=0$$
is the plane through these three points.
12.40 Let $\mathbf{v}=\left(\begin{array}{c}4 \\ -1 \\ 2\end{array}\right)$ and $\mathbf{w}=\left(\begin{array}{c}-1 \\ 2 \\ 3\end{array}\right)$.
(a) Is $\mathbf{p}=\left(\begin{array}{c}9 \\ -4 \\ 1\end{array}\right)$ a linear combination of $\mathbf{v}$ and $\mathbf{w}$ ? If so, find all possible ordered pairs of scalars $(a, b)$ such that $\mathbf{p}=a \mathbf{v}+b \mathbf{w}$.
(b) Suppose $\mathbf{r}$ is a linear combination of $\mathbf{v}$ and $\mathbf{w}$. Show that there is only one ordered pair of scalars $(a, b)$ such that $\mathbf{r}=a \mathbf{v}+b \mathbf{w}$.
12.41
(a) If $\mathbf{u} \cdot \mathbf{w}=\mathbf{v} \cdot \mathbf{w}$ for all vectors $\mathbf{w}$, then must $\mathbf{u}=\mathbf{v}$ ?
(b) If $\mathbf{u} \times \mathbf{w}=\mathbf{v} \times \mathbf{w}$ for all vectors $\mathbf{w}$, then must $\mathbf{u}=\mathbf{v}$ ?
12.42 Find $(3 \mathbf{i}+2 \mathbf{j}-\mathbf{k}) \times(-3 \mathbf{i}+4 \mathbf{j}+2 \mathbf{k})$.
12.43 If $\mathbf{i} \times \mathbf{v}=\mathbf{k}$, then must $\mathbf{v}=\mathbf{j}$ ?
12.44 Find an equation of the form $a x+b y+c z=d$ whose graph is the plane through the origin generated by $\left(\begin{array}{c}4 \\ -1 \\ 2\end{array}\right)$ and $\left(\begin{array}{c}-1 \\ 0 \\ 4\end{array}\right)$.

459

---

<!-- Page 460 -->

CHAPTER 12. VECTORS AND MATRICES IN THREE DIMENSIONS, PART 2
12.45 Find an equation whose graph is the plane that contains both $(-2,3,5)$ and the graph of the parametric equations $x=3-2 t, y=4+t, z=-5 t$.
12.46 If $\mathbf{a} \times \mathbf{b}=\mathbf{c}$ and $\mathbf{b} \times \mathbf{c}=\mathbf{a}$, then must $\mathbf{c} \times \mathbf{a}=\mathbf{b}$ ?
12.47
(a) Let $\mathbf{v}=4 \mathbf{i}-\mathbf{j}+2 \mathbf{k}$. Find a matrix $\mathbf{M}$ such that for any vector $\mathbf{w}$, we have $\mathbf{M w}=\mathbf{v} \times \mathbf{w}$.
(b) Show that for any nonzero vector $\mathbf{u}$, there is a matrix $\mathbf{N}$ such that $\mathbf{N} \mathbf{w}=\mathbf{u} \times \mathbf{w}$ for any vector $\mathbf{w}$.
12.48 Show that if $\mathbf{u} \cdot \mathbf{v}=0$ and $\mathbf{u} \times \mathbf{v}=\mathbf{0}$, then either $\mathbf{u}=\mathbf{0}$ or $\mathbf{v}=\mathbf{0}$.
12.49 Use the geometric interpretation of the determinant to explain why
$$\left|\begin{array}{ccc}
u_{1} & u_{2} & u_{3} \\
v_{1} & v_{2} & v_{3} \\
w_{1} & w_{2} & w_{3}
\end{array}\right|=\left|\begin{array}{ccc}
u_{1}+v_{1} & u_{2}+v_{2} & u_{3}+v_{3} \\
v_{1} & v_{2} & v_{3} \\
w_{1} & w_{2} & w_{3}
\end{array}\right| .$$
12.50 Find the inverse of each of the following:
(a) $\left(\begin{array}{lll}0 & 1 & 0 \\ 1 & 0 & 0 \\ 0 & 0 & 1\end{array}\right)$
(b) $\left(\begin{array}{lll}0 & 0 & 1 \\ 1 & 0 & 0 \\ 0 & 1 & 0\end{array}\right)$
(c) $\quad\left(\begin{array}{ccc}0 & 0 & -1 \\ 1 & 0 & 0 \\ 0 & 1 & 0\end{array}\right)$
12.51 Suppose that $\mathbf{A}$ and $\mathbf{B}$ both have inverses. Find the inverse of $\mathbf{A B}$ in terms of $\mathbf{A}^{-1}$ and $\mathbf{B}^{-1}$.
12.52 If $\mathbf{P}$ is the product of an invertible matrix and a non-invertible matrix, then does $\mathbf{P}$ have an inverse?
12.53 Suppose $\mathbf{A}$ is nonsingular. Then, do we have $\left(\mathbf{A}^{T}\right)^{-1}=\left(\mathbf{A}^{-1}\right)^{T}$ ?

Challenge Problems
12.54 We can project a vector on a plane just as we can project it onto a line. Suppose we draw the vector $\mathbf{v}$ from a point $O$ in the plane, where $\mathbf{v}$ is not in the plane. If we let $V$ be the head of $\mathbf{v}$, and let $F$ be a point in the plane such that $\overrightarrow{F V}$ is normal to the plane, then the vector $\overrightarrow{O F}$ is the projection of the vector onto the plane.
(a) Find a matrix $\mathbf{M}$ such that $\mathbf{M v}$ is the projection of $\mathbf{v}$ onto the $x y$-plane (the graph of $z=0$ ) for all vectors $\mathbf{v}$.
(b) $\star$ Find a matrix $\mathbf{N}$ such that $\mathbf{N v}$ is the projection of $\mathbf{v}$ onto the graph of $x+y+z=0$. Hints: 231,6
12.55 Let $\mathbf{v}=3 \mathbf{i}-2 \mathbf{j}+\mathbf{k}$. Find nonzero vectors $\mathbf{w}$ and $\mathbf{u}$ such that each of $\mathbf{v}, \mathbf{w}$, and $\mathbf{u}$ is orthogonal to the other two.
12.56 Let $A_{i j}$ be the minor of row $i$ and column $j$ of matrix $\mathbf{A}$, as described on page 404. Show that if $\mathbf{A}$ is invertible, then
$$\mathbf{A}^{-1}=\frac{1}{\operatorname{det}(\mathbf{A})}\left(\begin{array}{ccc}
A_{11} & -A_{21} & A_{31} \\
-A_{11} & A_{22} & -A_{32} \\
A_{13} & -A_{23} & A_{33}
\end{array}\right) .$$
12.57 Show that if a nonzero vector $\mathbf{v}$ makes an angle of $\alpha$ with $\mathbf{i}$, an angle of $\beta$ with $\mathbf{j}$, and an angle of $\gamma$ with $\mathbf{k}$, then we must have $\cos ^{2} \alpha+\cos ^{2} \beta+\cos ^{2} \gamma=1$. Hints: 273

460

---

<!-- Page 461 -->

CHALLENGE PROBLEMS
12.58 Show that if $\mathbf{u}$ and $\mathbf{v}$ are not parallel, then the vector $\|\mathbf{v}\| \mathbf{u}+\|\mathbf{u}\| \mathbf{v}$ bisects the angle between $\mathbf{u}$ and $\mathbf{v}$. Hints: 163
12.59 In the text, we developed an expression for the cross product by searching for a vector that is normal to two given vectors. In this problem, we find another way to develop the expression for the cross product of two vectors. So, for this problem, set aside what you already know about the cross product. Suppose we define the cross product such that we have the following:
(i) $\mathbf{i} \times \mathbf{j}=\mathbf{k}, \mathbf{j} \times \mathbf{k}=\mathbf{i}$, and $\mathbf{k} \times \mathbf{i}=\mathbf{j}$
(ii) $\mathbf{a} \times \mathbf{b}=-\mathbf{b} \times \mathbf{a}$ for any $\mathbf{a}$ and $\mathbf{b}$
(iii) $\mathbf{a} \times(k \mathbf{b})=k(\mathbf{a} \times \mathbf{b})$ for any $k, \mathbf{a}$, and $\mathbf{b}$
(iv) $\mathbf{a} \times(\mathbf{b}+\mathbf{c})=\mathbf{a} \times \mathbf{b}+\mathbf{a} \times \mathbf{c}$ for any $\mathbf{a}, \mathbf{b}$, and $\mathbf{c}$

What we have done here is defined the cross product to have some basic algebraic properties that we'd like the cross product to have. In the problems below, you will prove that starting from the properties above, we can derive some of the other properties of the cross product given in the text, as well as the expression for $\mathbf{v} \times \mathbf{w}$ in terms of the components of $\mathbf{v}$ and $\mathbf{w}$.
(a) Show that $\mathbf{v} \times \mathbf{v}=0$ for any vector $\mathbf{v}$.
(b) Show that if $\mathbf{v}=v_{1} \mathbf{i}+v_{2} \mathbf{j}+v_{3} \mathbf{k}$ and $\mathbf{w}=w_{1} \mathbf{i}+w_{2} \mathbf{j}+w_{3} \mathbf{k}$, then $\mathbf{v} \times \mathbf{w}=\left|\begin{array}{ll}v_{2} & v_{3} \\ w_{2} & w_{3}\end{array}\right| \mathbf{i}-\left|\begin{array}{ll}v_{1} & v_{3} \\ w_{1} & w_{3}\end{array}\right| \mathbf{j}+\left|\begin{array}{ll}v_{1} & v_{2} \\ w_{1} & w_{2}\end{array}\right| \mathbf{k}$.
(c) Show that $\mathbf{v} \times \mathbf{w}$ is orthogonal to $\mathbf{v}$ and $\mathbf{w}$.
12.60 Show that $(\mathbf{a} \times \mathbf{b}) \times(\mathbf{a} \times \mathbf{c})=(\mathbf{a} \cdot(\mathbf{b} \times \mathbf{c})) \mathbf{a}$. Hints: 19
12.61 Show that $(\mathbf{a} \times \mathbf{b}) \cdot(\mathbf{c} \times \mathbf{d})=(\mathbf{a} \cdot \mathbf{c})(\mathbf{b} \cdot \mathbf{d})-(\mathbf{a} \cdot \mathbf{d})(\mathbf{b} \cdot \mathbf{c})$. Hints: 36
12.62 Show that if $\mathbf{a}, \mathbf{b}, \mathbf{c}$ are linearly independent, and each two of them are orthogonal, then for any vector $\mathbf{v}$, we have
$$\mathbf{v}=\frac{\mathbf{v} \cdot \mathbf{a}}{\|\mathbf{a}\|^{2}} \mathbf{a}+\frac{\mathbf{v} \cdot \mathbf{b}}{\|\mathbf{b}\|^{2}} \mathbf{b}+\frac{\mathbf{v} \cdot \mathbf{c}}{\|\mathbf{c}\|^{2}} \mathbf{c}$$
12.63 Does there exist a $3 \times 2$ matrix $\mathbf{M}$ such that for every vector $\mathbf{v}$ in 3 dimensions, there is a vector $\mathbf{u}$ in 2 dimensions such that $\mathbf{M u = v} \boldsymbol{v}$ ? Hints: $181,135,41$
12.64 Find the shortest distance from $(0,1,2)$ to a point on the line through $(4,1,-3)$ and $(-2,5,1)$. Hints: 59
12.65 Let $A, B, C$, and $D$ be points in space such that the volume of parallelepiped with edges $\overline{A B}, \overline{A C}$, and $\overline{A D}$ is 80 . Hints: 242, 199
(a) If $\overline{A B}$ and $\overline{A C}$ are edges of parallelepiped $\mathcal{P}$ and $\overline{A D}$ is an interior diagonal of $\mathcal{P}$, then what is the volume of $\mathcal{P}$ ?
(b) If $\overline{A B}, \overline{A C}$, and $\overline{A D}$ are face diagonals of $Q$, then what is the volume of $Q$ ?
12.66
(a) Prove that for any vector $\mathbf{v}$, there exists a matrix $\mathbf{M}$ such that $\mathbf{M w}$ for any $\mathbf{w}$ equals the projection of $\mathbf{w}$ onto v. Hints: 210
(b) Suppose $\mathbf{w}$ is a nonzero vector and $\mathbf{M}$ is the matrix such that $\mathbf{M w}=\operatorname{proj}_{\mathbf{v}} \mathbf{w}$ for all $\mathbf{w}$. Find $\operatorname{det}(\mathbf{M})$. Hints: 138
(c) Let $\mathbf{v}=3 \mathbf{i}-2 \mathbf{j}+5 \mathbf{k}$. Find a matrix $\mathbf{M}$ such that $\mathbf{M w}$ equals the projection of $\mathbf{w}$ onto $\mathbf{v}$ for any vector $\mathbf{w}$.
(d) What is $\mathbf{M}^{2}$, where $\mathbf{M}$ is your answer to part (a)?

461

---

<!-- Page 462 -->

CHAPTER 12. VECTORS AND MATRICES IN THREE DIMENSIONS, PART 2
12.67★ The distance between two lines in space is the length of the shortest segment that has an endpoint on each line. Let $\mathbf{v}_{1}$ and $\mathbf{v}_{2}$ be direction vectors of two non-parallel lines in space, $k_{1}$ and $k_{2}$. Show that for any points $A_{1}$ on $k_{1}$ and $A_{2}$ on $k_{2}$, the distance between $k_{1}$ and $k_{2}$ equals
$$\frac{\left|A_{1} A_{2} \cdot\left(\mathbf{v}_{1} \times \mathbf{v}_{2}\right)\right|}{\left\|\mathbf{v}_{1} \times \mathbf{v}_{2}\right\|}$$

Hints: 149, 81, 105

462

---

