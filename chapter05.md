# Chapter 5: Parameterization and Trigonometric Coordinate Systems

<!-- Page 158 -->

CHAPTER 5. PARAMETERIZATION AND TRIGONOMETRIC COORDINATE SYSTEMS

Mathematics is the supreme judge; from its decisions there is no appeal. - Tobias Dantzig
5
Parameterization and Trigonometric Coordinate Systems
5.1 Parameterization

Imagine we wished to track the path of a particle traveling within the Cartesian plane. Suppose that we want to know more than just the path it takes, but we also want to know where it is at each moment in time. Then, saying that the particle travels along the graph of an equation like $y=x+2$ won't do-this doesn't tell us where the particle is at each moment in time. Instead, we can use equations called parametric equations.

Rather than having a single equation that relates $x$ and $y$, we can define a relationship between $x$ and $y$ using an intermediary variable called a parameter. We do so by expressing $x$ and $y$ as functions of the parameter, meaning we relate $x$ and $y$ with equations of the form $x=f(t), y=g(t)$, where $t$ is the parameter. (We often use $t$ as the variable for a parameter because we frequently use a parameter to represent time.) We refer to the equations $x=f(t), y=g(t)$ as parametric equations. When we graph parametric equations $x=f(t), y=g(t)$, we graph all points $(x, y)$ such that there is a value of $t$ for which $x=f(t)$ and $y=g(t)$. If the possible values of the parameter are not specified, then it is implied that the parameter can take on any real value for which the equations are defined.

For example, we can use the parametric equations
$$\begin{array}{l}
x=2-3 t \\
y=1+2 t
\end{array}$$
to represent the location of a particle that is at $(x, y)=(2,1)$ at time $t=0$ and moves 3 to the left and up 2 for each unit of time. When $t=4$ in these parametric equations, we have $x=-10$ and $y=9$, so $(x, y)=(-10,9)$ is on the graph of the parametric equations. If we let $t=-1$, we have $(x, y)=(5,-1)$, so if we leave $t$ unrestricted, then $(x, y)=(5,-1)$ is on the graph. To restrict the graph to only those points the particle will pass through from the time it starts at $(2,1)$, we would restrict the parameter to $t \geq 0$.

158

---

<!-- Page 159 -->

5.1. PARAMETERIZATION

Problems
Problem 5.1: In this problem, we find the graph of the parametric equations $x=2-3 t, y=1+2 t$.
(a) Choose several values of $t$ and compute $(x, y)$ for each value. Plot the resulting points. What does it look like the graph of all such points will be?
(b) Eliminate $t$ from the parametric equations $x=2-3 t, y=1+2 t$ to find an equation in which the only variables are $x$ and $y$. Show that for every pair ( $x_{1}, y_{1}$ ) that satisfies this new equation, we can find a value of $t$ in the parametric equations that gives $(x, y)=\left(x_{1}, y_{1}\right)$.
(c) Suppose we limit $t$ to the interval $[4,8]$. How does this affect the graph?

Problem 5.2: Find the graph of the parametric equations $x=1-t, y=2 t^{2}-t$.
Problem 5.3: Find the graph of the parametric equations $x=3+2 \cos t, y=4+2 \sin t$ for $0 \leq t<2 \pi$.
Problem 5.4: Find the graph of the parametric equations $x=\sin \theta, y=3-2 \cos 2 \theta$. (Be careful!)
Problem 5.5:
(a) Find parametric equations for $x$ and $y$ such that the graph of the parametric equations is the same as the graph of $x^{2}+y^{2}=1$.
(b) Is your answer to part (a) unique? Are there any other parametric equations that produce the same graph?
(c) Suppose a particle starts at the point $(0,-2)$, and moves at a constant speed clockwise around the origin along the graph of $x^{2}+y^{2}=4$. If the particle completes a full revolution in 4 seconds, then find parametric equations for the location of the particle in terms of $t$, where $t$ is the time in seconds since the particle started moving.

Problem 5.6: Find parametric equations for $x$ and $y$ such that $x^{2}-3 y^{2}=1$.
Problem 5.7: I'm riding my bike at a constant speed of 20 miles per hour on flat land when I ride over a dot of fresh yellow paint, thereby getting a yellow spot on my front wheel, which is 2 feet in diameter. I continue riding my bike in a straight line at 20 miles per hour. When $t$ seconds have passed since running over the dot, how many feet is the yellow spot on my tire from the yellow dot I ran over?

Problem 5.1: In this problem, we find the graph of the parametric equations $x=2-3 t, y=1+2 t$.
(a) Choose several values of $t$ and compute $(x, y)$ for each value. Plot the resulting points. What does it look like the graph of all such points will be?
(b) Eliminate $t$ from the parametric equations $x=2-3 t, y=1+2 t$ to find an equation in which the only variables are $x$ and $y$. Show that for every pair ( $x_{1}, y_{1}$ ) that satisfies this new equation, we can find a value of $t$ in the parametric equations that gives $(x, y)=\left(x_{1}, y_{1}\right)$.
(c) Suppose we limit $t$ to the interval $[4,8]$. How does this affect the graph?

Solution for Problem 5.1:
(a) At left atop the following page we have a table of values of $t$ and corresponding values of $x$ and $y$. At right, we have graphed several of the resulting points $(x, y)$ on the Cartesian plane.

159

---

<!-- Page 160 -->

CHAPTER 5. PARAMETERIZATION AND TRIGONOMETRIC COORDINATE SYSTEMS

\begin{tabular}{ccc}
$t$ & $x=2-3 t$ & $y=1+2 t$ \\
\hline-4 & 14 & -7 \\
-3 & 11 & -5 \\
-2 & 8 & -3 \\
-1 & 5 & -1 \\
0 & 2 & 1 \\
1 & -1 & 3 \\
2 & -4 & 5 \\
3 & -7 & 7
\end{tabular}

The points on the graph look collinear. It looks like the graph of the parametric equations is a line.
(b) We can confirm our guess from part (a) by eliminating the parameter from the parametric equations. Adding 2 times $x=2-3 t$ to 3 times $y=1+2 t$ gives $2 x+3 y=7$. The graph of this equation is indeed a line.

Concept: We can sometimes better understand a set of parametric equations by eliminating
the parameter from the equations.

Unfortunately, this only tells us that every point in the graph of the parametric equations is in the graph of $2 x+3 y=7$. In order to conclude that the graphs are the same, we must show that every point in the graph of $2 x+3 y=7$ is in the graph of the parametric equation. Fortunately, that's not too hard. Suppose that $\left(x_{1}, y_{1}\right)$ is in the graph of $2 x+3 y=7$, so we have $2 x_{1}+3 y_{1}=7$. To show that ( $x_{1}, y_{1}$ ) is in the graph of the parametric equations, we must show that there is a value of $t$ that gives $(x, y)=\left(x_{1}, y_{1}\right)$. To find that $t$, we solve the parametric equation $x=2-3 t$ for $t$, which gives $t=(2-x) / 3$. So, we let $t=\left(2-x_{1}\right) / 3$ in the parametric equations, and we have
$$\begin{array}{l}
x=2-3 \cdot \frac{2-x_{1}}{3}=x_{1} \\
y=1+2 \cdot \frac{2-x_{1}}{3}=\frac{7}{3}-\frac{2}{3} x_{1}=\frac{7}{3}-\frac{2}{3} \cdot \frac{7-3 y_{1}}{2}=y_{1}
\end{array}$$
which means $\left(x_{1}, y_{1}\right)$ is in the graph of the parametric equations. Therefore, every point in the graph of $2 x+3 y=7$ is in the graph of the parametric equations. We conclude that the graph of $x=2-3 t, y=1+2 t$ is the same as the graph of $2 x+3 y=7$.

WARNING!! ẩ

If parametric equations $x=f(t), y=g(t)$ satisfy an equation in terms of $x$ and $y$, we only know that the graph of the parametric equations is part of the graph of the non-parametric equation. To show that the graph of the parametric equations is the same as the graph of the non-parametric equation, we must show that every point in the graph of the non-parametric equation is in the graph of the parametric equations. We can usually do so by showing that for each point $\left(x_{1}, y_{1}\right)$ on the graph of the non-parametric equation, there is a value of $t$ such that $x_{1}=f(t), y_{1}=g(t)$.
(c) When $t=4$, we have $(x, y)=(-10,9)$, and when $t=8$, we have $(x, y)=(-22,17)$, so the graph of the parametric equations when $t$ is restricted to the interval $[4,8]$ is the line segment from $(-10,9)$ to $(-22,17)$. To see that every point on this segment is on the graph, and no other points are, we can start from $4 \leq t \leq 8$, multiply by -3 to produce $-12 \geq-3 t \geq-24$, and then add 2 to get $-10 \geq 2-3 t \geq-22$. Since $x=2-3 t$, we have $-10 \geq x \geq-22$. So, every point on the line from part (b) for which $-10 \geq x \geq-22$ is produced by values of $t$ in the interval [4,8], and no other values of $x$ are possible.

Problem 5.2: Find the graph of the parametric equations $x=1-t, y=2 t^{2}-t$.

160

---

<!-- Page 161 -->

5.1. PARAMETERIZATION

Solution for Problem 5.2: We start as in Problem 5.1, choosing values of $t$ and solving for $x$ and $y$.

\begin{tabular}{ccc}
$t$ & $x=1-t$ & $y=2 t^{2}-t$ \\
\hline-3 & 4 & 21 \\
-2 & 3 & 10 \\
-1 & 2 & 3 \\
0 & 1 & 0 \\
1 & 0 & 1 \\
2 & -1 & 6 \\
3 & -2 & 15
\end{tabular}

The $t^{2}$ in the parametric equation for $y$ suggests the graph might be a parabola, and the dashed parabola in the diagram seems to fit the data nicely. To see that the graph is indeed a parabola, we try to relate $x$ directly to $y$. We can't use elimination, as we did in Problem 5.1, but substitution does the job. From $x=1-t$, we have $t=1-x$, so
$$y=2 t^{2}-t=2(1-x)^{2}-(1-x)=2 x^{2}-4 x+2-1+x=2 x^{2}-3 x+1 .$$

As in the previous problem, we still must show that every point in the graph of $y=2 x^{2}-3 x+1$ is in the graph of the parametric equations. For any point ( $x_{1}, y_{1}$ ) in the graph of $y=2 x^{2}-3 x+1$, we have $y_{1}=2 x_{1}^{2}-3 x_{1}+1$. Solving the parametric equation $x=1-t$ for $t$ gives $t=1-x$. So, we let $t=1-x_{1}$ in the parametric equations, and we have
$$\begin{array}{l}
x=1-t=1-\left(1-x_{1}\right)=x_{1} \\
y=2 t^{2}-t=2\left(1-x_{1}\right)^{2}-\left(1-x_{1}\right)=2 x_{1}^{2}-3 x_{1}+1=y_{1}
\end{array}$$
which means that $\left(x_{1}, y_{1}\right)$ is in the graph of the parametric equations, as well. Therefore, the graph of the parametric equations is the same as the graph of $y=2 x^{2}-3 x+1$, which is the dashed parabola shown above.

Problem 5.3: Find the graph of the parametric equations $x=3+2 \cos t, y=4+2 \sin t$ for $0 \leq t<2 \pi$.

Solution for Problem 5.3: We choose values of $t$ for which we can evaluate sine and cosine easily.

\begin{tabular}{ccc|ccc}
$t$ & $x=3+2 \cos t$ & $y=4+2 \sin t$ & $t$ & $x=3+2 \cos t$ & $y=4+2 \sin t$ \\
\hline 0 & 5 & 4 & $\pi$ & 1 & 4 \\
$\pi / 6$ & $3+\sqrt{3}$ & 5 & $7 \pi / 6$ & $3-\sqrt{3}$ & 3 \\
$\pi / 3$ & 4 & $4+\sqrt{3}$ & $4 \pi / 3$ & 2 & $4-\sqrt{3}$ \\
$\pi / 2$ & 3 & 6 & $3 \pi / 2$ & 3 & 2 \\
$2 \pi / 3$ & 2 & $4+\sqrt{3}$ & $5 \pi / 3$ & 4 & $4-\sqrt{3}$ \\
$5 \pi / 6$ & $3-\sqrt{3}$ & 5 & $11 \pi / 6$ & $3+\sqrt{3}$ & 3
\end{tabular}

It looks like the graph is the circle shown at right. We can't use either the elimination tactic of Problem 5.1 or the straightforward substitution tactic of Problem 5.2 to turn the parametric equations into a single equation with only $x$ and $y$. So, we look for other strategies for eliminating the cost and $\sin t$ terms, which brings us to the trigonometric identity $\sin ^{2} t+\cos ^{2} t=1$.

Concept: Trig identities can be very useful in working with parametric equations.
न्द

Solving $x=3+2 \cos t$ and $y=4+2 \sin t$ for $\cos t$ and $\sin t$ give $\cos t=(x-3) / 2$ and $\sin t=(y-4) / 2$. Substituting

161

---

<!-- Page 162 -->

CHAPTER 5. PARAMETERIZATION AND TRIGONOMETRIC COORDINATE SYSTEMS

these into $\sin ^{2} t+\cos ^{2} t=1$ gives
$$\left(\frac{x-3}{2}\right)^{2}+\left(\frac{y-4}{2}\right)^{2}=1 .$$

Multiplying both sides by $2^{2}$ gives
$$(x-3)^{2}+(y-4)^{2}=2^{2} .$$

The graph of this equation is a circle with center $(3,4)$ and radius 2 , as expected, and as depicted above.
We're not finished yet! We have only shown that every point in the graph of the parametric equations is on the circle. We still have to show that every point on the circle is in the graph of the parametric equations.

We know one circle that is related to cosine and sine-we use the unit circle to define cosine and sine. From this definition, the unit circle is the graph of the parametric equations $x=\cos t, y=\sin t$. Multiplying the right sides of these equations simply scales every point away from the origin by a factor of 2 , so the graph of $x=2 \cos t$, $y=2 \sin t$ is a circle centered at the origin with radius 2 . We produce the graph of $x=3+2 \cos t, y=4+2 \sin t$ by translating each point on the graph of $x=2 \cos t, y=2 \sin t$ to the right 3 and up 4 . Therefore, the graph of $x=3+2 \cos t, y=4+2 \sin t$ is the full circle centered at $(3,4)$ with radius 2 .

Problem 5.4: Find the graph of the parametric equations $x=\sin \theta, y=3-2 \cos 2 \theta$. (Be careful!)

Solution for Problem 5.4: We can write $\cos 2 \theta$ in terms of $\sin \theta$, so we can easily eliminate the parameter by substituting $x$ for $\sin \theta$ in the resulting expression:
$$y=3-2 \cos 2 \theta=3-2\left(1-2 \sin ^{2} \theta\right)=3-2\left(1-2 x^{2}\right)=4 x^{2}+1 .$$

What's wrong with this finish:

We see the problem when we look back at the parametric equations. We have $x=\sin \theta$, so $x$ cannot be greater than 1 or less than -1 . There is an angle $\theta$ such that $\sin \theta=x$ for each $x$ from -1 to 1 . Therefore, the graph of the parametric equations is the graph of $y=4 x^{2}+1$ for which $-1 \leq x \leq 1$, not the entire parabola that is produced by graphing $y=4 x^{2}+1$ without restriction on $x$.

In Problem 5.4, we found that the parametric equations $x=\sin \theta, y=3-2 \cos 2 \theta$ satisfy the equation $y=4 x^{2}+1$. However, the graph of the parametric equations is not the same as the graph of $y=4 x^{2}+1$. The fact that the parametric equations $x=\sin \theta, y=3-2 \cos 2 \theta$ satisfy $y=4 x^{2}+1$
only tells us that the graph of the parametric equations is part of the graph of $y=4 x^{2}+1$. We then must consider the restrictions of the parametric equations to determine what portion of the graph of $y=4 x^{2}+1$ is the graph of the parametric equations.

