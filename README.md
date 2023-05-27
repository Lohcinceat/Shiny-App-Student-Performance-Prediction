# Student Performance Prediction Shiny App

This Shiny App project aims to predict the performance of students in secondary education using machine learning algorithms. The app utilizes the random forest algorithm implemented with the `randomForest` package in R. The prediction model is trained on a preprocessed dataset obtained from the UCI Machine Learning Repository.

## Features

The Shiny App provides the following features:

- User-friendly interface for inputting student information.
- Predicts the student's performance for the next semester based on the input data.
- Displays the prediction results and model performance metrics.
- Offers insights into the factors influencing student performance.

## Prerequisites

Before running the Shiny App, ensure that you have the following packages installed in your R environment:

- `caret`: For machine learning and model evaluation.
- `shiny`: For creating the web-based interactive application.
- `shinythemes`: For additional themes to customize the app's appearance.
- `tidyverse`: For data manipulation and visualization.
- `data.table`: For efficient data manipulation.
- `randomForest`: For implementing the random forest algorithm.

You can install these packages using the following command:

```R
install.packages(c("caret", "shiny", "shinythemes", "tidyverse", "data.table", "randomForest"))
```
Usage
To use the Shiny App:

Clone or download the project repository from GitHub.
Make sure you have the necessary packages installed (see Prerequisites).
Run the Shiny App by executing the runApp() function in the ui.R or server.R file, or use the RStudio interface to launch the app.
Input the student's information through the app's user interface.
Click the "Submit" button to generate the prediction results.
View the predicted performance and model performance metrics in the app's output.
Feel free to explore the app and experiment with different input values to analyze the factors affecting student performance.

Data Source
The dataset used for training and prediction is derived from the "Student Performance" dataset available in the UCI Machine Learning Repository. The dataset was preprocessed to ensure data quality and compatibility with the prediction model.
