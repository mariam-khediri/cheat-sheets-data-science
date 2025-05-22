
# 📊 **Python Data Visualization Cheat Sheet**

---

## 🔹 Libraries Overview

| Library        | Use Case                      | Import Statement                  |
| -------------- | ----------------------------- | --------------------------------- |
| **Matplotlib** | Basic static plots            | `import matplotlib.pyplot as plt` |
| **Seaborn**    | Statistical + aesthetic plots | `import seaborn as sns`           |
| **Plotly**     | Interactive visualizations    | `import plotly.express as px`     |
| **Pandas**     | Quick plots from DataFrames   | `df.plot()`                       |

---

## 🔸 **Matplotlib – Core Plot Types**

```python
import matplotlib.pyplot as plt

# Line Plot
plt.plot(x, y)
plt.title("Line Plot")
plt.show()

# Bar Chart
plt.bar(x, y)

# Histogram
plt.hist(data, bins=10)

# Scatter Plot
plt.scatter(x, y)

# Pie Chart
plt.pie(values, labels=labels, autopct='%1.1f%%')

# Box Plot
plt.boxplot(data)

# Subplots
fig, axs = plt.subplots(1, 2)
axs[0].plot(x1, y1)
axs[1].plot(x2, y2)
```

---

## 🔸 **Seaborn – Statistical Plots**

```python
import seaborn as sns

# Scatter + Regression Line
sns.lmplot(x="x", y="y", data=df)

# Histogram (Distribution)
sns.histplot(df['column'])

# Box Plot
sns.boxplot(x="category", y="value", data=df)

# Violin Plot
sns.violinplot(x="category", y="value", data=df)

# Count Plot (Bar plot of counts)
sns.countplot(x='category', data=df)

# Heatmap (Correlation matrix)
sns.heatmap(df.corr(), annot=True, cmap='coolwarm')

# Pairplot (matrix of scatter plots)
sns.pairplot(df)
```

---

## 🔸 **Plotly – Interactive Plots**

```python
import plotly.express as px

# Line Plot
px.line(df, x="x", y="y", title="Line Plot")

# Bar Chart
px.bar(df, x="x", y="y")

# Scatter Plot
px.scatter(df, x="x", y="y", color="label")

# Box Plot
px.box(df, x="category", y="value")

# Histogram
px.histogram(df, x="column")

# Pie Chart
px.pie(df, names="category", values="value")

# Heatmap
import plotly.figure_factory as ff
fig = ff.create_annotated_heatmap(z=df.corr().values,
                                  x=list(df.columns),
                                  y=list(df.columns))
fig.show()
```

---

## 🔸 **Pandas Built-in Plotting (uses Matplotlib backend)**

```python
# Line Plot
df.plot()

# Bar Chart
df['column'].value_counts().plot(kind='bar')

# Histogram
df['column'].plot(kind='hist', bins=10)

# Box Plot
df.plot(kind='box')

# Area Plot
df.plot(kind='area', alpha=0.4)
```

---

## 📌 Plot Type Summary

| Plot Type    | Matplotlib | Seaborn | Plotly      | Pandas |
| ------------ | ---------- | ------- | ----------- | ------ |
| Line Plot    | ✅          | ✅       | ✅           | ✅      |
| Bar Chart    | ✅          | ✅       | ✅           | ✅      |
| Histogram    | ✅          | ✅       | ✅           | ✅      |
| Scatter Plot | ✅          | ✅       | ✅           | ❌      |
| Box Plot     | ✅          | ✅       | ✅           | ✅      |
| Pie Chart    | ✅          | ❌       | ✅           | ❌      |
| Violin Plot  | ❌          | ✅       | ✅           | ❌      |
| Heatmap      | ❌          | ✅       | ✅           | ❌      |
| Count Plot   | ❌          | ✅       | ✅ (via bar) | ❌      |
| Pairplot     | ❌          | ✅       | ❌           | ❌      |

---
