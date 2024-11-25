# Revealing Customer Shopping Trends Dataset
## Project Overview

The goal of this project is to analyze different aspects of customer buying preferences to investigate what affects the review rating. By utilizing different kinds of charts PowerBI has to offer, stakeholders can find out important insights on how to improve the rating.

## Table of Contents

1. Project Overview
2. Dataset
3. Objectives
4. Technologies Used
5. How to Run the Project
6. Key Insights
7. Next Steps
8. Contributing
9. License

### Dataset

The dataset introduces a publicly available Kaggle dataset of a fictional clothing store. The CSV file includes synthetic data of 3900 distinct customers who made purchases and left reviews.

- ***Source***: [Shopping Trends Dataset](https://www.kaggle.com/datasets/iamsouravbanerjee/customer-shopping-trends-dataset/data)
- ***Date Range***: Not Applicable  
- ***Size***: 406 KB (filtered dataset)

### Objectives

- Identify the current average review rating and how far is it from the target value.
- Investigate variables that affect the review rating, eg. purchase history, subscription, demographics, buying preferences etc.
- Figure out which states have the highest and lowest rating, and factors contributing to it.

### Technologies Used
- ***PowerBI***: For all stages: validating and cleaning data, aggregating data, and creating dashboards.
- ***Git & GitHub***: For version control and sharing the project.

### How to Run the Project
#### Prerequisites
- Power BI or any tool that can open .pbix files.
#### Steps
1. Clone the repository:
```
git clone https://github.com/Ignacy98/customer_shopping_trends.git
cd customer_shopping_trends
```
2. Data Setup:
   - Download the dataset from ```shopping_trends_updated.csv```;
   - Place the dataset in the ```data/``` directory of the repository.
3. Load CSV Files (optional):
   - Open and load CSV files into PowerBI or Power BI Service and create customized visualizations.
4. View Visualizations:
   - Download a ```Customer Shopping Trends Dataset.pbix``` or open ```.jpg``` files to view dashboards.

### Key Insights

- ***Rating's below the target value***: the average review rating equals 3.78, which is 11% below the target value of 4.25.
- ***Purchase history and subscription have nothing to do with rating***: no evidence that purchase history or subscription status affected the review rating.
- ***Men give higher ratings***: male customers rate their purchases 4% higher that female.
- ***Highest vs lowest rating items***: Footwear gets the highest rating, Clothing the lowest. The best-reviewed item is Gloves, the worst-reviewed is Shirts. The gold color items get the highest rating, gray items get the lowest.
- ***States with the best and worst reviews observed***: In Texas customers leave the highest reviews, the lowest are in West Virginia.

### Next Steps

- Perform the analysis from the sales' perspective by identifying items and colors what make the most money.
- Check wether a payment method affects the rating in some way.

### Contributing
Contributions are welcome! If you have suggestions or improvements, feel free to open an issue or submit a pull request.

### License
This project is licensed under the Data License Agreement. Click [here](https://www.kaggle.com/datasets/iamsouravbanerjee/customer-shopping-trends-dataset/data) to see details.
