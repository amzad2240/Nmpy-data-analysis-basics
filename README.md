# Nmpy-data-analysis-basics
NumPy practice exercises for data science and analytics
# NumPy Data Analysis Basics

This repository contains NumPy practice problems and solutions.

## Topics Covered
- Array creation
- Boolean indexing
- Filtering
- Matrix operations

## Example
```python
import numpy as np

arr = np.array([10, 15, 20, 25, 30])
result = arr[(arr > 20) & (arr % 5 == 0)]
print(result)
