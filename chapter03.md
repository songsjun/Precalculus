# Chapter 3: Trigonometric Identities

<!-- Page 83 -->

Let it be an alliance of two large, formidable natures, mutually beheld, mutually feared before yet they recognize the deep identity which, beneath these disparities, unites them. - Ralph Waldo Emerson
3

Trigonometric Identities

A trigonometric identity is an equation involving trig functions that is true for all values of the variables for which the equation is defined. Back on page 38 we proved one of the most important trig identities,
$$\sin ^{2} \theta+\cos ^{2} \theta=1 .$$

Throughout Chapter 2 we hinted at several other identities, and on page 50, we used the unit circle to prove $\sin (-\theta)=-\sin \theta$ and $\cos (-\theta)=\cos \theta$ for all $\theta$. In this chapter, we derive and explore many more trig identities, and learn how to apply them to challenging problems. Don't try to memorize each new identity you encounter in this chapter. Instead, try to understand why the identities are true. Many of them will become automatic if you understand their derivations. Moreover, in Chapter 7, we'll see how complex numbers can help you remember many of these identities.

In this chapter, you will be asked to compute many trigonometric expressions. Do not use calculators or computers for these problems. The point of these problems is to learn how to apply identities to simplify expressions.

\begin{tabular}{|l|l|}
\hline Important: & Don't bother memorizing all the identities in this chapter. We'll let you know which ones are the most important, and you should make sure you understand those well enough that you have them memorized. The main purpose of this chapter is to learn how deeply related the trigonometric functions are, and how to use those relationships to simplify expressions and solve problems. You can usually look up the more obscure identities whenever you need them. Focus instead on how to apply them. \\
\hline
\end{tabular}

In that vein, you should know the identities $\sin ^{2} \theta+\cos ^{2} \theta=1, \cos (-\theta)=\cos \theta$, and $\sin (-\theta)=-\sin \theta$ well enough that you have them memorized. You can probably most easily internalize them by visualizing them on the unit circle.

83

---

<!-- Page 84 -->

CHAPTER 3. TRIGONOMETRIC IDENTITIES
3.1 Introduction to Trig Identities

Problems

