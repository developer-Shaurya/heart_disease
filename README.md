# Heart Disease Prediction Using Machine Learning

## Overview

This repository contains a machine learning project designed to predict the likelihood of heart disease in individuals using various classification algorithms. The project includes data preprocessing, visualization, model training, hyperparameter tuning, and model evaluation to identify the best-performing model.

## Project Structure

- **heart_disease_prediction.ipynb**: The main Jupyter Notebook file where the entire workflow of the project is implemented. This includes data preprocessing, visualization, model training, hyperparameter tuning, and final model evaluation.

- **heart_dataset.csv**: The dataset used for training and testing the models. This dataset contains various features related to heart health and is used to predict the likelihood of heart disease.

- **dashboard.pbix**: A Power BI file that contains a detailed visualization dashboard for the heart disease dataset. This file provides insights into the data and model performance through various visualizations.

- **dashboard.png**: An image of the visualization dashboard, included as a preview for users who may not have Power BI installed and cannot open the `.pbix` file.

## Models Used

The project explores the following machine learning models for heart disease prediction:

1. **K-Nearest Neighbors (KNN)**
2. **Support Vector Machine (SVM)**
3. **Decision Trees**
4. **Random Forest**

## Project Workflow

### 1. Data Preprocessing
- **Data Cleaning**: Handling missing values, correcting data types, and removing duplicates.
- **Feature Engineering**: Creating new features or modifying existing ones to improve model performance.
- **Normalization/Scaling**: Scaling features to ensure that models converge quickly and effectively.

### 2. Data Visualization
- Exploratory Data Analysis (EDA) was performed to understand the distribution of data, correlations between features, and the relationship between features and the target variable.
- Visualizations were created to uncover patterns and insights in the data, helping to guide the modeling process.

### 3. Train-Test Split
- The dataset was split into training and testing sets to evaluate model performance on unseen data.

### 4. Model Training & Hyperparameter Tuning
- All four models were trained on the training data.
- Hyperparameter tuning was performed to find the best set of parameters for each model, optimizing for accuracy.

### 5. Model Evaluation
- The models were evaluated based on accuracy and other relevant metrics.
- The best-performing model was selected based on its performance on the test data.

### 6. Model Implementation
- The final model was implemented to make predictions. By passing input arguments to the model, it provides predictions on the likelihood of heart disease based on the trained model.

## How to Use

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/heart-disease-prediction.git
   ```
2. **Navigate to the project directory**:
   ```bash
   cd heart-disease-prediction
   ```
3. **Open the Jupyter Notebook**:
   ```bash
   jupyter notebook heart_disease_prediction.ipynb
   ```
4. **Explore the dataset and visualization**:
   - View the dataset in `heart_dataset.csv`.
   - Open the Power BI visualization dashboard using `dashboard.pbix` or preview it using the `dashboard.png` file.

5. **Run the notebook**:
   - Follow the steps in the notebook to preprocess the data, train models, and make predictions.

## Visualization Dashboard

The visualization dashboard (`dashboard.pbix`) provides an interactive way to explore the data and model results. You can view the distribution of various features, correlations, and model performance metrics. A preview of this dashboard is provided in `dashboard.png`.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

---
