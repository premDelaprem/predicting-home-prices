### Contents ###
The below information conveys strategies I used to build and evaluate a model to predict housing prices in Ames, Iowa as part of a Kaggle competition.

---
1. Data Cleaning
> a. Observe missing values <br>
> b. Dropping vs. Imputing <br>
> c. Deciding imputing technique

2. EDA, Feature Engineering & Selection
> a. Scatter plots <br>
> b. Correlations to determine importance of features <br>
> c. Fine tuning selected features using Lasso
> d. Outlier analysis
> e. Preprocessing (scaling data, train/test splits, transforming data)

3. Modeling, Evaluation, Comparisons
> a. Building models <br>
> b. Evaluating r2 scores <br>
> c. Evaluating RMSE <br>

4. Conclusion <br>
---

The remainder of the notebook contains my code, visualizations, and analysis of the housing dataset as I attempt to build a predictive model that focuses on minimizing root mean squared error (RMSE).

---

### Data ###
The data is dervied from a 2011 housing set from Kaggle. The dataset is densely packed and contains granular housing information for homes in Ames, Iowa.

Visit https://www.kaggle.com/competitions/1113-ames-competition/data for a detailed Data Dictionary