# Education-Analytics
Personalized Education Analytics for online learning platforms


This project aims to analyze user engagement and learning outcomes using a dataset on online learning platforms. It intends to recommend personalized content or learning paths using this analysis. 

---

## Table of Contents 
1. [Notebooks](#notebooks)
2. [Data](#data)
3. [Results](#results)
4. [Dashboard](#dashboard)
5. [Requirements](#requirements)
6. [How to Run](#how-to-run)
7. [Key Insights](#key-insights)

--- 

## Notebooks

The analysis is structued into three notebooks: 
1. [Overview_EDA_Notebook](Notebooks/01_Overview_EDA.ipynb) -> Cleaning and Exploratory Data Analysis
2. [Feature_Engineering_Notebook](Notebooks/02_Feature_Engineering.ipynb) 
3. [Recommendation_Engine Notebook](Notebooks/03_Recommendation_Engine.ipynb) 
--- 

## Data 

The following dataset from Kaggle has been used for this project. 

[https://www.kaggle.com/datasets/adilshamim8/personalized-learning-and-adaptive-education-dataset?select=personalized_learning_dataset.csv]
- The dataset is downloadable and cen be opened locally.

---
 
## Results 

Excel summaries of the intermediate results are included in the 'Datsets/' folder

> Note: Some files may not render on GitHub due to size. Please download to view them locally.


--- 

## Dashboard 

To explore the interative Power BI dashboard, download [Project_Dashboard](Dashboard/Dashboard.pbix) and view it using Power BI Desktop 

## Requirements 

- Python 3.12.11 (or higher)
- Pandas
- Numpy
- Matplotlib
- Seaborn
- Scikit-learn

Install dependencies with: 

```bash
pip install -r requirements.txt 
```

## How to Run 

1. Open the notebooks in Google Colab or Jupyter Notebook
2. Ensure that all dependencies are installed
3. Run the notebooks sequentially:
  
--- 

## Key Insights 

* Time spent on videos is right-skewed; forum participation is spread out, and assignment completion is somewhat skewed towards higher completion.
* Final exam scores and quiz scores are spread out.
* Age has a roughly uniform distribution. Gender is balanced betwen male and female.
*  Droput likelihood is low, while engagement levels are moderate.
*  All courses have a similar median score at around 65
*  Learning style has no noticeable impact on final exam performance.




