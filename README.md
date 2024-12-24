# NumPy Examples for Learning

This repository contains various **NumPy** examples to help you learn and practice array manipulation, mathematics, and operations using NumPy, a powerful library for numerical computing in Python. Follow the examples to understand how to work with arrays, perform mathematical operations, and more.

## Table of Contents

- [Installation Instructions](https://www.youtube.com/watch?v=Y21OR1OPC9A)



## Installation Instructions

To get started with these examples, you need to set up a virtual environment and install the required packages. Follow these steps:

### Step 1: Create a Virtual Environment

1. Install `virtualenv` if you don't have it installed already:
   ```bash
   pip install virtualenv
   ```

2. Create a virtual environment:
   ```bash
   virtualenv venv
   ```

3. Activate the virtual environment:
   - **Windows**:
     ```bash
     venv\Scripts\activate
     ```
   - **Mac/Linux**:
     ```bash
     source venv/bin/activate
     ```

### Step 2: Install Required Libraries

1. Install **Jupyter Notebook** and **NumPy** by running:
   ```bash
   pip install jupyter numpy
   ```

2. To start Jupyter Notebook, run:
   ```bash
   jupyter notebook
   ```

   This will open Jupyter in your browser, where you can interact with the Python code.

### Step 3: Start Coding

1. After starting the Jupyter notebook, you can open the notebook files in the directory and run them one by one.

2. You can also copy and paste the code in new Jupyter notebooks to practice and experiment.

---

## Examples

Here are the examples you can explore:

### Example 1: Creating a NumPy Array
```python
import numpy as np
myarr = np.array([23, 63, 6, 2, 55])
myarr
```

### Example 2: Specifying Data Type of an Array
```python
import numpy as np
myarr = np.array([23, 63, 6, 2, 55], np.int64)
myarr
```

### Example 3: Array Shape
```python
import numpy as np
myarr = np.array([23, 63, 6, 2, 55])
myarr.shape
```

### Example 4: Array Data Type
```python
import numpy as np
myarr = np.array([23, 63, 6, 2, 55])
myarr.dtype
```

### Example 5: Modifying Array Elements
```python
import numpy as np
myarr = np.array([23, 63, 6, 2, 55])
myarr[2] = 54
myarr
```

### Example 6: Modifying 2D Array
```python
import numpy as np
myarr = np.array([[23, 63, 6, 2, 55]])
myarr[0, 2] = 54
myarr
```

### Example 7: Creating a 2D Array
```python
import numpy as np
list = np.array([[1, 2, 3], [4, 5, 6], [7, 8, 9]])
list
```

### Example 8: Array Data Type of 2D Array
```python
import numpy as np
list = np.array([[1, 2, 3], [4, 5, 6], [7, 8, 9]])
list.dtype
```

### Example 9: Array Shape of 2D Array
```python
import numpy as np
list = np.array([[1, 2, 3], [4, 5, 6], [7, 8, 9]])
list.shape
```

### Example 10: Array Size
```python
import numpy as np
list = np.array([[1, 2, 3], [4, 5, 6], [7, 8, 9]])
list.size
```

### Example 11: Create an Array of Zeros
```python
import numpy as np
zero = np.zeros((2, 5))
zero
```

### Example 12: Create an Empty Array
```python
import numpy as np
emp = np.empty((2, 5))
emp
```

### Example 13: Using linspace
```python
import numpy as np
lis = np.linspace(2, 3)
empl = np.empty_like(lis)
```

### Example 14: Identity Matrix
```python
import numpy as np
iden = np.identity(5)
iden
```

### Example 15: Using arange and reshape
```python
import numpy as np
arr = np.arange(99)
arr.reshape(3, 33)
```

### Example 16: Array Operations
```python
import numpy as np
li = np.array([[1, 2, 3], [4, 5, 6], [7, 8, 9]])
li.sum(axis=0)
li.sum(axis=1)
```

### Example 17: Transpose an Array
```python
import numpy as np
li = np.array([[1, 2, 3], [4, 5, 6], [7, 8, 9]])
li.T
```

### Example 18: Iterating Over Flat Arrays
```python
import numpy as np
li = np.array([[1, 2, 3], [4, 5, 6], [7, 8, 9]])
for item in li.flat:
    print(item)
```

### Example 19: Array Dimensions
```python
import numpy as np
li = np.array([[1, 2, 3], [4, 5, 6], [7, 8, 9]])
li.ndim
```

### Example 20: Array Memory Size
```python
import numpy as np
li = np.array([[1, 2, 3], [4, 5, 6], [7, 8, 9]])
li.nbytes
```

### Example 21: Non-zero Elements
```python
import numpy as np
li = np.array([[1, 2, 3], [4, 5, 6], [7, 8, 9]])
li.argmax()
li.argmin()
li.argsort()
li.argmax(axis=0)
li.argmax(axis=1)
```

### Example 22: Array Operations (Element-wise)
```python
import numpy as np
li1 = np.array([[1, 2, 3], [4, 5, 6], [7, 8, 9]])
li2 = np.array([[1, 2, 3], [4, 5, 6], [7, 8, 9]])
li1 + li2
li1 * li2
np.sqrt(li1)
li1.sum()
```

### Example 23: Size of Array Elements
```python
import numpy as np
li1 = [[1, 2, 3], [4, 5, 6], [7, 8, 9]]
li2 = np.array(li1)
sys.getsizeof(1) * len(li1)
li2.itemsize * li2.size
```

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
