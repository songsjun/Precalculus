# Chapter 6: Basics of Complex Numbers

<!-- Page 192 -->

CHAPTER 6. BASICS OF COMPLEX NUMBERS

There can be very little of present-day science and technology that is not dependent on complex number in one way or another. - Keith Devlin

CHAPTER 0

Basics of Complex Numbers

The numbers we have used so far in this book are real numbers. These are the numbers that we can plot on the number line. One characteristic of a real number is that its square is nonnegative. In particular, there is no real number whose square is -1 .

But imagine that such a number exists: that there is some number whose square is -1 . This leap brings us to a rich area of mathematics that we study in the next three chapters. We use the symbol $i$ to represent a number whose square is -1 :
$$i^{2}=-1 .$$

A complex number is a number of the form $a+b i$, where $a$ and $b$ are real numbers and $i^{2}=-1$. We call $a$ the real part of $a+b i$ and we call $b$ the imaginary part. If $b \neq 0$, then $a+b i$ is nonreal. If $a=0$, then the complex number $a+b i$ is called an imaginary number. (Some sources refer to imaginary numbers as "pure imaginary.") The number 0 is both real and imaginary, and all real numbers and all imaginary numbers are complex numbers. Just as we use the symbol $\mathbb{R}$ to refer to "all real numbers," we use the symbol $\mathbb{C}$ to refer to "all complex numbers."
6.1 Complex Number Arithmetic

In this section, we cover the basic arithmetic of complex numbers. To add two complex numbers, we add their real parts and add their imaginary parts. So, the sum of the complex numbers $a+b i$ and $c+d i$ as $(a+c)+(b+d) i$. We define the product of two complex numbers such that multiplication is distributive. So, we have
$$\begin{aligned}
(a+b i)(c+d i) & =a(c+d i)+b i(c+d i) \\
& =a c+a d i+b c i+b d i^{2} \\
& =a c+a d i+b c i-b d \\
& =(a c-b d)+(a d+b c) i
\end{aligned}$$

192

---

<!-- Page 193 -->

6.1. COMPLEX NUMBER ARITHMETIC

Problems

Problem 6.1: Find all values of $z$ such that $z^{2}+81=0$.

Problem 6.2: Evaluate $i^{2009}$.
Problem 6.3: Let $w=3-2 i$ and $z=2+5 i$. Express each of the following as a single complex number:
(a) $w+z$
(c) $w z$
(b) $w-3 z$
(d) $2 w^{2} z-3 w z^{2}$

Problem 6.4: Show that complex numbers are commutative under addition and multiplication. In other words, explain why $w+z=z+w$ and $w z=z w$ for all complex numbers $w$ and $z$.

Problem 6.5:
(a) Find all real values of $k$ such that the product $(3+2 i)(3+k i)$ is a real number.
(b) Let $z=a+b i$, where $a$ and $b$ are real numbers, and let $\bar{z}=a-b i$. Prove that $z \cdot \bar{z}$ is real.

Problem 6.6: Write $\frac{2-i}{3+2 i}$ as a complex number. In other words, find real numbers $a$ and $b$ such that $\frac{2-i}{3+2 i}=a+b i$.
Problem 6.7: The multiplicative inverse of a number $z$ is the number $w$ such that $w z=1$. For example, 0.25 is the multiplicative inverse of 4 . Show that any nonzero complex number $a+b i$ has a multiplicative inverse, and express that inverse in terms of $a$ and $b$.

Problem 6.8: Find all complex numbers $z$ such that $\frac{3 z-5 i}{2 z+3}=3-2 i$.

Problem 6.1: Find all values of $z$ such that $z^{2}+81=0$.

Solution for Problem 6.1: Isolating $z$ gives $z^{2}=-81$. We might immediately see that our solutions are $z= \pm 9 i$, because $i^{2}=-1$ and both $9^{2}$ and $(-9)^{2}$ equal 81 . We could also "take the square root" of both sides of $z^{2}=-81$ and write $z= \pm \sqrt{-81}$, where $\sqrt{-81}$ is a shorthand for $i \sqrt{81}$. So, we have $z= \pm i \sqrt{81}= \pm 9 i$. Another way to think about this latter approach is to think of -81 as $9^{2} i^{2}$, since $i^{2}=-1$. Therefore, we have $z^{2}=(9 i)^{2}$, from which we have $z= \pm 9 i$. $\square$

WARNING!!
We have to be careful about using notation like $\sqrt{-81}$. The real-valued function $f(x)=\sqrt{x}$ is only defined for $x \geq 0$. When we write $\sqrt{-81}$ as an intermediate step to solving an equation like $z^{2}=-81$, we should keep in mind that we mean $i \sqrt{81}$.

Problem 6.2: Evaluate $i^{2009}$.

Solution for Problem 6.2: We start by experimenting with smaller powers of $i$, hoping to find a pattern. We have

193

---

<!-- Page 194 -->

CHAPTER 6. BASICS OF COMPLEX NUMBERS

$i^{1}=i, i^{2}=-1, i^{3}=i^{2} \cdot i=-1 \cdot i=-i$, and $i^{4}=i^{2} \cdot i^{2}=(-1)^{2}=1$. Then, the powers repeat:
$$\begin{array}{l}
i^{5}=i^{4} \cdot i=i \\
i^{6}=i^{4} \cdot i^{2}=i^{2} \\
i^{7}=i^{4} \cdot i^{3}=i^{3} \\
i^{8}=i^{4} \cdot i^{4}=i^{4}=1
\end{array}$$

Therefore, we see that:

Important: The powers of $i$ repeat in cycles of 4 :
$$\begin{array}{l}
i^{1}=i^{5}=i^{9}=\cdots=i, \\
i^{2}=i^{6}=i^{10}=\cdots=-1, \\
i^{3}=i^{7}=i^{11}=\cdots=-i, \\
i^{4}=i^{8}=i^{12}=\cdots=1 .
\end{array}$$

Because 2009 leaves a remainder of 1 when divided by 4 , we have $i^{2009}=i^{4 \cdot 502+1}=\left(i^{4}\right)^{502} \cdot i^{1}=i$.
Problem 6.3: Let $w=3-2 i$ and $z=2+5 i$. Express each of the following as a single complex number:
(a) $w+z$
(c) $w z$
(b) $w-3 z$
(d) $2 w^{2} z-3 w z^{2}$

Solution for Problem 6.3:
(a) To add complex numbers, we add the real parts and add the imaginary parts:
$$w+z=(3-2 i)+(2+5 i)=(3+2)+(-2 i+5 i)=5+3 i$$
(b) We have
$$w-3 z=3-2 i-3(2+5 i)=3-2 i-6-15 i=-3-17 i$$
(c) We multiply complex numbers using the distributive property, just as we do when we multiply binomials:
$$(3-2 i)(2+5 i)=3(2+5 i)-2 i(2+5 i)=6+15 i-4 i-10 i^{2}=6+11 i-10(-1)=16+11 i$$
(d) We save ourselves a little bit of work by factoring the expression first: $2 w^{2} z-3 w z^{2}=w z(2 w-3 z)$. In the previous part, we found $w z=16+11 i$. We also have
$$2 w-3 z=2(3-2 i)-3(2+5 i)=6-4 i-6-15 i=-19 i$$
so
$$w z(2 w-3 z)=(16+11 i)(-19 i)=-304 i-209 i^{2}=209-304 i$$

Sidenote: We frequently use $w$ and $z$ as variables to represent complex numbers, rather than the $x$ and $y$ that are typically used in problems about real numbers. That said, the variable $x$ is so common that you'll see many equations in terms of $x$ that have nonreal solutions.

194

---

<!-- Page 195 -->

6.1. COMPLEX NUMBER ARITHMETIC

Problem 6.4: Show that complex numbers are commutative under addition and multiplication. In other words, explain why $w+z=z+w$ and $w z=z w$ for all complex numbers $w$ and $z$.

Solution for Problem 6.4: We let $w=a+b i$ and $z=c+d i$, and we have
$$w+z=(a+b i)+(c+d i)=(a+c)+(b+d) i=(c+a)+(d+b) i=z+w .$$

We also have
$$\begin{array}{l}
w z=(a+b i)(c+d i)=(a c-b d)+(a d+b c) i \\
z w=(c+d i)(a+b i)=(c a-d b)+(c b+d a) i=(a c-b d)+(a d+b c) i
\end{array}$$
so $w z=z w$.

We can similarly show that complex numbers are associative under addition and multiplication, and that multiplication of complex numbers is distributive.

Important: For any complex numbers $v, w$, and $z$, we have:
- $w+z=z+w$ and $w z=z w$
- $v+(w+z)=(v+w)+z$ and $(v w) z=v(w z)$
- $v(w+z)=v w+v z$

There's not really anything new here; these are the same properties that you have used for real numbers for years. As exemplified in Problem 6.4, we can prove these properties for complex numbers by using the corresponding properties for real numbers together with the definitions of addition and multiplication of complex numbers.

Problem 6.5:
(a) Find all values of $k$ such that the product $(3+2 i)(3+k i)$ is a real number.
(b) Let $z=a+b i$, where $a$ and $b$ are real numbers, and let $\bar{z}=a-b i$. Prove that $z \cdot \bar{z}$ is real.

Solution for Problem 6.5:
(a) Expanding the given product, we have $(3+2 i)(3+k i)=9-2 k+(6+3 k) i$. The result is only a real number when $6+3 k=0$, so $k=-2$.
(b) In part (a) we saw that the product of the nonreal numbers $3+2 i$ and $3-2 i$ is real. Notice that the only difference between these two numbers is the sign of the imaginary part. Let's see if we can generalize this observation by checking whether or not the product $(a+b i)(a-b i)$ is a real number. We find
$$(a+b i)(a-b i)=a(a-b i)+b i(a-b i)=a^{2}-a b i+a b i-b^{2} i^{2}=a^{2}+b^{2},$$
which is real because $a$ and $b$ are real.
Definition: If $z=a+b i$, then $a-b i$ is called the conjugate of $z$, denoted $\bar{z}$. So, we have $\overline{a+b i}=a-b i$. Together, a nonreal number and its conjugate are referred to as a conjugate pair.

