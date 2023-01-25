# Online Retail Data Analysis
This project is an analysis of the Online Retail Data Set, which contains all the transactions that occurred between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail. The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers. The data set can be found at https://archive.ics.uci.edu/ml/datasets/Online+Retail

The main objective of this project is to understand the customer behavior and purchase patterns, demographics, and preferences, and use this information to create targeted marketing campaigns and optimize business strategies.

The project begins by cleaning the data and removing any cancelled purchases. Outliers are also identified and removed.

Next, principal component analysis (PCA) and K-Means clustering are used to identify customer segments. The number of clusters is determined using the elbow method. The result is visualized using a scatter plot.

RFM analysis is also performed to identify the most valuable customers. The RFM score is used to segment customers into different groups and a bar chart is used to visualize the result.

The relationship between country and items mostly purchased, as well as the country with the highest sales in both 2010 and 2011, is analyzed. The most popular products and customers who frequently make purchases on the online retail store are also identified.

The project concludes with a summary of possible conclusions and recommendations that can be made based on the analysis.

To view the project and the code, please visit the GitHub repository: https://github.com/ericgwash/Online-Retail-KMeans-RFM-Model-

## Technologies used

Python
Pandas
Numpy
Seaborn
Matplotlib
Sklearn
Plotly

## Requirements

pandas
numpy
seaborn
matplotlib
sklearn
plotly

You can install all the requirements by running the following command in your terminal:

pip install -r requirements.txt


How to run the code

1. Clone the repository

git clone https://github.com/ericgwash/Online-Retail-KMeans-RFM-Model-.git


2. Change the directory to the project folder

cd OnlineRetailAnalysis


3. Run the code

python main.py


Please note that the dataset is not included in the repository, you need to download it from the link provided above and place it in the data folder before running the code.

## Conclusion

This project provides a comprehensive analysis of the Online Retail Data Set. It helps to understand the customer behavior and purchase patterns, demographics, and preferences, which can aid in creating targeted marketing campaigns and optimizing business strategies. Feel free to fork the project and play around with the code to generate different insights.
