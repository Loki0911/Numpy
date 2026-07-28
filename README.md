# NumPy for Data Science

A comprehensive collection of Jupyter Notebooks and resources for learning and mastering NumPy for data science applications.

> **Description:** NumPy for datascience - Learn fundamental to advanced NumPy concepts with practical examples and exercises.

---

## 📋 Contents

This repository includes:

- **3 Core Jupyter Notebooks** - Progressive learning from fundamentals to advanced techniques
- **NumPy Interview Questions** - PDF resource with common interview questions
- **100 NumPy Exercises** - Hands-on practice problems directory
- **Practical Tutorials** - Real-world examples for data preprocessing and numeric computation

---

## 📚 Notebooks

| # | Notebook | Description |
|---|----------|-------------|
| 1 | `1. numpy_fundamentals.ipynb` | Core concepts: arrays, dtypes, indexing, slicing, and basic operations |
| 2 | `2. more of numpy.ipynb`     | Intermediate & advanced topics: broadcasting, reshaping, linear algebra, and mathematical functions |
| 3 | `3. numpy_tricks.ipynb`      | Performance tips and patterns for writing efficient, idiomatic NumPy code |

---

## 📝 Additional Resources

- **`Numpy interview questions.pdf`** - Interview prep guide with common NumPy questions
- **`numpy_100_excercises/`** - Directory containing 100 practice exercises for hands-on learning

---

## 🚀 Getting Started

### Prerequisites
- Python 3.8 or higher
- pip or conda

### Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Loki0911/Numpy.git
   cd Numpy
   ```

2. **Create and activate a virtual environment:**
   ```bash
   python -m venv .venv
   
   # On macOS / Linux
   source .venv/bin/activate
   
   # On Windows
   .\.venv\Scripts\activate
   ```

3. **Install dependencies:**
   ```bash
   pip install --upgrade pip
   pip install numpy jupyter matplotlib scipy pandas
   ```

4. **Launch Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```

---

## 💡 Quick Example

Run this in a Jupyter notebook cell:

```python
import numpy as np

# Create an array
arr = np.array([1, 2, 3, 4, 5])

# Basic statistics
print("Sum:", arr.sum())
print("Mean:", arr.mean())
print("Std Dev:", arr.std())

# Broadcasting
arr2 = arr * 2
print("Doubled:", arr2)

# 2D Operations
matrix = np.arange(12).reshape(3, 4)
print("\nMatrix:\n", matrix)
print("Matrix Sum:", matrix.sum(axis=1))
```

---

## 📦 Requirements

- **Python:** 3.8+
- **Core Libraries:**
  - NumPy (latest)
  - Jupyter Notebook or JupyterLab
  - Matplotlib (optional, for visualizations)
  - Pandas (optional, for data analysis)
  - SciPy (optional, for scientific computing)

---

## 🎯 Learning Path

1. Start with `1. numpy_fundamentals.ipynb` to understand NumPy basics
2. Progress to `2. more of numpy.ipynb` for intermediate concepts
3. Explore `3. numpy_tricks.ipynb` for optimization and best practices
4. Practice with exercises in `numpy_100_excercises/`
5. Review `Numpy interview questions.pdf` for assessment

---

## 🤝 Contributing

Contributions are welcome! Here's how to contribute:

1. **Fork** the repository
2. **Create a branch** for your feature or improvement (`git checkout -b feature/your-feature`)
3. **Add or update** notebooks with clear explanations, examples, and outputs
4. **Commit** your changes (`git commit -m "Add descriptive message"`)
5. **Push** to your branch (`git push origin feature/your-feature`)
6. **Open a Pull Request** with a clear description of changes

### Guidelines
- Keep notebooks well-organized with markdown cells for documentation
- Include clear output examples for all code cells
- Add explanatory text cells to guide readers
- Follow NumPy naming conventions and best practices

---

## 📖 Topics Covered

- **Fundamentals:** Arrays, data types, indexing, slicing
- **Operations:** Broadcasting, reshaping, concatenation
- **Math Functions:** Linear algebra, statistical functions, trigonometric functions
- **Performance:** Memory efficiency, vectorization, advanced indexing
- **Practical Applications:** Data preprocessing, numeric computation, data analysis

---

## 📄 License

This repository does not yet include a license file. Consider adding one (MIT or Apache 2.0 are popular choices for educational content).

To add a license:
1. Create a `LICENSE` file in the repository root
2. Choose from [opensource.org](https://opensource.org/licenses/)

---

## 👤 About

**Repository Owner:** [@Loki0911](https://github.com/Loki0911)  
**Created:** July 2026  
**Last Updated:** July 2026

---

## 🔗 Related Resources

- [NumPy Official Documentation](https://numpy.org/doc/)
- [NumPy GitHub Repository](https://github.com/numpy/numpy)
- [Data Science with Python](https://www.python.org/)

---

## ❓ FAQ

**Q: Do I need prior Python experience?**  
A: Basic Python knowledge is helpful, but the notebooks start from fundamentals.

**Q: Can I use these materials for teaching?**  
A: Yes! Feel free to use and adapt these materials for educational purposes.

**Q: Where should I start?**  
A: Begin with `1. numpy_fundamentals.ipynb` for the best learning experience.

---

**Happy Learning! 🎓**
