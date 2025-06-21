<h1 align="center">📘 MathRi Project Guide</h1>

## 📂 About This Repository

This repository serves as a **central reference** for the MathRi project. It contains:

- 🧾 **Additional notes and explanations** for selected numerical techniques.
- 📄 A comprehensive **final report** that:
  - Explains the numerical methods used.
  - Summarizes and compares their **accuracy** and **time complexity** in a clear table.
  - Provides simplified descriptions of each technique for easy understanding.

Use this repository to get a high-level overview of the entire project before exploring the individual implementations.

---

## 🧠 Numerical Methods Overview

The numerical techniques used across the project include:

- 🔹 **[Physics-Informed Neural Networks (PINN)](https://github.com/MathRi-ATG/Physics-Informed-Neural-Network)**
- 🔹 **[Pseudo Spectral Method](https://github.com/MathRi-ATG/Pseudo-Spectral-Method)**
- 🔹 **[Crank-Nicholson](https://github.com/MathRi-ATG/Crank-Nicholson)**
- 🔹 **[Finite Element Method](https://github.com/MathRi-ATG/Finite-Element-Method)**
- 🔹 **[Presentation + All codes](https://github.com/MathRi-ATG/.github)**

---

## 📁 Structure of the Other 4 Repositories

Each of the four separate repositories corresponds to one numerical method and includes:

1. 🧩 **Complete implementation** of the method with detailed explanations.
2. 📈 **Result visualizations** specific to that technique.
3. 📊 **Accuracy analysis** using **True Relative Error (TRE)**:
   - TRE (True relative error) is computed by comparing the method’s output to a baseline (e.g., **Method of Lines**).
   - For **PINN**, comparison is made against a solution obtained from a trusted PDE-solving library.
4. ⏱ **Time complexity breakdown** within the Jupyter notebooks, showing:
   - Complexity of each individual code block.
   - Total complexity of the full implementation.

---

> 🔗 Start here for orientation, then dive into each method's repo for code, results, and in-depth analysis.
