# DEPIGraduationProject

## Overview:
This repository contains the graduation project for the DEPI Data Analysis Track. The dataset being analysed is the Supply Chain dataset.

## Project Structure:
1. **CSVs Folder**: This folder contains all of the CSV files in the project. This includes the original data, split data, and and merged data
2. **PowerBI Folder**: This folder contains the resulting PowerBI dashboard. There is both a .pbix file and a .pdf file of the final result
3. **Queries Folder**: This folder contains the SQL queries used to create the database and populate it with the data from the split CSV files.
4. **Scripts**: This folder contains various python helper scripts that were used during the scope of the project. 
5. **Documentation Final.pdf**: This PDF contains the documentation of the project. All aspecets of the project are covered here, from objectives till results and challenges encountered.
6. **Database Schema.png**: This is a diagram of the project's database schema.
7. **Final DEPI Data Analysis Notebook.ipynb**: This is the jupyter notebook that was used in the project. It had several functions, namely cleaning the data and creating visualizations.

## Objectives:
The project focuses on enhancing supply chain efficiency using data analysis. Key objectives include:
1. **Optimizing Inventory Management**: Analyze stock levels and lead times to align availability with demand, minimizing overstock and shortages.
2. **Reducing Supply Chain Costs**: Streamline logistics by evaluating shipping times, costs, and transportation modes to select more cost-effective solutions.
3. **Minimizing Product Defects**: Identify trends and causes behind defective products to reduce defect rates.
4. **Assessing Manufacturing Efficiency**: Evaluate manufacturing trends in terms of time and cost to improve performance.

## Results:
The dataset of only 100 rows limits detailed conclusions, yet some insights can be drawn:
1. **Defects**: No correlation between shipping time and defect rate suggests manufacturing, not shipping, is the primary cause of defects. Further data is needed for a deeper analysis.
2. **Shipping Costs**: Although average shipping costs were similar across modes, there was significant variability. Sea was cheapest, road costs were stable, while rail and air had similar, but sometimes steep, costs.
3. **Customer Demographics**: With most customers not disclosing gender, demographics were roughly balanced and surprisingly, men were the most profitable group, despite products being marketed to females.
4. **Product Revenue**: A weak relationship between product price and total revenue indicates that selling fewer high-priced items is more lucrative than selling more low-priced ones.
5. **Product Stock Levels**: Stock levels showed irregular patterns with a bimodal distribution, indicating both high and low extremes in stock levels across all suppliers, warranting further investigation.

## Team Members:
1. Aly Mohamed Salama Elsharkawy
2. Amira Osama Abdelghany
3. Marina Magdy Khalaf
4. Ramy Albert Mouris
5. Sarah Hamed Abdelhakim Muhammed

