# 📊 Data Science by Prajjal Dhar

Welcome to my **Data Science repository**.

This repository is where I am putting together my practical understanding of **Data Science, Data Analysis, Visualization and Machine Learning** using Python.

I believe Data Science should not be about memorizing functions or algorithms.

It should be about understanding the data, asking the right questions, finding patterns and then using those patterns to solve problems.

So here you will find my notebooks, examples, datasets, experiments and implementations as I learn and teach different concepts.

---

## 🧠 What You Will Find Here

```text
Python
   ↓
NumPy
   ↓
Pandas
   ↓
Data Visualization
   ↓
Exploratory Data Analysis
   ↓
Machine Learning
   ↓
Real World Projects
```

The repository is being built step by step.

---

# 🔢 NumPy

NumPy is where we start working with numerical data.

### Topics

📌 NumPy Arrays

📌 Array Creation

📌 Array Indexing

📌 Array Slicing

📌 Fancy Indexing

📌 Array Shape

📌 Reshape

📌 Axis

📌 Broadcasting

📌 Mathematical Operations

📌 Concatenation

📌 `concatenate`

📌 `hstack`

📌 `vstack`

📌 `stack`

📌 `split`

📌 Random Number Generation

### Example

```python
import numpy as np

arr = np.array([10, 20, 30, 40, 50])

print(arr)
print(arr.shape)
print(arr.mean())
```

The focus is not only on writing the code.

The focus is on understanding **what is happening inside the array**.

---

# 🐼 Pandas

Pandas is used for working with real datasets.

Here we learn how to load, understand, clean, transform and analyze data.

### Topics

📌 Series

📌 DataFrame

📌 Reading CSV files

📌 `head`

📌 `tail`

📌 `info`

📌 `describe`

📌 Selecting columns

📌 `loc`

📌 `iloc`

📌 Filtering

📌 Sorting

📌 Missing values

📌 Duplicate values

📌 `groupby`

📌 Aggregation

📌 `merge`

📌 `concat`

📌 Pivot Table

📌 MultiIndex

📌 Date and Time

### Example

```python
import pandas as pd

df = pd.read_csv("sales_data.csv")

print(df.head())
print(df.info())
print(df.describe())
```

---

# 📈 Graphs and Plots

Once we have the data, the next step is to **see the data**.

This section covers visualization using **Matplotlib and Seaborn**.

| Plot         | What We Understand                           |
| ------------ | -------------------------------------------- |
| Histogram    | Distribution of numerical data               |
| Box Plot     | Distribution and outliers                    |
| Bar Plot     | Category comparison                          |
| Count Plot   | Category frequency                           |
| Pie Chart    | Proportion and percentage                    |
| Line Plot    | Trend over time                              |
| Scatter Plot | Relationship between two numerical variables |
| Area Plot    | Trend and magnitude                          |
| Violin Plot  | Distribution and density                     |
| Heatmap      | Correlation and matrix relationships         |
| Pair Plot    | Multiple numerical relationships             |
| Joint Plot   | Relationship and individual distributions    |

---

# 🔍 Exploratory Data Analysis

EDA is one of the most important parts of Data Science.

Before building a Machine Learning model, we need to understand the data.

```text
Load Data
   ↓
Understand Data
   ↓
Clean Data
   ↓
Analyze Data
   ↓
Visualize Data
   ↓
Find Patterns
   ↓
Prepare Data
   ↓
Build Model
```

### Univariate Analysis

Understanding one variable.

Examples:

```text
Histogram
Box Plot
Count Plot
Pie Chart
```

### Bivariate Analysis

Understanding two variables.

Examples:

```text
Scatter Plot
Bar Plot
Line Plot
```

### Multivariate Analysis

Understanding multiple variables together.

Examples:

```text
Heatmap
Pair Plot
Multiple Variable Analysis
```

---

# 🤖 Machine Learning

After understanding the data, we move towards Machine Learning.

The main focus is on understanding **why an algorithm works**, not just how to import it.

