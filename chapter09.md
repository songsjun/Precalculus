# Chapter 9: Vectors in Two Dimensions

<!-- Page 298 -->

CHAPTER 9. VECTORS IN TWO DIMENSIONS

A plan is just a tangent vector on the manifold of reality. - Skratch Garrison
9
Vectors in Two Dimensions
9.1 What's a Vector?

A vector in two dimensions is an ordered pair of numbers, which we often denote as $\binom{x}{y}$. The numbers $x$ and $y$ are called components of the vector. Vectors have the following operations:
- Vector addition. We add vectors by adding the corresponding components:
$$\binom{a}{b}+\binom{c}{d}=\binom{a+c}{b+d} .$$
- Multiplication of a vector by a constant. We multiply a vector by a constant by multiplying each component of the vector by the constant:
$$k\binom{a}{b}=\binom{k a}{k b}$$

We often refer to real numbers as scalars when speaking of vectors. So, the product $k\binom{a}{b}$ is commonly referred to as scalar multiplication. In Problem 9.4, we'll see why real numbers earn this name when speaking of vectors.

Instead of referring to a vector by its components, we can give a vector a label. When we do so, we usually use a bold lowercase letter that is not italicized, like $\mathbf{v}$. Other notations that are sometimes used to denote a vector are $\vec{v}$ or $\hat{v}$.

298

---

<!-- Page 299 -->

9.1. WHAT'S A VECTOR?

A vector can be represented geometrically as an arrow. The arrow from $(0,0)$ to $(1,3)$ in the diagram at right represents the vector $\binom{1}{3}$. The diagram also shows an arrow from $(2,-4)$ to $(3,-1)$. These arrows represent the same vector. The location of a vector is irrelevant. So, any arrow that depicts "right 1 unit, up 3 units" represents the vector $\binom{1}{3}$.

We will occasionally refer to vectors with points, writing $\overrightarrow{B C}$ for the vector that is represented by the arrow from $B$ to $C$. If we write a vector with one point, such as $\vec{A}$, we mean the vector from the origin to that point. (Note that the notation $\overrightarrow{B C}$ is slightly different than the notation $\overrightarrow{B C} . \overrightarrow{B C}$ denotes the ray that starts at $B$, passes through $C$, and keeps going forever in that direction. The vector $\overrightarrow{B C}$ is represented by an arrow that goes from $B$ to $C$ and stops there.)

We won't always be this precise in our language when referring to vectors in a geometric context. We will often simply refer to "an arrow that represents a vector" as simply "a vector," rather than littering the text with "an arrow that represents." So, letting $\mathbf{v}=\binom{1}{3}$, we see that both $\vec{A}$ and $\overrightarrow{B C}$ in the diagram above are $\mathbf{v}$, and we can write $\vec{A}=\overrightarrow{B C}=\mathbf{v}$.

A vector with magnitude 1 is called a unit vector. The vector $\binom{x}{y}$ can also be written as $x \mathbf{i}+y \mathbf{j}$, where $\mathbf{i}$ is the unit vector $\binom{1}{0}$ and j is the unit vector $\binom{0}{1}$. For example, the vectors $\vec{A}$ and $\overrightarrow{B C}$ shown at right above are both $\mathbf{i}+3 \mathbf{j}$. We will mostly use the notation $\binom{1}{3}$, but will occasionally mix in $\mathbf{i}+3 \mathbf{j}$ notation so you'll be comfortable with it.

The zero vector is the vector in which both components are zero. We often denote this vector as simply $\mathbf{0}$. We also have a special symbol for the set of all vectors in two dimensions: $\mathbb{R}^{2}$. To see why we use this symbol, recall that $\mathbb{R}$ is the set of all real numbers. So, we use the symbol $\mathbb{R}^{2}$ to indicate the set of all ordered pairs of real numbers.

Problems

Problem 9.1: We define the norm of a vector $\binom{x}{y}$ to be the distance from $(x, y)$ to the origin in the Cartesian plane. We denote the norm of a vector $\mathbf{v}$ as $\|\mathbf{v}\|$. Find $\left\|\binom{x}{y}\right\|$ in terms of $x$ and $y$.

Problem 9.2:
(a) If $\mathbf{v}=3 \mathbf{i}-4 \mathbf{j}$, then what is $\left\|\frac{\mathbf{v}}{\|\mathbf{v}\|}\right\|$ ?
(b) If $\mathbf{v}=\binom{7}{-7}$, then what is $\left\|\frac{\mathbf{v}}{\|\mathbf{v}\|}\right\|$ ?
(c) If $\mathbf{v}=\binom{0.5}{-0.2}$, then what is $\left\|\frac{\mathbf{v}}{\|\mathbf{v}\|}\right\|$ ?
(d) Generalize your results from the first three parts. That is, what can we say about $\left\|\frac{\mathbf{v}}{\|\mathbf{v}\|}\right\|$ when $\mathbf{v}$ is a nonzero vector?

299

---

<!-- Page 300 -->

CHAPTER 9. VECTORS IN TWO DIMENSIONS

Problem 9.3: Let $x \mathbf{i}+y \mathbf{j}$ be a nonzero vector, and let $(r, \theta)$, where $r>0$, be the polar coordinates of the point with rectangular coordinates $(x, y)$. How are $r$ and $\theta$ related to the vector $x \mathbf{i}+y \mathbf{j}$ ?

Problem 9.4: Let $\mathbf{v}$ be a nonzero vector.
(a) Geometrically speaking, how are $\mathbf{v}$ and $3 \mathbf{v}$ related?
(b) Let $-\mathbf{v}=(-1) \mathbf{v}$ for any $\mathbf{v}$. Geometrically speaking, how are $\mathbf{v}$ and $-\mathbf{v}$ related?

Problem 9.5: In this problem, we explore vector addition. Let $\mathbf{v}=\binom{5}{1}$ and $\mathbf{w}=\binom{2}{4}$.
(a) Find $x$ and $y$ such that $\mathbf{v}+\mathbf{w}=\binom{x}{y}$.
(b) Let $O$ be the origin, let $A$ be the point (5,1), let $B$ be the point (2,4), and let $C$ be the point ( $x, y$ ), where $x$ and $y$ are your answers from part (a). What are $\overrightarrow{O A}, \overrightarrow{O B}, \overrightarrow{O C}$, and $\overrightarrow{A C}$ in terms of $\mathbf{v}$ and $\mathbf{w}$ ? What type of quadrilateral is $O A C B$ ?
(c) Use your answers to part (b) to give a geometric description of adding two vectors.

Problem 9.6: In this problem, we explore vector subtraction. Let $\mathbf{v}=\binom{5}{1}$ and $\mathbf{w}=\binom{2}{4}$.
(a) We define vector subtraction to fit with our definition of vector addition. The vector $\mathbf{w}-\mathbf{v}$ is the vector $\mathbf{u}$ such that $\mathbf{u}+\mathbf{v}=\mathbf{w}$. Use the definition of vector addition to find $x$ and $y$ such that $\mathbf{w}-\mathbf{v}=\binom{x}{y}$.
(b) Let $O$ be the origin, let $A$ be the point (5,1), let $B$ be the point (2,4), and let $C$ be the point ( $x, y$ ), where $x$ and $y$ are your answers from part (a). What are $\overrightarrow{O A}, \overrightarrow{O B}, \overrightarrow{O C}$, and $\overrightarrow{A B}$ in terms of $\mathbf{v}$ and $\mathbf{w}$ ?
(c) Show that for any points $P$ and $Q$ in the Cartesian plane, we have $\overrightarrow{P Q}=\vec{Q}-\vec{P}$.
(d) How are $\overrightarrow{P Q}$ and $\overrightarrow{Q P}$ related?

Problem 9.1: We define the norm of a vector $\binom{x}{y}$ to be the distance from $(x, y)$ to the origin in the Cartesian plane. We denote the norm of a vector $\mathbf{v}$ as $\|\mathbf{v}\|$. Find $\left\|\binom{x}{y}\right\|$ in terms of $x$ and $y$.

Solution for Problem 9.1: Applying the distance formula gives us
$$\left\|\binom{x}{y}\right\|=\sqrt{(x-0)^{2}+(y-0)^{2}}=\sqrt{x^{2}+y^{2}}$$

Important: The norm of a vector $\mathbf{v}=\binom{x}{y}$ is
$$\|v\|=\sqrt{x^{2}+y^{2}} .$$

The norm of a vector is also called the magnitude or length of the vector, since it measures the length of the geometric representation of the vector.

300

---

<!-- Page 301 -->

9.1. WHAT'S A VECTOR?

Problem 9.2:
(a) If $\mathbf{v}=3 \mathbf{i}-4 \mathbf{j}$, then what is $\left\|\frac{\mathbf{v}}{\|\mathbf{v}\|}\right\|$ ?
(b) If $\mathbf{v}=\binom{7}{-7}$, then what is $\left\|\frac{\mathbf{v}}{\|\mathbf{v}\|}\right\|$ ?
(c) If $\mathbf{v}=\binom{0.5}{-0.2}$, then what is $\left\|\frac{\mathbf{v}}{\|\mathbf{v}\|}\right\|$ ?
(d) Generalize your results from the first three parts. That is, what can we say about $\left\|\frac{\mathbf{v}}{\|\mathbf{v}\|}\right\|$ when $\mathbf{v}$ is a nonzero vector?

Solution for Problem 9.2:
(a) We have $\|\mathbf{v}\|=\sqrt{3^{2}+(-4)^{2}}=5$, so $\frac{\mathbf{v}}{\|\mathbf{v}\|}=\frac{1}{5} \mathbf{v}=\frac{3}{5} \mathbf{i}-\frac{4}{5} \mathbf{j}$. Therefore, we have
$$\left\|\frac{\mathbf{v}}{\|\mathbf{v}\|}\right\|=\sqrt{\left(\frac{3}{5}\right)^{2}+\left(-\frac{4}{5}\right)^{2}}=1$$
(b) We have $\|\mathbf{v}\|=\sqrt{7^{2}+(-7)^{2}}=7 \sqrt{2}$, so $\frac{\mathbf{v}}{\|\mathbf{v}\|}=\binom{1 / \sqrt{2}}{-1 / \sqrt{2}}$ and
$$\left\|\frac{\mathbf{v}}{\|\mathbf{v}\|}\right\|=\sqrt{\frac{1}{2}+\frac{1}{2}}=1 .$$

Very suspicious.
(c) We have $\|\mathbf{v}\|=\sqrt{(0.5)^{2}+(-0.2)^{2}}=\sqrt{0.29}$, so $\frac{\mathbf{v}}{\|\mathbf{v}\|}=\binom{0.5 / \sqrt{0.29}}{-0.2 / \sqrt{0.29}}$. Rather than rationalizing the denominator or getting rid of the decimals, we forge ahead finding $\left\|\frac{\mathbf{v}}{\|\mathbf{v}\|}\right\|$, because we're pretty confident something convenient will happen:
$$\left\|\frac{\mathbf{v}}{\|\mathbf{v}\|}\right\|=\sqrt{\left(\frac{0.5}{\sqrt{0.29}}\right)^{2}+\left(-\frac{0.2}{\sqrt{0.29}}\right)^{2}}=\sqrt{\frac{0.25+0.04}{0.29}}=1 .$$

Very convenient, indeed.
(d) We have a pretty good idea what the result will be. We let $\mathbf{v}=\binom{x}{y}$ and work through the details. We have $\|\mathbf{v}\|=\sqrt{x^{2}+y^{2}}$, which is nonzero because $\mathbf{v} \neq 0$, so
$$\left\|\frac{\mathbf{v}}{\|\mathbf{v}\|}\right\|=\sqrt{\left(\frac{x}{\sqrt{x^{2}+y^{2}}}\right)^{2}+\left(\frac{y}{\sqrt{x^{2}+y^{2}}}\right)^{2}}=\sqrt{\frac{x^{2}+y^{2}}{x^{2}+y^{2}}}=1 .$$

As noted in the introduction, a vector with magnitude 1 is called a unit vector. In Problem 9.2, we showed that the result of dividing a nonzero vector by its magnitude is a unit vector. Since $\frac{\mathbf{v}}{\|\mathbf{v}\|}$ is a unit vector, when we write $\mathbf{v}$ as
$$\mathbf{v}=\|\mathbf{v}\| \cdot \frac{\mathbf{v}}{\|\mathbf{v}\|^{\prime}}$$

301

---

<!-- Page 302 -->

CHAPTER 9. VECTORS IN TWO DIMENSIONS

we express $\mathbf{v}$ as the product of its magnitude and a unit vector. For example, we have $\|3 \mathbf{i}-4 \mathbf{j}\|=\sqrt{3^{2}+(-4)^{2}}=5$, so we can express $3 \mathbf{i}-4 \mathbf{j}$ as the product of its magnitude and direction vector as follows:
$$3 \mathbf{i}-4 \mathbf{j}=5\left(\frac{3}{5} \mathbf{i}-\frac{4}{5} \mathbf{j}\right)$$

Geometrically speaking, we can think of this unit vector as providing the direction of the vector, and the magnitude as telling us how far the vector goes in that direction. Since each nonzero vector can be written as the product of its magnitude and a unit vector, we can think of a nonzero vector as being defined by its magnitude and its direction (as given by the unit vector).

We can also define the direction of a vector by using an angle, as we'll see in the next problem.
Problem 9.3: Let $x \mathbf{i}+y \mathbf{j}$ be a nonzero vector, and let $(r, \theta)$, where $r>0$, be the polar coordinates of the point with rectangular coordinates $(x, y)$. How are $r$ and $\theta$ related to the vector $x \mathbf{i}+y \mathbf{j}$ ?

Solution for Problem 9.3: Since $x=r \cos \theta$ and $y=r \sin \theta$, we have
$$x \mathbf{i}+y \mathbf{j}=(r \cos \theta) \mathbf{i}+(r \sin \theta) \mathbf{j}=r((\cos \theta) \mathbf{i}+(\sin \theta) \mathbf{j}) .$$

We have
$$r=\sqrt{x^{2}+y^{2}}=\|x \mathbf{i}+y \mathbf{j}\|,$$
so $r$ is the magnitude of $x \mathbf{i}+y \mathbf{j}$. Since
$$\|(\cos \theta) \mathbf{i}+(\sin \theta) \mathbf{j}\|=\sqrt{(\cos \theta)^{2}+(\sin \theta)^{2}}=1,$$
we see that $(\cos \theta) \mathbf{i}+(\sin \theta) \mathbf{j}$ is a unit vector, so $\theta$ can be used to describe the direction of the vector.

Problem 9.4: Let $\mathbf{v}$ be a nonzero vector.
(a) Geometrically speaking, how are $\mathbf{v}$ and $3 \mathbf{v}$ related?
(b) Let $\mathbf{-} \mathbf{v}=(-1) \mathbf{v}$ for any $\mathbf{v}$. Geometrically speaking, how are $\mathbf{v}$ and $-\mathbf{v}$ related?

Solution for Problem 9.4:
(a) If we let $\mathbf{v}=\binom{a}{b}$, we have $3 \mathbf{v}=\binom{3 a}{3 b}$. The origin, the point $(a, b)$, and the point $(3 a, 3 b)$ are collinear, since all lie on the line through the origin with slope $\frac{b}{a}$ (when $a$ is nonzero; if $a=0$, then all three points are on the $y$-axis). Therefore, it appears that $\mathbf{v}$ and $3 \mathbf{v}$ have the same direction. To be more precise, we can express each as the product of its magnitude and direction. We have $\|\mathbf{v}\|=\sqrt{a^{2}+b^{2}}$ and $\|3 \mathbf{v}\|=\sqrt{(3 a)^{2}+(3 b)^{2}}=3 \sqrt{a^{2}+b^{2}}$, so
$$\begin{aligned}
\mathbf{v} & =\sqrt{a^{2}+b^{2}}\left(\frac{a}{\sqrt{a^{2}+b^{2}}} \mathbf{i}+\frac{b}{\sqrt{a^{2}+b^{2}}} \mathbf{j}\right) \\
3 \mathbf{v} & =3 \sqrt{a^{2}+b^{2}}\left(\frac{3 a}{3 \sqrt{a^{2}+b^{2}}} \mathbf{i}+\frac{3 b}{3 \sqrt{a^{2}+b^{2}}} \mathbf{j}\right) \\
& =3 \sqrt{a^{2}+b^{2}}\left(\frac{a}{\sqrt{a^{2}+b^{2}}} \mathbf{i}+\frac{b}{\sqrt{a^{2}+b^{2}}} \mathbf{j}\right)
\end{aligned}$$

We see that the vector 3 v has same direction as $\mathbf{v}$, but has three times the magnitude. That is, $3 \mathbf{v}$ is a "scaled" version of $\mathbf{v}$.

302

---

<!-- Page 303 -->

9.1. WHAT'S A VECTOR?
(b) If $\mathbf{v}=\binom{a}{b}$, then $-\mathbf{v}=\binom{-a}{-b}$. These two vectors are indicated in the diagram at right. The point $(a, b)$ and the point $(-a,-b)$ are on the line through the origin with slope $\frac{b}{a}$ (when $a \neq 0$; if $a=0$, then all three points on the $y$-axis with the origin in the middle). However, the origin is between $(a, b)$ and $(-a,-b)$, so the vector from the origin to $(a, b)$ is in the opposite direction as the vector from the origin to $(-a,-b)$. Since the origin is equidistant from $(a, b)$ and $(-a,-b)$, we see that $\mathbf{v}$ and $-\mathbf{v}$ have the same magnitude, but opposite direction.

Problem 9.5: In this problem, we explore vector addition. Let $\mathbf{v}=\binom{5}{1}$ and $\mathbf{w}=\binom{2}{4}$.
(a) Find $x$ and $y$ such that $\mathbf{v}+\mathbf{w}=\binom{x}{y}$.
(b) Let $O$ be the origin, let $A$ be the point $(5,1)$, let $B$ be the point $(2,4)$, and let $C$ be the point $(x, y)$, where $x$ and $y$ are your answers from part (a). What are $\overrightarrow{O A}, \overrightarrow{O B}, \overrightarrow{O C}$, and $\overrightarrow{A C}$ in terms of $\mathbf{v}$ and $\mathbf{w}$ ? What type of quadrilateral is $O A C B$ ?
(c) Use your answers to part (b) to give a geometric description for adding two vectors.

