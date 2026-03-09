# Chapter 8: Geometry of Complex Numbers

<!-- Page 256 -->

CHAPTER 8. GEOMETRY OF COMPLEX NUMBERS

The shortest path between two truths in the real domain passes through the complex domain. - Jacques Hadamard
8 8

Geometry of Complex Numbers

Many mathematical tools can be applied to a wide range of problems, including problems that seem very unrelated to each other. This chapter exhibits various deep relationships between two seemingly unrelated areas of mathematics: complex numbers and geometry. As you work through the following problems, keep in mind that many significant advances in mathematics have come from the realization that two seemingly different fields of mathematics are strongly related, or even the same.
8.1 Transformations of the Complex Plane

We start our investigation of the geometry of complex numbers with geometric transformations.
- Translation. When we apply a translation to a figure, we slide it a specified distance in a given direction. For example, points $A^{\prime}$ and $B^{\prime}$ at right are the result of translating $A$ and $B$, respectively, in the direction and by the distance suggested by the arrows. So, we say that $A^{\prime}$ is the "image" of $A$ under the translation shown at right, or that the translation "maps" $A$ to $A^{\prime}$. (We use the terms "image" and "maps" in this
manner with all transformations.)
- Rotation. When we rotate a figure, we spin it by some angle about some point. For example, in the diagram at right, the image of point $A$ under a rotation of angle $\theta$ counterclockwise about point $O$ is the point $A^{\prime}$ such that $O A=O A^{\prime}$ and $\angle A O A^{\prime}=\theta$, as shown at right. If $\theta$ is not an integer multiple of $\pi$, then there are two points that satisfy this description of $A^{\prime}$, which is why we must specify the orientation of the rotation as clockwise or counterclockwise. We call point $O$ the center of this rotation, and $\theta$ is the angle of rotation.

256

---

<!-- Page 257 -->

8.1. TRANSFORMATIONS OF THE COMPLEX PLANE
- Reflection. The image of point $A$ upon reflection over line $m$ is the point $A^{\prime}$ such that $m$ is the perpendicular bisector of $\overline{A A^{\prime}}$. In other words, if we fold our paper along line $m$, points $A$ and $A^{\prime}$ will coincide. If point $A$ is on $m$, then it is its own reflection. We call $m$ the axis of reflection.
- Dilation. At right is an example of dilation. Point $O$ is the center of dilation. The image of $A$ is the point $A^{\prime}$ on $\overrightarrow{O A}$ such that $O A^{\prime} / O A=2$. Similarly, the image of point $B$ is the point $B^{\prime}$ on $\overrightarrow{O B}$ such that $O B^{\prime} / O B=2$, and the image of point $C$ is the point $C^{\prime}$ on $\overrightarrow{O C}$ such that $O C^{\prime} / O C=2$. The image of the center of dilation is itself. We can think of the dilation as "stretching" $\triangle A B C$ away from $O$, and we say that $\triangle A^{\prime} B^{\prime} C^{\prime}$ is a dilation of $\triangle A B C$ about $O$.

In general, the image of a point $P$ upon dilation with scale factor $k$ and center $O$ is the point $P^{\prime}$ on $\overrightarrow{O P}$ such that $O P^{\prime}=k(O P)$ (when $k$ is positive).
The scale factor need not be positive. If the scale factor $k$ is negative, then the image of $P$ is the point $P^{\prime}$ on the ray from $O$ going in the opposite direction from $P$ such that $O P^{\prime}=|k| O P$.

We say that translations, rotations, and reflections are isometries, which means that they preserve distance. We can use this fact to show that a segment and its image under an isometry have the same length, and an angle and its image under an isometry have the same measure. A dilation is not an isometry, because it does not preserve length. It does, however, preserve angle measure, so, for example, $\angle A B C=\angle A^{\prime} B^{\prime} C^{\prime}$ in the dilation shown above.

We sometimes wish to speak about geometric figures in the complex plane that are more complicated than points, such as segments or triangles. Doing so with the notation of complex numbers could be confusing. For example, " $w z$ " typically refers to the product of complex numbers $w$ and $z$, not the segment from $w$ to $z$ in the complex plane. So, we usually stick to the notation of geometry when referring to such geometric objects in the complex plane. By convention, we use capital letters to denote points and the corresponding lowercase letters to denote corresponding complex numbers.

For example, in the diagram at right, point $P$ corresponds to the complex number $p$ and point $Q$ corresponds to the complex number $q$. We refer to the segment that connects $p$ and $q$ as $\overline{P Q}$. While we usually use capital letters for any geometric object besides a point, we will sometimes refer to points in the complex plane by the complex numbers to which they correspond. So, we could describe the situation depicted at right as either " $p$ is a $180^{\circ}$ rotation of $q$ about the origin" or " $P$ is a $180^{\circ}$ rotation of $Q$ about the origin."

Problems

Problem 8.1:
(a) What transformation maps any complex number $z$ to the complex number $z+2-3 i$ ?
(b) What transformation maps any complex number $z$ to $z+w$, where $w$ is a constant complex number?

Problem 8.2:
(a) If $z=\cos 12^{\circ}+i \sin 12^{\circ}+\cos 48^{\circ}+i \sin 48^{\circ}$, then what is the argument of $z$ ?
(b) Find $\operatorname{Im}\left(\left(\cos 12^{\circ}+i \sin 12^{\circ}+\cos 48^{\circ}+i \sin 48^{\circ}\right)^{6}\right)$.

257

---

<!-- Page 258 -->

CHAPTER 8. GEOMETRY OF COMPLEX NUMBERS

Problem 8.3: If $\omega$ and $\omega-i$ are both $n^{\text {th }}$ roots of unity, then what are the possible values of $n$ ?
Problem 8.4:
(a) What transformation maps $z$ to $2 z$ ?
(b) What transformation maps $z$ to $c z$, where $c$ is a positive real constant?

Problem 8.5:
(a) How are $z$ and $i z$ related to each other in the complex plane?
(b) Generalize your result from part (a) by finding a relationship between $z$ and $e^{i \alpha} z$ in the complex plane.

Problem 8.6: Describe in words the transformation that maps $z$ to $r e^{i \theta} \cdot z$, where $r$ is a positive real constant and $\theta$ is a real constant.

Problem 8.7: Let $q$ be the result of rotating $p$ an angle $\theta$ counterclockwise about $w$ in the complex plane. In this problem, we find $q$ in terms of $\theta, p$, and $w$.
(a) Let points $P, Q$, and $W$ correspond to complex numbers $p, q$, and $w$, respectively. Consider the translation that maps $W$ to the origin, $O$. Let this translation map $P$ to $P^{\prime}$ and $Q$ to $Q^{\prime}$. Find the complex numbers that correspond to $P^{\prime}$ and $Q^{\prime}$ in terms of $p, q$, and $w$.
(b) What is $\angle P^{\prime} O Q^{\prime}$ ?
(c) Why are $P^{\prime}$ and $Q^{\prime}$ equidistant from the origin?
(d) Find $q$ in terms of $p, w$, and $\theta$.

Problem 8.8: A pirate buries his treasure on a deserted island with an oak tree, a pine tree, and a gallows. To choose the burial location, he starts at the gallows and walks to the oak tree, counting his steps. When he reaches the oak tree, he turns right 90 degrees, walks the same number of steps as from the gallows to the oak tree, and places a spike in the ground.

He returns to the gallows, and then walks to the pine tree, again counting his steps. When he reaches the pine tree, he turns left 90 degrees, walks the same number of steps as from the gallows to the pine tree, and places another spike in the ground. He then buries the treasure at the midpoint of the segment with the spikes as endpoints, and then removes the spikes from the ground.

Years later, the pirate returns to the island to get his treasure. Unfortunately, the gallows are gone, and there is no sign of where it had been. Fortunately, the oak tree and pine tree are still there. In this problem, we help the pirate find his treasure. We do so by putting the problem on the complex plane.
(a) Let $g$ correspond to the gallows, $p$ to the pine, and $k$ to the oak. Find complex numbers in terms of $g, p$, and $k$ that correspond to each spike and to the treasure.
(b) When we place a geometry problem in the complex plane, we can choose where to place the origin. Suppose we choose the midpoint of the segment connecting the two trees as our origin. Then, how are $p$ and $k$ related? Why is this choice of origin so convenient?
(c) Where is the treasure?

Problem 8.1:
(a) What transformation maps any complex number $z$ to the complex number $z+2-3 i$ ?
(b) What transformation maps any complex number $z$ to $z+w$, where $w$ is a constant complex number?

258

---

<!-- Page 259 -->

8.1. TRANSFORMATIONS OF THE COMPLEX PLANE

Solution for Problem 8.1:
(a) We investigate by trying a few values of $z$. At right, we have plotted $2+4 i,-3+5 i$, and $-2 i$, and the results when we add $2-3 i$ to each. In each case, the result of the addition is 2 units to the right and 3 units below the original complex number. Writing $z$ as $a+b i$ makes it clear why $z+2-3 i$ is a translation of $z$ :
$$z+2-3 i=a+b i+2-3 i=(a+2)+(b-3) i$$

The effect of adding $2-3 i$ to $z$ is to add 2 to the real part (move 2 units right) and subtract 3 from the imaginary part (move 3 units down). Therefore, the result is a translation of $z$ by 2 units right and 3 units down.
(b) From our work in part (a), we aren't surprised to find that the transformation that maps $z$ to $z+w$ is a translation (even if $w=0$, which gives us the "do nothing" translation). If we let $w=c+d i$, we see that $z+w$ adds $c$ to the real part of $z$ (moves $c$ units horizontally) and adds $d$ to the imaginary part of $z$ (moves $d$ units vertically). Therefore, $z+w$ is a translation of $z$ by $c$ units horizontally and $d$ units vertically.

Problem 8.2: Find $\operatorname{Im}\left(\left(\cos 12^{\circ}+i \sin 12^{\circ}+\cos 48^{\circ}+i \sin 48^{\circ}\right)^{6}\right)$.

Solution for Problem 8.2: We could start by raising that whole expression to the sixth power, but that looks difficult. The angles are conveniently related, so we might try trig identities. This approach will work, but thinking about the problem geometrically gives a much faster solution.

Letting $w=\cos 12^{\circ}+i \sin 12^{\circ}$ and $z=\cos 48^{\circ}+i \sin 48^{\circ}$, our problem is to determine $\operatorname{Im}\left((w+z)^{6}\right)$. We know how to find $w+z$ in the complex plane when we have $w$ and $z$. Specifically, we let points $W, Z$, and $S$ in the complex plane correspond to $w, z$, and $w+z$, respectively, as shown at right. As we saw in Problem 8.1, adding a constant complex number $w$ corresponds to a translation in the complex plane. Adding $w$ to 0 and to $z$ give $w$ and $w+z$, respectively. So, the same translation that maps $O$ to $W$ also maps $Z$ to $S$. Therefore, $O W=Z S$ and $\overline{O W} \| \overline{Z S}$, which means that $O W S Z$ is a parallelogram. (We also saw this when we introduced graphing on the complex plane in Section 6.2.) Since $|w|=|z|$, we have $O Z=O W$, so this parallelogram is also a rhombus.

Since $O W S Z$ is a rhombus, diagonal $\overline{O S}$ bisects $\angle Z O W$. From the arguments of $W$ and $Z$, we know that $\angle W O A=12^{\circ}$ and $\angle Z O A=48^{\circ}$, so $\angle W O Z=36^{\circ}$ and $\angle S O W=\frac{1}{2} \angle W O Z=18^{\circ}$. This means that $\angle S O A=30^{\circ}$, which is an angle we like. Since $\angle S O A=30^{\circ}$, the argument of $w+z$ is $30^{\circ}$, which means we have $w+z=r e^{\pi i / 6}$ for some positive constant $r$. Therefore, $(w+z)^{6}=\left(r e^{\pi i / 6}\right)^{6}=r^{6} e^{\pi i}=r^{6}(-1)=-r^{6}$. We don't know exactly what the real part of this number is, but we know its imaginary part is 0 , so $\operatorname{Im}\left((w+z)^{6}\right)=0$.

Our solution to Problem 8.2 looks a lot longer than it really is. Once you're comfortable with the geometry of complex numbers, the observation that $w+z$ has argument $30^{\circ}$ is almost immediate, which makes determining that $\operatorname{Im}\left((w+z)^{6}\right)=0$ very easy.

Let's take another look at a problem that is simplified by thinking of adding complex numbers as a translation.
Problem 8.3: If $\omega$ and $\omega-i$ are both $n^{\text {th }}$ roots of unity, then what are the possible values of $n$ ?

259

---

<!-- Page 260 -->

CHAPTER 8. GEOMETRY OF COMPLEX NUMBERS

Solution for Problem 8.3: If we start algebraically, we have $\omega^{n}=(\omega-i)^{n}=1$. Um, then what? We sure don't want to expand $(\omega-i)^{n}$. We might write $\omega$ and $\omega-i$ in polar form and try to bash away with sines and cosines (you can take a swing at that on your own), but before we do that, let's think about the problem geometrically.

We let points $A$ and $B$ in the complex plane correspond to $\omega$ and $\omega-i$, respectively. Since $\omega$ and $\omega-i$ are both roots of unity, both are on the unit circle. The point $\omega-i$ is a one-unit downward translation of $\omega$, so $\overline{A B}$ is vertical with $A B=1$. Moreover, since $A$ and $B$ are on the unit circle, we have $O A=O B=1$, which means that $\triangle O A B$ is equilateral. Therefore, $\angle A O B=60^{\circ}$.

Since $\overline{A B}$ is vertical and no two points on the unit circle above the real axis are on the same vertical line, we know that $A$ and $B$ cannot both be above the real axis. Similarly, they cannot both be below it and neither can be on it, so one is above the real axis and the other is below it. Since $B$ is below $A$, we know that $A$ is above the real axis and $B$ is below it. The top half of the unit circle is the reflection of the bottom half over the real axis, so the real axis must bisect $\angle A O B$. This tells us that $\overline{A O}$ makes a $30^{\circ}$ angle with the real axis, limiting $A$ and $B$ to the two possibilities shown in the diagram, with points $A_{1}$ and $B_{1}$ forming one possible pair and points $A_{2}$ and $B_{2}$ forming the other possible pair.

For the first possibility we have $A_{1}=e^{\pi i / 6}$ and $B_{1}=e^{-\pi i / 6}$, and for the second we have $A_{2}=e^{5 \pi i / 6}$ and $B_{2}=e^{-5 \pi i / 6}$. Now, we're ready to find $n$.

If $\omega=e^{\pi i / 6}$ is an $n^{\text {th }}$ root of unity, we must have $\left(e^{\pi i / 6}\right)^{n}=1$, so $e^{\pi i n / 6}=1$. This means that $\pi i n / 6$ must be an integer multiple of $2 \pi$, so $\pi i n / 6=2 \pi i k$ for some integer $k$. Solving for $n$ gives $n=12 k$, which means that $n$ is a multiple of 12 . Similarly, if $\omega=e^{5 \pi i / 6}$, then we have $\left(e^{5 \pi i / 6}\right)^{n}=1$. This gives us $5 \pi i n / 6=2 \pi i k$ for some integer $k$, from which we find $5 n=12 k$. Once again, this means that $n$ is a multiple of 12 .

We must still confirm in both cases that $\omega-i$ is an $n^{\text {th }}$ root of unity when $n$ is a multiple of 12 . When $\omega=e^{\pi i / 6}$, we have $\omega-i=e^{-\pi i / 6}$ and
$$(\omega-i)^{n}=\left(e^{-\pi i / 6}\right)^{n}=\left(e^{-\pi i / 6}\right)^{12 k}=e^{-2 \pi i k}=1,$$
as desired. Similarly, when $\omega=e^{5 \pi i / 6}$, we have $\omega-i=e^{-5 \pi i / 6}$ and
$$(\omega-i)^{n}=\left(e^{-5 \pi i / 6}\right)^{n}=\left(e^{-5 \pi i / 6}\right)^{12 k}=e^{-10 \pi i k}=1 .$$
(We could also have noted that in both cases, we have $\omega-i=\bar{\omega}$, and we showed in Problem 7.21 that if $\omega$ is a root of unity, then so is $\bar{\omega}$.)

We can also use geometry to visualize the fact that $n$ must be a multiple of 12 . Our options for $A$ and $B$ are all primitive $12^{\text {th }}$ roots of unity, so the first 12 powers of each form the vertices of a regular dodecagon in the complex plane, as shown at left below.

Figure 8.1: $12{ }^{\text {th }}$ Roots of Unity

Figure 8.2: $24{ }^{\text {th }}$ Roots of Unity

Figure 8.3: $36{ }^{\text {th }}$ Roots of Unity

The diagrams above exhibit how the $12^{\text {th }}$ roots of unity are related to the $24^{\text {th }}$ and $36^{\text {th }}$ roots of unity. Similarly, whenever $n$ is a multiple of 12 , the $n^{\text {th }}$ roots of unity include the $12^{\text {th }}$ roots of unity. Moreover, if a regular $n$-gon

260

---

<!-- Page 261 -->

8.1. TRANSFORMATIONS OF THE COMPLEX PLANE

with all its vertices on the unit circle includes these 12 roots of unity among its vertices, then $n$ must be a multiple of 12 , because there will be an equal number of vertices of the $n$-gon between each two consecutive $12{ }^{\text {th }}$ roots of unity.

Problem 8.4:
(a) What transformation maps $z$ to $2 z$ ?
(b) What transformation maps $z$ to $c z$, where $c$ is a positive real constant?

Solution for Problem 8.4:
(a) We start by exploring a few examples. In the diagram at right, we have $2+i,-3+2 i$, and $1-2 i$, and the results of multiplying each of these by 2 . It appears that in each case, the result $2 z$ is on the ray from the origin through $z$, and that $2 z$ is twice as far from the origin as $z$ is. We can see why this occurs by looking at the exponential or polar form of $z$. Writing $z$ as re $e^{i \theta}$, we have
$$2 z=2 r e^{i \theta} .$$

So, the magnitude of $2 z$ is twice the magnitude of $z$, and the argument of $2 z$ is the same as that of $z$. Because the arguments of $2 z$ and $z$ are the same, they are on the same ray from the origin. Therefore, we conclude that $2 z$ is a dilation of $z$ about the origin with scale factor 2.
(b) Our previous part gives us a clear guide. Writing $z$ in exponential form gives us $c z=c r e^{i \theta}$, so the magnitude of $c z$ is $c$ times the magnitude of $z$, and the argument of $c z$ is the same as that of $z$. Therefore, $c z$ is on the ray from the origin through $z$, and is $c$ times as far from the origin as $z$, which means $c z$ is a dilation of $z$ about the origin with scale factor $c$.

If $c$ is negative, then the transformation that maps $z$ to $c z$ is still a dilation; it just has a negative scale factor, which means that $c z$ is in the opposite direction from the origin from $z$.

Problem 8.5:
(a) How are $z$ and $i z$ related to each other in the complex plane?
(b) Generalize your result from part (a) by finding a relationship between $z$ and $e^{i \alpha} z$ in the complex plane.

Solution for Problem 8.5:
(a) First, we experiment with a few values of $z$. If $z=1$, then $i z=i$. If $z=1+5 i$, then $i z=i(1+5 i)=-5+i$. If $z=-4-2 i$, then $i z=i(-4-2 i)= 2-4 i$. The latter two examples are depicted at right. In each of these three cases, we see that $i z$ is a $\frac{\pi}{2}$ counterclockwise rotation of $z$ about the origin.

