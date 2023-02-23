---
layout: default
title: "Differentiation Notes"
---
# Differentiation Notes

Essentially, calculus is about finding the gradient of stuff. But, some equations don’t really have simple gradients like linear equations.

> $y=mx +c$ , where m is the gradient

Instead, lets look at the equation $y = x^2$:

<img src="https://edsobsidiannotes.netlify.app/assets/Pasted image 20220422210133.png" style="width:100%;height:100%">

Looking at points 0 to 1, the y values increase by 1 (1 – 0). However, from 1 to 2 it increases by 3 (4-1). This means we cannot use a simple number to describe the gradient of this function.

Now, let’s look at the function where x = 1. We’re looking for the gradient of this point, and:

$Gradient = \frac{Rise}{Run}$

But to use that equation, we need 2 points.

Let’s choose point (4,2).

The gradient using this point is: $\frac{4-1}{2-1}$ = 3.

That’s good, but this point is really far away (relatively). If we’re looking for the gradient at a **particular point,** the closer we are to the point the better.

What about (1.05, 1.1025)?

The gradient then becomes 2.05.

That’s very close to 2, but we can’t exactly infer right now. What about (1.001, 1.002001)?

The gradient is now 2.001.

Well, it looks pretty clear that the gradient at 1 is 2.

How would we describe this using fancy words?

Let’s say P is (1, 1), and Q is some point on this function.

We’d say that the **limit** of the gradient of the line (or chord) PQ (now we’re treating this line as a linear equation), as Q approaches P, appears to be 2.

We call this gradient the **instantaneous rate of change**. (instantaneous meaning within a certain instance, rate of change being another word for gradient)

Great, we’ve stated that the gradient of a certain point is two. But wait a second. How can a point have a gradient, if it’s a stationary point?

Well, it can’t. But think of it like this.

Imagine we have a graph of a car’s distance travelled. The gradient of a point is essentially the velocity of this car. Velocity will increase when the distance function is steeper.

But, if we were to take a picture of the car in motion, then how could you tell that its moving?

You couldn’t with one image of the car, but with 2 at certain points, so you could compare the distance and time taken.

This makes it weird to think about velocity as a graph. If we were to isolate a single point on this graph of velocity, it wouldn’t make much sense because to compute velocity we need multiple points.

Now, let’s think about the speedometer of the car as it travels. Perhaps the speedometer is measuring a small amount of time, analysing the difference in distance the car travels between 20 and 20.0001 seconds into its journey.

Therefore, in the real world, this paradox of **instantaneous** rates of change is circumvented, by using a roughly similar approach that we used for the $y=x^2$ problem.

Thus, we should think of this rate of change not as **instantaneous,** but measuring a rate of change **over a _very_ small time**.

Now, lets look at the $y=x^2$ problem again.

<img src="https://edsobsidiannotes.netlify.app/assets/nice triangle.png" style="width:100%;height:100%">

Lets say the black and blue lines represent a **really** small change in value. In this case, we'll let the length of the black lines = h (run), and we'll think about the blue lines later.

We'll say the bottom left point (indicated as 1,1) is actually x, just the x in $f(x)$, an x value on the x axis. That means the bottom right point is x + h.

The point at the very top of this triangle is $f(x+h)$, where $f(x)=x^2$. This is because $f(x)$ is the output when given x, the x value in this case is x + h.

The blue line would be equal to the value of the point at the top, minus the value of $f(x)$, or the point that we’re basing this off. i.e. The top right point minus the bottom left point. This makes the **rise** of the gradient $f(x+h) - f(x)$. (the difference between the 2 points)

Now, the gradient formula is $\frac{Rise}{Run}$. Remember the run is the black line, which is essentially h. Therefore, The gradient of these points that we’re chosen is:

$\frac{f(x+h)-f(x)}{h}$

Remember that h is just some arbitrary value that we're adding to a point (variable) to create 2 points.

Now, we’ve said before that as the distance between these two points (on the x axis), we get closer to the gradient of the point.

Likewise, we describe this as a **limit**, where something approaches zero (in this case), which would be the distance between the two points.

Now, we can write the formula as:

$\displaystyle \lim_{h \to 0} \frac{f(x+h)-f(x)}{h}$

Does this work with our function, $f(x)=x^2$?

Let’s substitute our function into this formula.

$\displaystyle \lim_{h \to 0} \frac{x^2+2hx+h^2-x^2}{h}$

$\displaystyle \lim_{h \to 0} \frac{2hx+h^2}{h}$

$\displaystyle \lim_{h \to 0} 2x+h$

Now, at this point you may realise something from chapter 3 of Sadler 1. If h is approaching 0, doesn’t that mean we can’t divide it?

Well, yes but that’s exactly why we use limits in the first place! It essentially allows us to choose when to actually acknowledge that h = 0.

Just kidding. Remember, we’re still looking for the rate of change **over a small time**. h may approach 0, but by definition of limits (dont search that up), It’s not exactly 0 until we need it to.

So, since $h \to 0$, $(2x+h) \to 2x$, where h becomes 0.

Thus, instead of keeping the h part, we just state the gradient without the h.

Knowing that the “gradient” of the graph $y=x^2$ is $2x$, does this follow what we’ve found out before?

Well, what about the point (1,1)? Well, the x in the gradient equation is equal to the x in the function (and the point), so:

At the point (1,1),

Gradient $= 2 \times 1$
				  $= 2$

Just as we’ve found before!