Problem 3.1: In this problem, we find all $x$ with $0 \leq x<2 \pi \operatorname{such}$ that $\tan x+\sec x=\sqrt{3}$.
(a) Write the equation in terms of $\sin x$ and $\cos x$.
(b) Solve the equation for $\sin x$ in terms of $\cos x$.
(c) Use $\sin ^{2} x+\cos ^{2} x=1$ to find $\cos x$.
(d) Find all $x$ with $0 \leq x<2 \pi$ that satisfy the original equation. (Don't forget to check your answers.)

Problem 3.2: Prove the identity $\tan ^{2} x+1=\sec ^{2} x$.
Problem 3.3: Show that $\frac{(\csc x)(\sec x)}{1+\tan ^{2} x}=\cot x$.
Problem 3.4: Use the unit circle to express each of the following in terms of $\sin \theta, \cos \theta$, or $\tan \theta$ :
(a) $\sin \left(90^{\circ}-\theta\right)$
(b) $\cos \left(90^{\circ}-\theta\right)$
(c) $\quad \tan \left(90^{\circ}-\theta\right)$

Problem 3.5: Express each of the following in terms of $\sin \theta, \cos \theta, \tan \theta, \operatorname{cor} \cot \theta$ :
(a) $\quad \cos \left(\frac{\pi}{2}+\theta\right)$
(c) $\quad \tan (\pi+\theta)$
(b) $\quad \sin (\pi-\theta)$
(d) $\quad \cos \left(\theta-\frac{3 \pi}{2}\right)$

In each part, use the unit circle and/or graphs of trigonometric functions to explain your results.

Problem 3.6: In this problem, we find the smallest positive angle $\theta$ such that $\sin 2 \theta=\cos 3 \theta$.
(a) Use an identity from this section to write $\cos 3 \theta$ in terms of sine. (You do not have to write it in terms of $\sin \theta$; you should express $\cos 3 \theta$ as the sine of some expression.)
(b) Find an angle that satisfies your equation from part (a).
(c) Explain why the equation does not hold for any smaller positive value of $\theta$.

We'll start with an example that shows one reason why we care about trigonometric identities.
Problem 3.1: Find all $x$ with $0 \leq x<2 \pi$ such that $\tan x+\sec x=\sqrt{3}$.

Solution for Problem 3.1: We start by writing the equation in terms of sine and cosine.

\begin{tabular}{|l|} 
Concept: \\
A fruitful first step in many trig problems is rewriting the problem in terms of \\
sine and cosine, because most people have more experience with sine and cosine \\
than with the other trig functions.
\end{tabular}

Our equation now is $\frac{\sin x}{\cos x}+\frac{1}{\cos x}=\sqrt{3}$. Multiplying both sides by $\cos x$ gives $\sin x+1=\sqrt{3} \cos x$. Now what?

\begin{tabular}{|ll|}
\hline Concept: & When solving an equation that contains trig functions, it's often best to write the \\
equation in terms of a single trig function, so that you can then try to solve the \\
equation for that function.
\end{tabular}

84

---

<!-- Page 85 -->

3.1. INTRODUCTION TO TRIG IDENTITIES

We write $\sin x+1=\sqrt{3} \cos x$ in terms of a single trig function using $\sin ^{2} x+\cos ^{2} x=1$. Since $\cos ^{2} x=1-\sin ^{2} x$, we square both sides of the equation $\sin x+1=\sqrt{3} \cos x$, so that we can substitute $1-\sin ^{2} x$ for the resulting $\cos ^{2} x$. Squaring the equation gives
$$(\sin x+1)^{2}=3 \cos ^{2} x .$$

Substituting $\cos ^{2} x=1-\sin ^{2} x$ and expanding both sides gives $\sin ^{2} x+2 \sin x+1=3-3 \sin ^{2} x$. Simplifying this equation gives $2 \sin ^{2} x+\sin x-1=0$. This equation is quadratic in $\sin x$. Factoring gives
$$(\sin x+1)(2 \sin x-1)=0 .$$

From $\sin x+1=0$, we have $\sin x=-1$, which gives us $x=\frac{3 \pi}{2}$. (Remember, we are only asked for solutions such that $0 \leq x<2 \pi$.) From $2 \sin x-1=0$, we have $\sin x=\frac{1}{2}$, which gives us the solutions $x=\frac{\pi}{6}$ and $x=\frac{5 \pi}{6}$.

What's wrong with this finish:

If you try each of these "solutions," then you'll see a few problems. The value $x=\frac{\pi}{6}$ does indeed satisfy the original equation, but when $x=\frac{5 \pi}{6}$, we have $\tan x=-\frac{\sqrt{3}}{3}$ and $\sec x=-\frac{2 \sqrt{3}}{3}$, so $\tan x+\sec x=-\sqrt{3}$. Therefore, $x=\frac{5 \pi}{6}$ is not a solution to the original equation. Moreover, when $x=\frac{3 \pi}{2}$, both $\tan x$ and $\sec x$ are undefined. How did we get these false solutions?

WARNING!!
Whenever you solve an equation by performing some possibly irreversible steps, you must check your solutions at the end, to make sure they satisfy the original equation. Two common irreversible steps are squaring an equation and multiplying both sides of an equation by an expression that might equal zero.

Here, we took both of the irreversible steps described in the warning; the first when we squared both sides and the second when we multiplied both sides by $\cos x$. The first of these ultimately brought us the solution $x=\frac{5 \pi}{6}$ and the second brought us $x=\frac{3 \pi}{2}$. Since these "solutions" do not satisfy the original equation, we call them extraneous solutions, and they are not solutions of the original equation. Therefore, the only solution to the original equation is $x=\frac{\pi}{6}$.

In addition to helping us solve equations, the identity $\sin ^{2} x+\cos ^{2} x=1$ can help us derive new identities.
Problem 3.2: Prove the identity $\tan ^{2} x+1=\sec ^{2} x$.

Solution for Problem 3.2: Writing the left side in terms of sine and cosine leads us quickly to the proof:
$$\tan ^{2} x+1=\frac{\sin ^{2} x}{\cos ^{2} x}+1=\frac{\sin ^{2} x+\cos ^{2} x}{\cos ^{2} x}=\frac{1}{\cos ^{2} x}=\sec ^{2} x .$$

As an Exercise, you'll also prove the related identity $\cot ^{2} x+1=\csc ^{2} x$.

\begin{tabular}{|ll|}
\hline Important: & $\tan ^{2} x+1=\sec ^{2} x$, \\
$\cot ^{2} x+1=\csc ^{2} x$. \\
\hline
\end{tabular}

85

---

<!-- Page 86 -->

CHAPTER 3. TRIGONOMETRIC IDENTITIES

Problem 3.3: Show that $\frac{(\csc x)(\sec x)}{1+\tan ^{2} x}=\cot x$.

Solution for Problem 3.3: We could write everything in terms of sine and cosine, but we see that we can simplify the denominator of the left side immediately with $1+\tan ^{2} x=\sec ^{2} x$. So, we do that first:
$$\frac{(\csc x)(\sec x)}{1+\tan ^{2} x}=\frac{(\csc x)(\sec x)}{\sec ^{2} x}=\frac{\csc x}{\sec x}=\frac{\frac{1}{\sin x}}{\frac{1}{\cos x}}=\frac{\cos x}{\sin x}=\cot x .$$

Problem 3.4: Use the unit circle to express each of $\sin \left(90^{\circ}-\theta\right), \cos \left(90^{\circ}-\theta\right)$, and $\tan \left(90^{\circ}-\theta\right)$ in terms of $\sin \theta$, $\cos \theta, \tan \theta$, or $\cot \theta$.

Solution for Problem 3.4: In the diagram, point $P$ is the terminal point of the angle $\theta$. To find the terminal point of $90^{\circ}-\theta$, we start at $(0,1)$, which is the terminal point of $90^{\circ}$, and go $\theta$ clockwise, since $\theta$ is subtracted from $90^{\circ}$, not added. If $\theta$ is acute, then drawing altitudes from $P$ to the $x$-axis and $Q$ to the $y$-axis produces right triangles $\triangle Q B O$ and $\triangle P A O$. Since $Q O=P O$ and $\angle Q O B=\angle P O A$, we have $\triangle Q B O \cong \triangle P A O$. Therefore, $P A=Q B$ and $O A=O B$.

Since $P$ is the terminal point of $\theta$, we have $\cos \theta=O A$ and $\sin \theta=P A$. Since $Q$ is the terminal point of $90^{\circ}-\theta$, we have $\cos \left(90^{\circ}-\theta\right)=Q B$ and $\sin \left(90^{\circ}-\theta\right)=O B$. Combining these with $P A=Q B$ and $O A=O B$ from above gives us
$$\cos \left(90^{\circ}-\theta\right)=Q B=P A=\sin \theta$$
and
$$\sin \left(90^{\circ}-\theta\right)=O B=O A=\cos \theta .$$

We appear to have two new identities, but we haven't yet shown that these identities hold for all angles. We can extend our work above to other angles with some careful casework, or we can use the symmetry that our diagram suggests.

The actions of rotating the point $(1,0)$ an angle $\theta$ counterclockwise and rotating $(0,1)$ an angle $\theta$ clockwise are symmetric about the graph of $y=x$, which is dashed in the diagram at right. Therefore, the corresponding terminal points $P$ and $Q$ are symmetric about the line $y=x$. As we described on page 23, this means that we find the coordinates of $Q$ by reversing the coordinates of $P$. Since $P$ has coordinates $(\cos \theta, \sin \theta)$, point $Q$ has coordinates ( $\sin \theta, \cos \theta$ ). But because $Q$ is the terminal point of $90^{\circ}-\theta$, we can also express $Q$ as ( $\cos \left(90^{\circ}-\theta\right), \sin \left(90^{\circ}-\theta\right)$ ). Since we can express $Q$ both as ( $\sin \theta, \cos \theta$ ) and as ( $\cos \left(90^{\circ}-\theta\right), \sin \left(90^{\circ}-\theta\right)$ ), we must have $\cos \left(90^{\circ}-\theta\right)=\sin \theta$ and $\sin \left(90^{\circ}-\theta\right)=\cos \theta$.

\begin{tabular}{|l|}
\hline Important: \\
$\square$ \\
\hline
\end{tabular}$\quad$\begin{tabular}{rl}
$\sin \left(90^{\circ}-\theta\right)$ & $=\cos \theta$ \\
$\cos \left(90^{\circ}-\theta\right)$ & $=\sin \theta$
\end{tabular}

We can use these identities to find a similar one for tangent:
$$\tan \left(90^{\circ}-\theta\right)=\frac{\sin \left(90^{\circ}-\theta\right)}{\cos \left(90^{\circ}-\theta\right)}=\frac{\cos \theta}{\sin \theta}=\cot \theta .$$

86

---

<!-- Page 87 -->

3.1. INTRODUCTION TO TRIG IDENTITIES

We could also have discovered the relationship between $\cos \left(90^{\circ}-x\right)$ and $\sin x$ by examining the graphs of trigonometric functions. Converting to radians, we express $\cos \left(90^{\circ}-x\right)$ as $\cos \left(\frac{\pi}{2}-x\right)$, and consider the graph of $y=\cos \left(\frac{\pi}{2}-x\right)$. To produce this graph, we first create the graph of $y=\cos \left(\frac{\pi}{2}+x\right)$ by shifting the graph of $y=\cos x$ to the left by $\frac{\pi}{2}$.

Figure 3.1: Graph of $y=\cos \left(\frac{\pi}{2}+x\right)$

We then produce the graph of $y=\cos \left(\frac{\pi}{2}-x\right)$ by reflecting the graph of $y=\cos \left(\frac{\pi}{2}+x\right)$ over the $y$-axis. (To see why, let $f(x)=\cos \left(\frac{\pi}{2}+x\right)$. Reflecting the graph of $f$ over the $y$-axis gives us the graph of $y=f(-x)=\cos \left(\frac{\pi}{2}-x\right)$, as described on page 14.)

Figure 3.2: Graph of $y=\cos \left(\frac{\pi}{2}-x\right)$

The graph of $y=\cos \left(\frac{\pi}{2}-x\right)$ appears to be exactly the same as the graph of $y=\sin x$, which suggests that $\sin x=\cos \left(\frac{\pi}{2}-x\right)$ for all values of $x$. This graphical explanation is not a rigorous proof, but graphs can help us discover identities that we can rigorously prove by other means, such as our explanation with the unit circle.

Problem 3.5: Express each of the following in terms of $\sin \theta, \cos \theta$, or $\tan \theta$ :
(a) $\quad \cos \left(\frac{\pi}{2}+\theta\right)$
(c) $\quad \tan (\pi+\theta)$
(b) $\quad \sin (\pi-\theta)$
(d) $\quad \cos \left(\theta-\frac{3 \pi}{2}\right)$

In each part, use the unit circle and/or graphs of trigonometric functions to explain your results.

Solution for Problem 3.5:
(a) What's wrong with this solution:

87

---

<!-- Page 88 -->

CHAPTER 3. TRIGONOMETRIC IDENTITIES

Bogus Solution: The graph of $y=\cos \left(\frac{\pi}{2}+x\right)$ is the graph of $y=\cos x$ shifted $\frac{\pi}{2}$ to the
right. This graph is the same as the graph of $y=\sin x$, so we have $\cos \left(\frac{\pi}{2}+x\right)=\sin x$.
At first, we might question the claim that shifting the graph of $y=\cos x$ to the right by $\frac{\pi}{2}$ does indeed produce the graph of $y=\sin x$. So, let's try it:

Figure 3.3: Graph of $y=\cos x$ (dashed) and $y=\cos x$ shifted $\frac{\pi}{2}$ to the right (solid)

Sure enough, the resulting solid graph above is the graph of $y=\sin x$. Maybe the Bogus Solution is correct.

We test whether $\cos \left(\frac{\pi}{2}+\theta\right)$ always equals $\sin \theta$ by evaluating both for various values of $\theta$. Let's try $\theta=0$. That gives us $\cos \left(\frac{\pi}{2}+\theta\right)=0$ and $\sin \theta=0$. OK, that works; let's try $\theta=\frac{\pi}{4}$. Then, we have $\cos \left(\frac{\pi}{2}+\theta\right)=\cos \frac{3 \pi}{4}=-\frac{\sqrt{2}}{2}$ and $\sin \theta=\frac{\sqrt{2}}{2}$. Uh-oh. Those aren't equal; they're opposites. If we try a few more values of $\theta$, it appears that $\cos \left(\frac{\pi}{2}+\theta\right)$ and $\sin \theta$ are always opposites.

Looking more closely at our Bogus Solution reveals the error. The graph of $y=\cos \left(\frac{\pi}{2}+x\right)$ is the result of shifting the graph of $y=\cos x$ to the left by $\frac{\pi}{2}$, not to the right. (See page 13 if you don't see why.) The correct graph is below:

Figure 3.4: Graph of $y=\cos \left(\frac{\pi}{2}+x\right)$

This graph is the same as the graph of $y=\sin x$ reflected over the $x$-axis. Reflecting the graph of $y=\sin x$ over the $x$-axis gives us the graph of $y=-\sin x$ (see page 14). Since the graphs of $y=\cos \left(\frac{\pi}{2}+x\right)$ and $y=-\sin x$ appear to be the same, it seems like we must have $\cos \left(\frac{\pi}{2}+x\right)=-\sin x$ for all $x$.

See if you can also use the unit circle to explain this identity.

88

---

<!-- Page 89 -->

3.1. INTRODUCTION TO TRIG IDENTITIES
(b) We're asked to find $\sin (\pi-\theta)$ in terms of trigonometric functions of $\theta$. Suppose $\theta$ is an acute angle, and that $P$ is its terminal point. Let $Q$ be the terminal point of $\pi-\theta$, so that the segment joining $Q$ with the origin forms an angle of $\theta$ with the negative $x$-axis, as shown at right. Drawing altitudes from $P$ and $Q$ to the $x$-axis forms congruent right triangles $P O A$ and $Q O B$, from which we have $P A=Q B$. Therefore, $P$ and $Q$ are the same distance above the $x$-axis, so they have the same $y$-coordinates, which means their corresponding angles have the same sine.

If $\theta$ is obtuse $\left(\frac{\pi}{2}<\theta<\pi\right)$, then we have the essentially the same diagram, but with $P$ to the left of the $y$-axis and $Q$ to the right of the $y$-axis.

We can go through similar arguments for values of $\theta$ greater than $\pi$ or less than 0 . We could also note that rotating the point $(1,0)$ an angle of $\theta$ degrees counterclockwise and rotating the point ( $-1,0$ ) an angle of $\theta$ degrees clockwise are symmetric about the $y$-axis, as depicted at right.

If two points are symmetric about the $y$-axis, then the points have opposite $x$-coordinates and equal $y$-coordinates. Therefore, we have $\cos (\pi-\theta)=-\cos \theta$ and $\sin (\pi-\theta)=\sin \theta$.
(c) Back on page 50, we showed that the period of the tangent function is $\pi$. Therefore, we have $\tan (\pi+\theta)=\tan \theta$.
(e) We must find $\cos \left(\theta-\frac{3 \pi}{2}\right)$ in terms of trigonometric functions of $\theta$. At right, we show a case in which $\theta$ is a fourth quadrant angle (with terminal point $P$ ), so that $\theta-\frac{3 \pi}{2}$ is a first quadrant angle (with terminal point $Q$ ). We draw altitudes $\overline{P A}$ and $\overline{Q B}$ as shown. Since $P$ and $Q$ are the terminal points of angles that are $\frac{3 \pi}{2}$ apart, we have $\angle P O Q=\frac{\pi}{2}$, which means that $\angle Q O B=\frac{\pi}{2}-\angle P O A=\angle O P A$. This tells us that $\triangle Q O B \cong \triangle O P A$. Therefore, we have $O B=P A$.

Since $P$ and $Q$ are the terminal points of $\theta$ and $\theta-\frac{3 \pi}{2}$, respectively, we have $\sin \theta=-P A$ ( $P$ is below the $x$-axis, so $\sin \theta$ is negative) and $\cos \left(\theta-\frac{3 \pi}{2}\right)=O B$. Combining these with $O B=P A$ gives us $\cos \left(\theta-\frac{3 \pi}{2}\right)=-\sin \theta$.

We can also visualize this identity by graphing $y=\cos \left(x-\frac{3 \pi}{2}\right)$, which we do by shifting the graph of $y=\cos x$ to the right by $\frac{3 \pi}{2}$. The result is shown below:

Figure 3.5: Graph of $y=\cos \left(x-\frac{3 \pi}{2}\right)$

Just as in part (a), the resulting graph is the same as the graph of $y=\sin x$ reflected over the $x$-axis. We deduce that the graphs of $y=\cos \left(x-\frac{3 \pi}{2}\right)$ and $y=-\sin x$ are the same, so $\cos \left(x-\frac{3 \pi}{2}\right)=-\sin x$ for all $x$.

Testing with $x=\frac{7 \pi}{4}$ gives us $\cos \left(x-\frac{3 \pi}{2}\right)=\cos \frac{\pi}{4}=\frac{\sqrt{2}}{2}$ and $-\sin x=-\left(-\frac{\sqrt{2}}{2}\right)=\frac{\sqrt{2}}{2}$. Testing with $x=\frac{\pi}{6}$ gives us $\cos \left(x-\frac{3 \pi}{2}\right)=\cos \left(-\frac{4 \pi}{3}\right)=-\frac{1}{2}$ and $-\sin x=-\frac{1}{2}$. As expected, both our tests work.

89

---

<!-- Page 90 -->

CHAPTER 3. TRIGONOMETRIC IDENTITIES

Don't bother memorizing all the possible identities we can form by shifting an angle that is some multiple of $90^{\circ}$. As we just saw, thinking about the unit circle or about graphs of trigonometric functions can help you rediscover these identities whenever you need them. Probably the most commonly used are the ones we showed in Problem 3.4 for functions of $90^{\circ}-\theta$ and those for functions of $180^{\circ}-\theta$ :

Problem 3.6: Find the smallest positive angle $\theta$ such that $\sin 2 \theta=\cos 3 \theta$.

Solution for Problem 3.6: We don't have good tools yet for expressing $\sin 2 \theta$ and $\cos 3 \theta$ in terms of $\sin \theta$ and $\cos \theta$. However, we can turn $\cos 3 \theta$ into the sine of an expression by using the identity $\cos x=\sin \left(90^{\circ}-x\right)$, which turns $\sin 2 \theta=\cos 3 \theta$ into
$$\sin 2 \theta=\sin \left(90^{\circ}-3 \theta\right) .$$

Now, we at least see a way to find one solution; the sines of two angles are equal if the angles are equal. Solving $2 \theta=90^{\circ}-3 \theta$ gives us $\theta=18^{\circ}$. But how do we know that this is the smallest possible positive solution?

Consider what happens to both sides of the equation if we have $0^{\circ}<\theta<18^{\circ}$. For $\theta=18^{\circ}$, we found that we have $\sin 2 \theta=\cos 3 \theta$, or $\sin 36^{\circ}=\cos 54^{\circ}$. When we decrease $\theta$ from $18^{\circ}$, the value of $\sin 2 \theta$ decreases, because as $2 \theta$ decreases from $36^{\circ}$ (but stays positive), the terminal point of $2 \theta$ gets closer to $(1,0)$. That is, it gets closer to the $x$-axis, which means that $\sin 2 \theta$ decreases as $2 \theta$ decreases from $36^{\circ}$ to $0^{\circ}$. Meanwhile, as $\theta$ decreases from $18^{\circ}$ to $0^{\circ}$, the value of $\cos 3 \theta$ increases, since the terminal point of $3 \theta$ gets farther to the right of the $y$-axis as $3 \theta$ decreases from $54^{\circ}$ to $0^{\circ}$. Putting these observations together with $\sin 36^{\circ}=\cos 54^{\circ}$, we conclude that if $0^{\circ}<\theta<18^{\circ}$, then we have
$$\sin 2 \theta<\sin 36^{\circ}=\cos 54^{\circ}<\cos 3 \theta .$$

Therefore, we cannot have $\sin 2 \theta=\cos 3 \theta$ for any positive value of $\theta$ less than $18^{\circ}$.
3.1.1 Prove the identity $\cot ^{2} \theta+1=\csc ^{2} \theta$.
3.1.2 Prove that $\sin \left(360^{\circ}-\theta\right)=-\sin \theta$ for all angles $\theta$.
3.1.3 Use the identity you proved in Problem 3.2 to solve Problem 3.1 without first converting the equation to sines and cosines.
3.1.4 Find $\cos \left(\frac{3 \pi}{2}+\theta\right)$ in terms of $\sin \theta$ or $\cos \theta$.
3.1.5 Find the value of the product $\tan \left(\frac{\pi}{12}\right) \tan \left(\frac{2 \pi}{12}\right) \tan \left(\frac{3 \pi}{12}\right) \tan \left(\frac{4 \pi}{12}\right) \tan \left(\frac{5 \pi}{12}\right)$.
3.1.6 Find the range of
$$f(A)=\frac{\sin A\left(3 \cos ^{2} A+\cos ^{4} A+3 \sin ^{2} A+\sin ^{2} A \cos ^{2} A\right)}{\tan A(\sec A-\sin A \tan A)},$$
where $A$ is not an integer multiple of $\pi / 2$. (Source: HMMT)

90

---

<!-- Page 91 -->

3.2. SUMS AND DIFFERENCES OF ANGLES
3.2 Sums and Differences of Angles

In the previous section, we found identities to simplify expressions like $\sin \left(\frac{\pi}{2}+\theta\right)$ and $\cos \left(\theta-180^{\circ}\right)$. In each of the expressions we simplified, one of the angles was a multiple of $90^{\circ}$. In this section, we develop identities for trigonometric functions of the sum or difference of any two angles.

We start by proving that
$$\sin (\alpha+\beta)=\sin \alpha \cos \beta+\sin \beta \cos \alpha$$
for positive angles $\alpha$ and $\beta$ such that $\alpha+\beta<90^{\circ}$. We can extend this proof to all angles with a lot of careful casework; we won't do so here. (You'll have a chance to cover some of these cases as an Exercise.) You can use this identity for all problems after Problem 3.7.

Problems

Problem 3.7: In this problem, we will use the diagram at right to prove that if $\alpha$ and $\beta$ are positive angles such that $\alpha+\beta<90^{\circ}$, then
$$\sin (\alpha+\beta)=\sin \alpha \cos \beta+\sin \beta \cos \alpha$$

In the diagram, we have $A D=1, \angle B C A=\alpha$, and $\angle D A E=\beta$.
(a) Explain why $A E=\cos \beta$ and $D E=\sin \beta$.
(b) Find $E C$ in terms of sine and cosine of $\alpha$ and $\beta$.
(c) Find $\angle A D B$ in terms of $\alpha$ and $\beta$.
(d) Show that $A B=\sin (\alpha+\beta)$ and $\sin \alpha=\frac{A B}{A C}$.
(e) Show that $\sin (\alpha+\beta)=\sin \alpha \cos \beta+\sin \beta \cos \alpha$.

Problem 3.8: Use the identity you found in Problem 3.7 together with identities from the previous section to find $\sin (\alpha-\beta)$ in terms of $\sin \alpha, \cos \alpha, \sin \beta$, and $\cos \beta$. Test your identity with $\alpha=120^{\circ}$ and $\beta=60^{\circ}$.

Problem 3.9: In Problem 3.4, we found that $\sin \left(90^{\circ}-\alpha\right)=\cos \alpha$.
(a) Use $\sin \left(90^{\circ}-\alpha\right)=\cos \alpha$ together with the identity for $\sin (\alpha+\beta)$ to express $\cos (\alpha-\beta)$ in terms of $\sin \alpha$, $\cos \alpha, \sin \beta$ and $\cos \beta$.
(b) Test your identity in the previous part by letting $\alpha=120^{\circ}$ and $\beta=60^{\circ}$. If the result is not a true statement, then try the first part again.
(c) Find an identity for $\cos (\alpha+\beta)$.

Problem 3.10: Suppose that $\tan \alpha, \tan \beta$, and $\tan (\alpha+\beta)$ are all defined. Find $\tan (\alpha+\beta)$ in terms of $\tan \alpha$ and $\tan \beta$.
Problem 3.11:
(a) Find $\cos 15^{\circ}$.
(b) Find $\sin \frac{13 \pi}{12}$.

Problem 3.12: Find the value of $\cos \left(\arcsin \frac{4}{5}+\arctan \frac{5}{12}\right)$ without using a calculator.

91

---

<!-- Page 92 -->

CHAPTER 3. TRIGONOMETRIC IDENTITIES

Problem 3.13: Below is the graph of $y=3 \sin x+4 \cos x$ :

It looks like the graph of a function of the form $a \sin (b x+c)$ ! Why?
Problem 3.14: Compute $x$ if $\arctan x+\arctan 1=2\left(\arctan x-\arctan \frac{1}{3}\right)$. (Source: ARML)

Problem 3.7: Use the diagram at right to prove that if $\alpha$ and $\beta$ are positive angles such that $\alpha+\beta<90^{\circ}$, then
$$\sin (\alpha+\beta)=\sin \alpha \cos \beta+\sin \beta \cos \alpha$$

In the diagram, we have $A D=1, \angle B C A=\alpha$, and $\angle D A E=\beta$.

Solution for Problem 3.7: We start by finding the lengths of various segments in the diagram in terms of sine and cosine of $\alpha$ and $\beta$. Applying the right triangle relationships we learned on page 35 to $\triangle A D E$, we have $\cos \beta=\frac{A E}{A D}$ and $\sin \beta=\frac{D E}{A D}$. We therefore have $A E=\cos \beta$ and $D E=\sin \beta$.

Turning to $\triangle D E C$, we have $\tan \alpha=\frac{D E}{E C}$, so
$$E C=\frac{D E}{\tan \alpha}=\frac{\sin \beta \cos \alpha}{\sin \alpha} .$$

Next, we consider right triangle $A D B$. To find either leg of this triangle in terms of trig functions of $\alpha$ and $\beta$, we'll first have to find the acute angles of $\triangle A D B$ in terms of $\alpha$ and $\beta$. From the angles in $\triangle A D C$, we have $\angle A D C=180^{\circ}-\angle D A C-\angle D C A=180^{\circ}-\alpha-\beta$. Therefore, we have
$$\angle A D B=180^{\circ}-\angle A D C=180^{\circ}-\left(180^{\circ}-\alpha-\beta\right)=\alpha+\beta .$$

We can now use $\triangle A B D$ to find an expression for $\sin (\alpha+\beta)$ :
$$\sin (\alpha+\beta)=\sin \angle A D B=\frac{A B}{A D} .$$

Since $A D=1$, we have $A B=\sin (\alpha+\beta)$, as shown in the diagram.

92

---

<!-- Page 93 -->

3.2. SUMS AND DIFFERENCES OF ANGLES

We're almost there! We still have one more right triangle to investigate: $\triangle A B C$. This triangle gives us
$$\sin \alpha=\sin \angle A C B=\frac{A B}{A C}=\frac{A B}{A E+E C}=\frac{\sin (\alpha+\beta)}{\cos \beta+\frac{\sin \beta \cos \alpha}{\sin \alpha}},$$
so we have the equation
$$\frac{\sin (\alpha+\beta)}{\cos \beta+\frac{\sin \beta \cos \alpha}{\sin \alpha}}=\sin \alpha$$

Multiplying both sides by the denominator of the left side gives:
$$\begin{aligned}
\sin (\alpha+\beta) & =\sin \alpha\left(\cos \beta+\frac{\sin \beta \cos \alpha}{\sin \alpha}\right) \\
& =\sin \alpha \cos \beta+\sin \beta \cos \alpha
\end{aligned}$$
as desired.

With a great deal of careful casework, we can prove that this identity holds for any angles $\alpha$ and $\beta$. You'll see some of these cases as an Exercise. We can now use this identity to prove other identities for trigonometric functions of sums or differences of angles.

Concept: Once we find one trigonometric identity, we can often use it to quickly prove
other related identities.

Problem 3.8: Use the identity you found in Problem 3.7 together with identities from the previous section to find $\sin (\alpha-\beta)$ in terms of $\sin \alpha, \cos \alpha, \sin \beta$, and $\cos \beta$. Test your identity with $\alpha=120^{\circ}$ and $\beta=60^{\circ}$.

Solution for Problem 3.8: We write $\sin (\alpha-\beta)$ as $\sin (\alpha+(-\beta))$ and use the identity for the sine of a sum of angles:
$$\sin (\alpha-\beta)=\sin (\alpha+(-\beta))=\sin \alpha \cos (-\beta)+\sin (-\beta) \cos \alpha .$$

Now, we apply $\sin (-\beta)=-\sin \beta$ and $\cos (-\beta)=\cos \beta$ to the right side to find:
$$\sin (\alpha-\beta)=\sin \alpha \cos \beta-\sin \beta \cos \alpha .$$

If we let $\alpha=120^{\circ}$ and $\beta=60^{\circ}$, we have $\sin (\alpha-\beta)=\sin 60^{\circ}=\frac{\sqrt{3}}{2}$ and
$$\sin \alpha \cos \beta-\sin \beta \cos \alpha=\sin 120^{\circ} \cos 60^{\circ}-\sin 60^{\circ} \cos 120^{\circ}=\left(\frac{\sqrt{3}}{2}\right)\left(\frac{1}{2}\right)-\left(\frac{\sqrt{3}}{2}\right)\left(-\frac{1}{2}\right)=\frac{\sqrt{3}}{2} .$$

Now, we turn to cosine.
Problem 3.9: Find identities for $\cos (\alpha-\beta)$ and $\cos (\alpha+\beta)$.
Solution for Problem 3.9: We already have angle sum and difference identities for sine, so we look for ways to relate sine and cosine. Two identities come to mind, $\sin ^{2} \theta+\cos ^{2} \theta=1$ and $\sin \left(90^{\circ}-\theta\right)=\cos \theta$. The first doesn't look immediately helpful, because squaring the identities we already have for $\sin (\alpha+\beta)$ and $\sin (\alpha-\beta)$ looks scary. So, we focus instead on $\sin \left(90^{\circ}-\theta\right)=\cos \theta$, which gives us
$$\cos (\alpha-\beta)=\sin \left(90^{\circ}-(\alpha-\beta)\right)=\sin \left(90^{\circ}-\alpha+\beta\right) .$$

93

---

<!-- Page 94 -->

CHAPTER 3. TRIGONOMETRIC IDENTITIES

Now we have the sine of a combination of three angles. By grouping the first two, we can write it as the sine of a sum of two angles, which we know how to handle:
$$\cos (\alpha-\beta)=\sin \left(90^{\circ}-\alpha+\beta\right)=\sin \left(\left(90^{\circ}-\alpha\right)+\beta\right)$$

We can now apply the identity
$$\sin (x+y)=\sin x \cos y+\sin y \cos x$$

By letting $x=90^{\circ}-\alpha$ and $y=\beta$, we have
$$\cos (\alpha-\beta)=\sin \left(\left(90^{\circ}-\alpha\right)+\beta\right)=\sin \left(90^{\circ}-\alpha\right) \cos \beta+\sin \beta \cos \left(90^{\circ}-\alpha\right)$$

Finally, since $\sin \left(90^{\circ}-\alpha\right)=\cos \alpha$ and $\cos \left(90^{\circ}-\alpha\right)=\sin \alpha$, we have
$$\cos (\alpha-\beta)=\cos \alpha \cos \beta+\sin \alpha \sin \beta$$

We can either do essentially the same thing for $\cos (\alpha+\beta)$, or we can write $\cos (\alpha+\beta)$ as $\cos (\alpha-(-\beta))$ and use the identity we just proved:
$$\begin{aligned}
\cos (\alpha+\beta) & =\cos (\alpha-(-\beta)) \\
& =\cos \alpha \cos (-\beta)+\sin \alpha \sin (-\beta) \\
& =\cos \alpha \cos \beta-\sin \alpha \sin \beta
\end{aligned}$$
where we used $\cos (-\beta)=\cos \beta$ and $\sin (-\beta)=-\sin \beta$ in the last step.
Finally, we tackle tangent.
Problem 3.10: Suppose that $\tan \alpha, \tan \beta$, and $\tan (\alpha+\beta)$ are all defined. Find $\tan (\alpha+\beta)$ in terms of $\tan \alpha$ and $\tan \beta$.

Solution for Problem 3.10: We already know how to handle sine and cosine, so we write tangent in terms of sine and cosine, and use the identities we've already proved:
$$\tan (\alpha+\beta)=\frac{\sin (\alpha+\beta)}{\cos (\alpha+\beta)}=\frac{\sin \alpha \cos \beta+\sin \beta \cos \alpha}{\cos \alpha \cos \beta-\sin \alpha \sin \beta}$$

Now what? We want an identity in terms of $\tan \alpha$ and $\tan \beta$, but we just have sines and cosines.
There are a few ways we can reach our desired identity. We could divide the numerator and denominator of the our huge fraction above by $\cos \alpha \cos \beta$ (make sure you see why this works), or we can note that $\operatorname{since} \tan \alpha=\frac{\sin \alpha}{\cos \alpha}$, we have $\sin \alpha=\tan \alpha \cos \alpha$. Similarly, we have $\sin \beta=\tan \beta \cos \beta$, and we can write our identity as:
$$\begin{aligned}
\tan (\alpha+\beta) & =\frac{\sin \alpha \cos \beta+\sin \beta \cos \alpha}{\cos \alpha \cos \beta-\sin \alpha \sin \beta} \\
& =\frac{\tan \alpha \cos \alpha \cos \beta+\tan \beta \cos \beta \cos \alpha}{\cos \alpha \cos \beta-\tan \alpha \cos \alpha \tan \beta \cos \beta} \\
& =\frac{(\cos \alpha \cos \beta)(\tan \alpha+\tan \beta)}{(\cos \alpha \cos \beta)(1-\tan \alpha \tan \beta)}
\end{aligned}$$

Because $\tan \alpha$ and $\tan \beta$ are both defined, we know that $\cos \alpha \cos \beta \neq 0$. Therefore, the $\cos \alpha \cos \beta$ terms in the numerator and denominator cancel and leave
$$\tan (\alpha+\beta)=\frac{\tan \alpha+\tan \beta}{1-\tan \alpha \tan \beta}$$

As an Exercise, you'll prove the corresponding identity for $\tan (\alpha-\beta)$.

94

---

<!-- Page 95 -->

3.2. SUMS AND DIFFERENCES OF ANGLES

WARNING!! The identity
$$\tan (\alpha+\beta)=\frac{\tan \alpha+\tan \beta}{1-\tan \alpha \tan \beta}$$
only holds when $1-\tan \alpha \tan \beta \neq 0$ and when both $\tan \alpha$ and $\tan \beta$ are defined (that is, when $\cos \alpha \neq 0$ and $\cos \beta \neq 0$ ). If $\tan \alpha \tan \beta=1$, then $\tan (\alpha+\beta)$ is undefined.

Let's take a closer look at why $\tan (\alpha+\beta)$ is undefined when $\tan \alpha \tan \beta=1$. From $\tan \alpha \tan \beta=1$, we have $\sin \alpha \sin \beta=\cos \alpha \cos \beta$, so $\cos \alpha \cos \beta-\sin \alpha \sin \beta=0$. The left side equals $\cos (\alpha+\beta)$, which means $\cos (\alpha+\beta)=0$, so $\tan (\alpha+\beta)$ is undefined.

We now have identities for the sine, cosine, and tangent of a sum or difference of two angles:

Angle sum and difference identities:
$$\begin{array}{l}
\sin (\alpha+\beta)=\sin \alpha \cos \beta+\sin \beta \cos \alpha, \\
\sin (\alpha-\beta)=\sin \alpha \cos \beta-\sin \beta \cos \alpha, \\
\cos (\alpha+\beta)=\cos \alpha \cos \beta-\sin \alpha \sin \beta, \\
\cos (\alpha-\beta)=\cos \alpha \cos \beta+\sin \alpha \sin \beta, \\
\tan (\alpha+\beta)=\frac{\tan \alpha+\tan \beta}{1-\tan \alpha \tan \beta}, \\
\tan (\alpha-\beta)=\frac{\tan \alpha-\tan \beta}{1+\tan \alpha \tan \beta} .
\end{array}$$

These identities are sometimes expressed in more concise form using ± and $\mp$ :
$$\begin{array}{l}
\sin (\alpha \pm \beta)=\sin \alpha \cos \beta \pm \sin \beta \cos \alpha \\
\cos (\alpha \pm \beta)=\cos \alpha \cos \beta \mp \sin \alpha \sin \beta \\
\tan (\alpha \pm \beta)=\frac{\tan \alpha \pm \tan \beta}{1 \mp \tan \alpha \tan \beta}
\end{array}$$

The ± symbols on the right sides mean "match the sign of the $\pm$ on the left," while the $\mp$ symbols on the right sides mean "take the opposite of the sign of the ± on the left."

Don't bother memorizing all of these now. As you've just seen, if you only have $\sin (\alpha+\beta)$ memorized, you can derive all the rest pretty quickly. Moreover, in Chapter 7, we'll learn an even faster way to recall these identities.

Problem 3.11:
(a) Find $\cos 15^{\circ}$.
(b) Find $\sin \frac{13 \pi}{12}$.

95

---

<!-- Page 96 -->

CHAPTER 3. TRIGONOMETRIC IDENTITIES

Solution for Problem 3.11:
(a) If we start in the usual way, by building a right triangle on the unit circle, we end up with a right triangle with acute angles with measures $15^{\circ}$ and $75^{\circ}$ and hypotenuse length 1 . Unfortunately, we don't know anything (yet!) about the sides of such a triangle. However, we might be able to use our new angle sum and difference identities to express $15^{\circ}$ in terms of angles whose sine and cosine we know. We list a few of the angles we know how to handle: $0^{\circ}, 30^{\circ}, 45^{\circ}, 60^{\circ}, 90^{\circ}$. Aha! We have $45^{\circ}-30^{\circ}=15^{\circ}$, so we can use our difference of angles formula:
$$\begin{aligned}
\cos 15^{\circ} & =\cos \left(45^{\circ}-30^{\circ}\right) \\
& =\cos 45^{\circ} \cos 30^{\circ}+\sin 45^{\circ} \sin 30^{\circ} \\
& =\frac{\sqrt{2}}{2} \cdot \frac{\sqrt{3}}{2}+\frac{\sqrt{2}}{2} \cdot \frac{1}{2} \\
& =\frac{\sqrt{6}+\sqrt{2}}{4} .
\end{aligned}$$
(b) We know that adding fractions of the form $\frac{a}{3}$ and $\frac{b}{4}$ can give us a fraction with 12 as the denominator, and we know how to handle sine and cosine of angles like $\frac{\pi}{4}$ and $\frac{\pi}{3}$. So, again, we look over the angles we know how to handle, writing them with denominator 12 , and try to find a pair we can combine to get $\frac{13 \pi}{12}: \frac{3 \pi}{12}, \frac{4 \pi}{12}$, $\frac{6 \pi}{12}, \frac{8 \pi}{12}, \frac{9 \pi}{12}$. Success! We have $\frac{4 \pi}{12}+\frac{9 \pi}{12}=\frac{13 \pi}{12}$, so:
$$\begin{aligned}
\sin \frac{13 \pi}{12} & =\sin \left(\frac{9 \pi}{12}+\frac{4 \pi}{12}\right)=\sin \left(\frac{3 \pi}{4}+\frac{\pi}{3}\right) \\
& =\sin \frac{3 \pi}{4} \cos \frac{\pi}{3}+\sin \frac{\pi}{3} \cos \frac{3 \pi}{4} \\
& =\frac{\sqrt{2}}{2} \cdot \frac{1}{2}+\frac{\sqrt{3}}{2} \cdot\left(-\frac{\sqrt{2}}{2}\right) \\
& =\frac{\sqrt{2}-\sqrt{6}}{4}
\end{aligned}$$

As a quick check, we can note that this answer is negative, which is what we should expect, since the sine of a third quadrant angle must be negative.

Problem 3.12: Find the value of $\cos \left(\arcsin \frac{4}{5}+\arctan \frac{5}{12}\right)$ without using a calculator.

Solution for Problem 3.12: If we could calculate the angles that equal arcsin $\frac{4}{5}$ and arctan $\frac{5}{12}$, we could simply add these angles and take the cosine of the result. Unfortunately, we can't find these two angles without a calculator. However, we saw in Section 2.5 that we can calculate expressions like $\cos \left(\arcsin \frac{4}{5}\right)$, and we can use the angle sum formula to break $\cos \left(\arcsin \frac{4}{5}+\arctan \frac{5}{12}\right)$ into expressions like $\cos \left(\arcsin \frac{4}{5}\right)$ :
$$\cos \left(\arcsin \frac{4}{5}+\arctan \frac{5}{12}\right)=\cos \left(\arcsin \frac{4}{5}\right) \cos \left(\arctan \frac{5}{12}\right)-\sin \left(\arcsin \frac{4}{5}\right) \sin \left(\arctan \frac{5}{12}\right) .$$

One of these expressions is pretty easy: by the definition of arcsin, we have $\sin \left(\arcsin \frac{4}{5}\right)=\frac{4}{5}$. Let's tackle $\cos \left(\arcsin \frac{4}{5}\right)$ next. We seek $\cos \theta$, where $\sin \theta=\frac{4}{5}$ and $\theta$ is in the first quadrant (since the arcsine of a positive number less than 1 is a first quadrant angle). We'll take two approaches:

Method 1: Use trig identities. We have $\cos ^{2} \theta=1-\sin ^{2} \theta=1-\frac{16}{25}=\frac{9}{25}$. Since $\theta$ is in the first quadrant, $\cos ^{2} \theta=\frac{9}{25}$ gives us $\cos \theta=\frac{3}{5}$. So, $\cos \left(\arcsin \frac{4}{5}\right)=\frac{3}{5}$.

96

---

<!-- Page 97 -->

3.2. SUMS AND DIFFERENCES OF ANGLES

Method 2: Use the geometric interpretation of sine and cosine. Suppose $\triangle A B C$ is a right triangle with $\angle C=90^{\circ}$ and $\angle A=\theta$, as shown at right. Then, we have $\sin \theta=\frac{B C}{A B}$ and $\cos \theta=\frac{A C}{A B}$. Since we know that $\sin \theta=\frac{4}{5}$, we let $B C=4$ and $A B=5$. The Pythagorean Theorem then gives us $A C=3$, so $\cos \theta=\frac{3}{5}$. (We also could have simply recognized the Pythagorean triple $\{3,4,5\}$.)

Next, we tackle $\cos \left(\arctan \frac{5}{12}\right)$ and $\sin \left(\arctan \frac{5}{12}\right)$. We let $\phi=\arctan \frac{5}{12}$, so $\tan \phi=\frac{5}{12}$, and $0<\phi<\frac{\pi}{2}$. Again, we present two solutions:

Method 1: Use trig identities. We could write $\tan \phi$ in terms of $\sin \phi$ and $\cos \phi$, solve for $\sin \phi$ in terms of $\cos \phi$, and then use $\sin ^{2} \phi+\cos ^{2} \phi=1$. Instead, we'll use $\sec ^{2} \phi=\tan ^{2} \phi+1$ to find
$$\sec ^{2} \phi=\left(\frac{5}{12}\right)^{2}+1=\frac{25}{144}+1=\frac{169}{144} .$$

Since $0<\phi<\frac{\pi}{2}$, we know that $\sec \phi>0$, so we have $\sec \phi=\frac{13}{12}$, which gives us $\cos \phi=\frac{12}{13}$. Finally, we have $\sin ^{2} \phi=1-\cos ^{2} \phi=\frac{25}{169}$, so $\sin \phi=\frac{5}{13}$. Therefore, we have $\cos \left(\arctan \frac{5}{12}\right)=\frac{12}{13}$ and $\sin \left(\arctan \frac{5}{12}\right)=\frac{5}{13}$.

Method 2: Geometry. Let $\triangle X Y Z$ be a right triangle with $\angle Z=90^{\circ}, Z Y=5$, $X Z=12$, and $\angle X=\phi$, as shown at right. We have $\tan \phi=\frac{Y Z}{X Z}=\frac{5}{12}$. The Pythagorean Theorem (or knowing the $\{5,12,13\}$ Pythagorean triple) gives us $X Y=13$, so $\sin \phi=\frac{Y Z}{X Y}=\frac{5}{13}$ and $\cos \phi=\frac{X Z}{X Y}=\frac{12}{13}$.

Finally, we have
$$\begin{aligned}
\cos \left(\arcsin \frac{4}{5}+\arctan \frac{5}{12}\right) & =\cos \left(\arcsin \frac{4}{5}\right) \cos \left(\arctan \frac{5}{12}\right)-\sin \left(\arcsin \frac{4}{5}\right) \sin \left(\arctan \frac{5}{12}\right) \\
& =\frac{3}{5} \cdot \frac{12}{13}-\frac{4}{5} \cdot \frac{5}{13} \\
& =\frac{16}{65}
\end{aligned}$$

Problem 3.13: Below is the graph of $y=3 \sin x+4 \cos x$ :

It looks like the graph of a function of the form $a \sin (b x+c)$ ! Why?

Solution for Problem 3.13: The graph appears to have period $2 \pi$ and amplitude 5 , which might make us first guess that it is the graph of $y=5 \sin x$. The given graph doesn't pass through the origin, so it can't be the graph of $y=5 \sin x$; however, it might be the result of shifting the graph of $y=5 \sin x$ horizontally. If so, then it is the graph

97

---

<!-- Page 98 -->

CHAPTER 3. TRIGONOMETRIC IDENTITIES

of $y=5 \sin (x+\theta)$ for some angle $\theta$. If this graph is also the graph of $y=3 \sin x+4 \cos x$, then we must have
$$5 \sin (x+\theta)=3 \sin x+4 \cos x$$
for all $x$. Is that possible? Is there any value of $\theta$ for which this is true?
It's not clear how we could isolate $\theta$, but we can at least isolate $\sin (x+\theta)$ by dividing both sides by 5 , which gives
$$\sin (x+\theta)=\frac{3}{5} \sin x+\frac{4}{5} \cos x$$

Aha! We saw $\frac{3}{5}$ and $\frac{4}{5}$ in the previous problem. We have $\left(\frac{3}{5}\right)^{2}+\left(\frac{4}{5}\right)^{2}=1$, so we can view $\frac{3}{5}$ and $\frac{4}{5}$ as the cosine and sine of some angle. Using our identity for $\sin (x+\theta)$ tells us just what angle:
$$\sin (x+\theta)=\sin x \cos \theta+\sin \theta \cos x$$

So, if we let $\theta=\arccos \frac{3}{5}$, which means $\cos \theta=\frac{3}{5}$ and $\sin \theta=\frac{4}{5}$, then we do have $\sin (x+\theta)=\frac{3}{5} \sin x+\frac{4}{5} \cos x$, so
$$5 \sin (x+\theta)=3 \sin x+4 \cos x$$

Mystery solved!
Problem 3.14: Compute $x$ if $\arctan x+\arctan 1=2\left(\arctan x-\arctan \frac{1}{3}\right)$. (Source: ARML)

Solution for Problem 3.14: First, we simplify the equation. We seek $x$; while it isn't immediately obvious how to isolate $x$, we can isolate $\arctan x$. Doing so gives us
$$\arctan x=\arctan 1+2 \arctan \frac{1}{3}$$

We have $\arctan 1=\frac{\pi}{4}$, which gives us
$$\arctan x=\frac{\pi}{4}+2 \arctan \frac{1}{3}$$

But now what?
We'd like to solve for $x$; now that we've isolated $\arctan x$, we can isolate $x$ by taking the tangent of both sides, which gives us
$$\tan (\arctan x)=\tan \left(\frac{\pi}{4}+2 \arctan \frac{1}{3}\right)$$

By definition, we have $\tan (\arctan x)=x$. We have the tangent of a sum on the right, so we can apply the identity
$$\tan (\alpha+\beta)=\frac{\tan \alpha+\tan \beta}{1-\tan \alpha \tan \beta} .$$

We then have
$$x=\frac{\tan \frac{\pi}{4}+\tan \left(2 \arctan \frac{1}{3}\right)}{1-\tan \frac{\pi}{4} \tan \left(2 \arctan \frac{1}{3}\right)}$$

Since $\tan \frac{\pi}{4}=1$, we have
$$x=\frac{1+\tan \left(2 \arctan \frac{1}{3}\right)}{1-\tan \left(2 \arctan \frac{1}{3}\right)}$$

98

---

<!-- Page 99 -->

3.2. SUMS AND DIFFERENCES OF ANGLES

We're almost there-all we have to do is compute $\tan \left(2 \arctan \frac{1}{3}\right)$. Fortunately, the angle sum identity for tangent can do the job again:
$$\begin{aligned}
\tan \left(2 \arctan \frac{1}{3}\right) & =\tan \left(\arctan \frac{1}{3}+\arctan \frac{1}{3}\right) \\
& =\frac{\tan \left(\arctan \frac{1}{3}\right)+\tan \left(\arctan \frac{1}{3}\right)}{1-\tan \left(\arctan \frac{1}{3}\right) \tan \left(\arctan \frac{1}{3}\right)} \\
& =\frac{\frac{1}{3}+\frac{1}{3}}{1-\frac{1}{3} \cdot \frac{1}{3}} \\
& =\frac{3}{4}
\end{aligned}$$

Now we can find $x$ :
$$x=\frac{1+\tan \left(2 \arctan \frac{1}{3}\right)}{1-\tan \left(2 \arctan \frac{1}{3}\right)}=\frac{1+\frac{3}{4}}{1-\frac{3}{4}}=7$$

Exercises
3.2.1 Use the identities we learned in this section to write each of the following in terms of $\cos \theta, \sin \theta$, or $\tan \theta$.
(a) $\quad \sin (\pi+\theta)$
(c) $\quad \cos (3 \pi-\theta)$
(b) $\quad \cos \left(\frac{\pi}{2}+\theta\right)$
(d) $\quad \tan \left(\theta+\frac{3 \pi}{2}\right)$
3.2.2 Show that $\tan (\alpha-\beta)=\frac{\tan \alpha-\tan \beta}{1+\tan \alpha \tan \beta}$.
3.2.3 Evaluate $\tan 285^{\circ}$.
3.2.4 Prove that $\sin (\alpha-\beta) \sin (\alpha+\beta)=\sin ^{2} \alpha-\sin ^{2} \beta$.
3.2.5 Find all acute angles $x$ such that $\sin 2 x \sin 3 x=\cos 2 x \cos 3 x$. (Source: AHSME)
3.2.6 Angles $A$ and $B$ are acute angles such that $\tan A+\tan B+\tan A \tan B=1$. If $A-B=41^{\circ}$, compute the measure of angle $A$. (Source: NYSML)
3.2.7 Suppose that $\sin a+\sin b=\sqrt{5 / 3}$ and $\cos a+\cos b=1$. What is $\cos (a-b)$ ? (Source: AMC)
3.2.8 ★ In the text, we proved that $\sin (\alpha+\beta)=\sin \alpha \cos \beta+\sin \beta \cos \alpha$ only for the case where $\alpha$ and $\beta$ are acute angles such that $\alpha+\beta$ is also acute. In this problem, we explore the type of careful casework we can use to prove that this identity holds for all angles. We will prove that the identity holds if $\alpha$ and $\beta$ are acute but $\alpha+\beta$ is obtuse.
(a) Let $\gamma=\frac{\pi}{2}-\alpha$ and $\phi=\frac{\pi}{2}-\beta$. Why must $\gamma$ and $\phi$ be acute?
(b) Write $\sin (\alpha+\beta)$ in terms of $\gamma, \phi$, and $\pi$.
(c) Show that $\sin (\alpha+\beta)=\sin (\gamma+\phi)$.
(d) Express $\sin (\gamma+\phi)$ in terms of $\sin \alpha$, $\sin \beta, \cos \alpha$, and $\cos \beta$ to complete the proof of the identity for the case in which $\alpha$ and $\beta$ are acute but $\alpha+\beta$ is obtuse. Why is it important in this step that $\gamma$ and $\phi$ are acute?
(e) ★ Show that the identity holds if $\alpha$ and $\beta$ are both obtuse.

99

---

<!-- Page 100 -->

CHAPTER 3. TRIGONOMETRIC IDENTITIES
3.3 Double and Half Angles

In Problem 3.14, we used the identity for the tangent of a sum of angles to evaluate $\tan \left(2 \arctan \frac{1}{3}\right)$. In other words, we used the angle sum identity to evaluate the tangent of double an angle. Double angles and half angles occur frequently in trigonometry; in this section we develop and apply identities for trig functions of both.

Problems
Problem 3.15: Find $\sin 2 x$ and $\cos 2 x$ in terms of $\sin x$ and $\cos x$. Test your identities by finding $\sin 120^{\circ}$ and $\cos 120^{\circ}$ with them.

Problem 3.16: Find $\tan 2 x$ in terms of $\tan x$.
Problem 3.17: Use your identity for $\cos 2 x$ in Problem 3.15 together with $\sin ^{2} x+\cos ^{2} x=1$ to find $\cos (x / 2)$ and $\sin (x / 2)$ in terms of $\cos x$. Test your identities by finding $\cos 120^{\circ}$ and $\sin 120^{\circ}$ by letting $x=240^{\circ}$ in your identities.

Problem 3.18: Find $\cos 15^{\circ}$ using an identity you found in the previous problem. Compare your answer to the result in Problem 3.11.

Problem 3.19: Show that $\tan \frac{x}{2}=\frac{\sin x}{1+\cos x}=\frac{1-\cos x}{\sin x}$.
Problem 3.20: Compute the number of degrees in the smallest positive angle $x$ that satisfies the equation $8 \sin x \cos ^{5} x-8 \sin ^{5} x \cos x=1$. (Source: ARML)

Problem 3.21: Find $\left(\cos 20^{\circ}\right)\left(\cos 40^{\circ}\right)\left(\cos 80^{\circ}\right)$.

Problem 3.15: Find $\sin 2 x$ and $\cos 2 x$ in terms of $\sin x$ and $\cos x$. Test your identities by finding $\sin 120^{\circ}$ and $\cos 120^{\circ}$ with them.

Solution for Problem 3.15: Applying the angle sum identities for sine and cosine, we have
$$\begin{array}{l}
\sin 2 x=\sin (x+x)=\sin x \cos x+\sin x \cos x=2 \sin x \cos x \\
\cos 2 x=\cos (x+x)=\cos x \cos x-\sin x \sin x=\cos ^{2} x-\sin ^{2} x
\end{array}$$

We can use the identity $\sin ^{2} x+\cos ^{2} x=1$ to write $\cos 2 x$ solely in terms of $\cos x$ or in terms of $\sin x$. Substituting $\cos ^{2} x=1-\sin ^{2} x$ gives
$$\cos 2 x=\cos ^{2} x-\sin ^{2} x=\left(1-\sin ^{2} x\right)-\sin ^{2} x=1-2 \sin ^{2} x$$
and substituting $\sin ^{2} x=1-\cos ^{2} x$ gives
$$\cos 2 x=\cos ^{2} x-\sin ^{2} x=\cos ^{2} x-\left(1-\cos ^{2} x\right)=2 \cos ^{2} x-1$$

We can test these by letting $x=60^{\circ}$. Then, we have $\sin 2 x=\sin 120^{\circ}=\frac{\sqrt{3}}{2}$ and $2 \sin x \cos x=2 \cdot \frac{\sqrt{3}}{2} \cdot \frac{1}{2}=\frac{\sqrt{3}}{2}$. We also have $\cos 2 x=\cos 120^{\circ}=-\frac{1}{2}$ and $\cos ^{2} x-\sin ^{2} x=\frac{1}{4}-\frac{3}{4}=-\frac{1}{2}$. So, both our identities work for $x=120^{\circ}$.

100

---

<!-- Page 101 -->

3.3. DOUBLE AND HALF ANGLES

Problem 3.16: Find $\tan 2 x$ in terms of $\tan x$.

Solution for Problem 3.16: Applying the angle sum identity for tangent, we have
$$\tan 2 x=\tan (x+x)=\frac{\tan x+\tan x}{1-\tan x \tan x}=\frac{2 \tan x}{1-\tan ^{2} x} .$$

\begin{tabular}{|l|l|}
\hline & \begin{tabular}{l}
Important: \\
Double angle identities:
\end{tabular} \\
\hline
\end{tabular}

You'll use these identities enough that they're worth memorizing. (In fact, you'll likely use them so much in this chapter that you'll have them memorized by the end of the chapter.)

Problem 3.17: Find $\cos \frac{x}{2}$ and $\sin \frac{x}{2}$ in terms of $\cos x$.

Solution for Problem 3.17: We don't yet have any identities involving half angles. However, we do have double angle identities, which means we can express a trig function of an angle in terms of trig functions of half that angle. For example, if we start with
$$\sin 2 \theta=2 \sin \theta \cos \theta,$$
and let $\theta=\frac{x}{2}$, we have
$$\sin x=2 \sin \frac{x}{2} \cos \frac{x}{2} .$$

We now have an angle of $\frac{x}{2}$, but we unfortunately have both the cosine and sine of this angle. This happened because our identity for $\sin 2 \theta$ includes both $\sin \theta$ and $\cos \theta$. We'd prefer to use a double angle identity that only has one of $\sin \theta$ or $\cos \theta$, not both. Fortunately, $\cos 2 \theta$ offers such identities:
$$\cos 2 \theta=2 \cos ^{2} \theta-1=1-2 \sin ^{2} \theta$$

Letting $\theta=\frac{x}{2}$ in $\cos 2 \theta=2 \cos ^{2} \theta-1$ gives
$$\cos x=2 \cos ^{2} \frac{x}{2}-1$$

Solving for $\cos \frac{x}{2}$ gives
$$\cos \frac{x}{2}= \pm \sqrt{\frac{1+\cos x}{2}}$$

The ± here does not mean that $\cos \frac{x}{2}$ has two values! It means that we will take either the positive or the negative square root, depending on what quadrant $\frac{x}{2}$ is in. For example, if $x=240^{\circ}$, then $\frac{x}{2}=120^{\circ}$, which is a second quadrant angle. Therefore, $\cos 120^{\circ}$ is negative, and we must take the negative root in the identity. Letting $x=240^{\circ}$ in the identity gives
$$\cos 120^{\circ}=-\sqrt{\frac{1+\cos 240^{\circ}}{2}}=-\sqrt{\frac{1-\frac{1}{2}}{2}}=-\sqrt{\frac{1}{4}}=-\frac{1}{2},$$
as expected.

101

---

<!-- Page 102 -->

CHAPTER 3. TRIGONOMETRIC IDENTITIES

We deal with $\sin \frac{x}{2}$ by letting $\theta=\frac{x}{2}$ in $\cos 2 \theta=1-2 \sin ^{2} \theta$, which gives us
$$\cos x=1-2 \sin ^{2} \frac{x}{2} .$$

Solving for $\sin \frac{x}{2}$ gives
$$\sin \frac{x}{2}= \pm \sqrt{\frac{1-\cos x}{2}} .$$

Once again, the $\pm$ is a reminder that we must take the positive or negative root depending on the quadrant of $\frac{x}{2}$. We again consider the example $x=240^{\circ}$, which makes $\frac{x}{2}=120^{\circ}$, a second quadrant angle for which sine is positive. Therefore, we have
$$\sin 120^{\circ}=\sqrt{\frac{1-\cos 120^{\circ}}{2}}=\sqrt{\frac{1-\left(-\frac{1}{2}\right)}{2}}=\sqrt{\frac{3}{4}}=\frac{\sqrt{3}}{2},$$
as expected.

Let's try putting our half angle identities to work on an angle we can't tackle with the unit circle.
Problem 3.18: Find $\cos 15^{\circ}$ using an identity you found in the previous problem. Compare your answer to the result in Problem 3.11.

Solution for Problem 3.18: Earlier, we used the angle difference identities to find $\cos 15^{\circ}=\cos \left(45^{\circ}-30^{\circ}\right)=\frac{\sqrt{6}+\sqrt{2}}{4}$. We now can use half angle identities to compute $\cos 15^{\circ}$ as $\cos \frac{30^{\circ}}{2}$. Since $15^{\circ}$ is a first quadrant angle, we take the positive root, and we have
$$\cos 15^{\circ}=\cos \frac{30^{\circ}}{2}=\sqrt{\frac{1+\cos 30^{\circ}}{2}}=\sqrt{\frac{1+\frac{\sqrt{3}}{2}}{2}}=\sqrt{\frac{2+\sqrt{3}}{4}}=\frac{\sqrt{2+\sqrt{3}}}{2} .$$

Uh-oh! This doesn't look anything like the result we found with $\cos \left(45^{\circ}-30^{\circ}\right)$. Did we do something wrong?
If we calculate both $\frac{\sqrt{6}+\sqrt{2}}{4}$ and $\frac{\sqrt{2+\sqrt{3}}}{2}$ with a calculator, it appears that the two are equal. They sure don't look equal! To confirm by hand that they are equal, we get rid of some of the square roots by squaring both numbers:
$$\begin{array}{l}
\left(\frac{\sqrt{6}+\sqrt{2}}{4}\right)^{2}=\frac{6+2 \sqrt{6} \sqrt{2}+2}{16}=\frac{8+2 \cdot 2 \sqrt{3}}{16}=\frac{2+\sqrt{3}}{4} \\
\left(\frac{\sqrt{2+\sqrt{3}}}{2}\right)^{2}=\frac{2+\sqrt{3}}{4}
\end{array}$$

Now we see the whole story. Our two results for $\cos 15^{\circ}$ are positive and have equal squares, so the two must be the same.

Problem 3.19: Show that $\tan \frac{x}{2}=\frac{\sin x}{1+\cos x}=\frac{1-\cos x}{\sin x}$.

Solution for Problem 3.19: We already have $\cos \frac{x}{2}$ and $\sin \frac{x}{2}$, so we can find $\tan \frac{x}{2}$ :
$$\tan \frac{x}{2}=\frac{\sin \frac{x}{2}}{\cos \frac{x}{2}}=\frac{ \pm \sqrt{\frac{1-\cos x}{2}}}{ \pm \sqrt{\frac{1+\cos x}{2}}}= \pm \frac{\sqrt{1-\cos x}}{\sqrt{1+\cos x}}$$

102

---

<!-- Page 103 -->

3.3. DOUBLE AND HALF ANGLES

Again, we include $\pm$ to indicate that we we'll use the quadrant of $\frac{x}{2}$ to determine whether to take the positive or the negative result. We can simplify our expression a bit by getting rid of the square root in the denominator. We do so by multiplying the numerator and denominator by $\sqrt{1+\cos x}$. This gives us
$$\begin{aligned}
\tan \frac{x}{2} & = \pm \frac{\sqrt{1-\cos x}}{\sqrt{1+\cos x}} \cdot \frac{\sqrt{1+\cos x}}{\sqrt{1+\cos x}} \\
& = \pm \frac{\sqrt{(1-\cos x)(1+\cos x)}}{1+\cos x} \\
& = \pm \frac{\sqrt{1-\cos ^{2} x}}{1+\cos x}
\end{aligned}$$

We recognize $1-\cos ^{2} x$ as equal to $\sin ^{2} x$, so we can simplify even more:
$$\tan \frac{x}{2}= \pm \frac{\sqrt{1-\cos ^{2} x}}{1+\cos x}= \pm \frac{\sqrt{\sin ^{2} x}}{1+\cos x}= \pm \frac{\sin x}{1+\cos x}$$

We should worry about what happens if the denominator on the right side is 0 . If $1+\cos x=0$, then $\cos x=-1$, which means $x$ is an odd integer multiple of $\pi$. For these values of $x, \tan \frac{x}{2}$ is indeed undefined, because $\cos \frac{x}{2}=0$ whenever $x$ is an odd integer multiple of $\pi$.

We might think we're finished, but then we notice that the problem claims that
$$\tan \frac{x}{2}=\frac{\sin x}{1+\cos x}$$

Our result above has a $\pm$ in front of the right side. Is it true that we can drop the $\pm$ ? The value of $1+\cos x$ is always nonnegative, since $\cos x \geq-1$. So, to compare the sign of $\tan \frac{x}{2}$ to the sign of $\frac{\sin x}{1+\cos x}$, we need only compare the $\operatorname{signs}$ of $\tan \frac{x}{2}$ and $\sin x$. We investigate by considering all possible values of $x$.

If $\sin x=1$ or if $x$ is in the first or second quadrant, then $x=\theta+2 k \pi$ for some integer $k$ and some $\theta$ with $0<\theta<\pi$. Then, $\sin x$ is positive, and $\frac{x}{2}=\frac{\theta}{2}+k \pi$. Since $0<\frac{\theta}{2}<\frac{\pi}{2}$, the angle $\frac{\theta}{2}+k \pi$ is in the first or third quadrant, which means $\tan \frac{x}{2}$ is also positive.

If $\sin x=-1$ or if $x$ is in the third or fourth quadrant, then $x=\theta+2 k \pi$ for some integer $k$ and some $\theta$ with $\pi<\theta<2 \pi$. This means $\sin x$ is negative and $\frac{x}{2}=\frac{\theta}{2}+k \pi$. Since $\frac{\pi}{2}<\frac{\theta}{2}<\pi$, the angle $\frac{\theta}{2}+k \pi$ is in the second or fourth quadrant, which means $\tan \frac{x}{2}$ is also negative.

Finally, we note that if $x$ is an even multiple of $\pi$, then $\tan \frac{x}{2}=0$ and $\sin x=0$. (We noted above that if $x$ is an odd multiple of $\pi$, then both $\tan \frac{x}{2}$ and $(\sin x) /(1+\cos x)$ are undefined.)

The sign of $\tan \frac{x}{2}$ therefore matches that of $\sin x$ for all possible values of $x$ for which $\tan \frac{x}{2}$ is defined, so we have
$$\tan \frac{x}{2}=\frac{\sin x}{1+\cos x}$$

We multiply the numerator and denominator of the right side by $1-\cos x$ to produce the other desired identity:
$$\tan \frac{x}{2}=\frac{\sin x}{1+\cos x} \cdot \frac{1-\cos x}{1-\cos x}=\frac{(\sin x)(1-\cos x)}{1-\cos ^{2} x}=\frac{(\sin x)(1-\cos x)}{\sin ^{2} x}=\frac{1-\cos x}{\sin x} .$$

Extra! Challenge: Prove that
$$\arctan 1+\arctan 2+\arctan 3=\pi$$
by drawing three well-chosen triangles on the Cartesian plane. Answer on page 110.

103

---

<!-- Page 104 -->

CHAPTER 3. TRIGONOMETRIC IDENTITIES

Important: Half angle identities:
$$\begin{aligned}
\cos \frac{\theta}{2} & = \pm \sqrt{\frac{1+\cos \theta}{2}} \\
\sin \frac{\theta}{2} & = \pm \sqrt{\frac{1-\cos \theta}{2}} \\
\tan \frac{\theta}{2} & =\frac{\sin \theta}{1+\cos \theta}=\frac{1-\cos \theta}{\sin \theta}
\end{aligned}$$

The ± symbols on the first two are reminders that we must use the quadrant of $\frac{\theta}{2}$ to determine the appropriate sign.

If you know the double angle identities, then you should be able to quickly derive these half angle identities whenever you need them.

Problem 3.20: Compute the number of degrees in the smallest positive angle $x$ that satisfies the equation $8 \sin x \cos ^{5} x-8 \sin ^{5} x \cos x=1$. (Source: ARML)

Solution for Problem 3.20: Ultimately, our goal is to isolate a trig function, but the expression on the left is pretty complicated. Most intimidating are the fifth powers. We start chipping away at these in the same way we deal with high degree polynomials, by factoring. First, we factor out $8 \sin x \cos x$, and we have
$$8 \sin x \cos x\left(\cos ^{4} x-\sin ^{4} x\right)=1$$

Now, we have a difference of squares: we can factor $\cos ^{4} x-\sin ^{4} x$ as
$$\cos ^{4} x-\sin ^{4} x=\left(\cos ^{2} x\right)^{2}-\left(\sin ^{2} x\right)^{2}=\left(\cos ^{2} x-\sin ^{2} x\right)\left(\cos ^{2} x+\sin ^{2} x\right) .^{2}$$

Moreover, $\cos ^{2} x+\sin ^{2} x=1$, so we have $\cos ^{4} x-\sin ^{4} x=\cos ^{2} x-\sin ^{2} x$, which means
$$8 \sin x \cos x\left(\cos ^{4} x-\sin ^{4} x\right)=8 \sin x \cos x\left(\cos ^{2} x-\sin ^{2} x\right)$$

Our equation now is
$$8 \sin x \cos x\left(\cos ^{2} x-\sin ^{2} x\right)=1$$

We've at least reduced the powers of the trig functions, but we still have some work to do. We'd like to simplify the equation until we have just a single trig function set equal to a constant. We recognize some expressions on the left side that might help us continue simplifying. Specifically, we recognize $\sin x \cos x$ from the double angle identity for sine, and $\cos ^{2} x-\sin ^{2} x$ from the double angle identity for cosine. Applying these identities "in reverse" gives us $\sin x \cos x=\frac{1}{2} \sin 2 x$ and $\cos ^{2} x-\sin ^{2} x=\cos 2 x$. Now, our equation is $8\left(\frac{1}{2} \sin 2 x\right) \cos 2 x=1$, or
$$4 \sin 2 x \cos 2 x=1$$

Once again, we have the product of sine and cosine of the same angle, which makes us think of the double angle identity for sine. We have $\sin 2 x \cos 2 x=\frac{1}{2} \sin 2(2 x)=\frac{1}{2} \sin 4 x$, so now our equation is $4\left(\frac{1}{2} \sin 4 x\right)=1$, or $2 \sin 4 x=1$. Therefore, we have $\sin 4 x=\frac{1}{2}$. We can use what we know about sine to finish. (This is why we wanted to manipulate the equation into a single trig function set equal to a constant.) The smallest positive angle with sine equal to $\frac{1}{2}$ is $30^{\circ}$, so we have $4 x=30^{\circ}$, from which we find $x=\frac{15^{\circ}}{2}$.

The key step in our solution is recognizing that expressions in the problem match the forms of the double angle identities.

Concept: Recognizing the forms of common trigonometric identities can help solve many trigonometric problems.

104

---

<!-- Page 105 -->

3.3. DOUBLE AND HALF ANGLES

Problem 3.21: Find $\left(\cos 20^{\circ}\right)\left(\cos 40^{\circ}\right)\left(\cos 80^{\circ}\right)$.
Solution for Problem 3.21: This problem doesn't match the form of any of our identities, but the facts that $80^{\circ}=2 \cdot 40^{\circ}$ and $40^{\circ}=2 \cdot 20^{\circ}$ make us try applying the double angle identities. We have cosines, so let's try applying the cosine double angle identity to the latter two cosines:
$$\left(\cos 20^{\circ}\right)\left(\cos 40^{\circ}\right)\left(\cos 80^{\circ}\right)=\left(\cos 20^{\circ}\right)\left(2 \cos ^{2} 20^{\circ}-1\right)\left(2 \cos ^{2} 40^{\circ}-1\right) .$$

Yuck. And if we apply this again to the $\cos 40^{\circ}$ on the right, it will get even uglier.
Back to the drawing board. Those angles really make us want to use the double angle identities. The cosine double angle identity was a loser, but there is a cosine in the sine double angle identity. For example, we have
$$\sin 40^{\circ}=2 \cos 20^{\circ} \sin 20^{\circ},$$
so $\cos 20^{\circ}=\frac{\sin 40^{\circ}}{2 \sin 20^{\circ}}$. Making this substitution gives us
$$\left(\cos 20^{\circ}\right)\left(\cos 40^{\circ}\right)\left(\cos 80^{\circ}\right)=\left(\frac{\sin 40^{\circ}}{2 \sin 20^{\circ}}\right)\left(\cos 40^{\circ}\right)\left(\cos 80^{\circ}\right)=\frac{\left(\sin 40^{\circ}\right)\left(\cos 40^{\circ}\right)\left(\cos 80^{\circ}\right)}{2 \sin 20^{\circ}} .$$

At first, this doesn't look helpful, but then we see the product of sine and cosine of the same angle, which means we can use the sine double angle identity again. Running this identity "in reverse," as in Problem 3.20, we have $\left(\sin 40^{\circ}\right)\left(\cos 40^{\circ}\right)=\frac{\sin 80^{\circ}}{2}$, so we have
$$\left(\cos 20^{\circ}\right)\left(\cos 40^{\circ}\right)\left(\cos 80^{\circ}\right)=\frac{\left(\sin 40^{\circ}\right)\left(\cos 40^{\circ}\right)\left(\cos 80^{\circ}\right)}{2 \sin 20^{\circ}}=\frac{\left(\sin 80^{\circ}\right)\left(\cos 80^{\circ}\right)}{4 \sin 20^{\circ}} .$$

We can do it again! Since $\left(\sin 80^{\circ}\right)\left(\cos 80^{\circ}\right)=\frac{1}{2} \sin 160^{\circ}$, we have
$$\left(\cos 20^{\circ}\right)\left(\cos 40^{\circ}\right)\left(\cos 80^{\circ}\right)=\frac{\left(\sin 80^{\circ}\right)\left(\cos 80^{\circ}\right)}{4 \sin 20^{\circ}}=\frac{\sin 160^{\circ}}{8 \sin 20^{\circ}} .$$

Now we need to relate $\sin 160^{\circ}$ and $\sin 20^{\circ}$. We got this far by recognizing relationships among angles in the problem. We do the same here. We note that $160^{\circ}+20^{\circ}=180^{\circ}$. So, we apply the identity $\sin \left(180^{\circ}-x\right)=\sin x$ to see that $\sin 160^{\circ}=\sin 20^{\circ}$, which means these two cancel in the fraction above and leave the surprising result
$$\left(\cos 20^{\circ}\right)\left(\cos 40^{\circ}\right)\left(\cos 80^{\circ}\right)=\frac{1}{8} .$$

Concept: Recognizing relationships among angles in a complicated trig expression can help
simplify the expression.

Exercises
3.3.1 Evaluate $\sin 22.5^{\circ}$.
3.3.2 If $\sin \theta=\frac{1}{4}$, then what is $\cos 2 \theta$ ?
3.3.3 Prove that $\sin 2 x=\frac{2 \tan x}{1+\tan ^{2} x}$ for all $x$ for which $\tan x$ is defined.
3.3.4 Show that $\tan x+\cot x=2 \csc 2 x$.

105

---

<!-- Page 106 -->

CHAPTER 3. TRIGONOMETRIC IDENTITIES
3.3.5 If $-\pi / 2<A<\pi / 2$ and $A \neq-\pi / 4$, then prove that $\frac{\sin 2 A-\cos 2 A+1}{\sin 2 A+\cos 2 A+1}=\tan A$. (Source: CEMC)
3.3.6 If $\sin 2 \theta=21 / 25$ and $\cos \theta>\sin \theta$, then compute $\cos \theta-\sin \theta$. (Source: Mandelbrot)
3.3.7 Solve the equation $\cos \theta+\sin \theta=\sqrt{3 / 2}$ for $0 \leq \theta<2 \pi$.
3.3.8 In this problem, we prove the triple angle identities for sine and cosine.
(a) Prove that $\cos 3 \theta=4 \cos ^{3} \theta-3 \cos \theta$ for all angles $\theta$.
(b) Find a similar identity for $\sin 3 \theta$ by expressing $\sin 3 \theta$ in terms of $\sin \theta$.
(c) ★ Suppose $\frac{\cos 3 x}{\cos x}=\frac{1}{3}$ for some angle $x$, with $0 \leq x \leq \frac{\pi}{2}$. Determine $\frac{\sin 3 x}{\sin x}$. (Source: USAMTS)
3.4 Sum-to-product and Product-to-sum

Problems

Problem 3.22:
(a) Express $\cos \alpha \cos \beta$ in terms of $\cos (\alpha+\beta)$ and $\cos (\alpha-\beta)$.
(b) Find a similar identity for $\sin \alpha \sin \beta$.
(c) Find a similar identity for $\sin \alpha \cos \beta$.

Problem 3.23: In Problem 3.21, we proved that $\left(\cos 20^{\circ}\right)\left(\cos 40^{\circ}\right)\left(\cos 80^{\circ}\right)=\frac{1}{8}$ using double angle identities. Use one of the identities from Problem 3.22 to find another proof.

Problem 3.24:
(a) Use an identity from Problem 3.22 to show that $\cos x+\cos y=2 \cos \left(\frac{x+y}{2}\right) \cos \left(\frac{x-y}{2}\right)$.
(b) Find a similar identity to that in part (a) for $\cos x-\cos y$.
(c) Find identities for $\sin x+\sin y$ and $\sin x-\sin y$.

Problem 3.25: Compute $\frac{\sin 13^{\circ}+\sin 47^{\circ}+\sin 73^{\circ}+\sin 107^{\circ}}{\cos 17^{\circ}}$. (Source: ARML)

Problem 3.22:
(a) Express $\cos \alpha \cos \beta$ in terms of $\cos (\alpha+\beta)$ and $\cos (\alpha-\beta)$.
(b) Find a similar identity for $\sin \alpha \sin \beta$.
(c) Find a similar identity for $\sin \alpha \cos \beta$.

Solution for Problem 3.22:
(a) We first write out the angle sum and angle difference identities for cosine:
$$\begin{array}{l}
\cos (\alpha+\beta)=\cos \alpha \cos \beta-\sin \alpha \sin \beta \\
\cos (\alpha-\beta)=\cos \alpha \cos \beta+\sin \alpha \sin \beta
\end{array}$$

106

---

<!-- Page 107 -->

3.4. SUM-TO-PRODUCT AND PRODUCT-TO-SUM

Adding them cancels $\sin \alpha \sin \beta$ and leaves us with $\cos (\alpha+\beta)+\cos (\alpha-\beta)=2 \cos \alpha \cos \beta$. Dividing by 2 gives
$$\cos \alpha \cos \beta=\frac{1}{2}(\cos (\alpha+\beta)+\cos (\alpha-\beta)) .$$
(b) If we subtract $\cos (\alpha-\beta)$ from $\cos (\alpha+\beta)$ instead of adding, then we cancel $\cos \alpha \cos \beta$, and leave
$$\cos (\alpha+\beta)-\cos (\alpha-\beta)=-2 \sin \alpha \sin \beta .$$

Dividing by -2 gives
$$\sin \alpha \sin \beta=\frac{1}{2}(\cos (\alpha-\beta)-\cos (\alpha+\beta)) .$$
(c) We don't have a product of sine and cosine in our angle sum or difference identities for cosine, but we do have them in the corresponding sine identities:
$$\begin{array}{l}
\sin (\alpha+\beta)=\sin \alpha \cos \beta+\sin \beta \cos \alpha \\
\sin (\alpha-\beta)=\sin \alpha \cos \beta-\sin \beta \cos \alpha
\end{array}$$

Adding these and dividing by 2 gives us
$$\sin \alpha \cos \beta=\frac{1}{2}(\sin (\alpha+\beta)+\sin (\alpha-\beta)) .$$

We call the identities we found in Problem 3.22 product-to-sum and product-to-difference identities.

Important: Product-to-sum and product-to-difference identities:
$$\begin{aligned}
\cos \alpha \cos \beta & =\frac{1}{2}(\cos (\alpha+\beta)+\cos (\alpha-\beta)) \\
\sin \alpha \sin \beta & =\frac{1}{2}(\cos (\alpha-\beta)-\cos (\alpha+\beta)) \\
\sin \alpha \cos \beta & =\frac{1}{2}(\sin (\alpha+\beta)+\sin (\alpha-\beta))
\end{aligned}$$

Again, there's nothing to memorize here: these are a quick, direct result of the angle sum and angle difference identities. The main idea here is that we can turn a product of cosines or sines into a sum or difference. Sometimes this can be particularly convenient, especially when applying the identity gives us angles we know how to handle.

Problem 3.23: In Problem 3.21, we proved that $\left(\cos 20^{\circ}\right)\left(\cos 40^{\circ}\right)\left(\cos 80^{\circ}\right)=\frac{1}{8}$ using double angle identities. Use one of the identities from Problem 3.22 to find another proof.

Solution for Problem 3.23: We now have an identity for the product of two cosines, but in this problem, we have the product of three cosines. To which two should we apply the identity?

Concept: If a problem involves the product of sines and/or cosines of angles with a convenient sum or difference, consider the product-to-sum identities.

We apply the identity to $\left(\cos 40^{\circ}\right)\left(\cos 80^{\circ}\right)$, since the angles in these have sum $120^{\circ}$, which we know to handle inside trig functions. (See if you can find another solution by applying a product-to-sum identity to $\left(\cos 20^{\circ}\right)\left(\cos 40^{\circ}\right)$.) We have
$$\left(\cos 80^{\circ}\right)\left(\cos 40^{\circ}\right)=\frac{1}{2}\left(\cos \left(80^{\circ}-40^{\circ}\right)+\cos \left(80^{\circ}+40^{\circ}\right)\right)=\frac{1}{2}\left(\cos 40^{\circ}+\cos 120^{\circ}\right)=\frac{1}{2}\left(\cos 40^{\circ}-\frac{1}{2}\right),$$

107

---

<!-- Page 108 -->

CHAPTER 3. TRIGONOMETRIC IDENTITIES

so now we have
$$\left(\cos 20^{\circ}\right)\left(\cos 40^{\circ}\right)\left(\cos 80^{\circ}\right)=\frac{1}{2}\left(\cos 20^{\circ}\right)\left(\cos 40^{\circ}-\frac{1}{2}\right) .$$

If we expand the product on the right, we'll have another product of cosines with a convenient sum.

Concept: If a tactic makes some progress on a problem, but doesn't entirely solve it, look for a way to use the tactic again.

Expanding the product gives us
$$\left(\cos 20^{\circ}\right)\left(\cos 40^{\circ}\right)\left(\cos 80^{\circ}\right)=\frac{1}{2}\left(\cos 20^{\circ}\right)\left(\cos 40^{\circ}-\frac{1}{2}\right)=\frac{1}{2}\left(\left(\cos 40^{\circ}\right)\left(\cos 20^{\circ}\right)-\frac{1}{2} \cos 20^{\circ}\right) .$$

Applying a product-to-sum identity to $\left(\cos 40^{\circ}\right)\left(\cos 20^{\circ}\right)$ gives
$$\left(\cos 40^{\circ}\right)\left(\cos 20^{\circ}\right)=\frac{1}{2}\left(\cos \left(40^{\circ}+20^{\circ}\right)+\cos \left(40^{\circ}-20^{\circ}\right)\right)=\frac{1}{2}\left(\frac{1}{2}+\cos 20^{\circ}\right),$$
so we now have
$$\begin{aligned}
\left(\cos 20^{\circ}\right)\left(\cos 40^{\circ}\right)\left(\cos 80^{\circ}\right) & =\frac{1}{2}\left(\left(\cos 40^{\circ}\right)\left(\cos 20^{\circ}\right)-\frac{1}{2} \cos 20^{\circ}\right) \\
& =\frac{1}{2}\left(\frac{1}{2}\left(\frac{1}{2}+\cos 20^{\circ}\right)-\frac{1}{2} \cos 20^{\circ}\right) \\
& =\frac{1}{2}\left(\frac{1}{4}+\frac{1}{2} \cos 20^{\circ}-\frac{1}{2} \cos 20^{\circ}\right) \\
& =\frac{1}{8}
\end{aligned}$$

The two very different-looking proofs of $\left(\cos 20^{\circ}\right)\left(\cos 40^{\circ}\right)\left(\cos 80^{\circ}\right)=\frac{1}{8}$ exemplify how deeply related trigonometric identities are to each other. Many trig problems can be solved in a variety of ways using different combinations of identities, so don't get locked into looking for the solution-there may be several approaches that work.

Problem 3.24:
(a) Use an identity from Problem 3.22 to show that $\cos x+\cos y=2 \cos \left(\frac{x+y}{2}\right) \cos \left(\frac{x-y}{2}\right)$.
(b) Find an identity similar to that in part (a) for $\cos x-\cos y$.
(c) Find identities for $\sin x+\sin y$ and $\sin x-\sin y$.

Solution for Problem 3.24:
(a) We already have an identity that relates a product of cosines to a sum of cosines: our product-to-sum identity. We'll write it with the sum isolated on the left, since that's the form of the desired identity in this problem:
$$\cos (\alpha+\beta)+\cos (\alpha-\beta)=2 \cos \alpha \cos \beta$$

To convert this to an identity for $\cos x+\cos y$, we simply let $\alpha+\beta=x$ and $\alpha-\beta=y$. Adding these gives $2 \alpha=x+y$, so $\alpha=(x+y) / 2$. Subtracting $\alpha-\beta=y$ from $\alpha+\beta=x$ gives $\beta=(x-y) / 2$. Substituting these expressions for $\alpha$ and $\beta$ in the identity above gives the desired
$$\cos x+\cos y=2 \cos \left(\frac{x+y}{2}\right) \cos \left(\frac{x-y}{2}\right) .$$

108

---

<!-- Page 109 -->

3.4. SUM-TO-PRODUCT AND PRODUCT-TO-SUM
(b) The previous part gives us a clear path to find an identity for $\cos x-\cos y$. We start with
$$\cos (\alpha-\beta)-\cos (\alpha+\beta)=2 \sin \alpha \sin \beta .$$

Substituting $x=\alpha+\beta$ and $y=\alpha-\beta$ in this identity, so that $\alpha=(x+y) / 2$ and $\beta=(x-y) / 2$ as before, gives us
$$\cos y-\cos x=2 \sin \left(\frac{x+y}{2}\right) \sin \left(\frac{x-y}{2}\right),$$
or
$$\cos x-\cos y=-2 \sin \left(\frac{x+y}{2}\right) \sin \left(\frac{x-y}{2}\right) .$$
(c) For these, we turn to the product-to-sum identity that features a sum of sines. As before, we isolate the sum on the left:
$$\sin (\alpha+\beta)+\sin (\alpha-\beta)=2 \sin \alpha \cos \beta .$$

Once again, we use the substitution $x=\alpha+\beta$ and $y=\alpha-\beta$, so $\alpha=(x+y) / 2$ and $\beta=(x-y) / 2$, and we have
$$\sin x+\sin y=2 \sin \left(\frac{x+y}{2}\right) \cos \left(\frac{x-y}{2}\right) .$$

We don't have an identity with a difference of sines among those we found in Problem 3.22, but we can convert the sine sum above to a sine difference by noting that $\sin (-z)=-\sin z$. So, letting $y=-z$ in the sine sum identity above gives us
$$\sin x-\sin z=2 \sin \left(\frac{x-z}{2}\right) \cos \left(\frac{x+z}{2}\right) .$$

Important: Sum-to-product and difference-to-product identities:
$$\begin{array}{l}
\cos x+\cos y=2 \cos \left(\frac{x+y}{2}\right) \cos \left(\frac{x-y}{2}\right) \\
\cos x-\cos y=-2 \sin \left(\frac{x+y}{2}\right) \sin \left(\frac{x-y}{2}\right) \\
\sin x+\sin y=2 \sin \left(\frac{x+y}{2}\right) \cos \left(\frac{x-y}{2}\right) \\
\sin x-\sin y=2 \sin \left(\frac{x-y}{2}\right) \cos \left(\frac{x+y}{2}\right)
\end{array}$$

As with many of the other identities we've studied, you don't need to memorize these. We've seen that these are a direct result of the product-to-sum and product-to-difference identities, which are in turn a straightforward manipulation of the angle sum and angle difference identities.

Problem 3.25: Compute $\frac{\sin 13^{\circ}+\sin 47^{\circ}+\sin 73^{\circ}+\sin 107^{\circ}}{\cos 17^{\circ}}$. (Source: ARML)
Solution for Problem 3.25: This is a natural candidate for sum-to-product identities, both because we have a sum of sines in the numerator, and because the angles have convenient sums. But how should we pair up the sines to apply the sum of sines identity? We could pair the first two and the last two, since $13^{\circ}+47^{\circ}=60^{\circ}$ and $73^{\circ}+107^{\circ}=180^{\circ}$, or we could pair the outer two and the inner two, since $13^{\circ}+107^{\circ}=47^{\circ}+73^{\circ}=120^{\circ}$. Looking at the differences of the paired angles gives us the answer. In our first option, these differences are both $34^{\circ}$, while in the second option, we have $107-13^{\circ}=94^{\circ}$ and $73^{\circ}-47^{\circ}=26^{\circ}$. While $34^{\circ}, 94^{\circ}$, and $26^{\circ}$ are all inconvenient, we do note that $34^{\circ}$ is double the $17^{\circ}$ in the denominator.

109

---

<!-- Page 110 -->

CHAPTER 3. TRIGONOMETRIC IDENTITIES

Concept: In problems involving several trig functions of inconvenient angles, look for relationships among the angles.

Applying the sine sum-to-product identities to $\sin 13^{\circ}+\sin 47^{\circ}$ and $\sin 73^{\circ}+\sin 107^{\circ}$, we have
$$\begin{aligned}
\frac{\sin 13^{\circ}+\sin 47^{\circ}+\sin 73^{\circ}+\sin 107^{\circ}}{\cos 17^{\circ}} & =\frac{2 \sin 30^{\circ} \cos 17^{\circ}+2 \sin 90^{\circ} \cos 17^{\circ}}{\cos 17^{\circ}} \\
& =\frac{\cos 17^{\circ}\left(2 \cdot \frac{1}{2}+2 \cdot 1\right)}{\cos 17^{\circ}} \\
& =3 .
\end{aligned}$$

Exercises
3.4.1 Show that $(\cos 4 x-\cos 2 x) /(2 \sin 3 x)=-\sin x$ for all $x$ such that $\sin 3 x \neq 0$.
3.4.2 Find the acute angle $\theta$ such that $\cos 27^{\circ}+\cos 33^{\circ}=\sqrt{3} \cos \theta$.
3.4.3 Consider the following two identities:
$$\begin{array}{l}
\sin (\alpha+\beta)=\sin \alpha \cos \beta+\sin \beta \cos \alpha \\
\sin (\alpha-\beta)=\sin \alpha \cos \beta-\sin \beta \cos \alpha
\end{array}$$

If we subtract the second equation from the first, we get an identity for $\sin \beta \cos \alpha$. But we already have an identity for $\sin \alpha \cos \beta$, and it doesn't look just like the result we get for $\sin \beta \cos \alpha$ when we subtract above. Explain.
3.4.4 Express
$$\frac{\sin 10^{\circ}+\sin 20^{\circ}+\sin 30^{\circ}+\sin 40^{\circ}+\sin 50^{\circ}+\sin 60^{\circ}+\sin 70^{\circ}+\sin 80^{\circ}}{\cos 5^{\circ} \cos 10^{\circ} \cos 20^{\circ}}$$
without using trigonometric functions. (Source: HMMT)
3.4.5 Prove that
$$4 \sin A \sin B \sin C=-\sin (A+B+C)+\sin (B+C-A)+\sin (C+A-B)+\sin (A+B-C)$$
for all angles $A, B$, and $C$.
3.4.6★ Find the smallest positive integer solution to
$$\tan 19 x^{\circ}=\frac{\cos 96^{\circ}+\sin 96^{\circ}}{\cos 96^{\circ}-\sin 96^{\circ}}$$
(Source: AIME) Hints: 282, 24

Extra! The diagram at right can be used to prove that
$$\arctan 1+\arctan 2+\arctan 3=\pi .$$

Don't see how? Here's a hint: All three triangles are right triangles, and all three have an acute angle with a vertex at $(0,1)$. What is the tangent of each of these acute angles?

110

---

<!-- Page 111 -->

3.4. SUM-TO-PRODUCT AND PRODUCT-TO-SUM

Sidenote: Loosely speaking, sound is caused by vibrations that are sinusoidal in nature; these cause what are called sound waves. These waves have an amplitude (which is related to the volume of the sound) and a frequency. The frequency of a sound is related to the pitch of the sound, which is how high or low the sound is. As we noted on page 61, the frequency of a sinusoidal function of time is the reciprocal of the function's period. So, the period of a sound wave is related to the pitch of the sound.

If you've ever tuned a guitar by striking two strings and listening to how the sounds they make interact, you've heard the sum-to-product rule in action. If the guitar is in tune, then you hear a nice, even sound. But if you have the guitar very nearly in tune, but not quite, then the sound oscillates. If the guitar is further out of tune, then the sound oscillates a little more. Let's see if we can explain what's going here.

Each string produces a sound wave that is of the form $f(t)=\sin a t$ for some constant $a$. If the guitar is perfectly in tune, then the two waves don't interfere at all, and you hear a nice, smooth sound. We can get an example of what happens here by looking at the graph of $y=\sin 30 x+\sin 30 x$ :

Figure 3.6: Graph of $y=\sin 30 x+\sin 30 x$

That's a nice, smooth, even sound-the amplitude of the wave is constant throughout. But what happens if they are a little off? Below is the graph of $y=\sin 31 x+\sin 29 x$ :

Figure 3.7: Graph of $y=\sin 31 x+\sin 29 x$

Here, we can see what you hear when the strings are just a little bit out of tune. Instead of a nice, even oscillation, there is an overall up and down to the intensity of the sound. When the strings are a little more out of tune, this up and down happens more quickly, so the sound oscillates faster. Let's graph $y=\sin 32 x+\sin 28 x$ to get a picture of what's happening:

Figure 3.8: Graph of $y=\sin 32 x+\sin 28 x$

See if you can use the sum-to-product identity to figure out what's going on here. Answer on page 127

111

---

<!-- Page 112 -->

CHAPTER 3. TRIGONOMETRIC IDENTITIES

$3.5 \star$ Problem Solving with Identities
We've solved a number of challenging problems with trig identities. In each case, the section in which the problem appeared gave us a very convenient hint which identity to try. In this section, we tackle problems without this helping hand, and in doing so, learn some strategies for determining which identity will be helpful on a given problem.

There are no guiding parts on the problems in this section, but we have provided hints that you can look up in the back of the book if you get stuck.

Problems
Problem 3.26: Determine $A+B$ if $A$ and $B$ are acute angles such that
$$\sin A+\sin B=\sqrt{\frac{3}{2}} \quad \text { and } \quad \cos A-\cos B=\sqrt{\frac{1}{2}}$$
(Source: COMC) Hints: 84
Problem 3.27: Find the sum of the roots of $\tan ^{2} x-9 \tan x+1=0$ that are between $x=0$ and $x=2 \pi$ radians. (Source: AHSME) Hints: 137, 225

Problem 3.28: Let $a=\pi / 2008$. Find the smallest positive integer $n$ such that
$$2\left[\cos a \sin a+\cos 4 a \sin 2 a+\cos 9 a \sin 3 a+\cdots+\cos \left(n^{2} a\right) \sin (n a)\right]$$
is an integer. (Source: AIME) Hints: 189, 195
Problem 3.29: Let $a, b, c, d$ be positive real numbers such that
$$\begin{array}{l}
a^{2}+b^{2}=1 \\
c^{2}+d^{2}=1 \\
a c-b d=\frac{1}{2}
\end{array}$$

Calculate $a d+b c$. (Source: Mandelbrot) Hints: 79
Problem 3.30: Evaluate
$$\frac{\cos 1^{\circ}+\cos 2^{\circ}+\cos 3^{\circ}+\cdots+\cos 43^{\circ}+\cos 44^{\circ}}{\sin 1^{\circ}+\sin 2^{\circ}+\sin 3^{\circ}+\cdots+\sin 43^{\circ}+\sin 44^{\circ}} .$$
(Source: AIME) Hints: 103
Problem 3.31: Given any seven real numbers, prove that there are two of them, $x$ and $y$, such that
$$0 \leq \frac{x-y}{1+x y} \leq \frac{1}{\sqrt{3}} .$$
(Source: Canada) Hints: 212
Problem 3.32: Evaluate $\left(\sin 1^{\circ}\right)\left(\sin 3^{\circ}\right)\left(\sin 5^{\circ}\right) \cdots\left(\sin 177^{\circ}\right)\left(\sin 179^{\circ}\right)$. Hints: 29

112

---

<!-- Page 113 -->

$3.5 \star$. PROBLEM SOLVING WITH IDENTITIES

Problem 3.26: Determine $A+B$ if $A$ and $B$ are acute angles such that
$$\sin A+\sin B=\sqrt{\frac{3}{2}} \quad \text { and } \quad \cos A-\cos B=\sqrt{\frac{1}{2}} .$$
(Source: COMC)

Solution for Problem 3.26: Our first instinct might be to try sum-to-product and difference-to-product identities since we have a sum of sines and a difference of cosines. Applying these identities to each equation gives
$$\begin{aligned}
2 \sin \left(\frac{A+B}{2}\right) \cos \left(\frac{A-B}{2}\right) & =\sqrt{\frac{3}{2}} \\
-2 \sin \left(\frac{A+B}{2}\right) \sin \left(\frac{A-B}{2}\right) & =\sqrt{\frac{1}{2}}
\end{aligned}$$

Uh-oh. It's not so clear what to do with that. We want $A+B$, but dividing the first equation by the second eliminates the terms involving $A+B$. It's not at all clear how we can get rid of the terms involving $A-B$. Let's look around for something different before trying to force this to work.

Concept: Don't get locked into one way of attacking a problem-look for several starting
points, go a little ways down each path, and then choose the one that looks most fruitful.

We expect that we'll have to combine the equations in some way, but it's not obvious that adding or multiplying them will do any good. We need some way to conveniently combine the sines and cosines, which brings us back to $\sin ^{2} \theta+\cos ^{2} \theta=1$. The square roots on the right sides of the original equations are another reason we might think of this identity, since squaring each equation will get rid of the square roots. We're not sure what we'll do with the other terms that squaring produces, but maybe it will all work out in the end.

Squaring each equation gives:
$$\begin{aligned}
\sin ^{2} A+2 \sin A \sin B+\sin ^{2} B & =\frac{3}{2} \\
\cos ^{2} A-2 \cos A \cos B+\cos ^{2} B & =\frac{1}{2}
\end{aligned}$$

Adding these allows us to use $\sin ^{2} A+\cos ^{2} A=\sin ^{2} B+\cos ^{2} B=1$, and we have
$$2+2 \sin A \sin B-2 \cos A \cos B=2,$$
so $\sin A \sin B-\cos A \cos B=0$. This is promising, because we're looking for $A+B$, and the left side looks a lot like the identity for $\cos (A+B)$. Writing out that identity, we see that
$$\cos (A+B)=\cos A \cos B-\sin A \sin B=-(\sin A \sin B-\cos A \cos B),$$
and we just showed that the final expression on the right equals 0 . Therefore, we have $\cos (A+B)=0$. Since $A$ and $B$ are acute, we must have $0^{\circ}<A+B<180^{\circ}$, so $A+B=90^{\circ}$.

Taking a couple different first steps helped us avoid getting stuck. We weren't sure that either one of these would solve the problem, but they both initially looked promising. So, we took them both, and found that one of them gave us a result that we could use to solve the problem. (Our "failed" start will work, too, but it's quite a bit more work-see if you can figure out how.)