Now that we know what to look for, we have a pretty strong clue how to prove it. Angles and complex numbers suggest using exponential form. Letting $z=r e^{i \theta}$ and noting that $i=e^{\pi i / 2}$, we have
$$i z=e^{\frac{\pi i}{2}} \cdot r e^{i \theta}=r e^{i\left(\theta+\frac{\pi}{2}\right)}$$

Therefore, $i z$ is just as far from the origin in the complex plane as $z$ is, but its argument is $\frac{\pi}{2}$ greater. That is, $i z$ in the complex plane is a $\frac{\pi}{2}$ counterclockwise rotation of $z$ about the origin.

261

---

<!-- Page 262 -->

CHAPTER 8. GEOMETRY OF COMPLEX NUMBERS
(b) The previous part gives us a guide. We let $z=r e^{i \theta}$, and we have
$$e^{i \alpha} z=e^{i \alpha} \cdot r e^{i \theta}=r e^{i(\alpha+\theta)} .$$

So, $e^{i \alpha} z$ and $z$ are the same distance from the origin, but the argument of $e^{i \alpha} z$ is $\alpha$ greater than the argument of $z$. Therefore, $e^{i \alpha} z$ is the result of rotating $z$ counterclockwise about the origin by an angle of $\alpha$.

Important: When $z$ is rotated $\alpha$ counterclockwise about the origin in the complex plane,
! the result is $e^{i \alpha} z$.

In Problems 8.1, 8.4, and 8.5, we explored a specific case of a transformation and then used our specific case as guidance to find a more general result. This is a very common and important strategy for finding proofs of general statements.

Concept: Many general results can be discovered by first exploring simple examples.

Problem 8.6: Describe in words the transformation that maps $z$ to $r e^{i \theta} \cdot z$, where $r$ is a positive real constant and $\theta$ is a real constant.

Solution for Problem 8.6: The transformation that maps $z$ to $r e^{i \theta} \cdot z$ is simply a combination of the transformations we learned in Problem 8.4 and Problem 8.5. From Problem 8.5, we know that $e^{i \theta} z$ is the result of rotating $z$ an angle of $\theta$ counterclockwise about the origin. From Problem 8.4, we know that $r \cdot\left(e^{i \theta} z\right)$ is the result of dilating $e^{i \theta} z$ by a scale factor of $r$ from the origin. Therefore, the transformation that maps $z$ to $r e^{i \theta} \cdot z$ is a counterclockwise rotation by an angle $\theta$ followed by a dilation with scale factor $r$.

Problem 8.7: If $q$ is the result of rotating $p$ an angle $\theta$ counterclockwise about $w$ in the complex plane, then find $q$ in terms of $\theta, p$, and $w$.

Solution for Problem 8.7: Let $Q$ be the image of a counterclockwise rotation of $P$ about $W$ by $\theta$, as shown, and let points $P, Q$, and $W$ correspond to complex numbers $p, q$, and $w$, respectively. The only rotations we know how to handle are rotations about the origin. So, we turn this problem into a problem we know how to handle by translating the center of rotation, $W$, to the origin. We apply the same translation to $P$ and to $Q$, and we have the diagram at right, where $P^{\prime}, Q^{\prime}$, and $W^{\prime}$ are the images of $P, Q$, and $W$ under the translation that maps $W$ to the origin.

The translation that maps $W$ to the origin must map the complex number $w$ to 0 . Therefore, this translation maps any complex number $z$ to $z-w$. Since $P^{\prime}$ is the image of $P$ under this translation, $P^{\prime}$ corresponds to the complex number $p^{\prime}=p-w$. Similarly, we have $q^{\prime}=q-w$, where $q^{\prime}$ corresponds to $Q^{\prime}$.

Next, we note that since $Q$ is the image of $P$ upon rotation about $W$, we have $Q W=W P$. Since translating a segment does not change its length, we have $Q^{\prime} W^{\prime}=W^{\prime} P^{\prime}$ as well. Translating an angle does not change its measure, so $\angle Q^{\prime} W^{\prime} P^{\prime}=\angle Q W P=\theta$. Since $Q^{\prime} W^{\prime}=W^{\prime} P^{\prime}$ and $\angle Q^{\prime} W^{\prime} P^{\prime}=\theta$, point $Q^{\prime}$ is the image of point $P^{\prime}$ upon a counterclockwise rotation of angle $\theta$.

The image of $z$ upon a counterclockwise rotation by $\theta$ about the origin is $e^{i \theta} z$. Since $Q^{\prime}$ is the image of $P^{\prime}$ under such a rotation, we have $q^{\prime}=e^{i \theta} p^{\prime}$. Substituting our expressions above for $p^{\prime}$ and $q^{\prime}$, we have $q-w=e^{i \theta}(p-w)$.

262

---

<!-- Page 263 -->

8.1. TRANSFORMATIONS OF THE COMPLEX PLANE

Solving for $q$ gives
$$q=e^{i \theta}(p-w)+w .$$

This is often easier to visualize in the form
$$q-w=e^{i \theta}(p-w)$$
for the reasons we discussed in our solution to Problem 8.7: $q-w$ and $p-w$ are the images under the translation that maps $w$ to the origin, and $e^{i \theta}(p-w)$ is the image upon rotating $p-w$ by $\theta$ about the origin.

Problem 8.8: A pirate buries his treasure on a deserted island with an oak tree, a pine tree, and a gallows. To choose the burial location, he starts at the gallows and walks to the oak tree, counting his steps. When he reaches the oak tree, he turns right 90 degrees, walks the same number of steps as from the gallows to the oak tree, and places a spike in the ground.

He returns to the gallows, and then walks to the pine tree, again counting his steps. When he reaches the pine tree, he turns left 90 degrees, walks the same number of steps as from the gallows to the pine tree, and places another spike in the ground. He then buries the treasure at the midpoint of the segment with the spikes as endpoints, and then removes the spikes from the ground.

Years later, the pirate returns to the island to get his treasure. Unfortunately, the gallows are gone, and there is no sign of where it had been. Fortunately, the oak tree and pine tree are still there. How can the pirate find his treasure?

Solution for Problem 8.8: We let $G, P$, and $K$ be the gallows, the pine, and the oak, respectively. We also let $S_{1}$ and $S_{2}$ be the spikes, and $T$ be the treasure, as shown in the diagram.

