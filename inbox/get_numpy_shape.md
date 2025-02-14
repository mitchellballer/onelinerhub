# Get array shape

```python
import numpy as np
arr = np.array([[1, 2], [3, 4], [5, 6]])
shape = arr.shape
```

- `import numpy as np` - load [lib:Numpy module](/python-numpy/how-to-install-python-numpy-lib) for Python
- `np.array` - declare Numpy array
- `[[1, 2], [3, 4], [5, 6]]` - sample matrix data
- `.shape` - attribute contains shape of a given array
- `shape` - will contain arr shape

## Example: 
```python
import numpy as np
arr = np.array([[1, 2], [3, 4], [5, 6]])
print( arr.shape )
```
```
(3,2)
```
```python
import numpy as np
arr = np.array([[[1, 2, 3], [4, 5, 6]],
                [[7, 8, 9], [10, 11, 12]],
                [[13, 14, 15], [16, 17, 18]]])
print( arr.shape )
```
```
(3, 2, 3)
```