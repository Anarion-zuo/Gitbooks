# Probability

## Universality of Uniform Distribution

Let $F$ be a continuous strictly increasing CDF. If let:
$$
X=F^{-1}(u),u\sim Unif(0,1)
$$
We can create a random variable $X$ following distribution $F$. It is easier to generate a uniform distribution than most of the others.

Generally, for any linear form of $u$, such as $a+bu$, the property of uniform still holds.

The other way of writing this is: if $X\sim F$, then $F(X)$ is going to be normally distributed between $0$ and $1$.

## Normal Distribution

PDF of $N(0,1)$:
$$
\phi(z)=\frac{1}{\sqrt{2\pi}}e^{-\frac{z^2}{2}}
$$
Generally:
$$
X=\mu+\sigma z,\sigma>0,\mu\in\R,X\sim N(\mu,\sigma^2)
$$
