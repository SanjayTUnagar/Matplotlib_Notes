# 📊 Matplotlib Complete Python Data Visualization Guide

> A comprehensive Matplotlib cheat sheet covering the most commonly used charts, customization options, advanced plots, and best practices for Python Data Visualization.

<p align="center">
  <img src="Matplotlib_Complete_Guide.png" alt="Matplotlib Complete Guide">
  <img  width="100%" alt="Matplotlib Python data visualization guide" src="https://github.com/user-attachments/assets/fc397b10-b550-48fb-b15d-f4688bcaa1cf" />

</p>

---

# 📚 Table of Contents

- Introduction
- What is Matplotlib?
- Key Features
- Installation
- Importing Library
- Basic Plot Syntax
- Types of Charts
- Customization Options
- Common Functions
- Advanced Plot Examples
- Working with Pandas
- Complete Example
- Tips & Best Practices
- Resources

---

# 📖 Introduction

Matplotlib is one of the most popular Python libraries for creating static, animated, and interactive visualizations.

It is widely used in:

- Data Analysis
- Data Science
- Machine Learning
- Artificial Intelligence
- Business Intelligence
- Research
- Statistics

---

# 🚀 What is Matplotlib?

Matplotlib is an open-source Python library used to visualize data.

It provides a flexible interface for creating publication-quality graphs and charts.

---

# ⭐ Key Features

- Easy to Learn
- Beginner Friendly
- Highly Customizable
- Publication Quality Figures
- Supports Static & Interactive Charts
- Works with NumPy
- Works with Pandas
- Supports Multiple Plot Types

---

# 📦 Installation

```bash
pip install matplotlib
```

---

# 📥 Import Library

```python
import matplotlib.pyplot as plt
import numpy as np
import pandas as pd
```

---

# 📈 Basic Plot Syntax

```python
plt.plot(x, y)

plt.title("Title")

plt.xlabel("X Axis")

plt.ylabel("Y Axis")

plt.grid(True)

plt.show()
```

---

# 📊 Chart Types

## 1️⃣ Line Plot

Used for showing trends over time.

```python
plt.plot(x, y)
```

---

## 2️⃣ Bar Chart

Used for comparing categories.

```python
plt.bar(categories, values)
```

---

## 3️⃣ Scatter Plot

Used for showing relationships between variables.

```python
plt.scatter(x, y)
```

---

## 4️⃣ Histogram

Used for frequency distribution.

```python
plt.hist(data)
```

---

## 5️⃣ Pie Chart

Used for percentage distribution.

```python
plt.pie(values)
```

---

## 6️⃣ Area Plot

Used for cumulative data.

```python
plt.fill_between(x, y)
```

---

## 7️⃣ Multiple Plots (Subplots)

```python
plt.subplot(1,2,1)

plt.subplot(1,2,2)
```

---

# 🎨 Customization Options

## Colors

```python
color='red'
```

## Marker

```python
marker='o'
```

## Line Style

```python
linestyle='--'
```

## Line Width

```python
linewidth=2
```

## Figure Size

```python
plt.figure(figsize=(8,5))
```

## Grid

```python
plt.grid(True)
```

## Legend

```python
plt.legend()
```

## Save Figure

```python
plt.savefig("plot.png")
```

---

# ⚙️ Commonly Used Functions

| Function | Description |
|-----------|-------------|
| plt.plot() | Line Plot |
| plt.bar() | Bar Chart |
| plt.scatter() | Scatter Plot |
| plt.hist() | Histogram |
| plt.pie() | Pie Chart |
| plt.fill_between() | Area Plot |
| plt.subplot() | Multiple Plots |
| plt.title() | Add Title |
| plt.xlabel() | X Label |
| plt.ylabel() | Y Label |
| plt.legend() | Show Legend |
| plt.grid() | Grid |
| plt.savefig() | Save Figure |
| plt.show() | Display Plot |

---

# 🚀 Advanced Plot Examples

## Box Plot

```python
plt.boxplot(data)
```

---

## Heatmap

```python
plt.imshow(data)

plt.colorbar()
```

---

## 3D Plot

```python
from mpl_toolkits import mplot3d
```

---

## Polar Plot

```python
plt.polar(theta, r)
```

---

## Bubble Chart

```python
plt.scatter(x, y, s=size)
```

---

# 🐼 Working with Pandas

```python
import pandas as pd

df = pd.read_csv("data.csv")

plt.plot(df["X"], df["Y"])

plt.show()
```

---

# 💻 Complete Example

```python
import matplotlib.pyplot as plt

x = [1,2,3,4,5]

y = [3,1,4,2,5]

plt.figure(figsize=(6,4))

plt.plot(
    x,
    y,
    marker='o',
    color='purple',
    linewidth=2
)

plt.title("My First Plot")

plt.xlabel("X Axis")

plt.ylabel("Y Axis")

plt.grid(True)

plt.show()
```

---

# 💡 Tips & Best Practices

- Use meaningful titles.
- Label both axes.
- Choose the correct chart.
- Keep charts clean.
- Use legends when required.
- Avoid unnecessary colors.
- Save figures in high resolution.
- Use grids for better readability.

---

# 📚 Learning Resources

- Official Matplotlib Documentation
- Python Documentation
- NumPy Documentation
- Pandas Documentation

---

# 🛠️ Technologies Used

- Python
- Matplotlib
- NumPy
- Pandas

---

# 🎯 Suitable For

- Beginners
- Students
- Data Analysts
- Data Scientists
- Python Developers
- Machine Learning Engineers

---

# ⭐ If you found this project useful

Give this repository a ⭐ on GitHub.

Happy Coding! 🚀

