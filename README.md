# Loan Default Risk Analysis Project

## 📊 Project Overview
A comprehensive data analysis project focused on understanding and predicting loan default risks using a large-scale banking dataset. This project aims to help financial institutions make more informed lending decisions by identifying key patterns and risk factors associated with loan defaults.

### 🎯 Business Problem
Banks face significant financial risks from loan defaults. This project analyzes historical loan data to:
- Identify key predictors of loan defaults
- Understand customer segments with higher default risks
- Provide data-driven insights for loan approval processes
- Help optimize lending strategies to minimize default risks

## 📋 Dataset
The analysis uses a publicly available dataset from Kaggle containing:
- 307,511 loan applications
- 122 features per application
- Demographic, financial, and behavioral attributes
- Binary target variable (1 = default, 0 = non-default)

[Dataset Source](https://www.kaggle.com/datasets/gauravduttakiit/loan-defaulter?select=previous_application.csv)

## 🔍 Key Features Analyzed
- Contract Types
- Income Levels
- Credit Amounts
- Employment Duration
- Age Groups
- Goods Price Categories
- Family Demographics
- Housing Status
- Employment Types

## 📈 Analysis Methodology

### 1. Data Preprocessing
- **Missing Value Analysis**
  - Identified and handled missing data
  - Removed columns with ≥40% missing values
  - Applied appropriate imputation strategies

- **Feature Engineering**
  - Converted negative day values to positive
  - Created meaningful categorical bins for numerical features
  - Removed redundant and low-value features

### 2. Feature Analysis
- **Categorical Variables**
  - Contract type distribution
  - Employment type analysis
  - Housing status impact

- **Numerical Variables**
  - Income distribution analysis
  - Credit amount patterns
  - Age group default rates

### 3. Risk Factor Analysis
- Default rates across different segments
- Correlation between features and default probability
- Identification of high-risk customer profiles

## 🛠 Technical Details

### Technologies Used
- Python 3.x
- Pandas for data manipulation
- NumPy for numerical operations
- Matplotlib/Seaborn for visualization
- Jupyter Notebook for analysis environment

## 🤝 Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

## 📝 License
This project is licensed under the MIT License.

## 👥 Authors
- Nhlanhla Mokoena - https://github.com/Murci20965

## 🙏 Acknowledgments
- Kaggle for providing the dataset
- HexSofwares Internship program for project guidance

## 📧 Contact
- nhlanhla18mokoena@gmail.com
- https://github.com/Murci20965/HexSoftwares_Loan_Data_Analysis.


