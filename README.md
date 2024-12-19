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
# Exponential random variable
For $\lambda \gt 0$,

$`f(x) =
  \begin{cases}
    \lambda e^{-\lambda x} & \quad \text{if } x \geq 0\\
    0 & \quad \text{if } x \lt 0
  \end{cases}
`$

$`\begin{align}
P(X \geq a) &= \int_a^\infty \lambda e^{-\lambda x} dx\\
&= \lambda \int_a^\infty e^{-\lambda x} dx\\
&= \lambda \cdot \frac{-1}\lambda e^{-\lambda x}|_a^\infty\\
&= 0 - (-e^{-\lambda a})\\
& = e^{-\lambda a}
\end{align}
`$

$\mathrm{E}[X] = \int_0^\infty x \cdot \lambda e^{-\lambda x} dx = \frac{1}\lambda$

$\mathrm{E}[X^2] = \int_0^\infty x^2 \cdot \lambda e^{-\lambda x} dx = \frac{2}{\lambda^2}$

$\mathrm{Var}(X) = \mathrm{E}[X^2] -(\mathrm{E}[X])^2 = \frac{1}{\lambda^2}$
