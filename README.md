# codealpha_amazon_eda
📊 Exploratory Data Analysis — Amazon Sales Dataset
CodeAlpha Data Analytics Internship | Task 2

📌 Overview
This project performs a comprehensive Exploratory Data Analysis (EDA) on the Amazon Sales Dataset. The goal is to uncover trends, patterns, and anomalies in product pricing, discounts, ratings, and categories using Python.

📂 Dataset

Source: Amazon Sales Dataset — Kaggle
File: amazon.csv
Size: 1,465 products across multiple categories
Key Columns: product_name, category, actual_price, discounted_price, discount_percentage, rating, rating_count, review_content


🔍 What's Covered
StepDescriptionData LoadingLoad and preview the datasetData CleaningFix data types, remove ₹/% symbols, handle nulls & duplicatesUnivariate AnalysisDistributions of ratings, prices, discounts, categoriesBivariate AnalysisDiscount vs Rating, Price vs Price, Rating by CategoryOutlier DetectionIQR method with boxplots for all numeric featuresCorrelation HeatmapRelationships between all numeric variablesKey FindingsAuto-printed summary of insights

💡 Key Insights

Most products are rated between 3.8 – 4.5 out of 5
Average discount across all products is around 47%
Higher discounts do not strongly correlate with higher ratings
Price has significant high-end outliers — a few premium products skew the distribution
Electronics and Computers dominate the product count


🛠️ Tools & Libraries
Python 3.x
Pandas
NumPy
Matplotlib
Seaborn
Jupyter Notebook

▶️ How to Run

Clone this repository

bashgit clone https://github.com/amnanawaz28/codealpha_amazon_eda

Install dependencies

bashpip install pandas numpy matplotlib seaborn

Download amazon.csv from Kaggle and place it in the project folder
Open and run the notebook

bashjupyter notebook amazon_eda.ipynb


🏢 Internship
Organization: CodeAlpha
Domain: Data Analytics
Task: 2 of 4
