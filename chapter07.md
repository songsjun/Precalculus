# Chapter 7: Trigonometry and Complex Numbers

<!-- Page 219 -->

A complex system that works is invariably found to have evolved from a simple system that worked. - John Gall
Оснитее 7
Trigonometry and Complex Numbers
7.1 Polar Form of Complex Numbers

In Chapter 5, we learned how to convert rectangular coordinates ( $x, y$ ) into polar coordinates ( $r, \theta$ ). In this section, we apply this conversion technique to complex numbers to write complex numbers in polar form.

Problems

Problem 7.1: Explain why every complex number can be written in the form $r(\cos \theta+i \sin \theta)$ for some constants $r$ and $\theta$ with $r \geq 0$. We call this form the polar form of a complex number.

Problem 7.2: Suppose $z=r(\cos \theta+i \sin \theta)$, where $r \geq 0$. What is $|z|$ in terms of $r$ and $\theta$ ?
Problem 7.3: Write each of the following in polar form by finding the positive value of $r$ and the value of $\theta$ with $0 \leq \theta<2 \pi$ such that the given complex number equals $r(\cos \theta+i \sin \theta)$.
(a) -6
(b) $4+4 i$
(c) $3-i \sqrt{3}$
(d) $-\sqrt{2}+i \sqrt{6}$

Problem 7.4: Let $w=3+i \sqrt{3}$ and $z=2 \sqrt{3}-6 i$.
(a) Find $w z$.
(b) Express $w, z$, and $w z$ in polar form. Notice anything interesting?

219

---

<!-- Page 220 -->

CHAPTER 7. TRIGONOMETRY AND COMPLEX NUMBERS

Problem 7.5: Let $w=r(\cos \alpha+i \sin \alpha)$ and $z=s(\cos \beta+i \sin \beta)$. Express $w z$ in polar form.

Problem 7.6:
(a) Prove that $(\cos \theta+i \sin \theta)^{n}=\cos n \theta+i \sin n \theta$ for any positive integer $n$ and any angle $\theta$.
(b) Prove that $(\cos \theta-i \sin \theta)^{n}=\cos n \theta-i \sin n \theta$ for any positive integer $n$ and any angle $\theta$.

Problem 7.7: Express $\cos 5 \theta$ in terms of $\cos \theta$.

Problem 7.1: Explain why every complex number can be written in the form $r(\cos \theta+i \sin \theta)$ for some constants $r$ and $\theta$ with $r \geq 0$. We call this form the polar form of a complex number.

Solution for Problem 7.1: Let $z$ be the complex number $x+y i$, where $x$ and $y$ are real numbers. In Section 5.2, we learned that any point in the Cartesian plane with rectangular coordinates $(x, y)$ can also be denoted with the polar coordinates $(r, \theta)$, where $x=r \cos \theta$ and $y=r \sin \theta$, with $r \geq 0$ and $0 \leq \theta<2 \pi$. Therefore, for any ordered pair of real numbers ( $x, y$ ), there is a constant $r$ and an angle $\theta$ such that $x=r \cos \theta$ and $y=r \sin \theta$. This means that we can write the complex number $x+y i$ in the form $r(\cos \theta+i \sin \theta)$ for some constants $r$ and $\theta$ such that $r \geq 0$ and $0 \leq \theta<2 \pi$.

The expression $\cos \theta+i \sin \theta$ is sometimes shortened to cis $\theta$. We'll use this notation sparingly in this text, because in the next section we will introduce a better way to express complex numbers in terms of $r$ and $\theta$.

Because the complex number $z=x+y i$ in the complex plane corresponds to rectangular coordinates $(x, y)$ in the Cartesian plane, we call $x+y i$ the rectangular form of the complex number $z$. Similarly, because $z=r(\cos \theta+i \sin \theta)$ in the complex plane corresponds to the point in the Cartesian plane with polar coordinates ( $r, \theta$ ), we call this the polar form of $z$. We call $r$ the magnitude of the complex number and $\theta$ the number's argument.

Don't we already have something called the magnitude of a complex number?
Problem 7.2: Suppose $z=r(\cos \theta+i \sin \theta)$, where $r \geq 0$. What is $|z|$ in terms of $r$ and $\theta$ ?

Solution for Problem 7.2: Solution 1: Algebra. We have
$$|z|=|r \cos \theta+i r \sin \theta|=\sqrt{(r \cos \theta)^{2}+(r \sin \theta)^{2}}=\sqrt{r^{2}\left(\cos ^{2} \theta+\sin ^{2} \theta\right)}=\sqrt{r^{2}}=r$$
(The step $\sqrt{r^{2}}=r$ is only valid because $r \geq 0$.)
Solution 2: Geometry. As we saw in Problem 7.1, the point $r(\cos \theta+i \sin \theta)$ in the complex plane corresponds to the point $(r, \theta)$ in the Cartesian plane. Since $|z|$ equals the distance from $z$ to the origin in the complex plane, and the distance from ( $r, \theta$ ) to the origin in the Cartesian plane is $r$ (when $r \geq 0$ ), we have $|z|=r$.

Problem 7.3: Write each of the following in polar form by finding the positive value of $r$ and the value of $\theta$ with $0 \leq \theta<2 \pi$ such that the given complex number equals $r(\cos \theta+i \sin \theta)$.
(a) -6
(b) $4+4 i$
(c) $3-i \sqrt{3}$
(d) $-\sqrt{2}+i \sqrt{6}$

220

---

<!-- Page 221 -->

7.1. POLAR FORM OF COMPLEX NUMBERS

Solution for Problem 7.3:

Converting complex numbers in rectangular form to polar form is exactly the same as converting the rectangular coordinates $(x, y)$ to polar coordinates $(r, \theta)$.
(a) The point -6 in the complex plane is 6 units to the left of the origin. In the Cartesian plane, the polar coordinates of the point 6 units to the left of the origin are $(6, \pi)$. Therefore, a polar form of the complex number -6 is $6(\cos \pi+i \sin \pi)$, or $6 \operatorname{cis} \pi$.
(b) The point $4+4 i$ in the complex plane is point $P$ in the diagram at right. Since $P A=A O=4$, we know that $\triangle P A O$ is an isosceles right triangle. Therefore, we have $P O=4 \sqrt{2}$ and $\angle P O A=\frac{\pi}{4}$, which means that a polar form of $4+4 i$ is $4 \sqrt{2}\left(\cos \frac{\pi}{4}+i \sin \frac{\pi}{4}\right)$, or $4 \sqrt{2}$ cis $\frac{\pi}{4}$.
(c) The point $3-i \sqrt{3}$ in the complex plane is point $P$ in the diagram at right. We have $P O=\sqrt{P A^{2}+A O^{2}}=2 \sqrt{3}$, so the hypotenuse of $\triangle P A O$ is double the smaller leg of $\triangle P A O$. Therefore, we have $\angle P O A=\frac{\pi}{6}$. Since $P$ is $\frac{\pi}{6}$ clockwise from the positive $x$-axis, it is $\frac{11 \pi}{6}$ radians counterclockwise from the $x$-axis. So, we can write $3-i \sqrt{3}$ in polar form as $2 \sqrt{3}\left(\cos \frac{11 \pi}{6}+i \sin \frac{11 \pi}{6}\right)$, or $2 \sqrt{3} \operatorname{cis} \frac{11 \pi}{6}$.
(d) The point $-\sqrt{2}+i \sqrt{6}$ in the complex plane is point $P$ in the diagram at right. We have $P O=\sqrt{P A^{2}+A O^{2}}=2 \sqrt{2}$, so the hypotenuse of $\triangle P A O$ is double the smaller leg of $\triangle P A O$. Therefore we have $\angle P O A=\frac{\pi}{3}$, which means that $P$ is $\frac{2 \pi}{3}$ radians counterclockwise from the positive $x$-axis. So, the polar form of $-\sqrt{2}+i \sqrt{6}$ is $2 \sqrt{2}\left(\cos \frac{2 \pi}{3}+i \sin \frac{2 \pi}{3}\right)$, or $2 \sqrt{2}$ cis $\frac{2 \pi}{3}$.

Sidenote: You may have noticed that while we usually write complex numbers in the form $a+b i$, with the $i$ after the imaginary part of the number, in the problem above we have written $3-i \sqrt{3}$ and $-\sqrt{2}+i \sqrt{6}$ instead of $3-\sqrt{3} i$ and $-\sqrt{2}+\sqrt{6} i$. We follow this convention in part to avoid confusion, since we might mistake the $i$ in $3-\sqrt{3} i$ as being inside the square root symbol. (This mistake is particularly easy to make when the numbers in question are hand-written.)

Problem 7.4: Let $w=3+i \sqrt{3}$ and $z=2 \sqrt{3}-6 i$.
(a) Find $w z$.
(b) Express $w, z$, and $w z$ in polar form. Notice anything interesting?

Solution for Problem 7.4:
(a) We have
$$w z=(3+i \sqrt{3})(2 \sqrt{3}-6 i)=6 \sqrt{3}-18 i+6 i+6 \sqrt{3}=12 \sqrt{3}-12 i .$$
(b) We could take a geometric approach, as we did in Problem 7.3. Or, we can note by the forms of $w, z$, and $w z$ that the arguments of these complex numbers are multiples of $\frac{\pi}{6}$. We can determine the corresponding

221

---

<!-- Page 222 -->

CHAPTER 7. TRIGONOMETRY AND COMPLEX NUMBERS

arguments by first factoring out the magnitudes of each, and then using our knowledge of trigonometry to find the arguments. Since $|w|=|3+i \sqrt{3}|=2 \sqrt{3}$, we factor $2 \sqrt{3}$ out from $w$ to find
$$w=3+i \sqrt{3}=2 \sqrt{3}\left(\frac{\sqrt{3}}{2}+\frac{1}{2} i\right) .$$

The argument of $w$ then is the angle $\theta$ such that $\cos \theta=\frac{\sqrt{3}}{2}$ and $\sin \theta=\frac{1}{2}$, so we have $\theta=\frac{\pi}{6}$ and $w=2 \sqrt{3}\left(\cos \frac{\pi}{6}+i \sin \frac{\pi}{6}\right)$.

Similarly, $|z|=|2 \sqrt{3}-6 i|=\sqrt{12+36}=4 \sqrt{3}$, and we have $z=2 \sqrt{3}-6 i=4 \sqrt{3}\left(\frac{1}{2}-\frac{\sqrt{3}}{2} i\right)$. This means the argument of $z$ is the angle $\theta$ such that $\cos \theta=\frac{1}{2}$ and $\sin \theta=-\frac{\sqrt{3}}{2}$, which gives us $\theta=\frac{5 \pi}{3}$. So, we have $z=4 \sqrt{3}\left(\cos \frac{5 \pi}{3}+i \sin \frac{5 \pi}{3}\right)$.

Finally, we have $|w z|=|12 \sqrt{3}-12 i|=\sqrt{432+144}=24$, and $w z=24\left(\frac{\sqrt{3}}{2}-\frac{1}{2} i\right)$. Therefore, we seek $\theta$ such that $\cos \theta=\frac{\sqrt{3}}{2}$ and $\sin \theta=-\frac{1}{2}$, which gives us $\theta=\frac{11 \pi}{6}$ and $w z=24\left(\cos \frac{11 \pi}{6}+i \sin \frac{11 \pi}{6}\right)$.

Listing all of our results, we have
$$\begin{aligned}
w & =2 \sqrt{3}\left(\cos \frac{\pi}{6}+i \sin \frac{\pi}{6}\right) \\
z & =4 \sqrt{3}\left(\cos \frac{5 \pi}{3}+i \sin \frac{5 \pi}{3}\right) \\
w z & =24\left(\cos \frac{11 \pi}{6}+i \sin \frac{11 \pi}{6}\right)
\end{aligned}$$

Interesting-the magnitude of $w z$ is the product of the magnitudes of $w$ and $z$, and the argument of $w z$ is the sum of the arguments of $w$ and $z$.

Is our observation at the end of this solution true for any two complex numbers $w$ and $z$ ?
Problem 7.5: Let $w=r(\cos \alpha+i \sin \alpha)$ and $z=s(\cos \beta+i \sin \beta)$. Express $w z$ in polar form.

Solution for Problem 7.5: We have
$$\begin{aligned}
w z & =r(\cos \alpha+i \sin \alpha) \cdot s(\cos \beta+i \sin \beta) \\
& =r s \cdot(\cos \alpha+i \sin \alpha)(\cos \beta+i \sin \beta) \\
& =r s \cdot(\cos \alpha \cos \beta-\sin \alpha \sin \beta+i \sin \alpha \cos \beta+i \cos \alpha \sin \beta)
\end{aligned}$$

We recognize the real part of the expression in parentheses as $\cos (\alpha+\beta)$ and the imaginary part as $\sin (\alpha+\beta)$, so we have
$$w z=r s(\cos (\alpha+\beta)+i \sin (\alpha+\beta))$$

Important: For any two complex numbers $w$ and $z$, the magnitude of $w z$ is the product of
the magnitudes of $w$ and $z$, and the argument of $w z$ is the sum of the arguments
of $w$ and $z$ (or a multiple of $2 \pi$ less than the sum of the arguments of $w$ and $z$, if
we restrict arguments to being in the interval $[0,2 \pi)$ ).

222

---

<!-- Page 223 -->

7.1. POLAR FORM OF COMPLEX NUMBERS

Problem 7.6:
(a) Prove that $(\cos \theta+i \sin \theta)^{n}=\cos n \theta+i \sin n \theta$ for any positive integer $n$ and any angle $\theta$.
(b) Prove that $(\cos \theta-i \sin \theta)^{n}=\cos n \theta-i \sin n \theta$ for any positive integer $n$ and any angle $\theta$.

Solution for Problem 7.6:
(a) We have already done the heavy lifting for this problem when we solved Problem 7.5. There, we showed that $(\operatorname{cis} \alpha)(\operatorname{cis} \beta)=\operatorname{cis}(\alpha+\beta)$. So, we have
$$(\cos \theta+i \sin \theta)^{2}=(\cos \theta+i \sin \theta)(\cos \theta+i \sin \theta)=\cos (\theta+\theta)+i \sin (\theta+\theta)=\cos 2 \theta+i \sin 2 \theta$$

We multiply this result by $\cos \theta+i \sin \theta$ to find an expression for $(\cos \theta+i \sin \theta)^{3}$ :
$$\begin{aligned}
(\cos \theta+i \sin \theta)^{3} & =(\cos \theta+i \sin \theta)(\cos \theta+i \sin \theta)^{2} \\
& =(\cos \theta+i \sin \theta)(\cos 2 \theta+i \sin 2 \theta) \\
& =\cos (\theta+2 \theta)+i \sin (\theta+2 \theta) \\
& =\cos 3 \theta+i \sin 3 \theta
\end{aligned}$$

We use induction to extend this argument to any integer $n$. Clearly, we have $(\cos \theta+i \sin \theta)^{n}=\cos n \theta+i \sin n \theta$ for $n=1$. Assuming that $(\cos \theta+i \sin \theta)^{k}=\cos k \theta+i \sin k \theta$ for some positive integer $k$, we have
$$\begin{aligned}
(\cos \theta+i \sin \theta)^{k+1} & =(\cos \theta+i \sin \theta)(\cos \theta+i \sin \theta)^{k} \\
& =(\cos \theta+i \sin \theta)(\cos k \theta+i \sin k \theta) \\
& =\cos (\theta+k \theta)+i \sin (\theta+k \theta) \\
& =\cos ((k+1) \theta)+i \sin ((k+1) \theta)
\end{aligned}$$

Therefore, by induction, we have $(\cos \theta+i \sin \theta)^{n}=\cos n \theta+i \sin n \theta$ for all positive integers $n$.
(b) The complex numbers in this part are not in polar form, but they are the conjugates of the complex numbers in part (a). This observation gives us a quick solution. If two complex numbers are equal, their conjugates must be equal. So, taking the conjugate of both sides of
$$(\cos \theta+i \sin \theta)^{n}=\cos n \theta+i \sin n \theta$$
gives
$$\overline{(\cos \theta+i \sin \theta)^{n}}=\overline{\cos n \theta+i \sin n \theta}=\cos n \theta-i \sin n \theta .$$

Since $\overline{z^{n}}=(\bar{z})^{n}$, we have
$$\overline{(\cos \theta+i \sin \theta)^{n}}=(\overline{\cos \theta+i \sin \theta})^{n}=(\cos \theta-i \sin \theta)^{n},$$
so we have the desired $(\cos \theta-i \sin \theta)^{n}=\cos n \theta-i \sin n \theta$.

The relationship we proved in part (a) is commonly referred to as de Moivre's Theorem.

Important:
!

De Moivre's Theorem states that
$$(\cos \theta+i \sin \theta)^{n}=\cos n \theta+i \sin n \theta$$
for any $\theta$ and any positive integer $n$.

223

---

<!-- Page 224 -->

CHAPTER 7. TRIGONOMETRY AND COMPLEX NUMBERS

This relationship is historically important because it helped pave the way for a deeper understanding of complex numbers that we explore in the next section. Because de Moivre's Theorem is a straightforward result of the concepts we'll develop in the next section, you don't need to memorize it now.

