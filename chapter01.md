# Chapter 1: Functions Review

<!-- Page 1 -->

The chief function of the body is to carry the brain around. - Thomas Edison
CHAPTER

Functions Review
1.1 Function Basics

Suppose we have a machine that accepts any number, multiplies it by two, adds three to this product, and then outputs the result. Mathematically speaking, this machine is a function because there is only one possible output from the machine for each input to the machine. We can give this function a label, $f$, and write the function as
$$f(x)=2 x+3 .$$

This simple equation describes the machine. The " $(x)$ " after $f$ on the left side indicates that we are putting $x$ into the function $f$. When speaking, $f(x)$ is read " $f$ of $x$." The $x$ in the equation $f(x)=2 x+3$ is a dummy variable, which means that it is essentially a placeholder. When we put a specific number in our machine, we replace $x$ with that number in the equation $f(x)=2 x+3$ to determine what the machine outputs. For example,
$$f(5)=2 \cdot 5+3=13,$$
so the machine outputs 13 when we put 5 into it.
Functions are really that simple. We define the function, and then whenever we input a number to the function, we follow the definition to get an output. Usually, we use an equation, such as $f(x)=2 x+3$, to define a function. For the obvious reason, $f$ is the most commonly used label for $f$ unctions.

In this chapter, we will discuss only functions that take real number inputs and give real number outputs. The domain of a function consists of all the values we are able to input to the function and get an output, and the range of the function consists of all the values that can come out of the function.

Extra! It isn't that they can't see the solution. It is that they can't see the problem.

-G. K. Chesterton
1

---

<!-- Page 2 -->

CHAPTER 1. FUNCTIONS REVIEW

For example, consider the function
$$f(x)=\frac{1}{x-3}$$

The value $x=3$ is not part of the domain of this function, because $\frac{1}{x-3}$ is not defined when $x=3$. We can safely put any other value of $x$ into this function, so the domain of $f$ is "all real numbers except 3 ." Similarly, there is no value of $x$ for which it is possible to make the function output 0 . However, we can make the function output any other real number, so the range of $f$ is "all real numbers except 0 ."

We call a function that can only output real numbers a real-valued function, or, even more simply, a real function. Unless a problem states otherwise, you can assume that all functions in this chapter are real functions. Moreover, you can assume that they are only defined for real number inputs. Later in this book we will explore a variety of functions that can take nonreal inputs and give nonreal outputs.

We will sometimes use interval notation to express the domain and range of a function. For example, we can denote "all real numbers greater than 3 and less than 5 " by the interval $(3,5)$. We use "(" and ")" to indicate that the values 3 and 5 are not included. Notice that we don't write $(5,3)$; the lesser end of the interval always comes first. We write $x \in(3,5)$ to indicate that $x$ is a number in this interval, The " $x \epsilon^{\prime \prime}$ means " $x$ is in," and $(3,5)$ indicates the real numbers greater than 3 and less than 5, as we just described.

To include a boundary value in the interval, we use "[" for the lower bound and "]" for the upper bound. For example, the statement $x \in(-3,5]$ means $-3<x \leq 5$ and $y \in[-12.2,0]$ means $-12.2 \leq y \leq 0$.

Finally, to indicate an interval that has no upper bound or no lower bound (or neither), we use the $\infty$ symbol. For example, we write $t>-3$ as $t \in(-3,+\infty)$. The " $(-3$ " part indicates that no numbers equal to -3 or lower than -3 are in the interval. The " $+\infty$ )" part indicates that the interval continues forever in the positive direction; that is, there is no upper bound. So, the interval ( $-3,+\infty$ ) is all real numbers greater than -3 . Similarly, the statement $w \in(-\infty,-2]$ is the same as $w \leq-2$. Notice that we always use "(" with $-\infty$ and ")" with $+\infty$, instead of "[" and "]". In both cases, there is not a boundary value to include in the interval, so we must use "(" or ")" instead of "[" or "]".

To write all real numbers in interval notation, we can write $(-\infty,+\infty)$. We often use the symbol $\mathbb{R}$ to denote "all real numbers." Therefore, we typically write the interval $(-\infty, \infty)$ as " $\mathbb{R}$ ", so $x \in \mathbb{R}$ means " $x$ is a real number."

Problems
Problem 1.1: Let $f(x)=2 x^{2}-3$.
(a) Find $f(2)$.
(b) Find all values of $t$ such that $f(t)=47$.
(c) Find $f(3 x+1)$.

Problem 1.2: A function can be defined to accept multiple inputs. For example, let
$$g(a, b, c)=3 a-2 b+7 c^{2}$$
(a) Evaluate $g(3,-5,-1)$.
(b) Find $b$ if $g(b, 2,-1)=21$.

Problem 1.3: Suppose $t(x)=a x^{4}+b x^{2}+x+5$, where $a$ and $b$ are constants. In this problem, we find $t(4)$ if $t(-4)=3$.
(a) Use $t(-4)=3$ to write an equation in terms of $a$ and $b$.
(b) Express t(4) in terms of $a$ and $b$.
(c) Find $t(4)$.

2

---

<!-- Page 3 -->

1.1. FUNCTION BASICS

Problem 1.4: Find the domain and range of each of the following functions:
(a) $f(x)=2 x-3$
(c) $g(t)=\frac{2 t}{t-1}$
(b) $f(x)=\sqrt{-2 x+7}$
(d) $h(x)=9 x^{2}+4$

Problem 1.5: Suppose $p(x)=2 \sqrt{x}+3$, but that $p(x)$ is only defined for $4 \leq x \leq 9$. In other words, the domain of $p$ is all real numbers from 4 to 9 .
(a) Is there a value of $x$ for which $p(x)=5$ ?
(b) What is the range of $p$ ?

Problem 1.6: Find the domain of each of the following functions:
(a) $f(x)=\frac{\sqrt{2 x-5}}{x-3}$
(b) $g(t)=\frac{2 t-4}{\frac{1}{t}-\frac{1}{3 t-4}}$

Problem 1.7: Notice that $\frac{x^{2}-x}{x-1}=\frac{(x-1)(x)}{x-1}=x$. Are $f(x)=\frac{x^{2}-x}{x-1}$ and $g(x)=x$ the same function?

Problem 1.1: Let $f(x)=2 x^{2}-3$.
(a) Find $f(2)$.
(b) Find all values of $t$ such that $f(t)=47$.
(c) Find $f(3 x+1)$.

Solution for Problem 1.1:
(a) We simply replace $x$ with 2 in the function definition, which gives us $f(2)=2(2)^{2}-3=8-3=5$.
(b) If $f(t)=47$, we must have $2 t^{2}-3=47$. Adding 3 to both sides gives $2 t^{2}=50$, and dividing by 2 gives $t^{2}=25$. The two values of $t$ that satisfy this equation are $t=5$ and $t=-5$. Checking our answer, we find $f(5)=2(5)^{2}-3=47$ and $f(-5)=2(-5)^{2}-3=47$.

Concept: We can often check our answers in algebra problems by plugging the solutions we find back into the original question.
(c) We can input an entire expression into a function by replacing the dummy variable in the function definition with the expression. Moreover, we can replace the $x$ in the function definition $f(x)=2 x^{2}-3$ with an expression that contains $x$. For example, we have
$$f(3 x+1)=2(3 x+1)^{2}-3=2\left(9 x^{2}+6 x+1\right)-3=18 x^{2}+12 x-1$$

Problem 1.2: A function can be defined to accept multiple inputs. For example, let
$$g(a, b, c)=3 a-2 b+7 c^{2}$$
(a) Evaluate $g(3,-5,-1)$.
(b) Find $b$ if $g(b, 2,-1)=21$.

3

---

<!-- Page 4 -->

CHAPTER 1. FUNCTIONS REVIEW

Solution for Problem 1.2:
(a) We replace the dummy variables $a, b$, and $c$ in the function definition with the values $3,-5$, and -1 , in that order. This gives us $g(3,-5,-1)=3(3)-2(-5)+7(-1)^{2}=26$.
(b) What's wrong with this solution:

Bogus Solution: We have
$$g(b, 2,-1)=3(2)-2 b+7(-1)^{2}=-2 b+13$$
so we seek the value of $b$ such that $-2 b+13=21$, which is $b=-4$.
We see our mistake immediately if we check our answer. We have
$$g(-4,2,-1)=3(-4)-2(2)+7(-1)^{2}=-9,$$
but we want $g(b, 2,-1)=21$. Looking at our Bogus Solution above, we see that in finding an expression for $g(b, 2,-1)$, we set $a=2$ and $c=-1$, and left $b$ as $b$. But this isn't what we must do to evaluate $g(b, 2,-1)$.

WARNING!! "

When evaluating a function that accepts multiple inputs, make sure you assign the values to the dummy variables in the correct order.

To evaluate $g(b, 2,-1)$, we replace $a$ in the function definition with $b$, we replace $b$ with 2 , and replace $c$ with -1 . This gives us
$$g(b, 2,-1)=3 b-2(2)+7(-1)^{2}=3 b+3 .$$

So, we seek the value of $b$ such that $3 b+3=21$, which gives us $b=6$. Checking our answer, we find that $g(6,2,-1)=21$, as desired.

Problem 1.3: Suppose $t(x)=a x^{4}+b x^{2}+x+5$, where $a$ and $b$ are constants. Find $t(4)$ if $t(-4)=3$.

Solution for Problem 1.3: We have
$$t(4)=a(4)^{4}+b(4)^{2}+4+5=256 a+16 b+4+5=256 a+16 b+9 .$$

If we can find $a$ and $b$, then we can evaluate $t(4)$. We turn to the only other piece of information we have, which is $t(-4)=3$. We have
$$t(-4)=a(-4)^{4}+b(-4)^{2}+(-4)+5=256 a+16 b-4+5=256 a+16 b+1,$$
so $t(-4)=3$ gives us $256 a+16 b+1=3$, which means $256 a+16 b=2$. Unfortunately, this doesn't tell us $a$ or $b$. However, looking back at our expression for $t(4)$, we see that we don't need $a$ and $b$. We need $256 a+16 b$, which we know equals 2 . So, we have $t(4)=256 a+16 b+9=2+9=11$.