Solution for Problem 9.5:
(a) Following the rule for vector addition, we have $\binom{5}{1}+\binom{2}{4}=\binom{5+2}{1+4}=\binom{7}{5}$.
(b) Since the arrow from $O$ to $A$ indicates going to the right 5 and up 1, we have $\overrightarrow{O A}=\binom{5}{1}=\mathbf{v}$. Similarly, we have $\overrightarrow{O B}=\binom{2}{4}=\mathbf{w}$, and $\overrightarrow{O C}=\binom{7}{5}=\mathbf{v}+\mathbf{w}$. To get from $A$ to $C$, we go right 2 and up 4, so $\overrightarrow{A C}=\binom{2}{4}$. This is $\mathbf{w}$ ! We therefore have $\overrightarrow{A C}=\mathbf{w}=\overrightarrow{O B}$, which means sides $\overline{A C}$ and $\overline{O B}$ of $O A C B$ are parallel ( $\overrightarrow{A C}$ and $\overrightarrow{O B}$ have the same direction) and have the same length ( $\overrightarrow{A C}$ and $\overrightarrow{O B}$ have the same magnitude). So, $O A C B$ is a parallelogram.
(c) In $\triangle O A C$, we see that $\overrightarrow{O A}=\mathbf{v}, \overrightarrow{A C}=\mathbf{w}$, and $\overrightarrow{O C}=\mathbf{v}+\mathbf{w}$. This isn't a coincidence. We can follow exactly the same steps to add any two vectors. We start at the origin and draw the arrow corresponding to $\mathbf{v}$. Then, starting from where this arrow ends, we draw the arrow corresponding to $\mathbf{w}$. The arrow from the origin to the end of this second arrow corresponds to $\mathbf{v}+\mathbf{w}$. We can also view $\mathbf{v}+\mathbf{w}$ as the diagonal of the parallelogram with $\mathbf{v}$ and $\mathbf{w}$ as consecutive sides.

We can also see in our diagram that vector addition is commutative. That is, we have
$$\mathbf{v}+\mathbf{w}=\mathbf{w}+\mathbf{v},$$
where $\mathbf{v}+\mathbf{w}$ corresponds to the path $O \rightarrow A \rightarrow C$ and $\mathbf{w}+\mathbf{v}$ corresponds to the path $O \rightarrow B \rightarrow C$.

The vector addition illustrated in the previous problem can be extended to any number of vectors. The process of adding vectors described in part (c) is sometimes referred to as head-to-tail addition, where the start of an arrow depicting a vector is the tail of the vector and the end of the arrow is the vector's head.

303

---

<!-- Page 304 -->

CHAPTER 9. VECTORS IN TWO DIMENSIONS

We add a series of vectors by drawing the first, and then drawing the second by placing the tail of the second at the head of the first. We continue in this manner until all the vectors are drawn. The arrow from the tail of the first vector to the head of the last represents the sum of all the vectors.

Now that we have a handle on addition, we turn to vector subtraction.
Problem 9.6: Let $\mathbf{v}=\binom{5}{1}$ and $\mathbf{w}=\binom{2}{4}$.
(a) We define vector subtraction to fit with our definition of vector addition. The vector $\mathbf{w}-\mathbf{v}$ is the vector $\mathbf{u}$ such that $\mathbf{u}+\mathbf{v}=\mathbf{w}$. Use the definition of vector addition to find $x$ and $y$ such that $\mathbf{w}-\mathbf{v}=\binom{x}{y}$.
(b) Let $O$ be the origin, let $A$ be the point $(5,1)$, let $B$ be the point $(2,4)$, and let $C$ be the point $(x, y)$, where $x$ and $y$ are your answers from part (a). What are $\overrightarrow{O A}, \overrightarrow{O B}, \overrightarrow{O C}$, and $\overrightarrow{A B}$ in terms of $\mathbf{v}$ and $\mathbf{w}$ ?
(c) Show that for any points $P$ and $Q$ in the Cartesian plane, we have $\overrightarrow{P Q}=\vec{Q}-\vec{P}$.
(d) How are $\overrightarrow{P Q}$ and $\overrightarrow{Q P}$ related?

Solution for Problem 9.6:
(a) If $\mathbf{w}-\mathbf{v}=\binom{x}{y}$, then we must have $\mathbf{w}=\binom{x}{y}+\mathbf{v}$. Applying the definition of vector addition, we have
$$\binom{2}{4}=\binom{x}{y}+\binom{5}{1}=\binom{x+5}{y+1} .$$

Therefore, we must have $x+5=2$ and $y+1=4$, so $x=2-5=-3$ and $y=4-1=3$. In other words, vector subtraction works in exactly the way we would expect:
$$\binom{x}{y}=\mathbf{w}-\mathbf{v}=\binom{2}{4}-\binom{5}{1}=\binom{2-5}{4-1}=\binom{-3}{3} .$$

In general, we can follow the same process to show that:
Important: For any vectors $\binom{a}{b}$ and $\binom{c}{d}$, we have
$$\binom{a}{b}-\binom{c}{d}=\binom{a-c}{b-d} .$$

This also means that we can view vector subtraction as a combination of vector addition and scalar multiplication:
$$\binom{a}{b}-\binom{c}{d}=\binom{a}{b}+(-1)\binom{c}{d}=\binom{a}{b}+\binom{-c}{-d}=\binom{a-c}{b-d} .$$

304

---

<!-- Page 305 -->

9.2. THE DOT PRODUCT
(b) As in the previous problem, we have $\overrightarrow{O A}=\mathbf{v}$ and $\overrightarrow{O B}=\mathbf{w}$. Since $(x, y)=(-3,3)$ from part (a), we have $\overrightarrow{O C}=\binom{-3}{3}=\mathbf{w}-\mathbf{v}$. Since point $B$ is 3 to the left and 3 above $A$, we have $\overrightarrow{A B}=\binom{-3}{3}$, so $\overrightarrow{A B}=\mathbf{w}-\mathbf{v}$.
(c) In the diagram, let $O$ be the origin. From our definition of vector subtraction, the vector $\vec{Q}-\vec{P}$ is the vector we must add to $\vec{P}$ to get $\vec{Q}$. Consider the vector $\operatorname{sum} \vec{P}+\overrightarrow{P Q}$. Since $\vec{P}$ is the vector from the origin to $P$, and the vector $\overrightarrow{P Q}$ is the vector from $P$ to $Q$, when we perform head-to-tail addition to get $\vec{P}+\overrightarrow{P Q}$, we go from the origin to $P$, and then from $P$ to $Q$. So, the vector sum $\vec{P}+\overrightarrow{P Q}$ equals $\vec{Q}$. Therefore, $\overrightarrow{P Q}$ is indeed the vector we must add to $\vec{P}$ to get $\vec{Q}$, which means $\overrightarrow{P Q}=\vec{Q}-\vec{P}$.
(d) Using the relationship from part (c), we have $\overrightarrow{P Q}=\vec{Q}-\vec{P}$ and $\overrightarrow{Q P}=\vec{P}-\vec{Q}$, so $\overrightarrow{P Q}=-\overrightarrow{Q P}$. We could also have noted that the vector from $P$ to $Q$ (the vector $\overrightarrow{P Q}$ ) has the same length but opposite direction as the vector from $Q$ to $P(\overrightarrow{Q P})$, so we have $\overrightarrow{P Q}=-\overrightarrow{Q P}$.

Important: For any points $A$ and $B$, we have $\overrightarrow{A B}=\vec{B}-\vec{A}$.
$$!$$

Exercises
9.1.1 Use the definitions of vector addition and multiplication of a vector by a scalar to show that $\mathbf{0}+\mathbf{v}=\mathbf{v}$ and $0 \mathbf{v}=0$ for all $\mathbf{v}$.
9.1.2 Evaluate the following:
(a) $\left\|\binom{4}{-5}\right\|$
(b) $\|7 i-24 j\|$
9.1.3 Express each of the following as a single vector:
(a) $\binom{4}{-3}+2\binom{5}{-3}-\binom{-1}{7}$
(b) $\quad\binom{-1}{6}-2\binom{-6}{2}-3\binom{0}{4}$
9.1.4 If $A, B, C$, and $D$ are points in the Cartesian plane such that $\overrightarrow{A B}=\overrightarrow{C D}$ and the four points are not all on the same line, then must $A B D C$ be a parallelogram?
9.1.5 Show that $\|c \mathbf{v}\|=|c|\|\mathbf{v}\|$ for all vectors $\mathbf{v}$ and scalars $c$.
9.2 The Dot Product

In the previous section, we learned how to add and subtract vectors and how to multiply a vector by a scalar. In this section, we define a special product of two vectors, the dot product. We denote the dot product of vectors $\mathbf{v}$

305

---

<!-- Page 306 -->

CHAPTER 9. VECTORS IN TWO DIMENSIONS

and $\mathbf{w}$ as $\mathbf{v} \cdot \mathbf{w}$. Letting $\mathbf{v}=\binom{v_{1}}{v_{2}}$ and $\mathbf{w}=\binom{w_{1}}{w_{2}}$, we define the dot product $\mathbf{v} \cdot \mathbf{w}$ as
$$\binom{v_{1}}{v_{2}} \cdot\binom{w_{1}}{w_{2}}=v_{1} w_{1}+v_{2} w_{2} .$$

The dot product is also sometimes referred to as the inner product.
Problems

Problem 9.7: Let $\mathbf{p}=\binom{4}{-3}, \mathbf{q}=\binom{5}{2}$, and $\mathbf{r}=\binom{-2}{7}$.
(a) Evaluate $\mathbf{p} \cdot \mathbf{q}$ and $\mathbf{q} \cdot \mathbf{p}$.
(b) Evaluate $\mathbf{p} \cdot(2 \mathbf{r})$ and $2(\mathbf{p} \cdot \mathbf{r})$.
(c) Evaluate $\mathbf{p} \cdot(\mathbf{q}+\mathbf{r})$ and $\mathbf{p} \cdot \mathbf{q}+\mathbf{p} \cdot \mathbf{r}$.
(d) Generalize your results from parts (a), (b), and (c). That is, show that for all vectors $\mathbf{u}, \mathbf{v}, \mathbf{w}$ and all scalars $a$, we have $\mathbf{u} \cdot \mathbf{v}=\mathbf{v} \cdot \mathbf{u}, \mathbf{u} \cdot(a \mathbf{v})=a(\mathbf{u} \cdot \mathbf{v})$ and $\mathbf{u} \cdot(\mathbf{v}+\mathbf{w})=\mathbf{u} \cdot \mathbf{v}+\mathbf{u} \cdot \mathbf{w}$.

Problem 9.8: Show that for any vector $\mathbf{v}$, we have $\mathbf{v} \cdot \mathbf{v}=\|\mathbf{v}\|^{2}$.
Problem 9.9: In this problem, we find a geometric interpretation of the dot product of two nonzero vectors.
(a) Let $V$ and $W$ be points in the Cartesian plane such that $\vec{V}=\mathbf{v}$ and $\vec{W}=\mathbf{w}$, and let $O$ be the origin. Let $\theta=\angle W O V$. Use $\triangle W O V$ to express $(\mathbf{v}-\mathbf{w}) \cdot(\mathbf{v}-\mathbf{w})$ in terms of $\|\mathbf{v}\|,\|\mathbf{w}\|$, and $\theta$.
(b) Expand the product $(\mathbf{v}-\mathbf{w}) \cdot(\mathbf{v}-\mathbf{w})$ using your results from Problem 9.7.
(c) Combine your results in parts (a) and (b) to show that $\mathbf{v} \cdot \mathbf{w}=\|\mathbf{v}\|\|\mathbf{w}\| \cos \theta$.

Problem 9.10: Find the angle between each pair of vectors below.
(a) $\binom{-1}{\sqrt{3}}$ and $\binom{0}{-2}$
(b) $\binom{12}{-8}$ and $\binom{2}{3}$
(c) $\binom{2}{1}$ and $\binom{-2-\sqrt{3}}{-1+2 \sqrt{3}}$

Problem 9.11: We say that two vectors are orthogonal if their dot product is zero. Suppose we draw arrows representing two nonzero vectors from the same point. If these vectors are orthogonal, then how are the arrows that represent them related?

Problem 9.12: If $\mathbf{p} \cdot \mathbf{q}=\mathbf{p} \cdot \mathbf{r}$ for a nonzero vector $\mathbf{p}$, then must we have $\mathbf{q}=\mathbf{r}$ ?
Problem 9.13: Use the dot product to prove that
$$\left(x_{1} y_{1}+x_{2} y_{2}\right)^{2} \leq\left(x_{1}^{2}+x_{2}^{2}\right)\left(y_{1}^{2}+y_{2}^{2}\right)$$
for all real $x_{1}, x_{2}, y_{1}$, and $y_{2}$. When does equality hold?

306

---

<!-- Page 307 -->

9.2. THE DOT PRODUCT

Problem 9.14: Suppose $f$ is a function whose domain is $\mathbb{R}^{2}$, which means that its domain is all vectors in two dimensions. We say that $f$ is a linear function if
(i) $f(a \mathbf{v})=a f(\mathbf{v})$ for all scalars $a$ and vectors $\mathbf{v}$, and
(ii) $f(\mathbf{v}+\mathbf{w})=f(\mathbf{v})+f(\mathbf{w})$ for all vectors $\mathbf{v}$ and $\mathbf{w}$.

Suppose $g(\mathbf{w})$ is a linear function that maps vectors to scalars. That is, it takes a vector as an input and gives a scalar as an output. For example, $g(\mathbf{w})=\binom{2}{1} \cdot \mathbf{w}$ is one such function.
(a) Explain why $g(x \mathbf{i}+y \mathbf{j})=x g(\mathbf{i})+y g(\mathbf{j})$.
(b) Why does part (a) tell us that there exists some vector $\mathbf{v}$ such that $g(\mathbf{w})=\mathbf{v} \cdot \mathbf{w}$ for all $\mathbf{w}$ ? Is this vector $\mathbf{v}$ unique?

Problem 9.7: Let $\mathbf{p}=\binom{4}{-3}, \mathbf{q}=\binom{5}{2}$, and $\mathbf{r}=\binom{-2}{7}$.
(a) Evaluate $\mathbf{p} \cdot \mathbf{q}$ and $\mathbf{q} \cdot \mathbf{p}$.
(b) Evaluate $\mathbf{p} \cdot(2 \mathbf{r})$ and 2(p ⋅ r).
(c) Evaluate $\mathbf{p} \cdot(\mathbf{q}+\mathbf{r})$ and $\mathbf{p} \cdot \mathbf{q}+\mathbf{p} \cdot \mathbf{r}$.
(d) Generalize your results from parts (a), (b), and (c). That is, show that for all vectors $\mathbf{u}, \mathbf{v}, \mathbf{w}$ and all scalars $a$, we have $\mathbf{u} \cdot \mathbf{v}=\mathbf{v} \cdot \mathbf{u}, \mathbf{u} \cdot(a \mathbf{v})=a(\mathbf{u} \cdot \mathbf{v})$ and $\mathbf{u} \cdot(\mathbf{v}+\mathbf{w})=\mathbf{u} \cdot \mathbf{v}+\mathbf{u} \cdot \mathbf{w}$.

Solution for Problem 9.7:
(a) We have $\mathbf{p} \cdot \mathbf{q}=(4)(5)+(-3)(2)=14$ and $\mathbf{q} \cdot \mathbf{p}=(5)(4)+(2)(-3)=14$, so $\mathbf{p} \cdot \mathbf{q}=\mathbf{q} \cdot \mathbf{p}$.
(b) We have
$$p \cdot(2 r)=\binom{4}{-3} \cdot\binom{-4}{14}=(4)(-4)+(-3)(14)=-58$$
and
$$2(\mathbf{p} \cdot \mathbf{r})=2\left(\binom{4}{-3} \cdot\binom{-2}{7}\right)=2(4(-2)+(-3)(7))=-58$$

Interesting; we have $\mathbf{p} \cdot(2 \mathbf{r})=2(\mathbf{p} \cdot \mathbf{r})$.
(c) We have
$$\mathbf{p} \cdot(\mathbf{q}+\mathbf{r})=\binom{4}{-3} \cdot\left(\binom{5}{2}+\binom{-2}{7}\right)=\binom{4}{-3} \cdot\binom{3}{9}=(4)(3)+(-3)(9)=-15$$
and
$$\mathbf{p} \cdot \mathbf{q}+\mathbf{p} \cdot \mathbf{r}=\binom{4}{-3} \cdot\binom{5}{2}+\binom{4}{-3}\binom{-2}{7}=14-29=-15 .$$

We're not surprised to see that $\mathbf{p} \cdot(\mathbf{q}+\mathbf{r})=\mathbf{p} \cdot \mathbf{q}+\mathbf{p} \cdot \mathbf{r}$.
(d) Let $\mathbf{u}=\binom{u_{1}}{u_{2}}, \mathbf{v}=\binom{v_{1}}{v_{2}}$, and $\mathbf{w}=\binom{w_{1}}{w_{2}}$. We then have
$$\begin{array}{l}
\mathbf{u} \cdot \mathbf{v}=u_{1} v_{1}+u_{2} v_{2} \\
\mathbf{v} \cdot \mathbf{u}=v_{1} u_{1}+v_{2} u_{2}=u_{1} v_{1}+u_{2} v_{2}
\end{array}$$

307

---

<!-- Page 308 -->

CHAPTER 9. VECTORS IN TWO DIMENSIONS

