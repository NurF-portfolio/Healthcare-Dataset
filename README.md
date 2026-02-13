# Healthcare Dataset Analysis

## Overview

This project focuses on cleaning, analyzing, and visualizing a healthcare dataset sourced from Kaggle. Python and Google Colab were used for data cleaning and exploratory data analysis (EDA), while Power BI was utilized for data visualization. The project aims to ensure high data quality and deliver meaningful insights through clear and effective visualizations.

## Data sourced

This dataset consists of 10,000 records, each representing a synthetic patient healthcare record. It includes various attributes such as patient demographics, medical conditions, and admission details. The dataset is intended for educational and non-commercial use and is entirely synthetic, containing no real patient information.

## Tool Used

- **Python (via Google Colab)** – Used for data cleaning, processing, and exploratory data analysis (EDA).
- **Google Colab** – Development environment for Python notebooks. 
- **Power BI** – Used to create interactive and insightful data visualizations

## Project Structure

```
Healtcare-Datasets/
├── LICENSE
├── README.md
├── Notebooks         
│   └── Healthcare_Data_Analysis.ipynb             # Python language via Google Colab
├── Data/
│   ├── Raw/                                       # Original dataset from Kaggle (Healthcare Dataset)
│   └── Cleaned/                                   # Cleaned dataset (processed using Python via Google Colab)
├── Reports/
│   └── Healthcare Data Analysis Dashboard.PNG     # Power BI dashboard screenshots
│   └── Healthcare Data Sales Dashboard.PNG        # Power BI dashboard screenshots
└── PowerBI/
    └── Healthcare Data Analysis Dashboard.pbix
```
## How to run / view project

1. Download the raw dataset from the data/raw/ folder in the project repository.
2. Download the Colab notebook (.ipynb) from the notebooks/ folder.
3. Open the notebook in Google Colab.
4. Ensure all required Python libraries (listed in the notebook, e.g., pandas, numpy, matplotlib) are installed.
5. Run the code cells sequentially to clean, process, and analyze the data. The cleaned dataset will be saved in data/cleaned/.
6. Explore the visualizations in Power BI using the processed dataset provided.
 
## Methodology

This project follows a structured end-to-end data analysis workflow, starting from data preprocessing in Python to interactive dashboard development in Power BI.

1. Data Collection
   - Dataset obtained from [Kaggle](https://www.kaggle.com/datasets/prasad22/healthcare-dataset)

2. Data Cleaning & Preprocessing (Python – Google Colab)  
   - Checked for missing values and duplicates
   - Verified data types for consistency     
   - Converted data types for accurate analysis  
   - Created new calculated features to enhance insights

3. Exploratory Data Analysis (EDA)  
   - Analyzed data distributions and key metrics  
   - Identified trends, patterns, and relationships  
   - Generated visualizations using Matplotlib and Seaborn  

4. Data Preparation for Dashboard  
   - Aggregated and transformed data for reporting  
   - Basic data modeling in Power BI
   - Exported cleaned datasets for use in Power BI dashboards

5. Dashboard Development (Power BI)  
   - Designed interactive dashboard layout  
   - Created KPI indicators 
   - Developed slicers and filters for dynamic analysis  


## Key Findings / Insights
- July recorded the highest total billing amount (122,755,334.67), which was 13.78% higher than February, the lowest month (107,892,482.27). July contributed 8.66% of the overall billing amount.
- Ibuprofen was the most common medication among patients with abnormal test results, representing 6.76% of total patients.
- The Abnormal test result category had the highest average number of patients (3,275.60), followed closely by Normal (3,260.60) and Inconclusive (3,228), indicating a relatively balanced distribution across result types.


## Visualization Preview

Healthcare Data Analysis Dashboard
![Dashboard Screenshots](https://github.com/NurF-portfolio/Healthcare-Dataset/blob/98dc840a1b845f728954ab012210b499171a132b/Reports/Healthcare%20Data%20Analysis%20Dashboard.PNG)

Healthcare Data Sales Dahsboard
![Dashboard Screenshots](https://github.com/NurF-portfolio/Healthcare-Dataset/blob/98dc840a1b845f728954ab012210b499171a132b/Reports/Healthcare%20Data%20Sales%20Dashboard.PNG)


## Conclusion
The hospital dataset shows clear patterns in patient demographics, hospital stays, and billing activity. Patients around age 38 represent the largest group, with balanced gender distributions, and most admissions are Elective or Emergency. Lengths of stay typically range from 11 to 21 days, varying by age, condition, and admission type. Billing amounts differ by patient characteristics, medical conditions, and medications, with Obesity and Ibuprofen associated with higher totals. Overall, the data highlights key trends in hospital utilization and finances, providing actionable insights for operational planning and healthcare management.


## License

This project is shared under the Creative Commons Attribution-NoDerivatives 4.0 International License (CC BY-ND 4.0).  
You are welcome to view and share the work, but you may not modify it in any way. Please give appropriate credit when sharing.  

More information: [CC BY-ND 4.0 License](https://creativecommons.org/licenses/by-nd/4.0/)
