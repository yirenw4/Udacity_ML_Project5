## Udacity_ML_Project5
- Using Machine Learning Algorithms XGBoost Classifer to predict the drection of the opening price of SSE Composit Index

### Purpose
- The purpose of this project is to apply the XGBoost classifier into the China's stock market to determine where XGboost classifier can be used to predict the directionality of Open Price of SSE Composite index (up or down). In this project, the label will be defined as "1" if the predicted Open price goes up relaive to the Open price in the last day.

### Usage 
To run the project, please open the jupyter notebook Stock_Price_Project.ipynb

### Data 
All data used for this project comes from Yahoo Finance:

[https://finance.yahoo.com/quote/000001.SS/history?p=000001.SS]

The data is the historical data from 2000-06-08 to 2020-6-05.  And the raw data is included in the file "000001.SS_new.csv". And it contains 6 fileds discussed below.

- Date: calendar date for any given data row
- Open: opening value (recorded at 9:30) for the SSE
- High: highest value on any given day for the SSE
- Low: lowest value on any given day for the SSE
- Close: closing value (recorded at 16:00) for the SSE
- Volume: number of shares of SSE components traded

The raw data consists of 4959 trading days. 

### Libaries Used
- scikit-learn
- SageMaker

## Additional Documents
- Stock_Price_Project.ipynb: contains code and exploratory data analysis and commentary. Written in Python (3.7) in Jupyter Notebooks
- report.pdf: project report, containing summary of the analyses and key conclusions
- 000001.SS_new.csv: raw data, as discussed in the 'Data' section above
