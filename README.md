# US County-Level Election Analysis

## Project Title:
**The Impact of Social and Economic Factors on U.S. Election Outcomes at the County Level**

## Description
This project's aim is to analyze the how socioeconomic factors influence the US's election results in county level. We will analyze various social factors, such as race, education, and marital status, and economic factors, such as GDP, to understand which socioeconomic factors have the most impact on the election results, and possibly building a machine learning model that can predict the election results effectively given our variables in our datasets. Research Question: How do socioeconomic factors influence U.S. election outcomes at the county level?

The datasets used in this project are U.S. Census and Election Results dataset from Kaggle, which is our main dataset, and GDP by County. The US Census and Election Results dataset combines U.S. county-level demographics, economic, and election data from 2000 to 2020. The dataset integrates information from multiple resources: U.S. Census Bureau, the Bureau of Economic Analysis, and MIT Election data. In this project, this dataset is merged with GDP by County dataset to further investigate the election results. As a result, the merged dataset includes socioeconomic variables from 2005 to 2018. You can find the U.S. Census and Election Results dataset in the following link: [Visit Kaggle Dataset](https://www.kaggle.com/datasets/minhbtnguyen/us-census-for-election-predictions-20002020/data)

## Objective
- Investigate how economic indicators (e.g., GDP, unemployment) and social indicators (e.g., education, population composition) correlate with U.S. election outcomes.
- Build predictive models to assess the impact of these variables on voting behavior at the county level.

## Data Sources
- `county_census_and_election_result.csv` — Census and election data by county
- `GDP by County.csv` — County-level GDP data

## Tools & Technologies
- Python
- Pandas, NumPy, Scipy, Scikit-learn, XGBoost
- Matplotlib, Seaborn
- Jupyter Notebook

## Repository Structure
- data/ # Raw datasets
- notebooks/ # Main analysis notebook
- README.md # Project documentation
- requirements.txt # Python dependencies
- variables_requirement.txt # Detailed explanation of variables 

## Results Summary
- Identified key economic and social predictors for election outcomes.
- Built regression/classification models to predict election results.
- Visualized correlations and key relationships between variables.

## Future Work
- Include more recent data.
- Add additional predictors (e.g., voter turnout, campaign spending).

## Contact
If you have any questions, feel free to contact me at jrgllshnn@gmail.com.