\begin{tabular}{|l|l|}
\hline WARNING!! " & As noted earlier, if parametric equations $x=f(t), y=g(t)$ satisfy an equation in terms of $x$ and $y$, then we only know that the graph of the parametric equations is part of the graph of the non-parametric equation. Sometimes the parametric equations have restrictions that limit the graph of the parametric equations to only a portion of the graph of the non-parametric equation. \\
\hline
\end{tabular}

Our first few examples have given us a sense of how parametric equations work, but not much sense for what parametric equations are good for. Unfortunately, you'll have to wait until your study of calculus and physics to

162

---

<!-- Page 163 -->

5.1. PARAMETERIZATION

put parametric equations to heavy use, but Problem 5.3 gives some hint as to why parametric equations can be useful. In that problem, we showed that the equation $(x-3)^{2}+(y-4)^{2}=2^{2}$ can be modeled with the parametric equations $x=3+2 \cos t, y=4+2 \sin t$. We cannot write the equation $(x-3)^{2}+(y-4)^{2}=2^{2}$ such that one of $x$ or $y$ is a function of the other. However, our parametric equations allow us to write both $x$ and $y$ as functions of some other variable. The ability to express $x$ and/or $y$ as functions of another variable becomes particularly important in calculus, which offers very powerful tools that we can apply to functions.

Problem 5.5:
(a) Find parametric equations for $x$ and $y$ such that the graph of the parametric equations is the same as the graph of $x^{2}+y^{2}=1$.
(b) Is your answer to part (a) unique? Are there any other parametric equations that produce the same graph?
(c) Suppose a particle starts at the point $(0,-2)$, and moves at a constant speed clockwise around the origin along the graph of $x^{2}+y^{2}=4$. If the particle completes a full revolution in 4 seconds, then find parametric equations for the location of the particle in terms of $t$, where $t$ is the time in seconds since the particle started moving.

Solution for Problem 5.5:
(a) The graph of $x^{2}+y^{2}=1$ is the unit circle. Any point on the unit circle is the terminal point of some angle $\theta$. We defined the functions $\cos \theta$ and $\sin \theta$ such that the coordinates of this terminal point are $x=\cos \theta$, $y=\sin \theta$. Therefore, we say that $x=\cos \theta, y=\sin \theta$ is a parameterization of $x^{2}+y^{2}=1$ because the graph of the parametric equations $x=\cos \theta, y=\sin \theta$ is the same as the graph of $x^{2}+y^{2}=1$.
(b) Our answer in part (a) isn't the only parameterization of $x^{2}+y^{2}=1$. We also could have let $x=\cos (-\theta)$, $y=\sin (-\theta)$. Then, we still have $x^{2}+y^{2}=1$, and the parameterization produces every point on the circle. What's the difference between the two parameterizations $x=\cos \theta, y=\sin \theta$ and $x=\cos (-\theta)$, $y=\sin (-\theta)$ ? Both parameterizations produce the same curve, but if we care about how the curve is traced out as we vary $\theta$, then there is a difference between these two parameterizations. As $\theta$ goes from 0 to $2 \pi$, the curve described by $x=\cos \theta, y=\sin \theta$ starts at ( 1,0 ) and is produced by moving along the unit circle counterclockwise about the origin. On the other hand, as $\theta$ goes from 0 to $2 \pi$, the curve described by $x=\cos (-\theta), y=\sin (-\theta)$ starts at $(1,0)$ and is generated clockwise from the origin.

There are infinitely many other ways we could have chosen the parametric equations. The equations $x=\sin 2 t, y=\cos 2 t$ work, as do $x=-\cos \pi t, y=-\sin \pi t$ and $x=\sin \left(t^{2}-t^{3}\right), y=-\cos \left(t^{2}-t^{3}\right)$. While it doesn't matter which of these parameterizations we use to describe the graph of $x^{2}+y^{2}=1$, it can be very important which parameterization we choose when using parametric equations to model a process. In our next part, we'll see why.
(c) The first difference we see between this and part (a) is that the circle has radius 2 instead of radius 1 . So, we might think to use the parameterization $x=2 \cos t, y=2 \sin t$. But, as described in part (b), a particle that follows the path given by $x=2 \cos t, y=2 \sin t$ will go counterclockwise, not clockwise. We saw in part (b) how to deal with that wrinkle. A particle that follows the path given by $x=2 \cos (-t), y=2 \sin (-t)$ will travel clockwise as $t$ increases. However, when $t=0$, this parameterization gives $(x, y)=(2,0)$, and we want the particle to start at $(0,-2)$. We take care of that with a phase shift, using the parameterization $x=2 \cos \left(-t-\frac{\pi}{2}\right), y=2 \sin \left(-t-\frac{\pi}{2}\right)$.

We're not finished yet! We still have to worry about how fast the particle travels around the circle. The particle makes a full revolution in 4 seconds, so it must be back at $(0,-2)$ after 4 seconds. Therefore, we need the periods of the trig functions we use in our parameterization to be 4 . Since the period of a function of the form $\sin a t$ or $\cos a t$ is $\frac{2 \pi}{|a|}$ (for $a \neq 0$ ), we must have $|a|=\frac{\pi}{2}$. Therefore, a parameterization for the path of the particle is $x=2 \cos \left(-\frac{\pi}{2} t-\frac{\pi}{2}\right), y=2 \sin \left(-\frac{\pi}{2} t-\frac{\pi}{2}\right)$.

This isn't the only way we can express this parameterization. We can use trigonometric identities to

163

---

<!-- Page 164 -->

CHAPTER 5. PARAMETERIZATION AND TRIGONOMETRIC COORDINATE SYSTEMS

simplify it. Since $\cos \left(\theta-\frac{\pi}{2}\right)=\sin \theta$ and $\sin \left(\theta-\frac{\pi}{2}\right)=-\cos \theta$, we can express our parameterization as $x=2 \sin \left(-\frac{\pi}{2} t\right), y=-2 \cos \left(-\frac{\pi}{2} t\right)$. Also, noting that $\sin (-\theta)=-\sin \theta$ and $\cos (-\theta)=\cos \theta$, we can express the parameterization as $x=-2 \sin \left(\frac{\pi}{2} t\right), y=-2 \cos \left(\frac{\pi}{2} t\right)$.

We can check this answer by noting that when $t=0$, we have $(x, y)=(0,-2)$, as expected. When $t=1$, the particle has traveled one quarter-circle clockwise about the origin, and be at $(-2,0)$. Sure enough, our parameterization gives $(x, y)=(-2,0)$ when $t=1$.

We say that we parameterize an equation when we find parametric equations for the variables in the equation. So, for example, we found that we can parameterize $x^{2}+y^{2}=1$ as $x=\cos \theta, y=\sin \theta$. However, we also saw that this is not the only way to parameterize $x^{2}+y^{2}=1$.

Concept: There are usually many ways to parameterize a given equation.

Problem 5.6: Parameterize the equation $x^{2}-3 y^{2}=1$.

Solution for Problem 5.6: The graph of $x^{2}-3 y^{2}=1$ is a hyperbola. What's wrong with this solution:

Bogus Solution: We add $3 y^{2}$ to both sides and take the square root. This gives us the
equation $x= \pm \sqrt{1+3 y^{2}}$. So, the graph of $x= \pm \sqrt{1+3 t^{2}}, y=t$ is the same as the graph of $x^{2}-3 y^{2}=1$.

The problem here is that $\pm \sqrt{1+3 t^{2}}$ is not a function. We can say that the graph of $x=\sqrt{1+3 t^{2}}, y=t$ together with the graph of $x=-\sqrt{1+3 t^{2}}, y=t$ gives us the graph of $x^{2}-3 y^{2}=1$, but we still do not have a single pair of functions $f(t)$ and $g(t)$ such that the graph of $x=f(t), y=g(t)$ is the graph of $x^{2}-3 y^{2}=1$.

We've already seen a couple of examples in which trig identities helped us relate parametric equations to an equation in which $x$ and/or $y$ are squared, so we look for a way for apply trig identities here. Specifically, we look for identities in which we have a difference of squares of trig functions, since the equation $x^{2}-3 y^{2}=1$ has a difference of squares of variable terms $x$ and $\sqrt{3} y$. We might consider the trig identity
$$\cos ^{2} \theta-\sin ^{2} \theta=\cos 2 \theta,$$
but that isn't promising for a couple of reasons. First, there's the $\cos 2 \theta$ on the right-what will we do with that? Also, we figure that $x$ probably can't be some constant times $\cos \theta$ or $\sin \theta$, since there are solutions to the equation $x^{2}-3 y^{2}=1$ in which $x$ and $y$ are arbitrarily large numbers. Back to the drawing board.

An identity that involves squares of trig functions besides sine and cosine is $\tan ^{2} \theta+1=\sec ^{2} \theta$. Rearranging this gives $\sec ^{2} \theta-\tan ^{2} \theta=1$. Aha! If we let $x^{2}=\sec ^{2} \theta$ and $3 y^{2}=\tan ^{2} \theta$, then $x^{2}-3 y^{2}$ becomes $\sec ^{2} \theta-\tan ^{2} \theta$, which we know equals 1 . So, we can let $x=\sec \theta$ and $y=\frac{1}{\sqrt{3}} \tan \theta$ be the desired parametric equations. (We could have taken the negative square root in either equation and produced valid parametric equations, too.)

But why can we "take the square root" here to get a valid parameterization, but we couldn't do so in the Bogus Solution? We rejected the result of Bogus Solution, $x= \pm \sqrt{1+3 t^{2}}, y=t$ because $\pm \sqrt{1+3 t^{2}}$ is not a function. But what if took the positive square root and wrote the parameterization as $x=\sqrt{1+3 t^{2}}, y=t$ ? The problem here is that this parameterization only produces points for which $x>0$. All points with $x<0$ that are on the graph of $x^{2}-3 y^{2}=1$, such as $(-1,0)$, are excluded from the graph of $x=\sqrt{1+3 t^{2}}, y=t$.

164

---

<!-- Page 165 -->

5.1. PARAMETERIZATION

With this in mind, we check to make sure that the graph of $x=\sec \theta, y=\frac{1}{\sqrt{3}} \tan \theta$ does capture the full hyperbola that is the graph of $x^{2}-3 y^{2}=1$. As $\theta$ ranges from $-\frac{\pi}{2}$ to $\frac{\pi}{2}$, we produce the branch of the hyperbola for which $x$ is positive, where we produce the upper half of this branch when $0 \leq \theta \leq \frac{\pi}{2}$ and the lower half when $-\frac{\pi}{2}<\theta \leq 0$. Then, as $\theta$ ranges from $\frac{\pi}{2}$ to $\frac{3 \pi}{2}$, we produce the branch of the hyperbola for which $x$ is negative. So, the entire hyperbola is produced by graphing $x=\sec \theta, y=\frac{1}{\sqrt{3}} \tan \theta$.

Problem 5.7: I'm riding my bike at a constant speed of 20 miles per hour on flat land when I ride over a dot of fresh yellow paint, thereby getting a yellow spot on my front wheel, which is 2 feet in diameter. I continue riding my bike in a straight line at 20 miles per hour. When $t$ seconds have passed since running over the dot, how many feet is the yellow spot on my tire from the yellow dot I ran over?

Solution for Problem 5.7: What's wrong with this solution:

There are several mistakes here. First, $t$ is in seconds, my speed is in miles per hour, and we want the answer in feet. So, we have to convert 20 miles per hour to feet per second. Since there are 5280 feet in a mile, 20 miles is $20 \cdot 5280$ feet. There are 60 minutes in an hour and 60 seconds in each minute, so there are $60 \cdot 60=3600$ seconds in an hour. Therefore, $20 \cdot 5280$ feet per hour is $20 \cdot 5280 / 3600$ feet per second, which is approximately 29.33 feet per second.

The more interesting mistake comes from the fact that the answer is not simply $29.33 t$ feet. The bike has moved $29.33 t$ feet forward, because it has moved in a straight line at 29.33 feet per second for $t$ seconds. However, the spot has not moved in a straight line. Sometimes it is touching the ground, sometimes it is at the top of the wheel, and most of the time it is somewhere in-between. The spot doesn't move in a straight line-as the center of the wheel moves forward, the spot rotates around it at constant rate.

To figure out where the spot is after $t$ seconds, we have to take both the forward motion of the bike and the rotary motion of the wheel into account. We'll do so by considering the horizontal motion of the spot and the vertical motion of the spot separately. We let $x(t)$ be the distance forward the spot has moved in $t$ seconds, and $y(t)$ be how far off the ground the spot is after $t$ seconds. In other words, we will find parametric equations for the location of the spot. Then, the distance from the starting point of the spot to its location after $t$ seconds is simply $\sqrt{(x(t))^{2}+(y(t))^{2}}$.

First, we tackle the horizontal movement. The center of the wheel moves forward at a speed of approximately $29.33 t$ feet per second. However, the spot has not always moved the same distance forward as the center of the wheel has. Sometimes it's a little ahead of the center of the wheel, and sometimes it's a little behind the center of the wheel. To figure out exactly where the spot is relative to the center of the wheel, we have to figure out how much the spot has rotated around the center of the wheel. So, we have to figure out how much the wheel has turned.

For the moment, we'll forget about the fact that the wheel is moving forward and focus on the rotation, so we can figure out where the spot is relative to the center of the wheel at time $t$. The spot starts directly below the center of the wheel, and then turns an angle $\theta$. We can figure out where the spot is relative to the center in much the same way we tackled the Ferris wheel problem on page 62. We think of the wheel as the unit circle. Moreover, the radius of the bike wheel is 1 foot , so, because we are using feet as our units, the wheel really is a unit circle.

Extra! The path the spot follows in Problem 5.7 is called a cycloid. Galileo gave the curve its name, and mathematicians of the 17th century argued so much about properties of the curve that it became known as the "Helen of Geometers." Source: "Cycloid" by E. Weisstein

165

---

<!-- Page 166 -->

CHAPTER 5. PARAMETERIZATION AND TRIGONOMETRIC COORDINATE SYSTEMS

The spot starts at the "bottom" of the circle, corresponding to an angle of $\frac{3 \pi}{2}$. We let the wheel move in the "positive" direction, as shown, so that the wheel rotates clockwise. Suppose the spot rotates clockwise an angle $\theta$ about the center, as suggested by the grey spots and arrows. We can think of the spot as the terminal point of the angle $\frac{3 \pi}{2}-\theta$. So, the spot's horizontal displacement from the wheel's center is $\cos \left(\frac{3 \pi}{2}-\theta\right)$ feet and its vertical displacement from the center is $\sin \left(\frac{3 \pi}{2}-\theta\right)$ feet. To find $x(t)$ and $y(t)$, we must combine the horizontal displacement relative to the center of the wheel with the fact that the wheel moves forward $29.33 t$ feet, and we note that the center of the wheel is 1 foot off the ground. So, we have
$$\begin{array}{l}
x(t) \approx 29.33 t+\cos \left(\frac{3 \pi}{2}-\theta\right), \\
y(t)=1+\sin \left(\frac{3 \pi}{2}-\theta\right) .
\end{array}$$

Uh-oh. What do we do about $\theta$ ? We have to express $\theta$ in terms of $t$, too. Fortunately, that's not too hard to do. When the wheel turns a full rotation of $2 \pi$, the bike moves forward by the circumference of the wheel, which is $2 \pi$ feet, since the diameter of the wheel is 2 feet. So, the number of radians the wheel turns equals the distance the bike moves forwards in feet (this is a convenient coincidence caused by the fact that the wheel has radius 1 foot). Therefore, in the $t$ seconds that the bike moves forward $29.33 t$ feet, the wheel turns an angle $\theta=29.33 t$ radians. So, the parametric equations for the position of the spot are
$$\begin{array}{l}
x(t) \approx 29.33 t+\cos \left(\frac{3 \pi}{2}-29.33 t\right), \\
y(t) \approx 1+\sin \left(\frac{3 \pi}{2}-29.33 t\right) .
\end{array}$$

Applying angle sum identities for sine and cosine, we have
$$\begin{array}{l}
x(t) \approx 29.33 t-\sin 29.33 t, \\
y(t) \approx 1-\cos 29.33 t .
\end{array}$$