Important: The product of a complex number and its conjugate is a real number.
195

---

<!-- Page 196 -->

CHAPTER 6. BASICS OF COMPLEX NUMBERS

Note that in order to prove this fact in Problem 6.5, we wrote a complex number in terms of its real and imaginary parts by writing $z=a+b i$. We also used this strategy in Problem 6.4.

Concept: If you are given a problem involving a general complex number $z$, it may help to write $z$ in the form $a+b i$, and then express the problem in terms of $a$ and $b$.

We've covered addition, subtraction, and multiplication of complex numbers. Let's put conjugates to work by turning to division.

Problem 6.6: Write $\frac{2-i}{3+2 i}$ as a complex number. In other words, find real numbers $a$ and $b$ such that $\frac{2-i}{3+2 i}=a+b i$.

Solution for Problem 6.6: Knowing that $(3+2 i)(3-2 i)$ is real, we multiply the given fraction by $\frac{3-2 i}{3-2 i}$, which equals 1 , to produce an equivalent fraction with a real denominator:
$$\frac{2-i}{3+2 i}=\frac{2-i}{3+2 i} \cdot \frac{3-2 i}{3-2 i}=\frac{(2-i)(3-2 i)}{(3+2 i)(3-2 i)}=\frac{6-4 i-3 i+2 i^{2}}{3^{2}+2^{2}}=\frac{4-7 i}{13} .$$

Therefore, we have $\frac{2-i}{3+2 i}=\frac{4}{13}-\frac{7}{13} i$.

The fact that $z \bar{z}$ is real for all complex numbers $z$ gives us a way to divide by a complex number.
Important: If $w$ and $z$ are complex numbers and $z \neq 0$, then we express the quotient $w / z$
as a complex number by multiplying both the numerator and denominator by the conjugate of the denominator, $\bar{z}$ :
$$\frac{w}{z}=\frac{w}{z} \cdot \frac{\bar{z}}{\bar{z}}=\frac{w \bar{z}}{z \bar{z}} .$$

Since $z \bar{z}$ is always real, we can express $w \bar{z} /(z \bar{z})$ as a complex number, which means we can write it in the form $a+b i$ for some pair of real numbers $a$ and $b$.

Problem 6.7: The multiplicative inverse of a number $z$ is the number $w$ such that $w z=1$. For example, 0.25 is the multiplicative inverse of 4 . Show that any nonzero complex number $a+b i$ has a multiplicative inverse, and express that inverse in terms of $a$ and $b$.

Solution for Problem 6.7: We expect that the multiplicative inverse is simply $\frac{1}{z}$, expressed as a complex number using the process we learned in Problem 6.6. If we let
$$w=\frac{1}{a+b i}=\frac{1}{a+b i} \cdot \frac{a-b i}{a-b i}=\frac{a-b i}{a^{2}+b^{2}},$$
then
$$w z=\frac{a-b i}{a^{2}+b^{2}} \cdot(a+b i)=\frac{(a-b i)(a+b i)}{a^{2}+b^{2}}=\frac{a^{2}+b^{2}}{a^{2}+b^{2}}=1 .$$

This only fails if $a^{2}+b^{2}=0$. Since $a$ and $b$ are real, their squares are nonnegative, and can only both be 0 if $a=b=0$. Therefore, if $a+b i$ is a nonzero complex number, then its multiplicative inverse is $\frac{a-b i}{a^{2}+b^{2}}$.

Problem 6.8: Find all complex numbers $z$ such that $\frac{3 z-5 i}{2 z+3}=3-2 i$.

196

---

<!-- Page 197 -->

6.1. COMPLEX NUMBER ARITHMETIC

Solution for Problem 6.8: We get rid of the fraction by multiplying both sides of the equation by the denominator of the fraction. This gives
$$3 z-5 i=(2 z+3)(3-2 i)$$

Expanding the right side gives
$$3 z-5 i=6 z-4 i z+9-6 i$$

Putting all the terms with $z$ on the left and the terms without $z$ on the right gives $-3 z+4 i z=9-i$. Factoring $z$ out of the left side gives $z(-3+4 i)=9-i$. Dividing both sides by $-3+4 i$ gives
$$z=\frac{9-i}{-3+4 i}=\frac{9-i}{-3+4 i} \cdot \frac{-3-4 i}{-3-4 i}=\frac{-31-33 i}{25}=-\frac{31}{25}-\frac{33}{25} i .$$

Exercises
6.1.1 Find all $z$ such that $4 z^{2}+12=0$.
6.1.2 Let $a=3+4 i$ and $b=12-5 i$. Compute each of the following:
(a) $a-b$
(c) $a^{2}+3 a+2$
(b) $a b$
(d) $\frac{a}{\bar{b}}+\frac{\bar{a}}{b}$
6.1.3 Write each of the following in the form $a+b i$, where $a$ and $b$ are real:
(a) $\overline{2 i}+\overline{7-2 i}$
(b) $\frac{1}{2+3 i+1+2 i}$
6.1.4 Let $f(x)=\frac{x^{6}+x^{4}}{x+1}$. Find each of the following:
(a) $f(i)$
(b) $f(-i)$
(c) $f(i-1)$
6.1.5 What is $\left(i-i^{-1}\right)^{-1}$ ? (Source: AHSME)
6.1.6 Solve each of the following equations for $z$ :
(a) $\frac{z+3 i}{z-3}=2$
(b) $\frac{1+2 i}{3 z}=4+5 i$
(c) $3 z+\frac{z}{1+i}=10-4 i$
6.1.7 Use the definitions of complex number addition and complex number multiplication to prove that complex numbers are distributive. In other words, prove that $w\left(z_{1}+z_{2}\right)=w z_{1}+w z_{2}$ for any complex numbers $w$, $z_{1}$, and $z_{2}$.
6.1.8 Let $S=i^{n}+i^{-n}$, where $n$ is an integer. What are the possible values of $S$ ? (Source: AHSME)

197

---

<!-- Page 198 -->

CHAPTER 6. BASICS OF COMPLEX NUMBERS
6.2 The Complex Plane

A complex number can be represented as a point in the complex plane. Like the Cartesian plane, the complex plane has two axes: a horizontal real axis for the real part, and a vertical imaginary axis for the imaginary part. The real axis of the complex plane is labeled Re and the imaginary axis is labeled Im . Plotting the complex number $x+y i$ on the complex plane is the same as plotting the point $(x, y)$ in the Cartesian plane. The figure at right shows the numbers $1+2 i,-5-3 i$, and $2-4 i$ plotted in the complex plane.

Just as the point $(0,0)$ is called the origin on the Cartesian plane, the point that represents 0 on the complex plane is also called the origin of the complex plane.

Problems
Problem 6.9:
(a) Let $w=2+3 i$. Plot $w, \bar{w}$, and $-w$ on the complex plane.
(b) For any complex number $z$, how is $z$ related to $\bar{z}$ on the complex plane? How is $z$ related to $-z$ on the complex plane?

Problem 6.10:
(a) Let $w=2+4 i$ and $z=3-2 i$. Plot $w, z$, and $w+z$ on the complex plane. Connect the origin to $w$, then connect $w$ to $w+z$, then connect $w+z$ to $z$, then connect $z$ to the origin. Notice anything interesting?
(b) Suppose $w$ and $z$ are nonzero complex numbers such that $w / z$ is not real. Connect the origin to $w$, then connect $w$ to $w+z$, then connect $w+z$ to $z$, then connect $z$ to the origin. What type of quadrilateral must result? Why?

Problem 6.11:
(a) What is the distance between $3+4 i$ and the origin in the complex plane?
(b) What is the distance between $a+b i$ and the origin in the complex plane?

Problem 6.12: Let $|a+b i|=\sqrt{a^{2}+b^{2}}$.
(a) Evaluate $|5-12 i|$ and $|3-3 i|$.
(b) Suppose $w=3-5 i$ and $z=-2+7 i$. Find $|w-z|$. Find the distance between $w$ and $z$ on the complex plane. Notice anything interesting?
(c) For any complex numbers $w$ and $z$, how is $|w-z|$ related to the distance between $w$ and $z$ on the complex plane?
(d) Show that if $|z|=0$, then $z=0$.

Problem 6.13: Describe the graphs of each of the following:
(a) $|z|=3$
(b) $|z-4|=3$
(c) $|z+5-4 i|=2 \sqrt{2}$
(d) $|z-w|=c$, where $w$ is a complex number and $c$ is real.

198

---

<!-- Page 199 -->

6.2. THE COMPLEX PLANE

Problem 6.9: For any complex number $z$, how is $z$ related to $\bar{z}$ on the complex plane? How is $z$ related to $-z$ on the complex plane?

Solution for Problem 6.9: We start by experimenting with a specific value of $z$.

Concept: Trying specific examples can be a good way to discover general relationships.

Suppose $z=2+3 i$. Then, we have $\bar{z}=2-3 i$ and $-z=-2-3 i$. We see that $\bar{z}$ is the reflection of $z$ over the real axis and $-z$ is the reflection of $\bar{z}$ over the imaginary axis. Is this just a coincidence?

To see if this is true in general, we let $z=a+b i$. Then, we have $\bar{z}=a-b i$ and $-z=-a-b i$. So, $z$ and $\bar{z}$ have the same real part and opposite imaginary parts. Therefore, $z$ and $\bar{z}$ are reflections of each other over the real axis. Similarly, $\bar{z}$ and $-z$ have the same imaginary part, but opposite real parts, so $\bar{z}$ and $-z$ are reflections of each other over the imaginary axis.

But how are $z$ and $-z$ related? Because $z=a+b i$ and $-z=-a-b i$, the points corresponding to $z$ and $-z$ are in exactly opposite directions from the origin. We also see that $z$ and $-z$ are the same distance from the origin. Therefore, $-z$ is the $180^{\circ}$ rotation of $z$ around the origin on the complex plane. (Note: We sometimes refer to the $180^{\circ}$ rotation of a point $A$ around a point $P$ as the "reflection of point $A$ through point $P$.")

