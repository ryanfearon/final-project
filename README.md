[Final Project.pdf](https://github.com/ryanfearon/final-project/files/6826704/Final.Project.pdf)
# final-project
Predicting 
Yelp 
Rating
A guide by Josh, Ian, Ryan and Douglas

Topic: Yelp Review Predictor
Testing our predictive model on  Yelp reviews. Can we predict a Yelp star rating based on various attributes specific to the restaurant? 

What attributes would customer (reviewers) consider most important to their rating? Does it depend on the type of restaurant? 

Steps in the Process
Gather Data
Import Json into Jupyter Notebook
Drop unwanted columns/features, filtered data by category, refined to OH
Factorized attribute columns to break object into separate individual feature strings
Convert data to binary via out of the box get dummies function to prep for machine learning
Trained data, and ran multiple different models to see best fit
Random Forest ftw
Compared Actual vs. Predicted Yelp stars
Took a look at feature importance


Cleaning the Dataset
Step 1: remove all businesses that are not restaurants
Step 2: include only restaurants in Ohio
Step 3: cleaning and restructuring columns

Feature Importance Heatmap

Feature Importance Heatmap

Feature Importance Plot

Shows most features aside from review counts do not matter in terms of affecting the rating

Feature Importance Ratings

Yelp Stars, Actual (red) vs Predicted (blue)

Shows that we were more accurate with prediction of the middle, more common ratings (2-4) versus the less common outlier ratings (1 and 5), which makes sense

Actual vs. Predicted Ratings

Yelp Stars, Ohio Dataset 

1. Challenges/Limitations

Finding small business datasetObtaining actual restaurant data.
A  Lack of Restaurant Data   The industry is very inept when it comes to data collection.
Breaking up feature object into separate strings   Out of the box factorize pandas function
Dealing with null / naan values   Treating them as false, rather than dropping or true.

2. If we had more time...

Utilize web scraping and NLP Adding further dimensions and accuracy to predictions
Take a zoomed look at each featureHistograms per feature, determine actual feature importance
Expand analysis to identify biasesInclude intangible features and expand data set.

Conclusion

Questions ?


Go Browns!
