# 📊 Data Science Learning & Projects

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=flat-square&logo=python)](https://www.python.org/)
[![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)](LICENSE)
[![GitHub](https://img.shields.io/badge/GitHub-arib--06-black?style=flat-square&logo=github)](https://github.com/arib-06)

A comprehensive collection of data science projects, machine learning models, and Python fundamentals practice work. This repository documents my journey in mastering data science concepts through hands-on projects and practical implementations.

## 📋 Overview

This repository serves as a portfolio of data science work including:
- Python fundamentals and advanced concepts
- Data analysis and manipulation
- Exploratory Data Analysis (EDA)
- Machine learning projects
- Data visualization
- Real-world dataset analysis

## 🎯 Project Highlights

### 1. **Python Basics** `Python basics/`
- Fundamental Python programming concepts
- Data structures and algorithms
- Object-oriented programming (OOP)
- File I/O and data handling
- **Skills**: Variables, loops, functions, classes, error handling

### 2. **Data Analysis Projects** `Project.py`
- Real-world data cleaning and preprocessing
- Statistical analysis and insights
- Data transformation and feature engineering
- **Dataset**: Amazon Bestsellers with categories
- **Skills**: Pandas, NumPy, data wrangling

### 3. **EDA & Visualization** `bestsellers with categories.csv`
- Comprehensive exploratory data analysis
- Statistical distributions and correlations
- Visual insights through charts and graphs
- Category-wise performance analysis

## 🛠️ Tech Stack

| Category | Tools & Libraries |
|----------|------------------|
| **Programming** | Python 3.8+ |
| **Data Manipulation** | Pandas, NumPy |
| **Visualization** | Matplotlib, Seaborn, Plotly |
| **Analysis** | SciPy, Scikit-learn |
| **Notebooks** | Jupyter, Google Colab |
| **Version Control** | Git, GitHub |

## 📂 Repository Structure

```
DATA-SCience/
├── Python basics/              # Python fundamentals
│   ├── Variables & types
│   ├── Control flow
│   ├── Functions
│   ├── OOP concepts
│   └── File handling
├── Project.py                  # Main data analysis project
├── bestsellers with categories.csv  # Dataset
└── README.md                   # This file
```

## 🚀 Getting Started

### Prerequisites
```bash
Python >= 3.8
pip or conda
```

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/arib-06/DATA-SCience.git
   cd DATA-SCience
   ```

2. **Create virtual environment** (Optional but recommended)
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**
   ```bash
   pip install pandas numpy matplotlib seaborn scipy scikit-learn jupyter
   ```

### Running the Projects

**Run the main analysis**
```bash
python Project.py
```

**Explore in Jupyter**
```bash
jupyter notebook
```

## 📊 Key Projects & Learnings

### Amazon Bestsellers Analysis
- **Objective**: Analyze book sales trends and categories
- **Dataset**: Bestsellers with category information
- **Analysis Type**: EDA, Statistical Analysis
- **Key Insights**:
  - Category distribution in bestsellers
  - Price trends across categories
  - Rating and review analysis
  - Author popularity patterns

## 💡 Skills Developed

### Data Science
- [x] Data cleaning and preprocessing
- [x] Exploratory Data Analysis (EDA)
- [x] Statistical analysis
- [x] Data visualization
- [x] Feature engineering basics
- [x] Python data science workflow

### Python Programming
- [x] Core Python concepts
- [x] Object-oriented programming
- [x] Working with libraries (Pandas, NumPy)
- [x] File handling and I/O
- [x] Error handling and debugging

## 📈 Learning Path

1. **Foundation** → Python basics and fundamentals
2. **Data Manipulation** → Pandas and NumPy
3. **Analysis** → EDA and statistical analysis
4. **Visualization** → Creating meaningful charts
5. **Projects** → Real-world dataset analysis

## 🔍 Code Examples

### Data Loading & Exploration
```python
import pandas as pd
import numpy as np

# Load dataset
df = pd.read_csv('bestsellers with categories.csv')

# Explore structure
print(df.head())
print(df.info())
print(df.describe())
```

### Data Cleaning
```python
# Handle missing values
df.fillna(df.mean(), inplace=True)

# Remove duplicates
df.drop_duplicates(inplace=True)

# Data type conversion
df['price'] = pd.to_numeric(df['price'], errors='coerce')
```

### Visualization
```python
import matplotlib.pyplot as plt
import seaborn as sns

# Distribution plot
plt.figure(figsize=(10, 6))
sns.histplot(df['price'], kde=True)
plt.title('Price Distribution')
plt.show()
```

## 📚 Resources & References

- [Pandas Documentation](https://pandas.pydata.org/docs/)
- [NumPy Guide](https://numpy.org/doc/)
- [Matplotlib Tutorials](https://matplotlib.org/stable/tutorials/)
- [Scikit-learn Documentation](https://scikit-learn.org/)
- [Kaggle Datasets](https://www.kaggle.com/)
- [DataCamp Python Courses](https://www.datacamp.com/)

## 🎓 Learning Outcomes

By exploring this repository, you'll understand:
- How to approach data analysis systematically
- Best practices for data cleaning and preprocessing
- Creating professional visualizations
- Deriving actionable insights from data
- Python best practices and coding standards

## 📝 Future Enhancements

- [ ] Add machine learning models
- [ ] Implement advanced EDA techniques
- [ ] Create interactive Plotly dashboards
- [ ] Add statistical hypothesis testing
- [ ] Develop predictive models
- [ ] Create data science documentation
- [ ] Add more real-world datasets

## 💬 Connect & Collaborate

**LinkedIn**: [Mohammad Aribul Haq](https://linkedin.com/in/aribul-haq)
**GitHub**: [@arib-06](https://github.com/arib-06)
**Email**: Contact via GitHub

## 📜 License

This project is open-source and available under the MIT License. See the LICENSE file for details.

---

**Last Updated**: December 2025
**Status**: ✅ Active Learning & Development

Created with ❤️ for Data Science Learning