Concept: Keep your eye on the ball. Sometimes we don't need to evaluate every variable in a problem in order to solve the problem.

Now that we have a little practice evaluating functions, let's try finding the domain and range of specific functions.

Problem 1.4: Find the domain and range of each of the following functions:
(a) $f(x)=2 x-3$
(c) $\quad g(t)=\frac{2 t}{t-1}$
(b) $f(x)=\sqrt{-2 x+7}$
(d) $\quad h(x)=9 x^{2}+4$

4

---

<!-- Page 5 -->

1.1. FUNCTION BASICS

Solution for Problem 1.4:
(a) We can input any real number to $f$, so the domain of $f$ is all real numbers. It appears that any real number can be output from $f$. To show that the range of $f$ is all real numbers, we show that for any real number $y$, we can find an $x$ such that $f(x)=y$. Since $f(x)=2 x-3$, we seek the value of $x$ such that $2 x-3=y$. Solving for $x$ gives $x=(y+3) / 2$. So, for any real number $y$, if we let $x=(y+3) / 2$, then we have $f(x)=y$. This tells us that every real number is in the range of $f$. Therefore, both the domain and range are all real numbers. Since we can use the symbol $\mathbb{R}$ to indicate the real numbers, we can write, "The domain and range of $f$ are both $\mathbb{R}$."
(b) The square root of a negative number is not a real number, so we must have $-2 x+7 \geq 0$. This gives us $x \leq 7 / 2$, so the domain is all real numbers less than or equal to $7 / 2$. In interval notation, the domain is ( $-\infty, 7 / 2$ ].

Intuitively, we might guess that because $-2 x+7$ can equal any nonnegative number, the range of $f$ is all nonnegative real numbers. We can explicitly show that this is the range of $f$ as we did in part (a). We let
$$y=f(x)=\sqrt{-2 x+7}$$

We then solve this equation for $x$ in terms of $y$. Squaring both sides of $y=\sqrt{-2 x+7}$ gives $y^{2}=-2 x+7$. We solve for $x$ by subtracting 7 from both sides, then dividing by -2 , to find
$$x=\frac{7-y^{2}}{2}$$

So, for any nonnegative value of $y$, if we let $x=\left(7-y^{2}\right) / 2$, then we have
$$f(x)=f\left(\frac{7-y^{2}}{2}\right)=\sqrt{-2\left(\frac{7-y^{2}}{2}\right)+7}=\sqrt{-7+y^{2}+7}=\sqrt{y^{2}}=y$$

This final step, $\sqrt{y^{2}}=y$, is only valid because $y$ is nonnegative. We therefore see that all nonnegative real numbers are in the range of $f$, because for every nonnegative value of $y$, we can find an $x$ such that $f(x)=y$. Since $\sqrt{-2 x+7}$ cannot be negative, no negative numbers are in the range of $f$. So, the range of $f$ is all nonnegative real numbers, which we can write as $[0,+\infty)$.
(c) We cannot have $t=1$ in $g(t)=2 t /(t-1)$, since this would make the denominator equal to 0 . There are no other restrictions on the input to $g$, so the domain is all real numbers except 1 .

Finding the range of $g$ is a little trickier. We let $y=g(t)$, so we have
$$y=\frac{2 t}{t-1}$$

Then we solve for $t$ in terms of $y$. Multiplying both sides by $t-1$ gives $y t-y=2 t$. Solving this equation for $t$ in terms of $y$ gives
$$t=\frac{y}{y-2}$$
(Note that $t$ cannot be 1 in this equation, since $t=1$ gives us $1=\frac{y}{y-2}$, from which we have $y-2=y$, which has no solution for $y$.) For any desired output $y$ except $y=2$, we can use $t=\frac{y}{y-2}$ to find the input, $t$, to $g(t)$ that will produce the desired output. Therefore, the range is all real numbers except 2 . We can denote "all real numbers except $2^{\prime \prime}$ with interval notation as $(-\infty, 2) \cup(2,+\infty)$.

The " $\cup$ " in $(-\infty, 2) \cup(2,+\infty)$ means "or," so, " $y \in(-\infty, 2) \cup(2,+\infty)$ " means $y$ is in the interval $(-\infty, 2)$ or the interval $(2,+\infty)$.

5

---

<!-- Page 6 -->

CHAPTER 1. FUNCTIONS REVIEW

Sidenote: The union of two intervals consists of all numbers that are in either one or both of the intervals. As we just saw, we use the symbol $\cup$ to denote a union of two intervals, so $(-\infty, 2) \cup(2,+\infty)$ means "all numbers in the interval $(-\infty, 2)$ or the interval $(2,+\infty)$."

The intersection of two intervals consists of all numbers that are in both of the intervals. We use the symbol $\cap$ to refer to the intersection of two intervals. For example, the expression $[3,7] \cap[5,11]$ refers to the numbers that are in both the interval [3,7] and the interval [5,11]. These numbers form the interval [5,7], so we can write
$$[3,7] \cap[5,11]=[5,7] .$$

On the other hand, the numbers that are either in [3,7] or in [5,11] (or in both) form the interval $[3,11]$. Therefore, we have
$$[3,7] \cup[5,11]=[3,11] .$$

We also have a special notation for "all real numbers except a few specific values." We can write "all real numbers except $2^{\prime \prime}$ as $\mathbb{R} \backslash\lbrace 2 \rbrace $. If we wish to exclude several specific values, we just list them inside the curly braces. So, we write "all real numbers except 5, 6 , and $7^{\prime \prime}$ as $\mathbb{R} \backslash\lbrace 5,6,7 \rbrace $.
(d) We can input any real number to the function $h(x)=9 x^{2}+4$, so the domain of $h$ is $\mathbb{R}$. Because the square of a real number is always nonnegative, the expression $9 x^{2}$ is always nonnegative. Therefore, the expression $9 x^{2}+4$ must be greater than or equal to 4 . Since $9 x^{2}+4$ can equal any number that is greater than or equal to 4 , the range of $h$ is $[4,+\infty)$.

Note that in parts (b) and (c), we find the domain by considering operations that we are not able to perform. Specifically, we cannot take the square root of a negative number in a real function, and we cannot divide by zero. This is typically how we find the domain when it is not obvious that the domain is all real numbers, as it is in parts (a) and (d). Finding the range is often a matter of considering the possible outputs of special expressions like square roots, perfect squares, or absolute values. But, as shown in part (c), the restrictions on the range can also be more subtle. There, we found a strategy that is often useful for determining the range of complicated functions:

Concept: We can often find the range of a function by setting the function definition equal
to a new variable, and then solving for the dummy variable in terms of the new variable.

For some functions, we need the advanced tools of calculus to determine the range. For still others, the best we can do is estimate the range numerically, usually using a computer. When we ask for the range of a function in this text, we'll only consider functions whose ranges we can find without these techniques.

Sometimes functions are defined with explicit constraints on the domain of the function. The range of such a function consists only of those outputs that can be obtained from the permitted inputs. Here's an example:

Problem 1.5: Suppose $p(x)=2 \sqrt{x}+3$, but that $p(x)$ is only defined for $4 \leq x \leq 9$. (In other words, the domain of $p$ is all real numbers from 4 to 9 .) Find the range of $p$.

Solution for Problem 1.5: What's wrong with this solution:
```
Bogus Solution: The output of \sqrt{}{x}\mathrm{ can be any nonnegative real number, so the result of}
        IT
```

6

---

<!-- Page 7 -->

1.1. FUNCTION BASICS

Our Bogus Solution completely ignores the restriction on the domain of $p$.

Since $p$ is only defined for inputs $x$ such that $4 \leq x \leq 9$, the range consists of all values of $p$ that can result from inputting a value of $x$ such that $4 \leq x \leq 9$. Because $4 \leq x \leq 9$, we have $2 \leq \sqrt{x} \leq 3$. Multiplying all parts of this inequality chain by 2 gives $4 \leq 2 \sqrt{x} \leq 6$ and adding 3 to all parts of this chain gives $7 \leq 2 \sqrt{x}+3 \leq 9$. Therefore, for all $x$ such that $4 \leq x \leq 9$, we have $7 \leq p(x) \leq 9$.

We're not finished yet! We've only shown that all values in the range of $p$ are between 7 and 9 , inclusive (which means 7 and 9 are included). We haven't shown that all real numbers from 7 to 9 are in the range. This is somewhat "obvious," since $p(x)$ goes "smoothly" from 7 to 9 as $x$ goes from 4 to 9 . However, to explicitly prove that all possible values from 7 to 9 are in the range, we let $y=p(x)=2 \sqrt{x}+3$ and solve for $x$ in terms of $y$. This gives us
$$x=\left(\frac{y-3}{2}\right)^{2} .$$

For any value of $y$ from 7 to 9 , we can use this equation to find the value of $x$ for which $p(x)$ equals this $y$. (Make sure you see why all the resulting values of $x$ are in the domain of $p$.)

Finding the domain and range of more complicated functions can be pretty tricky. We'll try finding the domain of a couple of such functions.

Problem 1.6: Find the domain of each of the following functions:
(a) $f(x)=\frac{\sqrt{2 x-5}}{x-3}$
(b) $g(t)=\frac{2 t-4}{\frac{1}{t}-\frac{1}{3 t-4}}$

