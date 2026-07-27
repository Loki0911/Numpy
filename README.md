# NumPy for Data Science

This repository collects Jupyter Notebook examples and notes demonstrating how to use NumPy for data science tasks.

> Description: Numpy for datascience .

## Contents

- Jupyter Notebooks demonstrating NumPy usage (arrays, dtypes, indexing, slicing, linear algebra, broadcasting, random sampling, and performance tips)
- Example workflows for data preprocessing and numeric computation
- Practical recipes and notebook-driven tutorials

## Notebooks

| # | Notebook | Description |
|---|----------|-------------|
| 1 | `numpy_fundamentals.ipynb` | Core concepts: arrays, dtypes, indexing, slicing, and basic operations |
| 2 | `more_of_numpy.ipynb`     | Intermediate topics: broadcasting, reshaping, and mathematical functions |
| 3 | `numpy_tricks.ipynb`      | Handy tips and patterns for writing efficient, idiomatic NumPy code |

## Getting Started

Clone the repository and install the dependencies:

```bash
git clone https://github.com/Loki0911/Numpy.git
cd Numpy
python -m venv .venv
source .venv/bin/activate  # macOS / Linux
# .\.venv\Scripts\activate   # Windows
pip install --upgrade pip
pip install numpy jupyter
jupyter notebook
```

## Quick Example

Run this in a notebook cell:

```python
import numpy as np

# Create an array
arr = np.array([1, 2, 3, 4])

# Basic operations
print("Sum:", arr.sum())
print("Mean:", arr.mean())

# Broadcasting
arr2 = arr * 2
print(arr2)
```

## Requirements

- Python 3.8+
- NumPy
- Jupyter Notebook or JupyterLab

## Contributing

Contributions are welcome. Suggested workflow:

1. Fork the repository
2. Create a topic branch for your change
3. Add or update notebooks with clear explanations and outputs
4. Open a pull request and describe your changes

Please keep notebooks tidy (clear outputs when appropriate) and include explanatory comments and text cells.

## License

This repository does not yet include a license file. If you'd like to apply one, add a LICENSE file to the repository (e.g., MIT or Apache 2.0).

## Contact

Repository owner: @Loki0911
