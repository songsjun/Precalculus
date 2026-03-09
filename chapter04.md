# Chapter 4: Applications to Geometry

<!-- Page 128 -->

CHAPTER 4. APPLICATIONS TO GEOMETRY

Geometry is the science of correct reasoning on incorrect figures. - George Polya
$$4$$

Applications to Geometry

We explore many applications of trigonometric functions to geometry in this chapter. Throughout the chapter, you will encounter trig functions of angles that you cannot evaluate in your head or with pencil and paper, such as $\sin 14^{\circ}$. When you encounter such expressions in this chapter, you can use a calculator to approximate them.
4.1 Right Triangle Trigonometry

Back on page 35, we proved the following:

Important: If triangle $X Y Z$ is a right triangle with $\angle X Y Z=90^{\circ}$ and $\angle X=\theta$, then
$$\sin \theta=\frac{Y Z}{X Z}, \quad \cos \theta=\frac{Y X}{X Z}, \quad \tan \theta=\frac{Y Z}{X Y} .$$

Another way of viewing this is: If $\theta$ is the measure of
an acute angle in a right triangle, then we have
$$\sin \theta=\frac{\text { opposite leg }}{\text { hypotenuse }}, \quad \cos \theta=\frac{\text { adjacent leg }}{\text { hypotenuse }}, \quad \tan \theta=\frac{\text { opposite leg }}{\text { adjacent leg }} .$$

