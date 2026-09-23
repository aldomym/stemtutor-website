---
title: "The Simplest Derivation of the quadratic formula"
date: 2026-09-22
draft: false
params:
  math: true
---
<script type="text/javascript"
  src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML">
</script>
We all have heard of it. The quadratic formula. It is a very well known formula that allows us to solve any arbitrary quadratic equation by just substituting the values of the coefficients.
But where does it come from? How do we know it's correct? Here we will answer this question.
## The problem
We need to find an x that satisfies the equation
$$ax^2+bx+c=0.$$
for all coefficients a, b and c. The way in which we could do this is simple. What we do first is to multiply both sides by 4a. This way, we get
$$4a^2x^2+4abx+4ac=0$$
Now, subtract 4ac from both sides. We get now
$$4a^2x^2+4abx=-4ac$$
Now, add b² to both sides of the equation. Obtaining,
$$4a^2x^2+4abx+b^2=b^2-4ac$$
We notice something, the left hand side of this equation is a perfect square of the form
$$(x+y)^2=x^2+2xy+y^2$$
So that we can write this like (and you can check it)
$$(2ax+b)^2=b^2-4ac$$
Now, it's just a matter of doing basic manipulations. We now take the square root of both sides:
$$2ax+b=\pm\sqrt{b^2-4ac}$$
We now have to subtract b from both sides and divide by 2a. The result is the well known formula:
$$x=\frac{-b\pm\sqrt{b^2-4ac}}{2a}$$
Which is the famous and expected result. QED.
