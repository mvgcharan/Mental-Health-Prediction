# Student Mental Health Analysis and Depression Prediction

## Overview

This project presents a comprehensive machine learning pipeline for analyzing student mental health data and predicting depression levels based on demographic, academic, lifestyle, and psychological factors. The notebook demonstrates the complete data science workflow, including data preprocessing, exploratory data analysis, feature engineering, model training, and performance evaluation.

The objective of this project is to identify significant factors associated with student mental health and develop predictive models that can assist in understanding depression patterns within the dataset.

---

## Project Objectives

- Analyze student mental health data using exploratory data analysis.
- Clean and preprocess the dataset for machine learning.
- Engineer features through encoding and scaling techniques.
- Train classification models to predict depression.
- Evaluate model performance using standard classification metrics.
- Visualize model performance through confusion matrices.

---

## Dataset

The project uses the dataset:

**`mental_fem.csv`**

The dataset contains demographic, socioeconomic, lifestyle, and mental health-related attributes that are used to predict depression levels.

---

## Project Workflow

### 1. Data Loading

- Import the dataset
- Inspect the dataset structure
- Display summary statistics

### 2. Data Preprocessing

- Remove duplicate records
- Handle missing values
- Validate and clean numerical attributes
- Encode categorical features
- Scale numerical features

### 3. Exploratory Data Analysis (EDA)

The notebook includes data visualization and statistical analysis to understand:

- Feature distributions
- Data quality
- Relationships among variables
- Class distribution

### 4. Feature Engineering

- Label Encoding
- Feature Scaling
- Data transformation
- Pipeline preparation

### 5. Model Development

Machine learning models implemented include:

- Random Forest Classifier
- K-Nearest Neighbors (KNN)

Additional preprocessing techniques include:

- StandardScaler
- MaxAbsScaler
- Principal Component Analysis (PCA)

### 6. Model Evaluation

Models are evaluated using:

- Accuracy Score
- Confusion Matrix
- Classification Report

The confusion matrix is visualized to assess model performance.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Scikit-plot

---

## Installation


Navigate to the project directory:

```bash
cd student-mental-health-analysis
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

---

## Running the Project

Launch Jupyter Notebook:

```bash
jupyter notebook Spltopic_code.ipynb
```

or

```bash
jupyter lab
```

---

## Required Libraries

Install the required Python packages:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn scikit-plot
```

---

## Project Structure

```
Student-Mental-Health-Analysis/
│
├── Spltopic_code.ipynb
├── README.md

```

---

## Results

The notebook demonstrates the end-to-end implementation of a machine learning pipeline for depression prediction. Multiple preprocessing techniques and classification algorithms are explored to evaluate predictive performance. The final evaluation includes classification metrics and confusion matrix visualizations to compare model effectiveness.

---

## Future Enhancements

- Hyperparameter optimization
- Cross-validation for improved model reliability
- Additional machine learning algorithms
- Deep learning-based prediction models
- Interactive dashboard using Streamlit or Flask
- Model deployment as a web application

---

## License

This project is intended for educational, academic, and research purposes.

---

## Author

Developed as part of a machine learning project focused on student mental health analysis and depression prediction.
