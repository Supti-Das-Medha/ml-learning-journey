# Machine Learning & Open Source Learning Journey 🚀

Welcome to my Machine Learning learning repository!

This repository documents my journey of learning **Python, Data Science, Machine Learning, and Open Source Development**. It serves as both a **learning diary** and a **portfolio**, where I record my progress, challenges, solutions, and key concepts learned throughout the journey.

My long-term goal is to build strong Machine Learning fundamentals, contribute to open-source projects, conduct AI research, and prepare for higher studies.

---

# 🛠️ Tech Stack & Tools

- Python 3.x
- NumPy
- Pandas
- Matplotlib
- Scikit-Learn
- Jupyter Notebook
- Git
- GitHub
- VS Code
- Anaconda

---

# 🎯 Learning Objectives

- Master Python for Data Science and Machine Learning.
- Build strong mathematical and programming foundations.
- Learn Data Analysis and Data Preprocessing.
- Understand Machine Learning algorithms from scratch.
- Develop real-world Machine Learning projects.
- Practice a professional Git & GitHub workflow.
- Contribute to open-source organizations (e.g., Scikit-Learn).
- Prepare for AI research and higher studies (MS/PhD).

---

# 📅 Learning Log & Roadmap

## 🔹 Phase 1 – Python & NumPy Fundamentals

### 🚀 Today's Progress (Day 1)

#### 📖 Topics Covered

- Introduction to NumPy
- Why NumPy is faster than Python Lists
- Creating 1D Arrays
- Creating 2D Arrays
- Vectorized Operations
- Element-wise Computation

#### 📂 File Added

```text
01_numpy_basics.ipynb
```

---

## 📚 Concepts Learned

Today I learned the following NumPy fundamentals:

- Introduction to NumPy
- Installing and importing NumPy
- Creating NumPy arrays using `np.array()`
- Difference between Python Lists and NumPy Arrays
- Creating 1D arrays
- Creating 2D arrays
- Understanding:
  - Shape (`shape`)
  - Size (`size`)
  - Number of Dimensions (`ndim`)
  - Data Type (`dtype`)
- Indexing arrays
- Vectorized operations
- Element-wise mathematical operations
- Scalar operations
- Faster numerical computation using NumPy

---

## 💻 Python Commands Practiced

```python
import numpy as np

np.array()

arr.shape
arr.ndim
arr.size
arr.dtype

arr + 10
arr - 5
arr * 2
arr / 2

arr1 + arr2
arr1 * arr2
```

---

## 🧠 New Terminologies Learned

| Term | Meaning |
|------|---------|
| NumPy | Numerical Python Library |
| Array | Collection of same-type elements |
| Vectorization | Performing operations without explicit loops |
| Dimension | Number of axes |
| Shape | Number of rows and columns |
| dtype | Data type of array elements |
| Scalar | A single numerical value |

---

## 🛠️ Challenges Faced & Solutions (Troubleshooting Log)

### 1️⃣ Jupyter Notebook File Relocation

**Problem**

Moving the notebook (`.ipynb`) directly from the Jupyter browser dashboard to the local project folder was confusing.

**Solution**

Downloaded the notebook into the **Downloads** folder and then moved it into the project directory:

```text
ml-learning-journey/
```

---

### 2️⃣ Git Push Rejected (Branch Out-of-Sync)

**Problem**

Received the following error:

```text
[rejected] main -> main (fetch first)
```

because the remote repository contained newer commits.

**Solution**

Updated the local repository using:

```bash
git pull origin main --rebase
```

Then successfully pushed with:

```bash
git push origin main
```

---

## ⚠️ Common Mistakes I Learned

- Forgetting to import NumPy using:

```python
import numpy as np
```

- Mixing Python Lists with NumPy Arrays.
- Confusing `shape` and `size`.
- Forgetting commas while creating arrays.
- Assuming NumPy behaves exactly like Python Lists.
- Forgetting to save the notebook before pushing to GitHub.

---

## 💡 Key Takeaways

- NumPy arrays are much faster than standard Python lists.
- Vectorization eliminates the need for many explicit loops.
- Git helps maintain version history and track learning progress.
- Writing troubleshooting notes makes future debugging easier.
- Consistent daily practice is more valuable than studying many topics at once.

---

## 🎯 Learning Outcome

After completing Day 1, I can confidently:

- Import and use NumPy.
- Create 1D and 2D arrays.
- Perform vectorized mathematical operations.
- Access array properties.
- Understand why NumPy is essential for Machine Learning.
- Push projects to GitHub using a professional workflow.

---

## 📅 Next Learning Goal

Tomorrow I plan to learn:

- Array Indexing
- Array Slicing
- Reshaping Arrays
- Mathematical Functions
- Random Module
- NumPy Practice Problems