Important: In the complex plane, we have the following:
- The point $-z$ is a $180^{\circ}$ rotation of point $z$ about the origin.
- The points $z$ and $\bar{z}$ are reflections of each other over the real axis.
- The points $\bar{z}$ and $-z$ are reflections of each other over the imaginary axis.

Don't memorize these relationships! If you understand why they are true, they should become obvious to you.
Problem 6.10: Suppose $w$ and $z$ are nonzero complex numbers such that $w / z$ is not a real constant. (In other words, there is no real number $a$ such that $w=a z$.) Connect the origin to $w$, then connect $w$ to $w+z$, then connect $w+z$ to $z$, then connect $z$ to the origin. What type of quadrilateral must result? Why?

Solution for Problem 6.10: Again, we start with an example. Suppose $w=2+4 i$ and $z=3-2 i$, so $w+z=5+2 i$. In the diagram at right, we connect the points as suggested. We appear to have a parallelogram.

To see if this is always the case, we let $w=a+b i$ and $z=c+d i$. So, we have $w+z=(a+c)+(b+d) i$. If $a \neq 0$, then the slope between $w$ and the origin is $b / a$, as is the slope between $w+z$ and $z$. If $a=0$, then both of these lines are vertical lines. In either case, these two sides of the quadrilateral are parallel. Similarly, the slopes of the other two sides are either both equal to $d / c$ or they are both undefined (when both sides
are vertical). So, these two sides are parallel as well. Therefore, both pairs of opposite sides of the quadrilateral are parallel, which means the quadrilateral is a parallelogram.

199

---

<!-- Page 200 -->

CHAPTER 6. BASICS OF COMPLEX NUMBERS

Problem 6.11:
(a) What is the distance between $3+4 i$ and the origin in the complex plane?
(b) What is the distance between $a+b i$ and the origin in the complex plane?

Solution for Problem 6.11:
(a) Finding the distance between $3+4 i$ and the origin on the complex plane is the same as finding the distance between $(3,4)$ and $(0,0)$ on the Cartesian plane. We can use the distance formula, or build a right triangle as shown at right, to find that the desired distance is $\sqrt{(3-0)^{2}+(4-0)^{2}}=5$.
(b) The distance between $a+b i$ and 0 on the complex plane is the same as the distance between $(a, b)$ and $(0,0)$ on the Cartesian plane. So, the desired distance is $\sqrt{a^{2}+b^{2}}$.

Just as we use $|x|$ to denote the distance between a real number $x$ and 0 on the number line, we use $|z|$ to represent the distance between a complex number $z$ and the origin on the complex plane. We call $|z|$ the magnitude of $z$. The magnitude of a complex number is sometimes called the norm of the number.

Important: The magnitude of $z$, denoted by $|z|$, equals the distance from $z$ to the origin on
! the complex plane. If $z=a+b i$, we have
$$|z|=\sqrt{a^{2}+b^{2}} .$$

Problem 6.12:
(a) Evaluate $|5-12 i|$ and $|3-3 i|$.
(b) Suppose $w=3-5 i$ and $z=-2+7 i$. Find $|w-z|$. Find the distance between $w$ and $z$ on the complex plane. Notice anything interesting?
(c) For any complex numbers $w$ and $z$, how is $|w-z|$ related to the distance between $w$ and $z$ on the complex plane?
(d) Show that if $|z|=0$, then $z=0$.

Solution for Problem 6.12:
(a) We have $|5-12 i|=\sqrt{5^{2}+(-12)^{2}}=13$ and $|3-3 i|=\sqrt{3^{2}+(-3)^{2}}=3 \sqrt{2}$.
(b) We have $w-z=5-12 i$, and in the previous part we found that $|5-12 i|=13$. We plot $w$ and $z$ in the diagram at right. We see that the horizontal distance between them is 5 and the vertical distance between them is 12 , so the segment connecting the two points is the hypotenuse of a right triangle with legs of lengths 5 and 12. Therefore, the Pythagorean Theorem tells us that the distance between $w$ and $z$ on the complex plane is $\sqrt{5^{2}+12^{2}}=13$.

Notice that the distance between $w$ and $z$ equals $|w-z|$. Is this a coincidence?
(c) No, it's not a coincidence. Suppose $w=a+b i$ and $z=c+d i$. Finding the distance between $w$ and $z$ in the complex plane is the same as finding the distance between $(a, b)$ and $(c, d)$ on the Cartesian plane. So, the distance between $w$ and $z$ is $\sqrt{(a-c)^{2}+(b-d)^{2}}$.

200

---

<!-- Page 201 -->

6.2. THE COMPLEX PLANE

Because $w-z=(a+b i)-(c+d i)=(a-c)+(b-d) i$, we have
$$|w-z|=\sqrt{(a-c)^{2}+(b-d)^{2}} .$$

This tells us that:
Important: The distance between complex numbers $w$ and $z$ on the complex plane is $|w-z|$.
(1)
(d) Geometrically, the equation $|z-0|=0$ tells us that the distance from $z$ to 0 in the complex plane is 0 . Therefore, we must have $z=0$.

Algebraically, if we let $z=a+b i$, where $a$ and $b$ are real, then the equation $|z|=0$ tells us that $\sqrt{a^{2}+b^{2}}=0$. Squaring both sides gives $a^{2}+b^{2}=0$. Since $a$ and $b$ are real, their squares are nonnegative. So, we only have $a^{2}+b^{2}=0$ if $a^{2}=b^{2}=0$, which means $a=b=0$. Therefore, we again have $z=0$.

Problem 6.13: Describe the graphs of each of the following:
(a) $|z|=3$
(b) $|z-4|=3$
(c) $|z+5-4 i|=2 \sqrt{2}$
(d) $|z-w|=c$, where $w$ is a complex number and $c$ is real.

Solution for Problem 6.13:
(a) If $|z|=3$, then the distance from $z$ to the origin of the complex plane is 3 . Therefore, $z$ must be on the circle centered at the origin with radius 3 . Moreover, every point $z$ on this circle satisfies the equation $|z|=3$, because every point on this circle is 3 units from the origin. Therefore, the graph $|z|=3$ describes a circle of radius 3 centered at the origin.
(b) The equation $|z-4|=3$ tells us that the distance between $z$ and 4 in the complex plane is 3, so the graph is a circle of radius 3 centered at the point that represents 4 . Since $4=4+0 i$, the center of the circle is on the real axis, 4 units to the right of the origin.
(c) Writing $z+5-4 i$ as $z-(-5+4 i)$, we see that the graph of the equation $|z-(-5+4 i)|=2 \sqrt{2}$ consists of all points that are a distance of $2 \sqrt{2}$ from the point $-5+4 i$. Therefore, the graph is a circle of radius $2 \sqrt{2}$ centered at $-5+4 i$.
(d) Generalizing our work from parts (a)-(c), we see that the graph of the equation $|z-w|=c$ consists of all points that are a distance $c$ from the complex number $w$. In other words, the graph is a circle of radius $c$ centered at $w$ (shown at right for $w=2+i$ and $c=6$ ).

Exercises
6.2.1 Plot each of the following in the complex plane:
(a) $4+7 i$
(b) $-6-2 i$
(c) $(3+i)(-2+5 i)$

201

---

<!-- Page 202 -->

CHAPTER 6. BASICS OF COMPLEX NUMBERS
6.2.2 Find the magnitude of each of the following complex numbers:
(a) $24-7 i$
(b) $2+2 i \sqrt{3}$
(c) $(1+2 i)(2+i)$
6.2.3 Let $w=3+5 i$ and $z=12+2 i$. Find the area of the convex quadrilateral in the complex plane that has vertices $w, z, \bar{w}$, and $\bar{z}$.
6.2.4 Find the distance between the points $4+7 i$ and $-3-17 i$ in the complex plane.
6.2.5 Show that the midpoint of the segment connecting $z_{1}$ and $z_{2}$ on the complex plane is $\left(z_{1}+z_{2}\right) / 2$.
6.2.6
(a) Find the magnitude of $\frac{1+2 i}{2+i}$.
(b) Find the magnitude of $\frac{6+11 i}{11+6 i}$. (You can use a calculator for this part.)
(c) Notice anything interesting? Can you generalize your observations from the first two parts?
6.2.7 Four complex numbers lie at the vertices of a square in the complex plane. Three of the numbers are $1+2 i$, $-2+i$ and $-1-2 i$. What is the fourth number? (Source: AMC 12)
6.3 Real and Imaginary Parts

Not only can we produce a geometric representation of complex numbers by considering the real and imaginary parts of the numbers, but we can also use the real and imaginary parts of a complex numbers to prove important relationships and solve a variety of problems.

We often use $\operatorname{Re}(z)$ to refer to the real part of the complex number $z$, and we use $\operatorname{Im}(z)$ to refer to the imaginary part of $z$. So, for example $\operatorname{Re}(2-4 i)=2$ and $\operatorname{Im}(2-4 i)=-4$.

Problems

Problem 6.14: Show that $\operatorname{Re}(z)=\frac{z+\bar{z}}{2}$ and $\operatorname{Im}(z)=\frac{z-\bar{z}}{2 i}$.
Problem 6.15: Let $z$ and $w$ be complex numbers.
(a) Show that $\overline{z+w}=\bar{z}+\bar{w}$.
(b) Show that $\overline{z w}=\bar{z} \cdot \bar{w}$.

Problem 6.16:
(a) Show that $\overline{\bar{z}}=z$ for all complex numbers $z$.
(b) Show that $\bar{z}=z$ if and only if $z$ is real.
(c) Show that $\bar{z}=-z$ if and only if $z$ is imaginary.

Problem 6.17: Solve the equation $z+2 \bar{z}=6-4 i$ for $z$.

202

---

<!-- Page 203 -->

6.3. REAL AND IMAGINARY PARTS

Problem 6.18:
(a) Prove that $z \bar{z}=|z|^{2}$ for all complex numbers $z$.
(b) Prove that $|z w|=|z \| w|$ for all complex numbers $z$ and $w$.

