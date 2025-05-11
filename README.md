Problem Statement
This assignment involves the study and visualization of the population growth of Escherichia coli (E. coli) bacteria sampled from untreated water. The bacterial lineage was observed and quantified using fluorescence microscopy (Zeiss AxioVert 200M, ZEISS™ Germany). The experiment captures the growth sequence of rod-shaped E. coli cells over time, modeled by a differential equation.

Here is a professional, submission-ready `README.md` content for your assignment:

---

# 📘 Assignment 1: Modeling and Visualization of *E. coli* Bacterial Growth

## 🔬 Problem Statement

This assignment involves the study and visualization of the population growth of *Escherichia coli* (E. coli) bacteria sampled from untreated water. The bacterial lineage was observed and quantified using fluorescence microscopy (Zeiss AxioVert 200M, ZEISS™ Germany). The experiment captures the growth sequence of rod-shaped E. coli cells over time, modeled by a differential equation.

---

## 🧮 Mathematical Model

The growth of E. coli is represented by the following differential equation:

$$
\frac{dy}{2^x \cdot \ln(2)} = dx
$$

With the initial condition:

$$
y(0) = 1
$$

### ✅ Solution:

Solving this gives:

$$
y(x) = 2^x
$$

Where:

* `x` = time in hours
* `y(x)` = number of E. coli bacteria cells

---

## ⏱ Time Points for Evaluation

The bacterial population is evaluated at specific time instances:

```
x = [1, 2, 6, 7, 8, 9, 11, 12] (in hours)
```

---

## 📊 Objective

1. Compute the number of E. coli cells for each hour using the equation.
2. Plot a histogram to visualize the distribution of bacterial growth.
3. Use **Sturges' Rule** to determine the number of histogram bins.
4. Plot the histogram using **relative frequency**.

---

## 🧑‍💻 Technologies Used

* Python 3.x
* Numpy
* Matplotlib

---

## 🚀 How to Run

1. Install dependencies (if needed):

   ```bash
   pip install numpy matplotlib
   ```

2. Run the Python script:

   ```bash
   python e_coli_growth_visualization.py
   ```

---

## 📈 Sample Output

The histogram generated represents the **relative frequency** of E. coli cell counts at different time intervals.

---

## 📋 Data Table

| Time (x in hours) | E. coli Cell Count (y = 2^x) |
| ----------------- | ---------------------------- |
| 1                 | 2                            |
| 2                 | 4                            |
| 6                 | 64                           |
| 7                 | 128                          |
| 8                 | 256                          |
| 9                 | 512                          |
| 11                | 2048                         |
| 12                | 4096                         |

---

## 📎 References

* Zeiss AxioVert 200M Microscope
* E. coli colony time-lapse observations
* Sturges’ Rule for histogram bin selection

---

Let me know if you want this packaged into a `.zip` file or turned into a formal report!
