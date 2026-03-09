# Chapter 13: Vector Geometry

<!-- Page 463 -->

There ain't no rules around here! We're trying to accomplish something! - Thomas Edison

CHAPTER 13

Vector Geometry
13.1 Introduction

Most of our applications of vectors to geometry start from basic principles that we have already studied. We'll start this section with a reminder of these basics, and a reminder of some of the notation we use when applying vectors to a geometry problems. All of the following relationships apply both to vectors in two dimensions and to vectors in three dimensions.

We depict the vector from a point $O$ to a point $V$ as $\overrightarrow{O V}$. When $O$ is the origin, we can express this simply as $\vec{V}$.
We add two vectors using "head-to-tail addition," an example of which is shown at right. Point $O$ is the origin, and we find the vector sum $\vec{V}+\vec{W}$ by drawing a copy of $\vec{W}$ starting at point $V$, thereby producing $\overrightarrow{V P}$ in the diagram. Since $\overrightarrow{V P}=\vec{W}$, quadrilateral $O V P W$ is a parallelogram, and we have $\vec{P}=\vec{V}+\vec{W}$.

At left we have a picture of vector subtraction. As explained on page 305, the vector from $V$ to $W$ is $V \vec{W}$, where we have
$$\overrightarrow{V W}=\vec{W}-\vec{V} .$$

Since $\vec{W}$ and $\vec{V}$ are vectors from the origin, the relationship $\overrightarrow{V W}=\vec{W}-\vec{V}$ gives us a convenient way to express any vector in terms of vectors from the origin.

The last two basic tools we'll use a great deal in this chapter are magnitude and the dot product. The magnitude of $V \vec{W}$ is the length of $\overline{V W}$, so we have
$$\|\vec{W}\|=V W .$$

463

---

<!-- Page 464 -->

CHAPTER 13. VECTOR GEOMETRY

The dot product of two vectors is the product of the magnitudes of the two vectors and the cosine of the angle between them. So, if $\theta$ is the angle between vectors $\vec{V}$ and $\vec{W}$, then we have
$$\vec{V} \cdot \vec{W}=\vec{W} \cdot \vec{V}=\|\vec{V}\|\|\vec{W}\| \cos \theta .$$

Now, let's get to the problems!
Problems

Problem 13.1: Show that for any three points $A, B$, and $C$, we have $\overrightarrow{A B}-\overrightarrow{A C}=\overrightarrow{C B}$.
Problem 13.2: Show that for any distinct points $A, B, C$, and $D$, we have $\vec{A}+\vec{C}=\vec{B}+\vec{D}$ if and only if $A B C D$ is a parallelogram.

Problem 13.3:
(a) Let $M$ be the midpoint of $\overline{A B}$. Find $\vec{M}$ in terms of $\vec{A}$ and $\vec{B}$.
(b) Let $k$ be a real number, and let $T$ be on $\overline{A B}$ such that $\frac{A T}{B T}=k$. Find $\vec{T}$ in terms of $\vec{A}, \vec{B}$, and $k$.

Problem 13.4:
(a) Geometrically speaking, what does $\vec{A} \cdot \vec{A}$ equal?
(b) Express $A B^{2}$ in terms of $\vec{A} \cdot \vec{A}, \vec{A} \cdot \vec{B}$, and $\vec{B} \cdot \vec{B}$. What trigonometric relationship is this known as?

Problem 13.5:
(a) Use the dot product to write an equation in terms of $\vec{A}, \vec{B}, \vec{C}$, and $\vec{D}$ that is true if and only if $\overleftrightarrow{A B} \perp \overleftrightarrow{C D}$.
(b) Use vectors to show that each median of an equilateral triangle is also an altitude of the triangle.
(c) Use vectors to show that if each median of a triangle is also an altitude of the triangle, then the triangle is equilateral.

Problem 13.6:
(a) Show that if $A, B, C$, and $D$ are points in space such that $A B^{2}+C D^{2}=B C^{2}+A D^{2}$, then $\overrightarrow{A C}$ and $\overrightarrow{B D}$ are orthogonal.
(b) Look back at Problem 8.17 on page 274. How is part (a) a more general result than the problem we solved in Problem 8.17? What sorts of problems can we consider with vectors that we cannot tackle with complex numbers?

Problem 13.1: Show that for any three points $A, B$, and $C$, we have $\overrightarrow{A B}-\overrightarrow{A C}=\overrightarrow{C B}$.

Solution for Problem 13.1: We tackle this problem by expressing each vector in terms of vectors from the origin, which will allow us to cancel the appearances of $A$ on the left side. But we have to be careful:

WARNING!! We have $\overrightarrow{A B}=\vec{B}-\vec{A}$, not $\overrightarrow{A B}=\vec{A}-\vec{B}$.

464

---

<!-- Page 465 -->

13.1. INTRODUCTION

So, we have
$$\begin{array}{l}
\overrightarrow{A B}=\vec{B}-\vec{A}, \\
\overrightarrow{A C}=\vec{C}-\vec{A} .
\end{array}$$

Subtracting the second equation from the first gives
$$\overrightarrow{A B}-\overrightarrow{A C}=(\vec{B}-\vec{A})-(\vec{C}-\vec{A})=\vec{B}-\vec{C}=\overrightarrow{C B} .$$

Problem 13.2: Show that for any distinct points $A, B, C$, and $D$, we have $\vec{A}+\vec{C}=\vec{B}+\vec{D}$ if and only if $A B C D$ is a parallelogram.

Solution for Problem 13.2: We have an "if and only if" problem, so we really have two problems. First, we show that if $\vec{A}+\vec{C}=\vec{B}+\vec{D}$, then $A B C D$ is a parallelogram. We can rearrange the equation as $\vec{B}-\vec{A}=\vec{C}-\vec{D}$, so $\overrightarrow{A B}=\overrightarrow{D C}$. This tells us that $\overline{A B} \| \overline{D C}$ and that $A B=D C$, so $A, B, C$, and $D$ are vertices of a parallelogram. We know that this parallelogram
is $A B C D$, not $B A C D$, because $\overrightarrow{A B}=\overrightarrow{D C}$ tells us that going from $A$ to $B$ is the same direction as going from $D$ to $C$.

Conversely, if $A B C D$ is a parallelogram, we have $\overrightarrow{D C}=\overrightarrow{A B}$, so $\vec{C}-\vec{D}=\vec{B}-\vec{A}$. Adding $\vec{A}$ and $\vec{D}$ to both sides gives $\vec{A}+\vec{C}=\vec{B}+\vec{D}$.

Notice that nothing in our solution to Problem 13.2 assumes that points $A, B, C$ and $D$ are in the same plane. This means our proof above holds in three dimensions as well as in two dimensions. In other words, it shows that for any points $A, B, C$, and $D$ in space, we have $\vec{A}+\vec{C}=\vec{B}+\vec{D}$ if and only if $A B C D$ is a parallelogram. It follows that if $\vec{A}+\vec{C}=\vec{B}+\vec{D}$, then $A, B, C$, and $D$ are coplanar (meaning they are all in the same plane).

Problem 13.3:
(a) Let $M$ be the midpoint of $\overline{A B}$. Find $\vec{M}$ in terms of $\vec{A}$ and $\vec{B}$.
(b) Let $k$ be a real number, and let $T$ be on $\overline{A B}$ such that $\frac{A T}{B T}=k$. Find $\vec{T}$ in terms of $\vec{A}, \vec{B}$, and $k$.

Solution for Problem 13.3:
(a) A natural guess is that $\vec{M}$ is the average of $\vec{A}$ and $\vec{B}$. To see that this guess is correct, let $O$ be the origin, and let $C$ be the point such that $\vec{C}=\vec{A}+\vec{B}$. Then, $O A C B$ is a parallelogram. The diagonals of a parallelogram bisect each other, so the midpoint of $\overline{O C}$ is the midpoint of $\overline{A B}$. Therefore, point $M$ is on $\overline{O C}$ such that $O M=\frac{O C}{2}$. This
means that $\vec{M}$ has the same direction as $\vec{C}$ but half the magnitude. Therefore, we have
$$\vec{M}=\frac{\vec{C}}{2}=\frac{\vec{A}+\vec{B}}{2} .$$
Important: If $M$ is the midpoint of $\overline{A B}$, then $\vec{M}=(\vec{A}+\vec{B}) / 2$.
Another way we could have proved this is to note that if $M$ is the midpoint of $\overline{A B}$, then $\overrightarrow{A M}$ and $\overrightarrow{B M}$ are equal in magnitude, but in opposite directions. We therefore have $\overrightarrow{A M}=-\overrightarrow{B M}$. Since we also have

465

---

<!-- Page 466 -->

CHAPTER 13. VECTOR GEOMETRY

$\overrightarrow{A M}=\vec{M}-\vec{A}$ and $\overrightarrow{B M}=\vec{M}-\vec{B}$, we must have
$$\vec{M}-\vec{A}=-(\vec{M}-\vec{B}) .$$

Solving for $\vec{M}$ gives $\vec{M}=(\vec{A}+\vec{B}) / 2$, as before.
(b) Our second solution to part (a) gives us a pretty good guide to solving this part. Since $T$ is on $\overline{A B}$ such that $A T / B T=k$, we must have $\overrightarrow{T A}=k(\overrightarrow{B T})$. Notice that we are careful to make sure the two vectors in this equation are pointing in the same direction. Writing $\overrightarrow{T A}$ as $\vec{A}-\vec{T}$
and $\overrightarrow{B T}$ as $\vec{T}-\vec{B}$, we have
$$\vec{A}-\vec{T}=k(\vec{T}-\vec{B}) .$$

Solving for $\vec{T}$ gives
$$\vec{T}=\frac{\vec{A}+k \vec{B}}{1+k} .$$

One way to think about the relationship among $\vec{T}, \vec{A}$, and $\vec{B}$ is that $\vec{T}$ is the weighted average of $\vec{A}$ and $\vec{B}$. This becomes an even more natural way to think about the relationship if we let $a=A T$, and $b=B T$, so $A T / B T=a / b$ and we have
$$\vec{T}=\frac{\vec{A}+\frac{a}{b} \vec{B}}{1+\frac{a}{b}}=\frac{b \vec{A}+a \vec{B}}{b+a}$$

It may seem a bit counterintuitive that we weight $\vec{A}$ by the length of $\overline{B T}$ rather than the length of $\overline{A T}$. To get a sense for why this weighting is correct, note that if $T$ is much closer to $A$ than to $B$, then $B T$ is much larger than $A T$, so $\frac{b}{b+a}$ is close to 1 and $\frac{a}{b+a}$ is close to 0 . This makes $\vec{T}$ close to $\vec{A}$ in our expression above, which is as expected when $T$ is much closer to $A$ than to $B$.

Problem 13.4:
(a) Geometrically speaking, what does $\vec{A} \cdot \vec{A}$ equal?
(b) Express $A B^{2}$ in terms of $\vec{A} \cdot \vec{A}, \vec{A} \cdot \vec{B}$, and $\vec{B} \cdot \vec{B}$. What trigonometric relationship is this known as?

Solution for Problem 13.4:
(a) Since $\vec{A} \cdot \vec{A}=\|\vec{A}\|^{2}$, the expression $\vec{A} \cdot \vec{A}$ equals the square of the distance from $A$ to the origin.
(b) Just as $\vec{A} \cdot \vec{A}$ is the square of the distance from $A$ to the origin, the expression $\overrightarrow{A B} \cdot \overrightarrow{A B}$ equals the square of the distance from $A$ to $B$. Therefore, we have
$$A B^{2}=\overrightarrow{A B} \cdot \overrightarrow{A B}=(\vec{B}-\vec{A}) \cdot(\vec{B}-\vec{A})=\vec{B} \cdot \vec{B}-\vec{B} \cdot \vec{A}-\vec{A} \cdot \vec{B}+\vec{A} \cdot \vec{A} .$$

Since $\vec{A} \cdot \vec{B}=\vec{B} \cdot \vec{A}$, we have
$$A B^{2}=\vec{A} \cdot \vec{A}+\vec{B} \cdot \vec{B}-2 \vec{A} \cdot \vec{B} .$$

Letting $O$ be the origin, so that $\|\vec{A}\|=O A,\|\vec{B}\|=O B$, and $\angle A O B$ equals the angle between $\vec{A}$ and $\vec{B}$, we recognize the equation above as the Law of Cosines:
$$A B^{2}=O A^{2}+O B^{2}-2(O A)(O B) \cos \angle A O B .$$

466

---

<!-- Page 467 -->

13.1. INTRODUCTION

