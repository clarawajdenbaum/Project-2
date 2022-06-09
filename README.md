# Stroke predictions
## Predicting strokes 

**Clara Wajdenbaum**

### Business problem:

The goal is to make predictions about people whon have strokes based on the data provided.

### Data:
healthcare-dataset-stroke-data.csv | https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset 

### Methods:

I removed the rows with missing values and I removed the 'id' column.
I scaled the integer and float columns and I have OneHotEncode the object columns.

### Results:

**No Stroke or Stroke by Age**

![No Stroke or Stroke by Age](https://user-images.githubusercontent.com/101348370/170679816-3145f3c2-0f1b-489a-b189-91fffa25fa66.png)

**Histogram**

![Histogram](https://user-images.githubusercontent.com/101348370/172846965-4c929056-d857-4d78-b9e1-b1a80b94c871.png)

### Modeling Results:

The Classification Tree model with 'max_depth' of 5, 'min_samples_leaf' of 20 and 'min_samples_split' of 2 has an accuracy score of 94.87%.
The Logistic Regression Tree model has an accuracy score of 94.87%.
The KNN model with kneighborsclassifier__n_neighbors'of 6, 'kneighborsclassifier__p' of 1 and 'kneighborsclassifier__weights' of 'uniform' has a score of 94.71%.

### Summary:

All three of our models work very well on our test set but I will choose the **Classification Tree** as I think it is the easiest one to use and also has the best score.

### For further information:

For any additional questions, please contact **clara.wajdenbaum@icloud.com**