Problem 6.19: Suppose $|z+w|=2$ and $|z|=|w|=3$. Find $|z-w|$.
Problem 6.20: In this problem, we find all complex numbers $z$ such that $z^{2}=21-20 i$.
(a) Let $z=a+b i$ in the given equation. Find a system of equations involving $a$ and $b$.
(b) Solve for $b$ in terms of $a$ in one of the equations, and substitute the expression you found for $b$ into the other equation.
(c) Solve the equation you formed in part (b) for all possible values of $a$.
(d) Find all complex numbers $z$ such that $z^{2}=21-20 i$.

Problem 6.21: Find and graph all $z$ such that $|z-3|=|z+2 i|$.
Problem 6.22: In this problem, we find $|z|$ if the complex number $z$ satisfies $z+|z|=2+8 i$.
(a) Let $r=|z|$. Express $z$ in terms of $r$.
(b) What is the real part of $z$ ? What is the imaginary part of $z$ ? Find $|z|$.
(c) Solve the problem again by letting $z=a+b i$.
(Source: AHSME)

Problem 6.14: Show that $\operatorname{Re}(z)=\frac{z+\bar{z}}{2}$ and $\operatorname{Im}(z)=\frac{z-\bar{z}}{2 i}$.

Solution for Problem 6.14: Let $z=a+b i$ so that $\bar{z}=a-b i$. Then
$$\begin{array}{l}
\frac{z+\bar{z}}{2}=\frac{(a+b i)+(a-b i)}{2}=\frac{2 a}{2}=a \\
\frac{z-\bar{z}}{2 i}=\frac{(a+b i)-(a-b i)}{2 i}=\frac{2 b i}{2 i}=b .
\end{array}$$

So, $\operatorname{Re}(z)=a=\frac{z+\bar{z}}{2}$ and $\operatorname{Im}(z)=b=\frac{z-\bar{z}}{2 i}$.

\begin{tabular}{|l|}
\hline Important: For any complex number $z$, we have \\
$\qquad \operatorname{Re}(z)=\frac{z+\bar{z}}{2} \quad$ and $\quad \operatorname{Im}(z)=\frac{z-\bar{z}}{2 i}$
\end{tabular}

Problem 6.15: Let $z$ and $w$ be complex numbers.
(a) Show that $\overline{z+w}=\bar{z}+\bar{w}$.
(b) Show that $\overline{z w}=\bar{z} \cdot \bar{w}$.

Solution for Problem 6.15: Let $z=a+b i$ and $w=c+d i$, where $a, b, c$, and $d$ are real numbers.

203

---

<!-- Page 204 -->

CHAPTER 6. BASICS OF COMPLEX NUMBERS
(a) Since $z+w=a+b i+c+d i=(a+c)+(b+d) i$, the conjugate of $z+w$ is
$$\overline{z+w}=\overline{(a+c)+(b+d) i}=(a+c)-(b+d) i .$$

Similarly, the conjugate of $z$ is $\bar{z}=a-b i$, and the conjugate of $w$ is $\bar{w}=c-d i$, and their sum is
$$a-b i+c-d i=(a+c)-(b+d) i .$$

So, we have $\overline{z+w}=\bar{z}+\bar{w}$.
(b) We have
$$z w=(a+b i)(c+d i)=a c+a d i+b c i+b d i^{2}=(a c-b d)+(a d+b c) i,$$
so the conjugate of $z w$ is $\overline{z w}=(a c-b d)-(a d+b c) i$. Also, we have
$$\bar{z} \cdot \bar{w}=(a-b i)(c-d i)=a c-a d i-b c i+b d i^{2}=(a c-b d)-(a d+b c) i,$$
so $\overline{z w}=\bar{z} \cdot \bar{w}$.

Important: For any complex numbers $z$ and $w$, we have $\overline{z+w}=\bar{z}+\bar{w}$ and $\overline{z w}=\bar{z} \cdot \bar{w}$.
(1)

We'll be seeing these two very important relationships again when we study nonreal roots of polynomials in Section 6.4.

Problem 6.16:
(a) Show that $\overline{\bar{z}}=z$ for all complex numbers $z$.
(b) Show that $\bar{z}=z$ if and only if $z$ is real.
(c) Show that $\bar{z}=-z$ if and only if $z$ is imaginary.

Solution for Problem 6.16: Let $z=a+b i$, where $a$ and $b$ are real numbers.
(a) Since $\bar{z}=a-b i$, we have $\overline{\bar{z}}=\overline{a-b i}=a+b i=z$.
(b) Since $\bar{z}=a-b i$, the equation $\bar{z}=z$ becomes $a-b i=a+b i$. Subtracting $a$ from both sides gives $-b i=b i$. Therefore, we have $2 b i=0$, so $b=0$. This gives us $z=a+b i=a+0 i=a$, so $z$ is real. This shows that $\bar{z}=z$ only if $z$ is real.

We're not finished with our proof! We have only shown that when $\bar{z}=z$, then $z$ is real. (In other words, we have $\bar{z}=z$ only if $z$ is real.) We have not shown that the equation $\bar{z}=z$ is true for all real numbers. In other words, we haven't shown that $\bar{z}=z$ if $z$ is real.

To show that $\bar{z}=z$ whenever $z$ is real, we let $z=a$, where $a$ is a real number. We then have $\bar{z}=\bar{a}=a$, so $\bar{z}=z$ if $z$ is real.

Important: Suppose $A$ and $B$ are two mathematical statements. The statement " $A$ if and only if $B^{\prime \prime}$ means both of the following:
- If $A$ is true, then $B$ is also true.
- If $B$ is true, then $A$ is also true.

Therefore, as we just saw, proving an "if and only if" statement requires proving two statements, not just one.

204

---

<!-- Page 205 -->

6.3. REAL AND IMAGINARY PARTS
(c) Since $\bar{z}=a-b i$, the equation $\bar{z}=-z$ becomes $a-b i=-a-b i$. Adding $b i$ to both sides gives $a=-a$, so $a=0$. Therefore, we have $z=a+b i=b i$, so $z$ is imaginary. This shows that $\bar{z}=-z$ only if $z$ is imaginary.

As with part (b), this is an "if and only if" statement. We must also show that $\bar{z}=-z$ if $z$ is imaginary. Letting $z=b i$, we have $\bar{z}=\overline{b i}=-b i=-z$, as desired.

Problem 6.17: Solve $z+2 \bar{z}=6-4 i$ for $z$.

Solution for Problem 6.17: Letting $z=a+b i$, for some real numbers $a$ and $b$, the given equation becomes $(a+b i)+2(a-b i)=6-4 i$. Simplifying the left side gives $3 a-b i=6-4 i$. Since two complex numbers are equal if and only if their real parts are equal and their imaginary parts are equal, we have $3 a=6$ and $-b=-4$. Solving these two equations gives $a=2$ and $b=4$, so $z=a+b i=2+4 i$.

Problem 6.18:
(a) Prove that $z \bar{z}=|z|^{2}$ for all complex numbers $z$.
(b) Prove that $|z w|=|z||w|$ for all complex numbers $z$ and $w$.

Solution for Problem 6.18: Let $z=a+b i$ and $w=c+d i$ for real numbers $a, b, c$, and $d$.
(a) Since $\bar{z}=a-b i$, we have $z \bar{z}=(a+b i)(a-b i)=a^{2}+b^{2}=\left(\sqrt{a^{2}+b^{2}}\right)^{2}=|a+b i|^{2}=|z|^{2}$.
(b) First, we note that $z w=(a+b i)(c+d i)=a c-b d+(a d+b c) i$. So, we have
$$\begin{aligned}
|z w|=|a c-b d+(a d+b c) i| & =\sqrt{(a c-b d)^{2}+(a d+b c)^{2}} \\
& =\sqrt{a^{2} c^{2}-2 a b c d+b^{2} d^{2}+a^{2} d^{2}+2 a b c d+b^{2} c^{2}} \\
& =\sqrt{a^{2} c^{2}+a^{2} d^{2}+b^{2} c^{2}+b^{2} d^{2}} \\
& =\sqrt{a^{2}\left(c^{2}+d^{2}\right)+b^{2}\left(c^{2}+d^{2}\right)} \\
& =\sqrt{\left(a^{2}+b^{2}\right)\left(c^{2}+d^{2}\right)} \\
& =\sqrt{a^{2}+b^{2}} \sqrt{c^{2}+d^{2}} \\
& =|a+b i \| c+d i|=|z||w|
\end{aligned}$$

We could also have used part (a) together with a little cleverness to solve part (b). From part (a), we have
$$|z w|^{2}=z w(\overline{z w})=z w \bar{z} \cdot \bar{w}=(z \bar{z})(w \bar{w})=|z|^{2}|w|^{2}$$

Since all the magnitudes are nonnegative numbers, we can take the positive square root of both sides to get $|z w|=|z||w|$.

Important: The relationship $|z|^{2}=z \bar{z}$ can be very helpful in problems involving the magni-
! tudes of complex numbers.

Problem 6.19: Suppose $|z+w|=2$ and $|z|=|w|=3$. Find $|z-w|$.

205

---

<!-- Page 206 -->

CHAPTER 6. BASICS OF COMPLEX NUMBERS

Solution for Problem 6.19: There's no clear way to express $|z-w|$ in terms of $|z+w|,|z|$, and $|w|$, so we write it in terms of $z, w, \bar{z}$, and $\bar{w}$ :
$$|z-w|^{2}=(z-w) \overline{(z-w)}=(z-w)(\bar{z}-\bar{w})=z \bar{z}-z \bar{w}-w \bar{z}+w \bar{w}$$

Notice that we work with $|z-w|^{2}$ rather than $|z-w|$ to avoid square roots.

Concept: It's sometimes easier to work with the square of the magnitude of a complex number than with the magnitude itself.

From $|z|=|w|=3$, we find that $z \bar{z}=|z|^{2}=9$ and $w \bar{w}=|w|^{2}=9$, so we have
$$|z-w|^{2}=z \bar{z}-z \bar{w}-w \bar{z}+w \bar{w}=18-z \bar{w}-w \bar{z}$$