so the dot product is commutative: we have $\mathbf{u} \cdot \mathbf{v}=\mathbf{v} \cdot \mathbf{u}$ for all vectors $\mathbf{u}$ and $\mathbf{v}$. We also have
$$\mathbf{u} \cdot(a \mathbf{v})=\binom{u_{1}}{u_{2}} \cdot\binom{a v_{1}}{a v_{2}}=\left(u_{1}\right)\left(a v_{1}\right)+\left(u_{2}\right)\left(a v_{2}\right)=a\left(u_{1} v_{1}+u_{2} v_{2}\right)$$
and
$$a(\mathbf{u} \cdot \mathbf{v})=a\left(\binom{u_{1}}{u_{2}} \cdot\binom{v_{1}}{v_{2}}\right)=a\left(u_{1} v_{1}+u_{2} v_{2}\right) .$$

Therefore, we have $\mathbf{u} \cdot(a \mathbf{v})=a(\mathbf{u} \cdot \mathbf{v})$ for all scalars $a$ and vectors $\mathbf{u}$ and $\mathbf{v}$.
Turning to $\mathbf{u} \cdot(\mathbf{v}+\mathbf{w})$ and $\mathbf{u} \cdot \mathbf{v}+\mathbf{u} \cdot \mathbf{w}$, we have
$$\mathbf{u} \cdot(\mathbf{v}+\mathbf{w})=\binom{u_{1}}{u_{2}} \cdot\binom{v_{1}+w_{1}}{v_{2}+w_{2}}=u_{1}\left(v_{1}+w_{1}\right)+u_{2}\left(v_{2}+w_{2}\right)$$
and
$$\mathbf{u} \cdot \mathbf{v}+\mathbf{u} \cdot \mathbf{w}=\binom{u_{1}}{u_{2}} \cdot\binom{v_{1}}{v_{2}}+\binom{u_{1}}{u_{2}} \cdot\binom{w_{1}}{w_{2}}=u_{1} v_{1}+u_{2} v_{2}+u_{1} w_{1}+u_{2} w_{2}=u_{1}\left(v_{1}+w_{1}\right)+u_{2}\left(v_{2}+w_{2}\right) .$$

As expected, we have $\mathbf{u} \cdot(\mathbf{v}+\mathbf{w})=\mathbf{u} \cdot \mathbf{v}+\mathbf{u} \cdot \mathbf{w}$.

Important: For any scalar $a$ and vectors $\mathbf{u}, \mathbf{v}$, and $\mathbf{w}$, we have
$\square$
$$\begin{aligned}
\mathbf{u} \cdot \mathbf{v} & =\mathbf{v} \cdot \mathbf{u} \\
\mathbf{u} \cdot(a \mathbf{v}) & =a(\mathbf{u} \cdot \mathbf{v}) \\
\mathbf{u} \cdot(\mathbf{v}+\mathbf{w}) & =\mathbf{u} \cdot \mathbf{v}+\mathbf{u} \cdot \mathbf{w}
\end{aligned}$$

As we noted on page 307 , a function $f$ with domain $\mathbb{R}^{2}$ is a linear function if $f(a \mathbf{v})=a f(\mathbf{v})$ for all scalars $a$ and vectors $\mathbf{v}$, and $f(\mathbf{v}+\mathbf{w})=f(\mathbf{v})+f(\mathbf{w})$ for all vectors $\mathbf{v}$ and $\mathbf{w}$. Together, the properties $\mathbf{u} \cdot(a \mathbf{v})=a(\mathbf{u} \cdot \mathbf{v})$ and $\mathbf{u} \cdot(\mathbf{v}+\mathbf{w})=\mathbf{u} \cdot \mathbf{v}+\mathbf{u} \cdot \mathbf{w}$ tell us that for any vector $\mathbf{u}$, the function $f(\mathbf{v})=\mathbf{u} \cdot \mathbf{v}$ is a linear function. Combining this with the fact that $\mathbf{u} \cdot \mathbf{v}=\mathbf{v} \cdot \mathbf{u}$, we see that $f(\mathbf{v})=\mathbf{v} \cdot \mathbf{u}$ is also a linear function. We care about this because so many relationships in a great many fields of study are linear relationships. After we get a little more experience with the dot product, we'll prove that every linear function that maps vectors to scalars can be represented with a dot product. So, by studying the properties of the dot product, we are studying the properties of linear functions that arise in a wide range of fields.

Sidenote: We say that the function $g(\mathbf{u}, \mathbf{v})=\mathbf{u} \cdot \mathbf{v}$ is bilinear because it is linear in both $\mathbf{u}$ and $\mathbf{v}$.

Problem 9.8: Show that for any vector $\mathbf{v}$, we have $\mathbf{v} \cdot \mathbf{v}=\|\mathbf{v}\|^{2}$.

Solution for Problem 9.8: Let $\mathbf{v}=\binom{v_{1}}{v_{2}}$, so that
$$\mathbf{v} \cdot \mathbf{v}=\binom{v_{1}}{v_{2}} \cdot\binom{v_{1}}{v_{2}}=v_{1}^{2}+v_{2}^{2}=\|\mathbf{v}\|^{2} .$$

308

---

<!-- Page 309 -->

9.2. THE DOT PRODUCT
Important: For any vector $\mathbf{v}$, we have $\mathbf{v} \cdot \mathbf{v}=\|\mathbf{v}\|^{2}$.
(1)

We can use the basic principles we proved in Problems 9.7 and 9.8 to develop a geometric interpretation of the dot product.

Problem 9.9: Let $\theta$ be the angle between nonzero vectors $\mathbf{v}$ and $\mathbf{w}$. Show that $\mathbf{v} \cdot \mathbf{w}=\|\mathbf{v}\|\|\mathbf{w}\| \cos \theta$.

Solution for Problem 9.9: The presence of $\|\mathbf{v}\|,\|\mathbf{w}\|$ and $\cos \theta$ suggest a geometric approach. At right, we have points $V$ and $W$, where $\vec{V}=\mathbf{v}$ and $\vec{W}=\mathbf{w}$, and we let the origin be $O$. We therefore have $O V=\|\mathbf{v}\|, O W=\|\mathbf{w}\|$, and $W V=\|\overrightarrow{W V}\|=\|\mathbf{v}-\mathbf{w}\|$.

We try the Law of Cosines, since this will produce a term of the form $\|\mathbf{v}\|\|\mathbf{w}\| \cos \theta$. The Law of Cosines gives us $W V^{2}=O V^{2}+O W^{2}-2(O V)(O W) \cos \theta$, or
$$\|\mathbf{v}-\mathbf{w}\|^{2}=\|\mathbf{v}\|^{2}+\|\mathbf{w}\|^{2}-2\|\mathbf{v}\|\|\mathbf{w}\| \cos \theta .$$

To introduce dot products, we apply the relationship we proved in Problem 9.8, which gives $\mathrm{us}\|\mathbf{v}\|^{2}=\mathbf{v} \cdot \mathbf{v}$, $\|\mathbf{w}\|^{2}=\mathbf{w} \cdot \mathbf{w}$, and $\|\mathbf{v}-\mathbf{w}\|^{2}=(\mathbf{v}-\mathbf{w}) \cdot(\mathbf{v}-\mathbf{w})$, so we can write the Law of Cosines equation above as
$$(\mathbf{v}-\mathbf{w}) \cdot(\mathbf{v}-\mathbf{w})=\mathbf{v} \cdot \mathbf{v}+\mathbf{w} \cdot \mathbf{w}-2\|\mathbf{v}\|\|\mathbf{w}\| \cos \theta .$$

This equation doesn't have $\mathbf{v} \cdot \mathbf{w}$, yet. Applying the fact that the dot product is distributive, which we proved in Problem 9.7, we have
$$\begin{aligned}
(\mathbf{v}-\mathbf{w}) \cdot(\mathbf{v}-\mathbf{w}) & =(\mathbf{v}-\mathbf{w}) \cdot \mathbf{v}-(\mathbf{v}-\mathbf{w}) \cdot \mathbf{w} \\
& =\mathbf{v} \cdot \mathbf{v}-\mathbf{w} \cdot \mathbf{v}-\mathbf{v} \cdot \mathbf{w}+\mathbf{w} \cdot \mathbf{w}
\end{aligned}$$

Since $\mathbf{v} \cdot \mathbf{w}=\mathbf{w} \cdot \mathbf{v}$, our Law of Cosines equation now is
$$\mathbf{v} \cdot \mathbf{v}-2 \mathbf{v} \cdot \mathbf{w}+\mathbf{w} \cdot \mathbf{w}=\mathbf{v} \cdot \mathbf{v}+\mathbf{w} \cdot \mathbf{w}-2\|\mathbf{v}\|\|\mathbf{w}\| \cos \theta$$

Simplifying this equation gives
$$\mathbf{v} \cdot \mathbf{w}=\|\mathbf{v}\|\|\mathbf{w}\| \cos \theta .$$

Rearranging this equation gives
$$\cos \theta=\frac{\mathbf{v} \cdot \mathbf{w}}{\|\mathbf{v}\|\|\mathbf{w}\|}$$

We can use this relationship to find the angle between two vectors.
Problem 9.10: Find the angle between each pair of vectors below.
(a) $\quad\binom{-1}{\sqrt{3}}$ and $\binom{0}{-2}$
(b) $\quad\binom{12}{-8}$ and $\binom{2}{3}$
(c) $\quad\binom{2}{1}$ and $\binom{-2-\sqrt{3}}{-1+2 \sqrt{3}}$

Solution for Problem 9.10: In each of the following parts, let $\theta$ be the angle between the two given vectors.

309

---

<!-- Page 310 -->

CHAPTER 9. VECTORS IN TWO DIMENSIONS
(a) We have
$$\cos \theta=\frac{(-1)(0)+(\sqrt{3})(-2)}{\sqrt{(-1)^{2}+(\sqrt{3})^{2}} \cdot \sqrt{0^{2}+2^{2}}}=\frac{-2 \sqrt{3}}{4}=-\frac{\sqrt{3}}{2},$$
so $\theta=150^{\circ}$.
(b) We have
$$\cos \theta=\frac{(12)(2)+(-8)(3)}{\sqrt{12^{2}+(-8)^{2}} \cdot \sqrt{2^{2}+3^{2}}}=0,$$
so $\theta=90^{\circ}$.
(c) We have
$$\cos \theta=\frac{(2)(-2-\sqrt{3})+(1)(-1+2 \sqrt{3})}{\sqrt{2^{2}+1^{2}} \cdot \sqrt{(-2-\sqrt{3})^{2}+(-1+2 \sqrt{3})^{2}}}=\frac{-5}{\sqrt{5} \cdot 2 \sqrt{5}}=-\frac{1}{2^{\prime}}$$
so $\theta=120^{\circ}$.

Problem 9.11: We say that two vectors are orthogonal if their dot product is zero. Suppose we draw arrows representing two nonzero vectors from the same point. If these vectors are orthogonal, then how are the arrows that represent them related geometrically?

Solution for Problem 9.11: Let the vectors be $\mathbf{v}$ and $\mathbf{w}$. Since $\mathbf{v}$ and $\mathbf{w}$ are nonzero, we have $\|\mathbf{v}\|\|\mathbf{w}\| \cos \theta=0$ if and only if $\cos \theta=0$, which means the angle between the vectors is $90^{\circ}$. Therefore, the arrows representing the vectors are perpendicular if and only if the vectors are orthogonal.

So, we can interpret "orthogonal" geometrically to mean "perpendicular." Since these concepts are so closely related, they share a symbol. We can write that $\mathbf{v}$ and $\mathbf{w}$ are orthogonal as $\mathbf{v} \perp \mathbf{w}$.

The vector $\mathbf{0}$ is orthogonal to all vectors.
Problem 9.12: If $\mathbf{p} \cdot \mathbf{q}=\mathbf{p} \cdot \mathbf{r}$ for a nonzero vector $\mathbf{p}$, then must we have $\mathbf{q}=\mathbf{r}$ ?

Solution for Problem 9.12: No. Rearranging the equation $\mathbf{p} \cdot \mathbf{q}=\mathbf{p} \cdot \mathbf{r}$ gives $\mathbf{p} \cdot \mathbf{q}-\mathbf{p} \cdot \mathbf{r}=0$, which we can "factor" as $\mathbf{p} \cdot(\mathbf{q}-\mathbf{r})=0$, because the dot product is distributive. Therefore, if $\mathbf{p} \cdot \mathbf{q}=\mathbf{p} \cdot \mathbf{r}$, all we know is that the vector $\mathbf{q}-\mathbf{r}$ is orthogonal to $\mathbf{p}$. We cannot conclude that $\mathbf{q}=\mathbf{r}$.

Now that we know what to look for, we can quickly find an example for which $\mathbf{p} \cdot \mathbf{q}=\mathbf{p} \cdot \mathbf{r}$, but $\mathbf{q} \neq \mathbf{r}$. Let $\mathbf{p}=\binom{2}{-1}$. Then, we find $x$ and $y$ such that $\binom{2}{-1} \cdot\binom{x}{y}=0$. One such pair is $(x, y)=(1,2)$. Therefore, if $\mathbf{q}-\mathbf{r}=\binom{1}{2}$, then we have $\mathbf{p} \cdot \mathbf{q}=\mathbf{p} \cdot \mathbf{r}$. We can choose any vector for $\mathbf{r}$ and solve for the corresponding $\mathbf{q}$. Specifically, suppose $\mathbf{r}=\binom{3}{2}$, then we have $\mathbf{q}=\binom{1}{2}+\mathbf{r}=\binom{4}{4}$, and indeed we have $\mathbf{p} \cdot \mathbf{q}=\mathbf{p} \cdot \mathbf{r}=4$, but $\mathbf{q} \neq \mathbf{r}$.

WARNING!!
We cannot "divide" vectors from dot products. For example, if $\mathbf{u} \cdot \mathbf{v}=\mathbf{u} \cdot \mathbf{w}$, then we cannot deduce that $\mathbf{v}$ and $\mathbf{w}$ are the same.

310

---

<!-- Page 311 -->

9.2. THE DOT PRODUCT

Problem 9.13: Use the dot product to prove that
$$\left(x_{1} y_{1}+x_{2} y_{2}\right)^{2} \leq\left(x_{1}^{2}+x_{2}^{2}\right)\left(y_{1}^{2}+y_{2}^{2}\right)$$
for all real $x_{1}, x_{2}, y_{1}$, and $y_{2}$. When does equality hold?

Solution for Problem 9.13: The expression on the lesser side looks like the square of a dot product and the expression on the greater side looks like the product of the squares of vector norms. So, we let $\mathbf{x}=\binom{x_{1}}{x_{2}}$ and $\mathbf{y}=\binom{y_{1}}{y_{2}}$. Then, we have
$$\mathbf{x} \cdot \mathbf{y}=x_{1} y_{1}+x_{2} y_{2}$$
and
$$\|\mathbf{x}\|^{2}\|\mathbf{y}\|^{2}=\left(x_{1}^{2}+x_{2}^{2}\right)\left(y_{1}^{2}+y_{2}^{2}\right)$$

We also have $\mathbf{x} \cdot \mathbf{y}=\|\mathbf{x}\|\|\mathbf{y}\| \cos \theta$, where $\theta$ is the angle between $\mathbf{x}$ and $\mathbf{y}$. We must have $|\cos \theta| \leq 1$, so
$$\left|\frac{\mathbf{x} \cdot \mathbf{y}}{\|\mathbf{x}\|\|\mathbf{y}\|}\right|=|\cos \theta| \leq 1$$

Squaring the left and right ends of this, multiplying both sides by $\|\mathbf{x}\|^{2}\|\mathbf{y}\|^{2}$, and substituting our expressions for $\mathbf{x} \cdot \mathbf{y}$ and $\|\mathbf{x}\|^{2}\|\mathbf{y}\|^{2}$ from above gives the desired
$$\left(x_{1} y_{1}+x_{2} y_{2}\right)^{2} \leq\left(x_{1}^{2}+x_{2}^{2}\right)\left(y_{1}^{2}+y_{2}^{2}\right)$$
(Note that we can perform the initial squaring because both sides of the inequality are nonnegative.)
We have equality if and only if $|\cos \theta|=1$, which means $\theta=0^{\circ}$ or $\theta=180^{\circ}$. This occurs if and only if $\mathbf{x}$ and $\mathbf{y}$ are in the same direction, or in opposite directions. In either case, we must have $\mathbf{x}=\boldsymbol{c y}$ for some nonzero constant c. Conversely, if $\mathbf{x}=c \mathbf{y}$ for some nonzero constant $c$, then $\theta=0^{\circ}$ or $\theta=180^{\circ}$, in which case we have $|\cos \theta|=1$, so equality holds. Finally, equality holds if either vector is the vector $\mathbf{0}$. Therefore, equality holds in the inequality if and only if $\mathbf{y}$ is $\mathbf{0}$ or if $\mathbf{x}=c \mathbf{y}$ for some constant $c$. (Letting $c=0$ covers the case in which $\mathbf{x}$ is the zero vector.)

This result is called the Cauchy-Schwarz Inequality.
We finish this section by returning to our claim back on page 308 that every linear function that maps vectors to scalars can be represented with a dot product.

Problem 9.14: We say that a function $f$ with domain $\mathbb{R}^{2}$ is a linear function if
(i) $f(a \mathbf{v})=a f(\mathbf{v})$ for all scalars $a$ and vectors $\mathbf{v}$, and
(ii) $f(\mathbf{v}+\mathbf{w})=f(\mathbf{v})+f(\mathbf{w})$ for all vectors $\mathbf{v}$ and $\mathbf{w}$.

Suppose $g(\mathbf{w})$ is a linear function that maps vectors to scalars. That is, it takes a vector as an input and gives a scalar as an output. For example, $g(\mathbf{w})=\binom{2}{1} \cdot \mathbf{w}$ is one such function.
(a) Explain why $g(x \mathbf{i}+y \mathbf{j})=x g(\mathbf{i})+y g(\mathbf{j})$.
(b) Why does part (a) tell us that there exists some vector $\mathbf{v}$ such that $g(\mathbf{w})=\mathbf{v} \cdot \mathbf{w}$ for all $\mathbf{w}$ ? Is this vector $\mathbf{v}$ unique?

