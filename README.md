# PREDICTIVE-ANALYSIS-USING-MACHINE-LEARNING

*COMPANY*:CODTECH IT SOLUTIONS

*NAME*:Thaduri Poojitha

*INTERN ID*:CT04DF1335

*DOMAIN*:DATA ANALYTICS

*DURATION*:4 WEEKS

*MENTOR*:NEELA SANTHOSH

 ##YOU HAVE TO ENTER DESCRIPTION OF YOUR TASK Introduction

Predictive analysis is a branch of data science that uses statistical and machine learning techniques to forecast outcomes based on historical data. It enables businesses, researchers, and developers to identify trends and make data-driven decisions. In this project, we implement a predictive analysis pipeline using Python and several key libraries including pandas, NumPy, scikit-learn, matplotlib, and seaborn.

The primary aim is to train a machine learning model that can make accurate predictions and provide insights into the importance of each input feature, thus making the solution both predictive and interpretable.

Tools and Their Purpose

Tool/Library	Role in the Project

Python	Core programming language
Pandas	Data loading, cleaning, manipulation
NumPy	Numerical operations and array handling
Scikit-learn	Machine learning model, training, testing, evaluation
Matplotlib	Plotting results (static charts)
Seaborn	Enhanced visualization (feature importance, heatmaps)
Jupyter Notebook / Google Colab	Interactive development environment

Project Workflow Using Tools

1. Data Loading

Tool Used: pandas
The dataset is imported using pd.read_csv() or directly from sklearn.datasets. Pandas helps view and understand the data with functions like head(), info(), and describe().

2. Data Preprocessing

Tools Used: pandas, NumPy, scikit-learn.preprocessing
Missing values are handled, and features are encoded or scaled using tools like StandardScaler. This prepares the data for machine learning algorithms.

3. Splitting the Dataset

Tool Used: train_test_split from sklearn.model_selection
Data is split into training and testing sets (e.g., 80/20) to ensure unbiased evaluation of the model.

4. Model Training

Tool Used: LogisticRegression from sklearn.linear_model
A machine learning model is chosen (e.g., logistic regression for classification), and trained using .fit() on the training dataset.

5. Making Predictions

Tool Used: model.predict()
Predictions are made on the testing dataset, and stored for evaluation.

6. Evaluation Metrics

Tool Used: sklearn.metrics
Accuracy, precision, recall, and F1-score are calculated using classification_report and accuracy_score.

7. Feature Importance Visualization

Tools Used: matplotlib.pyplot, seaborn
Model coefficients or feature importances are plotted to visualize which features are most influential in prediction.

8. Saving the Output

Tool Used: plt.savefig()
Visual plots are saved in .png or .svg format for presentation or reporting.

Conclusion

This project demonstrates a complete predictive analysis pipeline using Python’s robust data science libraries. From loading and preprocessing data with pandas and NumPy, to building models with scikit-learn, and visualizing results using matplotlib and seaborn, each tool plays a critical role. The final model is evaluated for accuracy and interpretability, offering practical insights into the prediction process.

#OUTPUT

<img width="611" alt="Image" src="https://github.com/user-attachments/assets/d3248fdf-8bd5-4fd9-94fd-cb194fe995e3" />