113

---

<!-- Page 114 -->

CHAPTER 3. TRIGONOMETRIC IDENTITIES

This problem was also a good example of a very common strategy in dealing with trig identities:
Problem 3.27: Find the sum of the roots of $\tan ^{2} x-9 \tan x+1=0$ that are between $x=0$ and $x=2 \pi$ radians. (Source: AHSME)

Solution for Problem 3.27: Solution 1: Sines and cosines.

> Concept: When in doubt in a trig problem involving functions other than sine and cosine, try converting everything to sine and cosine.

Writing the equation in terms of sine and cosine gives
$$\frac{\sin ^{2} x}{\cos ^{2} x}-\frac{9 \sin x}{\cos x}+1=0$$

Multiplying both sides by $\cos ^{2} x$ gets rid of the fractions, and gives
$$\sin ^{2} x-9 \sin x \cos x+\cos ^{2} x=0 .$$

Aha! There's that $\sin ^{2} x+\cos ^{2} x$ again. Since this equals 1, we have $1-9 \sin x \cos x=0$, which means $\sin x \cos x=\frac{1}{9}$. We recognize the left side as $\frac{\sin 2 x}{2}$, so our equation now is $\sin 2 x=\frac{2}{9}$. What's wrong with this finish:

> Bogus Solution: From $\sin 2 x=\frac{2}{9}$, we have $2 x=\arcsin \frac{2}{9}$, so the only solution to the original equation is $x=\frac{1}{2} \arcsin \frac{2}{9}$.