311

---

<!-- Page 312 -->

CHAPTER 9. VECTORS IN TWO DIMENSIONS

Solution for Problem 9.14:
(a) Applying rule (ii) in our definition of a linear function, we have
$$g(x \mathbf{i}+y \mathbf{j})=g(x \mathbf{i})+g(y \mathbf{j})$$

Applying rule (i) to each of the terms on the right gives
$$g(x \mathbf{i}+y \mathbf{j})=g(x \mathbf{i})+g(y \mathbf{j})=x g(\mathbf{i})+y g(\mathbf{j}) .$$
(b) From part (a), we know that if $\mathbf{w}=w_{1} \mathbf{i}+w_{2} \mathbf{j}$, we have
$$g(\mathbf{w})=g\left(w_{1} \mathbf{i}+w_{2} \mathbf{j}\right)=w_{1} \cdot g(\mathbf{i})+w_{2} \cdot g(\mathbf{j})$$

So, if we let $\mathbf{v}=\binom{g(\mathbf{i})}{g(\mathbf{j})}$, then we have
$$g(\mathbf{w})=w_{1} \cdot g(\mathbf{i})+w_{2} \cdot g(\mathbf{j})=\binom{g(\mathbf{i})}{g(\mathbf{j})} \cdot\binom{w_{1}}{w_{2}}=\mathbf{v} \cdot \mathbf{w} .$$

Since $g(\mathbf{i})$ and $g(\mathbf{j})$ are unique, this choice of $\mathbf{v}$ is unique. Therefore, we have shown that:
Important: Each linear function $g$ that maps vectors to scalars can be defined as $g(\mathbf{w})=\mathbf{v} \cdot \mathbf{w}$
! for a unique vector $\mathbf{v}$.

This is why dot products are so important, and why you'll be seeing them throughout your future studies of science and mathematics.

Exercises
9.2.1 Evaluate each of the following
(a) $\binom{5}{-3} \cdot\binom{-2}{4}$
(b) $\quad\binom{-6}{-1} \cdot\binom{0}{-3}$
9.2.2 Let $\mathbf{u}=5 \mathbf{i}-12 \mathbf{j}$ and $\mathbf{v}=3 \mathbf{i}+4 \mathbf{j}$. Find $(\mathbf{u}-\mathbf{v}) \cdot(\mathbf{u}+\mathbf{v})$.
9.2.3 Find all vectors that have 5 as one component and are orthogonal to $\binom{-1}{2}$.
9.2.4 Which two pairs of the following 5 vectors are orthogonal: $\binom{4}{-6},\binom{-3}{4},\binom{8}{6},\binom{6}{9},\binom{9}{6}$.
9.2.5 Find, to the nearest degree, the measures of the angles of $\triangle A B C$ if $A$ is $(0,5), B$ is $(1,-3)$, and $C$ is $(-5,4)$.
9.2.6 In this problem, we find another proof that the algebraic and geometric representations of the dot product are equivalent. Let $\mathbf{v}=\binom{v_{1}}{v_{2}}$ and $\mathbf{w}=\binom{w_{1}}{w_{2}}$, and let $\phi$ be the angle between $\mathbf{v}$ and $\mathbf{w}$.
(a) Let $\left(r_{\mathbf{v}}, \theta_{\mathbf{v}}\right)$ and $\left(r_{\mathbf{w}}, \theta_{\mathbf{w}}\right)$ be the polar coordinates of the points whose rectangular coordinates are $\left(v_{1}, v_{2}\right)$ and $\left(w_{1}, w_{2}\right)$, respectively. Express $\|\mathbf{v}\|\|\mathbf{w}\| \cos \phi$ in terms of these polar coordinates.
(b) Show that your expression from part (a) equals $v_{1} w_{1}+v_{2} w_{2}$.

312

---

<!-- Page 313 -->

9.3. LINES AND LINEAR DEPENDENCE
9.3 Lines and Linear Dependence

In your study of algebra, you probably learned that if $a, b$, and $c$ are constants, then the graph of the equation of $a x+b y=c$ is a line. In this section, we revisit the algebra of lines in the Cartesian plane in the context of vectors.

Geometrically speaking, any two distinct points $A$ and $B$ determine a line $\overleftrightarrow{A B}$. We can think of this line as consisting of $A$ together with all the points we can reach by going either in the direction of $B$ or in the opposite direction (away from $B$ ). This leads us naturally to a description of a line using vectors.

As a reminder, parametric equations for $x$ and $y$ are equations that define the relationship between $x$ and $y$ through an intermediary variable. For example, consider the parametric equations $x=3 t, y=2 t$. We can write these parametric equations as a single parametric equation in terms of vectors:
$$\binom{x}{y}=t\binom{3}{2}$$

When we graph such a parametric equation, we graph all points $(x, y)$ such that there is a value of $t$ for which $(x, y)$ is a solution to the equation.

Problems
Problem 9.15: Let $A$ be $(2,3)$ and let $B$ be $(-3,1)$.
(a) Explain why $\overleftrightarrow{A B}$ is the graph of the parametric equation
$$\binom{x}{y}=\binom{2}{3}+t\binom{-5}{-2} .$$
(b) Is this the only parametric equation of the form
$$\binom{x}{y}=\mathbf{u}+t \mathbf{v}$$
whose graph is $\overleftrightarrow{A B}$ ?
Problem 9.16: Let $\mathbf{u}$ and $\mathbf{v}$ be vectors with $\mathbf{v} \neq \mathbf{0}$. Explain why the graph of the parametric equation
$$\binom{x}{y}=\mathbf{u}+t \mathbf{v}$$
fits our geometric description of a line.
Problem 9.17:
(a) Show that if the graph of $\binom{x}{y}=\mathbf{u}+t \mathbf{v}$ contains $(p, q)$, then the graph is the same as the graph of
$$\binom{x}{y}=\binom{p}{q}+s \mathbf{v} .$$
(b) Let $\mathbf{v}_{1}$ and $\mathbf{v}_{2}$ be nonzero vectors. Show that if the graphs of $\binom{x}{y}=\mathbf{u}_{1}+s \mathbf{v}_{1}$ and $\binom{x}{y}=\mathbf{u}_{2}+t \mathbf{v}_{2}$ both contain distinct points $\left(x_{a}, y_{a}\right)$ and $\left(x_{b}, y_{b}\right)$, then the graphs are the same and $\mathbf{v}_{1}=k \mathbf{v}_{2}$ for some constant $k$.

313

---

<!-- Page 314 -->

CHAPTER 9. VECTORS IN TWO DIMENSIONS

Problem 9.18:
(a) Express the equation $2 x-3 y=6$ as a parametric equation of the form $\binom{x}{y}=\mathbf{u}+t \mathbf{v}$.
(b) Show that the graph any equation of the form $a x+b y=c$, where at least one of $a$ and $b$ is nonzero, is also the graph of a parametric equation of the form
$$\binom{x}{y}=\mathbf{u}+t \mathbf{v}$$
(c) Show that the graph of any parametric equation of the form $\binom{x}{y}=\mathbf{u}+t \mathbf{v}$, where $\mathbf{v}$ is nonzero, is the same as the graph of some equation of the form $a x+b y=c$, where $a, b$, and $c$ are constants.
(d) How is the vector $\mathbf{v}$ related to the slope of the line $\binom{x}{y}=\mathbf{u}+t \mathbf{v}$ ?

Problem 9.19: The vector $a \mathbf{v}+b \mathbf{w}$, where $a$ and $b$ are scalars, is called a linear combination of $\mathbf{v}$ and $\mathbf{w}$. In this problem, we explore the graphs of all linear combinations of pairs of vectors. Specifically, we are interested in the graph of the parametric equation
$$\binom{x}{y}=s \mathbf{v}+t \mathbf{w}$$
where both $s$ and $t$ are parameters.
(a) What is the graph if $\mathbf{v}=\binom{2}{1}$ and $\mathbf{w}=\binom{6}{3}$ ?
(b) What is the graph if $\mathbf{v}=\binom{1}{0}$ and $\mathbf{w}=\binom{0}{1}$ ?
(c) What is the graph if $\mathbf{v}=\binom{1}{0}$ and $\mathbf{w}=\binom{-2}{1}$ ?

Problem 9.20: Let $\mathbf{v}$ and $\mathbf{w}$ be nonzero vectors. Show that the graph of the parametric equation $\binom{x}{y}=s \mathbf{v}+t \mathbf{w}$, where both $s$ and $t$ are parameters, is a line if $\mathbf{v}$ is a scalar multiple of $\mathbf{w}$.

Problem 9.21: Let $\mathbf{v}$ and $\mathbf{w}$ be nonzero vectors such that $\mathbf{v}$ is not a scalar multiple of $\mathbf{w}$. In this problem, we show that every point $(x, y)$ is in the graph of the parametric equation
$$\binom{x}{y}=s \mathbf{v}+t \mathbf{w},$$
where $s$ and $t$ are parameters.
(a) What is the graph of $\binom{x}{y}=\mathbf{v}+t \mathbf{w}$ ? (Note that the coefficient of $\mathbf{v}$ is 1 , not $s$.)
(b) What is the graph of $\binom{x}{y}=2 \mathbf{v}+t \mathbf{w}$ ?
(c) How are your graphs in parts (a) and (b) related?
(d) Show that every point $(x, y)$ is in the graph of the parametric equation $\binom{x}{y}=s \mathbf{v}+t \mathbf{w}$, where $s$ and $t$ are parameters.

314

---

<!-- Page 315 -->

9.3. LINES AND LINEAR DEPENDENCE

Problem 9.15: Let $A$ be $(2,3)$ and let $B$ be $(-3,1)$.
(a) Explain why $\overleftrightarrow{A B}$ is the graph of the parametric equation $\binom{x}{y}=\binom{2}{3}+t\binom{-5}{-2}$.
(b) Is this the only parametric equation of the form $\binom{x}{y}=\mathbf{u}+t \mathbf{v}$ whose graph is this line?

Solution for Problem 9.15:
(a) In the introduction of this section, we described the line through $A$ and $B$ as being all the points we can reach by starting at point $A$ and going either in the direction of $B$ or in the opposite direction (away from $B$ ). The direction from $A$ to $B$ is the direction of $\overrightarrow{A B}$. We have $\overrightarrow{A B}=\binom{-3}{1}-\binom{2}{3}=\binom{-5}{-2}$. To get to any point on $\overleftrightarrow{A B}$, we start from $(2,3)$ and add some multiple of $\overrightarrow{A B}$. So, $\overleftrightarrow{A B}$ is the graph of
$$\binom{x}{y}=\binom{2}{3}+t\binom{-5}{-2}$$
(b) The equation we found in part (a) isn't the only parametric equation whose graph is $\overleftrightarrow{A B}$. We can choose any point on the line as our starting point, and any other point on the line to travel towards (or away from) to produce an equation for the line. For example, we could start from $B$ and go towards or away from $A$.
Then, we have have $\overrightarrow{B A}=-\overrightarrow{A B}=\binom{5}{2}$, and the line is the graph of
$$\binom{x}{y}=\binom{-3}{1}+s\binom{5}{2} .$$

Moreover, we can use any nonzero multiple of $\binom{5}{2}$ as the direction vector. For example, if we let $s=4 k$ in the equation above, we have the parametric equation
$$\binom{x}{y}=\binom{-3}{1}+k\binom{20}{8}$$
which also has $\overleftrightarrow{A B}$ as its graph. So, the choice of $\mathbf{u}$ and $\mathbf{v}$ such that $\overleftrightarrow{A B}$ is the graph of $\binom{x}{y}=\mathbf{u}+t \mathbf{v}$ is not unique. Vector $\mathbf{u}$ can correspond to any point on $\overleftrightarrow{A B}$, and $\mathbf{v}$ can be any nonzero multiple of $\binom{-5}{-2}$.

Problem 9.16: Let $\mathbf{u}$ and $\mathbf{v}$ be vectors with $\mathbf{v} \neq 0$. Explain why the graph of the parametric equation $\binom{x}{y}=\mathbf{u}+t \mathbf{v}$ fits our geometric description of a line given on page 313.

Solution for Problem 9.16: Let $\mathbf{u}=\binom{u_{1}}{u_{2}}$. Then, the equation $\binom{x}{y}=\mathbf{u}+t \mathbf{v}=\binom{u_{1}}{u_{2}}+t \mathbf{v}$ consists of $\left(u_{1}, u_{2}\right)$ together with all points we can reach by starting from $\left(u_{1}, u_{2}\right)$ and going in the direction of $\mathbf{v}$, or going in the direction opposite $\mathbf{v}$. This is precisely the description of a line given on page 313.

The previous two problems are not a proof that the graph of the parametric equation $\binom{x}{y}=\mathbf{u}+t \mathbf{v}$ is a line.

315

---

<!-- Page 316 -->

CHAPTER 9. VECTORS IN TWO DIMENSIONS

They explain that if we define a line in the Cartesian plane to be the set of points that satisfy this equation for some specific $\mathbf{u}$ and $\mathbf{v}$, then this line fits our geometric description of a line.

Definition: If $\mathbf{u}$ and $\mathbf{v}$ are vectors with $\mathbf{v} \neq \mathbf{0}$, then the graph of the parametric equation
$$\binom{x}{y}=\mathbf{u}+t \mathbf{v}$$
where $t$ is a parameter, is a line.
The vector $\mathbf{v}$ is called a direction vector of the line, and we'll sometimes describe a direction vector of a line as being "parallel" to the line. As suggested in our solution to Problem 9.15, the direction vector of a line is not unique. In the next problem, we investigate how direction vectors of the same line are related.

Problem 9.17:
(a) Show that if the graph of $\binom{x}{y}=\mathbf{u}+t \mathbf{v}$ contains $(p, q)$, then the graph is the same as the graph of $\binom{x}{y}=\binom{p}{q}+s \mathbf{v}$.
(b) Let $\mathbf{v}_{1}$ and $\mathbf{v}_{2}$ be nonzero vectors. Show that if the graphs of $\binom{x}{y}=\mathbf{u}_{1}+s \mathbf{v}_{1}$ and $\binom{x}{y}=\mathbf{u}_{2}+t \mathbf{v}_{2}$ both contain distinct points $\left(x_{a}, y_{a}\right)$ and $\left(x_{b}, y_{b}\right)$, then the graphs are the same and $\mathbf{v}_{1}=k \mathbf{v}_{2}$ for some constant $k$.

Solution for Problem 9.17:
(a) We defined a line algebraically using a point on the line and a direction. This part asks us to show that no matter which point on the line we choose, we'll get the same line.

Since $(p, q)$ is in the graph of $\binom{x}{y}=\mathbf{u}+t \mathbf{v}$, we have $\binom{p}{q}=\mathbf{u}+t_{1} \mathbf{v}$ for some scalar $t_{1}$. Solving for $\mathbf{u}$ gives $\mathbf{u}=\binom{p}{q}-t_{1} \mathbf{v}$. Substituting this into $\binom{x}{y}=\mathbf{u}+t \mathbf{v}$ gives
$$\binom{x}{y}=\binom{p}{q}-t_{1} \mathbf{v}+t \mathbf{v}=\binom{p}{q}+\left(t-t_{1}\right) \mathbf{v}$$

To see that Equation (9.1) has the same graph as
$$\binom{x}{y}=\binom{p}{q}+s \mathbf{v}$$
we note that for any choice of $s$ in (9.2), letting $t=s+t_{1}$ in (9.1) gives the same $\binom{x}{y}$. Conversely, for any choice of $t$ in (9.1), choosing $s=t-t_{1}$ in (9.2) gives the same $\binom{x}{y}$. Therefore, every point in the graph of (9.1) is in the graph of (9.2), and vice versa, so the graphs are the same.
(b) Geometrically speaking, this problem is a fancy way way of saying "two points determine a line." That is, if two lines have two points in common, then the lines must be the same. Let's show that our algebraic definition of a line satisfies this principle.

We start by using part (a) to note that the graphs of the two given parametric equations are also the

316

---

<!-- Page 317 -->

9.3. LINES AND LINEAR DEPENDENCE

graphs of
$$\begin{array}{l}
\binom{x}{y}=\binom{x_{a}}{y_{a}}+s \mathbf{v}_{1}, \\
\binom{x}{y}=\binom{x_{a}}{y_{a}}+t \mathbf{v}_{2},
\end{array}$$
respectively. Since $\left(x_{b}, y_{b}\right)$ is in both graphs and is distinct from $\left(x_{a}, y_{a}\right)$, there are nonzero scalars $s_{b}$ and $t_{b}$ such that
$$\begin{array}{l}
\binom{x_{b}}{y_{b}}=\binom{x_{a}}{y_{a}}+s_{b} \mathbf{v}_{1}, \\
\binom{x_{b}}{y_{b}}=\binom{x_{a}}{y_{a}}+t_{b} \mathbf{v}_{2},
\end{array}$$

Taking the difference of these equations gives $s_{b} \mathbf{v}_{1}-t_{b} \mathbf{v}_{2}=\mathbf{0}$, so $\mathbf{v}_{1}=\frac{t_{b}}{s_{b}} \mathbf{v}_{2}$. Letting $k=\frac{t_{b}}{s_{b}}$ gives us $\mathbf{v}_{1}=k \mathbf{v}_{2}$, as desired.

We now must show that graphs of (9.3) and (9.4) are the same. Substituting $\mathbf{v}_{1}=k \mathbf{v}_{2}$ into (9.3) gives us
$$\binom{x}{y}=\binom{x_{a}}{y_{a}}+s k \mathbf{v}_{2},$$
where $s$ is a parameter and $k$ is constant. All we have left is showing that this equation has the same graph as (9.4). Fortunately, that's easy. For any choice of $t$ in (9.4), letting $s=\frac{t}{k}$ in (9.5) produces the same $\binom{x}{y}$. Conversely, for any choice of $s$ in (9.5), choosing $t=s k$ in (9.4) produces the same $\binom{x}{y}$. Therefore, Equations (9.4) and (9.5) have the same graph.

