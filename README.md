
## Credit Risk Modeling 

### Project Overview
This project aims to analyze credit risk using machine learning techniques. It includes data preprocessing, exploratory data analysis (EDA), feature engineering, model training, and evaluation. The goal is to develop a predictive model that assesses the likelihood of loan default.
## Datasets 
The project uses financial datasets related to credit risk. The following datasets are included:

 - **Credit_Risk_01.xlsx.csv:** Contains financial data related to loan applications.

 - **Credit_Risk_02.xlsx.csv:** Additional dataset with complementary information.

 -  **Features_Target_Description.xlsx.csv:** Provides a description of features and target variables.



### project Structure


```bash 
├── data/		       # Raw and processed datasets
├── notebooks/    # Vscode and  Colab for analysis and model building
├── models/	      # Trained machine learning models
├── reports/	     # Documentation and findings
├── README.md	    # Project description
```
    
## Installation
1. Clone the repository:
```bash
git clone https://github.com/SandeepSuthar169/Credit-Risk-Modeling-Project.git
```
2. Navigate to the project directory:
```bash
 cd Credit_Risk_Analysis
```
3. Create a virtual environment and activate it:
```bash
python -m venv .ven
.ven\Scripts\activate
```
4. Install dependencies:
```bash
pip install -r requirements.txt
```
## User
Run the Vscode and colab inside the notebooks/ directory to explore data and train models:
```bash 
 - Vscode
 - Colab 
```
## Methodology
1. Data Preprocessing

- Handle missing values

- Feature encoding

- Data normalization and scaling

2. Exploratory Data Analysis (EDA)

- Visualize key features

- Identify correlations and VIF(Variance Inflation Factor)

3. Feature Engineering

- Create meaningful features

- Remove redundant information

4. Model Training & Evaluation

- Train multiple models ( Random Forest )

- Evaluate performance using 
1. classp1:- 
- Precision:- 0.822
- Recall:- 0.717
- F1 Score:- 0.766

2. classp2:- 
- Precision:- 0.816
- Recall:- 0.936
- F1 Score:- 0.872

3. classp3:- 
- Precision:- 0.437
- Recall:- 0.199
- F1 Score:- 0.273

4. classp4:- 
- Precision:- 0.719
- Recall:- 0.709
- F1 Score:- 0.714
                                    

## Results
The final model is evaluated based on precision, recall, and overall prediction accuracy. The best-performing model is deployed for further analysis.
