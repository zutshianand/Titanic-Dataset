# Titanic-Dataset
The RMS Titanic was a British passenger liner that sank in the North Atlantic Ocean in the early morning hours of 15 April 1912, after it collided with an iceberg during its maiden voyage from Southampton to New York City. There were an estimated 2,224 passengers and crew aboard the ship, and more than 1,500 died, making it one of the deadliest commercial peacetime maritime disasters in modern history. The RMS Titanic was the largest ship afloat at the time it entered service and was the second of three Olympic-class ocean liners operated by the White Star Line. The Titanic was built by the Harland and Wolff shipyard in Belfast. Thomas Andrews, her architect, died in the disaster.

# Problem Statement
We need to predict whether a person survived or died in the titanic crash. 

# Approach
1. We import the dataset.

2. We perform data cleaning by dropping features and imputing missing values. For imputing missing values, we perform EDA to find out correlations between different numerical features and then draw conclusions from that. 

3. We do some Feature Engineering to create features having high correlation with the target feature.

4. We then fit our dataset to different models to get baseline accuracy.

5. We then perform GridSearch to get the best possible accuracy for the hyper parameters.

6. We then perform ensembling using various models used earlier in three different ways:
       
      a) Voting
      
      b) Bagging
      
      c) Boosting
