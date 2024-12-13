To solve $ax^{2} + bx + c$ via factorisation,
You need to think of b as a sum of two numbers, $p$ and $q$. And $a\times c$ is a product of $p$ and $q$. 
In short, 
$b = p + q$, 
$a \times c = p \times q$
If we find $p$ and $q$, then we're set. The question values will be such that we will be able to find our $p$ and $q$. How will we find them? Simply by making guesses of course.

Lets take a proper example: $x^{2} + 4x + 3$. 
We need to find: $p + q = 4$, $p \times q = 3$. 
Trying values like 1,2,3,4 etc. we see that the pair (1,3) satisfies the formulas for $p$ and $q$. 
So with $p = 3$, $q = 1$, we can write the quadratic formula as:
$$x^{2} + (3 + 1)x + 3 \times 1$$
Now open the brackets,
$$x^{2} + 3x + x + 3 \times 1$$
Taking x common out from the first two terms,
$$x(x + 3) + x + 3$$
Taking 1 common out from last two terms,
$$x(x+3) + 1(x+3)$$
Taking $(x+3)$ common out,
$$(x+3)(x+1)$$
There we go, we have the final factorized form of the quadratic formula.
Just a recap, what is the meaning of factorized form: We convert a quadratic polynomial (of degree 2) into products of linear polynomials (degree 1). It's like how splitting 6 into 2 $\times$ 3, we are splitting $x^{2}+4x+3$ into $(x+3)(x+1)$



Explanation:
Why should we find $p$ and $q$ in such a manner? Why split b into a sum and ac into a product?
We need to find $p$ and $q$ so that we split $b$ into $p + q$ in the main quadratic equation. Also write $c$ as $\frac{pq}{a}$.
$$ax^{2} + px + qx + \frac{pq}{a}$$
$$a\left(x^{2} + \frac{p}{a}x + \frac{q}{a}x + \frac{p}{a}\times\frac{q}{a}\right)$$
$$a\left(x(x + \frac{p}{a}) + \frac{q}{a}(x + \frac{p}{a})\right)$$
$$a\left((x + \frac{q}{a})(x + \frac{p}{a})\right)$$