Solution for Problem 1.6:
(a) The input to a square root must be nonnegative, so we must have $2 x-5 \geq 0$. This gives us $x \geq 5 / 2$. However, we cannot have $x=3$, since this will make the denominator equal to 0 .
WARNING!! Sometimes there is more than one constraint on the domain of a function. à
Combining these two constraints tells us that the domain is all real numbers greater than or equal to $5 / 2$ except 3 . We can write this in interval notation as $[5 / 2,3) \cup(3,+\infty)$.
(b) First, we notice that we cannot have $t=0$ or $3 t-4=0$, because we cannot divide by 0 . This tells us that we must exclude $t=0$ and $t=4 / 3$ from the domain. However, we're not finished, because we cannot have the entire denominator of $g(t)$ equal to 0 . Therefore, we must exclude from our domain those values of $t$ for which
$$\frac{1}{t}-\frac{1}{3 t-4}=0 .$$

Multiplying both sides by $t(3 t-4)$ to get rid of the fractions gives us $3 t-4-t=0$, from which we find $t=2$. So, the domain of $g$ is all real numbers except $0,4 / 3$, and 2 . We could write this as intervals with the unwieldy $(-\infty, 0) \cup\left(0, \frac{4}{3}\right) \cup\left(\frac{4}{3}, 2\right) \cup(2,+\infty)$. We can also write it as $\mathbb{R} \backslash\left\lbrace 0, \frac{4}{3}, 2\right\rbrace$, which reads "all real numbers except $0, \frac{4}{3}$, and 2 ."

7

---

<!-- Page 8 -->

CHAPTER 1. FUNCTIONS REVIEW

Problem 1.7: Notice that $\frac{x^{2}-x}{x-1}=\frac{(x-1)(x)}{x-1}=x$. Are $f(x)=\frac{x^{2}-x}{x-1}$ and $g(x)=x$ the same function?
Solution for Problem 1.7: No! The function $f$ is not defined for $x=1$, even though it appears that we can simplify our expression for $f(x)$ to just $x$. The simplification
$$\frac{x^{2}-x}{x-1}=\frac{x(x-1)}{x-1}=x$$
is only valid if $x \neq 1$. If $x=1$, then $\frac{x^{2}-x}{x-1}$ is $\frac{0}{0}$, which is not defined. In other words, 1 is not in the domain of $f$, but it is in the domain of $g$. So, $f$ and $g$ are not the same function.

We finish this section with the relatively obvious observation that the sum, product, and quotient of two functions are all themselves functions. For example, if $f$ and $g$ are functions, we can define a new function $h$ as $h=f+g$, where this means that $h(x)=f(x)+g(x)$. Note that $h(x)$ is only defined if both $f(x)$ and $g(x)$ are defined. Therefore, a number must be in the domains of both $f$ and $g$ in order to be in the domain of $f+g$.

In much the same way, we can define a new function as a linear combination of any two functions $f$ and $g$. Specifically, if $a$ and $b$ are constants, then we can define a new function $t$ as $t=a \cdot f+b \cdot g$, where this means that $t(x)=a \cdot f(x)+b \cdot g(x)$.

We can also define the function $p=f \cdot g$ such that $p(x)=f(x) \cdot g(x)$ and the function $q=f / g$ such that $q(x)=f(x) / g(x)$. Note that if $q=f / g$, then we must exclude values of $x$ for which $g(x)=0$ from the domain of $q$.

Exercises
1.1.1 Let $f(x)=x^{2}-x-6$.
(a) Compute $f(2)$.
(d) Is there a real value of $x$ such that $f(x)=6$ ?
(b) Find all $x$ such that $f(x)=0$.
(e) Find the range of $f$. Hints: 1
(c) Find $f(x-1)$.
1.1.2 Find the domain and range of each of the following real-valued functions:
(a) $f(x)=|1-x|$
(b) $f(t)=\sqrt{2-t}$
(c) $\quad h(x)=1-x^{2}$
(d) $\quad g(u)=\frac{1}{1+\frac{1}{u}}$
1.1.3 Let $f(x)=\sqrt{4-x}$ and $g(x)=\sqrt{2 x-6}$. Find the domain of $f \cdot g$ and the domain of $f / g$. Explain why these domains are different.
1.1.4 Do the functions $f(x)=\sqrt{\frac{2 x-5}{x-8}}$ and $g(x)=\frac{\sqrt{2 x-5}}{\sqrt{x-8}}$ have the same domain? Why or why not?
1.1.5 Let $f(x)=\frac{x+1}{x-1}$. Suppose $|x| \neq 1$. Simplify $f(x) \cdot f(-x)$.
1.1.6 A function $g(x)$ is defined for $-3 \leq x \leq 4$ such that $g(x)=(2+x)^{2}$. Find the range of $g$.
1.1.7 Let $T(a, b, c)=3 a^{b}-c$.
(a) Find $T(2,3,-5)$.
(b) Find all values of $x$ such that $T(x, 2,6)=21$.

8

---

<!-- Page 9 -->

1.2. GRAPHING FUNCTIONS
1.2 Graphing Functions

When we graph an equation in which the only variables are $x$ and/or $y$, we plot all points $(x, y)$ on the Cartesian plane that satisfy the equation. When we graph a function $f$, we graph the equation $y=f(x)$. For example, the graph of the function $f(x)=x^{2}$ is shown at right.

The $x$-intercepts of a graph are the points where the graph crosses the $x$-axis, while the $y$-intercepts are the points where the graph crosses the $y$-axis. For example, the point $(0,0)$ is both an $x$-intercept and a $y$-intercept of the graph of $f(x)=x^{2}$. (Note: Some sources use " $x$-intercept" to refer to the $x$-coordinate of a point where a graph crosses the $x$-axis, and likewise for " $y$-intercept." So, these sources would describe both the $x$-intercept and the $y$-intercept of the graph of $f(x)=x^{2}$ as 0 instead of $(0,0)$.)

In this section, we review the basics of graphing functions, getting information from the graph of a function, and transforming the graph of a function.

Problems
Problem 1.8: For each of the functions below, graph the function and find the $x$-intercepts and the $y$-intercepts of the graph.
(a) $f(x)=(x-6)^{2}-4$
(c) $f(x)=\sqrt{x+5}-3$
(b) $f(x)=4$
(d) $f(x)=|x+2|+1$

Problem 1.9: The graph of $y=f(x)$ is pictured at right.
(a) According to the graph, what is $f(2)$ ?
(b) According to the graph, for what values of $a$ is $f(a)=2$ ?

Problem 1.10:
(a) Is it possible for a vertical line to intersect the graph of a function at two different points? Why or why not?
(b) If there is no vertical line that passes through more than one point of a curve on the Cartesian plane, then is the curve the graph of a function?

9

---

<!-- Page 10 -->

CHAPTER 1. FUNCTIONS REVIEW

Problem 1.11: At right is the graph of $y=f(x)$.
(a) Explain why the graph of $y=f(x)+2$ is a 2-unit upward shift of the graph of $y=f(x)$.
(b) Explain why the graph of $y=f(x+2)$ is a 2-unit leftward shift of the graph of $y=f(x)$.
(c) Find the domain and range of $h$ if $h(x)=f(x+3)-4$.

Problem 1.12: Let $f(x)$ be the function graphed in the previous problem.
(a) Find the graph of $y=-f(x)$.
(b) Find the graph of $y=f(-x)$.
(c) Find the graph of $y=2 f(x)$.
(d) Find the graph of $y=f(2 x)$.

Problem 1.8: For each of the functions below, graph the function and find the $x$-intercepts and the $y$-intercepts of the graph.
(a) $f(x)=(x-6)^{2}-4$
(c) $f(x)=\sqrt{x+5}-3$
(b) $f(x)=4$
(d) $f(x)=|x+2|+1$

Solution for Problem 1.8:
(a) The graph of $y=(x-6)^{2}-4$ is an upward-opening parabola with vertex (6,-4). We find several points on the graph by finding $y$ for various values of $x$. A table with these points is at left below, and the graph is at right below.

\begin{tabular}{c|c}
$x$ & $y=f(x)$ \\
\hline 3 & 5 \\
4 & 0 \\
5 & -3 \\
6 & -4 \\
7 & -3 \\
8 & 0 \\
9 & 5
\end{tabular}

The $y$-intercept of the graph is the point where the graph intersects the $y$-axis. All points on the $y$-axis have an $x$-coordinate of 0 , so evaluating $f(0)$ gives us the $y$-coordinate of the $y$-intercept of the graph of $y=f(x)$. Since $f(0)=(0-6)^{2}-4=32$, the $y$-intercept of the graph is $(0,32)$.

The $x$-intercepts of the graph are those points where the graph intersects the $x$-axis. The $y$-coordinate of such a point is 0 , so the $x$-coordinates of the $x$-intercepts are the solutions to the equation $f(x)=0$. Therefore, we seek the values of $x$ such that $(x-6)^{2}-4=0$. Expanding and rearranging gives us $x^{2}-12 x+32=0$. Factoring gives $(x-4)(x-8)=0$, so our solutions are $x=4$ and $x=8$. Therefore, the $x$-intercepts of our graph are $(4,0)$ and $(8,0)$. (Notice that we could also read these off our graph.)

10

---

<!-- Page 11 -->

1.2. GRAPHING FUNCTIONS
(b) Since $f(x)=4$, the graph of $y=f(x)$ is the graph of $y=4$, which is a horizontal line as shown at right. This line meets the $y$-axis at $(0,4)$, so this is the $y$-intercept. The graph never hits the $x$-axis, so it does not have an $x$-intercept.
(c) As with the first part, we choose values of $x$, and then find $y$ such that $y=f(x)$. Notice that we start with $x=-5$ and then substitute greater values of $x$, because the domain of $f$ is $[-5,+\infty)$.

\begin{tabular}{c|c}
$x$ & $y=f(x)$ \\
\hline-5 & -3 \\
-4 & -2 \\
-1 & -1 \\
4 & 0 \\
11 & 1
\end{tabular}

