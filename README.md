# Telecom Customer Churn Analysis and Prediction

This project focuses on analyzing telecom customer data to understand customer behavior and predict customer churn. Customer churn refers to customers leaving or discontinuing a service. By studying churn patterns and building prediction models, businesses can take steps to improve customer retention and reduce revenue loss. The project includes data analysis, visualization, machine learning, and a Power BI dashboard for insights.


## Project Objectives

- Analyze telecom customer data
- Perform data cleaning and preprocessing
- Explore churn patterns using visualizations
- Identify important features affecting churn
- Build a machine learning model to predict churn
- Create an interactive dashboard to present insights


## Dataset

The project uses the IBM Telco Customer Churn dataset.
It contains information such as:

- Customer demographics
- Services used
- Contract type
- Tenure
- Monthly charges
- Churn status

This data helps in understanding customer behavior and building prediction models.

Dataset link: [Telco Customer Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

## Technologies Used
* Power BI
* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook


## Project Structure


Customer-churn-analysis/
│
├── notebooks/ -> EDA and ML notebooks
├── Power BI/ -> Dashboard files (.pbix)
├── data/ -> Dataset CSVs
├── images/ -> Only analysis plots
├── requirements.txt -> Minimal libraries for analysis
├── README.md -> This file
├── .gitignore
├── LICENSE
├── Instruction.pdf


## Exploratory Data Analysis (EDA)

EDA was performed to understand trends and patterns in the dataset.

Steps performed:

- Data cleaning and preprocessing
- Handling missing values
- Feature analysis
- Correlation checks
- Visualizations using charts and graphs

Key observations:

- Month-to-month contracts show higher churn
- Higher monthly charges increase churn probability
- Customers with longer tenure are more likely to stay


## Machine Learning Model

A classification model was built to predict customer churn.

Workflow:

1. Data preprocessing
2. Train-test split
3. Model training using Gradient Boosting
4. Model evaluation

The model outputs churn or non-churn predictions based on customer details. The saved model file (`.joblib`) is optional and primarily for reference.


## Power BI Dashboard

A Power BI dashboard was created to present insights visually.

It helps to:

- Monitor churn rate
- Analyze customer segments
- Compare different customer groups
- Understand revenue impact
- Identify high-risk customers

To view the dashboard, open the `.pbix` file inside the Power BI folder using Power BI Desktop.


## How to Run

Install dependencies:

pip install -r requirements.txt

* Start Jupyter Notebook:

jupyter notebook

Open and run the notebooks to explore the analysis and model.

##Summary

This project demonstrates the workflow of:
Data preprocessing
Exploratory data analysis
Machine learning model building
Business insights through dashboards
It provides practical understanding of how data can be used to predict customer churn and support better decision-making.

##Author

#Devanshi Parmar
GitHub: https://github.com/devanshiiparmar

For further inquiries or to discuss potential collaborations, please feel free to connect with me.