Problem 7.7: Express $\cos 5 \theta$ in terms of $\cos \theta$.

Solution for Problem 7.7: We could start by writing $\cos 5 \theta=\cos (4 \theta+\theta)$ and using the angle sum identity, but that would give us an expression that includes $\cos 4 \theta$ and $\sin 4 \theta$. We could then write $4 \theta$ as $3 \theta+\theta$ and apply angle sum identities again, but that will create quite a mess. Let's see if we can find a better approach.

As a starting point, we seek an equation that involves both $\cos 5 \theta$ and $\cos \theta$. De Moivre's Theorem gives us one:
$$\cos 5 \theta+i \sin 5 \theta=(\cos \theta+i \sin \theta)^{5}$$

Now, we just have to expand the right side. We can use the Binomial Theorem or a bit of algebra to see that
$$(x+y)^{5}=x^{5}+5 x^{4} y+10 x^{3} y^{2}+10 x^{2} y^{3}+5 x y^{4}+y^{5} .$$

We expand $(\cos \theta+i \sin \theta)^{5}$ by letting $x=\cos \theta$ and $y=i \sin \theta$ in our expansion of $(x+y)^{5}$. This gives us
$$\cos 5 \theta+i \sin 5 \theta=\cos ^{5} \theta+5 i \cos ^{4} \theta \sin \theta-10 \cos ^{3} \theta \sin ^{2} \theta-10 i \cos ^{2} \theta \sin ^{3} \theta+5 \cos \theta \sin ^{4} \theta+i \sin ^{5} \theta .$$

The real part of the left must equal the real part of the right. Combining this with the fact that $\sin ^{2} \theta=1-\cos ^{2} \theta$ gives us
$$\begin{aligned}
\cos 5 \theta & =\cos ^{5} \theta-10 \cos ^{3} \theta \sin ^{2} \theta+5 \cos \theta \sin ^{4} \theta \\
& =\cos ^{5} \theta-10 \cos ^{3} \theta\left(1-\cos ^{2} \theta\right)+5 \cos \theta\left(1-\cos ^{2} \theta\right)^{2} \\
& =\cos ^{5} \theta-10 \cos ^{3} \theta+10 \cos ^{5} \theta+5 \cos \theta\left(1-2 \cos ^{2} \theta+\cos ^{4} \theta\right) \\
& =\cos ^{5} \theta-10 \cos ^{3} \theta+10 \cos ^{5} \theta+5 \cos \theta-10 \cos ^{3} \theta+5 \cos ^{5} \theta \\
& =16 \cos ^{5} \theta-20 \cos ^{3} \theta+5 \cos \theta
\end{aligned}$$

Concept: De Moivre's Theorem can help us tackle problems involving $\cos n \theta$ or $\sin n \theta$,
where $n$ is a positive integer greater than 1 .

Sidenote: Above, we showed that
$$\cos 5 \theta=16 \cos ^{5} \theta-20 \cos ^{3} \theta+5 \cos \theta$$

So, if we let $f(x)=16 x^{5}-20 x^{3}+5 x$, then $\cos 5 \theta=f(\cos \theta)$. This polynomial $f(x)$ is one of a family of polynomials called the Chebyshev polynomials of the first kind. These polynomials are typically denoted $T_{n}$, and satisfy the definition $T_{0}(x)=1, T_{1}(x)=x$, and
$$T_{n+1}=2 x T_{n}(x)-T_{n-1}(x) .$$

You'll have a chance to explore Chebyshev polynomials in Challenge Problem 7.69, where you'll show that $T_{n}(\cos \theta)=\cos n \theta$ for any positive integer $n$ and any angle $\theta$. (In some sources, "Chebyshev" is given the alternative spelling "Tchebychev," which may explain why we typically use " $T$ " for the Chebyshev polynomials.)

224

---

<!-- Page 225 -->

7.2. EXPONENTIAL FORM OF COMPLEX NUMBERS

Exercises
7.1.1 Write each of the following in polar form:
(a) $-32 i$
(b) $2-2 i$
(c) $2 \sqrt{3}+6 i$
(d) $\frac{1}{4}-\frac{\sqrt{3}}{4} i$
7.1.2 Write each of the following in rectangular form:
(a) $6 \operatorname{cis} 150^{\circ}$
(c) $2 \operatorname{cis} \frac{2 \pi}{3}$
(b) $8 \operatorname{cis} 3780^{\circ}$
(d) $\quad 9 \operatorname{cis} \frac{3 \pi}{4}$
7.1.3 Show that if $w=r \operatorname{cis} \alpha$ and $z=s \operatorname{cis} \beta($ and $z \neq 0)$, then $\frac{w}{z}=\frac{r}{s} \operatorname{cis}(\alpha-\beta)$.
7.1.4 Evaluate each of the following in your head without using paper, pencil, pen, or a calculator.
(a) $(6 \sqrt{3}+18 i)(-2 \sqrt{3}+6 i)$
(b) $(4+4 i)(-3-3 i)(-10+10 i)$
7.1.5 For what values of $\theta$ does $\operatorname{cis} \theta=\operatorname{cis}(-\theta)$ ?
7.1.6 Test the identity we found in Problem 7.7 for $\cos 5 \theta$ by letting $\theta=30^{\circ}$.
7.1.7 Express $\cos 7 \theta$ in terms of $\cos \theta$.
7.1.8★ For how many positive integers $n$ less than or equal to 1000 is
$$(\sin t+i \cos t)^{n}=\sin n t+i \cos n t$$
true for all real $t$ ? (Source: AIME) Hints: 52
7.2 Exponential Form of Complex Numbers

In the last section, we saw that the argument of a product of complex numbers is the sum of the arguments of the complex numbers. This observation inspires another notation for complex numbers.

Problems

Problem 7.8: Let $f(x)=\cos x+i \sin x$.
(a) Show that $f(0)=1$ and $f(x) f(y)=f(x+y)$ for all real $x$ and $y$.
(b) Suppose a function $g$ satisfies $g(0)=1$ and $g(x) g(y)=g(x+y)$ for all real $x$ and $y$. Show that it also satisfies the following:
(i) $g(x) \neq 0$ for all $x$.
(ii) $g(x-y)=g(x) / g(y)$ for all real numbers $x$ and $y$.
(iii) $[g(x)]^{n}=g(n x)$ for any real number $x$ and any positive integer $n$.
(iv) $g(-x)=1 / g(x)$.
(c) What other functions $g$ have $g(0)=1$ and satisfy the identity $g(x) g(y)=g(x+y)$ for all $x$ and $y$ ?

225

---

<!-- Page 226 -->

CHAPTER 7. TRIGONOMETRY AND COMPLEX NUMBERS

Problem 7.8: Let $f(x)=\cos x+i \sin x$.
(a) Show that $f(0)=1$ and $f(x) f(y)=f(x+y)$ for all real $x$ and $y$.
(b) Suppose a function $g$ satisfies $g(0)=1$ and $g(x) g(y)=g(x+y)$ for all real $x$ and $y$. Show that it also satisfies the following:
(i) $g(x) \neq 0$ for all $x$.
(ii) $g(x-y)=g(x) / g(y)$ for all real numbers $x$ and $y$.
(iii) $[g(x)]^{n}=g(n x)$ for any real number $x$ and any positive integer $n$.
(iv) $g(-x)=1 / g(x)$.
(c) What other functions $g$ have $g(0)=1$ and satisfy the identity $g(x) g(y)=g(x+y)$ for all $x$ and $y$ ?

Solution for Problem 7.8:
(a) We have $f(0)=\cos 0+i \sin 0=1+0 i=1$. Proving that $f(x) f(y)=f(x+y)$ is essentially a simplified version of Problem 7.5:
$$\begin{aligned}
f(x) f(y) & =(\cos x+i \sin x)(\cos y+i \sin y) \\
& =\cos x \cos y-\sin x \sin y+i(\sin x \cos y+\cos x \sin y) \\
& =\cos (x+y)+i \sin (x+y) \\
& =f(x+y)
\end{aligned}$$
(b) Letting $y=-x$ in $g(x) g(y)=g(x+y)$ gives $g(x) g(-x)=g(0)=1$ for all $x$. Therefore, we cannot have $g(x)=0$ for any $x$, since $g(x) g(-x)$ cannot be 0 .

Since $g(x) g(y)=g(x+y)$, dividing both sides by $g(y)$ gives $g(x)=g(x+y) / g(y)$. Letting $x+y=z$, so that $x=z-y$, gives us $g(z-y)=g(z) / g(y)$, which proves (ii).