When $x=0$, we have $y=f(0)=-3+\sqrt{5}$, so the $y$-intercept is $(0,-3+\sqrt{5})$. When $y=0$, we have $0=\sqrt{x+5}-3$. Adding 3 to both sides gives $3=\sqrt{x+5}$, and squaring both sides of this gives $9=x+5$. Solving this gives $x=4$, so $(4,0)$ is the $x$-intercept of the graph.
(d) If $x \geq-2$, we have $|x+2|=x+2$, so if $x \geq-2$, we have $f(x)=x+2+1=x+3$. So, when graphing $y=f(x)$, we graph $y=x+3$ for $x \geq-2$. Similarly, if $x<-2$, we have $|x+2|=-x-2$, so graphing $y=f(x)$ for $x<-2$ is the same as graphing $y=-x-2+1=-x-1$. The result is shown at right.

When $x=0$, we have $y=f(0)=3$, so $(0,3)$ is the $y$-intercept of the graph. When $y=0$, we have $0=|x+2|+1$. Subtracting 1 gives $|x+2|=-1$, which has no solutions because absolute value is always nonnegative. So, the graph has no $x$-intercept. (We can also see this from our graph.)

Now that we've used the definition of a function to get information about the graph of the function, let's try going the other direction-using a graph to get information about the function.

Problem 1.9: The graph of $y=f(x)$ is pictured at right.
(a) According to the graph, what is $f(2)$ ?
(b) According to the graph, for what values of $a$ is $f(a)=2$ ?

Solution for Problem 1.9:
(a) The graph of $y=f(x)$ passes through $(2,3)$, so we have $f(2)=3$.

11

---

<!-- Page 12 -->

CHAPTER 1. FUNCTIONS REVIEW

Important: If the point $(a, b)$ is on the graph of $y=f(x)$, then $f(a)=b$. Conversely, if (1) $f(a)=b$, then $(a, b)$ is on the graph of $y=f(x)$.
(b) To determine the values of $a$ such that $f(a)=2$, we locate the points on the graph of $y=f(x)$ such that $y=2$. The $x$-coordinates of these points then are our desired values of $a$. Since $(0,2)$ is on the graph of $y=f(x)$, we have $f(0)=2$.

There is another point on the graph with $y$-coordinate equal to 2 , but it's not immediately obvious what the $x$-coordinate of this point is. However, this point is on the line segment connecting $(2,3)$ to $(3,0)$, so we can use the equation of the line through these two points to find the desired $x$-coordinate. The slope of this line is $(3-0) /(2-3)=-3$, so a point-slope equation of the line is $y-0=-3(x-3)$, or $y=-3 x+9$. When $y=2$ in this equation, we have $x=7 / 3$, so the line passes through ( $7 / 3,2$ ). Therefore, we have $f(7 / 3)=2$, so the two values of $a$ for which $f(a)=2$ are $a=0$ and $a=7 / 3$.

Problem 1.10:
(a) Is it possible for a vertical line to intersect the graph of a function at two different points? Why or why not?
(b) If there is no vertical line that passes through more than one point of a curve on the Cartesian plane, then is the curve the graph of a function?

Solution for Problem 1.10:
(a) For each value of $x$ in the domain of $f$, there is exactly one value of $f(x)$. So, for each such value of $x$, there is only one point $(x, y)$ on the graph of $y=f(x)$. Therefore, it is impossible for the graph of a function to pass through two points with the same $x$-coordinate. Because the equation of any vertical line has the form $x=a$ for some constant $a$, it is impossible for a vertical line to pass through more than one point on the graph of a function.
(b) If there is not a vertical line that passes through more than one point of a graph, then for every value of $x$, there is at most one value of $y$ such that $(x, y)$ is on the graph. In other words, for every $x$ for which there is a point $(x, y)$ on the graph, there is exactly one corresponding value of $y$, so the graph does indeed represent a function.
Problem 1.11: At right is the graph of $y=f(x)$.
(a) Explain why the graph of $y=f(x)+2$ is a 2-unit upward shift of the graph of $y=f(x)$.
(b) Explain why the graph of $y=f(x+2)$ is a 2-unit leftward shift of the graph of $y=f(x)$.
(c) Find the domain and range of $h$ if $h(x)=f(x+3)-4$.

12

---

<!-- Page 13 -->

1.2. GRAPHING FUNCTIONS

Solution for Problem 1.11:
(a) Suppose $x=a$, where $a$ is in the domain of $f$. Then, the point $(a, f(a))$ is on the graph of $y=f(x)$ and the point ( $a, f(a)+2$ ) is on the graph of $y=f(x)+2$. Therefore, every point of the graph of $y=f(x)+2$ is 2 units above the corresponding point on the graph of $y=f(x)$. So, the graph of $y=f(x)+2$ is a 2-unit upward shift of the graph of $y=f(x)$. The graph of $y=f(x)+2$ is solid in the graph at right, and the graph of $y=f(x)$ is dashed.

Similarly, if $k$ is positive, then the graph of
$$y=f(x)+k$$
is a $k$-unit upward shift of the graph of $y=f(x)$, and the graph of
$$y=f(x)-k$$
is a $k$-unit downward shift of the graph of $y=f(x)$.
(b) Suppose $x=a$, where $a$ is in the domain of $f$. Then, the point $(a, f(a))$ is on the graph of $y=f(x)$ and the point (a, f(a+2)) is on the graph of $y=f(x+2)$. Unfortunately, it isn't so clear how $f(a)$ and $f(a+2)$ are related. To get a point on the graph of $y=f(x+2)$ with $y$-coordinate equal to $f(a)$, we have to let $x=a-2$. When $x=a-2$ in $y=f(x+2)$, we have $y=f(a)$, so $(a-2, f(a))$ is on the graph of $y=f(x+2)$.

We've shown that for any $a$ in the domain of $f$, the point $(a, f(a))$ is on the graph of $y=f(x)$ and the point ( $a-2, f(a)$ ) is on the graph of $y=f(x+2)$. Therefore, every point on the graph of $y=f(x+2)$ is 2 units to the left of the corresponding point on the graph of $y=f(x)$. So, the graph of $y=f(x+2)$ is a 2-unit leftward shift of the graph of $y=f(x)$. The graph of $y=f(x+2)$ is solid in the graph at right above, and the graph of $y=f(x)$ is dashed.

Similarly, if $k>0$, then the graph of
$$y=f(x+k)$$
is a $k$-unit leftward shift of the graph of $y=f(x)$ and the graph of
$$y=f(x-k)$$
is a $k$-unit rightward shift of the graph of $y=f(x)$.
WARNING!! A common mistake is to think that the graph of $y=f(x+k)$ is a rightward shift of the graph of $y=f(x)$ when $k$ is positive. This is incorrect; make sure you see why.
(c) The graph of $y=f(x+3)-4$ is the result of shifting the graph of $y=f(x)$ downward 4 units and leftward 3 units. The leftward shift means the domain of $h$ is 3 units "to the left" of the domain of $f$. The domain of $f$ is $[-5,3]$, so the domain of $h$ is $[-8,0]$. The downward shift means the range of $h$ is 4 units "below" the range of $f$. The range of $f$ is $[-3,4]$, so the range of $h$ is $[-7,0]$.

In Problem 1.11, we learned the effect of adding a constant to the input or to the output of a function:
Important: When $k>0$, the graph of $y=f(x)+k$ results from shifting the graph of $y=f(x)$
vertically upward by $k$ units, while the graph of $y=f(x+k)$ results from shifting the graph of $y=f(x)$ horizontally to the left by $k$ units. Similarly, the graph of $y=f(x)-k$ is a $k$-unit downward shift of the graph of $y=f(x)$ and the graph of $y=f(x-k)$ is a $k$-unit rightward shift.

13

---

<!-- Page 14 -->

CHAPTER 1. FUNCTIONS REVIEW

Problem 1.12: At right is the graph of $y=f(x)$.
(a) Find the graph of $y=-f(x)$.
(b) Find the graph of $y=f(-x)$.
(c) Find the graph of $y=2 f(x)$.
(d) Find the graph of $y=f(2 x)$.

Solution for Problem 1.12:
(a) As before, we let $x=a$, where $a$ is in the domain of $f$. Then, the point ( $a, f(a)$ ) is on the graph of $y=f(x)$ and the point ( $a,-f(a)$ ) is on the graph of $y=-f(x)$. So, the $y$-coordinate of each point on the graph of $y=-f(x)$ is the opposite of the $y$-coordinate of the corresponding point on the graph of $y=f(x)$. Therefore, we form the graph of $y=-f(x)$ by reflecting the graph of $y=f(x)$ over the $x$-axis. Below, the graph of $y=-f(x)$ is solid and the graph of $y=f(x)$ is dashed.
(b) We let $x=a$, where $a$ is in the domain of $f$. Then, the point ( $a, f(a)$ ) is on the graph of $y=f(x)$ and the point ( $a, f(-a)$ ) is on the graph of $y=f(-x)$. We can find a point on the graph of $y=f(-x)$ with $f(a)$ as the $y$-coordinate by letting $x=-a$, which tells us that ( $-a, f(a)$ ) is on the graph of $y=f(-x)$. Therefore, the graph of $y=f(-x)$ is the result of reflecting the graph of $y=f(x)$ over the $y$-axis. Below, the graph of $y=f(-x)$ is solid and the graph of $y=f(x)$ is dashed.

Important: The graph of $y=-f(x)$ is the result of reflecting the graph of $y=f(x)$ over the $x$-axis.
The graph of $y=f(-x)$ is the result of reflecting the graph of $y=f(x)$ over the $y$-axis.

14

---

<!-- Page 15 -->