Problem 13.5:
(a) Use the dot product to write an equation in terms of $\vec{A}, \vec{B}, \vec{C}$, and $\vec{D}$ that is true if and only if $\overleftrightarrow{A B} \perp \overleftrightarrow{C D}$.
(b) Use vectors to show that each median of an equilateral triangle is also an altitude of the triangle.
(c) Use vectors to show that if each median of a triangle is also an altitude of the triangle, then the triangle is equilateral.

Solution for Problem 13.5:
(a) We have $\overleftrightarrow{A B} \perp \overleftrightarrow{C D}$ if and only if the angle between $\overrightarrow{A B}$ and $\overrightarrow{C D}$ is $90^{\circ}$. An angle between vectors calls for the dot product-the angle between $\overrightarrow{A B}$ and $\overrightarrow{C D}$ is $90^{\circ}$ if and only if $\overrightarrow{A B} \cdot \overrightarrow{C D}=0$. Expressing $\overrightarrow{A B}$ and $\overrightarrow{C D}$ in terms of $\vec{A}, \vec{B}, \vec{C}$, and $\vec{D}$, we see that $\overleftrightarrow{A B} \perp \overleftrightarrow{C D}$ if and only if
$$(\vec{B}-\vec{A}) \cdot(\vec{D}-\vec{C})=0$$
(b) Let $\triangle A B C$ be an equilateral triangle and let $M$ be the midpoint of $\overline{B C}$. To show that each median of the triangle is also an altitude, we must show that $\overline{A M} \perp \overline{B C}$. From part (a), we have $\overline{A M} \perp \overline{B C}$ if and only if
$$(\vec{M}-\vec{A}) \cdot(\vec{C}-\vec{B})=0$$

Since $\vec{M}=(\vec{B}+\vec{C}) / 2$, we have
$$(\vec{M}-\vec{A}) \cdot(\vec{C}-\vec{B})=\left(\frac{\vec{B}}{2}+\frac{\vec{C}}{2}-\vec{A}\right) \cdot(\vec{C}-\vec{B})$$

That doesn't look like much fun to expand, but we can pull a trick out of our complex number toolbox to help us:

Concept: Choosing your origin wisely can greatly simplify the application of vectors to
geometry problems.

Here, letting $A$ be the origin produces a very convenient form for the expression on the right above, and we have
$$\vec{M} \cdot(\vec{C}-\vec{B})=\left(\frac{\vec{B}}{2}+\frac{\vec{C}}{2}\right) \cdot(\vec{C}-\vec{B})$$

We factor out $\frac{1}{2}$ and expand the right side. The $\vec{B} \cdot \vec{C}$ term in the expansion cancels with the $-\vec{C} \cdot \vec{B}$ term and we are left with
$$\vec{M} \cdot(\vec{C}-\vec{B})=\left(\frac{\vec{B}}{2}+\frac{\vec{C}}{2}\right) \cdot(\vec{C}-\vec{B})=\frac{1}{2}(\vec{C} \cdot \vec{C}-\vec{B} \cdot \vec{B})$$
$\vec{B} \cdot \vec{B}$ and $\vec{C} \cdot \vec{C}$ are the squares of the magnitudes of $\vec{B}$ and $\vec{C}$, respectively. Since $A$ is the origin and $\triangle A B C$ is equilateral, the magnitudes of $\vec{B}$ and $\vec{C}$ are the same. So, $\vec{B} \cdot \vec{B}=\vec{C} \cdot \vec{C}$ and we have
$$\vec{M} \cdot(\vec{C}-\vec{B})=\frac{1}{2}(\vec{C} \cdot \vec{C}-\vec{B} \cdot \vec{B})=0$$

Since $A$ is the origin, we have $\vec{M}=A \vec{M}$, so $\vec{M} \cdot(\vec{C}-\vec{B})=0$ tells us that $\overrightarrow{A M} \cdot \overrightarrow{B C}=0$, which means $\overline{A M} \perp \overline{B C}$. Note that our proof only used the fact that $A B=A C$, not the fact that all three sides are equal. So, we have proved that in any isosceles triangle $A B C$ with $A B=A C$, the median from $A$ to $\overline{B C}$ is also an altitude. Applying this fact to each pair of equal sides of an equilateral triangle, we see that all of the medians of an equilateral triangle are also altitudes of the triangle.

467

---

<!-- Page 468 -->

CHAPTER 13. VECTOR GEOMETRY
(c) We can essentially reverse the steps we took in part (b). If median $\overline{A M}$ is perpendicular to side $\overline{B C}$, then we must have
$$(\vec{M}-\vec{A}) \cdot(\vec{C}-\vec{B})=0 .$$

We have $\vec{M}=(\vec{B}+\vec{C}) / 2$, and we let $A$ be the origin, and we have
$$\left(\frac{\vec{B}}{2}+\frac{\vec{C}}{2}\right) \cdot(\vec{C}-\vec{B})=0$$

We multiply by 2 and expand the dot product on the left side. The $\vec{B} \cdot \vec{C}$ and $-\vec{C} \cdot \vec{B}$ terms cancel and we have
$$\vec{C} \cdot \vec{C}-\vec{B} \cdot \vec{B}=0,$$
which gives us $\vec{C} \cdot \vec{C}=\vec{B} \cdot \vec{B}$. Therefore, the magnitudes of $\vec{B}$ and $\vec{C}$ are the same. This means that $B$ and $C$ are equidistant from the origin. But $A$ is the origin! So, we have $A B=A C$. Similarly, we can show that $A B=B C$ by considering the altitude from $B$, and we conclude that $\triangle A B C$ is equilateral.

Problem 13.6:
(a) Show that if $A, B, C$, and $D$ are points in space such that $A B^{2}+C D^{2}=B C^{2}+A D^{2}$, then $\overrightarrow{A C}$ and $\overrightarrow{B D}$ are orthogonal.
(b) Look back at Problem 8.17 on page 274. How is part (a) a more general result than the problem we solved in Problem 8.17? What sorts of problems can we consider with vectors that we cannot tackle with complex numbers?

Solution for Problem 13.6:
(a) Writing $A B^{2}=\overrightarrow{A B} \cdot \overrightarrow{A B}=(\vec{B}-\vec{A}) \cdot(\vec{B}-\vec{A})$, and likewise for the other terms in the given equation, we have
$$(\vec{B}-\vec{A}) \cdot(\vec{B}-\vec{A})+(\vec{D}-\vec{C}) \cdot(\vec{D}-\vec{C})=(\vec{C}-\vec{B}) \cdot(\vec{C}-\vec{B})+(\vec{D}-\vec{A}) \cdot(\vec{D}-\vec{A}) .$$

When we expand the dot products on both sides, $\vec{A} \cdot \vec{A}, \vec{B} \cdot \vec{B}, \vec{C} \cdot \vec{C}$, and $\vec{D} \cdot \vec{D}$ appear as terms on both sides, so these terms all cancel and we are left with
$$-2 \vec{B} \cdot \vec{A}-2 \vec{D} \cdot \vec{C}=-2 \vec{B} \cdot \vec{C}-2 \vec{D} \cdot \vec{A}$$

Dividing by 2 and rearranging this equation gives
$$\vec{B} \cdot \vec{C}-\vec{B} \cdot \vec{A}+\vec{D} \cdot \vec{A}-\vec{D} \cdot \vec{C}=0$$

We group the first two terms and the second two terms as
$$\vec{B} \cdot(\vec{C}-\vec{A})-\vec{D} \cdot(\vec{C}-\vec{A})=0$$

We factor again to get
$$(\vec{B}-\vec{D}) \cdot(\vec{C}-\vec{A})=0$$
so $\overrightarrow{D B} \cdot \overrightarrow{A C}=0$. This means that $\overrightarrow{A C}$ and $\overrightarrow{D B}$ are orthogonal. Since $\overrightarrow{B D}=-\overrightarrow{D B}$, we see that $\overrightarrow{A C} \cdot \overrightarrow{B D}= -\overrightarrow{A C} \cdot \overrightarrow{D B}=0$, so $\overrightarrow{A C}$ and $\overrightarrow{B D}$ are orthogonal as well.
(b) The main difference between our result in part (a) and the result in Problem 8.17 is that our work in Problem 8.17 only proves the result in two dimensions. Our work in part (a) shows that it holds in three dimensions, as well. Moreover, it shows that if we define distance in four or more dimensions analogously to our definition of distance in two and three dimensions, then the result holds for higher dimensions, as well. This is an example of one significant advantage vectors have over complex numbers: vectors can be applied to problems in more than two dimensions.

468

---

<!-- Page 469 -->

13.2. VECTORS IN THE TRIANGLE

Exercises
13.1.1
(a) Use vectors to prove that if the diagonals of quadrilateral $A B C D$ bisect each other, then $A B C D$ is a parallelogram.
(b) Use vectors to prove that the midpoints of the sides of any quadrilateral are the vertices of a parallelogram.
13.1.2 We call quadrilateral $A B C D$ is a kite if $A B=B C$ and $C D=D A$ (or if $B C=C D$ and $D A=A B$ ). Use vectors to show that the diagonals of a kite are perpendicular.
13.1.3 Show that if $M$ and $N$ are midpoints of $\overline{A C}$ and $\overline{B D}$, respectively, then $\overrightarrow{A B}+\overrightarrow{A D}+\overrightarrow{C B}+\overrightarrow{C D}=4 \overrightarrow{M N}$.
13.1.4 A median of a quadrilateral connects the midpoint of one side of the quadrilateral to the midpoint of the opposite side of the quadrilateral. Show that the diagonals of a quadrilateral are perpendicular if and only if the medians of the quadrilateral are equal in length.
13.1.5 Show that in any $\triangle A B C$, we have $C A^{2}+C B^{2}=2 C M^{2}+\frac{A B^{2}}{2}$, where $M$ is the midpoint of $\overline{A B}$.
13.1.6 Let $A, B, C$, and $D$ be points in space. Show that if $\overrightarrow{A B}$ and $\overrightarrow{C D}$ are orthogonal and $\overrightarrow{A C}$ and $\overrightarrow{B D}$ are orthogonal, then $\overrightarrow{A D}$ and $\overrightarrow{B C}$ are orthogonal.
13.2 Vectors in the Triangle

Problems

Problem 13.7: Show that all three medians of $\triangle A B C$ pass through a point $G$ such that $\vec{G}=(\vec{A}+\vec{B}+\vec{C}) / 3$.
Problem 13.8: Show that if we let the circumcenter of triangle $A B C$ be the origin, then all three altitudes of $\triangle A B C$ pass through the point $H$ such that $\vec{H}=\vec{A}+\vec{B}+\vec{C}$.

Problem 13.9: The centroid of a triangle is the point at which the triangle's medians are concurrent and the orthocenter of a triangle is the point at which the triangle's altitudes are concurrent. Let $G, H$, and $O$ be the centroid, orthocenter, and the circumcenter, respectively, of $\triangle A B C$. Show that if $O$ and $H$ are distinct points, then $G$ is on $\overline{O H}$ such that $O G / O H=1 / 3$.

Problem 13.10: Let $D, E, F$ be the midpoints of $\overline{B C}, \overline{A C}$, and $\overline{A B}$, respectively, and let $J, K$, $L$ be the feet of the altitudes of $\triangle A B C$ from $A, B, C$, respectively. Finally, let $H$ be the orthocenter of $\triangle A B C$ and let $U, V, W$ be the midpoints of $\overline{A H}, \overline{B H}$, and $\overline{C H}$, respectively. In this problem, we prove that a circle passes through $D, E, F, J, K, L, U, V$, and $W$. We call this circle the nine-point circle of $\triangle A B C$.
(a) Let the circumcenter of $\triangle A B C$ be the origin. Express $\vec{D}, \vec{E}$, and $\vec{F}$ in terms of $\vec{A}, \vec{B}$, and $\vec{C}$. Suppose $T$ is the center of the circle that passes through $D, E$, and $F$. Use the forms of $\vec{D}, \vec{E}$, and $\vec{F}$ to guess $\vec{T}$ in terms of $\vec{A}$, $\vec{B}, \vec{C}$. Confirm that your guess is correct by showing that $T D=T E=T F$.
(b) Find $\vec{U}, \vec{V}$, and $\vec{W}$ in terms of $\vec{A}, \vec{B}$, and $\vec{C}$. Show that $T U=T V=T W$, and that $U, V$, and $W$ are on the circle from part (a).
(c) Show that $\overline{U D}, \overline{V E}$, and $\overline{W F}$ are diameters of the nine-point circle. Why does this tell us that $J, K$, and $L$ are on the nine-point circle?