The problem here is that $\arcsin \frac{2}{9}$ is not the only value of $2 x$ such that $\sin 2 x=\frac{2}{9}$. What is wrong with this solution:

Alas, this is another convincing-but-wrong solution. It is true that there are only two angles from 0 to $2 \pi$ whose sines equal $\frac{2}{9}$. However, we are told that the sine of $2 x$ is $\frac{2}{9}$. Since $0 \leq x \leq 2 \pi$, we have $0 \leq 2 x \leq 4 \pi$. Therefore, in addition to the two values of $2 x$ we found in the second Bogus Solution, we also have two more between $2 \pi$ and $4 \pi$. We get these values of $2 x$ simply by adding $2 \pi$ to the values we already found, since $\sin (\theta+2 \pi)=\sin \theta$ for all

114

---

<!-- Page 115 -->

3.5★. PROBLEM SOLVING WITH IDENTITIES

$\theta$. So, these extra two values of $2 x$ are $2 x=2 \pi+\arcsin \frac{2}{9}$ and $2 x=3 \pi-\arcsin \frac{2}{9}$, which give $x=\pi+\frac{1}{2} \arcsin \frac{2}{9}$ and $x=\frac{3 \pi}{2}-\frac{1}{2} \arcsin \frac{2}{9}$, respectively. The sum of these two solutions for $x$ is $\frac{5 \pi}{2}$, and adding this to the sum of the first two solutions we found gives a total of $\frac{5 \pi}{2}+\frac{\pi}{2}=3 \pi$.

