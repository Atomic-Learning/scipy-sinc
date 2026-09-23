[`scipy.special.sinc`](https://docs.scipy.org/doc/scipy/reference/generated/scipy.special.sinc.html) implements the sinc function:

$$
\mathrm{sinc}(x) = \frac{\sin(\pi x)}{\pi x}
$$

The function can be called on a single value:

```python
import scipy.special

x = 0.5
result = scipy.special.sinc(x)
print(result)
```

It can also be applied to an array of values:

```python
import numpy as np

x = np.array([0.5, 1.0, 1.5])
result = scipy.special.sinc(x)
print(result)
```