Therefore, the distance from the spot on the wheel to the dot on the road is
$$\begin{aligned}
\sqrt{(x(t))^{2}+(y(t))^{2}} & \approx \sqrt{(29.33 t-\sin 29.33 t)^{2}+(1-\cos 29.33 t)^{2}} \\
& \approx \sqrt{860.25 t^{2}-58.66 t \sin 29.33 t+\sin ^{2} 29.33 t+1-2 \cos 29.33 t+\cos ^{2} 29.33 t} \\
& =\sqrt{860.25 t^{2}-58.66 t \sin 29.33 t-2 \cos 29.33 t+2} .
\end{aligned}$$

Exercises
5.1.1 What is the slope of the line that is the graph of $x=3 t+7, y=8 t-5$ ?
5.1.2 Find the graph of the parametric equations $x=3 \cos 2 t, y=-3 \sin 2 t$.
5.1.3 Find the graph of the parametric equations $x=-3+5 \cos \theta, y=2+5 \sin \theta$.
5.1.4 Find the graph of the parametric equations $x=4 \cos 2 t, y=1+\cos ^{2} 2 t$.
5.1.5 Find parametric equations for $x$ and $y$ such that $4 x^{2}+9 y^{2}=144$.
5.1.6 A particle starts at $(1,5)$ and travels at a constant speed in a circle around the point $(4,5)$. Find parametric equations to describe the location of the particle $t$ seconds after it starts moving if the particle travels counterclockwise and takes $8 \pi$ seconds to complete a full revolution around the circle.

166

---

<!-- Page 167 -->

5.2. POLAR COORDINATES
5.1.7 ★ What is the graph of the parametric equations $x=\frac{4}{1+t^{2}}, y=\frac{4 t}{1+t^{2}}$ ? Hints: 50,128
5.2 Polar Coordinates

When we plot points on the Cartesian plane, we typically identify the location of each point with coordinates that denote where the point is horizontally and vertically with respect to a point we call the origin. These are the $x$ and $y$-coordinates that you're already used to; we sometimes refer to these as rectangular coordinates. While this is the most common method we use to identify the location of a point on a plane, it is not the only method.

Polar coordinates offer another method for denoting the location of a point on a plane. As with rectangular coordinates, we start with a point we call the origin and we identify the location of each point with an ordered pair, $(r, \theta)$. The $r$-coordinate is the distance from the point to the origin; we call this coordinate the radial coordinate. The $\theta$-coordinate is the angular coordinate, which we define in the same way we related angles to points on the unit circle. A point with $\theta=0^{\circ}$ is directly to the right of the origin, a point with $\theta=90^{\circ}$ is directly above the origin, a point with $\theta=180^{\circ}$ is directly to the left of the origin, and so on, as depicted at right. For example, point $A$ at right has polar coordinates ( $3,30^{\circ}$ ) and point $B$ has polar coordinates ( $2,240^{\circ}$ ).

While each point only has one possible representation in rectangular coordinates, each point has multiple representations in polar coordinates.
For example, we can add $360^{\circ}$ to the angle, or subtract $360^{\circ}$ from it. So, the polar coordinates of $A$ could be written ( $3,390^{\circ}$ ) or ( $3,750^{\circ}$ ). We can also use a negative radius, which means "go in the direction opposite the one indicated by $\theta$." For example, we could express $A$ as $\left(-3,210^{\circ}\right)$, which tells us that $A$ is 3 units in the direction opposite $210^{\circ}$, which is the direction of $30^{\circ}$. Similarly, the polar coordinates $(r, \theta)$ and $\left(-r, \theta+180^{\circ}\right)$ always refer to the same point. We can also use a negative angle, so point $B$ above could be expressed as $\left(2,-120^{\circ}\right)$.

Problems
Problem 5.8: Convert each of the following rectangular coordinates to polar coordinates.
(a) $(0,-3)$
(c) $(-2 \sqrt{3},-6)$
(b) $(5,5)$

Problem 5.9: Convert each of the following polar coordinates to rectangular coordinates.
(a) $\left(8,60^{\circ}\right)$
(c) $\left(4 \sqrt{2}, 315^{\circ}\right)$
(b) $\left(12,-\frac{2 \pi}{3}\right)$

167

---

<!-- Page 168 -->

CHAPTER 5. PARAMETERIZATION AND TRIGONOMETRIC COORDINATE SYSTEMS

Problem 5.10:
(a) What are the rectangular coordinates of the point with polar coordinates $(1, \theta)$ ?
(b) What are the rectangular coordinates of the point with polar coordinates $(r, \theta)$ ? (You can assume $r>0$.)
(c) Suppose point $P$ is ( $x, y$ ) in rectangular coordinates and ( $r, \theta$ ) in polar coordinates, where $r>0$. Find $r$ in terms of $x$ and $y$. How must we modify our answer if we remove the restriction $r>0$ ? How is $\tan \theta$ related to $x$ and $y$ ?

Problem 5.11: When we graph an equation that has the variables $x$ and $y$, the graph consists of all points $(x, y)$ on the Cartesian plane that satisfy the equation. Similarly, the graph of an equation that has the variables $r$ and $\theta$ consists of all points with polar coordinates $(r, \theta)$ that satisfy the equation.
(a) What is the graph of $r=5$ ?
(b) What is the graph of $\theta=20^{\circ}$ ?

Problem 5.12:
(a) Graph the equation $r=6 \sin \theta$. Use your graph to guess the rectangular form of this equation.
(b) Prove that $r=6 \sin \theta$ is equivalent to the rectangular form you find in part (a).

Problem 5.13: In rectangular form, the general form of an equation whose graph is the circle with center ( $h, k$ ) and radius $t$ is
$$(x-h)^{2}+(y-k)^{2}=t^{2}$$

In this problem, we find the polar form of this equation. That is, we find the general form of an equation whose graph is the circle with center ( $r_{0}, \alpha$ ) (in polar coordinates) and radius $t$.
(a) Express $h$ and $k$ in terms of $r_{0}$ and $\alpha$.
(b) Show that the polar form of the given rectangular form is $r^{2}-2 r r_{0} \cos (\theta-\alpha)+r_{0}^{2}=t^{2}$.

Problem 5.14:
(a) What are the rectangular coordinates of the point that results when $(5 \sqrt{2}, 5 \sqrt{6})$ is rotated $\frac{2 \pi}{3}$ counterclockwise about the origin? Hints: 48
(b) Show that if the point $(x, y)$ is rotated $\theta$ counterclockwise about the origin, the result has rectangular coordinates
$$(x \cos \theta-y \sin \theta, y \cos \theta+x \sin \theta)$$

Problem 5.15: Let $h$ and $k$ be constants, and let $a$ and $b$ be positive constants with $a>b$. The graph of an equation of the form
$$\frac{(x-h)^{2}}{a^{2}}+\frac{(y-k)^{2}}{b^{2}}=1$$
is an ellipse whose major axis has length $2 a$. Every ellipse in the Cartesian plane with a horizontal major axis is the graph of an equation of this form.

The graph of the equation $7 x^{2}-6 \sqrt{3} x y+13 y^{2}=64$ is also an ellipse. Find the length of its major axis. Hints: 246

Problem 5.8: Convert each of the following rectangular coordinates to polar coordinates.
(a) $(0,-3)$
(b) $(5,5)$
(c) $(-2 \sqrt{3},-6)$

168

---

<!-- Page 169 -->

5.2. POLAR COORDINATES

Solution for Problem 5.8:
(a) The point $(0,-3)$ is 3 units directly below the origin. Because the point is 3 units from the origin, the point has $r=3$ in polar coordinates. Since the point is directly below the origin, the point has $\theta=270^{\circ}$. So, the polar coordinates of the point are $\left(3,270^{\circ}\right)$. As noted in the introduction to this section, there are many other ways we can express the polar coordinates of the point, such as $\left(3,-90^{\circ}\right),\left(-3,90^{\circ}\right)$, or $\left(3,630^{\circ}\right)$. Make sure you see why each of these describes the same point as $\left(3,270^{\circ}\right)$.
(b) The point $(5,5)$ is point $P$ at right. The rectangular coordinates give us $P A=A O=5$, so $\triangle P A O$ is an isosceles right triangle. Therefore, we have $P O=5 \sqrt{2}$ and $\angle P O A=45^{\circ}$, and the polar coordinates of point $P$ are ( $5 \sqrt{2}, 45^{\circ}$ ).
(c) Point $Q$ at right is $(-2 \sqrt{3},-6)$, so we have $A O=2 \sqrt{3}$ and $Q A=6$. To find the radius in polar coordinates, we note that $Q O=\sqrt{Q A^{2}+A O^{2}}=4 \sqrt{3}$. Because the hypotenuse of $\triangle Q A O$ is double one of the legs, we recognize that $\triangle Q A O$ is a 30-60-90 right triangle. Since $\angle Q O A$ is opposite the longer leg, we have $\angle Q O A=60^{\circ}$. Point $Q$ is $60^{\circ}$ counterclockwise from the negative $x$-axis, so its angle in polar coordinates is $180^{\circ}+60^{\circ}=240^{\circ}$. Therefore, point $Q$ in polar coordinates is $\left(4 \sqrt{3}, 240^{\circ}\right)$.

Problem 5.9: Convert each of the following polar coordinates to rectangular coordinates.
(a) $\left(8,60^{\circ}\right)$
(b) $\left(12,-\frac{2 \pi}{3}\right)$
(c) $\left(4 \sqrt{2}, 315^{\circ}\right)$

Solution for Problem 5.9:
(a) Let $P$ be the point with polar coordinates $\left(8,60^{\circ}\right)$, so that $P O=8$ and $\angle P O A=60^{\circ}$ in the diagram at right. From 30-60-90 triangle $P O A$, we have $A O=\frac{P O}{2}=4$ and $P A=A O \sqrt{3}= 4 \sqrt{3}$, so the rectangular coordinates of point $P$ are $(4,4 \sqrt{3})$.
(b) The point $Q$ with polar coordinates $\left(12,-\frac{2 \pi}{3}\right)$ is $\frac{2 \pi}{3}$ clockwise from the positive $x$-axis. Therefore, Q is in the third quadrant, as shown at right. Drawing altitude $\overline{Q A}$ produces right triangle $Q O A$ with hypotenuse $Q O=12$, from which we find $Q A=6 \sqrt{3}$ and $O A=6$. Since $Q$ is in the third quadrant, both rectangular coordinates are negative, so the rectangular coordinates of $Q$ are $(-6,-6 \sqrt{3})$.
(c) A point with angle $315^{\circ}$ in polar coordinates is in the fourth quadrant, $45^{\circ}$ clockwise from the positive $x$-axis as shown at right. From 45-45-90 triangle PAO, we find $P A=A O=4$, so the rectangular coordinates of $P$ are $(4,-4)$. (Make sure you see why the $y$-coordinate is negative.)

169

---

<!-- Page 170 -->

CHAPTER 5. PARAMETERIZATION AND TRIGONOMETRIC COORDINATE SYSTEMS

Problem 5.10:
(a) What are the rectangular coordinates of the point with polar coordinates $(1, \theta)$ ?
(b) What are the rectangular coordinates of the point with polar coordinates ( $r, \theta$ )? (You can assume $r>0$.)
(c) Suppose point $P$ is ( $x, y$ ) in rectangular coordinates and ( $r, \theta$ ) in polar coordinates, where $r>0$. Find $r$ in terms of $x$ and $y$. How must we modify our answer if we remove the restriction $r>0$ ? How is $\tan \theta$ related to $x$ and $y$ ?

Solution for Problem 5.10:
(a) The point $(1, \theta)$ is one unit from the origin, so it is on the unit circle. This point results when we rotate the point $(1,0)$ an angle of $\theta$ counterclockwise about the origin, which means that $(1, \theta)$ are the polar coordinates of the terminal point of $\theta$. We used this point to define $\cos \theta$ and $\sin \theta!$ Specifically, by our definitions of sine and cosine, the rectangular coordinates of the terminal point of $\theta$ are $(\cos \theta, \sin \theta)$.
(b) We can use our result from part (a) to quickly convert the polar coordinates ( $r, \theta$ ) to rectangular coordinates. In the diagram at right, point $Q$ has polar coordinates $(1, \theta)$, so it is on the unit circle. Point $P$ has polar coordinates $(r, \theta)$, so line $\overleftrightarrow{P Q}$ passes through the origin, as shown. Drawing altitudes from $P$ and $Q$ to the $x$-axis gives similar triangles PAO and QBO as shown. Because these triangles are similar, we have
$$\frac{P A}{Q B}=\frac{A O}{B O}=\frac{P O}{Q O} .$$

From the polar coordinates, we have $P O=r$ and $Q O=1$, so $\frac{P A}{Q B}=\frac{P O}{Q O}$ gives us $P A=r \cdot Q B$, and $\frac{A O}{B O}=\frac{P O}{Q O}$ gives us $A O=r \cdot B O$. Therefore, the distance from $P$ to each axis is $r$ times the corresponding distances from $Q$ to each axis. Combining this with the fact that $P$ is in the same quadrant as $Q$, we see that the rectangular coordinates of $P$ are $r$ times the rectangular coordinates of $Q$. So, the rectangular coordinates of $P$ are ( $r \cos \theta, r \sin \theta$ ).

We can check this result by using it to confirm our answers to Problem 5.9. Converting ( $8,60^{\circ}$ ) to rectangular coordinates gives ( $8 \cos 60^{\circ}, 8 \sin 60^{\circ}$ ), which is ( $4,4 \sqrt{3}$ ). Converting $\left(12,-\frac{2 \pi}{3}\right)$ to rectangular coordinates gives $\left(12 \cos \left(-\frac{2 \pi}{3}\right), 12 \sin \left(-\frac{2 \pi}{3}\right)\right)$, which is $(-6,-6 \sqrt{3})$. Converting $\left(4 \sqrt{2}, 315^{\circ}\right)$ to rectangular coordinates gives ( $4 \sqrt{2} \cos 315^{\circ}, 4 \sqrt{2} \sin 315^{\circ}$ ), which is ( $4,-4$ ). All three results match the ones we found earlier.
(c) The distance from $(x, y)$ in rectangular coordinates to the origin is $\sqrt{x^{2}+y^{2}}$. Therefore, when $(x, y)$ is converted to polar coordinates such that $r>0$, we have $r=\sqrt{x^{2}+y^{2}}$. If we remove the restriction that $r>0$, then we must instead write this relationship as $r^{2}=x^{2}+y^{2}$.

From the previous part, we have $x=r \cos \theta$ and $y=r \sin \theta$. If $x \neq 0$, we can divide the latter equation by the former to get $\frac{\sin \theta}{\cos \theta}=\frac{y}{x}$, so $\tan \theta=\frac{y}{x}$. If we restrict $r$ to be nonnegative, then we cannot deduce from $\tan \theta=\frac{y}{x}$ that $\theta=\arctan \frac{y}{x}$, because the range of arctangent is $\left(-\frac{\pi}{2}, \frac{\pi}{2}\right)$. For example, if we have $(x, y)=(-3,-3)$, then $\theta=\arctan \frac{y}{x}$ gives us $\theta=\frac{\pi}{4}$, but the angle when we express $(-3,-3)$ in polar coordinates with $r>0$ is $\frac{5 \pi}{4}$ radians, which is not the same angle as $\frac{\pi}{4}$ radians. If we allow $r$ to be negative, then we can let $\theta=\arctan \frac{y}{x}$, but then we must use the quadrant of $(x, y)$ to determine whether $r$ is positive or negative.

The best we can do to express $\theta$ simply in terms of $x$ and $y$ is to write $\tan \theta=\frac{y}{x}$ (for $x \neq 0$ ). If $x \neq 0$, there will be two values of $\theta$ with $0^{\circ} \leq \theta<360^{\circ}$ that satisfy this equation. We choose whichever one corresponds to the quadrant of $(x, y)$.

170

---

<!-- Page 171 -->

5.2. POLAR COORDINATES

