# AirPollutionAnalysis

Notes: I did this all on Jupyter Notebook, so it might not
translate over to Google Colab perfectly.The presentation 
can be found in this repo. It is titled
"ZhaLeonITP449FinalProject.pd"

OzoneAnalysis.ipynb contains code that I've used to create
several machine learning models to predict Ozone concentrations
in downtown Los Angeles based on other factors such as 
nitrogen oxides and temperature. I start off with a simple
linear regression model, which achieves an accuracy of roughly
57%, then attempt several variations and models before settling
on an XGBoost model with optimized hyperparameters. This last 
model has an accuracy of roughly 60%, which still isn't that high.
However, considering that the predictors I've included aren't 
reflective of all factors that go into tropospheric ozone
formation (specifically, I'm missing hydrocarbons), I think this
was a good jump up in performance. 