Solution 2: It's a quadratic in disguise! The given equation is quadratic in $\tan x$. To see this, we let $z=\tan x$, which gives us $z^{2}-9 z+1=0$. The quadratic formula then gives
$$\tan x=z=\frac{9 \pm \sqrt{81-4}}{2}=\frac{9 \pm \sqrt{77}}{2} .$$

Good luck finding the angles whose tangents equal those numbers without a calculator. We can at least tell that $\tan x$ is positive, which means that there are first and third quadrant angles that are solutions. But it doesn't appear to tell us much more. Maybe this is a dead end.

Looking back at the quadratic, we notice that the coefficients of the quadratic term and the constant term are both 1 . This means that the product of the roots is 1 . To see why, suppose the roots are $r$ and $s$. Then, we can factor the quadratic as $(z-r)(z-s)$. Expanding this product gives $z^{2}-(r+s) z+r s$. If this equals $z^{2}-9 z+1$, then we must have $r s=1$.

But how does this help? All it tells us is that the roots of the equation are reciprocals. In other words, if $\tan \theta$ is one solution, then $1 / \tan \theta$ is the other solution. But $1 / \tan \theta$ is $\cot \theta$, so now we know that we can write the two solutions to $z^{2}-9 z+1=0$ as $\tan \theta$ and $\cot \theta$ for some value of $\theta$. This doesn't tell us what $\theta$ is, but we don't need to know $\theta$. We only need the sum of the possible values of $\theta$.