We have one more magnitude to explore. As with the others, we start by looking at its square. We have $|z+w|^{2}=4$ and
$$|z+w|^{2}=(z+w) \overline{(z+w)}=z \bar{z}+z \bar{w}+w \bar{z}+w \bar{w}=9+z \bar{w}+w \bar{z}+9$$
so $18+z \bar{w}+w \bar{z}=4$, which means $z \bar{w}+w \bar{z}=-14$. Therefore, we have $|z-w|^{2}=18-(z \bar{w}+w \bar{z})=18-(-14)=32$, from which we find $|z-w|=4 \sqrt{2}$.

Problem 6.20: Find all complex numbers $z$ such that $z^{2}=21-20 i$.

Solution for Problem 6.20: We might start by taking the square root of both sides, so that $z= \pm \sqrt{21-20 i}$. But what does $\sqrt{21-20 i}$ really mean? The real-valued function $f(x)=\sqrt{x}$ is only defined for $x \geq 0$. Unfortunately, this doesn't help us define the square root of a nonreal number. Instead of trying to define $\sqrt{21-20 i}$, let's look for complex numbers whose squares equal $21-20 i$.

Let $z=a+b i$, so we have $(a+b i)^{2}=21-20 i$. Expanding the left side gives
$$a^{2}-b^{2}+2 a b i=21-20 i$$

Since $a$ and $b$ are real, we can equate the real parts of both sides to get $a^{2}-b^{2}=21$, and equate the imaginary parts to find $2 a b=-20$. Solving $2 a b=-20$ for $b$ gives $b=-10 / a$. Substituting this into $a^{2}-b^{2}=21$ gives
$$a^{2}-\frac{100}{a^{2}}=21$$

Multiplying this by $a^{2}$ gives us $a^{4}-21 a^{2}-100=0$. Factoring gives $\left(a^{2}-25\right)\left(a^{2}+4\right)=0$. However, $a$ is real, so $a^{2}$ must be nonnegative. Therefore, we have $a^{2}=25$, so $a= \pm 5$. Since $b=-10 / a$ we have $b=-2$ when $a=5$, and $b=2$ when $a=-5$. So, the two possible values of $z$ are $\pm(5-2 i)$.

Having found the two complex numbers whose squares equal $21-20 i$, we can see some of the difficulty that arises from defining $\sqrt{21-20 i}$. Which of the values $5-2 i$ or $-5+2 i$ should we take to be the square root? We can't simply call one "positive" and one "negative."

Due to these difficulties, we try to avoid using expressions like $\sqrt{21-20 i}$, and instead think of the "numbers whose squares equal $21-20 i$." We may sometimes refer to these two numbers as "the square roots" of $21-20 i$, and may even refer to one or the other as "a square root" of $21-20 i$. But we generally won't choose one or the other to equal $\sqrt{21-20 i}$ the way we choose 5 to equal $\sqrt{25}$.

We have these same difficulties when trying to define $\sqrt{-81}$. For example, which of $9 i$ or $-9 i$ is "the" square root of -81 ? However, as we saw in Problem 6.1 , we may occasionally stumble on expressions like $\sqrt{-81}$ when

206

---

<!-- Page 207 -->

6.3. REAL AND IMAGINARY PARTS

solving equations like $z^{2}=-81$. When this happens, the square root should always be preceded by $\pm$, as in $z= \pm \sqrt{-81}$. In other words, we are referring to both "square roots" of -81 ; that is, we are considering both numbers whose squares are -81 .

Problem 6.21: Find and graph all $z$ such that $|z-3|=|z+2 i|$.

Solution for Problem 6.21: Solution 1: Algebra. Letting $z=a+b i$, for real numbers $a$ and $b$, the equation becomes $|a+b i-3|=|a+b i+2 i|$, or
$$|(a-3)+b i|=|a+(b+2) i| .$$

Applying the definition of the magnitude of a complex number to both sides of this equation, we have
$$\sqrt{(a-3)^{2}+b^{2}}=\sqrt{a^{2}+(b+2)^{2}} .$$

Squaring both sides of this equation and expanding the squares of binomials gives
$$a^{2}-6 a+9+b^{2}=a^{2}+b^{2}+4 b+4 .$$

Simplifying this equation gives $6 a+4 b=5$, so our equation is $6 \cdot \operatorname{Re}(z)+4 \cdot \operatorname{Im}(z)=5$. The graph of this equation is a line, shown at right above. We can write the equation $6 \cdot \operatorname{Re}(z)+4 \cdot \operatorname{Im}(z)=5$ in terms of $z$ and $\bar{z}$ by noting that $\operatorname{Re}(z)=(z+\bar{z}) / 2$ and $\operatorname{Im}(z)=(z-\bar{z}) /(2 i)$. Substituting these into $6 \cdot \operatorname{Re}(z)+4 \cdot \operatorname{Im}(z)=5$ gives us $(3-2 i) z+(3+2 i) \bar{z}=5$.

We also could have tackled this problem algebraically by squaring $|z-3|=|z+2 i|$ to get $|z-3|^{2}=|z+2 i|^{2}$. We then use the fact that $|w|^{2}=w \bar{w}$ for all complex numbers $w$, which gives us $(z-3) \overline{(z-3)}=(z+2 i) \overline{(z+2 i)}$. Since $\overline{z-3}=\bar{z}-\overline{3}=\bar{z}-3$ and $\overline{(z+2 i)}=\bar{z}+\overline{2 i}=\bar{z}-2 i$, we have $(z-3)(\bar{z}-3)=(z+2 i)(\bar{z}-2 i)$. Expanding both sides and rearranging gives $(3-2 i) z+(3+2 i) \bar{z}=5$, as before.

Solution 2: Geometric intuition. We rewrite the equation so that both magnitudes are of differences between complex numbers, $|z-3|=|z-(-2 i)|$. The quantity on the left side of the equation is the distance from $z$ to 3 in the complex plane. Similarly, the right side is the distance from $z$ to $-2 i$ in the complex plane. Therefore, our equation tells us that $z$ is equidistant from 3 and $-2 i$ in the complex plane. So, $z$ must be on the perpendicular bisector of the segment that connects 3 and $-2 i$ in the complex plane.

The slope of the line connecting 3 and $-2 i$ is $\frac{2}{3}$, so the slope of its perpendicular bisector is $-\frac{3}{2}$. The perpendicular bisector passes through the midpoint of 3 and $-2 i$, which is $\frac{3-2 i}{2}=\frac{3}{2}-i$. Using this point and the slope of the line, we can write a point-slope form of the line:
$$\operatorname{Im}(z)-(-1)=-\frac{3}{2}\left(\operatorname{Re}(z)-\frac{3}{2}\right)$$

Rearranging this equation gives us $6 \cdot \operatorname{Re}(z)+4 \cdot \operatorname{Im}(z)=5$, as before.

The key to our second solution is using the geometric interpretations of $|z-3|$ and $|z+2 i|$.

Problem 6.22: The complex number $z$ satisfies $z+|z|=2+8 i$. What is $|z|$ ? (Source: AHSME)

207

---

<!-- Page 208 -->

CHAPTER 6. BASICS OF COMPLEX NUMBERS

Solution for Problem 6.22: Solution 1: Keep your eye on the ball. We want $|z|$, and our equation involves $|z|$, so we let $|z|=r$. Then, we have $z=2+8 i-|z|=(2-r)+8 i$. Written this way, we can see that the complex number $z$ has real part $2-r$ and imaginary part 8. Therefore, we have
$$|z|^{2}=(2-r)^{2}+8^{2}=r^{2}-4 r+68 .$$

We also have $|z|^{2}=r^{2}$, and combining this with our equation above gives $r^{2}=r^{2}-4 r+68$. Solving this equation gives us $r=17$, so $|z|=17$.

Solution 2: Let $z=a+b i$. Then, the given equation is
$$a+b i+\sqrt{a^{2}+b^{2}}=2+8 i .$$

The only imaginary term on the left is $b i$, so we have $b=8$. Equating the real parts of both sides then gives $a+\sqrt{a^{2}+64}=2$. Isolating the radical gives $\sqrt{a^{2}+64}=2-a$ and squaring both sides gives $a^{2}+64=4-4 a+a^{2}$. Solving this equation gives us $a=-15$. Because we squared the equation $\sqrt{a^{2}+64}=2-a$, we must check if the solution is extraneous. It isn't, so $|z|=|-15+8 i|=17$.

Exercises
6.3.1 Find $|(10+24 i)(8-6 i)|$ without finding the product $(10+24 i)(8-6 i)$.
6.3.2 Show that $|z|=|\bar{z}|$.
6.3.3 Solve $3 z+4 \bar{z}=12-5 i$ for $z$.
6.3.4 Solve each of the following equations:
(a) $z^{2}=2 i$
(b) $z^{2}=-5+12 i$
(c) $z^{2}=24-10 i$
6.3.5 Let $z=3+4 i$ and $w=5-12 i$. Evaluate the following expressions:
(a) $\left|\frac{1}{z}\right|$
(b) $\frac{1}{|z|}$
(c) $\left|\frac{z}{w}\right|$
(d) $\frac{|z|}{|w|}$

Compare your answers in parts (a) and (b), and compare your answers in parts (c) and (d). Notice anything interesting? (You should!) Prove that your observations will hold for any nonzero complex numbers.
6.3.6 Find all complex numbers $z$ such that $z / \bar{z}$ is
(a) a real number
(b) an imaginary number
6.3.7 Two solutions of $x^{4}-3 x^{3}+5 x^{2}-27 x-36=0$ are pure imaginary numbers. Find these two solutions. (Source: ARML) Hints: 174
6.4 Nonreal Roots of Polynomials

We can sometimes find roots of a polynomial by factoring the polynomial. For example, to find the roots of the quadratic $x^{2}-5 x+6$, we factor the quadratic as $(x-2)(x-3)$. Then, we have $(x-2)(x-3)=0$ if and only if $x-2=0$ or $x-3=0$, which gives us the roots $x=2$ and $x=3$. So, we see that if we can factor a polynomial as the product of linear factors, then we can quickly find the roots of the polynomial, since each linear factor clearly has exactly one root.