Important: If $(x, y)$ in rectangular coordinates is the same point as $(r, \theta)$ in polar coordinates,
$\square$ then
$$x=r \cos \theta, \quad y=r \sin \theta, \quad r^{2}=x^{2}+y^{2}, \quad \tan \theta=\frac{y}{x},$$
where $\tan \theta=\frac{y}{x}$ holds only if $x \neq 0$. If $x=0$ and $y \neq 0$, then $\cos \theta=0$ and $r^{2}=y^{2}$. If $x=y=0$, then $r=0$ and $\theta$ can be anything.

There's no need to memorize these relationships; you can "see" them whenever you need them by visualizing the diagram at right, which depicts the relationship between a first quadrant point $P$ and the origin $O$ using both rectangular and polar coordinates. All of the equations in the box above can be read directly from the diagram.

We can use these relationships to give an algebraic explanation why the polar coordinates
( $-r, \theta+180^{\circ}$ ) give the same point as ( $r, \theta$ ). Converting ( $-r, \theta+180^{\circ}$ ) to rectangular coordinates, we have
$$\begin{array}{l}
x=(-r) \cos \left(\theta+180^{\circ}\right)=(-r)(-\cos \theta)=r \cos \theta \\
y=(-r) \sin \left(\theta+180^{\circ}\right)=(-r)(-\sin \theta)=r \sin \theta
\end{array}$$
which are the rectangular coordinates of ( $r, \theta$ ) as well.
Now that we understand how to locate points in polar coordinates, let's explore graphing equations in polar coordinates. When we graph an equation that has the variables $x$ and $y$, the graph consists of all points $(x, y)$ on the Cartesian plane that satisfy the equation. Similarly, the graph of an equation that has the variables $r$ and $\theta$ consists of all points with polar coordinates $(r, \theta)$ that satisfy the equation.

Problem 5.11:
(a) What is the graph of $r=5$ ?
(b) What is the graph of $\theta=20^{\circ}$ ?

Solution for Problem 5.11:
(a) The graph of $r=5$ consists of all points that are 5 units away from the origin. Therefore, the graph is the circle with radius 5 centered at the origin.

Figure 5.1: Graph of $r=5$

Figure 5.2: Graph of $\theta=20^{\circ}$
(b) Any point ( $r, \theta$ ) with $\theta=20^{\circ}$ and $r>0$ in polar coordinates must be on the ray from the origin that makes a $20^{\circ}$ angle with the positive $x$-axis such that the ray is in the first quadrant. Conversely, any point on this

171

---

<!-- Page 172 -->

CHAPTER 5. PARAMETERIZATION AND TRIGONOMETRIC COORDINATE SYSTEMS

ray can be expressed in polar coordinates with an angle of $20^{\circ}$. We must also include points for which the radius is 0 (the origin) or negative. If the radius $r$ is negative, then the point ( $r, 20^{\circ}$ ) is in the direction opposite the aforementioned ray. In other words, when $r$ is negative, the point ( $r, 20^{\circ}$ ) is on the line formed by continuing this ray past the origin into the third quadrant, as shown at right above. Every point on this ray in the third quadrant can be written as $\left(s, 200^{\circ}\right)$ for some positive value of $s$, and such a point can also be written as $\left(-s, 200^{\circ}-180^{\circ}\right)$, or $\left(-s, 20^{\circ}\right)$. Therefore, the graph of $\theta=20^{\circ}$ is a line through the origin that passes through the first and third quadrants and makes an angle of $20^{\circ}$ with the $x$-axis.

Having tackled the simplest equations, those in which $r$ or $\theta$ is constant, let's look at an equation that includes both $r$ and $\theta$.

Problem 5.12:
(a) Graph the equation $r=6 \sin \theta$. Use your graph to guess the rectangular form of this equation.
(b) Prove that $r=6 \sin \theta$ is equivalent to the rectangular form you find in part (a).

Solution for Problem 5.12:
(a) We get a feel for the graph by finding $r$ for several values of $\theta$. When $\theta=0$, we have $r=0$, so the graph passes through the origin. When $0^{\circ}<\theta<180^{\circ}$, we have $r>0$, so there are points in the first and second quadrants in the graph, corresponding to $0^{\circ}<\theta<90^{\circ}$ and $90^{\circ}<\theta<180^{\circ}$, respectively. The largest value of $r$ occurs when $\sin \theta=1$, which is when $\theta=90^{\circ}$. This gives $r=6$, so the point 6 units directly above the origin is on the graph. Since $6 \sin \theta$ increases from 0 to 6 as $\theta$ goes from $0^{\circ}$ to $90^{\circ}$, and then goes back down from 6 to 0 as $\theta$ goes from $90^{\circ}$ to $180^{\circ}$, the graph goes from the origin through the first quadrant to the point 6 above the origin ( $(0,6)$ in rectangular coordinates, $\left(6,90^{\circ}\right)$ in polar coordinates), and then back down through the second quadrant to the origin.

When $180^{\circ}<\theta<360^{\circ}$, the value of $6 \sin \theta$ is negative. As we pick a few values of $\theta$ in this range, we notice that each produces a point we already found when examining $0^{\circ}<\theta<180^{\circ}$, since a negative radius means the point is in the direction opposite $\theta$. For example, if $\theta=210^{\circ}$, we have $r=6 \sin \theta=-3$, which gives us the point ( $-3,210^{\circ}$ ). But this point is the same as ( $3,210^{\circ}-180^{\circ}$ ), which is ( $3,30^{\circ}$ ), a point we already know is on the graph. Similarly, since $\sin \left(\alpha+180^{\circ}\right)=-\sin \alpha$, we can write the point ( $6 \sin \left(\alpha+180^{\circ}\right), \alpha+180^{\circ}$ ) as $\left(-6 \sin \alpha, \alpha+180^{\circ}\right)$, which is the same as $(6 \sin \alpha, \alpha)$. Therefore, we only have to worry about the angles $0^{\circ} \leq \theta<180^{\circ}$ when constructing the graph of $r=6 \sin \theta$. Our table and the corresponding points are below.

\begin{tabular}{c|c}
$\theta$ & $(r, \theta)$ \\
\hline $0^{\circ}$ & $\left(0,0^{\circ}\right)$ \\
$30^{\circ}$ & $\left(3,30^{\circ}\right)$ \\
$45^{\circ}$ & $\left(3 \sqrt{2}, 45^{\circ}\right)$ \\
$60^{\circ}$ & $\left(3 \sqrt{3}, 60^{\circ}\right)$ \\
$90^{\circ}$ & $\left(6,90^{\circ}\right)$ \\
$120^{\circ}$ & $\left(3 \sqrt{3}, 120^{\circ}\right)$ \\
$135^{\circ}$ & $\left(3 \sqrt{2}, 135^{\circ}\right)$ \\
$150^{\circ}$ & $\left(3,150^{\circ}\right)$
\end{tabular}

These points suggest that our graph is the circle with center $(0,3)$ and radius 3 . We know that in rectangular coordinates, an equation of the form
$$(x-h)^{2}+(y-k)^{2}=t^{2}$$

172

---

<!-- Page 173 -->

5.2. POLAR COORDINATES

has a graph that is a circle with center ( $h, k$ ) and radius $t$, so we guess that the graph of the equation $r=6 \sin \theta$ is the same as the graph of the equation $x^{2}+(y-3)^{2}=3^{2}$.
(b) Now that we have some clue what we're looking for, we know just how to look for it. We wish to show that the graphs of $r=6 \sin \theta$ and $x^{2}+(y-3)^{2}=3^{2}$ are the same. We start by looking at the equations we found in Problem 5.10 to relate polar and rectangular coordinates:
$$x=r \cos \theta, \quad y=r \sin \theta, \quad r^{2}=x^{2}+y^{2}, \quad \tan \theta=\frac{y}{x} .$$

Our goal is to use these relationships to convert $r=6 \sin \theta$ to $x^{2}+(y-3)^{2}=3^{2}$ (or vice versa). First, we note that the origin is in both graphs. For all other points, we have $r>0$, so we don't have to worry about inadvertently multiplying or dividing by 0 when we multiply or divide an equation by $r$. Here are a couple ways that we can convert the polar coordinate equation $r=6 \sin \theta$ to the rectangular coordinate equation $x^{2}+(y-3)^{2}=3^{2}$ :

Method 1: Substitution for $\sin \theta$. We write $y=r \sin \theta$ as $\sin \theta=\frac{y}{r}$. Substituting this into $r=6 \sin \theta$ gives $r=\frac{6 y}{r}$. Multiplying both sides by $r$ gives $r^{2}=6 y$. Aha! We have an equation for $r^{2}$ in terms of $x$ and $y$. Substituting $r^{2}=x^{2}+y^{2}$ gives $x^{2}+y^{2}=6 y$. Rearranging this gives $x^{2}+y^{2}-6 y=0$, and completing the square in $y$ gives $x^{2}+(y-3)^{2}=3^{2}$.

Method 2: Manipulation to introduce $r^{2}$ and $r \sin \theta$. We know that we can convert $r \sin \theta$ into y, and convert $r^{2}$ into $x^{2}+y^{2}$, so we multiply both sides of $r=6 \sin \theta$ by $r$ to give $r^{2}=6 r \sin \theta$. We can now write this equation as $x^{2}+y^{2}=6 y$, and finish as before. The key step in this second approach is trying to force the expressions $r \sin \theta$ and $r^{2}$ into the equation, since we can then eliminate the polar variables by substituting the equivalent rectangular variable expressions.

We also could have started with the rectangular coordinate equation $x^{2}+(y-3)^{2}=3^{2}$ and converted it to the polar coordinate equation $r=6 \sin \theta$. We start by expanding and rearranging $x^{2}+(y-3)^{2}=3^{2}$ to get $x^{2}+y^{2}=6 y$. Then, for any point ( $x, y$ ), we can let $r^{2}=x^{2}+y^{2}$ and $y=r \sin \theta$, and we have $r^{2}=6 r \sin \theta$. Dividing $r^{2}=6 r \sin \theta$ by $r$ gives $r=6 \sin \theta$.

We conclude that the graph of $r=6 \sin \theta$ is the same as the graph of $x^{2}+(y-3)^{2}=3^{2}$, which is a circle with radius 3 centered at the point with rectangular coordinates $(0,3)$.

Problem 5.13: In rectangular form, the general form of an equation whose graph is the circle with center ( $h, k$ ) and radius $t$ is
$$(x-h)^{2}+(y-k)^{2}=t^{2}$$

Find the polar form of this equation. That is, find the general form of an equation whose graph is the circle with center ( $r_{0}, \alpha$ ) (in polar coordinates) and radius $t$.

Solution for Problem 5.13: Our goal is to turn the equation in terms of $x, y, h$ and $k$ into an equation in terms of $r, \theta, r_{0}$ and $\alpha$. Again, our equations from Problem 5.10 are the key. Here, the conversion is a bit easier than in Problem 5.12. Since we are given the rectangular form, we can simply substitute $x=r \cos \theta$ and $y=r \sin \theta$ to replace the rectangular variables ( $x, y$ ) with the polar variables ( $r, \theta$ ). This gives us
$$(r \cos \theta-h)^{2}+(r \sin \theta-k)^{2}=t^{2}$$

However, we still have to get rid of $h$ and $k$-these are rectangular coordinates as well. Just as we can use $x=r \cos \theta$ and $y=r \sin \theta$ to convert the variables ( $x, y$ ) to the variables ( $r, \theta$ ), we can use them to express the center's rectangular coordinates $(h, k)$ in terms of its polar coordinates $\left(r_{0}, \alpha\right)$. We therefore have $h=r_{0} \cos \alpha$ and $k=r_{0} \sin \alpha$, and the equation of our circle is
$$\left(r \cos \theta-r_{0} \cos \alpha\right)^{2}+\left(r \sin \theta-r_{0} \sin \alpha\right)^{2}=t^{2}$$

173

---

<!-- Page 174 -->

CHAPTER 5. PARAMETERIZATION AND TRIGONOMETRIC COORDINATE SYSTEMS

Expanding the squares gives
$$r^{2} \cos ^{2} \theta-2 r r_{0} \cos \theta \cos \alpha+r_{0}^{2} \cos ^{2} \alpha+r^{2} \sin ^{2} \theta-2 r r_{0} \sin \theta \sin \alpha+r_{0}^{2} \sin ^{2} \alpha=t^{2}$$

Seeing squares of cosine and sine makes us look for ways to add them to get 1 . Fortunately, factoring does the trick both for both $\theta$ and $\alpha$. We can rewrite the equation as
$$r^{2}\left(\cos ^{2} \theta+\sin ^{2} \theta\right)-2 r r_{0}(\cos \theta \cos \alpha+\sin \theta \sin \alpha)+r_{0}^{2}\left(\cos ^{2} \alpha+\sin ^{2} \alpha\right)=t^{2}$$

Applying trigonometric identities to each of the three expressions in parentheses, the equation becomes
$$r^{2}-2 r r_{0} \cos (\theta-\alpha)+r_{0}^{2}=t^{2}$$

Problem 5.14:
(a) What are the rectangular coordinates of the point that results when $(5 \sqrt{2}, 5 \sqrt{6})$ is rotated $\frac{2 \pi}{3}$ counterclockwise about the origin?
(b) Show that if the point $(x, y)$ is rotated $\theta$ counterclockwise about the origin, the result has rectangular coordinates $(x \cos \theta-y \sin \theta, y \cos \theta+x \sin \theta)$.

Solution for Problem 5.14:
(a) Aside from the name of this section, we have a number of clues to try polar coordinates. First, we don't have good tools for handling rotations in rectangular coordinates (aside from rotating by multiples of $\frac{\pi}{2}$ ). Second, rotation has to do with angles, and we have angles in polar coordinates, not in rectangular coordinates. So, we start by converting $(5 \sqrt{2}, 5 \sqrt{6})$ to polar coordinates. We have $r^{2}=x^{2}+y^{2}=50+150=200$, so we can let $r=10 \sqrt{2}$. We also have $\tan \theta=\frac{y}{x}=\sqrt{3}$. Since the point is in the first quadrant and we are using the positive value of $r$, we have $\theta=\frac{\pi}{3}$. Therefore, the point $(5 \sqrt{2}, 5 \sqrt{6})$ in rectangular coordinates is the same as the point $\left(10 \sqrt{2}, \frac{\pi}{3}\right)$ in polar coordinates.

Finding the result of rotating $\left(10 \sqrt{2}, \frac{\pi}{3}\right)$ counterclockwise $\frac{2 \pi}{3}$ about the origin is easy. We simply add $\frac{2 \pi}{3}$ to the angle, since rotation about the origin changes the angle by the amount of the rotation, but it doesn't change the distance from the point to the origin. So, rotating $\left(10 \sqrt{2}, \frac{\pi}{3}\right)$ counterclockwise $\frac{2 \pi}{3}$ gives us $(10 \sqrt{2}, \pi)$. Converting this back to rectangular coordinates gives $(-10 \sqrt{2}, 0)$.
(b) We use our first part as a guide.

Concept: When proving a formula, it's often useful to work out a specific example, and
then use the example as a guide to find the proof.

Let $(r, \alpha)$ be the polar coordinates of the point with rectangular coordinates $(x, y)$. Rotating $(r, \alpha)$ counterclockwise about the origin by $\theta$ gives the point with polar coordinates $(r, \alpha+\theta)$. The rectangular coordinates of this point are ( $r \cos (\alpha+\theta), r \sin (\alpha+\theta)$ ). Applying angle sum identities, we can write these coordinates as
$$(r \cos \alpha \cos \theta-r \sin \alpha \sin \theta, r \sin \alpha \cos \theta+r \sin \theta \cos \alpha) .$$

That's not quite what we were looking for-the result we wish to prove has $x$ and $y$, and no $r$ or $\alpha$. Since $(x, y)$ in rectangular coordinates is ( $r, \alpha$ ) in polar coordinates, we have $x=r \cos \alpha$ and $y=r \sin \alpha$. We can substitute $x$ for $r \cos \alpha$ and $y$ for $\sin \alpha$ in the long coordinates above to give the simpler-looking
$$(x \cos \theta-y \sin \theta, y \cos \theta+x \sin \theta)$$

