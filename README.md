# Mathematics Engine

A collection of mathematical experiments, symbolic proofs, and visualizations built with Python and Jupyter Notebooks. This project explores mathematical concepts through symbolic computation, animated figures, and trajectory visualization.

## 📌 Overview

The **Mathematics Engine** project brings mathematical ideas to life using Python-based computational tools. It includes notebooks for exploring symbolic proofs, generating animated figures, and visualizing trajectories.

Whether you're learning mathematical programming, experimenting with symbolic mathematics, or exploring computational visualizations, this repository provides a starting point for further experimentation.

## ✨ Features

- **Symbolic Mathematics:** Explore mathematical expressions and proofs using SymPy.
- **Animated Figures:** Experiment with animated mathematical figures and visual representations.
- **Trajectory Visualization:** Visualize trajectories and mathematical motion.
- **Interactive Notebooks:** Run and modify Python code directly in Jupyter Notebook.
- **Extensible Experiments:** Build upon existing notebooks to explore additional mathematical concepts.

## 📂 Project Structure

```text
Mathematics-engine/
├── .ipynb_checkpoints/
├── Animated_Figures.ipynb
├── Symbolic_Proof_using_SymPy.ipynb
├── animating_trajectory.ipynb
└── README.md
```

### Notebook Descriptions

| Notebook | Description |
|---|---|
| `Animated_Figures.ipynb` | Experiments with animated mathematical figures. |
| `Symbolic_Proof_using_SymPy.ipynb` | Explores symbolic mathematics and mathematical proofs using SymPy. |
| `animating_trajectory.ipynb` | Explores trajectory animation and visualization. |

## 🛠️ Technologies Used

- **Python** — Core programming language.
- **Jupyter Notebook** — Interactive computational environment.
- **SymPy** — Symbolic mathematics and algebraic computation.
- **Matplotlib** — Mathematical plotting and visualization.

Additional dependencies may be required depending on the notebook.

## 🚀 Getting Started

### Prerequisites

Make sure you have Python 3 installed on your computer.

You will also need Git to clone the repository.

### 1. Clone the Repository

```bash
git clone https://github.com/Ibrahist/Mathematics-engine.git
```

### 2. Navigate to the Project Directory

```bash
cd Mathematics-engine
```

### 3. Create a Virtual Environment

```bash
python -m venv .venv
```

Activate the environment:

**Windows**

```bash
.venv\Scripts\activate
```

**Linux / macOS**

```bash
source .venv/bin/activate
```

### 4. Install Dependencies

```bash
python -m pip install jupyter sympy matplotlib numpy
```

These are suggested starting dependencies. Install any additional packages required by individual notebooks.

### 5. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open a notebook in your browser and execute its cells to explore the experiments.

## 💻 Example: Symbolic Mathematics with SymPy

The following example demonstrates symbolic computation using SymPy:

```python
import sympy as sp

x = sp.symbols("x")

# Define a mathematical expression
expression = x**2 - 5*x + 6

# Factor the expression
factored = sp.factor(expression)

# Solve the equation
solutions = sp.solve(expression, x)

print("Expression:", expression)
print("Factored form:", factored)
print("Solutions:", solutions)
```

**Output:**

```text
Expression: x**2 - 5*x + 6
Factored form: (x - 2)*(x - 3)
Solutions: [2, 3]
```

## 📖 Learning Objectives

This project can be used to explore:

- Symbolic algebra and equation solving.
- Mathematical proofs and computational reasoning.
- Animated mathematical representations.
- Trajectory plotting and visualization.
- Scientific programming with Python.
- Interactive experimentation with Jupyter Notebooks.

## 🔮 Future Improvements

Potential directions for expanding the project include:

- Adding more mathematical formulas and symbolic proofs.
- Improving interactive mathematical visualizations.
- Introducing more animation examples.
- Adding numerical methods and equation solvers.
- Organizing experiments into dedicated mathematical topics.
- Including automated tests for reusable computational functions.

## 🤝 Contributing

Contributions, suggestions, and improvements are welcome.

1. Fork the repository.
2. Create a feature branch.
3. Add or improve a notebook.
4. Test your changes.
5. Submit a pull request.

For significant changes, consider opening an issue first to discuss the proposed improvement.

## 👨‍💻 Author

**Ibrahist**

GitHub: [@Ibrahist](https://github.com/Ibrahist)

## 📄 License

No license file is currently listed in the repository. Add an appropriate `LICENSE` file if you intend to distribute the project under an open-source license.

---

**Explore mathematics. Experiment with code. Visualize ideas.**
