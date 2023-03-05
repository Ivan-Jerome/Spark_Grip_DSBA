
# Prediction using Supervised ML

The given task can be solved using Supervised Machine Learning, where we use a linear regression model to predict the percentage of a student based on the number of study hours.

First, we need to collect data on the number of study hours and the corresponding percentage obtained by the student. We can use this data to plot a graph and see if there is a linear relationship between the two variables. The graph will help us understand if the model we are going to build will be a good fit for the data or not.

Next, we split the data into two sets: the training set and the test set. The training set will be used to train the linear regression model, while the test set will be used to evaluate the performance of the model.

We can split the data using Scikit-Learn's built-in train_test_split() method, which randomly splits the data into training and test sets based on a specified percentage. For example, we can use 80% of the data for training and the remaining 20% for testing.

After splitting the data, we can use Scikit-Learn's LinearRegression class to train the model on the training set. Once the model is trained, we can use it to predict the percentage of a student based on the number of study hours.

Finally, we can visualize the performance of the model by plotting the regression line on the graph. This will help us see how well the model fits the data.

If we get a predicted score of 93.69, it means that the model is performing well and can be used to predict the percentage of a student based on the number of study hours.

To modify this, we can try different regression models such as polynomial regression, decision tree regression, or support vector regression, and compare their performance. We can also use different evaluation metrics such as mean squared error, mean absolute error, or R-squared to evaluate the performance of the models. Additionally, we can try to gather more data or add more features to improve the accuracy of the model.
## Screenshots

![App Screenshot](https://raw.githubusercontent.com/JeromeGeek/Prediction-using-Supervised-ML/main/sample_screenshot1.png)
![App Screenshot](https://raw.githubusercontent.com/JeromeGeek/Prediction-using-Supervised-ML/main/sample_screenshot2.png)





## Tech Stack

Jupyter Notebook


## Run on Jupyter Notebook

Clone the project

```bash
$  gh repo clone JeromeGeek/Criminal-Record-Management
```

Now open it on Jupyter Notebook and run 


