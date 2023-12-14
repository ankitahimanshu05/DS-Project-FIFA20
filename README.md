The FIFA20 dataset is a challenging dataset. It is an Unsupervised Machine Learning (no target or label in the dataset). Two main takeaways of this project is: clustering the players based on their attributes and finding the most important features to group these players on.

As it is an unsupervised machine learning, there was a lot of assumptions made but all of our assumptions were backed by facts and numbers.

FIFA20 data set is huge with 18278 records of players (rows) and 104 features (columns). The data preprocessing part was a bit tricky and data needed to be handled differently. There were numerical and categorical features which needed to be handled separately so the whole data set was split into two categories and then handled accordingly. Later the categorical data were converted to numerical data.
Many features were dropped from the data set as they were not as important as others for model building.

The data set contained a lot of outliers in some features which were handled separately. There were lots of missing data. Some features were having more that 50% missing values, hence those were dropped. Features with less missing data were imputed accordingly.

The goal was to prepare a complete data analysis report on the given data set. The project also explores the football skills and cluster the players based on their attributes. This project also attempts to answer below mentioned questions:
1. Prepare a rank ordered list of top 10 countries with most players. Which countries are producing the most footballers that play at this level?
2. Plot the distribution of overall rating Vs. Age of players. Interpret what is the age after which a player stops playing.
3. Which type of offensive players tends to get paid the most: the striker, the right-winger or the left-winger

Important Note: Merge all 4 files before running.
