
## Credit Risk Modeling 

### Project Overview
This project aims to analyze credit risk using machine learning techniques. It includes data preprocessing, exploratory data analysis (EDA), feature engineering, model training, and evaluation. The goal is to develop a predictive model that assesses the likelihood of loan default.
## Datasets 
The project uses financial datasets related to credit risk. The following datasets are included:

 - **Credit_Risk_01.xlsx.csv:** Contains financial data related to loan applications.

 - **Credit_Risk_02.xlsx.csv:** Additional dataset with complementary information.

 -  **Features_Target_Description.xlsx.csv:** Provides a description of features and target variables.

### Features Target Variable and Description 

| Case_study1 table | Variable     |       Description                 |
| :-------- | :------- | :-------------------------------- |
| Internal      | Total_TL | Total trade lines/accounts in Bureau
| | TOt_Closed_TL | TOtal closed tradeline/accounts |
| |Tot_Active_TL  | Total active accounts|
| |Total_TLopened_L6M | Total accounts opened in laset 6 Months|
| |Tot_TL_closed_L6M  | Total accounts closes in laset 6 Months|
| |pct_tl_open_L6M    | Percent accounts opened in last 6 months|
| |pct_tl_closed_L6M  | percent accounts cloded in  last 6 months|
| |pct_active_tl      | Percent active accounts|
| |pct_closed_tl      | Percent closed accounts|
| |Total_TL_opened_L12M| Total accounts opened in last 12 Months|
| |Tot_TL_closed_L12M  | Total accounts closed in lat 12 Months|
| |pct_tl_open_L12M    | Percent accounts opened in last 12 months|
| |pct_tl_closed_L12M  | percent accounts closed in last 12 months|
| |Tol_Missed_Pmnt     | Total missed Paymants|
| |Auto_TL |Countombile accounts|
| |CC_TL |Count of Credit cart accounts|
| |Consemer_TL |Counts of Consumer goods accounts|
| |GOld_TL |Count of Gold loan accounts|
| |Home_TL |Count of Housing loan accounts|
| |PL_TL |Count of Personal loan accounts|
| |Secured_TL |Count of secured accounts|
| |Unsecured_TL |Count of unsecured accounts|
| |Other_TL |Count if other accounts|
| |Age_oldet_TL|Age of oldest opened account|
| |Age_Newest_TL |Age of newest opened accounts|
| Case study2 Table| | |
|Ciblil|time_since recent_payment|Time Since recent Payment made|
|External|time_since_first_deliquency|Time seice first Deliquency(midded payment)|
| |time_since_delinquent|Time Since recent Delinquency|
| |num_times_delinquent |Number of times Deliquency|
| |max_delinquency_level| maximum delinquency level|
| |max_recent_level_of_deliq|Maximun recent level if delinquncy |
| |num_deliq_6mts|Number of times delinqunts in last 6 months|
| |num_deliq_12mts|Number of times delinqunts in last 12 months|
| |num_deliq_6_12mts|Number of times delinquents between last 6 months and last 12 months|
| |max_deliq_6mts|Maximum delinquency level in last 6 months|
| |max_deliq_12mts|Maximum delinquency level in last 12 months |
| |num_times_30p_dpd |Number of times 30+ dpd|
| |num_times_60p_dpd|Number of times 60+ dpd|
| |num_sub|  	Number of sub standard payments - not making full payments|
| |num_sub_6mts	|Number of sub standard payments in last 6 months|
| |num_sub_12mts	|Number of sub standard payments in last 12 months|
| |num_dbt	|Number of doubtful payments|
| |num_dbt_6mts|	Number of doubtful payments in last 6 months|
| |num_dbt_12mts	|Number of doubtful payments in last 12 months|
| |num_lss|	Number of loss accounts|
| |num_lss_6mts|	Number of loss accounts in last 6 months|
| |num_lss_12mts|	Number of loss accounts in last 12 months|
| |recent_level_of_deliq|	Recent level of delinquency|
| |tot_enq|	Total enquiries|
| |CC_enq	|Credit card enquiries|
| |CC_enq_L6m	|Credit card enquiries in last 6 months|
| |CC_enq_L12m|	Credit card enquiries in last 12 months|
| |PL_enq|	Personal Loan enquiries|
| |PL_enq_L6m|	Personal Loan enquiries in last 6 months|
| |PL_enq_L12m|	Personal Loan enquiries in last 12 months|
| |time_since_recent_enq|	Time since recent enquiry|
| |enq_L12m|	Enquiries in last 12 months|
| |enq_L6m|	Enquiries in last 6 months|
| |enq_L3m|	Enquiries in last 3 months|
| |MARITALSTATUS|	Marital Status|
| |EDUCATION	|Education level|
| |AGE|	Age|
| |GENDER	| |
| |NETMONTHLYINCOME	||
| |Time_With_Curr_Empr|	Time with current Employer|
|  |pct_of_active_TLs_ever	|Percent active accounts ever|
| |pct_opened_TLs_L6m_of_L12m|	Percent accounts opened in last 6 months to last 12 months|
| |pct_currentBal_all_TL|	Percent current balance of all accounts|
| |CC_utilization|	Credit card utilization|
| |CC_Flag	|Credit card Flag|
| |PL_utilization	|Peronal Loan utilization|
| |PL_Flag	|Personal Loan Flag|
| |pct_PL_enq_L6m_of_L12m	|Percent enquiries PL in last 6 months to last 12 months|
||pct_CC_enq_L6m_of_L12m	|Percent enquiries CC in last 6 months to last 12 months|
||pct_PL_enq_L6m_of_ever	|Percent enquiries PL in last 6 months to last 6 months|
| |pct_CC_enq_L6m_of_ever	|Percent enquiries CC in last 6 months to last 6 months|
| |max_unsec_exposure_inPct	|Maximum unsecured exposure in percent
| |HL_Flag	|Housing Loan Flag|
| |GL_Flag|	Gold Loan Flag|
| |last_prod_enq2|	Lates product enquired for|
| |first_prod_enq2|	First productd enquired for|
| |Credit_Score|	Applicant's credit score|
| |Approved_Flag|	Priority levels|


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
