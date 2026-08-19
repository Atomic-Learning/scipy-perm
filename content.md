[`scipy.special.perm`{.python}](https://docs.scipy.org/doc/scipy/reference/generated/scipy.special.perm.html) computes the number of permutations $P(n, k)$ — the number of ordered ways of choosing $k$ items from a pool of $n$:

$$
P(n, k) = \frac{n!}{(n-k)!}
$$

The first argument to `perm`{.python} is $n$ and the second is $k$.

```py-cell
from scipy.special import perm

print("n=3, k=2: ", perm(3, 2))
print("n=100, k=10: ", perm(100, 10))
```

The function returns a float.