# Team Project : House Prices: Advanced Regression Techniques
There are several factors that influence the price a buyer is willing to pay for a house. Some are apparent and obvious and some are not. Nevertheless, a rational approach facilitated by machine learning can be very useful in predicting the house price. A large data set with 79 different features (like living area, number of rooms, location etc) along with their prices are provided for residential homes in Ames, Iowa. The challenge is to learn a relationship between the important features and the price and use it to predict the prices of a new set of houses. 

### Team Name : Data_Growl
- Danny Ki [Team Leader]
- Myeonghak Kim
- Yara Cho 

### Competition Description
Our group plans to introduce Ordinary Least Squares model as a regression technique. In our demonstration we will explore how various attributes affect the price of houses. Graphic explanation would mainly be used with minimal mathematical notations.

### Acknowledgments
The Ames Housing dataset was compiled by Dean De Cock for use in data science education. It's an incredible alternative for data scientists looking for a modernized and expanded version of the often cited Boston Housing dataset

### File descriptions
- train.csv : the training set
- test.csv : the test set
- data_description.txt : full description of each column, originally prepared by Dean De Cock but lightly edited to match the column names used here
- sample_submission.csv : a benchmark submission from a linear regression on year and month of sale, lot square footage, and number of bedrooms

### Evaluation Method
Submissions are evaluated on Root-Mean-Squared-Error (RMSE) between the logarithm of the predicted value and the logarithm of the observed sales price. (Taking logs means that errors in predicting expensive houses and cheap houses will affect the result equally.)

### Competition Timeline
- Start Date: 8/30/2016 1:08 AM UTC
- Merger Deadline: None
- Entry Deadline: None
- End Date: 3/1/2017 11:59 PM UTC

### Result
- Model : Ordinary Least Squares regression
- Kaggle Score : 0.12384
- Kaggle rank : 1042 / 4548 (22.9%) [2018.3.13]