We run into a complication with the polynomial $x^{2}+1$. We can't factor this as the product of two linear terms with real coefficients, and the polynomial doesn't have any real roots. So, we introduced the idea of complex

208

---

<!-- Page 209 -->

6.4. NONREAL ROOTS OF POLYNOMIALS

numbers to describe the roots of $x^{2}+1$, writing them as $x=i$ and $x=-i$, where $i$ is the number whose square is -1 . Complex numbers therefore also allow us to factor $x^{2}+1$ as a product of linear factors:
$$x^{2}+1=(x-i)(x+i) .$$

This might make you wonder if we need any more special types of numbers beyond complex numbers to factor more complicated polynomials as a product of linear factors. The answer turns out to be "no"; complex numbers are sufficient to factor any polynomial with complex coefficients. In order to see why, we'll need the Fundamental Theorem of Algebra.

Unfortunately, to prove the Fundamental Theorem of Algebra, we need tools that are much more advanced than those we will study in this text.

We'll also use the Factor Theorem and the Rational Root Theorem to study polynomials.

The Factor Theorem and the Rational Root Theorem are covered in detail in Art of Problem Solving's Intermediate Algebra.

Problems
Problem 6.23: Show that if complex numbers $w$ and $z$ satisfy $w z=0$, then either $w=0$ or $z=0$.
Problem 6.24: Consider the polynomial $f(x)=a_{n} x^{n}+a_{n-1} x^{n-1}+\cdots+a_{0}$, where $a_{n}, a_{n-1}, \ldots, a_{0}$ are complex numbers and $a_{n} \neq 0$.
(a) Show that there exist complex numbers $r_{1}, r_{2}, \ldots, r_{n}$ such that $f(x)=a_{n}\left(x-r_{1}\right)\left(x-r_{2}\right) \cdots\left(x-r_{n}\right)$.
(b) Use part (a) to explain why $f$ has exactly $n$ complex roots, where the same number may appear multiple times among the roots. (For example, the polynomial $x^{3}$ has the three roots 0,0 , and 0 .)

Problem 6.25: Find the roots of the following polynomials:
(a) $f(x)=x^{3}-2 x^{2}+3 x-18$
(b) $g(x)=2 x^{4}-8 x^{3}-3 x^{2}+22 x-40$

209

---

<!-- Page 210 -->

CHAPTER 6. BASICS OF COMPLEX NUMBERS

Problem 6.26: Let $p(x)=a_{n} x^{n}+a_{n-1} x^{n-1}+\cdots+a_{1} x+a_{0}$ and $q(x)=a_{m} x^{m}$ be polynomials with real coefficients.
(a) Show that $\overline{q(z)}=q(\bar{z})$ for all complex numbers $z$.
(b) Show that $\overline{p(z)}=p(\bar{z})$ for all complex numbers $z$.
(c) Show that if $p(z)=0$, then $p(\bar{z})=0$.

Problem 6.27: Find the monic polynomial $f(x)$ of minimal degree such that $f(2-i)=f(1+4 i)=0$ and all the coefficients of $f(x)$ are real. (The degree of a polynomial $a_{n} x^{n}+a_{n-1} x^{n-1}+\cdots+a_{0}$, with $a_{n} \neq 0$, is $n$, and the polynomial is called monic if $a_{n}=1$. For example, $x^{6}+3 x^{2}+7$ is a monic polynomial with degree 6 , and $3 x^{5}-x+1$ is a degree 5 polynomial that is not monic.)

Problem 6.28: Consider the equation $c_{4} z^{4}+i c_{3} z^{3}+c_{2} z^{2}+i c_{1} z+c_{0}=0$, where $c_{0}, c_{1}, c_{2}, c_{3}$, and $c_{4}$ are real constants.
(a) Find a function $h$ such that substituting $z=h(x)$ into the polynomial above produces a fourth degree polynomial in $x$ with real coefficients.
(b) If one solution for $z$ to the original equation is $a+b i$, where $a$ and $b$ are real, then what value of $x$ solves your equation from part (a)?
(c) What other value of $x$ must be a solution to your equation from (a)?
(d) Prove that $z=-a+b i$ is a solution to the original equation.
(Source: AHSME)

Problem 6.23: Show that if complex numbers $w$ and $z$ satisfy $w z=0$, then either $w=0$ or $z=0$.

Solution for Problem 6.23: If $w$ is 0 , then the " $w=0$ or $z=0$ " condition is satisfied. If $w$ is not zero, then we can divide both sides by $w$ to get $z=\frac{0}{w}=0$, and again the " $w=0$ or $z=0$ " condition is satisfied.

We can extend the result of Problem 6.23 to any number of complex numbers: if $z_{1} z_{2} z_{3} \cdots z_{n}=0$, then at least one of the numbers $z_{1}, z_{2}, \ldots, z_{n}$ must be 0 . This property is called the zero-product property. It's the same property that we use for real numbers to solve a quadratic equation like $x^{2}-5 x+6=0$. We factor the equation as $(x-2)(x-3)=0$, and then note that if the product $(x-2)(x-3)$ is 0 , then either $x-2=0$ or $x-3=0$. So, the solutions are $x=2$ and $x=3$. Of course, as we have seen, there are polynomials that cannot be factored as a product of linear terms with real coefficients. Let's see what happens if we allow complex coefficients in the factors.

Problem 6.24: Consider the polynomial $f(x)=a_{n} x^{n}+a_{n-1} x^{n-1}+\cdots+a_{0}$, where $a_{n}, a_{n-1}, \ldots, a_{0}$ are complex numbers and $a_{n} \neq 0$.
(a) Show that there exist complex numbers $r_{1}, r_{2}, \ldots, r_{n}$ such that $f(x)=a_{n}\left(x-r_{1}\right)\left(x-r_{2}\right) \cdots\left(x-r_{n}\right)$.
(b) Use part (a) to explain why $f$ has exactly $n$ complex roots, where the same number may appear multiple times among the roots. (For example, the polynomial $x^{3}$ has the three roots 0,0 , and 0 .)

Solution for Problem 6.24:
(a) The Fundamental Theorem of Algebra tells us that this polynomial has a complex root, which we'll call $r_{1}$. So, if we divide $x-r_{1}$ into $f(x)$, the quotient is a polynomial $g(x)$ with degree $n-1$. By the Factor Theorem, we therefore have
$$f(x)=\left(x-r_{1}\right) g(x)=\left(x-r_{1}\right)\left(b_{n-1} x^{n-1}+b_{n-2} x^{n-2}+\cdots+b_{0}\right)$$
for some constants $b_{n-1}, b_{n-2}, \ldots, b_{0}$. Applying the Fundamental Theorem of Algebra to $g(x)$, we know that it must have a complex root that we'll call $r_{2}$. Dividing $g(x)$ by $x-r_{2}$ gives a degree $n-2$ quotient. Again

210

---

<!-- Page 211 -->

6.4. NONREAL ROOTS OF POLYNOMIALS

by the Factor Theorem, we have
$$f(x)=\left(x-r_{1}\right)\left(x-r_{2}\right) h(x)$$
for some degree $n-2$ polynomial $h(x)$. Continuing in this manner, the quotient at each step has degree 1 less than the previous quotient. Therefore, we can express $f(x)$ as the product of a constant and $n$ linear factors:
$$f(x)=a_{n}\left(x-r_{1}\right)\left(x-r_{2}\right) \cdots\left(x-r_{n}\right)$$
(b) If $f(x)=0$, then product $\left(x-r_{1}\right)\left(x-r_{2}\right) \cdots\left(x-r_{n}\right)$ must equal 0 . By the zero-product property, the product of several complex numbers equals 0 if and only if at least one of the numbers is 0 . Therefore, we can only have $f(x)=0$ if $x-r_{i}=0$ for some $i$. The only solution to $x-r_{i}=0$ is $x=r_{i}$, which is a complex number. This tells us that $f$ has exactly $n$ complex numbers as its roots.

Problem 6.25: Find the roots of the following polynomials:
(a) $f(x)=x^{3}-2 x^{2}+3 x-18$
(b) $g(x)=2 x^{4}-8 x^{3}-3 x^{2}+22 x-40$

Solution for Problem 6.25:
(a) We use the Rational Root Theorem to hunt for integer roots by testing divisors of 18 to see if they are roots of $f(x)$. We find that $f(3)=0$ and
$$f(x)=(x-3)\left(x^{2}+x+6\right)$$

We can't factor $x^{2}+x+6$ easily, so we turn to the quadratic formula to find that the roots of $x^{2}+x+6$ are
$$x=\frac{-1 \pm i \sqrt{23}}{2}$$

So, the three roots of $f(x)$ are 3 and $\frac{-1 \pm i \sqrt{23}}{2}$.
(b) We start by searching for rational roots. We find that $x+2$ divides $g(x)$ evenly and gives us
$$g(x)=(x+2)\left(2 x^{3}-12 x^{2}+21 x-20\right) .$$

We continue by searching for roots of $2 x^{3}-12 x^{2}+21 x-20$. Again using the Rational Root Theorem to restrict our search, we find that $x-4$ is a factor. Dividing $2 x^{3}-12 x^{2}+21 x-20$ by $x-4$ gives us
$$g(x)=(x+2)(x-4)\left(2 x^{2}-4 x+5\right) .$$

As in part (a), we tackle the quadratic with the quadratic formula and find that its roots are
$$x=\frac{4 \pm 2 i \sqrt{6}}{4}=1 \pm \frac{\sqrt{6}}{2} i .$$

So, the four roots of $g(x)$ are $-2,4,1-\frac{\sqrt{6}}{2} i$, and $1+\frac{\sqrt{6}}{2} i$.

211

---

<!-- Page 212 -->

CHAPTER 6. BASICS OF COMPLEX NUMBERS

For both polynomials in Problem 6.25, the nonreal roots come in conjugate pairs. In other words, if $a+b i$ is a root, then so is $a-b i$. From the quadratic formula, we can see that nonreal roots of a quadratic with real coefficients must form a conjugate pair. Let's see if we can prove a similar statement for higher degree polynomials.

