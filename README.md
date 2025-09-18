# IT3212 Datadrevet Programvare - Student Project

A comprehensive data science project repository for the IT3212 Datadrevet Programvare course. This repository contains structured notebooks and resources for learning and applying data science techniques.

## 🎯 Project Overview

This is a student project designed to demonstrate proficiency in various data science techniques including data exploration, cleaning, transformation, outlier handling, and dimensionality reduction.

## 📁 Repository Structure

```
IT3212-Datadrevet-Programvare/
├── notebooks/                          # Jupyter notebooks for each task
│   ├── 01_data_exploration.ipynb      # Data Exploration (10 points)
│   ├── 02_data_cleaning.ipynb         # Data Cleaning (20 points)
│   ├── 03_data_transformation.ipynb   # Data Transformation (30 points)
│   ├── 04_handling_outliers.ipynb     # Handling Outliers (20 points)
│   ├── 05_data_splitting.ipynb        # Data Splitting (10 points)
│   └── 06_dimensionality_reduction_bonus.ipynb  # Bonus Task (10 points)
├── data/                               # Datasets (excluded from git)
│   └── README.md                       # Data directory guidelines
├── pyproject.toml                      # UV project configuration
├── .gitignore                          # Git ignore rules
└── README.md                           # This file
```

## 📊 Assignment Tasks

### Core Tasks (90 points total)

1. **Data Exploration (10 points)**
   - Load and examine dataset structure
   - Perform basic statistical analysis
   - Create visualizations to understand data distribution
   - Identify patterns and relationships

2. **Data Cleaning (20 points)**
   - Handle missing values
   - Detect and correct data inconsistencies
   - Remove or fix invalid data entries
   - Standardize data formats

3. **Data Transformation (30 points)**
   - Apply feature engineering techniques
   - Normalize and scale numerical features
   - Encode categorical variables
   - Create derived features

4. **Handling Outliers (20 points)**
   - Detect outliers using statistical methods
   - Visualize outliers in the data
   - Implement appropriate outlier treatment strategies
   - Evaluate the impact of outlier handling

5. **Data Splitting (10 points)**
   - Split data into training, validation, and test sets
   - Implement stratified sampling for classification tasks
   - Set up cross-validation techniques

### Bonus Task (10 points)

6. **Dimensionality Reduction (Optional)**
   - Apply Principal Component Analysis (PCA)
   - Implement t-SNE for visualization
   - Use Linear Discriminant Analysis (LDA)
   - Compare different dimensionality reduction techniques

## 🚀 Getting Started

### Prerequisites

- Python 3.9 or higher
- UV package manager (recommended) or pip

### Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/LarsMstangeland/IT3212-Datadrevet-Programvare.git
   cd IT3212-Datadrevet-Programvare
   ```

2. Install dependencies using UV:
   ```bash
   uv sync
   ```

   Or using pip:
   ```bash
   pip install -e .
   ```

3. Start Jupyter:
   ```bash
   jupyter lab
   ```

### Usage

1. Place your datasets in the `data/` directory
2. Open the notebooks in sequential order (01, 02, 03, etc.)
3. Follow the instructions and complete the TODO sections in each notebook
4. Document your findings and decisions as you work through each task

## 📝 Notes

- The `data/` directory is excluded from version control to prevent committing large datasets
- Each notebook builds upon the previous one, so work through them in order
- Document your reasoning for data science decisions
- Use the provided code structure as a starting point, but feel free to expand and improve

## 📚 Dependencies

Key Python packages used in this project:

- **Data Manipulation**: pandas, numpy
- **Visualization**: matplotlib, seaborn
- **Machine Learning**: scikit-learn, scipy
- **Development**: jupyter, black, isort, flake8

See `pyproject.toml` for the complete list of dependencies.

## 👨‍🎓 Course Information

- **Course**: IT3212 Datadrevet Programvare
- **Type**: Student Project
- **Total Points**: 100 (90 core + 10 bonus)

---

**Note**: This is a student project for educational purposes.
