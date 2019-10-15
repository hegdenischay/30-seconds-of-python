---
title: factorial_using_gamma
tags: math,beginner
---

Uses the `math.gamma` function (from the Python 3 `math` module) to compute the factorial of a number.
This approach is generally a bit faster than using a recursive function. 
`factorial_using_gamma` takes only the integer part of the argument passed to it, in order to closely resemble the recursive factorial function.

```py
import math
def factorial_using_gamma_function(fact):
     return math.gamma(int(fact+1))
```

```py
factorial_using_gamma_function(4) #24.0
```
