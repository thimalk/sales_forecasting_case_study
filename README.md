
# Sales Forecast Case Study

Kaggle competition case study on [Corporación Favorita Grocery Sales Forecasting](https://www.kaggle.com/competitions/favorita-grocery-sales-forecasting/overview). All three notebooks can run on [colab](https://colab.research.google.com/)

## Python Notebooks

1. Get External data `extract_temp_data.ipynb` 
  * This noetbook extract data from [worldweatheronline](https://www.worldweatheronline.com/developer/api/historical-weather-api.aspx) and you need to create free acount to access the data 
2. Exploratory analysis `favorita_exploratory_analysis.ipynb`
  * Data clearning
  * This notebook will explore each feature and target value to identify insight needed for forecasting modeling (from sample dataset) 
  * `whole_dataset_exploratory_analysis.ipynb` notebook will explore the complete dataset need at least 32GB to run.
3. Forecasting `favorita_exploratory_analysis.ipynb`
  * This script run the basline model and two other models base on [LGBM](https://lightgbm.readthedocs.io/en/latest/) and NN(Tensorflow)