Since $\cot \theta=\tan \left(\frac{\pi}{2}-\theta\right)$, we can now write the roots of $z^{2}-9 z+1=0$ as $\tan \theta$ and $\tan \left(\frac{\pi}{2}-\theta\right)$ for some value of $\theta$. Success! We only want the sum of the values of $x$ such that $\tan ^{2} x-9 \tan x+1=0$. We just found that if $x=\theta$ is a solution, then so is $x=\frac{\pi}{2}-\theta$. Therefore, the two first quadrant solutions have sum $\frac{\pi}{2}$. Moreover, since $\tan (\pi+\theta)=\tan \theta$, we simply add $\pi$ to $\theta$ and to $\frac{\pi}{2}-\theta$ to get the two third quadrant solutions, $\theta+\pi$ and $\frac{3 \pi}{2}-\theta$. The sum of these is $\frac{5 \pi}{2}$, so the sum of all four solutions is $\frac{\pi}{2}+\frac{5 \pi}{2}=3 \pi$.

Problem 3.28: Let $a=\pi / 2008$. Find the smallest positive integer $n$ such that
$$2\left[\cos a \sin a+\cos 4 a \sin 2 a+\cos 9 a \sin 3 a+\cdots+\cos \left(n^{2} a\right) \sin (n a)\right]$$
is an integer. (Source: AIME)
Solution for Problem 3.28: We don't see a good way to combine terms in the sum, so we turn to our product-to-sum identity for $\cos \alpha \sin \beta$, since that looks like the only tool we can use to get a different look at the problem. Applying this identity to first few terms gives
$$\begin{aligned}
\cos a \sin a & =\frac{1}{2}(\sin (a+a)+\sin (a-a))=\frac{1}{2}(\sin 2 a+\sin 0) \\
\cos 4 a \sin 2 a & =\frac{1}{2}(\sin (2 a+4 a)+\sin (2 a-4 a))=\frac{1}{2}(\sin 6 a+\sin (-2 a)) \\
\cos 9 a \sin 3 a & =\frac{1}{2}(\sin (3 a+9 a)+\sin (3 a-9 a))=\frac{1}{2}(\sin 12 a+\sin (-6 a)) \\
\cos 16 a \sin 4 a & =\frac{1}{2}(\sin (4 a+16 a)+\sin (4 a-16 a))=\frac{1}{2}(\sin 20 a+\sin (-12 a))
\end{aligned}$$

At first, adding these doesn't look promising. If only those negatives inside the sines in the last terms on the right were outside the sines instead-then we'd have a bunch of cancellation when we added.

Concept: Wishful thinking is a powerful problem solving tool—thinking about what you'd like to be true can focus your attention on the key step in a solution.

115

---

<!-- Page 116 -->

CHAPTER 3. TRIGONOMETRIC IDENTITIES

We don't have to just wish that $\sin (-a)=-\sin a$; this is an identity we already proved! So, now we can write the products in our sum as
$$\begin{aligned}
\cos a \sin a & =\frac{1}{2}(\sin 2 a-\sin 0) \\
\cos 4 a \sin 2 a & =\frac{1}{2}(\sin 6 a-\sin 2 a) \\
\cos 9 a \sin 3 a & =\frac{1}{2}(\sin 12 a-\sin 6 a) \\
\cos 16 a \sin 4 a & =\frac{1}{2}(\sin 20 a-\sin 12 a)
\end{aligned}$$

Adding all these will cancel out everything except $\frac{1}{2} \sin 20 a$ and $-\frac{1}{2} \sin 0$. But will this cancellation continue? Will we always be able to cancel part of the $k^{\text {th }}$ term with the term before it? We check by looking at what happens when we apply the product-to-sum identity to the $(k-1)^{\text {th }}$ and $k^{\text {th }}$ terms:
$$\begin{aligned}
\cos (k-1)^{2} a \sin (k-1) a & =\frac{1}{2}\left(\sin \left(k-1+(k-1)^{2}\right) a+\sin \left(k-1-(k-1)^{2}\right) a\right) \\
& =\frac{1}{2}\left(\sin \left(k^{2}-k\right) a+\sin \left(-k^{2}+3 k-2\right) a\right) \\
& =\frac{1}{2}(\sin k(k-1) a-\sin (k-1)(k-2) a) \\
\cos k^{2} a \sin k a & =\frac{1}{2}\left(\sin \left(k+k^{2}\right) a+\sin \left(k-k^{2}\right) a\right)=\frac{1}{2}(\sin (k+1) k a-\sin k(k-1) a)
\end{aligned}$$

Sure enough, we have the expected cancellation when we add these terms, so we see that when we add the entire original series, the only terms that will not cancel are the $-\frac{1}{2} \sin 0$ from $\cos a \sin a$ and $\frac{1}{2} \sin (n+1) n a$ from $\cos n^{2} a \sin a$. Therefore, we have
$$2\left[\cos a \sin a+\cos 4 a \sin 2 a+\cos 9 a \sin 3 a+\cdots+\cos \left(n^{2} a\right) \sin (n a)\right]=2\left(\frac{1}{2} \sin (n+1) n a-\frac{1}{2} \sin 0\right)=\sin (n+1) n a .$$

So, when $a=\pi / 2008$, the original summation equals $\sin \frac{(n+1) n \pi}{2008}$. We seek the smallest positive value of $n$ that makes this expression an integer. The sine of an angle is an integer if and only if the angle is an integer multiple of $\frac{\pi}{2}$. Therefore, $\frac{(n+1) n \pi}{2008}=\frac{k \pi}{2}$ for some integer $k$. Solving for $k$ gives $k=\frac{(n+1) n}{1004}$, so 1004 must evenly divide $(n+1) n$. The prime factorization of 1004 is $2^{2} \cdot 251$, so 251 must evenly divide $n+1$ or $n$. The smallest positive candidate for $n$ is 250 , but then $2^{2}$ doesn't divide $(n+1) n$. The next smallest candidate, $n=251$, works, since $2^{2}$ divides 252 . So, the smallest positive integer $n$ that satisfies the problem is $n=251$.

A series in which part of each term cancels with part of another term in a way that allows us to write the series much more simply is called a telescoping series. A key step in our solution above is realizing that the sum could be written in a form that would "telescope" and leave us a much simpler expression.

Concept: Many series involving trigonometric functions can be written as telescoping series.

Problem 3.29: Let $a, b, c, d$ be positive real numbers such that $a^{2}+b^{2}=1, c^{2}+d^{2}=1$, and $a c-b d=1 / 2$. Calculate $a d+b c$. (Source: Mandelbrot)

Solution for Problem 3.29: The two equations $a^{2}+b^{2}=1$ and $c^{2}+d^{2}=1$ are in the same form as the identity $\sin ^{2} \theta+\cos ^{2} \theta=1$. Since $a, b, c$, and $d$ are positive real numbers that satisfy these two equations, we can make

116

---

<!-- Page 117 -->

3.5★. PROBLEM SOLVING WITH IDENTITIES

the substitutions $a=\sin x, b=\cos x, c=\sin y$, and $d=\cos y$, where $x$ and $y$ are first quadrant angles. With this substitution, we are guaranteed to have $a^{2}+b^{2}=c^{2}+d^{2}=1$. Let's see what this substitution gives us in the third equation:
$$(\sin x)(\sin y)-(\cos x)(\cos y)=\frac{1}{2}$$

We now recognize a trig identity in the third equation as well; we can write the left side as
$$(\sin x)(\sin y)-(\cos x)(\cos y)=-((\cos x)(\cos y)-(\sin x)(\sin y))=-\cos (x+y),$$
so the third equation now is $-\cos (x+y)=\frac{1}{2}$, which gives us $\cos (x+y)=-\frac{1}{2}$. Since $x$ and $y$ are first quadrant angles, we know that $x+y$ is in the first or second quadrant. The only such angle for which $\cos (x+y)=-\frac{1}{2}$ is $120^{\circ}$.

But how does this help with $a d+b c$ ? Let's see what our substitution does to this expression:
$$a d+b c=(\sin x)(\cos y)+(\cos x)(\sin y) .$$

Another trig identity! We have
$$(\sin x)(\cos y)+(\cos x)(\sin y)=\sin (x+y) .$$

Since $x+y=120^{\circ}$, we have $a d+b c=\sin 120^{\circ}=\frac{\sqrt{3}}{2}$.

Concept: Trigonometry can be a powerful tool even in problems that don't appear to be about trigonometry.

A key sign that a trigonometric substitution might be helpful is the presence of an expression or equation that is conspicuously in a form found in a common trig identity.

Problem 3.30: Evaluate
$$\frac{\cos 1^{\circ}+\cos 2^{\circ}+\cos 3^{\circ}+\cdots+\cos 43^{\circ}+\cos 44^{\circ}}{\sin 1^{\circ}+\sin 2^{\circ}+\sin 3^{\circ}+\cdots+\sin 43^{\circ}+\sin 44^{\circ}} .$$
(Source: AIME)

Solution for Problem 3.30: The sum of trig functions suggests the sum-to-product identities, but there are 44 cosines in the numerator-to which pairs should we apply the identities?

Concept: Look for convenient relationships among the angles in trig problems.

The angles can be paired off into sums that equal $45^{\circ}$, which is an angle we know how to handle. Applying the cosine sum-to-product identity to these pairs gives
$$\begin{array}{c}
\cos 44^{\circ}+\cos 1^{\circ}=2 \cos \left(\frac{44^{\circ}+1^{\circ}}{2}\right) \cos \left(\frac{44^{\circ}-1^{\circ}}{2}\right)=2 \cos \frac{45^{\circ}}{2} \cos \frac{43^{\circ}}{2} \\
\cos 43^{\circ}+\cos 2^{\circ}=2 \cos \left(\frac{43^{\circ}+2^{\circ}}{2}\right) \cos \left(\frac{43^{\circ}-2^{\circ}}{2}\right)=2 \cos \frac{45^{\circ}}{2} \cos \frac{41^{\circ}}{2} \\
\cos 42^{\circ}+\cos 3^{\circ}=2 \cos \left(\frac{42^{\circ}+3^{\circ}}{2}\right) \cos \left(\frac{42^{\circ}-3^{\circ}}{2}\right)=2 \cos \frac{45^{\circ}}{2} \cos \frac{39^{\circ}}{2} \\
\vdots \\
\cos 23^{\circ}+\cos 22^{\circ}=2 \cos \left(\frac{23^{\circ}+22^{\circ}}{2}\right) \cos \left(\frac{23^{\circ}-22^{\circ}}{2}\right)=2 \cos \frac{45^{\circ}}{2} \cos \frac{1}{2}^{\circ}
\end{array}$$

117

---

<!-- Page 118 -->

CHAPTER 3. TRIGONOMETRIC IDENTITIES

And when we add all these up, we get... quite a mess. We can handle $\cos \frac{45}{2}^{\circ}$ with the half angle identity, but the rest of those cosines are intimidating.

Concept: When you encounter a nasty complication in a trig problem, and can't find an identity to wipe it out, look for something else in the problem to do the dirty work for you.

We could try pairing the cosines off again, but that will generate even more angles we don't know how to handle. (Try it and see.) Let's at least take a look at what happens with the sines in the denominator when we apply the sum-to-product identities. Maybe it will all work out in the end:
$$\begin{array}{c}
\sin 44^{\circ}+\sin 1^{\circ}=2 \sin \left(\frac{44^{\circ}+1^{\circ}}{2}\right) \cos \left(\frac{44^{\circ}-1^{\circ}}{2}\right)=2 \sin \frac{45^{\circ}}{2} \cos \frac{43^{\circ}}{2} \\
\sin 43^{\circ}+\sin 2^{\circ}=2 \sin \left(\frac{43^{\circ}+2^{\circ}}{2}\right) \cos \left(\frac{43^{\circ}-2^{\circ}}{2}\right)=2 \sin \frac{45^{\circ}}{2} \cos \frac{41^{\circ}}{2} \\
\sin 42^{\circ}+\sin 3^{\circ}=2 \sin \left(\frac{42^{\circ}+3^{\circ}}{2}\right) \cos \left(\frac{42^{\circ}-3^{\circ}}{2}\right)=2 \sin \frac{45^{\circ}}{2} \cos \frac{39^{\circ}}{2} \\
\vdots \\
\sin 23^{\circ}+\sin 22^{\circ}=2 \sin \left(\frac{23^{\circ}+22^{\circ}}{2}\right) \cos \left(\frac{23^{\circ}-22^{\circ}}{2}\right)=2 \sin \frac{45^{\circ}}{2} \cos \frac{1}{2}^{\circ}
\end{array}$$