174

---

<!-- Page 175 -->

5.2. POLAR COORDINATES

Important: The image of the point $(x, y)$ upon a rotation $\theta$ counterclockwise about the
origin is ( $x \cos \theta-y \sin \theta, y \cos \theta+x \sin \theta$ ).

Problem 5.15: Let $h$ and $k$ be constants, and let $a$ and $b$ be positive constants with $a>b$. The graph of an equation of the form
$$\frac{(x-h)^{2}}{a^{2}}+\frac{(y-k)^{2}}{b^{2}}=1$$
is an ellipse whose major axis has length $2 a$. Every ellipse in the Cartesian plane with a horizontal major axis is the graph of an equation of this form.

The graph of the equation $7 x^{2}-6 \sqrt{3} x y+13 y^{2}=64$ is also an ellipse. Find the length of its major axis.
Solution for Problem 5.15: Let $\mathcal{E}$ be the graph of $7 x^{2}-6 \sqrt{3} x y+13 y^{2}=64$. If we can manipulate $7 x^{2}-6 \sqrt{3} x y+13 y^{2}=64$ into the form $\frac{(x-h)^{2}}{a^{2}}+\frac{(y-k)^{2}}{b^{2}}=1$, then we can easily find the length of the major axis. Unfortunately, the $x y$ term is a problem. There is no $x y$ term in the form we're given for an ellipse with a horizontal major axis, so $\mathcal{E}$ must be an ellipse whose major axis is not horizontal. If our ellipse had a horizontal major axis, we could solve the problem quickly. So, we try to relate $\mathcal{E}$ to an ellipse with a horizontal major axis that is the same length as the major axis of E.

Rotation does not affect length, so we can view $\mathcal{E}$ as the result of rotating an ellipse $\mathcal{E}^{\prime}$ with a horizontal major axis. Suppose the required rotation is a counterclockwise rotation by $\theta$, so that for every point $\left(x^{\prime}, y^{\prime}\right)$ on $\mathcal{E}^{\prime}$, there is a point ( $x, y$ ) on $\mathcal{E}$ that is a counterclockwise rotation by $\theta$ of ( $x^{\prime}, y^{\prime}$ ). From the result of Problem 5.14, we have
$$\begin{array}{l}
x=x^{\prime} \cos \theta-y^{\prime} \sin \theta \\
y=x^{\prime} \sin \theta+y \cos \theta
\end{array}$$

Substituting these into $7 x^{2}-6 \sqrt{3} x y+13 y^{2}=64$ produces
$$7\left(x^{\prime} \cos \theta-y^{\prime} \sin \theta\right)^{2}-6 \sqrt{3}\left(x^{\prime} \cos \theta-y^{\prime} \sin \theta\right)\left(x^{\prime} \sin \theta+y^{\prime} \cos \theta\right)+13\left(x^{\prime} \sin \theta+y^{\prime} \cos \theta\right)^{2}=64 .$$

Yikes. Multiplying that out looks scary. Fortunately, we don't have to do so just yet. Our goal is to eliminate the $x^{\prime} y^{\prime}$ term. So, we just look at the $x^{\prime} y^{\prime}$ terms in the expansion of the left side, which are
$$-14 x^{\prime} y^{\prime} \cos \theta \sin \theta-6 \sqrt{3} x^{\prime} y^{\prime} \cos ^{2} \theta+6 \sqrt{3} x^{\prime} y^{\prime} \sin ^{2} \theta+26 x^{\prime} y^{\prime} \cos \theta \sin \theta$$

We want these terms to cancel, so we must have
$$-14 \cos \theta \sin \theta-6 \sqrt{3} \cos ^{2} \theta+6 \sqrt{3} \sin ^{2} \theta+26 \cos \theta \sin \theta=0$$

Simplifying a bit gives us $12 \cos \theta \sin \theta-6 \sqrt{3}\left(\cos ^{2} \theta-\sin ^{2} \theta\right)=0$. Now we see a chance to use trig identities. We have $\cos \theta \sin \theta=\frac{1}{2} \sin 2 \theta$ and $\cos ^{2} \theta-\sin ^{2} \theta=\cos 2 \theta$, so we can write the equation as
$$6 \sin 2 \theta-6 \sqrt{3} \cos 2 \theta=0$$
from which we have $(\sin 2 \theta) /(\cos 2 \theta)=\sqrt{3}$, or $\tan 2 \theta=\sqrt{3}$. Since $\tan 60^{\circ}=\sqrt{3}$, we find that $2 \theta=60^{\circ}$, so $\theta=30^{\circ}$. This means that $\mathcal{E}$ is a $30^{\circ}$ counterclockwise rotation of $\mathcal{E}^{\prime}$ about the origin.

We can now find the equation whose graph is $\mathcal{E}^{\prime}$. Substituting $\theta=30^{\circ}$ into Equation (5.1) gives
$$7\left(x^{\prime} \cdot \frac{\sqrt{3}}{2}-y^{\prime} \cdot \frac{1}{2}\right)^{2}-6 \sqrt{3}\left(x^{\prime} \cdot \frac{\sqrt{3}}{2}-y^{\prime} \cdot \frac{1}{2}\right)\left(x^{\prime} \cdot \frac{1}{2}+y^{\prime} \cdot \frac{\sqrt{3}}{2}\right)+13\left(x^{\prime} \cdot \frac{1}{2}+y^{\prime} \cdot \frac{\sqrt{3}}{2}\right)^{2}=64 .$$

175

---

<!-- Page 176 -->

CHAPTER 5. PARAMETERIZATION AND TRIGONOMETRIC COORDINATE SYSTEMS

Multiplying both sides by 4 gets rid of the fractions and gives
$$7\left(\sqrt{3} x^{\prime}-y^{\prime}\right)^{2}-6 \sqrt{3}\left(\sqrt{3} x^{\prime}-y^{\prime}\right)\left(x^{\prime}+\sqrt{3} y^{\prime}\right)+13\left(x^{\prime}+\sqrt{3} y^{\prime}\right)^{2}=256$$

Expanding and then simplifying the left side gives
$$16\left(x^{\prime}\right)^{2}+64\left(y^{\prime}\right)^{2}=256$$

The $x^{\prime} y^{\prime}$ terms all canceled out, as expected. Dividing both sides by 256 puts the equation in the form of an ellipse described in the problem,
$$\frac{\left(x^{\prime}\right)^{2}}{4^{2}}+\frac{\left(y^{\prime}\right)^{2}}{2^{2}}=1$$

Comparing this to
$$\frac{x^{2}}{a^{2}}+\frac{y^{2}}{b^{2}}=1$$
we find $a=4$, so the length of the major axis is $2 a=8$.

Exercises
5.2.1 Convert each of the following rectangular coordinates to polar coordinates. (You may use a calculator if necessary.)
(a) $(-5,0)$
(b) $(6 \sqrt{2}, 6)$
(c) $(-4,-4 \sqrt{3})$
5.2.2 Convert each of the following polar coordinates to rectangular coordinates.
(a) $\left(7,210^{\circ}\right)$
(b) $\left(9,-180^{\circ}\right)$
(c) $\left(-8, \frac{9 \pi}{4}\right)$
5.2.3 Graph the equation $r=\frac{4}{2 \cos \theta-5 \sin \theta}$.
5.2.4 The final form we found in Problem 5.13 for an equation whose graph is a circle does not match the form of the equation we graphed in Problem 5.12. But the graph we found in Problem 5.12 is indeed a circle. This suggests we can write the equation we graphed in Problem 5.12, which is $r=6 \sin \theta$, in the form we found in Problem 5.13, which is $r^{2}-2 r r_{0} \cos (\theta-\alpha)+r_{0}^{2}=t^{2}$. Show that we can do so.
5.2.5 Let $A$ and $B$ be points with polar coordinates $\left(6,137^{\circ}\right)$ and $(12, \theta)$, respectively, and let $O$ be the origin.
(a) Find all possible values of $\theta$ with $0^{\circ} \leq \theta<360^{\circ}$ such that $\overline{A O} \perp \overline{B O}$.
(b) Find all possible values of $\theta$ with $0^{\circ} \leq \theta<360^{\circ}$ such that $\overline{A B} \perp \overline{A O}$.
5.2.6 What does the graph of $r=2+3 \theta$ look like, where $\theta \geq 0$ and we express $\theta$ in radians when computing $r$ ?
5.2.7 A regular hexagon with center at the origin has one vertex at $(3,3)$. Find all vertices of the hexagon that are in the second quadrant.

176

---

<!-- Page 177 -->

5.3. COORDINATES IN THREE DIMENSIONS
5.3 Coordinates in Three Dimensions

Just as we use the horizontal and vertical coordinates $(x, y)$ to identify the location of a point in the two-dimensional Cartesian plane, we can identify the location of a point in three-dimensional Cartesian space with three coordinates $(x, y, z)$. We call the plane in which $z=0$ the $x y$-plane. Points on this plane are identified by the coordinates ( $x, y, 0$ ), where the $x$ and $y$ have the horizontal and vertical meanings they have in the Cartesian plane. For other points $(x, y, z)$ in space, the $z$-coordinate indicates how far above $(z>0)$ or below $(z<0)$ the $x y$-plane the point is. The $x$ - and $y$-coordinates of $(x, y, z)$ are the same as those of the point in $z=0$ plane that is directly above or below the point $(x, y, z)$.

As shown in the diagram at right, we have a third axis in three dimensions, which we call the $z$-axis. In this diagram we depict the point $(4,3,5)$. We include edges of a right rectangular prism with opposite vertices at $(0,0,0)$ and (4,3,5) to help show the location of (4,3,5) in space.

Just as all points $(x, y, z)$ with $z=0$ form the $x y$-plane, the $y z$-plane consists of all points of the form $(0, y, z)$, and the $\boldsymbol{x} \boldsymbol{z}$-plane consists of all points of the form form $(x, 0, z)$.

In most of the three-dimensional diagrams we include in this book, we'll omit the negative portions of each axis, and remove the tick marks and numbers along the axes, since these diagrams can get very cluttered if all of this information is included. Sometimes, we'll even exclude the axes, and just include the key geometric figures.

Problems

Problem 5.16: We start our exploration of coordinates in three dimensions by finding a formula for the distance between two points in space.
(a) Let $A$ be ( $-3,4,6$ ) and $B$ be ( $4,-1,2$ ). Find $A B$.
(b) Find a formula for the distance between the points $\left(x_{1}, y_{1}, z_{1}\right)$ and $\left(x_{2}, y_{2}, z_{2}\right)$.

Problem 5.17: Describe the graph of the equation $x^{2}+y^{2}+z^{2}-6 x-4 y+8 z=7$.

Problem 5.16:
(a) Let $A$ be ( $-3,4,6$ ) and $B$ be ( $4,-1,2$ ). Find $A B$.
(b) Find a formula for the distance between the points $\left(x_{1}, y_{1}, z_{1}\right)$ and $\left(x_{2}, y_{2}, z_{2}\right)$.

Solution for Problem 5.16:
(a) We find $A B$ by considering the rectangular prism with $A$ and $B$ as opposite vertices and with each edge parallel to a coordinate axis, as shown at right. We can then find $A B$ by applying the Pythagorean Theorem twice. As shown in the diagram, the points $(4,4,2)$ and $(-3,4,2)$ are vertices of the prism. Let these be $C$ and $D$, respectively. Right triangle $B C D$ gives us
$$B D=\sqrt{B C^{2}+C D^{2}}=\sqrt{25+49}=\sqrt{74} .$$

Then, right triangle $A D B$ gives us
$$A B=\sqrt{B D^{2}+A D^{2}}=\sqrt{74+16}=3 \sqrt{10} .$$

177

---

<!-- Page 178 -->

CHAPTER 5. PARAMETERIZATION AND TRIGONOMETRIC COORDINATE SYSTEMS
(b) We follow the same strategy as in part (a). We construct the rectangular prism with ( $x_{1}, y_{1}, z_{1}$ ) and ( $x_{2}, y_{2}, z_{2}$ ) as opposite vertices and with edges parallel to the coordinate axes, as shown. From right triangle $B C D$, we have $B D^{2}=C D^{2}+B C^{2}$, and from right triangle $A B D$, we have
$$A B^{2}=B D^{2}+A D^{2}=C D^{2}+B C^{2}+A D^{2},$$
so $A B=\sqrt{C D^{2}+B C^{2}+A D^{2}}$. Writing $C D, B C$, and $A D$ in
terms of the coordinates as shown, we see that the distance between $\left(x_{1}, y_{1}, z_{1}\right)$ and $\left(x_{2}, y_{2}, z_{2}\right)$ is
$$\sqrt{\left(x_{2}-x_{1}\right)^{2}+\left(y_{2}-y_{1}\right)^{2}+\left(z_{2}-z_{1}\right)^{2}} \text {. }$$

\begin{tabular}{|l|}
\hline Important: The distance between the points $\left(x_{1}, y_{1}, z_{1}\right)$ and $\left(x_{2}, y_{2}, z_{2}\right)$ is \\
$\sqrt{\left(x_{2}-x_{1}\right)^{2}+\left(y_{2}-y_{1}\right)^{2}+\left(z_{2}-z_{1}\right)^{2}}$.
\end{tabular}

Problem 5.17: Describe the graph of the equation $x^{2}+y^{2}+z^{2}-6 x-4 y+8 z=7$.

Solution for Problem 5.17: The equation strongly resembles a two-variable equation whose graph is a circle, so we suspect the graph is a sphere. When confronted with similar equations with two variables, we typically complete the squares in the quadratics, so we try that here. Completing the square in $x$, in $y$, and in $z$ gives us
$$(x-3)^{2}+(y-2)^{2}+(z+4)^{2}=7+9+4+16=36$$

The left side looks a lot like the distance formula in three dimensions. In fact, the expression on the left equals the square of the distance between $(x, y, z)$ and $(3,2,-4)$. Since the right side is $6^{2}$, the equation tells us that the distance between $(x, y, z)$ and $(3,2,-4)$ is 6 . Sure enough, the graph of all such points is a sphere with center $(3,2,-4)$ and radius 6 .

Just as Cartesian coordinates are not the only way to describe the location of a point in a plane, the rectangular coordinates $(x, y, z)$ described above are not the only way to describe the location of a point in space. We'll now introduce two other ways to describe the location of a point in space.

The first is cylindrical coordinates. In cylindrical coordinates, the $x$ - and $y$ coordinates are replaced by $r$ - and $\theta$-coordinates such that the point in the Cartesian plane with rectangular coordinates $(x, y)$ has polar coordinates $(r, \theta)$. The third cylindrical coordinate is the same $z$-coordinate as in rectangular coordinates. A depiction of the point ( $r, \theta, z$ ) in cylindrical coordinates is shown at right. When expressing a point in polar coordinates, the radius always comes first, the angle second, and the $z$-coordinate last.

Relating the cylindrical $r$ - and $\theta$-cylindrical coordinates to rectangular coordinates in three dimensions is the same as relating polar coordinates ( $r, \theta$ ) to rectangular coordinates $(x, y)$ in two dimension. If the cylindrical coordinates $(r, \theta, z)$ represent
the same point as the rectangular coordinates ( $x, y, z$ ), then $x=r \cos \theta$ and $y=r \sin \theta$. As with polar coordinates, we usually choose $r$ to be nonzero and $\theta$ such that $0 \leq \theta<2 \pi$. However, $r$ can be negative and $\theta$ can be outside the interval $[0,2 \pi)$, just as with polar coordinates.

178

---

<!-- Page 179 -->

5.3. COORDINATES IN THREE DIMENSIONS

Cylindrical coordinates aren't a natural analogue to polar coordinates. When a point is expressed in polar coordinates, the absolute value of the $r$-coordinate is the distance from the point to the origin, but in cylindrical coordinates, the $r$-coordinate gives the distance from the point to the $z$-axis, not the origin. A more natural analogue in three dimensions to the polar coordinates of two dimensions starts with letting the first coordinate represent the distance from the origin to the point. We do just that when we describe a point's location with spherical coordinates.