1.2. GRAPHING FUNCTIONS
(c) For each point ( $a, f(a)$ ) on the graph of $y=f(x)$, the point ( $a, 2 f(a)$ ) is on the graph of $y=2 f(x)$. The latter point is twice as far from the $x$-axis as the former. Similarly, each point on the graph of $y=2 f(x)$ can be found by doubling the distance from the $x$-axis of the corresponding point on the graph of $y=f(x)$. Therefore, the graph of $y=2 f(x)$ can be found by scaling the graph of $y=f(x)$ vertically away from the $x$-axis by a factor of 2 . At right, the graph of $y=2 f(x)$ is solid and the graph of $y=f(x)$ is dashed.
(d) For each point ( $2 a, f(2 a)$ ) on the graph of $y=f(x)$, the point ( $a, f(2 a)$ ) is on the graph of $y=f(2 x)$. The latter point is half as far from the $y$-axis as the former. Similarly, each point on the graph of $y=f(2 x)$ can be found by halving the distance from the $y$-axis of the corresponding point on the graph of $y=f(x)$. Therefore, the graph of $y=f(2 x)$ can be found by scaling the graph of $y=f(x)$ horizontally relative to the $y$-axis by a factor of $1 / 2$. At right, the graph of $y=f(2 x)$ is solid and the graph of $y=f(x)$ is dashed.

Important: When $k>0$, the graph of $y=k f(x)$ results from scaling the graph of $y=f(x)$
D vertically relative to the $x$-axis by a factor of $k$, while the graph of $y=f(k x)$ results from scaling the graph of $y=f(x)$ horizontally relative to the $y$-axis by a factor of $1 / k$.

WARNING!! The graph of $y=f(k x)$ is a horizontal scaling of the graph of $y=f(x)$ by a factor of $1 / k$, not by $k$. So, for example, the graph of $y=f(3 x)$ is the result of compressing the graph of $y=f(x)$ towards the $y$-axis, not stretching it away from the $y$-axis.

Exercises
1.2.1 Graph each of the following, and find the $x$-intercepts and $y$-intercepts of each graph.
(a) $f(x)=3 x-7$
(b) $f(x)=2-|x|$
(c) $f(x)=x^{2}-5 x+6$
1.2.2 Determine if each of the following graphs represents a function:

(a)

(b)

(c)

15

---

<!-- Page 16 -->

CHAPTER 1. FUNCTIONS REVIEW
1.2.3 Suppose $f(9)=2$. For each of the parts below, find a point that must be on the graph of the given equation.
(a) $y=f(x-3)+5$
(b) $y=2 f(x / 4)$
(c) $y=2 f(3 x-1)+7$
1.2.4 ★ Suppose $f(4)=8$. Note that the point $(2,8)$ is on the graph of $y=f(2 x)$ and that the point $(5,8)$ is on the graph of $y=f(2 x-6)$. So, the point we have found on the graph of $y=f(2 x-6)$ is 3 units to the right of the point we found on the graph of $y=f(2 x)$. Which of the following is true: (a) we made a mistake; (b) it's a coincidence-not every point on $y=f(2 x-6)$ is 3 to the right of a point on $y=f(2 x)$; (c) the graph of $y=f(2 x-6)$ is a 3 -unit rightward shift of the graph of $y=f(2 x)$. Explain your answer. Hints: 53
1.3 Composition

Sometimes we want to hook two (or more) machines together, taking the output from one machine and putting it into another. When we connect functions together like this, we are performing a composition of the functions. For example, the expression $f(g(x))$ means we put our input $x$ into function $g$, and then take the output, $g(x)$, and put that into function $f$. A composition of functions is also sometimes indicated with the symbol ∘. For example, when we write $h=f \circ g$, we define the function $h$ such that $h(x)=f(g(x))$.

Problems
Problem 1.13: Suppose $f(x)=3 x+7$ and $g(x)=2 \sqrt{x-3}$.
(a) Find $f(g(3))$ and $g(f(3))$.
(b) Find $a$ if $f(g(a))=25$.
(c) Is $g(f(-7))$ defined? Why or why not?
(d) Suppose that $h=g \circ f$. What is the domain of $h$ ?

Problem 1.14:
(a) Let $h(x)=f(g(x))$, where $f$ and $g$ are functions, and suppose $h(x)$ is defined for all values of $x$ in the domain of $g$. Explain why the range of $g$ must be part of the domain of $f$.
(b) Again, let $h(x)=f(g(x))$, where $f$ and $g$ are functions. Suppose every value in the range of $g$ is in the domain of $f$. Must the domain of $h$ be the same as the domain of $g$ ?

Problem 1.15: Let $f(a)=a-2$ and $F(a, b)=b^{2}+a$. Find $F(3, f(4))$. (Source: AHSME)
Problem 1.16:
(a) Let $f(x)=3 x-1$. Find $f(f(x))$ and $f(f(f(x)))$.
(b) Suppose $g(x)=a x+b$, where $a$ and $b$ are real constants. Find all possible pairs $(a, b)$ such that we have $g(g(x))=9 x+28$.

Problem 1.17: Let $f(x)=\sqrt{x}$ and $g(x)=x^{2}$. Is it true that $f(g(x))$ and $g(f(x))$ are the same function? Why or why not?

16

---

<!-- Page 17 -->

1.3. COMPOSITION

Problem 1.13: Suppose $f(x)=3 x+7$ and $g(x)=2 \sqrt{x-3}$.
(a) Find $f(g(3))$ and $g(f(3))$.
(b) Find $a$ if $f(g(a))=25$.
(c) Is $g(f(-7))$ defined? Why or why not?
(d) Suppose that $h=g \circ f$. What is the domain of $h$ ?

Solution for Problem 1.13:
(a) We have $g(3)=2 \sqrt{3-3}=0$, so $f(g(3))=f(0)=3(0)+7=7$. Similarly, we have $f(3)=3(3)+7=16$, so $g(f(3))=g(16)=2 \sqrt{16-3}=2 \sqrt{13}$. Notice that $f(g(3)) \neq g(f(3))$.

WARNING!! If $f(x)$ and $g(x)$ are functions, then the functions $f(g(x))$ and $g(f(x))$ are not necessarily the same function.
(b) We have
$$f(g(a))=f(2 \sqrt{a-3})=3(2 \sqrt{a-3})+7=6 \sqrt{a-3}+7$$
so $f(g(a))=25$ means
$$6 \sqrt{a-3}+7=25$$

Subtracting 7 from both sides and then dividing both sides by 6 gives $\sqrt{a-3}=3$. Squaring both sides gives us $a-3=9$, so $a=12$. Checking our answer, we find $f(g(12))=f(6)=25$, as expected.
(c) We have $f(-7)=3(-7)+7=-14$, so $g(f(-7))=g(-14)$. However, the value -14 is not in the domain of $g$. Since $g(-14)$ is not defined, $g(f(-7))$ is not defined.
(d) Since $h(x)=g(f(x))$, in order for $x$ to be in the domain of $h$, both $f(x)$ and $g(f(x))$ must be defined. The domain of $f$ is all real numbers; however, as we saw in the previous part, $g(f(x))$ is not defined for all real values of $x$.

In order for $g(f(x))$ to be defined, the value of $f(x)$ must be in the domain of $g$. The domain of $g$ is $[3,+\infty)$. Therefore, in order for $g(f(x))$ to be defined, we must have $f(x) \geq 3$. So, we must have $3 x+7 \geq 3$, which gives us $x \geq-4 / 3$. For all values of $x$ such that $x \geq-4 / 3$, the expression $g(f(x))$ is defined. For any value of $x$ less than $-4 / 3$, the expression $g(f(x))$ is not defined. Therefore, the domain of $h$ is $[-4 / 3,+\infty)$.

Problem 1.14:
(a) Let $h(x)=f(g(x))$, where $f$ and $g$ are functions, and suppose $h(x)$ is defined for all values of $x$ in the domain of $g$. Explain why the range of $g$ must be part of the domain of $f$.
(b) Again, let $h(x)=f(g(x))$, where $f$ and $g$ are functions. Suppose every value in the range of $g$ is in the domain of $f$. Must the domain of $h$ be the same as the domain of $g$ ?

Solution for Problem 1.14:
(a) Since $h(x)=f(g(x))$ and $h(x)$ is defined for all values of $x$ in the domain of $g$, the expression $f(g(x))$ must be defined for all values of $x$ in the domain of $g$. Because $f(g(x))$ is defined, the value of $g(x)$ is in the domain of $f$. So, every number in the range of $g$ must be in the domain of $f$.
(b) The expression $f(g(x))$ is not defined if $g(x)$ is not defined. Therefore, all values in the domain of $h$ must be in the domain of $g$. Conversely, if $x$ is in the domain of $g$, then $g(x)$ is defined. Furthermore, we are given that every value in the range of $g$ is in the domain of $f$, so $f(g(x))$ is defined for all $x$ in the domain of $g$. Therefore, every value in the domain of $g$ is in the domain of $h$. Since every value in the domain of $g$ is in the domain of $h$, and vice versa, we conclude that the domain of $h$ is the same as the domain of $g$.

17

---

<!-- Page 18 -->

CHAPTER 1. FUNCTIONS REVIEW

Problem 1.15: If $f(a)=a-2$ and $F(a, b)=b^{2}+a$, find the value of $F(3, f(4))$. (Source: AHSME)
Solution for Problem 1.15: We note that $f(4)=4-2=2$, so
$$F(3, f(4))=F(3,2)=2^{2}+3=7 .$$

Although the expression $F(3, f(4))$ looks a little intimidating, the process of evaluating it is just simple plug-and-chug arithmetic.

Concept: Don't be intimidated by notation. Often the notation is a fancy way of representing very simple ideas.

We'll see the value of notation as we move to more complicated problems throughout this book. However, we'll usually introduce notation with simple problems like Problem 1.15 so you can get used to the notation before using it on harder problems.

Problem 1.16:
(a) Let $f(x)=3 x-1$. Find $f(f(x))$ and $f(f(f(x)))$.
(b) Suppose $g(x)=a x+b$, where $a$ and $b$ are real constants. Find all possible pairs $(a, b)$ such that we have $g(g(x))=9 x+28$.

Solution for Problem 1.16:
(a) We have
$$f(f(x))=f(3 x-1)=3(3 x-1)-1=9 x-4$$