Problem 9.18:
(a) Express the equation $2 x-3 y=6$ as a parametric equation of the form $\binom{x}{y}=\mathbf{u}+t \mathbf{v}$.
(b) Show that the graph any equation of the form $a x+b y=c$, where at least one of $a$ and $b$ is nonzero, is also the graph of a parametric equation of the form $\binom{x}{y}=\mathbf{u}+t \mathbf{v}$.
(c) Show that the graph of any parametric equation of the form $\binom{x}{y}=\mathbf{u}+t \mathbf{v}$, where $\mathbf{v}$ is nonzero, is the same as the graph of some equation of the form $a x+b y=c$, where $a, b$, and $c$ are constants.
(d) How is the vector $\mathbf{v}$ related to the slope of the line $\binom{x}{y}=\mathbf{u}+t \mathbf{v}$ ?

Solution for Problem 9.18:
(a) Solving for $x$ gives $x=\frac{3}{2} y+3$. Letting $y=t$ gives us the parametric equations $x=\frac{3}{2} t+3, y=t$, or $\binom{x}{y}=\binom{3}{0}+t\binom{3 / 2}{1}$
(b) If $a \neq 0$, we can use part (a) as a guide. Solving $a x+b y=c$ for $x$ gives $x=-\frac{b}{a} y+\frac{c}{a}$. We can take $t=y$ as the parameter, and we have
$$\binom{x}{y}=\binom{c / a}{0}+t\binom{-b / a}{1}$$

317

---

<!-- Page 318 -->

CHAPTER 9. VECTORS IN TWO DIMENSIONS

If $a=0$, we can simply solve for $y$, since $a$ and $b$ cannot both be 0 . We have $y=-\frac{a}{b} x+\frac{c}{b}=\frac{c}{b}$, and taking $t=x$ as the parameter gives
$$\binom{x}{y}=\binom{0}{c / b}+t\binom{1}{-a / b}$$
(c) Let $\mathbf{u}=\binom{u_{1}}{u_{2}}$ and $\mathbf{v}=\binom{v_{1}}{v_{2}}$. Then, we have
$$\binom{x}{y}=\mathbf{u}+t \mathbf{v}=\binom{u_{1}}{u_{2}}+t\binom{v_{1}}{v_{2}}=\binom{u_{1}+t v_{1}}{u_{2}+t v_{2}},$$
so $x=u_{1}+t v_{1}, y=u_{2}+t v_{2}$. To produce an equation of the form $a x+b y=c$, we eliminate the parameter $t$. Multiplying $x=u_{1}+t v_{1}$ by $v_{2}$ and multiplying $y=u_{2}+t v_{2}$ by $v_{1}$ gives
$$\begin{array}{l}
v_{2} x=u_{1} v_{2}+t v_{1} v_{2} \\
v_{1} y=u_{2} v_{1}+t v_{1} v_{2}
\end{array}$$

Subtracting the second equation from the first eliminates the parameter $t$ and leaves us with
$$v_{2} x-v_{1} y=u_{1} v_{2}-u_{2} v_{1}$$

Letting $a=v_{2}, b=-v_{1}$, and $c=u_{1} v_{2}-u_{2} v_{1}$, we see that this equation is in the form $a x+b y=c$.
Unfortunately, we're not quite finished. Our work above only tells us that every point in the graph of
$$\binom{x}{y}=\mathbf{u}+t \mathbf{v}$$
is in the graph of
$$v_{2} x-v_{1} y=u_{1} v_{2}-u_{2} v_{1}$$

It does not tell us that every point in the graph of (9.7) is in the graph of (9.6). Fortunately, we've already done most of the work to go the other direction. Part (a) tells us that the graph of $v_{2} x-v_{1} y=u_{1} v_{2}-u_{2} v_{1}$ is the graph of a parametric equation of the form
$$\binom{x}{y}=\mathbf{u}^{\prime}+t^{\prime} \mathbf{v}^{\prime}$$
for some vectors $\mathbf{u}^{\prime}$ and $\mathbf{v}^{\prime}$. We showed in part (b) of Problem 9.17 that if the graphs of two equations of this form share two points, then the graphs are the same. We know that every point in the graph of $\binom{x}{y}=\mathbf{u}+t \mathbf{v}$ (and this graph definitely has more than one point because $\mathbf{v}$ is nonzero) is in the graph of (9.7), and therefore is in the graph of (9.8). Therefore, we conclude that the graphs of (9.6) and (9.8) are the same, which means that the graphs of (9.6) and (9.7) are the same.
(d) In part (c), we saw that the parametric equation $\binom{x}{y}=\mathbf{u}+t \mathbf{v}$ is has the same graph as $v_{2} x-v_{1} y=u_{1} v_{2}-u_{2} v_{1}$. We then have two cases to consider:

Case 1: $v_{1}=0$. If $v_{1}=0$, then $v_{2} x-v_{1} y=u_{1} v_{2}-u_{2} v_{1}$ is simply $v_{2} x=u_{1} v_{2}$. Dividing by $v_{2}\left(v_{2} \neq 0\right.$ because $\mathbf{v} \neq \mathbf{0}$ ), we have $x=u_{1}$. The graph of this equation is a vertical line with undefined slope. Looking back at the equation $\binom{x}{y}=\mathbf{u}+t \mathbf{v}$, we see that when $v_{1}=0$, the direction vector is $\binom{0}{v_{2}}$, which is indeed a "vertical" vector. Therefore, a line with undefined slope has a "vertical" direction vector, as expected.

Case 2: $v_{1} \neq 0$. If $v_{1} \neq 0$, then we can solve $v_{2} x-v_{1} y=u_{1} v_{2}-u_{2} v_{1}$ for $y$ to get $y=\frac{v_{2}}{v_{1}} x-\frac{u_{1} v_{2}}{v_{1}}+u_{2}$. The slope of this line is $\frac{v_{2}}{v_{1}}$. So, the slope of a line is the ratio of the vertical component of the direction vector to the horizontal component of the direction vector-this ratio is the traditional "rise over run" description of slope!

318

---

<!-- Page 319 -->

9.3. LINES AND LINEAR DEPENDENCE

We have therefore seen that our definition of a line with vectors fits nicely with the "graph of $a x+b y=c$ " understanding of lines in the Cartesian plane from basic algebra, where the direction vector of a line plays the role of "slope."

Problem 9.19: The vector $a \mathbf{v}+b \mathbf{w}$, where $a$ and $b$ are scalars, is called a linear combination of $\mathbf{v}$ and $\mathbf{w}$. In this problem, we explore the graphs of all linear combinations of pairs of vectors. Specifically, we are interested in the graph of the parametric equation
$$\binom{x}{y}=s \mathbf{v}+t \mathbf{w},$$
where both $s$ and $t$ are parameters.
(a) What is the graph if $\mathbf{v}=\binom{2}{1}$ and $\mathbf{w}=\binom{6}{3}$ ?
(b) What is the graph if $\mathbf{v}=\binom{1}{0}$ and $\mathbf{w}=\binom{0}{1}$ ?
(c) What is the graph if $\mathbf{v}=\binom{1}{0}$ and $\mathbf{w}=\binom{-2}{1}$ ?

Solution for Problem 9.19:
(a) We have
$$\binom{x}{y}=s\binom{2}{1}+t\binom{6}{3}=\binom{2 s+6 t}{s+3 t} .$$

The first component in $\binom{2 s+6 t}{s+3 t}$ is double the second one, so $\binom{x}{y}=\binom{2 s+6 t}{s+3 t}$ gives us $x=2 y$. Therefore, we see that the graph is a line through the origin.
(b) We have
$$\binom{x}{y}=s\binom{1}{0}+t\binom{0}{1}=\binom{s}{t} .$$

We can choose $s$ and $t$ to be anything, so the graph is the entire Cartesian plane.
(c) We have
$$\binom{x}{y}=s\binom{1}{0}+t\binom{-2}{1}=\binom{s-2 t}{t}$$

To show that every point ( $a, b$ ) is in the graph, we let $s=a+2 b$ and $t=b$ in the parametric equation above, which gives $(x, y)=(a, b)$. Therefore, once again all possible $(x, y)$ are in the graph, so the graph is the entire Cartesian plane.

The graph in part (a) is a line, while the graphs in parts (b) and (c) are the entire Cartesian plane. One key difference we notice in the two parts is that $\mathbf{v}$ is a scalar multiple of $\mathbf{w}$ in part (a), but not in parts (b) or (c). Let's investigate further.

Problem 9.20: Let $\mathbf{v}$ and $\mathbf{w}$ be nonzero vectors. Show that the graph of the parametric equation
$$\binom{x}{y}=s \mathbf{v}+t \mathbf{w},$$
where both $s$ and $t$ are parameters, is a line if $\mathbf{v}$ is a scalar multiple of $\mathbf{w}$.

319

---

<!-- Page 320 -->

CHAPTER 9. VECTORS IN TWO DIMENSIONS

Solution for Problem 9.20: If $\mathbf{v}=k \mathbf{w}$ for some scalar $k$, then we have
$$\binom{x}{y}=s \mathbf{v}+t \mathbf{w}=k s \mathbf{w}+t \mathbf{w}=(k s+t) \mathbf{w} .$$

The graph of this equation is indeed a line with direction vector $\mathbf{w}$.

Now, let's take a closer look at what happens when $\mathbf{v}$ is not a multiple of $\mathbf{w}$.
Problem 9.21: Let $\mathbf{v}$ and $\mathbf{w}$ be nonzero vectors such that $\mathbf{v}$ is not a scalar multiple of $\mathbf{w}$. In this problem, we show that every point $(x, y)$ is in the graph of the parametric equation $\binom{x}{y}=s \mathbf{v}+t \mathbf{w}$, where $s$ and $t$ are parameters.
(a) What is the graph of $\binom{x}{y}=\mathbf{v}+t \mathbf{w}$ ? (Note that the coefficient of $\mathbf{v}$ is 1 , not $s$.)
(b) What is the graph of $\binom{x}{y}=2 \mathbf{v}+t \mathbf{w}$ ?
(c) How are your graphs in parts (a) and (b) related?
(d) Show that every point $(x, y)$ is in the graph of the parametric equation $\binom{x}{y}=s \mathbf{v}+t \mathbf{w}$, where $s$ and $t$ are parameters.

Solution for Problem 9.21: Let $\mathbf{v}=\binom{v_{1}}{v_{2}}$.
(a) By our definition of a line, the graph is the line through $\left(v_{1}, v_{2}\right)$ in the direction of $\mathbf{w}$.
(b) By our definition of a line, the graph is the line through $\left(2 v_{1}, 2 v_{2}\right)$ in the direction of $\mathbf{w}$.
(c) The direction vectors of the lines in parts (a) and (b) are the same, so we suspect the two graphs do not intersect. The lines intersect at ( $x, y$ ) if there are constants $t_{1}$ and $t_{2}$ such that $\mathbf{v}+t_{1} \mathbf{w}=2 \mathbf{v}+t_{2} \mathbf{w}$. Solving for $\mathbf{v}$ gives $\mathbf{v}=\left(t_{1}-t_{2}\right) \mathbf{w}$. But we are told that $\mathbf{v}$ is not a scalar multiple of $\mathbf{w}$, so this is impossible. Therefore, the lines of parts (a) and (b) do not intersect.
(d) Continuing with our arguments from parts (a) and (b), for each possible value of s, the graph of $\binom{x}{y}=s \mathbf{v}+t \mathbf{w}$ is a line through $\left(s v_{1}, s v_{2}\right)$ with direction vector $\mathbf{w}$. Continuing our reasoning from part (c), we see that all of these lines are parallel. So, the graph of $\binom{x}{y}=s \mathbf{v}+t \mathbf{w}$ is a set of parallel lines. We suspect that any point ( $x_{0}, y_{0}$ ) is on one of these lines, but we have to prove it.

We'll start by developing some geometric intuition for why any ( $x_{0}, y_{0}$ ) must be on one of these parallel lines. At right, point $P$ is ( $x_{0}, y_{0}$ ); line $\ell_{\mathrm{v}}$ is the line through the origin with direction $\mathbf{v}$, and line $\ell_{\mathbf{w}}$ is the line through the origin with direction $\mathbf{w}$. To show that $P$ is on one of the set of parallel lines that is the graph of $\binom{x}{y}=s \mathbf{v}+t \mathbf{w}$, we draw line $\ell_{P}$ through $P$ parallel to $\ell_{\mathbf{w}}$. Since $\mathbf{v}$ is not a constant multiple of $\mathbf{w}$, lines $\ell_{\mathbf{v}}$ and $\ell_{P}$ are not parallel and must therefore intersect at a point we'll call $Q$. Since $Q$ is on $\ell_{\mathbf{v}}$, we have $\vec{Q}=s \mathbf{v}$ for some scalar $s$. Since $\ell_{P} \| \ell_{\mathbf{w}}$, we have $\overrightarrow{Q P}=t \mathbf{w}$ for some scalar $t$. Therefore, $\binom{x}{y}=\vec{P}=s \mathbf{v}+t \mathbf{w}$.

While that gives us some geometric intuition for why ( $x_{0}, y_{0}$ ) must be on one of these parallel lines, we'd like our proof to rest on the same definition of a line that we've been using throughout this section. In

320

---

<!-- Page 321 -->

9.3. LINES AND LINEAR DEPENDENCE

Problem 9.18, we showed that the graph of $\binom{x}{y}=\mathbf{v}+\mathbf{t w}$ is also the graph of the equation
$$w_{2} x-w_{1} y=w_{2} v_{1}-w_{1} v_{2}$$

Note that $(x, y)=\left(v_{1}, v_{2}\right)$ satisfies this equation, which is expected, since $\left(v_{1}, v_{2}\right)$ is on the line. This equation describes the line in part (a). In part (b), we considered the line $\binom{x}{y}=2 \mathbf{v}+t \mathbf{w}$. Again applying the result from Problem 9.18, this parametric equation can also be written as
$$w_{2} x-w_{1} y=w_{2}\left(2 v_{1}\right)-w_{1}\left(2 v_{2}\right)=2\left(w_{2} v_{1}-w_{1} v_{2}\right)$$

Similarly, for any specific value of $s$, the parametric equation $\binom{x}{y}=s \mathbf{v}+t \mathbf{w}$, where $t$ is a parameter and $s$ is fixed, can also be expressed as
$$w_{2} x-w_{1} y=w_{2}\left(s v_{1}\right)-w_{1}\left(s v_{2}\right)=s\left(w_{2} v_{1}-w_{1} v_{2}\right)$$

We wish to show that for any point $\left(x_{0}, y_{0}\right)$, we can choose a value of $s$ such that $\left(x_{0}, y_{0}\right)$ is on graph of Equation (9.9). We know that $\left(x_{0}, y_{0}\right)$ lies on
$$w_{2} x-w_{1} y=w_{2} x_{0}-w_{1} y_{0}$$
since this equation is satisfied by $(x, y)=\left(x_{0}, y_{0}\right)$. So, we choose $s=\frac{w_{2} x_{0}-w_{1} y_{0}}{w_{2} v_{1}-w_{1} v_{2}}$ in Equation (9.9):
$$w_{2} x-w_{1} y=s\left(w_{2} v_{1}-w_{1} v_{2}\right)=\frac{w_{2} x_{0}-w_{1} y_{0}}{w_{2} v_{1}-w_{1} v_{2}}\left(w_{2} v_{1}-w_{1} v_{2}\right)=w_{2} x_{0}-w_{1} y_{0}$$

Therefore, the point ( $x_{0}, y_{0}$ ) is indeed on one of the set of parallel lines described by $\binom{x}{y}=s \mathbf{v}+t \mathbf{w}$. Since this argument holds for any point $\left(x_{0}, y_{0}\right)$, the graph of $\binom{x}{y}=s \mathbf{v}+t \mathbf{w}$ is the entire Cartesian plane.

Our argument appears to show that the graph of $\binom{x}{y}=s \mathbf{v}+t \mathbf{w}$ is the entire Cartesian plane, but in Problem 9.19, we saw that the graph is just a line if $\mathbf{v}$ is a constant multiple of $\mathbf{w}$. So, where does our argument fail if $\mathbf{v}=k \mathbf{w}$ ?

The only step in our argument that might fail is when we let $s=\frac{w_{2} x_{0}-w_{1} y_{0}}{w_{2} v_{1}-w_{1} v_{2}}$. What if the denominator, $w_{2} v_{1}-w_{1} v_{2}$, is 0 ? Then, there's no such $s$. If $\mathbf{v}=k \mathbf{w}$, then $v_{1}=k w_{1}$ and $v_{2}=k w_{2}$, so we find that $w_{2} v_{1}-w_{1} v_{2}=k w_{1} w_{2}-k w_{1} w_{2}=0$. This is why the argument fails when $\mathbf{v}=k \mathbf{w}$. But is this the only case in which $w_{2} v_{1}-w_{1} v_{2}=0$ ?

Fortunately, yes, it is. We write $w_{2} v_{1}-w_{1} v_{2}=0$ as $w_{2} v_{1}=w_{1} v_{2}$. If $w_{1}$ and $w_{2}$ are nonzero, we can write this equation as $\frac{v_{1}}{w_{1}}=\frac{v_{2}}{w_{2}}$. Setting these equal to $k$ gives us $v_{1}=k w_{1}$ and $v_{2}=k w_{2}$, so $\mathbf{v}=k \mathbf{w}$. If $w_{1}$ is 0 , then $w_{2} \neq 0$, since $\mathbf{w} \neq 0$. Then, $w_{2} v_{1}=w_{1} v_{2}$ tells us that $v_{1}=0$ and we again have $\mathbf{v}=k \mathbf{w}$ for some $k$, namely $k=\frac{v_{2}}{w_{2}}$. Similarly, if $w_{2}=0$, we have $\mathbf{v}=\frac{v_{1}}{w_{1}} \mathbf{w}$.

