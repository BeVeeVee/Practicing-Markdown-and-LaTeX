# The Linear Approximation of the nth Root of a Number

```math
L(x) \approx f(a) + f`(a)(x-a)
```

This linear approximation function asserts the closest possible value to the nth root of a number.
To apply this to any nth root of a number, the formula can be written as follows:

```math
\sqrt[n]{x} \approx \sqrt[n]{S} + \frac{x - S}{n (\sqrt[n]{S})^{n-1}}
```
Where $\sqrt[n]{S}$ is the closest perfect root to $\sqrt[n]{x}$, which can be over or under.

Following this, an example is given: $\sqrt{42}$
Of this, the following variables can be assumed: $x = 42$, $n = 2$
For this example, two cases will be applied to follow the closest perfect square: $\sqrt{36}$ and $\sqrt{49}$

**Example 1**:

```math
\sqrt{42} \approx \sqrt{36} + \frac{42 - 36}{2 \sqrt{36}}\\
\sqrt{42} \approx 6 + \frac{6}{2(6)}\\
\sqrt{42} \approx 6 + \frac{6}{12}\\
\sqrt{42} \approx 6 \frac{1}{2}
```

**Example 2**:

```math
\sqrt{42} \approx \sqrt{49} + \frac{42 - 49}{2 \sqrt{49}}\\
\sqrt{42} \approx 7 - \frac{7}{2(7)}\\
\sqrt{42} \approx 7 - \frac{7}{14}\\
\sqrt{42} \approx 6 \frac{1}{2}
```

Both examples approximate to 6.5.
However, the real value states: $\sqrt{42} \approx 6.48$