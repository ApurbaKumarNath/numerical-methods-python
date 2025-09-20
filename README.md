# Foundations of Numerical Methods in Python

This repository is a collection of Jupyter notebooks that explore and implement fundamental numerical methods from the ground up. Each notebook is designed to be a self-contained guide, combining the underlying theory with practical Python code.

The primary libraries used are **NumPy** for numerical operations, **Pandas** for data presentation, and **Matplotlib** for visualization.

## Philosophy

The goal of this project is to demonstrate a clear understanding of how these powerful algorithms work. Each topical notebook is structured in two parts:

1.  **Theory:** A detailed explanation of the mathematical concepts, formulas, and logic behind the method.
2.  **Implementation:** A from-scratch Python implementation of the algorithm, often accompanied by examples and visualizations to verify the results.

This approach aims to bridge the gap between theoretical knowledge and practical application.

## Repository Structure

The notebooks are organized by topic for easy navigation:

*   **`00_Foundations/`**: A primer on the core NumPy and Pandas features that are essential for numerical computing in Python.
*   **`01_Solving_Linear_Systems/`**: Implements and compares methods for solving systems of linear equations, including the Matrix Inverse method and Gaussian Elimination.
*   **`02_Solving_Nonlinear_Equations/`**: Explores iterative methods for finding roots of nonlinear equations, such as the Bisection and Fixed-Point Iteration methods.
*   **`03_Polynomial_Interpolation/`**: A deep dive into various techniques for fitting polynomials to data points, including Lagrange, Vandermonde (Matrix Method), Newton's Divided Difference, and Hermite interpolation.
*   **`04_Numerical_Differentiation/`**: Covers finite difference formulas (Forward, Backward, Central) and the powerful Richardson Extrapolation technique for improving accuracy.
*   **`data/`**: Contains any data files used by the notebooks.

## The Numerical Methods Cookbook

The `Numerical_Methods_Cookbook.ipynb` in the root directory serves as a practical, hands-on companion to the more theoretical notebooks. It is structured in two distinct phases to demonstrate both foundational understanding and flexible problem-solving.

1.  **Phase 1: Core Logic, Unwrapped**
    This section strips away the complexity of classes and functions to present the core algorithmic logic of each method in its purest form. Using only fundamental loops and NumPy array operations, these from-scratch implementations are perfect for understanding the step-by-step process of methods like Vandermonde, Lagrange, and Newton's Divided Difference without the overhead of object-oriented design.

2.  **Phase 2: Algorithmic Puzzles & Analytical Thinking**
    Moving beyond direct implementation, this phase treats numerical methods as problem-solving puzzles. It features modified versions of the standard algorithms, designed to test a more flexible and robust understanding. In some cases, a solution is provided, challenging the reader to deduce the original problem statement—simulating a reverse-engineering and analytical thinking exercise. This section showcases the ability to adapt foundational knowledge to non-standard scenarios.

## How to Use

1.  Clone the repository:
    ```bash
    git clone https://github.com/your-username/numerical-methods-python.git
    ```
2.  Navigate to the directory:
    ```bash
    cd numerical-methods-python
    ```
3.  Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```
4.  Launch Jupyter Notebook or JupyterLab to explore the files.
    ```bash
    jupyter notebook
    ```