We can now use this result to find $f(f(f(x)))$ by inputting $f(f(x))$, which equals $9 x-4$, into $f(x)$ :
$$f(f(f(x)))=f(9 x-4)=3(9 x-4)-1=27 x-13$$
(b) In order to find $a$ and $b$, we first need an expression for $g(g(x))$. We have
$$g(g(x))=g(a x+b)=a(a x+b)+b=a^{2} x+a b+b$$

So, our equation $g(g(x))=9 x+28$ is now $a^{2} x+a b+b=9 x+28$. In order for this equation to be true for all values of $x$, the coefficient of $x$ on both sides must be the same and the constant terms on both sides must be the same. Therefore, we have the system of equations
$$\begin{aligned}
a^{2} & =9 \\
a b+b & =28
\end{aligned}$$

From $a^{2}=9$, we have $a= \pm 3$. Letting $a=3$ in the second equation gives $b=7$ and letting $a=-3$ in the second equation gives $b=-14$. So, our two possible pairs are $(a, b)=(3,7)$ and $(a, b)=(-3,-14)$.

We have a special notation for repeatedly feeding the output of a function back into the function itself. In this text, we will often write $f^{2}(x)$ to mean $f(f(x))$. Likewise, $f^{n}(x)$ usually refers to applying the function $f(x)$ exactly $n$ times; for example, $f^{5}(x)=f(f(f(f(f(x)))))$.

18

---

<!-- Page 19 -->

1.4. INVERSE FUNCTIONS

WARNING!! Some sources use $f^{2}(x)$ to mean $f(x) \cdot f(x)$ instead of $f(f(x))$. Likewise, $f^{n}(x)$ is sometimes used to denote $[f(x)]^{n}$. You'll often have to determine by context whether $f^{n}(x)$ refers to a function applied $n$ times, or to a function raised to the $n^{\text {th }}$ power.

Problem 1.17: Let $f(x)=\sqrt{x}$ and $g(x)=x^{2}$. Is it true that $f(g(x))$ and $g(f(x))$ are the same function? Why or why not?

Solution for Problem 1.17: At first glance, we might be tempted to reason as follows:

Bogus Solution: We have $f(g(x))=\sqrt{x^{2}}=x$ and $g(f(x))=(\sqrt{x})^{2}=x$, so $f(g(x))$ and $g(f(x))$
are the same.

This Bogus Solution contains two significant errors. First, the domain of $f$ is all nonnegative numbers, so the domain of $g(f(x))$ is all nonnegative numbers. However, because the domain of $g$ is all reals while the range of $g$ is all nonnegative numbers, the expression $f(g(x))$ is defined for all real $x$. Therefore, the domain of $f(g(x))$ is all real numbers. So, the two functions $g(f(x))$ and $f(g(x))$ have different domains, which means that the functions are not the same. For example, we have $f(g(-1))=f(1)=1$, but $g(f(-1))$ is undefined, because $f(-1)$ is undefined.

The other error occurs when we write $\sqrt{x^{2}}=x$. This statement is only true if $x \geq 0$. If $x<0$, then we have $\sqrt{x^{2}}=-x$. So, it is not true that $f(g(x))=x$ for all $x$. If $x \geq 0$, then $f(g(x))=x$, and if $x<0$, then $f(g(x))=-x$. We can capture both of these by writing $f(g(x))=|x|$.

Exercises
1.3.1 Check the answer to part (b) of Problem 1.16 by evaluating $g(g(x))$ for $g(x)=3 x+7$ and for $g(x)=-3 x-14$.
1.3.2 Let $f(x)=x^{2}-2 x$ and $g(x)=\sqrt{1-x}$.
(a) Find $f(g(x))$.
(b) Find the domain of $f(g(x))$.
(c) Is $g(f(-2))$ defined? Why or why not?
1.3.3 Are both $f\left(f^{2}(x)\right)$ and $f^{2}(f(x))$ the same as $f^{3}(x)$ ?
1.3.4 Let $a$ be a constant, and let $f(x)=a x$. Find an expression for $f^{n}(x)$ in terms of $a$ and $n$, where $n$ is a positive integer.
1.3.5 Suppose $h, f$, and $g$ are functions such that $h(x)=f(g(x))$. If $(3,0)$ is the only $x$-intercept of the graph of $g$, then can we determine the $x$-intercepts or $y$-intercepts of $h$ ?
1.4 Inverse Functions

You're probably very familiar with using Control-Z when typing on a computer: that's the "undo" command for many applications. Being able to "undo" the work of a function can be extremely useful. The machine that "undoes" the work of a function $f$ is called the inverse function of $f$.

19

---

<!-- Page 20 -->

CHAPTER 1. FUNCTIONS REVIEW

Definition: Function $g$ is the inverse of function $f$ if
$$\begin{array}{l}
g(f(x))=x \text { for all values of } x \text { in the domain of } f, \text { and } \\
f(g(x))=x \text { for all values of } x \text { in the domain of } g .
\end{array}$$

From our definition, we see that if $g$ is the inverse function of $f$, then $f$ is the inverse function of $g$. Moreover, the range of $g$ is the domain of $f$, and vice versa.

As we will see, not every function has an inverse. However, if a function has an inverse, then the inverse is unique, as our definition implies. We can see this by noting that if $g$ and $h$ are both inverses of $f$, then we have $g(f(x))=x$ and $h(f(x))=x$, so $g(f(x))=h(f(x))$ for all $x$ in the domain of $f$. Letting $y=f(x)$, we have $g(y)=h(y)$ for all $y$ in the domain of $g$ and $h$, so $g$ and $h$ are the same function.

We have a special notation to denote the inverse of a function. We often write the inverse of $f$ as $f^{-1}$.
WARNING!! When working with functions, $f^{-1}$ does not mean $\frac{1}{f}$ ! The expression $f^{-1}$ is a special notation that denotes the inverse of the function $f$.

Problems
Problem 1.18: In this problem we find the inverse of the function $f(x)=3 x-5$.
(a) Let $g$ be the inverse of $f$, so that we have $f(g(x))=x$ and $g(f(x))=x$. Which of these equations is easier to use to find $g(x)$ ?
(b) Use the definition of $f$ to solve the equation $f(y)=x$ for $y$.
(c) What is $g(x)$ ?
(d) Check your answer by confirming that $g(f(x))=x$.

Problem 1.19: Let $f(x)=\frac{-5-x}{3-2 x}$.
(a) Find $f^{-1}(7)$, without finding $f^{-1}(x)$.
(b) Find $f^{-1}(x)$.

Problem 1.20:
(a) Does the function $g(x)=2 x^{2}-9$ have an inverse? If it does, find it. If it doesn't, explain why it doesn't.
(b) Does the function $h(x)=3 \sqrt{2 x+1}$ have an inverse? If it does, find it. If it doesn't, explain why it doesn't. (Be careful on this part!)

Problem 1.21:
(a) Explain how to determine from the graph of a function whether or not the function has an inverse.
(b) How are the graph of a function and the graph of its inverse related?

Problem 1.22: Suppose functions $f$ and $g$ both have inverses. Show that if $h=f \circ g$, then the inverse of $h$ is $g^{-1} \circ f^{-1}$.

Problem 1.18: Find the inverse of the function $f(x)=3 x-5$.

20

---

<!-- Page 21 -->

1.4. INVERSE FUNCTIONS

Solution for Problem 1.18: Suppose $g$ is the inverse of $f$. Then, we must have
$$g(f(x))=f(g(x))=x .$$

The equation $f(g(x))=x$ is more helpful, because we know $f(x)$. So, we can put $g(x)$ into $f(x)$, which gives us $f(g(x))=3 g(x)-5$. Therefore, we must have $3 g(x)-5=x$.

We isolate $g(x)$ by adding 5 to both sides, then dividing by 3 . This gives us $g(x)=\frac{x+5}{3}$. We can check our work by confirming that $f(g(x))=g(f(x))=x$. Therefore, we have $f^{-1}(x)=\frac{x+5}{3}$.

Note that we found the inverse of $f$ by solving the equation $f(g(x))=x$ for $g(x)$. Make sure you see why this produces a function $g$ that is the inverse of $f$.

Important: If $f$ has an inverse $g$, then we can often find that inverse by solving the equation
$$1 \quad f(g(x))=x \text { for } g(x) \text {. }$$

If you find the idea of "solving for a function" confusing, you can instead let $y=g(x)$ and solve for $y$. For example, when $f(x)=3 x-5$, we can solve for $y$ in $f(y)=x$ to find the inverse of $f$. Since $f(y)=x$, we have $3 y-5=x$. Solving for $y$ gives $y=\frac{x+5}{3}$, so the inverse of $f$ is $f^{-1}(x)=\frac{x+5}{3}$.

Problem 1.19: Let $f(x)=\frac{-5-x}{3-2 x}$.
(a) Find $f^{-1}(7)$, without finding $f^{-1}(x)$.
(b) Find $f^{-1}(x)$.

Solution for Problem 1.19:
(a) Suppose $y=f^{-1}(7)$. Because $f^{-1}$ is the inverse of $f$, we have $f\left(f^{-1}(x)\right)=x$ for all values of $x$. Specifically, we have $f\left(f^{-1}(7)\right)=7$, so because $y=f^{-1}(7)$, we have $f(y)=7$. We also could have deduced $f(y)=7$ by noting that $y=f^{-1}(7)$ means that the $y$ is the input to $f$ that produces 7 as an output.
$$\text { Important: If function } f \text { has an inverse, then } f(a)=b \text { means that } f^{-1}(b)=a \text {, and vice versa. }$$

Since $f(y)=7$, we have
$$\frac{-5-y}{3-2 y}=7$$

