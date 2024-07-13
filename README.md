# Financial-Market-News-using-Sentimental-Analysis
# Executed sentiment analysis on financial market news headlines using machine learning techniques.
This project introduces sentiment analysis of financial market news headlines using machine learning techniques.

The dataset stored in the NEWS.csv file contains several columns representing different parts of the news headlines. We preprocess these headers by concatenating the corresponding columns into full-text records. 

These labels are then converted to numerical features using the TF-IDF vectorization technique. We divide the data into training and test sets and use a standard scale to normalize the features.

A logistic regression model is trained on the preprocessed data to predict opinion labels indicating whether a news headline is positive or negative. 

Finally, we evaluate model performance using metrics such as classification report, accuracy score, and confusion matrix, which provides a comprehensive view of the model's predictive capabilities..
