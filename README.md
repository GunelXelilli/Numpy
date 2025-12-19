# NumPy Basics and Examples

This repository contains examples and practice scripts for learning **NumPy**, a powerful Python library for numerical computing.

## Table of Contents

- [About NumPy](https://github.com/GunelXelilli/Numpy/blob/main/README.md#about-numpy)  
- [Installation](https://github.com/GunelXelilli/Numpy/blob/main/README.md#installation)  
- [Usage](https://github.com/GunelXelilli/Numpy/blob/main/README.md#usage)  
- [Examples](https://github.com/GunelXelilli/Numpy/blob/main/README.md#examples)  
- [Contributing](https://github.com/GunelXelilli/Numpy/blob/main/README.md#contributing)  
- [License](https://github.com/GunelXelilli/Numpy/blob/main/README.md#license)  

## About NumPy

NumPy (Numerical Python) is a library for Python that provides:

- Fast and efficient arrays (`ndarray`)  
- Mathematical operations on arrays (matrix multiplication, statistics, etc.)  
- Linear algebra, Fourier transform, and random number capabilities  

It is widely used in **data science, machine learning, and scientific computing**.

## Installation

You can install NumPy using `pip`:

```bash
pip install numpy
```
Or using conda: 
```
conda install numpy
```
## Usage

To use the scripts in this repository:

Import NumPy in your Python scripts:
```
import numpy as np
```
Create arrays:

# 1D array
```
arr1 = np.array([1, 2, 3])
```
# 2D array
```
arr2 = np.array([[1, 2], [3, 4]])
```
## Examples

- **Matrix Operations:** Transpose, multiplication, determinant  
- **Statistics:** Mean, median, standard deviation  
- **Random Numbers:** Generate random arrays, permutations  
- **Indexing and Slicing:** Access elements, rows, and columns
   
Perform operations:

# Addition
```
arr_sum = arr1 + arr1
```

# Matrix multiplication
```
result = arr2 @ arr2.T
```


# Mean
```
mean_val = np.mean(arr2)
```

## Contributing

Contributions are welcome! Feel free to:

- Open an issue  
- Submit a pull request with new examples or improvements  

## License

This project is licensed under the MIT License.