The first spherical coordinate is $\rho$, pronounced "roh," which is the distance from the point to the origin. But specifying the distance from the origin to a point is not enough to determine exactly where the point is. In order to describe the location of the point, we need a pair of angles as well. The first of the two angles we use to describe a point $P$ in spherical coordinates is the same as the angle in cylindrical coordinates. We think of the half-plane that starts from the $z$-axis and extends through $P$. The angle $\theta$ is the angle between this plane and the positive $x$-axis, as shown, like the angle $\theta$ in cylindrical coordinates. We define the second angle $\phi$, pronounced "fee," as the angle between $\overline{O P}$ and the positive $z$-axis, as shown. Therefore, every point in space can be described with a triple ( $\rho, \theta, \phi$ ), with $\rho \geq 0,0 \leq \theta<2 \pi$ and $0 \leq \phi \leq \pi$.

While we usually restrict $\rho, \theta$, and $\phi$ such that $\rho \geq 0,0 \leq \theta<2 \pi$ and
$0 \leq \phi \leq \pi$, we don't have to. Allowing $\rho$ to be negative has the same effect as allowing $r$ to be negative in polar coordinates. When $r$ is negative in polar coordinates, the point is in the direction from the origin that is opposite the direction described by the $\theta$-coordinate. When $\rho$ is negative in polar coordinates, the point is in the direction from the origin that is opposite the direction described by the $\theta$ - and $\phi$-coordinates. So, for example, the point ( $1,0,1$ ) can be described as both ( $\sqrt{2}, 0, \frac{\pi}{4}$ ) and ( $-\sqrt{2}, \pi, \frac{3 \pi}{4}$ ) in spherical coordinates.

\begin{tabular}{|l|l|}
\hline WARNING!! & \begin{tabular}{l} 
When reading about spherical coordinates in another source, make sure you \\
know what each variable stands for and what the restrictions on each are. \\
While most sources will define the two angles in spherical coordinates in \\
essentially the same way we have here, some will use different variables \\
than we have. Even more confusing, some will use the same variables, but \\
reverse their meanings. Furthermore, some will restrict $\rho$ to be nonnegative, \\
and some will use $r$ rather than $\rho$
\end{tabular} \\
\hline
\end{tabular}

Problems
Problem 5.18:
(a) Describe the graph of all points with cylindrical coordinates $(r, \theta, z)$ such that $r=7$. Express the equation in rectangular coordinates.
(b) Describe the graph of $\theta=\frac{\pi}{3}$ in cylindrical coordinates. Express the equation in rectangular coordinates.

Problem 5.19: Suppose ( $\rho, \theta, \phi$ ) are the spherical coordinates of point $P$, where $\rho \geq 0$, and that ( $x, y, z$ ) are the rectangular coordinates of point $P$.
(a) Find $\rho$ in terms of $x, y$, and $z$.
(b) Let $O$ be the origin and $A$ be the foot of the altitude from $P$ to the $z$-axis. Find $A O$ in terms of $\rho, \theta$, and/or $\phi$.
(c) Find $x, y$, and $z$ in terms of $\rho, \theta$, and $\phi$.

179

---

<!-- Page 180 -->

CHAPTER 5. PARAMETERIZATION AND TRIGONOMETRIC COORDINATE SYSTEMS

Problem 5.20:
(a) Convert the cylindrical coordinates $\left(4, \frac{\pi}{3}, 4\right)$ to rectangular and spherical coordinates.
(b) Convert the spherical coordinates $\left(7, \frac{7 \pi}{4}, \frac{\pi}{3}\right)$ to rectangular and cylindrical coordinates.

Problem 5.21: Convert each of the following rectangular coordinates to cylindrical coordinates and to spherical coordinates.
(a) $(6,-6,-2 \sqrt{6})$
(b) $(-6,0,6 \sqrt{3})$

Problem 5.22:
(a) Describe the graph of the equation $z^{2}=x^{2}+y^{2}$.
(b) Find parametric equations for $x, y$, and $z$ for the equation $z^{2}=x^{2}+y^{2}$. (You will need two parameters.)

Problem 5.23:
(a) Describe the graph of all points with spherical coordinates $(\rho, \theta, \phi)$ such that $\rho=5$. Express the equation in rectangular coordinates, and give a parameterization of the equation for $x, y$, and $z$.
(b) Describe the graph of $\phi=\frac{2 \pi}{3}$ in spherical coordinates. Express the equation in rectangular coordinates.

For the final problem in this section, we need to understand how we determine the latitude and longitude that we typically use to locate points on the Earth's surface. To do so, we start with a great circle of a sphere, which is a cross-section of the sphere that has the same center as the sphere. We choose the great circle that is in the plane perpendicular to the axis of the Earth to be the equator of the earth. The equator has latitude $0^{\circ}$, and it divides the Earth into the Northern hemisphere and the Southern hemisphere.

The North and South Poles of the Earth are the points at which the axis intersects the surface of the Earth. To define longitude, we first choose one semicircle along the surface of the Earth, with the poles as endpoints, to be the prime meridian. We say that the longitude of any point on the prime meridian is $0^{\circ}$. For any point $P$ not on the prime meridian, we determine its longitude by considering the plane through $P$ parallel to the equator. Let this plane intersect the axis at $A$ and the prime meridian at $M$. Then, $\angle P A M$ is the longitude of $P$. We have one little wrinkle here-we add a direction to the longitude to tell us which way to go, east or west, to get to $P$ fastest from $M$. So, if $\angle P A M$ is $45^{\circ}$ and we go west from $M$ to get to $P$, then the latitude of $P$ is $45^{\circ} \mathrm{W}$, where the W stands for "west."

Now that we have longitude, we can use it to define latitude. First, we say the North and South Poles have latitudes $90^{\circ} \mathrm{N}$ and $90^{\circ} \mathrm{S}$, respectively. For any other point $T$ not on the equator, we let $E$ be the point on the equator with the same longitude as $T$ and let $O$ be the center of the Earth. Then, $\angle T O E$ gives us the latitude, where we assign the latitude the designation " N " if the point is in the Northern hemisphere and the designation " S " if it is in the Southern hemisphere. So, if $\angle T O E=30^{\circ}$ and $T$ is in the Northern hemisphere, we say that its latitude is $30^{\circ} \mathrm{N}$.

Note that the equator of the Earth is determined by the rotation of the Earth, whereas the prime meridian is an arbitrary choice. It was originally established by Sir George Airy as the Greenwich Meridian in 1851, and was established as the international standard by the International Meridian Conference in 1884.

180

---

<!-- Page 181 -->

5.3. COORDINATES IN THREE DIMENSIONS

It is now marked by a laser beam pointing towards the North Pole from the Royal Observatory in Greenwich, London.

Problem 5.24:
(a) What is the relationship between spherical coordinates and the latitude and longitude that we use to identify the location of points on the surface of the Earth?
(b) Why do we use a system much like spherical coordinates for points on the Earth's surface rather than using rectangular coordinates?
(c) Petr has lived his whole life in Petropavlovsk-Kamchatsky on the frigid northeastern shores of Siberia. He is sick of the cold, and has spent the last 5 years building a sailboat he hopes to sail to Honolulu, Hawaii, where he will be much warmer. If he sails at 10 km per hour, how many days will it take him to sail from Petropavlovsk-Kamchatsky, which has coordinates $52.92^{\circ} \mathrm{N}, 158.49^{\circ} \mathrm{E}$, to Honolulu, which has coordinates $21.31^{\circ} \mathrm{N}, 157.83^{\circ} \mathrm{W}$ ? You may assume the Earth is a sphere with radius 6370 kilometers, and that Petr travels along a single great circle of the sphere throughout his trip.

Problem 5.18:
(a) Describe the graph of all points with cylindrical coordinates $(r, \theta, z)$ such that $r=7$. Express the equation in rectangular coordinates.
(b) Describe the graph of the points in space such that $\theta=\frac{\pi}{3}$ in cylindrical coordinates. Express the equation in rectangular coordinates.

Solution for Problem 5.18:
(a) In two dimensions, the graph of $r=7$ is a circle centered at the origin with radius 7 . In three dimensions, we can let $z$ be any real number when we produce the graph of $r=7$. Therefore, every cross-section of the graph perpendicular to the $z$-axis is a circle with radius 7 centered at a point on the $z$-axis. Since all these circles have the same radius, the resulting graph of $r=7$ in three dimensions is a cylinder that extends forever in both directions of its axis. The radius of the cylinder is 7 , and the $z$-axis is the axis of the cylinder.

Just as in polar coordinates, we have
$$x^{2}+y^{2}=(r \cos \theta)^{2}+(r \sin \theta)^{2}=r^{2}\left(\cos ^{2} \theta+\sin ^{2} \theta\right)=r^{2} .$$

So, to express the equation $r=7$ in rectangular coordinates, we square the equation to get $r^{2}=49$, which gives $x^{2}+y^{2}=49$.
(b) In polar coordinates, the graph of $\theta=\frac{\pi}{3}$ is a line through the origin that makes an angle of $\frac{\pi}{3}$ with the $x$-axis such that the line passes through the first and third quadrants. Since we can use any value for the $z$-coordinate in the graph of $\theta=\frac{\pi}{3}$ in three dimensions, the graph of consists of the aforementioned line in the plane $z=0$, as well as every point "above" or "below" (i.e., with any $z$-coordinate) the line in space. In other words, the graph is a plane, as shown at right.

To convert the equation to rectangular coordinates, we note that $x=r \cos \theta= r \cos \frac{\pi}{3}=\frac{r}{2}$ and $y=r \sin \theta=\frac{r \sqrt{3}}{2}$. For all $r \neq 0$, we can divide these equations to get $\frac{x}{y}=\frac{1}{\sqrt{3}}$. Rearranging this equation gives $y=\sqrt{3} x$ as the equation in rectangular form. (Note that points of the form $(0,0, z)$ are on the graph and satisfy this equation.) □

181

---

<!-- Page 182 -->

CHAPTER 5. PARAMETERIZATION AND TRIGONOMETRIC COORDINATE SYSTEMS

Problem 5.19: Suppose $(\rho, \theta, \phi)$ are the spherical coordinates of point $P$, where $\rho \geq 0$, and that $(x, y, z)$ are the rectangular coordinates of point $P$.
(a) Find $\rho$ in terms of $x, y$, and $z$.
(b) Let $O$ be the origin and $A$ be the foot of the altitude from $P$ to the $z$-axis. Find $A O$ in terms of $\rho, \theta$, and/or $\phi$.
(c) Find $x, y$, and $z$ in terms of $\rho, \theta$, and $\phi$.

Solution for Problem 5.19:
(a) The value of $\rho$ is the distance from the origin to the point $(\rho, \theta, \phi)$ in spherical coordinates. The distance from $(x, y, z)$ to the origin is $\sqrt{x^{2}+y^{2}+z^{2}}$. Therefore, we must have $\rho=\sqrt{x^{2}+y^{2}+z^{2}}$.
(b) In the diagram at right, we have drawn $\overline{P A}$ perpendicular to the $z$-axis and $\overline{P B}$ perpendicular to the $x y$-plane, thereby creating rectangle $P B O A$. In right triangle $P O A$, we have $\cos \phi=\frac{A O}{P O}=\frac{A O}{\rho}$, so $A O=\rho \cos \phi$.
(c) Since the $z$-coordinate of $A$ matches that of $P$, we have $z=A O= \rho \cos \phi$. To find the $x$ - and $y$-coordinates of $P$, we focus on point $B$ in the $x y$-plane. Since $P B O A$ is a rectangle, we have $O B=P A$. From right triangle $P O A$, we have $\frac{P A}{P O}=\sin \phi$, so $P A=P O \sin \phi=\rho \sin \phi$. Therefore, we have $O B=P A=\rho \sin \phi$. The $x$ - and $y$-coordinates of $P$ match those of $B$. The cylindrical coordinates of $B$ are ( $O B, \theta, 0$ ), so the rectangular coordinates are $(O B \cos \theta, O B \sin \theta, 0)$. Therefore, the $x$ - and $y$-coordinates of $B$ and $P$ are $x=O B \cos \theta=\rho \sin \phi \cos \theta$ and $y=O B \sin \theta=\rho \sin \phi \sin \theta$.

In summary, we have:
Important: The point with spherical coordinates $(\rho, \theta, \phi)$ has rectangular coordinates
$\square$
$$\begin{array}{l}
x=\rho \sin \phi \cos \theta \\
y=\rho \sin \phi \sin \theta \\
z=\rho \cos \phi
\end{array}$$

Perhaps you've noticed that our proof only works if $0<\phi<\frac{\pi}{2}$. You'll complete the proof for other values of $\phi$ as an Exercise.

Problem 5.20:
(a) Convert the cylindrical coordinates $\left(4, \frac{\pi}{3}, 4\right)$ to rectangular and spherical coordinates.
(b) Convert the spherical coordinates $\left(7, \frac{7 \pi}{4}, \frac{\pi}{3}\right)$ to rectangular and cylindrical coordinates.

Solution for Problem 5.20:
(a) First, we convert to rectangular coordinates. We have $x=r \cos \theta=4 \cos \frac{\pi}{3}=2$ and $y=r \sin \theta=4 \sin \frac{\pi}{3}= 2 \sqrt{3}$. The $z$-coordinate is the same in rectangular and polar coordinates, so the rectangular coordinates of the point with cylindrical coordinates $\left(4, \frac{\pi}{3}, 4\right)$ are $(2,2 \sqrt{3}, 4)$.

Turning to spherical coordinates, the $\theta$-coordinate is the same in both cylindrical and spherical coordinates. We can use the rectangular coordinates to find
$$\rho=\sqrt{x^{2}+y^{2}+z^{2}}=\sqrt{4+12+16}=4 \sqrt{2} .$$

182

---

<!-- Page 183 -->

5.3. COORDINATES IN THREE DIMENSIONS

Finally, since $z=\rho \cos \phi$, we have $\cos \phi=\frac{z}{\rho}=\frac{1}{\sqrt{2}}=\frac{\sqrt{2}}{2}$. So, we can let $\phi=\frac{\pi}{4}$, and ( $4 \sqrt{2}, \frac{\pi}{3}, \frac{\pi}{4}$ ) are spherical coordinates of the point.
(b) As in part (a), we start by finding the rectangular coordinates:
$$\begin{array}{l}
x=\rho \sin \phi \cos \theta=7\left(\frac{\sqrt{3}}{2}\right)\left(\frac{\sqrt{2}}{2}\right)=\frac{7 \sqrt{6}}{4}, \\
y=\rho \sin \phi \sin \theta=7\left(\frac{\sqrt{3}}{2}\right)\left(-\frac{\sqrt{2}}{2}\right)=-\frac{7 \sqrt{6}}{4}, \\
z=\rho \cos \phi=7\left(\frac{1}{2}\right)=\frac{7}{2} .
\end{array}$$

To convert these to cylindrical coordinates, we note that we already have the $z$-coordinate from the rectangular coordinates and the $\theta$-coordinate from the spherical coordinates. Finally, we have
$$r=\sqrt{x^{2}+y^{2}}=\sqrt{\left(\frac{7 \sqrt{6}}{4}\right)^{2}+\left(\frac{7 \sqrt{6}}{4}\right)^{2}}=\frac{7 \sqrt{6}}{4} \cdot \sqrt{2}=\frac{7 \sqrt{3}}{2},$$
so $\left(\frac{7 \sqrt{3}}{2}, \frac{7 \pi}{4}, \frac{7}{2}\right)$ are cylindrical coordinates of the point.

Problem 5.21: Convert each of the following rectangular coordinates to cylindrical coordinates and to spherical coordinates.
(a) $(6,-6,-2 \sqrt{6})$
(b) $\quad(-4,0,4 \sqrt{3})$

Solution for Problem 5.21:
(a) In two dimensions, the point with rectangular coordinates $(6,-6)$ has polar coordinates $\left(6 \sqrt{2}, \frac{7 \pi}{4}\right)$, so the point in space with rectangular coordinates $(6,-6,-2 \sqrt{6})$ has cylindrical coordinates $\left(6 \sqrt{2}, \frac{7 \pi}{4},-2 \sqrt{6}\right)$.

