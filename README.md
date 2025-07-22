# Data Analysis and Preprocessing Demonstration Projects

## Overview
This repository contains two comprehensive data analysis projects that demonstrate essential data science workflows including data preprocessing, feature engineering, exploratory data analysis (EDA), and statistical analysis. The projects showcase how to properly prepare datasets for machine learning models while ensuring data quality and understanding underlying patterns.

## Projects

### 1.  Insurance Charges Prediction (`insurance.ipynb`)
**Objective:** Predict insurance charges using customer demographic and health information (regression problem)

**Dataset:** `insurance.csv`
- **Target Variable:** Insurance charges (continuous values)
- **Features:** Age, BMI, children, sex, smoker status, region

### 2.  Heart Disease Prediction (`heart.ipynb`)
**Objective:** Predict heart disease occurrence using medical indicators (classification problem)

**Dataset:** `heart.csv`
- **Target Variable:** Heart disease presence (categorical - binary classification)
- **Features:** Age, resting blood pressure, cholesterol levels, and other cardiac indicators

##  Key Demonstrations

### Data Preprocessing Pipeline
- **Data Loading & Inspection:** Comprehensive dataset exploration and structure analysis
- **Data Cleaning:** Handling missing values, duplicates, and data quality issues
- **Feature Scaling:** Standardization and normalization techniques for optimal model performance
- **Feature Engineering:** Creating new features and transforming existing ones for better predictive power

### Exploratory Data Analysis (EDA)
- **Statistical Analysis:** Descriptive statistics, data distribution analysis, and normality testing
- **Outlier Detection & Treatment:** Identifying anomalies and implementing appropriate handling strategies
- **Correlation Analysis:** Understanding relationships between features using correlation matrices and heatmaps
- **Data Visualization:** Comprehensive plotting including:
  - Distribution plots (histograms with KDE)
  - Count plots for categorical variables
  - Correlation heatmaps
  - Box plots for outlier visualization

### Statistical Insights
- **Distribution Analysis:** Testing for normal distribution and understanding data spread
- **Anomaly Reduction:** Systematic approach to reduce data anomalies and ensure data quality
- **Clustering Analysis:** Understanding how data points cluster together
- **Feature Relationships:** Analyzing correlations and dependencies between variables

##  Technical Implementation

### Libraries Used
- **pandas:** Data manipulation and analysis
- **numpy:** Numerical computations
- **seaborn & matplotlib:** Data visualization and statistical plotting
- **warnings:** Clean output management

### Key Analysis Components

#### 1. Data Quality Assessment
```python
# Data structure and types
df.info()
df.describe()

# Missing values and duplicates
df.isnull().sum()
df.duplicated().sum()
```

#### 2. Distribution Analysis
- Histogram plots with kernel density estimation (KDE)
- Statistical summaries for understanding data spread
- Normal distribution testing and visualization

#### 3. Relationship Mapping
- Correlation heatmaps to identify feature relationships
- Pairwise analysis between features and target variables
- Visual correlation matrices for pattern recognition

#### 4. Outlier Management
- Statistical outlier detection methods
- Visualization of anomalies using box plots
- Strategic outlier treatment to improve model performance

##  Project Outcomes

### Insurance Project Insights
- Analysis of demographic factors affecting insurance costs
- Understanding the impact of health indicators (BMI, smoking) on charges
- Family size influence on insurance pricing
- Regional variations in insurance costs

### Heart Disease Project Insights
- Identification of key cardiac risk factors
- Age and gender patterns in heart disease occurrence
- Clinical indicators correlation with disease probability
- Risk stratification based on multiple health parameters

##  Model Preparation Benefits

### Data Quality Assurance
- **Clean Datasets:** Systematic preprocessing ensures high-quality input data
- **Normal Distribution:** Proper scaling and transformation for optimal model performance
- **Reduced Anomalies:** Outlier treatment minimizes model bias and improves accuracy
- **Feature Optimization:** Engineered features provide better predictive power

### Statistical Validity
- **Distribution Alignment:** Ensuring features follow appropriate statistical distributions
- **Correlation Understanding:** Identifying multicollinearity and feature dependencies
- **Balanced Representation:** Proper handling of categorical variables and class imbalances

##  Getting Started

### Prerequisites
```bash
pip install pandas numpy seaborn matplotlib jupyter
```

### Running the Analysis
1. Clone this repository
2. Ensure CSV files are in the project directory
3. Open Jupyter notebooks:
   - `insurance.ipynb` for insurance analysis
   - `heart.ipynb` for heart disease analysis
4. Run cells sequentially to reproduce the analysis

##  Future Enhancements
- Machine learning model implementation
- Advanced feature engineering techniques
- Cross-validation and model evaluation metrics
- Hyperparameter tuning and optimization
- Deployment-ready model pipelines

##  Notes
- All visualizations are optimized for clear interpretation
- Statistical tests ensure robust analysis
- Code is well-documented for educational purposes
- Both regression and classification scenarios are covered
