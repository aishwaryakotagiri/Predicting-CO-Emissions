PREDICTING CO2 EMISSIONS
* This project explores the relationship between vehicle features and their CO₂ emissions using both classical machine learning and deep learning techniques. The goal is to accurately predict CO₂ emissions (in grams per kilometer) using key vehicle attributes like engine size, cylinders, fuel type, and fuel consumption.

* The project compares the performance of a Linear Regression model with a Neural Network model and includes visualizations to support the results.

What This Project Covers:
  - Loading and preprocessing a real-world dataset from Canada

  - Feature selection and one-hot encoding for categorical variables

  - Standardizing both input features and output values

  - Training a linear regression model for baseline performance

  - Building a neural network using TensorFlow and Keras

  - Using early stopping to prevent overfitting

  - Evaluating models using Mean Absolute Error (MAE) and R² score

Visualizing:

  - Actual vs predicted values

  - Model performance over epochs

Dataset Used:
This project uses the CO₂ Emissions - Canada dataset from Kaggle. It includes detailed specifications for vehicles sold in Canada, including engine size, number of cylinders, fuel type, fuel consumption, and measured CO₂ emissions.

Dataset Link:
How to Run This Project?
Clone the repository or download the Python file.

Download the dataset and place it in the same folder as the script. Rename the file to:
CO2 Emissions_Canada.csv

Install required libraries:
pip install pandas numpy tensorflow matplotlib seaborn scikit-learn

Run the script:
python co2_emissions_regression.py

The script will:
  - Train both models

  - Output their performance (MAE and R²)

  - Display plots showing prediction accuracy and training performance

Results:
The final neural network model achieved:

  Mean Absolute Error (MAE): 2.30 g/km

  R² Score: 1.00

This indicates extremely accurate predictions, with minimal error and excellent generalization on the test set.

Technologies Used
  - Python

  - TensorFlow / Keras

  - Scikit-learn

  - Pandas and NumPy

  - Matplotlib and Seaborn

About the Author
I'm Aishwarya Kotagiri, a student passionate about applying machine learning to solve real-world problems. This project was created to strengthen my understanding of regression, model comparison, and performance visualization.
