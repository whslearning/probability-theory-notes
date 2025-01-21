# Markov's inequality
https://www.youtube.com/watch?v=vjYanZ1nsZg

If $X \geq 0$ and $a \gt 0$,

$`Y =
  \begin{cases}
    0 & \quad \text{if } X \lt a\\
    a & \quad \text{if } X \geq a
  \end{cases}
`$
## A first course in probability
$`I =
  \begin{cases}
    1 & \quad \text{if } X \geq a\\
    0 & \quad \text{otherwise}
  \end{cases}
`$

then

$I \leq \frac{X}{a}$
# Chebyshev's inequality
https://www.youtube.com/watch?v=d5pnfFvggYk

Do not need $X \geq 0$
# Exponential random variable
https://www.youtube.com/watch?v=FOFtMqCxZt0

For $\lambda \gt 0$,

$`f(x) =
  \begin{cases}
    \lambda e^{-\lambda x} & \quad \text{if } x \geq 0\\
    0 & \quad \text{if } x \lt 0
  \end{cases}
`$

$P(X \geq a) = \int_a^\infty \lambda e^{-\lambda x} dx = e^{-\lambda a}$

$E[X] = \int_0^\infty x \cdot \lambda e^{-\lambda x} dx = \frac{1}\lambda$

$E[X^2] = \int_0^\infty x^2 \cdot \lambda e^{-\lambda x} dx = \frac{2}{\lambda^2}$

$\mathrm{Var}(X) = E[X^2] -(E[X])^2 = \frac{1}{\lambda^2}$
# Expectation
$E[X] = \sum_{x: p(x) > 0} x p(x)$

$E[aX + b] = \sum_{x: p(x) > 0} (ax + b)p(x) = aE[X] + b$

# Variance
$\mathrm{Var}(X) = E[(X - \mu)^2]$

$\mathrm{Var}(aX + b) = E[(aX + b - a\mu - b)^2] = a^2\mathrm{Var}(X)$
# Bernoulli
https://www.youtube.com/watch?v=J8L9kRGSvSY
# Geometric
https://www.youtube.com/watch?v=whbKmwMmB4s
# Markov chain