469

---

<!-- Page 470 -->

CHAPTER 13. VECTOR GEOMETRY

Problem 13.11: Suppose that $A^{\prime}, B^{\prime}$, and $C^{\prime}$ are on the circumcircle of $\triangle A B C$ such that $\overline{A A^{\prime}}, \overline{B B^{\prime}}$, and $\overline{C C^{\prime}}$ are diameters of the circumcircle. If $K, L$, and $M$ are the midpoints of $\overline{B C}, \overline{A C}$, and $\overline{A B}$, respectively, then show that $\overleftrightarrow{A^{\prime} K}, \overleftrightarrow{B^{\prime} L}$, and $\overleftrightarrow{C^{\prime} M}$ are concurrent.

Problem 13.12: Each segment from a vertex of a tetrahedron to the centroid of the opposite face of the tetrahedron is called a median of the tetrahedron. Prove that the medians of any tetrahedron are concurrent at a point called the centroid of the tetrahedron. Note that the centroid of a triangle cuts each median in a $2: 1$ ratio. Can we make a similar statement about the centroid of a tetrahedron?

Problem 13.7: Show that all three medians of $\triangle A B C$ pass through a point $G$ such that $\vec{G}=(\vec{A}+\vec{B}+\vec{C}) / 3$.
Solution for Problem 13.7: Let $M$ be the midpoint of $\overline{B C}$, so $\vec{M}=(\vec{B}+\vec{C}) / 2$ and
$$\overrightarrow{A M}=\vec{M}-\vec{A}=\frac{\vec{B}+\vec{C}}{2}-\vec{A} .$$

We have
$$\overrightarrow{A G}=\vec{G}-\vec{A}=\frac{\vec{A}+\vec{B}+\vec{C}}{3}-\vec{A}=\frac{\vec{B}+\vec{C}-2 \vec{A}}{3}=\frac{2}{3}\left(\frac{\vec{B}+\vec{C}}{2}-\vec{A}\right)=\frac{2}{3} A \vec{M} \text {. }$$

Since $\overrightarrow{A G}$ is a scalar multiple of $\overrightarrow{A M}$, points $A, G$, and $M$ are collinear. Moreover, since $\overrightarrow{A G}=\frac{2}{3} \overrightarrow{A M}$, point $G$ is on $\overline{A M}$ such that $A G=\frac{2}{3} A M$.

There's nothing special in our proof above about vertex $A$; the same exact steps show that $G$ is on the medians from $B$ and from $C$, and that the distance from $G$ to each vertex is $\frac{2}{3}$ of the length of the median from that vertex.
```
Important: The medians of any triangle are concurrent at a point called the centroid. If the
    ! centroid of $\triangle A B C$ is $G$, then $\vec{G}=(\vec{A}+\vec{B}+\vec{C}) / 3$.
```

Problem 13.8: Show that if we let the circumcenter of triangle $A B C$ be the origin, then all three altitudes of $\triangle A B C$ pass through the point $H$ such that $\vec{H}=\vec{A}+\vec{B}+\vec{C}$.

Solution for Problem 13.8: Because $H$ is on the altitude from $A$, we must have $\overleftrightarrow{A H} \perp \overleftrightarrow{B C}$. Vectors give us a nice condition to test if two lines are perpendicular: the dot product.
We have $\overrightarrow{A H}=\vec{H}-\vec{A}=(\vec{A}+\vec{B}+\vec{C})-\vec{A}=\vec{B}+\vec{C}$, so
$$\overrightarrow{A H} \cdot \overrightarrow{B C}=(\vec{B}+\vec{C}) \cdot(\vec{C}-\vec{B})=\vec{B} \cdot \vec{C}-\vec{B} \cdot \vec{B}+\vec{C} \cdot \vec{C}-\vec{C} \cdot \vec{B} .$$

Since $\vec{B} \cdot \vec{C}=\vec{C} \cdot \vec{B}$, two terms cancel, leaving
$$\overrightarrow{A H} \cdot \overrightarrow{B C}=\vec{C} \cdot \vec{C}-\vec{B} \cdot \vec{B}=\|\vec{C}\|^{2}-\|\vec{B}\|^{2} .$$

We'd like to show that this expression equals 0 , but now we seem stuck.
Concept: When stuck on a problem, look back at the problem for any information you haven't used.

470

---

<!-- Page 471 -->

13.2. VECTORS IN THE TRIANGLE

We haven't used the fact that the circumcenter of $\triangle A B C$ is the origin. The circumcenter of a triangle is equidistant from its vertices, so $\|\vec{A}\|=\|\vec{B}\|=\|\vec{C}\|$. Therefore, we have $\overrightarrow{A H} \cdot \overrightarrow{B C}=\|\vec{C}\|^{2}-\|\vec{B}\|^{2}=0$, which means that $\overleftrightarrow{A H} \perp \overleftrightarrow{B C}$. Similarly, we can show that $\overrightarrow{B H} \cdot \overrightarrow{A C}=\overrightarrow{C H} \cdot \overrightarrow{A B}=0$, so $H$ is on all three altitudes of $\triangle A B C$.

\begin{table}
\begin{tabular}{|l|l|}
\hline Important: & The altitudes of any triangle are concurrent at a point called the orthocenter. Let $H$ be the orthocenter of $\triangle A B C$. If the circumcenter of $\triangle A B C$ is the origin, then $\vec{H}=\vec{A}+\vec{B}+\vec{C}$. \\
\hline WARNING!! A & Let $H$ be the orthocenter of $\triangle A B C$. Our proof above only shows that we have $\vec{H}=\vec{A}+\vec{B}+\vec{C}$ if the circumcenter of $\triangle A B C$ is the origin. \\
\hline
\end{tabular}
\captionsetup{labelformat=empty}
\caption{Concept:
When applying vectors to a problem involving a triangle, choosing the circumcenter as the origin can greatly simplify the problem.}
\end{table}

We've already seen the power of choosing the origin wisely several times in problems involving the application of complex numbers or vectors to geometry problems. Problem 13.8 shows us a frequently useful choice for problems involving triangles.

As we saw in Problem 13.8, this tactic is useful because the magnitudes of the vectors from the origin to the vertices of the triangle are all equal if we let the circumcenter of the triangle be the origin. The simple form we found for the orthocenter when we let the circumcenter be the origin gives us another good reason to make this choice of origin in problems involving the orthocenter.

Problem 13.9: Let $G, H$, and $O$ be the centroid, orthocenter, and the circumcenter of $\triangle A B C$. Show that if $H$ and $O$ are distinct points, then $G$ is on $\overline{O H}$ such that $O G / O H=1 / 3$.

Solution for Problem 13.9: We have a convenient vector representation for the centroid, and if we let the circumcenter be the origin, we have a very convenient representation for the circumcenter and a nice one for the orthocenter. Letting $O$ be the origin, we have $\overrightarrow{O G}=\vec{G}$ and $\overrightarrow{O H}=\vec{H}$. Using our nice expressions for $\vec{G}$ and $\vec{H}$, we have
$$\vec{G}=\frac{\vec{A}+\vec{B}+\vec{C}}{3}=\frac{\vec{H}}{3} .$$

Therefore, $G$ is on $\overline{O H}$ such that $O G / O H=1 / 3$.

The line through the orthocenter, centroid, and circumcenter of a non-equilateral triangle is called the Euler line of the triangle. (If a triangle is equilateral, these three points are all the same.) In the diagram at right, the altitudes are dotted, the medians are dashed, and the solid line passing through the orthocenter, centroid, and circumcenter of the triangle is the Euler line.

Problem 13.10: Let $D, E, F$ be the midpoints of $\overline{B C}, \overline{A C}$, and $\overline{A B}$, respectively, and let $J, K, L$ be the feet of the altitudes of $\triangle A B C$ from $A, B, C$, respectively. Finally, let $H$ be the orthocenter of $\triangle A B C$ and let $U, V, W$ be the midpoints of $\overline{A H}, \overline{B H}$, and $\overline{C H}$, respectively. Show that a single circle passes through $D, E, F, J, K, L, U, V$, and $W$. This circle is called the nine-point circle of $\triangle A B C$.

471

---

<!-- Page 472 -->

CHAPTER 13. VECTOR GEOMETRY

Solution for Problem 13.10: We can show that all nine points are on the same circle by finding a single point that is the same distance from all nine points. We think to attack this problem with vectors because we can easily handle midpoints and the orthocenter with vectors. But to deal with the orthocenter, we must remember to let the circumcenter of $\triangle A B C$ be the origin.

We start with the easiest points to work with, the midpoints of the sides, since these are the simplest to express with vectors. We have
$$\begin{aligned}
\vec{D} & =\frac{\vec{B}+\vec{C}}{2} \\
\vec{E} & =\frac{\vec{A}+\vec{C}}{2} \\
\vec{F} & =\frac{\vec{A}+\vec{B}}{2}
\end{aligned}$$

The desired circle must pass through all three of these points. We let the circle have center $T$, and will refer to the circle as $\odot T$. Can we use the expressions for $\vec{D}, \vec{E}$, and $\vec{F}$ to deduce $\vec{T}$ in terms of $\vec{A}, \vec{B}$, and $\vec{C}$ ?

Concept: Don't overlook "guess-and-check" as a strategy, even in advanced problems. Guessing and then confirming that your guess is correct has a long and glorious history in mathematics and science.

We seek a point $T$ such that $\overrightarrow{D T}, \overrightarrow{E T}$, and $\overrightarrow{F T}$ all have the same magnitude. Since $\overrightarrow{D T}=\vec{T}-\vec{D}, \overrightarrow{E T}=\vec{T}-\vec{E}$, and $\overrightarrow{F T}=\vec{T}-\vec{F}$, a natural choice for $\vec{T}$ that offers a lot of cancellation in these differences is
$$\vec{T}=\frac{\vec{A}+\vec{B}+\vec{C}}{2} .$$

This expression gives very simple results for $\overrightarrow{D T}, \overrightarrow{E T}$, and $\overrightarrow{F T}$ :
$$\begin{array}{l}
\overrightarrow{D T}=\vec{T}-\vec{D}=\frac{\vec{A}+\vec{B}+\vec{C}}{2}-\frac{\vec{B}+\vec{C}}{2}=\frac{\vec{A}}{2} \\
\overrightarrow{E T}=\vec{T}-\vec{E}=\frac{\vec{A}+\vec{B}+\vec{C}}{2}-\frac{\vec{A}+\vec{C}}{2}=\frac{\vec{B}}{2} \\
\overrightarrow{F T}=\vec{T}-\vec{F}=\frac{\vec{A}+\vec{B}+\vec{C}}{2}-\frac{\vec{A}+\vec{B}}{2}=\frac{\vec{C}}{2}
\end{array}$$

Recalling that the origin is the circumcenter of $\triangle A B C$, we see that this choice of $\vec{T}$ is a winner, since $\|\vec{A}\|=\|\vec{B}\|=\|\vec{C}\|$ gives us $\|\overrightarrow{D T}\|=\|\overrightarrow{E T}\|=\|\overrightarrow{F T}\|$. So, $T$ is the center of the circle that passes through $D, E$, and $F$; we'll refer to this circle as $\odot T$. Moreover, because we know that $\|\vec{A}\|=R$, the circumradius of $\triangle A B C$, and $\|\overrightarrow{D T}\|=\|\vec{A}\| / 2$, we know that the radius of the circle through $D, E$, and $F$ is $R / 2$. We also recognize that
$$\vec{T}=\frac{\vec{A}+\vec{B}+\vec{C}}{2}=\frac{\vec{H}}{2},$$
so $T$ is the midpoint of the segment from the circumcenter to the orthocenter. This means $T$ is on the Euler line, too!

472

---

<!-- Page 473 -->

13.2. VECTORS IN THE TRIANGLE

Next, we turn to $U, V$, and $W$, because we know how to handle the orthocenter with vectors. Since $U, V$, and $W$ are the midpoints of $\overline{A H}, \overline{B H}$, and $\overline{C H}$, respectively, we have
$$\begin{array}{l}
\vec{U}=\frac{\vec{A}+\vec{H}}{2}=\frac{2 \vec{A}+\vec{B}+\vec{C}}{2} \\
\vec{V}=\frac{\vec{B}+\vec{H}}{2}=\frac{\vec{A}+2 \vec{B}+\vec{C}}{2} \\
\vec{W}=\frac{\vec{C}+\vec{H}}{2}=\frac{\vec{A}+\vec{B}+2 \vec{C}}{2}
\end{array}$$

