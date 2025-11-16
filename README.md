I am currently working on the Kaggle competition Juan López created. 
You are given the info for all the fights until 2023 and you have to predict 2024 and 2025 fights.
All the things that are in the notebook are what worked for the dataset.
I am trying to create time series lags for the fights, so to predict every fight the model is given the info about whether the fighter won or last his/her previous fights.
Once I create them, I will use partial autocorrelation to determine which lags are the most important.