Because $G K=K S_{1}$ and $\angle G K S_{1}=90^{\circ}$, the first spike is a $90^{\circ}$ counterclockwise rotation of the gallows about the oak tree. (It's a counterclockwise rotation because the pirate turns right when he reaches the oak tree from the gallows.) We know how to handle rotations on the complex plane. Moreover, $90^{\circ}$ rotations are particularly easy to handle
with complex numbers. So, we place the problem on the complex plane. We let the lowercase letters of each of the point labels be the corresponding complex numbers.

Because $S_{1}$ is a $90^{\circ}$ counterclockwise rotation of $G$ about $K$, we have
$$s_{1}=k+(g-k) e^{\pi i / 2}=k+(g-k) i .$$

Similarly, the second spike is a $90^{\circ}$ clockwise rotation (because the pirate turns left at the pine) of the gallows about the pine, so
$$s_{2}=p+(g-p) e^{-\pi i / 2}=p+(g-p)(-i) .$$

To find the treasure, we have to figure out how to find the midpoint of the segment connecting two points on the complex plane. Fortunately, this is pretty easy. The midpoint of the segment connecting ( $x_{1}, y_{1}$ ) and ( $x_{2}, y_{2}$ ) in the Cartesian plane is $\left(\frac{x_{1}+x_{2}}{2}, \frac{y_{1}+y_{2}}{2}\right)$. In the complex plane, this means that the midpoint of the segment connecting $z_{1}=x_{1}+y_{1} i$ and $z_{2}=x_{2}+y_{2} i$ is
$$\left(\frac{x_{1}+x_{2}}{2}\right)+\left(\frac{y_{1}+y_{2}}{2}\right) i,$$

263

---

<!-- Page 264 -->

CHAPTER 8. GEOMETRY OF COMPLEX NUMBERS

which equals $\left(z_{1}+z_{2}\right) / 2$. Intuitively, this makes sense-it tells us that the midpoint of the segment connecting two complex numbers in the complex plane is the average of the two numbers.

Applying this to our problem to find $t$, the complex number corresponding to the treasure, we have
$$t=\frac{s_{1}+s_{2}}{2}=\frac{k+(g-k) i+p+(g-p)(-i)}{2}=\frac{k+g i-k i+p-g i+p i}{2}=\frac{k+p}{2}+\frac{p-k}{2} \cdot i .$$

There's no $g$ in this expression-that means that the location of the treasure doesn't depend on the gallows at all! It only depends on the pine and oak trees, which means that the pirate can still find the treasure.

But how? How can he find the point that corresponds to $\frac{k+p}{2}+\frac{p-k}{2} \cdot i$ ? One quick way he can do that is to choose his origin wisely.

Concept: When placing a geometric problem on the complex plane, we can choose where
to place the origin. Choosing a convenient point can often simplify the problem greatly.

We recognize the first term in the expression $\frac{k+p}{2}+\frac{p-k}{2} \cdot i$; the point corresponding to $\frac{k+p}{2}$ is the midpoint of the segment connecting the trees. So, if we choose this midpoint to be the origin, then $\frac{k+p}{2}=0$, and the treasure is simply at $\frac{p-k}{2} \cdot i$. Moreover, since $\frac{k+p}{2}=0$, we have $k+p=0$, so $k=-p$. Therefore, the treasure is at $\frac{p-(-p)}{2} \cdot i$, which simplifies to $p i$. Aha! The point corresponding to $p i$ is a $90^{\circ}$ counterclockwise rotation of $p$ about the origin.

We now have a plan to find the treasure. We find the midpoint of the segment connecting the trees. We measure the distance from that point to the pine tree. We stand at the midpoint (the origin of our complex plane), face the pine tree, turn $90^{\circ}$ counterclockwise, and then walk that measured distance in the direction we face. Then, we dig.

And we find the treasure.

On the way to finding the treasure, we also discovered an unsurprising geometric relationship on the complex plane.

Important: The midpoint of the segment connecting $z_{1}$ and $z_{2}$ in the complex plane is $\frac{z_{1}+z_{2}}{2}$.
!

Exercises
8.1.1 Suppose $w$ is the image of $z$ upon a $180^{\circ}$ rotation about the origin. Express $w$ in terms of $z$.
8.1.2
(a) What is the image of $3+i$ upon a $30^{\circ}$ counterclockwise rotation about the origin?
(b) What is the image of $3+i$ upon a $120^{\circ}$ clockwise rotation about $1+2 i$ ?
8.1.3 Note that argument of $w+z$ is average of the arguments of $w$ and $z$ in Problem 8.2. Is this always true? If not, when is it true?
8.1.4 Describe in words the transformation that maps $z$ to $z /\left(r e^{i \theta}\right)$, where $r$ is a positive real constant and $\theta$ is a real constant.

264

---

<!-- Page 265 -->

8.2. PARALLEL AND PERPENDICULAR LINES
8.1.5 For each of the following functions, describe the corresponding transformation that maps $z$ to $f(z)$.
(a) $f(z)=z-5+2 i$.
(b) $f(z)=3 z-1$.
(c) $f(z)=\left(\frac{1}{2}+\frac{\sqrt{3}}{2} i\right) z$.
(d) $f(z)=(-1+i) z$.
(e) $f(z)=-i z-1+3 i$.
8.1.6 Suppose that $U$ is on $\overline{W Z}$ in the complex plane such that $U W / U Z=a / b$. Show that if $u, w$, and $z$ are complex numbers corresponding to $U, W$, and $Z$, then $u=(a z+b w) /(a+b)$.
8.1.7 $\star$ Let $z_{1}$ be a complex number. Let $z_{2}$ be the complex number obtained when $z_{1}$ is rotated counterclockwise about the origin by $\frac{\pi}{2}$, and let $z_{3}$ be the complex number obtained when $z_{2}$ is rotated counterclockwise about $4+3 i$ by $\frac{\pi}{2}$. Then $z_{3}$ is the same as the point obtained when $z_{1}$ is rotated counterclockwise about $w$ by $\theta$. Find $w$ and $\theta$.
8.2 Parallel and Perpendicular Lines

Problems

Problem 8.9: Let $W$ and $Z$ be points in the complex plane corresponding to nonzero complex numbers $w$ and $z_{\text {, }}$ respectively, and let $O$ be the origin.
(a) Show that if $\overleftrightarrow{W Z}$ passes through $O$, then $z / w$ is a real number.
(b) Show that if $z / w$ is a real number, then $\overleftrightarrow{W Z}$ must pass through $O$.

Problem 8.10: Suppose $S, T$, and $U$ are points in the complex plane corresponding to distinct complex numbers $s, t$, and $u$, respectively. Three points are said to be collinear if a line passes through all three points. In this problem, we show that these three points are collinear if and only if ( $s-t) /(u-t)$ is real.

Let $O$ be the origin. Consider the translation that maps $T$ to the origin. Let $S^{\prime}$ and $U^{\prime}$ be the images of $S$ and $U$, respectively, under this translation, and let the complex numbers $s^{\prime}$ and $u^{\prime}$ correspond to $S^{\prime}$ and $U^{\prime}$, respectively.
(a) Explain why $S, T$, and $U$ are collinear if and only if $S^{\prime}, O$, and $U^{\prime}$ are. What must be true of $s^{\prime}$ and $u^{\prime}$ if and only if $S^{\prime}, O$, and $U^{\prime}$ are collinear?
(b) Show that $S, T$, and $U$ are collinear if and only if $(s-t) /(u-t)$ is real.

Problem 8.11: Let $\overline{A B}$ and $\overline{C D}$ be segments in the complex plane, and let $a, b, c$, and $d$ be complex numbers corresponding to the endpoints of these segments. Show that $\overleftrightarrow{A B} \| \overleftrightarrow{C D}$ if and only if $(b-a) /(d-c)$ is real.

Problem 8.12: Use complex numbers to show that a quadrilateral is a parallelogram if and only if its diagonals bisect each other.

Problem 8.13: Let $\overline{A B}$ and $\overline{C D}$ be segments in the complex plane, and let $a, b, c$, and $d$ be complex numbers corresponding to the endpoints of these segments. Find a condition similar to that in Problem 8.11 that is necessary and sufficient to show that $\overleftrightarrow{A B} \perp \overleftrightarrow{C D}$.

265

---

<!-- Page 266 -->

CHAPTER 8. GEOMETRY OF COMPLEX NUMBERS

Problem 8.14: Let $\overline{A B}$ and $\overline{C D}$ be segments in the complex plane, and let $a, b, c$, and $d$ be complex numbers corresponding to the endpoints of these segments.
(a) Show that $\overleftrightarrow{A B} \| \overleftrightarrow{C D}$ if and only if $(a-b)(\bar{c}-\bar{d})-(\bar{a}-\bar{b})(c-d)=0$.
(b) Show that $\overleftrightarrow{A B} \perp \overleftrightarrow{C D}$ if and only if $(a-b)(\bar{c}-\bar{d})+(\bar{a}-\bar{b})(c-d)=0$.

Problem 8.15: Suppose $V W X Y Z$ is a pentagon such that the altitudes from $V, W, X$, and $Y$ to the respective opposite sides of the pentagon ( $V$ to $\overline{X Y}, W$ to $\overline{Y Z}$, etc.) meet at a common point $P$. In this problem, we show that the altitude from $Z$ to $\overline{W X}$ passes through $P$ as well.
(a) Write four equations corresponding to the four given altitudes. (Tip: Choose your origin wisely!)
(b) Write an equation that must be true if the altitude from $Z$ to $\overline{W X}$ passes through $P$.
(c) Combine your equations in part (a) to produce the equation in part (b).

Problem 8.9: Let W and Z be points in the complex plane corresponding to nonzero complex numbers $w$ and $z$, respectively, and let $O$ be the origin. Show that $\overleftrightarrow{W Z}$ passes through $O$ if and only if $z / w$ is a real number.

Solution for Problem 8.9: We must show both of the following:
(a) If $\overleftrightarrow{W Z}$ passes through $O$, then $z / w$ is real.
(b) If $z / w$ is real, then $\overleftrightarrow{W Z}$ passes through $O$.

Important: Suppose $\mathcal{P}$ and $Q$ are mathematical statements. The statement " $\mathcal{P}$ if and only if
□ $Q^{\prime \prime}$ means both of the following:
- If $\mathcal{P}$ is true, then $Q$ is also true.
- If $Q$ is true, then $\mathcal{P}$ is also true.

Both of these statements must be proved in order to show that " $\mathcal{P}$ if and only if $Q$."

We'll prove parts (a) and (b) separately. We'll start with part (a). Since $W$ and $Z$ are on the same line through the origin, we know that we can transform $W$ to $Z$ by performing a dilation about the origin (possibly with a negative scale factor). Therefore, there is some real constant $c$ such that $z=c w$, from which we have $\frac{z}{w}=c$.

Next we must take care of part (b). If $\frac{z}{w}=c$, where $c$ is a real number, then we have $z=c w$. Since $c$ is real, this means that $Z$ is the image of $W$ under some dilation about the origin, which means that $Z$ is on $\overleftrightarrow{O W}$, as desired.

We also could have tackled part (b) by noting that if $w=r e^{i \theta}$, then $z=c r e^{i \theta}$. If $c>0$, then $W$ and $Z$ have the same argument. If $c<0$, then their arguments differ by $\pi$. In both cases, $W$ and $Z$ lie on the same line through the origin.

We say that three points are collinear if they lie on the same line. Now that we know how to tell if the line through two given points in the complex plane passes through the origin, let's see if we can develop a similar test to determine if any given three points are collinear.

Problem 8.10: Suppose $S, T$, and $U$ are distinct points in the complex plane corresponding to complex numbers $s, t$, and $u$, respectively. Show that $S, T$, and $U$ are collinear if and only if $(s-t) /(u-t)$ is real.

266

---

<!-- Page 267 -->

8.2. PARALLEL AND PERPENDICULAR LINES

Solution for Problem 8.10: Just as we did with the general rotation problem in Problem 8.7, we tackle the general problem of collinearity by using translations to turn it into a problem we already know how to solve. We know how to tell if the line through two points passes through the origin, so we translate all three points such that the image of one of these points is the origin. The images of $S$, $T$, and $U$ are collinear if and only if $S, T$, and $U$ are. (We can see this by noting that applying a translation to $\angle S T U$ will not change the measure of the angle.)

The expressions $s-t$ and $u-t$ in $(s-t) /(u-t)$ suggest translating $T$ to the origin, since such a translation maps $S$ and $U$ to points $S^{\prime}$ and $U^{\prime}$ such that
$s^{\prime}=s-t$ and $u^{\prime}=u-t$. Letting $O$ be the origin, we can now apply our result from Problem 8.9. There, we showed that $\overrightarrow{S^{\prime} U^{\prime}}$ passes through the origin if and only if $s^{\prime} / u^{\prime}$ is real. Substituting our expressions for $s^{\prime}$ and $u^{\prime}$, we see that $\overleftrightarrow{S^{\prime} U^{\prime}}$ passes through the origin if and only if $(s-t) /(u-t)$ is a real number. Since $S^{\prime}, O$, and $U^{\prime}$ are collinear if and only if $(s-t) /(u-t)$ is real, and $S, T$, and $U$ are collinear if and only if $S^{\prime}, O$, and $U^{\prime}$ are collinear, we conclude that $S, T$, and $U$ are collinear if and only if $(s-t) /(u-t)$ is real.

We'll now turn to parallel lines. In addition to the usual definition that two lines are parallel if they do not intersect, we will also say that a line is parallel to itself. We can think of this as "all lines with the same direction are parallel." We will make the concept of "direction" of a line more rigorous in Section 9.3.

Problem 8.11: Let $\overline{A B}$ and $\overline{C D}$ be segments in the complex plane, and let $a, b, c$, and $d$ be complex numbers corresponding to the endpoints of these segments. Show that $\overleftrightarrow{A B} \| \overleftrightarrow{C D}$ if and only if $(b-a) /(d-c)$ is a real number.

Solution for Problem 8.11: There's no need to reinvent the wheel here; we have a pretty clear guide how to tackle this problem in our solution to Problem 8.10. We start by translating $\overline{A B}$ such that the image of $A$ is the origin, $O$. Let the image of $B$ under this translation be $B^{\prime}$, so that $b^{\prime}=b-a$. Similarly, we translate $\overline{C D}$ such that the image of $C$ is the origin and the image of $D$ is $D^{\prime}$, which gives us $d^{\prime}=d-c$. Since $\overleftrightarrow{O B^{\prime}} \| \overleftrightarrow{A B}$ and $\overleftrightarrow{O D^{\prime}} \| \overleftrightarrow{C D}$, we have $\overleftrightarrow{A B} \| \overleftrightarrow{C D}$ if and only if $\overleftrightarrow{O B^{\prime}}$ and $\overleftrightarrow{O D^{\prime}}$ are the same line, because there is only one line through $O$ parallel to $\overleftrightarrow{A B}$. In Problem 8.9, we saw that $\overleftrightarrow{O B^{\prime}}$ and $\overleftrightarrow{O D^{\prime}}$ are the same line if and only if $b^{\prime} / d^{\prime}$ is real. Substituting our expressions above for $b^{\prime}$ and $d^{\prime}$, this tells us that $\overleftrightarrow{O B^{\prime}}$ and $\overleftrightarrow{O D^{\prime}}$ are the same line if and only if $(b-a) /(d-c)$ is real. Every step in our reasoning is an "if and only if" step, so we have proved that $\overleftrightarrow{A B} \| \overleftrightarrow{C D}$ if and only if $(b-a) /(d-c)$ is a real number.
$\stackrel{\text { Important: }}{\square}$
$\stackrel{\text { Important }}{\square}$

Let $\overline{A B}$ and $\overline{C D}$ be segments in the complex plane, and let $a, b, c$, and $d$ be complex numbers corresponding to the endpoints of these segments. Then lines $\overleftrightarrow{A B}$ and $\overleftrightarrow{C D}$ are parallel if and only if ( $b-a) /(d-c)$ is a real number.

267

---

<!-- Page 268 -->

CHAPTER 8. GEOMETRY OF COMPLEX NUMBERS

Problem 8.12: Use complex numbers to show that a quadrilateral is a parallelogram if and only if its diagonals bisect each other.

Solution for Problem 8.12: Let complex numbers $a, b, c$, and $d$ correspond to the vertices of quadrilateral $A B C D$ in the complex plane. Then, the midpoint of diagonal $\overline{A C}$ is $\frac{a+c}{2}$ and the midpoint of diagonal $\overline{B D}$ is $\frac{b+d}{2}$.

First, we show that if the diagonals of $A B C D$ bisect each other, then $A B C D$ is a parallelogram. If the diagonals of $A B C D$ bisect each other, then the midpoints of $\overline{A C}$ and $\overline{B D}$ are the same. That is, we have
$$\frac{a+c}{2}=\frac{b+d}{2},$$
so $a+c=b+d$. We'd like to show that $\overline{A B} \| \overline{D C}$, which we can prove by showing that $(b-a) /(c-d)$ is real. So, we rearrange $a+c=b+d$ as $c-d=b-a$. Dividing both sides by $c-d$ gives $\frac{b-a}{c-d}=1$. Since this is real, we have $\overline{A B} \| \overline{D C}$. We could go through essentially the same steps to show that $\overline{A D} \| \overline{B C}$, or we could note that since $c-d=b-a$, we have $|c-d|=|b-a|$, which means that $D C=A B$. Combining $A B=D C$ with $\overline{A B} \| \overline{D C}$ tells us that $A B C D$ is a parallelogram.

Important: Let $\overline{A B}$ and $\overline{C D}$ be segments in the complex plane, and let $a, b, c$, and $d$ be
complex numbers corresponding to the endpoints of these segments. We have $A B=C D$ if and only if $|b-a|=|d-c|$.

Next, we show that if $A B C D$ is a parallelogram, then the diagonals bisect each other. We can take a bit of a shortcut here by letting $A$ be the origin, which means the midpoint of $\overline{A C}$ is simply $\frac{c}{2}$. Then, because $\overline{A B} \| \overline{D C}$ and $A B=D C$, the translation that maps $B$ to $A$ also maps $C$ to $D$. This translation maps $B$ to the origin, so it maps any complex number $z$ to $z-b$. Because this translation also maps $C$ to $D$, we have $d=c-b$. Therefore, we have $d+b=c$, so the midpoint of $\overline{B D}$ is $\frac{b+d}{2}=\frac{c}{2}$. This tells us that diagonals $\overline{A C}$ and $\overline{B D}$ have the same midpoint, which means they bisect each other.

Having tackled parallel lines, let's turn to perpendicular lines.
Problem 8.13: Let $\overline{A B}$ and $\overline{C D}$ be segments in the complex plane, and let $a, b, c$, and $d$ be complex numbers corresponding to the endpoints of these segments. Find a condition similar to that in Problem 8.11 that is necessary and sufficient to show that $\overleftrightarrow{A B} \perp \overleftrightarrow{C D}$.

Solution for Problem 8.13: Solution 1: Use the method of previous problems. As before, we start with translations to the origin. We translate $\overline{A B}$ such that the image of $A$ is the origin. This translation maps $B$ to a point $B^{\prime}$ that corresponds to $b^{\prime}=b-a$. Similarly, we translate $\overline{C D}$ such that the image of $C$ is the origin, which means the image of $D$ is the point $D^{\prime}$ that corresponds to $d^{\prime}=d-c$.

Translating a segment does not change its orientation, so $\overleftrightarrow{A B} \| \overleftrightarrow{O B^{\prime}}$. Therefore, the angle $\overleftrightarrow{\mathrm{OD}^{\prime}}$ makes with $\overleftrightarrow{\mathrm{OB}^{\prime}}$ is the same as the angle $\overleftrightarrow{\mathrm{OD}^{\prime}}$ makes with $\overleftrightarrow{\mathrm{AB}}$. Similarly, $\overleftrightarrow{\mathrm{OB}^{\prime}}$ makes the same angle with $\overleftrightarrow{C D}$ as it makes with $\overleftrightarrow{O D^{\prime}}$. Combining these observations, we see that the angle between $\overleftrightarrow{A B}$ and $\overleftrightarrow{C D}$ is the same as that between $\overline{O B^{\prime}}$ and $\overline{O D^{\prime}}$. This means that $\overleftrightarrow{A B} \perp \overleftrightarrow{C D}$ if and only if $\overline{O B^{\prime}} \perp \overline{O D^{\prime}}$. Therefore, our problem now is to prove that $\overline{O B^{\prime}} \perp \overline{O D^{\prime}}$ if and only if $\frac{b-a}{d-c}$ is imaginary. Since $b^{\prime}=b-a$ and $d^{\prime}=d-c$, we must show that $\overline{O B^{\prime}} \perp \overline{O D^{\prime}}$ if and only if $b^{\prime} / d^{\prime}$ is imaginary.

268

---

<!-- Page 269 -->

8.2. PARALLEL AND PERPENDICULAR LINES

If $\overline{O B^{\prime}} \perp \overline{O D^{\prime}}$, then the arguments of $b^{\prime}$ and $d^{\prime}$ differ by $\frac{\pi}{2}$. Therefore, if $d^{\prime}$ in exponential form is $r e^{i \theta}$, then $b^{\prime}$ is $s e^{i(\theta+(\pi / 2))}$ or $s e^{i(\theta-(\pi / 2))}$, where $r$ and $s$ are real numbers. If $b^{\prime}=s e^{i(\theta+(\pi / 2))}$, then we have
$$\frac{b^{\prime}}{d^{\prime}}=\frac{s e^{i(\theta+(\pi / 2))}}{r e^{i \theta}}=\frac{s}{r} e^{\pi i / 2}=\frac{s}{r} .$$

Similarly, if $b^{\prime}=s e^{i(\theta-(\pi / 2))}$, then we find $\frac{b^{\prime}}{d^{\prime}}=-\frac{s}{r} i$. In either case, $\frac{s}{r}$ is real, so $\frac{b^{\prime}}{d^{\prime}}$ is an imaginary number.
We must also show that if $\frac{b^{\prime}}{d^{\prime}}=k i$ for some real constant $k$, then $\overline{O B^{\prime}} \perp \overline{O D^{\prime}}$. Multiplying both sides by $d^{\prime}$ gives $b^{\prime}=\left(k d^{\prime}\right) i$. Therefore, $B^{\prime}$ is a $90^{\circ}$ counterclockwise rotation about the origin of the point corresponding to $k d^{\prime}$. The point corresponding to $k d^{\prime}$ is a dilation of $D^{\prime}$ about the origin, so it is on $\overleftrightarrow{O D^{\prime}}$. Since $B^{\prime}$ is a $90^{\circ}$ rotation about the origin of a point on $\overleftarrow{O D^{\prime}}$, we have $\overline{O B^{\prime}} \perp \overline{O D^{\prime}}$, as desired.

Solution 2: Use the result of Problem 8.11. We turn our problem about perpendicular lines into one about parallel lines by rotating one of the lines $90^{\circ}$ about the origin. Let $\overleftrightarrow{C^{\prime} D^{\prime}}$ be the image of $\overleftrightarrow{C D}$ upon a $90^{\circ}$ rotation counterclockwise about the origin. Therefore, we have $c^{\prime}=c i$ and $d^{\prime}=d i$. We have $\overleftrightarrow{A B} \perp \overleftrightarrow{C D}$ if and only if $\overleftrightarrow{A B} \| \overleftrightarrow{C^{\prime} D^{\prime}}$. From Problem 8.11, we have $\overleftrightarrow{A B} \| \overleftrightarrow{C^{\prime} D^{\prime}}$ if and only if $\frac{b-a}{d^{\prime}-c^{\prime}}$ is a real number. That is, $\overleftrightarrow{A B} \| \overleftrightarrow{C^{\prime} D^{\prime}}$ if and only if $\frac{b-a}{d^{\prime}-c^{\prime}}=t$ for some real constant $t$. Substituting our expressions for $c^{\prime}$ and $d^{\prime}$, this equation becomes
$$\frac{b-a}{d i-c i}=t$$

Multiplying both sides by $i$ gives $\frac{b-a}{d-c}=t i$, which is imaginary. Therefore, we have $\overleftrightarrow{A B} \perp \overleftrightarrow{C D}$ if and only if $\frac{b-a}{d-c}$ is an imaginary number, as before.

Important: Let $\overline{A B}$ and $\overline{C D}$ be segments in the complex plane, and let $a, b, c$, and $d$ be
$\square$ complex numbers corresponding to the endpoints of these segments. Then $\overleftrightarrow{A B} \perp \overleftrightarrow{C D}$ if and only if ( $b-a) /(d-c)$ is an imaginary number.

Problem 8.14: Let $A, B, C$, and $D$ be four different points in the complex plane, and let $a, b, c$, and $d$ be complex numbers corresponding to these points.
(a) Show that $\overleftrightarrow{A B} \| \overleftrightarrow{C D}$ if and only if $(b-a)(\bar{d}-\bar{c})-(\bar{b}-\bar{a})(d-c)=0$.
(b) Show that $\overleftrightarrow{A B} \perp \overleftrightarrow{C D}$ if and only if $(b-a)(\bar{d}-\bar{c})+(\bar{b}-\bar{a})(d-c)=0$.

Solution for Problem 8.14:
(a) In Problem 8.11, we showed that $\overleftrightarrow{A B} \| \overleftrightarrow{C D}$ if and only if $(b-a) /(d-c)$ is real. Back on page 204, we showed that a complex number $z$ is real if and only if $\bar{z}=z$, which we can write as $z-\bar{z}=0$. So, because $\overleftrightarrow{A B} \| \overleftrightarrow{C D}$ if and only if $(b-a) /(d-c)$ is real, we must have $z-\bar{z}=0$ for $z=(b-a) /(d-c)$ :
$$\frac{b-a}{d-c}-\overline{\left(\frac{b-a}{d-c}\right)}=0$$

Since we have
$$\overline{\left(\frac{b-a}{d-c}\right)}=\frac{\overline{b-a}}{\overline{d-c}}=\frac{\bar{b}-\bar{a}}{\bar{d}-\bar{c}^{\prime}}$$
we can write Equation (8.1) as
$$\frac{b-a}{d-c}-\frac{\bar{b}-\bar{a}}{\bar{d}-\bar{c}}=0$$

Multiplying both sides by $d-c$ and by $\bar{d}-\bar{c}$, we have the desired
$$(b-a)(\bar{d}-\bar{c})-(\bar{b}-\bar{a})(d-c)=0$$

269

---

<!-- Page 270 -->

CHAPTER 8. GEOMETRY OF COMPLEX NUMBERS
(b) We can follow essentially the same steps as in the previous part. In Problem 8.13 we showed that $\overleftrightarrow{A B} \perp \overleftrightarrow{C D}$ if and only if $(b-a) /(d-c)$ is imaginary. Back on page 204, we learned that a complex number $z$ is imaginary if and only if $\bar{z}=-z$, which we can rearrange as $z+\bar{z}=0$. So, letting $z=(b-a) /(d-c)$, we have
$$\frac{b-a}{d-c}+\overline{\left(\frac{b-a}{d-c}\right)}=0$$
which we can write as
$$\frac{b-a}{d-c}+\frac{\bar{b}-\bar{a}}{\bar{d}-\bar{c}}=0 .$$

Multiplying both sides by $(d-c)(\bar{d}-\bar{c})$ gives
$$(b-a)(\bar{d}-\bar{c})+(\bar{b}-\bar{a})(d-c)=0$$

Our work in Problem 8.14 allows us to write the conditions " $(b-a) /(d-c)$ is a real number" and " $(b-a) /(d-c)$ is an imaginary number" as equations involving only $a, b, c$, and $d$. These equations are often much more convenient to work with than the qualitative description of $(b-a) /(d-c)$ being real or imaginary.

Important: Let $A, B, C$, and $D$ be four different points in the complex plane, and let $a, b, c$,
and $d$ be complex numbers corresponding to these points.
- We have $\overleftrightarrow{A B} \| \overleftrightarrow{C D}$ if and only if $(b-a)(\bar{d}-\bar{c})-(\bar{b}-\bar{a})(d-c)=0$
- We have $\overleftrightarrow{A B} \perp \overleftrightarrow{C D}$ if and only if $(b-a)(\bar{d}-\bar{c})+(\bar{b}-\bar{a})(d-c)=0$

These aren't really new observations; they are equations that follow from the conditions we found earlier under which $\overleftrightarrow{A B}$ and $\overleftrightarrow{C D}$ are either parallel or perpendicular.

Looking back at our solution to Problem 8.14, we actually proved something a little bit stronger than we were required to. We needed $A$ and $B$ to be different to define line $\overleftrightarrow{A B}$, and needed $C$ and $D$ be different to define $\overleftrightarrow{C D}$. But nowhere in our proof do we use the fact that $A$ and $B$ differ from $C$ and $D$ ! We could have had $B$ and $D$ be the same point, and every step in the proof holds. Therefore, by letting $B$ and $D$ be the same point, we have a condition for $A, B$, and $C$ to be collinear:

The condition for perpendicularity given above also holds if we let $B$ and $D$ be the same point.
Concept: Sometimes we can prove a statement by proving a more general statement.

Problem 8.15: Suppose $V W X Y Z$ is a pentagon such that the altitudes from $V, W, X$, and $Y$ to the respective opposite sides of the pentagon ( $V$ to $\overline{X Y}, W$ to $\overline{Y Z}$, etc.) meet at a common point $P$. Show that the altitude from Z to $\overline{W X}$ passes through $P$ as well.

270

---

<!-- Page 271 -->

8.2. PARALLEL AND PERPENDICULAR LINES

Solution for Problem 8.15: We are given four pairs of perpendicular lines and must use them to prove a fifth pair of lines are perpendicular. One point is common to all the pairs of lines: $P$. So, we'll let $P$ be the origin, expecting that to make our algebra simpler. We let $v, w, x, y, z$ be the complex numbers corresponding to the respective vertices of the pentagon. Since $\overleftrightarrow{V P} \perp \overleftrightarrow{X Y}$, we have
$$(v-0)(\bar{x}-\bar{y})+(\bar{v}-0)(x-y)=0 .$$

We simplify $v-0$ and $\bar{v}-0$, and then write similar equations for each of the other three altitudes, and we have
$$\begin{aligned}
v(\bar{x}-\bar{y})+\bar{v}(x-y) & =0, \\
w(\bar{y}-\bar{z})+\bar{w}(y-z) & =0, \\
x(\bar{z}-\bar{v})+\bar{x}(z-v) & =0, \\
y(\bar{v}-\bar{w})+\bar{y}(v-w) & =0 .
\end{aligned}$$

We'd like to prove that $\overleftrightarrow{\mathrm{ZP}} \perp \overleftrightarrow{\mathrm{WX}}$, which is true if and only if
$$z(\bar{w}-\bar{x})+\bar{z}(w-x)=0 .$$

Looking at our initial four equations above, we see that all the terms in the expansion of Equation (8.2) appear in the expansions of the first four equations. Unfortunately, there are a bunch more terms in those four equations. Let's go ahead and expand them and get a closer look at those extra terms:
$$\begin{aligned}
v \bar{x}-v \bar{y}+\bar{v} x-\bar{v} y & =0, \\
w \bar{y}-w \bar{z}+\bar{w} y-\bar{w} z & =0, \\
x \bar{z}-x \bar{v}+\bar{x} z-\bar{x} v & =0, \\
y \bar{v}-y \bar{w}+\bar{y} v-\bar{y} w & =0 .
\end{aligned}$$

If we add all of these equations, the extra terms will all cancel! For example, the $v \bar{x}$ in the first equation cancels with the $-\bar{x} v$ in the third equation, and the $-v \bar{y}$ in the first equation cancels with the $\bar{y} v$ in the fourth equation. The terms that don't cancel when we add all four equations leave us with
$$x \bar{z}-w \bar{z}+\bar{x} z-\bar{w} z=0 .$$

Factoring, multiplying by -1 , and doing a little rearranging, gives us
$$z(\bar{w}-\bar{x})+\bar{z}(w-x)=0$$
so $\overleftrightarrow{\mathrm{ZP}} \perp \overleftrightarrow{\mathrm{WX}}$, as desired.
We glossed over an important strategy in setting up our solution to Problem 8.15. We wrote the four equations corresponding to the four given altitudes in a way that made it clear that we would have a lot of cancellation when we added the four equations. For example, if instead of writing the four equations
$$\begin{aligned}
v(\bar{x}-\bar{y})+\bar{v}(x-y) & =0, \\
w(\bar{y}-\bar{z})+\bar{w}(y-z) & =0, \\
x(\bar{z}-\bar{v})+\bar{x}(z-v) & =0, \\
y(\bar{v}-\bar{w})+\bar{y}(v-w) & =0,
\end{aligned}$$
we had written the four equations
$$\begin{aligned}
v(\bar{x}-\bar{y})+\bar{v}(x-y) & =0 \\
w(\bar{y}-\bar{z})+\bar{w}(y-z) & =0 \\
x(\bar{z}-\bar{v})+\bar{x}(z-v) & =0 \\
y(\bar{w}-\bar{v})+\bar{y}(w-v) & =0
\end{aligned}$$
then adding the four equations won't cancel the $v \bar{y}$ and $y \bar{v}$ terms. We'd have to subtract the last equation instead, and our key step would be "add the first three equations and subtract the last," which is a much harder key step to see. (Look at the last equation in each set to see the difference between the two systems.)

271

---

<!-- Page 272 -->

CHAPTER 8. GEOMETRY OF COMPLEX NUMBERS

We make sure our equations are set up in a convenient way by building them in a consistent manner. Here, we can set our equations up with a nice symmetry by visualizing the pentagon, and making sure the three points in each equation appear in the same order that they appear when we travel counterclockwise around the pentagon. For example, we go counterclockwise when we go from $V$ to $X$ to $Y$ around the pentagon, and $v, x$, and $y$ appear in that order in the first equation. Similarly, we go counterclockwise to go from $W$ to $Y$ to $Z$, so $w, y, z$ appear in
that order in the second equation, and so on.

Concept: Maintaining symmetry in systems of equations helps us find effective ways to
work with the equations.
8.2.1 Which of the following complex numbers lies on the line through $1+3 i$ and $5-2 i$ in the complex plane: $3-2 i, 9-7 i,-2+5 i$.
8.2.2 Show that the equation whose graph consists of all complex numbers $z$ on the line through $a$ and $b$ in the complex plane is
$$\frac{z-a}{b-a}=\frac{\bar{z}-\bar{a}}{\bar{b}-\bar{a}} .$$
8.2.3 Prove that the quadrilateral formed by connecting the midpoints of any quadrilateral is a parallelogram.
8.2.4 In Problem 8.13, we used an algebraic approach to show that if $O$ is the origin and points $B^{\prime}$ and $D^{\prime}$ in the complex plane satisfy $\overline{O B^{\prime}} \perp \overline{O D^{\prime}}$, then $\frac{b^{\prime}}{d^{\prime}}$ is an imaginary number, where $b^{\prime}$ and $d^{\prime}$ are the complex numbers corresponding to $B^{\prime}$ and $D^{\prime}$, respectively. Prove this fact using geometric transformations. That is, find a sequence of transformations that maps $B^{\prime}$ to $D^{\prime}$, and use this sequence to explain why $\frac{b^{\prime}}{d^{\prime}}$ must be imaginary.
8.2.5 A median of a triangle is the segment from a vertex of the triangle to the midpoint of the opposite side. In this problem, we show that the medians of a triangle are concurrent at a point called the centroid, and show that the distance from a vertex of the triangle to the triangle's centroid is $2 / 3$ the length of the median from that vertex.
(a) Let $a, b$, and $c$ be complex numbers corresponding to the respective vertices of $\triangle A B C$. Show that if $g=(a+b+c) / 3$ corresponds to point $G$, then point $G$ is on all three medians.
(b) Let $M$ be the midpoint of $\overline{B C}$. Show that $A G / G M=2$.
8.2.6 Show that the complex numbers $a, b$, and $c$ are collinear if and only if
$$a \bar{b}+b \bar{c}+c \bar{a}=\bar{a} b+\bar{b} c+\bar{c} a .$$
8.2.7 In convex quadrilateral $W X Y Z$, the midpoints of $\overline{W X}, \overline{W Y}$, and $\overline{X Z}$ are collinear. Show that the line through these points also passes through the midpoint of $\overline{Y Z}$.
8.2.8 $\star$ Let $A$ correspond to $1-5 i, B$ correspond to $3+2 i, C$ correspond to $-7 \sqrt{3}+7 i$, and $D$ correspond to $-2-2 i \sqrt{3}$. Find the acute angle between $\overleftrightarrow{A B}$ and $\overleftrightarrow{C D}$.
8.3 Distance

We introduced the magnitude of a complex number as the distance between that complex number and the origin in the complex plane. From this definition, we also saw that if $w$ and $z$ are complex numbers, then $|w-z|$ is the

272

---

<!-- Page 273 -->

8.3. DISTANCE

distance between $w$ and $z$ in the complex plane. In this section, we use the magnitude of complex numbers to solve problems involving lengths of segments.

Problems
Problem 8.16: Let complex numbers $w$ and $z$ correspond to points $W$ and $Z$ in the complex plane. Show that $W Z^{2}=(w-z)(\bar{w}-\bar{z})$.

Problem 8.17: Prove that $\overleftrightarrow{A B} \perp \overleftrightarrow{C D}$ if and only if $A C^{2}+B D^{2}=A D^{2}+B C^{2}$.
Problem 8.18: Let $c$ be a complex number and $t$ be a real number such that $t<c \bar{c}$. In this problem, we show that the graph of an equation of the form
$$z \bar{z}-c \bar{z}-\bar{c} z+t=0$$
is a circle.
(a) Find an equation whose graph is a circle with center $c$ and radius $r$.
(b) Show that the equation you found in part (a) is equivalent to $z \bar{z}-c \bar{z}-\bar{c} z+t=0$ for some real number $t$. Why must we have the restriction $t<c \bar{c}$ ?

Problem 8.19: In this problem, we find the figure that consists of all points Z such that $A \mathrm{Z}=k \cdot B \mathrm{Z}$, where $A$ and $B$ are points and $k$ is a positive real number with $k \neq 1$.
(a) Let $A$ be the origin and $B$ be 1 in the complex plane. Find an equation whose graph consists of the points $Z$ such that $A Z=k \cdot B Z$.
(b) Show that the desired figure is a circle.

Problem 8.20: The Triangle Inequality is a fancy way to say that the shortest distance between two points is a straight line. Specifically, the Triangle Inequality tells us that for any three points $A, B$, and $C$, we have
$$A B+B C \geq A C,$$
where equality holds if and only if $B$ is on $\overline{A C}$.
(a) Let $w$ and $z$ be complex numbers. Use the Triangle Inequality to prove that $|w|+|z| \geq|w+z|$. Under what conditions do we have $|w|+|z|=|w+z|$ ?
(b) Let $z_{1}, z_{2}, \ldots, z_{n}$ be complex numbers. Prove that $\left|z_{1}\right|+\left|z_{2}\right|+\cdots+\left|z_{n}\right| \geq\left|z_{1}+z_{2}+\cdots+z_{n}\right|$. Under what conditions do we have $\left|z_{1}\right|+\left|z_{2}\right|+\cdots+\left|z_{n}\right|=\left|z_{1}+z_{2}+\cdots+z_{n}\right|$ ?
(c) Show that for any real numbers $a, b, c$, and $d$, we have $\sqrt{a^{2}+b^{2}}+\sqrt{c^{2}+d^{2}} \geq \sqrt{(a+c)^{2}+(b+d)^{2}}$.

Problem 8.21: Find the smallest possible value of $|z-5|+|z+4-3 i|$.

Problem 8.16: Let complex numbers $w$ and $z$ correspond to points $W$ and $Z$ in the complex plane. Show that $W Z^{2}=(w-z)(\bar{w}-\bar{z})$.

Solution for Problem 8.16: We have $W Z=|w-z|$, so
$$W Z^{2}=|w-z|^{2}=(w-z) \overline{(w-z)}=(w-z)(\bar{w}-\bar{z}),$$
as desired.

273

---

<!-- Page 274 -->

CHAPTER 8. GEOMETRY OF COMPLEX NUMBERS

Important: If complex numbers $w$ and $z$ correspond to points $W$ and $Z$ in the complex
! plane, then $W Z^{2}=(w-z)(\bar{w}-\bar{z})$.

Problem 8.17: Prove that $\overleftrightarrow{A B} \perp \overleftrightarrow{C D}$ if and only if $A C^{2}+B D^{2}=A D^{2}+B C^{2}$.

Solution for Problem 8.17: We think to use complex numbers in this problem because we have a straightforward expression for the square of the distance between two points in the complex plane, and we have a somewhat similar simple condition for perpendicularity. We let $a, b, c$, and $d$ be complex numbers corresponding to points $A, B, C$, and $D$ in the complex plane. We then have
$$\begin{array}{l}
A C^{2}+B D^{2}=(a-c)(\bar{a}-\bar{c})+(b-d)(\bar{b}-\bar{d})=a \bar{a}-a \bar{c}-c \bar{a}+c \bar{c}+b \bar{b}-b \bar{d}-d \bar{b}+d \bar{d} \\
A D^{2}+B C^{2}=(a-d)(\bar{a}-\bar{d})+(b-c)(\bar{b}-\bar{c})=a \bar{a}-a \bar{d}-d \bar{a}+d \bar{d}+b \bar{b}-b \bar{c}-c \bar{b}+c \bar{c}
\end{array}$$

We see a lot of common terms in these, so subtracting will give us some cancellation:
$$\begin{aligned}
\left(A C^{2}+B D^{2}\right)-\left(A D^{2}+B C^{2}\right) & =(-a \bar{c}-c \bar{a}-b \bar{d}-d \bar{b})+(a \bar{d}+d \bar{a}+b \bar{c}+c \bar{b}) \\
& =a(\bar{d}-\bar{c})+b(\bar{c}-\bar{d})+c(\bar{b}-\bar{a})+d(\bar{a}-\bar{b}) \\
& =a(\bar{d}-\bar{c})-b(\bar{d}-\bar{c})-c(\bar{a}-\bar{b})+d(\bar{a}-\bar{b}) \\
& =(a-b)(\bar{d}-\bar{c})+(d-c)(\bar{a}-\bar{b})
\end{aligned}$$

So, we now have $A C^{2}+B D^{2}=A D^{2}+B C^{2}$ if and only if $(a-b)(\bar{d}-\bar{c})+(d-c)(\bar{a}-\bar{b})=0$. But this is exactly the condition for perpendicularity that we proved on page 270. Since $A C^{2}+B D^{2}=A D^{2}+B C^{2}$ if and only if $(a-b)(\bar{d}-\bar{c})+(d-c)(\bar{a}-\bar{b})=0$, and $(a-b)(\bar{d}-\bar{c})+(d-c)(\bar{a}-\bar{b})=0$ if and only if $\overleftrightarrow{A B} \perp \overleftrightarrow{C D}$, we have $A C^{2}+B D^{2}=A D^{2}+B C^{2}$ if and only if $A C^{2}+B D^{2}=A D^{2}+B C^{2}$.

So far, we've discussed points, lines, and distance. Since a circle is defined in terms of a point and a distance, we can describe a circle in the complex plane as the graph of an equation.

Problem 8.18: Let $c$ be a complex number and $t$ be a real number such that $t<c \bar{c}$. Show that the graph of an equation of the form
$$z \bar{z}-c \bar{z}-\bar{c} z+t=0$$
is a circle.

Solution for Problem 8.18: If point $z$ is on the circle with center $c$ and radius $r$, then $|z-c|=r$. Since both sides of $|z-c|=r$ are positive, the graph of $|z-c|=r$ is the same as the graph of $|z-c|^{2}=r^{2}$. We prefer this latter form because it allows us to get rid of the magnitude symbol, since $|z-c|^{2}=(z-c) \overline{(z-c)}=(z-c)(\bar{z}-\bar{c})$. So, the equation $|z-c|^{2}=r^{2}$ becomes
$$(z-c)(\bar{z}-\bar{c})=r^{2}$$

Expanding the left side and subtracting $r^{2}$ from both sides gives
$$z \bar{z}-\bar{c} z-c \bar{z}+c \bar{c}-r^{2}=0$$

Since $c \bar{c}$ must be real and $r^{2}$ is real, letting $t=c \bar{c}-r^{2}$ gives us
$$z \bar{z}-\bar{c} z-c \bar{z}+t=0$$
where $t$ is the real number $c \bar{c}-r^{2}$.

274

---

<!-- Page 275 -->

8.3. DISTANCE

To see that the graph of any such equation is a circle if $t<c \bar{c}$, we need only walk backwards through our steps above. We write $t$ as $c \bar{c}+t-c \bar{c}$, so we have
$$z \bar{z}-\bar{c} z-c \bar{z}+c \bar{c}+t-c \bar{c}=0 .$$

Factoring the first four terms and moving the other terms to the other side of the equation gives $(z-c)(\bar{z}-\bar{c})=c \bar{c}-t$, so $(z-c) \overline{(z-c)}=c \bar{c}-t$. Therefore, we have
$$|z-c|^{2}=c \bar{c}-t$$

The left side must be nonnegative. Now we see why we must have the condition $t<c \bar{c}$. We can write $c \bar{c}-t=r^{2}$ for some positive $r$, and we have $|z-c|^{2}=r^{2}$. Taking the square root gives $|z-c|=r$, and we know the graph of this equation is a circle with center $c$ and radius $r$.

The equation we just found for a circle in the complex plane is rather unwieldy, so we usually stick to the tools of Euclidean geometry in problems involving circles. However, applications of complex numbers to circles can be very effective, as we'll see in the next problem.

Problem 8.19: What figure consists of all points Z such that $A \mathrm{Z}=k \cdot B \mathrm{Z}$, where $A$ and $B$ are points and $k$ is a positive real number with $k \neq 1$ ?

Solution for Problem 8.19: We let $a, b$, and $z$ correspond to $A, B$, and Z , respectively, so that $A \mathrm{Z}=k \cdot B Z$ becomes $|z-a|=k|z-b|$. Before we square this equation to get rid of the magnitudes (which we can safely do because both sides are positive), we make life a bit easier on ourselves by letting $a=0$ and $b=1$, because this makes our equation $|z|=k|z-1|$. We can make this simplification because no matter where $A$ and $B$ are, we can draw the axes such that $A$ is the origin and $B$ corresponds to 1 on the real axis.

Squaring both sides of $|z|=k|z-1|$ gives $|z|^{2}=k^{2}|z-1|^{2}$, from which we have
$$z \bar{z}=k^{2}(z-1) \overline{(z-1)}=k^{2}(z-1)(\bar{z}-1)=k^{2}(z \bar{z}-z-\bar{z}+1) .$$

Rearranging gives
$$\left(k^{2}-1\right) z \bar{z}-k^{2} z-k^{2} \bar{z}+k^{2}=0 .$$

Dividing by $k^{2}-1$ gives
$$z \bar{z}-\frac{k^{2}}{k^{2}-1} z-\frac{k^{2}}{k^{2}-1} \bar{z}+\frac{k^{2}}{k^{2}-1}=0$$

If we let $c=t=\frac{k^{2}}{k^{2}-1}$, then we can write this equation in the form that we found in Problem 8.18:
$$z \bar{z}-\bar{c} z-c \bar{z}+t=0 .$$
(Note that $c=\bar{c}$ because $c$ is real.) We must only confirm that $c \bar{c}-t>0$ to deduce that the graph is a circle. Since $t=c=\bar{c}$, we have
$$c \bar{c}-t=c^{2}-c=c(c-1)=\left(\frac{k^{2}}{k^{2}-1}\right)\left(\frac{k^{2}}{k^{2}-1}-1\right)=\left(\frac{k^{2}}{k^{2}-1}\right)\left(\frac{1}{k^{2}-1}\right)=\frac{k^{2}}{\left(k^{2}-1\right)^{2}}$$
which is clearly positive, so the graph is a circle. Since $c=\frac{k^{2}}{k^{2}-1}$, the center of this circle is the point corresponding to $\frac{k^{2}}{k^{2}-1}$ on the real axis. And since $c \bar{c}-t=\frac{k^{2}}{\left(k^{2}-1\right)^{2}}$, the radius of the circle is $\frac{k}{k^{2}-1}$.

The circle we discovered in Problem 8.19 is called a circle of Apollonius, which is a circle that is defined as the set of points $Z$ such that $A Z=k \cdot B Z$ for some given points $A$ and $B$ and some positive constant $k \neq 1$.

We'll finish our discussion of distance in the complex plane with the Triangle Inequality, which is a fancy way to say that the shortest distance between two points is a straight line.

275

---

<!-- Page 276 -->

CHAPTER 8. GEOMETRY OF COMPLEX NUMBERS

Important: The Triangle Inequality states that for any three points $A, B$, and $C$, we have
(1)
$$A B+B C \geq A C,$$
where equality holds if and only if $B$ is on $\overline{A C}$.

Problem 8.20:
(a) Let $w$ and $z$ be complex numbers. Show that $|w|+|z| \geq|w+z|$. Under what conditions do we have $|w|+|z|=|w+z| ?$
(b) Let $z_{1}, z_{2}, \ldots, z_{n}$ be complex numbers. Prove that $\left|z_{1}\right|+\left|z_{2}\right|+\cdots+\left|z_{n}\right| \geq\left|z_{1}+z_{2}+\cdots+z_{n}\right|$. Under what conditions do we have $\left|z_{1}\right|+\left|z_{2}\right|+\cdots+\left|z_{n}\right|=\left|z_{1}+z_{2}+\cdots+z_{n}\right|$ ?
(c) Show that for any real numbers $a, b, c$, and $d$, we have $\sqrt{a^{2}+b^{2}}+\sqrt{c^{2}+d^{2}} \geq \sqrt{(a+c)^{2}+(b+d)^{2}}$.

Solution for Problem 8.20:
(a) First, we note that the inequality obviously holds (and equality holds) if $w$ or $z$ is 0 . To address the case in which both are nonzero, we turn to the complex plane. Let points $W, Z$, and $S$ correspond to complex numbers $w, z$, and $w \dot{+} z$, respectively, and let $O$ be the origin. As we have seen several times before, OWSZ is a parallelogram, so $W S=O Z=|z|$. Applying the Triangle Inequality to $\triangle O W S$ gives us $O W+W S \geq O S$. We have $O W=|w|, W S=|z|$ and $O S=|w+z|$, so we have $|w|+|z| \geq|w+z|$, as desired.

We have equality in the Triangle Inequality $O W+W S \geq O S$ if and only if $W$ is on $\overline{O S}$, so we have equality if and only if $w$ is on the segment connecting the origin to $w+z$ in the complex plane. Since $w$ is nonzero, this means $w+z$ must be nonzero and that $w=c(w+z)$ for some real constant $c$ with $0<c \leq 1$. Solving for $z$, we have $z=\frac{w}{c}-w=\left(\frac{1}{c}-1\right) w$. Since $0<c \leq 1$, we have $\frac{1}{c}-1>0$, so $z=\left(\frac{1}{c}-1\right) w$ tells us that $z$ is a dilation of $w$ about the origin with nonnegative scale factor. This means that $w$ and $c$ are on the same ray from the origin.
(b) We can extend the first part to the sum of the magnitudes of any number of complex numbers. Repeatedly applying part (a), we have
$$\begin{aligned}
\left|z_{1}\right|+\left|z_{2}\right|+\left|z_{3}\right|+\cdots+\left|z_{n}\right| & \geq\left|z_{1}+z_{2}\right|+\left|z_{3}\right|+\cdots+\left|z_{n}\right| \\
& \geq\left|z_{1}+z_{2}+z_{3}\right|+\left|z_{4}\right|+\cdots+\left|z_{n}\right| \\
& \geq \\
& \geq\left|z_{1}+z_{2}+z_{3}+\cdots+z_{n-1}\right|+\left|z_{n}\right| \\
& \geq\left|z_{1}+z_{2}+\cdots+z_{n}\right|
\end{aligned}$$

To see when equality holds, we note that we must have equality in each step above in order to have
$$\left|z_{1}\right|+\left|z_{2}\right|+\left|z_{3}\right|+\cdots+\left|z_{n}\right|=\left|z_{1}+z_{2}+\cdots+z_{n}\right| .$$

In our first step on line (8.3), we use the result of part (a) to get $\left|z_{1}\right|+\left|z_{2}\right| \geq\left|z_{1}+z_{2}\right|$, where equality holds if and only if $z_{1}$ and $z_{2}$ are on the same ray through the origin. If $z_{1}$ and $z_{2}$ are on the same ray through the origin, then $z_{1}+z_{2}$ is on this ray as well. In our next step on line (8.4), we again apply the result of part (a) to get $\left|z_{1}+z_{2}\right|+\left|z_{3}\right| \geq\left|z_{1}+z_{2}+z_{3}\right|$, where equality holds if and only if $z_{1}+z_{2}$ and $z_{3}$ are on the same ray through the origin. The ray from the origin through $z_{1}+z_{2}$ is also the ray through $z_{1}$ and $z_{2}$ (if equality holds in our first application of the Triangle Inequality), so we have $\left|z_{1}\right|+\left|z_{2}\right|+\left|z_{3}\right| \geq\left|z_{1}+z_{2}+z_{3}\right|$ if and only if $z_{1}, z_{2}$, and $z_{3}$ are on the same ray from the origin. Continuing in this way, we see that we have
$$\left|z_{1}\right|+\left|z_{2}\right|+\left|z_{3}\right|+\cdots+\left|z_{n}\right|=\left|z_{1}+z_{2}+\cdots+z_{n}\right|$$

276

---

<!-- Page 277 -->

8.3. DISTANCE

if and only if $z_{1}, z_{2}, z_{3}, \ldots, z_{n}$ are on the same ray from the origin.
(c) We can use magnitude to relate the square root of a sum of squares to a complex number: $|a+b i|=\sqrt{a^{2}+b^{2}}$. Similarly, we have $|c+d i|=\sqrt{c^{2}+d^{2}}$, so from the Triangle Inequality expression
$$|a+b i|+|c+d i| \geq|(a+b i)+(c+d i)|,$$
we have
$$\sqrt{a^{2}+b^{2}}+\sqrt{c^{2}+d^{2}} \geq|(a+c)+(b+d) i|=\sqrt{(a+c)^{2}+(b+d)^{2}} .$$

Important: For any complex numbers $z_{1}, z_{2}, z_{3}, \ldots, z_{n}$, we have
$$\left|z_{1}\right|+\left|z_{2}\right|+\cdots+\left|z_{n}\right| \geq\left|z_{1}+z_{2}+\cdots+z_{n}\right|,$$
where equality holds if and only if $z_{1}, z_{2}, z_{3}, \ldots, z_{n}$ are on the same ray from the origin.

The version with two terms, $\left|z_{1}\right|+\left|z_{2}\right| \geq\left|z_{1}+z_{2}\right|$, is often referred to as the Triangle Inequality. In Problem 8.20, we proved this algebraic expression of the Triangle Inequality by using the geometric expression of it. You might wonder if it's possible to go the other way-can we use the algebra of complex numbers to deduce that $\left|z_{1}\right|+\left|z_{2}\right| \geq\left|z_{1}+z_{2}\right|$, and then use this to produce the geometric interpretation of the Triangle Inequality? Reversing our solution to part (a) above takes us from $\left|z_{1}\right|+\left|z_{2}\right| \geq\left|z_{1}+z_{2}\right|$ to the geometric interpretation of the Triangle Inequality, but proving that $\left|z_{1}\right|+\left|z_{2}\right| \geq\left|z_{1}+z_{2}\right|$ with only algebraic tools is a bit trickier! You'll have a chance to show how to do it as an Exercise.

Problem 8.21: Find the smallest possible value of $|z-5|+|z+4-3 i|$.

Solution for Problem 8.21: Solution 1: Algebra. Applying the Triangle Inequality gives
$$|z-5|+|z+4-3 i| \geq|(z-5)+(z+4-3 i)|=|2 z-1-3 i| .$$

This isn't much help, since we can't do much with $|2 z-1-3 i|$.
We'd like to use the Triangle Inequality in a way that eliminates $z$. We could do so if the $z$ term were negative in one of terms. We can make that happen! Since $|w|=|-w|$ for any $w$, we have
$$|z-5|+|z+4-3 i|=|z-5|+|-(z+4-3 i)|=|z-5|+|-z-4+3 i| \geq|(z-5)+(-z-4+3 i)|=|-9+3 i|=3 \sqrt{10} .$$

We still have to confirm that this value is possible. We do so by noting that when $z=5$, we have $|z-5|+|z+4-3 i|= 0+|9-3 i|=3 \sqrt{10}$.

The key step here was thinking about what we'd like to have happen:

Concept: A little wishful thinking can go a long way.

277

---

<!-- Page 278 -->

CHAPTER 8. GEOMETRY OF COMPLEX NUMBERS

Solution 2: Geometry. The expression $|z-5|$ is the distance from $z$ to 5 in the complex plane. The expression $|z+4-3 i|$ equals $z-(-4+3 i)$, which is the distance from $z$ to $-4+3 i$ in the complex plane. By the Triangle Inequality, the sum of the distances from $z$ to 5 and to $-4+3 i$ in the complex plane is at least the distance from 5 to $-4+3 i$. The distance between these two points is $|5-(-4+3 i)|=|9-3 i|=3 \sqrt{10}$. As before, we must show that this value is achievable. From the Triangle Inequality, we know that we achieve this value if $z$ is any point on the segment from 5 to $-4+3 i$. We can obviously take $z$ to be either endpoint, and we'll get $3 \sqrt{10}$ as the value of the given expression.

Our second solution reinforces an important strategy when working with complex numbers:
Concept: Some complex number problems that don't appear to be about geometry can be solved quickly by thinking about the problem geometrically.

Exercises
8.3.1 What is the radius of the circle that is the graph of the equation $z \bar{z}+(-2+i) z+(-2-i) \bar{z}=11$ ?
8.3.2 Show that if $P$ is a point on altitude $\overline{A X}$ of $\triangle A B C$, then $A C^{2}-C P^{2}=A B^{2}-B P^{2}$.
8.3.3
(a) Prove that $|x+y-z|+|x-y+z| \geq 2|x|$.
(b) Prove that $|x|+|y|+|z| \leq|x+y-z|+|x-y+z|+|-x+y+z|$.
8.3.4 Show that if $w$ is a complex number and $a$ and $b$ are nonzero real numbers such that $|w|=|w+a|=|w+b i|=1$, then $a^{2}+b^{2}=4$.
8.3.5 Show that the sum of the lengths of the diagonals of a quadrilateral is less than the perimeter of the quadrilateral.
8.3.6★ In the text, we used the geometric version of the Triangle Inequality to prove a version of the Triangle Inequality for complex numbers, $|w|+|z| \geq|w+z|$. Prove this inequality using only the algebraic properties of complex numbers, without using geometry. Hints: $93,288,87$
8.4 Regular Polygons

We've already seen that complex numbers can be related to regular polygons when we discovered that plotting the $n^{\text {th }}$ roots of unity on the complex plane gives us the vertices of a regular $n$-gon. In this section, we explore geometry problems involving regular polygons that can be tackled with complex numbers.

Problems
Problem 8.22: Suppose $w$ and $z$ are the endpoints of a diagonal of a square in the complex plane. Find the other two vertices of the square in terms of $w$ and $z$.

Problem 8.23: The points $(0,0),(a, 11)$, and ( $b, 37$ ) are the vertices of an equilateral triangle. Find $a b$. (Source:
AIME) Hints: 80
Problem 8.24: Let $A B C$ be a triangle in the complex plane whose vertices correspond to the complex numbers $a, b$, and $c$. Prove that $\triangle A B C$ is equilateral if and only if $a-b=\zeta(c-b)$, where $\zeta$ is a primitive sixth root of unity.

278

---

<!-- Page 279 -->

8.4. REGULAR POLYGONS

Problem 8.25: Suppose $\triangle P_{1} P_{2} P_{3}$ and $\triangle Q_{1} Q_{2} Q_{3}$ are equilateral triangles with the same orientation. (By same orientation, we mean that the vertices are labeled in the same order, either clockwise or counterclockwise, in each triangle.) Let $M_{1}, M_{2}$, and $M_{3}$ be the midpoints of $\overline{P_{1} Q_{1}}, \overline{P_{2} Q_{2}}$, and $\overline{P_{3} Q_{3}}$, respectively. Show that $\triangle M_{1} M_{2} M_{3}$ is an equilateral triangle.

Problem 8.26: Points $X$ and $Y$ are outside $\triangle A B C$ such that $\triangle X A B$ and $\triangle Y B C$ are equilateral and do not overlap $\triangle A B C$. Let $P$ be the midpoint of $\overline{X B}, Q$ be the midpoint of $\overline{Y B}$, and $R$ be the midpoint of $\overline{A C}$. Prove that $\triangle P Q R$ is equilateral.

Problem 8.27: Let $n \geq 3$ be a positive integer, and let $P_{0} P_{1} \cdots P_{n-1}$ be a regular $n$-gon inscribed in a circle with radius 1. Compute $P_{0} P_{1} \cdot P_{0} P_{2} \cdots P_{0} P_{n-1}$.

We'll start with a warm-up by considering a regular polygon that's particularly easy to work with: a square.
Problem 8.22: Suppose $w$ and $z$ are the endpoints of a diagonal of a square in the complex plane. Find the other two vertices of the square in terms of $w$ and $z$.

Solution for Problem 8.22: Let complex numbers $w$ and $z$ correspond to points $W$ and Z in the complex plane, and let $A$ and $B$ be the other vertices of the square, as shown at right. While it's not immediately obvious how to find $A$ and $B$ from $W$ and Z , if we could locate the center of the square, we could quickly find $A$ and $B$ by rotating $W$ and Z by $90^{\circ}$ about this center. But we know how to find the center-it's the midpoint of diagonal $\overline{W Z}$.

Letting this midpoint be $P$, with corresponding complex number $p$, we have $p=\frac{w+z}{2}$. Since
$A P=W P=B P=\mathrm{ZP}$ and $\overline{A B} \perp \overline{W Z}$, points $A$ and $B$ are $90^{\circ}$ rotations of $W$ and Z about $P$. The complex number corresponding to a $90^{\circ}$ counterclockwise rotation of Z about $P$ is
$$p+(z-p) e^{\pi i / 2}=\frac{w+z}{2}+\left(z-\frac{w+z}{2}\right) i=\left(\frac{1}{2}-\frac{i}{2}\right) w+\left(\frac{1}{2}+\frac{i}{2}\right) z,$$
and the complex number corresponding to a $90^{\circ}$ counterclockwise rotation of $W$ about $P$ is
$$p+(w-p) e^{\pi i / 2}=\frac{w+z}{2}+\left(w-\frac{w+z}{2}\right) i=\left(\frac{1}{2}+\frac{i}{2}\right) w+\left(\frac{1}{2}-\frac{i}{2}\right) z .$$

We can let either of these correspond to $A$, and the other corresponds to $B$.

Problem 8.23: The points $(0,0),(a, 11)$, and $(b, 37)$ are the vertices of an equilateral triangle. Find $a b$. (Source: AIME)

Solution for Problem 8.23: Let $O$ be the origin, $A$ be $(a, 11)$, and $B$ be $(b, 37)$. We could start out with the distance formula. Since $O A=A B=B O$, we have
$$\sqrt{a^{2}+11^{2}}=\sqrt{(a-b)^{2}+(11-37)^{2}}=\sqrt{b^{2}+37^{2}} .$$

Yuck. We can relate $a^{2}$ and $b^{2}$ with $\sqrt{a^{2}+11^{2}}=\sqrt{b^{2}+37^{2}}$, but the expression $\sqrt{(a-b)^{2}+(11-37)^{2}}$ stops us cold. Substituting for $a$ or $b$ looks pretty ugly.

Concept:

When your initial approach to a problem hits a seemingly unsurpassable obstacle, take a step back and look for another way to view the problem that allows you to avoid the obstacle.

279

---

<!-- Page 280 -->

CHAPTER 8. GEOMETRY OF COMPLEX NUMBERS

Using the lengths of the sides of the triangle didn't help, so let's consider the angles of the triangle. All three angles are 60 degrees, which might suggest the Law of Cosines. Unfortunately, that brings us back to the lengths of the sides, which gets us right back to the nasty expressions above.

Since the lengths of the sides are difficult to deal with in this problem, we'd like to find a useful fact about equilateral triangles that doesn't require that we use the actual lengths of the sides. Because $\triangle O A B$ is equilateral, point $B$ is the image of rotating $A$ by $\frac{\pi}{3}$ about the origin. Notice that we are not using the actual lengths of the sides here-we are only using the fact that the side lengths are the same. This is promising, so we investigate further. We have just learned a tool for investigating rotations about the origin-complex numbers.

To use complex numbers, we view the problem in the complex plane, so $A$ is now the location of $a+11 i$ in the complex plane, and $B$ corresponds to $b+37 i$. Because rotating $A$ by $\frac{\pi}{3}$ degrees about the origin gives us point $B$, we must have
$$(a+11 i) e^{\pi i / 3}=b+37 i \quad \text { or } \quad(a+11 i) e^{-\pi i / 3}=b+37 i .$$

We'll work through the details of the first case, $(a+11 i) e^{\pi i / 3}=b+37 i$. Expanding the left side gives
$$(a+11 i) e^{\pi i / 3}=(a+11 i)\left(\frac{1}{2}+\frac{\sqrt{3}}{2} i\right)=\frac{a}{2}-\frac{11 \sqrt{3}}{2}+\frac{11}{2} i+\frac{a \sqrt{3}}{2} i,$$
so we have
$$\frac{a}{2}-\frac{11 \sqrt{3}}{2}+\left(\frac{11}{2}+\frac{a \sqrt{3}}{2}\right) i=b+37 i .$$

Equating the real parts and equating the imaginary parts of both sides gives
$$\begin{array}{l}
\frac{a}{2}-\frac{11 \sqrt{3}}{2}=b \\
\frac{11}{2}+\frac{a \sqrt{3}}{2}=37
\end{array}$$

The second equation gives us $a=21 \sqrt{3}$, and substituting this into the first equation gives $b=5 \sqrt{3}$, so $a b=315$.
If we work through the details of the case $(a+11 i) e^{-\pi i / 3}=b+37 i$ in the same manner as above, we'll find $a=-21 \sqrt{3}$ and $b=-5 \sqrt{3}$, so $a b=315$ in this case, as well. This isn't a surprise: the equilateral triangle we produce in this case is the reflection over the imaginary axis of the one we found in the first case.

In this problem, we combined our understanding of exponential and rectangular forms of complex numbers to tackle an analytic geometry problem that didn't appear to have anything to do with complex numbers. One of the clues that complex numbers might be helpful in this problem is:

Concept:
Complex numbers can often be helpful in problems involving rotations, since rotations are easy to express with complex numbers.

Problem 8.24: Let $A B C$ be a triangle in the complex plane whose vertices correspond to the complex numbers $a, b$, and $c$. Prove that $\triangle A B C$ is equilateral if and only if $a-b=\zeta(c-b)$, where $\zeta$ is a primitive sixth root of unity.

Solution for Problem 8.24: The two primitive sixth roots of unity are $e^{\pi i / 3}$ and $e^{5 \pi i / 3}$, so we must show that $\triangle A B C$ is equilateral if and only if $a-b=e^{\pi i / 3}(c-b)$ or $a-b=e^{5 \pi i / 3}(c-b)$. These equations look exactly like equations we encountered when discussing rotations. The equation $a-b=e^{\pi i / 3}(c-b)$ tells us that $A$ is the image of $C$ upon a $\frac{\pi}{3}$ radian counterclockwise rotation about $B$. That is, we have $C B=B A$ and $\angle A B C=60^{\circ}$, from which we deduce that $\triangle A B C$ is equilateral. Similarly, the equation $a-b=e^{5 \pi i / 3}(c-b)$ means $A$ is the image of $C$ upon a $\frac{5 \pi}{3}$ radian

280

---

<!-- Page 281 -->

8.4. REGULAR POLYGONS

counterclockwise rotation about $B$. Such a rotation is the same as a $2 \pi-\frac{5 \pi}{3}=\frac{\pi}{3}$ rotation clockwise, from which we again conclude that $C B=B A$ and $\angle A B C=60^{\circ}$, so $\triangle A B C$ is equilateral.

Conversely, if $\triangle A B C$ is equilateral, then a $60^{\circ}$ rotation about $B$ maps $C$ to $A$, because $B C=B A$ and $\angle A B C=60^{\circ}$. If this rotation is counterclockwise, then we have $a-b=e^{\pi i / 3}(c-b)$, and if it is clockwise, then $a-b=e^{5 \pi i / 3}(c-b)$.

Combining the previous two paragraphs, we conclude that $\triangle A B C$ is equilateral if and only if $a-b=\zeta(c-b)$, where $\zeta$ is a primitive sixth root of unity.

Let's put our new tool for equilateral triangles to work.
Problem 8.25: Suppose $\triangle P_{1} P_{2} P_{3}$ and $\triangle Q_{1} Q_{2} Q_{3}$ are equilateral triangles with the same orientation. (By same orientation, we mean that the vertices are labeled in the same order, either clockwise or counterclockwise, in each triangle.) Let $M_{1}, M_{2}$, and $M_{3}$ be the midpoints of $\overline{P_{1} Q_{1}}, \overline{P_{2} Q_{2}}$, and $\overline{P_{3} Q_{3}}$, respectively. Show that $\triangle M_{1} M_{2} M_{3}$ is an equilateral triangle.

Solution for Problem 8.25: It's not clear where to start using the tools of Euclidean geometry, but with complex numbers, we don't even need a diagram to solve the problem quickly. We have a corresponding complex number $p_{i}, q_{i}$, or $m_{i}$ for each of the vertices of the the three triangles, so that $m_{i}=\left(p_{i}+q_{i}\right) / 2$ for $i=1,2,3$, because $M_{i}$ is the midpoint of $\overline{P_{i} Q_{i}}$.

Since $\triangle P_{1} P_{2} P_{3}$ is equilateral, we have
$$p_{2}-p_{1}=\zeta\left(p_{3}-p_{1}\right)$$
for some primitive sixth root of unity $\zeta$. Similarly, equilateral $\triangle Q_{1} Q_{2} Q_{3}$ gives us
$$q_{2}-q_{1}=\zeta\left(q_{3}-q_{1}\right) .$$

We know that the primitive sixth roots of unity in these two equations are the same because the triangles have the same orientation. If we didn't know that the two triangles have the same orientation, we couldn't take the next step, which is to add the two equations to produce expressions of the form $p_{i}+q_{i}$ :
$$\left(p_{2}+q_{2}\right)-\left(p_{1}+q_{1}\right)=\zeta\left(\left(p_{3}+q_{3}\right)-\left(p_{1}+q_{1}\right)\right) .$$

Since $p_{i}+q_{i}=2 m_{i}$ for $i=1,2,3$, we can write the equation above as $2 m_{2}-2 m_{1}=\zeta\left(2 m_{3}-2 m_{1}\right)$. Dividing by 2 gives us $m_{2}-m_{1}=\zeta\left(m_{3}-m_{1}\right)$, so $\Delta M_{1} M_{2} M_{3}$ is equilateral.

Problem 8.26: Points $X$ and $Y$ are outside $\triangle A B C$ such that $\triangle X A B$ and $\triangle Y B C$ are equilateral and do not overlap $\triangle A B C$. Let $P$ be the midpoint of $\overline{X B}, Q$ be the midpoint of $\overline{Y B}$, and $R$ be the midpoint of $\overline{A C}$. Prove that $\triangle P Q R$ is equilateral.

Solution for Problem 8.26: We know how to handle equilateral triangles and midpoints with complex numbers. As usual, we use the corresponding lowercase letter to represent the complex number that corresponds to each point. We'll present two solutions.

Solution 1: Work forwards. Our goal in this approach is to express $p, q$, and $r$ in terms of $a, b$, and $c$, and then use these expressions to show that $\triangle P Q R$ is equilateral. Since $P$ and $Q$ are the midpoints of $\overline{X B}$ and $\overline{Y B}$, we'll have to find $x$ and $y$ in terms of $a, b$, and $c$ first. We do so with equilateral triangles $X A B$ and $Y B C$. We focus on rotation about point $B$, the vertex the two triangles have in common. What's wrong with this start:

281

---

<!-- Page 282 -->

CHAPTER 8. GEOMETRY OF COMPLEX NUMBERS

Bogus Solution: We have $x-b=\zeta(a-b)$ and $y-b=\zeta(c-b)$, where $\zeta$ is a primitive sixth root
of unity. If we subtract the second equation from the first, we eliminate $b$.

We see the problem with this start when we look at the diagram at right. The equation $x-b=\zeta(a-b)$ comes from the fact that $X$ is the image of $A$ upon a $60^{\circ}$ rotation counterclockwise about $B$, but the equation $y-b=\zeta(c-b)$ comes from the fact that $Y$ is the image of $C$ upon a $60^{\circ}$ rotation clockwise about $B$. The orientations of these two rotations are different, so we cannot use the same value of $\zeta$ for each rotation. We therefore cannot simply subtract the second equation from the first to eliminate $b$.

WARNING!!
The orientations of rotations matter in complex numbers, just as they matter in geometry.

To fix this problem, we write equations using rotations of the same orientation, as marked in the diagram, so that we can use the same primitive sixth root of unity:
$$\begin{array}{l}
a-b=\zeta(x-b) \\
y-b=\zeta(c-b)
\end{array}$$
where $\zeta$ is a primitive sixth root of unity. Note that we cannot be sure which primitive
sixth root of unity $\zeta$ is. In the diagram above, we would have $\zeta=e^{\pi i / 3}$, but if the vertices of $\triangle A B C$ were labeled in the opposite order, we'd have $\zeta=e^{5 \pi i / 3}$. By simply writing $\zeta$, we cover both cases, as long as we use the same orientation of rotation about $B$ to produce the equations above.

Before continuing with finding $p, q$, and $r$, we see that we can simplify our equations for $x$ and $y$ a great deal by letting $b$ be the origin, which gives $a=\zeta x$ and $y=\zeta c$. We therefore have
$$\begin{array}{l}
x=\frac{a}{\zeta^{\prime}} \\
y=\zeta c .
\end{array}$$

Point $B$ is also a natural choice for the origin because $B$ is part of the definitions of both $P$ and $Q$.
Concept: Strategically choosing the origin when applying complex numbers to geometry
can greatly simplify the algebra you'll have to deal with.

Next, we find $p, q$, and $r$ from the fact that $P, Q$, and $R$ are the midpoints of $\overline{X B}, \overline{Y B}$, and $\overline{A C}$ :
$$\begin{array}{l}
p=\frac{x+b}{2}=\frac{x}{2}, \\
q=\frac{y+b}{2}=\frac{y}{2}, \\
r=\frac{a+c}{2} .
\end{array}$$

We have $x=\frac{a}{\zeta}$ from line (8.5) and $y=\zeta c$ from line (8.6), so we can write $p$ and $q$ in terms of $a$ and $c$ :
$$\begin{aligned}
p & =\frac{a}{2 \zeta^{\prime}} \\
q & =\frac{\zeta c}{2} .
\end{aligned}$$

282

---

<!-- Page 283 -->

8.4. REGULAR POLYGONS

We have a bit of a puzzle when we turn to $\triangle P Q R$. We can test whether $P Q R$ is equilateral by testing rotation about any of the three vertices. Suppose we choose point $R$. Which should we try to confirm to check if $\triangle P Q R$ is equilateral, $p-r=\zeta(q-r)$ or $q-r=\zeta(p-r)$ ? We choose $p-r=\zeta(q-r)$ because the orientation of $60^{\circ}$ rotation about $R$ that would map $Q$ to $P$ is the same as the orientation of the $60^{\circ}$ rotation about $B$ that maps $X$ to $A$. This latter rotation is the one that gave us $\zeta$, and we want to be able to use the same primitive sixth root of unity to avoid confusion and
simplify the algebra. We have:
$$\begin{aligned}
p-r & =\frac{a}{2 \zeta}-\frac{a+c}{2}=\frac{(1-\zeta)}{2 \zeta} a-\frac{1}{2} c, \\
\zeta(q-r) & =\zeta\left(\frac{\zeta c}{2}-\frac{a+c}{2}\right)=-\frac{\zeta}{2} a+\frac{\zeta^{2}-\zeta}{2} c .
\end{aligned}$$

Our expressions for $p-r$ and $\zeta(q-r)$ don't appear to be the same. We can only be sure they're the same if the coefficients for $a$ match and the coefficients for $c$ match. In other words, we must check if
$$\begin{aligned}
\frac{1-\zeta}{2 \zeta} & =-\frac{\zeta}{2} & & (\text { equating the coefficients of } a) \\
-\frac{1}{2} & =\frac{\zeta^{2}-\zeta}{2} & & (\text { equating the coefficients of } c)
\end{aligned}$$

These both simplify to the same equation: $\zeta^{2}-\zeta+1=0$. So, if we can show that $\zeta^{2}-\zeta+1=0$ for both primitive sixth roots of unity $\zeta$, then we can conclude that our expressions for $p-r$ and $\zeta(q-r)$ are the same. We could test that this equation is true for both primitive sixth roots $\zeta$, but there's a slicker way to confirm that $\zeta^{2}-\zeta+1=0$. First, we note that $\zeta$ is a sixth root of unity, so it is a solution to $z^{6}-1=0$. Factoring the left side as a difference of squares gives
$$\left(z^{3}-1\right)\left(z^{3}+1\right)=0 .$$

The roots of $z^{3}-1$ are cube roots of unity, so they cannot be primitive sixth roots. Therefore, $\zeta$ is a root of $z^{3}+1$. Factoring this as a sum of cubes gives $(z+1)\left(z^{2}-z+1\right)$. Since -1 is a primitive square root of unity rather than a primitive sixth root of unity, we know that $\zeta$ is not a root of $z+1$. So, we know that the two primitive sixth roots of unity are roots of $z^{2}-z+1=0$. This means we have $\zeta^{2}-\zeta+1=0$, as desired. Therefore, we have $1-\zeta=-\zeta^{2}$ and $\zeta^{2}-\zeta=-1$, and we can write our expressions for $p-r$ and $\zeta(q-r)$ as follows:
$$\begin{aligned}
p-r & =\frac{(1-\zeta)}{2 \zeta} a-\frac{1}{2} c=\frac{-\zeta^{2}}{2 \zeta} a-\frac{1}{2} c=-\frac{\zeta}{2} a-\frac{1}{2} c \\
\zeta(q-r) & =-\frac{\zeta}{2} a+\frac{\zeta^{2}-\zeta}{2} c=-\frac{\zeta}{2} a-\frac{1}{2} c
\end{aligned}$$

Therefore, we have $p-r=\zeta(q-r)$, as desired.
One key step in this solution was noticing that two very different-looking expressions involving $\zeta$ are equivalent.

\begin{tabular}{|cl|}
\hline Concept: & When working with roots of unity, we will occasionally encounter two very \\
different-looking expressions that we can show are equivalent.
\end{tabular}

Looking back, there wasn't any reason to know immediately that $\frac{1-\zeta}{2 \zeta}=-\frac{\zeta}{2}$, but once we discovered that we needed this to be true to solve the problem, we focused on it and were able to prove it. What if we had taken this strategy for the whole problem-what if we focused first on what we wanted to be true?

283

---

<!-- Page 284 -->

CHAPTER 8. GEOMETRY OF COMPLEX NUMBERS

Solution 2: Work backwards. In this solution, we start with expressions for $p, q$, and $r$ in terms of $x, y, a, b$, and $c$, and work backwards from an equation that implies that $\triangle P Q R$ is equilateral. Our goal is to find an equivalent equation that we can prove is true.

As in the first solution we find expressions for $p, q$, and $r$ using the fact that $P, Q$, and $R$ are the midpoints of $\overline{X B}, \overline{Y B}$, and $\overline{A C}$ :
$$\begin{array}{l}
p=\frac{x+b}{2} \\
q=\frac{y+b}{2} \\
r=\frac{a+c}{2}
\end{array}$$

There are a variety of equations we can write in terms of $p, q$, and $r$ that are true if and only if $\triangle P Q R$ is equilateral. We choose one involving $p-q$ since this will eliminate $b$ when we substitute the expressions above. Specifically, if we can show that $p-q=\zeta(r-q)$, where $\zeta$ is a primitive sixth root of unity, then we can deduce that $\triangle P Q R$ is equilateral. Substituting our expressions for $p, q$, and $r$, we wish to show that
$$\frac{x-y}{2}=\zeta\left(\frac{a+c-y-b}{2}\right) .$$

We turn to equilateral triangles $\triangle X A B$ and $\triangle Y B C$ in order to produce equations involving $x, y, a, b$, and $c$. In writing equations including $\zeta$, we must make sure to use the same orientation of rotation that we used when writing $p-q=\zeta(r-q)$.

There are three different equations we could write for each triangle, one for rotation about each vertex. Rather than write them all down, we use our target Equation (8.7) as a guide. Since $\overline{A B}$ is a side of $\triangle X A B$ and $\overline{Y C}$ is a side of $\triangle Y B C$, we can write the right side of Equation (8.7) in terms of complex numbers corresponding to sides of these two triangles:
$$\frac{x-y}{2}=\zeta\left(\frac{(a-b)+(c-y)}{2}\right) .$$

The $a-b$ tells us to focus on the rotation about $B$ in $\triangle X A B$ and the $c-y$ tells us to focus on the rotation about $Y$ in $\triangle Y B C$. These rotations (taking the same orientation we use to write $p-q=\zeta(r-q)$ ) give us
$$\begin{array}{l}
x-b=\zeta(a-b) \\
b-y=\zeta(c-y)
\end{array}$$

Aha! If we simply add these two equations, we get
$$x-y=\zeta(a+c-y-b)$$

Dividing this equation by 2 gives us Equation (8.7), which we have shown is equivalent to $p-q=\zeta(r-q)$. Therefore, we can deduce that $\triangle P Q R$ is equilateral.

Our second solution is much simpler than the first. If we had been lucky in choosing the right equations for $\triangle X A B$ and $\triangle Y B C$ in the first solution, we might have stumbled on the simpler approach we found in the second solution. The key to our second solution was working backwards to give us clues how to approach the problem in a way that would provide the desired result quickly.

Concept: Working backwards from the desired result is a powerful problem solving strat- egy.

284

---

<!-- Page 285 -->

8.4. REGULAR POLYGONS

Equilateral triangles and squares are not the only regular polygons for which complex numbers can be helpful.
Problem 8.27: Let $n \geq 3$ be a positive integer, and let $P_{0} P_{1} \cdots P_{n-1}$ be a regular $n$-gon inscribed in a circle with radius 1. Compute $P_{0} P_{1} \cdot P_{0} P_{2} \cdots P_{0} P_{n-1}$.

Solution for Problem 8.27: If "circle with radius 1" isn't enough of a hint to try complex numbers, "regular $n$-gon" sure is, because we have an easy way to represent a regular $n$-gon on the complex plane-with the $n^{\text {th }}$ roots of unity. We let $p_{0}, p_{1}, \ldots, p_{n-1}$ be the $n^{\text {th }}$ roots of unity, and let $P_{k}$ correspond to $p_{k}$ for each root. Moreover, we let $p_{k}=e^{2 \pi i k / n}$ for each $k$, which makes $p_{0}=1$. This is particularly convenient because we can now express each length $P_{0} P_{k}$ as $\left|p_{0}-p_{k}\right|=\left|1-e^{2 \pi i k / n}\right|$. Therefore, the desired product is
$$\left|1-e^{1 \cdot 2 \pi i / n}\right| \cdot\left|1-e^{2 \cdot 2 \pi i / n}\right| \cdot\left|1-e^{3 \cdot 2 \pi i / n}\right| \cdots\left|1-e^{(n-1) \cdot 2 \pi i / n}\right| .$$

If we don't recognize what to do right away, we can experiment.

Concept: When a problem is given in terms of an integer $n$, experimenting with small values of $n$ can give clues to the solution.

When $n=2$, the product is simply $|1-(-1)|=2$. When $n=3$, we have $|1-\omega| \cdot\left|1-\omega^{2}\right|$, where $\omega=e^{2 \pi i / 3}$. Computing this product gives
$$|1-\omega| \cdot\left|1-\omega^{2}\right|=\left|(1-\omega)\left(1-\omega^{2}\right)\right|=\left|1-\omega^{2}-\omega+\omega^{3}\right| .$$

We can simplify this expression by noting that because $\omega$ is a primitive cube root of unity, we have $\omega^{3}-1=0$. Therefore, not only do we have $\omega^{3}=1$, but factoring gives us $(\omega-1)\left(\omega^{2}+\omega+1\right)=0$. Since $\omega \neq 1$, we have $\omega^{2}+\omega+1=0$, so $\omega^{2}+\omega=-1$. Therefore, we have
$$\left|1-\omega^{2}-\omega+\omega^{3}\right|=\left|1-\left(\omega^{2}+\omega\right)+1\right|=3 .$$
Important: If $\omega$ is a primitive cube root of unity, then $\omega^{2}+\omega+1=0$.
D

So, when $n=2$, the product is 2 , and when $n=3$, the product is 3 . We now have a guess for what we'll get when $n=4$. Let's check:
$$|1-i| \cdot|1-(-1)| \cdot|1-(-i)|=2|(1-i)(1+i)|=4$$

We now have a pretty strong suspicion that the product equals $n$ for any positive integer $n$, but it's still not so clear how to prove it. Let's take another look at the product, and think about where else we have seen similar products:
$$\left|1-e^{1 \cdot 2 \pi i / n}\right| \cdot\left|1-e^{2 \cdot 2 \pi i / n}\right| \cdot\left|1-e^{3 \cdot 2 \pi i / n}\right| \cdots\left|1-e^{(n-1) \cdot 2 \pi i / n}\right| .$$

Each term is the difference of 1 and an $n^{\text {th }}$ root of unity. We have seen a product of differences involving the $n^{\text {th }}$ roots of unity before, in the factorization of the polynomial $z^{n}-1$. If $f(z)=z^{n}-1$, then we can write $f(z)$ as
$$f(z)=(z-1)\left(z-e^{1 \cdot 2 \pi i / n}\right)\left(z-e^{2 \cdot 2 \pi i / n}\right)\left(z-e^{3 \cdot 2 \pi i / n}\right) \cdots\left(z-e^{(n-1) \cdot 2 \pi i / n}\right)$$

Except for the first term, $z-1$, this looks almost exactly like our desired product. Fortunately, we can also factor

285

---

<!-- Page 286 -->

CHAPTER 8. GEOMETRY OF COMPLEX NUMBERS

$f(z)$ as $(z-1)\left(z^{n-1}+z^{n-2}+z^{n-3}+\cdots+1\right)$, which allows us to divide by $z-1$ to get
$$\begin{aligned}
\left(z-e^{1 \cdot 2 \pi i / n}\right)\left(z-e^{2 \cdot 2 \pi i / n}\right)\left(z-e^{3 \cdot 2 \pi i / n}\right) \cdots\left(z-e^{(n-1) \cdot 2 \pi i / n}\right) & =\frac{f(z)}{z-1} \\
& =\frac{(z-1)\left(z^{n-1}+z^{n-2}+z^{n-3}+\cdots+1\right)}{z-1} \\
& =z^{n-1}+z^{n-2}+z^{n-3}+\cdots+1
\end{aligned}$$

We also could have jumped straight to
$$\left(z-e^{1 \cdot 2 \pi i / n}\right) \cdot\left(z-e^{2 \cdot 2 \pi i / n}\right)\left(z-e^{3 \cdot 2 \pi i / n}\right) \cdots \cdots\left(z-e^{(n-1) \cdot 2 \pi i / n}\right)=z^{n-1}+z^{n-2}+z^{n-3}+\cdots+1$$
by noting that the roots of the polynomial on the right are all the $n^{\text {th }}$ roots of unity except 1 . Speaking of 1 , we let $z=1$ in this equation to find that
$$\begin{aligned}
\left|1-e^{1 \cdot 2 \pi i / n}\right| \cdot\left|1-e^{2 \cdot 2 \pi i / n}\right| \cdots \cdot\left|1-e^{(n-1) \cdot 2 \pi i / n}\right| & =\left|\left(1-e^{1 \cdot 2 \pi i / n}\right) \cdot\left(1-e^{2 \cdot 2 \pi i / n}\right) \cdots \cdots\left(1-e^{(n-1) \cdot 2 \pi i / n}\right)\right| \\
& =\left|1^{n-1}+1^{n-2}+1^{n-3}+\cdots+1^{1}+1\right| \\
& =n,
\end{aligned}$$
as expected.

Exercises
8.4.1 Suppose $P Q R S$ is a square in the complex plane, and that $p$ and $q$ correspond to $P$ and $Q$, respectively. Find the two possible complex numbers that correspond to $R$ in terms of $p$ and $q$.
8.4.2 Let $O$ be the center of a circle $\omega$. Points $A, B, C, D, E, F$ on $\omega$ are chosen such that the triangles $O A B, O C D$, $O E F$ are equilateral and have the same orientation. Let $L, M, N$ be the midpoints of $\overline{B C}, \overline{D E}, \overline{F A}$, respectively. Prove that triangle $L M N$ is equilateral.
8.4.3 Let $A B C D$ be a parallelogram. Suppose we construct equilateral triangles $A B G$ and $B C F$ externally on sides $\overline{A B}$ and $\overline{B C}$, respectively. Show that triangle $D F G$ is equilateral.
8.4.4 Prove that each of the following are necessary and sufficient conditions for the triangle formed by plotting complex numbers $a, b$, and $c$ in the complex plane to be an equilateral triangle. (That is, show that if $a, b, c$ satisfy the condition, then the triangle is equilateral, and show that if the triangle is equilateral, then $a, b$, and $c$ satisfy the given condition.)
(a) $a-b=\omega(b-c)$, where $\omega$ is a primitive cube root of unity. Hints: 281
(b) $a+\omega b+\omega^{2} c=0$, where $\omega$ is a primitive cube root of unity. Hints: 14
8.4.5★ Inside square $A B C D$, we construct equilateral triangles $A B K, B C L, C D M$, and $D A N$. Prove that the 12 points which are the midpoints of $\overline{K L}, \overline{L M}, \overline{M N}, \overline{N K}, \overline{A K}, \overline{B K}, \overline{B L}, \overline{C L}, \overline{C M}, \overline{D M}, \overline{D N}$, amd $\overline{A N}$ form the vertices of a regular dodecagon.
8.5★ Classic Theorems

In this section, we exhibit the power of complex numbers by proving four classic geometry theorems. Some of these proofs are quite difficult, so don't feel bad if you can't find them on your own. But, do work through and enjoy them!

286

---

<!-- Page 287 -->

8.5★. CLASSIC THEOREMS

Problems

Problem 8.28: Ptolemy's Inequality: Prove that for any four points $A, B, C, D$ in a plane, we have
$$(A B)(C D)+(B C)(A D) \geq(A C)(B D) .$$

Hints: 56

Problem 8.29: Outer Napoleon Triangle: Starting with $\triangle P Q R$, we construct equilateral triangles $\triangle A P Q, \triangle B Q R$, and $\triangle C R P$ such that these triangles do not overlap $\triangle P Q R$. Prove that the triangle formed by connecting the centers of these three equilateral triangles is itself equilateral. Hints: 243

Problem 8.30: Monge's Theorem: Three circles are drawn in a plane with different radii such that no circle is inside another. The common external tangents to each pair of circles are drawn, as shown. The intersections of pairs of common external tangents are labeled $Z_{1}, Z_{2}$, and $Z_{3}$, as shown. Show that $Z_{1}, Z_{2}$, and $Z_{3}$ are collinear. Hints: 218, 284

Problem 8.31: Simson Line: Let Z be a point on the circumcircle of $\triangle A B C$ besides $A, B$, and $C$. Show that the feet of the perpendiculars from $Z$ to the lines containing the sides of $\triangle A B C$ are collinear. Hints: 120, 61

We used a geometric explanation of the Triangle Inequality to develop an inequality relating complex numbers. Let's try turning the tables, and use complex numbers to develop a geometric inequality.

Problem 8.28: Ptolemy's Inequality: Show that for any four points $A, B, C, D$ in a plane, we have
$$(A B)(C D)+(B C)(A D) \geq(A C)(B D)$$

Solution for Problem 8.28: We let complex numbers $a, b, c, d$ correspond to $A, B, C, D$, respectively, so that
$$(A B)(C D)+(B C)(A D)=|b-a| \cdot|d-c|+|c-b| \cdot|d-a| .$$

We have to prove an inequality, and the Triangle Inequality gives us a tool to produce inequalities regarding magnitudes of complex numbers. To apply $|w|+|z| \geq|w+z|$, we write
$$|b-a| \cdot|d-c|+|c-b| \cdot|d-a|=|(b-a)(d-c)|+|(c-b)(d-a)| .$$

287

---

<!-- Page 288 -->

CHAPTER 8. GEOMETRY OF COMPLEX NUMBERS

Applying the Triangle Inequality gives
$$|(b-a)(d-c)|+|(c-b)(d-a)| \geq|(b-a)(d-c)+(c-b)(d-a)| .$$
(Note that our expression for $(A B)(C D)+(B C)(A D)$ is on the larger side of this inequality, which gives us some confidence that we're moving in the correct direction.) We can see that some of the terms in the expression on the lesser side will cancel when we expand, so we give that a try:
$$\begin{aligned}
|(b-a)(d-c)+(c-b)(d-a)| & =|b d-b c-a d+a c+c d-a c-b d+a b| \\
& =|a b+c d-b c-a d|
\end{aligned}$$

If we can't see that this expression factors, then we can always get a hint from the desired inequality. We want to show that $(A B)(C D)+(B C)(A D)$ is at least $(A C)(B D)$, which equals $|(c-a)(d-b)|$. Expanding this gives us exactly the expression above, $|a b+c d-b c-a d|$, and now we have our proof:
$$\begin{aligned}
(A B)(C D)+(B C)(A D) & =|b-a| \cdot|d-c|+|c-b| \cdot|d-a| \\
& =|(b-a)(d-c)|+|(c-b)(d-a)| \\
& \geq|(b-a)(d-c)+(c-b)(d-a)| \\
& =|a b+c d-b c-a d| \\
& =|(c-a)(d-b)| \\
& =(A C)(B D) .
\end{aligned}$$

As an extra challenge, see if you can discover the conditions under which equality holds in Ptolemy's Inequality.
Problem 8.29: Outer Napoleon Triangle: Starting with $\triangle P Q R$, we construct triangles equilateral triangles $\triangle A P Q, \triangle B Q R$, and $\triangle C R P$ such that these triangles do not overlap $\triangle P Q R$. Prove that the triangle formed by connecting the centers of these three equilateral triangles is equilateral.

Solution for Problem 8.29: As usual, we let the lowercase version of each point be the complex number corresponding to that point. We start by finding expressions for $a, b$, and $c$ in terms of $p, q$, and $r$. From equilateral triangle $A P Q$, we have $a-q=\zeta(p-q)$, where $\zeta$ is a primitive sixth root of unity. Therefore, we have $a=\zeta(p-q)+q$. Similarly, from triangles $B Q R$ and $C R P$, we have $b=\zeta(q-r)+r$ and $c=\zeta(r-p)+p$.

Note that we are careful to use the same orientation for each rotation so that we can use the same primitive sixth root. For example, in $\triangle A P Q$, we get $a-q=\zeta(p-q)$ from considering the $\frac{\pi}{3}$ counterclockwise rotation of $P$ about $Q$ in the diagram at right, and we likewise consider counterclockwise rotations to produce our expressions for $b$ and $c$.

The medians of an equilateral triangle intersect at the center of the triangle. As you should have showed in Exercise 8.2.5, the centroid of a triangle in the complex
plane is the average of the vertices of the triangle. So, if we let $Z_{1}, Z_{2}$, and $Z_{3}$ be the centers of triangles $A P Q, B Q R$, and $C R P$, respectively, we have
$$\begin{array}{l}
z_{1}=\frac{a+p+q}{3}=\frac{\zeta(p-q)+q+p+q}{3}=\frac{(1+\zeta) p+(2-\zeta) q}{3}, \\
z_{2}=\frac{b+q+r}{3}=\frac{\zeta(q-r)+r+q+r}{3}=\frac{(1+\zeta) q+(2-\zeta) r}{3}, \\
z_{3}=\frac{c+r+p}{3}=\frac{\zeta(r-p)+p+r+p}{3}=\frac{(1+\zeta) r+(2-\zeta) p}{3} .
\end{array}$$

288

---

<!-- Page 289 -->

8.5 ★. CLASSIC THEOREMS

We can prove that triangle $Z_{1} Z_{2} Z_{3}$ is equilateral by showing that $\left(z_{3}-z_{1}\right)=\zeta\left(z_{2}-z_{1}\right)$. (Note that we are careful again to use the same orientation of rotation as with the earlier equilateral triangles.) Substituting, we find that
$$z_{3}-z_{1}=\frac{(1+\zeta) r+(2-\zeta) p}{3}-\frac{(1+\zeta) p+(2-\zeta) q}{3}=\frac{(1-2 \zeta) p+(-2+\zeta) q+(1+\zeta) r}{3},$$
and
$$z_{2}-z_{1}=\frac{(1+\zeta) q+(2-\zeta) r}{3}-\frac{(1+\zeta) p+(2-\zeta) q}{3}=\frac{(-1-\zeta) p+(-1+2 \zeta) q+(2-\zeta) r}{3},$$
so
$$\zeta\left(z_{2}-z_{1}\right)=\frac{\left(-\zeta-\zeta^{2}\right) p+\left(-\zeta+2 \zeta^{2}\right) q+\left(2 \zeta-\zeta^{2}\right) r}{3} .$$

Uh-oh; our expression for $\zeta\left(z_{2}-z_{1}\right)$ doesn't seem to match our expression for $z_{3}-z_{1}$. However, we do have $\zeta^{2}$ in the expression for $\zeta\left(z_{2}-z_{1}\right)$, and back on page 283 we saw a convenient manipulation for primitive sixth roots of unity. Specifically, if $\zeta$ is a primitive sixth root of unity, then $\zeta^{2}-\zeta+1=0$, so $\zeta^{2}=\zeta-1$. Making this substitution in our expression for $\zeta\left(z_{2}-z_{1}\right)$ gives
$$\zeta\left(z_{2}-z_{1}\right)=\frac{(-\zeta-(\zeta-1)) p+(-\zeta+2(\zeta-1)) q+(2 \zeta-(\zeta-1)) r}{3}=\frac{(1-2 \zeta) p+(-2+\zeta) q+(1+\zeta) r}{3},$$
which does indeed match our expression for $z_{3}-z_{1}$. Since $z_{3}-z_{1}=\zeta\left(z_{2}-z_{1}\right)$, we know that $Z_{1} Z_{2} Z_{3}$ is equilateral.

Sidenote: The "Outer Napoleon Triangle" is equilateral; is the "inner" one also equilateral? If you construct equilateral triangles $\triangle A P Q, \triangle B Q R$, and $\triangle C R P$ so that they overlap $\triangle P Q R$, is the triangle formed by connecting the centers of these three equilateral triangles also equilateral?

Problem 8.30: Monge's Theorem: Three circles are drawn in a plane with different radii such that no circle is inside another. The common external tangents to each pair of circles are drawn, as shown. The intersections of pairs of common external tangents are labeled $Z_{1}, Z_{2}$, and $Z_{3}$, as shown. Show that $Z_{1}, Z_{2}$, and $Z_{3}$ are collinear.

Solution for Problem 8.30: The only clue that we might be able to solve this problem with complex numbers is that we wish to prove three points collinear. We have a pretty straightforward condition for collinearity in the complex plane. Letting $z_{1}, z_{2}$, and $z_{3}$ be complex numbers corresponding to points $Z_{1}, Z_{2}$, and $Z_{3}$, the points are collinear if and only if
$$\left(z_{1}-z_{2}\right)\left(\overline{z_{3}}-\overline{z_{2}}\right)-\left(\overline{z_{1}}-\overline{z_{2}}\right)\left(z_{3}-z_{2}\right)=0 .$$

Extra! There's a wonderful proof of Monge's Theorem that involves thinking of the problem as a crosssection of a three-dimensional configuration. As a hint, consider the centers of the three circles as the centers of three spheres whose radii equal the radii of the corresponding circles.

Solution on page 297.

289

---

<!-- Page 290 -->

CHAPTER 8. GEOMETRY OF COMPLEX NUMBERS

Now our goal is to find $z_{1}, z_{2}$, and $z_{3}$ in terms of the radii and the complex numbers corresponding to the centers of the circles. We let $P, \mathrm{Q}$, and $R$ be the centers of the circles, and we'll refer to the circles as $\odot P, \odot Q$, and $\odot R$. Let $\odot P, \odot Q$, and $\odot R$ have radii $a, b$, and $c$, respectively, with $a>b>c$. The two common external tangents to $\odot P$ and $\odot Q$ meet at $Z_{3}$, the two common external tangents to $\odot Q$ and $\odot R$ meet at $\mathrm{Z}_{2}$, and the two common external tangents to $\odot P$ and $\odot R$ meet at $Z_{1}$.

We start with $Z_{3}$. $P$ and $Q$ are equidistant from the common external tangents to $\odot P$ and $\odot Q$, so they are on the angle bisector of the angle formed by these tangents, which means $P, Q$, and $Z_{3}$ are collinear, as shown. We draw radii $\overline{P X}$ and $\overline{Q Y}$ to the common tangent, thereby forming similar right triangles $P X Z_{3}$ and $Q Y Z_{3}$.

Since $P, Q$, and $Z_{3}$ are collinear, we know that $\left(z_{3}-p\right) /(q-p)$ is real and equals the ratio of magnitudes of $z_{3}-p$ and $q-p$. That is, we have
$$\frac{z_{3}-p}{q-p}=\frac{P Z_{3}}{P Q} .$$

We can use similar triangles $P X Z_{3}$ and $Q Y Z_{3}$ to express $P Z_{3} / P Q$ in terms of the radii of the circles. Specifically, we have $Q Z_{3} / P Z_{3}=b / a$, so $P Q / P Z_{3}=\left(P Z_{3}-Q Z_{3}\right) / P Z_{3}=1-(b / a)=(a-b) / a$, which means
$$\frac{z_{3}-p}{q-p}=\frac{P Z_{3}}{P Q}=\frac{a}{a-b} .$$

Therefore, we have
$$z_{3}=p+\frac{a}{a-b}(q-p)=\frac{a p-b p}{a-b}+\frac{a q-a p}{a-b}=\frac{a q-b p}{a-b} .$$

Similarly, we have
$$\begin{array}{l}
z_{2}=\frac{b r-c q}{b-c}, \\
z_{1}=\frac{a r-c p}{a-c} .
\end{array}$$

We have to compute the expression
$$\left(z_{1}-z_{2}\right)\left(\overline{z_{3}}-\overline{z_{2}}\right)-\left(\overline{z_{1}}-\overline{z_{2}}\right)\left(z_{3}-z_{2}\right),$$
since we wish to show that it equals 0 . This looks pretty scary, until we realize that we haven't chosen our origin yet. If we choose $z_{2}$ to be the origin, then this expression becomes a much more manageable
$$z_{1} \overline{z_{3}}-\overline{z_{1}} z_{3} .$$

Moreover, by letting $z_{2}$ be the origin, the expression above for $z_{2}$ must be 0 , so
$$\frac{b r-c q}{b-c}=0,$$

290

---

<!-- Page 291 -->

8.5★. CLASSIC THEOREMS

which gives us $r=\frac{c q}{b}$, thereby allowing us to eliminate $r$ from our expressions for $z_{1}$ and $z_{3}$ :
$$\begin{array}{l}
z_{1}=\frac{a r-c p}{a-c}=\frac{\frac{a c q}{b}-c p}{a-c}=\frac{a c q-b c p}{b(a-c)}=\frac{c}{b(a-c)}(a q-b p), \\
z_{3}=\frac{a q-b p}{a-b}=\frac{1}{a-b}(a q-b p) .
\end{array}$$

Concept: Don't always specify the origin right away-sometimes waiting will allow you to exploit symmetry in a problem or will reveal a surprisingly useful choice for the origin.

This particularly useful choice for the origin pretty much finishes off the problem. We now see that we don't even have to compute $z_{1} \overline{z_{3}}-\overline{z_{1}} z_{3}$. We have
$$\frac{z_{1}}{z_{3}}=\frac{\frac{c}{b(a-c)}(a q-b p)}{\frac{1}{a-b}(a q-b p)}=\frac{c(a-b)}{b(a-c)^{\prime}}$$
which is real because $a, b$, and $c$ are real. Since $z_{1} / z_{3}$ is a real number, the origin, $Z_{1}$, and $Z_{3}$ are collinear. But $Z_{2}$ is the origin, so we have shown that $Z_{1}, Z_{2}$, and $Z_{3}$ are collinear! (Moreover, we have also proved a relationship among $\mathrm{Z}_{1} \mathrm{Z}_{2} / \mathrm{Z}_{3} \mathrm{Z}_{2}$ and the radii of the circles.)

Problem 8.31: Simson Line: Let $Z$ be a point on the circumcircle of $\triangle A B C$ besides $A, B$, and $C$. Show that the feet of the perpendiculars from Z to the lines containing the sides of $\triangle A B C$ are collinear.

Solution for Problem 8.31: Let the feet of the perpendiculars from $Z$ to $\overleftrightarrow{B C}, \overleftrightarrow{A C}$, and $\overleftrightarrow{A B}$ be $P, Q$, and $R$, respectively. As usual, we let the lowercase letters of each of the point labels be the corresponding complex numbers. In order to show that $P, Q$, and $R$ are collinear, we would like to show that
$$(p-q)(\bar{p}-\bar{r})-(\bar{p}-\bar{q})(p-r)=0 .$$

Our first step is to find $p, q$, and $r$ in terms of $a, b, c$, and $z$. Fortunately, we only have to find one of them, since they'll all have the same form. Once we have one of them, we hopefully can use that form to determine the other two.

Since $P$ is on $\overleftrightarrow{B C}$, complex numbers $p, b$, and $c$ are collinear in the complex plane. This means that
$$(p-b)(\bar{b}-\bar{c})-(\bar{p}-\bar{b})(b-c)=0 .$$

We still need to find another equation for $p$ (the one we just found only comes from the fact that $P$ is on $\overleftrightarrow{B C}$, which isn't enough to uniquely specify $P$ ). We turn to our other restriction on $P$, which is that $\overleftrightarrow{Z P} \perp \overleftrightarrow{B C}$. This means that we have
$$(p-z)(\bar{b}-\bar{c})+(\bar{p}-\bar{z})(b-c)=0 .$$

291

---

<!-- Page 292 -->

CHAPTER 8. GEOMETRY OF COMPLEX NUMBERS

Comparing this to Equation (8.8), we see something promising. If we add the two equations, we cancel $\bar{p}$, and we can solve for $p$. So, we add Equations (8.8) and (8.9) by combining ( $\bar{b}-\bar{c}$ ) terms and ( $b-c$ ) terms:
$$((p-b)+(p-z))(\bar{b}-\bar{c})+(-(\bar{p}-\bar{b})+(\bar{p}-\bar{z}))(b-c)=0 .$$

We therefore have $(2 p-b-z)(\bar{b}-\bar{c})+(\bar{b}-\bar{z})(b-c)=0$, and solving for $p$ gives
$$p=\frac{1}{2}\left(-\frac{(\bar{b}-\bar{z})(b-c)}{\bar{b}-\bar{c}}+b+z\right) .$$
(Note that we can divide by $\bar{b}-\bar{c}$ because $b \neq c$.) Well, at least we found $p$, but that expression on the right is quite a mess. We're not stuck yet, though. We haven't chosen our origin. One natural choice might appear to be $z$, but then we're left with $\bar{b}$ and $\bar{c}$, and we'd prefer to get rid of them, too. Otherwise, after writing similar expressions for $q$ and $r$, we'll have $\bar{a}, \bar{b}$, and $\bar{c}$ to deal with on top of $a, b$, and $c$. (Try it and see-you'll get a nice enough expression for $p$, but once you join it with the expressions for $q$ and $r$, you'll have quite an intimidating mess on your hands for $(p-q)(\bar{p}-\bar{r})-(\bar{p}-\bar{q})(p-r)$.)

So, we go back to the drawing board on choosing the origin. We focus on the conjugates, since they scared us off the choice of $z$ as the origin. A natural choice that presents itself for the origin is the center of the circle. By choosing the center of the circle as the origin and letting the radius of the circle be 1 , we have $|a|=|b|=|c|=|z|=1$, so $a \bar{a}=b \bar{b}=c \bar{c}=z \bar{z}=1$. This allows us to get rid of all of the conjugates in our expression for $p$ in Equation (8.10)! Let's see what happens when we substitute to get rid of the conjugates:
$$p=\frac{1}{2}\left(-\frac{\left(\frac{1}{b}-\frac{1}{z}\right)(b-c)}{\frac{1}{b}-\frac{1}{c}}+b+z\right)=\frac{1}{2}\left(-\frac{\left(\frac{z-b}{b z}\right)(b-c)}{\frac{c-b}{b c}}+b+z\right)=\frac{1}{2}\left(\frac{(z-b) c}{z}+b+z\right)=\frac{1}{2}\left(b+c+z-\frac{b c}{z}\right) .$$

Now that's something we can work with! By symmetry, we can now write expressions for $q$ and $r$, and we have
$$\begin{array}{l}
p=\frac{1}{2}\left(b+c+z-\frac{b c}{z}\right), \\
q=\frac{1}{2}\left(c+a+z-\frac{c a}{z}\right), \\
r=\frac{1}{2}\left(a+b+z-\frac{a b}{z}\right) .
\end{array}$$

Now we're ready to tackle $(p-q)(\bar{p}-\bar{r})-(\bar{p}-\bar{q})(p-r)$. If we can show this equals 0 , then we know that $P, Q$, and $R$ are collinear. Each of the differences in this expression gives us a lot of cancellation, so it's not nearly as scary as it looks. We'll start by simplifying $(p-q)(\bar{p}-\bar{r})$, since we can simply take the conjugate of the result to get $(\bar{p}-\bar{q})(p-r)$. We find
$$\begin{aligned}
(p-q)(\bar{p}-\bar{r}) & =\frac{1}{4}\left(b-a-\frac{b c}{z}+\frac{a c}{z}\right)\left(\bar{c}-\bar{a}-\frac{\bar{b} \bar{c}}{\bar{z}}+\frac{\bar{a} \bar{b}}{\bar{z}}\right) \\
& =\frac{1}{4}\left(b-a-(b-a) \frac{c}{z}\right)\left(\bar{c}-\bar{a}-(\bar{c}-\bar{a}) \frac{\bar{b}}{\bar{z}}\right) \\
& =\frac{1}{4}(b-a)\left(1-\frac{c}{z}\right)(\bar{c}-\bar{a})\left(1-\frac{\bar{b}}{\bar{z}}\right) \\
& =\frac{1}{4}(b-a)\left(\frac{z-c}{z}\right)(\bar{c}-\bar{a})\left(\frac{\bar{z}-\bar{b}}{\bar{z}}\right) \\
& =\frac{1}{4 z \bar{z}}(b-a)(z-c)(\bar{c}-\bar{a})(\bar{z}-\bar{b}) .
\end{aligned}$$

292

---

<!-- Page 293 -->

8.6. SUMMARY

We're very close now! We can again substitute for the conjugates (so $z \bar{z}=1$, for example), and we have
$$(p-q)(\bar{p}-\bar{r})=\frac{1}{4}(b-a)(z-c)\left(\frac{1}{c}-\frac{1}{a}\right)\left(\frac{1}{z}-\frac{1}{b}\right)=\frac{1}{4 a b c d}(b-a)(z-c)(a-c)(b-z) .$$

Taking the conjugate of this, and then substituting for $\bar{a}, \bar{b}, \bar{c}$, and $\bar{z}$, gives
$$\begin{aligned}
(\bar{p}-\bar{q})(p-r) & =\frac{1}{4 \bar{a} \bar{b} \bar{c} \bar{d}}(\bar{b}-\bar{a})(\bar{z}-\bar{c})(\bar{a}-\bar{c})(\bar{b}-\bar{z}) \\
& =\frac{a b c d}{4}\left(\frac{1}{b}-\frac{1}{a}\right)\left(\frac{1}{z}-\frac{1}{c}\right)\left(\frac{1}{a}-\frac{1}{c}\right)\left(\frac{1}{b}-\frac{1}{z}\right) \\
& =\frac{a b c d}{4}\left(\frac{a-b}{a b}\right)\left(\frac{c-z}{c z}\right)\left(\frac{c-a}{a c}\right)\left(\frac{z-b}{b z}\right) \\
& =\frac{1}{4 a b c d}(a-b)(c-z)(c-a)(z-b)
\end{aligned}$$

This equals our expression for $(p-q)(\bar{p}-\bar{r})$ because each of the four differences here is the opposite of the corresponding difference in our expression for $(p-q)(\bar{p}-\bar{r})$. Therefore, $(p-q)(\bar{p}-\bar{r})$ equals its own conjugate, which means it is real. This tells us that $P, Q$, and $R$ are collinear. The line that contains these points is called a Simson Line of the triangle.

The key step in this solution can be a very powerful strategy:

Concept:

When applying complex numbers to a geometry problem involving a single circle, letting the circle be the unit circle centered at the origin can be a very powerful strategy. One reason this is so useful is that for any point $z$ on the circle, we have $\bar{z}=\frac{1}{z}$.
8.6 Summary

The image of a translation of $z$ by the complex number $w$ is $z+w$, the image of a dilation of $z$ about the origin by scale factor $c$ is $c z$, and the image of a rotation of $z$ about a point $w$ counterclockwise by an angle $\theta$ is $e^{i \theta}(z-w)+w$.

Important: The midpoint of the segment connecting $z_{1}$ and $z_{2}$ in the complex plane is $\frac{z_{1}+z_{2}}{2}$. $!$

Important: Let $A, B, C$, and $D$ be four different points in the complex plane, and let $a, b, c$, and $d$ be complex numbers corresponding to these points.
- We have $\overleftrightarrow{A B} \| \overleftrightarrow{C D}$ if and only if $(b-a)(\bar{d}-\bar{c})-(\bar{b}-\bar{a})(d-c)=0$. This is equivalent to the condition that $(b-a) /(d-c)$ is real.
- We have $\overleftrightarrow{A B} \perp \overleftrightarrow{C D}$ if and only if $(b-a)(\bar{d}-\bar{c})+(\bar{b}-\bar{a})(d-c)=0$. This is equivalent to the condition that $(b-a) /(d-c)$ is imaginary.

Important: If complex numbers $w$ and $z$ correspond to points $W$ and $Z$ in the complex plane, then $\mathrm{WZ}^{2}=(w-z)(\bar{w}-\bar{z})$.

293

---

<!-- Page 294 -->

CHAPTER 8. GEOMETRY OF COMPLEX NUMBERS

\begin{tabular}{|l|l|}
\hline Important: & \begin{tabular}{l}
For any complex numbers $z_{1}, z_{2}, z_{3}, \ldots, z_{n}$, we have
$$\left|z_{1}\right|+\left|z_{2}\right|+\cdots+\left|z_{n}\right| \geq\left|z_{1}+z_{2}+\cdots+z_{n}\right|$$ \\
where equality holds if and only if $z_{1}, z_{2}, z_{3}, \ldots, z_{n}$ are on the same ray from the origin.
\end{tabular} \\
\hline Important: & Let $\triangle A B C$ be a triangle in the complex plane whose vertices correspond to the complex numbers $a, b$, and $c$. Triangle $A B C$ is equilateral if and only if $a-b=\zeta(c-b)$, where $\zeta$ is a primitive sixth root of unity. \\
\hline
\end{tabular}

Things To Watch Out For! 

WARNING!! The orientations of rotations matter in complex numbers, just as they matter in geometry.

Problem Solving Strategies 

Concepts:
- When placing a geometric problem on the complex plane, we can choose where to place the origin. Choosing a convenient point can often simplify the problem greatly.
- Sometimes we can prove a statement by proving a more general statement.
- Maintaining symmetry in systems of equations helps us find effective ways to work with the equations.
- A little wishful thinking can go a long way.
- Some complex number problems that don't appear to be about geometry can be solved quickly by thinking about the problem geometrically.
- When your initial approach to a problem hits a seemingly unsurpassable obstacle, take a step back and look for another way to view the problem that allows you to avoid the obstacle.
- Complex numbers can often be helpful in problems involving rotations, since rotations are easy to express with complex numbers.
- Working backwards from the desired result is a powerful problem solving strategy.
- Don't always specify the origin right away-sometimes waiting will allow you to exploit symmetry in a problem or will reveal a surprisingly useful choice for the origin.
- When applying complex numbers to a geometry problem involving a single circle, consider letting the circle be the unit circle centered at the origin.

294

---

<!-- Page 295 -->

REVIEW PROBLEMS

REVIEW PROBLEMS
8.32 Describe the transformation that maps $z$ to $\bar{z}$ in the complex plane.
8.33 For all $z$, let $f_{1}(z)$ be the image of $z$ upon a translation of 2 units horizontally and -3 units vertically, and let $f_{2}(z)$ be the image of $z$ upon a rotation about $4 i$ counterclockwise by $\frac{\pi}{2}$.
(a) Find $\left(f_{2} \circ f_{1}\right)(z)$ in terms of $z$.
(b) Find $\left(f_{1} \circ f_{2}\right)(z)$ in terms of $z$.
8.34 Let $f(z)=i \bar{z}$. Describe the transformation that maps $z$ to $f(z)$ for all $z$.
8.35 What must be true about the points corresponding to complex numbers $a, b$ and $c$ under each of the following conditions:
(a) $|a-b|+|a-c|=|b-c|$
(b) $\quad|a-b|^{2}+|a-c|^{2}=|b-c|^{2}$
8.36 For a given nonzero complex number $z$, describe in words how to find the following points in the complex plane:
(a) $\frac{z}{|z|}$
(b) $z+\bar{z}$
(c) $z+|z|$
8.37 Use complex numbers to show that the line segment connecting the midpoints of two sides of a triangle is parallel to the third side and half the length of the third side.
8.38 Let $A$ correspond to $3-2 i$ and $B$ correspond to $1-5 i$.
(a) $\overline{A B}$ is perpendicular to the line through $B$ and which of the following on the complex plane: $2-7 i,-6+2 i$, $-5-i$ ?
(b) Find an equation whose graph consists of point $B$ as well as all complex numbers $z$ such that the line through $z$ and $B$ is perpendicular to $\overline{A B}$.
8.39 Use complex numbers to show that if $\angle A D B=90^{\circ}$, then point $D$ is on the circle with $\overline{A B}$ as diameter.
8.40 Suppose that $2+i$ and $8-3 i$ are opposite vertices of a regular hexagon in the complex plane. What are the complex numbers that correspond to the other four vertices?
8.41 The median of a trapezoid is the segment with the midpoints of the trapezoid's legs as endpoints. Use complex numbers to prove that the median of a trapezoid is parallel to the bases of the trapezoid, and that the length of the median is the average of the lengths of the bases.
8.42 Use complex numbers to prove that the diagonals of a parallelogram are perpendicular if and only if the parallelogram is a rhombus.
8.43 Let $a$ and $b$ be distinct complex numbers. Show that $z$ lies on the perpendicular bisector of $a$ and $b$ if and only if
$$(\bar{a}-\bar{b}) z+(a-b) \bar{z}=a \bar{a}-b \bar{b}$$
8.44 Suppose $W X Y Z$ is a square with center $O$. Let $T$ be the midpoint of $\overline{W X}$ and $S$ be the midpoint of $\overline{O Y}$. Use complex numbers to show that $\triangle T S Z$ is an isosceles right triangle.

295

---

<!-- Page 296 -->

CHAPTER 8. GEOMETRY OF COMPLEX NUMBERS
8.45 Use complex numbers to show that if $W, X, Y$, and $Z$ are four points in a plane such that $\overline{W X}$ is perpendicular to both $\overline{X Y}$ and $\overline{W Z}$, then the midpoint of $\overline{Y Z}$ is the same distance from $W$ and $X$.
8.46 Show that a line segment joining the midpoints of opposite sides of a quadrilateral and the line segment joining the midpoints of the diagonals bisect each other.
8.47 Suppose $A B C D$ is a parallelogram and that complex numbers $a, b, c$, and $d$ correspond to $A, B, C$, and $D$, respectively. Find $d$ in terms of $a, b$, and $c$.
8.48 Show that $|w-z| \geq|w|-|z|$ for all complex numbers $w$ and $z$.
8.49 Let $P$ be a point inside rectangle $A B C D$. Show that $A P^{2}+C P^{2}=B P^{2}+D P^{2}$.

Challenge Problems
8.50 Let $O$ be the center of square $A B C D$. Show that no matter what line $k$ we draw through $O$, the sum of the squares of the distances from the vertices of $A B C D$ to $k$ is the same. Hints: 17
8.51 Given a triangle $A B C$, suppose we construct squares $B C D J, C A F G$, and $A B H K$ on the sides of the triangle such that the squares do not overlap the triangle. We then locate points $P$ and $Q$ such that GCDQ and BHPJ are parallelograms. Prove that $\triangle P A Q$ is an isosceles right triangle. Hints: 269
8.52 Let $z, a$, and $b$ be complex numbers such that $a \neq b$. Let $w$ be the reflection of $z$ over the line joining $a$ and $b$, and let $p$ be the projection of $z$ onto the line joining $a$ and $b$. (That is, let $p$ be the foot of the perpendicular from $z$ to the line through $a$ and $b$.) Find $p$ and $w$ in terms of $a, b$, and $z$. Hints: 150
8.53 Let $f(x)=\sqrt{x^{2}+(x-1)^{2}}+\sqrt{x^{2}+(x+1)^{2}}$. Find the minimum value of $f$ over all real numbers. Hints: 207,40
8.54 If $z_{1}$ and $z_{2}$ are complex numbers such that $\left|z_{1}-5+3 i\right| \leq 4$ and $\left|z_{2}-5 i\right| \leq 2$, find the maximum and minimum values of $\left|z_{1}-z_{2}\right|$. Hints: 35
8.55 Let $z$ be a complex number. Find the minimum value of
$$|z-2|+|z-(1+2 i)|+|z-(-1+i)|+|z-(-1-i)|$$

Hints: 151
8.56 Let $\triangle A B C$ be a triangle in the complex plane whose vertices correspond to complex numbers $a, b$, and $c$. Show that each of the following is a necessary and sufficient condition for $\triangle A B C$ to be equilateral:
(a) $a^{2}+b^{2}+c^{2}=a b+a c+b c$. Hints: 111,233
(b) $\frac{1}{a-b}+\frac{1}{b-c}+\frac{1}{c-a}=0$.
(c) $(b-c)^{2}+(c-a)^{2}+(a-b)^{2}=0$.
8.57 ★ For a positive integer $n$, define $S_{n}$ to be the minimum value of the sum
$$\sqrt{(2 \cdot 1-1)^{2}+a_{1}^{2}}+\sqrt{(2 \cdot 2-1)^{2}+a_{2}^{2}}+\sqrt{(2 \cdot 3-1)^{2}+a_{3}^{2}}+\cdots+\sqrt{(2 \cdot n-1)^{2}+a_{n}^{2}}$$
where $a_{1}, a_{2}, \ldots, a_{n}$ are positive real numbers whose sum is 17 . There is a unique positive integer $n$ for which $S_{n}$ is also an integer. Find this n. (Source: AIME)
8.58 Suppose $A B C D E$ is a pentagon such that the lines connecting $A, B, C$, and $D$ respectively to the midpoints of $\overline{E B}, \overline{A C}, \overline{B D}$, and $\overline{C E}$ are concurrent. Show that the line connecting $E$ to the midpoint of $\overline{A D}$ also passes through this common point. Hints: 95, 264

296

---

<!-- Page 297 -->

CHALLENGE PROBLEMS
8.59 Let $P_{0} P_{1} \cdots P_{n-1}$ be a regular $n$-gon inscribed in a unit circle $C$, and let $P$ be a point on $C$.
(a) Prove that $P P_{0}^{2}+P P_{1}^{2}+\cdots+P P_{n-1}^{2}=2 n$ for any $P$. Hints: 172
(b) Prove that $P P_{0}^{4}+P P_{1}^{4}+\cdots+P P_{n-1}^{4}=6 n$ for any $P$.
8.60★ There are $2 n$ complex numbers that satisfy both $z^{28}-z^{8}-1=0$ and $|z|=1$. These numbers have the form $z_{m}=\cos \theta_{m}+i \sin \theta_{m}$, where $0^{\circ} \leq \theta_{1}<\theta_{2}<\cdots<\theta_{2 n}<360^{\circ}$ and angles are measured in degrees. Find the value of $\theta_{2}+\theta_{4}+\cdots+\theta_{2 n}$. (Source: AIME) Hints: 22, 113
8.61 Regular decagon $P_{1} P_{2} \cdots P_{10}$ is drawn in the coordinate plane, with $P_{1}$ at $(1,0)$ and $P_{6}$ at $(3,0)$. If $P_{n}$ is the point $\left(x_{n}, y_{n}\right)$, compute the numerical value of
$$\left(x_{1}+y_{1} i\right)\left(x_{2}+y_{2} i\right)\left(x_{3}+y_{3} i\right) \cdots\left(x_{10}+y_{10} i\right) .$$
(Source: ARML) Hints: 217
8.62 ★ The sides of rectangle $A B C D$ have lengths 10 and 11. An equilateral triangle is drawn so that no point of the triangle lies outside $A B C D$. Find the maximum possible area of such a triangle. (Source: AIME) Hints: 161
8.63★ Let $P$ be a point inside equilateral triangle $A B C$ with side $s$. Show that
$$3\left(P A^{4}+P B^{4}+P C^{4}+s^{4}\right)=\left(P A^{2}+P B^{2}+P C^{2}+s^{2}\right)^{2} .$$

Hints: 96,89
8.64★ Given triangle $A B C$, construct equilateral triangles $B C X, C A Y, A B Z$ externally. Let $B^{\prime}$ and $N^{\prime}$ be the midpoints of $\overline{B C}$ and $\overline{C Y}$, respectively, and let $M$ and $N$ be the midpoints of $\overline{A Z}$ and $\overline{C X}$, respectively. Prove that $\overline{B^{\prime} N^{\prime}} \perp \overline{M N}$. (Source: Argentina) Hints: 127,85

Extra! Here's the magical three-dimensional proof of Monge's Theorem that is suggested on page 289. Suppose we start with three spheres with different radii such that no sphere is entirely within another. There are two planes that are tangent to all three spheres such that the three spheres are sandwiched between the two planes. Since the spheres do not have the same radii, these two planes intersect in a line which we'll call line $k$. For each pair of spheres, there is a cone that is tangent to both spheres. The aforementioned planes are also tangent to each cone, and therefore include the vertex of
each cone. So, the vertex of each of the three cones determined by a pair of the spheres is on the line that is the intersection of the planes.

With all that mind, picture the cross-section that is formed by the plane that bisects the angle between the planes. This plane must pass through the centers of the spheres, and must include line $k$ (and therefore the vertex of each cone). Moreover, the intersection of the plane and each cone produces the two lines that are tangent to the corresponding pair of circles. Therefore, this cross-section produces exactly the situation in Monge's Theorem, and shows why the three points in question are collinear.

297

---

