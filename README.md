# LAB-7

# Advertising Click Prediction Project

This project uses a logistic regression model to predict whether a user will click on an advertisement based on user information and internet behavior.

## Dataset Features

The dataset contains the following columns:

* Daily Time Spent on Site
* Age
* Area Income
* Daily Internet Usage
* Ad Topic Line
* City
* Male
* Country
* Timestamp
* Clicked on Ad

## Steps Performed

1. Imported the required libraries.
2. Loaded the dataset into a dataframe.
3. Explored the data using:

   * `info()`
   * `describe()`
   * heatmap for missing values
4. Created visualizations such as:

   * Histogram of Age
   * Jointplots
   * Pairplot with hue based on Clicked on Ad
5. Selected the main numerical features:

   * Daily Time Spent on Site
   * Age
   * Area Income
   * Daily Internet Usage
   * Male
6. Split the data into training and testing sets.
7. Trained a logistic regression model.
8. Predicted values on the testing set.
9. Evaluated the model using a classification report.

## Model Performance

The logistic regression model achieved around 91% accuracy on the testing data.

## Conclusion

The model performed well in predicting whether a user would click on an advertisement. Features such as time spent on site, internet usage, age, and area income were useful in making predictions.