We need to show that each of $U, V$, and $W$ is $R / 2$ from $T$, so we find the magnitudes of $\overrightarrow{U T}, \overrightarrow{V T}$, and $\overrightarrow{W T}$ :
$$\begin{array}{l}
\|\overrightarrow{U T}\|=\|\vec{T}-\vec{U}\|=\left\|\frac{\vec{A}+\vec{B}+\vec{C}}{2}-\frac{2 \vec{A}+\vec{B}+\vec{C}}{2}\right\|=\left\|-\frac{\vec{A}}{2}\right\|=\left\|\frac{\vec{A}}{2}\right\|=\frac{R}{2}, \\
\|\overrightarrow{V T}\|=\|\vec{T}-\vec{V}\|=\left\|\frac{\vec{A}+\vec{B}+\vec{C}}{2}-\frac{\vec{A}+2 \vec{B}+\vec{C}}{2}\right\|=\left\|-\frac{\vec{B}}{2}\right\|=\left\|\frac{\vec{B}}{2}\right\|=\frac{R}{2}, \\
\|\overrightarrow{W T}\|=\|\vec{T}-\vec{W}\|=\left\|\frac{\vec{A}+\vec{B}+\vec{C}}{2}-\frac{\vec{A}+\vec{B}+2 \vec{C}}{2}\right\|=\left\|-\frac{\vec{C}}{2}\right\|=\left\|\frac{\vec{C}}{2}\right\|=\frac{R}{2} .
\end{array}$$

So, $\odot T$ passes through $U, V$, and $W$ in addition to $D, E$, and $F$. Six points down, three to go!
The last three points, the feet of the altitudes of $\triangle A B C$, look a lot more challenging. We haven't seen simple vector expressions in terms of $\vec{A}, \vec{B}$, and $\vec{C}$ for the feet of the altitudes of $\triangle A B C$. So, let's try learning a little bit more about the six points that we have already proved are on the circle. Looking closely at our diagram, it looks like $\overline{D U}, \overline{E V}$, and $\overline{F W}$ each pass through $T$. If they do, they're diameters of $\odot T$.

Concept: Precise diagrams can help you discover important relationships in geometry prob-
lems.

Of course, it's not good enough that $\overline{D U}, \overline{E V}$, and $\overline{F W}$ look like diameters. We have to prove it. Vectors can help us with that, too. The midpoint of $\overline{D U}$ is
$$\frac{\vec{D}+\vec{U}}{2}=\frac{\frac{\vec{B}+\vec{C}}{2}+\frac{2 \vec{A}+\vec{B}+\vec{C}}{2}}{2}=\frac{\vec{A}+\vec{B}+\vec{C}}{2}=\vec{T} .$$

Success! $T$ is the midpoint of $\overline{D U}$, so $\overline{D U}$ is indeed a diameter of $\odot T$. Similarly, $\frac{\vec{E}+\vec{V}}{2}=\vec{T}$ and $\frac{\vec{F}+\vec{W}}{2}=\vec{T}$, so $\overline{E V}$ and $\overline{F W}$ are diameters of $\odot T$ as well.

Now, we're ready to tackle $J, K$, and $L$. The circumcircle of a right triangle is the circle with the hypotenuse of the triangle as a diameter. Therefore, the circumcircle of right triangle $D J U$ is the circle with hypotenuse $\overline{D U}$ as diameter. But this is $\odot T$ ! Since $\odot T$ is the circumcircle of $\triangle D J U$, it passes through $J$. Similarly, $\odot T$ is the circumcircle of right triangles $E K V$ and $F L W$, so $K$ and $L$ are on $\odot T$, as well.

Extra! The midpoint of any segment from the orthocenter of a triangle to a point on the circumcircle of the triangle is on the nine-point circle of the triangle.

473

---

<!-- Page 474 -->

CHAPTER 13. VECTOR GEOMETRY

\begin{tabular}{|l|l|}
\hline Sidenote: & \begin{tabular}{l}
The nine-point circle has interesting relationships to other parts of a triangle. For example, the incircle of a triangle is tangent to the ninepoint circle, as shown at right (except when the triangle is equilateral, in which case the two circles are the same). The nine-point circle is also tangent to the excircles of $\triangle A B C$, which are the \\
three circles outside $\triangle A B C$ that are tangent to one side of the triangle and tangent to the extensions of the other two sides. That the nine-point circle of a triangle is tangent to the incircle and the excircles of the triangle is sometimes referred to as Feuerbach's Theorem. \\
One direct result of Feuerbach's Theorem is that the inradius of a triangle is no more than half the circumradius of the triangle. See if you can figure out why!
\end{tabular} \\
\hline
\end{tabular}

Problem 13.11: Suppose that $A^{\prime}, B^{\prime}$, and $C^{\prime}$ are on the circumcircle of $\triangle A B C$ such that $\overline{A A^{\prime}}, \overline{B B^{\prime}}$, and $\overline{C C^{\prime}}$ are diameters of the circumcircle. If $K, L$, and $M$ are the midpoints of $\overline{B C}, \overline{A C}$, and $\overline{A B}$, respectively, then show that $\overleftrightarrow{A^{\prime} K}, \overleftrightarrow{B^{\prime} L}$, and $\overleftrightarrow{C^{\prime} M}$ are concurrent.

Solution for Problem 13.11: We use vectors because we know how to express all the key points with vectors in terms of $\vec{A}, \vec{B}$, and $\vec{C}$. First, we have
$$\vec{K}=\frac{\vec{B}+\vec{C}}{2}, \quad \vec{L}=\frac{\vec{C}+\vec{A}}{2}, \quad \vec{M}=\frac{\vec{A}+\vec{B}}{2} .$$

Then, we let the circumcenter be the origin. Since the circumcenter is the midpoint of $\overline{A^{\prime} A}, \overline{B^{\prime} B}$, and $\overline{C^{\prime} C}$, we have $\overrightarrow{A^{\prime}}=-\vec{A}, \overrightarrow{B^{\prime}}=-\vec{B}$, and $\overrightarrow{C^{\prime}}=-\vec{C}$.

We seek a point $P$ such that $P$ is on $\overleftrightarrow{A^{\prime} K}, \overleftrightarrow{B^{\prime} L}$, and $\overleftrightarrow{C^{\prime} M}$. From the symmetry of the
problem, we expect that we can express $\vec{P}$ as some symmetric expression in terms of $\vec{A}, \vec{B}$, and $\vec{C}$. Of course, the simplest outcome would be if $P$ were the origin, but our diagram makes it clear that the lines $\overleftrightarrow{A^{\prime} K}, \overleftrightarrow{B^{\prime} L}$, and $\overleftrightarrow{C^{\prime} M}$ don't meet at the center of the circle.

So, we try the next simplest reasonable guess, the orthocenter. In fact, this might have been our first guess if we had taken a close look at the diagram! If $\vec{P}=\vec{A}+\vec{B}+\vec{C}$, we have
$$\begin{array}{l}
\overrightarrow{A^{\prime} P}=\vec{P}-\overrightarrow{A^{\prime}}=\vec{A}+\vec{B}+\vec{C}-(-\vec{A})=2 \vec{A}+\vec{B}+\vec{C} \\
\overrightarrow{K P}=\vec{P}-\vec{K}=\vec{A}+\vec{B}+\vec{C}-\left(\frac{\vec{B}+\vec{C}}{2}\right)=\frac{2 \vec{A}+\vec{B}+\vec{C}}{2}
\end{array}$$

Success! We have $\overrightarrow{A^{\prime} P}=2 \overrightarrow{K P}$, so the orthocenter is on $\overleftrightarrow{A^{\prime} K}$ for any choice of $A, B$, and $C$. Similarly, we can show that the orthocenter is on $\overleftrightarrow{B^{\prime} L}$ and $\overleftrightarrow{C^{\prime} M}$, so the three lines are concurrent at the orthocenter.

Once we made the observation that we expect $\vec{P}$ to have a symmetric expression in terms of $\vec{A}, \vec{B}$, and $\vec{C}$, we also could have found $\vec{P}$ without further guessing. We start by noting that $\overrightarrow{A^{\prime} K}=\frac{\vec{B}+\vec{C}}{2}-(-\vec{A})=\vec{A}+\frac{\vec{B}+\vec{C}}{2}$. So, we seek the vector $\vec{P}=t(\vec{A}+\vec{B}+\vec{C})$ such that $\overrightarrow{A^{\prime} P}$ is a scalar multiple of $\vec{A}+\frac{\vec{B}+\vec{C}}{2}$. We have
$$\overrightarrow{A^{\prime} P}=t(\vec{A}+\vec{B}+\vec{C})-(-\vec{A})=(t+1) \vec{A}+t \vec{B}+t \vec{C} .$$

This is a scalar multiple of $\vec{A}+\frac{\vec{B}+\vec{C}}{2}$ if and only if $t+1=2 t$, which gives us $t=1$. By essentially the same argument, the point $P$ such that $\vec{P}=\vec{A}+\vec{B}+\vec{C}$ is on the other two lines as well.

474

---

<!-- Page 475 -->

13.2. VECTORS IN THE TRIANGLE

Let's see if we can take some of our tools for triangles up one dimension, and apply them to the threedimensional analogue of a triangle: a tetrahedron.

Problem 13.12: Each segment from a vertex of a tetrahedron to the centroid of the opposite face of the tetrahedron is called a median of the tetrahedron. Prove that the medians of any tetrahedron are concurrent at a point called the centroid of the tetrahedron. The centroid of a triangle cuts each median in a $2: 1$ ratio. Can we make a similar statement about the centroid of a tetrahedron?

Solution for Problem 13.12: The vector to the midpoint of a segment is the average of the vectors to the endpoints of the segment. The vector to the centroid of a triangle is the average of the vectors to vertices of the triangle. A reasonable guess is that if there is a point $G$ on all four medians of some tetrahedron $A B C D$, then
$$\vec{G}=\frac{\vec{A}+\vec{B}+\vec{C}+\vec{D}}{4} .$$

Let $V$ be the centroid of face $B C D$, so
$$\vec{V}=\frac{\vec{B}+\vec{C}+\vec{D}}{3} .$$

To show that $G$ is on $\overline{A V}$, we find $\overrightarrow{A G}$ and $\overrightarrow{A V}$ :
$$\begin{array}{l}
\overrightarrow{A G}=\vec{G}-\vec{A}=\frac{\vec{A}+\vec{B}+\vec{C}+\vec{D}}{4}-\vec{A}=\frac{\vec{B}+\vec{C}+\vec{D}-3 \vec{A}}{4} \\
\overrightarrow{A V}=\vec{V}-\vec{A}=\frac{\vec{B}+\vec{C}+\vec{D}}{3}-\vec{A}=\frac{\vec{B}+\vec{C}+\vec{D}-3 \vec{A}}{3}
\end{array}$$

So, we have $\overrightarrow{A G}=\frac{3}{4} \overrightarrow{A V}$, which means that $G$ is the point on $\overline{A V}$ such that $A G / A V=3 / 4$. We can similarly show that this choice of $G$ is on each of the other medians, and divides each median in this same ratio. Therefore, just as the medians of a triangle are concurrent at a point that divides each median in a $2: 1$ ratio, the medians of a tetrahedron are concurrent at a point that divides each median in a $3: 1$ ratio.
Exercises
13.2.1 Find the centroid of the triangle with vertices $(1,4,-1),(-4,5,2)$, and $(6,-1,7)$.
13.2.2 Let $a=B C, b=A C$, and $c=A B$ in $\triangle A B C$.
(a) Let $D$ be on $\overline{B C}$ such that $\overline{A D}$ bisects $\angle B A C$. Find $\vec{D}$ in terms of $a, b, c, \vec{A}, \vec{B}$, and $\vec{C}$. Hints: 104
(b) Let $I$ be the incenter of $\triangle A B C$. Find $\vec{I}$ in terms of $a, b, c, \vec{A}, \vec{B}$, and $\vec{C}$.
13.2.3 Show that for any point $P$ and any triangle $A B C$, the sum of the squares of the sides of the triangle is no greater than 3 times the sum of the squares of the distances from $P$ to each of the vertices of $\triangle A B C$. At what point do we have equality?
13.2.4 Show that if $H$ and $O$ are the orthocenter and circumcenter, respectively, of $\triangle A B C$, then $\vec{H}=\vec{A}+\vec{B}+\vec{C}-2 \vec{O}$.
13.2.5 The centroids of the faces of a tetrahedron are $(17,0,3),(-2,13,3),(1,2,15)$, and $(1,-1,2)$. What are its vertices?
13.2.6 ★ Points $U, V$, and $W$ are the reflections of the circumcenter of $\triangle A B C$ over $\overleftrightarrow{B C}, \overleftrightarrow{A C}$, and $\overleftrightarrow{A B}$. Show that $\overleftrightarrow{A U}$, $\overleftrightarrow{B V}$, and $\overleftrightarrow{C W}$ are concurrent. At what special point of $\triangle A B C$ are they concurrent?