Multiplying both sides by $3-2 y$ gives $-5-y=7(3-2 y)$. Solving this equation gives us $y=2$. Therefore, $f^{-1}(7)=2$.
(b) As we just learned, we can find the inverse of $f$ by solving the equation $f(y)=x$ for $y$ in terms of $x$. Using our definition of $f$, the equation $f(y)=x$ becomes
$$\frac{-5-y}{3-2 y}=x$$

Multiplying both sides by $3-2 y$ gives $-5-y=x(3-2 y)$. Isolating the terms with $y$ on the left side gives $2 x y-y=3 x+5$, so $y(2 x-1)=3 x+5$. Dividing by $2 x-1$ gives
$$f^{-1}(x)=y=\frac{3 x+5}{2 x-1}$$

21

---

<!-- Page 22 -->

CHAPTER 1. FUNCTIONS REVIEW

With this, we can check our answer to the first part by directly evaluating $f^{-1}(7)=2$.

We say that a function is invertible if it has an inverse. As you might have guessed, not all functions are invertible.

Problem 1.20:
(a) Does the function $g(x)=2 x^{2}-9$ have an inverse? If it does, find it. If it doesn't, explain why it doesn't.
(b) Does the function $h(x)=3 \sqrt{2 x+1}$ have an inverse? If it does, find it. If it doesn't, explain why it doesn't.

Solution for Problem 1.20:
(a) Both $g(1)$ and $g(-1)$ equal -7 . If $g$ has an inverse, should this inverse return 1 or -1 when -7 is input? We can't tell! Therefore, $g$ is not reversible; it does not have an inverse.

Important: If a function gives the same output for two different inputs, then the function
□ does not have an inverse.

On the other hand, if a function never gives the same output for two different inputs, then the function is invertible-we can tell from the output of the function what input produced that output.

Important: If there are no two different inputs to a function that produce the same output,
□ then the function has an inverse.
(b) We start by looking for two different inputs to $h$ that give the same output. After inputting a few values to $h$, we notice that as we input higher and higher values of $x$, we get higher and higher values of $h(x)$. This makes us think that $h$ might indeed have an inverse, since it seems impossible to find two different inputs that give the same output. So, we try to find the inverse of $h$ by solving the equation $h(y)=x$ for $y$. This gives us the equation
$$3 \sqrt{2 y+1}=x$$

Squaring both sides gives us $9(2 y+1)=x^{2}$. Solving for $y$ gives
$$y=\frac{x^{2}}{18}-\frac{1}{2}$$

This isn't the end of the story, however. Recall our definition of inverse functions. Functions $f$ and $h$ are inverse functions of each other if
$$\begin{array}{l}
h(f(x))=x \text { for all values of } x \text { in the domain of } f, \text { and } \\
f(h(x))=x \text { for all values of } x \text { in the domain of } h .
\end{array}$$

We let $f(x)=\frac{x^{2}}{18}-\frac{1}{2}$. Our work above suggests that this is the inverse of $h$. However, if $f$ is the inverse of $h$, then $h$ is the inverse of $f$. So, we should have $h(f(x))=x$ for all $x$ in the domain of $f$. Unfortunately, we have $f(-3)=0$, but $h(f(-3))=h(0)=3$, so we don't have $h(f(x))=x$ when $x=-3$. The problem here is that the function $f(x)=\frac{x^{2}}{18}-\frac{1}{2}$ does not have an inverse. We can see this quickly by noting that $f(3)=f(-3)=0$. So, where did we go wrong?

Let's evaluate $h(f(x))$ and see if it really does equal $x$. Maybe this will shed some light on where we went wrong. We have
$$h(f(x))=3 \sqrt{2 f(x)+1}=3 \sqrt{\frac{x^{2}}{9}-1+1}=3 \sqrt{\frac{x^{2}}{9}}=\sqrt{x^{2}}$$

Here, we have to be careful.

22

---

<!-- Page 23 -->

1.4. INVERSE FUNCTIONS

WARNING!! We only have $\sqrt{x^{2}}=x$ if $x$ is nonnegative.
Now, we've found our problem. We only have $h(f(x))=x$ if $\sqrt{x^{2}}=x$. This only occurs if $x$ is nonnegative. So, if we restrict the domain of $f$ to nonnegative numbers, then we have $h(f(x))=x$ for all values of $x$ in the domain of $f$. We can quickly confirm that $f(h(x))=x$ for all $x$ in the domain of $h$ as well. So, the inverse of $h$ is $h^{-1}(x)=\frac{x^{2}}{18}-\frac{1}{2}$, where the function $h^{-1}$ is only defined for nonnegative values of $x$.

Problem 1.21:
(a) Explain how to determine from the graph of a function whether or not the function has an inverse.
(b) How are the graph of a function and the graph of its inverse related?

Solution for Problem 1.21:
(a) A function has an inverse if and only if we can always tell from the output of the function what the input was. If $f$ has an inverse, then when we graph $y=f(x)$, there can be no two points on the graph with the same $y$-coordinate. If there were, then we would have two different inputs (the $x$-coordinates of points on the graph) that provide the same output (the common $y$-coordinate) for the function, so it couldn't have an inverse. "No two points on the graph have the same $y$-coordinate" means the same thing as "No horizontal line intersects the graph in more than one point." Therefore, we have a horizontal line test for whether or not a function has an inverse:
(b) Suppose the point $(a, b)$ is on the graph of $y=f(x)$. Then, we have $f(a)=b$, so $f^{-1}(b)=a$. Because $f^{-1}(b)=a$, the point ( $b, a$ ) is on the graph of $y=f^{-1}(x)$. Therefore, if ( $a, b$ ) is on the graph of a function, then ( $b, a$ ) is on the graph of its inverse.

The fact that the points on the graph of $y=f^{-1}(x)$ can be found by reversing the coordinates of the points on the graph of $y=f(x)$ has a geometric interpretation. We just learned that if $(a, b)$ is on the graph of $y=f(x)$, then $(b, a)$ is on the graph of $y=f^{-1}(x)$. In the graph at right, we have plotted the points $(5,6),(6,-3)$, and $(-7,1)$. We have also plotted the points that result when the coordinates of these three points are reversed. We see that the new points are the result of reflecting the old points over the line $y=x$. The graph of $y=x$ is the dashed line in the diagram at right.

In general, reversing the coordinates of a point has the same effect as reflecting the point over the graph of $y=x$. To prove this, we let point $P$ be $(a, b)$ and $Q$ be $(b, a)$. The slope of $\overline{P Q}$ is -1 , so $\overline{P Q}$ is perpendicular to the graph of $y=x$. Furthermore, the midpoint of $\overline{P Q}$ is $\left(\frac{a+b}{2}, \frac{a+b}{2}\right)$, which is on the graph of $y=x$. So, the graph of $y=x$ is the perpendicular bisector of $\overline{P Q}$, which means that $P$ and $Q$ are images of each other upon reflection over the graph of $y=x$. So, each point on the graph of $y=f^{-1}(x)$ is the mirror image of a point on the graph of $y=f(x)$ when reflected over the line $y=x$ (and vice versa). Therefore, the entire graph of $y=f^{-1}(x)$ is the mirror image of the graph of $y=f(x)$ when reflected over the line $x=y$.

Important: If the function $f$ has an inverse $f^{-1}$, then the graph of $y=f^{-1}(x)$ is the reflection
of the graph of $y=f(x)$ over the line $x=y$.

23

---

<!-- Page 24 -->

CHAPTER 1. FUNCTIONS REVIEW

Problem 1.22: Suppose functions $f$ and $g$ both have inverses. Show that if $h=f \circ g$, then the inverse of $h$ is $g^{-1} \circ f^{-1}$.

Solution for Problem 1.22: Let $t=g^{-1} \circ f^{-1}$. To show that $t$ is the inverse of $h$, we must show that $h(t(x))=x$ and $t(h(x))=x$. We'll start with $h(t(x))$. Using our definitions of $h$ and $t$, we have
$$h(t(x))=f\left(g\left(g^{-1}\left(f^{-1}(x)\right)\right)\right) .$$

That looks pretty scary! But seeing both $g$ and $g^{-1}$ right next to each other reminds us that $g\left(g^{-1}(x)\right)=x$. In other words, the output of $g \circ g^{-1}$ is always the same as the input. So, when we put $f^{-1}(x)$ into $g \circ g^{-1}$, we get $f^{-1}(x)$ out, which means
$$g\left(g^{-1}\left(f^{-1}(x)\right)\right)=f^{-1}(x)$$

So, using this in our expression for $h(t(x))$ above, we have
$$h(t(x))=f\left(g\left(g^{-1}\left(f^{-1}(x)\right)\right)\right)=f\left(f^{-1}(x)\right) .$$

Because $f^{-1}$ is the inverse of $f$, we have $f\left(f^{-1}(x)\right)=x$, so $h(t(x))=x$.
We can do essentially the same thing for $t(h(x))$. We start with
$$t(h(x))=g^{-1}\left(f^{-1}(f(g(x)))\right) .$$

Because $f$ is the inverse of $f^{-1}$, we have $f^{-1}(f(g(x)))=g(x)$, so $t(h(x))=g^{-1}\left(f^{-1}(f(g(x)))\right)=g^{-1}(g(x))=x$, as desired. Because $h(t(x))=t(h(x))=x$ when $h=f \circ g$ and $t=g^{-1} \circ f^{-1}$, the function $g^{-1} \circ f^{-1}$ is the inverse of $f \circ g$.

Exercises
1.4.1 If $f(x)=\frac{x-1}{x-2}$, what is the value of $f^{-1}(3)$ ?
1.4.2 Determine whether or not each of the following functions has an inverse. If the function has an inverse, find it.
(a) $f(x)=2 x-7$
(c) $f(x)=\sqrt{2-x}$
(e) $f(x)=\sqrt{4-x}+\sqrt{x-2}$
(b) $f(x)=\frac{1}{2 x+3}$
(d) $f(x)=|5-x|$
(f) $\star \quad f(x)=x^{2}-6 x+3$, where $x \geq 4$
1.4.3 Describe all ordered pairs $(a, b)$ such that the inverse of $f(x)=a x+b$ satisfies $f(x)=f^{-1}(x)$ for all $x$.
1.4.4 Let $g(x)=\frac{a x+b}{c x+d}$, where $a, b, c$, and $d$ are positive and $a d \neq b c$. Which of $\frac{a}{b}, \frac{a}{c}$, and $\frac{a}{d}$ cannot be in the domain of $g^{-1}$ ? Hints: 146
1.5 Summary

