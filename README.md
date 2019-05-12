# Team Project : House Prices: Advanced Regression Techniques
There are several factors that influence the price a buyer is willing to pay for a house. Some are apparent and obvious and some are not. Nevertheless, a rational approach facilitated by machine learning can be very useful in predicting the house price. A large data set with 79 different features (like living area, number of rooms, location etc) along with their prices are provided for residential homes in Ames, Iowa. The challenge is to learn a relationship between the important features and the price and use it to predict the prices of a new set of houses. 

### Team Name : Data_Growl
- Danny Ki [Team Leader]
- Myeonghak Kim
- Ara Cho 

### Competition Description
Our group plans to introduce Ordinary Least Squares model as a regression technique. In our demonstration we will explore how various attributes affect the price of houses. Graphic explanation would mainly be used with minimal mathematical notations.

### Acknowledgments
The Ames Housing dataset was compiled by Dean De Cock for use in data science education. It's an incredible alternative for data scientists looking for a modernized and expanded version of the often cited Boston Housing dataset

### File descriptions
- train.csv : The training set
- test.csv : The test set
- data_description.txt : Full description of each column
- sample_submission.csv : Sample submission file

### Evaluation Method
Submissions are evaluated on Root-Mean-Squared-Error (RMSE) between the logarithm of the predicted value and the logarithm of the observed sales price. 

RMSE = <img src="https://latex.codecogs.com/gif.latex?%5Csqrt%7B%5Cfrac%7B1%7D%7Bn%7D%5CSigma_%7Bi%3D1%7D%5E%7Bn%7D%7B%5CBig%28%5Cfrac%7Bd_i%20-f_i%7D%7B%5Csigma_i%7D%5CBig%29%5E2%7D%7D">

### Competition Timeline
- Start Date: 8/30/2016 1:08 AM UTC
- Merger Deadline: None
- Entry Deadline: None
- End Date: 3/1/2017 11:59 PM UTC

### Prediction
- Model : Ordinary Least Squares regression
- Kaggle Score : 0.12384
- Kaggle rank : 1042 / 4548 (22.9%) [ 2018.3.13 ]
