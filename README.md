# Customer Churn Prediction Using Keras

## Overview

This project focuses on predicting customer churn for a telecom company using deep learning techniques implemented with **Keras**. The aim is to build predictive models to determine which customers are likely to leave the telecom service provider, enabling the company to take preventative actions.

The project involves data manipulation, visualization, and the creation of three sequential models in Keras. These models will help predict churn based on various features, with performance evaluated using confusion matrices and accuracy graphs over epochs.

---

## Project Structure

1. **Data Manipulation**: 
   - Analyze the dataset and filter specific customer segments.
   - Create subsets of customers based on specific conditions (e.g., tenure, total charges).
  
2. **Data Visualization**: 
   - Visualize the distribution of customers likely to churn using pie charts and bar plots for different variables like 'Internet Service'.

3. **Model Building**: 
   - Develop three different Keras models to predict churn:
     - **Model 1**: Basic Sequential model using `tenure` as the feature.
     - **Model 2**: Sequential model with dropout layers.
     - **Model 3**: Sequential model using multiple features (`tenure`, `Monthly Charges`, and `Total Charges`).

---

## Requirements

- **Python 3.x**
- **Keras**
- **TensorFlow**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Jupyter Notebook**

---

## Files in the Repository

- `customer_churn_analysis.ipynb`: Jupyter notebook containing the entire analysis and model-building process.
- `customer_churn.csv`: Dataset used for churn prediction.
- `requirements.txt`: List of dependencies required to run the project.

---

