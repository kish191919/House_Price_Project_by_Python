# Project : House Prices: Advanced Regression Techniques
This is a perfect competition for data science students who have completed an online course in machine learning and are looking to expand their skill set before trying a featured competition. 

### Competition Description
Ask a home buyer to describe their dream house, and they probably won't begin with the height of the basement ceiling or the proximity to an east-west railroad. But this playground competition's dataset proves that much more influences price negotiations than the number of bedrooms or a white-picket fence.

With 79 explanatory variables describing (almost) every aspect of residential homes in Ames, Iowa, this competition challenges you to predict the final price of each home.

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