---
## 🚀 Today's Progress (Day 2)

### 📖 Topics Covered

- Creating arrays with `np.zeros()`
- Creating arrays with `np.ones()`
- Generating sequences using `np.arange()`
- Creating evenly spaced values using `np.linspace()`
- Understanding array `shape`
- Understanding element `dtype`
- Displaying arrays in Jupyter Notebook

#### 📂 File Added

```text
02_numpy_array_creation.ipynb
```

---

## 📚 Concepts Learned

Today I learned different ways to create NumPy arrays and explored their basic properties.

- Creating arrays filled with zeros
- Creating arrays filled with ones
- Using `dtype=int` to create integer arrays
- Generating consecutive values with `np.arange()`
- Understanding that the `stop` value is **not included** in `np.arange()`
- Generating evenly spaced values with `np.linspace()`
- Understanding that both `start` and `stop` values are included in `np.linspace()`
- Checking the shape of an array using `shape`
- Checking the data type of array elements using `dtype`

---

## 💻 Python Commands Practiced

```python
import numpy as np

np.zeros()
np.ones()
np.arange()
np.linspace()

arr.shape
arr.dtype

print(arr)
```

---

## 🧠 New Terminologies Learned

| Term | Meaning |
|------|---------|
| `zeros()` | Creates an array filled with zeros |
| `ones()` | Creates an array filled with ones |
| `arange()` | Generates a sequence of values within a range |
| `linspace()` | Generates evenly spaced values |
| `dtype` | Data type of the array elements |
| `shape` | Dimensions of the array |

---

## 🛠️ Challenges Faced & Solutions (Troubleshooting Log)

### 1️⃣ Understanding `(5,)` in `arr.shape`

**Problem**

I was confused about why the output was `(5,)` instead of just `5`.

**Solution**

Learned that `shape` always returns a **tuple**, and `(5,)` represents a one-dimensional array containing 5 elements.

---

### 2️⃣ Difference Between `arr` and `print(arr)`

**Problem**

I was unsure why Jupyter showed output when I wrote only `arr`.

**Solution**

Learned that Jupyter automatically displays the last expression in a cell, while `print(arr)` explicitly prints the array and is commonly used in Python scripts.

---

## ⚠️ Common Mistakes I Learned

- Forgetting that `np.arange()` excludes the stop value.
- Mixing the behavior of `arange()` and `linspace()`.
- Confusing the data type of the array (`type(arr)`) with the data type of its elements (`arr.dtype`).
- Misunderstanding the tuple format returned by `shape`.

---

## 💡 Key Takeaways

- NumPy provides multiple ways to create arrays depending on the problem.
- `arange()` is useful for generating sequences with a fixed step.
- `linspace()` is useful when a fixed number of evenly spaced values is required.
- Understanding `shape` and `dtype` is essential before working with machine learning datasets.
- Writing clear comments improves code readability and documentation quality.

---

## 🎯 Learning Outcome

After completing Day 2, I can confidently:

- Create arrays using `zeros()`, `ones()`, `arange()`, and `linspace()`.
- Explain the difference between `arange()` and `linspace()`.
- Understand why `shape` returns a tuple.
- Identify the data type of array elements.
- Write cleaner and more professional NumPy code.

---

## 📅 Next Learning Goal

Tomorrow I plan to learn:

- Array Indexing
- Array Slicing
- Reshaping Arrays
- Mathematical Functions
- Random Module

# 📈 Learning Progress

| Day | Topic | Status |
|-----|-------|--------|
| Day 1 | NumPy Basics | ✅ Completed |
| Day 2 | Indexing & Slicing | ✅ Completed |
| Day 3 | Array Manipulation | ⏳ Upcoming |
| Day 4 | Mathematical Functions | ⏳ Upcoming |
| Day 5 | NumPy Practice Problems | ⏳ Upcoming |

---

# 🚀 Future Plans

- Learn Pandas
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Data Visualization
- Statistics for Machine Learning
- Scikit-Learn
- Regression
- Classification
- Clustering
- Deep Learning Basics
- Open Source Contributions
- Research Projects

---

# ⭐ Repository Purpose

This repository documents my continuous learning journey and showcases my progress in **Python, Machine Learning, Open Source Development, and AI Research**.

I will update this repository regularly with new notebooks, projects, troubleshooting notes, and learning milestones as I continue my Machine Learning journey.

---

## 📌 Repository Structure

```text
ml-learning-journey/
│
├── 01_numpy_basics.ipynb
├── README.md
└── (More notebooks will be added...)
```

---

## 🌱 Daily Commitment

> **"Learn something new every day, practice consistently, and build one step at a time."**

Happy Learning! 🚀