# Online Retail Data Analysis 
This project is a part of the AAI-550 course in the Applied Artificial Intelligence Program at the University of San Diego (USD). 
-- Project Status: [Completed]

## Installation
1. Open a terminal/command prompt
2. macOS w/ homebrew
    open a terminal and enter:
    brew install python
3. Windows
    open a powershell window and enter: 
    winget install -e --id Python.Python.3
4. In the same CLI install the following packages
    pip install numpy
    pip install pandas
    pip install matplotlib
    pip install seaborn
    pip install plotly
    pip install scikit-learn
    pip install ucimlrepo
    pip install notebook
5. Download a copy of the Jupyter Notebook from the repo
6. In terminal/powershell enter:
    jupyter notebook
7. In the localhost window that is launched from the above command, navigate to downloaded notebook directory and open
  
## Project Intro/Objective
This project centers on a comprehensive analysis of the 2011 Annual Sales for an Online Retail Company, totaling $9,747,748. Notably, the top 5 customers contribute 10% to the business, while the top 5 countries account for a substantial 79%. To enhance strategic planning, a Prediction Model has been developed for total sales per item, offering insights for targeted applications per country and customer.

The current prediction model, while promising, requires further investigation and refinement. Despite limitations, the Random Forest model stands out as the most suitable for predicting Total Sale per Item due to its adeptness with complex, non-linear data. However, there are concerns about potential overfitting, as indicated by perfect scores for Decision Tree and Random Forest models without outliers.

The focus of this data-driven initiative is to gain a comprehensive understanding of the annual business performance from December 2010 to December 2011. The developed prediction model plays a key role in strategizing for the upcoming year, providing forecasts for individual item sales. The versatility of this model allows for its application on a per-country and per-customer basis, with potential for further fine-tuning.

The project utilizes a public dataset sourced from the UCI Machine Learning Repository, offering valuable insights into an online retailer's products, customers, and transactions. With one year of data comprising 541,909 records and 6 variables, including invoice number, stock code, description, quantity, invoice date, unit price, customer ID, and country, the dataset is a rich resource for various data analysis and machine learning tasks. It provides the foundation for exploring patterns and trends in online shopping behavior, including customer segmentation, product recommendation, market basket analysis, and sales forecasting.

Dataset URL: https://archive.ics.uci.edu/dataset/352/online+retail

## Partner(s)/Contributor(s)  
•	Arifa Kokab <br/>
•	Laxmi Sulakshana Rapolu<br/>
•	Andrew Roehr <br/>

## Methods Used
•	Inferential Statistics<br/>
•	Machine Learning<br/>
•	Data Visualization<br/>
•	Data Manipulation<br/>

## Technologies
•	Python<br/>
•	Jupyter Notebook<br/>

## Project Description
Our project aims to analyze the Online Retail dataset, which captures transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail business. Here are the key aspects:

### Dataset Description
Data Source: <br/>
 	•	The dataset was obtained from https://archive.ics.uci.edu/dataset/352/online+retail.<br/>
	•	Number of Variables: It contains 6 variables.<br/>
	•	Size of Dataset: There are 541,909 instances (transactions).<br/>

### Data Dictionary
The dataset includes the following variables:<br/>
	•	InvoiceNo: A 6-digit integral number uniquely assigned to each transaction. If it starts with the letter ‘c’, it indicates a cancellation.<br/>
	•	StockCode: A 5-digit integral number uniquely assigned to each distinct product.<br/>
	•	Description: Product name.<br/>
	•	Quantity: The quantities of each product per transaction.<br/>
	•	InvoiceDate: Represents when each transaction occurred.<br/>
	•	UnitPrice: Product price per unit in sterling.<br/>
Additionally:<br/>
	•	CustomerID: A 5-digit integral number uniquely assigned to each customer.<br/>
	•	Country: Indicates the country where each customer resides.<br/>

### Questions and Hypotheses
Exploratory Questions:<br/>
	◦	What are the most popular products?<br/>
	◦	Are there any seasonal trends in sales?<br/>
	◦	How do customer behaviors differ across countries?<br/>
Hypotheses:<br/>
	◦	Hypothesis 1: High-quantity purchases occur during holiday seasons.<br/>
	◦	Hypothesis 2: Certain products have higher demand in specific countries.<br/>

### Data Analysis, Visualization, and Modeling
Our approach involves:<br/>
	•	Data Cleaning and Preprocessing:<br/>
		◦	Handling missing values (if any).<br/>
		◦	Addressing outliers.<br/>
		◦	Standardizing features.<br/>
	•	Exploratory Data Analysis (EDA):<br/>
		◦	Visualizing product sales over time.<br/>
		◦	Identifying customer segments.<br/>
	•	Feature Engineering:<br/>
		◦	Creating new features (e.g., total transaction amount).<br/>
Modeling:<br/>
	◦	Regression or clustering models.<br/>
	◦	Predicting future sales or customer segments.

### Roadblocks
Challenges:<br/>
	•	Data Quality: Ensuring data consistency and accuracy.<br/>
	•	Model Selection: Choosing appropriate algorithms.<br/>
	•	Interpretability: Making model results understandable for stakeholders.<br/>

## MIT License

## Acknowledgments
We would like to thank Professor Dallin Munger, M.S., for his coursework and guidance. 