475

---

<!-- Page 476 -->

CHAPTER 13. VECTOR GEOMETRY

$13.3 \star$ Vectors, Complex Numbers, and Challenging Problems

Our work so far in this chapter probably reminds you of some of the work we did in Chapter 8 with complex numbers. For example, if $M$ is the midpoint of $\overline{A B}$, then $\vec{M}=(\vec{A}+\vec{B}) / 2$ in vectors and $m=(a+b) / 2$ in complex numbers. Also, if $O A C B$ is a parallelogram and $O$ is the origin, then $\vec{A}+\vec{B}=\vec{C}$ in vectors and $a+b=c$ in complex numbers. If $G$ is the centroid of $\triangle A B C$, we have $\vec{G}=(\vec{A}+\vec{B}+\vec{C}) / 3$ and $g=(a+b+c) / 3$. And so on. What's going on here?

Let's look back at what a vector in two dimensions is. Vectors in two dimensions are ordered pairs of numbers that have the following operations:
- Vector addition. We add vectors by adding the corresponding components:
$$\binom{a}{b}+\binom{c}{d}=\binom{a+c}{b+d} .$$
- Multiplication of a vector by a constant. We multiply a vector by a constant by multiplying each component of the vector by the constant:
$$k\binom{a}{b}=\binom{k a}{k b}$$

A complex number is an ordered pair of real numbers, the real part and the imaginary part of the complex number. Complex numbers have these same two operations:
- Complex number addition. We have $(a+b i)+(c+d i)=(a+c)+(b+d) i$.
- Multiplication of a complex number by a real constant. If $k$ is real, we have $k(a+b i)=k a+(k b) i$.

We see that complex numbers are vectors, so the similarities between the applications of vectors to geometry and the applications of complex numbers to geometry are not a coincidence!

We also defined multiplication of complex numbers as
$$(a+b i)(c+d i)=(a c-b d)+(a d+b c) i$$

Note that the dot product is not multiplication of vectors in the same sense, since the dot product of two vectors is not a vector, whereas the product of two complex numbers is itself a complex number. We saw in Chapter 8 that complex number multiplication has some very nice applications to geometry, particularly when dealing with rotations.

As we've seen, we usually use complex numbers and vectors for different types of algebraic problems. For example, we wouldn't use vector notation to express the roots of $x^{2}+x+1$, we don't use the concept of "conjugate" with general vectors in two dimensions, and we don't generally use anything quite like matrices when dealing with complex numbers. Some tools overlap, such as magnitude, which is essentially the same in both.

With most problems that involve complex numbers or more general vectors, it's clear which tool we should use. In this section, we look at a series of very challenging problems in an area where the applications of complex numbers and vectors overlap a great deal: geometry. Some of these problems are best tackled with the machinery we've developed for complex numbers, others with the tools we've used with vectors. Still other problems can be tackled with either, and others with concepts drawn from both.

476

---

<!-- Page 477 -->

13.3★. VECTORS, COMPLEX NUMBERS, AND CHALLENGING PROBLEMS

Problems
Problem 13.13: Consider the points $A(0,12), B(10,9), C(8,0)$, and $D(-4,7)$. There is a unique square $S$ such that each of the four points is on a different side of $S$. Find the area of $S$. (Source: AIME) Hints: 106

Problem 13.14: Points $P$ and $Q$ are on sides $\overline{A B}$ and $\overline{A C}$ of equilateral triangle $A B C$ such that $\overline{P Q} \| \overline{B C}$. Show that if $M$ is the midpoint of $\overline{P C}$ and $T$ is the centroid of $\triangle A P Q$, then $\triangle T M B$ is a 30-60-90 triangle.

Problem 13.15: Way back on page 185, we helped Petr figure how long his trip to Honolulu would be by finding the distance along the surface of the earth from his home city of Petropavlovsk-Kamchatsky, which has coordinates $52.92^{\circ} \mathrm{N}, 158.49^{\circ} \mathrm{E}$, to Honolulu, which has coordinates $21.31^{\circ} \mathrm{N}, 157.83^{\circ} \mathrm{W}$. Before he left on his trip, he tried to look up the distance between the two cities on the internet. He found a formula that said the distance between points $P$ and $Q$ on the Earth is $\alpha R$, where $R$ is the radius of the Earth and $\alpha$ is the angle such that $0 \leq \alpha \leq \pi$ and
$$\cos \alpha=\cos \lambda_{P} \cos \lambda_{Q} \cos (\Delta \beta)+\sin \lambda_{P} \sin \lambda_{Q}$$

Unfortunately, he couldn't find any information about what the symbols $\lambda_{P}, \lambda_{Q}$, and $\Delta \beta$ mean. Help Petr by figuring out what this formula is all about. Hints: 4

Problem 13.16: Let $O$ be the center of the circumcircle $\Gamma$ of a regular polygon $A_{1} A_{2} A_{3} \cdots A_{25} A_{26}$ with 26 sides. Let $O_{1}$ and $O_{2}$ be the reflections of $O$ over $\overline{A_{25} A_{1}}$ and $\overline{A_{2} A_{6}}$, respectively. Prove that $\overline{O_{1} O_{2}}$ is equal in length to a side of an equilateral triangle inscribed in $\Gamma$. Hints: 191

Problem 13.17: Let $A B C D E F$ be a convex hexagon with $A B=B C, C D=D E$, and $E F=F A$. Show that the lines containing the altitudes of triangles $B C D, D E F$, and $F A B$ from $C, E$, and $A$, respectively, are concurrent. (Source: Poland) Hints: 275

Problem 13.18: Use complex numbers to prove that the area of a triangle with side lengths $a, b$, and $c$ is
$$\sqrt{s(s-a)(s-b)(s-c)}$$
where $s=(a+b+c) / 2$ is the semiperimeter of the triangle. Hints: 285

Problem 13.13: Consider the points $A(0,12), B(10,9), C(8,0)$, and $D(-4,7)$. There is a unique square $\mathcal{S}$ such that each of the four points is on a different side of $S$. Find the area of $S$. (Source: AIME)

Solution for Problem 13.13: First, we note that because $\overline{A C}$ and $\overline{B D}$ intersect, each segment connects points on opposite sides of the square. Next, we wonder what additional piece of information we need in order find the side length of the square.

If we knew a direction of the side of the square through $A$, that would be enough for us to build the whole square. The opposite side has the same direction, so we could use this direction to draw lines through $A$ and $C$ containing the sides of the square. Then, we draw lines through $B$ and $D$ perpendicular to the line through $A$, and the four intersection points of our four lines give us the vertices of the square.

All this talk about "direction" has us thinking about vectors. Let's see how we might apply vectors to the

477

---

<!-- Page 478 -->

CHAPTER 13. VECTOR GEOMETRY

problem. We let $\mathbf{u}=\binom{p}{q}$ be a unit vector in a direction of the side of the square through $A$. Any vector orthogonal to $\binom{p}{q}$ is perpendicular to the side through $A$, and is therefore in the direction of the side through $B$. This means that the vector $\mathbf{v}=\binom{-q}{p}$ is in the direction of the side through $B$. That uses the fact that consecutive sides of a square are perpendicular. Now, we look for a way to use the fact that the sides of a square are the same length.

We can find a vector whose length equals the side length of the square by projecting $\overrightarrow{B D}$ onto $\binom{p}{q}$, the direction of the side through $A$. Similarly, the magnitude of the projection of $\overrightarrow{A C}$ onto $\binom{-q}{p}$ must also be the length of a side of the square.

Since $\overrightarrow{A C}=\binom{8-0}{0-12}=\binom{8}{-12}$ and $\overrightarrow{B D}=\binom{-4-10}{7-9}=\binom{-14}{-2}$, and $\mathbf{u}$ and $\mathbf{v}$ are unit vectors, the projections of $\overrightarrow{A C}$ onto $\mathbf{v}$ and of $\overrightarrow{B D}$ onto $\mathbf{u}$ are
$$\begin{array}{l}
\operatorname{proj}_{\mathbf{v}} \overrightarrow{A C}=\frac{\overrightarrow{A C} \cdot \mathbf{v}}{\|\mathbf{v}\|^{2}} \mathbf{v}=\frac{-8 q-12 p}{1^{2}} \mathbf{v}=(-8 q-12 p) \mathbf{v}, \\
\operatorname{proj}_{\mathbf{u}} \overrightarrow{B D}=\frac{\overrightarrow{B D} \cdot \mathbf{u}}{\|\mathbf{u}\|^{2}} \mathbf{u}=\frac{-14 p-2 q}{1^{2}} \mathbf{u}=(-14 p-2 q) \mathbf{u}
\end{array}$$

As discussed above, the magnitudes of these projections are equal. We have $\|\mathbf{u}\|=\|\mathbf{v}\|=1$, so the magnitudes of these projections are $|-8 q-12 p|$ and $|-14 p-2 q|$. If these are equal, then we have either $-8 q-12 p=-14 p-2 q$ or $-(-8 q-12 p)=-14 p-2 q$. The first gives $p=3 q$ and the second gives $13 p=-5 q$. So, we have
$$\binom{p}{q}=\frac{1}{\sqrt{1^{2}+3^{2}}}\binom{3}{1} \quad \text { or } \quad\binom{p}{q}=\frac{1}{\sqrt{(-5)^{2}+13^{2}}}\binom{-5}{13} .$$
(Remember, $\binom{p}{q}$ is a unit vector.) A quick sketch of both cases tells us which we want, and exhibits the interesting result that if there's a second square such that each of the given points is on a different extended side of the square.
$$\binom{p}{q}=\frac{1}{\sqrt{1^{2}+3^{2}}}\binom{3}{1}$$
$$\binom{p}{q}=\frac{1}{\sqrt{(-5)^{2}+13^{2}}}\binom{-5}{13}$$

We have $p=3 / \sqrt{10}$ and $q=1 / \sqrt{10}$ in the case in which $A, B, C$, and $D$ are on the sides of the square themselves (rather than the extensions of the side). The side length of the square equals the magnitude of the projection found above, or $|-8 q-12 p|=44 / \sqrt{10}$. Therefore, the area of the square is $(44 / \sqrt{10})^{2}=193.6$.
(Note that we can also take $\binom{p}{q}$ to be the negatives of the direction vectors found above, and doing so leads to the same two squares.)

478

---

<!-- Page 479 -->

13.3★. VECTORS, COMPLEX NUMBERS, AND CHALLENGING PROBLEMS

Sidenote: The triangle relationships we developed in the previous section using vectors also hold in complex numbers. Let $a, b$, and $c$ be complex numbers that correspond to the respective vertices of $\triangle A B C$ in the complex plane. Then, the centroid of $\triangle A B C$ is $(a+b+c) / 3$. If the origin is the circumcenter of $\triangle A B C$, then the orthocenter of $\triangle A B C$ is $a+b+c$ and the center of the nine-point circle of $\triangle A B C$ is $(a+b+c) / 2$.

Problem 13.14: Points $P$ and $Q$ are on sides $\overline{A B}$ and $\overline{A C}$ of equilateral triangle $A B C$ such that $\overline{P Q} \| \overline{B C}$. Show that if $M$ is the midpoint of $\overline{P C}$ and $T$ is the centroid of $\triangle A P Q$, then $\triangle T M B$ is a 30-60-90 triangle.

Solution for Problem 13.14: We have complex number tools for dealing with equilateral triangles, so we'll start with complex numbers. As usual, we denote the complex number corresponding to each point with the lowercase version of the uppercase letter used to label the point. We let $A$ be the origin, so equilateral triangle $A B C$ gives us $b=\zeta c$, where $\zeta$ is a primitive sixth root of unity. Since $\overline{P Q} \| \overline{B C}$, we have $\angle A P Q=\angle A B C$ and $\angle A Q P=\angle A C B$, which means $\triangle A P Q$ is equilateral, too. Therefore, the same rotation that maps $C$ to $B$ also maps $Q$ to $P$, which means that $p=\zeta q$. Moreover, $Q$ is a dilation of $C$ about the origin, so there's some real constant $k$ such that $q=k c$. Therefore, we
have $p=\zeta k c$, and we now have $b, p$, and $q$ in terms of $c$.

