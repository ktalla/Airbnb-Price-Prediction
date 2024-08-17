# Airbnb Price Prediction Project

## Project Overview

This project aims to build a machine learning model to predict Airbnb rental prices based on various features such as location, room type, amenities, and more. The project involves data preprocessing, feature engineering, model training, and evaluation to improve the prediction accuracy.

## Project Structure

1. **Data Loading and Cleaning**
   - The dataset is loaded and cleaned by handling missing values and transforming columns as necessary.

2. **Exploratory Data Analysis (EDA)**
   - A detailed analysis is performed to understand the distribution of the data and relationships between different features.

3. **Feature Engineering**
   - Transformation of categorical variables using techniques such as one-hot encoding.
   - Creation of new features by combining existing ones to capture more complex patterns.

4. **Modeling**
   - Different machine learning models are applied, including Decision Trees and Random Forests.
   - Hyperparameter tuning is performed using Grid Search and Random Search to improve the model's performance.

5. **Evaluation**
   - The models are evaluated using metrics like accuracy, and cross-validation is used to check for overfitting.
   - The project discusses the results and potential reasons for low accuracy, such as overfitting.

6. **Conclusion and Future Work**
   - The project concludes with insights into model performance and suggestions for improving the model by using alternative approaches like linear regression or neural networks.

## How to Run

1. **Install Dependencies**
   - Ensure you have Python 3 installed along with the necessary libraries, including `pandas`, `numpy`, `scikit-learn`, and `matplotlib`.

2. **Run the Notebook**
   - Open `Final Lab (2).ipynb` in Jupyter Notebook or any compatible environment.
   - Run the cells sequentially to reproduce the results.

3. **Modify and Experiment**
   - Feel free to modify the code to experiment with different models or techniques.

## Future Work

- **Model Optimization**: Explore different models like linear regression or neural networks to improve prediction accuracy.
- **Feature Engineering**: Further investigation into feature interactions to enhance model performance.
- **Deployment**: Consider deploying the model using a web framework to make predictions accessible via an API.

## License

This project is licensed under the MIT License. Feel free to use and modify the code as per your requirements.