Turning to spherical coordinates, we have $\rho=\sqrt{x^{2}+y^{2}+z^{2}}=\sqrt{36+36+24}=4 \sqrt{6}$. The $\theta$-coordinate is the same in spherical coordinates as in cylindrical coordinates. To find $\phi$, we use the fact that $z=\rho \cos \phi$, so we have $-2 \sqrt{6}=(4 \sqrt{6}) \cos \phi$. Therefore, we have $\cos \phi=-\frac{1}{2}$, so we take $\phi=\frac{2 \pi}{3}$. This gives us the spherical coordinates $\left(4 \sqrt{6}, \frac{7 \pi}{4}, \frac{2 \pi}{3}\right)$.
(b) In two dimensions, the point with rectangular coordinates $(-4,0)$ has polar coordinates $(4, \pi)$, so the the point in three dimensions with rectangular coordinates $(-4,0,4 \sqrt{3})$ has cylindrical coordinates $(4, \pi, 4 \sqrt{3})$.

In spherical coordinates, we have $\rho=\sqrt{x^{2}+y^{2}+z^{2}}=\sqrt{16+48}=8$, and the $\theta$-coordinate is the same in spherical coordinates as in cylindrical coordinates. From $z=\rho \cos \phi$, we have $4 \sqrt{3}=8 \cos \phi$, so $\cos \phi=\frac{\sqrt{3}}{2}$ and $\phi=\frac{\pi}{6}$. Therefore, $\left(8, \pi, \frac{\pi}{6}\right)$ are spherical coordinates of the point.

Problem 5.22:
(a) Describe the graph of the equation $z^{2}=x^{2}+y^{2}$.
(b) Find parametric equations for $x, y$, and $z$ for the equation $z^{2}=x^{2}+y^{2}$. (You will need two parameters.)

183

---

<!-- Page 184 -->

CHAPTER 5. PARAMETERIZATION AND TRIGONOMETRIC COORDINATE SYSTEMS

Solution for Problem 5.22:
(a) We can begin by experimenting with different values of $z$. When $z=0$, we have $x^{2}+y^{2}=0$, so when $z=0$, the graph is just a point. Letting $z=1$ or $z=-1$ gives $x^{2}+y^{2}=1$, which describes a circle with radius 1 . Similarly, for larger and larger values of $z$, the resulting equations have graphs that are circles with larger and larger radii.

We might therefore guess that the graph is a pair of cones that open forever in both directions. Expressing the surface in cylindrical coordinates makes it very obvious that this is the case. We have $z^{2}=x^{2}+y^{2}=r^{2}$, so $z= \pm r$. Therefore, the radius of each circular cross-section of the graph equals the distance from the cross-section to the origin. The graph is the pair of cones shown at right. Each cone has the $z$-axis as its axis.
(b) Consider the upper cone, for which $z>0$. In part (a), we saw that every cross-section of the surface with constant $z$-coordinate is a circle with radius $r$ centered at a point on the $z$-axis, where $r=z$. So, the $x$ - and $y$-coordinates can be parameterized as $x=r \cos \theta, y=r \sin \theta$. This holds for any positive value of $z$, so we can parameterize the upper cone with $x=r \cos \theta, y=r \sin \theta, z=r$.

This parameterization holds for the lower cone, too! If we have $x=r \cos \theta, y=r \sin \theta$, and $z=r$ then $x^{2}+y^{2}=r^{2}=z^{2}$ still, so $(x, y, z)=(r \cos \theta, r \sin \theta, r)$ is on the circle centered at $(0,0, r)$ in the plane $z=r$. As $\theta$ ranges from 0 to $2 \pi$, we trace out the whole circle, so the parameterization $x=r \cos \theta, y=r \sin \theta, z=r$ generates all the points on the lower cone for $r<0$. Finally, taking $r=0$ shows that the parameterization includes the origin, as well.

One significant difference in our answer to part (b) above and the parameterizations we performed in Section 5.1 is that our parameterization in part (b) above required 2 parameters, whereas each parameterization in Section 5.1 required only 1 parameter. The reason for this difference is that our parameterizations in Section 5.1 were used to describe 1-dimensional curves in a 2-dimensional plane, whereas the parameterization of the cone describes a 2 -dimensional surface in a 3 -dimensional space. Since we are describing a 2 -dimensional surface, we need two parameters.

Problem 5.23:
(a) Describe the graph of all points with spherical coordinates $(\rho, \theta, \phi)$ such that $\rho=5$. Express the equation in rectangular coordinates, and give a parameterization of the equation for $x, y$, and $z$.
(b) Describe the graph of the points in space such that $\phi=\frac{2 \pi}{3}$ in spherical coordinates. Express the equation in rectangular coordinates.

Solution for Problem 5.23:
(a) The graph of $\rho=5$ consists of all points that are exactly 5 units from the origin. Therefore, the graph is a sphere centered at the origin with radius 5 . To express the equation in rectangular coordinates, we write $\rho$ as $\sqrt{x^{2}+y^{2}+z^{2}}$. Since this quantity is always nonnegative, we can square the equation $\sqrt{x^{2}+y^{2}+z^{2}}=5$ to produce the more attractive equivalent equation $x^{2}+y^{2}+z^{2}=25$.

We can parameterize this equation using the conversion from spherical to rectangular coordinates. Since $\rho=5$, we have the parameterization $x=\rho \cos \theta \sin \phi=5 \cos \theta \sin \phi, y=\rho \sin \theta \sin \phi=5 \sin \theta \sin \phi$, $z=\rho \cos \phi=5 \cos \phi$.
(b) Let $O$ be the origin and $P$ be a point that has $\phi=\frac{2 \pi}{3}$ in spherical coordinates. The $\phi$-coordinate gives us the angle that $\overline{O P}$ makes with the positive portion of the $z$-axis. Therefore, any point on the ray $\overrightarrow{O P}$ has $\phi=\frac{2 \pi}{3}$ when expressed in spherical coordinates. Moreover, we can rotate any point on this ray about the $z$-axis

184

---

<!-- Page 185 -->

5.3. COORDINATES IN THREE DIMENSIONS

by any angle to produce another point with the same $\phi$-coordinate. In other words, we can form a portion of the graph by rotating the whole ray around the $z$-axis, thereby sweeping out a cone. Since we can allow $\rho$ to be negative, the graph consists of two cones, one below the $x y$-plane (for $\rho>0$ ), and one above the $x y$-plane (for $\rho<0$ ).

We can see for certain that the graph is a cone by considering a particular cross-section perpendicular to the $z$-axis. For such a cross-section, $z$ is fixed. Because $\phi$ is also fixed by the equation $\phi=\frac{2 \pi}{3}$, the relationship $z=\rho \cos \phi$ tells us that $\rho$ must also be constant for all points on the graph in this cross-section. Moreover, since $\phi$ is fixed for all points in the graph, the relationship $z=\rho \cos \phi$ tells us that $\rho$ is directly proportional to $z$. Finally, for any point in the cross-section, we have
$$x^{2}+y^{2}=(\rho \sin \phi \cos \theta)^{2}+(\rho \sin \phi \sin \theta)^{2}=\left(\rho^{2} \sin ^{2} \phi\right)\left(\cos ^{2} \theta+\sin ^{2} \theta\right)=\rho^{2} \sin ^{2} \phi$$

So, the cross-section is a circle with radius $\rho \sin \phi$, which is directly proportional to $\rho$, and therefore directly proportional to $z$. Since every cross-section is a circle with radius directly proportional to the magnitude of $z$, the graph of $\phi=\frac{2 \pi}{3}$ is a pair of cones with vertex at the origin and with the $z$-axis as their common axis.

We can express the equation in rectangular coordinates by starting from the equation $x^{2}+y^{2}=\rho^{2} \sin ^{2} \phi$ above. Since $\phi=\frac{2 \pi}{3}$, we have $x^{2}+y^{2}=\frac{3 \rho^{2}}{4}$. We also have $\rho^{2}=x^{2}+y^{2}+z^{2}$, so $x^{2}+y^{2}=\frac{3}{4}\left(x^{2}+y^{2}+z^{2}\right)$, which simplifies as $x^{2}+y^{2}=3 z^{2}$. (We also could have noted that $z=\rho \cos \phi$, so $\rho \sin \phi=z \frac{\sin \phi}{\cos \phi}=z \tan \phi$. For $\phi=\frac{2 \pi}{3}$, we then have $x^{2}+y^{2}=\rho^{2} \sin ^{2} \phi=z^{2} \tan ^{2} \phi=3 z^{2}$.)

Problem 5.24:
(a) What is the relationship between spherical coordinates and the latitude and longitude that we use to identify the location of points on the surface of the Earth? (A definition of latitude and longitude can be found on page 180.)
(b) Why do we use a system much like spherical coordinates for points on the Earth's surface rather than using rectangular coordinates?
(c) Petr has lived his whole life in Petropavlovsk-Kamchatsky on the frigid northeastern shores of Siberia. He is sick of the cold, and has spent the last 5 years building a sailboat he hopes to sail to Honolulu, Hawaii, where he will be much warmer. If he sails at 10 km per hour, how many days will it take him to sail from Petropavlovsk-Kamchatsky, which has coordinates $52.92^{\circ} \mathrm{N}, 158.49^{\circ} \mathrm{E}$, to Honolulu, which has coordinates $21.31^{\circ} \mathrm{N}, 157.83^{\circ} \mathrm{W}$ ? You may assume the Earth is a sphere with radius 6370 kilometers, and that Petr travels along a single great circle of the sphere throughout his trip.

Solution for Problem 5.24:
(a) Let the center of the Earth be the origin, and the Earth's axis be the $z$-axis, with the North Pole on the positive $z$-axis and the South Pole on the negative $z$-axis. Then, longitude is closely related to $\theta$ and latitude is related to $\phi$. If we take the prime meridian to be entirely within in the $x z$-plane, so that the prime meridian intersects the positive $x$-axis as shown, then we can view "east" as counterclockwise, so the longitude of a point in the Eastern hemisphere equals the angle $\theta$ in spherical coordinates. The points in the Western hemisphere correspond to those with values of $\theta$ for which $180^{\circ}<\theta<360^{\circ}$. We can take care of these by noting that subtracting $360^{\circ}$ from $\theta$ doesn't change the location of a point with this $\theta$-coordinate, and $-180^{\circ}<\theta-360^{\circ}<0^{\circ}$. Therefore, the $\theta$-coordinate of any point in the Western hemisphere equals the
negative of its longitude.

185

---

<!-- Page 186 -->

CHAPTER 5. PARAMETERIZATION AND TRIGONOMETRIC COORDINATE SYSTEMS

Turning to latitude, suppose $P_{1}$ is a point on the Earth's surface in the Southern hemisphere and $O$ is the origin. The angle between $\overline{O P_{1}}$ and the positive $z$-axis ( $\phi$ in spherical coordinates) is $90^{\circ}$ plus the latitude of $\underline{P_{1}}$. Meanwhile, suppose point $P_{2}$ is on the Earth's surface in the Northern hemisphere. The angle between $\overline{O P_{2}}$ and the positive $z$-axis is $90^{\circ}$ minus the latitude of $P_{2}$.
(b) If we center the Earth at the origin (and assume the Earth is a sphere), then in spherical coordinates, all the points on the Earth's surface have the same $\rho$ coordinate. So, in order to tell anyone the location of a point on the Earth's surface, we need only tell them two coordinates, $\theta$ and $\phi$. In rectangular coordinates, all three coordinates must be specified to determine a point on the Earth's surface.
(c) Let the center of the Earth be $O$, let Petropavlovsk-Kamchatsky be $P$, and let Honolulu be $H$. To find the amount of time Petr spends sailing, we must find the distance along the surface of Earth from $P$ to $H$. This distance is the arc of a great circle. We know the radius of this circle; it equals the radius of the Earth. We only have to find the angle swept out by this arc, which is $\angle P O H$, and then we can find the length of the arc. Unfortunately, it's not so obvious how to find that angle from the latitude and longitude of $P$ and of $H$.

However, we do know that $P O$ and $O H$ equal the radius of the Earth, which we'll let be $r$. If we can determine any other angle or the third side length of $\triangle P O H$, then we can find $\angle P O H$. We are essentially given the spherical coordinates of $P$ and of $H$; we can use these to find the distance from $P$ to $H$ using the three-dimensional distance formula.

We let ( $\rho_{P}, \theta_{P}, \phi_{P}$ ) and ( $\rho_{H}, \theta_{H}, \phi_{H}$ ) be the spherical coordinates of $P$ and $H$. The first coordinate is easy; it equals the radius of the Earth, so we have $\rho_{P}=\rho_{H}=r$. Turning to the $\theta$-coordinate, we apply the reasoning of part (a) to the longitudes of $P$ and $H$. Since $P$ is in the Eastern hemisphere, its $\theta$-coordinate equals its longitude, so $\theta_{P}=158.49^{\circ}$ for $P$. Point $H$ is in the Western hemisphere, so we can take its $\theta$ to be the negative of its longitude, which gives $\theta_{H}=-157.83^{\circ}$. Finally, both $P$ and $H$ are in the Northern hemisphere, so their $\phi$-coordinates are in $90^{\circ}$ minus their latitudes. This gives us $\phi_{P}=37.08^{\circ}$ and $\phi_{H}=68.69^{\circ}$. Now, we can find $P H$ by converting these spherical coordinates to rectangular coordinates and using the distance formula. We can do both of these in one step using the relationships $x=\rho \cos \theta \sin \phi, y=\rho \sin \theta \sin \phi$, and $z=\rho \cos \phi$. Since $\rho_{P}=\rho_{H}=r$, we have
$$P H=\sqrt{\left(r \cos \theta_{H} \sin \phi_{H}-r \cos \theta_{P} \sin \phi_{P}\right)^{2}+\left(r \sin \theta_{H} \sin \phi_{H}-r \sin \theta_{P} \sin \phi_{P}\right)^{2}+\left(r \cos \phi_{H}-r \cos \phi_{P}\right)^{2}} .$$

Substituting all our values from above, we find that $P H \approx 4970 \mathrm{~km}$. Since we have $P O, H O$, and $P H$, we can use the Law of Cosines to find $\cos \angle P O H$ :
$$\cos \angle P O H=\frac{P O^{2}+H O^{2}-P H^{2}}{2(P O)(O H)} \approx 0.696$$

Therefore, $\angle P O H \approx 45.9^{\circ}$, which means that Petr will sail $\frac{45.9^{\circ}}{360^{\circ}} \approx 0.128$ of a great circle during his trip. Since the circumference of the Earth is $2 \pi(6370) \approx 40000 \mathrm{~km}$, Petr will sail $0.128(40000) \approx 5120 \mathrm{~km}$. He sails at 10 kilometers per hour, so he'll sail for 512 hours, which is 21 days and 8 hours.

That's a long trip. You might wonder if there's a formula to find the distance between two points on the Earth given their latitudes and longitudes. There is, and you'll prove it on page 480.
5.3.1 Express each of the following rectangular coordinates in cylindrical and spherical coordinates.
(a) $(-2 \sqrt{2}, 2 \sqrt{2}, 4)$
(b) $(3,0,-3 \sqrt{3})$
5.3.2 Suppose the point with spherical coordinates $(\rho, \theta, \phi)$, where $\rho \geq 0$, has cylindrical coordinates $(r, \theta, z)$. Express $\rho$ in terms of $r, \theta$, and $z$.

186

---

<!-- Page 187 -->