The only points we haven't tackled yet are $M$ and $T$. Since $M$ is the midpoint of $\overline{P C}$, we have
$$m=\frac{p+c}{2}=\frac{(\zeta k+1) c}{2}$$

Since $T$ is the centroid of $\triangle A P Q$, we have
$$t=\frac{a+p+q}{3}=\frac{0+k c+\zeta k c}{3}=\frac{(1+\zeta) k c}{3} .$$

Looking at our diagram, it appears that if $\triangle T M B$ is a 30-60-90 triangle, then $\angle T M B=90^{\circ}$ and $\angle M T B=60^{\circ}$. We could use our usual complex number tools to show separately that $|b-t|=2|m-t|$ and $\bar{B} \bar{M} \perp \overline{T M}$, and thereby deduce that $\triangle T M B$ is a 30-60-90 triangle. Instead, we note that we can prove that $\triangle T M B$ is a 30-60-90 triangle in one step if we show that $b-t=2 \zeta(m-t)$, since this equation would tell us that $B T=2 M T$ and that a $60^{\circ}$ rotation about $T$ (with the same orientation as the rotation we used to map $C$ to $B$ ) maps $\overrightarrow{T M}$ to $\overrightarrow{T B}$. From this, we can deduce that $\triangle T M B$ is a 30-60-90 triangle with $\angle B T M=60^{\circ}$ and $\angle B M T=90^{\circ}$.

Now that we have a plan, it's time to execute it:
$$2 \zeta(m-t)=2 \zeta\left(\frac{(\zeta k+1) c}{2}-\frac{(1+\zeta) k c}{3}\right)=2 c \zeta\left(\frac{3(\zeta k+1)-2(1+\zeta) k}{6}\right)=\frac{c \zeta}{3}(\zeta k+3-2 k)$$
and
$$b-t=\zeta c-\frac{(1+\zeta) k c}{3}=\frac{3 \zeta c-k c-\zeta k c}{3}=\frac{c}{3}(3 \zeta-k-\zeta k) .$$

To see that these are equal, we'll have to use the fact that $\zeta^{2}=\zeta-1$ for either primitive sixth root of unity:
$$2 \zeta(m-t)=\frac{c \zeta}{3}(\zeta k+3-2 k)=\frac{c}{3}\left(\zeta^{2} k+3 \zeta-2 k \zeta\right)=\frac{c}{3}((\zeta-1) k+3 \zeta-2 k \zeta)=\frac{c}{3}(3 \zeta-k-k \zeta) .$$

This equals our expression for $b-t$ above, so $b-t=2 \zeta(m-t)$, which means that $\angle B T M=60^{\circ}$ and $B T=2 M T$. Therefore, triangle TMB is a 30-60-90 triangle.

479

---

<!-- Page 480 -->

CHAPTER 13. VECTOR GEOMETRY

Vectors give us another way to think about some applications of complex numbers to geometry problems. For some people, it is much more natural to think of rotating $\overrightarrow{T M}$ by $60^{\circ}$ about $T$ to get a vector in the direction of $\overrightarrow{B T}$ than it is to think of rotating $m$ by $60^{\circ}$ about $t$ to get a complex number that is on the ray from $t$ through $b$. One way to tie these two ideas together is to associate each complex number with a vector from the origin to the corresponding point in the complex plane. So, $T \vec{M}$ is the vector from $t$ to $m$ in the complex plane. Since $\overrightarrow{T M}=\vec{M}-\vec{T}$, we associate $T \vec{M}$ with the complex number $m-t$.

With this in mind, you might realize that you want to show that $b-t=2 \zeta(m-t)$ by thinking, "Triangle TMB is a $30-60-90$ triangle if $\angle M T B=60^{\circ}$ and $B T=2 M T$. So, if rotating $m-t$ by $60^{\circ}$ and then scaling the result by a factor of 2 produces $b-t$, then $\triangle T M B$ is a 30-60-90 triangle. Therefore, we wish to show that $b-t=2 \zeta(m-t)$, where the factor of $\zeta$ provides the rotation and the 2 provides the scaling."

Problem 13.15: Way back on page 185, we helped Petr figure how long his trip to Honolulu would be by finding the distance along the surface of the earth from his home city of Petropavlovsk-Kamchatsky, which has coordinates $52.92^{\circ} \mathrm{N}, 158.49^{\circ} \mathrm{E}$, to Honolulu, which has coordinates $21.31^{\circ} \mathrm{N}, 157.83^{\circ} \mathrm{W}$. Before he left on his trip, he tried to look up the distance between the two cities on the internet. He found a formula that said the distance between points $P$ and $Q$ on the Earth is $\alpha R$, where $R$ is the radius of the Earth and $\alpha$ is the angle such that $0 \leq \alpha \leq \pi$ and
$$\cos \alpha=\cos \lambda_{P} \cos \lambda_{Q} \cos (\Delta \beta)+\sin \lambda_{P} \sin \lambda_{Q}$$

Unfortunately, he couldn't find any information about what the symbols $\lambda_{P}, \lambda_{Q}$, and $\Delta \beta$ mean. Help Petr by figuring out what this formula is all about.

Solution for Problem 13.15: The key to our solution to the earlier problem was finding the angle formed by connecting each city to the center of the Earth. Vectors give us a nice tool for finding angles: the dot product. In order to use the dot product, we'll have to use the rectangular coordinates of the cities. However, the latitude and longitude are in terms of coordinates that are essentially spherical. So, we'll start with spherical coordinates for the cities and convert them into rectangular coordinates. Let the spherical coordinates of cities $P$ and $Q$ be ( $R, \theta_{P}, \phi_{P}$ ) and ( $R, \theta_{Q}, \phi_{Q}$ ), where $R$ is the radius of the Earth. Converting these to rectangular coordinates, city $P$ is at ( $R \cos \theta_{P} \sin \phi_{P}, R \sin \theta_{P} \sin \phi_{P}, R \cos \phi_{P}$ ) and city $Q$ is at ( $R \cos \theta_{Q} \sin \phi_{Q}, R \sin \theta_{Q} \sin \phi_{Q}, R \cos \phi_{Q}$ ). Letting the center of the Earth be the origin, we have
$$\vec{P} \cdot \vec{Q}=\|\vec{P}\|\|\vec{Q}\| \cos \alpha=R^{2} \cos \alpha,$$
where $\alpha$ is the angle between $\vec{P}$ and $\vec{Q}$. Computing the dot product gives
$$\begin{aligned}
\vec{P} \cdot \vec{Q} & =\left(R \cos \theta_{P} \sin \phi_{P}\right)\left(R \cos \theta_{Q} \sin \phi_{Q}\right)+\left(R \sin \theta_{P} \sin \phi_{P}\right)\left(R \sin \theta_{Q} \sin \phi_{Q}\right)+\left(R \cos \phi_{P}\right)\left(R \cos \phi_{Q}\right) \\
& =R^{2}\left(\cos \theta_{P} \sin \phi_{P} \cos \theta_{Q} \sin \phi_{Q}+\sin \theta_{P} \sin \phi_{P} \sin \theta_{Q} \sin \phi_{Q}+\cos \phi_{P} \cos \phi_{Q}\right) \\
& =R^{2}\left(\left(\sin \phi_{P} \sin \phi_{Q}\right)\left(\cos \theta_{P} \cos \theta_{Q}+\sin \theta_{P} \sin \theta_{Q}\right)+\cos \phi_{P} \cos \phi_{Q}\right) \\
& =R^{2}\left(\left(\sin \phi_{P} \sin \phi_{Q}\right) \cos \left(\theta_{P}-\theta_{Q}\right)+\cos \phi_{P} \cos \phi_{Q}\right)
\end{aligned}$$

Substituting this into the equation above for $\vec{P} \cdot \vec{Q}$, we have
$$R^{2}\left(\left(\sin \phi_{P} \sin \phi_{Q}\right) \cos \left(\theta_{P}-\theta_{Q}\right)+\cos \phi_{P} \cos \phi_{Q}\right)=R^{2} \cos \alpha .$$

Dividing by $R^{2}$ gives
$$\cos \alpha=\sin \phi_{P} \sin \phi_{Q} \cos \left(\theta_{P}-\theta_{Q}\right)+\cos \phi_{P} \cos \phi_{Q} .$$

This looks very close to the formula Petr found, which is
$$\cos \alpha=\cos \lambda_{P} \cos \lambda_{Q} \cos (\Delta \beta)+\sin \lambda_{P} \sin \lambda_{Q}$$

480

---

<!-- Page 481 -->

13.3★. VECTORS, COMPLEX NUMBERS, AND CHALLENGING PROBLEMS

Right away, we suspect that $\Delta \beta=\theta_{P}-\theta_{Q}$. Since the $\theta$ coordinates in spherical coordinates are essentially the same as longitude, we can take the $\Delta \beta$ to be the difference in longitude between $P$ and $Q$.

Turning to the relationship between the $\phi$ angles and the $\lambda$ angles, we see that for these angles, Petr's formula has cosines where ours has sines, and vice versa. We unravel this mystery by recalling the relationship between latitude and the $\phi$-coordinate of spherical coordinates. If $P$ is in the Southern hemisphere and $O$ is the center of the Earth, then the angle $\overline{\mathrm{OP}}$ makes with the upper half of the Earth's axis ( $\phi_{P}$ in spherical coordinates) is $90^{\circ}$ plus the latitude of $P$. If $P$ is in the Northern hemisphere, then the angle $\overline{O P}$ makes with the upper half of the Earth's axis is $90^{\circ}$ minus the latitude of $P$. Taking $\lambda_{P}$ to be the latitude of $P$, where we let $\lambda_{P}>0$ for points in the Northern hemisphere and $\lambda_{P}<0$ for points in the Southern hemisphere, we have $\phi_{P}=90^{\circ}-\lambda_{P}$. Therefore, we have $\cos \phi_{P}=\sin \lambda_{P}$ and $\sin \phi_{P}=\cos \lambda_{P}$, so Equation (13.1) becomes
$$\cos \alpha=\cos \lambda_{P} \cos \lambda_{Q} \cos (\Delta \beta)+\sin \lambda_{P} \sin \lambda_{Q}$$
and the mystery of Petr's formula is solved.
Problem 13.16: Let $O$ be the center of the circumcircle $\Gamma$ of a regular polygon $A_{1} A_{2} A_{3} \cdots A_{25} A_{26}$ with 26 sides. Let $\mathrm{O}_{1}$ and $\mathrm{O}_{2}$ be the reflections of O over $\overline{A_{25} A_{1}}$ and $\overline{A_{2} A_{6}}$, respectively. Prove that $\overline{O_{1} O_{2}}$ is equal in length to a side of an equilateral triangle inscribed in $\Gamma$.

Solution for Problem 13.16: Our main clue to start with complex numbers is the regular polygon. We place the problem in the complex plane by letting $O$ be the origin and letting $A_{k}$ correspond to $\underline{e^{k \pi i / 13}}$ for $1 \leq k \leq 26$. So, if we let $\omega=e^{\pi i / 13}$, then $A_{k}$ corresponds to $\omega^{k}$. Since $O_{1}$ is the reflection of the origin over $\overline{A_{25} A_{1}}$, the midpoint of $\overline{A_{25} A_{1}}$ is the midpoint of $\overline{\mathrm{OO}_{1}}$. Therefore, $\mathrm{O}_{1}$ is the dilation of this midpoint about the the origin with scale factor 2 . The midpoint of $\overline{A_{25} A_{1}}$ is $\left(\omega^{25}+\omega\right) / 2$, so $O_{1}$ corresponds to twice this number, or $\omega^{25}+\omega$. Similarly, $O_{2}$ corresponds to $\omega^{6}+\omega^{2}$.

We wish to show that $O_{1} O_{2}$ equals the length of a side of an equilateral triangle inscribed in the circle. The radius of the circle is 1 , so the side length of an equilateral triangle inscribed in the circle is $\sqrt{3}$. We have $O_{1} O_{2}=\left|\omega^{6}+\omega^{2}-\left(\omega^{25}+\omega\right)\right|$, so we now must show that
$$\left|\omega^{6}+\omega^{2}-\omega^{25}-\omega\right|=\sqrt{3}$$

