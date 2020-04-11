# Earnings-Prediction-using-WRDS
# Introduction
This project involves building forecasting models based on cross-sectional or panel data to predict future earnings of a company. 
The data source for the project has been sourced from WRDS(Wharton Reaserch Data Services) that hosts a repository of all publicly traded firms' financial and accounting data. 

https://wrds-www.wharton.upenn.edu/

# Project Explanation and Methodology
The main aim of this project is to work with existing financial models like Random Walk, HVZ, Earnings Persistence and Residual Income models to understand how much of variance and accuracy they provide for earnings prediction.Further building on this, I have also worked on improving the performance of existing models by augmenting additional features by conducting feature engineering and theoretical research on financial data. The important metrics that were used to decide on best performing model are bias and accuracy of prediction when compared to financial analysts forecasts, which is also sourced from WRDS.

# Results and Conclusion
From the above analysis, it was found that most of the models only explain 15 to 20 percent of variance while predicting earnings. The reasons are obvious that a firm's earnings are influenced and controlled by huge number factors, both external and internal to the company, which may not be quantifiable. Out of the 4 different models, HVZ performed best in terms of bias and accuracy for prediction. This model was further tried to be improved by including additional features which slighlty improved the model performance by ~2 to 3%. For future work, soft information like textual data from Management Discussions, earnings call or Investor forums like Seeking Alpha can be incorporated through text and NLP analysis to observe the change in model prediction.