Putting this all together, we see that $w_{2} v_{1}-w_{1} v_{2}=0$ if and only if $\mathbf{v}$ is a multiple of $\mathbf{w}$. Therefore, we have $w_{2} v_{1}-w_{1} v_{2} \neq 0$ if and only if $\mathbf{v}$ is not a multiple of $\mathbf{w}$, and our argument above shows that the graph of $\binom{x}{y}=s \mathbf{v}+t \mathbf{w}$ is the entire Cartesian plane if $w_{2} v_{1}-w_{1} v_{2} \neq 0$. So, the graph is the entire Cartesian plane whenever $\mathbf{v}$ is not a multiple of $\mathbf{w}$.

In the last two problems, we investigated the graph of the parametric equation
$$\binom{x}{y}=s \mathbf{v}+t \mathbf{w},$$

321

---

<!-- Page 322 -->

CHAPTER 9. VECTORS IN TWO DIMENSIONS

where $s$ and $t$ are parameters. We found that the shape of the graph depends on whether or not $\mathbf{v}$ is a multiple of $\mathbf{w}$. This distinction is so important that we have a special name for it. We say that $\mathbf{v}$ and $\mathbf{w}$ are linearly dependent if one is a multiple of the other, and that $\mathbf{v}$ and $\mathbf{w}$ are linearly independent if neither is a multiple of the other.

As we continue our study of vectors, we'll want to expand our definition of "linearly dependent" and "linearly independent" to describe groups of more than 2 vectors. Here's how we do so:

Definition: We say that $\mathbf{v}_{1}, \mathbf{v}_{2}, \ldots, \mathbf{v}_{n}$ are linearly dependent if there are scalars $a_{1}, a_{2}, \ldots, a_{n}$, not all 0 , such that
$$a_{1} \mathbf{v}_{1}+a_{2} \mathbf{v}_{2}+\cdots+a_{n} \mathbf{v}_{n}=\mathbf{0} .$$

If the only scalars that satisfy this equation are $a_{1}=a_{2}=\cdots=a_{n}=0$, then the vectors are linearly independent.
To see why this definition is equivalent to our initial definition of "linearly dependent" when we have only two vectors, suppose that $\mathbf{v}$ and $\mathbf{w}$ are nonzero and linearly dependent by our first definition. Then, we must have $\mathbf{v}=k \mathbf{w}$. Letting $a_{1}=1, a_{2}=-k$ gives us $a_{1} \mathbf{v}+a_{2} \mathbf{w}=\mathbf{0}$, which shows that $\mathbf{v}$ and $\mathbf{w}$ are linearly dependent by our new definition. If we start instead with the fact that $\mathbf{v}$ and $\mathbf{w}$ are nonzero and linearly dependent by our new definition, then there must be scalars $a_{1}$ and $a_{2}$, not both zero, such that $a_{1} \mathbf{v}+a_{2} \mathbf{w}=\mathbf{0}$. We can't have $a_{1}=0$, since this would mean $a_{2} \mathbf{w}=0$, but $\mathbf{w}$ is nonzero and we cannot have $a_{1}=a_{2}=0$. Since $a_{1} \neq 0$, we can solve $a_{1} \mathbf{v}+a_{2} \mathbf{w}=\mathbf{0}$ for $\mathbf{v}$ to find $\mathbf{v}=-\frac{a_{2}}{a_{1}} \mathbf{w}$, which satisfies our first definition of linearly dependent.

We also have to make sure the definitions are equivalent if either vector is $\mathbf{0}$. If $\mathbf{v}=\mathbf{0}$, then $\mathbf{w}=0 \mathbf{v}$, so $\mathbf{v}$ and $\mathbf{w}$ are linearly dependent by our first definition. Also, we have $\mathbf{1} \mathbf{v}+\mathbf{0} \mathbf{w}=\mathbf{0}$ in this case, so the vectors are linearly dependent by our second definition, as well. Similarly, the definitions are equivalent if $\mathbf{w}=\mathbf{0}$.

Therefore, the two definitions given for two vectors being linearly dependent are equivalent.

Important: Two vectors are linearly dependent if and only if one is a multiple of the other.
Otherwise, they are linearly independent.

Exercises
9.3.1 Find an equation of the form $a x+b y=c$ that has the same graph as the parametric equation
$$\binom{x}{y}=\binom{3}{-1}+s\binom{-4}{5}$$
9.3.2 Find a parametric equation of the form $\binom{x}{y}=\mathbf{u}+t \mathbf{v}$ that has the same graph as $3 x-y=4$.
9.3.3 Find all pairs of linearly dependent vectors in the list $\binom{4}{-6},\binom{-9}{6},\binom{12}{8},\binom{-6}{9},\binom{9}{6}$.
9.3.4
(a) Show that if $\mathbf{u}$ and $\mathbf{v}$ are linearly independent, then for each vector $\mathbf{w}$, then there is a unique pair of scalars $a$ and $b$ such that $\mathbf{w}=a \mathbf{u}+b \mathbf{v}$.
(b) Show that if there is more than one pair of scalars $a$ and $b$ such that $a \mathbf{u}+b \mathbf{v}=\mathbf{w}$ for three given vectors $\mathbf{u}$, $\mathbf{v}$, and $\mathbf{w}$, then $\mathbf{u}$ and $\mathbf{v}$ are linearly dependent.

322

---

<!-- Page 323 -->

9.4. PROJECTIONS
9.4 Projections

A vector is normal to a line if it is orthogonal to any vector in the direction of that line. So, for example, $\mathbf{j}$ is normal to the graph of the line $y=3$, the vector $\mathbf{i}+\mathbf{j}$ is normal to the graph of $x+y=7$, and $\mathbf{v}$ is normal to line $\ell$ in the diagram at right.

The projection of a point onto a line is the foot of the perpendicular from the point to the line. So, in the diagram at left, $P$ is the projection of point $A$ onto $k$.

We can extend the concept of projection to vectors. To find the projection of $\mathbf{v}$ onto a nonzero vector $\mathbf{a}$, we draw $\mathbf{v}$ from a point $O$, and then draw a line through $O$ with direction vector $\mathbf{a}$. We then let $P$ be the projection of the head of $\mathbf{v}$ onto this line. We call $\overrightarrow{O P}$ the projection of $\mathbf{v}$ onto $\mathbf{a}$. (Note that $O$ does not have to be
the origin in this definition!) We denote the projection of $\mathbf{v}$ onto $\mathbf{a}$ as $\operatorname{proj}_{\mathbf{a}} \mathbf{v}$, so $\operatorname{proj}_{\mathbf{a}} \mathbf{v}=\overrightarrow{O P}$.

One reason we draw a line in the direction of a rather than just drawing a or a ray in the direction of $\mathbf{a}$ is shown at right. Here, the projection of the head of $\mathbf{v}$ onto the line is on the opposite side of $O$ from $\mathbf{a}$. Even though $\overrightarrow{O P}$ is in the opposite direction from $\mathbf{a}$, we call $\overrightarrow{O P}$ the projection of $\mathbf{v}$ onto $\mathbf{a}$.

Problems
Problem 9.22:
(a) Find a vector that is normal to the graph of $3 x+y=0$.
(b) Find a vector that is normal to the graph of $3 x+y+10=0$.
(c) Let $a, b$, and $c$ be constants such that at least one of $a$ and $b$ is nonzero. Find a vector in terms of $a, b$, and $c$ that is normal the graph of $a x+b y+c=0$.

Problem 9.23:
(a) Show that if $\mathbf{n}$ is normal to line $\ell$, then $k \mathbf{n}$ is normal to line $\ell$ for any constant $k$.
(b) Show that if $\mathbf{n}_{1}$ and $\mathbf{n}_{2}$ are nonzero vectors that are normal to the same line $\ell$, then $\mathbf{n}_{1}$ and $\mathbf{n}_{2}$ are linearly dependent.

Problem 9.24: Let $\mathbf{v}=\binom{3}{4}$.
(a) Find $\operatorname{proj}_{\mathrm{i}} \mathbf{v}$ and $\operatorname{proj}_{\mathrm{j}} \mathbf{v}$.
(b) Find the projection of $\mathbf{v}$ onto $2 \mathbf{i}$.
(c) Find the projection of $\mathbf{v}$ onto $-776 \mathbf{j}$.

Problem 9.25: In this problem, we find the projection of $\mathbf{v}=\binom{4 \sqrt{3}}{4}$ onto the vector $\mathbf{w}=\binom{1}{\sqrt{3}}$. Let $\theta$ be the angle between $\mathbf{v}$ and $\mathbf{w}$, let $O$ be the origin, and let $V$ and $W$ be points such that $\vec{V}=\mathbf{v}$ and $\vec{W}=\mathbf{w}$.
(a) Let $P$ be the foot of the perpendicular from $V$ to $\overleftrightarrow{\mathrm{OW}}$. What is OP in terms of $\|\mathrm{v}\|,\|\mathrm{w}\|$, and $\theta$ ?
(b) Find $\operatorname{proj}_{\mathbf{w}} \mathbf{v}$.

323

---

<!-- Page 324 -->

CHAPTER 9. VECTORS IN TWO DIMENSIONS

Problem 9.26: Find $\operatorname{proj}_{\mathbf{w}} \mathbf{v}$ for any two vectors $\mathbf{v}$ and $\mathbf{w}$ in terms of $\mathbf{v} \cdot \mathbf{w},\|\mathbf{w}\|$, and $\mathbf{w}$.
Problem 9.27: Let $\mathbf{a}=4 \mathbf{i}+3 \mathbf{j}$ and $\mathbf{b}=-\mathbf{i}+3 \mathbf{j}$, and let $\mathbf{p}=\operatorname{proj}_{\mathbf{b}} \mathbf{a}$.
(a) Find p .
(b) Let $\mathbf{n}=\mathbf{a}-\mathbf{p}$. Find $\mathbf{b} \cdot \mathbf{n}$.
(c) Explain the geometric significance of your result in part (b).

Problem 9.28: The distance between a point and a line is the length of the shortest possible segment from the point to the line.
(a) Why does the distance between a point and a line equal the distance between the point and the projection of the point onto the line?
(b) Find the distance between $(4,-2)$ and the graph of $3 x-2 y-7=0$. Hints: 45,134
(c) Generalize your results in part (b) by finding an expression for the distance between the point ( $x_{0}, y_{0}$ ) and the line $a x+b y+c=0$, where $a, b, c, x_{0}$, and $y_{0}$ are constants.

Problem 9.22:
(a) Find a vector that is normal to the graph of $3 x+y=0$.
(b) Find a vector that is normal to the graph of $3 x+y+10=0$.
(c) Let $a, b$, and $c$ be constants such that at least one of $a$ and $b$ is nonzero. Find a vector in terms of $a, b$, and $c$ that is normal the graph of $a x+b y+c=0$.

Solution for Problem 9.22:
(a) First, we'll get an intuitive understanding what's going on here by using our ideas of "slope" and "perpendicular" from basic algebra. Let the graph of $3 x+y=0$ be line $\ell$. Writing the equation as $y=-3 x$, we see that the line has slope -3 . Therefore, any line perpendicular to $\ell$ has slope $1 / 3$. So, a line through the origin perpendicular to $\ell$ must pass through $(3,1)$. Therefore, one vector that should be normal to $\ell$ is $\binom{3}{1}$.

This isn't an entirely satisfying solution; it completely avoids the question of why the slope of the line perpendicular to $\ell$ is $1 / 3$. Instead of relying on "slope" and "perpendicular," let's use the definition of a normal vector. A normal vector must be orthogonal to any direction vector of the line. So, let's try to find a direction vector of the line. If $\left(x_{1}, y_{1}\right)$ and $\left(x_{2}, y_{2}\right)$ are two different points on the line, then $a$ vector from one to the other, such as $\binom{x_{2}-x_{1}}{y_{2}-y_{1}}$, is in the direction of the line. Since $\left(x_{1}, y_{1}\right)$ and $\left(x_{2}, y_{2}\right)$ are on the line, we have
$$\begin{array}{l}
3 x_{1}+y_{1}=0 \\
3 x_{2}+y_{2}=0
\end{array}$$

Subtracting the first equation from the second, we have $3\left(x_{2}-x_{1}\right)+1\left(y_{2}-y_{1}\right)=0$. Writing the left side as a dot product, out pops the normal vector:
$$\binom{3}{1} \cdot\binom{x_{2}-x_{1}}{y_{2}-y_{1}}=0 .$$

324

---

<!-- Page 325 -->

9.4. PROJECTIONS

This tells us that $\binom{3}{1}$ is orthogonal to any vector between two points in the line, so it is normal to the line. The vector $\binom{3}{1}$ isn't the only vector normal to $\ell$. As we'll investigate in Problem 9.23, any scalar multiple of $\binom{3}{1}$ is also normal to $\ell$, and any vector that is normal to $\ell$ must be a scalar multiple of $\binom{3}{1}$ (including negative multiples and 0 ).
(b) In part (a), the coefficients of $x$ and $y$ gave us components of a vector normal to the line. Maybe that just happens because the line $3 x+y=0$ goes through the origin. If we let $\left(x_{1}, y_{1}\right)$ and $\left(x_{2}, y_{2}\right)$ be points on the line $3 x+y+10=0$, we have
$$\begin{array}{l}
3 x_{1}+y_{1}+10=0 \\
3 x_{2}+y_{2}+10=0
\end{array}$$

Subtracting the first from the last gives us $3\left(x_{2}-x_{1}\right)+1\left(y_{2}-y_{1}\right)=0$, and again we have
$$\binom{3}{1} \cdot\binom{x_{2}-x_{1}}{y_{2}-y_{1}}=0 .$$

So, the vector $\binom{3}{1}$ is orthogonal to any vector between two points on the line, and is therefore normal to the line.
(c) The first two parts give us a guide. We let $\left(x_{1}, y_{1}\right)$ and $\left(x_{2}, y_{2}\right)$ be on the line, so
$$\begin{array}{l}
a x_{1}+b y_{1}+c=0 \\
a x_{2}+b y_{2}+c=0
\end{array}$$

Subtracting the first equation from the second gives $a\left(x_{2}-x_{1}\right)+b\left(y_{2}-y_{1}\right)=0$, so
$$\binom{a}{b} \cdot\binom{x_{2}-x_{1}}{y_{2}-y_{1}}=0,$$
which means that $\binom{a}{b}$ is orthogonal to any vector between two points on the line. Therefore, $\binom{a}{b}$ is normal to the line.

Important: The vector $\binom{a}{b}$ is normal to the graph of $a x+b y+c=0$.
Sidenote: While we'll be working with normal vectors only in the context of lines and planes in this book, you'll be seeing them again in the context of curves and curved surfaces when you study calculus, physics, and other subjects. We say that a vector is normal to a curve at a certain point on the curve if the vector is normal to the line through that point that is tangent to the curve. In three dimensions, a vector that is normal to a surface at a point is normal to the plane through that point that is tangent to the surface.

325

---

<!-- Page 326 -->

CHAPTER 9. VECTORS IN TWO DIMENSIONS

Problem 9.23:
(a) Show that if $\mathbf{n}$ is normal to line $\ell$, then $k \mathbf{n}$ is normal to line $\ell$ for any constant $k$.
(b) Show that if $\mathbf{n}_{1}$ and $\mathbf{n}_{2}$ are nonzero vectors that are normal to the same line $\ell$, then $\mathbf{n}_{1}$ and $\mathbf{n}_{2}$ are linearly dependent.

Solution for Problem 9.23:
(a) Let $\mathbf{d}$ be a direction vector of $\ell$, so $\mathbf{n} \cdot \mathbf{d}=0$. We showed in Problem 9.17 that any vector in the direction of line $\ell$ is of the form $c \mathbf{d}$ for some scalar $c$. For any scalar $k$, we have $(k \mathbf{n}) \cdot(c \mathbf{d})=k c(\mathbf{n} \cdot \mathbf{d})=0$, so the vector $k \mathbf{n}$ is orthogonal to every vector in the direction of $\ell$, which means kn is normal to $\ell$.
(b) We'll first think about the geometry of the problem, and then provide an algebraic proof. We can think of a vector that is normal to $\ell$ as being the direction vector of a line perpendicular to $\ell$. For any point, there is only one line through the point perpendicular to $\ell$, and we showed in Problem 9.17 that any two possible direction vectors of the same line must be linearly dependent. Moreover, all lines perpendicular to $\ell$ are parallel to each other, so any two possible direction vectors of lines normal to $\ell$ are linearly dependent.

To prove algebraically that $\mathbf{n}_{1}$ and $\mathbf{n}_{2}$ are linearly dependent, we will show that it is impossible for them to be linearly independent. We start by noting that if $\mathbf{d}$ is a direction vector of $\ell$, then we have $\mathbf{n}_{1} \cdot \mathbf{d}=0$ and $\mathbf{n}_{2} \cdot \mathbf{d}=0$. If $\mathbf{n}_{1}$ and $\mathbf{n}_{2}$ are linearly independent, the graph of $\binom{x}{y}=s \mathbf{n}_{1}+\boldsymbol{t} \mathbf{n}_{2}$ passes through every point ( $x, y$ ). Specifically, this means that there are some constants $a_{1}$ and $a_{2}$ such that $\mathbf{d}=a_{1} \mathbf{n}_{1}+a_{2} \mathbf{n}_{2}$. Multiplying $\mathbf{n}_{1} \cdot \mathbf{d}=0$ and $\mathbf{n}_{2} \cdot \mathbf{d}=0$ by $a_{1}$ and $a_{2}$, respectively, gives
$$\begin{array}{l}
a_{1} \mathbf{n}_{1} \cdot \mathbf{d}=0 \\
a_{2} \mathbf{n}_{2} \cdot \mathbf{d}=0
\end{array}$$

