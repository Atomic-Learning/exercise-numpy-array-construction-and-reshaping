In the code cell below, do the following:

- Create a one-dimensional array with a series of three `bool`s of your choice
- Create a three-dimensional array with every value being equal to zero. This array should have a size of 4 in dimension 1, a size of 3 in dimension 2 and a size of 2 in dimension 3
- Create an array of the same dimension and size with the values 0-23 (inclusive)
- Create an array of the same dimension and size with the values every other value from 4-50 (inclusive)

```py-cell
import numpy as np

# Write your code here
```

# Sample Solution

Click below to see a sample solution.

>[!HIDDEN]
>
> Create an array containing three boolean values:
> 
>```py-cell
> import numpy as np
>
> bools = np.array([True, False, True])
> print(bools)
> ```
>
> Create the zero-filled 3-D array with shape `(4, 3, 2)`:
>
> ```py-cell
> a = np.zeros([4, 3, 2])
> print(a)
> ```
> 
> Create a 3-D array containing values from 0 to 23:
>
> ```py-cell
> b = np.arange(24).reshape([4, 3, 2])
> print(b)
> ```
>
> Create a 3-D array containing every other value from 4 to 50 (inclusive):
>
> ```py-cell
> c = np.arange(4, 51, 2).reshape([4, 3, 2])
> print(c)
> ```
>
> In the cell above, note any initial array is created using `np.arange()` and then reshaped into a 3-D array using the `.reshape()` method.
