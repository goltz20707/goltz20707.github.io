---
layout: post
title: Phi and the Fibonaccis
excerpt: In which I distract y'all with math.
date: 2015-10-02 14:40:56 -04:00
---
Yesterday was a bad, bad day for Roseburg, Oregon, and to a
only-slightly-lesser extent, for all of the United States.  To give
you something else to think about, here's some math.

You may have heard of the [Fibonacci
sequence](https://en.wikipedia.org/wiki/Fibonacci_number "Wikipedia
page on Fibonacci numbers").  It's a
sequence of integers where each entry in the sequence is the sum of
the previous two.  (To "seed" the sequence, the first and second
numbers in the sequence are both 1.)  So the sequence goes:

> 1, 1, 2, 3, 5, 8, 13, 21, ...

and so on.

In general, we designate the first number of the sequence as
\\(F_1\\), the second as \\(F_2\\), and so on.  So we can say that
\\(F_n = F_{n-1} + F_{n-2}\\).

We'll get back to Fibonacci.For now, let's talk about \\(\\phi\\)
(pronounced "fee").

\\(\\phi\\) is the [Golden
Ratio](https://en.wikipedia.org/wiki/Golden_ratio "Wikipedia page on
Golden Ratio"), supposedly the most pleasing ratio to
the eye.  (Seriously, it comes up a *lot* in architecture.)
Mathematically, \\(\\phi = \\frac{1+\\sqrt{5}}{2}\\).

Now, something interesting happens when you multiply \\(\\phi\\) by
itself:

\\[\\phi^2 = (\\frac{1+\\sqrt{5}}{2})^2\\]

\\[= (\\frac{1+\\sqrt{5}}{2})(\\frac{1+\\sqrt{5}}{2})\\]

\\[= \frac{1 + 2\\sqrt{5} + 5}{4}\\]

\\[= \frac{2 + 2\\sqrt{5}}{4} + \frac{4}{4}\\]

\\[= \\phi + 1]

So \\(\\phi^2 = \\phi + 1\\).  This means:

\\[\\phi^3 = \\phi(\\phi^2) = \\phi(\\phi + 1) = \\phi^2 + \\phi =
2\\phi + 1\\]

I'll spare you the remaining calculations, but you can show for
yourself that:

\\[\\phi^4 = 3\\phi + 2\\]

\\[\\phi^5 = 5\\phi + 3\\]

and so on.

Do those coefficients look familiar?  They all belong to the Fibonacci
sequence.  In fact, in general:

\\[\\phi^n = F_n\\phi + F_{n-1}\\]

In fact, if we define \\(F_0 = 0\\), then this holds for all \\(n \ge
0\\).

And one more connection: Let's look at the ratio of each number in the
Fibonacci sequence to the one just before it, starting with \(F_3\):

\\[\\frac{3}{2} = 1.5\\]
\\[\\frac{5}{3} = 1.66666...\\]
\\[\\frac{8}{5} = 1.6\\]
\\[\\frac{13}{8} = 1.625\\]
\\[\\frac{21}{13} = 1.61538...\\]
\\[\\frac{34}{21} = 1.61904...\\]

and so on.  Now, \\(\\phi = 1.61803...\\), and in fact the ratio of
adjacent Fibonacci numbers approaches \\(\\phi\\) as we go to
infinity.  Or in mathematical terms:

\\[\\lim_{n\\to\\infty} \\frac{F_n}{F_{n-1}} = \\phi\\]

Cool, huh?