Adding these gives $a_{1} \mathbf{n}_{1} \cdot \mathbf{d}+a_{2} \mathbf{n}_{2} \cdot \mathbf{d}=0$, so $\left(a_{1} \mathbf{n}_{1}+a_{2} \mathbf{n}_{2}\right) \cdot \mathbf{d}=0$, which means $\mathbf{d} \cdot \mathbf{d}=0$. But we can't have $\mathbf{d} \cdot \mathbf{d}=0$ because $\mathbf{d}$ is nonzero! So, we conclude that $\mathbf{n}_{1}$ and $\mathbf{n}_{2}$ are linearly dependent.

Now that we have a thorough understanding of normal vectors, we turn to projections.
Problem 9.24: Let $\mathbf{v}=\binom{3}{4}$.
(a) Find the projections of $\mathbf{v}$ onto $\mathbf{i}$ and $\mathbf{j}$.
(b) Find the projection of $\mathbf{v}$ onto $2 \mathbf{i}$.
(c) Find the projection of $\mathbf{v}$ onto $-776 \mathbf{j}$.

Solution for Problem 9.24:
(a) To find the projections of $\mathbf{v}$ onto $\mathbf{i}$ and $\mathbf{j}$, we draw $\mathbf{v}$ from the origin to (3,4). When $\mathbf{i}$ is drawn from the origin, it lies along the $x$-axis. Therefore, we project $(3,4)$ onto the $x$-axis to find the projection of $\mathbf{v}$ onto $\mathbf{i}$. As shown in the diagram at right, the projection of ( 3,4 ) onto the $x$-axis is ( 3,0 ), so the desired projection of $\mathbf{v}$ onto $\mathbf{i}$ is $\binom{3}{0}$. Similarly, the projection $(3,4)$ onto the $y$-axis is $(0,4)$, so the projection of $\mathbf{v}$ onto $\mathbf{j}$ is $\binom{0}{4}$.
(b) Just as with $\mathbf{i}$, the vector $2 \mathbf{i}$ lies along the $x$-axis when drawn from the origin. So, the projection of $\mathbf{v}$ onto $2 \mathbf{i}$ is the same as the projection of $\mathbf{v}$ onto $\mathbf{i}$, which is $\binom{3}{0}$.

326

---

<!-- Page 327 -->

9.4. PROJECTIONS

Concept: When $\mathbf{v}$ is projected onto vector $\mathbf{a}$, the magnitude of $\mathbf{a}$ is irrelevant; only its
direction affects the projection.
(c) Only the direction of -776 j affects the projection. When -776 j is drawn from the origin, it lies along the $y$-axis, so the projection of $\mathbf{v}$ onto $-776 \mathbf{j}$ is the same as the projection of $\mathbf{v}$ onto $\mathbf{j}$, which is $\binom{0}{4}$.

Problem 9.25: Find the projection of $\mathbf{v}=\binom{4 \sqrt{3}}{4}$ onto the vector $\mathbf{w}=\binom{1}{\sqrt{3}}$.

Solution for Problem 9.25: First, we draw $\mathbf{v}$ and $\mathbf{w}$ from the origin, and we draw the line $k$ containing $\mathbf{w}$. Then, letting $V$ be the head of $\mathbf{v}$, we project $V$ onto $k$, which gives us point $P$ as shown. Our goal is to find $\vec{P}$. We know the direction of $\vec{P}$, since it is the same as that of $\mathbf{w}$. So, we only have to find the magnitude of $\vec{P}$. We can do so with right triangle $V O P$, where $O$ is the origin. In this triangle, we have $\cos \angle V O P=\frac{O P}{O V}$. But $O V=\|\mathbf{v}\|=8$, so $\cos \angle V O P=\frac{O P}{8}$. If we can find $\cos \angle V O P$, then we can find $O P$. Since $\cos \angle V O P$ is the cosine of an angle between vectors $\mathbf{v}$ and $\mathbf{w}$, this sounds like a job for the dot product.

We have
$$\cos \angle V O P=\frac{\mathbf{v} \cdot \mathbf{w}}{\|\mathbf{v}\|\|\mathbf{w}\|}=\frac{(4 \sqrt{3})(1)+(4)(\sqrt{3})}{(8)(2)}=\frac{\sqrt{3}}{2} .$$

Therefore, we have $O P=8 \cos \angle V O P=4 \sqrt{3}$. Since $\vec{P}$ is a vector in the same direction as $\mathbf{w}$ but with magnitude $4 \sqrt{3}$, we find $\vec{P}$ by multiplying the unit vector in the direction of $\mathbf{w}$ by the magnitude of $\vec{P}$. The unit vector in the direction of $\mathbf{w}$ is $\frac{\mathbf{w}}{\|\mathbf{w}\|}$, so we have
$$\vec{P}=4 \sqrt{3} \cdot \frac{\mathbf{w}}{\|\mathbf{w}\|}=4 \sqrt{3} \cdot \frac{\mathbf{w}}{2}=2 \sqrt{3} \mathbf{w}=\binom{2 \sqrt{3}}{6} .$$

Problem 9.26: Find $\operatorname{proj}_{\mathbf{w}} \mathbf{v}$ for any two vectors $\mathbf{v}$ and $\mathbf{w}$ in terms of $\mathbf{v} \cdot \mathbf{w},\|\mathbf{w}\|$, and $\mathbf{w}$.

Solution for Problem 9.26: Let $\theta$ be the angle between $\mathbf{v}$ and $\mathbf{w}$. We'll handle the cases of acute and obtuse $\theta$ separately, and then address the special cases in which $\theta$ is $0, \frac{\pi}{2}$, or $\pi$. In all cases, we draw $\mathbf{v}$ and $\mathbf{w}$ from a point $O$ to points $V$ and $W$, respectively, and let $\theta$ be the angle between these vectors. We then let $P$ be the projection of $V$ onto line $\overleftrightarrow{\mathrm{OW}}$.

Case 1: $\theta$ is acute. We proceed as in Problem 9.25. We find $\overrightarrow{O P}$ by first finding $\|\overrightarrow{O P}\|$, and then scaling $\mathbf{w}$ by the appropriate factor. From right triangle $V O P$, we have $\|\overrightarrow{O P}\|=O V \cos \angle V O P=\|\mathbf{v}\| \cos \theta$. Since $\theta$ is the angle between $\mathbf{v}$ and $\mathbf{w}$, we have
$$\|\overrightarrow{O P}\|=\|\mathbf{v}\| \cos \theta=\|\mathbf{v}\| \frac{\mathbf{v} \cdot \mathbf{w}}{\|\mathbf{v}\|\|\mathbf{w}\|}=\frac{\mathbf{v} \cdot \mathbf{w}}{\|\mathbf{w}\|} .$$

To find $\overrightarrow{O P}$, we scale the unit vector in the direction of $\mathbf{w}$ by $\|\overrightarrow{O P}\|$. From Problem 9.2, the unit vector in the direction of $\mathbf{w}$ is $\frac{\mathbf{w}}{\|\mathbf{w}\| \text {, so }}$
$$\operatorname{proj}_{\mathbf{w}} \mathbf{v}=\overrightarrow{O P}=\|\overrightarrow{O P}\| \frac{\mathbf{w}}{\|\mathbf{w}\|}=\frac{\mathbf{v} \cdot \mathbf{w}}{\|\mathbf{w}\|^{2}} \mathbf{w} .$$

327

---

<!-- Page 328 -->

CHAPTER 9. VECTORS IN TWO DIMENSIONS

Case 2: $\theta$ is obtuse. We proceed as before, but now $O$ is between $W$ and $P$, as shown. So, $\|\overrightarrow{O P}\|=O V \cos \angle V O P=\|\mathbf{v}\| \cos (\pi-\theta)=-\|\mathbf{v}\| \cos \theta$. We then have
$$\|\overrightarrow{O P}\|=-\|\mathbf{v}\| \cos \theta=-\|\mathbf{v}\| \frac{\mathbf{v} \cdot \mathbf{w}}{\|\mathbf{v}\|\|\mathbf{w}\|}=-\frac{\mathbf{v} \cdot \mathbf{w}}{\|\mathbf{w}\|} .$$

Note that this result is positive, because $\mathbf{v} \cdot \mathbf{w}$ is negative when the angle between $\mathbf{v}$ and $\mathbf{w}$ is obtuse. To find $\overrightarrow{O P}$, we multiply the unit vector in the direction of $\mathbf{w}$ by $-\|\overrightarrow{O P}\|$, where the negative sign accounts for the fact that $\overrightarrow{O P}$ and $\mathbf{w}$ are in opposite directions. We therefore have
$$\operatorname{proj}_{\mathbf{w}} \mathbf{v}=\overrightarrow{O P}=-\|\overrightarrow{O P}\| \frac{\mathbf{w}}{\|\mathbf{w}\|}=\frac{\mathbf{v} \cdot \mathbf{w}}{\|\mathbf{w}\|^{2}} \mathbf{w} .$$

This is the same expression as when $\theta$ is acute.
Case 3: $\theta=0$ or $\theta=\pi$. In this case, we have $\mathbf{v}=k \mathbf{w}$ for some scalar $k$, and we should have $\operatorname{proj}_{\mathbf{w}} \mathbf{v}=\mathbf{v}$, because $\mathbf{v}$ is already in the same (or opposite) direction as $\mathbf{w}$. The expression above for $\operatorname{proj}_{\mathbf{w}} \mathbf{v}$ gives us
$$\frac{\mathbf{v} \cdot \mathbf{w}}{\|\mathbf{w}\|^{2}} \mathbf{w}=\frac{k \mathbf{w} \cdot(\mathbf{w})}{\|\mathbf{w}\|^{2}}\left(\frac{1}{k} \mathbf{v}\right)=\frac{k\|\mathbf{w}\|^{2}}{\|\mathbf{w}\|^{2}}\left(\frac{1}{k} \mathbf{v}\right)=\mathbf{v},$$
as expected.
Case 4: $\theta=\frac{\pi}{2}$. If $\mathbf{v}$ and $\mathbf{w}$ are orthogonal, then $\operatorname{proj}_{\mathbf{w}} \mathbf{v}=\mathbf{0}$, since $P$ will be the same point as $O$. The expression we derived for $\operatorname{proj}_{\mathbf{w}} \mathbf{v}$ in the other cases delivers the correct answer in this case, too, because $\mathbf{v} \cdot \mathbf{w}=0$ when $\mathbf{v}$ and w are orthogonal.

Since we've covered all the possible cases, we have shown that:

We can test this formula for $\operatorname{proj}_{\mathbf{w}} \mathbf{v}$ by confirming our result in Problem 9.25. Letting $\mathbf{v}=\binom{4 \sqrt{3}}{4}$ and $\mathbf{w}=\binom{1}{\sqrt{3}}$, we have
$$\operatorname{proj}_{\mathbf{w}} \mathbf{v}=\frac{\mathbf{v} \cdot \mathbf{w}}{\|\mathbf{w}\|^{2}} \mathbf{w}=\frac{(4 \sqrt{3})(1)+(4)(\sqrt{3})}{2^{2}}\binom{1}{\sqrt{3}}=\binom{2 \sqrt{3}}{6},$$
which matches our answer from earlier.
Problem 9.27: Let $\mathbf{a}=4 \mathbf{i}+3 \mathbf{j}$ and $\mathbf{b}=-\mathbf{i}+3 \mathbf{j}$, and let $\mathbf{p}=\operatorname{proj}_{\mathbf{b}} \mathbf{a}$.
(a) Find $\mathbf{p}$.
(b) Let $\mathbf{n}=\mathbf{a}-\mathbf{p}$. Find $\mathbf{b} \cdot \mathbf{n}$.
(c) Explain the geometric significance of your result in part (b).

Solution for Problem 9.27:
(a) We have $\operatorname{proj}_{\mathbf{b}} \mathbf{a}=\frac{\mathbf{a} \cdot \mathbf{b}}{\|\mathbf{b}\|^{2}} \mathbf{b}=\frac{(4)(-1)+(3)(3)}{\left(\sqrt{(-1)^{2}+3^{2}}\right)^{2}} \mathbf{b}=\frac{1}{2} \mathbf{b}=-\frac{1}{2} \mathbf{i}+\frac{3}{2} \mathbf{j}$.

328

---

<!-- Page 329 -->

9.4. PROJECTIONS
(b) We have $\mathbf{n}=(4 \mathbf{i}+3 \mathbf{j})-\left(-\frac{1}{2} \mathbf{i}+\frac{3}{2} \mathbf{j}\right)=\frac{9}{2} \mathbf{i}+\frac{3}{2} \mathbf{j}$, and
$$\mathbf{n} \cdot \mathbf{b}=\left(\frac{9}{2} \mathbf{i}+\frac{3}{2} \mathbf{j}\right) \cdot(-\mathbf{i}+3 \mathbf{j})=\frac{9}{2} \cdot(-1)+\frac{3}{2} \cdot 3=0 .$$

Therefore, $\mathbf{n}$ is orthogonal to $\mathbf{b}$.
(c) Writing $\mathbf{n}=\mathbf{a}-\mathbf{p}$ as $\mathbf{a}=\mathbf{p}+\mathbf{n}$ tells the story. Suppose we draw $\mathbf{a}$ and $\mathbf{b}$ from the origin. Because $\mathbf{p}$ is the projection of $\mathbf{a}$ onto $\mathbf{b}$, the vector from the head of $\mathbf{p}$ to the head of a must be normal to the line that contains $\mathbf{p}$. If we let this normal vector be $\mathbf{n}$, we must therefore have $\mathbf{a}=\mathbf{p}+\mathbf{n}$ and $\mathbf{n} \cdot \mathbf{p}=0$. Since $\mathbf{b}$ and $\mathbf{p}$ are in the same or opposite directions, we must also have $\mathbf{n} \cdot \mathbf{b}=0$.

Another way to look at this is that $\mathbf{n}$ is the projection of $\mathbf{a}$ onto a vector orthogonal to $\mathbf{b}$. This is depicted in the diagram at right. Therefore, we see that $\mathbf{a}$ is the sum of the projections of $\mathbf{a}$ onto $\mathbf{b}$ and onto a nonzero vector orthogonal to $\mathbf{b}$.

There's nothing special about the particular vectors $\mathbf{a}$ and $\mathbf{b}$ in Problem 9.27. We can make the same observations for any nonzero vectors $\mathbf{a}$ and $\mathbf{b}$.

You'll find a lot more use for projections and for expressing a vector as a sum of two orthogonal vectors when you study physics. We'll finish this section with an application to analytic geometry.

Problem 9.28: The distance between a point and a line is the length of the shortest possible segment from the point to the line.
(a) Why does the distance between a point and a line equal the distance between the point and the projection of the point onto the line?
(b) Find the distance between $(4,-2)$ and the graph of $3 x-2 y-7=0$.
(c) Generalize your results in part (b) by finding an expression for the distance between the point ( $x_{0}, y_{0}$ ) and the line $a x+b y+c=0$, where $a, b, c, x_{0}$, and $y_{0}$ are constants.

Solution for Problem 9.28:
(a) Let $P$ be the point and $\ell$ be the line. Let $B$ be the projection of $P$ onto $\ell$ and let $A$ be any other point on $\ell$. The Pythagorean Theorem then gives us $P B^{2}+A B^{2}=P A^{2}$. Therefore, we have $P A>P B$. So, $P$ is closer to $B$ than to any other point on $\ell$.
(b) Let the point be $P$ and the line be $\ell$. The shortest distance from $P$ to $\ell$ is $P B$, where $B$ is on $\ell$ such that $\overline{P B} \perp \ell$. Unfortunately, it's not clear from our diagram what the coordinates of $B$ are. We could find those coordinates by finding the equation of the line through $P$ perpendicular to $\ell$, and then solving a system of equations. Then, we'd have to use the distance formula, and our diagram makes it obvious that we'll be dealing with a lot of fractions. That looks like a lot of work. Maybe we can find a better way.

Point $B$ is the projection of $P$ onto $\ell$, and the vector from $B$ to $P$ is normal to $\ell$. We know the direction of this vector! From our work in Problem 9.22, we know that $3 \mathbf{i}-2 \mathbf{j}$ is normal to the graph of $3 x-2 y-7=0$. However, we don't know the magnitude of $\overrightarrow{B P}$ because we don't know exactly where $B$ is. If only point $B$ were a convenient point, then this problem would be a lot easier.

Let's take a look at a convenient point on $\ell$, such as $(5,4)$, which we'll call point $A$. This point is on $\ell$ because $(x, y)=(5,4)$ satisfies $3 x-2 y-7=0$. How is this convenient point related to the desired point?

329

---

<!-- Page 330 -->

CHAPTER 9. VECTORS IN TWO DIMENSIONS

Triangle $P A B$ is a right triangle. Therefore, not only is $B$ the projection of $P$ onto $\overleftrightarrow{A B}$, but $B$ is also the projection of $A$ onto $\overleftrightarrow{B P}$. Aha! We know the direction of $\overleftrightarrow{B P}$-the vector normal to $\ell$ is in this direction. So, we can find $\|\overrightarrow{B P}\|$ by projecting $\overrightarrow{A P}$ onto the normal vector!