Problem 6.26: Let $p(x)=a_{n} x^{n}+a_{n-1} x^{n-1}+\cdots+a_{1} x+a_{0}$ and $q(x)=a_{m} x^{m}$ be polynomials with real coefficients.
(a) Show that $\overline{q(z)}=q(\bar{z})$ for all complex numbers $z$.
(b) Show that $\overline{p(z)}=p(\bar{z})$ for all complex numbers $z$.
(c) Show that if $p(z)=0$, then $p(\bar{z})=0$.

Solution for Problem 6.26:
(a) In Problem 6.15, we showed that for all complex numbers $w$ and $z$, we have $\overline{w z}=\bar{w} \cdot \bar{z}$. Using this relationship, along with the fact that $a_{m}$ is real, we see that
$$\overline{a_{m} z^{m}}=\overline{a_{m}} \cdot \overline{z^{m}}=a_{m} \overline{z^{m}} .$$

Now, we note that
$$\overline{z^{m}}=\bar{z} \cdot \overline{z^{m-1}}=\bar{z} \cdot \bar{z} \cdot \overline{z^{m-2}}=\cdots=\underbrace{\bar{z} \cdot \bar{z} \cdots \bar{z}}_{m \bar{z}^{\prime} \mathrm{s}}=\bar{z}^{m},$$
which gives us $\overline{q(z)}=\overline{a_{n i} z^{n l}}=a_{m} \overline{z^{m}}=a_{m} \bar{z}^{m}=q(\bar{z})$.
(b) In Problem 6.15, we also showed that for all complex numbers $w$ and $z$, we have $\overline{w+z}=\bar{w}+\bar{z}$. Combining this with part (a), we have
$$\begin{aligned}
\overline{p(z)} & =\overline{a_{n} z^{n}+a_{n-1} z^{n-1}+\cdots+a_{1} z+a_{0}} \\
& =\overline{a_{n} z^{n}}+\overline{a_{n-1} z^{n-1}}+\cdots+\overline{a_{1} z}+\overline{a_{0}} \\
& =a_{n} \bar{z}^{n}+a_{n-1} \bar{z}^{n-1}+\cdots+a_{1} \bar{z}+a_{0} \\
& =p(\bar{z})
\end{aligned}$$
as desired.
(c) From part (b), we have $p(\bar{z})=\overline{p(z)}$. So, if $p(z)=0$, then we have $p(\bar{z})=\overline{p(z)}=\overline{0}=0$.

Important: Let $p(x)$ be a polynomial with real coefficients. If $z$ is a root of $p(x)$, then $\bar{z}$ is also
$\square$ a root of $p(x)$. In other words, the nonreal roots of $p(x)$ come in conjugate pairs.

We can sometimes use this fact to build a polynomial given some, but not all, of its roots.
Problem 6.27: Find the monic polynomial $f(x)$ of minimal degree such that $f(2-i)=f(1+4 i)=0$ and all the coefficients of $f(x)$ are real. (The degree of a polynomial $a_{n} x^{n}+a_{n-1} x^{n-1}+\cdots+a_{0}$, with $a_{n} \neq 0$, is $n$, and the polynomial is called monic if $a_{n}=1$. For example, $x^{6}+3 x^{2}+7$ is a monic polynomial with degree 6 , and $3 x^{5}-x+1$ is a degree 5 polynomial that is not monic.)

Solution for Problem 6.27: Since $2-i$ is a root of $f$ and the coefficients of $f$ are real, $2+i$ must also be a root of $f$. Therefore, the quadratic with roots $2-i$ and $2+i$ must be a factor of $f$. Here are two ways to find this quadratic:

Method 1: Multiply the linear factors. Since $2-i$ and $2+i$ are roots, the desired quadratic is
$$\begin{aligned}
(x-(2-i))(x-(2+i)) & =x^{2}-(2+i) x-(2-i) x+(2-i)(2+i) \\
& =x^{2}-4 x+5
\end{aligned}$$

212

---

<!-- Page 213 -->

6.4. NONREAL ROOTS OF POLYNOMIALS

Method 2: Sum and product of roots. The sum of the roots of $a x^{2}+b x+c=0$ is $-b / a$ and the product of the roots is $c / a$. Our work in Method 1 above shows why this result is true when $a=1$. Specifically, we can write a monic quadratic with roots $r$ and $s$ as $(x-r)(x-s)$. Expanding this product gives $x^{2}-(r+s) x+r s$, so the coefficient of the linear term is the opposite of the sum of the roots, and the constant term is the product of the roots. Since our roots in this case are $2-i$ and $2+i$, the sum is 4 and the product is 5 , which means the desired quadratic is $x^{2}-4 x+5$.

Similarly, because $1+4 i$ is a root of $f$, so is $1-4 i$. The sum of these roots is 2 and their product is 17 , so $1+4 i$ and $1-4 i$ are the roots of the quadratic $x^{2}-2 x+17$.

Since $f$ must be divisible by both $x^{2}-4 x+5$ and $x^{2}-2 x+17$, and these two quadratics have no linear factors in common, the product of these two monic quadratics produces the desired monic polynomial $f$ with smallest possible degree:
$$f(x)=\left(x^{2}-4 x+5\right)\left(x^{2}-2 x+17\right)=x^{4}-6 x^{3}+30 x^{2}-78 x+85$$

Problem 6.28: Suppose $a+b i$ is a solution of the polynomial equation
$$c_{4} z^{4}+i c_{3} z^{3}+c_{2} z^{2}+i c_{1} z+c_{0}=0$$
where $c_{0}, c_{1}, c_{2}, c_{3}, c_{4}, a$ and $b$ are real constants. Prove that $-a+b i$ is also a solution. (Source: AHSME)
Solution for Problem 6.28: Let $g(z)=c_{4} z^{4}+i c_{3} z^{3}+c_{2} z^{2}+i c_{1} z+c_{0}$. The coefficients of $g(z)$ are not all real, so we can't deduce that the nonreal roots come in conjugate pairs. We don't know much about roots of polynomials with nonreal coefficients, so we'd like to relate $g(z)$ to a polynomial in which all the coefficients are real. If we had such a polynomial, we'd at least know that its nonreal roots come in conjugate pairs.

We notice that the imaginary coefficients are in the terms with odd powers of $z$, so if we let $z=x i$, the resulting coefficients of $x$ are real:
$$g(x i)=c_{4} x^{4}+c_{3} x^{3}-c_{2} x^{2}-c_{1} x+c_{0}$$

Aha! Now, we've related $g(z)$ to a polynomial with real coefficients. We let
$$f(x)=g(x i)=c_{4} x^{4}+c_{3} x^{3}-c_{2} x^{2}-c_{1} x+c_{0}$$
and investigate the roots of $f(x)$. We are given that $g(a+b i)=0$. Because $f(x)=g(x i)$, we therefore know that $f(x)$ is 0 when $x i=a+b i$. Solving for $x$ gives us $x=(a+b i) / i=b-a i$, and we have
$$f(b-a i)=g((b-a i) i)=g(a+b i)=0$$

Since $f(b-a i)=0$ and $f(x)$ has real coefficients, we know that $\overline{b-a i}=b+a i$ is also a root of $f(x)$. Now, because $g(x i)=f(x)=0$ when $x=b+a i$, we see that $g(z)=0$ when $z=x i=(b+a i) i=-a+b i$, as desired.

Exercises
6.4.1 Find all roots of $g(x)=2 x^{3}+5 x^{2}+15 x+18$.
6.4.2 Find all roots of $f(t)=2 t^{4}-23 t^{2}+27 t-36$.
6.4.3 Let $g(x)$ be a polynomial with real coefficients such that $g(2+i)=g(3+i)=0$, and $\operatorname{deg} g \leq 4$. Other than $2+i$ and $3+i$, find all possible roots of $g$.
6.4.4 Prove that a fourth degree polynomial with a real root and real coefficients must have another real root (that may be the same as the first real root).

213

---

<!-- Page 214 -->

CHAPTER 6. BASICS OF COMPLEX NUMBERS
6.4.5 ★ A polynomial of degree four with leading coefficient 1 and integer coefficients has two real zeros, both of which are integers. Which of the following can also be a zero of the polynomial?
$$\frac{1+i \sqrt{11}}{2}, \frac{1+i}{2}, \frac{1}{2}+i, 1+\frac{i}{2}, \frac{1+i \sqrt{13}}{2} .$$
(Source: AMC 12) Hints: 2
6.4.6 $\star$ Find all values of $x$ such that $x^{4}+5 x^{2}+4 x+5=0$. Hints: 262
6.5 Summary

A complex number is a number of the form $a+b i$, where $a$ and $b$ are real numbers and $i^{2}=-1$. We call $a$ the real part of $a+b i$ and we call $b$ the imaginary part. If $b \neq 0$, then $a+b i$ is nonreal. If $a=0$, then the complex number $a+b i$ is called an imaginary number. Addition and multiplication of complex numbers are defined as follows:
$$\begin{aligned}
(a+b i)+(c+d i) & =(a+c)+(b+d) i \\
(a+b i)(c+d i) & =(a c-b d)+(a d+b c) i
\end{aligned}$$

\begin{tabular}{|l|l|}
\hline Important: ! & \begin{tabular}{l}
For any complex numbers $v, w$, and $z$, we have: \\
- $w+z=z+w$ and $w z=z w$ \\
- $v+(w+z)=(v+w)+z$ and $(v w) z=v(w z)$ \\
- $v(w+z)=v w+v z$
\end{tabular} \\
\hline
\end{tabular}

Important: The powers of $i$ repeat in cycles of 4 :
$$\begin{array}{l}
i^{1}=i^{5}=i^{9}=\cdots=i, \\
i^{2}=i^{6}=i^{10}=\cdots=-1, \\
i^{3}=i^{7}=i^{11}=\cdots=-i, \\
i^{4}=i^{8}=i^{12}=\cdots=1 .
\end{array}$$

If $z=a+b i$, then $a-b i$ is called the conjugate of $z$, denoted $\bar{z}$. So, we have $\overline{a+b i}=a-b i$. Together, a nonreal number and its conjugate are referred to as a conjugate pair. The product of a complex number and its conjugate is a real number. For any complex numbers $z$ and $w$, we have $\overline{z+w}=\bar{z}+\bar{w}$ and $\overline{z w}=\bar{z} \cdot \bar{w}$.