We'll look at $O_{1} O_{2}^{2}$, since we can use the fact that $|z|^{2}=z \bar{z}$ to work with our scary expression for $O_{1} O_{2}$. We have
$$O_{1} O_{2}^{2}=\left(\omega^{6}+\omega^{2}-\omega^{25}-\omega\right) \overline{\left(\omega^{6}+\omega^{2}-\omega^{25}-\omega\right)}=\left(\omega^{6}+\omega^{2}-\omega^{25}-\omega\right)\left(\bar{\omega}^{6}+\bar{\omega}^{2}-\bar{\omega}^{25}-\bar{\omega}\right)$$

That looks plenty terrifying to expand, but before we start doing so, we make a few simplifying observations. First, because $\left|\omega^{k}\right|=1$, we have $\omega^{k} \bar{\omega}^{k}=1$, which means $\bar{\omega}^{k}=\frac{1}{\omega^{k}}$. Since $\omega^{26}=1$, we have
$$\bar{\omega}^{k}=\frac{1}{\omega^{k}}=\frac{\omega^{26}}{\omega^{k}}=\omega^{26-k}$$
(See if you can find a geometric explanation for this relationship.) Applying this to the terms in the second factor of our expression for $\mathrm{O}_{1} \mathrm{O}_{2}^{2}$ gets rid of the conjugates and leaves
$$O_{1} O_{2}^{2}=\left(\omega^{6}+\omega^{2}-\omega^{25}-\omega\right)\left(\omega^{20}+\omega^{24}-\omega-\omega^{25}\right)$$

Next, we note that every vertex of the polygon is diametrically opposite another vertex of the polygon, and is 13 vertices away from its opposite. So, rotating one vertex by $\pi$ around the origin gives a vertex that is 13 vertices away from the original vertex. In complex numbers, we write this as $\omega^{k}=-\omega^{k-13}$. Another way to see this is to note that $\omega^{13}=\left(e^{\pi i / 13}\right)^{13}=e^{\pi i}=-1$, so $\omega^{k}=\omega^{k-13} \cdot \omega^{13}=-\omega^{k-13}$. Applying this relationship to every term in the expression with exponent 13 or greater, we have
$$O_{1} O_{2}^{2}=\left(\omega^{6}+\omega^{2}+\omega^{12}-\omega\right)\left(-\omega^{7}-\omega^{11}-\omega+\omega^{12}\right)$$

481

---

<!-- Page 482 -->

CHAPTER 13. VECTOR GEOMETRY

Now, we're ready to expand, keeping in mind the simplification $\omega^{k}=-\omega^{k-13}$ whenever we see a power of $\omega$ greater than 12 . We find
$$\begin{aligned}
O_{1} O_{2}^{2}= & \left(\omega^{6}+\omega^{2}+\omega^{12}-\omega\right)\left(-\omega^{7}-\omega^{11}-\omega+\omega^{12}\right) \\
= & \omega^{6}\left(-\omega^{7}-\omega^{11}-\omega+\omega^{12}\right)+\omega^{2}\left(-\omega^{7}-\omega^{11}-\omega+\omega^{12}\right) \\
& \quad+\omega^{12}\left(-\omega^{7}-\omega^{11}-\omega+\omega^{12}\right)-\omega\left(-\omega^{7}-\omega^{11}-\omega+\omega^{12}\right) \\
= & \left(-\omega^{13}-\omega^{17}-\omega^{7}+\omega^{18}\right)+\left(-\omega^{9}-\omega^{13}-\omega^{3}+\omega^{14}\right) \\
& \quad+\left(-\omega^{19}-\omega^{23}-\omega^{13}+\omega^{24}\right)+\left(\omega^{8}+\omega^{12}+\omega^{2}-\omega^{13}\right) \\
= & \left(1+\omega^{4}-\omega^{7}-\omega^{5}\right)+\left(-\omega^{9}+1-\omega^{3}-\omega\right) \\
& \quad+\left(\omega^{6}+\omega^{10}+1-\omega^{11}\right)+\left(\omega^{8}+\omega^{12}+\omega^{2}+1\right) \\
= & 4+\omega^{12}-\omega^{11}+\omega^{10}-\omega^{9}+\omega^{8}-\omega^{7}+\omega^{6}-\omega^{5}+\omega^{4}-\omega^{3}+\omega^{2}-\omega
\end{aligned}$$

That's quite a compelling expression! We can simplify it either by recognizing it as geometric series with common ratio $-\omega$, or by recalling the factorization
$$\omega^{13}+1=(\omega+1)\left(\omega^{12}-\omega^{11}+\omega^{10}-\omega^{9}+\omega^{8}-\omega^{7}+\omega^{6}-\omega^{5}+\omega^{4}-\omega^{3}+\omega^{2}-\omega+1\right)$$

Since we have $\omega^{13}=-1$ but $\omega \neq 1$, the factorization above gives us
$$0=\omega^{12}-\omega^{11}+\omega^{10}-\omega^{9}+\omega^{8}-\omega^{7}+\omega^{6}-\omega^{5}+\omega^{4}-\omega^{3}+\omega^{2}-\omega+1,$$
so $\omega^{12}-\omega^{11}+\omega^{10}-\omega^{9}+\omega^{8}-\omega^{7}+\omega^{6}-\omega^{5}+\omega^{4}-\omega^{3}+\omega^{2}-\omega=-1$. Substituting this into our expression for $O_{1} O_{2}^{2}$ gives $O_{1} O_{2}^{2}=4-1=3$, so $O_{1} O_{2}=\sqrt{3}$, as desired.

Concept: Sometimes persistent algebraic manipulation can tackle hard geometry problems
when your geometric instincts fail you.

That said, don't always reach for complex numbers or vectors right away when you see a geometry problem.

> WARNING!! Unless you very quickly see that vectors or complex numbers can be used to A solve a particular geometry problem, you should usually spend some time trying to apply geometric tools to the problem before reaching for algebraic tools.

Problem 13.17: Let $A B C D E F$ be a convex hexagon with $A B=B C, C D=D E$, and $E F=F A$. Show that the lines containing the altitudes of triangles $B C D, D E F$, and $F A B$ from $C, E$, and $A$, respectively, are concurrent.
(Source: Poland)

Solution for Problem 13.17: The condition for perpendicularity in vectors is a little easier to work with than the condition we have for complex numbers, so we'll try applying vectors to the problem. We'll let $X$ be the intersection of the altitudes from $C$ and $E$, and our goal is to prove that $X$ is on the altitude from $A$, as well. Since $X$ is on the altitudes from $C$ and $E$ to $\overline{B D}$ and $\overline{D F}$, respectively, we have $\overrightarrow{C X} \cdot \overrightarrow{B D}=0$ and $\overrightarrow{E X} \cdot \overrightarrow{D F}=0$. We'd like to prove that $\overrightarrow{A X} \cdot \overrightarrow{F B}=0$. Since there are many points in common in each of these statements, we write each vector as a vector difference, hoping to be able to find some convenient ways to combine the equations:
$$\begin{array}{l}
(\vec{X}-\vec{C}) \cdot(\vec{D}-\vec{B})=0 \\
(\vec{X}-\vec{E}) \cdot(\vec{F}-\vec{D})=0
\end{array}$$

482

---

<!-- Page 483 -->

13.3★. VECTORS, COMPLEX NUMBERS, AND CHALLENGING PROBLEMS

It's tempting at this point to choose $X$ to be the origin, but the conditions $A B=B C, C D=D E$, and $E F=F A$ give us pause. It's not clear how we would use these conditions if $X$ were the origin. (That said, it is possible to finish the problem with $X$ as the origin! See if you can find such a solution on your own.) Rather than choose our origin right away, we'll continue with the problem, hoping that we'll find a choice of origin that allows us to use the given equal lengths effectively.

Our hopes of combining the two dot products above to show that $(\vec{X}-\vec{A}) \cdot(\vec{B}-\vec{F})=0$ appear to be dashed-there are no instances of $\vec{A}$ in the first two equations, and it's not clear how to introduce $\vec{A}$ and get rid of $\vec{E}$ and $\vec{C}$. We do at least see that we'll get some cancellation if we expand and add the left sides, since the $\vec{X} \cdot \vec{D}$ in the first equation will cancel with the $-\vec{X} \cdot \vec{D}$ in the second. But the rest will be a mess.

The symmetry of the problem suggests that we go ahead and include the desired dot product:
$$\begin{array}{l}
(\vec{X}-\vec{C}) \cdot(\vec{D}-\vec{B})=0 \\
(\vec{X}-\vec{E}) \cdot(\vec{F}-\vec{D})=0 \\
(\vec{X}-\vec{A}) \cdot(\vec{B}-\vec{F})=k
\end{array}$$

Our goal is to show that $k=0$. Again, note that we've set up these equations to have a convenient symmetry. This symmetry would have been obscured if we had written the equations in the equivalent forms:
$$\begin{array}{l}
(\vec{C}-\vec{X}) \cdot(\vec{D}-\vec{B})=0 \\
(\vec{X}-\vec{E}) \cdot(\vec{D}-\vec{F})=0 \\
(\vec{A}-\vec{X}) \cdot(\vec{F}-\vec{B})=k
\end{array}$$

Concept: When you have options for how to set up parts of a problem, do so in a way that allows you to exploit symmetry where possible.

Returning to the equations
$$\begin{array}{l}
(\vec{X}-\vec{C}) \cdot(\vec{D}-\vec{B})=0 \\
(\vec{X}-\vec{E}) \cdot(\vec{F}-\vec{D})=0 \\
(\vec{X}-\vec{A}) \cdot(\vec{B}-\vec{F})=k
\end{array}$$
we see that if we expand the dot products on the left and add all the results, all of the terms with $\vec{X}$ will cancel, and we'll be left with
$$-\vec{C} \cdot(\vec{D}-\vec{B})-\vec{E} \cdot(\vec{F}-\vec{D})-\vec{A} \cdot(\vec{B}-\vec{F})=k .$$

We'd like to show that the left side is 0 , but in this form, it's not clear how to. Expanding everything on the left side won't offer any cancellation. However, we could group the terms on the left side by $\vec{B}, \vec{D}$, and $\vec{F}$ instead of by $\vec{A}, \vec{C}$, and $\vec{E}$.

Concept: A different way of looking at the same information can offer important insights.

Grouping the terms by $\vec{B}, \vec{D}$, and $\vec{F}$ gives
$$k=-\vec{C} \cdot(\vec{D}-\vec{B})-\vec{E} \cdot(\vec{F}-\vec{D})-\vec{A} \cdot(\vec{B}-\vec{F})=\vec{B} \cdot(\vec{C}-\vec{A})+\vec{D} \cdot(\vec{E}-\vec{C})+\vec{F} \cdot(\vec{A}-\vec{E}) .$$

OK, maybe that's not so helpful, either. We seem stuck.

483

---

<!-- Page 484 -->

CHAPTER 13. VECTOR GEOMETRY

Concept: When stuck on a problem, focus information in the problem that you haven't used yet.

We haven't used the side equalities. What can we deduce from $A B=B C$ ? We can deduce that $B$ is on the perpendicular bisector of $\overline{A C}$. Similarly, $D$ is on the perpendicular bisector of $\overline{C E}$ and $F$ is on the perpendicular bisector of $\overline{A E}$. Aha! There's a point on all three of these perpendicular bisectors-the circumcenter of $\triangle A C E$ ! Looking back at our expressions above, we see that this observation solves the problem. If we choose the circumcenter of $\triangle A C E$ to be the origin, then $\overleftrightarrow{O B} \perp \overline{A C}, \overleftrightarrow{O D} \perp \overline{C E}$, and $\overleftrightarrow{O F} \perp \overline{E A}$, so we have
$$\vec{B} \cdot \overrightarrow{A C}=\vec{D} \cdot \overrightarrow{C E}=\vec{F} \cdot \overrightarrow{E A}=0 .$$

Applying these to Equation (13.2), we have
$$k=\vec{B} \cdot(\vec{C}-\vec{A})+\vec{D} \cdot(\vec{E}-\vec{C})+\vec{F} \cdot(\vec{A}-\vec{E})=\vec{B} \cdot \overrightarrow{A C}+\vec{D} \cdot \overrightarrow{C E}+\vec{F} \cdot \overrightarrow{E A}=0 .$$

Since $\overrightarrow{A X} \cdot \overrightarrow{F B}=k=0$, point $X$ is also on the altitude from $A$ to $\overline{F B}$. Therefore, the three altitudes described in the problem are concurrent.

Problem 13.18: Prove that the area of a triangle with side lengths $a, b$, and $c$ is
$$\sqrt{s(s-a)(s-b)(s-c)}$$
where $s=(a+b+c) / 2$ is the semiperimeter of the triangle.

Sidenote: Art of Problem Solving Community member Miles Dillon Edwards produced the following dazzling proof of Heron's formula while still in high school. His proof was published in the American Mathematical Monthly in 2008.

