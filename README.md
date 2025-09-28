# IT2011-Group-Assignment

Project Overview

This project is part of IT2011 – Group Assignment (Progress Evaluation I). The focus is on Data Preprocessing and Exploratory Data Analysis (EDA) to prepare a dataset for forecasting tasks. Each group member handled a different preprocessing technique, and the group combined them into a single preprocessing pipeline.

Dataset Details

Dataset Name: stores_sales_forecasting.csv

Description: Contains historical sales records from multiple stores, including features such as store information, sales, profit, and order dates.

Purpose: The dataset is used to demonstrate data preprocessing, transformation, and EDA techniques in preparation for building predictive models.

Location: data/raw/stores_sales_forecasting.csv

Group Member Roles

Each group member was responsible for one preprocessing technique:

Member 1 (IT24610815): Discretization / Binning

Member 2 (IT24104350): Encoding Categorical Variables

Member 3 (IT24104025): Outlier Detection and Removal

Member 4 (IT24103968): Normalization / Scaling

Member 5 (IT24104008): Feature Engineering

Member 6 (IT24103956): Data Transformation (Yeo-Johnson)

All individual work is stored in separate notebooks under the notebooks/ folder. The group pipeline notebook (group_pipeline.ipynb) combines all techniques.

How to Run the Code

Clone the repository:

git clone https://github.com/<username>/IT2011-Group-Assignment.git
cd IT2011-Group-Assignment


Install dependencies:

pip install -r requirements.txt


Run Jupyter Notebook or Colab:

jupyter notebook


Open the desired .ipynb file from the notebooks/ folder or run the group_pipeline.ipynb to execute the complete preprocessing pipeline.

Outputs & Results:

EDA visualizations: saved in results/eda_visualizations/

Transformed dataset: saved in data/processed/
