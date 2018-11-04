# Calculus 1 : Math 1300 Notes
#### George Allison University of Colorado Boulder 2016

#### Problems with tangent and velocity  
Recall:  
   Point-Slope form:   **y - y**** 1 **** = m(x - x ****1**** )**
   Slope-Intercept form: **y = mx + b**
   Velocity = change in position / change in time = Δs/Δt

A secant line  is a line that goes through two points on a function

Understand, a secant line on a graph can roughly show the slope of the graph that it intersects.

The closer the two points of intersection are, the more accurate their slope is to the curve of f(x)

If the two points get infinitely close together, effectively making the secant line into a tangent line, then the slope of the tangent line will be equal to the slope of the point on the curve that it is touching. The slope of the tangent line, which equals the slope of that point on f(x) is called the derivative.

#### Understanding limits and limit laws

A limit is a value that approaches another value. Notation: *limx→af(x)=b*

[https://www.khanacademy.org/math/precalculus/limit-topic-precalc/limits-precalc/v/introduction-to-limits-hd](https://www.khanacademy.org/math/precalculus/limit-topic-precalc/limits-precalc/v/introduction-to-limits-hd)

**Some basic rules for calculating limits without a graph:**

1.
1.limx→ax=a
2.
2.When _c_ is a constant  limx→ac=c
3.
3.When _c_ is a constant  limx→acf(x) = _c_[limx→af(x)]
4.
4.limx→af(x)g(x)
 = limx→af(x)∗limx→ag(x)
 = limx→af(x)∗limx→ag(x)

**The Squeeze Theorem** - If x≤g(x)≤h(x)f when x is near a, and L = limx→af(x)=limx→ah(x) then limx→ag(x)=L  In other words, if two functions  squeeze together with a function in the middle, then the limits of all the functions at that point are the same.

In the above graph, limx→1f(x)=limx→1h(x), so by the squeeze theorem, limx→1g(x) is equivalent too.

Intermediate Value Theorem: If f(x) is continuous on (a,b) then there is a number N between f(a) and f(b) and there is a number C between a and b such that f(C) = N.

How to tell if a function is continuous

Some types of functions are always continuous (on their respective domains) such as:

**Polynomial functions, Rational functions, Root functions, Trig functions, Exponential functions, and Logarithmic functions.**

If f(x) and g(x) are continuous at a, then the following are continuous as well:

**f(x) + g(x)       f(x) - g(x)       f(x) \* g(x)      and     f(x) / g(x)    ** _if g(a) does not equal zero_

Functions that are not continuous have discontinuities. There are 3 types of discontinuities:

**Removable discontinuities** , which can either be where:

 f(x) is undefined but the limit exists, or

f(x) is defined but the limit does not exist

**Infinite discontinuities** where f(x) goes off to infinity

**Jump discontinuities** where the function &quot;jumps&quot; from one y value to another

Removable discontinuity at x = 2 where the limit exists, and at x = 6 where the limit does not exist.

Infinite discontinuity at x = 5, Jump discontinuity at x = 3

Derivatives and rates of change

The derivative is the slope of a line tangent to a function at a point a.

This formula shows the instantaneous rate of change of f at a: limx→aff(x)−f(a)x−a

The derivative as a function

The derivatives of each point on a function f(x) can be graphed as it&#39;s own function which is written as f &#39;(x)  which sounds like &quot;f prime of x&quot;

What f(x) could represent                                What f &#39;(x) would represent

| Quantity of something over time | The instantaneous rate of change of the quantity over time |
| --- | --- |
| Position / displacement of an object over time | The velocity (or speed) of the object |
| The cost of something over time | The [marginal cost](https://en.wikipedia.org/wiki/Marginal_cost) |

Some definitions:

        A functions f is **differentiable** at a if f &#39;(a) exists.

        If f is differentiable then it must be continuous (but not the other way around!)

On a graph, f is not differentiable at a if there is a corner or cusp, there is a vertical tangent line (i.e. xf(3)), or if there are any discontinuities.

Higher derivatives: f &quot;(x) is the derivative of f &#39;(x), f &#39;&#39;&#39;(x) is the derivative of f &quot;(x), etc…

Better ways to find the derivatives of functions

[Some universal rules:](https://www.mathsisfun.com/calculus/derivatives-rules.html)

-The derivative of a constant function is always zero

ddx(c)=0

-The derivative of x is always x

ddx(x)=x

- **The power rule**

ddx(xn)=nxn−1

For example: ddxx5=5x4,ddx2x3=6x2,ddxx1/2=12x−1/2

-The sum rule: ddx(f(x)+g(x))=ddxf(x)+ddxg(x)

-The derivative of ex=ex❑

- **The product rule:** ddx(f(x)∗g(x))=(f&#39;(x)∗g(x))+(f(x)∗g&#39;(x))

**-The quotient rule:** g(x)2f(x/g(x))=(f&#39;(x)∗g(x))−(f(x)∗g&#39;(x))/ddx

**-The Chain Rule:** If g is differentiable at x and f is differentiable at g(x) then the composition of (f∘g) ot f(g(x)) is differentiable at x.

**f(g(x))&#39; = f &#39;(g(x))\*g &#39;(x)**

**Original         \&gt;\&gt;\&gt;          Derivative                     Original         \&gt;\&gt;\&gt;               Derivative**

| tan(x) | sec(x) | csc(x) | -csc(x)cot(x) |
| --- | --- | --- | --- |
| sec(x) | sec(x)tan(x) | cot(x) | -csc2(x) |
| arctan(x) | 1/1+x2 | arccos(x) |
-1/❑
 |
| arcsin(x) |
1/❑
 | logax | 1/x ln(a) |
| ln(x) | 1/x |
ex❑


 |
ex


 |

Implicit Differentiation

Differentiation in respect to y (basically a variation of the chain rule)

For use in functions that cannot be written in y=x form

Two main steps:

1. Differentiate both sides in respect to x, when differentiating a term with y multiply it by dy/dx.
2. Solve for dy/dx

Linear Approximation

This is used when a function f(x) is not easy to calculate at a given point, but it is easy to calculate at a point near the given point. The tangent line is calculated and a point is taken from there instead of the actual function.

**Formula for linear approximation: l(x)=f &#39;(a)(x-a)+f(a)**

Example: estimate e0.1❑

Step 1. Get a &quot;ballpark&quot; guess. e0.1❑is close to e0 which equals 1. So e0.1is probably close to 1. Our a variable will be 0.

Step 2. Use the formula with the a variable. l(x) = ddxe0(x−0)+e0 = 1(x-0)+1

Step 3. Plug in the given x variable. 1((0.1)-0)+1 = 1.1

So e0.1 is about 1.1

\*\*\*Linear approximation can give a bad estimate if a small distance on the tangent line move a large distance on f(x)

[Related Rates](https://www.khanacademy.org/math/differential-calculus/derivative-applications/rates-of-change/v/falling-ladder-related-rates) \&lt;kahn academy link

For use in related simultaneous rates of change.

Recall: Pythagorean Theorem, Volume of a cone

First step to a related rates problem: draw a picture

Step 2: write an equation that includes the variable that you are solving for.

Step 3: get the equation in terms of one variable, possibly with the use of other equations

Step 4: substitute and solve.

Example:

Water is leaking at a rate of 12 ft3/min out of an inverted cone that is 50 feet tall and has a diameter of 20 feet. How fast is the water level falling when the depth of the water is 20 feet?

Step 1:Notice: the radius and height are proportional. Solving for dh/dt

Step 2: V = 13πr2h       1050=r2h2 so r2 = (0.2)h2

 dv/dt = -12

Step 3: V = π/75\*h3

Step 4: dv/dt = π/25\* h2    -12 = π/25\*(202)     dh/dt = -3/4π ft/min

The mean value theorem: If f(x) is defined and continuous on [a,b] and differentiable on (a,b) then there is at least one number c in the interval such that f(c) = the slope of f(x)

Extreme value theorem: If f(x) is defined and continuous on [a,b] then f must attain a maximum and a minimum.

Intermediate value theorem: If f(x) is defined and continuous on [a,b] and N is a number between f(a) and f(b) then there must be a number c within [a,b] such that f(c) = N

L&#39;Hospital&#39;s Rule

If there is an indeterminate form, the limit of derivative of the numerator over the derivative of the denominator equals the limit of the original function.

limf(x)g(x)=limf&#39;(x)g&#39;(x)

Simplify 0^0 1^inf and inf^inf by taking ln of both sides

If 0 \* inf then rewrite the equation

Get the limit in the form of  0/0 or inf/inf then use l&#39;hospital&#39;s rule to solve

Antiderivatives

Taking derivatives backwards

Definition of a definite integral as the limit of a Riemann sum

The limit of a Riemann sum equals the integral of the function.

limn→∞∑i=1nf(xi−1)Δx,whereΔx=b−an,=∫abf(x)dx

Evaluating definite integrals as the limit of a Riemann sum

Example: ∫03exdx=limn→∞∑i=1ne3i/n∗3n

Properties of definite integrals (if all are defined and continuous on [a,b]

Addition:The integral of a sum can be separated to the sum of integrals

Inner point: an integral can be broken up as the addition of two or more integrals

Odd functions always have an integral of 0, even functions are symmetrical so they are 2 x one side.

The Evaluation Theorem

(FTC part 2)

An integral form a,b of f(x) can be evaluated as F(b) - F(a) where F(x) is any antiderivative of f(x)

Indefinite Integrals

The antiderivative of a function is the indefinite integral.

Net Change Theorem

The integral of the rate of change is the net change ∫abF&#39;(x)dx=F(b)−F(a)

Area Accumulation

Derivatives of Integrals

The derivative of the integral equals the original function

U-Substitution

Substitute u with the innermost part of the function and solve for du then simplify and substitute the original function back in.

Area between curves and integration in respect to x and y

Either integrate in respect to x and use multiple integrals to find the area, or integrate in respect to y.

