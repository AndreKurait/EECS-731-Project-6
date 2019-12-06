# EECS 731 Project 6

This is Andre Kurait's sixth project for EECS 731, Data Science in Fall 2019.
For this project, I analyzed several anomaly detection models on taxi data.

## Project Requirements
### D(St)reams of Anomalies
The real world does not slow down for bad data
1. Set up a data science project structure in a new git repository in your GitHub account
2. Download the benchmark data set from https://www.kaggle.com/boltzmannbrain/nab or https://github.com/numenta/NAB/tree/master/data 
3. Load the one of the data set into panda data frames
4. Formulate one or two ideas on how feature engineering would help the data set to establish additional value using exploratory data analysis
5. Build one or more anomaly detection models to determine the anomalies using the other columns as features
6. Document your process and results
7. Commit your notebook, source code, visualizations and other supporting files to the git repository in GitHub

## Project structure
```bash
.
├── Data
│   └── Historical_Product_Demand.csv
├── README.md
└── Shipping.ipynb
```

## Conclusion
Overall, I was not able to some accuracy in predicting demand. It wasn't great, but I learned a lot about the ARIMA and Seasonal ARIMA models.