There are those cosines again, but this time we're happy to see them! We can use these to cancel out the ones we found when we paired off the cosines. We have
$$\frac{\cos 1^{\circ}+\cos 2^{\circ}+\cdots+\cos 44^{\circ}}{\sin 1^{\circ}+\sin 2^{\circ}+\cdots+\sin 44^{\circ}}=\frac{2 \cos \frac{45}{2}^{\circ}\left(\cos \frac{43}{2}^{\circ}+\cos \frac{41}{2}^{\circ}+\cdots+\cos \frac{1}{2}^{\circ}\right)}{2 \sin \frac{45}{2}^{\circ}}\left(\cos \frac{43}{2}^{\circ}+\cos \frac{41}{2}^{\circ}+\cdots+\cos \frac{1}{2}^{\circ}\right)=\cot \frac{45}{2}^{\circ} .$$

Now, we know what to do. We apply the half angle identity for tangent to find
$$\cot \frac{45}{2}^{\circ}=\frac{1}{\tan \frac{45^{\circ}}{2}}=\frac{1}{\left(\sin 45^{\circ}\right) /\left(1+\cos 45^{\circ}\right)}=\frac{1+\cos 45^{\circ}}{\sin 45^{\circ}}=\frac{1+\frac{\sqrt{2}}{2}}{\frac{\sqrt{2}}{2}}=\frac{2+\sqrt{2}}{\sqrt{2}}=\sqrt{2}+1 .$$

Problem 3.31: Given any seven real numbers, prove that there are two of them, $x$ and $y$, such that
$$0 \leq \frac{x-y}{1+x y} \leq \frac{1}{\sqrt{3}}$$
(Source: Canada)

Solution for Problem 3.31: There don't appear to be any good algebraic tools for attacking this problem. Even multiplying both sides of the right side inequality by $1+x y$ is complicated by the fact that $1+x y$ might be negative. However, the expression $(x-y) /(1+x y)$ does resemble the angle difference identity for tangent:
$$\tan (A-B)=\frac{\tan A-\tan B}{1+\tan A \tan B} .$$

Another clue that we can use this identity is that $x$ and $y$ can be "any real numbers." The range of $\tan \theta$ is all real numbers, so letting $x=\tan A$ and $y=\tan B$ is a permissible substitution, since no matter what $x$ and $y$ are, there

118

---

<!-- Page 119 -->

3.5★. PROBLEM SOLVING WITH IDENTITIES

are angles $A$ and $B$ such that $x=\tan A$ and $y=\tan B$. Writing the given inequality with this substitution, we have
$$0 \leq \frac{\tan A-\tan B}{1+\tan A \tan B} \leq \frac{1}{\sqrt{3}} .$$

Applying the angle difference identity for tangent, we have
$$0 \leq \tan (A-B) \leq \frac{1}{\sqrt{3}}$$

What does this tell us about $A$ and $B$ ? The algebraic expression is not the only part of the problem we can relate to trig. Viewing the two constants on the ends of the inequality as tangents of angles as well, we have
$$\tan 0 \leq \tan (A-B) \leq \tan \frac{\pi}{6} .$$

Now we have a different view of the problem. We can view each of the seven real numbers as the tangent of some angle from $-\frac{\pi}{2}$ to $\frac{\pi}{2}$, and our problem becomes:

Given any seven angles whose measures are in the interval $\left(-\frac{\pi}{2}, \frac{\pi}{2}\right)$, prove that there are two of them, $A$ and $B$, such that
$$\tan 0 \leq \tan (A-B) \leq \tan \frac{\pi}{6} .$$

We now consider what angles have tangents between $\tan 0$ and $\tan \frac{\pi}{6}$. We have $\tan 0 \leq \tan (A-B) \leq \tan \frac{\pi}{6}$ when the slope of the line through the origin and the terminal point of $A-B$ is positive but no greater than the slope of the line through the origin and the terminal point of $\frac{\pi}{6}$. The only first quadrant angles for which this is true are $0 \leq A-B \leq \frac{\pi}{6}$. (It is also true for some third quadrant angles, but because $A$ and $B$ are in the interval $\left(-\frac{\pi}{2}, \frac{\pi}{2}\right)$, the angle $A-B$ cannot be in the third quadrant.)

All we have to do now is show that for any seven angles in the interval $\left(-\frac{\pi}{2}, \frac{\pi}{2}\right)$, there are two that are no more than $\frac{\pi}{6}$ apart. To do this, we note that we can break the interval $\left(-\frac{\pi}{2}, \frac{\pi}{2}\right)$ into 6 non-overlapping intervals that are no longer than $\frac{\pi}{6}$ :
$$\left(-\frac{\pi}{2},-\frac{\pi}{3}\right] ; \quad\left(-\frac{\pi}{3},-\frac{\pi}{6}\right] ; \quad\left(-\frac{\pi}{6}, 0\right] ; \quad\left(0, \frac{\pi}{6}\right] ; \quad\left(\frac{\pi}{6}, \frac{\pi}{3}\right] ; \quad\left(\frac{\pi}{3}, \frac{\pi}{2}\right) .$$

If any two angles are in the same interval, then they are no more than $\frac{\pi}{6}$ apart, and we have the two desired angles. If we restrict ourselves to one angle per interval, the most we can have is 6 angles. Since we have 7 angles distributed among these 6 intervals, there must be an interval with at least 2 angles. Letting $A$ be the larger of these two angles and $B$ be the smaller, we have $0 \leq A-B \leq \frac{\pi}{6}$, so $\tan 0 \leq \tan (A-B) \leq \tan \frac{\pi}{6}$, as desired.

\begin{tabular}{|l|l|}
\hline Sidenote: & A key step in our solution to Problem 3.31 is the observation that if 7 angles are distributed among 6 intervals, then at least 2 of the angles must be in the same interval. This is an example of the Pigeonhole Principle, which states that if more than $n$ objects are distributed among $n$ holes, then at least one hole must contain more than one of the objects. We discuss the Pigeonhole Principle in more detail in Art of Problem Solving's Intermediate Counting \& Probability. \\
\hline
\end{tabular}

Problem 3.32: Evaluate $\left(\sin 1^{\circ}\right)\left(\sin 3^{\circ}\right)\left(\sin 5^{\circ}\right) \cdots\left(\sin 177^{\circ}\right)\left(\sin 179^{\circ}\right)$.

119

---

<!-- Page 120 -->

CHAPTER 3. TRIGONOMETRIC IDENTITIES

Solution for Problem 3.32: We can pair off terms whose angles sum to $180^{\circ}$. We might try the product-to-sum identity (give it a try), but seeing the $180^{\circ}$ suggests that we can also use $\sin \left(180^{\circ}-\theta\right)=\sin \theta$ to give
$$\left(\sin 1^{\circ}\right)\left(\sin 3^{\circ}\right)\left(\sin 5^{\circ}\right) \cdots\left(\sin 177^{\circ}\right)\left(\sin 179^{\circ}\right)=\left(\sin 1^{\circ}\right)\left(\sin 3^{\circ}\right) \cdots\left(\sin 89^{\circ}\right)\left(\sin 89^{\circ}\right)\left(\sin 87^{\circ}\right) \cdots\left(\sin 3^{\circ}\right)\left(\sin 1^{\circ}\right) .$$

We can now pair up the sines as squares of sines. This suggests trying $\sin ^{2} \theta=1-\cos ^{2} \theta$, but that turns our product into a product of differences, which looks scary. If only those products of two sines of the same angle were the product of the sine and the cosine of the same angle, then we could use the sine double angle identity in reverse to simplify the problem.

This bit of wishful thinking pays off when we recognize that we can again pair off the angles in a convenient way, since we can pair them such that the angles sum to $90^{\circ}$. We want to turn some sines into cosines and we have angles that add to $90^{\circ}$, so the identity $\sin \theta=\cos \left(90^{\circ}-\theta\right)$ might help us out. Applying this to the second batch of sines in the product gives:
$$\begin{aligned}
\left(\sin 1^{\circ}\right)\left(\sin 3^{\circ}\right) \cdots\left(\sin 89^{\circ}\right)\left(\sin 89^{\circ}\right)\left(\sin 87^{\circ}\right) \cdots\left(\sin 3^{\circ}\right)\left(\sin 1^{\circ}\right) & \\
= & \left(\sin 1^{\circ}\right)\left(\sin 3^{\circ}\right) \cdots\left(\sin 89^{\circ}\right)\left(\cos 1^{\circ}\right)\left(\cos 3^{\circ}\right) \cdots\left(\cos 87^{\circ}\right)\left(\cos 89^{\circ}\right) .
\end{aligned}$$

Notice that we could have gotten straight to this from this initial product by applying $\sin \theta=\cos \left(\theta-90^{\circ}\right)$.

Concept: There are many ways to tackle most trig identity problems. You won't always find the fastest way, and reviewing your solutions may reveal relationships that will help you solve future problems.

We can now apply the sine double angle identity in reverse:
$$\begin{aligned}
\left(\sin 1^{\circ}\right)\left(\sin 3^{\circ}\right) \cdots\left(\sin 89^{\circ}\right)\left(\cos 1^{\circ}\right)\left(\cos 3^{\circ}\right) \cdots\left(\cos 89^{\circ}\right) & =\left(\sin 1^{\circ}\right)\left(\cos 1^{\circ}\right)\left(\sin 3^{\circ}\right)\left(\cos 3^{\circ}\right) \cdots\left(\sin 89^{\circ}\right)\left(\cos 89^{\circ}\right) \\
& =\left(\frac{\sin 2^{\circ}}{2}\right)\left(\frac{\sin 6^{\circ}}{2}\right) \cdots\left(\frac{\sin 178^{\circ}}{2}\right) \\
& =\frac{1}{2^{45}}\left(\sin 2^{\circ}\right)\left(\sin 6^{\circ}\right) \cdots\left(\sin 178^{\circ}\right)
\end{aligned}$$

Once again, we have angles that pair to $180^{\circ}$, so we try $\sin \theta=\sin \left(180^{\circ}-\theta\right)$. But we have to be careful:

WARNING!! Watch out for special cases. When pairing off terms in a sequence, a summation, or a product, you have to pay special attention to the middle term if there are an odd number of terms.

Here, we have 45 terms, so we can't pair them all off. There's one extra term-the middle term, which is $\sin 90^{\circ}$. But this simply equals 1 , so we can continue without it, since it doesn't affect the product. After applying the identity $\sin \left(180^{\circ}-\theta\right)=\sin \theta$ to all terms with angles greater than $90^{\circ}$, we have
$$\frac{1}{2^{45}}\left(\sin 2^{\circ}\right)\left(\sin 6^{\circ}\right) \cdots\left(\sin 178^{\circ}\right)=\frac{1}{2^{45}}\left(\sin 2^{\circ}\right)\left(\sin 2^{\circ}\right)\left(\sin 6^{\circ}\right)\left(\sin 6^{\circ}\right) \cdots\left(\sin 86^{\circ}\right)\left(\sin 86^{\circ}\right) .$$

Uh-oh. We can't pair these angles off to add to $90^{\circ}$ like we did before. If we apply $\sin \theta=\cos \left(90^{\circ}-\theta\right)$ to the second sine in each pair, we have
$$\frac{1}{2^{45}}\left(\sin 2^{\circ}\right)\left(\cos 88^{\circ}\right)\left(\sin 6^{\circ}\right)\left(\cos 84^{\circ}\right) \cdots\left(\sin 86^{\circ}\right)\left(\cos 4^{\circ}\right) .$$

Now what? Looks like we're stuck.

120

---

<!-- Page 121 -->

3.5★. PROBLEM SOLVING WITH IDENTITIES

Concept: Don't get so mired in one-step tactics that you stop thinking strategically. When
hopelessly stuck, step back and think more broadly about what you're trying to accomplish.

We'd like to make the huge product
$$\frac{1}{2^{45}}\left(\sin 2^{\circ}\right)\left(\sin 2^{\circ}\right)\left(\sin 6^{\circ}\right)\left(\sin 6^{\circ}\right) \cdots\left(\sin 86^{\circ}\right)\left(\sin 86^{\circ}\right)$$
collapse in some way. We collapsed a sum in Problem 3.28 by writing each term as a difference, so that part of each term cancels with another. To do the same in a product, we write each term as a quotient, hoping the denominator of each term will cancel with the numerator of another. So, we look for ways to rewrite some of our terms as quotients. A natural candidate for this approach is the sine double angle formula, because we've used it fruitfully this way before.

We write $\sin 2^{\circ}=\frac{\sin 4^{\circ}}{2 \cos 2^{\circ}}$, and think about whether or not doing the same for other terms will produce the desired cancellation. It's not immediately obvious that the $\cos 2^{\circ}$ will cancel with a numerator in another term, but the $\sin 4^{\circ}$ makes us focus on the $\sin 86^{\circ}$ term, since $\cos 86^{\circ}=\sin 4^{\circ}$. Indeed, we have $\sin 86^{\circ}=\frac{\sin 172^{\circ}}{2 \cos 86^{\circ}}$, and we see that we'll get some cancellation. So, rewriting all the terms in our product similarly, we have:
$$\frac{1}{2^{45}}\left(\sin 2^{\circ}\right)\left(\sin 2^{\circ}\right)\left(\sin 6^{\circ}\right)\left(\sin 6^{\circ}\right) \cdots\left(\sin 86^{\circ}\right)\left(\sin 86^{\circ}\right)=\frac{1}{2^{45}}\left(\frac{\sin 4^{\circ}}{2 \cos 2^{\circ}}\right)^{2}\left(\frac{\sin 12^{\circ}}{2 \cos 6^{\circ}}\right)^{2} \cdots\left(\frac{\sin 172^{\circ}}{2 \cos 86^{\circ}}\right)^{2} .$$

We then apply $\cos \theta=\sin \left(90^{\circ}-\theta\right)$, knowing we will get some cancellation. We find:
$$\frac{1}{2^{45}}\left(\frac{\sin 4^{\circ}}{2 \cos 2^{\circ}}\right)^{2}\left(\frac{\sin 12^{\circ}}{2 \cos 6^{\circ}}\right)^{2} \cdots\left(\frac{\sin 172^{\circ}}{2 \cos 86^{\circ}}\right)^{2}=\frac{1}{2^{45}} \cdot \frac{1}{2^{44}}\left(\frac{\sin 4^{\circ}}{\sin 88^{\circ}}\right)^{2}\left(\frac{\sin 12^{\circ}}{\sin 84^{\circ}}\right)^{2}\left(\frac{\sin 20^{\circ}}{\sin 80^{\circ}}\right)^{2} \cdots\left(\frac{\sin 172^{\circ}}{\sin 4^{\circ}}\right)^{2} .$$

We see that some of the sines immediately cancel, but some are left over. The sine of each multiple of $4^{\circ}$ less than $90^{\circ}$ appears in a denominator. The numerator contains sines of every multiple of $4^{\circ}$ less than $180^{\circ}$ that is not a multiple of $8^{\circ}$. Cancelling the common sines leaves only sines of multiples of $8^{\circ}$ in the denominator and the sines of angles greater than $90^{\circ}$ in the numerator:
$$\frac{1}{2^{45}} \cdot \frac{1}{2^{44}}\left(\frac{\sin 4^{\circ}}{\sin 88^{\circ}}\right)^{2}\left(\frac{\sin 12^{\circ}}{\sin 84^{\circ}}\right)^{2}\left(\frac{\sin 20^{\circ}}{\sin 80^{\circ}}\right)^{2} \cdots\left(\frac{\sin 172^{\circ}}{\sin 4^{\circ}}\right)^{2}=\frac{1}{2^{89}}\left(\frac{\left(\sin 92^{\circ}\right)\left(\sin 100^{\circ}\right)\left(\sin 108^{\circ}\right) \cdots\left(\sin 172^{\circ}\right)}{\left(\sin 88^{\circ}\right)\left(\sin 80^{\circ}\right)\left(\sin 72^{\circ}\right) \cdots\left(\sin 8^{\circ}\right)}\right)^{2} .$$

And now, the identity $\sin \theta=\sin \left(180^{\circ}-\theta\right)$ provides the finishing touch:
$$\frac{1}{2^{89}}\left(\frac{\left(\sin 92^{\circ}\right)\left(\sin 100^{\circ}\right)\left(\sin 108^{\circ}\right) \cdots\left(\sin 172^{\circ}\right)}{\left(\sin 88^{\circ}\right)\left(\sin 80^{\circ}\right)\left(\sin 72^{\circ}\right) \cdots\left(\sin 8^{\circ}\right)}\right)^{2}=\frac{1}{2^{89}}\left(\frac{\left(\sin 92^{\circ}\right)\left(\sin 100^{\circ}\right)\left(\sin 108^{\circ}\right) \cdots\left(\sin 172^{\circ}\right)}{\left(\sin 92^{\circ}\right)\left(\sin 100^{\circ}\right)\left(\sin 108^{\circ}\right) \cdots\left(\sin 172^{\circ}\right)}\right)^{2}=\frac{1}{2^{89}} .$$

The final result suggests that there might be a better way to solve this problem-there are 90 terms in the original product and the answer is $2 \cdot \frac{1}{2^{90}}$. Let's look for a better solution.

Concept: If you do a lot of arduous work on a problem and come to a relatively simple answer, try to use that answer as a guide to find a simpler solution.

So, we go back to the original product:
$$\left(\sin 1^{\circ}\right)\left(\sin 3^{\circ}\right)\left(\sin 5^{\circ}\right) \cdots\left(\sin 177^{\circ}\right)\left(\sin 179^{\circ}\right) .$$

We'd like to find a way to introduce 89 or 90 factors of $\frac{1}{2}$. We've seen how to introduce factors of $\frac{1}{2}$ with the double angle formula for sine, such as when we wrote $\sin 2^{\circ}=\frac{\cos 2^{\circ}}{2 \sin 4^{\circ}}$. We expect that this means we'll have to introduce

121

---

<!-- Page 122 -->

CHAPTER 3. TRIGONOMETRIC IDENTITIES

terms with an even number of degrees, since we'll be using the sine double angle formula. A natural choice now is to introduce all the missing even degree measures by writing the desired expression as a quotient:
$$\left(\sin 1^{\circ}\right)\left(\sin 3^{\circ}\right)\left(\sin 5^{\circ}\right) \cdots\left(\sin 177^{\circ}\right)\left(\sin 179^{\circ}\right)=\frac{\left(\sin 1^{\circ}\right)\left(\sin 2^{\circ}\right)\left(\sin 3^{\circ}\right) \cdots\left(\sin 178^{\circ}\right)\left(\sin 179^{\circ}\right)}{\left(\sin 2^{\circ}\right)\left(\sin 4^{\circ}\right)\left(\sin 6^{\circ}\right) \cdots\left(\sin 176^{\circ}\right)\left(\sin 178^{\circ}\right)}$$

This gives us 89 terms in the denominator, which suggests we're on the right track. We need to pair up factors in the numerator in a way that allows us to finish with the sine double angle formula. Therefore, we need to find $\cos 1^{\circ}, \cos 2^{\circ}, \ldots, \cos 89^{\circ}$ to pair up with $\sin 1^{\circ}, \sin 2^{\circ}, \ldots, \sin 89^{\circ}$. This means we have to focus on turning the sines of obtuse angles into cosines of acute angles. The identity $\sin \theta=\cos \left(\theta-90^{\circ}\right)$ does the trick, and we have
$$\begin{aligned}
\frac{\left(\sin 1^{\circ}\right)\left(\sin 2^{\circ}\right)\left(\sin 3^{\circ}\right) \cdots\left(\sin 178^{\circ}\right)\left(\sin 179^{\circ}\right)}{\left(\sin 2^{\circ}\right)\left(\sin 4^{\circ}\right)\left(\sin 6^{\circ}\right) \cdots\left(\sin 176^{\circ}\right)\left(\sin 178^{\circ}\right)} & =\frac{\left(\sin 1^{\circ}\right)\left(\sin 2^{\circ}\right) \cdots\left(\sin 89^{\circ}\right)\left(\sin 90^{\circ}\right)\left(\cos 1^{\circ}\right)\left(\cos 2^{\circ}\right) \cdots\left(\cos 89^{\circ}\right)}{\left(\sin 2^{\circ}\right)\left(\sin 4^{\circ}\right)\left(\sin 6^{\circ}\right) \cdots\left(\sin 176^{\circ}\right)\left(\sin 178^{\circ}\right)} \\
& =\frac{\left(\sin 1^{\circ}\right)\left(\cos 1^{\circ}\right)\left(\sin 2^{\circ}\right)\left(\cos 2^{\circ}\right) \cdots\left(\sin 89^{\circ}\right)\left(\cos 89^{\circ}\right)(1)}{\left(\sin 2^{\circ}\right)\left(\sin 4^{\circ}\right)\left(\sin 6^{\circ}\right) \cdots\left(\sin 176^{\circ}\right)\left(\sin 178^{\circ}\right)} \\
& =\frac{\left(\frac{1}{2} \sin 2^{\circ}\right)\left(\frac{1}{2} \sin 42^{\circ}\right) \cdots\left(\frac{1}{2} \sin 178^{\circ}\right)}{\left(\sin 2^{\circ}\right)\left(\sin 4^{\circ}\right)\left(\sin 6^{\circ}\right) \cdots\left(\sin 176^{\circ}\right)\left(\sin 178^{\circ}\right)} \\
& =\frac{1}{2^{89}} .
\end{aligned}$$

