# Customer Segmentation Prediction for Automobile Market Expansion

This project is designed to help an automobile company predict the appropriate customer segment for new potential customers in a new market. The company has identified similarities between the new market and their existing market, where customer segmentation has been an effective strategy.

## Project Overview

The company has five products (P1, P2, P3, P4, and P5) and has segmented its existing customers into four groups (A, B, C, D). The goal of this project is to apply the same segmentation model to predict the segment for 2627 new potential customers in the new market.

### Key Steps:

1. **Data Collection**: 
   - The project uses a dataset named `Customer_Segmentations.csv` that contains historical customer data, including features that describe the customers and their corresponding segment.

2. **Data Preprocessing**:
   - The data is preprocessed to handle missing values, categorical variables, and scaling of numerical features.
   - Label Encoding and One-Hot Encoding are used for categorical variables.
   - Data balancing techniques like Random Oversampling are applied if necessary.

3. **Feature Selection**:
   - Recursive Feature Elimination (RFE) is employed to select the most relevant features for the model.

4. **Modeling**:
   - The project uses multiple machine learning models, including Logistic Regression and Support Vector Machine (SVM), to predict customer segments.
   - The models are trained and evaluated using common metrics like accuracy, precision, recall, F1-score, and confusion matrix.

5. **Prediction**:
   - After training, the model is used to predict the segment of the new potential customers.
   - The predictions can be used by the company's sales and marketing teams to target the new customers effectively.