---

## 📈 Regression

Regression is used when we want to predict a numerical value.

### Algorithms

📌 Linear Regression

📌 Multiple Linear Regression

📌 Polynomial Regression

📌 Decision Tree Regression

📌 Random Forest Regression

### Example

```python
from sklearn.linear_model import LinearRegression

model = LinearRegression()

model.fit(X_train, y_train)

predictions = model.predict(X_test)
```

---

# 🎯 Classification

Classification is used when the output belongs to a category.

### Algorithms

📌 Logistic Regression

📌 K Nearest Neighbors

📌 Decision Tree

📌 Random Forest

📌 Support Vector Machine

📌 Naive Bayes

### Example

```python
from sklearn.ensemble import RandomForestClassifier

model = RandomForestClassifier()

model.fit(X_train, y_train)

predictions = model.predict(X_test)
```

---

# 🔵 Clustering

Clustering is used when we want to find groups or patterns in data without predefined labels.

### Algorithms

📌 K Means

📌 Hierarchical Clustering

📌 DBSCAN

### Example

```python
from sklearn.cluster import KMeans

model = KMeans(n_clusters=3)

model.fit(X)

labels = model.labels_
```

---

# 📏 Model Evaluation

Building a model is not enough.

We also need to understand how well the model performs.

## Regression Metrics

📌 MAE

📌 MSE

📌 RMSE

📌 R² Score

## Classification Metrics

📌 Accuracy

📌 Precision

📌 Recall

📌 F1 Score

📌 Confusion Matrix

---

# ⚙️ Machine Learning Workflow

```text
Dataset
   ↓
Data Cleaning
   ↓
EDA
   ↓
Feature Selection
   ↓
Feature Engineering
   ↓
Train Test Split
   ↓
Scaling
   ↓
Model Training
   ↓
Prediction
   ↓
Evaluation
   ↓
Improvement
```

---

# 📂 Repository Structure

```text
Data Science
│
├── NumPy
│
├── Pandas
│
├── Graphs Plot
│
├── EDA
│
├── Machine Learning
│   │
│   ├── Regression
│   │
│   ├── Classification
│   │
│   └── Clustering
│
├── Datasets
│
└── README.md
```

---

# 🛠️ Technologies

```text
Python
NumPy
Pandas
Matplotlib
Seaborn
Scikit Learn
Jupyter Notebook
Git
GitHub
```

---

# 🎯 My Approach

I prefer learning by **building and experimenting**.

For every concept, I try to understand:

```text
What is it?
      ↓
Why do we need it?
      ↓
How does it work?
      ↓
How do we implement it?
      ↓
Where can we use it?
```

The goal is not to simply remember:

```python
model.fit()
```

The goal is to understand **what happens when we call it and why we are using that model in the first place**.

---

# 🚀 What's Next

This repository will continue to grow with topics such as:

📌 Statistics

📌 Probability

📌 Feature Engineering

📌 Advanced Machine Learning

📌 Ensemble Learning

📌 Hyperparameter Tuning

📌 Cross Validation

📌 NLP

📌 Deep Learning

📌 Generative AI

📌 RAG

📌 Agentic AI

📌 Real World Projects

---

# 👨‍💻 About Me

I am **Prajjal Dhar**, a Developer Advocate and Full Stack Developer with a strong interest in **Data Science, Machine Learning, Generative AI and Agentic AI**.

I also work in technical education and enjoy breaking complex technical concepts into practical examples that developers and students can actually understand.

I believe the best way to learn technology is:

> **Learn → Understand → Build → Break → Fix → Teach**

This repository is a part of that journey.

---

## ⭐ Keep Learning

Data Science is not just about algorithms.

It is about **data, logic, mathematics, experimentation and problem solving**.

Keep learning.

Keep building.

Keep questioning.

And most importantly,

**Understand what you are doing.**

### Prajjal Dhar

Developer Advocate | Full Stack Developer | Data Science | Machine Learning | GenAI | Agentic AI
