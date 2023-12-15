# Emerging Technologies

Welcome to my repository for the module **Emerging Technologies**. Here, you will find two Jupyter notebooks containing the tasks I completed during the semester and the final project.

## Getting Started

To run the notebooks locally or explore the code, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/emerging-technologies.git
    ```

2. Navigate to the project directory:
    ```bash
    cd emerging-technologies
    ```

3. Install the required packages if you haven't already. You can use Anaconda, a popular package manager and environment manager, to create a virtual environment and install the necessary packages.

    - **Anaconda Installation (if not installed):**

      If you don't have Anaconda installed, you can download it from the official website: [Anaconda Downloads](https://www.anaconda.com/products/distribution)

    - **Create a Virtual Environment (optional but recommended):**

      You can create a virtual environment to isolate your project dependencies. Replace `myenv` with the name you want for your environment.

      ```bash
      conda create --name myenv python=3.8
      ```

      Activate the virtual environment:

      - **On Windows:**

        ```bash
        conda activate myenv
        ```

      - **On macOS and Linux:**

        ```bash
        source activate myenv
        ```

    - **Install Required Packages (Qiskit, NumPy):**

      With the virtual environment activated, you can install the required packages using pip:

      ```bash
      pip install qiskit numpy
      ```

4. Open Jupyter notebooks:

    ```bash
    jupyter notebook
    ```

## Table of Contents

1. [Tasks](#tasks)
    - The Collatz Conjecture Problem
    - Approximating Square Roots
    - Counting Possible Functions
    - Matrix Multiplication
  
2. [Project](#project)

---

## [Tasks](/tasks.ipynb)

### Task 1: The Collatz Conjecture Problem
*The Collatz Conjectuce Problem[[1]](https://www.quantamagazine.org/why-mathematicians-still-cant-solve-the-collatz-conjecture-20200922/) is a famous unsolved problem in mathematics. It's a relatively simple, yet intriguing mathematical puzzle that has stumped mathematics for decades.*

### Task 2: Approximating Square Roots
*This function sqrt(x) starts with an initial guess z0, and it repeatedly improves the guess using the formula for Newton's method[[2]](https://en.wikipedia.org/wiki/Newton's_method) until the difference between consecutive guesses is less than the specified threshold. The result is an approximation of the square root of the input number x[[3]](https://www.geeksforgeeks.org/square-root-of-a-number-without-using-sqrt-function/).*

### Task 3: Counting Possible Functions
*How many times do you need to call the function to be certain what function it is?
This question, in a sense, is a question of combinations.*

### Task 4: Matrix Multiplication
*Matrix multiplication is a binary operation that produces another matrix by multiplying two matrices. The elements of the matrix are multiplied using basic arithmetic. When two matrices are multiplied, the row elements of the first matrix are multiplied by the column elements of the second matrix.[[4]](https://www.toppr.com/guides/python-guide/examples/python-examples/native-datatypes/multiply-matrix/python-program-to-multiply-two-matrices/)*

---

## [Project](/project.ipynb)

### Deutsch's Algorithm Exploration
The project focuses on Deutsch's algorithm, a fundamental quantum computing concept. The Jupyter notebook provides an in-depth exploration of the algorithm, including problem formulation, classical solutions, and quantum advantages.

#### Content Overview:
- Introduction
  - Background on Deutsch's Algorithm
  - Classical vs. Quantum Solutions
- Problem Statements
  - Details of Each Task
- Quantum Circuit Implementation
  - Code snippets using Qiskit
  - Simulation and Results
- Conclusion
  - Summary of Findings
  
#### [Link to the Project Notebook](/project.ipynb)

---


