# CardioVascular_Disease_Prediction

## Project Overview

This project aims to predict the likelihood of an individual having cardiovascular disease using machine learning techniques. The model analyzes various health factors, including age, gender, blood pressure, cholesterol levels, and other metrics to assess the risk. The dataset used for training comes from publicly available health databases, and the project applies various classifiers to evaluate prediction accuracy.

## Features

- **Data Preprocessing**: Handling missing values, outlier detection, and normalization of features.
- **Feature Engineering**: Selection of important features that influence cardiovascular risk.
- **Machine Learning Models**: Multiple classification algorithms (Logistic Regression, Decision Trees, Random Forest, etc.) have been implemented and compared for performance.
- **Model Evaluation**: Metrics like accuracy, precision, recall, and F1 score are used for model performance analysis.
- **User-Friendly**: Provides an interface to input health metrics and receive predictions.

## Technologies Used

- **Programming Language**: Python
- **Libraries**: 
  - Scikit-learn for building and evaluating models.
  - Pandas and NumPy for data manipulation and analysis.
  - Matplotlib and Seaborn for data visualization.

## How to Use

1. **Clone the Repository**:
```bash
git clone https://github.com/1BYDH8/CardioVascular_Disease_Prediction.git
```
2. **Install the Required Libraries: Ensure you have Python installed, then install the dependencies:**
```bash
pip install -r requirements.txt
```
3. **Run the Jupyter Notebook: Launch the notebook to explore the data and models:**
```bash
jupyter notebook Cardiovascular_Disease_Prediction.ipynb
```
4. **Train the Model:** Follow the instructions in the notebook to preprocess the data, train the model, and evaluate the predictions.

5. **Make Predictions:** Once the model is trained, you can input new data through the provided interface to predict the likelihood of cardiovascular disease.

## **How It Works**
1. **Data Collection:** The model is trained on a dataset that includes various health metrics such as blood pressure, cholesterol, age, and gender.
2. **Preprocessing:** The data is cleaned, and missing values are handled. Features are normalized to ensure fair weightage.
3. **Model Training:** Several machine learning algorithms are trained and tested, including Logistic Regression, Decision Trees, and Random Forests.
4. **Prediction:** Based on the input health data, the trained model predicts whether the individual is likely to have cardiovascular disease.

## **Performance Evaluation**

**The project evaluates the models using key performance metrics such as:**
- Accuracy: Percentage of correct predictions made by the model.
- Precision: How many of the predicted positive cases were actually positive.
- Recall: How many of the actual positive cases were correctly identified by the model.
- F1 Score: A balance between precision and recall.
These metrics are displayed in confusion matrices and graphical plots for easy analysis.

## **Future Improvements**
- Integration of more complex models like Neural Networks for enhanced accuracy.
- Inclusion of more detailed medical history and lifestyle factors to improve prediction accuracy.
- Deployment of the model using Flask or Django for a web-based prediction tool.