That's much easier, but it would have been a pretty hard solution to find without the big clue that we're looking for 89 factors of $\frac{1}{2}$. With that clue in mind, we found a new strategy:

\begin{tabular}{|ll|}
\hline Concept: & Some products can be evaluated by strategically multiplying by expressions that \\
$\bigcirc$-Dual 1 in order to introduce convenient cancellation. \\
\hline
\end{tabular}

We did so in our second solution by multiplying by a bunch of factors of the form $\frac{\sin 2 n^{\circ}}{\sin 2 n^{\circ}}$.

Our solution to Problem 3.32 is a good example of how to tackle hard problems. We didn't have a single magical observation that solved the problem. We often took steps without knowing for sure that they'd lead to a solution. We used wishful thinking to help guide us, and stepped back when one of our forward steps proved to be a blind alley. Above all, we didn't give up-we kept trying new approaches until we found a combination of tactics that solved the problem. And after we solved the problem, we used the answer, together with some other clues in our solution, to go back and find a nicer solution.
Exercises
3.5.1 Find $A$ such that $0^{\circ}<A<90^{\circ}$ and $\cos 41^{\circ}+\sin 41^{\circ}=\sqrt{2} \sin A$. (Source: NYSML)
3.5.2 Find a solution for Problem 3.29 that doesn't require trigonometry.
3.5.3 Determine the sum of the angles $A$ and $B$, where $0^{\circ} \leq A, B \leq 180^{\circ}$, and
$$\sin A+\sin B=\sqrt{\frac{3}{2}}, \quad \cos A+\cos B=\sqrt{\frac{1}{2}} .$$
(Source: COMC) (Note: This is not exactly the same as Problem 3.26.)
3.5.4 If $\tan x+\tan y=25$ and $\cot x+\cot y=30$, then what is $\tan (x+y)$ ? (Source: AIME)
3.5.5 Let $A$ and $B$ be acute angles such that $\tan A=1 / 7$ and $\sin B=1 / \sqrt{10}$. Find the degree measure of $A+2 B$ without using a calculator.

122

---

<!-- Page 123 -->

3.6. SUMMARY
3.5.6 Find all acute angles $\theta$ such that $\sin \theta+\sin 2 \theta=\cos \theta+\cos 2 \theta$.
3.5.7 Given $\cos (\alpha+\beta)+\sin (\alpha-\beta)=0$ and $\tan \beta=1 / 2000$, find $\tan \alpha$. (Source: HMMT)
3.5.8★ Given that
$$(1+\sin t)(1+\cos t)=\frac{5}{4}$$
find $(1-\sin t)(1-\cos t)$. (Source: AIME) Hints: 67, 44
3.5.9★ Solve the system
$$\begin{array}{l}
2 x+y x^{2}=y \\
2 y+z y^{2}=z \\
2 z+x z^{2}=x
\end{array}$$

Hints: 240
3.6 Summary

In this chapter, we explored the following identities:
$$\begin{array}{rlll}
\sin ^{2} \theta+\cos ^{2} \theta=1 & \sin (-\theta)=-\sin \theta & \sin \left(90^{\circ}-\theta\right)=\cos \theta & \sin \left(180^{\circ}-\theta\right)=\sin \theta \\
\tan ^{2} \theta+1=\sec ^{2} \theta & \cos (-\theta)=\cos \theta & \cos \left(90^{\circ}-\theta\right)=\sin \theta & \cos \left(180^{\circ}-\theta\right)=-\cos \theta \\
\cot ^{2} \theta+1=\csc ^{2} \theta & \tan (-\theta)=-\tan \theta & \tan \left(90^{\circ}-\theta\right)=\cot \theta & \tan \left(180^{\circ}-\theta\right)=-\tan \theta
\end{array}$$

Angle sum and difference identities:
$$\begin{array}{ll}
\sin (\alpha+\beta)=\sin \alpha \cos \beta+\sin \beta \cos \alpha & \sin (\alpha-\beta)=\sin \alpha \cos \beta-\sin \beta \cos \alpha \\
\cos (\alpha+\beta)=\cos \alpha \cos \beta-\sin \alpha \sin \beta & \cos (\alpha-\beta)=\cos \alpha \cos \beta+\sin \alpha \sin \beta \\
\tan (\alpha+\beta)=\frac{\tan \alpha+\tan \beta}{1-\tan \alpha \tan \beta} & \tan (\alpha-\beta)=\frac{\tan \alpha-\tan \beta}{1+\tan \alpha \tan \beta}
\end{array}$$

Double angle and half-angle identities:
$$\begin{array}{ll}
\sin 2 x=2 \sin x \cos x & \cos \frac{\theta}{2}= \pm \sqrt{\frac{1+\cos \theta}{2}} \\
\cos 2 x=\cos ^{2} x-\sin ^{2} x=2 \cos ^{2} x-1=1-2 \sin ^{2} x & \sin \frac{\theta}{2}= \pm \sqrt{\frac{1-\cos \theta}{2}} \\
\tan 2 x=\frac{2 \tan x}{1-\tan ^{2} x} & \tan \frac{\theta}{2}=\frac{\sin \theta}{1+\cos \theta}=\frac{1-\cos \theta}{\sin \theta}
\end{array}$$

Product-to-sum and sum-to-product identities:
$$\begin{array}{ll}
\cos \alpha \cos \beta=\frac{1}{2}(\cos (\alpha+\beta)+\cos (\alpha-\beta)) & \cos x+\cos y=2 \cos \left(\frac{x+y}{2}\right) \cos \left(\frac{x-y}{2}\right) \\
\sin \alpha \sin \beta=\frac{1}{2}(\cos (\alpha-\beta)-\cos (\alpha+\beta)) & \cos x-\cos y=-2 \sin \left(\frac{x+y}{2}\right) \sin \left(\frac{x-y}{2}\right) \\
\sin \alpha \cos \beta=\frac{1}{2}(\sin (\alpha+\beta)+\sin (\alpha-\beta)) & \sin x+\sin y=2 \sin \left(\frac{x+y}{2}\right) \cos \left(\frac{x-y}{2}\right) \\
& \sin x-\sin y=2 \sin \left(\frac{x-y}{2}\right) \cos \left(\frac{x+y}{2}\right)
\end{array}$$

123

---

<!-- Page 124 -->

CHAPTER 3. TRIGONOMETRIC IDENTITIES

Things To Watch Out For! 

WARNING!!
Whenever you solve an equation by performing some possibly irreversible steps, you must check your solutions at the end, to make sure they satisfy the original equation. Two common irreversible steps are squaring an equation and multiplying both sides of an equation by an expression that might equal zero.

Problem Solving Strategies

Concepts:
- If a tactic makes some progress on a problem, but doesn't entirely solve it, look for a way to use the tactic again.
- Don't get locked into one way of attacking a problem-look for several starting points, go a little ways down each path, and then choose the one that looks most fruitful.
- Experiment! Don't wait until you see the whole solution before you try something-you might end up waiting forever. Take little steps that might be promising, and reassess after each step.
- Wishful thinking is a powerful problem solving tool-thinking about what you'd like to be true can focus your attention on the key step in a solution.
- A fruitful first step in many trig problems is rewriting the problem in terms of sine and cosine, because most people have more experience with sine and cosine than with the other trig functions.
- When solving an equation that contains trig functions, it's often best to write the equation in terms of a single trig function, so that you can then try to solve the equation for that function.
- Recognizing the forms of common trigonometric identities can help solve many trigonometric problems.
- Recognizing relationships among angles in a complicated trig expression can help simplify the expression.
- Many series involving trigonometric functions can be written as telescoping series.
- Trigonometry can be a powerful tool even in problems that don't appear to be about trigonometry.

Extra! You may have heard that prior to calculators, people sometimes used logarithm tables to perform multiplication and division of large numbers. But what did they do before mathematicians developed logarithms? They used trig! More specifically, they used the product-to-sum and product-to-difference identities to turn products into easier-to-handle sums and differences. If you can't figure out how this works, look up prosthaphaeresis on the internet.

124

---

<!-- Page 125 -->

REVIEW PROBLEMS

Review Problems
3.33 Prove that $\tan (\pi-\theta)=-\tan \theta$.
3.34 Express $\sin (\theta-\pi)$ in terms of $\cos \theta$ and/or $\sin \theta$.
3.35 Prove each of the identities below using only the identities $\sin (-x)=\sin x, \cos (-x)=-\cos x, \sin \left(90^{\circ}-x\right)= \cos x, \sin ^{2} x+\cos ^{2} x=1$, and $\sin (x+y)=\sin x \cos y+\sin y \cos x$. Try to do this problem without looking back in the book. The goal of this problem is to learn that you do not have to memorize all of these identities-you can rebuild them from a small group of basic identities whenever you need them.
(a) $\quad \cos (x-y)=\cos x \cos y+\sin x \sin y$
(d) $\quad \cos \frac{x}{2}=\sqrt{\frac{1+\cos x}{2}}$ for $0<x<\pi$
(b) $\sin 2 x=2 \sin x \cos x$
(e) $\quad \cos x \cos y=\frac{1}{2}(\cos (x+y)+\cos (x-y))$
(c) $\quad \tan (x+y)=\frac{\tan x+\tan y}{1-\tan x \tan y}$
(f) $\quad \sin x-\sin y=2 \sin \left(\frac{x-y}{2}\right) \cos \left(\frac{x+y}{2}\right)$
3.36 Simplify $\sin (x-y) \cos y+\cos (x-y) \sin y$. (Source: AHSME)
3.37 Which of the following equals $\sqrt{2} \cos \left(\frac{\pi}{4}-x\right)$ ?
(a) $\quad \cos x+\sin x$
(c) $\quad \cos x-\sin x$
(b) $-\cos x+\sin x$
(d) $-\cos x-\sin x$
3.38 Determine the constants $a$ and $b$ so that $\frac{-3+4 \cos ^{2} \theta}{1-2 \sin \theta}=a+b \sin \theta$. (Source: CEMC)
3.39 What is the range of the function $g(t)=2 \sin t+3 \cos t$ ?
3.40 Compute $\frac{\tan ^{2} 20^{\circ}-\sin ^{2} 20^{\circ}}{\tan ^{2} 20^{\circ} \sin ^{2} 20^{\circ}}$. (Source: HMMT)
3.41 Show that $\frac{\tan (\alpha-\beta)+\tan \beta}{1-\tan (\alpha-\beta) \tan \beta}=\tan \alpha$.
3.42 Express $\tan \left(\frac{3 \pi}{2}+\theta\right)$ in terms of $\tan \theta$.
3.43 Show that there is no triangle $A B C$ for which $\cos A \cos B-\sin A \sin B=1$.
3.44 The complicated trigonometric expression shown below is equivalent to either $\sin x, \cos x$, or $\tan x$. Which one is it?
$$\frac{\sqrt{3} \sin \left(x+30^{\circ}\right)-\cos \left(x+30^{\circ}\right)}{4 \cos x \sin \left(x+30^{\circ}\right)-4 \sin x \cos \left(x+30^{\circ}\right)}$$
(Source: Mandelbrot)
3.45 Evaluate $\tan \left(\arccos \left(-\frac{1}{2}\right)+\arcsin \frac{\sqrt{2}}{2}\right)$.
3.46 Compute $\left(\sin 15^{\circ}+\sin 75^{\circ}\right)^{6}$. (Source: ARML)
3.47 Simplify $\frac{\sin 2 x}{\sin x}-\frac{\cos 2 x}{\cos x}$.
3.48 Find all possible values of $\sin 2 \theta$ if $\cos \theta=-0.6$.

125

---

<!-- Page 126 -->

CHAPTER 3. TRIGONOMETRIC IDENTITIES
3.49 Show that $\frac{\cot x-1}{\cot x+1}=\frac{\cos 2 x}{1+\sin 2 x}$.
3.50 If $\sin 2 x=24 / 25$, find the value of $\sin ^{4} x+\cos ^{4} x$.
3.51 Find $\tan \frac{5 \pi}{8}$.
3.52 Find all $x$ such that $0 \leq x \leq 2 \pi$ and $\sin 2 x \leq \sin x$.
3.53 For $-\pi \leq \theta \leq \pi$, find all solutions to the equation $2\left(\sin ^{2} \theta-\cos ^{2} \theta\right)=8 \sin \theta-5$. (Source: CEMC)
3.54
(a) Show that $\frac{\sin \theta+\sin 2 \theta}{1+\cos \theta+\cos 2 \theta}=\tan \theta$ if $0 \leq \theta<\pi / 2$.
(b) If $\pi / 2<\theta<\pi$, for what value(s) of $\theta$ is the identity in part (a) not true? (Source: CEMC)
3.55 Find the acute angle $\phi$ such that $2 \sin 52^{\circ} \sin 68^{\circ}=\frac{1}{2}+\sin \phi$.
3.56 Prove the identity $\frac{\tan x}{1-\cot x}+\frac{\cot x}{1-\tan x}=\sec x \csc x+1$.
3.57 Show that $\frac{\sin x+\sin 3 x+\sin 5 x}{\cos x+\cos 3 x+\cos 5 x}=\tan 3 x$ for all $x$ for which $\tan 3 x$ is defined.

Challenge Problems
3.58 Find the value of $\tan x$ if $\sin x+\cos x=1 / 5$ and $\pi / 2<x<\pi$. Hints: 44
3.59 If $f\left(\frac{x}{x-1}\right)=\frac{1}{x}$ for all $x \neq 0,1$, and $0<\theta<\pi / 2$, then find $f\left(\sec ^{2} \theta\right)$. Hints: 156
3.60 Compute the smallest positive angle $x$, in degrees, such that $\tan 4 x=\frac{\cos x-\sin x}{\cos x+\sin x}$. (Source: NYSML) Hints: 261
3.61 Determine all points at which the graphs of $y=8 \cos x+5 \tan x$ and $y=5 \sec x+2 \sin 2 x$ intersect, where $0 \leq x \leq 2 \pi$. (Source: CEMC)
3.62 Find all $x$ between $-\pi / 2$ and $\pi / 2$ such that $1-\sin ^{4} x-\cos ^{2} x=1 / 16$. (Source: HMMT)
3.63 Let $y$ be a fixed real number, $0<y<\pi$, and let $f(x)=\frac{\sin x+\sin (x+y)}{\cos x-\cos (x+y)}$ for $0 \leq x \leq \pi-y$. Show that $f$ is constant. Hints: 166
3.64 Suppose that $\sec x+\tan x=22 / 7$. Find $\csc x+\cot x$. (Source: AIME) Hints: 147
3.65 Prove that for all real $x$ and $y$, we have $-\frac{1}{2} \leq \frac{(x+y)(1-x y)}{\left(1+x^{2}\right)\left(1+y^{2}\right)} \leq \frac{1}{2}$. Hints: 253
3.66 Determine all $\theta$ such that $0 \leq \theta \leq \frac{\pi}{2}$ and $\sin ^{5} \theta+\cos ^{5} \theta=1$. Hints: 122
3.67 Find, with proof, all real numbers $x$ between 0 and $2 \pi$ such that $\tan 7 x-\sin 6 x=\cos 4 x-\cot 7 x$. (Source: USAMTS) Hints: 267
3.68 Find the value of $10 \cot \left(\cot ^{-1} 3+\cot ^{-1} 7+\cot ^{-1} 13+\cot ^{-1} 21\right)$. (Source: AIME) Hints: 26
3.69 Find $\cos \frac{\pi}{7} \cdot \cos \frac{2 \pi}{7} \cdot \cos \frac{4 \pi}{7}$. Hints: 223

126

---

<!-- Page 127 -->

CHALLENGE PROBLEMS
3.70
(a) Express $\tan 3 x$ in terms of $\tan x$.
(b) Let $\theta$ be the angle in the second quadrant for which $\cos \theta=-8 / 17$. Determine $\tan (3 \theta / 2)$. (Source: Mandelbrot)
(c) Solve for $x: \tan 20^{\circ} \tan 40^{\circ} \tan 80^{\circ}=\tan x$. Hints: 72, 20
3.71 If $\sin \theta+\cos \theta+\tan \theta+\cot \theta+\sec \theta+\csc \theta=7$, then find $\sin 2 \theta$. (Source: NYSML) Hints: 99, 168
3.72 ★ The first two terms of a sequence are $a_{1}=1$ and $a_{2}=\frac{1}{\sqrt{3}}$. For $n \geq 1$,
$$a_{n+2}=\frac{a_{n}+a_{n+1}}{1-a_{n} a_{n+1}} .$$

What is $\left|a_{2009}\right|$ ? (Source: AMC) Hints: 208
3.73★ Find the least positive integer $n$ such that
$$\frac{1}{\sin 45^{\circ} \sin 46^{\circ}}+\frac{1}{\sin 47^{\circ} \sin 48^{\circ}}+\cdots+\frac{1}{\sin 133^{\circ} \sin 134^{\circ}}=\frac{1}{\sin n^{\circ}} .$$
(Source: AIME) Hints: 108, 86
3.74★ Find the sum of the values of $x$ such that $\cos ^{3} 3 x+\cos ^{3} 5 x=8 \cos ^{3} 4 x \cos ^{3} x$, where $x$ is measured in degrees and $100<x<200$. (Source: AIME) Hints: 178
3.75 $\star$ An angle $x$ is chosen at random from the interval $0^{\circ}<x<90^{\circ}$. Find the probability that the numbers $\sin ^{2} x, \cos ^{2} x$, and $\sin x \cos x$ are not the lengths of the sides of a triangle. (Source: AIME)
3.76 ★ Show that if $x+y+z=x y z$, then $\frac{2 x}{1-x^{2}}+\frac{2 y}{1-y^{2}}+\frac{2 z}{1-z^{2}}=\frac{2 x}{1-x^{2}} \cdot \frac{2 y}{1-y^{2}} \cdot \frac{2 z}{1-z^{2}}$. Hints: 153
3.77 ★ The sequence $\left\{a_{n}\right\}$ satisfies $a_{0}=0$ and $a_{n+1}=\frac{8}{5} a_{n}+\frac{6}{5} \sqrt{4^{n}-a_{n}^{2}}$ for $n \geq 0$. Find $a_{10}$. (Source: AIME) Hints: 145, 216
3.78★ Prove that $\sum_{k=1}^{n} \arctan \frac{1}{2 k^{2}}=\arctan \frac{n}{n+1}$.

Sidenote: On page 111, we asked what causes the oscillations we hear when tuning an instrument that is almost in tune, but not quite. To investigate, we graphed $y=\sin 30 x+\sin 30 x, y=\sin 31 x+\sin 29 x$, and $y=\sin 32 x+\sin 28 x$. Applying the sum-to-product identity gives us a clearer picture of what's going on in the graphs. While $\sin 30 x+\sin 30 x$ is just $2 \sin 30 x$, applying the sum-to-product identity for sine gives
$$\begin{array}{l}
\sin 31 x+\sin 29 x=2 \sin 30 x \cos x \\
\sin 32 x+\sin 28 x=2 \sin 30 x \cos 2 x
\end{array}$$

In each case, the $2 \sin 30 x$ of the in-tune guitar is damped by an extra term that oscillates. Since $\cos 2 x$ oscillates twice as fast (has half the period) as $\cos x$, the sound oscillates much faster for the $\sin 32 x+\sin 28 x$ guitar than it does for the $\sin 31 x+\sin 29 x$ guitar.

127

---