Some people remember these relationships with the mnemonic "SOHCAHTOA" (pronounced "so-cah-toe$\mathrm{ah}^{\prime \prime}$ ):

Sine: Opposite/Hypotenuse, Cosine: Adjacent/Hypotenuse, Tangent: Opposite/Adjacent.
In this section, we apply these relationships to a variety of problems.

128

---

<!-- Page 129 -->

4.1. RIGHT TRIANGLE TRIGONOMETRY
$$\begin{array}{l}
\text { Important: Throughout this chapter we will use some very common conventions when } \\
\text { working with angles of a triangle and trigonometric functions of those angles. } \\
\text { Specifically, when referring to the angles of } \triangle A B C \text {, we will often refer angles of } \\
\text { the triangle solely by their vertices. That is, we will write } \angle A, \angle B \text {, and } \angle C \text { rather } \\
\text { than using three points to identify each angle. When writing trigonometric } \\
\text { functions, we will often omit the } \angle \text { symbol and simply write sin } A \text {, which is the } \\
\text { same as sin } \angle B A C \text {. When referring to the side lengths of } \triangle A B C \text {, we often let } \\
a=B C, b=A C \text {, and } c=A B \text {. }
\end{array}$$

Problems

Problem 4.1:
(a) In $\triangle A B C$, we have $\angle A B C=90^{\circ}, A C=6$, and $\angle B A C=24^{\circ}$. Find $B C$ and $A B$.
(b) In $\triangle P Q R$, we have $P Q=7, Q R=24$, and $\angle P Q R=90^{\circ}$. Find $\angle Q P R$.

Problem 4.2: The angle of elevation is the angle above the horizontal at which a viewer must look to see an object that is higher than the viewer. Similarly, the angle of depression is the angle below the horizontal at which a viewer must look to see an object that is below the viewer.
(a) A surveyor measures the angle of elevation from her feet to the top of a building as $5^{\circ}$. The surveyor knows that the building is 500 feet tall. Assuming the ground is flat and level between the surveyor and the building, how far away is the surveyor from the building?
(b) A bee is on a hill looking at a building. The building is 400 feet tall. The angle of elevation from the bee to the top of the building is $4^{\circ}$ and the angle of depression from the bee to the bottom of the building is $2^{\circ}$. What is the shortest distance the bee will have to fly to reach the building? (Answer to the nearest hundred feet.)

Problem 4.3: Suppose the slope of a line graphed in the Cartesian plane is $m$, where $m \neq 0$. Show that $m$ equals the tangent of one of the angles that the line makes with the $x$-axis.

Problem 4.4: In right triangle $A B C, \angle A B C=90^{\circ}$ and $A C=4$. If $P$ is on $\overline{A C}$ such that $B P=1$ and $\overline{B P} \perp \overline{A C}$, then find all possible values of $\angle B C P$. (Source: CEMC)

Problem 4.5: In $\triangle A B C$, let $a=B C$ and $b=A C$, and let $[A B C]$ be the area of $\triangle A B C$. Show that $[A B C]=\frac{1}{2} a b \sin C$.
Problem 4.6: What is the largest possible area of a triangle that has two consecutive sides of length 10 ? Prove that no larger area is possible.

Problem 4.7: $A B C D$ is a square and $M$ and $N$ are the midpoints of $\overline{B C}$ and $\overline{C D}$, respectively. What is $\sin \angle M A N$ ?
(Source: AHSME)

129

---

<!-- Page 130 -->

CHAPTER 4. APPLICATIONS TO GEOMETRY

Problem 4.1:
(a) In $\triangle A B C$, we have $\angle A B C=90^{\circ}, A C=6$, and $\angle B A C=24^{\circ}$. Find $B C$ and $A B$.
(b) In $\triangle P Q R$, we have $P Q=7, Q R=24$, and $\angle P Q R=90^{\circ}$. Find $\angle Q P R$.

Solution for Problem 4.1:
(a) We have
$$\begin{array}{l}
\sin \angle B A C=\frac{B C}{A C} \\
\cos \angle B A C=\frac{A B}{A C}
\end{array}$$

Using a calculator to compute $\sin 24^{\circ}$ and $\cos 24^{\circ}$, we find
$$\begin{array}{l}
B C=A C \sin \angle B A C=6 \sin 24^{\circ} \approx 2.44, \\
A B=A C \cos \angle B A C=6 \cos 24^{\circ} \approx 5.48 .
\end{array}$$
(b) We have
$$\tan \angle Q P R=\frac{Q R}{P Q}=\frac{24}{7} .$$

Using a calculator, we find that
$$\angle Q P R=\arctan \frac{24}{7} \approx 73.74^{\circ} .$$

Trigonometry has a great many real-world applications. Surveyors and (perhaps more interesting to you) video game programmers use trigonometry frequently. Here's an example; we'll see several more throughout this chapter.

Problem 4.2: The angle of elevation is the angle above the horizontal at which a viewer must look to see an object that is higher than the viewer. Similarly, the angle of depression is the angle below the horizontal at which a viewer must look to see an object that is below the viewer.
(a) A surveyor measures the angle of elevation from her feet to the top of a building as $5^{\circ}$. The surveyor knows that the building is 500 feet tall. Assuming the ground is flat and level between the surveyor and the building, how far away is the surveyor from the building?
(b) A bee is on a hill looking at a building. The building is 400 feet tall. The angle of elevation from the bee to the top of the building is $4^{\circ}$ and the angle of depression from the bee to the bottom of the building is $2^{\circ}$. What is the shortest distance the bee will have to fly to reach the building? (Answer to the nearest hundred feet.)

130

---

<!-- Page 131 -->

4.1. RIGHT TRIANGLE TRIGONOMETRY

Solution for Problem 4.2:
(a) The diagram at right depicts the building, with the surveyor at point Z . We seek $Z X$, which is one leg of $\triangle X Y Z$, and we know the other leg of $\triangle X Y Z$. When we apply trigonometric relationships to $\triangle X Y Z$, we focus the side we know, the side we want, and the acute angle we know:
$$\tan \angle Y Z X=\frac{Y X}{Z X} .$$

Solving for ZX gives us
$$Z X=\frac{Y X}{\tan \angle Y Z X}=\frac{500}{\tan 5^{\circ}} \approx 5715 .$$

Therefore, the surveyor is approximately 5715 feet from the building.
(b) In the diagram, the bee is at point $B$, and the distance from the bee to the building is $B T$, where $T$ is the foot of the perpendicular from the bee to the building. We have two right triangles, and we know the measures of the acute angles in those triangles, but we don't know any of the side lengths of those triangles. In hopes of finding useful relationships among lengths of segments in the diagram, we let $B T=x$, and try to find other lengths in the diagram in terms of $x$. We assign a variable to $B T$ both because $\overline{B T}$ is a side of both right
triangles, and because $B T$ is the length we seek in the problem.

We know that $X Y=400$, so we focus on the segments along $\overline{X Y}$. From $\triangle B T Y$, we have $\tan \angle T B Y=\frac{Y T}{B T}$, so
$$Y T=B T \tan \angle T B Y=x \tan 4^{\circ} \approx 0.070 x .$$

From $\triangle B T X$, we have $\tan \angle T B X=\frac{X T}{B T}$, so
$$X T=B T \tan \angle T B X=x \tan 2^{\circ} \approx 0.035 x .$$

Since we know that $X Y=400$, we now have an equation for $x$. We have $X Y=Y T+X T \approx 0.105 x$, so $0.105 x \approx 400$, from which we find $x \approx 3800$. Therefore, the bee is approximately 3800 feet from the building.

Our key step in this solution was the first one:
Concept: Many geometry problems are solved by assigning variables to lengths or angles
in the problems, and then finding other lengths or angles in terms of the variables. The goal then is to find an equation that you can solve.

In addition to the many applications of trigonometry to Euclidean geometry, there are also applications to analytic geometry.

Problem 4.3: Suppose the slope of a line graphed in the Cartesian plane is $m$, where $m \neq 0$. Show that $m$ equals the tangent of one of the angles that the line makes with the $x$-axis.
Extra! There is a difference between not knowing and not knowing yet.
-Shelia Tobias
131

---

<!-- Page 132 -->

CHAPTER 4. APPLICATIONS TO GEOMETRY

Solution for Problem 4.3: We'll first address a line with positive slope. In the diagram at right, the line makes an acute angle of $\theta$ with the $x$-axis as shown. (We don't need the $y$-axis for this problem, so we haven't included it.) Point $Y$ is on the line above the $x$-axis, and point $Z$ is the foot of the altitude from $Y$ to the $x$-axis. The slope of this line is positive, so we have $m=\frac{Y Z}{X Z}$. From right triangle $Y X Z$, we have
$$\tan \theta=\frac{Y Z}{X Z}=m .$$

Turning to a line with negative slope, we start with the diagram at left. Point $P$ is on the line above the $x$-axis, and $Q$ is the foot of the altitude from $P$ to the $x$-axis. As we move upward along the line, we go to the left, not the right, so we have $m=-\frac{P Q}{Q R}$. However, in $\triangle P Q R$, we have
$$\tan \alpha=\frac{P Q}{Q R}=-m .$$

Uh-oh. The problem says that the tangent of one of the angles the line makes with the $x$-axis should be equal to the slope, not the negative of the slope. Let's take a look at the obtuse angle the line makes with the $x$-axis. Since this angle together with $\alpha$ makes a straight angle, we have $\alpha+\theta=180^{\circ}$, so
$$\tan \theta=\tan \left(180^{\circ}-\alpha\right)=\frac{\sin \left(180^{\circ}-\alpha\right)}{\cos \left(180^{\circ}-\alpha\right)}=\frac{\sin \alpha}{-\cos \alpha}=-\tan \alpha .$$

Therefore, we have $\tan \theta=-(-m)=m$, and once again, the tangent of one of the angles formed by the line and the $x$-axis equals the slope.

Our solution to Problem 4.3 gives us a quick way to visualize this relationship, so you shouldn't have to memorize it.

Problem 4.4: In right triangle $A B C, \angle A B C=90^{\circ}$ and $A C=4$. If $P$ is on $\overline{A C}$ such that $B P=1$ and $\overline{B P} \perp \overline{A C}$, then find all possible values of $\angle B C P$. (Source: CEMC)

Solution for Problem 4.4: We let the desired angle be $\theta$, and present two solutions:
Solution 1: Find sides in terms of $\theta$. We have one side length in right triangle $A B C$ and one in right triangle $B P C$. If we could find one more side in either triangle, we could use the trigonometric relationships in a right triangle to find $\theta$. We focus on $\overline{B C}$, since this segment is a side of both triangles. In $\triangle B P C$, we have $\sin \theta=\frac{B P}{B C}=\frac{1}{B C}$, so $B C=\frac{1}{\sin \theta}$.
In $\triangle A B C$, we have $\cos \theta=\frac{B C}{A C}=\frac{B C}{4}$, so $B C=4 \cos \theta$. (Notice that in each case, we investigate the trig function that we can express in terms of $B C$ and a side length that we know.) We now have two different expressions for $B C$, so these expressions must be equal:
$$\frac{1}{\sin \theta}=4 \cos \theta$$

Multiplying both sides by $\sin \theta$ gives $4 \sin \theta \cos \theta=1$. Applying the sine double angle identity (in "reverse") makes our equation $2 \sin 2 \theta=1$, so $\sin 2 \theta=\frac{1}{2}$. Since $\theta$ is acute, there are two possible solutions, $2 \theta=30^{\circ}$ or $2 \theta=150^{\circ}$. The former gives $\theta=15^{\circ}$ and the latter gives $\theta=75^{\circ}$. So, the two possible values of $\angle B C P$ are $15^{\circ}$ and $75^{\circ}$.

132

---

<!-- Page 133 -->

4.1. RIGHT TRIANGLE TRIGONOMETRY

We can see why the possibilities for $\angle C$ are complementary in the diagrams at right. Specifically, for any triangle $A B C$ that satisfies the problem, we can swap the labels $A$ and $C$ to produce another triangle that satisfies the problem. Since $\angle A+\angle C=90^{\circ}$, we know that these two possibilities for $\angle C$ must be complementary.

Solution 2: Area. All those right angles suggest that we might be able to use area to solve this problem. Since $\overline{B P}$ is an altitude of $\triangle A B C$ to side $\overline{A C}$, we have
$$[A B C]=\frac{(B P)(A C)}{2}=2,$$
where $[A B C]$ denotes the area of $\triangle A B C$. We can also express the area of $\triangle A B C$ as half the product of its legs. Using trigonometric relationships in $\triangle A B C$, we can express both legs in terms of $\theta$. As explained above, we have $B C=4 \cos \theta$. We also have $\sin \theta=\frac{A B}{A C}=\frac{A B}{4}$, so $A B=4 \sin \theta$. Therefore,
$$[A B C]=\frac{(A B)(B C)}{2}=8 \sin \theta \cos \theta .$$

We now have two expressions for $[A B C]$. Setting these equal gives $8 \sin \theta \cos \theta=2$, and the rest of the solution proceeds as before.

Both solutions involve the key first step of assigning a variable and expressing lengths in terms of that variable. The second offers a very useful general geometric problem solving tactic:

Concept: Area can be a surprisingly powerful problem solving tool, even in problems that don't appear to be about area.

Having seen one example of a relationship between trigonometric functions and area, let's now take a look at a more general one.

Problem 4.5: In $\triangle A B C$, let $a=B C, b=A C$, and $c=A B$, and let $[A B C]$ be the area of $\triangle A B C$. Show that $[A B C]=\frac{1}{2} a b \sin C$.

Solution for Problem 4.5: Our usual formula for triangle area is "one-half base times height." We seek a way to express a height of the triangle in terms of $\angle C$, hoping to convert the "one-half base times height" formula to the desired formula. So, we draw altitude $\overline{B P}$, and we have
$$[A B C]=\frac{(B P)(A C)}{2}=\frac{(B P)(b)}{2} .$$

What's wrong with this finish:

Bogus Solution: The altitude introduces a right triangle with acute angle $\angle C$. We have
$\sin C=\frac{B P}{B C}=\frac{B P}{a}$, so $B P=a \sin C$, and
$$[A B C]=\frac{(B P)(b)}{2}=\frac{1}{2} a b \sin C .$$

So, for any $\triangle A B C$ with $a=B C$ and $b=A C$, we have $[A B C]=\frac{1}{2} a b \sin C$.

133

---

<!-- Page 134 -->

CHAPTER 4. APPLICATIONS TO GEOMETRY

The problem here is that our proof does not adequately cover every possible triangle $A B C$. The Bogus Solution only covers the the case in which $\angle C$ is acute. What happens if we have $\angle C=90^{\circ}$ ? Then $P$ is at $C$, which presents some problems. Worse yet, what if $\angle C>90^{\circ}$ ? We still have to address these two cases. (Our proof above does handle the cases in which $\angle A=90^{\circ}$ or $\angle A>90^{\circ}$; make sure you see why.)

WARNING!!
When proving a statement for all possible triangles, make sure your proof is valid for all possible triangles. Specifically, you may have to address right and obtuse triangles as separate cases from acute triangles.

Fortunately, taking care of the other cases is pretty easy. If $\angle C=90^{\circ}$, then we have $[A B C]=\frac{(A C)(B C)}{2}=\frac{1}{2} a b$. Since $\sin 90^{\circ}=1$, the proposed formula also gives $[A B C]=\frac{1}{2} a b \sin 90^{\circ}=\frac{1}{2} a b$, so the proposed formula gives the correct area when $\angle C=90^{\circ}$.

If $\angle C>90^{\circ}$, we have the diagram at right, where again our first step is drawing the altitude from $B$. From $\triangle B C P$, we have $\sin \angle B C P=\frac{B P}{B C}$, so $B P=B C \sin \angle B C P= a \sin \angle B C P$. Therefore, we have
$$[A B C]=\frac{(A C)(B P)}{2}=\frac{(b)(a \sin \angle B C P)}{2}=\frac{1}{2} a b \sin \angle B C P .$$

That's close, but not quite the same as our desired formula, $[A B C]=\frac{1}{2} a b \sin \angle A C B$.
However, we have $\angle B C P=180^{\circ}-\angle A C B$, so
$$[A B C]=\frac{1}{2} a b \sin \angle B C P=\frac{1}{2} a b \sin \left(180^{\circ}-\angle A C B\right) .$$

Applying the identity $\sin \theta=\sin \left(180^{\circ}-\theta\right)$ gives $[A B C]=\frac{1}{2} a b \sin \left(180^{\circ}-\angle A C B\right)=\frac{1}{2} a b \sin \angle A C B$, so the desired formula works when $\angle C$ is obtuse as well.

Important: If $a=B C, b=A C$, and $[A B C]$ is the area of $\triangle A B C$, then
$$[A B C]=\frac{1}{2} a b \sin C$$

Problem 4.6: What is the largest possible area of a triangle that has two consecutive sides of length 10 ? Prove that no larger area is possible.

Solution for Problem 4.6: Let the triangle be $\triangle \mathrm{XYZ}$ with $\mathrm{XY}=Y Z=10$. We can relate the area of XYZ to the two sides with the formula we just proved:
$$[X Y Z]=\frac{1}{2}(X Y)(Y Z) \sin \angle X Y Z=50 \sin \angle X Y Z$$

The maximum possible value of $\sin \angle X Y Z$ is 1 , which occurs when $\angle X Y Z=90^{\circ}$. Therefore, the maximum possible area of $\triangle X Y Z$ is 50 , which occurs when $\angle X Y Z$ is a right angle.

Problem 4.7: $A B C D$ is a square and $M$ and $N$ are the midpoints of $\overline{B C}$ and $\overline{C D}$, respectively. What is $\sin \angle M A N$ ? (Source: AHSME)

Solution for Problem 4.7: We present two solutions.

134

---

<!-- Page 135 -->

4.1. RIGHT TRIANGLE TRIGONOMETRY

Solution 1: Trig Identities. We start with the diagram at right, in which $\alpha$ is the angle whose sine we seek. While we don't have a right triangle that includes $\alpha$ as an acute angle, we can easily relate $\alpha$ to acute angles $\angle B A M$ and $\angle D A N$ in right triangles $B A M$ and $D A N$. Because $\triangle B A M$ and $\triangle D A N$ are congruent by SAS Congruence $(A B=A D, \angle B=\angle D$, and $B M=D N$ ), we have $\angle D A N=\angle B A M$. Letting both of these angles have measure $\theta$, we have
$$\sin \alpha=\sin \left(90^{\circ}-2 \theta\right)=\cos 2 \theta=2 \cos ^{2} \theta-1 .$$
(We used the two identities $\sin \left(90^{\circ}-x\right)=\cos x$ and $\cos 2 x=2 \cos ^{2} x-1$ here. We could have used either of the other cosine double angle identities, as well.)

From right triangle $M A B$, we have $\cos \theta=\frac{A B}{A M}$. Since $M$ is the midpoint of $\overline{B C}$ and $A B C D$ is a square, we have $M B=\frac{B C}{2}=\frac{A B}{2}$. Therefore, applying the Pythagorean Theorem to $\triangle B A M$ gives
$$A M=\sqrt{A B^{2}+B M^{2}}=\sqrt{A B^{2}+\frac{A B^{2}}{4}}=\frac{\sqrt{5}}{2} A B,$$
which means $\frac{A B}{A M}=\frac{2}{\sqrt{5}}$ and we have
$$\sin \alpha=2 \cos ^{2} \theta-1=2\left(\frac{A B}{A M}\right)^{2}-1=2\left(\frac{2}{\sqrt{5}}\right)^{2}-1=\frac{3}{5} .$$

Solution 2: Area. We let $A B=A D=2 x$, so $M B=M C=N C=N D=x$. (We let $A B=2 x$ rather than $A B=x$ to avoid introducing fractions when computing the shorter segments.) We draw $\overline{M N}$ to divide the square into three right triangles and $\triangle A M N$. The square has area $4 x^{2}$, and we have $[A M B]=[A N D]=x^{2}$ and $[C N M]=\frac{x^{2}}{2}$. We therefore have $[A M N]=4 x^{2}-x^{2}-x^{2}-\frac{x^{2}}{2}=\frac{3 x^{2}}{2}$. We have $A N=A M=x \sqrt{5}$ from the Pythagorean Theorem, so
$$[A M N]=\frac{1}{2}(A N)(A M) \sin \alpha=\frac{5 x^{2}}{2} \sin \alpha .$$

Therefore, we must have $\frac{5 x^{2}}{2} \sin \alpha=\frac{3 x^{2}}{2}$, so $\sin \alpha=\frac{3}{5}$. Once again, we have used area to tackle a problem that doesn't appear to be about area.

Notice that our answer doesn't depend on $x$. Because scaling the diagram up or down doesn't affect $\angle M A N$, we could have chosen a specific value for $A B$ rather than letting it be $x$. So, we could have simply let $A B=A D=2$ and proceeded as above to find $\sin \alpha$.
Exercises
4.1.1 If $\angle P Q R=90^{\circ}, \angle Q R P=42^{\circ}$, and $Q P=8$, then what are $P R$ and $Q R$ to the nearest hundredth?
4.1.2 If $X Y=4 Y Z$ and $\angle X Y Z=90^{\circ}$, then what is $\angle X Z Y$ to the nearest degree?
4.1.3 Find the measure of an acute angle formed by the $x$-axis and the graph of $2 x+3 y=7$. (Answer to the nearest degree.)

135

---

<!-- Page 136 -->

CHAPTER 4. APPLICATIONS TO GEOMETRY
4.1.4 Find the area of $\triangle A B C$ if $A B=4 B C=12$ and $\angle A B C=30^{\circ}$.
4.1.5 I'm standing at the peak of a mountain that is 14,000 feet above sea level. The angle of depression from this peak to a nearby smaller peak is $4^{\circ}$. On my map, these two peaks are represented by points that are 1 inch apart. If each inch on my map represents 1.2 miles, and there are 5280 feet in a mile, then how many feet above sea level is the second peak?
4.1.6 The radius of the circle at right is 1 . For each of the following trigonometric expressions, find a segment in the diagram that has length equal to the trigonometric expression: $\sin \theta, \cos \theta, \sec \theta, \csc \theta, \tan \theta, \cot \theta$. (Note: You are not asked to express each trig function in terms of multiple segments in the diagram; you must find a segment whose length equals the corresponding trig function.)
4.1.7 $A, B$, and $C$ are vertices of a cube such that $\overline{A B}$ is an interior diagonal of the cube and $\overline{A C}$ is a diagonal of a face of the cube. Find $\cos \angle A B C$.
4.1.8 ★ Square $A B C D$ has center $O$ and $A B=900$. Points $E$ and $F$ are on $\overline{A B}$ with
$A E<B F$ and $E$ between $A$ and $F$ such that $\angle E O F=45^{\circ}$ and $E F=400$. Find $B F$. (Source: AIME)
4.2 Law of Cosines

Problems

Problem 4.8: In $\triangle A B C$, let $A C=14, B C=12$, and $\angle C=34^{\circ}$. In this problem, we find $A B$ to the nearest hundredth.
(a) Draw altitude $\overline{B X}$ from $B$ to $\overline{A C}$. Find $C X$ and $B X$ to the nearest hundredth.
(b) Find $X A$ to the nearest hundredth.
(c) Use parts (a) and (b) to find $A B$ to the nearest hundredth.

Problem 4.9: Let $\triangle A B C$ be an acute triangle with $a=B C, b=A C$, and $c=A B$. Use Problem 4.8 as a guide to prove that
$$c^{2}=a^{2}+b^{2}-2 a b \cos C$$

Problem 4.10: An airplane leaves an aircraft carrier and flies due south at $400 \mathrm{~km} / \mathrm{h}$. The carrier proceeds $60^{\circ}$ east of north at $32 \mathrm{~km} / \mathrm{h}$. If the plane has enough fuel for 5 hours of flying, what is the maximum distance south the pilot can travel, so that the fuel remaining will allow a safe return to the carrier? (You may assume Earth is flat in this problem.) (Source: CEMC)

Problem 4.11: In $\triangle A B C$, we have $A B=5, B C=7$, and $A C=8$. Find $\angle B A C$.

Problem 4.12: Equilateral triangle $A B C$ has been creased and folded so that vertex $A$ now rests at $A^{\prime}$ on $\overline{B C}$ as shown. If $B A^{\prime}=1$ and $A^{\prime} C=2$, then what is the length of crease $\overline{P Q}$ ? (Source: AMC 12)
(a) Why do $60^{\circ}$ and $120^{\circ}$ angles suggest trying the Law of Cosines?
(b) Find $P Q$. Hints: 228

Problem 4.13: In quadrilateral $A B C D$, we have $\angle A=\angle C, A B=C D=180$, and $A D \neq B C$. The perimeter of $A B C D$ is 640. Find $\cos A$. (Source: AIME) Hints: 175

136

---

<!-- Page 137 -->

4.2. LAW OF COSINES

Problem 4.8: In $\triangle A B C$, let $A C=14, B C=12$, and $\angle C=34^{\circ}$. Find $A B$ to the nearest hundredth.

Solution for Problem 4.8: We know how to use trigonometry to find side lengths in right triangles, so we start by drawing an altitude from $B$ to $\overline{A C}$ as shown. This creates right triangle $\triangle B C X$ with the $34^{\circ}$ angle as one of its acute angles. From right triangle $\triangle C B X$, we have
$$\frac{B X}{B C}=\sin C \approx 0.559,$$
so $B X \approx 0.559(B C) \approx 6.71$. Similarly, we have $C X / B C=\cos C \approx 0.829$, so $C X \approx 9.95$.
This doesn't tell us $A B$ yet, but we now have the length of one leg of $\triangle B X A$. If we can find the other, we can use the Pythagorean Theorem to find $A B$. Fortunately, $X A$ is easy to find: $X A=A C-C X \approx 4.05$. Now, we can use the Pythagorean Theorem to find
$$A B=\sqrt{B X^{2}+X A^{2}} \approx 7.84 .$$

In Problem 4.8, we were given two side lengths of a triangle and the measure of the angle between these two sides. We then found the third side. There was nothing particularly special about the side lengths or the angle. We might be able to follow essentially the same process for any triangle. Let's give it a try.

Problem 4.9: Let $\triangle A B C$ be an acute triangle with $a=B C, b=A C$, and $c=A B$. Find a formula for $c$ in terms of $a, b$, and $\angle C$.

Solution for Problem 4.9: We use Problem 4.8 as a guide. In fact, this problem is essentially the same as Problem 4.8 , but with variables $a, b$, and $\angle C$ in place of the numbers that were given in the earlier problem. We can use the same steps. We draw altitude $\overline{B X}$ from $B$ to $\overline{A C}$. Then, we have $\sin C=B X / B C$, so $B X=B C \sin C=a \sin C$. We also have $\cos C=C X / B C$, so $C X=B C \cos C=a \cos C$. Therefore, we have $A X=A C-C X=b-a \cos C$. Next we apply the Pythagorean Theorem to $\triangle A B X$ to find $A B^{2}=B X^{2}+A X^{2}$. Substituting our expressions for these three sides gives us
$$\begin{aligned}
c^{2} & =a^{2} \sin ^{2} C+(b-a \cos C)^{2} \\
& =a^{2} \sin ^{2} C+b^{2}-2 a b \cos C+a^{2} \cos ^{2} C \\
& =a^{2}\left(\sin ^{2} C+\cos ^{2} C\right)+b^{2}-2 a b \cos C
\end{aligned}$$

Since $\sin ^{2} C+\cos ^{2} C=1$, we have
$$c^{2}=a^{2}+b^{2}-2 a b \cos C .$$

We can test our new formula with the data from Problem 4.8.

Concept: Once you think you've found a new formula, check your work by trying the
formula on specific examples you have solved without the formula.

In Problem 4.8, we have $a=12, b=14$, and $\angle C=34^{\circ}$, so we have
$$c^{2}=a^{2}+b^{2}-2 a b \cos C \approx 61.44 .$$

Taking the square root of both sides gives $c \approx 7.84$, which agrees with our answer from Problem 4.8.
With a little more casework (which you'll supply as an Exercise), we can show that this equation holds for any triangle $A B C$.

137

---

<!-- Page 138 -->

CHAPTER 4. APPLICATIONS TO GEOMETRY

Important: Let $a=B C, b=A C$, and $c=A B$ in $\triangle A B C$. The Law of Cosines states that
$$c^{2}=a^{2}+b^{2}-2 a b \cos C$$

Notice that when $\angle C=90^{\circ}$, we have $\cos C=0$, so the Law of Cosines becomes $c^{2}=a^{2}+b^{2}$, which is just the Pythagorean Theorem.

Problem 4.8 is just a specific example of Problem 4.9, so we call Problem 4.9 a generalization of Problem 4.8.

Concept: Solving a specific example of a general problem can often provide a guide for solving the general problem.

Problem 4.10: An airplane leaves an aircraft carrier and flies due south at $400 \mathrm{~km} / \mathrm{h}$. The carrier proceeds $60^{\circ}$ east of north at $32 \mathrm{~km} / \mathrm{h}$. If the plane has enough fuel for 5 hours of flying, what is the maximum distance south the pilot can travel, so that the fuel remaining will allow a safe return to the carrier? (You may assume Earth is flat in this problem.) (Source: CEMC)

Solution for Problem 4.10: We start with a diagram, including the path of the ship and the path of the plane. The plane leaves the ship at $L$, flies south to $T$ before turning, and then flies to $S$, where it lands on the ship. Because the plane flies south and the ship goes $60^{\circ}$ east of north, we have $\angle T L S=180^{\circ}-60^{\circ}=120^{\circ}$. If the plane flies for 5 hours, then the ship moves $32 \cdot 5=160 \mathrm{~km}$ and the plane flies $400 \cdot 5=2000 \mathrm{~km}$. Therefore, $L S=160$ and $L T+T S=2000$. We let the desired distance, $L T$, be $x$, so $T S=2000-x$, as shown. We have expressions for all three sides of $\Delta L S T$, and we know one angle, so we apply the Law of Cosines:
$$T S^{2}=L T^{2}+L S^{2}-2(L T)(L S) \cos \angle T L S$$

Inserting our expressions and values for lengths and the angle, we have
$$(2000-x)^{2}=x^{2}+160^{2}-2(x)(160) \cos 120^{\circ} .$$

We have $\cos 120^{\circ}=-\frac{1}{2}$ (which is one reason the Law of Cosines is often helpful in problems involving $120^{\circ}$ angles), and expanding the left side of the equation gives
$$2000^{2}-4000 x+x^{2}=x^{2}+160^{2}+160 x .$$

Solving this equation gives $x \approx 955$, so the plane can fly approximately 955 km south.

Problem 4.11: In $\triangle A B C$, we have $A B=5, B C=7$, and $A C=8$. Find $\angle B A C$.

Solution for Problem 4.11: We are given all three side lengths of the triangle, so we have all the information in the Law of Cosines except the angle measure. Therefore, we can solve for $\cos \angle B A C$ with the Law of Cosines. We have
$$B C^{2}=A B^{2}+A C^{2}-2(A B)(A C) \cos \angle B A C,$$
so
$$\cos \angle B A C=\frac{A B^{2}+A C^{2}-B C^{2}}{2(A B)(A C)}=\frac{25+64-49}{2(5)(8)}=\frac{1}{2} .$$

Since $0^{\circ}<\angle B A C<180^{\circ}, \cos \angle B A C=\frac{1}{2}$ gives us $\angle B A C=60^{\circ}$.
```
Concept: The Law of Cosines can be used to find angle measures as well as side lengths.
```

138

---

<!-- Page 139 -->

4.2. LAW OF COSINES

Problem 4.12: Equilateral triangle $A B C$ has been creased and folded so that vertex $A$ now rests at $A^{\prime}$ on $\overline{B C}$ as shown. If $B A^{\prime}=1$ and $A^{\prime} C=2$, then what is the length of crease $\overline{P Q}$ ? (Source: AMC 12)

Solution for Problem 4.12: We know that the side length of the original equilateral triangle is $B A^{\prime}+A^{\prime} C=3$, but we can't immediately find any other lengths. So, we assign a variable and hope to express other side lengths in terms of that variable. We might start by letting $z=P Q$, but we don't see any way to express another side length in terms of $z$. Therefore, we start by letting $x=B P$, which gives us $A P=A B-B P=3-x$. But now we seem stuck.

Concept: When stuck on a problem, focus on information you haven't used yet.

We haven't used the fact that $\triangle P A^{\prime} \mathrm{Q}$ is the reflection of $\triangle P A \mathrm{Q}$ over $\overline{P Q}$. This tells us that $P A^{\prime}=P A$, so $P A^{\prime}=3-x$. Now, we have expressions for the lengths of all three sides of $\triangle P A^{\prime} B$. We also know that $\angle P B A^{\prime}=60^{\circ}$, so we apply the Law of Cosines:
$$\left(P A^{\prime}\right)^{2}=B P^{2}+\left(B A^{\prime}\right)^{2}-2(B P)\left(B A^{\prime}\right) \cos \angle P B A^{\prime},$$
so
$$(3-x)^{2}=x^{2}+1-2 x \cos 60^{\circ} .$$

Since $\cos 60^{\circ}=\frac{1}{2}$, we have $(3-x)^{2}=x^{2}-x+1$. Expanding the left side gives $9-6 x+x^{2}=x^{2}-x+1$, from which we find $x=\frac{8}{5}$. Therefore, we have $B P=\frac{8}{5}$ and $P A^{\prime}=P A=3-B P=\frac{7}{5}$.

We can do the same thing with $\overline{A C}$ !

Concept: If a tactic gives some information in a problem, but doesn't completely solve it,
then try applying that tactic to the problem again in another way.

We let $Q C=y$, so $A^{\prime} Q=A Q=3-y$. Applying the Law of Cosines to $\Delta A^{\prime} Q C$ gives
$$\left(A^{\prime} Q\right)^{2}=\left(A^{\prime} C\right)^{2}+Q C^{2}-2\left(A^{\prime} C\right)(Q C) \cos \angle A^{\prime} C Q,$$
so
$$(3-y)^{2}=4+y^{2}-2(2)(y) \cos 60^{\circ} .$$

Solving this equation for $y$ gives us $y=\frac{5}{4}$, so $Q C=\frac{5}{4}$ and $A^{\prime} Q=A Q=3-Q C=\frac{7}{4}$.
One more time! We have $A P=\frac{7}{5}, A Q=\frac{7}{4}$, and $\angle P A Q=60^{\circ}$, so we apply the Law of Cosines to find
$$\begin{aligned}
P Q^{2}=A P^{2}+A Q^{2}-2(A P)(A Q) \cos \angle P A Q & =\left(\frac{7}{5}\right)^{2}+\left(\frac{7}{4}\right)^{2}-2\left(\frac{7}{5}\right)\left(\frac{7}{4}\right)\left(\frac{1}{2}\right) \\
& =\frac{49}{25}+\frac{49}{16}-\frac{49}{20}=\frac{49 \cdot 16+49 \cdot 25-49 \cdot 20}{400}=\frac{49 \cdot 21}{400} .
\end{aligned}$$

Taking the square root gives $P Q=7 \sqrt{21} / 20$.

Each of the previous three problems featured a $60^{\circ}$ or $120^{\circ}$ angle. Usually, when we see $60^{\circ}$ or $120^{\circ}$, our first strategy is to look for equilateral triangles or $30-60-90$ triangles. But since $\cos 60^{\circ}=\frac{1}{2}$ and $\cos 120^{\circ}=-\frac{1}{2}$, the Law of Cosines has a particularly simple form when the angle is $60^{\circ}$ or $120^{\circ}$.

139

---

<!-- Page 140 -->

CHAPTER 4. APPLICATIONS TO GEOMETRY

Concept: If a geometry problem contains a $60^{\circ}$ or $120^{\circ}$ angle, you may be able to tackle it with the Law of Cosines.

WARNING!! The Law of Cosines can lead to some pretty heavy algebra, so usually we look for equilateral triangles or 30-60-90 triangles before pulling out the Law of Cosines on a problem that involves $60^{\circ}$ or $120^{\circ}$ angles.

Problem 4.13: In quadrilateral $A B C D$, we have $\angle A=\angle C, A B=C D=180$, and $A D \neq B C$. The perimeter of $A B C D$ is 640. Find $\cos A$. (Source: AIME)

Solution for Problem 4.13: That the question asks for the cosine of an angle suggests that we either build right triangles or we apply the Law of Cosines. But we don't have any triangles. So, we make some. The obvious candidate for building triangles is to draw diagonals. We don't want to draw diagonal $\overline{A C}$, since that will break up two angles that we know are equal, and we'll probably have to use that angle equality. So, we try
drawing $\overline{B D}$ first, thereby creating two triangles that share a side and have equal angles. We apply the Law of Cosines to each, using $\angle A$ in $\triangle A B D$ and $\angle C$ in $\triangle C B D$ :
$$\begin{array}{l}
B D^{2}=A B^{2}+A D^{2}-2(A B)(A D) \cos A \\
B D^{2}=C B^{2}+C D^{2}-2(C B)(C D) \cos C
\end{array}$$

Setting our two expressions for $B D^{2}$ equal, and noting that $\cos C=\cos A$ because $\angle A=\angle C$, gives us
$$A B^{2}+A D^{2}-2(A B)(A D) \cos A=C B^{2}+C D^{2}-2(C B)(C D) \cos A .$$

We also have $A B=C D=180$, so $A B^{2}=C D^{2}$, and the equation is now
$$A D^{2}-2(180)(A D) \cos A=C B^{2}-2(180)(C B) \cos A .$$

To solve for $\cos A$, we group the $\cos A$ terms on the left, and we have
$$2(180)(C B) \cos A-2(180)(A D) \cos A=C B^{2}-A D^{2},$$
so
$$\cos A=\frac{C B^{2}-A D^{2}}{2(180)(C B-A D)} .$$
(This step only avoids dividing by 0 because we are told that $A D \neq B C$. This gives us some confidence that we're on the right track.) Factoring the numerator of the right side as a difference of squares, we have
$$\cos A=\frac{(C B-A D)(C B+A D)}{2(180)(C B-A D)}=\frac{C B+A D}{2(180)} .$$

Now, we just have to find $C B+A D$. We go back to the problem, and look for information we haven't used yet. We haven't used the perimeter. That involves the sum of sides! Let's try it. We have $A B+C D+C B+A D=640$ and $A B=C D=180$, so $C B+A D=640-180-180=280$, and we have
$$\cos A=\frac{C B+A D}{2(180)}=\frac{280}{2(180)}=\frac{280}{360}=\frac{7}{9} .$$

140

---

<!-- Page 141 -->

4.3. LAW OF SINES

Exercises
4.2.1 Complete our proof of the Law of Cosines by proving it for obtuse and right triangles.
4.2.2 Two airplanes take off from the same airport at the same time. One flies due west at 200 miles per hour. The other flies $40^{\circ}$ north of due east at 250 miles per hour. To the nearest mile, how many miles apart are the planes 90 minutes after takeoff?
4.2.3 Prove each of the following:
(a) If $A B^{2}=B C^{2}+C A^{2}$, then $\angle A C B$ is right.
(b) If $A B^{2}>B C^{2}+C A^{2}$, then $\angle A C B$ is obtuse.
(c) If $A B^{2}<B C^{2}+C A^{2}$, then $\angle A C B$ is acute.

In each case, is the converse of the given statement true? Why or why not? (The converse of a statement of the form "If $X$, then $Y$ " is "If $Y$, then $X$.")
4.2.4 One side of a triangle has length twice that of another side, and the third side has length 6 . If one angle of the triangle is $120^{\circ}$, then what are the possible values of the lengths of the sides of the triangle?
4.2.5 If $X Y=3, Y Z=5$, and $Z X=7$, then what is $\angle X Y Z$ ?
4.2.6 Quadrilateral $A B C D$ is inscribed in a circle. If $A B=2, B C=3, C D=4$, and $D A=6$, then what is $A C$ ? (Source: CEMC)
4.2.7 ★ Equilateral triangle $\mathcal{T}$ is inscribed in circle $A$, which has radius 10 . Circle $B$ with radius 3 is internally tangent to circle $A$ at one vertex of $\mathcal{T}$. Circles $C$ and $D$, both with radius 2, are internally tangent to circle $A$ at the other two vertices of $\mathcal{T}$. Circles $B, C$, and $D$ are all externally tangent to circle $E$. Find the radius of circle E. (Source: AIME)
4.2.8★ Triangle $A B C$ has a right angle at $B$ and contains a point $P$ for which $P A=10, P B=6$, and $\angle A P B=\angle B P C=\angle C P A$. Find $P C$. (Source: AIME) Hints: 205
4.3 Law of Sines

We start with an important fact from elementary geometry that will be helpful in this section. In the diagram at right, we say that $\angle B A C$ is inscribed in arc $\overparen{B C}$ of the circle because $A, B$, and $C$ are all on the circle. The measure of an inscribed angle equals half the measure of the arc it intercepts, so $\angle A=\frac{\overparen{B C}}{2}$. If you are not familiar with this relationship, try proving it yourself before looking it up in a geometry text or online. (This relationship, and many others involving angles and circles, is covered in Art of Problem Solving's Introduction to Geometry.)

Problems
Problem 4.14: In $\triangle P Q R$, we have $P R=12, \angle Q P R=66^{\circ}$, and $\angle P R Q=63^{\circ}$. In this problem, we find $P Q$ and $Q R$.
(a) Let $T$ be the foot of the altitude from $P$ to $\overline{Q R}$. Find $P T$ to the nearest hundredth.
(b) Use $P T$ to find $P Q$ to the nearest hundredth.
(c) Find $Q R$ to the nearest hundredth.

141

---

<!-- Page 142 -->

CHAPTER 4. APPLICATIONS TO GEOMETRY

Problem 4.15: Suppose that $\triangle A B C$ is an acute triangle with $a=B C, b=A C$, and $c=A B$. Prove that
$$\frac{a}{\sin A}=\frac{b}{\sin B}=\frac{c}{\sin C} .$$

Problem 4.16: Let points $P$ and $Q$ be points on a shoreline that are 1.5 miles apart. Let $B$ be the base of a radio tower on a distant island, and $T$ be the top of the tower. A surveyor uses an angle measurement tool to determine that $\angle P Q B=58^{\circ}$ and $\angle Q P B=72^{\circ}$. She also measures that the angle of elevation from $P$ to the top of the tower is $1^{\circ}$. In this problem, we find the height of the tower in feet.
(a) Find $P B$.
(b) How tall is the tower in feet?

Problem 4.17: In this problem, we prove the Extended Law of Sines, which states that if $a=B C, b=A C, c=A B$, and $R$ is the radius of circumcircle of $\triangle A B C$, then
$$\frac{a}{\sin A}=\frac{b}{\sin B}=\frac{c}{\sin C}=2 R$$
(Note: The circumcircle of a triangle is the circle that passes through all three vertices of the triangle.)
(a) Start with acute triangle $\triangle A B C$. Let $D$ be the point on the circumcircle such that $\overline{A D}$ is a diameter of the circle. What angle of $\triangle A B C$ equals $\angle A D C$, and why must these angles be equal? Hints: 229
(b) Show that $\frac{b}{\sin \angle A B C}=2 R$, where $R$ is the circumradius of $\triangle A B C$.
(c) Prove that the Extended Law of Sines holds for right and obtuse triangles.

Problem 4.18:
(a) Let $\triangle A B C$ and $\triangle D E F$ be triangles such that $A B=D E=7, B C=E F=5$, and $\angle C A B=\angle F D E=30^{\circ}$. Must $\sin \angle A C B=\sin \angle D F E ?$
(b) Must $\triangle A B C$ and $\triangle D E F$ be congruent? If not, can we deduce anything about the relationship between $\angle A C B$ and $\angle D F E$ ?

Problem 4.19: In triangle $A B C, A B=13, B C=15$, and $C A=14$. Point $D$ is on $\overline{B C}$ with $C D=6$. Point $E$ is on $\overline{B C}$ such that $C E>C D$ and $\angle B A E=\angle C A D$. Find $B E$. (Source: AIME) Hints: 241,179

Problem 4.14: Suppose $P R=12, \angle Q P R=66^{\circ}$, and $\angle P R Q=63^{\circ}$ in $\triangle P Q R$. Find $P Q$ and $R Q$ to the nearest hundredth.

Solution for Problem 4.14: We start by building a right triangle, since we know how to use trigonometry to find lengths of sides in a right triangle. We draw altitude $\overline{P T}$ to side $\overline{Q R}$. From right triangle $\triangle P T R$, we have $P T / P R=\sin R$, so $P T=P R \sin R \approx 10.69$. We also have $T R / P R=\cos R$, so $T R=P R \cos R \approx 5.45$.

Now, we can use right triangle $\triangle P Q T$ to find lengths $Q T$ and $P Q$. First, we find that $\angle Q=180^{\circ}-66^{\circ}-63^{\circ}=51^{\circ}$. We have $P T / P Q=\sin Q$, so we have $P Q=P T /(\sin Q) \approx 13.76$. We also have $P T / Q T=\tan Q$, so $Q T=P T /(\tan Q) \approx 8.66$.
Finally, we have $Q R=Q T+T R \approx 14.11$.

Let's try using our approach in Problem 4.14 to produce another "law."

142

---

<!-- Page 143 -->

4.3. LAW OF SINES

Problem 4.15: Suppose that $\triangle A B C$ is an acute triangle with $a=B C, b=A C$, and $c=A B$. Prove that
$$\frac{a}{\sin A}=\frac{b}{\sin B}=\frac{c}{\sin C} .$$

Solution for Problem 4.15: We use Problem 4.14 as a guide. We draw altitude $\overline{A T}$ to $\overline{B C}$. From right triangle $\triangle A T C$, we have $\sin C=A T / A C$, so $A T=A C \sin C=b \sin C$. From right triangle $\triangle A B T$, we have $\sin B=A T / A B$, so $A T=A B \sin B=c \sin B$. These two expressions for $A T$ must be equal, so we have $b \sin C=c \sin B$. Dividing this equation by $\sin B$ and by $\sin C$, we have
$$\frac{b}{\sin B}=\frac{c}{\sin C} .$$

We can follow essentially the same steps starting with the altitude from $C$ to $\overline{A B}$ to show that $b /(\sin B)=a /(\sin A)$. So, we have
$$\frac{a}{\sin A}=\frac{b}{\sin B}=\frac{c}{\sin C} .$$

Important: Let $a=B C, b=A C$, and $c=A B$ in $\triangle A B C$. The Law of Sines states that
$$\frac{a}{\sin A}=\frac{b}{\sin B}=\frac{c}{\sin C} .$$

We'll tackle the cases in which $\triangle A B C$ is right or obtuse in Problem 4.17.
Problem 4.16: Let points $P$ and $Q$ be points on a shoreline that are 1.5 miles apart. Let $B$ be the base of a radio tower on a distant island, and $T$ be the top of the tower. A surveyor uses an angle measurement tool to determine that $\angle P Q B=58^{\circ}$ and $\angle Q P B=72^{\circ}$. She also measures that the angle of elevation from $P$ to the top of the tower is $1^{\circ}$. How tall is the tower in feet? (There are 5280 feet in a mile.)

Solution for Problem 4.16: We first consider $\triangle B P T$ at right. We want $B T$, the height of the lighthouse, and the surveyor found that $\angle B P T=1^{\circ}$. If we could find any of the lengths of the sides of $\triangle B P T$, we could use trigonometry to find the remaining sides. Unfortunately, we don't yet know any of the sides of this triangle, so we turn to what we know about point
Q.

We are given two angle measures and a side length of $\triangle P Q B$, so we can find the third angle, and then use the Law of Sines to find the other sides. We have $\angle P B Q=180^{\circ}-58^{\circ}-72^{\circ}=50^{\circ}$. The side length we're most interested in is $P B$, since we can use that to find $B T$ in the right triangle above. Applying the Law of Sines to $\triangle P Q B$ gives
$$\frac{P B}{\sin \angle P Q B}=\frac{P Q}{\sin \angle Q B P^{\prime}}$$
so
$$P B=\frac{P Q \sin \angle P Q B}{\sin \angle Q B P}=\frac{1.5 \sin 58^{\circ}}{\sin 50^{\circ}} \approx 1.66 .$$

143

---

<!-- Page 144 -->

CHAPTER 4. APPLICATIONS TO GEOMETRY

Now we can find the height of the tower. In right triangle $B P T$, we have $\tan \angle B P T=\frac{B T}{P B}$. Since $P B \approx 1.66$ miles and $\angle B P T=1^{\circ}$, we have $B T=P B \tan \angle B P T \approx 0.0290$ miles. There are 5280 feet in one mile, so the height of the tower is $0.0290 \cdot 5280 \approx 153$ feet.

Problem 4.17: Prove the Extended Law of Sines, which states that if $a=B C, b=A C, c=A B$, and $R$ is the radius of the circumcircle of $\triangle A B C$, then
$$\frac{a}{\sin A}=\frac{b}{\sin B}=\frac{c}{\sin C}=2 R .$$
(Note: The circumcircle of a triangle is the circle that passes through all three vertices of the triangle.)

Solution for Problem 4.17: If $\triangle A B C$ is acute, then we already know that the first three ratios are equal, so we only have to prove that one of them equals $2 R$. To get a clue where to start, we rewrite $\frac{c}{\sin C}=2 R$ as $\sin C=\frac{c}{2 R}$. This suggests that we seek a right triangle with $c$ as one leg length and $2 R$ as the length of the hypotenuse. Therefore, we locate point $D$ on the circle such that $\overline{A D}$ is a diameter (which has length $2 R$ ), and we draw $\overline{A D}$ and $\overline{B D}$. Since $\angle A B D$ is inscribed in a semicircle, we have $\angle A B D=90^{\circ}$, so $\triangle A B D$ is a right triangle with leg $A B=c$ and hypotenuse $A D=2 R$. Then, we have $\sin \angle A D B=\frac{A B}{A D}=\frac{c}{2 R}$, which means we only have to show that $\sin \angle A D B=\sin \angle C$ to finish. Since $\angle A D B$ and $\angle C$ are inscribed in the same arc
of the circle, these two angles are equal, which means $\sin C=\sin \angle A D B=\frac{c}{2 R}$, as desired.

Unfortunately, we're not quite finished. Our proof above assumes that $\angle C$ is acute. We have to tackle the cases of right angles and obtuse angles separately.

The proof is pretty straightforward for right angles; we can even use the diagram above. $A D B$ is a right triangle with $\angle A B D=90^{\circ}$, and the circumradius of the triangle is $R=A D / 2$, so $A D=2 R$. Since $\sin \angle A B D=\sin 90^{\circ}=1$, we also have $\frac{A D}{\sin \angle A B D}=A D$. Setting our two expressions for $A D$ equal gives $\frac{A D}{\sin \angle A B D}=2 R$.

If $\angle C$ is obtuse, our first step is still to build right triangle $A D B$, as shown at right. As before, we have $\sin \angle A D B=\frac{A B}{A D}=\frac{c}{2 R}$; however, we clearly don't have $\angle A D B=\angle C$ in this case. But we don't need the angles to be equal! We only need their sines to be equal to be able to conclude that $\sin C=\frac{c}{2 R}$. Supplementary angles (angles that sum to $180^{\circ}$ ) have equal sines, so we wonder if $\angle C$ and $\angle A D B$ are supplementary. The measure of an angle inscribed in an arc of a circle is half the measure of the arc, so we have
$$\angle A D B+\angle C=\frac{\overparen{A C B}}{2}+\frac{\overparen{A D B}}{2}=\frac{\overparen{A C B}+\overparen{A D B}}{2} .$$

Putting the $\operatorname{arcs} \widehat{A C B}$ and $\widehat{A D B}$ together gives us the whole circle, so the sum of their measures is $360^{\circ}$. Therefore, we have $\angle A D B+\angle C=180^{\circ}$, so $\angle A D B=180^{\circ}-\angle C$, and $\sin C=\sin \left(180^{\circ}-\angle C\right)=\sin \angle A D B=\frac{c}{2 R}$, as desired.
```
Important: Let a = BC, b = AC, and c= AB in \ ABC, and let R be the radius of the
    !
```

```
    a
```

144

---

<!-- Page 145 -->

4.3. LAW OF SINES

Problem 4.18:
(a) Let $\triangle A B C$ and $\triangle D E F$ be triangles such that $A B=D E=7, B C=E F=5$, and $\angle C A B=\angle F D E=30^{\circ}$. Must $\sin \angle A C B=\sin \angle D F E ?$
(b) Must $\triangle A B C$ and $\triangle D E F$ be congruent? If not, can we deduce anything about the relationship between $\angle A C B$ and $\angle D F E$ ?

Solution for Problem 4.18:
(a) Applying the Law of Sines to $\triangle A B C$ gives
$$\frac{A B}{\sin \angle A C B}=\frac{B C}{\sin \angle C A B}=\frac{5}{\sin 30^{\circ}}=10 .$$

Therefore, we have
$$\sin \angle A C B=\frac{A B}{10}=\frac{7}{10} .$$

Similarly, applying the Law of Sines to $\triangle D E F$ gives
$$\frac{D E}{\sin \angle D F E}=\frac{E F}{\sin \angle F D E}=\frac{5}{\sin 30^{\circ}}=10,$$
so
$$\sin \angle D F E=\frac{D E}{10}=\frac{7}{10} .$$

Therefore, we must have $\sin \angle A C B=\sin \angle D F E$.
(b) If $\triangle A B C \cong \triangle D E F$, then we must have $\angle A C B=\angle D F E$. At this point, all we know is that the sine of each of these angles equals $\frac{7}{10}$. However, there are two angles between $0^{\circ}$ and $180^{\circ}$ whose sine equals $\frac{7}{10}$, one acute angle and one obtuse angle. We can find these angles with a calculator. The acute angle is approximately $44.4^{\circ}$, and the obtuse angle is $180^{\circ}-44.4^{\circ}=135.6^{\circ}$, since $\sin x=\sin \left(180^{\circ}-x\right)$. We aren't given any information in the problem that prevents $\angle A C B$ or $\angle D F E$ from taking on either of these measures.

We might have $\angle A C B=44.4^{\circ}$ while $\angle D F E=135.6$. Then, we have $\angle A B C=180^{\circ}-44.4^{\circ}-30^{\circ}=105.6^{\circ}$, while $\angle D E F=180^{\circ}-135.6^{\circ}-30^{\circ}= 14.4^{\circ}$. In this case, the triangles are clearly not congruent. (The two triangles are drawn to scale at right.) All we can say is that if the triangles are not congruent, then $\angle A C B+\angle D F E=180^{\circ}$, since the sines of these two angles are equal but the angles are not equal.

Problem 4.19: In triangle $A B C, A B=13, B C=15$, and $C A=14$. Point $D$ is on $\overline{B C}$ with $C D=6$. Point $E$ is on $\overline{B C}$ such that $C E>C D$ and $\angle B A E=\angle C A D$. Find $B E$. (Source: AIME)

145

---

<!-- Page 146 -->

CHAPTER 4. APPLICATIONS TO GEOMETRY

Solution for Problem 4.19: We let $\theta$ be the measure of equal angles $\angle B A E$ and $\angle C A D$. We need to use this angle equality, but we don't see any likely candidates for congruent triangles. We do have some equal side lengths, so perhaps the Law of Sines will allow us to use the angle equality somehow. Applying the Law of Sines to $\triangle A C D$ and $\triangle A B E$ gives:
$$\frac{B E}{\sin \theta}=\frac{A E}{\sin B}=\frac{A B}{\sin \angle A E B} \quad \text { and } \quad \frac{C D}{\sin \theta}=\frac{A D}{\sin C}=\frac{A C}{\sin \angle A D C} .$$

Dividing $\frac{B E}{\sin \theta}=\frac{A E}{\sin B}$ by $\frac{C D}{\sin \theta}=\frac{A D}{\sin C}$ cancels out $\sin \theta$ and leaves
$$\frac{B E}{C D}=\frac{A E}{A D} \cdot \frac{\sin C}{\sin B} .$$

We know $C D$, but we don't know any of the lengths on the right side. While we don't know the sines on the right, their ratio suggests applying the Law of Sines to $\triangle A B C$, since we know the side lengths of $\triangle A B C$. This gives us $\frac{A B}{\sin C}=\frac{A C}{\sin B}$, so $\frac{\sin C}{\sin B}=\frac{A B}{A C}$, and we know $A B$ and $A C$. So, we now have
$$B E=\frac{A E}{A D} \cdot \frac{\sin C}{\sin B} \cdot C D=\frac{A E}{A D} \cdot \frac{A B}{A C} \cdot C D .$$

We know three of the lengths on the right side, but not $A E$ or $A D$. Let's take a look at the third ratio in each of the original Law of Sines equations we found on line (4.1). Dividing $\frac{B E}{\sin \theta}=\frac{A B}{\sin \angle A E B}$ by $\frac{C D}{\sin \theta}=\frac{A C}{\sin \angle A D C}$ gives
$$\frac{B E}{C D}=\frac{A B}{A C} \cdot \frac{\sin \angle A D C}{\sin \angle A E B} .$$

Solving for $B E$ gives us
$$B E=\frac{A B}{A C} \cdot \frac{\sin \angle A D C}{\sin \angle A E B} \cdot C D .$$

This looks familiar. The only difference between this and our final result on line (4.2) is that here we have $\frac{\sin \angle A D C}{\sin \angle A E B}$ in place of $\frac{A E}{A D}$. The Law of Sines together with the identity $\sin x=\sin \left(180^{\circ}-x\right)$ explains why these are equal. Applying the Law of Sines to $\triangle A E D$ gives $\frac{A E}{\sin \angle A D E}=\frac{A D}{\sin \angle A E D}$, so we have
$$\frac{A E}{A D}=\frac{\sin \angle A D E}{\sin \angle A E D}=\frac{\sin \left(180^{\circ}-\angle A D C\right)}{\sin \left(180^{\circ}-\angle A E B\right)}=\frac{\sin \angle A D C}{\sin \angle A E B} .$$

This brings us right back to Equation (4.2).

We still have to find $\frac{A E}{A D}$ (or the corresponding ratio of sines). So far, we've made progress by focusing on each of the three little triangles, and on the large triangle $\triangle A B C$. The only triangles we haven't used yet are $\triangle A D B$ and $\triangle A E C$. Let's try the Law of Sines on these.

\begin{tabular}{|ll|}
\hline Concept: & When stuck on a problem, experiment with parts of the problem you haven't \\
\hline used.
\end{tabular}

146

---

<!-- Page 147 -->

4.3. LAW OF SINES

The Law of Sines applied to $\triangle A E C$ and $\triangle A D B$ gives us
$$\frac{A E}{\sin C}=\frac{E C}{\sin \angle E A C}=\frac{A C}{\sin \angle A E C} \quad \text { and } \quad \frac{A D}{\sin B}=\frac{B D}{\sin \angle B A D}=\frac{A B}{\sin \angle A D B} .$$

We start with the first two ratios in these equalities, because $\angle E A C=\angle B A D$ (since both equal $\theta+\angle D A E$ ). Dividing $\frac{A E}{\sin C}=\frac{E C}{\sin \angle E A C}$ by $\frac{A D}{\sin B}=\frac{B D}{\sin \angle B A D}$ gives
$$\frac{A E}{A D} \cdot \frac{\sin B}{\sin C}=\frac{E C}{B D} \cdot \frac{\sin \angle B A D}{\sin \angle E A C} .$$

We saw earlier that $\frac{\sin C}{\sin B}=\frac{A B}{A C}$, and $\angle B A D=\angle E A C$ means the sines on the right cancel. So, now we have
$$\frac{A E}{A D}=\frac{E C}{B D} \cdot \frac{\sin \angle B A D}{\sin \angle E A C} \cdot \frac{\sin C}{\sin B}=\frac{E C}{B D} \cdot \frac{A B}{A C} .$$

Success! We are given $A B$ and $A C$, and we have $B D=B C-C D=9$ and $E C=B C-B E=15-B E$. So, going back to our earlier expression for $B E$ in Equation (4.2), we have
$$B E=\frac{A E}{A D} \cdot \frac{A B}{A C} \cdot C D=\frac{E C}{B D} \cdot\left(\frac{A B}{A C}\right)^{2} \cdot C D=\frac{15-B E}{9} \cdot\left(\frac{13}{14}\right)^{2} \cdot 6 .$$

Solving $B E=\frac{15-B E}{9} \cdot\left(\frac{13}{14}\right)^{2} \cdot 6$ gives $B E=2535 / 463$.

Exercises
4.3.1 My house is on one side of a river and my neighbor's house is on the other. I'd like to figure out how far away his house is from mine, but I don't want to get wet, and we don't have a boat or a bridge. There's a well on my property that is 150 feet from my house. If I stand at my house and face the well, I must then turn $42^{\circ}$ to my left to be facing my neighbor's house. If I stand at the well and face my house, I must turn $123^{\circ}$ to my right to face my neighbor's house. To the nearest foot, what is the distance between my house and my neighbor's house?
4.3.2 The Leaning Tower of Alpine has been constructed $5^{\circ}$ from perfectly vertical. When it casts a 20 foot shadow in the direction directly opposite the direction it leans, the angle of elevation from the tip of the shadow to the sun is $72^{\circ}$. How far is the top of the tower from the ground (to the nearest foot)?
4.3.3 Prove that if $A B>A C>B C$ in $\triangle A B C$, then $\angle C>\angle B>\angle A$. Is the converse true?
4.3.4 The perimeter of a triangle is numerically 12 times the average of the sines of the angles of the triangle. If one side of the triangle has length 2 , what are the possible measures of the angle opposite that side?
4.3.5 In Problem 4.18, we encountered $\triangle A B C$ and $\triangle D E F$ such that $A B=D E=7, B C=E F=5$, and $\angle C A B= \angle F D E=30^{\circ}$, and showed that these two triangles need not be congruent. When I first created this problem to demonstrate why there is no "Side-Side-Angle Congruence Theorem," I had the 5 and 7 reversed, so that $A B=D E=5, B C=E F=7$, and $\angle C A B=\angle F D E=30^{\circ}$. Why did I have to change it?
4.3.6 What's wrong with this "proof" of the Angle-Angle Similarity Theorem:

Suppose we have $\triangle A B C$ and $\triangle D E F$ with $\angle A=\angle D$ and $\angle B=\angle E$. The Law of Sines gives us
$$\frac{B C}{\sin A}=\frac{A C}{\sin B} \quad \text { and } \quad \frac{E F}{\sin D}=\frac{D F}{\sin E} .$$

Therefore, we have $B C / A C=(\sin A) /(\sin B)$ and $E F / D F=(\sin D) /(\sin E)$. Since $\angle A=\angle D$ and $\angle B=\angle E$, we have $(\sin A) /(\sin B)=(\sin D) /(\sin E)$. So, we have
$$\frac{B C}{A C}=\frac{\sin A}{\sin B}=\frac{\sin D}{\sin E}=\frac{E F}{D F} .$$

147

---

<!-- Page 148 -->

CHAPTER 4. APPLICATIONS TO GEOMETRY

Because $\angle A=\angle D$ and $\angle B=\angle E$, we have $\angle C=\angle F$. We can follow essentially the same steps as above to deduce that $B C: A C: A B=E F: D F: D E$.
4.3.7 ★ Distinct points $A$ and $B$ are on a semicircle with diameter $\overline{M N}$ and center $C$. The point $P$ is on $\overline{C N}$ and $\angle C A P=\angle C B P=10^{\circ}$. If $\overparen{M A}=40^{\circ}$, then what is $\overparen{B N}$ ? (Source: AHSME)
4.4 More Triangle Relationships

In addition to the Law of Sines and the Law of Cosines, there are many other triangle relationships that involve trigonometric functions of the angles of a triangle, or that can be proved using trig. In this section, we discover some of these relationships. More importantly, we learn how to develop them-there are far too many of these relationships to memorize them all. Instead, we learn how to derive them, so we can do so whenever we need them.

Before we get started, we'll review some notation we typically use with triangles, definitions of some of the key parts of a triangle, and a list of some of the basic relationships we will use.

We let the side lengths of $\triangle A B C$ be $a=B C, b=A C$, and $c=A B$. We denote the area of $\triangle A B C$ as $[A B C]$. The semiperimeter of a triangle is half the triangle's perimeter, and we usually use $s$ to denote the semiperimeter. The circle that passes through all three vertices of $\triangle A B C$ is called the circumcircle of $\triangle A B C$ and its radius is called the circumradius of the triangle. The circle that is tangent to all three sides of a triangle is the incircle of the triangle; its radius is the inradius of the triangle. We usually use $R$ for the circumradius of a triangle and $r$ for the inradius of the triangle.

Two formulas that we proved in Art of Problem Solving's Introduction to Geometry that will be useful in this section are:
- Let $F$ be the point where the incircle of $\triangle A B C$ is tangent to side $\overline{A B}$. Then, we have $A F=s-a$ and $B F=s-b$.
- $[A B C]=r s$.

You'll have a chance to prove these as Exercises.
Problems

Problem 4.20: Show that $[A B C]=\frac{a b c}{4 R}$. Hints: 194

Problem 4.21: Show that $b=c \cos A+a \cos C$ in acute triangle $A B C$. Hints: 280
Problem 4.22: Show that $\tan \frac{A}{2}=\frac{r}{s-a}$ and $\cos \frac{A}{2}=\sqrt{\frac{s(s-a)}{b c}}$. Hints: 176

Problem 4.23: Show that $\sin A+\sin B+\sin C=\frac{s}{R}$ in any triangle $A B C$.

Problem 4.24: Show that in any non-right triangle $A B C$, we have $\tan A+\tan B+\tan C=\tan A \tan B \tan C$.
Hints: 203

148

---

<!-- Page 149 -->

4.4. MORE TRIANGLE RELATIONSHIPS

Problem 4.25: In this problem, we prove Stewart's Theorem. Let point $D$ be on side $\overline{B C}$, and let $d=A D, m=B D$, and $n=C D$. Stewart's Theorem states that
$$a\left(d^{2}+m n\right)=m b^{2}+n c^{2} .$$
(a) Which of the triangle relationships involving lengths is most likely to produce expressions like those in Stewart's Theorem?
(b) Apply your answer to part (a) to triangles $A B D$ and $A C D$. Which angles of these two triangles will be most convenient to focus on, and why?
(c) Eliminate the trig functions from your results in part (b) and perform some clever algebra to prove that $a\left(d^{2}+m n\right)=m b^{2}+n c^{2}$.

Problem 4.20: Show that $[A B C]=\frac{a b c}{4 R}$.

Solution for Problem 4.20: Rather than start from scratch with a diagram, we try using formulas we already know.

Concept: Many triangle formulas can be proved by combining formulas you already know.

We look at the key features of $\frac{a b c}{4 R}$. First, we have a product of side lengths in the numerator. We already have an area formula with a product of side lengths:
$$[A B C]=\frac{1}{2} a b \sin C$$

We also already have a formula involving $R$, the Extended Law of Sines, which tells us that $2 R=\frac{c}{\sin C}$. Solving this for $\sin C$ gives $\sin C=\frac{c}{2 R}$, and substituting this into $[A B C]=\frac{1}{2} a b \sin C$ gives $[A B C]=\frac{a b c}{4 R}$.

Problem 4.21: Show that $b=c \cos A+a \cos C$ in acute triangle $A B C$.

Solution for Problem 4.21: We present two solutions:
Solution 1: Geometry. The two cosines suggest that we look for right triangles, one with $\angle A$ as one of the acute angles and one with $\angle C$. Drawing altitude $\overline{B X}$ accomplishes both. From right triangle $B X A$, we have $\cos A=\frac{A X}{A B}=\frac{A X}{c}$, so $A X=c \cos A$. Similarly, we have $C X=a \cos C$. Therefore, we have
$$b=A C=A X+C X=c \cos A+a \cos C .$$

Solution 2: Formula Bashing. We already have a formula that relates the cosine of an angle of a triangle to the side lengths of the triangle: the Law of Cosines. Solving for the cosine in the Law of Cosines gives
$$\cos A=\frac{b^{2}+c^{2}-a^{2}}{2 b c} .$$

Doing the same for $\cos C$ and substituting into $c \cos A+a \cos C$ gives
$$c \cos A+a \cos C=c \cdot \frac{b^{2}+c^{2}-a^{2}}{2 b c}+a \cdot \frac{a^{2}+b^{2}-c^{2}}{2 a b}=\frac{b^{2}+c^{2}-a^{2}+a^{2}+b^{2}-c^{2}}{2 b}=b .$$

149

---

<!-- Page 150 -->

CHAPTER 4. APPLICATIONS TO GEOMETRY

(Note that our second solution shows that this relationship holds for right and obtuse triangles, too.)
Problem 4.22: Show that $\tan \frac{A}{2}=\frac{r}{s-a}$ and $\cos \frac{A}{2}=\sqrt{\frac{s(s-a)}{b c}}$.

Solution for Problem 4.22: We'll start with the formula for $\tan \frac{A}{2}$. Angle bisectors produce angles that are half the angles of the triangle, and the angle bisectors intersect at the center of the incircle. Because the incircle is tangent to all three sides of the triangle, we form a right triangle by connecting the incenter of the triangle to a vertex and to a neighboring point of tangency. The first desired formula jumps right out at us now. In right triangle $I A F$, we have $A F=s-a, I F=r$, and $\angle I A F=\frac{\angle A}{2}$, so $\tan \frac{A}{2}=\frac{r}{s-a}$.

Unfortunately, triangle $I A F$ isn't going to give us $\cos \frac{A}{2}$ quickly, since we don't have a nice expression for $I A$. However, we can express $\cos \frac{A}{2}$ in terms of $\cos A$, and we can write $\cos A$ in terms of the side lengths of $\triangle A B C$ using the Law of Cosines. This plan might look daunting, but there are a couple reasons it also looks promising. First, the cosine half-angle formula introduces a square root, which we need. Second, the numerator of the desired expression has squared side lengths when we expand $s(s-a)$, and the Law of Cosines had squared side lengths. Applying the half-angle formula and then the Law of Cosines gives:
$$\begin{aligned}
\cos \frac{A}{2} & =\sqrt{\frac{1+\cos A}{2}}=\sqrt{\frac{1+\frac{b^{2}+c^{2}-a^{2}}{2 b c}}{2}} \\
& =\sqrt{\frac{2 b c+b^{2}+c^{2}-a^{2}}{4 b c}}=\sqrt{\frac{(b+c)^{2}-a^{2}}{4 b c}} \\
& =\sqrt{\frac{(b+c+a)(b+c-a)}{4 b c}}=\sqrt{\frac{(2 s)(2 s-2 a)}{4 b c}}=\sqrt{\frac{s(s-a)}{b c}} .
\end{aligned}$$

Problem 4.23: Show that $\sin A+\sin B+\sin C=\frac{s}{R}$ in any triangle $A B C$.
Solution for Problem 4.23: Sines, side lengths, and the circumradius: this looks like a job for the Extended Law of Sines. Since
$$\frac{a}{\sin A}=\frac{b}{\sin B}=\frac{c}{\sin C}=2 R,$$
we have
$$\sin A+\sin B+\sin C=\frac{a}{2 R}+\frac{b}{2 R}+\frac{c}{2 R}=\frac{a+b+c}{2 R}=\frac{s}{R} .$$

Problem 4.24: Show that in any non-right triangle $A B C$, we have $\tan A+\tan B+\tan C=\tan A \tan B \tan C$.

Solution for Problem 4.24: We start by asking ourselves why it's important that the three angles be angles of a non-right triangle.
Concept: Focusing on the key restrictions in a problem often leads to the solution.

In a right triangle, the tangent of one of the angles is undefined, so that explains why the triangle must be non-right. But what's important about $A, B$, and $C$ being the angles of a triangle? The only thing we know from

150

---

<!-- Page 151 -->

4.4. MORE TRIANGLE RELATIONSHIPS

the fact that the three angles are the angles of a triangle is $A+B+C=180^{\circ}$. This at least allows us to eliminate one of the variables in the identity. We have $C=180^{\circ}-(A+B)$, so $\tan C=\tan \left(180^{\circ}-(A+B)\right)$. Applying the identity $\tan \left(180^{\circ}-x\right)=-\tan x$ gives $\tan C=\tan \left(180^{\circ}-(A+B)\right)=-\tan (A+B)$, and now we have a clear path to the solution:
$$\tan C=-\tan (A+B)=-\frac{\tan A+\tan B}{1-\tan A \tan B} .$$

Note that we cannot have $1-\tan A \tan B=0$ because this only occurs if $\tan A=\frac{1}{\tan B}=\cot B$. This only holds in a triangle if $A+B=90^{\circ}$. However, we are told that the triangle is not a right triangle, so we cannot have $A+B=90^{\circ}$.

Multiplying both ends of Equation (4.3) by $1-\tan A \tan B$ and rearranging gives the desired
$$\tan A+\tan B+\tan C=\tan A \tan B \tan C .$$

Problem 4.25: Let point $D$ be on side $\overline{B C}$, and let $d=A D, m=B D$, and $n=C D$. Stewart's Theorem states that
$$a\left(d^{2}+m n\right)=m b^{2}+n c^{2} .$$

Prove Stewart's Theorem.

Solution for Problem 4.25: The desired equation has multiple squares of side lengths, just like the Law of Cosines. We'll likely have to apply the Law of Cosines to both $\triangle A B D$ and $\triangle A C D$, since we need equations involving $m, n$, and $d$. We focus on $\angle A D C$ and $\angle A D B$, because these angles are supplementary, which allows us to easily relate their cosines: $\cos \angle A D C=\cos \left(180^{\circ}-\angle A D B\right)=-\cos \angle A D B$. From the Law of Cosines, we have
$$\begin{array}{l}
\cos \angle A D C=\frac{d^{2}+n^{2}-b^{2}}{2 d n} \\
\cos \angle A D B=\frac{d^{2}+m^{2}-c^{2}}{2 d m}
\end{array}$$

Therefore, $\cos \angle A D C=-\cos \angle A D B$ gives us
$$\frac{d^{2}+n^{2}-b^{2}}{2 d n}=-\frac{d^{2}+m^{2}-c^{2}}{2 d m} .$$

Multiplying both sides by $2 d m n$ gives
$$d^{2} m+m n^{2}-b^{2} m=-\left(d^{2} n+m^{2} n-c^{2} n\right) .$$

Rearranging this equation gives $d^{2} m+d^{2} n+m n^{2}+m^{2} n=b^{2} m+c^{2} n$. Factoring gives $d^{2}(m+n)+m n(m+n)=b^{2} m+c^{2} n$, and because $m+n=a$, we have the desired $a\left(d^{2}+m n\right)=m b^{2}+n c^{2}$.
Sidenote: For some people, Stewart's Theorem is easier to remember as
$$d a d+\operatorname{man}=b m b+c n c .$$

Most of the relationships we discovered in this section are not that important, which is why they are not in Important boxes. However, the two key strategies we used to find them are important:

151

---

<!-- Page 152 -->

CHAPTER 4. APPLICATIONS TO GEOMETRY

Concepts: Two strategies for proving triangle identities are:
- Use trigonometric and geometric identities that you have already proved. Use parts of the desired identity as clues for which known identities you should try to use.
- Use geometric tools in combination with trigonometry, often by building right triangles.

Exercises
4.4.1 Let $F$ be the point where the incircle of $\triangle A B C$ is tangent to side $\overline{A B}$. Show that $A F=s-a$ and $B F=s-b$.
4.4.2 Show that $[A B C]=r s$.
4.4.3 Complete our geometric proof that $b=c \cos A+a \cos C$ by addressing the cases in which $\triangle A B C$ is right or obtuse.
4.4.4 Show that in $\triangle A B C$, we have $\sin A \sin B \sin C=\frac{[A B C]}{2 R^{2}}$.
4.4.5
(a) Use the identity we found for $\cos \frac{A}{2}$ to show that $\sin \frac{A}{2}=\sqrt{\frac{(s-b)(s-c)}{b c}}$.
(b) Prove that $[A B C]=\sqrt{s(s-a)(s-b)(s-c)}$. (This is known as Heron's formula. We present a dazzling proof of Heron's formula with complex numbers on page 484.)
(c) Show that $R=\frac{a b c}{\sqrt{(a+b+c)(a-b+c)(a+b-c)(b+c-a)}}$.
4.4.6 Let $M$ be the midpoint of $\overline{B C}$. Find the length of median $\overline{A M}$ in terms of $a, b$, and $c$.
4.4.7 ★ Let $\triangle A B C$ be an acute triangle whose altitudes meet at point $H$. Show that $A H=2 R \cos A$. Hints: 279
4.4.8 ★ Show that in $\triangle A B C$, if $a=B C$ and $b=A C$, then we have $\frac{\tan \frac{A-B}{2}}{\tan \frac{A+B}{2}}=\frac{a-b}{a+b}$. This is sometimes called the

Law of Tangents. Hints: 30
4.5 Summary

Important: If triangle $X Y Z$ is a right triangle with $\angle X Y Z=90^{\circ}$ and
$\angle X=\theta$, then
$$\sin \theta=\frac{Y Z}{X Z}, \quad \cos \theta=\frac{Y X}{X Z}, \quad \tan \theta=\frac{Y Z}{X Y} .$$

Another way of viewing this is: If $\theta$ is the measure of an acute angle in a right triangle, then we have
$$\sin \theta=\frac{\text { opposite leg }}{\text { hypotenuse }}, \quad \cos \theta=\frac{\text { adjacent leg }}{\text { hypotenuse }}, \quad \tan \theta=\frac{\text { opposite leg }}{\text { adjacent leg }} .$$

152

---

<!-- Page 153 -->

4.5. SUMMARY

Important: If $a=B C, b=A C$, and $[A B C]$ is the area of $\triangle A B C$, then
$\square$
$[A B C]=\frac{1}{2} a b \sin C$.

Important: Let $a=B C, b=A C$, and $c=A B$ in $\triangle A B C$. The Law of Cosines states that
$$c^{2}=a^{2}+b^{2}-2 a b \cos C .$$

Important: Let $a=B C, b=A C$, and $c=A B$ in $\triangle A B C$, and let $R$ be the radius of the circumcircle of $\triangle A B C$ (the radius of the circle that passes through all three vertices of $\triangle A B C$ ). The Extended Law of Sines tells us that
$$\frac{a}{\sin A}=\frac{b}{\sin B}=\frac{c}{\sin C}=2 R .$$

Things To Watch Out For! 
When proving a statement for all possible triangles, make sure your proof is valid for all possible triangles. Specifically, you may have to address right and obtuse triangles as separate cases from acute triangles.

Problem Solving Strategies 
Concepts:
- Many geometry problems can be solved by assigning variables to lengths or angles in the problems, and then finding other lengths or angles in terms of the variables. The goal is usually to find a way to build an equation that you can solve.
- Area can be a surprisingly powerful problem solving tool, even in problems that don't appear to be about area.
- Once you think you've found a new formula, check your work by trying the formula on specific examples you have solved without the formula.
- Solving a specific example of a general problem can often provide a guide for solving the general problem.
- When stuck on a problem, focus on information you haven't used yet.
- If a tactic gives some information in a problem, but doesn't completely solve it, then try applying that tactic to the problem again in another way.
- Most complex problems can be solved in more than one way. So, don't get trapped into thinking that you need to find the way to solve the problem.
- Focusing on the key restrictions in a problem often leads to the solution.

Extra! On page 135, we asked you to find a $3-4-5$ right triangle in a problem. The $3-4-5$ triangle is in bold at right. The lower left square in the grid corresponds to the square in the original problem.

153

---

<!-- Page 154 -->

CHAPTER 4. APPLICATIONS TO GEOMETRY

Review Problems
4.26 In right triangle $S T U$, we have $\angle S=3 \angle T$ and $\angle U=90^{\circ}$. Find $S T / T U$ to the nearest hundredth.
4.27 Find all possible values of $\angle P Q R$ if $P Q=12, Q R=4 \sqrt{3}$, and the area of $\triangle P Q R$ is $12 \sqrt{6}$.
4.28 If $J K=12, K L=7$, and $\angle J L K=90^{\circ}$, then what is $\angle J K L$ to the nearest degree?
4.29 Let the graphs of $2 x-3 y=7$ and $3 x-y=9$ be $k$ and $\ell$, respectively.
(a) To the nearest degree, find the acute angle between $k$ and the $x$-axis.
(b) To the nearest degree, find the acute angle between $\ell$ and the $x$-axis.
(c) To the nearest degree, find the acute angle between $k$ and $\ell$.
(d) ★ Find an expression for the tangent of an angle between two lines with slopes $m_{1}$ and $m_{2}$, where $m_{1} \neq m_{2}$. Test your result with $k$ and $\ell$.
4.30 Two strips of width 1 overlap at an angle of $\alpha$ as shown. What is the area of the overlap in terms of $\alpha$ ? (Source: AHSME)
4.31 A boat sails 9 miles per hour along the latitude $30^{\circ} \mathrm{N}$. Assuming that the Earth is a sphere with radius 3950 miles, how long will it take the boat to sail from longitude $19^{\circ} \mathrm{W}$ to $46^{\circ} \mathrm{W}$ (to the nearest hour)?
4.32 $M$ is the midpoint of side $\overline{A B}$ of $\triangle A B C$. If $\angle A B C=90^{\circ}$, and $\sin \angle M C B=0.8$, then what is $\cos \angle A C B$ ?
4.33 Triangle $A B C$ has a right angle at $C, A C=3$ and $B C=4$. Triangle $A B D$ has a right angle at $A$ and $\underline{A D}=12$. Points $C$ and $D$ are on opposite sides of $\overline{A B}$. The line through $D$ parallel to $\overline{A C}$ meets $\overline{C B}$ extended at $E$. Find $D E / D B$. (Source: $A H S M E$ )
4.34 In $\triangle G H I$, we have $G H=H I=9$ and $G I=6$.
(a) Find $\tan \angle G I H$.
(b) Find $\tan \angle G H I$.
(c) Find $\cos \angle G H I$.
4.35 When I look due west, I look straight at a mountain peak that I know is 4.6 miles away. If I turn northward $37^{\circ}$, I will be looking directly at a mountain peak that is 5.8 miles away. To the nearest tenth of a mile, how far apart are the mountain peaks?
4.36 What's wrong with the following proof of the Pythagorean Theorem:

In the text, we proved that if $a=B C, b=A C$, and $c=A B$, then $c^{2}=a^{2}+b^{2}-2 a b \cos C$. If $\angle C=90^{\circ}$, then we have $\cos C=0$. Therefore, if $\angle C=90^{\circ}$, we have $c^{2}=a^{2}+b^{2}$.
4.37 Find the angles of a triangle with side lengths 2,2 , and $\sqrt{6}-\sqrt{2}$.
4.38 In $\triangle A B C, A B=5, B C=7, A C=9$, and $D$ is on $\overline{A C}$ with $B D=5$. Find $A D / D C$. (Source: $A H S M E$.
4.39 Is it possible for the three side lengths of a triangle to form an arithmetic sequence with common difference 1 , and have one angle with measure $60^{\circ}$ ? Why or why not?

154

---

<!-- Page 155 -->

CHALLENGE PROBLEMS
4.40 We define the dihedral angles between two intersecting planes as follows. Suppose line $k$ is the intersection of the planes, and point $A$ is on $k$. Let point $B$ be in one plane and $C$ in the other such that both $\overline{A B}$ and $\overline{A C}$ are perpendicular to $k$. Then, $\angle B A C$ and its supplement are the dihedral angles between the planes. (There are two dihedral angles between two intersecting planes, just as there are two angles between two intersecting lines.)

A regular tetrahedron is a triangular pyramid in which all four faces are equilateral triangles. Find the acute dihedral angle between two faces of a regular tetrahedron to the nearest tenth of a degree.
4.41 In $\triangle P Q R$, we have $P Q=4, Q R=6$, and $\angle P=2 \angle R$. Find $\cos \angle R$.
4.42 Does there exist a triangle $A B C$ such that $A B=3, B C=8, \angle A=73^{\circ}$, and $\angle C=57^{\circ}$ ? Why or why not?
4.43 A plane takes off, flies in straight line for 350 miles, then turns $20^{\circ}$ and flies straight for another 2 hours before landing at an airport that is 800 miles from where the plane took off. How long did the whole flight take if the plane flew at a constant speed throughout the flight?
4.44 The base of an isosceles triangle is 6 inches and one of the equal sides is 12 inches. What is the radius of the circle through the vertices of the triangle? (Source: AHSME)
4.45 Show that in $\triangle A B C$, if $A B \cos B=A C \cos C$, then $\angle B=\angle C$.
4.46 We showed in the text that there is no such thing as the "Side-Side-Angle Congruence Theorem." However, suppose $A B=D E=6, A C=D F=12$, and $\angle B C A=\angle E F D=30^{\circ}$. Use the Law of Sines to explain why we can conclude that $\triangle A B C \cong \triangle D E F$ in this special case. What makes this case special?
4.47 The Angle Bisector Theorem states that if $D$ is on side $\overline{B C}$ of $\triangle A B C$ such that $\angle B A D=\angle C A D$, then $A B / B D=A C / C D$. Prove the Angle Bisector Theorem.

Challenge Problems
4.48 In the diagram at right, $\overline{A D}$ is an altitude of $\triangle A B C$ with length 1 , and angles $B$ and $C$ are acute. Use the diagram at right to prove the angle sum identity for sine,
$$\sin (\alpha+\beta)=\sin \alpha \cos \beta+\sin \beta \cos \alpha$$

Hints: 278
4.49 Show that in $\triangle A B C$, we have $4 \cos \frac{A}{2} \cos \frac{B}{2} \cos \frac{C}{2}=\frac{S}{R}$.
4.50 Let $\triangle A B C$ be an acute triangle whose altitudes meet at point $H$, and let $X$ be on $\overline{B C}$ such that $\overline{A X} \perp \overline{B C}$. Show that $H X=2 R \cos B \cos C$. Hints: 63
4.51 In triangle $A B C, D$ is on $\overline{A C}$ and $F$ is on $\overline{B C}$. Also, $\overline{A B} \perp \overline{A C}, \overline{A F} \perp \overline{B C}$, and $B D=D C=F C=1$. Find $A C$. (Source: AHSME) Hints: 49
4.52 In quadrilateral $A B C D, B C=8, C D=12, A D=10$, and $\angle A=\angle B=60^{\circ}$. Find $A B$. (Source: AIME) Hints: 129, 101
4.53 A right circular cone has a base with radius 600 and height $200 \sqrt{7}$. An ant starts at a point on the surface of the cone whose distance from the vertex of the cone is 125 , and crawls along the surface of the cone to a point on the exact opposite side of the cone whose distance from the vertex is $375 \sqrt{2}$. Find the least distance that the ant could have crawled. (Source: AIME) Hints: 259

155

---

<!-- Page 156 -->

CHAPTER 4. APPLICATIONS TO GEOMETRY
4.54 In $\triangle A B C$, the angles $A, B$, and $C$ satisfy the equation $\cos A \cos B+\sin A \sin B \sin C=1$. Determine all possible values of $\angle C$. (Source: CEMC) Hints: 65
4.55 Consider a pyramid $P A B C D$ whose base $A B C D$ is square and whose vertex $P$ is equidistant from $A, B, C$, and $D$. Show that if $A B=1$ and $\angle A P B=2 \theta$, then the volume of the pyramid is $\sqrt{\cos 2 \theta} /(6 \sin \theta)$. (Source: AHSME)
4.56 Points $A, B$, and $C$ on a circle of radius $r$ are situated so that $A B=A C, A B>r$, and the length of minor arc $\overparen{B C}$ is $r$. Show that $A B / B C=\frac{1}{2} \csc \frac{1}{4}$. (Source: AHSME) Hints: 266
4.57 The lengths of the sides of a triangle are consecutive integers, and the largest angle is twice the smallest angle. What is the cosine of the smallest angle? (Source: AHSME) Hints: 248
4.58 Point $D$ is on side $\overline{C B}$ of triangle $A B C$. If $\angle C A D=\angle D A B=60^{\circ}, A C=3$, and $A B=6$, then what is the length of $\overline{A D}$ ? (Source: AHSME)
4.59 An observer walks along a level road directly towards an elevated object $P$. He takes observations at three points $A, B$, and $C$, in order, and notes that the angles of elevation of $P$ are $\theta, 2 \theta$, and $3 \theta$, respectively. Prove that $A B>2 B C$. (Source: CEMC) Hints: 238, 133
4.60 Point $D$ is on $\overline{B C}$ such that $\angle B A D=\angle C A D$. Find $A D$ in terms of $a, b$, and $c$, where $a=B C, b=A C$, and $c=A B$.
4.61 Triangle $A B C$ is isosceles with $A B=A C$ and altitude $A M=11$. Suppose that there is a point $D$ on $\overline{A M}$ with $A D=10$ and $\angle B D C=3 \angle B A C$. Find the perimeter of $\triangle A B C$. (Source: AIME) Hints: 110,92
4.62★ Find $\sin 18^{\circ}$. (See if you can find both a geometric and an algebraic solution.) Hints: 157, 90
4.63 Let $a, b, c$ be the three sides of a triangle, and let $\alpha, \beta, \gamma$, respectively, be the angles opposite them. If $a^{2}+b^{2}=1989 c^{2}$, find
$$\frac{\cot \gamma}{\cot \alpha+\cot \beta} .$$
(Source: AIME) Hints: 159
4.64 Show that if $A, B$, and $C$ are the angles of a triangle, then $\tan \frac{A}{2} \tan \frac{B}{2}+\tan \frac{B}{2} \tan \frac{C}{2}+\tan \frac{C}{2} \tan \frac{A}{2}=1$.
4.65★ The axis of the Earth makes an angle of $66.5^{\circ}$ with the plane in which it orbits the sun. The latitude of Vancouver is $49^{\circ} \mathrm{N}$, which means that if we form an angle by connecting Vancouver to the center of the Earth, and then connecting the center of the Earth to a point on the equator with the same longitude as Vancouver, the angle has measure $49^{\circ}$. (This is $\angle V O E$ at right.)

At right is a cross-section of the Earth that includes Vancouver and the Earth's axis. Vancouver is point $V$, point $E$ is on the equator, point $O$ is the center of the Earth, $S$ is the Sun, and $\overline{V Y}$ is perpendicular to the Earth's axis. The summer solstice is the day of the year with the most
hours of sunlight in the Northern hemisphere. Find the number of hours of sunlight Vancouver receives on the summer solstice. Hints: 219,27,171
4.66 Triangle $A B C$ is a right triangle with $A C=7, B C=24$, and right angle at $C$. Point $M$ is the midpoint of $A B$, and $D$ is on the same side of line $A B$ as $C$ so that $A D=B D=15$. Find the area of $\triangle C D M$. (Source: AIME)
4.67* A circle is inscribed in quadrilateral $A B C D$, tangent to $\overline{A B}$ at $P$ and to $\overline{C D}$ at $Q$. Given that $A P=19$, $P B=26, C Q=37$, and $Q D=23$, find the square of the radius of the circle. (Source: AIME) Hints: 78

156

---

<!-- Page 157 -->

CHALLENGE PROBLEMS
4.68★ Show that if $A, B$, and $C$ are the angles of a triangle, then
$$\cos ^{2} A+\cos ^{2} B+\cos ^{2} C+2 \cos A \cos B \cos C=1$$

Hints: 68,21
4.69★ .
(a) Prove that if $A B C D$ is a cyclic quadrilateral (a quadrilateral that can be inscribed in a circle), then the area of $A B C D$ is $\sqrt{(s-a)(s-b)(s-c)(s-d)}$, where $a, b, c$, and $d$ are the side lengths of $A B C D$ and $s=(a+b+c+d) / 2$. (This result is known as Brahmagupta's formula.) Hints: 260,3
(b) $\star$ Prove that the area of any quadrilateral $A B C D$ is
$$\sqrt{(s-a)(s-b)(s-c)(s-d)-a b c d \cos ^{2}\left(\frac{A+C}{2}\right)}$$
(This result is known as Bretschneider's formula.) Hints: 186, 169, 286
4.70★ In parallelogram $A B C D$, let $O$ be the intersection of diagonals $\overline{A C}$ and $\overline{B D}$. Angles $C A B$ and $D B C$ are each twice as large as angle $D B A$, and angle $A C B$ is $r$ times as large as angle $A O B$. Find $r$. (Source: AIME) Hints: 7
4.71★ Show that in $\triangle A B C$, we have
$$B C^{3} \cos (B-C)+C A^{3} \cos (C-A)+A B^{3} \cos (A-B)=3(B C)(C A)(A B)$$

Hints: 265

157

---

