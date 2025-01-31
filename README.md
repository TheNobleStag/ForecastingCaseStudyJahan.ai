# ForecastingCaseStudyJahan.ai

This is a case study done for a competition in [Kaggle](https://www.kaggle.com/competitions/favorita-grocery-sales-forecasting/overview). The dataset for the code can be downloaded [here](https://www.kaggle.com/competitions/favorita-grocery-sales-forecasting/data).

To set up the environmet run ```pip install -r requirements.txt```

I have used lag 7, lag 14 and rolling mean 7 for model training. Which means I can only predict upto 7 days ahead. Otherwise I would end up using future data which would result in a data leakage.