5.4. SUMMARY
5.3.3 In Problem 5.19 we only proved the relationship between spherical coordinates and rectangular coordinates for $0<\phi<\frac{\pi}{2}$. Complete our proof by addressing points for which $\frac{\pi}{2} \leq \phi \leq \pi$ or $\phi=0$.
5.3.4 Show that if $\rho \geq 0$, then the distance from ( $\rho \sin \phi \cos \theta, \rho \sin \phi \sin \theta, \rho \cos \phi$ ) to the origin is $\rho$.
5.3.5 Let the cylindrical coordinates of $P$ be $(r, \theta, z)$. What are cylindrical coordinates of the following points:
(a) The reflection of $P$ through the $x y$-plane.
(b) The rotation of $P$ by $\pi$ around the $z$-axis.
(c) ★ The reflection of $P$ through the origin. (The reflection of a point $X$ through a point $Y$ is the point $Z$ such that $Y$ is the midpoint of $\overline{X Z}$.)
5.3.6 We showed that the graph of $\phi=\frac{2 \pi}{3}$ in spherical coordinates is a pair of cones. Are there any values of $c$ for which the graph of $\phi=c$ is not a pair of cones?
5.3.7 Suppose we used cylindrical coordinates to identify the location of points on the surface of the Earth, with the center of the Earth as the origin.
(a) Would it be possible to travel along the surface of the Earth and keep the $r$-coordinate constant? The $\theta$-coordinate? The $z$-coordinate?
(b) Is it possible to travel along the surface of the Earth and keep two of the cylindrical coordinates constant?
5.3.8
(a) Describe the graph of all points such that $\rho=4$ and $\theta=\frac{2 \pi}{5}$ in spherical coordinates.
(b) ★ Describe the graph of all points such that $\theta=\frac{\pi}{2}$ and $\rho=6 \sin \phi$ in spherical coordinates.
5.3.9 Consider the equation $(x+3)^{2}+(y+5)^{2}+(z-1)^{2}=4$.
(a) Find a parameterization for $x, y$, and $z$ for all points that satisfy the equation.
(b) $\star$ Find a parameterization for the portion of the graph of the equation that is on or above the $x y$-plane.
5.4 Summary

Rather than having a single equation that relates $x$ and $y$, we sometimes define a relationship between $x$ and $y$ through an intermediary variable called a parameter. We do so by expressing $x$ and $y$ as functions of a third variable, such as $t$. We call the system $x=f(t), y=g(t)$ a pair of parametric equations, where $t$ is the parameter. When we graph parametric equations $x=f(t), y=g(t)$, we graph all points ( $x, y$ ) such that there is a value of $t$ for which $x=f(t)$ and $y=g(t)$.

In addition to the more common rectangular coordinates $(x, y)$, polar coordinates offer another method for denoting the location of a point on a plane. As with rectangular coordinates, we start with a point we call the origin and we identify the location of each point with an ordered pair, $(r, \theta)$. The $r$-coordinate is the distance from the point to the origin; we call this coordinate the radius. The $\theta$-coordinate is the angle, which we define in the same way we related angles to points on the unit circle.

We can also use a negative radius, which means "go in the direction opposite the one indicated by $\theta$." For example, we could express $A$ as $\left(-3,210^{\circ}\right)$, which tells us
that $A$ is 3 units in the direction opposite $210^{\circ}$, which is the direction of $30^{\circ}$. Similarly, the polar coordinates $(r, \theta)$ and $\left(-r, \theta+180^{\circ}\right)$ always refer to the same point. We can also use a negative angle, so point $B$ at right could be expressed as $\left(2,-120^{\circ}\right)$.

187

---

<!-- Page 188 -->

CHAPTER 5. PARAMETERIZATION AND TRIGONOMETRIC COORDINATE SYSTEMS

If ( $x, y$ ) in rectangular coordinates is the same point as ( $r, \theta$ ) in polar coordinates, then
$$x=r \cos \theta, \quad y=r \sin \theta, \quad r^{2}=x^{2}+y^{2}, \quad \tan \theta=\frac{y}{x},$$
where $\tan \theta=\frac{y}{x}$ holds only if $x \neq 0$. If $x=0$ and $y \neq 0$, then $\cos \theta=0$ and $r^{2}=y^{2}$. If $x=y=0$, then $r=0$ and $\theta$ can be anything.

Just as we use the horizontal and vertical coordinates $(x, y)$ to identify the location of a point in the twodimensional Cartesian plane, we can identify the location of a point in three-dimensional space with three coordinates $(x, y, z)$. We call the plane in which $z=0$ the $x y$-plane. Points on this plane are identified by the coordinates $(x, y, 0)$, where the $x$ and $y$ have the horizontal and vertical meanings they have in the Cartesian plane. For other points $(x, y, z)$ in space, the $z$-coordinate indicates how far above $(z>0)$ or below $(z<0)$ the $x y$-plane the point is. The $x$ - and $y$-coordinates of the point are the same as those of the point in the $z=0$ plane that is directly above or below the point $(x, y, z)$.

Important: The distance between the points $\left(x_{1}, y_{1}, z_{1}\right)$ and $\left(x_{2}, y_{2}, z_{2}\right)$ is
$$\sqrt{\left(x_{2}-x_{1}\right)^{2}+\left(y_{2}-y_{1}\right)^{2}+\left(z_{2}-z_{1}\right)^{2}}$$

There are two commonly used coordinate systems in three dimensions that use angles among their coordinates. In cylindrical coordinates, the $x$ - and $y$-coordinates are replaced with $r$ - and $\theta$-coordinates such that the point in the Cartesian plane with rectangular coordinates $(x, y)$ has polar coordinates $(r, \theta)$. The third cylindrical coordinate is the same as the $z$-coordinate from rectangular coordinates. A depiction of the point ( $r, \theta, z$ ) in cylindrical coordinates is shown at left below. When expressing a point in polar coordinates, the radius always comes first, the angle second, and the $z$-coordinate last.

If the cylindrical coordinates ( $r, \theta, z$ ) represent the same point as the rectangular coordinates ( $x, y, z$ ), then $x=r \cos \theta$ and $y=r \sin \theta$. As with polar coordinates, we usually choose $r$ to be nonzero and $\theta$ such that $0 \leq \theta<2 \pi$. However, $r$ can be negative and $\theta$ can be outside the interval $[0,2 \pi)$, again just as with polar coordinates.

Figure 5.3: Cylindrical Coordinates

Figure 5.4: Spherical Coordinates

The spherical coordinates of a point are typically denoted as $(\rho, \theta, \phi)$, The $\rho$-coordinate is the distance from the $P$ to the origin. The $\theta$-coordinate is essentially the same as the angle in cylindrical coordinates. The $\phi$-coordinate is the angle between $\overline{O P}$ and the positive $z$-axis, as shown. We typically choose the spherical coordinates such that $\rho \geq 0,0 \leq \theta \leq 2 \pi$, and $0 \leq \phi \leq \pi$. The point with spherical coordinates ( $\rho, \theta, \phi$ ) has rectangular coordinates
$$x=\rho \sin \phi \cos \theta, \quad y=\rho \sin \phi \sin \theta, \quad z=\rho \cos \phi,$$
and we have $\rho^{2}=x^{2}+y^{2}+z^{2}$.

188

---

<!-- Page 189 -->

REVIEW PROBLEMS

Things To Watch Out For! 

WARNING!!
- If parametric equations $x=f(t), y=g(t)$ satisfy an equation in terms of $x$ and $y$, we only know that the graph of the parametric equations is part of the graph of the non-parametric equation. To show that the graph of the parametric equations is the same as the graph of the nonparametric equation, we must show that every point in the graph of the non-parametric equation is in the graph of the parametric equations. We can usually do so by showing that for each point ( $x_{1}, y_{1}$ ) on the graph of the non-parametric equation, there is a value of $t$ such that $x_{1}=f(t), y_{1}=g(t)$.
- The graph of parametric equations is not necessarily the same as that of a non-parametric equation satisfied by the parametric equations. Sometimes the parametric equations have restrictions that limit the graph of the parametric equations to only a portion of the graph of the non-parametric equation.
- When reading about spherical coordinates in another source, make sure you know what each variable stands for and what the restrictions on each are. While most sources will define the two angles in spherical coordinates in essentially the same way we have here, some will use different variables than we have. Even more confusing, some will use the same variables, but reverse their meanings. Furthermore, some will restrict $\rho$ to be nonnegative, and some will use $r$ rather than $\rho$.

Review Problems
5.25 Find the graph of the parametric equations $x=3 a-1, y=2 a^{2}-a$.
5.26 Find parametric equations for $x$ and $y$ such that $x^{2}+4 x+y^{2}-2 y=11$.
5.27 Find the graph of the parametric equations $x=(\sin t)(\cos t), y=2 \cos ^{2} 2 t$.
5.28 Describe the curve that results from graphing the parametric equations $x=\frac{1}{1-t^{2}}, y=\frac{t}{1-t^{2}}$.
5.29 Convert each of the following rectangular coordinates to polar coordinates. You may use a calculator on this problem. Approximate angles to the nearest hundredth of a radian.
(a) $(-7,-7)$
(b) $\quad(6 \sqrt{3},-6 \sqrt{2})$
(c) $(-5,8)$
5.30 Convert each of the following polar coordinates to rectangular coordinates.
(a) $\left(5,0^{\circ}\right)$
(b) $\left(-4,210^{\circ}\right)$
(c) $\quad\left(8,-\frac{\pi}{4}\right)$
5.31 Describe the graph of the equation $r^{2}=3 r \cos \theta-5 r \sin \theta-2$.
5.32
(a) What point results from rotating $(4,5)$ by $60^{\circ}$ clockwise about the origin?
(b) What point results from rotating $(4,5)$ by $60^{\circ}$ clockwise about $(2,5)$ ?
(c) ★ What point results from rotating $(4,5)$ by $60^{\circ}$ clockwise about $(-2,7)$ ?

189

---

<!-- Page 190 -->

CHAPTER 5. PARAMETERIZATION AND TRIGONOMETRIC COORDINATE SYSTEMS
5.33 Let point $M$ be the midpoint of the segment with endpoints $\left(r_{1}, \theta_{1}\right)$ and $\left(r_{2}, \theta_{2}\right)$ in polar coordinates.
(a) Must it always be possible to express $M$ in polar coordinates as $\left(\frac{r_{1}+r_{2}}{2}, \theta\right)$ for some angle $\theta$ ?
(b) Must it always be possible to express $M$ in polar coordinates as $\left(r, \frac{\theta_{1}+\theta_{2}}{2}\right)$ for some radius $r$ ?
5.34 What symmetry must the graph of $f(r, \theta)=0$ have if:
(a) $f(r, \theta)=f(-r, \theta)$ for all $r$ and $\theta$.
(b) $f(r, \theta)=f(r,-\theta)$ for all $r$ and $\theta$.
5.35 Express each of the following rectangular coordinates in cylindrical and spherical coordinates.
(a) $(2,-2,2 \sqrt{2})$
(b) $(\sqrt{3}, 3,-2 \sqrt{3})$
5.36
(a) Convert the cylindrical coordinates $\left(6, \frac{2 \pi}{3},-1\right)$ to rectangular coordinates.
(b) Convert the spherical coordinates $\left(12, \frac{\pi}{4}, \frac{3 \pi}{4}\right)$ to rectangular coordinates.
5.37 Describe the graph of all points in space such that $y^{2}+z^{2}=9$.
5.38 What is the graph of $r+z=6$ in cylindrical coordinates?
5.39 Describe the graphs of each of the following equations:
(a) $r=5$ in cylindrical coordinates.
(c) $\theta=-\frac{\pi}{3}$ in cylindrical coordinates.
(b) $\quad \rho=3$ in spherical coordinates.
(d) $\phi=\frac{3 \pi}{4}$ in spherical coordinates.
5.40 Describe the surface that is the graph of all points with cylindrical coordinates $(r, \theta, z)$ such that $r^{2}+z^{2}=2 z$.
5.41 Describe the surface that consists of all points with spherical coordinates $(\rho, \theta, \phi)$ such that $\rho=6 \cos \phi$.
5.42 Describe the graph of $\rho=\frac{3}{\sin \phi}$ in spherical coordinates.
5.43
(a) What geometric transformation maps any point with spherical coordinates $(\rho, \theta, \phi)$ to a point with spherical coordinates $(\rho, \theta+\pi, \phi)$ ?
(b) What geometric transformation maps any point with spherical coordinates $(\rho, \theta, \phi)$ to a point with spherical coordinates $(\rho, \theta, \pi-\phi)$ ?

Challenge Problems
5.44
(a) Graph $r=\sin (2 \theta)$.
(b) Graph $r=\sin (3 \theta)$.
(c) Graph $r=\sin (4 \theta)$.
(d) Graph $r=\sin (5 \theta)$.
(e) ★ Generalize your results from the first four parts: describe the graph of $r=\sin (k \theta)$ for any integer $k$.

190

---

<!-- Page 191 -->

CHALLENGE PROBLEMS
5.45
(a) Find parametric equations for $x$ and $y$ whose graph is a circle with center $(h, k)$ and radius $r$.
(b) Find parametric equations for $x, y$, and $z$ whose graph is a sphere with center $(a, b, c)$ and radius $\rho$. (You will need two parameters.)
(c) Find parametric equations for $x, y$, and $z$ whose graph is a cylinder with radius $r$ and with the $x$-axis as its axis. (You will need two parameters.)
5.46 Find parametric equations whose graph is the portion of the curve $x^{2}-4 x+y^{2}-2 y+1=0$ that is above the $x$-axis. Hints: 177, 107
5.47 Let $(x, y)$ be a point that does not lie on the negative $x$-axis, and let $(r, \theta)$ be the point's polar coordinates, where $r>0$ and $-\pi<\theta<\pi$. Show that $\theta=2 \arctan \frac{y}{x+\sqrt{x^{2}+y^{2}}}$. Hints: 66
5.48 Find the smallest distance between the point $(1,2,3)$ and a point on the graph of the parametric equations $x=2-t, y=4+t, z=3+2 t$.
5.49 The witch of Agnesi, named after mathematician Maria Gaetana Agnesi, is a curve that is defined as follows. Let $O$ be the origin, let $T$ be the point $(0,1)$, and let $\ell$ be the line through $T$ parallel to the $x$-axis. Let $C$ be the circle centered at $\left(0, \frac{1}{2}\right)$ with radius $\frac{1}{2}$. For any point $P$ on the circle besides $O$ and $T$, we draw a ray from $O$ through $P$. Let this ray intersect $\ell$ at point $X$. We then draw the altitude from $X$ to the line through $P$ parallel to the $x$-axis. The foot of this altitude, point $A$, is on the witch curve. When we trace out the resulting points $A$ for all possible $P$, and include point $T$, we get the witch curve, which is dotted in the diagram.
(a) Find a parameterization for the witch curve. Hints: 23
(b) Find a function $f$ such that the witch curve is the graph of the function $y=f(x)$.
$5.50 \star$ A sphere with radius 2 centered at the origin is painted red. A hole with radius 1 is drilled through the sphere along the $x$-axis. Find a parameterization for the red surface that remains. Hints: $244,10,235$
$5.51 \star$ Coin $\mathcal{A}$ with radius 1 is placed on the Cartesian plane so that its center is at the origin. Coin $\mathcal{B}$ with radius 1 is placed on the Cartesian plane so that its center is at $(0,2)$, which means that the two coins are tangent at $(0,1)$. Suppose the point on $\mathcal{B}$ that is initially touching coin $\mathcal{A}$ is painted red. We then roll coin $\mathcal{B}$ counterclockwise around $\operatorname{coin} \mathcal{A}$ such that the two always remain touching, and $\operatorname{coin} \mathcal{A}$ never moves.
(a) Find parametric equations for the path of the red point. Hints: 148, 117, 8
(b) During a full revolution of $\operatorname{coin} \mathcal{B}$ around coin $\mathcal{A}$, how many revolutions does the red point make around the center of coin $\mathcal{B}$ ? (The point completes a full revolution about the center of $\operatorname{coin} \mathcal{B}$ whenever it is again directly below the center of $\mathcal{B}$.)
(c) Suppose the radius of coin $\mathcal{A}$ is $n$, where $n$ is a positive integer, and that $\operatorname{coin} \mathcal{B}$ has radius 1 and is initially centered at $(0, n+1)$. Answer the questions of part (a) and part (b) if we again roll coin $\mathcal{B}$ about the circumference of $\operatorname{coin} \mathcal{A}$.

191

---