A function gives a single output for each input. The domain of a function consists of all the values we are able to input to the function and get an output. Meanwhile, the range of the function consists of all the values that can come out of the function.

When we graph the function $f$, we graph the equation $y=f(x)$ on the Cartesian plane. Therefore, if the point $(a, b)$ is on the graph of $y=f(x)$, then $f(a)=b$. Conversely, if $f(a)=b$, then $(a, b)$ is on the graph of $y=f(x)$.

\begin{tabular}{|l|} 
Important: \\
A curve on the Cartesian plane is the graph of some function if and only if every \\
vertical line passes through no more than one point on the curve. We call this \\
the vertical line test.
\end{tabular}

24

---

<!-- Page 25 -->

1.5. SUMMARY

When we perform a composition of two functions, we place the output from the first function into the second. For example, both $f(g(x))$ and $(f \circ g)(x)$ indicate that we take the output $g(x)$ and input this result to $f$. We have a special notation for when we feed the output of a function back into the function itself. In this text, we write $f^{2}(x)$ to mean $f(f(x))$. Likewise, $f^{n}(x)$ refers to applying the function $f(x)$ exactly $n$ times; for example, $f^{5}(x)=f(f(f(f(f(x)))))$.

Finally, we have a special name for a pair of functions such that each function "undoes" the action of the other:

Definition: If $f$ and $g$ are functions such that
$$\begin{array}{l}
g(f(x))=x \text { for all values of } x \text { in the domain of } f, \text { and } \\
f(g(x))=x \text { for all values of } x \text { in the domain of } g,
\end{array}$$
then $f$ is the inverse of $g$, and $g$ is the inverse of $f$.

Not every function has an inverse. If a function gives the same output for two different inputs, then the function does not have an inverse. If there are no two different inputs to a function that produce the same output, then the function has an inverse. If $f$ has an inverse $g$, then we can often find that inverse by solving the equation $f(g(x))=x$ for $g(x)$.

We usually denote the inverse of the function $f$ as $f^{-1}$. If $f$ has an inverse, then the graph of $f^{-1}$ is the reflection of the graph of $f$ over the line $y=x$.

Important: A function has an inverse if and only if there does not exist a horizontal line
that passes through more than one point on the graph of the function.

Things To Watch Out For! 
- When evaluating a function that accepts multiple inputs, make sure you assign the values to the dummy variables in the correct order.
- We must take into account any restrictions on the domain of a function when finding the range of the function.
- Sometimes there is more than one constraint on the domain of a function.

25

---

<!-- Page 26 -->

CHAPTER 1. FUNCTIONS REVIEW
- A common mistake is to think that the graph of $y=f(x+k)$ is a rightward shift of the graph of $y=f(x)$ when $k$ is positive. This is incorrect; make sure you see why.
- The graph of $y=f(k x)$ is a horizontal scaling of the graph of $y=f(x)$ by a factor of $1 / k$, not by $k$. So, the graph of $y=f(3 x)$ is the result of compressing the graph of $y=f(x)$ towards the $y$-axis, not stretching it away from the $y$-axis.
- Some sources use $f^{2}(x)$ to mean $f(x) \cdot f(x)$ instead of $f(f(x))$. Likewise, $f^{n}(x)$ is sometimes used to denote $[f(x)]^{n}$. You'll often have to determine by context whether $f^{n}(x)$ refers to a function applied $n$ times, or to a function raised to the $n^{\text {th }}$ power.
- Don't be intimidated by notation. Often the notation is a fancy way of representing very simple ideas.
- When working with functions, $f^{-1}$ does not mean $\frac{1}{f}$ ! The expression $f^{-1}$ is a special notation that denotes the inverse of the function $f$.

Problem Solving Strategies

Concepts:
- We can often check our answers in algebra problems by plugging the solutions we find back into the original question.
- Keep your eye on the ball. Sometimes we don't need to evaluate every variable in a problem in order to solve the problem.

Review Problems
1.23 Find the domain and range of each of the following functions:
(a) $A(x)=4 x^{2}+1$
(c) $P(x)=\frac{1}{3+\sqrt{x+1}}$
(b) $\quad o(x)=3+\sqrt{16-(x-3)^{2}}$
(d) $\quad S(x)=\frac{12 x-9}{6-9 x}$
1.24 Find the domain of each of the following functions:
(a) $f(x)=\frac{1}{\sqrt{2 x-5}}+\sqrt{9-3 x}$
(b) $f(x)=|\sqrt{x}-2|+|\sqrt{x-2}|$
(c) $g(x)=\sqrt{|x|-2}+\sqrt{|x-3|}$
1.25 Let $f(x)=\frac{4 x}{x+2}$ and $g(x)=\frac{2 x}{x+4}$. Find $f(g(x))$.
1.26 Let $f(x)=a x^{2}+b x+c$ and $g(x)=a x^{2}-b x+c$. If $f(1)=g(1)+2$ and $f(2)=2$, find $g(2)$.

26

---

<!-- Page 27 -->

REVIEW PROBLEMS
1.27 At right is the graph of $y=f(x)$. Graph each of the following:
(a) $y=f(x-3)$
(b) $y=2 f(x)+1$
(c) $y=f(-x)$
(d) $y=f(2-x)$
(e) $\star \quad y=\frac{1}{2} f(2 x-1)+3$ Hints: 249
1.28 Suppose that $f(f(x))=g(f(x))$ for all real $x$. Must $f$ and $g$ be the same function?
1.29 For each of the following three graphs, determine if the graph could represent a function. If the graph can represent a function, then determine if the function has an inverse. If it does have an inverse, then graph the inverse.

(a)

(b)

(c)
1.30 Let $f(x, y, z)=\frac{x-z}{y-z}$. If $f(a, b, c)=1$, what is the value of $f(a, c, b)$ ?
1.31 Suppose that $f(x)=-x^{2}+b x+c$ and $g(x)=d x+e$, where $b, c, d$, and $e$ are real constants. Is it possible that $f(g(x))=x^{2}$ ? Why or why not?
1.32 Must the inverse of a linear function $f(x)=a x+b$, where $a \neq 0$, be a linear function?
1.33 Suppose that a function $f(x)$ is defined for all real $x$. How can you use the graph of $f(x)$ to produce the graph of $y=|f(x)|$ ?
1.34 Let $f(t)=\frac{t}{1-t}$, where $t \neq 1$. If $y=f(x)$, then $x$ can be expressed as which of the following:
$$f(1 / y),-f(y),-f(-y), f(-y), f(y) ?$$
(Source: AHSME)
1.35 The function $f$ defined by $f(x)=\frac{c x}{2 x+3}$ satisfies $f(f(x))=x$ for all real numbers $x$ except $-3 / 2$. Find $c$. (Source: AHSME)
1.36 Suppose that $f(x)$ has an inverse, $f^{-1}(x)$. Must $f^{-1}(2 x)$ be the inverse of $f(2 x)$ ? If so, prove it. If not, find an expression that is the inverse of $f(2 x)$.
1.37 The function $f(x)=x^{2}$ is not invertible. However, if we let $g(x)=\sqrt{x}$, then $f(g(x))=(\sqrt{x})^{2}=x$. So, why isn't $f$ invertible?

27

---

<!-- Page 28 -->

CHAPTER 1. FUNCTIONS REVIEW

Challenge Problems
1.38 Describe all constants $a$ and $b$ such that $f(x)=\frac{2 x+a}{b x-2}$ and $f(x)=f^{-1}(x)$ for all $x$ in the domain of $f$.
1.39 Suppose that a function $f(x)$ has domain $(-1,1)$. Find the domains of the following functions:
(a) $f(x+1)$
(b) $f(1 / x)$
(c) $f(\sqrt{x})$
(d) $\star f\left(\frac{x+1}{x-1}\right)$
1.40 Find the domain and range of the function $f(x)=\sqrt{2-x-x^{2}}$. Hints: 47
1.41 Let $f\left(x^{2}+1\right)=x^{4}+5 x^{2}+3$. What is $f\left(x^{2}-1\right)$ ? (Source: AMC 12) Hints: 184
1.42 Suppose that a function $f(x)$ is defined for all real $x$. How can we obtain the graph of $f(|x|)$ from the graph of $f(x)$ ? Hints: 271
1.43 If $f(f(x))=x$ for all $x$ for which $f(x)$ is defined and $f(0)=2003$, find all roots of the equation $f(x)=0$.
1.44 For which constants $a, b, c$, and $d$ does the function $f(x)=\frac{a x+b}{c x+d}$ have an inverse?
1.45 Suppose that $g(x)=f(x) f(|x|)$, where $f(x)$ is a function with $\mathbb{R}$ as its domain. Must all $x$-intercepts of the graph of $f$ be $x$-intercepts of the graph of $g$ ? Must all $x$-intercepts of the graph of $g$ be $x$-intercepts of the graph of $f$ ?
1.46 At right is the graph of $y=f(x)$. Draw the graph of $y=\frac{3}{2} f(2 x-2)-1$.
1.47 ★ The function $f$ defined by
$$f(x)=\frac{a x+b}{c x+d}$$
where $a, b, c$, and $d$ are nonzero real numbers, has the properties $f(19)=19, f(97)=97$, and $f(f(x))=x$ for all values of $x$ except $-d / c$. Find the unique number that is not in the range of $f$. (Source: AIME) Hints: 185

28

---

