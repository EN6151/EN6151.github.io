---
layout: post
author: Cian Conway
title: Complex Numbers in the Leaving Cert
permalink: /blog/:title/
wordcount: 1258
readtime: 6m 16s
excerpt_separator: <!--more-->
---

## Background Knowledge

Before jumping into this article it should be assumed that you have a decent grasp on trigonometry in particular sin cos and tan, and Pythagoras theorem will benefit you greatly in studying complex numbers. Basic understanding of coordinate geometry and plotting points on a graph is also useful.

This topic can often leave students a bit confused about why we are doing certain things so a visual representation of every step in this process is critical to understanding what is going on.

<!--more-->

## What is a complex number?

A complex number is a number which consists of a real part and an imaginary part.

What does imaginary mean in this context? We define imaginary numbers using the letter i (this can also sometimes be represented by j but in the Leaving Cert we use i).

What makes the i imaginary is we let it be equal to the square root of minus one.
`i = sqrt(-1)`
You can type the square root of minus one into your calculator but you will get an error because this number doesn’t exist. Why?

When we square a number it becomes positive. For example `5²` is `25` and `(-5)²` is also `25`. This is because when we square a number we are multiplying it by itself, so it will either be a plus multiplied by a plus or a minus multiplied by a minus resulting in a positive number. So to look for the square root of a negative number makes no sense as there are no two numbers that are the same which can multiply together to give us a negative number.

In the next section we will talk about how we represent these real and imaginary parts together into a complex number.

## Argand Diagram

### Cartesian Form

The standard way we write complex numbers is in Cartesian form, also called rectangular form. When writing a complex number we will write it in the form `a +bi` where a is the real part and b is the imaginary part. We then plot this on our diagram, we are often asked to plot these on a diagram in a part (a) in the leaving cert complex numbers question.

It will usually be written as `z = a +bi` where z is our complex number as a whole.

### The diagram

When dealing with complex numbers we use what is called an Argand diagram. This is basically an x-y axis where the x-axis represents our real component and the y-axis represents the imaginary component of our complex number `a +bi` .

![Argand Diagram](/images/complex-numbers/argand.png){:class="img-responsive"}

This is not the only way of representing complex numbers and during the leaving cert you will be asked at times to convert between these methods of representing complex numbers. We talk about these below.

## Modulus

The modulus is the length of our line from the origin (0,0) to our plotted point on our Argand diagram. We see the modulus as being represented by two vertical lines like this `|z|`. So during your leaving cert if you are asked to find `|z|` know that it means the modulus.

The formula for the modulus is `sqrt(a²+b²)` To see why this is our formula take a look at the diagrams below. This is where our trigonometry knowledge becomes useful. We construct a right angled triangle with the modulus representing our hypotenuse and the x axis being one of the sides of the triangle, by joining the plotted point with the x axis perpendicularly we have a right angled triangle.

Now if we think of how we calculate the length of the hypotenuse we use Pythagoras theorem. That is `c² = a² + b²` where c is the hypotenuse. Subbing in our real value for a and our imaginary value for be we get
`c = sqrt(a² + b²)`, our formula for the modulus. This isn’t the only place we will use trigonometry so remember that right angled triangle as we move on from here.

## Polar Form

Polar form is another way of representing a complex number. This method gives instead of pointing us to a point in a coordinate grid gives us the magnitude (modulus) and an angle theta `θ`. Some understanding of the unit circle is helpful if you really want to get into the specifics of this formula but we will touch on that in another post.

The complex number represented in polar form is in the form of:  
`z = r(cosθ + isinθ)`
Where z is the complex number, r is the modulus and theta is our angle (or argument) which we will discuss next.

![Argument](/images/complex-numbers/argument.png){:class="img-responsive"}

### Argument

We call the angle `θ` the argument. It is important to note that the argument is measured from the positive sense of the x-axis. What does this mean? It means that we measure it from the positive side of the x-axis in an anti clockwise direction shown below.

When calculating this argument it is often very helpful to draw our complex number on the argand diagram first if we can. The reason for this is we will be using trigonometry to determine the angle.

To do this we are primarily going to be using tan because we will know both the x and y coordinates for any point on the Argand diagram in Cartesian form. The imaginary coordinate will be our vertical line and the real component will be the horizontal. This is shown more clearly in the diagram below.

![Tan theta](/images/complex-numbers/sohcahtoa.png){:class="img-responsive"}

It is always useful to draw out these diagrams when you are calculating the argument `θ`, as sometimes we will have to calculate a different angle which we call `α` (alpha). This is because the angle we want to calculate is from the positive sense of the x-axis anticlockwise so in some cases we need to calculate a different angle and add or take it away from 180 or 360. Example of this is shown below.

![Tan alpha](/images/complex-numbers/alpha.png){:class="img-responsive"}

When converting from polar form back to Cartesian form we use the below formulae.

`x = rcosθ` for the real part
`y = rsinθ` for the imaginary part (don’t forget to add the i in after.

## Multiplying Complex Numbers

When we multiply complex numbers it is relatively straightforward. We simply multiply the same as we would any regular algebraic expression however when we encounter an `i²` we change this to be `-1`.

Things become a bit trickier when we are dealing with division of complex numbers. When doing this we must multiply by the conjugate of the complex number. The conjugate is just the denominator with the sign of the imaginary component changed. So when we multiply by this we are multiplying by the conjugate over itself.

The reason why we do this is because multiplying by the conjugate over itself is effectively the same as multiplying by one as anything over itself is equal to one. Additionally this will cause the imaginary number on the denominator (bottom of our sum) to disappear leaving us with just a real number on the bottom.

An example of this can be seen below.

![Argument](/images/complex-numbers/conjugate.png){:class="img-responsive"}

## Conclusion

That has been out introduction to complex numbers, you can expect more content over the coming weeks to prepare students for the leaving certificate examination in mathematics.

We will also begin producing a series on common junior cert questions and topics in September. If you have any questions regarding any of the mathematics discussed here please reach out and we would be happy to help.