Important: If $w$ and $z$ are complex numbers and $z \neq 0$, then we express the quotient $w / z$
as a complex number by multiplying both the numerator and denominator by the conjugate of the denominator, $\bar{z}$ :
$$\frac{w}{z}=\frac{w}{z} \cdot \frac{\bar{z}}{\bar{z}}=\frac{w \bar{z}}{z \bar{z}} .$$

Since $z \bar{z}$ is always real, we can express $w \bar{z} /(z \bar{z})$ as a complex number, which means we can write it in the form $a+b i$ for some pair of real numbers $a$ and $b$.

A complex number can be represented as a point in the complex plane. Like the Cartesian plane, the complex plane has two axes: a horizontal real axis for the real part, and a vertical imaginary axis for the imaginary part. The real axis of the complex plane is labeled Re and the imaginary axis is labeled Im . Plotting the complex number $x+y i$ on the complex plane is the same as plotting the point $(x, y)$ in the Cartesian plane.

214

---

<!-- Page 215 -->

6.5. SUMMARY

Important: The magnitude of $z$, denoted by $|z|$, equals the distance from $z$ to the origin on the complex plane. If $z=a+b i$, we have
$$|z|=\sqrt{a^{2}+b^{2}}=\sqrt{z \cdot \bar{z}} .$$

The distance between complex numbers $w$ and $z$ on the complex plane is $|w-z|$.
Important: We often use $\operatorname{Re}(z)$ to refer to the real part of the complex number $z$, and we
use $\operatorname{Im}(z)$ to refer to the imaginary part of $z$. So, for example $\operatorname{Re}(2-4 i)=2$ and $\operatorname{Im}(2-4 i)=-4$. For any complex number $z$, we have
$$\operatorname{Re}(z)=\frac{z+\bar{z}}{2} \quad \text { and } \quad \operatorname{Im}(z)=\frac{z-\bar{z}}{2 i} .$$

The Fundamental Theorem of Algebra states that every one-variable polynomial with complex coefficients has at least one complex root.

Important: Let $p(x)$ be a polynomial with real coefficients. If $z$ is a root of $p(x)$, then $\bar{z}$ is also
a root of $p(x)$. In other words, the nonreal roots of $p(x)$ come in conjugate pairs.

Things To Watch Out For! 

WARNING!!
We have to be careful about using notation like $\sqrt{-81}$. The real-valued function $f(x)=\sqrt{x}$ is only defined for $x \geq 0$. When we write $\sqrt{-81}$ as an intermediate step to solving an equation like $z^{2}=-81$, we should keep in mind that we mean $i \sqrt{81}$.

Problem Solving Strategies 

Concepts:
- If you are given a problem involving a general complex number $z$, it may help to write $z$ in the form $a+b i$, and then express the problem in terms of $a$ and $b$.
- It's sometimes easier to work with the square of the magnitude of a complex number than with the magnitude itself, in part because we can then apply the relationship $|z|^{2}=z \bar{z}$.
- Trying specific examples can be a good way to discover general relationships.
- Many complex number concepts have a strong geometric significance as well as an algebraic one, so if you have trouble understanding an algebraic relationship regarding complex numbers, try considering it in the complex plane.

215

---

<!-- Page 216 -->

CHAPTER 6. BASICS OF COMPLEX NUMBERS

Review Problems
6.29 Let $w=2+3 i$ and $z=4-5 i$. Express each of the following as a complex number:
(a) $2 w-3 z$
(c) $\frac{2}{\bar{w}+z}$
(e) $\frac{-y+x i}{x+y i}$
(b) $\frac{1}{w}$
(d) $\frac{w^{3}+2 w^{2} z+w z^{2}}{w^{2} z+w z^{2}}$
(f) $\frac{(1-i)^{4}}{(1+i)^{3}}$
6.30 Solve the equation $-3-x^{2}=9+x^{2}$.
6.31 Express $\frac{1}{1+\frac{1}{1-\frac{1}{1+i}}}$ in the form $a+b i$, where $a$ and $b$ are real numbers.
6.32 Find the complex number $z$ such that $\frac{z}{1+z}=-1+i$.
6.33 Four complex numbers are plotted in the plane, as shown. One of them is $z$. The other three are $-z, \bar{z}$, and $-\bar{z}$. Which is which?
6.34 Let $w$ and $z$ be complex numbers.
(a) Show that $w \bar{z}+\bar{w} z$ is real.
(b) Show that $w \bar{z}-\bar{w} z$ is imaginary.
6.35 Find two complex numbers whose squares equal $5-12 i$.
6.36 Find all real numbers $c$ such that $7+i$ is 5 units from $10+c i$ on the complex plane.
6.37 Find the area of the region enclosed by the graph of $|z-4+5 i|=2 \sqrt{3}$.
6.38 The diagram to the right shows several numbers in the complex plane. The circle has radius 1 and is centered at the origin. One of these numbers is the reciprocal of $F$. Which one? (Source: AHSME)
6.39 Find all complex numbers $z$ such that $|z+1-i|=|z-2|$.
6.40 The product of the complex numbers $a+b i$ and $c+d i$ is real, where $a, b, c$, and $d$ are real numbers. Prove that the product of the complex numbers $b+a i$ and $d+c i$ is also real.
6.41 Describe the graph of each of the following:
(a) $z-\bar{z}=-8 i$
(b) $(4-i) z-(4+i) \bar{z}=16 i$
(c) $|7+i-2 z|=4$
6.42 Graph $|z-5+2 i| \leq 4$ on the complex plane.
6.43 Simplify $(i+1)^{3200}-(i-1)^{3200}$.
6.44 Show that $|z-1|^{2}+|z+1|^{2}=4$ for all $z$ such that $|z|=1$.

216

---

<!-- Page 217 -->

CHALLENGE PROBLEMS
6.45
(a) Prove that for any complex numbers $w$ and $z$, we have $2\left(|w|^{2}+|z|^{2}\right)=|w-z|^{2}+|w+z|^{2}$.
(b) The relationship in part (a) is sometimes referred to as the parallelogram law. Why?
6.46 One of the roots of $x^{4}+9 x^{3}+48 x^{2}+78 x-136=0$ is $-3+5 i$. Find the other three roots.
6.47 Let $f(x)$ be a polynomial with degree 6 and rational coefficients. The polynomial has five distinct roots: 1 , $2-i, 2+i, 1-i$, and $1+i$.
(a) We call a value that appears twice among the roots of a polynomial a double root of the polynomial. Explain why $f$ has a double root.
(b) Which root is the double root?
6.48 Let $r_{1}=a+b i$ and $r_{2}=a-b i$, where $a$ and $b$ are nonzero real numbers. Find the minimum degree of a polynomial with real coefficients and roots $r_{1} i$ and $r_{2} i$.

Challenge Problems
6.49 Evaluate $i+2 i^{2}+3 i^{3}+4 i^{4}+\cdots+64 i^{64}$.
6.50 Let $a, b$, and $c$ be complex numbers. Suppose we want to solve the equation $a z+b \bar{z}=c$ for $z$.
(a) Show that if $|a| \neq|b|$, then the equation has a unique solution $z$.
(b) Describe the solutions when $a=-1+3 i, b=1+3 i$, and $c=i$.
6.51 Find all complex numbers $z$ such that $|z-1|=|z+3|=|z-i|$. (Source: ARML) Hints: 121
6.52 Find the area of the region of points $z$ in the complex plane such that
$$|z+4-4 i| \leq 4 \sqrt{2} \quad \text { and } \quad|z-4-4 i| \geq 4 \sqrt{2}$$
6.53 Find all roots of the polynomial $i y^{3}-8 y^{2}-22 i y+21$.
6.54 Show that the points $w, x, y$, and $z$ are the vertices of a parallelogram in the complex plane if and only if the sum of some two of them is equal to the sum of the other two. Hints: 164
6.55 ★ Let $u$ and $v$ be complex numbers such that $|u|=|v|=1, u \neq v$, and $u \neq-v$. Show that $\frac{4 u v}{(u+v)^{2}}$ is real, and that $\frac{u+v}{u-v}$ is imaginary. Hints: 102
6.56★ Let $(x, y)$ be a pair of real numbers satisfying
$$56 x+33 y=-\frac{y}{x^{2}+y^{2}} \text { and } 33 x-56 y=\frac{x}{x^{2}+y^{2}}$$

Determine the value of $|x|+|y|$. Hints: 94
$6.57 \star$ Suppose we define a sequence of complex numbers by $z_{1}=0$ and $z_{n+1}=z_{n}^{2}+i$ for $n \geq 1$. How far away from the origin is $z_{111}$ ? (Source: AHSME) Hints: 206
6.58 ★ Show that if $w_{1}+w_{2}+w_{3}=0$ and $\left|w_{1}\right|=\left|w_{2}\right|=\left|w_{3}\right|=1$, then $w_{1}^{2}+w_{2}^{2}+w_{3}^{2}=0$. Hints: $11,69,60$

217

---

<!-- Page 218 -->

CHAPTER 6. BASICS OF COMPLEX NUMBERS
6.59★ A function $f$ is defined on the complex numbers by $f(z)=(a+b i) z$, where $a$ and $b$ are positive numbers. This function has the property that the image of each point in the complex plane is equidistant from that point and the origin. Given that $|a+b i|=8$, find the value of $b^{2}$. (Source: AIME) Hints: 143, 125
6.60 For all nonzero complex numbers $z$, let $f(z)=1 / \bar{z}$.
(a) Show that $f(f(z))=z$ for all $z \neq 0$.
(b) $\star$ As $z$ varies along the line $(1+2 i) z-(1-2 i) \bar{z}=i$, what curve does $f(z)$ trace?

Hints: 268
6.61★ Find all ordered pairs $(a, b)$ such that $a+\frac{a+8 b}{a^{2}+b^{2}}=2$ and $b+\frac{8 a-b}{a^{2}+b^{2}}=0$. Hints: 226

218

---

