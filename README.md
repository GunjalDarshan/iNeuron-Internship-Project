# iNeuron-Internship-Project


## Campus Placement Prediction

This project focuses on predicting campus placements for students based on various factors such as their educational background, degree specialization, work experience, and other relevant features. The goal is to build a predictive model that can accurately determine whether a student will be placed in a job or not.

### Project Structure

The project is structured as follows:

1. **Import Libraries and Load Dataset**: Import the necessary libraries and load the dataset containing information about students and their placement status.

2. **Data Preprocessing**: Perform data preprocessing tasks such as handling missing values, encoding categorical columns, and feature engineering.

3. **Model Building**: Build several classification models using different algorithms such as Logistic Regression, K-Nearest Neighbors, Decision Trees, Random Forests, and Gradient Boosting. Train these models on the preprocessed data.

4. **Model Evaluation**: Evaluate the performance of each model using accuracy score. Compare the accuracy scores of different models to determine the best performing one.

5. **Prediction on New Data**: Create a user interface using tkinter to allow users to input their details and get a prediction on whether they will be placed or not. Use the trained model to make predictions on the new data.

6. **Save Model Using Joblib**: Save the best performing model using joblib so that it can be easily loaded and used for future predictions.

### Dependencies

The project requires the following dependencies:

- numpy
- pandas
- matplotlib
- scikit-learn
- tkinter

Make sure these dependencies are installed before running the project.

### Usage

To use the project, follow these steps:

1. Clone the project repository from GitHub.

2. Install the required dependencies mentioned above.

3. Run the Jupyter Notebook or Python script to train the models, evaluate their performance, and save the best model using joblib.

4. Use the saved model to make predictions on new data by running the tkinter user interface.

### Conclusion

This project demonstrates the application of machine learning algorithms for campus placement prediction. By analyzing various factors, the models can provide insights into the likelihood of a student getting placed in a job.
