# Customer Churn Analysis and Prediction

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

Here’s how the project is organized:
notebooks/ – Jupyter notebooks for data analysis and machine learning. Explore these to see the EDA, feature analysis, and model training.
Power BI/ – Contains the dashboard files (.pbix) that visualize customer churn and insights. Open them in Power BI Desktop.
data/ – All the dataset files (.csv) are stored here.
images/ – Contains charts and plots generated during analysis. Only visualizations.
requirements.txt – Lists the Python libraries needed to run the notebooks.
README.md – You are reading it! Explains the project and how to use it.
.gitignore – Files and folders that Git will ignore.
LICENSE – The project license.
Instruction.pdf – Any instructions or documentation included by the author.


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
We trained a Gradient Boosting classification model to understand customer churn patterns.

The workflow includes:

- Data preprocessing
- Splitting the data into training and test sets
- Training the Gradient Boosting model
- Evaluating model performance

The model helps identify which customers are more likely to churn based on their features. 
The saved model file (`.joblib`) is included for reference but is not required to run the notebooks.


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

## Summary

This project demonstrates the workflow of:
Data preprocessing
Exploratory data analysis
Machine learning model building
Business insights through dashboards
It provides practical understanding of how data can be used to predict customer churn and support better decision-making.

## Author

#Devanshi Parmar
GitHub: https://github.com/devanshiiparmar

For further inquiries or to discuss potential collaborations, please feel free to connect with me.
