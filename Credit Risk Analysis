# Credit Risk Analysis: What Drives Loan Default?

Exploratory data analysis of 307,511 loan applications from Home Credit, to find which applicant characteristics are linked to loan default.

## Problem Statement
Lenders lose money when applicants default. This project analyzes the financial and demographic attributes of loan applicants to understand what influences default and to suggest ways to reduce lending risk.

## Dataset
| File | Rows | Columns | Description |
|---|---|---|---|
| `application_data.csv` | 307,511 | 122 | Current loan applications. `TARGET` = 1 means the applicant defaulted. |
| `previous_application.csv` | 1,670,214 | 37 | Earlier loan applications of the same clients. |

The data files are not included in this repository because of their size. Download them from the Home Credit Default Risk dataset and place them next to the notebook.

## Tools
Python, Pandas, NumPy, Matplotlib, Seaborn, Jupyter Notebook

## Approach
1. **Data exploration:** checked the structure, data types, and dimensions of the data.
2. **Missing values:** calculated the percentage missing per column and dropped columns with more than 50% missing values.
3. **Data cleaning:** converted day-based fields (`DAYS_BIRTH`, `DAYS_REGISTRATION`, `DAYS_ID_PUBLISH`) into years.
4. **Class imbalance:** found about 11 non-defaulters for every defaulter, so I analyzed the two groups separately instead of comparing raw counts.
5. **Univariate analysis:** pie, count, and percentage bar plots for categorical columns; histograms and distribution plots for numerical columns.
6. **Outliers:** reviewed outliers (for example, one very large income value and applicants with more than 10 children) and flagged them instead of removing valid data.
7. **Merging:** merged the application data with previous applications to study repeat borrowers.
8. **Bivariate analysis:** compared variables such as education and family status against default and approval outcomes.

## Key Findings
- Applicants with secondary education defaulted more often than those with higher education.
- Married applicants defaulted less than single applicants and those in civil marriages.
- Pensioners showed lower default rates. Managers and high-skilled staff were the most reliable repayers.
- Male applicants made up a higher share of defaulters than female applicants.
- Credit amount, annuity, age, and external credit scores (`EXT_SOURCE_2`, `EXT_SOURCE_3`) had different distributions for defaulters and non-defaulters.

## Limitations
- This project is exploratory analysis only. It does not train a predictive model.
- The findings show association, not cause.

## Next Steps
- Build a logistic regression or tree-based model to predict default and evaluate it with ROC-AUC and precision-recall.
- Handle the class imbalance with resampling or class weights.

## How to Run
1. Clone this repository and install the libraries: `pip install pandas numpy matplotlib seaborn jupyter`
2. Place `application_data.csv` and `previous_application.csv` in the project folder.
3. Open `CreditRiskAnalyzer_solutionfile.ipynb` and run all cells.

## Author
**MP Neha** | [LinkedIn](https://linkedin.com/in/neha-mp) | [GitHub](https://github.com/NEHAmp4) | mpneha313@gmail.com
