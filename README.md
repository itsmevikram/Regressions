# Regressions
Regression Problems using Python and Machine Learning

1. Extracting the dataset.
2. Check for NaN values is successful with 0 NaNs.
3. Graphically Representing the data to find out outliers.In here we are using box plot.
4. Using the map function to covert the category features like smokers,sex into numbers,but for region we will use Label Encoder i.e. sklearn default library for encoding category features.
5. Charges column which is our dependent variable having lots of outliers present which can create problems while traing our model.
6. We calculate the Z-Scores or performing standardisation for the charges column in order to find that upto what limit we keep the data in order to deal with the outliers. 
7. In here we have taken 0.85 standard deviation from the mean to deal with outliers.
8. Applying the Label Encoder in region column to the covert the regions into numbers,you can also use pandas dummies to instead of this.
9. Splitting the data into train and test set.
10. Performing Cross validation with diferent regeression models.
11. It was found that Gradient Boosting Regression Algorithm performed well with the data compared to other models applied. 
12. Traing the model with the data and measuring the accuracy using Mean Squared Error.
