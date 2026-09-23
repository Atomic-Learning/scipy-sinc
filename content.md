[`scipy.special.sinc`](https://docs.scipy.org/doc/scipy/reference/generated/scipy.special.sinc.html) implements the sinc function:

$$
\mathrm{sinc}(x) = \frac{\sin(\pi x)}{\pi x}
$$

where $x$ is measured in radians. The function can be called on a single value:

```py-cell
import scipy.special

x = 0.5
result = scipy.special.sinc(x)
print(result)
```

It can also be applied to an array of values:

```py-cell
import numpy as np
from scipy.special import sinc

x = np.array([0.5, 1.0, 1.5])
result = sinc(x)
print(result)
```