Solution for Problem 13.18: We need to prove a formula for the area of a triangle that involves the semiperimeter. We already have one such formula: the area of a triangle equals its semiperimeter times the radius of its incircle (which we call the inradius). So, we start with the diagram at right, in which the angle bisectors of $\triangle A B C$ meet at the incenter, $I$, as shown. We connect the incenter to the three vertices and to the points at which the incircle is tangent to the sides of the triangle, forming three pairs of congruent right triangles, such as $\triangle A F I$ and $\triangle A E I$. We label the pairs of equal angles at $I$ as shown, as well as the equal tangents from the vertices.

We let the radius of the circle be $r$, and we label the distances from $I$ to
the vertices as shown. Adding all the angles at $I$ gives us $\alpha+\beta+\gamma=\pi$, since all six angles at $I$ must sum to $2 \pi$. That's a pretty convenient angle. Multiplying complex numbers leads to adding angles. Maybe we can tackle this problem with complex numbers.

We'll need complex numbers with arguments $\alpha, \beta$, and $\gamma$. In right triangle $I E A$, we have $r^{2}+x^{2}=u^{2}$ and $\tan \alpha=\frac{x}{r}$, so the complex number $r+x i$ has magnitude $u$ and argument $\alpha$. In other words, we have $r+x i=u e^{i \alpha}$. Similarly, we have $r+y i=v e^{i \beta}$ from $\triangle B F I$ and $r+z i=w e^{i \gamma}$ from $\triangle C D I$.

Our purpose in finding these complex numbers was to multiply them, and thereby add their arguments:
$$(r+x i)(r+y i)(r+z i)=\left(u e^{i \alpha}\right)\left(v e^{i \beta}\right)\left(w e^{i \gamma}\right)=u v w e^{i(\alpha+\beta+\gamma)} .$$

484

---

<!-- Page 485 -->

13.4. SUMMARY

Since $\alpha+\beta+\gamma=\pi$, we have
$$(r+x i)(r+y i)(r+z i)=u v w e^{\pi i}=-u v w,$$
which means that $(r+x i)(r+y i)(r+z i)$ is real. Therefore, the imaginary part of this expression is 0 . Expanding this product yields gives
$$\operatorname{Im}((r+x i)(r+y i)(r+z i))=r^{2}(x+y+z)-x y z .$$

Since this equals 0 , we have
$$r=\sqrt{\frac{x y z}{x+y+z}} .$$

Since the perimeter of $\triangle A B C$ is $2(x+y+z)$, we have $x+y+z=s$. Letting $a=B C, b=A C$, and $c=A B$, we have $a=y+z, b=x+z$, and $c=x+y$. Therefore, we have $x=s-y-z=s-(y+z)=s-a$. Similarly, we find $y=s-b$ and $z=s-c$. So, we have
$$r=\sqrt{\frac{(s-a)(s-b)(s-c)}{s}} .$$

We finish by noting that the area of $\triangle A B C$ is the sum of the areas of $\triangle I A B, \triangle I A C$, and $\triangle I B C$, which is
$$\frac{r a}{2}+\frac{r b}{2}+\frac{r c}{2}=r\left(\frac{a+b+c}{2}\right)=r s=\sqrt{s(s-a)(s-b)(s-c)} .$$

This formula is known as Heron's Formula.
13.4 Summary

Things To Watch Out For! 

WARNING!!
- We have $\overrightarrow{A B}=\vec{B}-\vec{A}$, not $\overrightarrow{A B}=\vec{A}-\vec{B}$.
- Let $H$ be the orthocenter of $\triangle A B C$. We proved that if the circumcenter of $\triangle A B C$ is the origin, then $\vec{H}=\vec{A}+\vec{B}+\vec{C}$. If the circumcenter of $\triangle A B C$ is not the origin, then we cannot conclude that $\vec{H}=\vec{A}+\vec{B}+\vec{C}$.

485

---

<!-- Page 486 -->

CHAPTER 13. VECTOR GEOMETRY

Problem Solving Strategies

Concepts:
- Choosing your origin wisely can greatly simplify the application of vectors to geometry problems.
- When stuck on a problem, look back at the problem for any information you haven't used.
- When applying vectors to a problem involving a triangle, choosing the circumcenter as the origin can greatly simplify the problem.
- Don't overlook "guess-and-check" as a strategy, even in advanced problems. Guessing and then confirming that your guess is correct has a long and glorious history in mathematics and science.
- Precise diagrams can help you discover important relationships in geometry problems.
- Sometimes persistent algebraic manipulation can tackle hard geometry problems when your geometric instincts fail you.
- When you have options for how to set up parts of a problem, do so in a way that allows you to exploit symmetry where possible.
- A different way of looking at the same information can offer important insights.

Challenge Problems
13.19 Show that for any points $W, X, Y$, and $Z$, we have $W X^{2}+Y Z^{2}-X Y^{2}-Z W^{2}=2 \overrightarrow{W Y} \cdot \overrightarrow{Z X}$.
13.20 Use vectors to show that the sum of the squares of the side lengths of a quadrilateral equals the sum of the squares of the diagonals of the quadrilateral if and only if the quadrilateral is a parallelogram.
13.21 In tetrahedron $A B C D$, points $M, N, P, Q, R$, and $S$ are the midpoints of $\overline{A B}, \overline{C D}, \overline{A C}, \overline{B D}, \overline{A D}$, and $\overline{B C}$, respectively. Show that $\overleftrightarrow{M N}, \overleftrightarrow{P Q}$, and $\overleftrightarrow{R S}$ are concurrent. Hints: 57
13.22 Let the diagonals of $A B C D$ meet at $X$. Show that if
$$A B^{2}+B C^{2}+C D^{2}+D A^{2}=2\left(A X^{2}+B X^{2}+C X^{2}+D X^{2}\right) .$$
then either the diagonals of $A B C D$ are perpendicular or one of the diagonals bisects the other. Hints: 15
13.23 Mr. Assumption was trying to find the orthocenter of the triangle with vertices $(4,-3),(2,-1)$, and $(-1,5)$. Here's what he wrote: "If $\triangle A B C$ is a triangle, then the orthocenter $H$ satisfies $\vec{H}=\vec{A}+\vec{B}+\vec{C}$. So, we get the orthocenter by simply adding the coordinates: $(4+2-1,-3-1+5)=(5,-1)$." What mistake did Mr. Assumption make?
13.24 Let $O$ be the circumcenter of $\triangle A B C$. Let $M$ be the midpoint of $\overline{A B}$, and let $X$ be the centroid of $\triangle A C M$. Show that $\overleftrightarrow{C M} \perp \overleftrightarrow{S X}$ if and only if $A B=A C$.
13.25 Let $A B C D$ be a cyclic quadrilateral (a quadrilateral that is inscribed in a circle). Show that the orthocenters of $A B C, B C D, C D A$, and $D A B$ are the vertices of a quadrilateral that is congruent to $A B C D$.

486

---

<!-- Page 487 -->

CHALLENGE PROBLEMS
13.26 Let $O, H$, and $R$ be the circumcenter, orthocenter, and circumradius, respectively, of $\triangle A B C$.
(a) Show that $O H^{2}=R^{2}(3+2(\cos 2 A+\cos 2 B+\cos 2 C))$. Hints: 224
(b) Show that in any $\triangle A B C$, we have $\cos ^{2} A+\cos ^{2} B+\cos ^{2} C \geq \frac{3}{4}$. Hints: 82
13.27 Let point $X$ be any point inside $\triangle A B C$. Through the midpoints of $\overline{A B}, \overline{B C}$, and $\overline{C A}$, we draw lines that are parallel to $\overline{X C}, \overline{X A}$, and $\overline{X B}$, respectively. Show that these three lines are concurrent. Hints: 64
13.28 Points $U, V, W, X, Y$, and $Z$ are the centroids of triangles $A B C, B C D, C D E, D E F, E F A$, and $F A B$, respectively, in convex hexagon $A B C D E F$. Show that each pair of opposite sides of hexagon $U V W X Y Z$ are parallel and equal in length.
13.29 In tetrahedron $A B C D$, the angle $\angle B D C$ is a right angle and the foot of the perpendicular from $D$ to $A B C$ is the intersection of the altitudes of $\triangle A B C$. Show that $\angle A D B=\angle A D C=90^{\circ}$. (Source:IMO) Hints: 215,258
13.30 Harrison wants to construct a hexagon such that the midpoints of its edges have coordinates $(0,0),(5,0)$, $(6,2),(4,4),(2,4)$, and $(-2,3)$, in no particular order. Can he do this? If so, how? Hints: 232
13.31 Describe the set of points $X$ that satisfy $\overrightarrow{A X} \cdot \overrightarrow{C X}=\overrightarrow{C B} \cdot \overrightarrow{A X}$, where $A, B$, and $C$ are three different points.
13.32 Regular polygon $P_{1} P_{2} P_{3} \cdots P_{n}$ is inscribed in a circle with center $C$ and radius $r$. Show that for any point $X$, we have
$$\left(P_{1} X\right)^{2}+\left(P_{2} X\right)^{2}+\left(P_{3} X\right)^{2}+\cdots+\left(P_{n} X\right)^{2}=n\left(r^{2}+C X^{2}\right)$$
13.33 Vertex $A$ of the acute triangle $A B C$ is equidistant from the circumcenter $O$ and the orthocenter $H$ of $\triangle A B C$. Determine all possible values for the measure of angle $A$. (Source: IMO) Hints: 234
13.34 Three vertices of a regular octahedron are at $(2,6,-8),(6,4,-4)$, and $(4,8,0)$. Find the coordinates of the other three vertices of the octahedron. Hints: $114,43,173$
13.35 Let $a$ and $b$ be complex numbers. Show that the area of the parallelogram in the complex plane with consecutive vertices at the origin, $a$, and $b$, is $\left|\frac{1}{2}(a \bar{b}-\bar{a} b)\right|$. Hints: 167, 196
13.36★ In tetrahedron $A B C D$, we have $A B=C D=6, A C=B D=8$, and $A D=B C$. Let $X$ be the centroid of $\triangle B C D$ and $Y$ be the centroid of $\triangle A B C$. Find $A D$ if $\overline{A X} \perp \overline{D Y}$. Hints: 251, 197
13.37 ★ A fixed point $P$ is given inside a sphere with center $O$. Three mutually perpendicular rays (meaning each pair of rays is perpendicular) from $P$ intersect the sphere at points $U, V$, and $W$. Point $Q$ is the vertex diagonally opposite to $P$ in the parallelepiped with edges $\overline{P U}, \overline{P V}$, and $\overline{P W}$. Show that $O Q$ is the same for all possible choices of the three mutually perpendicular rays from $P$. (Source: IMO)
$13.38 \star \overline{W Y}$ and $\overline{X Z}$ intersect at $O$. Points $G_{1}$ and $G_{2}$ are the centroids of triangles $W X O$ and $Y Z O$, and points $H_{1}$ and $H_{2}$ are the orthocenters of XYO and ZWO. Show that $\overline{G_{1} G_{2}} \perp \overline{H_{1} H_{2}}$. Hints: 247, 13, 28, 200
13.39* The altitudes of tetrahedron $A B C D$ are extended externally beyond $A, B, C$, and $D$ to points $E, F, G$, and $H$, respectively, such that $A E=k / h_{a}, B F=k / h_{b}, C G=k / h_{c}$, and $H D=k / h_{d}$, where $k$ is a constant and $h_{a}$ denotes the length of the altitude of $A B C D$ from vertex $A$, and likewise for $h_{b}, h_{c}$ and $h_{d}$. Prove that the centroid of EFGH is also the centroid of $A B C D$.(Source: Canada) Hints: 100, 140
13.40★ The angles of convex hexagon $A B C D E F$ are equal. Prove that $|A B-D E|=|B C-E F|=|C D-F A|$. Hints: 180, 42
13.41★ Let $D, E$, and $F$ be on $\overline{B C}, \overline{A C}$, and $\overline{A B}$, respectively, such that $\overline{A D}, \overline{B E}$, and $\overline{C F}$ be the angle bisectors of $\triangle A B C$. If $\angle E D F=90^{\circ}$, then find all possible values of $\angle B A C$. (Source: USAMO) Hints: 201, 76
13.42 $\star$ Triangle $A B C$ is isosceles with $A B=A C$ and $B C=1 . D$ on $\overline{A B}$ such that $A D=1$ and $\angle D A C=\pi / 7$. Find CD. Hints: 154

487

---