In the diagram, we have drawn the vector $\mathbf{n}$ from $A$ normal to $\ell$, so $\mathbf{n}=3 \mathbf{i}-2 \mathbf{j}$. The projection of $\overrightarrow{A P}$ onto this vector, $\overrightarrow{A D}$, has magnitude equal to $B P$, since $B P D A$ is a rectangle. We have $\overrightarrow{A P}=\vec{P}-\vec{A}= (4 \mathbf{i}-2 \mathbf{j})-(5 \mathbf{i}+4 \mathbf{j})=-\mathbf{i}-6 \mathbf{j}$, and we're ready to find the desired distance:
$$B P=\left\|\frac{\overrightarrow{A P} \cdot \mathbf{n}}{\|\mathbf{n}\|^{2}} \mathbf{n}\right\|=\left|\frac{\overrightarrow{A P} \cdot \mathbf{n}}{\|\mathbf{n}\|^{2}}\right|\|\mathbf{n}\|=\left|\frac{(-1)(3)+(-6)(-2)}{\left(\sqrt{3^{2}+(-2)^{2}}\right)^{2}}\right|\|\mathbf{n}\|=\frac{9}{13} \sqrt{13} .$$
(c) We use the previous part as a guide. Let $P$ be ( $x_{0}, y_{0}$ ) and let $A$ be a point ( $x, y$ ) on the graph of $a x+b y+c=0$. The vector normal to the graph is $\mathbf{n}=a \mathbf{i}+b \mathbf{j}$, and we seek the magnitude of the projection of $\overrightarrow{A P}$ onto $\mathbf{n}$. We have $\overrightarrow{A P}=\left(x_{0}-x\right) \mathbf{i}+\left(y_{0}-y\right) \mathbf{j}$, so the desired distance is
$$\left\|\frac{\overrightarrow{A P} \cdot \mathbf{n}}{\|\mathbf{n}\|^{2}} \mathbf{n}\right\|=\left|\frac{\left(\left(x_{0}-x\right) \mathbf{i}+\left(y_{0}-y\right) \mathbf{j}\right) \cdot(a \mathbf{i}+b \mathbf{j})}{\|\mathbf{n}\|^{2}}\right|\|\mathbf{n}\|=\left|\frac{\left(x_{0}-x\right) a+\left(y_{0}-y\right) b}{\|\mathbf{n}\|^{2}}\right|\|\mathbf{n}\|=\frac{\left|a x_{0}+b y_{0}-a x-b y\right|}{\sqrt{a^{2}+b^{2}}} .$$

Since $(x, y)$ is on the graph of $a x+b y+c=0$, we have $-a x-b y=c$, so our desired formula for the distance between $\left(x_{0}, y_{0}\right)$ and $a x+b y+c=0$ is
$$\frac{\left|a x_{0}+b y_{0}+c\right|}{\sqrt{a^{2}+b^{2}}} .$$

Important: The distance between the point $\left(x_{0}, y_{0}\right)$ and the graph of $a x+b y+c=0$ is
D
$$\frac{\left|a x_{0}+b y_{0}+c\right|}{\sqrt{a^{2}+b^{2}}} .$$

As one quick check, we can note that if ( $x_{0}, y_{0}$ ) is on the graph of $a x+b y+c=0$, then $a x_{0}+b y_{0}+c=0$, and our formula for the distance between ( $x_{0}, y_{0}$ ) and the line correctly gives 0 .

WARNING!!
Note that when using the formula
$$\frac{\left|a x_{0}+b y_{0}+c\right|}{\sqrt{a^{2}+b^{2}}}$$
to find the distance between ( $x_{0}, y_{0}$ ) and $a x+b y+c=0$, all of the terms in the equation for the line are on the same side. If we have an equation such as $2 x+5 y=8$, then we do not have $a=2, b=5$ and $c=8$. We move the 8 to the other side and have $2 x+5 y-8=0$, so $a=2, b=5$, and $c=-8$.

Excrdises
9.4.1 Find proj $_{\mathbf{v}} \mathbf{u}$ for each of the following:
(a) $\mathbf{u}=\binom{2}{0}, \mathbf{v}=\binom{3}{4}$
(b) $\mathbf{u}=\binom{-3}{1}, \mathbf{v}=\binom{2}{-2}$

330

---

<!-- Page 331 -->

9.5. SUMMARY
9.4.2 Suppose $\operatorname{proj}_{\mathbf{v}} \mathbf{u}=9 \mathbf{i}-3 \mathbf{j}$.
(a) If $\mathbf{w}=3 \mathbf{v}$, then what is $\operatorname{proj}_{\mathbf{w}} \mathbf{u}$ ?
(b) If $\mathbf{x}=3 \mathbf{u}$, then what is $\operatorname{proj}_{\mathbf{v}} \mathbf{x}$ ?
9.4.3
(a) Find an equation of the form $a x+b y+c=0$ whose graph is a line through $(3,4)$ such that $5 \mathbf{i}-3 \mathbf{j}$ is normal to the line.
(b) Find a vector with magnitude 5 that is normal to the graph of $2 x+4 y=7$.
9.4.4 Show that if $\operatorname{proj}_{\mathbf{x}} \mathbf{u}=\operatorname{proj}_{\mathbf{x}} \mathbf{v}$ for all vectors $\mathbf{x}$, then $\mathbf{u}=\mathbf{v}$.
9.4.5 Let $\mathbf{v}$ be a nonzero vector.
(a) If $\operatorname{proj}_{\mathbf{v}} \mathbf{w}=\operatorname{proj}_{\mathbf{v}}(-\mathbf{w})$, then must $\mathbf{w}=\mathbf{0}$ ?
(b) If $\operatorname{proj}_{\mathbf{v}} \mathbf{w}=\operatorname{proj}_{(-\mathbf{v})} \mathbf{w}$, then must $\mathbf{w}=\mathbf{0}$ ?
9.4.6 Let $\mathbf{u}$ be the unit vector $x \mathbf{i}+y \mathbf{j}$, and let $\mathbf{u}^{\perp}=-y \mathbf{i}+x \mathbf{j}$.
(a) Find the angle between $\mathbf{u}$ and $\mathbf{u}^{\perp}$.
(b) Show that for any vector $\mathbf{a}$, we have $\mathbf{a}=\operatorname{proj}_{\mathbf{u}} \mathbf{a}+\operatorname{proj}_{\mathbf{u}^{1}} \mathbf{a}$. Explain the result both geometrically and algebraically.
(c) Show that $\|\mathbf{a}\|^{2}=(\mathbf{a} \cdot \mathbf{u})^{2}+\left(\mathbf{a} \cdot \mathbf{u}^{\perp}\right)^{2}$.
9.4.7 Let $\theta$ be the angle between $\mathbf{u}$ and $\mathbf{v}$, where $\mathbf{u} \cdot \mathbf{v} \neq 0$. Find
$$\frac{\mathbf{u} \cdot \mathbf{v}}{\left(\operatorname{proj}_{\mathbf{v}} \mathbf{u}\right) \cdot\left(\operatorname{proj}_{\mathbf{u}} \mathbf{v}\right)}$$
in terms of $\theta$.
9.5 Summary

A vector in two dimensions is an ordered pair of numbers, which we can denote as $\binom{x}{y}$. The numbers $x$ and $y$ are called components of the vector. We often refer to real numbers as scalars when speaking of vectors. The sum of of two vectors is given by $\binom{a}{b}+\binom{c}{d}=\binom{a+c}{b+d}$, and the product of a scalar and a vector is given by $k\binom{a}{b}=\binom{k a}{k b}$.

We denote the vector from the origin to a point $C$ as $\vec{C}$. We refer to the vector from point $A$ to point $\vec{B}$ as $\overrightarrow{A B}$, and we have $\overrightarrow{A B}=\vec{B}-\vec{A}$.

A vector with magnitude 1 is called a unit vector. The vector $\binom{x}{y}$ can also be written as $x \mathbf{i}+y \mathbf{j}$, where $\mathbf{i}$ is the unit vector $\binom{1}{0}$ and $\mathbf{j}$ is the unit vector $\binom{0}{1}$. The zero vector, which is written as $\mathbf{0}$, is the vector in which both components are zero. We use the symbol $\mathbb{R}^{2}$ for the set of all vectors in two dimensions.

The norm of a vector $\mathbf{v}=\binom{x}{y}$ is $\|\mathbf{v}\|=\sqrt{x^{2}+y^{2}}$. The norm of a vector is also called the magnitude or length of the vector, since it measures the length of the geometric representation of the vector.

331

---

<!-- Page 332 -->

CHAPTER 9. VECTORS IN TWO DIMENSIONS

We define the dot product $\mathbf{v} \cdot \mathbf{w}$ as $\binom{v_{1}}{v_{2}} \cdot\binom{w_{1}}{w_{2}}=v_{1} w_{1}+v_{2} w_{2}$. The dot product has the following properties:
- $\mathbf{u} \cdot \mathbf{v}=\mathbf{v} \cdot \mathbf{u}$
- $\mathbf{u} \cdot(a \mathbf{v})=a(\mathbf{u} \cdot \mathbf{v})$
- $\mathbf{u} \cdot(\mathbf{v}+\mathbf{w})=\mathbf{u} \cdot \mathbf{v}+\mathbf{u} \cdot \mathbf{w}$
- $\mathbf{v} \cdot \mathbf{v}=\|\mathbf{v}\|^{2}$
- $\mathbf{v} \cdot \mathbf{w}=\|\mathbf{v}\|\|\mathbf{w}\| \cos \theta$, where $\theta$ is the angle between $\mathbf{v}$ and $\mathbf{w}$

We say that a function $f$ with domain $\mathbb{R}^{2}$ is a linear function if $f(a \mathbf{v})=a f(\mathbf{v})$ for all scalars $a$ and vectors $\mathbf{v}$, and $f(\mathbf{v}+\mathbf{w})=f(\mathbf{v})+f(\mathbf{w})$ for all vectors $\mathbf{v}$ and $\mathbf{w}$.

If $\mathbf{u}$ and $\mathbf{v}$ are vectors with $\mathbf{v} \neq \mathbf{0}$, then the graph of the parametric equation $\binom{x}{y}=\mathbf{u}+t \mathbf{v}$, is a line.

Definition: We say that $\mathbf{v}_{1}, \mathbf{v}_{2}, \ldots, \mathbf{v}_{n}$ are linearly dependent if there are scalars $a_{1}, a_{2}, \ldots, a_{n}$, not all 0 , such that
$$a_{1} \mathbf{v}_{1}+a_{2} \mathbf{v}_{2}+\cdots+a_{n} \mathbf{v}_{n}=\mathbf{0} .$$

If the only scalars that satisfy this equation are $a_{1}=a_{2}=\cdots=a_{n}=0$, then the vectors are linearly independent.

\begin{tabular}{|ll|}
\hline Important: & Two vectors are linearly dependent if and only if one is a multiple of the other. \\
\hline
\end{tabular}

A vector is normal to a line if it is orthogonal to any vector in the direction of that line. The vector $\binom{a}{b}$ is normal to the graph of $a x+b y+c=0$.

The projection of a point onto a line is the foot of the perpendicular from the point to the line. To find the projection of $\mathbf{v}$ onto a nonzero vector $\mathbf{a}$, we draw $\mathbf{v}$ from a point $O$, and then draw a line through $O$ with direction vector $\mathbf{a}$. We then let $P$ be the projection of the head of $\mathbf{v}$ onto this line. We call $\overrightarrow{O P}$ the projection of
$\mathbf{v}$ onto $\mathbf{a}$. (Note that $O$ does not have to be the origin in this definition!) We denote the projection of $\mathbf{v}$ onto $\mathbf{a}$ as $\operatorname{proj}_{\mathbf{a}} \mathbf{v}$, so $\operatorname{proj}_{\mathbf{a}} \mathbf{v}=\overrightarrow{O P}$.

\begin{tabular}{|c|}
\hline Important: For any vector $\mathbf{v}$ and any nonzero vector $\mathbf{w}$, we have \\
$\operatorname{proj}_{\mathbf{w}} \mathbf{v}=\frac{\mathbf{v} \cdot \mathbf{w}}{\|\mathbf{w}\|^{2}} \mathbf{w}$
\end{tabular}

332

---

<!-- Page 333 -->

REVIEW PROBLEMS

Important: The distance between the point ( $x_{0}, y_{0}$ ) and the graph of $a x+b y+c=0$ is
$$\frac{\left|a x_{0}+b y_{0}+c\right|}{\sqrt{a^{2}+b^{2}}}$$

REVIEW PROBLEMS
9.29 Evaluate $\left\|\binom{-6}{2}\right\|$ and $\|15 \mathbf{i}-8 \mathbf{j}\|$.
9.30 Find $k$ such that $4 \mathbf{i}-5 \mathbf{j}$ and $-3 \mathbf{i}+k \mathbf{j}$ are linearly dependent.
9.31 Find a vector $\mathbf{v}$ such that $\|\mathbf{v}\|=10$ and $\mathbf{v}$ is in the same direction as $4 \mathbf{i}-6 \mathbf{j}$.
9.32 Let $A, B$, and $C$ be points in the Cartesian plane. Find all possible values of $\overrightarrow{A B}+\overrightarrow{B C}+\overrightarrow{C A}$.
9.33 Points $A, B$, and $C$ are in the Cartesian plane such that $\vec{C}=\frac{1}{2}(\vec{A}+\vec{B})$. How are $A, B$, and $C$ related geometrically?
9.34 Show that $\|\mathbf{v}\|+\|\mathbf{w}\| \geq\|\mathbf{v}+\mathbf{w}\|$. What geometric result is this known as?
9.35 Evaluate each of the following
(a) $(3 \mathbf{i}-2 \mathbf{j}) \cdot 8 \mathbf{i}$
(b) $\quad\binom{-2}{5} \cdot\binom{-4}{3}$
9.36 How are $\mathbf{u} \cdot \mathbf{v},\|\mathbf{u}\|$, and $\|\mathbf{v}\|$ related if $\mathbf{u}$ and $\mathbf{v}$ have the same direction? What if they have opposite directions?
9.37
(a) Suppose $\mathbf{a}$ is a nonzero vector and $\mathbf{b}$ and $\mathbf{c}$ are vectors such that $\mathbf{a} \cdot \mathbf{b}=\mathbf{a} \cdot \mathbf{c}=0$. Must $\mathbf{b}$ and $\mathbf{c}$ be linearly dependent?
(b) Suppose $\mathbf{a}, \mathbf{b}$, and $\mathbf{c}$ are nonzero vectors such that $\mathbf{a} \cdot \mathbf{b}=0$ and $\mathbf{a} \cdot \mathbf{c} \neq 0$. Must $\mathbf{b}$ and $\mathbf{c}$ be linearly independent?
9.38 Let $\mathbf{u}=3 \mathbf{i}+2 \mathbf{j}$. Suppose each vector $\mathbf{v}$ such that $\mathbf{u} \cdot \mathbf{v}=9$ is drawn from the origin in the Cartesian plane. How are the heads of all these vectors related?
9.39 Show that $\|\mathbf{v}+\mathbf{w}\|=\|\mathbf{v}-\mathbf{w}\|$ if and only if $\mathbf{v}$ and $\mathbf{w}$ are orthogonal.
9.40
(a) If two vectors have the same direction, but different magnitudes, then must one vector be a scalar multiple of the other?
(b) If one vector is a scalar multiple of the other, then must they have the same direction?
9.41 If $\mathbf{u} \cdot \mathbf{v}$ is nonzero, can we tell just from this dot product whether the angle between $\mathbf{u}$ and $\mathbf{v}$ is acute or obtuse?
9.42 Find proj $_{\mathbf{u}} \mathbf{v}$ for each of the following:
(a) $\quad \mathbf{u}=\binom{3}{5}, \mathbf{v}=\binom{0}{-3}$
(b) $\quad \mathbf{u}=\binom{5}{7}, \mathbf{v}=\binom{2}{-4}$
9.43 If proj $_{\mathbf{v}} \mathbf{u}=\mathbf{u}$, then must $\mathbf{u}$ and $\mathbf{v}$ be linearly dependent?

333

---

<!-- Page 334 -->

CHAPTER 9. VECTORS IN TWO DIMENSIONS
9.44 Find both an algebraic and a geometric proof that $\left\|\operatorname{proj}_{\mathbf{b}} \mathbf{a}\right\| \leq\|\mathbf{a}\|$.

Challenge Problems
9.45 Prove that any three vectors $\mathbf{u}, \mathbf{v}$, and $\mathbf{w}$ are linearly dependent.
9.46 How many vectors in two dimensions have one component equal to 2 and have magnitude 6? How are these vectors related geometrically?
9.47 Suppose that $\mathbf{u} \cdot \mathbf{v}=2$ and $\mathbf{v} \cdot \mathbf{w}=-3$. What are the possible values of $\mathbf{u} \cdot \mathbf{w}$ ?
9.48 Suppose $\mathbf{a}=3 \mathbf{i}-\mathbf{j}$. Hints: 98
(a) Explain why more than one vector $\mathbf{b}$ satisfies $\operatorname{proj}_{\mathbf{a}} \mathbf{b}=6 \mathbf{i}-2 \mathbf{j}$. Find two such vectors.
(b) Suppose we also know that $\|\mathbf{b}\|=10$. Then, how many different vectors $\mathbf{b}$ satisfy proj $_{\mathbf{a}} \mathbf{b}=6 \mathbf{i}-2 \mathbf{j}$ ?
(c) Suppose that $\operatorname{proj}_{\mathbf{j}} \mathbf{b}=-\mathbf{j}$. Then, how many different vectors $\mathbf{b}$ satisfy $\operatorname{proj}_{\mathbf{a}} \mathbf{b}=6 \mathbf{i}-2 \mathbf{j}$ ?
9.49 Show that if $\mathbf{u}$ and $\mathbf{v}$ are linearly independent, then the values of proj $_{\mathbf{u}} \mathbf{r}$ and proj $\mathbf{v}_{\mathbf{v}} \mathbf{r}$ uniquely determine $\mathbf{r}$. In other words, if we are given values for $\operatorname{proj}_{\mathbf{u}} \mathbf{r}$ and $\operatorname{proj}_{\mathbf{v}} \mathbf{r}$, then there is always only one possible vector $\mathbf{r}$ that produces the given values of $\operatorname{proj}_{\mathbf{u}} \mathbf{r}$ and $\operatorname{proj}_{\mathbf{v}} \mathbf{r}$. Hints: 97
9.50 If $\mathbf{u}, \mathbf{v}$, and $\mathbf{w}$ are nonzero vectors such that $\mathbf{u}=\operatorname{proj}_{\mathbf{v}} \mathbf{u}+\operatorname{proj}_{\mathbf{w}} \mathbf{u}$, then must we have $\mathbf{v} \cdot \mathbf{w}=0$ ? Hints: 46
$9.51 \star$ Find the pair of equations whose graphs are the two lines that bisect the angles formed by the graphs of the lines $4 x-3 y=5$ and $x-2 y+7=0$. Hints: 220

334

---