The identity $[g(x)]^{n}=g(n x)$ is simply a repeated application of $g(x) g(y)=g(x+y)$. Specifically, we have $\left[(g(x)]^{2}=g(x) g(x)=g(2 x)\right.$, and $[g(x)]^{3}=[g(x)]^{2} g(x)=g(2 x) g(x)=g(2 x+x)=g(3 x)$, and so on. We can formalize this with induction. We clearly have $[g(x)]^{1}=g(x)$, and if $[g(x)]^{k}=g(k x)$ for some positive integer $k$, then we have
$$[g(x)]^{k+1}=g(x)[g(x)]^{k}=g(x) g(k x)=g(x+k x)=g((k+1) x)$$

This shows that if $[g(x)]^{n}=g(n x)$ holds for $n=k$, then it holds for $n=k+1$. We have already showed that it holds for $n=1$, so by induction, it holds for all positive integers $n$. (Perhaps you recognize this argument from our proof of de Moivre's Theorem.)

Since $g(0)=1$ and $g(x) / g(y)=g(x-y)$, letting $x=0$ gives us $1 / g(y)=g(-y)$, which proves identity (iv).
(c) Exponential functions have this behavior! For example, if $g(x)=2^{x}$, we have $g(0)=2^{0}=1$ and
$$g(x) g(y)=2^{x} \cdot 2^{y}=2^{x+y}=g(x+y)$$

Notice that exponential functions also satisfy the identities described in part (b); these are examples of the laws of exponents with which you're already familiar.

We see that the arguments of complex numbers appear to behave a lot like exponents. Specifically, we showed in Problem 7.8 that the function
$$f(x)=\cos x+i \sin x$$
satisfies the equation
$$f(x) f(y)=f(x+y)$$

226

---

<!-- Page 227 -->

7.2. EXPONENTIAL FORM OF COMPLEX NUMBERS

for all $x$ and $y$. Moreover, we confirmed that $f(0)=1$, and that $f$ satisfies many of the relationships we know as the laws of exponents, such as $f(x) / f(y)=f(x-y), f(-x)=1 / f(x)$, and $[f(x)]^{n}=f(n x)$ for all positive integers $n$.

Because $f(x)=\cos x+i \sin x$ satisfies the same relationships that exponential functions satisfy, we have a special exponential notation for complex numbers. We write $\cos x+i \sin x$ as $e^{i x}$.

Definition: For all real $x$, we define $e^{i x}$ as
$$e^{i x}=\cos x+i \sin x .$$

With this notation, we can write the identities we showed in Problem 7.8 as
$$\begin{aligned}
e^{i x} \cdot e^{i y} & =e^{i(x+y)} \\
e^{i x} / e^{i y} & =e^{i(x-y)} \\
\left(e^{i x}\right)^{n} & =e^{i n x} \\
e^{i(-x)} & =\frac{1}{e^{i x}}
\end{aligned}$$

Now you see why we use this notation-all of these relationships are easy to recall because they are the same as the laws of exponents. For example, if you see $e^{i \alpha} / e^{i \beta}$ in a problem, it's easy to recall that this equals $e^{i(\alpha-\beta)}$, but if you see $(\cos \alpha+i \sin \alpha) /(\cos \beta+i \sin \beta)$ in a problem, it may not be immediately obvious that this expression equals $\cos (\alpha-\beta)+i \sin (\alpha-\beta)$. You might also have noticed that for positive integers $n$, the relationship $\left(e^{i x}\right)^{n}=e^{i n x}$ is de Moivre's Theorem. This is why we suggested not memorizing de Moivre's Theorem after we proved it on page 223. Exponential form makes de Moivre's Theorem easy to remember.

Because $\cos x+i \sin x=e^{i x}$, we can write the polar form of a complex number $z=r(\cos \theta+i \sin \theta)$ in the form
$$z=r e^{i \theta} .$$

We call this the exponential form of the complex number $z$, where $r$ is the magnitude of $z$ and $\theta$ is the argument, as with polar form.

WARNING!! We always use radians in exponential notation, never degrees.

You'll have to wait until your study of calculus to see technical reasons for using radians rather than degrees, but our introduction of radians in Section 2.2 gives a qualitative explanation why we prefer radians.

\begin{tabular}{|l|l|}
\hline Sidenote: & \begin{tabular}{l}
The symbol $e$ is not just a placeholder to remind us that complex numbers can be written in an exponential form. There is a real number $e$ such that we have $e^{i \theta}=\cos \theta+i \sin \theta$. This real number is irrational and approximately equal to 2.7182818. \\
There are many ways to define $e$. One of the simplest is to consider the expression $g(n)=\left(1+\frac{1}{n}\right)^{n}$. Using a calculator or computer, compute $g(n)$ for larger and larger values of $n$. As $n$ gets very large, you'll find that $g(n)$ appears to become constant. That constant is $e$. \\
While you'll find $e$ very useful in your study of complex numbers, you'll see many more wonderful properties of $e$ in your continued study of mathematics, and you'll learn why it is considered one of the most important constants in mathematics.
\end{tabular} \\
\hline
\end{tabular}

227

---

<!-- Page 228 -->

CHAPTER 7. TRIGONOMETRY AND COMPLEX NUMBERS

Problems

Problem 7.9: Express each of the following in exponential form:
(a) $-2 i$
(b) $1-i$
(c) $-3 \sqrt{3}+3 i$

Problem 7.10: Express each of the following in rectangular form:
(a) $e^{\pi i}$
(b) $6 e^{\pi i / 3}$
(c) $\quad 4 e^{7 \pi i / 4}$

Problem 7.11: Evaluate the following:
(a) $(1+i)^{20}$
(b) $\quad(3-i \sqrt{3})^{5}$

Problem 7.12: For what values of $\theta$ is $e^{i \theta}=1$ ?

Problem 7.13: Show that if $z=r e^{i \theta}$, then $\bar{z}=r e^{-i \theta}$.
Problem 7.14:
(a) Use exponential form to prove that $z \bar{z}=|z|^{2}$ for all complex numbers $z$.
(b) Use exponential form to prove that $|z w|=|z||w|$ for all complex numbers $z$ and $w$.
(c) Prove that complex number multiplication is associative. In other words, show that if $w_{1}, w_{2}$, and $w_{3}$ are complex numbers, then $\left(w_{1} w_{2}\right) w_{3}=w_{1}\left(w_{2} w_{3}\right)$.

Problem 7.15: Express $e^{i x} \cdot e^{i y}$ in terms of $\cos x, \sin x, \cos y$, and $\sin y$. How does your result make remembering the angle sum identities for $\cos (x+y)$ and $\sin (x+y)$ easy?

Problem 7.16:
(a) Find $\cos \theta$ in terms of $e^{i \theta}$ and $e^{-i \theta}$.
(b) Explain how you can use your relationship from part (a) to remember the product-to-sum identity for $\cos x \cos y$.

Problem 7.17: Find the positive integer $n$ such that
$$\arctan \frac{1}{3}+\arctan \frac{1}{4}+\arctan \frac{1}{5}+\arctan \frac{1}{n}=\frac{\pi}{4}$$
(Source: AIME) Hints: 74, 124

Problem 7.9: Express each of the following in exponential form:
(a) $-2 i$
(b) $1-i$
(c) $-3 \sqrt{3}+3 i$

Solution for Problem 7.9: Converting rectangular form to exponential form is essentially the same as converting rectangular form to polar form.
(a) We have $|-2 i|=2$. Since $-2 i$ is 2 units below the origin in the complex plane, the argument of $-2 i$ in exponential (and polar) form is $\frac{3 \pi}{2}$. Therefore, we have $-2 i=2 e^{3 \pi i / 2}$.

228

---

<!-- Page 229 -->

7.2. EXPONENTIAL FORM OF COMPLEX NUMBERS
(b) We have $|1-i|=\sqrt{2}$, so we convert $1-i$ to exponential form by writing $1-i=\sqrt{2}\left(\frac{\sqrt{2}}{2}-\frac{\sqrt{2}}{2} i\right)$ and finding the angle $\theta$ such that $\cos \theta=\frac{\sqrt{2}}{2}$ and $\sin \theta=-\frac{\sqrt{2}}{2}$. This angle is $\frac{7 \pi}{4}$, so we have $1-i=\sqrt{2} e^{7 \pi i / 4}$.
(c) We have $|-3 \sqrt{3}+3 i|=6$, so we convert $-3 \sqrt{3}+3 i$ to exponential form by writing $-3 \sqrt{3}+3 i=6\left(-\frac{\sqrt{3}}{2}+\frac{i}{2}\right)$ and finding the angle $\theta$ such that $\cos \theta=-\frac{\sqrt{3}}{2}$ and $\sin \theta=\frac{1}{2}$. This angle is $\frac{5 \pi}{6}$, so we have $-3 \sqrt{3}+3 i=6 e^{5 \pi i / 6}$.

Problem 7.10: Express each of the following in rectangular form:
(a) $e^{\pi i}$
(b) $6 e^{\pi i / 3}$
(c) $\quad 4 e^{7 \pi i / 4}$

Solution for Problem 7.10:
(a) We have $e^{\pi i}=\cos \pi+i \sin \pi=-1+0 i=-1$.

Sidenote: Adding 1 to both sides of $e^{\pi i}=-1$ gives us an equation that relates the five most important constants in mathematics:
$$e^{\pi i}+1=0 .$$
(b) We have $6 e^{\pi i / 3}=6\left(\cos \frac{\pi}{3}+i \sin \frac{\pi}{3}\right)=6\left(\frac{1}{2}+\frac{\sqrt{3}}{2} i\right)=3+3 i \sqrt{3}$.
(c) We have $4 e^{7 \pi i / 4}=4\left(\cos \frac{7 \pi}{4}+i \sin \frac{7 \pi}{4}\right)=4\left(\frac{\sqrt{2}}{2}-\frac{\sqrt{2}}{2} i\right)=2 \sqrt{2}-2 i \sqrt{2}$.

Problem 7.11: Evaluate the following:
(a) $(1+i)^{20}$
(b) $\quad(3-i \sqrt{3})^{5}$

Solution for Problem 7.11:
(a) We could start with the Binomial Theorem to expand $(1+i)^{20} \ldots$ on second thought, maybe not. Exponential form offers a much easier way. In exponential form, $1+i$ is $\sqrt{2} e^{\pi i / 4}$, so we have
$$(1+i)^{20}=\left(\sqrt{2} e^{\pi i / 4}\right)^{20}=\left(2^{1 / 2}\right)^{20} e^{20 \pi i / 4}=2^{10} e^{5 \pi i}=1024(\cos 5 \pi+i \sin 5 \pi)=-1024 .$$
(b) As in the previous part, we convert $3-i \sqrt{3}$ to exponential form, writing it as $2 \sqrt{3} e^{11 \pi i / 6}$. We therefore have
$$(3-i \sqrt{3})^{5}=\left(2 \sqrt{3} e^{11 \pi i / 6}\right)^{5}=(2 \sqrt{3})^{5} e^{55 \pi i / 6}=32 \cdot 9 \sqrt{3}\left(\cos \frac{55 \pi}{6}+i \sin \frac{55 \pi}{6}\right) .$$

Subtracting multiples of $2 \pi$ repeatedly from $\frac{55 \pi}{6}$ gives us
$$(3-i \sqrt{3})^{5}=288 \sqrt{3}\left(\cos \frac{7 \pi}{6}+i \sin \frac{7 \pi}{6}\right)=288 \sqrt{3}\left(-\frac{\sqrt{3}}{2}-\frac{i}{2}\right)=-432-144 i \sqrt{3} .$$

Problem 7.12: For what values of $\theta$ is $e^{i \theta}=1$ ?
Solution for Problem 7.12: We obviously have $e^{i \theta}=1$ when $\theta=0$, but are there other values of $\theta$ for which $e^{i \theta}=1$ ? Writing $e^{i \theta}$ in polar form gives us $\cos \theta+i \sin \theta=1$, which means that $\cos \theta=1$ and $\sin \theta=0$. Therefore, $\theta$ must be an integer multiple of $2 \pi$ in order to have $e^{i \theta}=1$.

229

---

<!-- Page 230 -->

CHAPTER 7. TRIGONOMETRY AND COMPLEX NUMBERS

We also could have reasoned to this answer by thinking about the complex plane. Plotting the point $e^{i \theta}$ in the complex plane is the same as plotting the point with polar coordinates $(1, \theta)$ in the Cartesian plane. So, the point $e^{i \theta}$ is on the unit circle graphed in the complex plane. Specifically, it is the terminal point of $\theta$, which means we have $e^{i \theta}=1$ if and only if $\theta$ is an integer multiple of $2 \pi$.

Problem 7.13: Show that if $z=r e^{i \theta}$, then $\bar{z}=r e^{-i \theta}$.

Solution for Problem 7.13: We have $z=r e^{i \theta}=r(\cos \theta+i \sin \theta)$, so
$$\bar{z}=\overline{r \cos \theta+r i \sin \theta}=r \cos \theta-r i \sin \theta=r(\cos \theta-i \sin \theta) .$$

Because $\cos \theta=\cos (-\theta)$ and $\sin \theta=-\sin (-\theta)$, we have
$$\bar{z}=r(\cos \theta-i \sin \theta)=r(\cos (-\theta)-i(-\sin (-\theta)))=r(\cos (-\theta)+i \sin (-\theta))=r e^{-i \theta}$$
$$\text { Important: If } z=r e^{i \theta}, \text { then } \bar{z}=r e^{-i \theta}$$

Problem 7.14:
(a) Use exponential form to prove that $z \bar{z}=|z|^{2}$ for all complex numbers $z$.
(b) Use exponential form to prove that $|z w|=|z||w|$ for all complex numbers $z$ and $w$.
(c) Prove that complex number multiplication is associative. In other words, show that if $w_{1}, w_{2}$, and $w_{3}$ are complex numbers, then $\left(w_{1} w_{2}\right) w_{3}=w_{1}\left(w_{2} w_{3}\right)$.

Solution for Problem 7.14:
(a) Let $z=r e^{i \theta}$, so $|z|=r$ and $\bar{z}=r e^{-i \theta}$. Therefore, we have
$$z \bar{z}=\left(r e^{i \theta}\right)\left(r e^{-i \theta}\right)=r^{2} e^{i \theta-i \theta}=r^{2}=|z|^{2} .$$
(b) Back on page 205, we bashed through this proof with rectangular form, but exponential form gives the result immediately. Let $z=r e^{i \theta}$ and $w=s e^{i \phi}$. Then, $|z|=r,|w|=s$, and
$$|z w|=\left|\left(r e^{i \theta}\right)\left(s e^{i \phi}\right)\right|=\left|r s e^{i(\theta+\phi)}\right|=\left|r s \| e^{i(\theta+\phi)}\right|=r s=|z||w| .$$
(c) Let $w_{1}=r_{1} e^{i \theta_{1}}, w_{2}=r_{2} e^{i \theta_{2}}$, and $w_{3}=r_{3} e^{i \theta_{3}}$. Then, we have
$$\begin{array}{l}
\left(w_{1} w_{2}\right) w_{3}=\left(r_{1} e^{i \theta_{1}} \cdot r_{2} e^{i \theta_{2}}\right) r_{3} e^{i \theta_{3}}=r_{1} r_{2} e^{i\left(\theta_{1}+\theta_{2}\right)} \cdot r_{3} e^{i \theta_{3}}=r_{1} r_{2} r_{3} e^{i\left(\theta_{1}+\theta_{2}+\theta_{3}\right)} \\
w_{1}\left(w_{2} w_{3}\right)=r_{1} e^{i \theta_{1}}\left(r_{2} e^{i \theta_{2}} \cdot r_{3} e^{i \theta_{3}}\right)=r_{1} e^{i \theta_{1}}\left(r_{2} r_{3} e^{i\left(\theta_{2}+\theta_{3}\right)}\right)=r_{1} r_{2} r_{3} e^{i\left(\theta_{1}+\theta_{2}+\theta_{3}\right)}
\end{array}$$
so $\left(w_{1} w_{2}\right) w_{3}=w_{1}\left(w_{2} w_{3}\right)$.
Concept: Exponential form sometimes offers an easy way to prove facts involving complex
number multiplication.

230

---

<!-- Page 231 -->

7.2. EXPONENTIAL FORM OF COMPLEX NUMBERS

Problem 7.15: Express $e^{i x} \cdot e^{i y}$ in terms of $\cos x, \sin x, \cos y$, and $\sin y$. How does your result make remembering the angle sum identities for $\cos (x+y)$ and $\sin (x+y)$ easy?

Solution for Problem 7.15: We have
$$\begin{aligned}
e^{i x} \cdot e^{i y} & =(\cos x+i \sin x)(\cos y+i \sin y) \\
& =\cos x \cos y-\sin x \sin y+i(\sin x \cos y+\cos x \sin y)
\end{aligned}$$

However, we also have
$$e^{i x} \cdot e^{i y}=e^{i(x+y)}=\cos (x+y)+i \sin (x+y)$$

Our two expressions for $e^{i x} \cdot e^{i y}$ must be equal:
$$\cos (x+y)+i \sin (x+y)=\cos x \cos y-\sin x \sin y+i(\sin x \cos y+\cos x \sin y)$$

Two complex numbers are equal if and only if their real parts are equal and their imaginary parts are equal. Therefore, the equation above gives us
$$\begin{array}{l}
\cos (x+y)=\cos x \cos y-\sin x \sin y \\
\sin (x+y)=\sin x \cos y+\cos x \sin y
\end{array}$$

These are the familiar angle sum identities, and now we have a way to quickly remember them, rather than having to memorize them.

We don't call our work above a "proof" of the angle sum identities because our explanation above depends upon the fact that the function $f(x)=\cos x+i \sin x$ behaves like an exponential function. However, we proved this behavior using the angle sum identities! So, using this behavior to "prove" the angle sum identities would be circular reasoning. (By "circular reasoning," we mean using a statement we wish to prove as a step in proving the statement itself. This is clearly invalid!)

Problem 7.16:
(a) Find $\cos \theta$ in terms of $e^{i \theta}$ and $e^{-i \theta}$.
(b) Explain how you can use your relationship from part (a) to remember the product-to-sum identity for $\cos x \cos y$.

Solution for Problem 7.16:
(a) We have
$$\begin{aligned}
e^{i \theta} & =\cos \theta+i \sin \theta \\
e^{-i \theta} & =\cos (-\theta)+i \sin (-\theta)=\cos \theta-i \sin \theta
\end{aligned}$$
where we have used the identities $\cos (-\theta)=\cos \theta$ and $\sin (-\theta)=-\sin \theta$ in our expression for $e^{-i \theta}$. Adding our equations for $e^{i \theta}$ and $e^{-i \theta}$ eliminates $i \sin \theta$ and gives $e^{i \theta}+e^{-i \theta}=2 \cos \theta$, so
$$\cos \theta=\frac{e^{i \theta}+e^{-i \theta}}{2}$$

As an Exercise, you'll derive a similar expression for $\sin \theta$.

\begin{tabular}{|l|l|}
\hline Important: & For any angle $\theta$, we have
$$\begin{aligned}
\cos \theta & =\frac{e^{i \theta}+e^{-i \theta}}{2} \\
\sin \theta & =\frac{e^{i \theta}-e^{-i \theta}}{2 i}
\end{aligned}$$ \\
\hline
\end{tabular}

231

---

<!-- Page 232 -->

CHAPTER 7. TRIGONOMETRY AND COMPLEX NUMBERS
(b) Using the identity from the previous part, we have
$$\begin{aligned}
\cos x \cos y & =\left(\frac{e^{i x}+e^{-i x}}{2}\right)\left(\frac{e^{i y}+e^{-i y}}{2}\right) \\
& =\frac{1}{4}\left(e^{i(x+y)}+e^{i(x-y)}+e^{i(y-x)}+e^{i(-x-y)}\right) \\
& =\frac{1}{2}\left(\frac{e^{i(x+y)}+e^{-i(x+y)}}{2}+\frac{e^{i(x-y)}+e^{-i(x-y)}}{2}\right)
\end{aligned}$$

Again applying the identity from part (a), we see that the two fractions in parentheses above equal $\cos (x+y)$ and $\cos (x-y)$, and we have the product-to-sum identity for a product of cosines:
$$\cos x \cos y=\frac{1}{2}(\cos (x+y)+\cos (x-y))$$

Concept: The exponential form of complex numbers is a helpful way to remember trigonometric identities.

Problem 7.17: Find the positive integer $n$ such that
$$\arctan \frac{1}{3}+\arctan \frac{1}{4}+\arctan \frac{1}{5}+\arctan \frac{1}{n}=\frac{\pi}{4} .$$
(Source: AIME)

Solution for Problem 7.17: We could tackle this problem by taking the tangent of both sides and using the angle sum identity for tangent repeatedly. But complex numbers offer a much nicer solution. On the left, we have a sum of angles. Where else have we seen a sum of angles? When we multiply complex numbers in polar or exponential form, the argument of the product is the sum of the arguments of the factors. So, we can view each term on the left as the argument of a complex number, and the sum on the left is the argument of the product of these complex numbers.

But what complex number has argument arctan $\frac{1}{3}$ ? Comparing the rectangular form to the polar form quickly gives the answer, since $x+y i=r(\cos \theta+i \sin \theta)$ gives us $x=r \cos \theta$ and $y=r \sin \theta$. Dividing these gives us $\frac{y}{x}=\frac{\sin \theta}{\cos \theta}=\tan \theta$. So, a complex number with $\tan \theta=\frac{1}{3}$ is $x+y i=3+1 i$. Similarly, $4+1 i$ has argument $\arctan \frac{1}{4}$, $5+1 i$ has argument $\arctan \frac{1}{5}$, and $n+1 i$ has argument $\arctan \frac{1}{n}$. The argument of the product
$$(3+i)(4+i)(5+i)(n+i)$$
is equal to the sum of the arguments of these four complex numbers. From the expressions we just found for the arguments of these four numbers, we see that the argument of this product is
$$\arctan \frac{1}{3}+\arctan \frac{1}{4}+\arctan \frac{1}{5}+\arctan \frac{1}{n}$$
which we are given is equal to $\frac{\pi}{4}$. Since the argument of $(3+i)(4+i)(5+i)(n+i)$ equals $\frac{\pi}{4}$, and $\cos \frac{\pi}{4}=\sin \frac{\pi}{4}$, the real and imaginary parts of the product must be equal positive numbers. Expanding the product gives
$$\begin{aligned}
(3+i)(4+i)(5+i)(n+i) & =(11+7 i)(5+i)(n+i) \\
& =(48+46 i)(n+i) \\
& =(48 n-46)+(48+46 n) i
\end{aligned}$$

232

---

<!-- Page 233 -->

7.3. ROOTS OF UNITY

We therefore have $48 n-46=48+46 n$, from which we find $n=47$.

Exercises
7.2.1 Express each of the following in exponential form:
(a) $-32 i$
(c) $-\frac{\sqrt{2}}{6}+\frac{\sqrt{2}}{6} i$
(b) $-8+8 i \sqrt{3}$
(d) $2 \sqrt{15}+2 i \sqrt{5}$
7.2.2 Express each of the following in rectangular form:
(a) $e^{4 \pi i}$
(c) $e^{-5 \pi i / 3}$
(b) $e^{5 \pi i / 4}$
(d) $e^{17 \pi i / 3}$
7.2.3 Prove that $\sin \theta=\frac{e^{i \theta}-e^{-i \theta}}{2 i}$.
7.2.4 Reproduce the angle difference identities for sine and cosine by expressing $\frac{e^{i x}}{e^{i y}}$ in rectangular form.
7.2.5 Compute the following in your head. (Don't use paper, pencil, pen, or a calculator.)
(a) $\frac{8+8 i}{-3+3 i}$
(b) $\frac{-12-4 i \sqrt{3}}{3+3 i \sqrt{3}}$
7.2.6 Evaluate each of the following:
(a) $(1-i)^{16}$
(b) $(-2 \sqrt{3}+6 i)^{8}$
7.2.7 For what positive integers $n$ is $(-3+i \sqrt{3})^{n}$ a real number?
7.2.8 Show that $e^{i \alpha}+e^{i \beta}=2 \cos \left(\frac{\alpha-\beta}{2}\right) e^{i(\alpha+\beta) / 2}$.
7.3 Roots of Unity

In this section, we focus on the roots of a special class of polynomials, those of the form
$$f(x)=x^{n}-1,$$
where $n$ is a positive integer. The roots of such a polynomial are called the $n^{\text {th }}$ roots of unity. We call these the roots of unity because finding the roots of $x^{n}-1$ is equivalent to finding those numbers whose $n^{\text {th }}$ power is 1 . Obviously, 1 is one of these roots, but if $n>1$, then there are other roots of $f$, as well. We explore these other roots in this section because they appear in so many areas of mathematics.

Problems
Problem 7.18: Find the roots of each of the following polynomials in rectangular and exponential forms. Plot the roots of each on the complex plane.
(a) $f(x)=x^{3}-1$
(b) $g(x)=x^{4}-1$
(c) $h(x)=x^{6}-1$

233

---

<!-- Page 234 -->

CHAPTER 7. TRIGONOMETRY AND COMPLEX NUMBERS

Problem 7.19: In this problem, we find the roots of $f(x)=x^{5}-1$.
(a) How many roots does $f$ have? Why is it difficult to find the roots of $f$ using the techniques you used in the previous problem?
(b) Let $t=r e^{i \theta}$. If $f(t)=0$, then what is $r$ ?
(c) If $f(t)=0$, then what are the possible values of $t$ ?

Problem 7.20: Let $n$ be a positive integer. What are the roots of $f(x)=x^{n}-1$ ? If we plot the roots in the complex plane, then they are the vertices of what type of figure?

Problem 7.21: Suppose $\omega$ is a root of $f(z)=z^{n}-1$. Which of the following must also be a root of $f(z)$ ?
(a) $\bar{\omega}$
(b) $\omega-1$
(c) $\frac{1}{\omega}$

Problem 7.22: In this problem, we extend our understanding of the roots of unity to find the roots of other complex numbers.
(a) At most how many different complex numbers have fourth powers equal to $-8-8 i \sqrt{3}$ ?
(b) Find all complex numbers whose fourth power is $-8-8 i \sqrt{3}$. Plot all of them in the complex plane.
(c) How are your answers to part (b) related to the fourth roots of unity?
(d) Let $x=r e^{i \theta}$. How are the $n^{\text {th }}$ roots of $x$ related to the $n^{\text {th }}$ roots of unity?

Problem 7.23: An $n^{\text {th }}$ root of unity, $z$, is called a primitive $n^{\text {th }}$ root of unity if $z^{n}=1$ and $z^{k} \neq 1$ for $k= 1,2,3, \ldots, n-1$. For example, -1 is a primitive square root of unity, since $(-1)^{2}=1$, but $(-1)^{1} \neq 1$.
(a) Find the primitive cube roots of unity.
(b) Find the primitive fourth roots of unity.
(c) Find the primitive sixth roots of unity.
(d) Let $n$ be a positive integer greater than 1 . Prove that $e^{2 \pi i / n}$ is a primitive $n^{\text {th }}$ root of unity.

Problem 7.24: Is $e^{6 \pi i / 5}$ a primitive fifth root of unity?
Problem 7.25: Let $\omega=e^{2 \pi k i / n}$, where $k$ is a positive integer, be an $n^{\text {th }}$ root of unity.
(a) Show that if $\operatorname{gcd}(k, n)=1$, then $\omega$ is a primitive $n^{\text {th }}$ root of unity.
(b) Show that if $\operatorname{gcd}(k, n) \neq 1$, then $\omega$ is not a primitive $n^{\text {th }}$ root of unity.
(c) Let $a$ and $b$ be positive integers such that $0<b<a<n$. Show that if $\omega$ is a primitive $n^{\text {th }}$ root of unity, then it is impossible to have $\omega^{a}=\omega^{b}$. Why does this show that the first $n-1$ powers of $\omega$ are the $n-1 n^{\text {th }}$ roots of unity besides 1 ?

Problem 7.18: Find the roots of each of the following polynomials in rectangular and exponential forms. Plot the roots of each on the complex plane.
(a) $f(x)=x^{3}-1$
(b) $g(x)=x^{4}-1$
(c) $h(x)=x^{6}-1$

234

---

<!-- Page 235 -->

7.3. ROOTS OF UNITY

Solution for Problem 7.18:
(a) Factoring $x^{3}-1$ as a difference of cubes, we have $f(x)=(x-1)\left(x^{2}+x+1\right)$. (We also could have noticed that $f(1)=0$, so $x-1$ is a factor of $f$.) Therefore, 1 is a root of $f$, and so are the roots of the quadratic $x^{2}+x+1$. Applying the quadratic formula gives us the roots $x=\frac{-1 \pm i \sqrt{3}}{2}$. So, the roots in rectangular form are $1,-\frac{1}{2}+\frac{\sqrt{3}}{2} i,-\frac{1}{2}-\frac{\sqrt{3}}{2} i$, and in exponential form, they are $e^{0}, e^{2 \pi i / 3}, e^{4 \pi i / 3}$. Since the magnitude of each root is 1 , we can plot each by plotting the terminal point of the angle of the exponential form of the root. Connecting the three points produces an equilateral triangle.
(b) Factoring $x^{4}-1$ as a difference of squares gives $\left(x^{2}-1\right)\left(x^{2}+1\right)$. The roots of $x^{2}-1$ are 1 and -1 , and the roots of $x^{2}+1$ are $i$ and $-i$, so the roots of $f(x)$ in rectangular form are $1, i,-1,-i$. In exponential form, these roots are $e^{0}, e^{\pi i / 2}, e^{\pi i}, e^{3 \pi i / 2}$. Again, the magnitude of each root is 1 , so we can plot each root by locating the terminal point of its angle in exponential form. As shown at right, plotting the roots on the complex plane produces the vertices of a square.
(c) Factoring $x^{6}-1$ as a difference of squares gives $\left(x^{3}-1\right)\left(x^{3}+1\right)$. Factoring each of these as a difference or sum of cubes gives us
$$f(x)=x^{6}-1=\left(x^{3}-1\right)\left(x^{3}+1\right)=(x-1)\left(x^{2}+x+1\right)(x+1)\left(x^{2}-x+1\right) .$$

So, 1 and -1 are roots of $f$, and applying the quadratic formula to the two quadratics tells us that the following are the roots of $f$ in rectangular form:
$$1, \frac{-1+i \sqrt{3}}{2}, \frac{-1-i \sqrt{3}}{2},-1, \frac{1+i \sqrt{3}}{2}, \frac{1-i \sqrt{3}}{2} .$$

In exponential form, these are
$$e^{0}, e^{2 \pi i / 3}, e^{4 \pi i / 3}, e^{\pi i}, e^{\pi i / 3}, e^{5 \pi i / 3} .$$

Putting these in order by increasing argument (angle), we have
$$e^{0}, e^{\pi i / 3}, e^{2 \pi i / 3}, e^{\pi i}, e^{4 \pi i / 3}, e^{5 \pi i / 3} .$$

Each argument is $\pi / 3$ more than the previous, and we aren't surprised to find that these roots are evenly spaced about the unit circle. Connecting them in this order gives us a regular hexagon, as shown at right.

Problem 7.19: In this problem, we find the roots of $f(x)=x^{5}-1$.
(a) How many roots does $f$ have? Why is it difficult to find the roots of $f$ using the techniques we used in the previous problem?
(b) Let $t=r e^{i \theta}$. If $f(t)=0$, then what is $r$ ?
(c) If $f(t)=0$, then what are the possible values of $t$ ?

Solution for Problem 7.19:
(a) Because $f$ has degree 5 , it has 5 roots. We can't use the difference of squares or difference of cubes factorizations, but we can see that $f(1)=0$, so 1 is a root. Factoring out $x-1$ gives
$$f(x)=(x-1)\left(x^{4}+x^{3}+x^{2}+x+1\right) .$$

235

---

<!-- Page 236 -->

CHAPTER 7. TRIGONOMETRY AND COMPLEX NUMBERS

Unfortunately, now we're stuck. None of our typical root-finding techniques helps us with $x^{4}+x^{3}+x^{2}+x+1$. We'll have to try something different.
(b) Having seen that all the roots of $x^{3}-1, x^{4}-1$, and $x^{6}-1$ are of the form $e^{i \theta}$, we try to find roots in exponential form. We let $t=r e^{i \theta}$, where $r$ is a nonnegative real number and $t$ is a root of $f$. Since $f(t)=0$, we have $\left(r e^{i \theta}\right)^{5}=1$, or $r^{5} e^{5 i \theta}=1$. The magnitude of the right side is 1 , so the magnitude of the left side must be 1 . Since $r$ is nonnegative, we have $\left|r^{5} e^{5 i \theta}\right|=r^{5}$, so now we have $r^{5}=1$, which means $r=1$. (To see why there are no other nonnegative real numbers such that $r^{5}=1$, note that $r^{5}>1$ if $r>1$ and $r^{5}<1$ if $0 \leq r<1$.)
(c) Since $f(t)=0$ and $t=r e^{i \theta}$ gave us $r^{5} e^{5 i \theta}=1$, and we found that $r=1$, we must have $e^{5 i \theta}=1$. As we saw in Problem 7.12, if $e^{5 i \theta}=1$, then $5 \theta$ must be an integer multiple of $2 \pi$. Therefore, we must have $5 \theta=2 \pi k$ for some integer $k$ in order to have $e^{5 i \theta}=1$. Dividing by 5 gives us $\theta=2 \pi k / 5$, so the roots are of the form $t=e^{2 \pi k i / 5}$. Letting $k$ be each of $0,1,2,3$, and 4 gives us the roots of $f$ :
$$e^{0}, e^{2 \pi i / 5}, e^{4 \pi i / 5}, e^{6 \pi i / 5}, e^{8 \pi i / 5} .$$

Any other integer $k$ just reproduces one of these values. For example, if $k=5$,
then $\theta=2 \pi k / 5=2 \pi$, which produces the same root as $\theta=0$. Similarly, increasing $k$ by 5 always increases $\theta$ by $2 \pi$, which doesn't change $e^{i \theta}$ because $e^{i(\theta+2 \pi)}=e^{i \theta} \cdot e^{2 \pi i}=e^{i \theta} \cdot 1=e^{i \theta}$.

We aren't at all surprised to see that the roots of $f$ are equally spaced around the unit circle, and that connecting them forms a regular pentagon.

Problem 7.20: Let $n$ be a positive integer. What are the roots of $f(x)=x^{n}-1$ ? If we plot the roots in the complex plane, then they are the vertices of what type of figure?

Solution for Problem 7.20: The previous two problems give us a clear guide. We let $t$ be a root of $f(x)$, and write $t$ in exponential form: $t=r e^{i \theta}$, where $r \geq 0$. Since $f(t)=0$, we must have $\left(r e^{i \theta}\right)^{n}=1$, so $r^{n} e^{i n \theta}=1$. This tells us that $\left|r^{n} e^{i n \theta}\right|=1$. Since $r \geq 0$, we have $\left|r^{n} e^{i n \theta}\right|=r^{n}$, so $\left|r^{n} e^{i n \theta}\right|=1$ means that $r^{n}=1$, which gives us $r=1$. (Yes, this should all look familiar-it's exactly the same reasoning we used to find the roots of $x^{5}-1$.)

Since $r=1$, the equation $f(t)=1$ is now $e^{i n \theta}=1$, which means we must have $n \theta=2 \pi k$ for some integer $k$. Dividing by $n$ gives us $\theta=2 \pi k / n$, so our roots are of the form $t=e^{2 k \pi i / n}$. Letting $k$ be each of $0,1,2, \ldots, n-1$ gives us the roots of $f$ :
$$e^{0}, e^{2 \pi i / n}, e^{4 \pi i / n}, e^{6 \pi i / n}, \ldots, e^{2(n-1) \pi i / n},$$

Notice that any other integer $k$ just reproduces one of these values. For example, if $k=n$, then $\theta=2 \pi k / n=2 \pi$, which produces the same root as $\theta=0$. Similarly, increasing $k$ by $n$ always increases $\theta$ by $2 \pi$, which doesn't change $e^{i \theta}$.

These $n$ roots are equally spaced about the unit circle. The angle of each is $2 \pi / n$ from its neighbors, including the roots $e^{0}$ and $e^{2(n-1) \pi i / n}$. Therefore, plotting these $n$ roots on the complex plane produces the vertices of a regular polygon with $n$ sides.

Important: The $n$ roots of
are
$$\begin{array}{c}
f(x)=x^{n}-1 \\
e^{0}, e^{2 \pi i / n}, e^{4 \pi i / n}, e^{6 \pi i / n}, \ldots, e^{2(n-1) \pi i / n}
\end{array}$$

These are also referred to as the $n^{\text {th }}$ roots of unity.

236

---

<!-- Page 237 -->

7.3. ROOTS OF UNITY

Problem 7.21: Suppose $\omega$ is a root of $f(z)=z^{n}-1$. Which of the following must also be a root of $f(z)$ ?
(a) $\bar{\omega}$
(b) $\omega-1$
(c) $\frac{1}{\omega}$

Solution for Problem 7.21:
(a) As we showed on page 212 , if $z$ is a root of a polynomial $f$ with real coefficients, then $\bar{z}$ is also a root $f$. Therefore if $\omega$ is a root of $f(z)=z^{n}-1$, then so is $\bar{\omega}$. In other words, if $\omega$ is an $n^{\text {th }}$ root of unity, then so is $\bar{\omega}$.
(b) We can quickly see that $\omega-1$ is not necessarily a root of $f$ by noting that $\omega=1$ is a root of $f(z)=z^{n}-1$, but this gives $\omega-1=0$, which is clearly not a root of $f$.
(c) Since $\omega^{n}=1$, we have
$$f\left(\frac{1}{\omega}\right)=\left(\frac{1}{\omega}\right)^{n}-1=\frac{1}{\omega^{n}}-1=\frac{1}{1}-1=0 .$$

Therefore, $\frac{1}{\omega}$ is a root of $f$.

Now that we know how to find $n^{\text {th }}$ roots of unity, we can find the $n^{\text {th }}$ roots of other complex numbers.
Problem 7.22:
(a) At most how many different complex numbers have fourth powers equal to $-8-8 i \sqrt{3}$ ?
(b) Find all complex numbers whose fourth power is $-8-8 i \sqrt{3}$. Plot all of them in the complex plane.
(c) How are your answers to part (b) related to the fourth roots of unity?
(d) Let $x=r e^{i \theta}$. How are the $n^{\text {th }}$ roots of $x$ related to the $n^{\text {th }}$ roots of unity?

Solution for Problem 7.22:
(a) We seek the complex numbers $z$ such that $z^{4}=-8-8 i \sqrt{3}$. Rewriting this as $z^{4}+8+8 i \sqrt{3}=0$, we see that we seek the roots of the polynomial $z^{4}+8+8 i \sqrt{3}$. Since this polynomial has degree 4 , it has 4 roots. So, there are no more than 4 different complex numbers whose fourth power is $-8-8 i \sqrt{3}$. (We don't know for sure yet that there are 4 , because we haven't shown that the polynomial doesn't have any repeated roots.)
(b) We found the roots of unity by using the exponential form of complex numbers. Let's try the same here. We let $z=r e^{i \theta}$, where $r \geq 0$, be a solution to the equation $z^{4}=-8-8 i \sqrt{3}$, so we have
$$r^{4} e^{4 i \theta}=-8-8 i \sqrt{3}$$

It's not so clear what to do with that, so we write the right side in exponential form, too. This gives us
$$r^{4} e^{4 i \theta}=16\left(-\frac{1}{2}-\frac{\sqrt{3}}{2} i\right)=16 e^{4 \pi i / 3} .$$

Comparing the magnitudes of both sides of $r^{4} e^{4 i \theta}=16 e^{4 \pi i / 3}$ gives us $r^{4}=16$, which gives us $r=2$ (remember, $r$ is a nonnegative real number). All that's left is to find $\theta$ such that $e^{4 i \theta}=e^{4 \pi i / 3}$. Clearly, $\theta=\frac{\pi}{3}$ works, and gives us the solution $z=r e^{\pi i / 3}=2\left(\frac{1}{2}+\frac{\sqrt{3}}{2} i\right)=1+i \sqrt{3}$; however, we expect to find four solutions, not just one. What are the others?

We find the others by recalling that $e^{i(\alpha+2 \pi)}=e^{i \alpha}$ for all angles $\alpha$. So,
$$e^{4 \pi i / 3}=e^{i[(4 \pi / 3)+2 \pi]}=e^{i[(4 \pi / 3)+4 \pi]}=e^{i[(4 \pi / 3)+6 \pi]}=\cdots$$

237

---

<!-- Page 238 -->

CHAPTER 7. TRIGONOMETRY AND COMPLEX NUMBERS

This means that we can write the equation $e^{4 i \theta}=e^{4 \pi i / 3}$ as $e^{4 i \theta}=e^{i[(4 \pi / 3)+2 \pi k]}$, where $k$ is an integer. From this equation, we have $4 \theta=\frac{4 \pi}{3}+2 \pi k$. Dividing by 4 gives $\theta=\frac{\pi}{3}+\frac{\pi k}{2}$. When $k=0$, we have the first solution we found, $\theta=\frac{\pi}{3}$. Letting $k=1,2,3$ gives $\theta=\frac{5 \pi}{6}, \frac{4 \pi}{3}, \frac{11 \pi}{6}$, respectively. When $k=4$, we have $\theta=\frac{\pi}{3}+2 \pi$, which gives us the same value of $r e^{i \theta}$ that $k=0$ gave us. Similarly, any other value of $k$ reproduces one of the four solutions we have already found, since increasing $k$ by 4 increases $\theta$ by $2 \pi$, which leaves $e^{i \theta}$ unchanged.

Putting our four values of $\theta$ together with $r=2$ gives us the following four numbers whose fourth power is $-8-8 i \sqrt{3}$ :
$$2 e^{\pi i / 3}, 2 e^{5 \pi i / 6}, 2 e^{4 \pi i / 3}, 2 e^{11 \pi i / 6}$$

In rectangular form, these are
$$1+i \sqrt{3},-\sqrt{3}+i,-1-i \sqrt{3}, \sqrt{3}-i .$$

We have plotted these in the complex plane at right. Connecting them forms a square.
(c) Seeing that the four fourth roots of $-8-8 i \sqrt{3}$ are the vertices of a square in the complex plane makes us wonder if these roots are related to the roots of unity. In our solution to part (b), we found the desired values of $\theta$ with the equation $\theta=\frac{\pi}{3}+\frac{\pi k}{2}$. The angles $\frac{\pi k}{2}$ for $k=0,1,2,3$ are the angles of the fourth roots of unity. This allows us to express each of our solutions for $r e^{i \theta}$ in terms of one of the fourth roots of unity:
$$\begin{aligned}
2 e^{(\pi i / 3)+0} & =2 e^{\pi i / 3} \cdot e^{0 i} \\
2 e^{(\pi i / 3)+(\pi i / 2)} & =2 e^{\pi i / 3} \cdot e^{\pi i / 2} \\
2 e^{(\pi i / 3)+(\pi i)} & =2 e^{\pi i / 3} \cdot e^{\pi i} \\
2 e^{(\pi i / 3)+(3 \pi i / 2)} & =2 e^{\pi i / 3} \cdot e^{3 \pi i / 2}
\end{aligned}$$

Aha! To produce the solutions of $z^{4}=16 e^{4 \pi i / 3}$, we multiply each of the fourth roots of unity by $2 e^{\pi i / 3}$.
(d) Part (c) gives us a guide for generating the $n^{\text {th }}$ roots of any complex number $r e^{i \theta}$. First, we find the $n^{\text {th }}$ roots of unity, which are $e^{2 \pi i k / n}$ for $0 \leq k<n$. Next, we note that if $z^{n}=r e^{i \theta}$, then raising both sides to the power $\frac{1}{n}$ gives $z=\sqrt[n]{r} e^{i \theta / n}$ as one solution. We then multiply each of the $n^{\text {th }}$ roots of unity by this number to produce the $n$ roots of $r e^{i \theta}$.

To confirm that this procedure does indeed produce the $n$ values of $z$ such that $z^{n}=r e^{i \theta}$, let $z=\sqrt[n]{r} e^{i \theta / n} \cdot \omega$, where $\omega$ is one of the $n^{\text {th }}$ roots of unity. Since $\omega$ is an $n^{\text {th }}$ root of unity, we have $\omega^{n}=1$, and
$$z^{n}=\left(\sqrt[n]{r} e^{i \theta / n} \cdot \omega\right)^{n}=(\sqrt[n]{r})^{n} \cdot\left(e^{i \theta / n}\right)^{n} \cdot \omega^{n}=r e^{i \theta},$$
so $z$ is indeed one of the $n^{\text {th }}$ roots of $r e^{i \theta}$. Since no two of the $n^{\text {th }}$ roots of unity have the same argument, multiplying each of these by $\sqrt[n]{r} e^{i \theta / n}$ produces $n$ complex numbers that have $n$ different arguments. In other words, no two of these $n$ numbers are the same. Therefore, we have found the $n$ different numbers whose $n^{\text {th }}$ power is $r e^{i \theta}$.

Problem 7.23: An $n^{\text {th }}$ root of unity, $z$, is called a primitive $\boldsymbol{n}^{\text {th }}$ root of unity if $z^{n}=1$ and $z^{k} \neq 1$ for $k=1,2,3, \ldots, n-1$. For example, -1 is a primitive square root of unity, since $(-1)^{2}=1$, but $(-1)^{1} \neq 1$.
(a) Find the primitive cube roots of unity.
(b) Find the primitive fourth roots of unity.
(c) Find the primitive sixth roots of unity.
(d) Let $n$ be a positive integer greater than 1 . Prove that $e^{2 \pi i / n}$ is a primitive $n^{\text {th }}$ root of unity.

238

---

<!-- Page 239 -->

7.3. ROOTS OF UNITY

Solution for Problem 7.23:
(a) By the definition of primitive roots of unity, if $\omega$ is a primitive cube root of unity, then $\omega^{3}=1, \omega \neq 1$, and $\omega^{2} \neq 1$. The three cube roots of unity are $1, e^{2 \pi i / 3}$, and $e^{4 \pi i / 3}$. Clearly the first is not a primitive cube root of unity since we must have $\omega \neq 1$. We check the other two by computing their squares. We have
$$\begin{array}{l}
\left(e^{2 \pi i / 3}\right)^{2}=e^{4 \pi i / 3} \neq 1 \\
\left(e^{4 \pi i / 3}\right)^{2}=e^{8 \pi i / 3} \neq 1
\end{array}$$

Therefore, both $e^{2 \pi i / 3}$ and $e^{4 \pi i / 3}$ are primitive cube roots of unity.
(b) The fourth roots of unity are $1, e^{\pi i / 2}, e^{\pi i}, e^{3 \pi i / 2}$. The first and third are not primitive fourth roots because the first equals 1 and the square of $e^{\pi i}$ is 1 . The other two are primitive fourth roots because for each one, the root, its square, and its cube all do not equal 1 . So, the primitive fourth roots of unity are $e^{\pi i / 2}$ and $e^{3 \pi i / 2}$.
(c) The sixth roots of unity are
$$1, e^{\pi i / 3}, e^{2 \pi i / 3}, e^{\pi i}, e^{4 \pi i / 3}, e^{5 \pi i / 3}$$

The first is not a primitive sixth root. Both $e^{2 \pi i / 3}$ and $e^{4 \pi i / 3}$ are cube roots of unity, so they are not primitive sixth roots. Similarly, $e^{\pi i}$ is a square root of unity, so it's not a primitive sixth root. If $\omega=e^{\pi i / 3}$, then $\omega^{k} \neq 1$ for $1 \leq k \leq 5$ (since $\omega^{k}$ for these values represent the 5 sixth roots of unity besides 1 ). To check the powers of $e^{5 \pi i / 3}$, we let $\omega=e^{5 \pi i / 3}$ and compute the first 5 powers of $\omega$. When the argument of the result is greater than $2 \pi$, we can subtract integer multiples of $2 \pi$ without changing the result. We find:
$$\begin{array}{l}
\omega^{1}=e^{5 \pi i / 3} \\
\omega^{2}=e^{10 \pi i / 3}=e^{4 \pi i / 3} \\
\omega^{3}=e^{15 \pi i / 3}=e^{3 \pi i / 3} \\
\omega^{4}=e^{20 \pi i / 3}=e^{2 \pi i / 3} \\
\omega^{5}=e^{25 \pi i / 3}=e^{1 \pi i / 3}
\end{array}$$

Not only are none of these five powers of $\omega$ equal to 1 , but all five are different. Interesting! We now know that $e^{5 \pi i / 3}$ is a primitive cube root of unity, and we have a clue that we'll investigate in Problem 7.25 for determining which $n^{\text {th }}$ roots of unity are primitive.
(d) In each of the previous parts, we saw that $e^{2 \pi i / n}$ is an $n^{\text {th }}$ root of unity. We can quickly prove that this is always the case by noting that if $\omega=e^{2 \pi i / n}$, then $\omega^{k}=e^{2 \pi k i / n}$. If $0<k<n$, then the argument of $\omega^{k}$ is between, but not equal to, 0 and $2 \pi$. Therefore, $\omega^{k}$ cannot equal 1 . So, we conclude that $\omega=e^{2 \pi i / n}$ is a primitive $n^{\text {th }}$ root of unity.

The first three parts above suggest a pattern regarding which roots are primitive and which are not. When $n=3$, we found that $e^{2 \pi k i / n}$ is a primitive $n^{\text {th }}$ root of unity for $k=1$ and $k=2$. When $n=4$, we found that $e^{2 \pi k i / n}$ is a primitive $n^{\text {th }}$ root of unity for $k=1$ and $k=3$. When $n=6$, we found that $e^{2 \pi k i / n}$ is a primitive $n^{\text {th }}$ root of unity for $k=1$ and $k=5$. We might guess that $e^{2 \pi k i / n}$ is a primitive $n^{\text {th }}$ root of unity if $k=1$ or $k=n-1$, and not a primitive root otherwise. Before we dive into proving that, let's take a look at a fifth root of unity.

Problem 7.24: Is $e^{6 \pi i / 5}$ a primitive fifth root of unity?

Solution for Problem 7.24: We let $\omega=e^{6 \pi i / 5}$ and find the first four powers of $\omega$. As before, we can subtract positive

239

---

<!-- Page 240 -->

CHAPTER 7. TRIGONOMETRY AND COMPLEX NUMBERS

integer multiples of $2 \pi$ from the argument of each result without changing its value:
$$\begin{array}{l}
\omega^{1}=e^{6 \pi i / 5} \\
\omega^{2}=e^{12 \pi i / 5}=e^{2 \pi i / 5} \\
\omega^{3}=e^{18 \pi i / 5}=e^{8 \pi i / 5} \\
\omega^{4}=e^{24 \pi i / 5}=e^{4 \pi i / 5}
\end{array}$$

Since none of these first four powers of $\omega$ equals 1 , but $\omega^{5}=1$, we know that $\omega=e^{6 \pi i / 5}$ is a primitive fifth root of unity. Also, we see that these four powers of $\omega$ produce the four fifth roots of unity besides 1 .

The result of Problem 7.24 disproves our hypothesis that only $e^{2 \pi i / n}$ and $e^{2 \pi(n-1) i / n}$ can be primitive $n^{\text {th }}$ roots of unity, since we found that $e^{2 \pi k i / 5}$ is a primitive fifth root of unity when $k=3$. Back to the drawing board. Let's look back at our results above and see if we can find some other pattern in which of the $n^{\text {th }}$ roots of unity are primitive $n^{\text {th }}$ roots of unity.

In looking over the results of the past two problems, we see that $e^{2 \pi k i / n}$ is a primitive $n^{\text {th }}$ root of unity if $k$ and $n$ have no common divisors besides 1 , and the root is not primitive otherwise. If we test all the eighth and ninth roots of unity, we'll find that this pattern holds. Moreover, we'll see the same pattern we saw when we discovered that the first four powers of $e^{6 \pi i / 5}$ produce the four $5^{\text {th }}$ roots of unity besides 1 , and that the first five powers of $e^{5 \pi i / 3}$ produce the five $6^{\text {th }}$ roots of unity besides 1 . These observations give us a strong clue how to quickly determine which $n^{\text {th }}$ roots of unity are primitive.

Concept: Investigating examples can reveal patterns that help you conjecture and prove general results.

We use the notation $\operatorname{gcd}(p, q)$ to refer to the greatest common divisor of $p$ and $q$.
Problem 7.25: Let $\omega=e^{2 \pi k i / n}$, where $k$ is a positive integer, be an $n^{\text {th }}$ root of unity.
(a) Show that if $\operatorname{gcd}(k, n)=1$, then $\omega$ is a primitive $n^{\text {th }}$ root of unity.
(b) Show that if $\operatorname{gcd}(k, n) \neq 1$, then $\omega$ is not a primitive $n^{\text {th }}$ root of unity.
(c) Let $a$ and $b$ be positive integers such that $0<b<a<n$. Show that if $\omega$ is a primitive $n^{\text {th }}$ root of unity, then it is impossible to have $\omega^{a}=\omega^{b}$. Why does this show that the first $n-1$ powers of $\omega$ are the $n-1 n^{\text {th }}$ roots of unity besides 1 ?

Solution for Problem 7.25:
(a) Suppose that $q$ is a positive integer such that $\omega^{p}=1$, which means $e^{2 \pi k p i / n}=1$. Therefore, $2 \pi k p i / n$ must be an integer multiple of $2 \pi i$, so $k p / n$ is an integer. Since $k$ and $n$ have no common factors besides 1 , the only way $k p / n$ can be an integer is if $n$ divides $p$ evenly. Therefore, we can only have $\omega^{p}=1$ if $p$ is a multiple of $n$. This means that there is no $p$ with $1 \leq p \leq n-1$ such that $\omega^{p}=1$, so $\omega$ is a primitive $n^{\text {th }}$ root of unity.
(b) We start just as in the previous part, with $p$ being a positive integer such that $\omega^{p}=1$, which means $e^{2 \pi k p i / n}=1$. Therefore, $2 \pi k p i / n$ must be an integer multiple of $2 \pi i$, so $k p / n$ is an integer. However, if $\operatorname{gcd}(k, n) \neq 1$, then some factors of $n$ cancel with factors of $k$ in the fraction $k p / n$, which means there is an equivalent fraction with a smaller denominator. When $p$ equals this denominator, the fraction is an integer. Therefore, we can have a value of $p$ smaller than $n$ such that $\omega^{p}=1$.

To make this argument more formal, we can let $d=\operatorname{gcd}(k, n)$. Since $d$ divides $n$ and $k$, we have $n=d t$ and $k=d u$ for some positive integers $t$ and $u$, so $k / n=u / t$. We can now write $\omega$ as $\omega=e^{2 \pi k i / n}=e^{2 \pi u i / t}$. Now, when we raise $\omega$ to the $t$ power, we have:
$$\omega^{t}=\left(e^{2 \pi u i / t}\right)^{t}=e^{2 \pi u i}$$

240

---

<!-- Page 241 -->

7.3. ROOTS OF UNITY

Since $u$ is an integer, we have $e^{2 \pi u i}=1$, which means $\omega^{t}=1$. Moreover, since $n=d t$ and $d>1$, we have $0<t<n$, so $\omega^{t}=1$ tells us that $\omega$ is not a primitive $n^{\text {th }}$ root of unity.
(c) If $\omega^{a}=\omega^{b}$, then dividing both sides by $\omega^{b}$ gives $\omega^{a-b}=1$. Since $\omega^{a-b}=\left(e^{2 \pi k i / n}\right)^{a-b}=e^{2 \pi k(a-b) i / n}$, we must have
$$e^{2 \pi k(a-b) i / n}=1 .$$

Therefore, $2 \pi k(a-b) i / n$ must be an integer multiple of $2 \pi i$, which means $k(a-b) / n$ must be an integer. However, since $\omega$ is a primitive $n^{\text {th }}$ root, we must have $\operatorname{gcd}(k, n)=1$. So, if $k(a-b) / n$ is an integer, then $n$ must divide $a-b$. But we have $0<b<a<n$, which means that $0<a-b<n$, so it is impossible for $n$ to divide $a-b$. We have reached a contradiction, which means that our original assumption, $\omega^{a}=\omega^{b}$, must be false. We conclude that no two of the first $n-1$ powers of $\omega$ are equal.

Moreover, we can conclude that the first $n-1$ powers of any primitive $n^{\text {th }}$ root of unity give us the $n-1 n^{\text {th }}$ roots of unity besides 1 . To see why, we note that because $\omega$ is an $n^{\text {th }}$ root of unity, we have $\omega^{n}=1$, so
$$\left(\omega^{p}\right)^{n}=\omega^{p n}=\left(\omega^{n}\right)^{p}=1^{p}=1,$$
which means $\omega^{p}$ is an $n^{\text {th }}$ root of unity for any $p$. Because $\omega$ is primitive, none of the first $n-1$ powers of $\omega$ equals 1 and no two of the first $n-1$ powers of $\omega$ are equal. Therefore, these first $n-1$ powers of $\omega$ are the $n^{\text {th }}$ roots of unity besides 1 .

Important: For any positive integer $n$ greater than 1 , we have the following:
- The complex numbers
$$e^{0}, e^{2 \pi i / n}, e^{4 \pi i / n}, e^{6 \pi i / n}, \ldots, e^{2(n-1) \pi i / n}$$
are the $n$ different $n^{\text {th }}$ roots of unity.
- If $\operatorname{gcd}(k, n)=1$, then $\omega=e^{2 \pi i k / n}$ is a primitive $n^{\text {th }}$ root of unity, and
$$1, \omega, \omega^{2}, \omega^{3}, \ldots, \omega^{n-1}$$
are all of the $n^{\text {th }}$ roots of unity.

Exercises
7.3.1 Find all $x$ that satisfy $x^{8}=1$. Which solutions are primitive eighth roots of unity?
7.3.2 If the six solutions of $x^{6}=-64$ are written in the form $a+b i$, where $a$ and $b$ are real, then find the product of the solutions with $a>0$. (Source: AHSME)
7.3.3 Let $\omega$ be a sixth root of unity. Find all possible values of $\omega+\omega^{2}$.
7.3.4
(a) Show that each $12^{\text {th }}$ root of unity is a primitive $k^{\text {th }}$ root of unity for some positive integer $k$. What are the possible values of $k$ ?
(b) For each integer $k$ in part (a), count how many $12^{\text {th }}$ roots of unity are primitive $k^{\text {th }}$ roots of unity.
7.3.5 Show that if $\omega$ is a primitive $n^{\text {th }}$ root of unity for $n=2 m$, then $\omega^{2}$ is a primitive $m^{\text {th }}$ root of unity.

241

---

<!-- Page 242 -->

CHAPTER 7. TRIGONOMETRY AND COMPLEX NUMBERS
7.3.6
(a) Let $\alpha$ be a cube root of unity, and let $\beta$ be a fifth root of unity. Prove that $\alpha \beta$ is a $15^{\text {th }}$ root of unity.
(b) Let $\alpha$ be a primitive cube root of unity, and let $\beta$ be a primitive fifth root of unity. Prove that $\alpha \beta$ is a primitive $15^{\text {th }}$ root of unity.
(c) Let $\alpha$ be a primitive fourth root of unity, and let $\beta$ be a primitive sixth root of unity. Is $\alpha \beta$ necessarily a primitive $24^{\text {th }}$ root of unity?
7.3.7 ★ We say that a polynomial is irreducible over the rational numbers if it cannot be factored as the product of polynomials with smaller positive degree and rational coefficients. Find a degree 4 polynomial with leading coefficient 1 and rational coefficients such that the polynomial is irreducible over the rational numbers and all the polynomial's roots are all twelfth roots of unity. (Source: HMMT) Hints: 182
7.4 Problems Involving Roots of Unity

Problems

Problem 7.26: In this problem, we find the roots of the polynomial $f(x)=x^{8}+x^{7}+x^{6}+x^{5}+x^{4}+x^{3}+x^{2}+x+1$.
(a) What kind of series is the expression $x^{8}+x^{7}+x^{6}+x^{5}+x^{4}+x^{3}+x^{2}+x+1$ ?
(b) Viewing $f(x)$ as a series of the type you determined in part (a), find another expression for $f(x)$.
(c) Find the roots of $f(x)$ by determining the values of $x$ for which your expression in part (b) equals 0 . (You can leave your answers in exponential form.)

Problem 7.27: Find the roots of $g(z)=z^{6}+z^{4}+z^{2}+1$.
Problem 7.28: Let $\omega=e^{4 \pi i / 7}$. Evaluate $(2+\omega)\left(2+\omega^{2}\right)\left(2+\omega^{3}\right)\left(2+\omega^{4}\right)\left(2+\omega^{5}\right)\left(2+\omega^{6}\right)$. Hints: 236,252
Problem 7.29: Find all solutions to $z^{6}+z^{4}+z^{3}+z^{2}+1=0$. (Source: AIME) Hints: 263
Problem 7.30: Find the sum of the $n^{\text {th }}$ roots of unity.
Problem 7.31: Let $n$ be a positive integer. In this problem, we evaluate the sum
$$\cos \frac{2 \pi}{2 n+1}+\cos \frac{2 \cdot 2 \pi}{2 n+1}+\cos \frac{3 \cdot 2 \pi}{2 n+1}+\cdots+\cos \frac{n \cdot 2 \pi}{2 n+1}$$
(a) Evaluate the sum $\cos \frac{2 \pi}{m}+\cos \frac{2 \cdot 2 \pi}{m}+\cos \frac{3 \cdot 2 \pi}{m}+\cdots+\cos \frac{m \cdot 2 \pi}{m}$, where $m$ is a positive integer.
(b) Evaluate the sum $\cos \frac{2 \pi}{2 n+1}+\cos \frac{2 \cdot 2 \pi}{2 n+1}+\cos \frac{3 \cdot 2 \pi}{2 n+1}+\cdots+\cos \frac{n \cdot 2 \pi}{2 n+1}$, where $n$ is a positive integer.

Problem 7.32: The equation
$$x^{10}+(13 x-1)^{10}=0$$
has the 10 complex roots $r_{1}, \overline{r_{1}}, r_{2}, \overline{r_{2}}, r_{3}, \overline{r_{3}}, r_{4}, \overline{r_{4}}, r_{5}, \overline{r_{5}}$. Find the value of
$$\frac{1}{r_{1} \overline{r_{1}}}+\frac{1}{r_{2} \overline{r_{2}}}+\frac{1}{r_{3} \overline{r_{3}}}+\frac{1}{r_{4} \overline{r_{4}}}+\frac{1}{r_{5} \overline{r_{5}}}$$
(Source: AIME)

242

---

<!-- Page 243 -->

7.4. PROBLEMS INVOLVING ROOTS OF UNITY

Problem 7.26: Find the roots of the polynomial $f(x)=x^{8}+x^{7}+x^{6}+x^{5}+x^{4}+x^{3}+x^{2}+x+1$.

Solution for Problem 7.26: If we're very experienced with polynomials, we might recognize $f(x)$ as a factor of $x^{9}-1$. But if we don't see this right way, all is not lost. The polynomial $f(x)$ is a geometric series; each term in the sum is produced by multiplying the previous term by a constant ratio. By writing $f(x)$ as
$$f(x)=1+x+x^{2}+x^{3}+x^{4}+x^{5}+x^{6}+x^{7}+x^{8}$$
we see that we can think of $f(x)$ as a geometric series with first term 1 and constant ratio $x$. To simplify this sum, we multiply both sides by $x$, which gives
$$x f(x)=x+x^{2}+x^{3}+x^{4}+x^{5}+x^{6}+x^{7}+x^{8}+x^{9} .$$

Subtracting our equation for $f(x)$ from our equation for $x f(x)$ gives $(x-1) f(x)=x^{9}-1$. What's wrong with this finish:

Bogus Solution: Dividing both sides by $x-1$ gives
$$f(x)=\frac{x^{9}-1}{x-1}$$

If $x^{9}-1=0$, then $f(x)=0$. The solutions to $x^{9}-1=0$ are the ninth roots of unity, so the roots of $f$ are the 9 ninth roots of unity.

Our first clue that this is incorrect is that $f$ has degree 8 , so it must have 8 roots, not 9 . Where we went wrong is that the step from $(x-1) f(x)=x^{9}-1$ to $f(x)=\frac{x^{9}-1}{x-1}$ is only valid if $x \neq 1$. We must have $x \neq 1$ to avoid dividing by 0 . When $x=1$, our original expression for $f(x)$ gives us $f(1)=9$. When $x \neq 1$, we do indeed have $f(x)=\frac{x^{9}-1}{x-1}$, so $f(x)=0$ when $x \neq 1$ and $x^{9}-1=0$. Therefore, the solutions to $f(x)=0$ are the ninth roots of unity except for $x=1$. So, the roots of $f$ are
$$e^{2 \pi i / 9}, e^{4 \pi i / 9}, e^{6 \pi i / 9}, e^{8 \pi i / 9}, e^{10 \pi i / 9}, e^{12 \pi i / 9}, e^{14 \pi i / 9}, e^{16 \pi i / 9} .$$

The key step in the solution to Problem 7.26 was noticing that the polynomial is a geometric series. This observation is particularly useful with polynomials of the form $x^{n}+x^{n-1}+x^{n-2}+\cdots+1$.

Concept: Many problems involving polynomials of the form
$$x^{n}+x^{n-1}+x^{n-2}+\cdots+1$$
can be solved by writing the polynomial in the form
$$\frac{x^{n+1}-1}{x-1}$$
and using our knowledge of roots of unity.

Problem 7.27: Find the roots of $g(z)=z^{6}+z^{4}+z^{2}+1$.

Solution for Problem 7.27: As in Problem 7.26, the polynomial is a geometric series. It doesn't have exactly the same form as the polynomial in Problem 7.26, but hopefully the same strategy will work. Multiplying $g(z)=z^{6}+z^{4}+z^{2}+1$ by $z^{2}$ gives
$$z^{2} g(z)=z^{8}+z^{6}+z^{4}+z^{2} .$$

243

---

<!-- Page 244 -->

CHAPTER 7. TRIGONOMETRY AND COMPLEX NUMBERS

Subtracting the equation for $g(z)$ from this gives $\left(z^{2}-1\right) g(z)=z^{8}-1$. If $z^{2} \neq 1$, then we can divide both sides by $z^{2}-1$ to get
$$g(z)=\frac{z^{8}-1}{z^{2}-1}$$
(We can also use the formula for summing geometric series to reach this expression for $g(z)$.) Therefore, we have $g(z)=0$ if $z^{8}=1$ and $z^{2} \neq 1$, which means that the roots of $g$ are the eighth roots of unity except for 1 and -1 . These are
$$e^{\pi i / 4}, e^{\pi i / 2}, e^{3 \pi i / 4}, e^{5 \pi i / 4}, e^{3 \pi i / 2}, e^{7 \pi i / 4}$$

Problem 7.28: Let $\omega=e^{4 \pi i / 7}$. Evaluate $(2+\omega)\left(2+\omega^{2}\right)\left(2+\omega^{3}\right)\left(2+\omega^{4}\right)\left(2+\omega^{5}\right)\left(2+\omega^{6}\right)$.
Solution for Problem 7.28: First, we recognize that $\omega$ is a seventh root of unity, because $\omega^{7}=\left(e^{4 \pi i / 7}\right)^{7}=e^{4 \pi i}=1$. Moreover, $\omega$ is a primitive seventh root of unity, so $\omega, \omega^{2}, \omega^{3}, \omega^{4}, \omega^{5}$, and $\omega^{6}$ are the six seventh roots of unity besides 1 . But how does that help?

We could multiply the whole desired expression out. That will work, but it will take a fair amount of diligence and patience. Perhaps we can do something clever instead. Where else have we seen a product of binomials involving the seventh roots of unity?

Concept: When working with a difficult expression, think about where else you have seen similar expressions.

We encounter the product of binomials involving the seventh roots of unity in the factored form of $z^{7}-1$ :
$$z^{7}-1=(z-1)\left(z-r_{1}\right)\left(z-r_{2}\right)\left(z-r_{3}\right)\left(z-r_{4}\right)\left(z-r_{5}\right)\left(z-r_{6}\right),$$
where the $r_{i}$ are the seventh roots of unity besides 1 . We've already seen that these roots are $\omega, \omega^{2}, \omega^{3}, \omega^{4}, \omega^{5}$, and $\omega^{6}$ (in some order), so we have
$$z^{7}-1=(z-1)(z-\omega)\left(z-\omega^{2}\right)\left(z-\omega^{3}\right)\left(z-\omega^{4}\right)\left(z-\omega^{5}\right)\left(z-\omega^{6}\right) .$$

Aha! We can make the desired expression appear by letting $z=-2$ :
$$(-2)^{7}-1=(-2-1)(-2-\omega)\left(-2-\omega^{2}\right)\left(-2-\omega^{3}\right)\left(-2-\omega^{4}\right)\left(-2-\omega^{5}\right)\left(-2-\omega^{6}\right) .$$

Factoring -1 out of each of the final six expressions in parentheses gives us
$$-129=-3(-1)^{6}(2+\omega)\left(2+\omega^{2}\right)\left(2+\omega^{3}\right)\left(2+\omega^{4}\right)\left(2+\omega^{5}\right)\left(2+\omega^{6}\right)$$
so
$$(2+\omega)\left(2+\omega^{2}\right)\left(2+\omega^{3}\right)\left(2+\omega^{4}\right)\left(2+\omega^{5}\right)\left(2+\omega^{6}\right)=\frac{129}{3}=43 .$$

Problem 7.29: Find all solutions to $z^{6}+z^{4}+z^{3}+z^{2}+1=0$. (Source: AIME)
Solution for Problem 7.29: If only the $z^{6}$ were just $z$, then we could find the roots easily; the roots of $z^{4}+z^{3}+z^{2}+z+1$ are the fifth roots of unity besides 1 :
$$z^{4}+z^{3}+z^{2}+z+1=\frac{z^{5}-1}{z-1} .$$

244

---

<!-- Page 245 -->

7.4. PROBLEMS INVOLVING ROOTS OF UNITY

Aha! Adding $z^{6}-z$ to both sides makes the left side the polynomial whose roots we seek, and we can factor the right side further:
$$\begin{aligned}
z^{6}+z^{4}+z^{3}+z^{2}+1=\frac{z^{5}-1}{z-1}+z^{6}-z & =\frac{z^{5}-1}{z-1}+z\left(z^{5}-1\right) \\
& =\frac{z^{5}-1+z(z-1)\left(z^{5}-1\right)}{z-1} \\
& =\frac{\left(z^{2}-z+1\right)\left(z^{5}-1\right)}{z-1}
\end{aligned}$$

We can factor $z^{5}-1$ as $(z-1)\left(z^{4}+z^{3}+z^{2}+z+1\right)$. The $z-1$ cancels with the denominator and leaves
$$z^{6}+z^{4}+z^{3}+z^{2}+1=\left(z^{2}-z+1\right)\left(z^{4}+z^{3}+z^{2}+z+1\right) .$$

The roots of $z^{4}+z^{3}+z^{2}+z+1$ are the fifth roots of unity besides 1 . We could use the quadratic formula to find the roots of $z^{2}-z+1$, or we could note that $z^{3}+1=(z+1)\left(z^{2}-z+1\right)$, so the roots of $z^{2}-z+1$ are the nonreal cube roots of -1 . Since $-1=e^{\pi i}$, the nonreal cube roots of -1 are $e^{\pi i / 3}$ and $e^{5 \pi i / 3}$.

Therefore, the solutions to the given equation are $e^{2 \pi i / 5}, e^{4 \pi i / 5}, e^{6 \pi i / 5}, e^{8 \pi i / 5}, e^{\pi i / 3}, e^{5 \pi i / 3}$.

Sidenote: In hindsight, it isn't surprising that the nonreal fifth roots of unity are also roots of $z^{6}+z^{4}+z^{3}+z^{2}+1$. For any fifth root of unity, we have $z^{5}=1$, so $z^{6}=z^{5} \cdot z=z$. Therefore, if $z$ is a nonreal fifth root of unity, we have
$$z^{6}+z^{4}+z^{3}+z^{2}+z+1=z+z^{4}+z^{3}+z^{2}+1,$$
which equals 0 because the nonreal fifth roots of unity are the roots of the polynomial $z^{4}+z^{3}+z^{2}+z+1$.

Problem 7.30: Find the sum of the $n^{\text {th }}$ roots of unity.

Solution for Problem 7.30: First, we write out the sum:
$$e^{0 \pi i / n}+e^{2 \pi i / n}+e^{2 \cdot 2 \pi i / n}+e^{3 \cdot 2 \pi i / n}+e^{4 \cdot 2 \pi i / n}+\cdots+e^{(n-1) \cdot 2 \pi i / n} .$$

Here are two ways to tackle this sum:
Method 1: It's a geometric series! This sum is an $n$-term geometric series with first term $e^{0 \pi i / n}$ and common ratio $e^{2 \pi i / n}$, so its sum is
$$\frac{e^{0 \pi i / n}-e^{0 \pi i / n} \cdot\left(e^{2 \pi i / n}\right)^{n}}{1-e^{2 \pi i / n}}=\frac{1-e^{2 n \pi i / n}}{1-e^{2 \pi i / n}}=\frac{1-e^{2 \pi i}}{1-e^{2 \pi i / n}}=\frac{1-1}{1-e^{2 \pi i / n}}=0 .$$

Method 2: Consider the polynomial $z^{n}-1$. The terms in the sum are the roots of $z^{n}-1$, because they are the $n^{\text {th }}$ roots of unity. We can see that the sum of the roots of this polynomial is 0 by writing the polynomial in the form
$$\left(z-r_{1}\right)\left(z-r_{2}\right)\left(z-r_{3}\right) \cdots\left(z-r_{n}\right)$$
where the $r_{i}$ are the roots of the polynomial. To form each term in the expansion of this product, we choose one of the terms in each binomial, and then take the product of all the chosen terms. The full expansion includes every possible product we can form in this manner. For example, when we take $-r_{1}$ from $z-r_{1}$ and take $z$ from each of the other $n-1$ binomials, we get $-r_{1} z^{n-1}$. Continuing in this way, the only way we can form a term with $z^{n-1}$ is when we take $-r_{i}$ from one factor and $z$ from each of the other $n-1$ factors. Grouping all of these products gives us
$$z^{n-1}\left(-r_{1}-r_{2}-r_{3}-\cdots-r_{n}\right)$$

245

---

<!-- Page 246 -->

CHAPTER 7. TRIGONOMETRY AND COMPLEX NUMBERS

as the $z^{n-1}$ term in the expansion. However, the product $\left(z-r_{1}\right)\left(z-r_{2}\right)\left(z-r_{3}\right) \cdots\left(z-r_{n}\right)$ equals $z^{n}-1$, and there is no $z^{n-1}$ term in the polynomial $z^{n}-1$. Therefore, the coefficient of $z^{n-1}$ in the expansion of $\left(z-r_{1}\right)\left(z-r_{2}\right)\left(z-r_{3}\right) \cdots\left(z-r_{n}\right)$ must be 0 . We just found that this coefficient is the opposite of the sum of the roots, so the sum of the roots is 0 .

Sidenote: It's not just the sum of the roots that we can quickly determine from the coefficients of a polynomial. Consider the expansion of the product
$$\left(z-r_{1}\right)\left(z-r_{2}\right)\left(z-r_{3}\right) \cdots\left(z-r_{n}\right)$$

The highest degree term is $z^{n}$. As just explained, the coefficient of the $z^{n-1}$ term in the expansion is $-\left(r_{1}+r_{2}+r_{3}+\cdots+r_{n}\right)$. But what about the $z^{n-2}$ term in the expansion?

To form $a z^{n-2}$ term, we can take $-r_{1}$ and $-r_{2}$ from the first two factors, and $z$ from the other $n-2$ factors, which gives us $r_{1} r_{2} z^{n-2}$. We can do similarly to form every possible term $r_{i} r_{j} z^{n-2}$ with $i \neq j$, so the $z^{n-2}$ term in the expansion is
$$\left(r_{1} r_{2}+r_{1} r_{3}+r_{1} r_{4}+\cdots+r_{n-1} r_{n}\right) z^{n-2}$$

Therefore, the coefficient of $z^{n-2}$ is the sum of all possible pairs of roots.
The coefficient of $z^{n-1}$ is $(-1)^{1}$ times the sum of the roots. The coefficient of $z^{n-2}$ is $(-1)^{2}$ times the sum of all possible products of two of the roots. Continuing in this vein, we can show that the coefficient of $z^{n-3}$ is $(-1)^{3}$ times the sum of all possible products of three of the roots, $z^{n-4}$ is $(-1)^{4}$ times the sum of all possible products of four of the roots, and so on.

These relationships are often referred to as Vieta's formulas, and they are covered extensively in Art of Problem Solving's Intermediate Algebra book.

Problem 7.31: Evaluate the sum $\cos \frac{2 \pi}{2 n+1}+\cos \frac{2 \cdot 2 \pi}{2 n+1}+\cos \frac{3 \cdot 2 \pi}{2 n+1}+\cdots+\cos \frac{n \cdot 2 \pi}{2 n+1}$, where $n$ is a positive integer.

Solution for Problem 7.31: The sum consists of terms of the form $\cos \frac{k \cdot 2 \pi}{2 n+1}$. These are the real parts of some of the $(2 n+1)^{\text {th }}$ roots of unity.

Concept: Problems involving the real or imaginary parts of roots of unity can often be
solved using complex numbers, so keep an eye out for cosines or sines that are the real or imaginary parts of roots of unity.

The given sum has the real parts of only $n$ of the $(2 n+1)^{\text {th }}$ roots of unity. It's not clear how to handle such a sum, so we first look at a simpler problem.

Concept: We can often get hints for how to tackle a hard problem by first tackling a simpler version of the problem.

One simpler version of the problem is to consider the real parts of all the $m^{\text {th }}$ roots of unity:
$$\cos \frac{2 \pi}{m}+\cos \frac{2 \cdot 2 \pi}{m}+\cos \frac{3 \cdot 2 \pi}{m}+\cdots+\cos \frac{m \cdot 2 \pi}{m} .$$

While we haven't tackled a sum like this, we have tackled a closely related sum—the sum of the $n^{\text {th }}$ roots of unity themselves. We just showed that the sum of the $m^{\text {th }}$ roots of unity is 0 . Therefore, the sum of the real parts of the

246

---

<!-- Page 247 -->

7.4. PROBLEMS INVOLVING ROOTS OF UNITY

$m^{\text {th }}$ roots of unity is also 0 (and so is the sum of the imaginary parts). This gives us
$$\cos \frac{2 \pi}{m}+\cos \frac{2 \cdot 2 \pi}{m}+\cos \frac{3 \cdot 2 \pi}{m}+\cdots+\cos \frac{m \cdot 2 \pi}{m}=0$$

How does this help us with our original problem? Letting $m=2 n+1$ in the equation above produces
$$\cos \frac{2 \pi}{2 n+1}+\cos \frac{2 \cdot 2 \pi}{2 n+1}+\cos \frac{3 \cdot 2 \pi}{2 n+1}+\cdots+\cos \frac{(2 n+1) \cdot 2 \pi}{2 n+1}=0$$

This contains all the terms in the desired sum, plus a bunch more terms:
$$\underbrace{\cos \frac{2 \pi}{2 n+1}+\cos \frac{2 \cdot 2 \pi}{2 n+1}+\cdots+\cos \frac{n \cdot 2 \pi}{2 n+1}}_{\text {Desired sum }}+\underbrace{\cos \frac{(n+1) \cdot 2 \pi}{2 n+1}+\cos \frac{(n+2) \cdot 2 \pi}{2 n+1}+\cdots+\cos \frac{(2 n+1) \cdot 2 \pi}{2 n+1}}_{\text {Extra terms }}=0 .$$

We do at least know how to handle one of the extra terms: the last one simplifies to $\cos 2 \pi$, which is 1 . But what about the rest?

Here are two methods for tackling the rest of terms and finishing the problem:
Method 1: Pair up the angles in the sum. We can often handle complicated sums (or products) of trig expressions by exploiting relationships among the angles in the terms. Here, we can pair each angle in the desired sum with an angle in the "extra terms" such that the sum of the angles is $2 \pi$. For example, $\frac{2 \pi}{2 n+1}+\frac{(2 n) \cdot 2 \pi}{2 n+1}=\frac{(2 n+1) \cdot 2 \pi}{2 n+1}=2 \pi$. Since $\cos (2 \pi-\theta)=\cos \theta$, we have
$$\cos \frac{(n+1) \cdot 2 \pi}{2 n+1}+\cos \frac{(n+2) \cdot 2 \pi}{2 n+1}+\cdots+\cos \frac{(2 n) \cdot 2 \pi}{2 n+1}=\cos \frac{(n) \cdot 2 \pi}{2 n+1}+\cos \frac{(n-1) \cdot 2 \pi}{2 n+1}+\cdots+\cos \frac{1 \cdot 2 \pi}{2 n+1}$$

Hence, we can now write Equation (7.1) as
$$2\left(\cos \frac{2 \pi}{2 n+1}+\cos \frac{2 \cdot 2 \pi}{2 n+1}+\cdots+\cos \frac{n \cdot 2 \pi}{2 n+1}\right)+1=0$$
from which we see that the desired sum equals $-\frac{1}{2}$.
Method 2: Geometry. We can visualize the $(2 n+1)^{\text {th }}$ roots of unity as points equally spaced on the circumference of the unit circle, starting with the root at 1 , as shown at right. The picture tells the story. The roots above the $x$-axis correspond to the terms in the desired sum. The roots on and below the $x$-axis are the "extra terms." The roots below the $x$-axis are the reflections of the "desired" roots over the $x$-axis, so the real part of each of these roots equals the real part of one of the "desired" roots. Therefore, the sum of the real parts of all the roots is twice the desired sum plus 1 . Since the sum of the real parts of all of the roots must equal 0 , we conclude that the desired sum is $-\frac{1}{2}$.

Problem 7.32: The equation
$$x^{10}+(13 x-1)^{10}=0$$
has the 10 complex roots $r_{1}, \overline{r_{1}}, r_{2}, \overline{r_{2}}, r_{3}, \overline{r_{3}}, r_{4}, \overline{r_{4}}, r_{5}, \overline{r_{5}}$. Find the value of
$$\frac{1}{r_{1} \overline{r_{1}}}+\frac{1}{r_{2} \overline{r_{2}}}+\frac{1}{r_{3} \overline{r_{3}}}+\frac{1}{r_{4} \overline{r_{4}}}+\frac{1}{r_{5} \overline{r_{5}}}$$
(Source: AIME)

247

---

<!-- Page 248 -->

CHAPTER 7. TRIGONOMETRY AND COMPLEX NUMBERS

Solution for Problem 7.32: We sure don't want to multiply out $(13 x-1)^{10}$. Perhaps we can rewrite the equation in a more convenient form. Subtracting $(13 x-1)^{10}$ from both sides gives
$$x^{10}=-(13 x-1)^{10}$$

This is close to an equation we know how to solve. We know what to do with $x^{10}=1$, and what to do with $x^{10}=c$ for some constant $c$. While we're not so sure what to do with $x^{10}$ equal to an expression, we can rewrite this equation as the tenth power of an expression equal to a constant by dividing both sides of $x^{10}=-(13 x-1)^{10}$ by $(13 x-1)^{10}$, which gives
$$\left(\frac{x}{13 x-1}\right)^{10}=-1 .$$
(Note that we can take this step without worrying about dividing by 0 because $x=1 / 13$ is clearly not a solution to $x^{10}=-(13 x-1)^{10}$, since $x=1 / 13$ makes the right side 0 and the left side nonzero.)

Now, we have an equation that's a lot more familiar.

Concept: A great many equations can be solved by manipulating the equation into a form you already know how to tackle.

To make this equation exactly like an equation we have solved before, we can let $t=\frac{x}{13 x-1}$, so our equation is simply $t^{10}=-1$. We can now use Problem 7.22 as a guide to find $t$. We have $t^{10}=-1=e^{\pi i}$, so the 10 solutions for $t$ are $e^{\pi i / 10}$ times each of the tenth roots of unity. Since we can express each tenth root of unity as $e^{2 \pi k i / 10}$ for some integer $k$ with $0 \leq k<10$, each solution for $t$ has the form $t=e^{\pi i / 10} \cdot e^{2 \pi k i / 10}=e^{(2 k+1) \pi i / 10}$ for some integer $k$.

We now must find $x$ in terms of $t$. Multiplying both sides of $t=\frac{x}{13 x-1}$ by $13 x-1$ gives $13 t x-t=x$, so $x=\frac{t}{13 t-1}$. Therefore,
$$x=\frac{t}{13 t-1}=\frac{e^{(2 k+1) \pi i / 10}}{13 e^{(2 k+1) \pi i / 10}-1}$$
is a solution of the given equation for any integer $k$.
That's not a pretty expression, but we aren't asked for the solutions of the original equation-we must evaluate an expression in terms of these solutions. Hopefully, once we plug these solutions into the desired expression, something convenient will happen. Let's try the first term in the desired expression, $\frac{1}{r_{1} \overline{r_{1}}}$. If $r_{1}=\frac{t}{13 t-1}$ is one solution, then
$$\begin{aligned}
\frac{1}{r_{1} \overline{r_{1}}}=\frac{1}{r_{1}} \cdot \overline{\left(\frac{1}{r_{1}}\right)} & =\left(\frac{13 t-1}{t}\right) \overline{\left(\frac{13 t-1}{t}\right)} \\
& =\left(\frac{13 t-1}{t}\right)\left(\frac{13 \bar{t}-1}{\bar{t}}\right) \\
& =\frac{(13 t-1)(13 \bar{t}-1)}{t \bar{t}} \\
& =\frac{169 t \bar{t}-13 t-13 \bar{t}+1}{t \bar{t}} .
\end{aligned}$$

Before we substitute for $t$, we notice that $t \bar{t}=|t|^{2}=1$ because $t=e^{(2 k+1) \pi i / 10}$ and $\left|e^{i \theta}\right|=1$ for any angle $\theta$. Therefore, we have
$$\frac{1}{r_{1} \overline{r_{1}}}=\frac{169 t \bar{t}-13 t-13 \bar{t}+1}{t \bar{t}}=\frac{169-13(t+\bar{t})+1}{1}=170-13(t+\bar{t}) .$$

Since $\bar{t}=\overline{e^{(2 k+1) \pi i / 10}}=e^{-(2 k+1) \pi i / 10}$, we have
$$\frac{1}{r_{1} \overline{r_{1}}}=170-13\left(e^{(2 k+1) \pi i / 10}+e^{-(2 k+1) \pi i / 10}\right) .$$

248

---

<!-- Page 249 -->

7.4. PROBLEMS INVOLVING ROOTS OF UNITY

We still have two exponentials in this expression, but their exponents are opposites. We've seen this before, back in Problem 7.16, where we showed that $\cos \theta=\left(e^{i \theta}+e^{-i \theta}\right) / 2$. So, we have $e^{i \theta}+e^{-i \theta}=2 \cos \theta$. Applying this to our expression above gives us
$$\frac{1}{r_{1} \overline{r_{1}}}=170-13\left(e^{(2 k+1) \pi i / 10}+e^{-(2 k+1) \pi i / 10}\right)=170-26 \cos \left(\frac{(2 k+1) \pi}{10}\right) .$$

This expression has 5 different possible values, one for each of $k=0,1,2,3$, and 4 . When $k=5$, we have $\cos \left(\frac{(2 k+1) \pi}{10}\right)=\cos \frac{11 \pi}{10}$, which equals $\cos \frac{9 \pi}{10}$, so our expression for $\frac{1}{r_{1} \overline{r_{1}}}$ is the same for $k=5$ as it is for $k=4$. Similarly, every integer $k$ gives us a value of our expression $\frac{1}{r_{1} \overline{r_{1}}}$ that equals one of the 5 values we find for $k=0,1,2,3$, or 4 .

Since there is a solution to $x^{10}+(13 x-1)^{10}=0$ of the form $x=e^{(2 k+1) \pi i / 10} /\left(13 e^{(2 k+1) \pi i / 10}-1\right)$ for each of the tenth roots of unity, we know that among the five terms of the form $\frac{1}{r_{1} \overline{r_{1}}}$, each of the 5 possible values of $170-26 \cos \left(\frac{(2 k+1) \pi}{10}\right)$ occurs. Therefore, our desired sum equals
$$5(170)-26\left(\cos \frac{\pi}{10}+\cos \frac{3 \pi}{10}+\cos \frac{5 \pi}{10}+\cos \frac{7 \pi}{10}+\cos \frac{9 \pi}{10}\right) .$$

We're almost there! We have $\cos \frac{5 \pi}{10}=\cos \frac{\pi}{2}=0$. The other two cosines can be grouped in pairs whose angles sum to $\pi$, which reminds us that $\cos x=-\cos (\pi-x)$. So, we have $\cos \frac{\pi}{10}+\cos \frac{9 \pi}{10}=\cos \frac{3 \pi}{10}+\cos \frac{7 \pi}{10}=0$. Therefore, the sum of cosines in our expression for the desired sum is 0 , so the sum equals $5(170)=850$.

Exercises
7.4.1
(a) Find the roots of $z^{2}-z+1$ in exponential form.
(b) Find the roots of $z^{5}+1$ in exponential form.
(c) Find a degree 4 polynomial whose roots are the nonreal roots you found in part (b).
(d) Find the roots of $x^{6}-x^{5}+x^{4}-x^{3}+x^{2}-x+1$. (You can leave your answers in exponential form.)
7.4.2 Let $\omega$ be a $13^{\text {th }}$ root of unity. Evaluate $(1-\omega)\left(1-\omega^{2}\right) \cdots\left(1-\omega^{12}\right)$.
7.4.3 Let $z$ be such that $z^{7}=1$ and $z \neq 1$. Compute the numerical value of
$$z^{10}+\frac{1}{z^{10}}+z^{30}+\frac{1}{z^{30}}+z^{50}+\frac{1}{z^{50}}$$
(Source: NYSML)
7.4.4 The nonzero complex numbers $a, b$, and $c$ satisfy $\frac{a}{b}=\frac{b}{c}=\frac{c}{a}$. What are the possible values of $\frac{a+b-c}{a-b+c}$ ?
7.4.5 Factor $x^{7}+x^{4}+x^{3}+x+1$ into the product of two polynomials with integer coefficients and positive degrees.
7.4.6★ The polynomial
$$P(x)=\left(1+x+x^{2}+\cdots+x^{17}\right)^{2}-x^{17}$$
has 34 roots of the form $z_{k}=r_{k}\left[\cos \left(2 \pi \alpha_{k}\right)+i \sin \left(2 \pi \alpha_{k}\right)\right], k=1,2, \ldots, 34$, with $0<\alpha_{1} \leq \alpha_{2} \leq \alpha_{3} \leq \cdots \leq \alpha_{34}<1$ and $r_{k}>0$. Find $\alpha_{1}+\alpha_{2}+\alpha_{3}+\alpha_{4}+\alpha_{5}$. (Source: AIME) Hints: 209,58

249

---

<!-- Page 250 -->

CHAPTER 7. TRIGONOMETRY AND COMPLEX NUMBERS
7.5 Summary

The form $x+y i$ is the rectangular form of a complex number. A complex number can also be written in the polar form $r(\cos \theta+i \sin \theta)$ or the exponential form $r e^{i \theta}$. We typically have $r \geq 0$ in polar and exponential form, so that $r$ is the magnitude of the complex number. The $\theta$ in polar and exponential form is called the argument of the complex number. The rectangular form of a complex number is related to the polar and exponential forms by $x=r \cos \theta, y=r \sin \theta$, so $r^{2}=x^{2}+y^{2}$ and $\tan \theta=\frac{y}{x}$ (when $\cos \theta$ is nonzero).

\begin{tabular}{|l|l|}
\hline Important: (1) & For any angle $\theta$, we have
$$\begin{array}{l}
\cos \theta=\frac{e^{i \theta}+e^{-i \theta}}{2} \\
\sin \theta=\frac{e^{i \theta}-e^{-i \theta}}{2 i}
\end{array}$$ \\
\hline
\end{tabular}

\begin{tabular}{|l|l|}
\hline Important: (1) & \begin{tabular}{l}
The $n$ roots of $f(x)=x^{n}-1$ are
$$e^{0}, e^{2 \pi i / n}, e^{4 \pi i / n}, e^{6 \pi i / n}, \ldots, e^{2(n-1) \pi i / n} .$$ \\
These are also referred to as the $\boldsymbol{n}^{\text {th }}$ roots of unity, since these are the $n$ complex numbers whose $n^{\text {th }}$ power is 1 .
\end{tabular} \\
\hline
\end{tabular}
$$\begin{array}{l}
\text { Important: } \\
\text { An } n^{\text {th }} \text { root of unity, } z, \text { is called a primitive } n^{\text {th }} \text { root of unity if } z^{n}=1 \text { and } z^{k} \neq 1 \\
\text { for } k=1,2,3, \ldots, n-1 . \text { If } \operatorname{gcd}(k, n)=1, \text { then } \omega=e^{2 \pi i k / n} \text { is a primitive } n^{\text {th }} \text { root of } \\
\text { unity, and } 1, \omega, \omega^{2}, \omega^{3}, \ldots, \omega^{n-1} \text { are all of the } n^{\text {th }} \text { roots of unity. }
\end{array}$$

Things To Watch Out For! 
We always use radians in exponential notation, never degrees.

Problem Solving Strategies 

Concepts: - Investigating examples can reveal patterns that help conjecture and prove general results.
- When working with a difficult expression, think about where else you have seen similar expressions.

250

---

<!-- Page 251 -->

REVIEW PROBLEMS

Concepts:
- We can often get hints for how to tackle a hard problem by first tackling a simpler version of the problem.
- A great many equations can be solved by manipulating the equation into a form you already know how to tackle.
- De Moivre's Theorem can help us tackle problems involving $\cos n \theta$ or $\sin n \theta$, where $n$ is a positive integer greater than 1 .
- Exponential form sometimes offers an easy way to prove facts involving complex number multiplication.
- The exponential form of complex numbers is a helpful way to remember trigonometric identities.
- Many problems involving polynomials of the form $x^{n}+x^{n-1}+x^{n-2}+\cdots+1$ can be solved by writing the polynomial in the form $\frac{x^{n+1}-1}{x-1}$, and using our knowledge of the roots of unity.
- Problems involving the real or imaginary parts of roots of unity can often be solved using complex numbers, so keep an eye out for cosines or sines that are the real or imaginary parts of roots of unity.

Review Problems
7.33 Write each of the following in polar form:
(a) -9
(c) $8+8 i$
(b) $\quad \sqrt{6}+\sqrt{2} i$
(d) $-\frac{1}{2}-\frac{1}{2} i$
7.34 Write each of the following in rectangular form:
(a) $4 \mathrm{cis} 120^{\circ}$
(c) $8 \operatorname{cis} \frac{\pi}{6}$
(b) $\quad \frac{1}{2} \mathrm{cis} 315^{\circ}$
(d) $20 \operatorname{cis} 97 \pi$
7.35 For what values of $\theta$ does $\operatorname{cis} \theta=\operatorname{cis} 2 \theta$ ?
7.36 Determine all integer values of $\theta$ with $0^{\circ} \leq \theta \leq 90^{\circ}$ for which $(\cos \theta+i \sin \theta)^{75}$ is a real number. (Source: ARML)
7.37 Express each of the following in exponential form:
(a) $24-24 i$
(b) $\frac{4 \sqrt{3}}{3}+4 i$
7.38 Express each of the following in rectangular form:
(a) $e^{3 \pi i / 2}$
(b) $6 e^{7 \pi i / 6}$
7.39 Use the fact that $e^{-i \theta}=\frac{1}{e^{i \theta}}$ to reproduce the identities for $\sin (-\theta)$ and $\cos (-\theta)$.
7.40 Describe all complex numbers $z$ such that $\left|\frac{z}{\bar{z}}+\frac{\bar{z}}{z}\right|=\sqrt{3}$.

251

---

<!-- Page 252 -->

CHAPTER 7. TRIGONOMETRY AND COMPLEX NUMBERS
7.41 Evaluate each of the following:
(a) $\left(\frac{\sqrt{3}}{4}-\frac{1}{4} i\right)^{8}$
(b) $\quad \frac{(-3 \sqrt{3}-3 i)^{8}}{(1+\sqrt{3} i)^{6}}$
7.42
(a) Express $\sin 5 \theta$ in terms of $\sin \theta$.
(b) Show that $\sin 4 \theta$ cannot be expressed as a function of $\sin \theta$.
7.43 If $w \cdot z$ is a nonzero real number and $|w|=|z|$, then which of the following is true:
(a) $w+z$ is real.
(b) $w+z$ is either real or pure imaginary.
(c) It is possible that $w+z$ is neither real nor pure imaginary.
7.44 Find all solutions to $z^{3}=-4 \sqrt{2}+4 \sqrt{2} i$ in exponential form.
7.45 Let $z=e^{i \theta}$, where $z \neq 1$. Show that $\frac{1+z}{1-z}=i \cot \frac{\theta}{2}$.
7.46
(a) Find the product of the $n^{\text {th }}$ roots of unity.
(b) Find the product of the primitive $n^{\text {th }}$ roots of unity.
7.47 Let $n$ be a positive integer. How are the roots of $x^{2 n+1}+1$ related to the roots of $x^{2 n+1}-1$
(a) algebraically?
(b) geometrically, in the complex plane?
7.48 Let $w$ be a nonzero complex number. Suppose the solutions to the equation $z^{n}=w$ are graphed in the complex plane. Prove that the resulting points are vertices of a regular $n$-gon.
7.49 Let $x_{n}+i y_{n}=(1+i \sqrt{3})^{n}$, where $x_{n}$ and $y_{n}$ are real and $n$ is a positive integer. If $x_{19} y_{91}+x_{91} y_{19}=2^{k} \sqrt{3}$, compute $k$. (Source: ARML)
7.50 Show that $\overline{e^{z}}=e^{\bar{z}}$ for all complex numbers $z$.
7.51 The hyperbolic sine, hyperbolic cosine, and hyperbolic tangent functions are defined and denoted as follows:
$$\sinh x=\frac{e^{x}-e^{-x}}{2}, \quad \cosh x=\frac{e^{x}+e^{-x}}{2}, \quad \tanh x=\frac{e^{x}-e^{-x}}{e^{x}+e^{-x}}$$

Prove the following identities:
(a) $\cosh ^{2} x-\sinh ^{2} x=1$.
(b) $\quad \sinh (x+y)=\sinh x \cosh y+\cosh x \sinh y$.
(c) $\quad \tanh (x+y)=\frac{\tanh x+\tanh y}{1+\tanh x \tanh y}$.
(d) $\quad \sinh x+\sinh y=2 \sinh \frac{x+y}{2} \cosh \frac{x-y}{2}$.
7.52 If $x=\frac{-1+i \sqrt{3}}{2}$ and $y=\frac{-1-i \sqrt{3}}{2}$, then find all nonnegative integers $n$ such that $x^{n}+y^{n}=-1$.

252

---

<!-- Page 253 -->

CHALLENGE PROBLEMS

Challenge Problems
7.53 The equation $z^{6}+z^{3}+1=0$ has one complex root with argument (angle) $\theta$ between $90^{\circ}$ and $180^{\circ}$ in the complex plane. Determine the degree measure of $\theta$. (Source: AIME)
7.54 Let $z$ be a root of $x^{5}-1=0$, with $z \neq 1$. Compute the value of
$$z^{15}+z^{16}+z^{17}+\cdots+z^{50}$$
(Source: ARML)
7.55 Find all solutions to the equation $z^{7}+8 z^{4}-2 i z^{3}-16 i=0$. Hints: 39
7.56 Let $\theta=\arctan 2$. What quadrant does the angle $8 \theta$ lie in? (No calculators!) Hints: 192
7.57 Find all $z$ such that $z^{9}+z^{6}+z^{3}=-1$. Hints: 170,283
7.58 Describe all integers $n$ such that the polynomial $x^{2 n}+1+(x+1)^{2 n}$ is divisible by $x^{2}+x+1$. Hints: 254
7.59 Find all $z$ such that $32 z^{5}+16 z^{4}+8 z^{3}+4 z^{2}+2 z+1=0$. Hints: 12
7.60 Let $x$ and $y$ be two $k^{\text {th }}$ roots of unity. Prove that $(x+y)^{k}$ is real. (Source: HMMT) Hints: 38
7.61 If $\omega^{1997}=1$ and $\omega \neq 1$, then evaluate
$$\frac{1}{1+\omega}+\frac{1}{1+\omega^{2}}+\cdots+\frac{1}{1+\omega^{1997}}$$
(Source: Mandelbrot) Hints: 214
7.62 A sequence of complex numbers $z_{0}, z_{1}, z_{2}, \ldots$ satisfies the rule
$$z_{n+1}=\frac{i z_{n}}{\bar{z}_{n}}$$

Suppose that $\left|z_{0}\right|=1$ and $z_{2005}=1$. How many possible values are there for $z_{0}$ ? (Source: AMC 12) Hints: 109, 70
7.63 The sequences $a_{1}, a_{2}, a_{3}, \ldots$ and $b_{1}, b_{2}, b_{3}, \ldots$ are defined by $a_{1}=\alpha, b_{1}=\beta$, and $a_{n+1}=\alpha a_{n}-\beta b_{n}, b_{n+1}=\beta a_{n}+\alpha b_{n}$ for all $n \geq 1$. How many pairs of real numbers $(\alpha, \beta)$ are there such that $a_{1997}=a_{1}$ and $b_{1997}=b_{1}$ ? Hints: 152,132
7.64 Show that $\tan n \theta=\frac{\binom{n}{1} \tan \theta-\binom{n}{3} \tan ^{3} \theta+\cdots}{1-\binom{n}{2} \tan ^{2} \theta+\cdots}$. Hints: 16
7.65 Given that $z$ is a complex number such that $z+\frac{1}{z}=2 \cos 3^{\circ}$, find the least integer that is greater than $z^{2000}+\frac{1}{z^{2000}}$. (Source: AIME) Hints: 257
7.66★ For a positive integer $n$, let $\Phi_{n}(x)$ denote the polynomial whose leading coefficient is 1 , and whose roots are the primitive $n^{\text {th }}$ roots of unity. These polynomials are called the cyclotomic polynomials.
(a) Show that $x^{n}-1$ can be factored as $\Phi_{d_{1}}(x) \Phi_{d_{2}}(x) \Phi_{d_{3}}(x) \cdots \Phi_{d_{k}}(x)$, where $d_{1}, d_{2}, d_{3}, \ldots, d_{k}$ are all of the positive divisors of $n$. Hints: 141
(b) Find $\Phi_{n}(x)$ for $1 \leq n \leq 10$. Hints: 256
(c) Find $\Phi_{p}(x)$, where $p$ is a prime.
(d) Show that if $n>2$, then the degree of $\Phi_{n}(x)$ is even.
(e) Show that $\Phi_{2 n}(x)=\Phi_{n}(-x)$ for all odd integers $n>2$. Hints: 188

253

---

<!-- Page 254 -->

CHAPTER 7. TRIGONOMETRY AND COMPLEX NUMBERS
7.67 ★ Show that
$$\binom{n}{0}-\binom{n}{2}+\binom{n}{4}-\binom{n}{6}+\cdots=2^{n / 2} \cos \frac{n \pi}{4}$$
and
$$\binom{n}{1}-\binom{n}{3}+\binom{n}{5}-\binom{n}{7}+\cdots=2^{n / 2} \sin \frac{n \pi}{4} .$$

Hints: 272
7.68 ★ If $w=\cos 40^{\circ}+i \sin 40^{\circ}$, then express $\left|w+2 w^{2}+3 w^{3}+\cdots+9 w^{9}\right|^{-1}$ in the form $a \sin b$. (Source: AHSME) Hints: 165, 88
7.69★ The sequence of functions $\left\{T_{n}\right\}$ is defined by $T_{0}(x)=1, T_{1}(x)=x$, and $T_{n}(x)=2 x T_{n-1}(x)-T_{n-2}(x)$ for all $n \geq 2$. Show that $T_{n}(\cos \theta)=\cos n \theta$.
7.70★ The angles $\alpha, \beta$, and $\gamma$ satisfy $e^{i \alpha}+e^{i \beta}+e^{i \gamma}=0$. Show that $e^{3 i \alpha}=e^{3 i \beta}=e^{3 i \gamma}$. Hints: 190,77
7.71★ Show that
$$\cos x+\cos y+\cos z+\cos (x+y+z)=4 \cos \left(\frac{x+y}{2}\right) \cos \left(\frac{x+z}{2}\right) \cos \left(\frac{y+z}{2}\right)$$
and
$$\sin x+\sin y+\sin z-\sin (x+y+z)=4 \sin \left(\frac{x+y}{2}\right) \sin \left(\frac{x+z}{2}\right) \sin \left(\frac{y+z}{2}\right) .$$

Hints: 211, 130
7.72★ Find a cubic polynomial whose roots are $\cos 2 \pi / 7, \cos 4 \pi / 7$, and $\cos 6 \pi / 7$. Hints: 162,25
$7.73 \star$ Let $f(x)=x^{2004}+2 x^{2003}+3 x^{2002}+\cdots+2004 x+2005$ and $z=\cos \left(\frac{\pi}{1003}\right)+i \sin \left(\frac{\pi}{1003}\right)$. Express the product
$$f(z) f\left(z^{2}\right) \cdots f\left(z^{2005}\right)$$
in the form $a^{b}$, where $a$ and $b$ are integers. Hints: 155, 73, 227
$7.74 \star$ Let $v$ and $w$ be distinct, randomly chosen roots of the equation $z^{1997}-1=0$. Find the probability that $\sqrt{2+\sqrt{3}} \leq|v+w|$. (Source: AIME) Hints: 139, 276
$7.75 \star$ Show that if $n$ is a positive integer greater than 1 , then
$$\sin \frac{\pi}{n} \sin \frac{2 \pi}{n} \cdots \sin \frac{(n-1) \pi}{n}=\frac{n}{2^{n-1}} .$$

Hints: 37, 183, 142

254

---

<!-- Page 255 -->

CHALLENGE PROBLEMS

Extra!

What is $i^{i}$ ?
De Moivre's Theorem allows us to raise nonreal numbers to integer powers, and our work with finding roots of unity gives us some idea how to handle raising nonreal numbers to rational powers. But what about raising a nonreal number to a nonreal power?

Let's start simpler, by raising a real number to a nonreal power. We know how to raise $e$ to a nonreal power, but what is $2^{i}$ ? The only number we know how to raise to the power $i$ is $e$, so we write 2 as a power of $e$. By definition, the power that we must raise $e$ to in order to get 2 is the base $e$ logarithm of 2 . We typically denote the base $e$ logarithm as $\ln$, so, for example, $\ln e^{3}=3$. Since we must raise $e$ to the power $\ln 2$ to get 2 , we can write 2 as $e^{\ln 2}$, so we have
$$2^{i}=\left(e^{\ln 2}\right)^{i}=e^{(\ln 2) i}=\cos (\ln 2)+i \sin (\ln 2) .$$

So, now we know how to raise positive real numbers besides $e$ to nonreal powers-express the base of the expression as a power of $e$.

We computed $2^{i}$ by writing 2 as $e^{\ln 2}$. So, to compute $i^{i}$, we try writing $i$ as $e^{\ln i}$, which would allow us to write $i^{i}$ as $\left(e^{\ln i}\right)^{i}$. We don't yet know what $\ln i$ is, but we do know how to write $i$ as a power of $e$. Specifically, we have $e^{\pi i / 2}=\cos \frac{\pi}{2}+i \sin \frac{\pi}{2}=i$, so we can choose to let $\ln i=\pi i / 2$, and we have
$$i^{i}=\left(e^{\pi i / 2}\right)^{i}=e^{(\pi i / 2) \cdot i}=e^{-\pi / 2} .$$

Weird! We raise $i$ to the power $i$, and the result is a real number!
But wait! We also have $e^{5 \pi i / 2}=i$. So
$$i^{i}=\left(e^{5 \pi i / 2}\right)^{i}=e^{-5 \pi / 2}$$

In fact we see that we could have gotten any number of the form $e^{-\pi / 2+2 k \pi}$ where $k$ is an integer. There are a lot of possible values. What is going on here?

We'd like to define $i^{i}$ such that it has only one value. Our work above seems to give many values of $i^{i}$, so one of our steps may involve using a "function" that isn't properly defined to give a unique output for each input. We've seen something like this before when we defined inverse trig functions. There, we had to restrict the domain of $\cos x$ in order to define an inverse. Let's see if something similar is going on here.

Remember we wrote $i=e^{\ln i}$. Raising $e$ to a power is a function, since
$$e^{a+b i}=e^{a} \cdot e^{b i}=e^{a}(\cos b+i \sin b)=e^{a} \cos b+e^{a} i \sin b,$$
which definitely has only one possible value. But what about $\ln$ ? Since we wrote $i=e^{\ln i}$, we're assuming that $\ln$ is an inverse to $f(x)=e^{x}$. In order for $f$ to have an inverse, no two inputs can go to the same output. This is OK when $x$ is real. When we allow nonreal inputs to $f(x)=e^{x}$, we have a different story, because $f(x)=f(x+2 \pi i)$.

Now we see the problem! In order to build the function in we need to restrict the domain of $f$. (Remember this is exactly what we did in defining arccos, since cos itself did not have an inverse.) One of the most common choices for restricting the domain of $f$ is forcing the imaginary part of the input to be in $(-\pi, \pi]$.

If we make this choice, then
$$i^{i}=e^{i \ln i}=e^{i(\pi i / 2)}=e^{-\pi / 2} .$$

As you might guess, this is far from the end of the story. Defining $\ln$ in this way introduces some unsettling consequences. For example, compare $\ln e^{\pi i}$ to $\ln \left(e^{1.0000001 \pi i}\right)$. The first equals $\pi i$. We'd expect the second to be quite close to $\pi i$, but, no, it's actually $-0.9999999 \pi i$. Naturally, mathematicians have an answer for dealing with this oddity, too. Perhaps you'll study it in college when you study complex analysis or topology.

255

---

