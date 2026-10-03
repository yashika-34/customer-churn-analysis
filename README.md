"# Customer Churn Analysis

A data-driven project focused on understanding why customers leave a telecom service and identifying the strongest churn drivers. The analysis uses a customer churn dataset to explore contract type, tenure, monthly charges, payment behavior, and service usage patterns.

## Project Objective

The goal of this project is to:

- analyze customer retention patterns,
- identify risk factors associated with churn,
- visualize key trends and customer segments,
- support business decisions for reducing customer attrition.

## Dashboard Summary

This churn analysis highlights the most important business signals behind customer exits:

- month-to-month contracts are strongly associated with churn,
- longer-tenure customers are more stable,
- higher monthly charges may contribute to customer dissatisfaction,
- payment methods and internet services can influence customer retention,
- senior citizens and certain service combinations show elevated churn risk.

The project is structured to provide both a data narrative and a visual dashboard-style summary for stakeholder review.

## Dataset

The project uses the Telco Customer Churn dataset from the telecom domain.

Key columns include:

- customer ID
- gender
- senior citizen status
- partner/dependents
- tenure
- phone/internet service status
- contract type
- payment method
- monthly charges
- total charges
- churn label

Data source: `data/Telco-Customer-Churn.csv`

## Repository Structure

```text
Customer_Churn_Analysis/
├── data/
│   └── Telco-Customer-Churn.csv
├── notebooks/
│   └── churn_analysis.ipynb
├── visuals/
│   ├── churn_distribution.png
│   ├── contract_vs_churn.png
│   ├── internet_service_churn.png
│   ├── monthly_charges_distribution.png
│   ├── payment_method_churn.png
│   ├── senior_citizen_churn.png
│   ├── tenure_distribution.png
├── presentation/
├── reports/
├── sql/
├── README.md
├── requirements.txt
└── .gitignore
```

## Tools and Libraries

This project is built using Python and common data science libraries, including:

- pandas
- matplotlib
- seaborn
- numpy
- scikit-learn

See `requirements.txt` for the full dependency list.

## Key Visuals

### Churn Distribution

![Churn Distribution](./visuals/churn_distribution.png)

This chart shows the overall proportion of churned versus retained customers, helping to establish the baseline problem.

### Contract Type vs Churn

![Contract Type vs Churn](./visuals/contract_vs_churn.png)

This visual helps reveal how contract length relates to customer retention and churn risk.

### Internet Service and Churn

![Internet Service vs Churn](./visuals/internet_service_churn.png)

This chart highlights differences in churn based on the type of internet service customers use.

### Monthly Charges Distribution

![Monthly Charges Distribution](./visuals/monthly_charges_distribution.png)

This visualization shows how charges are distributed and whether higher bills align with churn risk.

### Payment Method and Churn

![Payment Method vs Churn](./visuals/payment_method_churn.png)

This chart explores whether specific payment methods correlate with churn and retention behavior.

### Senior Citizen Churn

![Senior Citizen vs Churn](./visuals/senior_citizen_churn.png)

This view helps assess whether senior citizen status is associated with different churn patterns.

### Tenure Distribution

![Tenure Distribution](./visuals/tenure_distribution.png)

This analysis provides insight into how customer lifetime and tenure relate to churn outcomes.

## Dashboard Perspective

The visual outputs together form a dashboard-style story for business stakeholders:

1. Churn baseline and customer loss trend
2. Contract structure as a retention driver
3. Pricing and service plan impact
4. Payment behavior and retention signals
5. Customer segment risk factors such as senior citizenship and service category

This dashboard helps teams prioritize retention campaigns and identify the customer groups most likely to churn.

## Notebook

The full exploratory analysis and visual generation are contained in:

- `notebooks/churn_analysis.ipynb`

The notebook walks through data preparation, exploratory analysis, key feature review, and visual storytelling.

## How to Run

1. Open the project in a Python environment.
2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Launch the notebook:

```bash
jupyter notebook notebooks/churn_analysis.ipynb
```

## Business Impact

This analysis can help customer success and retention teams:

- target high-risk accounts earlier,
- tailor retention offers by contract type or payment method,
- better understand customer complaints and churn motivations,
- prioritize interventions for at-risk segments.

## License

This project is intended for educational and analytical use.

## Author

Customer Churn Analysis project
" 
