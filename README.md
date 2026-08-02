# Machine Learning & Open Source Learning Journey 🚀

Welcome to my machine learning repository! This repository tracks my progress in Python, Data Science, and Machine Learning foundations as part of my preparation for Open Source contributions and Higher Studies.

## 🛠️ Stack & Tools
- Python 3.x
- NumPy & Pandas
- Scikit-Learn
- Git & GitHub

## 📌 Objectives
- Master Git/GitHub workflow.
- Implement core Machine Learning algorithms.
- Prepare for contributions to NumFOCUS organizations (e.g., Scikit-Learn).

---

## 📅 Learning Log & Roadmap

### 🔹 Phase 1: Python & NumPy Fundamentals

#### 🚀 Today's Progress (Day 1)
- **Topic:** Introduction to NumPy, 1D and 2D Arrays, and Vectorized Operations.
- **File Added:** `01_numpy_basics.ipynb`

#### 🛠️ Challenges Faced & Solutions (Troubleshooting Log)

1. **Jupyter Notebook File Relocation**
   - **Problem:** Moving `.ipynb` directly from the Jupyter browser dashboard to the local project directory was not supported.
   - **Solution:** Downloaded the notebook file locally to `Downloads` and then moved it into the project folder (`ml-learning-journey`).

2. **Git Push Rejected (Branch Out-of-Sync)**
   - **Problem:** Encountered `[rejected] - main -> main (fetch first)` because the remote repo had newer changes.
   - **Solution:** Synced the local repository with remote changes smoothly using:
     ```bash
     git pull origin main --rebase
     ```
     Then successfully pushed with:
     ```bash
     git push origin main
     ```

#### 💡 Key Takeaways
- NumPy array operations are significantly faster than standard Python lists.
- Maintaining a clean Git troubleshooting log makes learning structured and reproducible.
